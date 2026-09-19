<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#imoZnEc)"><path fill="url(#icVEdpd)" class="o7w9zg64j"/><path fill="url(#iPaXeqc)" class="o7w9zg64j"/></g><g filter="url(#imoZnEc)"><path fill="url(#icVEdpd)" class="o7w9zg64j"/><path fill="url(#iPaXeqc)" class="o7w9zg64j"/></g><path fill="url(#iPgyEhA)" class="oee7_jcbf"/><path fill="url(#iI1KRgc)" class="oee7_jcbf"/><path fill="url(#iYDPFlw)" class="tvol8bc0y"/><path fill="url(#iE8LWHx)" class="tvol8bc0y"/><path fill="url(#ih8Cblq)" class="xppftxbjk"/><g filter="url(#i3Qr4tw)"><path fill="url(#ix0Giod)" class="pah2rdb4s"/><path fill="url(#iNNaMhe)" class="pah2rdb4s"/></g><path fill="url(#ibq89Hd)" class="e027e2bgf"/><path fill="url(#iTvXJ1c)" class="e027e2bgf"/><path fill="url(#iYMAMnb)" class="e027e2bgf"/><g filter="url(#i1NgIbe)"><path fill="url(#i6I3Fqe)" class="xh_onccts"/></g><g filter="url(#iw6hTud)"><path fill="url(#i9DHSKe)" class="mgg31acdx"/><path fill="url(#iSizZpd)" class="mgg31acdx"/><path fill="url(#iJDd75d)" class="mgg31acdx"/><path fill="url(#id4sXwd)" class="mgg31acdx"/><path fill="url(#iDyFT3W)" class="mgg31acdx"/></g><g filter="url(#idWG1xe)"><path class="sxvgztbtq"/></g><g filter="url(#icYO5mL)"><path class="pgoodobuo"/></g><g filter="url(#i3B7jhe)"><path class="vztrb29ya"/><path fill="url(#isgK0Uc)" class="yncacpbuq"/><path fill="url(#idSdy6d)" class="yncacpbuq"/></g><g filter="url(#ivaqVKc)"><path class="w9oqzlbnq"/><path fill="url(#iy53ZFe)" class="hw-58yx8d"/></g><path fill="url(#ig16kEj)" class="vn7vddclp"/><path fill="url(#iIMVdub)" class="d2yggc19e"/><path fill="url(#im1WAbd)" class="d2yggc19e"/><g filter="url(#idkBjAb)"><path fill="url(#imGanJd)" class="keu1p0veb"/></g><g filter="url(#iSxF3jb)"><path class="z022zguoo"/></g><g clip-rule="evenodd" filter="url(#izqNexe)" class="d2kvgvbvc"><path class="lmabwac7x"/><path fill="url(#iSLKfMb)" class="i0sr-bo4m"/></g><path class="o391lpb9t"/><g filter="url(#iyiAqXC)"><path fill="url(#itP1Red)" class="imo-j1fmc"/><path fill="url(#iJhfRkr)" class="imo-j1fmc"/><path fill="url(#iVD6ugc)" class="imo-j1fmc"/><path fill="url(#iNKjoVb)" class="imo-j1fmc"/><path fill="url(#i12rgId)" class="imo-j1fmc"/></g><path fill="url(#iJy4r3d)" class="xz9sr4b2l"/><path fill="url(#iNGlyFd)" class="xz9sr4b2l"/><path fill="url(#iPXhqib)" class="nwfpxhhly"/><path fill="url(#iujmEgI)" class="nwfpxhhly"/><g filter="url(#ivfNuBc)"><path class="hzpabxl1k"/></g><g filter="url(#iW77Aab)"><path class="f6_kmwash"/></g><g filter="url(#ijzCdWb)"><path class="uwp5l69ey"/></g><g filter="url(#iVkGwAw)"><path stroke="url(#igIM0bd)" class="whvu5ybpj"/></g><g filter="url(#ikcH2Kx)"><path stroke="url(#idjWPue)" class="n__qyxjso"/></g><g filter="url(#i06RBmd)"><path class="ki-2s9xtq"/></g><defs><radialGradient id="iPaXeqc" cx="0" cy="0" r="1" gradientTransform="rotate(161.322 8.254 15.316)scale(5.27798 10.393)" gradientUnits="userSpaceOnUse"><stop offset=".54" class="f8_tgzbue"/><stop offset="1" class="v_-r5lbgt"/></radialGradient><radialGradient id="iPgyEhA" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.93285 -3.98995 0 15.583 20.363)" gradientUnits="userSpaceOnUse"><stop offset=".49" class="yxp43-b2w"/><stop offset="1" class="fl68biezf"/></radialGradient><radialGradient id="iI1KRgc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.17187 -.58594 0 13.188 21.183)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="p8uhw_khn"/><stop offset="1" class="ij1ferbmv"/></radialGradient><radialGradient id="iYDPFlw" cx="0" cy="0" r="1" gradientTransform="matrix(-.92987 3.82055 -4.53851 -1.1046 22.284 14.706)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset=".909" class="by5wrxbms"/></radialGradient><radialGradient id="iE8LWHx" cx="0" cy="0" r="1" gradientTransform="matrix(.35375 .48515 -.41214 .30052 21.384 15.03)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="ih8Cblq" cx="0" cy="0" r="1" gradientTransform="rotate(64.592 -7.294 14.466)scale(3.58066 1.62757)" gradientUnits="userSpaceOnUse"><stop class="cy485ebzy"/><stop offset="1" class="pi95o6_xg"/></radialGradient><radialGradient id="iNNaMhe" cx="0" cy="0" r="1" gradientTransform="rotate(114.356 6.137 9.73)scale(4.56231 3.13463)" gradientUnits="userSpaceOnUse"><stop class="nsb85pi4s"/><stop offset="1" class="fmf48dbfr"/></radialGradient><radialGradient id="ibq89Hd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.70515 2.05291 0 13.07 12.148)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="e5zcqub-y"/><stop offset="1" class="f5_upsyin"/></radialGradient><radialGradient id="iTvXJ1c" cx="0" cy="0" r="1" gradientTransform="rotate(-44.203 15.219 -7.11)scale(5.90707 1.32182)" gradientUnits="userSpaceOnUse"><stop offset=".377" class="sgbnv8bju"/><stop offset="1" class="dwxb55a4s"/></radialGradient><radialGradient id="iYMAMnb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.01648 18.5784 0 16 21.546)" gradientUnits="userSpaceOnUse"><stop class="pnv4kibsp"/><stop offset=".247" class="d0rqgobjl"/><stop offset=".847" class="cpg60d_-h"/></radialGradient><radialGradient id="iSizZpd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.22268 10.6787 0 9.286 10.083)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iJDd75d" cx="0" cy="0" r="1" gradientTransform="matrix(.13754 -3.03019 5.3689 .24369 21.455 11.663)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="id4sXwd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.8448 -1.87103 1.37344 -2.08823 20.546 4.094)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="iDyFT3W" cx="0" cy="0" r="1" gradientTransform="matrix(1.0916 1.77888 -4.11904 2.52761 14.501 2.173)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="isgK0Uc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.65461 0 0 -.98523 15.899 4.898)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="idSdy6d" cx="0" cy="0" r="1" gradientTransform="matrix(3.88123 -6.1452 6.80825 4.3 9.044 9.652)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iy53ZFe" cx="0" cy="0" r="1" gradientTransform="matrix(3.91742 .45788 -.1917 1.64015 17.706 7.687)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="im1WAbd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.94552 -.2366 .25284 -2.07905 9.665 13.268)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="o8wr4h7sd"/><stop offset="1" class="t0w03e0rr"/></radialGradient><radialGradient id="imGanJd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1053 .18973 -.2328 -1.35625 9.638 13.268)" gradientUnits="userSpaceOnUse"><stop class="ab9g3hmui"/><stop offset="1" class="bwc1tpbev"/></radialGradient><radialGradient id="iSLKfMb" cx="0" cy="0" r="1" gradientTransform="matrix(1.3711 .9961 -.44329 .61017 11.605 13.202)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="sozvcjboj"/><stop offset=".568" class="b8btyqb8s"/></radialGradient><radialGradient id="itP1Red" cx="0" cy="0" r="1" gradientTransform="rotate(102.826 5.441 14.816)scale(9.56418 8.44437)" gradientUnits="userSpaceOnUse"><stop offset=".546" class="qtml67ysr"/><stop offset=".692" class="qtml67ysr"/><stop offset="1" class="ndg2zkbnv"/></radialGradient><radialGradient id="iJhfRkr" cx="0" cy="0" r="1" gradientTransform="matrix(1 2.48437 -.40982 .16496 15.346 12.53)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="i--8zbrku"/><stop offset="1" class="rusf7f63f"/></radialGradient><radialGradient id="iVD6ugc" cx="0" cy="0" r="1" gradientTransform="matrix(.98438 3.84375 -.63406 .16238 17.174 10.374)" gradientUnits="userSpaceOnUse"><stop class="i--8zbrku"/><stop offset="1" class="rusf7f63f"/></radialGradient><radialGradient id="iNKjoVb" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 4.375 -.54534 .0818 19.455 9.561)" gradientUnits="userSpaceOnUse"><stop class="i--8zbrku"/><stop offset="1" class="rusf7f63f"/></radialGradient><radialGradient id="i12rgId" cx="0" cy="0" r="1" gradientTransform="rotate(98.227 6.39 15.592)scale(3.93108 .49375)" gradientUnits="userSpaceOnUse"><stop offset=".001" class="i--8zbrku"/><stop offset="1" class="rusf7f63f"/></radialGradient><radialGradient id="iJy4r3d" cx="0" cy="0" r="1" gradientTransform="matrix(-3.96874 1.06253 -.45292 -1.69174 22.94 20.358)" gradientUnits="userSpaceOnUse"><stop class="yzag7e8_g"/><stop offset="1" class="tgllzx6xq"/></radialGradient><radialGradient id="iujmEgI" cx="0" cy="0" r="1" gradientTransform="rotate(76.973 -2.325 25.618)scale(8.17927 4.47567)" gradientUnits="userSpaceOnUse"><stop class="awna98bfd"/><stop offset="1" class="i4docjyne"/></radialGradient><filter id="imoZnEc" width="20.98" height="11.177" x="5.603" y="20.607" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.423529 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4121"/></filter><filter id="i3Qr4tw" width="13.076" height="15.613" x="9.487" y="6.129" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.580392 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4121"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.67451 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4121" result="effect2_innerShadow_4002_4121"/></filter><filter id="i1NgIbe" width="12.214" height="13.502" x="12.005" y="8.036" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4121" stdDeviation=".625"/></filter><filter id="iw6hTud" width="15.525" height="9.975" x="7.831" y="2.401" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4121"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4121" result="effect2_innerShadow_4002_4121"/></filter><filter id="idWG1xe" width="2.8" height="1.394" x="17.51" y="9.542" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4121"/></filter><filter id="icYO5mL" width="2.8" height="1.377" x="11.17" y="9.559" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4121"/></filter><filter id="i3B7jhe" width="8.338" height="7.623" x="8.061" y="3.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4121"/><feGaussianBlur result="effect2_foregroundBlur_4002_4121" stdDeviation=".25"/></filter><filter id="ivaqVKc" width="8.069" height="7.367" x="15.208" y="3.841" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.305882 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4121"/><feGaussianBlur result="effect2_foregroundBlur_4002_4121" stdDeviation=".25"/></filter><filter id="idkBjAb" width="1.5" height="2.767" x="8.283" y="11.884" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4121" stdDeviation=".125"/></filter><filter id="iSxF3jb" width="2.746" height="1.245" x="11.15" y="9.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4121" stdDeviation=".125"/></filter><filter id="izqNexe" width="3.412" height="1.562" x="11.244" y="12.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0392157 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4121"/></filter><filter id="iyiAqXC" width="11.547" height="12.795" x="13.324" y="8.484" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.662745 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4121"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.627451 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4121" result="effect2_innerShadow_4002_4121"/></filter><filter id="ivfNuBc" width="2.467" height="5.606" x="17.564" y="8.389" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4121" stdDeviation=".25"/></filter><filter id="iW77Aab" width="2.78" height="4.622" x="15.346" y="10.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4121" stdDeviation=".25"/></filter><filter id="ijzCdWb" width="2.438" height="3.281" x="13.906" y="12.245" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4121" stdDeviation=".25"/></filter><filter id="iVkGwAw" width="3.688" height="7.656" x="20.862" y="12.434" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4121" stdDeviation=".25"/></filter><filter id="ikcH2Kx" width="2.422" height="10.188" x="20.064" y="8.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4121" stdDeviation=".25"/></filter><filter id="i06RBmd" width="6.067" height="3.429" x="16.854" y="4.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4121" stdDeviation=".3"/></filter><linearGradient id="icVEdpd" x1="20.291" x2="5.914" y1="27.87" y2="30.775" gradientUnits="userSpaceOnUse"><stop class="ee6wyldiv"/><stop offset="1" class="lrdcrkb9v"/></linearGradient><linearGradient id="ix0Giod" x1="15.65" x2="15.65" y1="6.129" y2="21.542" gradientUnits="userSpaceOnUse"><stop class="lw14vgbrd"/><stop offset="1" class="yor2p9b5i"/></linearGradient><linearGradient id="i6I3Fqe" x1="18.719" x2="15.313" y1="10.313" y2="19.719" gradientUnits="userSpaceOnUse"><stop class="gz4_ruujd"/><stop offset="1" class="cliycfpeq"/></linearGradient><linearGradient id="i9DHSKe" x1="23.857" x2="9.852" y1="6.742" y2="6.742" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="ig16kEj" x1="23.355" x2="21.9" y1="12.563" y2="15.188" gradientUnits="userSpaceOnUse"><stop class="q2140yplm"/><stop offset=".351" class="zwpu2qbnf"/></linearGradient><linearGradient id="iIMVdub" x1="8.538" x2="10.297" y1="13.421" y2="13.267" gradientUnits="userSpaceOnUse"><stop class="mlsv8jb5y"/><stop offset="1" class="l7gss9bru"/></linearGradient><linearGradient id="iNGlyFd" x1="20.314" x2="20.396" y1="20.26" y2="20.553" gradientUnits="userSpaceOnUse"><stop offset=".245" class="f8osbx-ej"/><stop offset="1" class="oxk0gpbzd"/></linearGradient><linearGradient id="iPXhqib" x1="19.564" x2="26.002" y1="28.952" y2="27.577" gradientUnits="userSpaceOnUse"><stop class="uu8x24bjn"/><stop offset="1" class="gmelrdffb"/></linearGradient><linearGradient id="igIM0bd" x1="23.907" x2="21.737" y1="13.134" y2="16.946" gradientUnits="userSpaceOnUse"><stop class="lk7dbcc7r"/><stop offset="1" class="tmqbcuz_q"/></linearGradient><linearGradient id="idjWPue" x1="21.692" x2="19.09" y1="9.388" y2="10.498" gradientUnits="userSpaceOnUse"><stop class="lk7dbcc7r"/><stop offset="1" class="tmqbcuz_q"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-facepalming-light" /></template>
<style>
.ab9g3hmui {
  stop-color: var(--svg-color--c18472, #C18472);
}

.awna98bfd {
  stop-color: var(--svg-color--ff9946, #FF9946);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.b8btyqb8s {
  stop-color: var(--svg-color--262626, #262626);
  stop-opacity: 0;
}

.bwc1tpbev {
  stop-color: var(--svg-color--ca8b7a, #CA8B7A);
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cliycfpeq {
  stop-color: var(--svg-color--c5847b, #C5847B);
}

.cpg60d_-h {
  stop-color: var(--svg-color--c3777f, #C3777F);
  stop-opacity: 0;
}

.cy485ebzy {
  stop-color: var(--svg-color--48413f, #48413F);
}

.d0rqgobjl {
  stop-color: var(--svg-color--c3777f, #C3777F);
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d2yggc19e {
  d: path("M9.516 11.347c-.943.132-1.685.925-1.685 1.904a1.94 1.94 0 0 0 1.834 1.938a93 93 0 0 1-.15-3.842");
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.dwxb55a4s {
  stop-color: var(--svg-color--ac7764, #AC7764);
  stop-opacity: 0;
}

.e027e2bgf {
  d: path("M9.774 17.438a4.72 4.72 0 0 0 4.686 4.108h2.276a4.72 4.72 0 0 0 4.686-4.108c.142-2.272.285-5.067.39-7.337a1.75 1.75 0 0 0-1.662-1.727h-1.69a2.92 2.92 0 0 1-2.667-1.74a.8.8 0 0 0-.742-.505h-1.535c-2.226 0-4.03 1.824-4.03 4.075c0 2.244.14 4.984.287 7.234");
}

.e5zcqub-y {
  stop-color: var(--svg-color--cf9489, #CF9489);
}

.ee6wyldiv {
  stop-color: var(--svg-color--f84d1b, #F84D1B);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f5_upsyin {
  stop-color: var(--svg-color--e0ad9b, #E0AD9B);
}

.f6_kmwash {
  stroke: var(--svg-color--ffd6bf, #FFD6BF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m16.22 10.936l1.03 2.871");
}

.f8_tgzbue {
  stop-color: var(--svg-color--ff5016, #FF5016);
}

.f8osbx-ej {
  stop-color: var(--svg-color--d74a13, #D74A13);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fl68biezf {
  stop-color: var(--svg-color--da8986, #DA8986);
}

.fmf48dbfr {
  stop-color: var(--svg-color--e3b29d, #E3B29D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gmelrdffb {
  stop-color: var(--svg-color--ff8040, #FF8040);
}

.gz4_ruujd {
  stop-color: var(--svg-color--c27f5e, #C27F5E);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hw-58yx8d {
  d: path("m21.885 10.708l-.035-.762c-.013-.92-.774-1.68-1.695-1.719h-1.688c-1.072 0-1.923-.761-2.435-1.694c0 0-.148-.23-.27-.63c-.292-.96.651-1.707 1.64-1.538c1.251.214 2.765.622 3.855 1.333c2.104 1.372 1.736 3.845.628 5.01");
}

.hzpabxl1k {
  stroke: var(--svg-color--ffd6bf, #FFD6BF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m18.44 9.264l.716 3.856");
}

.i--8zbrku {
  stop-color: var(--svg-color--d79a81, #D79A81);
}

.i0sr-bo4m {
  d: path("M14.517 13c.15.11.183.32.074.47a2.02 2.02 0 0 1-1.641.828a2.05 2.05 0 0 1-1.639-.824a.336.336 0 1 1 .538-.404c.255.341.656.556 1.1.556c.457 0 .854-.216 1.098-.551c.11-.15.32-.184.47-.075");
}

.i4docjyne {
  stop-color: var(--svg-color--ff9946, #FF9946);
  stop-opacity: 0;
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ij1ferbmv {
  stop-color: var(--svg-color--e19785, #E19785);
  stop-opacity: 0;
}

.imo-j1fmc {
  d: path("M18.028 8.504a1.1 1.1 0 0 1 1.289.873l.414 2.15l-.1-1.609a1.1 1.1 0 0 1 2.195-.136l.23 3.687l.38-.785a1.15 1.15 0 1 1 2.07 1.004l-.95 1.958c-.203.488-.212.939-.222 1.416c-.01.436-.019.893-.176 1.421c-.275.925-.823 1.667-1.062 1.922l-3.063.875c-2.36-.578-3.078-1.922-3.469-3.047a15.5 15.5 0 0 0-.765-1.844l-1.351-2.602a1.1 1.1 0 0 1 1.952-1.014l.225.432l-.539-1.568a1.1 1.1 0 0 1 2.081-.714l.471 1.372l-.482-2.502a1.1 1.1 0 0 1 .872-1.289");
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.keu1p0veb {
  d: path("M9.432 12.134a1.153 1.153 0 0 0 .1 2.267a94 94 0 0 1-.1-2.267");
}

.ki-2s9xtq {
  fill: var(--svg-color--3f3f3f, #3F3F3F);
  d: path("m20.767 6.742l-2.764-.306a.617.617 0 0 1-.55-.614c0-.405.386-.7.776-.59c.749.213 1.532.442 2.185.604c1.403.348 1.8 1.115 1.907 1.602c-.196-.313-.813-.555-1.554-.696");
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l7gss9bru {
  stop-color: var(--svg-color--c9887d, #C9887D);
}

.lk7dbcc7r {
  stop-color: var(--svg-color--ffd6bf, #FFD6BF);
}

.lmabwac7x {
  fill: var(--svg-color--0e0e0e, #0E0E0E);
  d: path("M14.517 13c.15.11.183.32.074.47a2.02 2.02 0 0 1-1.641.828a2.05 2.05 0 0 1-1.639-.824a.336.336 0 1 1 .538-.404c.255.341.656.556 1.1.556c.457 0 .854-.216 1.098-.551c.11-.15.32-.184.47-.075");
}

.lrdcrkb9v {
  stop-color: var(--svg-color--e5571e, #E5571E);
}

.lw14vgbrd {
  stop-color: var(--svg-color--e8b6a1, #E8B6A1);
}

.mgg31acdx {
  d: path("M21.448 5.56a2.8 2.8 0 0 1 1.529 1.268c.563.99.48 2.173-.128 3.046a1.9 1.9 0 0 0-.326 1.055v1.432a2.1 2.1 0 0 0-.805-.323l.095-1.937a1.75 1.75 0 0 0-1.663-1.727h-1.69a2.92 2.92 0 0 1-2.666-1.74a.8.8 0 0 0-.742-.505h-1.536c-2.226 0-4.03 1.824-4.03 4.075l.038 1.854c-.307.045-.627.148-.869.318V10.93a1.9 1.9 0 0 0-.326-1.055a2.88 2.88 0 0 1-.173-2.95a2.83 2.83 0 0 1 1.567-1.358a3.23 3.23 0 0 0 1.67-1.339a2.804 2.804 0 0 1 3.486-1.1c.46.201.979.201 1.44 0c.338-.142.71-.226 1.1-.226c1.016 0 1.905.55 2.398 1.365c.371.615.953 1.06 1.631 1.294");
}

.mlsv8jb5y {
  stop-color: var(--svg-color--d19787, #D19787);
}

.n__qyxjso {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m20.94 9.64l.671 8.437");
}

.ndg2zkbnv {
  stop-color: var(--svg-color--d3918e, #D3918E);
}

.nsb85pi4s {
  stop-color: var(--svg-color--e3b29d, #E3B29D);
}

.nwfpxhhly {
  d: path("M17.177 23.337a1 1 0 0 1 .723-1.221l5.303-1.339a1 1 0 0 1 1.213.718l2.414 9.29h-7.719z");
}

.o391lpb9t {
  fill: var(--svg-color--87004d, #87004D);
  d: path("M17.643 18.228a2.47 2.47 0 0 0-2.06-1.12c-.862 0-1.618.45-2.059 1.12c-.096.144.038.316.192.297h3.726c.153.039.296-.143.2-.297");
}

.o7w9zg64j {
  d: path("M25.583 30.784v-.39c0-5.4-4.47-9.787-9.99-9.787c-5.52.01-9.99 4.387-9.99 9.786v.391z");
}

.o8wr4h7sd {
  stop-color: var(--svg-color--e8af99, #E8AF99);
  stop-opacity: 0;
}

.oee7_jcbf {
  d: path("M15.583 23.608c-1.46 0-2.64-.912-2.64-2.04v-2.41c0-1.129 1.18-2.04 2.64-2.04s2.64.911 2.64 2.04v2.41c0 1.128-1.18 2.04-2.64 2.04");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.oxk0gpbzd {
  stop-color: var(--svg-color--d74a13, #D74A13);
  stop-opacity: 0;
}

.p8uhw_khn {
  stop-color: var(--svg-color--e19785, #E19785);
}

.pah2rdb4s {
  d: path("M9.771 17.434a4.72 4.72 0 0 0 4.686 4.108h2.276a4.72 4.72 0 0 0 4.686-4.108c.142-2.272.288-5.063.394-7.333a1.75 1.75 0 0 0-1.663-1.727h-1.69a2.92 2.92 0 0 1-2.667-1.74a.8.8 0 0 0-.742-.505h-1.535c-2.226 0-4.03 1.824-4.03 4.075c0 2.244.137 4.98.284 7.23");
}

.pgoodobuo {
  fill: var(--svg-color--202020, #202020);
  d: path("M11.48 10.218a3.35 3.35 0 0 1 2.097-.433a.335.335 0 0 1-.082.663a2.68 2.68 0 0 0-1.672.344q-.062.037-.09.058l-.02.014l-.004.002a.335.335 0 0 1-.41-.528z");
}

.pi95o6_xg {
  stop-color: var(--svg-color--231828, #231828);
}

.pnv4kibsp {
  stop-color: var(--svg-color--cb6d70, #CB6D70);
}

.q2140yplm {
  stop-color: var(--svg-color--fdc9ab, #FDC9AB);
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qtml67ysr {
  stop-color: var(--svg-color--fecab5, #FECAB5);
}

.rusf7f63f {
  stop-color: var(--svg-color--d79a81, #D79A81);
  stop-opacity: 0;
}

.sgbnv8bju {
  stop-color: var(--svg-color--ac7764, #AC7764);
}

.sozvcjboj {
  stop-color: var(--svg-color--262626, #262626);
}

.sxvgztbtq {
  fill: var(--svg-color--202020, #202020);
  d: path("M20.095 10.35c-.211-.185-.457-.38-.83-.497c-.366-.115-.826-.146-1.462-.069a.334.334 0 1 0 .082.664c.58-.07.936-.034 1.18.043c.24.075.4.197.59.363a.334.334 0 0 0 .44-.505");
}

.t0w03e0rr {
  stop-color: var(--svg-color--e8af99, #E8AF99);
}

.tgllzx6xq {
  stop-color: var(--svg-color--d54625, #D54625);
}

.tmqbcuz_q {
  stop-color: var(--svg-color--ffd6bf, #FFD6BF);
  stop-opacity: 0;
}

.tvol8bc0y {
  d: path("M21.456 15.078c.404-.013.783-.15 1.09-.372v1.123a2.62 2.62 0 0 1-1.616 2.435q.309-.658.417-1.423z");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.uu8x24bjn {
  stop-color: var(--svg-color--e5562d, #E5562D);
}

.uwp5l69ey {
  stroke: var(--svg-color--ffd6bf, #FFD6BF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m14.781 13.12l.688 1.531");
}

.v_-r5lbgt {
  stop-color: var(--svg-color--ff5016, #FF5016);
  stop-opacity: 0;
}

.vn7vddclp {
  d: path("M21.529 15.188q.121-1.924.223-3.849a1.941 1.941 0 0 1-.223 3.85");
}

.vztrb29ya {
  fill: var(--svg-color--23181c, #23181C);
  d: path("M15.873 6.502a3 3 0 0 1-.08-.165a.8.8 0 0 0-.741-.505h-1.535c-2.226 0-4.22 2.121-4.22 4.372v.332c-.41-.312-.736-.97-.736-2.036c0-1.292.943-1.946 1.544-2.362c.17-.118.312-.217.399-.306l.12-.126c.422-.447 1.173-1.244 2.484-1.592a6.7 6.7 0 0 1 1.986-.193c.472.022.805.43.805.903v1.661z");
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w9oqzlbnq {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m21.885 10.708l-.035-.762c-.013-.92-.774-1.68-1.695-1.719h-1.688c-1.072 0-1.923-.761-2.435-1.694c0 0-.148-.23-.27-.63c-.292-.96.651-1.707 1.64-1.538c1.251.214 2.765.622 3.855 1.333c2.104 1.372 1.736 3.845.628 5.01");
}

.whvu5ybpj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m23.675 13.31l-.938 1.89a3.56 3.56 0 0 0-.36 1.781c.08.969-.265 1.828-.64 2.234");
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.xh_onccts {
  d: path("M17.3 9.303a.946.946 0 0 1 1.108.75l.356 1.849l-.086-1.383a.946.946 0 1 1 1.888-.117l.197 3.17l.327-.675a.989.989 0 1 1 1.78.863l-.817 1.684c-.174.42-.182.807-.19 1.218c-.008.374-.017.767-.152 1.221c-.236.796-.707 1.434-.913 1.653l-2.634.752c-2.028-.497-2.646-1.652-2.982-2.62a13 13 0 0 0-.659-1.585l-1.161-2.238a.946.946 0 0 1 1.678-.872l.194.372l-.463-1.348a.946.946 0 0 1 1.79-.614l.404 1.18l-.415-2.152a.946.946 0 0 1 .75-1.108");
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.xppftxbjk {
  d: path("M9.73 15.078a2 2 0 0 1-1.09-.372v1.123a2.62 2.62 0 0 0 1.616 2.435a5 5 0 0 1-.417-1.423z");
}

.xz9sr4b2l {
  d: path("M17.74 21.263a.25.25 0 0 1 .182-.302l4.733-1.205a.25.25 0 0 1 .305.184l.274 1.13l-5.229 1.267z");
}

.yncacpbuq {
  d: path("M15.873 6.502a3 3 0 0 1-.08-.165a.8.8 0 0 0-.741-.505h-1.535c-2.226 0-4.22 2.121-4.22 4.372v.332c-.41-.312-.736-.97-.736-2.036c0-1.292.943-1.946 1.544-2.362c.17-.118.312-.217.399-.306l.12-.126c.422-.447 1.173-1.244 2.484-1.592a6.7 6.7 0 0 1 1.986-.193c.472.022.805.43.805.903v1.661z");
}

.yor2p9b5i {
  stop-color: var(--svg-color--ce978e, #CE978E);
}

.yxp43-b2w {
  stop-color: var(--svg-color--cf7675, #CF7675);
}

.yzag7e8_g {
  stop-color: var(--svg-color--ff764c, #FF764C);
}

.z022zguoo {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.525 10.555c.31-.222 1.082-.613 1.996-.46");
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

.zwpu2qbnf {
  stop-color: var(--svg-color--fabd9a, #FABD9A);
}

</style>
