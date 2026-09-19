<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="kdxurrb5l"/><path fill="url(#iFLGpNc)" class="p_e-k7cbk"/><path fill="url(#idBnOKb)" class="p_e-k7cbk"/><g filter="url(#iMLus8c)"><path fill="url(#iERHLDd)" class="le1pndjky"/><path fill="url(#irbtrEe)" class="le1pndjky"/><path fill="url(#iG9430b)" class="le1pndjky"/><path fill="url(#iwYWX8b)" class="le1pndjky"/></g><g filter="url(#itVGMHb)"><path fill="url(#iV5cJkr)" class="jj7jub4iq"/><path fill="url(#ioymdte)" class="jj7jub4iq"/><path fill="url(#is1F1he)" class="jj7jub4iq"/></g><path fill="url(#iepRZKl)" class="z408u8b1r"/><path fill="url(#ipiCJQe)" class="z408u8b1r"/><path fill="url(#iZyO3ye)" class="z408u8b1r"/><path clip-rule="evenodd" class="jsfdypblf"/><g filter="url(#i6QHGGI)"><path clip-rule="evenodd" class="d96f4j16q"/></g><path class="o9wuu5x1b"/><path fill="url(#ikAqgRd)" class="y3v72abak"/><path fill="url(#i8sOxje)" class="gkvlgqbjm"/><ellipse fill="url(#ihScDWc)" transform="scale(-1 1)rotate(74.61 -11.764 -.022)" class="l--rvobkj"/><g filter="url(#iuBrI8c)"><path fill="url(#iitL5Ce)" class="if64f89hh"/></g><g filter="url(#iEAbjzd)"><path fill="url(#isGtybn)" class="fkj2nijfp"/><path fill="url(#ibLTAvJ)" class="fkj2nijfp"/></g><g filter="url(#iyo0uMx)"><path class="n7_r_obfk"/><path fill="url(#i2lXewj)" class="y_3eji5af"/></g><g filter="url(#ivPO1cd)"><path class="e80eg5bhl"/><path fill="url(#iKccX5c)" class="grwl__ubh"/><path fill="url(#im9OVLc)" class="grwl__ubh"/></g><g filter="url(#i0gykoe)"><circle fill="url(#ituhdeb)" class="yzi2v60pl"/><circle fill="url(#iBIGF5U)" class="yzi2v60pl"/></g><g filter="url(#iEM0c4d)"><path fill="url(#iMvfgbc)" clip-rule="evenodd" class="k6--2_w9c"/></g><rect fill="url(#i9HZAie)" transform="scale(-1 1)rotate(45 -41.287 -13.074)" class="hrxlqmt6c"/><rect fill="url(#iwL7NEd)" transform="scale(-1 1)rotate(45 -41.287 -13.074)" class="hrxlqmt6c"/><rect fill="url(#i0csxTc)" transform="scale(-1 1)rotate(45 -41.287 -13.074)" class="hrxlqmt6c"/><rect transform="rotate(45 11.782 25.365)" class="c-ms0dq1b"/><rect fill="url(#i9Q7TNg)" transform="rotate(45 11.782 25.365)" class="ds0v_tl4r"/><rect fill="url(#i3xLhGc)" transform="rotate(45 11.782 25.365)" class="ds0v_tl4r"/><g filter="url(#iVXFUlJ)"><path fill="url(#iDU2Kzb)" class="r2ntrrblt"/></g><path fill="url(#ibgQKHl)" class="r2ntrrblt"/><path fill="url(#ipY2Bqc)" class="r2ntrrblt"/><g filter="url(#icXWbvJ)"><rect fill="url(#i3GpgEb)" class="v6ymu42gc"/><rect fill="url(#iIQ7Due)" class="v6ymu42gc"/></g><rect fill="url(#i9Og5Bb)" class="v6ymu42gc"/><g filter="url(#iPIWc9c)"><path stroke="url(#im1vwqc)" class="gqkzjlbuj"/></g><g filter="url(#iwveuOd)"><path stroke="url(#ivynPpc)" class="k1dzkgluc"/></g><path fill="url(#iYIHqTd)" class="o_hfrkbzf"/><path fill="url(#iuw6Ucc)" class="o_hfrkbzf"/><defs><radialGradient id="iFLGpNc" cx="0" cy="0" r="1" gradientTransform="rotate(101.587 .81 9.778)scale(.68058 .96065)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="ng2hgzbhn"/><stop offset=".684" class="nz7jfnb_b"/></radialGradient><radialGradient id="idBnOKb" cx="0" cy="0" r="1" gradientTransform="matrix(-.18357 -.3509 .5266 -.2755 10.53 11.595)" gradientUnits="userSpaceOnUse"><stop class="av0_6yb2f"/><stop offset="1" class="lhhdsccyq"/></radialGradient><radialGradient id="irbtrEe" cx="0" cy="0" r="1" gradientTransform="rotate(-53.18 17.35 .043)scale(1.06144 1.29411)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="pe7odhb7d"/><stop offset="1" class="ao9a_pbsn"/></radialGradient><radialGradient id="iG9430b" cx="0" cy="0" r="1" gradientTransform="rotate(-140 7.397 4.146)scale(6.51586 2.53177)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="vb_gc7b6b"/><stop offset="1" class="rhkf30kvu"/></radialGradient><radialGradient id="iwYWX8b" cx="0" cy="0" r="1" gradientTransform="matrix(.37586 .31539 -.49185 .58616 8.633 11.953)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="g87nnpbqu"/><stop offset="1" class="igg0ouipp"/></radialGradient><radialGradient id="iV5cJkr" cx="0" cy="0" r="1" gradientTransform="rotate(168.984 2.747 6.482)scale(3.88925 5.91237)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="lbq-lsb6f"/><stop offset="1" class="g-7ivnbav"/></radialGradient><radialGradient id="ioymdte" cx="0" cy="0" r="1" gradientTransform="rotate(166.088 2.984 4.89)scale(1.86588 3.00185)" gradientUnits="userSpaceOnUse"><stop class="tue5drbtp"/><stop offset="1" class="d6crxg3sz"/></radialGradient><radialGradient id="is1F1he" cx="0" cy="0" r="1" gradientTransform="rotate(-34.168 29.652 -2.23)scale(.6834 .33578)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="ja8qkqbty"/><stop offset="1" class="rxuswac8h"/></radialGradient><radialGradient id="iepRZKl" cx="0" cy="0" r="1" gradientTransform="matrix(-.78958 .5288 -.2581 -.38538 6.986 13.597)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="desyi4b3l"/><stop offset="1" class="ene2socfu"/></radialGradient><radialGradient id="ipiCJQe" cx="0" cy="0" r="1" gradientTransform="rotate(50.843 -10.742 13.71)scale(1.50878 1.57221)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="kplqz4bbv"/><stop offset="1" class="necsq7bka"/></radialGradient><radialGradient id="ikAqgRd" cx="0" cy="0" r="1" gradientTransform="matrix(-.22077 .2631 -.51117 -.42892 8.897 11.691)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="i8sOxje" cx="0" cy="0" r="1" gradientTransform="matrix(-.20185 .24055 -.52057 -.4368 9.053 11.548)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="isGtybn" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.09375 .5802 0 20.802 15.15)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="u7ghpzbeu"/><stop offset="1" class="e6d6f-wgx"/></radialGradient><radialGradient id="ibLTAvJ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49998 -3.09376 1.67378 -.81152 23.52 14.713)" gradientUnits="userSpaceOnUse"><stop class="evh2ptbcz"/><stop offset="1" class="p7g900bdp"/><stop offset="1" class="bp_f34bqt"/></radialGradient><radialGradient id="i2lXewj" cx="0" cy="0" r="1" gradientTransform="rotate(-45.372 16.754 -19.196)scale(6.80605 3.84932)" gradientUnits="userSpaceOnUse"><stop class="xy0op_eyz"/><stop offset="1" class="p53pr-blg"/></radialGradient><radialGradient id="iKccX5c" cx="0" cy="0" r="1" gradientTransform="rotate(-150.994 14.7 4.713)scale(3.60894 4.34333)" gradientUnits="userSpaceOnUse"><stop class="v7qdu5boj"/><stop offset="1" class="kdd3vfboh"/></radialGradient><radialGradient id="im9OVLc" cx="0" cy="0" r="1" gradientTransform="matrix(1.0625 2.625 -1.48498 .60106 19.49 13.838)" gradientUnits="userSpaceOnUse"><stop class="xwt5g5sto"/><stop offset="1" class="x484pmbxx"/></radialGradient><radialGradient id="ituhdeb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.90038 -2.5625 2.1013 -1.55835 20.751 15.874)" gradientUnits="userSpaceOnUse"><stop class="nmlj7qb8u"/><stop offset="1" class="wijlc3r_o"/></radialGradient><radialGradient id="iBIGF5U" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 -2.34375 2.00586 1.12328 16.845 16.405)" gradientUnits="userSpaceOnUse"><stop class="n35yqc9wi"/><stop offset="1" class="e9nymn0gr"/></radialGradient><radialGradient id="iMvfgbc" cx="0" cy="0" r="1" gradientTransform="rotate(-138.668 11.43 4.377)scale(4.20282 3.66642)" gradientUnits="userSpaceOnUse"><stop class="fgfvt8_za"/><stop offset="1" class="kb1q69u9p"/></radialGradient><radialGradient id="iwL7NEd" cx="0" cy="0" r="1" gradientTransform="rotate(79.16 -.565 1.44)scale(1.58615 1.72717)" gradientUnits="userSpaceOnUse"><stop class="lkqdv0bwp"/><stop offset="1" class="vou8iltko"/></radialGradient><radialGradient id="i0csxTc" cx="0" cy="0" r="1" gradientTransform="rotate(-89.442 2.4 1.929)scale(1.40065 .72809)" gradientUnits="userSpaceOnUse"><stop class="go679fbfb"/><stop offset="1" class="jo92-ub-i"/></radialGradient><radialGradient id="i3xLhGc" cx="0" cy="0" r="1" gradientTransform="rotate(-47.663 40.378 1.5)scale(.6726 1.0441)" gradientUnits="userSpaceOnUse"><stop class="brjpzuruh"/><stop offset="1" class="ea_rhjb1f"/></radialGradient><radialGradient id="iDU2Kzb" cx="0" cy="0" r="1" gradientTransform="matrix(-15.56247 -.06247 .03888 -9.68481 25.99 22.307)" gradientUnits="userSpaceOnUse"><stop class="vn7ncpb8d"/><stop offset="1" class="htcu-gvqd"/></radialGradient><radialGradient id="ibgQKHl" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.625 -39.1562 0 17.115 19.37)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="mh1kw6b0u"/><stop offset="1" class="mg_zulb9j"/></radialGradient><radialGradient id="i3GpgEb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.25 -15.4957 0 25.24 16.65)" gradientUnits="userSpaceOnUse"><stop class="ypx_bsb1m"/><stop offset="1" class="o3pqq4zbd"/></radialGradient><radialGradient id="im1vwqc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.71874 10.18756 -7.15636 -4.71965 28.77 3.62)" gradientUnits="userSpaceOnUse"><stop offset=".008" class="yi5996bix"/><stop offset="1" class="p_197nrym"/></radialGradient><radialGradient id="ivynPpc" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 -3.53125 2.69792 1.14602 19.538 6.572)" gradientUnits="userSpaceOnUse"><stop offset=".008" class="yi5996bix"/><stop offset="1" class="p_197nrym"/></radialGradient><radialGradient id="iYIHqTd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.53418 0 0 -3.55867 20.646 8.611)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="yi5996bix"/><stop offset=".717" class="wvcdyrpfm"/></radialGradient><filter id="iMLus8c" width="7.789" height="6.596" x="4.183" y="9.463" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.403922 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24058"/></filter><filter id="itVGMHb" width="5.592" height="8.621" x="2.465" y="8.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.14902 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24058"/></filter><filter id="i6QHGGI" width=".814" height="1.199" x="7.14" y="10.554" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.168627 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24058"/></filter><filter id="iuBrI8c" width="3.831" height="3.046" x="2.457" y="12.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24058" stdDeviation=".25"/></filter><filter id="iEAbjzd" width="7.367" height="4.959" x="17.412" y="12.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".1"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.494118 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24058"/></filter><filter id="iyo0uMx" width="9.125" height="15.5" x="17.927" y="1.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.501961 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24058"/></filter><filter id="ivPO1cd" width="14.805" height="6.438" x="11.177" y="12.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.678431 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24058"/></filter><filter id="i0gykoe" width="5.582" height="5.582" x="16.06" y="13.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24058" stdDeviation=".25"/></filter><filter id="iEM0c4d" width="6.341" height="6.485" x="11.286" y="12.793" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24058" stdDeviation=".25"/></filter><filter id="iVXFUlJ" width="28.578" height="11" x="3.771" y="16.807" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="3" dy="-1"/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.654902 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24058"/></filter><filter id="icXWbvJ" width="28.344" height="2.496" x="2.662" y="15.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.698039 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24058"/></filter><filter id="iPIWc9c" width="5.047" height="14.518" x="21.786" y="1.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24058" stdDeviation=".25"/></filter><filter id="iwveuOd" width="2.999" height="4.468" x="17.976" y="2.604" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24058" stdDeviation=".25"/></filter><linearGradient id="iERHLDd" x1="7.884" x2="10.361" y1="14.204" y2="11.589" gradientUnits="userSpaceOnUse"><stop class="xwzzv0ryq"/><stop offset="1" class="l3_0v7cyw"/></linearGradient><linearGradient id="iZyO3ye" x1="7.096" x2="6.988" y1="13.598" y2="13.75" gradientUnits="userSpaceOnUse"><stop class="yzpor-bup"/><stop offset="1" class="jo-sb289k"/></linearGradient><linearGradient id="ihScDWc" x1="-.009" x2=".225" y1=".062" y2=".139" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iitL5Ce" x1="5.335" x2="2.186" y1="14.574" y2="12.661" gradientUnits="userSpaceOnUse"><stop offset=".421" class="sj3owrynx"/><stop offset="1" class="i4z7nbbdt"/></linearGradient><linearGradient id="i9HZAie" x1="1.641" x2="-.116" y1="2.961" y2="3.171" gradientUnits="userSpaceOnUse"><stop class="t7wbu9b2k"/><stop offset="1" class="t9935ox4b"/></linearGradient><linearGradient id="i9Q7TNg" x1="11.468" x2="13.015" y1="28.867" y2="28.624" gradientUnits="userSpaceOnUse"><stop class="gbuoa-pfp"/><stop offset="1" class="h8mgf7b3a"/></linearGradient><linearGradient id="ipY2Bqc" x1="16.56" x2="16.56" y1="17.807" y2="19.213" gradientUnits="userSpaceOnUse"><stop class="nihdd8-bi"/><stop offset="1" class="x6h_eubpf"/></linearGradient><linearGradient id="iIQ7Due" x1="2.865" x2="12.115" y1="17.244" y2="17.244" gradientUnits="userSpaceOnUse"><stop class="d673tl90q"/><stop offset="1" class="f-q8xrbdi"/></linearGradient><linearGradient id="i9Og5Bb" x1="17.927" x2="17.927" y1="18.154" y2="17.619" gradientUnits="userSpaceOnUse"><stop class="b0b_4h8fx"/><stop offset="1" class="vngbibvro"/></linearGradient><linearGradient id="iuw6Ucc" x1="19.412" x2="19.412" y1="8.611" y2="8.104" gradientUnits="userSpaceOnUse"><stop class="dcrtohb5r"/><stop offset="1" class="k3-gog70w"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-taking-bath-medium" /></template>
<style>
.ao9a_pbsn {
  stop-color: var(--svg-color--9c6e67, #9C6E67);
  stop-opacity: 0;
}

.av0_6yb2f {
  stop-color: var(--svg-color--a66d75, #A66D75);
}

.b0b_4h8fx {
  stop-color: var(--svg-color--b1a1c2, #B1A1C2);
}

.bp_f34bqt {
  stop-color: var(--svg-color--bd9b86, #BD9B86);
  stop-opacity: 0;
}

.brjpzuruh {
  stop-color: var(--svg-color--88828e, #88828E);
}

.c-ms0dq1b {
  width: 1.608px;
  height: 5.132px;
  x: 11.782px;
  y: 25.365px;
  fill: var(--svg-color--735f86, #735F86);
  rx: 0.804px;
}

.d673tl90q {
  stop-color: var(--svg-color--bcb9bf, #BCB9BF);
}

.d6crxg3sz {
  stop-color: var(--svg-color--68514d, #68514D);
  stop-opacity: 0;
}

.d96f4j16q {
  fill: var(--svg-color--403235, #403235);
  fill-rule: evenodd;
  d: path("M7.734 11.101a1 1 0 0 1 .16-.22a.188.188 0 1 0-.256-.277a1.3 1.3 0 0 0-.234.317c-.078.143-.15.328-.163.532a.188.188 0 0 0 .376.023a.9.9 0 0 1 .117-.375");
}

.dcrtohb5r {
  stop-color: var(--svg-color--807f86, #807F86);
}

.desyi4b3l {
  stop-color: var(--svg-color--ba9682, #BA9682);
}

.ds0v_tl4r {
  width: 1.608px;
  height: 5.132px;
  x: 11.782px;
  y: 25.365px;
  rx: 0.804px;
}

.e6d6f-wgx {
  stop-color: var(--svg-color--a07f6c, #A07F6C);
}

.e80eg5bhl {
  fill: var(--svg-color--4bd1f1, #4BD1F1);
  d: path("M14.396 19.432a3.22 3.22 0 0 0 2.705-1.475a2.5 2.5 0 0 0 1.658.615c.66 0 1.256-.245 1.687-.64c.51.615 1.401 1.023 2.415 1.023c1.585 0 2.87-.998 2.87-2.23c0-1.051-1.285-2.23-2.87-2.23c-.79 0-1.504.247-2.023.647a.107.107 0 0 1-.15-.019c-.432-.546-1.135-.902-1.929-.902a2.5 2.5 0 0 0-1.417.428a.107.107 0 0 1-.152-.035a3.219 3.219 0 1 0-2.794 4.818");
}

.e9nymn0gr {
  stop-color: var(--svg-color--3dc6eb, #3DC6EB);
  stop-opacity: 0;
}

.ea_rhjb1f {
  stop-color: var(--svg-color--88828e, #88828E);
  stop-opacity: 0;
}

.ene2socfu {
  stop-color: var(--svg-color--ad8570, #AD8570);
}

.evh2ptbcz {
  stop-color: var(--svg-color--bd9b86, #BD9B86);
}

.f-q8xrbdi {
  stop-color: var(--svg-color--bcb9bf, #BCB9BF);
  stop-opacity: 0;
}

.fgfvt8_za {
  stop-color: var(--svg-color--6bf3ff, #6BF3FF);
}

.fkj2nijfp {
  d: path("M18.501 13.578a2.288 2.288 0 0 1 4.216-.309l1.812 3.6h-7.117z");
}

.ft5dv1b6b {
  fill: none;
}

.g-7ivnbav {
  stop-color: var(--svg-color--583e3b, #583E3B);
}

.g87nnpbqu {
  stop-color: var(--svg-color--a67d65, #A67D65);
}

.gbuoa-pfp {
  stop-color: var(--svg-color--807d83, #807D83);
}

.gkvlgqbjm {
  d: path("M8.81 11.837a1 1 0 0 1-.072-.055c-.179-.15-.26-.347-.181-.44c.078-.094.286-.048.465.102q.036.03.066.062z");
}

.go679fbfb {
  stop-color: var(--svg-color--bebac2, #BEBAC2);
}

.gqkzjlbuj {
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M22.302 2.666c1.219-.052 3.656.94 3.656 3.766v9.375");
}

.grwl__ubh {
  d: path("M14.396 19.432a3.22 3.22 0 0 0 2.705-1.475a2.5 2.5 0 0 0 1.658.615c.66 0 1.256-.245 1.687-.64c.51.615 1.401 1.023 2.415 1.023c1.585 0 2.87-.998 2.87-2.23c0-1.051-1.285-2.23-2.87-2.23c-.79 0-1.504.247-2.023.647a.107.107 0 0 1-.15-.019c-.432-.546-1.135-.902-1.929-.902a2.5 2.5 0 0 0-1.417.428a.107.107 0 0 1-.152-.035a3.219 3.219 0 1 0-2.794 4.818");
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.h8mgf7b3a {
  stop-color: var(--svg-color--807d83, #807D83);
  stop-opacity: 0;
}

.hrxlqmt6c {
  width: 1.608px;
  height: 5.132px;
  rx: 0.804px;
}

.htcu-gvqd {
  stop-color: var(--svg-color--c7bdd3, #C7BDD3);
}

.i4z7nbbdt {
  stop-color: var(--svg-color--644a48, #644A48);
  stop-opacity: 0;
}

.if64f89hh {
  d: path("M4.548 13.257a16 16 0 0 0 1.24 1.495a3.64 3.64 0 0 1-2.55-.618c-.52-.354-.264-1.165.335-1.357c.432-.14.707.114.975.48");
}

.igg0ouipp {
  stop-color: var(--svg-color--a67d65, #A67D65);
  stop-opacity: 0;
}

.ja8qkqbty {
  stop-color: var(--svg-color--5f4745, #5F4745);
}

.jj7jub4iq {
  d: path("M6.401 8.56c-.66-.165-1.14.2-1.35.48c-.65.865-.458 1.217-1.24 1.836c-.826.654-1.106 1.083-1.236 1.55l-.003.01c-.128.46-.394 1.412 1.018 2.597c1.3 1.091 2.376 1.203 2.81 1.185l-.022.058c-.106.29.054.58.344.687c.248.091.56-.058.766-.401c.236-.393.402-.686.53-.92a.31.31 0 0 0-.074-.388l-1.07-.899c-.451-.378-.454-.922-.416-1.13c-.454-.406-.548-.729-.465-1.056c.137-.543.33-.585 1.048-1.555c.723-.976.187-1.848-.64-2.054");
}

.jo-sb289k {
  stop-color: var(--svg-color--a17363, #A17363);
  stop-opacity: 0;
}

.jo92-ub-i {
  stop-color: var(--svg-color--968da0, #968DA0);
  stop-opacity: 0;
}

.jsfdypblf {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M9.612 13.059a.155.155 0 0 0 .171.14c.417-.04.753-.323.852-.42a.157.157 0 0 0-.219-.225c-.085.083-.355.303-.663.333a.157.157 0 0 0-.141.172");
}

.k1dzkgluc {
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M20.226 3.385c-.458.406-1.375 1.612-1.375 3.187");
}

.k3-gog70w {
  stop-color: var(--svg-color--8f9198, #8F9198);
  stop-opacity: 0;
}

.k6--2_w9c {
  fill-rule: evenodd;
  d: path("M17.128 15.157c-.476.39-.798.967-.846 1.628c-.031.414.049.811.214 1.161a2.742 2.742 0 1 1 .631-2.789");
}

.kb1q69u9p {
  stop-color: var(--svg-color--6bf3ff, #6BF3FF);
  stop-opacity: 0;
}

.kdd3vfboh {
  stop-color: var(--svg-color--66ebff, #66EBFF);
  stop-opacity: 0;
}

.kdxurrb5l {
  fill: var(--svg-color--886761, #886761);
  d: path("m8.3 15.656l1.423-1.033l1.332 1.832l-1.422 1.033z");
}

.kplqz4bbv {
  stop-color: var(--svg-color--9e6563, #9E6563);
  stop-opacity: 0;
}

.l--rvobkj {
  rx: 0.081px;
  ry: 0.11px;
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l3_0v7cyw {
  stop-color: var(--svg-color--ab826c, #AB826C);
}

.lbq-lsb6f {
  stop-color: var(--svg-color--503339, #503339);
}

.le1pndjky {
  d: path("M8.787 10.314c-.802-.61-1.383-.672-1.59-.646L4.182 13.26l2.993 2.614c2.742.88 4.965-1.592 4.545-2.592s-2.006-2.262-2.934-2.968");
}

.lhhdsccyq {
  stop-color: var(--svg-color--a66d75, #A66D75);
  stop-opacity: 0;
}

.lkqdv0bwp {
  stop-color: var(--svg-color--7a6a8b, #7A6A8B);
}

.mg_zulb9j {
  stop-color: var(--svg-color--a887c7, #A887C7);
}

.mh1kw6b0u {
  stop-color: var(--svg-color--bba9cd, #BBA9CD);
  stop-opacity: 0;
}

.n35yqc9wi {
  stop-color: var(--svg-color--3dc6eb, #3DC6EB);
}

.n7_r_obfk {
  fill: var(--svg-color--adadad, #ADADAD);
  d: path("M24.952 6.182v10.937h1.6V6.182a4.312 4.312 0 1 0-8.625 0v1.03h1.6v-1.03a2.713 2.713 0 0 1 5.425 0");
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.necsq7bka {
  stop-color: var(--svg-color--9e6563, #9E6563);
}

.ng2hgzbhn {
  stop-color: var(--svg-color--bf9580, #BF9580);
}

.nihdd8-bi {
  stop-color: var(--svg-color--a090b0, #A090B0);
}

.nmlj7qb8u {
  stop-color: var(--svg-color--6ef3ff, #6EF3FF);
}

.nz7jfnb_b {
  stop-color: var(--svg-color--ad7f6d, #AD7F6D);
}

.o_hfrkbzf {
  d: path("M21.091 8.611c.28 0 .509-.23.456-.504c-.249-1.307-1.37-2.293-2.714-2.293S16.37 6.8 16.12 8.107c-.052.274.177.504.457.504z");
}

.o3pqq4zbd {
  stop-color: var(--svg-color--d5d3d8, #D5D3D8);
}

.o9wuu5x1b {
  fill: var(--svg-color--fff, #fff);
  d: path("m9.142 11.442l-.798.951c-.377-.316-.504-.785-.284-1.048c.22-.262.705-.219 1.082.097");
}

.p_197nrym {
  stop-color: var(--svg-color--c1c1c2, #C1C1C2);
  stop-opacity: 0;
}

.p_e-k7cbk {
  d: path("M9.895 10.877a1.26 1.26 0 0 1-.648-.122l-.145.173l1.083.909c.305-.097.532-.41.408-.663c-.106-.217-.364-.337-.698-.297");
}

.p53pr-blg {
  stop-color: var(--svg-color--a09fa0, #A09FA0);
  stop-opacity: 0;
}

.p7g900bdp {
  stop-color: var(--svg-color--8e706a, #8E706A);
  stop-opacity: 0;
}

.pe7odhb7d {
  stop-color: var(--svg-color--916051, #916051);
}

.r2ntrrblt {
  d: path("m5.227 22.376l-1.456-4.57h25.578l-1.477 4.59a7.8 7.8 0 0 1-7.425 5.41h-7.788a7.8 7.8 0 0 1-7.432-5.43");
}

.rhkf30kvu {
  stop-color: var(--svg-color--bd927e, #BD927E);
  stop-opacity: 0;
}

.rxuswac8h {
  stop-color: var(--svg-color--5f4745, #5F4745);
  stop-opacity: 0;
}

.sj3owrynx {
  stop-color: var(--svg-color--644a48, #644A48);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t7wbu9b2k {
  stop-color: var(--svg-color--887a96, #887A96);
}

.t9935ox4b {
  stop-color: var(--svg-color--a9a6ac, #A9A6AC);
}

.tue5drbtp {
  stop-color: var(--svg-color--68514d, #68514D);
}

.u7ghpzbeu {
  stop-color: var(--svg-color--956d71, #956D71);
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.v6ymu42gc {
  width: 27.844px;
  height: 2.246px;
  x: 2.662px;
  y: 15.908px;
  rx: 1.123px;
}

.v7qdu5boj {
  stop-color: var(--svg-color--66ebff, #66EBFF);
}

.vb_gc7b6b {
  stop-color: var(--svg-color--c19382, #C19382);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vn7ncpb8d {
  stop-color: var(--svg-color--e1daea, #E1DAEA);
}

.vngbibvro {
  stop-color: var(--svg-color--bbb2c3, #BBB2C3);
  stop-opacity: 0;
}

.vou8iltko {
  stop-color: var(--svg-color--7a6a8b, #7A6A8B);
  stop-opacity: 0;
}

.wijlc3r_o {
  stop-color: var(--svg-color--6ef3ff, #6EF3FF);
  stop-opacity: 0;
}

.wvcdyrpfm {
  stop-color: var(--svg-color--929192, #929192);
}

.x484pmbxx {
  stop-color: var(--svg-color--6af0ff, #6AF0FF);
  stop-opacity: 0;
}

.x6h_eubpf {
  stop-color: var(--svg-color--bcb0c8, #BCB0C8);
  stop-opacity: 0;
}

.xwt5g5sto {
  stop-color: var(--svg-color--6af0ff, #6AF0FF);
}

.xwzzv0ryq {
  stop-color: var(--svg-color--a87a72, #A87A72);
}

.xy0op_eyz {
  stop-color: var(--svg-color--a09fa0, #A09FA0);
}

.y_3eji5af {
  d: path("M24.952 6.182v10.937h1.6V6.182a4.312 4.312 0 1 0-8.625 0v1.03h1.6v-1.03a2.713 2.713 0 0 1 5.425 0");
}

.y3v72abak {
  d: path("m8.653 12.024l-.004-.003c-.308-.258-.447-.6-.31-.763c.136-.163.497-.085.805.173l.004.003z");
}

.yi5996bix {
  stop-color: var(--svg-color--c1c1c2, #C1C1C2);
}

.ypx_bsb1m {
  stop-color: var(--svg-color--fefcff, #FEFCFF);
}

.yzi2v60pl {
  cx: 18.851px;
  cy: 16.73px;
  r: 2.291px;
}

.yzpor-bup {
  stop-color: var(--svg-color--a17363, #A17363);
}

.z408u8b1r {
  d: path("m7.949 14.154l-1.546-.97a.913.913 0 0 0 1.546.97");
}

</style>
