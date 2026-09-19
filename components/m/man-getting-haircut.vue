<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iI9Hdne)" class="syu65hrvi"/><path fill="url(#i33NKjU)" class="syu65hrvi"/><path fill="url(#iKLv0qc)" class="syu65hrvi"/><path fill="url(#iduiXoc)" class="syu65hrvi"/><path fill="url(#ipi1zON)" class="syu65hrvi"/><path fill="url(#iDcto9c)" class="gxqjmikmg"/><path fill="url(#iTLOAwN)" class="gxqjmikmg"/><path class="tkln9gb_r"/><path fill="url(#iEEkPAd)" class="a_kudi-dv"/><path fill="url(#iZfQtPd)" class="a_kudi-dv"/><path class="u1w4jn-zg"/><path fill="url(#id8zfFb)" class="jgp08zdxo"/><path fill="url(#ioNWO1c)" class="jgp08zdxo"/><circle fill="url(#iOT8jZc)" class="ehw1oivax"/><g filter="url(#iq1y5Li)"><circle fill="url(#imtNIZb)" class="i-_w3pl3s"/></g><g filter="url(#iKditSb)"><circle fill="url(#ikWp5ib)" class="poyan9ogy"/><circle fill="url(#im5BNbA)" class="poyan9ogy"/></g><g filter="url(#i9kFHod)"><circle class="h6mapivpu"/><circle fill="url(#iRE0JAx)" class="g5u3zkh1m"/><circle fill="url(#iuzcbjc)" class="g5u3zkh1m"/></g><path fill="url(#iquE8Tb)" class="pgx41lb8h"/><path fill="url(#iN9IbLb)" class="pgx41lb8h"/><path fill="url(#iXP5arb)" class="pgx41lb8h"/><path fill="url(#iOY83Qc)" class="pgx41lb8h"/><path fill="url(#icpxceb)" class="pgx41lb8h"/><g filter="url(#i9DvPld)"><path class="rhwb21akg"/><path fill="url(#i00J2rd)" class="hjpcf-cgn"/><path fill="url(#iHG0nYs)" class="hjpcf-cgn"/><path fill="url(#i02NtIe)" class="hjpcf-cgn"/><path fill="url(#idlU4Em)" class="hjpcf-cgn"/><path fill="url(#izc9sIe)" class="hjpcf-cgn"/><path fill="url(#iNmfhAc)" class="hjpcf-cgn"/></g><path fill="url(#iNJekce)" class="hjpcf-cgn"/><path fill="url(#iaZWAGc)" class="hjpcf-cgn"/><path fill="url(#ioKvOub)" class="hjpcf-cgn"/><path fill="url(#iyn0Z0b)" class="hjpcf-cgn"/><g filter="url(#i6EmGdd)"><path class="wifd57bhn"/></g><g filter="url(#igqWGie)"><path class="ndcqgbbqr"/><path fill="url(#i3tafRb)" class="kv8z47b6z"/><path fill="url(#iRr9iAb)" class="kv8z47b6z"/><path fill="url(#iqTfYCe)" class="kv8z47b6z"/></g><g filter="url(#i4gWD3b)"><path stroke="url(#iw3zYde)" class="lm7x8mbti"/></g><path class="jgpkicc4o"/><path class="k5rz6m_ej"/><path fill="url(#icapqMe)" class="aa6p47bnq"/><path class="de734mb6s"/><g filter="url(#imyYpIe)"><path class="n0mdw4xep"/><path fill="url(#ie2Vnwc)" class="qnvktkxoh"/></g><g filter="url(#iRK1Zbb)"><path fill="url(#iBGb7Xb)" class="ne28hevog"/></g><path class="u3uvzrbhu"/><path fill="url(#iG5VMkb)" class="t3at67xsm"/><path class="h8ctczbhu"/><g filter="url(#iqO25Qb)"><path fill="url(#if1cogc)" class="ul1-t-qnt"/></g><g filter="url(#ixPcyep)"><ellipse transform="rotate(-27.914 12.156 12.888)" class="b7uj0ybsd"/><ellipse fill="url(#imfS2qb)" transform="rotate(-27.914 12.156 12.888)" class="tq9wobc8t"/></g><g filter="url(#iZfU4lH)"><path fill="url(#iUPYYdc)" clip-rule="evenodd" class="uoxk3uguq"/></g><g filter="url(#iIcESbd)"><path class="ggmvcerjb"/></g><g filter="url(#iK7OdJd)"><path fill="url(#iDKx4lc)" clip-rule="evenodd" class="q7gzk7bcw"/></g><g filter="url(#iizfpkc)"><path class="w3vw2zbpg"/></g><path fill="url(#iQGt0Be)" class="ogdh_qdtu"/><path fill="url(#igrfRNc)" class="ogdh_qdtu"/><path fill="url(#i6aWuwc)" class="ogdh_qdtu"/><path fill="url(#i1u7Ree)" class="ogdh_qdtu"/><path fill="url(#itn3g2b)" class="ogdh_qdtu"/><path fill="url(#i8tw17J)" class="s80emud-s"/><path fill="url(#iNF0E9d)" class="s80emud-s"/><path fill="url(#iYOf03l)" class="t6-u-13dn"/><path fill="url(#iWZrKfc)" class="t6-u-13dn"/><g filter="url(#imqQpjd)"><circle fill="url(#iU3M6Sb)" class="omp34eowh"/><circle fill="url(#iBevg4b)" class="omp34eowh"/><circle fill="url(#iW728bI)" class="omp34eowh"/></g><g filter="url(#iSFSdXd)"><path fill="url(#i7b2hDb)" clip-rule="evenodd" class="rizphhb9m"/></g><path fill="url(#i9PEg7c)" clip-rule="evenodd" class="rizphhb9m"/><g filter="url(#ierpQHc)"><path fill="url(#iTSvCGd)" clip-rule="evenodd" class="tp7243aiy"/></g><g filter="url(#i3Kk0Id)"><circle stroke="url(#i8C9hUb)" class="h5siw4ltz"/></g><g filter="url(#iNXkKxd)"><circle stroke="url(#iNEopHb)" class="f-2829b6h"/></g><g filter="url(#iy7I3hb)"><circle stroke="url(#i0uN1Zd)" class="r8eqjtbel"/></g><g filter="url(#iadG5Xc)"><circle stroke="url(#ixQYagx)" class="f3i1fktfn"/></g><defs><radialGradient id="iI9Hdne" cx="0" cy="0" r="1" gradientTransform="rotate(154.071 8.254 14.159)scale(15.0662 17.3462)" gradientUnits="userSpaceOnUse"><stop class="tet72waca"/><stop offset="1" class="bmx48tuma"/></radialGradient><radialGradient id="i33NKjU" cx="0" cy="0" r="1" gradientTransform="rotate(-115.528 17.4 10.835)scale(12.9022 18.5657)" gradientUnits="userSpaceOnUse"><stop offset=".879" class="rxprtfb0z"/><stop offset="1" class="m-fo0lvbc"/></radialGradient><radialGradient id="iKLv0qc" cx="0" cy="0" r="1" gradientTransform="rotate(166.984 5.917 10.473)scale(6.38273 2.1839)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="zdar40bkv"/><stop offset="1" class="cybfe7yaw"/></radialGradient><radialGradient id="iduiXoc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6713 0 0 -14.1675 21.546 29.871)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="puczgzv3j"/><stop offset="1" class="mq0bii3nt"/></radialGradient><radialGradient id="ipi1zON" cx="0" cy="0" r="1" gradientTransform="matrix(1.24045 0 0 9.50024 7.166 29.871)" gradientUnits="userSpaceOnUse"><stop class="wke-8-xfb"/><stop offset="1" class="h-56b9bpz"/></radialGradient><radialGradient id="iDcto9c" cx="0" cy="0" r="1" gradientTransform="matrix(3.25185 0 0 9.13279 21.576 29.092)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="kin3dabop"/><stop offset="1" class="jlkbatyzp"/></radialGradient><radialGradient id="iTLOAwN" cx="0" cy="0" r="1" gradientTransform="matrix(.87006 0 0 11.9715 21.576 29.87)" gradientUnits="userSpaceOnUse"><stop class="hos3q5hgu"/><stop offset="1" class="txm2ysbkn"/></radialGradient><radialGradient id="iEEkPAd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.70862 0 0 -8.85437 7.31 29.871)" gradientUnits="userSpaceOnUse"><stop offset=".614" class="vp_-q7ldm"/><stop offset=".956" class="k-z4zg2os"/></radialGradient><radialGradient id="iZfQtPd" cx="0" cy="0" r="1" gradientTransform="matrix(-.8463 0 0 -10.457 7.31 29.871)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="oxun88gow"/><stop offset="1" class="zi0iv1bfj"/></radialGradient><radialGradient id="id8zfFb" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 1.75 -3.03541 .97567 13.7 19.506)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="r5vidg5lt"/><stop offset="1" class="h2ud6q2-e"/></radialGradient><radialGradient id="ioNWO1c" cx="0" cy="0" r="1" gradientTransform="rotate(139.583 4.382 13.566)scale(2.48229 1.07513)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="ap3tehvur"/><stop offset="1" class="dy253plrj"/><stop offset="1" class="jwr2g_bnr"/></radialGradient><radialGradient id="iOT8jZc" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 8.19 13.666)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="im5BNbA" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 19.756 13.401)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="iRE0JAx" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 19.343 14.488)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="iuzcbjc" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 19.385 13.666)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="iXP5arb" cx="0" cy="0" r="1" gradientTransform="scale(9.40738 8.23895)rotate(90 .07 1.536)" gradientUnits="userSpaceOnUse"><stop offset=".712" class="jiyvp-brd"/><stop offset="1" class="hfzmunkww"/></radialGradient><radialGradient id="iOY83Qc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 16.962 12.393)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="icpxceb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39218 1.7313 0 12.4 12.36)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="i00J2rd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.43986 4.43352 -7.5396 -5.84979 18.31 5.946)" gradientUnits="userSpaceOnUse"><stop class="ck410xb1o"/><stop offset="1" class="qeh0r4bjq"/></radialGradient><radialGradient id="i02NtIe" cx="0" cy="0" r="1" gradientTransform="rotate(-95.29 9.807 .238)scale(2.00292 .98368)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="euj6xpbnj"/><stop offset="1" class="hchnd0bsx"/></radialGradient><radialGradient id="idlU4Em" cx="0" cy="0" r="1" gradientTransform="matrix(.85996 -1.96834 1.60534 .70136 18.845 11.927)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ghdrqrbfe"/><stop offset="1" class="d7zypgbet"/></radialGradient><radialGradient id="izc9sIe" cx="0" cy="0" r="1" gradientTransform="matrix(.99373 1.23303 -1.08867 .87739 13.838 5.057)" gradientUnits="userSpaceOnUse"><stop class="wn92vfpti"/><stop offset="1" class="t4clght5m"/></radialGradient><radialGradient id="iNmfhAc" cx="0" cy="0" r="1" gradientTransform="matrix(1.45237 -3.03851 1.04984 .50181 18.807 9.443)" gradientUnits="userSpaceOnUse"><stop class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="iNJekce" cx="0" cy="0" r="1" gradientTransform="matrix(.26142 1.01586 -1.67013 .42978 15.31 5.057)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="s_ha1fylz"/><stop offset="1" class="e0ciekbtt"/></radialGradient><radialGradient id="iaZWAGc" cx="0" cy="0" r="1" gradientTransform="matrix(1.108 1.60044 -3.3305 2.30572 10.228 6.319)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="pb3_oi83v"/><stop offset="1" class="gt3e5dbiv"/></radialGradient><radialGradient id="ioKvOub" cx="0" cy="0" r="1" gradientTransform="matrix(-7.21429 3.2501 -4.0668 -9.02713 15.768 9.298)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="gmm-ghbsu"/><stop offset=".959" class="g3s2gbbst"/></radialGradient><radialGradient id="iyn0Z0b" cx="0" cy="0" r="1" gradientTransform="rotate(109.643 7.603 11.426)scale(2.74487 1.764)" gradientUnits="userSpaceOnUse"><stop offset=".346" class="nr3rksbet"/><stop offset="1" class="y9qcw5bms"/></radialGradient><radialGradient id="iw3zYde" cx="0" cy="0" r="1" gradientTransform="matrix(.02462 -.62786 1.8836 .07386 14.53 17.682)" gradientUnits="userSpaceOnUse"><stop class="zjmwko4fr"/><stop offset="1" class="md9bsbc9k"/></radialGradient><radialGradient id="icapqMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90401 -1.06968 0 16.795 13.317)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ie2Vnwc" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 16.566 13.067)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iG5VMkb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90406 -1.06973 0 12.428 13.317)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="imfS2qb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.57 .625)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iUPYYdc" cx="0" cy="0" r="1" gradientTransform="matrix(.19698 -.81253 1.78256 .43214 17.067 11.465)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><radialGradient id="iDKx4lc" cx="0" cy="0" r="1" gradientTransform="matrix(-.19698 -.81253 1.78256 -.43214 12.162 11.466)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><radialGradient id="iQGt0Be" cx="0" cy="0" r="1" gradientTransform="rotate(152.815 10.952 5.477)scale(5.16422 4.07334)" gradientUnits="userSpaceOnUse"><stop class="j52kqi5ci"/><stop offset=".901" class="p8j84vbpc"/></radialGradient><radialGradient id="igrfRNc" cx="0" cy="0" r="1" gradientTransform="matrix(.03906 .32813 -.31029 .03694 23.134 5.156)" gradientUnits="userSpaceOnUse"><stop class="zjwaehbsp"/><stop offset="1" class="p3ke5p64t"/></radialGradient><radialGradient id="i6aWuwc" cx="0" cy="0" r="1" gradientTransform="matrix(4.17626 .56873 -.43132 3.16722 19.343 5.883)" gradientUnits="userSpaceOnUse"><stop offset=".949" class="urqhv2b1h"/><stop offset="1" class="jtcqeoejk"/></radialGradient><radialGradient id="i1u7Ree" cx="0" cy="0" r="1" gradientTransform="rotate(165.562 10.232 5.23)scale(2.61605 1.13614)" gradientUnits="userSpaceOnUse"><stop class="lg_7a3bcy"/><stop offset="1" class="xrrmohu-n"/></radialGradient><radialGradient id="itn3g2b" cx="0" cy="0" r="1" gradientTransform="matrix(1.23439 1.92187 -3.1166 2.00174 20.696 5.984)" gradientUnits="userSpaceOnUse"><stop offset=".893" class="t_i0qw3fw"/><stop offset="1" class="h9turkxgz"/></radialGradient><radialGradient id="iU3M6Sb" cx="0" cy="0" r="1" gradientTransform="rotate(141.18 10.65 7.923)scale(.43619)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="cz-qsgbfy"/><stop offset="1" class="j80tr6o9y"/></radialGradient><radialGradient id="iBevg4b" cx="0" cy="0" r="1" gradientTransform="matrix(.19922 -.48438 1.17186 .48198 23.594 7.862)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="m8bo-jb-t"/><stop offset="1" class="wy7e69bbh"/></radialGradient><radialGradient id="iW728bI" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 .04684 -.05916 .55254 23.369 7.424)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="zk512ndyg"/><stop offset="1" class="hy0z0nf6k"/></radialGradient><radialGradient id="i7b2hDb" cx="0" cy="0" r="1" gradientTransform="matrix(2.20247 -1.61719 2.56784 3.49718 21.396 10.611)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="cnux6p8xn"/><stop offset="1" class="jaxt-o31p"/></radialGradient><radialGradient id="iTSvCGd" cx="0" cy="0" r="1" gradientTransform="matrix(2.53124 -1.40627 1.98705 3.57664 24.543 8.788)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="cnux6p8xn"/><stop offset="1" class="jaxt-o31p"/></radialGradient><filter id="iq1y5Li" width="2.992" height="2.992" x="8.366" y="12.17" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_23" stdDeviation=".25"/></filter><filter id="iKditSb" width="3.592" height="3.592" x="17.713" y="11.745" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_23"/></filter><filter id="i9kFHod" width="2.992" height="2.992" x="17.888" y="12.17" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_23" stdDeviation=".25"/></filter><filter id="i9DvPld" width="12.614" height="8.301" x="8.307" y="4.807" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.584314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_23"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.572549 0 0 0 0 0.0156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_23" result="effect2_innerShadow_4002_23"/></filter><filter id="i6EmGdd" width="3.262" height="4.184" x="12.744" y="12.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_23" stdDeviation=".375"/></filter><filter id="igqWGie" width="2.079" height="2.884" x="13.575" y="12.998" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_23" stdDeviation=".05"/></filter><filter id="i4gWD3b" width="3.621" height="1.474" x="12.804" y="16.253" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_23" stdDeviation=".05"/></filter><filter id="imyYpIe" width=".787" height=".697" x="16.06" y="12.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_23" stdDeviation=".05"/></filter><filter id="iRK1Zbb" width=".892" height=".914" x="16.901" y="12.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_23" stdDeviation=".1"/></filter><filter id="iqO25Qb" width=".987" height="1.041" x="12.455" y="12.555" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_23" stdDeviation=".1"/></filter><filter id="ixPcyep" width=".914" height=".705" x="11.7" y="12.535" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_23" stdDeviation=".05"/></filter><filter id="iZfU4lH" width="2.604" height="1.648" x="15.879" y="10.253" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_23"/></filter><filter id="iIcESbd" width="2.709" height="1.502" x="15.826" y="10.339" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_23" stdDeviation=".2"/></filter><filter id="iK7OdJd" width="2.604" height="1.648" x="10.745" y="10.253" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_23"/></filter><filter id="iizfpkc" width="2.709" height="1.502" x="10.693" y="10.339" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_23" stdDeviation=".2"/></filter><filter id="imqQpjd" width=".726" height=".726" x="23.426" y="7.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.52549 0 0 0 0 0.388235 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_23"/></filter><filter id="iSFSdXd" width="3.834" height="4.387" x="20.968" y="7.903" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.45098 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_23"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.282353 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_23" result="effect2_innerShadow_4002_23"/></filter><filter id="ierpQHc" width="4.283" height="3.734" x="24.166" y="6.426" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.203922 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_23"/></filter><filter id="i3Kk0Id" width="3.843" height="3.843" x="24.637" y="6.397" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_23" stdDeviation=".1"/></filter><filter id="iNXkKxd" width="2.734" height="2.734" x="25.191" y="6.951" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_23" stdDeviation=".1"/></filter><filter id="iy7I3hb" width="2.734" height="2.734" x="21.543" y="8.965" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_23" stdDeviation=".1"/></filter><filter id="iadG5Xc" width="3.805" height="3.805" x="21.008" y="8.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_23" stdDeviation=".1"/></filter><linearGradient id="imtNIZb" x1="9.862" x2="9.221" y1="13.945" y2="13.945" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="ikWp5ib" x1="20.471" x2="19.652" y1="12.574" y2="15.112" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="iquE8Tb" x1="18.654" x2="11.01" y1="14.056" y2="15.195" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset=".916" class="as9qb1byz"/></linearGradient><linearGradient id="iN9IbLb" x1="9.213" x2="11.528" y1="16.755" y2="16.453" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="iHG0nYs" x1="9.748" x2="12.653" y1="13.399" y2="8.239" gradientUnits="userSpaceOnUse"><stop class="kyzs66gfi"/><stop offset="1" class="zsx4vmb0f"/></linearGradient><linearGradient id="i3tafRb" x1="13.749" x2="14.688" y1="14.716" y2="14.716" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="iRr9iAb" x1="15.553" x2="14.527" y1="15.039" y2="15.024" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="iqTfYCe" x1="14.809" x2="14.809" y1="15.782" y2="15.208" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="iBGb7Xb" x1="17.573" x2="17.259" y1="13.037" y2="13.231" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="if1cogc" x1="13.172" x2="12.858" y1="13.037" y2="13.231" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i8tw17J" x1="24.949" x2="23.758" y1="5.564" y2="5.219" gradientUnits="userSpaceOnUse"><stop class="p9lsnsm5t"/><stop offset="1" class="lapvr59ed"/></linearGradient><linearGradient id="iNF0E9d" x1="23.801" x2="23.875" y1="7.057" y2="6.768" gradientUnits="userSpaceOnUse"><stop offset=".16" class="zl0fwhbas"/><stop offset="1" class="lxc0fmbqt"/></linearGradient><linearGradient id="iYOf03l" x1="22.887" x2="23.152" y1="7.913" y2="6.616" gradientUnits="userSpaceOnUse"><stop class="p9lsnsm5t"/><stop offset="1" class="lapvr59ed"/></linearGradient><linearGradient id="iWZrKfc" x1="24.298" x2="24.1" y1="7.994" y2="7.939" gradientUnits="userSpaceOnUse"><stop class="jd-vaq0no"/><stop offset="1" class="gof7ehbkx"/></linearGradient><linearGradient id="i9PEg7c" x1="23.637" x2="23.578" y1="8.084" y2="8.311" gradientUnits="userSpaceOnUse"><stop offset=".209" class="ni_6htbzm"/><stop offset="1" class="ajm38_jxm"/></linearGradient><linearGradient id="i8C9hUb" x1="24.887" x2="28.077" y1="8.687" y2="7.214" gradientUnits="userSpaceOnUse"><stop offset=".616" class="w5_7ycb6b"/><stop offset=".9" class="srm_r_guo"/></linearGradient><linearGradient id="iNEopHb" x1="25.441" x2="27.573" y1="8.565" y2="7.58" gradientUnits="userSpaceOnUse"><stop offset=".247" class="jzjqx7qlk"/><stop offset=".669" class="gl3wl_9gz"/></linearGradient><linearGradient id="i0uN1Zd" x1="21.793" x2="23.925" y1="10.578" y2="9.594" gradientUnits="userSpaceOnUse"><stop offset=".247" class="rraw6sbsp"/><stop offset=".669" class="r8ibvzbki"/></linearGradient><linearGradient id="ixQYagx" x1="24.563" x2="22.91" y1="9.791" y2="10.332" gradientUnits="userSpaceOnUse"><stop class="znwvjy5yx"/><stop offset="1" class="zi0lb2bns"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-getting-haircut" /></template>
<style>
.a_kudi-dv {
  d: path("M7.31 21.341c-2.273 1.964-3.71 4.85-3.71 8.067v.463h3.71z");
}

.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.aa6p47bnq {
  d: path("M16.797 12.506a.893.893 0 0 1 .86 1.129h-1.725a.897.897 0 0 1 .865-1.129");
}

.ajm38_jxm {
  stop-color: var(--svg-color--ff3178, #FF3178);
  stop-opacity: 0;
}

.ap3tehvur {
  stop-color: var(--svg-color--f5c028, #F5C028);
}

.as9qb1byz {
  stop-color: var(--svg-color--f9a528, #F9A528);
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.b7uj0ybsd {
  cx: 12.156px;
  cy: 12.888px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.bmx48tuma {
  stop-color: var(--svg-color--2477dd, #2477DD);
}

.ck410xb1o {
  stop-color: var(--svg-color--ffe336, #FFE336);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnux6p8xn {
  stop-color: var(--svg-color--ff7046, #FF7046);
}

.cybfe7yaw {
  stop-color: var(--svg-color--27719e, #27719E);
  stop-opacity: 0;
}

.cz-qsgbfy {
  stop-color: var(--svg-color--ebdbe4, #EBDBE4);
}

.d7zypgbet {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
  stop-opacity: 0;
}

.de734mb6s {
  fill: var(--svg-color--000, #000);
  d: path("M16.285 13.4a.51.51 0 0 1 .512-.512a.51.51 0 0 1 .455.747h-.906a.46.46 0 0 1-.06-.236");
}

.dy253plrj {
  stop-color: var(--svg-color--ffc328, #FFC328);
  stop-opacity: 0;
}

.e0ciekbtt {
  stop-color: var(--svg-color--ffc926, #FFC926);
  stop-opacity: 0;
}

.ehw1oivax {
  cx: 9.862px;
  cy: 13.666px;
  r: 1.671px;
}

.euj6xpbnj {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.f-2829b6h {
  cx: 26.558px;
  cy: 8.318px;
  r: 1.117px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.f3i1fktfn {
  cx: 22.91px;
  cy: 10.332px;
  r: 1.652px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.ft5dv1b6b {
  fill: none;
}

.g3s2gbbst {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
}

.g5u3zkh1m {
  cx: 19.384px;
  cy: 13.666px;
  r: 0.996px;
}

.ggmvcerjb {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.01 11.317c-.209-.193-.803-.52-1.658-.44");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghdrqrbfe {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
}

.gl3wl_9gz {
  stop-color: var(--svg-color--ff7e7a, #FF7E7A);
  stop-opacity: 0;
}

.gmm-ghbsu {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
  stop-opacity: 0;
}

.gof7ehbkx {
  stop-color: var(--svg-color--a2889f, #A2889F);
  stop-opacity: 0;
}

.gt3e5dbiv {
  stop-color: var(--svg-color--f29322, #F29322);
  stop-opacity: 0;
}

.gxqjmikmg {
  d: path("M21.577 29.87h3.708v-.462c0-3.218-1.436-6.103-3.709-8.067z");
}

.h-56b9bpz {
  stop-color: var(--svg-color--1f6ce0, #1F6CE0);
  stop-opacity: 0;
}

.h2ud6q2-e {
  stop-color: var(--svg-color--c37d25, #C37D25);
  stop-opacity: 0;
}

.h5siw4ltz {
  cx: 26.558px;
  cy: 8.318px;
  r: 1.671px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.h6mapivpu {
  cx: 19.384px;
  cy: 13.666px;
  r: 0.996px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.h8ctczbhu {
  fill: var(--svg-color--000, #000);
  d: path("M12.938 13.4a.51.51 0 0 0-.512-.512a.51.51 0 0 0-.455.747h.906a.5.5 0 0 0 .06-.236");
}

.h9turkxgz {
  stop-color: var(--svg-color--c36841, #C36841);
}

.hchnd0bsx {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
  stop-opacity: 0;
}

.hfzmunkww {
  stop-color: var(--svg-color--bb7930, #BB7930);
}

.hjpcf-cgn {
  d: path("m19.438 7.182l.429.214c.752.373 1.181 1.228 1.02 2.135l-.59 3.043c-.053.314-.26.526-.573.534c.036-.505.069-1.318.082-1.446c.043-.434-.025-.561-.422-.957c-.215-.213-.376-.533-.376-.854v-.854c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.919-.427s-3.275.267-3.92.427a.52.52 0 0 0-.429.534v.854c0 .32-.107.64-.376.854l-.16.16c-.216.16-.324.495-.324.762c.014.156.035 1.053.06 1.426a.634.634 0 0 1-.596-.532l-.59-3.043c-.108-.854.322-1.709 1.073-2.082c1.015-.445 1.385-1.12 2.202-1.815c.59-.534 1.45-.694 2.201-.32c.537.16 1.127.16 1.664 0c.806-.268 1.719-.054 2.363.533l.805.8c.215.268.483.428.805.588");
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.hos3q5hgu {
  stop-color: var(--svg-color--367bf1, #367BF1);
}

.hy0z0nf6k {
  stop-color: var(--svg-color--a4888c, #A4888C);
  stop-opacity: 0;
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i-_w3pl3s {
  cx: 9.862px;
  cy: 13.666px;
  r: 0.996px;
}

.j52kqi5ci {
  stop-color: var(--svg-color--e98728, #E98728);
}

.j80tr6o9y {
  stop-color: var(--svg-color--c7b1b5, #C7B1B5);
}

.jaxt-o31p {
  stop-color: var(--svg-color--ff2d78, #FF2D78);
}

.jd-vaq0no {
  stop-color: var(--svg-color--93768e, #93768E);
}

.jgp08zdxo {
  d: path("M12.63 18.49h3.985v1.384c0 1.1-.892 1.812-1.992 1.812s-1.992-.712-1.992-1.812z");
}

.jgpkicc4o {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M14.614 16.8c-.508 0-.985-.12-1.386-.33c-.137-.07-.285.085-.198.21c.335.508.919.846 1.584.846s1.25-.338 1.584-.846c.087-.13-.06-.28-.198-.21c-.4.21-.873.33-1.386.33");
}

.jiyvp-brd {
  stop-color: var(--svg-color--f39c27, #F39C27);
  stop-opacity: 0;
}

.jlkbatyzp {
  stop-color: var(--svg-color--43a0f3, #43A0F3);
}

.jtcqeoejk {
  stop-color: var(--svg-color--fcb831, #FCB831);
}

.jwr2g_bnr {
  stop-color: var(--svg-color--f5c028, #F5C028);
  stop-opacity: 0;
}

.jzjqx7qlk {
  stop-color: var(--svg-color--ff7e7a, #FF7E7A);
}

.k-z4zg2os {
  stop-color: var(--svg-color--517cc3, #517CC3);
}

.k5rz6m_ej {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.004 12.234c.654 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34h-2.233a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.372-1.129");
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.kin3dabop {
  stop-color: var(--svg-color--43a2ff, #43A2FF);
}

.kv8z47b6z {
  d: path("m14.231 13.38l-.531 1.702a.54.54 0 0 0 .52.7h.787c.37 0 .63-.356.521-.7l-.531-1.702c-.114-.376-.646-.376-.766 0");
}

.kyzs66gfi {
  stop-color: var(--svg-color--e07027, #E07027);
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.lapvr59ed {
  stop-color: var(--svg-color--d9b4c8, #D9B4C8);
}

.lg_7a3bcy {
  stop-color: var(--svg-color--da7126, #DA7126);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lm7x8mbti {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.614 16.8c-.508 0-.985-.12-1.386-.33c-.137-.07-.285.085-.198.21c.335.508.919.846 1.584.846s1.25-.338 1.584-.846c.087-.13-.06-.28-.198-.21c-.4.21-.873.33-1.386.33Z");
}

.lxc0fmbqt {
  stop-color: var(--svg-color--c0a0b5, #C0A0B5);
  stop-opacity: 0;
}

.m-fo0lvbc {
  stop-color: var(--svg-color--407da5, #407DA5);
}

.m8bo-jb-t {
  stop-color: var(--svg-color--996e9f, #996E9F);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbmro29rs {
  stop-color: var(--svg-color--ffe833, #FFE833);
}

.md9bsbc9k {
  stop-color: var(--svg-color--ffbe30, #FFBE30);
  stop-opacity: 0;
}

.mq0bii3nt {
  stop-color: var(--svg-color--459bfc, #459BFC);
  stop-opacity: 0;
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.mrt-5h0hn {
  stop-color: var(--svg-color--c64f38, #C64F38);
}

.n0mdw4xep {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.731 12.695c.064.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.245.158-.358c.152-.114.326-.136.39-.051");
}

.ndcqgbbqr {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m14.231 13.38l-.531 1.702a.54.54 0 0 0 .52.7h.787c.37 0 .63-.356.521-.7l-.531-1.702c-.114-.376-.646-.376-.766 0");
}

.ne28hevog {
  d: path("M17.593 13.282a.84.84 0 0 0-.232-.463l-.26.285l.117.228z");
}

.ni_6htbzm {
  stop-color: var(--svg-color--b71143, #B71143);
}

.nr3rksbet {
  stop-color: var(--svg-color--f4b22d, #F4B22D);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ogdh_qdtu {
  d: path("M20.283 6.381c-1.215-.027-1.642-.097-2.18-.285l1.061 1.785c.189.318.538.506.901.44c.85-.155 2.12-.53 2.703-1.053c.843-.758.785-1.492.715-1.758c-.07-.265-.211-.445-.352-.453s-.26.062-.39.375c-.212.508-.883.985-2.458.95");
}

.omp34eowh {
  cx: 23.739px;
  cy: 7.515px;
  r: 0.313px;
}

.oxun88gow {
  stop-color: var(--svg-color--438dec, #438DEC);
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p3ke5p64t {
  stop-color: var(--svg-color--ffbe22, #FFBE22);
  stop-opacity: 0;
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.p8j84vbpc {
  stop-color: var(--svg-color--ffd530, #FFD530);
}

.p9lsnsm5t {
  stop-color: var(--svg-color--9b8299, #9B8299);
}

.pb3_oi83v {
  stop-color: var(--svg-color--c9993e, #C9993E);
}

.pgx41lb8h {
  d: path("M9.51 13.053a30 30 0 0 1-.059-1.44c0-.267.108-.587.322-.747l.162-.16c.268-.214.375-.534.375-.855v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.92-.427c1.932 0 3.274.267 3.919.427c.214.054.43.267.43.534v.854c0 .32.16.641.375.855c.503.352.471.546.43.96c-.013.13-.054 1.196-.09 1.442l-.266 3.962c-.16 1.771-1.553 3.006-3.213 3.006H13.03c-1.713 0-3.052-1.235-3.213-3.006z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.poyan9ogy {
  cx: 19.384px;
  cy: 13.666px;
  r: 1.671px;
}

.puczgzv3j {
  stop-color: var(--svg-color--459bfc, #459BFC);
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.q7gzk7bcw {
  fill-rule: evenodd;
  d: path("M12.833 11.459c-.72-.068-1.183.213-1.295.317a.473.473 0 0 1-.64-.696c.306-.282 1.032-.656 2.023-.563a.473.473 0 1 1-.088.942");
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qeh0r4bjq {
  stop-color: var(--svg-color--ffe336, #FFE336);
  stop-opacity: 0;
}

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
  stop-opacity: 0;
}

.qnvktkxoh {
  d: path("M16.731 12.695c.064.085-.07.189-.22.302c-.151.113-.264.192-.327.107c-.064-.085.007-.245.158-.358c.152-.114.326-.136.39-.051");
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r5vidg5lt {
  stop-color: var(--svg-color--c37d25, #C37D25);
}

.r8eqjtbel {
  cx: 22.91px;
  cy: 10.332px;
  r: 1.117px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.r8ibvzbki {
  stop-color: var(--svg-color--ff9266, #FF9266);
  stop-opacity: 0;
}

.rhwb21akg {
  fill: var(--svg-color--ffa91b, #FFA91B);
  d: path("m19.438 7.182l.429.214c.752.373 1.181 1.228 1.02 2.135l-.59 3.043c-.053.314-.26.526-.573.534c.036-.505.069-1.318.082-1.446c.043-.434-.025-.561-.422-.957c-.215-.213-.376-.533-.376-.854v-.854c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.919-.427s-3.275.267-3.92.427a.52.52 0 0 0-.429.534v.854c0 .32-.107.64-.376.854l-.16.16c-.216.16-.324.495-.324.762c.014.156.035 1.053.06 1.426a.634.634 0 0 1-.596-.532l-.59-3.043c-.108-.854.322-1.709 1.073-2.082c1.015-.445 1.385-1.12 2.202-1.815c.59-.534 1.45-.694 2.201-.32c.537.16 1.127.16 1.664 0c.806-.268 1.719-.054 2.363.533l.805.8c.215.268.483.428.805.588");
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rizphhb9m {
  fill-rule: evenodd;
  d: path("M23.013 7.957a.1.1 0 0 0-.124.068l-.104.357a.22.22 0 0 1-.174.148a1.842 1.842 0 1 0 1.514.434a.21.21 0 0 1-.068-.22l.101-.349a.1.1 0 0 0-.068-.124zm.74 2.391a.844.844 0 1 1-1.687 0a.844.844 0 0 1 1.688 0");
}

.rraw6sbsp {
  stop-color: var(--svg-color--ff9266, #FF9266);
}

.rxprtfb0z {
  stop-color: var(--svg-color--407da5, #407DA5);
  stop-opacity: 0;
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.s_ha1fylz {
  stop-color: var(--svg-color--ddb13b, #DDB13B);
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.s80emud-s {
  d: path("m24.342 3.159l-1.388 4.83l1.186.345l1.072-3.729a1.15 1.15 0 0 0-.784-1.421z");
}

.srm_r_guo {
  stop-color: var(--svg-color--ff6792, #FF6792);
}

.syu65hrvi {
  d: path("M3.601 29.408c0-5.916 4.854-10.711 10.842-10.711s10.842 4.795 10.842 10.71v.464H3.601z");
}

.t_i0qw3fw {
  stop-color: var(--svg-color--c36841, #C36841);
  stop-opacity: 0;
}

.t3at67xsm {
  d: path("M12.426 12.506a.893.893 0 0 0-.86 1.129h1.724a1 1 0 0 0 .033-.236a.9.9 0 0 0-.897-.893");
}

.t4clght5m {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
  stop-opacity: 0;
}

.t6-u-13dn {
  d: path("m19.694 5.736l5.42 1.536l-.338 1.188l-4.313-1.222a1.15 1.15 0 0 1-.793-1.42z");
}

.tet72waca {
  stop-color: var(--svg-color--339ff3, #339FF3);
}

.tkln9gb_r {
  fill: var(--svg-color--2b7fde, #2B7FDE);
  d: path("M7.31 21.341c-2.273 1.964-3.71 4.85-3.71 8.067v.463h3.71z");
}

.tp7243aiy {
  fill-rule: evenodd;
  d: path("M24.457 7.17a.1.1 0 0 1 .123-.07l.36.095c.079.02.162-.01.216-.073a1.842 1.842 0 1 1-.412 1.52a.22.22 0 0 0-.153-.171l-.351-.094a.1.1 0 0 1-.071-.122zm1.664 1.87a.844.844 0 1 0 .872-1.444a.844.844 0 0 0-.872 1.445");
}

.tq9wobc8t {
  cx: 12.156px;
  cy: 12.888px;
  rx: 0.39px;
  ry: 0.197px;
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.txm2ysbkn {
  stop-color: var(--svg-color--367bf1, #367BF1);
  stop-opacity: 0;
}

.u1w4jn-zg {
  fill: var(--svg-color--f4aa28, #F4AA28);
  d: path("M12.63 18.49h3.985v1.384c0 1.1-.892 1.812-1.992 1.812s-1.992-.712-1.992-1.812z");
}

.u3uvzrbhu {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.219 12.234c-.654 0-1.206.45-1.356 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.372-1.129");
}

.ul1-t-qnt {
  d: path("M13.242 13.294c0-.288-.235-.48-.299-.539l-.288.28l.178.36z");
}

.uoxk3uguq {
  fill-rule: evenodd;
  d: path("M16.395 11.459c.72-.068 1.183.213 1.295.317a.473.473 0 0 0 .64-.696c-.306-.282-1.032-.656-2.023-.563a.473.473 0 0 0 .088.942");
}

.urqhv2b1h {
  stop-color: var(--svg-color--fcb831, #FCB831);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vp_-q7ldm {
  stop-color: var(--svg-color--517cc3, #517CC3);
  stop-opacity: 0;
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.w3vw2zbpg {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.218 11.317c.21-.193.803-.52 1.659-.44");
}

.w5_7ycb6b {
  stop-color: var(--svg-color--ff4f4f, #FF4F4F);
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.wifd57bhn {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m14.338 13.544l-.82 1.701c-.103.35.142.7.488.7h.738c.346 0 .59-.355.488-.7l-.498-1.701c-.107-.377-.284-.377-.396 0");
}

.wke-8-xfb {
  stop-color: var(--svg-color--1f6ce0, #1F6CE0);
}

.wn92vfpti {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.wy7e69bbh {
  stop-color: var(--svg-color--c8b3b7, #C8B3B7);
  stop-opacity: 0;
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.xaad_wcir {
  stop-color: var(--svg-color--bb4f29, #BB4F29);
}

.xrrmohu-n {
  stop-color: var(--svg-color--f09f2b, #F09F2B);
  stop-opacity: 0;
}

.y9qcw5bms {
  stop-color: var(--svg-color--f4b22d, #F4B22D);
  stop-opacity: 0;
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.zdar40bkv {
  stop-color: var(--svg-color--145491, #145491);
}

.zi0iv1bfj {
  stop-color: var(--svg-color--438dec, #438DEC);
  stop-opacity: 0;
}

.zi0lb2bns {
  stop-color: var(--svg-color--ff5185, #FF5185);
  stop-opacity: 0;
}

.zjmwko4fr {
  stop-color: var(--svg-color--ffd069, #FFD069);
}

.zjwaehbsp {
  stop-color: var(--svg-color--ffd437, #FFD437);
}

.zk512ndyg {
  stop-color: var(--svg-color--a4888c, #A4888C);
}

.zl0fwhbas {
  stop-color: var(--svg-color--a28b95, #A28B95);
}

.znwvjy5yx {
  stop-color: var(--svg-color--ff5c88, #FF5C88);
}

.zsx4vmb0f {
  stop-color: var(--svg-color--e07027, #E07027);
  stop-opacity: 0;
}

</style>
