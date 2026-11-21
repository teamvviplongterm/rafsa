55) 0%,rgba(56,225,255,.18) 40%,transparent 68%);animation:ssGlow 2.4s ease-in-out infinite}
.ss-verify::after{content:"";position:absolute;inset:0;z-index:-1;border-radius:50%;border:2px solid rgba(198,255,61,.8);opacity:0;animation:ssPing 2.4s cubic-bezier(.2,.6,.3,1) infinite}
.ss-verify svg{position:relative;width:100%;height:100%;overflow:visible}
.ss-vb-shape{transform-origin:12px 12px;animation:ssRot 9s linear infinite}
.ss-vb-shine{animation:ssShine 3.2s ease-in-out infinite}
.ss-vb-check{stroke-dasharray:14;stroke-dashoffset:14;animation:ssDraw .6s .5s cubic-bezier(.6,0,.2,1) forwards}
@keyframes ssGlow{0%,100%{opacity:.45;transform:scale(.85)}50%{opacity:1;transform:scale(1.05)}}
@keyframes ssPing{0%{transform:scale(.9);opacity:.9}100%{transform:scale(2);opacity:0}}
@keyframes ssShine{0%,55%{transform:translateX(-26px)}100%{transform:translateX(30px)}}
@keyframes ssDraw{to{stroke-dashoffset:0}}
.ss .ss-sub{margin-top:8px;font-size:14px;font-weight:600;color:var(--mut)}

