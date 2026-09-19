<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iv5QCeb)" transform="scale(-1 1)rotate(-4.337 80.738 265.297)" class="z8jy9-b3h"/><path class="s972eabyx"/><path fill="url(#im4Bx3F)" class="uc8p_0bsw"/><path fill="url(#iJXSqob)" class="uc8p_0bsw"/><path fill="url(#iul56Vd)" class="uc8p_0bsw"/><path fill="url(#iC8Djdd)" class="uc8p_0bsw"/><path fill="url(#ipz01Pe)" class="uc8p_0bsw"/><path fill="url(#ixWZb9b)" class="teubnce1a"/><path fill="url(#iKWEGTd)" class="teubnce1a"/><path fill="url(#iPOU6zd)" class="teubnce1a"/><path fill="url(#iHQNwLc)" class="teubnce1a"/><path fill="url(#ikcJavp)" class="teubnce1a"/><path fill="url(#iNDEknb)" class="teubnce1a"/><circle fill="url(#iXXSmAb)" transform="matrix(-1 0 0 1 10.426 11.42)" class="mftxrcb_l"/><g filter="url(#iFr5A9c)"><path clip-rule="evenodd" class="nwysaqbbn"/></g><path class="ntxow7bsx"/><path fill="url(#i3dyp5d)" class="w9e_hp45s"/><path fill="url(#i3Q5fmb)" class="w9e_hp45s"/><path fill="url(#iMR4Szd)" class="w9e_hp45s"/><rect transform="matrix(-1 0 0 1 27.262 10.005)" class="u9s7qvbon"/><path fill="url(#ivAumjJ)" class="s9u_pkb1z"/><path fill="url(#ika88Bc)" class="s9u_pkb1z"/><path fill="url(#i0ebAkc)" class="s9u_pkb1z"/><path fill="url(#iL2rkVb)" class="s9u_pkb1z"/><g filter="url(#iN6vAhc)"><path class="p3w7zobfd"/><path fill="url(#isjK0Qc)" class="g03wnfdbp"/><path fill="url(#izzdQhe)" class="g03wnfdbp"/></g><path fill="url(#i1PKCGe)" class="g03wnfdbp"/><g filter="url(#iBud8Ib)"><path class="ra4b_vxmi"/><path fill="url(#iklbMIE)" class="jul0_iufc"/><path fill="url(#iTm2JKy)" class="jul0_iufc"/></g><g filter="url(#iJf8asc)"><path stroke="url(#iIDoFIe)" class="mg7jlrprx"/></g><path class="cwn5j3-fq"/><path fill="url(#iXi37Ge)" class="u43aj25jg"/><path fill="url(#iQQmKNd)" class="u43aj25jg"/><path fill="url(#iuFD7Md)" class="u43aj25jg"/><g filter="url(#iONLvib)"><path class="sa2u8w_4a"/><path fill="url(#irzfBZr)" class="gfogqobsd"/></g><path class="dn7klsb_e"/><path fill="url(#iJiFxtd)" class="x0ts0cb2w"/><path fill="url(#i3jyH6d)" class="x0ts0cb2w"/><path fill="url(#iQIsgRP)" class="x0ts0cb2w"/><path fill="url(#iNEJ4se)" class="x0ts0cb2w"/><path fill="url(#ih0MGqc)" class="x0ts0cb2w"/><path fill="url(#iOg4Xae)" class="goyescc5e"/><g filter="url(#iQEhjic)"><path fill="url(#ideIhmW)" class="jgi7b6w2r"/><path fill="url(#i53xlJe)" class="jgi7b6w2r"/></g><g filter="url(#i1aNFCd)"><path fill="url(#i5e48Ce)" class="ppehd5bdz"/></g><path fill="url(#iJgCPPc)" class="ppehd5bdz"/><path fill="url(#iif8WEl)" class="p6l1enb-u"/><path clip-rule="evenodd" class="n56o4pn0v"/><path class="co-v7wd3f"/><path fill="url(#i5LxmEe)" class="sef70m78x"/><path fill="url(#iymgfpb)" class="qrrjvfgyy"/><ellipse fill="url(#ipECBte)" transform="scale(-1 1)rotate(24.61 -22.741 -45.833)" class="m1l7k9jve"/><g filter="url(#iwkf42c)"><path class="p082bkbzi"/></g><defs><radialGradient id="im4Bx3F" cx="0" cy="0" r="1" gradientTransform="matrix(-7.06247 3.6563 -1.3298 -2.56862 27.703 9.915)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="m8pmc0btt"/><stop offset="1" class="m72ygetof"/></radialGradient><radialGradient id="iJXSqob" cx="0" cy="0" r="1" gradientTransform="matrix(-6.99996 5.0938 -5.69913 -7.8318 27.016 9.04)" gradientUnits="userSpaceOnUse"><stop offset=".757" class="z26-wfbav"/><stop offset=".956" class="iou487baj"/></radialGradient><radialGradient id="iul56Vd" cx="0" cy="0" r="1" gradientTransform="matrix(.85936 1.25 -.4913 .33776 26.922 10.932)" gradientUnits="userSpaceOnUse"><stop offset=".418" class="yeyqi9phi"/><stop offset="1" class="j9k09pb-s"/></radialGradient><radialGradient id="iC8Djdd" cx="0" cy="0" r="1" gradientTransform="matrix(-.59003 .20312 -.95675 -2.77925 28.465 11.088)" gradientUnits="userSpaceOnUse"><stop class="mcvrg0kam"/><stop offset="1" class="q-30hhb4p"/></radialGradient><radialGradient id="ipz01Pe" cx="0" cy="0" r="1" gradientTransform="matrix(.78125 .57812 -.69035 .9329 26.72 9.869)" gradientUnits="userSpaceOnUse"><stop class="bjjn4ob6s"/><stop offset="1" class="snqm-cbpd"/></radialGradient><radialGradient id="iKWEGTd" cx="0" cy="0" r="1" gradientTransform="matrix(1.22254 -5.1875 2.96948 .69982 17.605 16.947)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="s6seicc8w"/><stop offset="1" class="yjn3q9srk"/></radialGradient><radialGradient id="iPOU6zd" cx="0" cy="0" r="1" gradientTransform="matrix(-.5907 5.65625 -2.14876 -.2244 20.576 12.541)" gradientUnits="userSpaceOnUse"><stop class="kve1gec_d"/><stop offset="1" class="r0_3lybww"/></radialGradient><radialGradient id="iHQNwLc" cx="0" cy="0" r="1" gradientTransform="matrix(2.40625 .71875 -1.45293 4.86416 14.891 13.353)" gradientUnits="userSpaceOnUse"><stop class="wpy2jtqib"/><stop offset="1" class="u6kcyml4j"/></radialGradient><radialGradient id="ikcJavp" cx="0" cy="0" r="1" gradientTransform="rotate(-155.706 9.98 3.576)scale(1.76241 2.14376)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="p5n-ewbqx"/><stop offset="1" class="q11m-vutr"/></radialGradient><radialGradient id="iNDEknb" cx="0" cy="0" r="1" gradientTransform="matrix(1.03125 .60937 -.64188 1.08628 18.323 10.634)" gradientUnits="userSpaceOnUse"><stop class="gjadyfboc"/><stop offset="1" class="asuvzebmi"/></radialGradient><radialGradient id="iXXSmAb" cx="0" cy="0" r="1" gradientTransform="matrix(1.01953 .46875 -.49222 1.07057 0 .714)" gradientUnits="userSpaceOnUse"><stop class="bmfdee-fc"/><stop offset=".906" class="y5luhbaev"/></radialGradient><radialGradient id="i3Q5fmb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 .1875 -.31663 -2.16355 19.328 9.947)" gradientUnits="userSpaceOnUse"><stop class="wtj81mbzy"/><stop offset="1" class="k870jjb1v"/></radialGradient><radialGradient id="iMR4Szd" cx="0" cy="0" r="1" gradientTransform="matrix(.875 .42186 -.65916 1.36719 14.64 8.431)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="gz3om4b5e"/><stop offset="1" class="s9nkndynh"/></radialGradient><radialGradient id="i0ebAkc" cx="0" cy="0" r="1" gradientTransform="matrix(4.65317 9.34098 -2.71885 1.35439 17.916 21.12)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="y_4ptxbzf"/><stop offset="1" class="ado7u1b7k"/></radialGradient><radialGradient id="iL2rkVb" cx="0" cy="0" r="1" gradientTransform="matrix(1.82682 4.82558 -1.33887 .50686 18.089 21.086)" gradientUnits="userSpaceOnUse"><stop class="hpbocun_g"/><stop offset="1" class="umrurxb6b"/></radialGradient><radialGradient id="i1PKCGe" cx="0" cy="0" r="1" gradientTransform="rotate(-161.643 16.291 11.706)scale(.94262 1.56541)" gradientUnits="userSpaceOnUse"><stop class="rmzq06bzd"/><stop offset="1" class="n1b4mhj1w"/></radialGradient><radialGradient id="iTm2JKy" cx="0" cy="0" r="1" gradientTransform="rotate(119.055 .84 14.783)scale(2.25217 1.02691)" gradientUnits="userSpaceOnUse"><stop class="nkql81bxe"/><stop offset="1" class="bi5pn_1vn"/></radialGradient><radialGradient id="irzfBZr" cx="0" cy="0" r="1" gradientTransform="matrix(-2.4375 4.75 -1.7011 -.87293 14.985 18.76)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="v1sha93vg"/><stop offset="1" class="kg-rnkb9f"/></radialGradient><radialGradient id="iJiFxtd" cx="0" cy="0" r="1" gradientTransform="rotate(128.66 4.96 12.833)scale(4.60225 17.5153)" gradientUnits="userSpaceOnUse"><stop offset=".554" class="j96xv6b5h"/><stop offset="1" class="osaguabiz"/></radialGradient><radialGradient id="i3jyH6d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.01137 -2.1808 7.2546 -3.3644 17.464 22.458)" gradientUnits="userSpaceOnUse"><stop class="sq7_rccwx"/><stop offset="1" class="n8gqlhnrc"/></radialGradient><radialGradient id="iQIsgRP" cx="0" cy="0" r="1" gradientTransform="matrix(2.05437 1.35958 -1.29324 1.95413 13.956 16.8)" gradientUnits="userSpaceOnUse"><stop class="gewgt1jbg"/><stop offset="1" class="roa1y3bvy"/></radialGradient><radialGradient id="ih0MGqc" cx="0" cy="0" r="1" gradientTransform="rotate(-154.573 11.17 6.459)scale(2.11071 .26513)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="c6vpnsb1w"/><stop offset="1" class="j23k_cb2p"/></radialGradient><radialGradient id="iOg4Xae" cx="0" cy="0" r="1" gradientTransform="matrix(-.3125 .60583 -.77155 -.39799 22.203 6.084)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="fvok_qxen"/><stop offset="1" class="suyap8bzv"/></radialGradient><radialGradient id="i53xlJe" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 -.04687 .05715 1.0287 18.664 5.67)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="d7kch3t0q"/><stop offset="1" class="admd7db0k"/></radialGradient><radialGradient id="i5e48Ce" cx="0" cy="0" r="1" gradientTransform="matrix(3.4375 3.125 -3.54355 3.8979 16.789 3.008)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="jve2rcqoj"/><stop offset="1" class="kpbiulbbs"/></radialGradient><radialGradient id="iJgCPPc" cx="0" cy="0" r="1" gradientTransform="matrix(.11717 -1.30469 2.76647 .24846 17.422 7.202)" gradientUnits="userSpaceOnUse"><stop offset=".064" class="jfv70ccah"/><stop offset="1" class="b30rr0b3q"/></radialGradient><radialGradient id="iif8WEl" cx="0" cy="0" r="1" gradientTransform="matrix(.45312 .9414 -1.52974 .7363 18.359 5.49)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="bervkqbmz"/><stop offset="1" class="c479w-bpn"/></radialGradient><radialGradient id="i5LxmEe" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 0 0 -.53125 21.027 5.744)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iymgfpb" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 0 0 -.54102 21.195 5.765)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><linearGradient id="iv5QCeb" x1=".116" x2="2.084" y1="2.096" y2="1.619" gradientUnits="userSpaceOnUse"><stop class="rvkj67bhb"/><stop offset="1" class="yvc-8db_y"/></linearGradient><linearGradient id="ixWZb9b" x1="17.606" x2="17.606" y1="8.384" y2="17.504" gradientUnits="userSpaceOnUse"><stop class="s-mmaacyl"/><stop offset="1" class="b108nwbbf"/></linearGradient><linearGradient id="i3dyp5d" x1="15.485" x2="16.891" y1="10.978" y2="8.541" gradientUnits="userSpaceOnUse"><stop class="cx6lx2x4e"/><stop offset="1" class="sbq6vwbkt"/></linearGradient><linearGradient id="ivAumjJ" x1="19.547" x2="22.922" y1="20.041" y2="28.166" gradientUnits="userSpaceOnUse"><stop class="rshq-s3st"/><stop offset="1" class="rvpou-b_v"/></linearGradient><linearGradient id="ika88Bc" x1="24.155" x2="22.88" y1="24.705" y2="25.188" gradientUnits="userSpaceOnUse"><stop class="q2m7j_fif"/><stop offset="1" class="mt6f54ber"/></linearGradient><linearGradient id="isjK0Qc" x1="26.102" x2="25.946" y1="29.002" y2="28.689" gradientUnits="userSpaceOnUse"><stop class="vrnt79u8g"/><stop offset="1" class="z-p3-w_an"/></linearGradient><linearGradient id="izzdQhe" x1="23.86" x2="24.516" y1="29.4" y2="28.962" gradientUnits="userSpaceOnUse"><stop class="sted03b1z"/><stop offset="1" class="ubkqlww9x"/></linearGradient><linearGradient id="iklbMIE" x1="13.828" x2="12.36" y1="22.728" y2="22.072" gradientUnits="userSpaceOnUse"><stop class="rz90b38rn"/><stop offset="1" class="lngpjjb0b"/></linearGradient><linearGradient id="iIDoFIe" x1="12.563" x2="7.625" y1="21.259" y2="21.072" gradientUnits="userSpaceOnUse"><stop class="f7j3ni3bi"/><stop offset="1" class="i_d2dkbya"/></linearGradient><linearGradient id="iXi37Ge" x1="5.86" x2="5.36" y1="19.595" y2="20.759" gradientUnits="userSpaceOnUse"><stop offset=".024" class="ruyfycb4r"/><stop offset="1" class="vuvc8_ujh"/></linearGradient><linearGradient id="iQQmKNd" x1="5.86" x2="5.096" y1="22.556" y2="21.751" gradientUnits="userSpaceOnUse"><stop class="clpaphbux"/><stop offset="1" class="gei07kbgq"/></linearGradient><linearGradient id="iuFD7Md" x1="4.078" x2="4.485" y1="21.837" y2="21.978" gradientUnits="userSpaceOnUse"><stop offset=".213" class="e2g34f-cy"/><stop offset="1" class="vx88q5bse"/></linearGradient><linearGradient id="iNEJ4se" x1="18.828" x2="18.141" y1="17.228" y2="18.16" gradientUnits="userSpaceOnUse"><stop class="hv04c4bjr"/><stop offset="1" class="j2u_3dtev"/></linearGradient><linearGradient id="ideIhmW" x1="18.976" x2="21.838" y1="6.412" y2="6.584" gradientUnits="userSpaceOnUse"><stop class="egm-dub4f"/><stop offset="1" class="zhwoohbuw"/></linearGradient><linearGradient id="ipECBte" x1="-.007" x2=".179" y1=".05" y2=".11" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><filter id="iFr5A9c" width="10.118" height="5.774" x="7.605" y="7.06" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.929412 0 0 0 0 0.552941 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_9926"/></filter><filter id="iN6vAhc" width="4.813" height="3.178" x="23.453" y="27.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.286275 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_9926"/></filter><filter id="iBud8Ib" width="8.943" height="4.095" x="5.772" y="19.447" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.513726 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_9926"/></filter><filter id="iJf8asc" width="6.408" height="2.475" x="6.884" y="19.716" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_9926" stdDeviation=".2"/></filter><filter id="iONLvib" width="3.978" height="6.092" x="11.71" y="15.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.458824 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_9926"/></filter><filter id="iQEhjic" width="4.443" height="5.249" x="17.396" y="3.471" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.576471 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_9926"/></filter><filter id="i1aNFCd" width="6.391" height="5.479" x="15.981" y="1.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.835294 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_9926"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.592157 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_9926" result="effect2_innerShadow_2_9926"/></filter><filter id="iwkf42c" width="1.117" height=".648" x="20.218" y="4.397" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.2 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_9926"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-running-facing-right" /></template>
<style>
.admd7db0k {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
  stop-opacity: 0;
}

.ado7u1b7k {
  stop-color: var(--svg-color--ec8b4b, #EC8B4B);
  stop-opacity: 0;
}

.asuvzebmi {
  stop-color: var(--svg-color--529cea, #529CEA);
  stop-opacity: 0;
}

.b108nwbbf {
  stop-color: var(--svg-color--337fe1, #337FE1);
}

.b30rr0b3q {
  stop-color: var(--svg-color--ef9926, #EF9926);
  stop-opacity: 0;
}

.bervkqbmz {
  stop-color: var(--svg-color--ffd040, #FFD040);
}

.bi5pn_1vn {
  stop-color: var(--svg-color--f3953d, #F3953D);
  stop-opacity: 0;
}

.bjjn4ob6s {
  stop-color: var(--svg-color--e9b636, #E9B636);
}

.bmfdee-fc {
  stop-color: var(--svg-color--fc9d34, #FC9D34);
}

.c479w-bpn {
  stop-color: var(--svg-color--fead30, #FEAD30);
}

.c6vpnsb1w {
  stop-color: var(--svg-color--9c959a, #9C959A);
}

.clpaphbux {
  stop-color: var(--svg-color--5a418f, #5A418F);
}

.co-v7wd3f {
  fill: var(--svg-color--fff, #fff);
  d: path("M21.304 5.765h-.988c0-.391.221-.709.494-.709s.494.318.494.71");
}

.cwn5j3-fq {
  fill: var(--svg-color--473f82, #473F82);
  d: path("m5.263 19.612l1.234.472l.16 1.75a45 45 0 0 1-1.715 1.633c-.428.387-.844.467-1.146.433c-.23-.026-.312-.276-.23-.492l1.374-3.65a.25.25 0 0 1 .323-.146");
}

.cx6lx2x4e {
  stop-color: var(--svg-color--2c6bd5, #2C6BD5);
}

.d7kch3t0q {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
}

.dn7klsb_e {
  fill: var(--svg-color--918996, #918996);
  d: path("M14.649 14.267s4.125 3.031 6.023 4.703a17.7 17.7 0 0 1-2.544 2.854a.92.92 0 0 1-1.23-.013c-.92-.81-1.78-1.6-2.616-2.552c-1.375-1.562-1.047-2.663-.766-3.312c.244-.563.857-1.354 1.133-1.68");
}

.e2g34f-cy {
  stop-color: var(--svg-color--5e5d8f, #5E5D8F);
}

.egm-dub4f {
  stop-color: var(--svg-color--ffc33e, #FFC33E);
}

.f7j3ni3bi {
  stop-color: var(--svg-color--ffcc43, #FFCC43);
}

.ft5dv1b6b {
  fill: none;
}

.fvok_qxen {
  stop-color: var(--svg-color--ffbf42, #FFBF42);
}

.g03wnfdbp {
  d: path("m26.961 27.095l-2.46.07l-1.048 1.391l.624 1.184a.25.25 0 0 0 .335.106l3.41-1.75c.197-.1.317-.328.197-.513c-.247-.38-.74-.488-1.058-.488");
}

.gei07kbgq {
  stop-color: var(--svg-color--5a418f, #5A418F);
  stop-opacity: 0;
}

.gewgt1jbg {
  stop-color: var(--svg-color--afa8b2, #AFA8B2);
}

.gfogqobsd {
  d: path("m14.774 21.595l.914-2.148l-1.793-3.844c-1.258 1.754-1.739 2.664-1.98 3.055c-.269.432-.298.922.062 1.281c.637.569 2.13 1.341 2.797 1.656");
}

.gjadyfboc {
  stop-color: var(--svg-color--529cea, #529CEA);
}

.goyescc5e {
  d: path("M22.035 5.935a1 1 0 0 1-.258-.457h-.18v1.125c.215.137.522.115.613-.09c.079-.175.02-.394-.175-.578");
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gz3om4b5e {
  stop-color: var(--svg-color--4db0fb, #4DB0FB);
}

.hpbocun_g {
  stop-color: var(--svg-color--d77364, #D77364);
}

.hv04c4bjr {
  stop-color: var(--svg-color--908582, #908582);
}

.i_d2dkbya {
  stop-color: var(--svg-color--ffcc43, #FFCC43);
  stop-opacity: 0;
}

.iou487baj {
  stop-color: var(--svg-color--b7733e, #B7733E);
}

.j23k_cb2p {
  stop-color: var(--svg-color--9c959a, #9C959A);
  stop-opacity: 0;
}

.j2u_3dtev {
  stop-color: var(--svg-color--908582, #908582);
  stop-opacity: 0;
}

.j96xv6b5h {
  stop-color: var(--svg-color--917ea3, #917EA3);
  stop-opacity: 0;
}

.j9k09pb-s {
  stop-color: var(--svg-color--fea724, #FEA724);
  stop-opacity: 0;
}

.jfv70ccah {
  stop-color: var(--svg-color--b28146, #B28146);
}

.jgi7b6w2r {
  d: path("M21.81 4.972c-.038-.801-.297-1.188-.42-1.3h-3.732l-.062 3.163c.866 2.122 3.511 2.213 3.906 1.445c.395-.767.353-2.38.309-3.308");
}

.jul0_iufc {
  d: path("m14.063 22.658l.652-1.278l-2.613-1.683l-.344 1.015l-5.836-.687l.625 1.773c1.422.446 4.465 1.408 5.504 1.68c1.074.281 1.848-.434 2.012-.82");
}

.jve2rcqoj {
  stop-color: var(--svg-color--ffbc2b, #FFBC2B);
}

.k870jjb1v {
  stop-color: var(--svg-color--5aa7ea, #5AA7EA);
  stop-opacity: 0;
}

.kg-rnkb9f {
  stop-color: var(--svg-color--827483, #827483);
  stop-opacity: 0;
}

.kpbiulbbs {
  stop-color: var(--svg-color--ffa629, #FFA629);
}

.kve1gec_d {
  stop-color: var(--svg-color--63a0db, #63A0DB);
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.lngpjjb0b {
  stop-color: var(--svg-color--ffb657, #FFB657);
  stop-opacity: 0;
}

.m1l7k9jve {
  cx: 0.064px;
  cy: 0.088px;
  rx: 0.064px;
  ry: 0.088px;
}

.m72ygetof {
  stop-color: var(--svg-color--d38d2e, #D38D2E);
}

.m8pmc0btt {
  stop-color: var(--svg-color--d38d2e, #D38D2E);
  stop-opacity: 0;
}

.mcvrg0kam {
  stop-color: var(--svg-color--ffd05b, #FFD05B);
}

.mftxrcb_l {
  cx: 0.63px;
  cy: 0.63px;
  r: 0.63px;
}

.mg7jlrprx {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m12.703 20.181l-.392 1.14a.4.4 0 0 1-.435.266l-4.563-.656");
}

.mt6f54ber {
  stop-color: var(--svg-color--ffd558, #FFD558);
  stop-opacity: 0;
}

.n1b4mhj1w {
  stop-color: var(--svg-color--64628c, #64628C);
  stop-opacity: 0;
}

.n56o4pn0v {
  fill: var(--svg-color--87014d, #87014D);
  fill-rule: evenodd;
  d: path("M20.559 6.879a.125.125 0 0 0 .001.177c.239.233.583.293.692.304a.125.125 0 0 0 .026-.248c-.094-.01-.367-.062-.543-.235a.125.125 0 0 0-.176.002");
}

.n8gqlhnrc {
  stop-color: var(--svg-color--9583a6, #9583A6);
  stop-opacity: 0;
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.nkql81bxe {
  stop-color: var(--svg-color--f3953d, #F3953D);
}

.ntxow7bsx {
  fill: var(--svg-color--379ffb, #379FFB);
  d: path("m14.151 10.038l1.324-2.718l2.764 1.323a1.483 1.483 0 0 1-1.255 2.686z");
}

.nwysaqbbn {
  fill: var(--svg-color--ffc538, #FFC538);
  fill-rule: evenodd;
  d: path("M12.296 10.182a1.85 1.85 0 0 1 1.873-.286l2.687 1.093l.866-2.13l-2.687-1.093a4.15 4.15 0 0 0-4.2.64l-2.997 2.508a.65.65 0 0 0-.085.911l.636.772a.65.65 0 0 0 .918.086z");
}

.osaguabiz {
  stop-color: var(--svg-color--917ea3, #917EA3);
}

.p082bkbzi {
  stroke: var(--svg-color--bc5f4e, #BC5F4E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M21.035 4.597c-.129 0-.41 0-.617.149");
}

.p3w7zobfd {
  fill: var(--svg-color--534e8c, #534E8C);
  d: path("m26.961 27.095l-2.46.07l-1.048 1.391l.624 1.184a.25.25 0 0 0 .335.106l3.41-1.75c.197-.1.317-.328.197-.513c-.247-.38-.74-.488-1.058-.488");
}

.p5n-ewbqx {
  stop-color: var(--svg-color--2b71e5, #2B71E5);
}

.p6l1enb-u {
  d: path("m19.04 6.426l-.2-1.44a.727.727 0 0 0 .2 1.44");
}

.ppehd5bdz {
  d: path("M21.172 4.219c.656 0 .968-.371 1-.836c0-.657-.502-.796-.696-.817c-.218-.023-.304-.047-.61-.261a.9.9 0 0 0-.91-.098c-.148.07-.476.105-.71.035c-.39-.117-.695-.113-.996.117c-.21.16-.363.16-.613.16c-.344 0-.636.154-.856.32c-.657.498-.582 2.208-.258 3.169c.31.919.777 1.027 1.168.992c.47-.042.59-.399.66-.695c.057-.238.2-.792.266-1.04c.135-.062.431-.284.531-.671s.493-.432.758-.407c.162.016.61.032 1.266.032");
}

.q-30hhb4p {
  stop-color: var(--svg-color--ffd05b, #FFD05B);
  stop-opacity: 0;
}

.q11m-vutr {
  stop-color: var(--svg-color--2b71e5, #2B71E5);
  stop-opacity: 0;
}

.q2m7j_fif {
  stop-color: var(--svg-color--ffd558, #FFD558);
}

.qrrjvfgyy {
  d: path("m20.894 5.765l-.004-.072c0-.185.079-.336.176-.336s.176.15.176.336l-.004.072z");
}

.r0_3lybww {
  stop-color: var(--svg-color--347cdb, #347CDB);
  stop-opacity: 0;
}

.ra4b_vxmi {
  fill: var(--svg-color--ffc439, #FFC439);
  d: path("m14.063 22.658l.652-1.278l-2.613-1.683l-.344 1.015l-5.836-.687l.625 1.773c1.422.446 4.465 1.408 5.504 1.68c1.074.281 1.848-.434 2.012-.82");
}

.rmzq06bzd {
  stop-color: var(--svg-color--64628c, #64628C);
}

.roa1y3bvy {
  stop-color: var(--svg-color--9b92a1, #9B92A1);
  stop-opacity: 0;
}

.rshq-s3st {
  stop-color: var(--svg-color--ffc235, #FFC235);
}

.ruyfycb4r {
  stop-color: var(--svg-color--444367, #444367);
}

.rvkj67bhb {
  stop-color: var(--svg-color--dfa741, #DFA741);
}

.rvpou-b_v {
  stop-color: var(--svg-color--ffc443, #FFC443);
}

.rz90b38rn {
  stop-color: var(--svg-color--ffb657, #FFB657);
}

.s-mmaacyl {
  stop-color: var(--svg-color--4091ec, #4091EC);
}

.s6seicc8w {
  stop-color: var(--svg-color--346ece, #346ECE);
}

.s972eabyx {
  fill: var(--svg-color--ffb93c, #FFB93C);
  d: path("M28.239 11.837c.285-.363.293-.87.07-1.293c-.223-.421-.547-.832-1.016-.812c-.328.014-.598.276-.711.619a1 1 0 0 0-.206.076l-3 1.448a1.6 1.6 0 0 1-1.639-.149l-2.223-1.622a1.15 1.15 0 1 0-1.356 1.858l2.224 1.622a3.9 3.9 0 0 0 3.993.362l2.918-1.421c.246-.121.72-.4.946-.688");
}

.s9nkndynh {
  stop-color: var(--svg-color--4db0fb, #4DB0FB);
  stop-opacity: 0;
}

.s9u_pkb1z {
  d: path("M22.985 21.947c.515 1.76 1.457 4.933 1.547 5.219l-1.075 1.39c-.86-1.614-2.641-4.986-2.93-5.66c-.242-.566-.566-.71-.808-.855l-1.34-.805l1.973-2.473c.12.094.594.445 1.32 1.074c.735.637 1.169 1.618 1.313 2.11");
}

.sa2u8w_4a {
  fill: var(--svg-color--97919e, #97919E);
  d: path("m14.774 21.595l.914-2.148l-1.793-3.844c-1.258 1.754-1.739 2.664-1.98 3.055c-.269.432-.298.922.062 1.281c.637.569 2.13 1.341 2.797 1.656");
}

.sbq6vwbkt {
  stop-color: var(--svg-color--2f89f4, #2F89F4);
  stop-opacity: 0;
}

.sef70m78x {
  d: path("M20.699 5.765v-.004c0-.32.137-.58.306-.58c.17 0 .307.26.307.58v.004z");
}

.snqm-cbpd {
  stop-color: var(--svg-color--e9b636, #E9B636);
  stop-opacity: 0;
}

.sq7_rccwx {
  stop-color: var(--svg-color--885fa7, #885FA7);
}

.sted03b1z {
  stop-color: var(--svg-color--4c438d, #4C438D);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.suyap8bzv {
  stop-color: var(--svg-color--eba544, #EBA544);
}

.teubnce1a {
  d: path("m18.864 8.92l-.74-.39a1 1 0 0 0-.584-.107l-2.003 1.774c.229 1.789-.13 3.008-.9 4.077l4.253 3.23c1.517-2.635 1.93-5.073 1.556-6.354c-.318-1.229-1.05-1.899-1.582-2.23");
}

.u43aj25jg {
  d: path("m5.263 19.612l1.234.472l.16 1.75a45 45 0 0 1-1.715 1.633c-.428.387-.844.467-1.146.433c-.23-.026-.312-.276-.23-.492l1.374-3.65a.25.25 0 0 1 .323-.146");
}

.u6kcyml4j {
  stop-color: var(--svg-color--598fc9, #598FC9);
  stop-opacity: 0;
}

.u9s7qvbon {
  width: 1.484px;
  height: 1.324px;
  fill: var(--svg-color--ffc039, #FFC039);
  rx: 0.662px;
}

.ubkqlww9x {
  stop-color: var(--svg-color--4c438d, #4C438D);
  stop-opacity: 0;
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.uc8p_0bsw {
  d: path("M28.239 11.837c.285-.363.293-.87.07-1.293c-.223-.421-.547-.832-1.016-.812c-.328.014-.598.276-.711.619a1 1 0 0 0-.206.076l-3 1.448a1.6 1.6 0 0 1-1.639-.149l-2.223-1.622a1.15 1.15 0 1 0-1.356 1.858l2.224 1.622a3.9 3.9 0 0 0 3.993.362l2.918-1.421c.246-.121.72-.4.946-.688");
}

.umrurxb6b {
  stop-color: var(--svg-color--d77364, #D77364);
  stop-opacity: 0;
}

.v1sha93vg {
  stop-color: var(--svg-color--746484, #746484);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vrnt79u8g {
  stop-color: var(--svg-color--443088, #443088);
}

.vuvc8_ujh {
  stop-color: var(--svg-color--444367, #444367);
  stop-opacity: 0;
}

.vx88q5bse {
  stop-color: var(--svg-color--484083, #484083);
  stop-opacity: 0;
}

.w9e_hp45s {
  d: path("m14.151 10.038l1.324-2.718l2.764 1.323a1.483 1.483 0 0 1-1.255 2.686z");
}

.wpy2jtqib {
  stop-color: var(--svg-color--598fc9, #598FC9);
}

.wtj81mbzy {
  stop-color: var(--svg-color--5aa7ea, #5AA7EA);
}

.x0ts0cb2w {
  d: path("M14.649 14.267s4.125 3.031 6.023 4.703a17.7 17.7 0 0 1-2.544 2.854a.92.92 0 0 1-1.23-.013c-.92-.81-1.78-1.6-2.616-2.552c-1.375-1.562-1.047-2.663-.766-3.312c.244-.563.857-1.354 1.133-1.68");
}

.y_4ptxbzf {
  stop-color: var(--svg-color--ec8b4b, #EC8B4B);
}

.y5luhbaev {
  stop-color: var(--svg-color--e17e4b, #E17E4B);
}

.yeyqi9phi {
  stop-color: var(--svg-color--fea724, #FEA724);
}

.yjn3q9srk {
  stop-color: var(--svg-color--346ece, #346ECE);
  stop-opacity: 0;
}

.yvc-8db_y {
  stop-color: var(--svg-color--efc441, #EFC441);
}

.z-p3-w_an {
  stop-color: var(--svg-color--534f8c, #534F8C);
  stop-opacity: 0;
}

.z26-wfbav {
  stop-color: var(--svg-color--b7733e, #B7733E);
  stop-opacity: 0;
}

.z8jy9-b3h {
  d: path("M0 0h1.946v3.44H0z");
}

.zhwoohbuw {
  stop-color: var(--svg-color--ffc247, #FFC247);
}

</style>
