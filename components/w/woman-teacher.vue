<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iG3GIeX)"><path fill="url(#iZ1blid)" class="sq_vp-4np"/></g><path fill="url(#iWZLTPc)" class="m23un_v9r"/><path fill="url(#iZhYo4d)" class="m23un_v9r"/><path fill="url(#iG9myyD)" class="m23un_v9r"/><g filter="url(#i8Ovy6b)"><path stroke="url(#ihRyUEe)" class="aoym4l1xy"/></g><g filter="url(#iC4F8Kc)"><path fill="url(#ihd8Syd)" class="s599a1bap"/><path fill="url(#iGouupc)" class="s599a1bap"/><path fill="url(#ivSmf0b)" class="s599a1bap"/></g><g filter="url(#imdlEGc)"><path fill="url(#iBWW3qc)" clip-rule="evenodd" class="n02eidbqs"/><path fill="url(#i0SuEec)" clip-rule="evenodd" class="n02eidbqs"/><path fill="url(#igTKj2d)" clip-rule="evenodd" class="n02eidbqs"/><path fill="url(#i2PPmqd)" clip-rule="evenodd" class="n02eidbqs"/><path fill="url(#i3mGnte)" clip-rule="evenodd" class="n02eidbqs"/><path fill="url(#iXVf8nd)" clip-rule="evenodd" class="n02eidbqs"/><path fill="url(#i5tIdWd)" clip-rule="evenodd" class="n02eidbqs"/><path fill="url(#iS15nXd)" clip-rule="evenodd" class="n02eidbqs"/><path fill="url(#iEw2Mte)" clip-rule="evenodd" class="n02eidbqs"/><path fill="url(#iKrvyue)" clip-rule="evenodd" class="n02eidbqs"/></g><path fill="url(#iWn8A8c)" class="bta5wpblo"/><path fill="url(#i1TCM1k)" class="bta5wpblo"/><path fill="url(#iGED6Pb)" class="bta5wpblo"/><path fill="url(#iG6RJad)" class="rekkd-b6b"/><path fill="url(#ijG3Ble)" class="rekkd-b6b"/><path fill="url(#iaHTpCd)" class="rekkd-b6b"/><path fill="url(#iDEHmlb)" class="k4ucljb_r"/><path fill="url(#izdxWxc)" class="k4ucljb_r"/><path fill="url(#iHhLu3d)" class="zk02wzc7y"/><g filter="url(#i7XrhPM)"><path fill="url(#i1qvtFr)" class="eseh3ccnk"/><path fill="url(#idSeBCc)" class="eseh3ccnk"/><path fill="url(#iE7nvFb)" class="eseh3ccnk"/><path fill="url(#i3oNjre)" class="eseh3ccnk"/></g><g filter="url(#idZUgKc)"><path fill="url(#iye3gQe)" class="kdpvi8bty"/><path fill="url(#ibsHVHc)" class="kdpvi8bty"/><path fill="url(#iwwrY5c)" class="kdpvi8bty"/><path fill="url(#i8DBofm)" class="kdpvi8bty"/></g><path fill="url(#iUORo5c)" class="k2he7fbdg"/><path fill="url(#i0a6Tvb)" class="g51venbyw"/><path fill="url(#iYTj5Db)" class="xpfqoet5v"/><path fill="url(#iXxcGoc)" class="scqmvqbyx"/><path clip-rule="evenodd" class="v8d-6__pr"/><path fill="url(#iQyMHce)" clip-rule="evenodd" class="n-73b991b"/><g filter="url(#iHQWsZd)"><path fill="url(#iedzVjb)" class="qibo5-0bn"/></g><g filter="url(#izKEJcc)"><path fill="url(#inKEYud)" class="gc9m5mdrr"/></g><path fill="url(#iivjUXQ)" class="k_mhzeg6j"/><path fill="url(#isD866c)" class="anvnien4h"/><g filter="url(#iLwBqqq)"><path stroke="url(#i4Vj05r)" class="jgqht7b_r"/></g><g filter="url(#iecDDDb)"><path stroke="url(#iCcunCn)" class="rm4x5nmvd"/></g><g filter="url(#i8CVzDb)"><path stroke="url(#iIlTMjz)" class="gtmeeib0y"/></g><g filter="url(#ixITwXd)"><path stroke="url(#ioVA5me)" class="zcr5gg5_s"/></g><g filter="url(#iOJxnOd)"><path stroke="url(#ijyyeOc)" class="dhd2d0b1r"/></g><g filter="url(#idIvyUd)"><path stroke="url(#ij8ML3d)" class="nyj5kteen"/></g><g filter="url(#iodfSwd)"><path fill="url(#iiOtYfN)" class="la8u06l5z"/></g><g filter="url(#iKk99rb)"><path fill="url(#iw8jW9b)" class="jdxiygy-f"/></g><g filter="url(#irSLDfe)"><path class="kyonfdcsy"/><path fill="url(#iUjBvCd)" class="tt6zhpmrj"/></g><g filter="url(#iQwzkRd)"><path class="t6j-eenhm"/><path fill="url(#i4DRsnd)" class="w_th7pbmt"/></g><g filter="url(#ipGMMEe)"><path fill="url(#i3P6AXd)" class="dysvcqzhm"/><path fill="url(#inMNuSb)" class="dysvcqzhm"/><path fill="url(#iwnxbgb)" class="dysvcqzhm"/><path fill="url(#i1rY5Zc)" class="dysvcqzhm"/><path fill="url(#izNECwe)" class="dysvcqzhm"/><path fill="url(#iiQYHZb)" class="dysvcqzhm"/><path fill="url(#iay7Jyd)" class="dysvcqzhm"/></g><path fill="url(#i7mShAb)" class="dysvcqzhm"/><g filter="url(#iUGylYd)"><path class="wec460bot"/></g><g filter="url(#iILnqOd)"><path fill="url(#iFw3bJb)" class="d9yh9ccdg"/><path fill="url(#iu9ayod)" class="d9yh9ccdg"/><path fill="url(#iQHPAdd)" class="d9yh9ccdg"/><path fill="url(#ibfzRBB)" class="d9yh9ccdg"/></g><path fill="url(#iw9aaHc)" class="d9yh9ccdg"/><path fill="url(#iRAeBxd)" class="d9yh9ccdg"/><path stroke="url(#iOI3Lld)" class="eajhqmsyf"/><g filter="url(#iEBXs2d)"><path class="xerarbgsl"/></g><g filter="url(#iGBpD2V)"><path class="lhzq6sthb"/></g><g filter="url(#isQwczc)"><path class="toyl6td3i"/></g><g filter="url(#it42dFd)"><path clip-rule="evenodd" class="ivh818b_e"/></g><path class="k4uqm-3qp"/><path fill="url(#itTcy9c)" class="cyv1u6bkx"/><path class="y_oifu3xm"/><g filter="url(#iLZzuXf)"><path class="sm6solb0h"/><path fill="url(#i1uyKnC)" class="as_1moxii"/></g><g filter="url(#iyTLlGc)"><path fill="url(#ivvzTxu)" class="mtw9cmojx"/></g><path class="l0olepbgo"/><path fill="url(#imcuO1Y)" class="flgk3ob-g"/><path class="j_sh0abos"/><g filter="url(#iip3Whd)"><path fill="url(#iXU9Bvc)" class="xv5mlgynl"/></g><g filter="url(#ipd0hQJ)"><ellipse transform="rotate(-27.914 13.543 10.024)" class="p8v5p6bjo"/><ellipse fill="url(#iGFdXfb)" transform="rotate(-27.914 13.543 10.024)" class="yg2bpcbyf"/></g><g filter="url(#iGVX8hb)"><path class="prpkwxers"/></g><g filter="url(#iuN1GGb)"><path class="hkhuycurt"/></g><g filter="url(#i59oxRd)"><path fill="url(#iGTMHpc)" class="b3yosxwqw"/><path fill="url(#i4c91gt)" class="b3yosxwqw"/></g><g filter="url(#iGVWPFb)"><path fill="url(#iAeWfgd)" class="jb7dwha5m"/><path fill="url(#idSQTki)" class="jb7dwha5m"/><path fill="url(#iunJIlr)" class="jb7dwha5m"/></g><g filter="url(#iPQz2OH)"><path stroke="url(#ikpFD0i)" class="h-hceo6qn"/></g><g filter="url(#iwl7mbd)"><path fill="url(#i1eJpwb)" class="n6p6pxbvb"/><path fill="url(#isvvZdc)" class="n6p6pxbvb"/></g><defs><radialGradient id="iZhYo4d" cx="0" cy="0" r="1" gradientTransform="rotate(-56.746 27.057 6.904)scale(18.2363 24.9585)" gradientUnits="userSpaceOnUse"><stop class="hpdf2p89l"/><stop offset="1" class="wfc059byj"/></radialGradient><radialGradient id="iG9myyD" cx="0" cy="0" r="1" gradientTransform="matrix(-9.99996 -14.06247 13.90983 -9.89141 29.572 25.494)" gradientUnits="userSpaceOnUse"><stop class="od6_koblh"/><stop offset="1" class="cxrlhcc-d"/></radialGradient><radialGradient id="ivSmf0b" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.31138 -.61764 0 2.014 4.33)" gradientUnits="userSpaceOnUse"><stop offset=".355" class="g043vp3zf"/><stop offset="1" class="sihp1fb9k"/></radialGradient><radialGradient id="i0SuEec" cx="0" cy="0" r="1" gradientTransform="matrix(2.32402 1.10011 -1.55825 3.29187 19.849 14.033)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="w3-vy4c8j"/><stop offset="1" class="w72oynbwi"/></radialGradient><radialGradient id="igTKj2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.47663 -2.69702 0 11.417 12.762)" gradientUnits="userSpaceOnUse"><stop class="lcrdwk1fj"/><stop offset="1" class="denqa3bda"/></radialGradient><radialGradient id="i2PPmqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.59621 -5.82947 0 16.009 12.855)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="ag6fa4z4y"/><stop offset="1" class="qir_1cb0f"/></radialGradient><radialGradient id="i3mGnte" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24637 1.61745 -1.57046 -1.21016 11.076 11.042)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="ha2cq84sa"/><stop offset="1" class="p4wkjrbae"/></radialGradient><radialGradient id="iXVf8nd" cx="0" cy="0" r="1" gradientTransform="rotate(100.537 2.263 9.147)scale(2.56847 2.67458)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="tgqxysbgm"/><stop offset="1" class="p1xq25bjq"/></radialGradient><radialGradient id="i5tIdWd" cx="0" cy="0" r="1" gradientTransform="matrix(1.10051 2.12352 -4.04525 2.09645 12.657 3.524)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="esx41hbqq"/><stop offset=".921" class="v9rq5jjti"/></radialGradient><radialGradient id="iS15nXd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.11125 1.21229 -1.69415 -1.55295 21.531 4.948)" gradientUnits="userSpaceOnUse"><stop class="duwob45dr"/><stop offset="1" class="v61l3jbat"/></radialGradient><radialGradient id="iEw2Mte" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 11.073 6.61)scale(1.92879 4.19679)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="hottnizrg"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="iKrvyue" cx="0" cy="0" r="1" gradientTransform="matrix(-.00847 -1.38058 .45265 -.00278 13.291 6.03)" gradientUnits="userSpaceOnUse"><stop offset=".295" class="sufhn4bec"/><stop offset="1" class="kpf8h5ohf"/></radialGradient><radialGradient id="iWn8A8c" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.0469 -6.21865 0 16.01 15.963)" gradientUnits="userSpaceOnUse"><stop class="zlcjw7bgf"/><stop offset="1" class="qna-_2b3m"/></radialGradient><radialGradient id="i1TCM1k" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.375 -2.9375 0 22.666 20.494)" gradientUnits="userSpaceOnUse"><stop class="us4ivbb3t"/><stop offset="1" class="yvo_l_bkn"/></radialGradient><radialGradient id="iGED6Pb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 1.53125 -1.23438 -1.23438 12.727 19.088)" gradientUnits="userSpaceOnUse"><stop class="rkna2zbug"/><stop offset="1" class="ox51r5bse"/></radialGradient><radialGradient id="iG6RJad" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.1875 3.85106 0 27.004 28.244)" gradientUnits="userSpaceOnUse"><stop class="rqxi6yb_m"/><stop offset="1" class="vuu7bk4vv"/></radialGradient><radialGradient id="izdxWxc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.92068 0 0 -17.2807 11.468 29.793)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="qo_nu3b1v"/><stop offset="1" class="b4vmzacii"/></radialGradient><radialGradient id="iHhLu3d" cx="0" cy="0" r="1" gradientTransform="matrix(3.59375 0 0 13.6636 15.197 18.771)" gradientUnits="userSpaceOnUse"><stop class="tp0kp63lp"/><stop offset="1" class="ei_98vf4e"/></radialGradient><radialGradient id="idSeBCc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.59385 -3.38389 2.04685 -.9641 21.24 19.454)" gradientUnits="userSpaceOnUse"><stop class="kl3ja4pbq"/><stop offset="1" class="ybzr6jbff"/></radialGradient><radialGradient id="iE7nvFb" cx="0" cy="0" r="1" gradientTransform="matrix(-.9453 -1.33595 .2433 -.17216 19.681 20.464)" gradientUnits="userSpaceOnUse"><stop class="uqvywhymc"/><stop offset="1" class="y1kgfac6n"/></radialGradient><radialGradient id="i3oNjre" cx="0" cy="0" r="1" gradientTransform="matrix(.53247 1.23437 -2.31052 .99669 17.531 15.776)" gradientUnits="userSpaceOnUse"><stop offset=".359" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="ibsHVHc" cx="0" cy="0" r="1" gradientTransform="matrix(.0625 -3.125 1.26232 .02525 13.525 20.37)" gradientUnits="userSpaceOnUse"><stop class="kiracnbim"/><stop offset="1" class="n8mbjcbow"/></radialGradient><radialGradient id="i8DBofm" cx="0" cy="0" r="1" gradientTransform="rotate(122.784 2.74 11.85)scale(1.09654 2.05252)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="fgkcx3bbf"/><stop offset="1" class="gihkuibxq"/></radialGradient><radialGradient id="iUORo5c" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.4375 -2.45255 0 16.386 15.991)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="oa_0r4bea"/><stop offset=".637" class="kpqm10zsn"/><stop offset="1" class="p33y7xmqq"/></radialGradient><radialGradient id="i0a6Tvb" cx="0" cy="0" r="1" gradientTransform="matrix(-1 1 -1.11832 -1.11832 23.057 23.643)" gradientUnits="userSpaceOnUse"><stop class="yomsttbzk"/><stop offset=".814" class="gchclybws"/></radialGradient><radialGradient id="iYTj5Db" cx="0" cy="0" r="1" gradientTransform="matrix(1.59343 0 0 4.99275 9.072 24.635)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="ydne4ly1n"/><stop offset="1" class="h55048b_d"/></radialGradient><radialGradient id="iw8jW9b" cx="0" cy="0" r="1" gradientTransform="matrix(2.50032 -1.13651 1.38763 3.05278 20.067 11.16)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="iUjBvCd" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 40.92 -52.122)scale(1.31049)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="i4DRsnd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07897 0 0 -1.03211 11.321 10.72)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="i3P6AXd" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.323 7.162)scale(7.19417 9.62928)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="m45oyzb-o"/></radialGradient><radialGradient id="inMNuSb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.11929 1.12097 -.95106 -1.79807 17.918 10.88)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="iwnxbgb" cx="0" cy="0" r="1" gradientTransform="matrix(.84069 -4.06346 5.15576 1.06668 13.82 16.993)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="i1rY5Zc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.47428 -11.8712 0 15.746 9.694)" gradientUnits="userSpaceOnUse"><stop offset=".593" class="ajxs5ri3z"/><stop offset="1" class="x05md6_2b"/></radialGradient><radialGradient id="izNECwe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.44711 1.50632 -2.59342 -9.37825 16.639 11.844)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="iiQYHZb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15598 1.4187 0 18.32 9.76)" gradientUnits="userSpaceOnUse"><stop class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="iay7Jyd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36616 1.56571 0 14.082 9.847)" gradientUnits="userSpaceOnUse"><stop class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="i7mShAb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.35305 0 0 -4.45428 21.127 11.254)" gradientUnits="userSpaceOnUse"><stop class="f902gfhfn"/><stop offset="1" class="jh40i5bvl"/></radialGradient><radialGradient id="iu9ayod" cx="0" cy="0" r="1" gradientTransform="matrix(-.70061 -2.46083 1.40812 -.4009 16.797 11.984)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="iRAeBxd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28734 .91954 -1.23165 -1.7243 16.297 11.625)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="e6-lebcyw"/><stop offset="1" class="b8os9sbcy"/></radialGradient><radialGradient id="itTcy9c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81499 -1.29633 0 18.2 10.12)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i1uyKnC" cx="0" cy="0" r="1" gradientTransform="matrix(-.23254 -.29966 .41256 -.32015 17.97 10.204)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="imcuO1Y" cx="0" cy="0" r="1" gradientTransform="matrix(0 .815 -1.29634 0 13.817 10.12)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iGFdXfb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00776 -.49539 .59548 -.00932 13.528 10.34)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iGTMHpc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.43481 4.15877 -1.81377 -1.49803 13.281 3.736)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="esh4v5qtq"/><stop offset=".911" class="nria2ku7r"/></radialGradient><radialGradient id="i4c91gt" cx="0" cy="0" r="1" gradientTransform="matrix(-3.11681 2.22665 -1.10044 -1.54037 13.141 4.285)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="dpv-wxbjb"/><stop offset="1" class="abu2lcc5n"/><stop offset="1" class="sxoxd_kke"/></radialGradient><radialGradient id="iAeWfgd" cx="0" cy="0" r="1" gradientTransform="rotate(115.63 8.1 6.883)scale(5.07502 7.20568)" gradientUnits="userSpaceOnUse"><stop offset=".627" class="crfaaqblp"/><stop offset="1" class="ehjghj3fe"/></radialGradient><radialGradient id="idSQTki" cx="0" cy="0" r="1" gradientTransform="rotate(105.909 7.824 8.901)scale(3.45561 7.24187)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="z-gx2rb2w"/><stop offset="1" class="gbpc14bxe"/></radialGradient><radialGradient id="iunJIlr" cx="0" cy="0" r="1" gradientTransform="rotate(-117.848 11.436 -.435)scale(7.34765 6.56835)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="s3t3owbgt"/><stop offset="1" class="yehxt3bls"/></radialGradient><radialGradient id="isvvZdc" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 2.71875 11.385 10.192)" gradientUnits="userSpaceOnUse"><stop class="zobbewbqd"/><stop offset="1" class="cesjesv2y"/></radialGradient><filter id="iG3GIeX" width="27.98" height="21.09" x="2.014" y="4.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.81585 0 0 0 0 0.641744 0 0 0 0 0.41905 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1653"/></filter><filter id="i8Ovy6b" width="27.413" height="20.785" x="2.678" y="3.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1653" stdDeviation=".2"/></filter><filter id="iC4F8Kc" width="27.91" height="20.96" x="2.014" y="4.03" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.482353 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1653"/></filter><filter id="imdlEGc" width="15.336" height="15.336" x="8.466" y="1.903" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.537255 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1653"/></filter><filter id="i7XrhPM" width="2.797" height="14.522" x="18.064" y="15.488" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1653"/></filter><filter id="idZUgKc" width="2.797" height="14.521" x="11.157" y="15.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.164706 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1653"/></filter><filter id="iHQWsZd" width="4.593" height="5.591" x="8.96" y="24.419" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.588235 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1653"/></filter><filter id="izKEJcc" width="4.593" height="5.591" x="18.664" y="24.419" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.458824 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1653"/></filter><filter id="iLwBqqq" width="2.222" height=".3" x="18.883" y="25.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1653" stdDeviation=".05"/></filter><filter id="iecDDDb" width="2.222" height=".3" x="10.87" y="25.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1653" stdDeviation=".05"/></filter><filter id="i8CVzDb" width="2.222" height=".3" x="18.883" y="27.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1653" stdDeviation=".05"/></filter><filter id="ixITwXd" width="2.222" height=".3" x="10.87" y="27.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1653" stdDeviation=".05"/></filter><filter id="iOJxnOd" width="2.222" height=".3" x="18.883" y="28.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1653" stdDeviation=".05"/></filter><filter id="idIvyUd" width="2.222" height=".3" x="10.87" y="28.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1653" stdDeviation=".05"/></filter><filter id="iodfSwd" width="3.333" height="3.233" x="9.685" y="9.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.501961 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1653"/></filter><filter id="iKk99rb" width="3.233" height="3.483" x="19.241" y="8.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1653"/></filter><filter id="irSLDfe" width="3.158" height="3.158" x="19.279" y="9.141" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1653" stdDeviation=".25"/></filter><filter id="iQwzkRd" width="2.658" height="2.658" x="9.992" y="9.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1653" stdDeviation=".125"/></filter><filter id="ipGMMEe" width="10.237" height="11.326" x="10.89" y="5.791" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1653"/></filter><filter id="iUGylYd" width="2.886" height="3.694" x="14.403" y="9.712" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1653" stdDeviation=".25"/></filter><filter id="iILnqOd" width="2.386" height="3.194" x="14.816" y="9.823" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1653" stdDeviation=".125"/></filter><filter id="iEBXs2d" width="3.014" height="1.291" x="16.956" y="9.309" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1653"/></filter><filter id="iGBpD2V" width="3.014" height="1.291" x="12.048" y="9.309" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1653"/></filter><filter id="isQwczc" width="2.463" height="1.095" x="12.183" y="7.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1653"/></filter><filter id="it42dFd" width="2.463" height="1.095" x="17.625" y="7.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1653"/></filter><filter id="iLZzuXf" width=".788" height=".698" x="17.463" y="9.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1653" stdDeviation=".05"/></filter><filter id="iyTLlGc" width=".893" height=".915" x="18.308" y="9.754" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1653" stdDeviation=".1"/></filter><filter id="iip3Whd" width=".988" height="1.042" x="13.845" y="9.691" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1653" stdDeviation=".1"/></filter><filter id="ipd0hQJ" width=".915" height=".706" x="13.086" y="9.671" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1653" stdDeviation=".05"/></filter><filter id="iGVX8hb" width="2.268" height=".98" x="17.657" y="7.923" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1653" stdDeviation=".1"/></filter><filter id="iuN1GGb" width="2.268" height=".98" x="12.181" y="7.923" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1653" stdDeviation=".1"/></filter><filter id="i59oxRd" width="5.001" height="5.23" x="9.274" y="3.414" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1653" stdDeviation=".375"/></filter><filter id="iGVWPFb" width="8.952" height="5.804" x="12.678" y="2.61" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1653" stdDeviation=".125"/></filter><filter id="iPQz2OH" width="1.147" height="2.317" x="12.804" y="3.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1653" stdDeviation=".125"/></filter><filter id="iwl7mbd" width="10.29" height="4.06" x="10.894" y="8.682" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376863 0 0 0 0 0.313721 0 0 0 0 0.444863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1653"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.160784 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1653" result="effect2_innerShadow_4002_1653"/></filter><linearGradient id="iZ1blid" x1="11.828" x2="31.271" y1="4.619" y2="22.854" gradientUnits="userSpaceOnUse"><stop class="lj0sm1b7l"/><stop offset=".568" class="u1egy7b7t"/><stop offset="1" class="auorgtyhp"/></linearGradient><linearGradient id="iWZLTPc" x1="30.072" x2="9.135" y1="13.307" y2="13.307" gradientUnits="userSpaceOnUse"><stop class="nfwti5bbx"/><stop offset="1" class="r4c-t7bme"/></linearGradient><linearGradient id="ihRyUEe" x1="13.447" x2="31.259" y1="3.56" y2="24.372" gradientUnits="userSpaceOnUse"><stop class="y1ij6ubnw"/><stop offset="1" class="jpk8o_7uj"/></linearGradient><linearGradient id="ihd8Syd" x1="-4.897" x2="28.916" y1="25.651" y2="25.651" gradientUnits="userSpaceOnUse"><stop class="xtl7t4edr"/><stop offset="1" class="wn11gcx8f"/></linearGradient><linearGradient id="iGouupc" x1="3.103" x2="3.103" y1="5.213" y2="23.651" gradientUnits="userSpaceOnUse"><stop class="e1bvu4b8w"/><stop offset="1" class="jij-d9bro"/></linearGradient><linearGradient id="iBWW3qc" x1="20.723" x2="13.449" y1="3.736" y2="17.239" gradientUnits="userSpaceOnUse"><stop class="yr1vjkbzu"/><stop offset="1" class="btu9i2bec"/></linearGradient><linearGradient id="ijG3Ble" x1="25.183" x2="25.183" y1="30.464" y2="26.647" gradientUnits="userSpaceOnUse"><stop class="ax9s6wi3k"/><stop offset="1" class="bd-canb4c"/></linearGradient><linearGradient id="iaHTpCd" x1="22.416" x2="23.228" y1="29.276" y2="29.26" gradientUnits="userSpaceOnUse"><stop offset=".254" class="ja44woagt"/><stop offset="1" class="x16kbobeb"/></linearGradient><linearGradient id="iDEHmlb" x1="7.144" x2="9.538" y1="28.157" y2="28.157" gradientUnits="userSpaceOnUse"><stop class="zs64g5eig"/><stop offset="1" class="fczdhwb3o"/></linearGradient><linearGradient id="i1qvtFr" x1="18.064" x2="20.86" y1="18.384" y2="18.384" gradientUnits="userSpaceOnUse"><stop class="ryydajfhb"/><stop offset=".371" class="ub4gkwbqs"/></linearGradient><linearGradient id="iye3gQe" x1="13.954" x2="11.157" y1="18.384" y2="18.384" gradientUnits="userSpaceOnUse"><stop class="ik2h44jfq"/><stop offset=".639" class="rd-uo94io"/></linearGradient><linearGradient id="iwwrY5c" x1="12.119" x2="12.681" y1="16.948" y2="17.166" gradientUnits="userSpaceOnUse"><stop class="krazlsbaw"/><stop offset="1" class="cd-mikbpl"/></linearGradient><linearGradient id="iXxcGoc" x1="21.853" x2="17.478" y1="24.807" y2="24.807" gradientUnits="userSpaceOnUse"><stop class="f30052bab"/><stop offset="1" class="r4xas9tfi"/></linearGradient><linearGradient id="iQyMHce" x1="10.324" x2="10.752" y1="23.588" y2="23.588" gradientUnits="userSpaceOnUse"><stop class="k_snybcwj"/><stop offset="1" class="a_s1o9xch"/></linearGradient><linearGradient id="iedzVjb" x1="12.509" x2="8.572" y1="28.026" y2="28.026" gradientUnits="userSpaceOnUse"><stop class="dsswvpb9g"/><stop offset="1" class="w9napxb6c"/><stop offset="1" class="wi-1d9bnt"/></linearGradient><linearGradient id="inKEYud" x1="22.478" x2="18.664" y1="27.619" y2="27.619" gradientUnits="userSpaceOnUse"><stop class="u44n60b3i"/><stop offset="1" class="w9napxb6c"/><stop offset="1" class="g0o1xozbh"/></linearGradient><linearGradient id="iivjUXQ" x1="10.791" x2="21.664" y1="21.963" y2="21.963" gradientUnits="userSpaceOnUse"><stop class="auppp8bgz"/><stop offset="1" class="auppp8bgz"/></linearGradient><linearGradient id="isD866c" x1="16.41" x2="16.41" y1="21.026" y2="22.198" gradientUnits="userSpaceOnUse"><stop class="alxt_0b7l"/><stop offset="1" class="ux8m6ubss"/></linearGradient><linearGradient id="i4Vj05r" x1="19.033" x2="20.861" y1="26.127" y2="26.127" gradientUnits="userSpaceOnUse"><stop class="d2n_fybiv"/><stop offset="1" class="dt611t2tz"/></linearGradient><linearGradient id="iCcunCn" x1="12.942" x2="10.744" y1="26.127" y2="26.127" gradientUnits="userSpaceOnUse"><stop class="e-u8dsp0m"/><stop offset="1" class="iv0ea6b5j"/></linearGradient><linearGradient id="iIlTMjz" x1="19.033" x2="20.861" y1="27.393" y2="27.393" gradientUnits="userSpaceOnUse"><stop class="d2n_fybiv"/><stop offset="1" class="dt611t2tz"/></linearGradient><linearGradient id="ioVA5me" x1="12.942" x2="10.744" y1="27.393" y2="27.393" gradientUnits="userSpaceOnUse"><stop class="e-u8dsp0m"/><stop offset="1" class="iv0ea6b5j"/></linearGradient><linearGradient id="ijyyeOc" x1="19.033" x2="20.861" y1="28.658" y2="28.658" gradientUnits="userSpaceOnUse"><stop class="d2n_fybiv"/><stop offset="1" class="dt611t2tz"/></linearGradient><linearGradient id="ij8ML3d" x1="12.942" x2="10.744" y1="28.658" y2="28.658" gradientUnits="userSpaceOnUse"><stop class="e-u8dsp0m"/><stop offset="1" class="iv0ea6b5j"/></linearGradient><linearGradient id="iiOtYfN" x1="9.685" x2="12.658" y1="10.807" y2="10.807" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="iFw3bJb" x1="16.009" x2="16.009" y1="12.767" y2="10.073" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="iQHPAdd" x1="14.958" x2="15.816" y1="12.001" y2="12.106" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="ibfzRBB" x1="16.009" x2="16.009" y1="12.859" y2="12.246" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="iw9aaHc" x1="16.087" x2="16.087" y1="12.833" y2="12.693" gradientUnits="userSpaceOnUse"><stop class="b8os9sbcy"/><stop offset="1" class="e6-lebcyw"/></linearGradient><linearGradient id="iOI3Lld" x1="15.276" x2="15.731" y1="14.343" y2="13.467" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="ivvzTxu" x1="18.981" x2="18.667" y1="10.174" y2="10.367" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iXU9Bvc" x1="14.563" x2="14.248" y1="10.173" y2="10.367" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ikpFD0i" x1="13.104" x2="13.652" y1="4.493" y2="5.773" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient><linearGradient id="i1eJpwb" x1="22.939" x2="16.089" y1="7.067" y2="13.917" gradientUnits="userSpaceOnUse"><stop class="xrqg_7scz"/><stop offset="1" class="nq67yg_fv"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-teacher" /></template>
<style>
.a_s1o9xch {
  stop-color: var(--svg-color--6d6670, #6D6670);
  stop-opacity: 0;
}

.a9dfe182j {
  stop-color: var(--svg-color--d4993e, #D4993E);
}

.abu2lcc5n {
  stop-color: var(--svg-color--ffe134, #FFE134);
  stop-opacity: 0;
}

.ag6fa4z4y {
  stop-color: var(--svg-color--e26b25, #E26B25);
}

.ajxs5ri3z {
  stop-color: var(--svg-color--f3943b, #F3943B);
  stop-opacity: 0;
}

.alxt_0b7l {
  stop-color: var(--svg-color--dcd5e1, #DCD5E1);
}

.anvnien4h {
  d: path("M11.157 21.502c0-.384.311-.695.695-.695h9.812v1.39h-9.812a.695.695 0 0 1-.695-.695");
}

.aoym4l1xy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M3.228 4.403h26.213a.1.1 0 0 1 .1.1v19.585");
}

.as_1moxii {
  d: path("M18.136 9.83c.063.086-.07.19-.222.303c-.151.113-.264.193-.327.108c-.064-.085.007-.246.159-.36c.151-.113.326-.136.39-.05");
}

.auorgtyhp {
  stop-color: var(--svg-color--d6753d, #D6753D);
}

.auppp8bgz {
  stop-color: var(--svg-color--564567, #564567);
}

.ax9s6wi3k {
  stop-color: var(--svg-color--614451, #614451);
}

.b3yosxwqw {
  d: path("M11.092 4.679c.624-.556 1.524-.562 2.03-.472l.403 1.297c-.258-.04-.488.05-.682.235c-.457 1.266-2.031 1.965-2.76 2.155c-.152-1.498-.068-2.256 1.01-3.215");
}

.b4vmzacii {
  stop-color: var(--svg-color--7f6260, #7F6260);
}

.b8os9sbcy {
  stop-color: var(--svg-color--e2802f, #E2802F);
}

.bd-canb4c {
  stop-color: var(--svg-color--614451, #614451);
  stop-opacity: 0;
}

.bta5wpblo {
  d: path("M16.014 15.51c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.btu9i2bec {
  stop-color: var(--svg-color--e37923, #E37923);
}

.cd-mikbpl {
  stop-color: var(--svg-color--6f5048, #6F5048);
  stop-opacity: 0;
}

.cesjesv2y {
  stop-color: var(--svg-color--52396b, #52396B);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crfaaqblp {
  stop-color: var(--svg-color--f49523, #F49523);
  stop-opacity: 0;
}

.cxrlhcc-d {
  stop-color: var(--svg-color--358175, #358175);
  stop-opacity: 0;
}

.cyv1u6bkx {
  d: path("M18.203 9.64a.897.897 0 0 1 .864 1.133h-1.732a.9.9 0 0 1 .868-1.133");
}

.d2n_fybiv {
  stop-color: var(--svg-color--d27619, #D27619);
}

.d9yh9ccdg {
  d: path("m15.625 10.357l-.534 1.707a.542.542 0 0 0 .523.703h.79c.37 0 .632-.357.523-.703l-.534-1.707c-.115-.379-.649-.379-.768 0");
}

.denqa3bda {
  stop-color: var(--svg-color--d77117, #D77117);
  stop-opacity: 0;
}

.dhd2d0b1r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.033 28.58h1.922");
}

.dpv-wxbjb {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
}

.dsswvpb9g {
  stop-color: var(--svg-color--ffd743, #FFD743);
}

.dt611t2tz {
  stop-color: var(--svg-color--d27619, #D27619);
  stop-opacity: 0;
}

.duwob45dr {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
}

.dysvcqzhm {
  d: path("M10.898 9.451h.013l-.01-.266l-.01-.308c.02-.953.576-1.322.813-1.445l.051-.02q.027-.013.052-.02a2.32 2.32 0 0 0 1.195-1.241l.082-.195a.265.265 0 0 1 .464-.051a3.88 3.88 0 0 0 3.204 1.68h3.234c.181 0 1.087.089 1.141 1.34l-.12 3.086c-.123 2.815-2.321 4.706-5.005 4.706s-4.882-1.89-5.006-4.706z");
}

.e-u8dsp0m {
  stop-color: var(--svg-color--ffb60a, #FFB60A);
}

.e0lgwbeaw {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
}

.e1bvu4b8w {
  stop-color: var(--svg-color--d78248, #D78248);
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.e6-lebcyw {
  stop-color: var(--svg-color--e2802f, #E2802F);
  stop-opacity: 0;
}

.eajhqmsyf {
  fill: var(--svg-color--8a004f, #8A004F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.604 13.254a.205.205 0 0 0-.248.043a.2.2 0 0 0-.021.249a1.99 1.99 0 0 0 3.348 0a.2.2 0 0 0-.022-.25a.206.206 0 0 0-.247-.042c-.407.216-.885.34-1.405.34c-.516 0-1-.124-1.405-.34Z");
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.ehjghj3fe {
  stop-color: var(--svg-color--f49523, #F49523);
}

.ei_98vf4e {
  stop-color: var(--svg-color--7a5d72, #7A5D72);
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.eseh3ccnk {
  d: path("m19.313 16.01l1.4 2.988c.09.19-.05.41-.26.41l-.963-.265c-.422-.105-.436.277-.276.437l1.36 1.56c.26.26.36.65.23 1l-2.74 7.87V15.588z");
}

.esh4v5qtq {
  stop-color: var(--svg-color--ee971b, #EE971B);
  stop-opacity: 0;
}

.esx41hbqq {
  stop-color: var(--svg-color--cba140, #CBA140);
}

.f30052bab {
  stop-color: var(--svg-color--e9266f, #E9266F);
}

.f902gfhfn {
  stop-color: var(--svg-color--ffda39, #FFDA39);
}

.fczdhwb3o {
  stop-color: var(--svg-color--4f2e37, #4F2E37);
}

.fgkcx3bbf {
  stop-color: var(--svg-color--481e13, #481E13);
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.fkdj3ejgt {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
}

.flgk3ob-g {
  d: path("M13.815 9.64a.897.897 0 0 0-.864 1.133h1.732a1 1 0 0 0 .032-.236a.903.903 0 0 0-.9-.896");
}

.ft5dv1b6b {
  fill: none;
}

.g043vp3zf {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
}

.g0o1xozbh {
  stop-color: var(--svg-color--ffab30, #FFAB30);
}

.g51venbyw {
  d: path("M22.057 23.118c.55 0 1 .45 1 1v2.29h-2v-2.29c0-.55.44-1 1-1");
}

.gbpc14bxe {
  stop-color: var(--svg-color--ffe337, #FFE337);
  stop-opacity: 0;
}

.gc9m5mdrr {
  d: path("M18.664 25.38a.81.81 0 0 0 .303.667a.8.8 0 0 0-.303.636c0 .267.116.503.303.637a.8.8 0 0 0-.303.636c0 .267.116.504.303.637a.84.84 0 0 0-.303.668c.01.42.32.749.685.749h2.935c.426 0 .773-.4.773-.893v-3.604c0-.493-.347-.894-.773-.894H19.44a.776.776 0 0 0-.777.76");
}

.gchclybws {
  stop-color: var(--svg-color--feae1b, #FEAE1B);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gihkuibxq {
  stop-color: var(--svg-color--4a1d14, #4A1D14);
  stop-opacity: 0;
}

.gsggv-b-p {
  stop-color: var(--svg-color--f09429, #F09429);
  stop-opacity: 0;
}

.gtmeeib0y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.033 27.315h1.922");
}

.h-hceo6qn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.104 4.148c.024.244.236 1.162.548 1.718");
}

.h11_utkon {
  stop-color: var(--svg-color--b96201, #B96201);
}

.h55048b_d {
  stop-color: var(--svg-color--b36c17, #B36C17);
}

.ha2cq84sa {
  stop-color: var(--svg-color--c9681c, #C9681C);
}

.hkhuycurt {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.149 8.256c-.324-.079-1.13-.04-1.668.346");
}

.hottnizrg {
  stop-color: var(--svg-color--ffd336, #FFD336);
  stop-opacity: 0;
}

.hpdf2p89l {
  stop-color: var(--svg-color--25585f, #25585F);
}

.ik2h44jfq {
  stop-color: var(--svg-color--744036, #744036);
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.iv0ea6b5j {
  stop-color: var(--svg-color--ffb60a, #FFB60A);
  stop-opacity: 0;
}

.ivh818b_e {
  fill: var(--svg-color--bd4f26, #BD4F26);
  fill-rule: evenodd;
  d: path("m19.757 8.394l-.138.231za.27.27 0 0 1-.277.461l-.004-.002l-.022-.012l-.092-.047c-.081-.039-.2-.09-.344-.135a2.3 2.3 0 0 0-1.077-.093a.27.27 0 0 1-.093-.53c.515-.091.992 0 1.334.11a3.3 3.3 0 0 1 .561.239l.01.005l.002.002z");
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.j_sh0abos {
  fill: var(--svg-color--000, #000);
  d: path("M14.328 10.537a.51.51 0 0 0-.513-.513a.51.51 0 0 0-.457.75h.909a.5.5 0 0 0 .061-.237");
}

.ja44woagt {
  stop-color: var(--svg-color--4f2737, #4F2737);
}

.jb7dwha5m {
  d: path("M15.403 2.894c-1.138-.251-2.358.96-2.476 1.38c1.55 3.637 3.928 3.29 6.567 2.997c1.58-.175 1.751.545 1.886.893c-.438-4.075-3.384-4.698-5.977-5.27");
}

.jdxiygy-f {
  d: path("M20.858 12.336a1.616 1.616 0 1 0 0-3.233a1.616 1.616 0 0 0 0 3.233");
}

.jgqht7b_r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.033 26.05h1.922");
}

.jh40i5bvl {
  stop-color: var(--svg-color--ffda39, #FFDA39);
  stop-opacity: 0;
}

.jij-d9bro {
  stop-color: var(--svg-color--d78248, #D78248);
  stop-opacity: 0;
}

.jpk8o_7uj {
  stop-color: var(--svg-color--f69c5b, #F69C5B);
}

.k_mhzeg6j {
  d: path("M21.664 22.995v-2.286c0-.388-.36-.699-.81-.699h-8.659c-1.041 0-1.871.73-1.871 1.622c0 .752.61 1.362 1.363 1.362z");
}

.k_snybcwj {
  stop-color: var(--svg-color--6d6670, #6D6670);
}

.k2he7fbdg {
  d: path("M15.994 18.24c-1.14 0-2.06-.92-2.06-2.06v-2.56c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
}

.k4ucljb_r {
  d: path("M9.304 30.01V17.765a10.98 10.98 0 0 0-4.32 8.745v3.5z");
}

.k4uqm-3qp {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.41 9.368c.657 0 1.21.452 1.362 1.063a.275.275 0 0 1-.27.343h-2.24a.23.23 0 0 1-.229-.273a1.404 1.404 0 0 1 1.377-1.133");
}

.kdpvi8bty {
  d: path("m12.664 16.026l-1.36 2.973c-.09.19.05.41.26.41l.963-.266c.422-.105.437.277.277.437l-1.36 1.56c-.26.26-.36.65-.23 1l2.74 7.87V15.59z");
}

.kiracnbim {
  stop-color: var(--svg-color--875955, #875955);
}

.kl3ja4pbq {
  stop-color: var(--svg-color--90645e, #90645E);
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.kpf8h5ohf {
  stop-color: var(--svg-color--db6009, #DB6009);
  stop-opacity: 0;
}

.kpqm10zsn {
  stop-color: var(--svg-color--c07518, #C07518);
}

.krazlsbaw {
  stop-color: var(--svg-color--6f5048, #6F5048);
}

.kyonfdcsy {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M20.858 11.799a1.079 1.079 0 1 0 0-2.158a1.079 1.079 0 0 0 0 2.158");
}

.l0olepbgo {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.607 9.368c-.656 0-1.21.452-1.361 1.063a.275.275 0 0 0 .269.343h2.24c.144 0 .258-.13.23-.273a1.41 1.41 0 0 0-1.378-1.133");
}

.la8u06l5z {
  d: path("M11.302 12.336a1.616 1.616 0 1 0 0-3.233a1.616 1.616 0 0 0 0 3.233");
}

.lcrdwk1fj {
  stop-color: var(--svg-color--c9641b, #C9641B);
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lhzq6sthb {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.862 10.148c-.267-.469-.672-.84-1.545-.84c-.382 0-.75.106-1.077.371c-.27.218-.234.497-.025.602l.559.319c.654-.212 1.378-.24 2.088-.452");
}

.lj0sm1b7l {
  stop-color: var(--svg-color--efbe85, #EFBE85);
}

.m23un_v9r {
  d: path("M3.014 24V5.01h25.99V24z");
}

.m45oyzb-o {
  stop-color: var(--svg-color--eb9235, #EB9235);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.mtw9cmojx {
  d: path("M19 10.418a.84.84 0 0 0-.232-.464l-.26.286l.117.23z");
}

.n-73b991b {
  fill-rule: evenodd;
  d: path("M12.418 30.01v-8.406h-2.094v8.406z");
}

.n02eidbqs {
  fill-rule: evenodd;
  d: path("M23.226 12.136a3.25 3.25 0 0 0 .326-1.434c0-.47-.097-.91-.27-1.311h.005a3 3 0 0 0-.282-.515l-.002-.004a3.25 3.25 0 0 1-.529-1.779v-.01A3.315 3.315 0 0 0 19.16 3.77a.54.54 0 0 1-.457-.234a3.32 3.32 0 0 0-2.694-1.382a3.32 3.32 0 0 0-2.694 1.382a.57.57 0 0 1-.458.234l-.085.001a3.315 3.315 0 0 0-3.229 3.313v.01c0 .63-.183 1.25-.529 1.78l-.002.003a3.31 3.31 0 0 0-.221 3.26a.52.52 0 0 1 0 .457a3.228 3.228 0 0 0 2.907 4.646h8.621a3.23 3.23 0 0 0 3.233-3.233a3.3 3.3 0 0 0-.326-1.413a.52.52 0 0 1 0-.457M10.911 9.45h-.013l1.204 2.366c.124 2.816 1.223 0 3.907 0c2.683 0 3.853 3.134 3.977.319l1.141-3.212c-.054-1.25-.96-1.338-1.14-1.338h-3.235a3.88 3.88 0 0 1-3.204-1.681a.265.265 0 0 0-.464.051l-.082.195c-.227.564-.66.994-1.195 1.24q-.024.008-.052.02l-.051.021c-.237.123-.793.492-.814 1.445l.01.308z");
}

.n6p6pxbvb {
  d: path("M20.844 8.682h-3.47c-.3 0-.58.14-.77.37a.64.64 0 0 1-.51.24a.64.64 0 0 1-.51-.24c-.19-.23-.47-.37-.77-.37h-3.48c-.19 0-.34.15-.34.34v.22c0 .11.05.2.13.26c.04.03.07.08.07.13v1.1c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91v-.61c.01-.2.17-.35.37-.35s.36.16.37.36v.6c0 1.05.85 1.91 1.91 1.91h.71c1.05 0 1.91-.85 1.91-1.91v-1.11c0-.05.02-.1.06-.13c.08-.06.13-.16.13-.26v-.21c0-.19-.15-.34-.34-.34m-5.46 1.95c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65v-.72c0-.49.39-.88.88-.88h2.08c.49 0 .89.39.89.88zm5.28 0c0 .91-.74 1.65-1.65 1.65h-.55c-.91 0-1.65-.74-1.65-1.65v-.72c0-.49.39-.88.88-.88h2.09c.49 0 .88.39.88.88z");
}

.n8mbjcbow {
  stop-color: var(--svg-color--875955, #875955);
  stop-opacity: 0;
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.nfwti5bbx {
  stop-color: var(--svg-color--509245, #509245);
}

.nq67yg_fv {
  stop-color: var(--svg-color--3c2850, #3C2850);
}

.nria2ku7r {
  stop-color: var(--svg-color--d8772c, #D8772C);
}

.nyj5kteen {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.942 28.58H11.02");
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.oa_0r4bea {
  stop-color: var(--svg-color--dd9c2b, #DD9C2B);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.od6_koblh {
  stop-color: var(--svg-color--358175, #358175);
}

.ox51r5bse {
  stop-color: var(--svg-color--61332b, #61332B);
  stop-opacity: 0;
}

.p1xq25bjq {
  stop-color: var(--svg-color--d76a18, #D76A18);
  stop-opacity: 0;
}

.p33y7xmqq {
  stop-color: var(--svg-color--894e01, #894E01);
}

.p4wkjrbae {
  stop-color: var(--svg-color--c9681c, #C9681C);
  stop-opacity: 0;
}

.p8v5p6bjo {
  cx: 13.543px;
  cy: 10.024px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.391px;
  ry: 0.198px;
}

.pb_rvfc5z {
  stop-color: var(--svg-color--ffe842, #FFE842);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.prpkwxers {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.957 8.256c.324-.079 1.13-.04 1.668.346");
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qibo5-0bn {
  d: path("M13.353 25.38a.81.81 0 0 1-.302.667a.8.8 0 0 1 .302.636a.77.77 0 0 1-.302.637a.8.8 0 0 1 .302.636a.77.77 0 0 1-.302.637c.187.144.302.39.302.668c-.009.42-.32.749-.685.749H9.734c-.427 0-.774-.4-.774-.893v-3.604c0-.493.347-.894.774-.894h2.842c.475 0 .77.39.777.76");
}

.qir_1cb0f {
  stop-color: var(--svg-color--e26b25, #E26B25);
  stop-opacity: 0;
}

.qna-_2b3m {
  stop-color: var(--svg-color--764747, #764747);
}

.qo_nu3b1v {
  stop-color: var(--svg-color--5d3841, #5D3841);
  stop-opacity: 0;
}

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwjswe-rp {
  stop-color: var(--svg-color--e48538, #E48538);
  stop-opacity: 0;
}

.r4c-t7bme {
  stop-color: var(--svg-color--44803d, #44803D);
}

.r4xas9tfi {
  stop-color: var(--svg-color--bf1b74, #BF1B74);
}

.rd-uo94io {
  stop-color: var(--svg-color--72433e, #72433E);
}

.rekkd-b6b {
  d: path("M22.684 30.01V17.765a10.98 10.98 0 0 1 4.32 8.745v3.5z");
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.rkna2zbug {
  stop-color: var(--svg-color--61332b, #61332B);
}

.rm4x5nmvd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.942 26.05H11.02");
}

.rqxi6yb_m {
  stop-color: var(--svg-color--7c5a5a, #7C5A5A);
}

.ryydajfhb {
  stop-color: var(--svg-color--613327, #613327);
}

.s3t3owbgt {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
  stop-opacity: 0;
}

.s599a1bap {
  d: path("M29.004 24H3.014V5.01l-.92-.68c-.05.09-.08.2-.08.3v19.74c0 .35.28.62.62.62h26.74c.24 0 .44-.13.55-.33z");
}

.scqmvqbyx {
  d: path("M10.324 21.89v8.12h11.34v-9.19c0-.45-.36-.81-.81-.81h-8.64c-1.05-.01-1.89.84-1.89 1.88");
}

.sihp1fb9k {
  stop-color: var(--svg-color--bc7b53, #BC7B53);
  stop-opacity: 0;
}

.sm6solb0h {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.136 9.83c.063.086-.07.19-.222.303c-.151.113-.264.193-.327.108c-.064-.085.007-.246.159-.36c.151-.113.326-.136.39-.05");
}

.sq_vp-4np {
  d: path("M29.384 25H2.634c-.34 0-.62-.28-.62-.62V4.63c0-.34.28-.62.62-.62h26.74c.35 0 .62.28.62.62v19.74a.61.61 0 0 1-.61.63");
}

.sufhn4bec {
  stop-color: var(--svg-color--db6009, #DB6009);
}

.sxoxd_kke {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
  stop-opacity: 0;
}

.t6j-eenhm {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M11.321 11.799a1.079 1.079 0 1 0 0-2.158a1.079 1.079 0 0 0 0 2.158");
}

.tgqxysbgm {
  stop-color: var(--svg-color--d76a18, #D76A18);
}

.toyl6td3i {
  fill: var(--svg-color--bd4f26, #BD4F26);
  d: path("m12.596 8.854l-.005.002a.27.27 0 0 1-.277-.462h.002l.003-.003l.01-.005a2 2 0 0 1 .148-.077c.1-.047.24-.108.412-.163c.342-.109.82-.2 1.335-.11a.27.27 0 0 1-.094.531c-.4-.07-.785 0-1.077.093a3 3 0 0 0-.457.194");
}

.tp0kp63lp {
  stop-color: var(--svg-color--bfaaba, #BFAABA);
}

.tt6zhpmrj {
  d: path("M20.858 11.799a1.079 1.079 0 1 0 0-2.158a1.079 1.079 0 0 0 0 2.158");
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.u1egy7b7t {
  stop-color: var(--svg-color--e8ac81, #E8AC81);
}

.u44n60b3i {
  stop-color: var(--svg-color--ffe243, #FFE243);
}

.ub4gkwbqs {
  stop-color: var(--svg-color--764440, #764440);
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.uqvywhymc {
  stop-color: var(--svg-color--8a5d57, #8A5D57);
}

.us4ivbb3t {
  stop-color: var(--svg-color--9a6d66, #9A6D66);
}

.ux8m6ubss {
  stop-color: var(--svg-color--b2acb9, #B2ACB9);
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v61l3jbat {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
  stop-opacity: 0;
}

.v8d-6__pr {
  fill: var(--svg-color--513358, #513358);
  fill-rule: evenodd;
  d: path("M12.418 30.01v-8.406h-2.094v8.406z");
}

.v9rq5jjti {
  stop-color: var(--svg-color--cba140, #CBA140);
  stop-opacity: 0;
}

.vsluyubzo {
  stop-color: var(--svg-color--f8a322, #F8A322);
  stop-opacity: 0;
}

.vuu7bk4vv {
  stop-color: var(--svg-color--735451, #735451);
}

.w_th7pbmt {
  d: path("M11.321 11.799a1.079 1.079 0 1 0 0-2.158a1.079 1.079 0 0 0 0 2.158");
}

.w2e_edyjl {
  stop-color: var(--svg-color--f09429, #F09429);
}

.w3-vy4c8j {
  stop-color: var(--svg-color--e38923, #E38923);
}

.w72oynbwi {
  stop-color: var(--svg-color--e38923, #E38923);
  stop-opacity: 0;
}

.w9napxb6c {
  stop-color: var(--svg-color--f5891f, #F5891F);
}

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.wec460bot {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m15.614 10.496l-.686 1.708a.542.542 0 0 0 .523.702h.79c.37 0 .631-.357.523-.702l-.534-1.708c-.115-.378-.496-.378-.616 0");
}

.wfc059byj {
  stop-color: var(--svg-color--25585f, #25585F);
  stop-opacity: 0;
}

.wi-1d9bnt {
  stop-color: var(--svg-color--f19e2d, #F19E2D);
}

.wn11gcx8f {
  stop-color: var(--svg-color--f1b58b, #F1B58B);
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.x05md6_2b {
  stop-color: var(--svg-color--d97c39, #D97C39);
}

.x16kbobeb {
  stop-color: var(--svg-color--4f2737, #4F2737);
  stop-opacity: 0;
}

.xerarbgsl {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.156 10.148c.267-.469.672-.84 1.544-.84c.382 0 .75.106 1.078.371c.27.218.234.497.025.602l-.559.319c-.655-.212-1.379-.24-2.088-.452");
}

.xpfqoet5v {
  d: path("M9.96 23.11c-.55 0-1 .45-1 1v2.29h2v-2.29c0-.55-.44-1-1-1");
}

.xrqg_7scz {
  stop-color: var(--svg-color--52336d, #52336D);
}

.xtl7t4edr {
  stop-color: var(--svg-color--d18f7b, #D18F7B);
}

.xv5mlgynl {
  d: path("M14.633 10.43c0-.288-.235-.481-.299-.54l-.29.28l.179.363z");
}

.y_oifu3xm {
  fill: var(--svg-color--000, #000);
  d: path("M17.69 10.537a.51.51 0 0 1 .513-.513a.51.51 0 0 1 .456.75h-.909a.47.47 0 0 1-.06-.237");
}

.y1ij6ubnw {
  stop-color: var(--svg-color--ffd59c, #FFD59C);
}

.y1kgfac6n {
  stop-color: var(--svg-color--8a5d57, #8A5D57);
  stop-opacity: 0;
}

.y7n0ymbzx {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
  stop-opacity: 0;
}

.ybzr6jbff {
  stop-color: var(--svg-color--90645e, #90645E);
  stop-opacity: 0;
}

.ydne4ly1n {
  stop-color: var(--svg-color--df9a32, #DF9A32);
}

.yehxt3bls {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
}

.yg2bpcbyf {
  cx: 13.543px;
  cy: 10.024px;
  rx: 0.391px;
  ry: 0.198px;
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.yr1vjkbzu {
  stop-color: var(--svg-color--ffd93c, #FFD93C);
}

.yvo_l_bkn {
  stop-color: var(--svg-color--9a6d66, #9A6D66);
  stop-opacity: 0;
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.z-gx2rb2w {
  stop-color: var(--svg-color--ffe337, #FFE337);
}

.zcr5gg5_s {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.942 27.315H11.02");
}

.zk02wzc7y {
  d: path("M18.064 14.744h-4.11V30.01h4.11z");
}

.zlcjw7bgf {
  stop-color: var(--svg-color--61342d, #61342D);
}

.zobbewbqd {
  stop-color: var(--svg-color--52396b, #52396B);
}

.zs64g5eig {
  stop-color: var(--svg-color--623d44, #623D44);
}

</style>