/* ===== chips ===== */
.ss-chips{display:grid;grid-template-columns:repeat(3,1fr);gap:8px;margin:16px 0 0}
.ss-chip{padding:11px 4px;border-radius:14px;background:rgba(255,255,255,.03);border:1px solid rgba(255,255,255,.07)}
.ss-chip b{display:block;font-size:15px;font-weight:800;color:#fff}
.ss-chip span{display:block;margin-top:3px;font-size:10.5px;font-weight:700;letter-spacing:1.2px;text-transform:uppercase;color:var(--mut)}

/* ===== button ===== */
.ss-btn{position:relative;display:flex;align-items:center;gap:14px;width:100%;min-height:64px;margin-top:20px;padding:8px 10px 8px 10px;border-radius:18px;overflow:hidden;isolation:isolate;touch-action:manipulation;
color:#0a0d06!important;background:linear-gradient(100deg,#d8ff5c,#b4f22a);
box-shadow:0 10px 28px rgba(198,255,61,.28),inset 0 1px 0 rgba(255,255,255,.55);transition:transform .15s ease}
.ss-btn::before{content:"";position:absolute;top:0;left:0;width:35%;height:100%;z-index:-1;background:linear-gradient(105deg,transparent,rgba(255,255,255,.55),transparent);transform:translate3d(-140%,0,0) skewX(-20deg);animation:ssSweep 3s ease-in-out infinite}
.ss-btn:hover{transform:translateY(-2px)}
.ss-btn:active{transform:scale(.985)}
.ss-btn:focus-visible{outline:3px solid #fff;outline-offset:4px}
.ss-btn-ic{flex-shrink:0;display:grid;place-items:center;width:46px;height:46px;border-radius:13px;background:#0b0f08}
.ss-btn-ic svg{width:24px;height:24px;margin-left:-2px}
.ss-btn-txt{flex:1;text-align:left;line-height:1.1}
.ss-btn-txt b{display:block;font-size:18px;font-weight:900;letter-spacing:.6px;text-transform:uppercase}
.ss-btn-txt span{display:block;margin-top:3px;font-size:12px;font-weight:700;opacity:.7}
.ss-btn-arr{flex-shrink:0;width:22px;height:22px;margin-right:8px}
@keyframes ssSweep{0%{transform:translate3d(-140%,0,0) skewX(-20deg)}55%,100%{transform:translate3d(340%,0,0) skewX(-20deg)}}

/* ===== footer ===== */
.ss .ss-ads{margin-top:20px;font-size:13px;font-weight:700;color:#cfd6cc}
.ss-ads b{color:var(--cyan)}
.ss-div{height:1px;margin:16px 0 14px;background:linear-gradient(90deg,transparent,rgba(255,255,255,.12),transparent)}
.ss .ss-disc{font-size:11.5px;line-height:1.6;color:#6f7a73}
.ss-disc b{color:#a9b3ab}

/* ===== telegram help panel ===== */
.ss-help{display:none;margin-top:14px;padding:14px;border-radius:16px;text-align:left;font-size:13.5px;color:var(--txt);background:rgba(56,225,255,.06);border:1px solid rgba(56,225,255,.25)}
.ss-help.on{display:block;animation:ssIn .3s cubic-bezier(.2,.9,.3,1) both}
.ss-help>b{color:#fff;font-size:14px}
.ss-help-row{display:flex;gap:8px;margin-top:10px}
.ss-help-row a{flex:1;padding:12px 6px;border-radius:12px;text-align:center;font-size:13px;font-weight:800;touch-action:manipulation}
.ss-h-retry{background:var(--lime);color:#0a0d06!important}
.ss-h-get{background:rgba(255,255,255,.07);border:1px solid rgba(255,255,255,.14);color:#fff!important}
.ss .ss-h-tip{margin-top:10px;font-size:11.5px;line-height:1.5;color:var(--mut)}
.ss-h-tip b{color:#fff}

/* ===== responsive ===== */
@media(max-width:420px){
.ss{padding:14px 12px}
.ss-card{padding:20px 16px 18px;border-radius:24px}
.ss-btn{min-height:60px;gap:12px}
.ss-btn-ic{width:42px;height:42px}
.ss-btn-txt b{font-size:16px}
.ss-chip b{font-size:14px}
}
@media(min-width:900px){.ss-card{padding:36px 36px 28px}}
@media(prefers-reduced-motion:reduce){.ss *,.ss *::before,.ss *::after{animation:none!important;transition:none!important}.ss-vb-check{stroke-dashoffset:0}}
</style>

<span class="ss-live"><i></i>LIVE NOW</span>

    </div>
   </div>
   </div>
 <script type="speculationrules">
{"prefetch":[{"source":"document","where":{"and":[{"href_matches":"/"},{"not":{"href_matches":["/wp-.php","/wp-admin/","/wp-content/uploads/","/wp-content/","/wp-content/plugins/","/wp-content/themes/twentytwentyfive/","/\?(.+)"]}},{"not":{"selector_matches":"a[rel~="nofollow"]"}},{"not":{"selector_matches":".no-prefetch, .no-prefetch a"}}]},"eagerness":"conservative"}]}
</script>
<script>
( () => {
const lazyloadRunObserver = () => {
const lazyloadBackgrounds = document.querySelectorAll( .e-con.e-parent:not(.e-lazyloaded) );
const lazyloadBackgroundObserver = new IntersectionObserver( ( entries ) => {
entries.forEach( ( entry ) => {
if ( entry.isIntersecting ) {
let lazyloadBackground = entry.target;
if( lazyloadBackground ) {
lazyloadBackground.classList.add( 'e-lazyloaded' );
}
lazyloadBackgroundObserver.unobserve( entry.target );
}
});
}, { rootMargin: '200px 0px 200px 0px' } );
lazyloadBackgrounds.forEach( ( lazyloadBackground ) => {
lazyloadBackgroundObserver.observe( lazyloadBackground );
} );
};
const events = [
'DOMContentLoaded',
'elementor/lazyload/observe',
];
events.forEach( ( event ) => {
document.addEventListener( event, lazyloadRunObserver );
} );
} )();
</script>
<script data-wp-strategy="defer" defer id="hostinger-reach-embed-js" src="https://cdn-reach.hostinger.com/js/embed.js"></script>

</body>
