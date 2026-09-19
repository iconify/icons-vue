<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i55neXb)" transform="rotate(-27.486 7.73 6.851)" class="m0j2adc3x"/><path fill="url(#iRPaY7d)" transform="rotate(-27.486 7.73 6.851)" class="m0j2adc3x"/><path fill="url(#ieAIo3c)" transform="rotate(-27.486 7.73 6.851)" class="m0j2adc3x"/><path fill="url(#iI6EPWb)" transform="rotate(-27.486 7.73 6.851)" class="m0j2adc3x"/><path fill="url(#i12Tiac)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><path fill="url(#iedrh3b)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><path fill="url(#iBORENc)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><path fill="url(#idX16ke)" transform="scale(-1 1)rotate(-27.486 1.85 53.136)" class="pnmas4b0d"/><g filter="url(#ihqUQxz)"><path fill="url(#iVAnGZb)" class="q1wg51bmi"/><path fill="url(#i0AhJLc)" class="q1wg51bmi"/><path fill="url(#i8igjWE)" class="q1wg51bmi"/><path fill="url(#il5AC0d)" class="q1wg51bmi"/></g><g filter="url(#iu282hZ)"><rect fill="url(#iE3hHec)" class="uywq_y1iv"/><rect fill="url(#i1HNLPr)" class="uywq_y1iv"/></g><g filter="url(#iy6VZjW)"><path stroke="url(#ibRzype)" class="ijj045bhz"/></g><path fill="url(#i8au7wd)" class="g4offrb0h"/><path fill="url(#iHoWnVL)" class="g4offrb0h"/><path fill="url(#iCij2sz)" class="nm-q8ebbk"/><path fill="url(#iBlABrf)" class="nm-q8ebbk"/><path fill="url(#iF7g9qc)" class="z0ggixb3q"/><path fill="url(#iDp8kCc)" class="z0ggixb3q"/><path fill="url(#ifHDS2c)" class="tzfcre5-h"/><path fill="url(#ihsWgme)" class="tzfcre5-h"/><circle fill="url(#iyiTEAb)" class="gknucfb8h"/><circle fill="url(#iyEw6wd)" class="gknucfb8h"/><path fill="url(#iANYCKO)" class="y0nqeezxq"/><path fill="url(#ilM1Iye)" class="y0nqeezxq"/><path fill="url(#iGf76ye)" class="l2at7otgu"/><path fill="url(#i383xNc)" class="l2at7otgu"/><path fill="url(#i1NoS8b)" class="ufmuzl7ni"/><path fill="url(#ij9Wvnd)" class="ufmuzl7ni"/><path fill="url(#iCBlCAc)" class="rh3jx3c9i"/><path fill="url(#inej4re)" class="rh3jx3c9i"/><circle fill="url(#is0pJed)" transform="matrix(-1 0 0 1 21.398 7)" class="e4y-1lbum"/><circle fill="url(#isdBRue)" transform="matrix(-1 0 0 1 21.398 7)" class="e4y-1lbum"/><g filter="url(#iv1cGJb)"><path fill="url(#ilmwlid)" class="em3ofwhyw"/><path fill="url(#iSuCE7b)" class="em3ofwhyw"/><path fill="url(#iTnerGc)" class="em3ofwhyw"/></g><g filter="url(#iV9UqFb)"><path fill="url(#ii9TU6b)" class="qno0gyhtd"/><path fill="url(#iAW9NPa)" class="qno0gyhtd"/><path fill="url(#irsbW7b)" class="qno0gyhtd"/></g><g filter="url(#iVXJL9v)"><path fill="url(#iMd3cGY)" class="tphhgybtp"/><path fill="url(#iKoLy8d)" class="tphhgybtp"/></g><g filter="url(#i2TeMOd)"><path fill="url(#ipt2RNb)" class="x9t-2zb_r"/><path fill="url(#ijEmnZt)" class="x9t-2zb_r"/><path fill="url(#iqv6bwe)" class="x9t-2zb_r"/></g><g filter="url(#iR4Dk3y)"><path fill="url(#i1fW1XY)" class="g5fg-5cgy"/><path fill="url(#iL5td6D)" class="g5fg-5cgy"/></g><g filter="url(#iv50Oad)"><path fill="url(#ihiVjwC)" class="uv_bhvydh"/></g><g filter="url(#iYbOytC)"><path fill="url(#imrVfMc)" class="u6_y93pge"/><path fill="url(#iID6PAd)" class="u6_y93pge"/></g><g filter="url(#iJmirTr)"><path fill="url(#iQ3Ldac)" class="qd4tofb7u"/></g><g filter="url(#isJS4Vc)"><path fill="url(#it1w2ie)" class="nvirpp9bq"/></g><g filter="url(#iJh6mde)"><path fill="url(#ixKrPfb)" class="kv3enpo0a"/><path fill="url(#iIOJZDd)" class="kv3enpo0a"/></g><g filter="url(#iJl9oDb)"><path fill="url(#imGINwe)" class="fzjqedceo"/></g><g filter="url(#ixvxaGN)"><path fill="url(#iI0yU5b)" class="rc5fpablb"/></g><g filter="url(#iGEoWUc)"><path fill="url(#i7YLZNB)" clip-rule="evenodd" class="rxm6nppqt"/></g><path fill="url(#iYiFlDd)" class="v60d8yb_v"/><path fill="url(#izPqLzb)" class="pgalr_bqp"/><g filter="url(#ir9jDub)"><path class="bll85w0ed"/></g><g filter="url(#iVOtLmd)"><path class="k49s7u2jw"/></g><g filter="url(#iijfnXe)"><path fill="url(#ioUPaxe)" class="przpgcbzb"/></g><path fill="url(#iNavaOb)" class="przpgcbzb"/><g filter="url(#ifFLyrc)"><path class="s7a934b5m"/></g><g filter="url(#igGm3ka)"><path class="c-x9-vskh"/><path fill="url(#itADyQb)" class="jxkz5w5ce"/><path fill="url(#iCXVQzb)" class="jxkz5w5ce"/><path fill="url(#inYgIoc)" class="jxkz5w5ce"/></g><path class="oxjnikb3r"/><g filter="url(#iknBTSc)"><path class="u8xde_fso"/></g><g filter="url(#ipU5Yxd)"><path class="xgvxkebfh"/></g><path class="ctdwkio9o"/><path fill="url(#iVYJNFb)" class="oge6r-buh"/><path class="im4wg0bzf"/><g filter="url(#ilHwMQe)"><path class="styss3bew"/><path fill="url(#iDryAbb)" class="c-95a726o"/></g><g filter="url(#iqjF6he)"><path fill="url(#ibJIxKd)" class="nkc4sz_mu"/></g><path class="lghqvdpyh"/><path fill="url(#ilvtEAb)" class="jxo3ryqpx"/><path class="sqq3pyb6i"/><g filter="url(#iU0eRZc)"><path fill="url(#idmLNbd)" class="f3sav0_om"/></g><g filter="url(#ilVOaic)"><ellipse transform="rotate(-27.914 14.792 12.913)" class="i9ptfsj3a"/><ellipse fill="url(#iqEZLAi)" transform="rotate(-27.914 14.792 12.913)" class="kiedr_brj"/></g><g filter="url(#iryM5Hc)"><path fill="url(#iW26kve)" class="atyjoz1aa"/></g><g filter="url(#iyhY8vd)"><path class="b0fux9bsc"/><path fill="url(#ihbBhGd)" class="pxw0zzedl"/></g><path class="hg-g6h4_r"/><g filter="url(#iUcEyhE)"><path class="dssvo9bbk"/></g><path class="q8lf5_6yk"/><g filter="url(#iC7iAic)"><path class="vej6r8a3c"/></g><defs><radialGradient id="i55neXb" cx="0" cy="0" r="1" gradientTransform="rotate(90.019 -.557 10.368)scale(4.75464 1.72872)" gradientUnits="userSpaceOnUse"><stop class="g2y7heb1k"/><stop offset="1" class="xukae21xj"/></radialGradient><radialGradient id="ieAIo3c" cx="0" cy="0" r="1" gradientTransform="matrix(-.81736 1.73031 -3.31873 -1.5677 10.181 7.328)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="zx13l8w6l"/><stop offset="1" class="t07n6xojw"/></radialGradient><radialGradient id="iI6EPWb" cx="0" cy="0" r="1" gradientTransform="rotate(-176.149 5.36 6.832)scale(1.28611 1.19239)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="qf2r2ccba"/><stop offset="1" class="uo2e3-sou"/></radialGradient><radialGradient id="i12Tiac" cx="0" cy="0" r="1" gradientTransform="rotate(90.019 -.997 3.08)scale(4.75464 1.72872)" gradientUnits="userSpaceOnUse"><stop class="g2y7heb1k"/><stop offset="1" class="xukae21xj"/></radialGradient><radialGradient id="iBORENc" cx="0" cy="0" r="1" gradientTransform="matrix(-.81736 1.73031 -3.31873 -1.5677 2.452 .476)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="zx13l8w6l"/><stop offset="1" class="t07n6xojw"/></radialGradient><radialGradient id="idX16ke" cx="0" cy="0" r="1" gradientTransform="rotate(-176.149 1.38 3.537)scale(1.28611 1.19239)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="qf2r2ccba"/><stop offset="1" class="uo2e3-sou"/></radialGradient><radialGradient id="iVAnGZb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.98437 -8.78125 0 17.375 21.945)" gradientUnits="userSpaceOnUse"><stop offset=".165" class="fmwe_9bnp"/><stop offset="1" class="rcnz-20vq"/></radialGradient><radialGradient id="il5AC0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .25 -6.76923 0 17.938 21.945)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="vtfzq1zlw"/><stop offset="1" class="utuf8geyx"/></radialGradient><radialGradient id="iE3hHec" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.1875 -18 0 17.781 5.695)" gradientUnits="userSpaceOnUse"><stop offset=".443" class="id87reb_m"/><stop offset="1" class="htmlfhblq"/></radialGradient><radialGradient id="i1HNLPr" cx="0" cy="0" r="1" gradientTransform="matrix(.25781 .9375 -1.66543 .458 8.96 6.273)" gradientUnits="userSpaceOnUse"><stop offset=".405" class="c0s8udrlx"/><stop offset="1" class="q46dg-bku"/></radialGradient><radialGradient id="i8au7wd" cx="0" cy="0" r="1" gradientTransform="rotate(176.461 3.991 3.074)scale(.66582 1.05015)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="szuswrb-r"/><stop offset="1" class="sbel2qb8e"/></radialGradient><radialGradient id="iHoWnVL" cx="0" cy="0" r="1" gradientTransform="matrix(-.2132 .05173 -.03984 -.16419 8.083 6.282)" gradientUnits="userSpaceOnUse"><stop class="alb2mybdx"/><stop offset="1" class="spunz4bdn"/></radialGradient><radialGradient id="iCij2sz" cx="0" cy="0" r="1" gradientTransform="matrix(-.70411 .04658 -.0787 -1.18967 8.863 5.875)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="szuswrb-r"/><stop offset="1" class="sbel2qb8e"/></radialGradient><radialGradient id="iBlABrf" cx="0" cy="0" r="1" gradientTransform="matrix(-.2259 .05875 -.04809 -.18493 8.777 6.312)" gradientUnits="userSpaceOnUse"><stop class="alb2mybdx"/><stop offset="1" class="spunz4bdn"/></radialGradient><radialGradient id="iF7g9qc" cx="0" cy="0" r="1" gradientTransform="rotate(176.126 5.03 3.12)scale(.67032 1.15903)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="szuswrb-r"/><stop offset="1" class="sbel2qb8e"/></radialGradient><radialGradient id="iDp8kCc" cx="0" cy="0" r="1" gradientTransform="matrix(-.21457 .05712 -.04771 -.17925 10.179 6.32)" gradientUnits="userSpaceOnUse"><stop class="alb2mybdx"/><stop offset="1" class="spunz4bdn"/></radialGradient><radialGradient id="ifHDS2c" cx="0" cy="0" r="1" gradientTransform="rotate(175.983 4.687 3.116)scale(.70792 1.26809)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="szuswrb-r"/><stop offset="1" class="sbel2qb8e"/></radialGradient><radialGradient id="ihsWgme" cx="0" cy="0" r="1" gradientTransform="matrix(-.22656 .06252 -.05386 -.19519 9.496 6.362)" gradientUnits="userSpaceOnUse"><stop class="alb2mybdx"/><stop offset="1" class="spunz4bdn"/></radialGradient><radialGradient id="iyiTEAb" cx="0" cy="0" r="1" gradientTransform="rotate(134.624 3.957 5.724)scale(.6044)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="svjjs0b3e"/><stop offset=".91" class="umuctbc3u"/></radialGradient><radialGradient id="iyEw6wd" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .21094 -.20725 -.17654 10.827 6.85)" gradientUnits="userSpaceOnUse"><stop class="iqe9e2uud"/><stop offset="1" class="ks97e6bva"/></radialGradient><radialGradient id="iANYCKO" cx="0" cy="0" r="1" gradientTransform="matrix(-.66762 0 0 -1.09544 24.218 5.896)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="qzfufsu3s"/><stop offset="1" class="zw2whl-je"/></radialGradient><radialGradient id="ilM1Iye" cx="0" cy="0" r="1" gradientTransform="rotate(117.929 10.237 10.362)scale(.21624 .19082)" gradientUnits="userSpaceOnUse"><stop class="swlqzkb4o"/><stop offset="1" class="qao3n1bvl"/></radialGradient><radialGradient id="iGf76ye" cx="0" cy="0" r="1" gradientTransform="matrix(-.70736 0 0 -1.24403 23.543 5.875)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="qzfufsu3s"/><stop offset="1" class="zw2whl-je"/></radialGradient><radialGradient id="i383xNc" cx="0" cy="0" r="1" gradientTransform="rotate(116.317 9.834 10.393)scale(.24205 .20513)" gradientUnits="userSpaceOnUse"><stop class="swlqzkb4o"/><stop offset="1" class="qao3n1bvl"/></radialGradient><radialGradient id="i1NoS8b" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 0 0 -1.20947 22.124 5.895)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="qzfufsu3s"/><stop offset="1" class="zw2whl-je"/></radialGradient><radialGradient id="ij9Wvnd" cx="0" cy="0" r="1" gradientTransform="matrix(-.10193 .21094 -.17622 -.08515 22.093 6.198)" gradientUnits="userSpaceOnUse"><stop class="swlqzkb4o"/><stop offset="1" class="qao3n1bvl"/></radialGradient><radialGradient id="iCBlCAc" cx="0" cy="0" r="1" gradientTransform="matrix(-.70944 0 0 -1.32351 22.826 5.896)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="qzfufsu3s"/><stop offset="1" class="zw2whl-je"/></radialGradient><radialGradient id="inej4re" cx="0" cy="0" r="1" gradientTransform="matrix(-.10762 .23083 -.18853 -.0879 22.792 6.229)" gradientUnits="userSpaceOnUse"><stop class="swlqzkb4o"/><stop offset="1" class="qao3n1bvl"/></radialGradient><radialGradient id="is0pJed" cx="0" cy="0" r="1" gradientTransform="rotate(127.213 .238 .266)scale(.65236)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="h27r7g9xr"/><stop offset=".91" class="shek1db6a"/></radialGradient><radialGradient id="isdBRue" cx="0" cy="0" r="1" gradientTransform="matrix(-.06323 .28125 -.28686 -.0645 .462 .182)" gradientUnits="userSpaceOnUse"><stop class="cftjypctq"/><stop offset="1" class="ns732vbyd"/></radialGradient><radialGradient id="ilmwlid" cx="0" cy="0" r="1" gradientTransform="matrix(-6.125 0 0 -11.7203 18.313 18.758)" gradientUnits="userSpaceOnUse"><stop class="cg05ombch"/><stop offset="1" class="i25jr6cdh"/></radialGradient><radialGradient id="iSuCE7b" cx="0" cy="0" r="1" gradientTransform="rotate(77.286 -1.694 16.51)scale(3.83375 5.43507)" gradientUnits="userSpaceOnUse"><stop offset=".102" class="v8rezjblq"/><stop offset="1" class="u1b9dcc6t"/></radialGradient><radialGradient id="iTnerGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.88881 -1.74726 0 19.826 21.256)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="yyr7j8rnv"/><stop offset="1" class="ymbigdcyd"/></radialGradient><radialGradient id="ii9TU6b" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.55078 -.69088 0 6.5 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset="1" class="wpbhksb1v"/></radialGradient><radialGradient id="iMd3cGY" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.13872 -.62832 0 26.294 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset="1" class="wpbhksb1v"/></radialGradient><radialGradient id="ipt2RNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.26953 -1.27419 0 4.074 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset=".72" class="wpbhksb1v"/></radialGradient><radialGradient id="ijEmnZt" cx="0" cy="0" r="1" gradientTransform="matrix(2.48437 0 0 5.55129 2.773 6.883)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="aufvjo_md"/><stop offset="1" class="d2-2pqbwj"/></radialGradient><radialGradient id="i1fW1XY" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.88672 -1.125 0 28.438 6.488)" gradientUnits="userSpaceOnUse"><stop class="i9_a76-ul"/><stop offset=".72" class="wpbhksb1v"/></radialGradient><radialGradient id="iL5td6D" cx="0" cy="0" r="1" gradientTransform="matrix(-2.48437 0 0 -5.55129 29.188 6.883)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="aufvjo_md"/><stop offset="1" class="d2-2pqbwj"/></radialGradient><radialGradient id="iID6PAd" cx="0" cy="0" r="1" gradientTransform="rotate(138.833 2.145 12.111)scale(1.93493 1.5766)" gradientUnits="userSpaceOnUse"><stop class="tn93407hk"/><stop offset="1" class="t7wtrebxf"/></radialGradient><radialGradient id="iQ3Ldac" cx="0" cy="0" r="1" gradientTransform="matrix(-2.84376 2.48436 -2.68024 -3.06799 11.406 27.992)" gradientUnits="userSpaceOnUse"><stop class="hekob1wbk"/><stop offset=".787" class="q-vr2ac-v"/></radialGradient><radialGradient id="iIOJZDd" cx="0" cy="0" r="1" gradientTransform="rotate(129.405 6.729 15.316)scale(1.6175 1.31795)" gradientUnits="userSpaceOnUse"><stop class="tn93407hk"/><stop offset="1" class="t7wtrebxf"/></radialGradient><radialGradient id="imGINwe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.84375 1.53126 -1.60652 -2.9835 23.719 28.54)" gradientUnits="userSpaceOnUse"><stop class="uhxzzsbrl"/><stop offset=".787" class="o6imu6bzx"/></radialGradient><radialGradient id="i7YLZNB" cx="0" cy="0" r="1" gradientTransform="rotate(103.081 4.686 11.78)scale(5.77259 7.80996)" gradientUnits="userSpaceOnUse"><stop offset=".412" class="p-4sfzbzp"/><stop offset="1" class="wvbuym-2v"/></radialGradient><radialGradient id="iYiFlDd" cx="0" cy="0" r="1" gradientTransform="rotate(176.801 6.688 6.631)scale(.70031 .84071)" gradientUnits="userSpaceOnUse"><stop offset=".854" class="xl910dy6z"/><stop offset="1" class="qnghx6b7d"/></radialGradient><radialGradient id="izPqLzb" cx="0" cy="0" r="1" gradientTransform="rotate(102.937 4.204 13.568)scale(1.11341 1.65485)" gradientUnits="userSpaceOnUse"><stop offset=".053" class="aao4qobhm"/><stop offset=".275" class="mwjg5o1vq"/></radialGradient><radialGradient id="ioUPaxe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.65883 0 0 -2.57517 17.094 13.493)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="q-5k2pvgj"/><stop offset="1" class="j9ne5bb7q"/></radialGradient><radialGradient id="iNavaOb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00002 3.52409 -4.33659 -.00002 15.914 12.107)" gradientUnits="userSpaceOnUse"><stop offset=".732" class="mb43on0cd"/><stop offset="1" class="hw9-utbwm"/></radialGradient><radialGradient id="itADyQb" cx="0" cy="0" r="1" gradientTransform="rotate(-105.892 13.336 .743)scale(1.16407 .6661)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="iVYJNFb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4167 -.66104 0 16.91 12.837)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="eijss2b4a"/><stop offset=".787" class="mj--szbch"/></radialGradient><radialGradient id="iDryAbb" cx="0" cy="0" r="1" gradientTransform="matrix(-.10567 -.13617 .18747 -.14547 16.807 12.996)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ilvtEAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4167 -.66104 0 14.916 12.837)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="eijss2b4a"/><stop offset=".787" class="mj--szbch"/></radialGradient><radialGradient id="iqEZLAi" cx="0" cy="0" r="1" gradientTransform="matrix(-.00352 -.2251 .27059 -.00424 14.785 13.057)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iW26kve" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12349 1.33892 -.5517 -.46294 14.65 10.029)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="pf6z3-bjj"/><stop offset="1" class="us2dmwbcp"/></radialGradient><radialGradient id="ihbBhGd" cx="0" cy="0" r="1" gradientTransform="rotate(114.039 5.297 10.282)scale(2.37813 4.54526)" gradientUnits="userSpaceOnUse"><stop offset=".273" class="qao18ac_v"/><stop offset="1" class="y3mq3eusn"/></radialGradient><filter id="ihqUQxz" width="9.5" height="4.284" x="11.172" y="21.645" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.419608 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23318"/></filter><filter id="iu282hZ" width="27.875" height="1.225" x="2.063" y="5.775" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.341176 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23318"/></filter><filter id="iy6VZjW" width="27.781" height=".75" x="2.023" y="6.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23318" stdDeviation=".125"/></filter><filter id="iv1cGJb" width="10.708" height="10.353" x="10.803" y="11.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.196078 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23318"/></filter><filter id="iV9UqFb" width="1.93" height="8.989" x="5.039" y="1.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23318"/></filter><filter id="iVXJL9v" width="1.93" height="8.989" x="24.992" y="1.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23318"/></filter><filter id="i2TeMOd" width="1.93" height="5.973" x="3.109" y="3.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23318"/></filter><filter id="iR4Dk3y" width="1.93" height="5.973" x="26.922" y="3.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23318"/></filter><filter id="iv50Oad" width="3.719" height="6.065" x="8.891" y="22.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.627451 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23318"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.592157 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23318" result="effect2_innerShadow_3987_23318"/></filter><filter id="iYbOytC" width="4.477" height="4.023" x="8.516" y="19.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.192157 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23318"/></filter><filter id="iJmirTr" width="4.833" height="2.114" x="7.039" y="27.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.239216 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23318"/></filter><filter id="isJS4Vc" width="3.719" height="5.564" x="19.922" y="22.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".1"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.627451 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23318"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.592157 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23318" result="effect2_innerShadow_3987_23318"/></filter><filter id="iJh6mde" width="4.477" height="4.023" x="19.539" y="19.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.192157 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23318"/></filter><filter id="iJl9oDb" width="4.833" height="2.114" x="20.159" y="27.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.239216 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23318"/></filter><filter id="ixvxaGN" width=".636" height=".646" x="16.798" y="12.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23318" stdDeviation=".1"/></filter><filter id="iGEoWUc" width="6.864" height="7.364" x="12.482" y="8.142" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.584314 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23318"/></filter><filter id="ir9jDub" width="1.282" height="1.282" x="17.479" y="12.217" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23318" stdDeviation=".075"/></filter><filter id="iVOtLmd" width="1.282" height="1.282" x="13.14" y="12.217" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23318" stdDeviation=".075"/></filter><filter id="iijfnXe" width="4.807" height="4.999" x="13.585" y="10.632" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.45098 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23318"/></filter><filter id="ifFLyrc" width="1.358" height="1.726" x="15.161" y="12.717" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23318" stdDeviation=".125"/></filter><filter id="igGm3ka" width="1.058" height="1.426" x="15.385" y="12.804" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23318" stdDeviation=".05"/></filter><filter id="iknBTSc" width="1.48" height=".587" x="16.236" y="12.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23318"/></filter><filter id="ipU5Yxd" width="1.48" height=".587" x="14.112" y="12.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23318"/></filter><filter id="ilHwMQe" width=".367" height=".326" x="16.571" y="12.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23318" stdDeviation=".025"/></filter><filter id="iqjF6he" width=".323" height=".333" x="17.001" y="12.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23318" stdDeviation=".025"/></filter><filter id="iU0eRZc" width=".367" height=".392" x="14.97" y="12.803" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23318" stdDeviation=".025"/></filter><filter id="ilVOaic" width=".425" height=".33" x="14.58" y="12.748" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23318" stdDeviation=".025"/></filter><filter id="iryM5Hc" width="2.179" height="2.284" x="12.895" y="9.723" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23318" stdDeviation=".125"/></filter><filter id="iyhY8vd" width="4.546" height="3.437" x="14.175" y="8.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23318" stdDeviation=".125"/></filter><filter id="iUcEyhE" width="1.024" height=".375" x="16.662" y="11.886" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23318" stdDeviation=".025"/></filter><filter id="iC7iAic" width="1.024" height=".375" x="14.142" y="11.886" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23318" stdDeviation=".025"/></filter><linearGradient id="iRPaY7d" x1="7.383" x2="8.908" y1="7.933" y2="8.286" gradientUnits="userSpaceOnUse"><stop offset=".136" class="s84b2w06p"/><stop offset="1" class="gt36rlbyf"/></linearGradient><linearGradient id="iedrh3b" x1="-.347" x2="1.178" y1="1.081" y2="1.434" gradientUnits="userSpaceOnUse"><stop offset=".136" class="s84b2w06p"/><stop offset="1" class="gt36rlbyf"/></linearGradient><linearGradient id="i0AhJLc" x1="20.313" x2="17.781" y1="25.258" y2="24.82" gradientUnits="userSpaceOnUse"><stop offset=".124" class="x05mmvhgv"/><stop offset="1" class="bq07whb_v"/></linearGradient><linearGradient id="i8igjWE" x1="11.625" x2="14.438" y1="25.352" y2="24.258" gradientUnits="userSpaceOnUse"><stop class="jsyhh4bgt"/><stop offset="1" class="sc63ikbnc"/></linearGradient><linearGradient id="ibRzype" x1="2.398" x2="29.867" y1="7.406" y2="7.406" gradientUnits="userSpaceOnUse"><stop class="pty90zojz"/><stop offset=".498" class="lshdhbblk"/><stop offset=".759" class="ty2qe1a3m"/><stop offset="1" class="up_0b0b8w"/></linearGradient><linearGradient id="iAW9NPa" x1="5.039" x2="6.531" y1="7.477" y2="7.477" gradientUnits="userSpaceOnUse"><stop offset=".181" class="b4uz6upmi"/><stop offset="1" class="u-rrnxf4y"/></linearGradient><linearGradient id="irsbW7b" x1="5.039" x2="5.313" y1="7.348" y2="7.348" gradientUnits="userSpaceOnUse"><stop offset=".36" class="l097mcblv"/><stop offset="1" class="zdbzi7bsz"/></linearGradient><linearGradient id="iKoLy8d" x1="24.992" x2="26.188" y1="6.488" y2="6.488" gradientUnits="userSpaceOnUse"><stop offset=".181" class="b4uz6upmi"/><stop offset="1" class="u-rrnxf4y"/></linearGradient><linearGradient id="iqv6bwe" x1="2.958" x2="3.452" y1="6.488" y2="6.488" gradientUnits="userSpaceOnUse"><stop offset=".282" class="pg65l5bvs"/><stop offset="1" class="iywz772fi"/></linearGradient><linearGradient id="ihiVjwC" x1="12.28" x2="8.891" y1="24.627" y2="24.627" gradientUnits="userSpaceOnUse"><stop offset=".335" class="s7xwhlbed"/><stop offset="1" class="vr3repb8u"/></linearGradient><linearGradient id="imrVfMc" x1="12.492" x2="8.516" y1="21.774" y2="21.774" gradientUnits="userSpaceOnUse"><stop class="t2qgq-21l"/><stop offset=".912" class="c3kzq0biv"/></linearGradient><linearGradient id="it1w2ie" x1="23.686" x2="20.749" y1="25.206" y2="25.206" gradientUnits="userSpaceOnUse"><stop offset=".335" class="s7xwhlbed"/><stop offset="1" class="vr3repb8u"/></linearGradient><linearGradient id="ixKrPfb" x1="19.539" x2="23.516" y1="21.774" y2="21.774" gradientUnits="userSpaceOnUse"><stop class="t2qgq-21l"/><stop offset=".912" class="c3kzq0biv"/></linearGradient><linearGradient id="iI0yU5b" x1="17.224" x2="17.074" y1="13.014" y2="13.106" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iCXVQzb" x1="15.436" x2="15.826" y1="13.781" y2="13.829" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="inYgIoc" x1="15.914" x2="15.914" y1="14.171" y2="13.892" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="ibJIxKd" x1="17.265" x2="17.123" y1="12.981" y2="13.069" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="idmLNbd" x1="15.256" x2="15.113" y1="12.981" y2="13.069" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-lifting-weights-medium-light" /></template>
<style>
.aao4qobhm {
  stop-color: var(--svg-color--edb89c, #EDB89C);
}

.alb2mybdx {
  stop-color: var(--svg-color--f4c5a9, #F4C5A9);
}

.atyjoz1aa {
  d: path("M13.717 10.207c.284-.252.693-.255.923-.214l.184.59a.36.36 0 0 0-.31.107c-.208.576-1.02.98-1.353 1.067c-.069-.682.066-1.113.556-1.55");
}

.aufvjo_md {
  stop-color: var(--svg-color--483a56, #483A56);
  stop-opacity: 0;
}

.b0fux9bsc {
  fill: var(--svg-color--ffffc8, #FFFFC8);
  d: path("M15.566 9.098c-.78 0-1.083.677-1.141.884c.761 1.788 1.763 1.536 3.228 1.536c.782 0 .752.347.818.518c-.215-2.004-1.375-2.938-2.905-2.938");
}

.b4uz6upmi {
  stop-color: var(--svg-color--392f45, #392F45);
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.bll85w0ed {
  fill: var(--svg-color--e1a587, #E1A587);
  d: path("M18.12 13.349a.49.49 0 1 0 0-.982a.49.49 0 0 0 0 .982");
}

.bq07whb_v {
  stop-color: var(--svg-color--a99cbb, #A99CBB);
  stop-opacity: 0;
}

.c-95a726o {
  d: path("M16.881 12.826c.03.038-.031.086-.1.137s-.12.088-.149.05c-.029-.04.003-.113.072-.164c.07-.052.148-.062.177-.023");
}

.c-x9-vskh {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m15.74 13.033l-.244.777c-.05.16.07.32.238.32h.36a.247.247 0 0 0 .237-.32l-.242-.777c-.052-.172-.295-.172-.35 0");
}

.c0s8udrlx {
  stop-color: var(--svg-color--6b5678, #6B5678);
}

.c3kzq0biv {
  stop-color: var(--svg-color--453060, #453060);
}

.cftjypctq {
  stop-color: var(--svg-color--dcb09a, #DCB09A);
}

.cg05ombch {
  stop-color: var(--svg-color--886fd9, #886FD9);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ctdwkio9o {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.007 12.615c.298 0 .55.205.619.484a.125.125 0 0 1-.123.155h-1.02a.105.105 0 0 1-.103-.124a.64.64 0 0 1 .627-.515");
}

.d2-2pqbwj {
  stop-color: var(--svg-color--0e0716, #0E0716);
}

.dssvo9bbk {
  stroke: var(--svg-color--a1683f, #A1683F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.762 12.161c.116-.066.386-.21.824-.167");
}

.dvyniwihb {
  stop-color: var(--svg-color--c57f82, #C57F82);
}

.e4y-1lbum {
  r: 0.398px;
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.eijss2b4a {
  stop-color: var(--svg-color--8b6259, #8B6259);
}

.em3ofwhyw {
  d: path("m10.948 13.026l2.396-1.12l2.578 3.399l2.469-3.563l2.729 1.318a.25.25 0 0 1 .113.34l-1.194 2.303a1 1 0 0 0-.112.482l.12 5.76h-7.985v-5.788a1 1 0 0 0-.098-.433l-1.136-2.363a.25.25 0 0 1 .12-.335");
}

.f3sav0_om {
  d: path("M15.288 13.098c0-.131-.107-.219-.136-.245l-.131.127l.08.165z");
}

.fmwe_9bnp {
  stop-color: var(--svg-color--b9adcc, #B9ADCC);
}

.ft5dv1b6b {
  fill: none;
}

.fzjqedceo {
  d: path("M24.992 29.53v.376H20.36v-1.914h2.352c.383.377 1.215.73 1.836.941c.398.169.445.442.445.597");
}

.g2y7heb1k {
  stop-color: var(--svg-color--edb495, #EDB495);
}

.g4offrb0h {
  d: path("M7.5 5.71a.399.399 0 1 1 .797-.034v.46a.38.38 0 0 1-.758.032z");
}

.g5fg-5cgy {
  d: path("M28.852 4.402a.8.8 0 0 0-.8-.8h-.33a.8.8 0 0 0-.8.8v4.173a.8.8 0 0 0 .8.8h.33a.8.8 0 0 0 .8-.8z");
}

.gknucfb8h {
  cx: 10.586px;
  cy: 7px;
  r: 0.398px;
}

.gt36rlbyf {
  stop-color: var(--svg-color--e0aa90, #E0AA90);
  stop-opacity: 0;
}

.h27r7g9xr {
  stop-color: var(--svg-color--c2937c, #C2937C);
}

.hekob1wbk {
  stop-color: var(--svg-color--695381, #695381);
}

.hg-g6h4_r {
  stroke: var(--svg-color--854e32, #854E32);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.762 12.161c.116-.066.386-.21.824-.167");
}

.htmlfhblq {
  stop-color: var(--svg-color--615f65, #615F65);
}

.hw9-utbwm {
  stop-color: var(--svg-color--b26b97, #B26B97);
}

.i25jr6cdh {
  stop-color: var(--svg-color--694cb1, #694CB1);
}

.i9_a76-ul {
  stop-color: var(--svg-color--5e546b, #5E546B);
}

.i9ptfsj3a {
  cx: 14.792px;
  cy: 12.913px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.178px;
  ry: 0.09px;
}

.id87reb_m {
  stop-color: var(--svg-color--918e92, #918E92);
}

.ijj045bhz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M2.398 6.406H29.43");
}

.im4wg0bzf {
  fill: var(--svg-color--000, #000);
  d: path("M16.678 13.147c0-.13.104-.234.233-.234a.232.232 0 0 1 .208.341h-.413a.2.2 0 0 1-.028-.107");
}

.iqe9e2uud {
  stop-color: var(--svg-color--eec2a5, #EEC2A5);
}

.iywz772fi {
  stop-color: var(--svg-color--615e66, #615E66);
  stop-opacity: 0;
}

.j9ne5bb7q {
  stop-color: var(--svg-color--d4988a, #D4988A);
}

.jsyhh4bgt {
  stop-color: var(--svg-color--8d7b95, #8D7B95);
}

.jxkz5w5ce {
  d: path("m15.74 13.033l-.244.777c-.05.16.07.32.238.32h.36a.247.247 0 0 0 .237-.32l-.242-.777c-.052-.172-.295-.172-.35 0");
}

.jxo3ryqpx {
  d: path("M14.915 12.739a.407.407 0 0 0-.392.515h.787a.41.41 0 0 0-.394-.515");
}

.k49s7u2jw {
  fill: var(--svg-color--be7f6b, #BE7F6B);
  d: path("M13.781 13.349a.49.49 0 1 0 0-.982a.49.49 0 0 0 0 .982");
}

.kiedr_brj {
  cx: 14.792px;
  cy: 12.913px;
  rx: 0.178px;
  ry: 0.09px;
}

.ks97e6bva {
  stop-color: var(--svg-color--eec2a5, #EEC2A5);
  stop-opacity: 0;
}

.kv3enpo0a {
  d: path("M23.516 21.066a1.988 1.988 0 0 0-3.977 0v1.686c0 .193.157.35.35.35h3.277a.35.35 0 0 0 .35-.35z");
}

.l097mcblv {
  stop-color: var(--svg-color--433f49, #433F49);
}

.l2at7otgu {
  d: path("M23.823 5.627a.422.422 0 1 0-.843-.033v.584a.4.4 0 0 0 .798.031z");
}

.lghqvdpyh {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.82 12.615a.64.64 0 0 0-.618.484c-.02.08.04.155.122.155h1.02a.105.105 0 0 0 .104-.124a.64.64 0 0 0-.627-.515");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lshdhbblk {
  stop-color: var(--svg-color--9a969d, #9A969D);
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.m0j2adc3x {
  d: path("M7.73 6.851h2.46v7.269H7.73z");
}

.mb43on0cd {
  stop-color: var(--svg-color--cc8e8e, #CC8E8E);
  stop-opacity: 0;
}

.mj--szbch {
  stop-color: var(--svg-color--875b54, #875B54);
}

.mwjg5o1vq {
  stop-color: var(--svg-color--dca18f, #DCA18F);
}

.nkc4sz_mu {
  d: path("M17.274 13.092a.4.4 0 0 0-.105-.21l-.118.13l.053.103z");
}

.nm-q8ebbk {
  d: path("M8.16 5.627a.422.422 0 1 1 .844-.033v.584a.4.4 0 0 1-.798.031z");
}

.ns732vbyd {
  stop-color: var(--svg-color--dcb09a, #DCB09A);
  stop-opacity: 0;
}

.nvirpp9bq {
  d: path("m22.668 28.448l.473-5.464h-3.22l.479 5.464z");
}

.o6imu6bzx {
  stop-color: var(--svg-color--59417a, #59417A);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oge6r-buh {
  d: path("M16.912 12.739a.407.407 0 0 1 .392.515h-.787a.41.41 0 0 1 .394-.515");
}

.oxjnikb3r {
  fill: var(--svg-color--89004e, #89004E);
  d: path("M15.904 14.573c-.239 0-.462-.058-.65-.158c-.064-.033-.133.04-.093.1a.883.883 0 0 0 1.485 0c.04-.062-.029-.133-.093-.1c-.188.1-.41.158-.65.158");
}

.p-4sfzbzp {
  stop-color: var(--svg-color--fae7ad, #FAE7AD);
}

.pf6z3-bjj {
  stop-color: var(--svg-color--ffe0b1, #FFE0B1);
}

.pg65l5bvs {
  stop-color: var(--svg-color--615e66, #615E66);
}

.pgalr_bqp {
  d: path("M18.12 13.593a.735.735 0 1 0 0-1.47a.735.735 0 0 0 0 1.47");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pnmas4b0d {
  d: path("M0 0h2.46v7.269H0z");
}

.przpgcbzb {
  d: path("M13.59 12.488h.005l-.005-.122l-.005-.14c.01-.433.263-.601.37-.657l.024-.01l.024-.009c.243-.112.44-.308.543-.564l.038-.129a.12.12 0 0 1 .21-.023c.329.48.877.776 1.458.776h1.472c.082 0 .494.069.519.638l-.054 1.242c-.056 1.28-1.056 2.14-2.277 2.14s-2.221-.86-2.278-2.14z");
}

.pty90zojz {
  stop-color: var(--svg-color--7b7784, #7B7784);
}

.pxw0zzedl {
  d: path("M15.566 9.098c-.78 0-1.083.677-1.141.884c.761 1.788 1.763 1.536 3.228 1.536c.782 0 .752.347.818.518c-.215-2.004-1.375-2.938-2.905-2.938");
}

.q-5k2pvgj {
  stop-color: var(--svg-color--ffcba2, #FFCBA2);
}

.q-vr2ac-v {
  stop-color: var(--svg-color--5c447a, #5C447A);
}

.q1wg51bmi {
  d: path("M16 25.93c-2.363 0-4.203-.72-4.828-1.078v-2.907h9.5v3.016c-.573.323-2.31.969-4.672.969");
}

.q46dg-bku {
  stop-color: var(--svg-color--6b5678, #6B5678);
  stop-opacity: 0;
}

.q8lf5_6yk {
  stroke: var(--svg-color--854e32, #854E32);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M15.066 12.161a1.3 1.3 0 0 0-.824-.167");
}

.qao18ac_v {
  stop-color: var(--svg-color--f3c8a0, #F3C8A0);
  stop-opacity: 0;
}

.qao3n1bvl {
  stop-color: var(--svg-color--e2b69c, #E2B69C);
  stop-opacity: 0;
}

.qd4tofb7u {
  d: path("M7.04 29.53v.376h4.632v-1.914H9.32c-.383.377-1.215.73-1.836.941c-.398.169-.445.442-.445.597");
}

.qf2r2ccba {
  stop-color: var(--svg-color--d9996f, #D9996F);
}

.qnghx6b7d {
  stop-color: var(--svg-color--d09681, #D09681);
}

.qno0gyhtd {
  d: path("M5.04 2.894a.8.8 0 0 1 .8-.8h.329a.8.8 0 0 1 .8.8v7.189a.8.8 0 0 1-.8.8h-.33a.8.8 0 0 1-.8-.8z");
}

.qzfufsu3s {
  stop-color: var(--svg-color--d9af8d, #D9AF8D);
}

.rc5fpablb {
  d: path("M17.234 13.13a.4.4 0 0 0-.111-.221l-.125.136l.056.11z");
}

.rcnz-20vq {
  stop-color: var(--svg-color--a090b1, #A090B1);
}

.rh3jx3c9i {
  d: path("M23.108 5.588a.424.424 0 1 0-.847-.016v.661a.411.411 0 0 0 .823.015z");
}

.rxm6nppqt {
  fill-rule: evenodd;
  d: path("M19.198 13.183c.097-.198.148-.42.148-.652c0-.213-.044-.414-.123-.596h.003a1.5 1.5 0 0 0-.129-.235a1.5 1.5 0 0 1-.241-.81v-.004c0-.833-.676-1.508-1.508-1.508a.25.25 0 0 1-.208-.106a1.51 1.51 0 0 0-2.452 0a.26.26 0 0 1-.208.106h-.039a1.51 1.51 0 0 0-1.468 1.508v.004c0 .287-.084.57-.24.81l-.002.001a1.51 1.51 0 0 0-.1 1.483a.24.24 0 0 1 0 .209a1.47 1.47 0 0 0 1.323 2.114h3.921a1.47 1.47 0 0 0 1.323-2.114a.24.24 0 0 1 0-.209m-5.603-.886l.542.742c.056 1.28.556 0 1.777 0s1.754 1.425 1.81.144l.519-.937c-.025-.57-.437-.61-.52-.61h-1.47c-.582 0-1.13-.284-1.458-.764a.12.12 0 0 0-.211.024l-.038.088c-.256.716-.968.867-.951 1.313");
}

.s7a934b5m {
  fill: var(--svg-color--ce8b83, #CE8B83);
  d: path("m15.735 13.096l-.312.777c-.05.16.069.32.237.32h.36a.247.247 0 0 0 .238-.32l-.243-.777c-.052-.172-.226-.172-.28 0");
}

.s7xwhlbed {
  stop-color: var(--svg-color--f9bea4, #F9BEA4);
}

.s84b2w06p {
  stop-color: var(--svg-color--764549, #764549);
}

.sbel2qb8e {
  stop-color: var(--svg-color--c78b7b, #C78B7B);
}

.sc63ikbnc {
  stop-color: var(--svg-color--ac9ebe, #AC9EBE);
  stop-opacity: 0;
}

.shek1db6a {
  stop-color: var(--svg-color--c5897c, #C5897C);
}

.spunz4bdn {
  stop-color: var(--svg-color--f4c5a9, #F4C5A9);
  stop-opacity: 0;
}

.sqq3pyb6i {
  fill: var(--svg-color--000, #000);
  d: path("M15.149 13.147a.23.23 0 0 0-.234-.234a.232.232 0 0 0-.207.341h.413a.23.23 0 0 0 .028-.107");
}

.styss3bew {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.881 12.826c.03.038-.031.086-.1.137s-.12.088-.149.05c-.029-.04.003-.113.072-.164c.07-.052.148-.062.177-.023");
}

.svjjs0b3e {
  stop-color: var(--svg-color--d3a080, #D3A080);
}

.swlqzkb4o {
  stop-color: var(--svg-color--e2b69c, #E2B69C);
}

.szuswrb-r {
  stop-color: var(--svg-color--f2c59f, #F2C59F);
}

.t07n6xojw {
  stop-color: var(--svg-color--cc947b, #CC947B);
  stop-opacity: 0;
}

.t2qgq-21l {
  stop-color: var(--svg-color--574471, #574471);
}

.t7wtrebxf {
  stop-color: var(--svg-color--624d77, #624D77);
  stop-opacity: 0;
}

.tn93407hk {
  stop-color: var(--svg-color--624d77, #624D77);
}

.tphhgybtp {
  d: path("M26.922 2.894a.8.8 0 0 0-.8-.8h-.33a.8.8 0 0 0-.8.8v7.189a.8.8 0 0 0 .8.8h.33a.8.8 0 0 0 .8-.8z");
}

.ty2qe1a3m {
  stop-color: var(--svg-color--97959c, #97959C);
}

.tzfcre5-h {
  d: path("M8.876 5.588a.424.424 0 1 1 .847-.016v.661a.411.411 0 0 1-.823.015z");
}

.u-rrnxf4y {
  stop-color: var(--svg-color--51435f, #51435F);
  stop-opacity: 0;
}

.u1b9dcc6t {
  stop-color: var(--svg-color--624ba3, #624BA3);
  stop-opacity: 0;
}

.u6_y93pge {
  d: path("M8.516 21.066a1.988 1.988 0 1 1 3.976 0v1.686a.35.35 0 0 1-.35.35H8.866a.35.35 0 0 1-.35-.35z");
}

.u8xde_fso {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M16.436 12.97c.121-.214.306-.382.703-.382a.76.76 0 0 1 .49.168c.123.1.106.227.011.274l-.254.145c-.298-.096-.627-.109-.95-.205");
}

.ufmuzl7ni {
  d: path("M22.392 5.626a.401.401 0 1 0-.803-.014v.575a.391.391 0 0 0 .783.013z");
}

.uhxzzsbrl {
  stop-color: var(--svg-color--65507e, #65507E);
}

.umuctbc3u {
  stop-color: var(--svg-color--c38478, #C38478);
}

.uo2e3-sou {
  stop-color: var(--svg-color--edae8a, #EDAE8A);
  stop-opacity: 0;
}

.up_0b0b8w {
  stop-color: var(--svg-color--8d8c90, #8D8C90);
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.us2dmwbcp {
  stop-color: var(--svg-color--ffe0b1, #FFE0B1);
  stop-opacity: 0;
}

.utuf8geyx {
  stop-color: var(--svg-color--cabed2, #CABED2);
  stop-opacity: 0;
}

.uv_bhvydh {
  d: path("m9.404 28.878l-.513-5.894h3.218l-.533 5.966z");
}

.uywq_y1iv {
  width: 27.875px;
  height: 1.025px;
  x: 2.063px;
  y: 5.975px;
  rx: 0.2px;
}

.v60d8yb_v {
  d: path("M13.773 13.593a.735.735 0 1 0 0-1.47a.735.735 0 0 0 0 1.47");
}

.v8rezjblq {
  stop-color: var(--svg-color--402b83, #402B83);
}

.vej6r8a3c {
  stroke: var(--svg-color--a1683f, #A1683F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.066 12.161a1.3 1.3 0 0 0-.824-.167");
}

.vr3repb8u {
  stop-color: var(--svg-color--e3aa95, #E3AA95);
}

.vtfzq1zlw {
  stop-color: var(--svg-color--cabed2, #CABED2);
}

.wpbhksb1v {
  stop-color: var(--svg-color--50425e, #50425E);
}

.wvbuym-2v {
  stop-color: var(--svg-color--dca489, #DCA489);
}

.x05mmvhgv {
  stop-color: var(--svg-color--887497, #887497);
}

.x9t-2zb_r {
  d: path("M3.11 4.402a.8.8 0 0 1 .8-.8h.33a.8.8 0 0 1 .8.8v4.173a.8.8 0 0 1-.8.8h-.33a.8.8 0 0 1-.8-.8z");
}

.xgvxkebfh {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M15.392 12.97c-.121-.214-.306-.382-.702-.382a.76.76 0 0 0-.49.168c-.124.1-.107.227-.012.274l.254.145c.298-.096.627-.109.95-.205");
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.xl910dy6z {
  stop-color: var(--svg-color--cc9183, #CC9183);
}

.xukae21xj {
  stop-color: var(--svg-color--d8a38c, #D8A38C);
}

.y0nqeezxq {
  d: path("M24.483 5.71a.399.399 0 1 0-.796-.034v.46a.38.38 0 0 0 .758.032z");
}

.y3mq3eusn {
  stop-color: var(--svg-color--f3c8a0, #F3C8A0);
}

.ymbigdcyd {
  stop-color: var(--svg-color--8263c1, #8263C1);
  stop-opacity: 0;
}

.yyr7j8rnv {
  stop-color: var(--svg-color--5a3e9b, #5A3E9B);
}

.z0ggixb3q {
  d: path("M9.592 5.626a.401.401 0 1 1 .803-.014v.575a.391.391 0 0 1-.783.013z");
}

.zdbzi7bsz {
  stop-color: var(--svg-color--433f49, #433F49);
  stop-opacity: 0;
}

.zw2whl-je {
  stop-color: var(--svg-color--c48b7e, #C48B7E);
}

.zx13l8w6l {
  stop-color: var(--svg-color--a06353, #A06353);
}

</style>
