<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iuPUjXK)" class="jg__x_b3k"/><rect fill="url(#igqluge)" class="t3gf2pooa"/><rect fill="url(#iUAydXd)" class="t3gf2pooa"/><circle fill="url(#iSjNSXd)" class="ll93foxsj"/><circle fill="url(#igKH8Nb)" class="ll93foxsj"/><g filter="url(#iDGj9Yb)"><circle fill="url(#ivu6Sob)" class="ja-c2-y0b"/></g><circle fill="url(#if1zsss)" class="xtyrtq_4k"/><circle fill="url(#iCx0iwe)" class="xtyrtq_4k"/><g filter="url(#iYmA9Fe)"><circle fill="url(#ilTltWb)" class="dyuoo2b0b"/></g><g filter="url(#iOCpiyd)"><path fill="url(#iUwKtXc)" class="hq3ckfbkl"/><path fill="url(#iEBraXc)" class="hq3ckfbkl"/><path fill="url(#iOVMkrd)" class="hq3ckfbkl"/></g><g filter="url(#iTsJbjU)"><path fill="url(#ibBGWDb)" class="o1ng31bsc"/></g><path fill="url(#iYNFiuc)" class="o1ng31bsc"/><path fill="url(#iSXqPXc)" class="o1ng31bsc"/><path fill="url(#ig6kn7d)" class="o1ng31bsc"/><path fill="url(#ii7QfHd)" class="o1ng31bsc"/><path fill="url(#izAjGnc)" class="o1ng31bsc"/><path fill="url(#iiQEeAd)" class="o1ng31bsc"/><g filter="url(#i4qSx7c)"><circle fill="url(#i1tOlmb)" class="y7wl_rbeg"/></g><circle fill="url(#i6wCPob)" class="u5uc3vg4f"/><circle class="fz80s53fc"/><g filter="url(#iMLiW1b)"><circle fill="url(#i17EGDb)" transform="matrix(-1 0 0 1 18.723 13.762)" class="el7r9pbsw"/></g><circle fill="url(#i51g7Pd)" transform="matrix(-1 0 0 1 18.504 13.527)" class="y2c1oq0fx"/><circle fill="url(#iyg3sde)" transform="matrix(-1 0 0 1 18.504 13.527)" class="y2c1oq0fx"/><circle transform="matrix(-1 0 0 1 18.484 13.527)" class="m8bj1mb9s"/><g filter="url(#isP9ihc)"><path fill="url(#iRenKOe)" class="zm9-51tyy"/></g><g filter="url(#iqN3aId)"><path stroke="url(#ivHpKHe)" class="tk9x5nw_u"/></g><path fill="url(#ixMFOQe)" class="pkku2fbqv"/><path class="yqk_xqsqr"/><path fill="url(#iyo09wb)" class="zpxnljbfi"/><path fill="url(#imK6vCc)" clip-rule="evenodd" class="ydv3enbju"/><path fill="url(#i8KVxLe)" class="cstpoqe2v"/><g filter="url(#i51aeCP)"><path class="cjzuonbhl"/><path fill="url(#iw7PeQe)" class="pky976qgh"/><path fill="url(#i2JYECe)" class="pky976qgh"/><path fill="url(#iCtsNFb)" class="pky976qgh"/></g><rect fill="url(#iLy5pFb)" class="z2o3bacur"/><rect fill="url(#iSz3BAc)" class="z2o3bacur"/><rect fill="url(#iFCUjAd)" class="z2o3bacur"/><rect fill="url(#iA8K1Lb)" class="z2o3bacur"/><rect fill="url(#iHky5tb)" transform="rotate(-17.452 5.516 21.554)" class="i0xws6gtg"/><rect fill="url(#iH2ru6d)" transform="rotate(-17.452 5.516 21.554)" class="i0xws6gtg"/><rect fill="url(#i0eQ6fb)" transform="rotate(-17.452 5.516 21.554)" class="i0xws6gtg"/><rect fill="url(#ixrbcYc)" transform="rotate(-17.452 5.516 21.554)" class="i0xws6gtg"/><rect fill="url(#iLkdMgc)" transform="rotate(-30.06 2.878 22.953)" class="g0ctisbgx"/><rect fill="url(#iNPe5WE)" transform="rotate(-30.06 2.878 22.953)" class="g0ctisbgx"/><rect fill="url(#iuM2nId)" transform="rotate(-30.06 2.878 22.953)" class="g0ctisbgx"/><rect fill="url(#iHTWtAe)" transform="rotate(-30.06 2.878 22.953)" class="g0ctisbgx"/><rect fill="url(#ikdxKqc)" transform="rotate(-32.714 1.35 25.402)" class="kj71sfbhv"/><rect fill="url(#iMGtXwg)" transform="rotate(-32.714 1.35 25.402)" class="kj71sfbhv"/><rect fill="url(#iGUOQge)" transform="rotate(-32.714 1.35 25.402)" class="kj71sfbhv"/><g filter="url(#iio2uLd)"><path class="r_m0m432l"/><path fill="url(#iyANPRo)" class="inicu83ai"/><path fill="url(#ioeigbc)" class="inicu83ai"/><path fill="url(#i8e6EJd)" class="inicu83ai"/><path fill="url(#iZi46hw)" class="inicu83ai"/><path fill="url(#iwA1LMb)" class="inicu83ai"/><path fill="url(#i7pkC2c)" class="inicu83ai"/></g><rect transform="matrix(-1 0 0 1 23.28 21.002)" class="fk_sd4b3f"/><rect fill="url(#i5cKy7J)" transform="matrix(-1 0 0 1 23.28 21.002)" class="lvqejss-o"/><rect fill="url(#iFbacFb)" transform="matrix(-1 0 0 1 23.28 21.002)" class="lvqejss-o"/><rect transform="scale(-1 1)rotate(-17.452 56.974 97.053)" class="l257jccgu"/><rect fill="url(#iAe9aMb)" transform="scale(-1 1)rotate(-17.452 56.974 97.053)" class="i7m2j00fs"/><rect fill="url(#i56EY8b)" transform="scale(-1 1)rotate(-17.452 56.974 97.053)" class="i7m2j00fs"/><rect transform="scale(-1 1)rotate(-30.061 28.18 65.703)" class="uvhjscb1o"/><rect fill="url(#iXxxUfc)" transform="scale(-1 1)rotate(-30.061 28.18 65.703)" class="gl17utj4l"/><rect fill="url(#iw4dd4c)" transform="scale(-1 1)rotate(-30.061 28.18 65.703)" class="gl17utj4l"/><rect fill="url(#ixP16ad)" transform="scale(-1 1)rotate(-32.714 27.948 64.915)" class="ij5lprb2c"/><rect fill="url(#iWnLhMc)" transform="scale(-1 1)rotate(-32.714 27.948 64.915)" class="ij5lprb2c"/><rect fill="url(#itioSUc)" transform="scale(-1 1)rotate(-32.714 27.948 64.915)" class="ij5lprb2c"/><g filter="url(#iPuZS3r)"><path fill="url(#iIBXVZc)" class="m7zmv-b2q"/></g><path class="cyjy2_b1a"/><path fill="url(#iWSslae)" class="jaguiib4s"/><path fill="url(#iybPmle)" class="jaguiib4s"/><path fill="url(#i7xtMae)" class="jaguiib4s"/><path fill="url(#iDhOhRd)" class="jaguiib4s"/><path fill="url(#iXBY41H)" class="jaguiib4s"/><path class="v62k80b2s"/><defs><radialGradient id="iuPUjXK" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.5625 22.9424 0 16.038 29.982)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="udi_mfp4v"/><stop offset="1" class="rvq6gmb5w"/></radialGradient><radialGradient id="igqluge" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.93354 -1.99461 0 16 21.732)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="dfkyv0s4o"/><stop offset="1" class="i40h4bbfl"/></radialGradient><radialGradient id="iUAydXd" cx="0" cy="0" r="1" gradientTransform="matrix(.1582 4.32031 -2.99315 .1096 15.842 21.271)" gradientUnits="userSpaceOnUse"><stop offset=".627" class="iv7v1nb3o"/><stop offset=".924" class="q53_zdbrw"/></radialGradient><radialGradient id="igKH8Nb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.14062 0 0 -2.35156 10.076 14.271)" gradientUnits="userSpaceOnUse"><stop offset=".569" class="ult0y8bvs"/><stop offset="1" class="oukb_nb4n"/></radialGradient><radialGradient id="ivu6Sob" cx="0" cy="0" r="1" gradientTransform="matrix(-.89844 0 0 -1.30469 9.834 14.271)" gradientUnits="userSpaceOnUse"><stop offset=".47" class="p-lt9kb3w"/><stop offset="1" class="vsdiecbqp"/></radialGradient><radialGradient id="iCx0iwe" cx="0" cy="0" r="1" gradientTransform="matrix(1.61023 0 0 2.38281 22.31 14.271)" gradientUnits="userSpaceOnUse"><stop offset=".596" class="faf527bpe"/><stop offset="1" class="u8epgmbkl"/></radialGradient><radialGradient id="ilTltWb" cx="0" cy="0" r="1" gradientTransform="matrix(1.12895 -1.07641 1.63635 1.71621 21.89 14.43)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="lt6k7o0fo"/><stop offset=".791" class="a7iu9vb1v"/></radialGradient><radialGradient id="iUwKtXc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55469 9.31951 -15.88124 -2.64932 18.32 4.26)" gradientUnits="userSpaceOnUse"><stop offset=".488" class="q3lmwvq-b"/><stop offset="1" class="h27flvbap"/></radialGradient><radialGradient id="iEBraXc" cx="0" cy="0" r="1" gradientTransform="rotate(-168.986 10.22 3.242)scale(4.87097 3.98496)" gradientUnits="userSpaceOnUse"><stop offset=".275" class="v1f5judsg"/><stop offset="1" class="dqs_mibtz"/></radialGradient><radialGradient id="iOVMkrd" cx="0" cy="0" r="1" gradientTransform="rotate(157.684 6.642 3.214)scale(4.52651 1.96574)" gradientUnits="userSpaceOnUse"><stop class="qhidatbjk"/><stop offset="1" class="uaafun-3k"/></radialGradient><radialGradient id="ig6kn7d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.82215 17.5452 0 15.82 22.05)" gradientUnits="userSpaceOnUse"><stop offset=".059" class="wjd3pjbpb"/><stop offset="1" class="yfpl-j8nb"/></radialGradient><radialGradient id="ii7QfHd" cx="0" cy="0" r="1" gradientTransform="matrix(6.53125 -2.1875 1.7829 5.32324 9.132 6.603)" gradientUnits="userSpaceOnUse"><stop class="fq1qgwqrn"/><stop offset="1" class="svm3t3bnk"/></radialGradient><radialGradient id="izAjGnc" cx="0" cy="0" r="1" gradientTransform="rotate(-142.193 11.405 3.624)scale(2.29406 2.71785)" gradientUnits="userSpaceOnUse"><stop offset=".596" class="ywetm9lbn"/><stop offset="1" class="akc2n4bxa"/></radialGradient><radialGradient id="iiQEeAd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.15625 2.42578 0 13.444 13.04)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="exnunbb1a"/><stop offset="1" class="jmhwzrbhq"/></radialGradient><radialGradient id="i1tOlmb" cx="0" cy="0" r="1" gradientTransform="rotate(69.179 -3.1 15.209)scale(3.15946)" gradientUnits="userSpaceOnUse"><stop class="ltf0tqb9y"/><stop offset="1" class="enitdihfo"/></radialGradient><radialGradient id="i6wCPob" cx="0" cy="0" r="1" gradientTransform="rotate(95.856 .777 12.865)scale(1.83772 1.80959)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="h50m5ib7f"/><stop offset="1" class="bng_m2b0t"/></radialGradient><radialGradient id="i17EGDb" cx="0" cy="0" r="1" gradientTransform="rotate(48.116 -1.842 1.568)scale(2.66802)" gradientUnits="userSpaceOnUse"><stop class="bw57fdcce"/><stop offset="1" class="hkndu6boi"/></radialGradient><radialGradient id="i51g7Pd" cx="0" cy="0" r="1" gradientTransform="matrix(-.2461 1.67187 -1.6463 -.24233 1.645 1.426)" gradientUnits="userSpaceOnUse"><stop offset=".618" class="ogpl8rbbb"/><stop offset="1" class="w0ry1tv8g"/></radialGradient><radialGradient id="iRenKOe" cx="0" cy="0" r="1" gradientTransform="rotate(-179.479 10.185 6.523)scale(3.43734 3.6257)" gradientUnits="userSpaceOnUse"><stop class="k589lpbub"/><stop offset=".808" class="ebc1zfyja"/></radialGradient><radialGradient id="ixMFOQe" cx="0" cy="0" r="1" gradientTransform="rotate(-81.193 18.42 1.621)scale(2.24522 3.5001)" gradientUnits="userSpaceOnUse"><stop class="nrrnwgb2j"/><stop offset="1" class="ju7pygbji"/></radialGradient><radialGradient id="iyo09wb" cx="0" cy="0" r="1" gradientTransform="matrix(.51562 -1.05469 2.4217 1.18394 14.983 18.818)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="hbx3qwnwa"/><stop offset=".929" class="g3i-1pbcq"/></radialGradient><radialGradient id="iw7PeQe" cx="0" cy="0" r="1" gradientTransform="rotate(73.968 -11.567 15.393)scale(6.46576 13.0703)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="bxi9tgmwe"/><stop offset="1" class="tn-w78xgx"/></radialGradient><radialGradient id="i2JYECe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.93323 -.03125 .0265 -1.639 14.244 27.264)" gradientUnits="userSpaceOnUse"><stop offset=".165" class="gbny4_b4j"/><stop offset="1" class="glfls735f"/></radialGradient><radialGradient id="iCtsNFb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.59378 3.81248 -2.48353 -1.68964 11.842 25.045)" gradientUnits="userSpaceOnUse"><stop offset=".284" class="oxi0f3b2m"/><stop offset="1" class="vl_ql576y"/></radialGradient><radialGradient id="iLy5pFb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.6161 1.22861 0 10.293 23.618)" gradientUnits="userSpaceOnUse"><stop class="iw38491ye"/><stop offset="1" class="zl7ptbcaa"/></radialGradient><radialGradient id="iSz3BAc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.22395 0 0 -3.23423 10.681 23.383)" gradientUnits="userSpaceOnUse"><stop class="lxs7f3b1j"/><stop offset="1" class="u84zz4ukw"/></radialGradient><radialGradient id="iA8K1Lb" cx="0" cy="0" r="1" gradientTransform="matrix(-.33793 2.79084 -2.2828 -.27641 10.116 21.903)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="ws-ofvbpp"/><stop offset="1" class="i2p625zaz"/></radialGradient><radialGradient id="iHky5tb" cx="0" cy="0" r="1" gradientTransform="matrix(.20372 -3.21174 1.70613 .10822 6.079 24.768)" gradientUnits="userSpaceOnUse"><stop class="x9syn5bsf"/><stop offset="1" class="ippisxk_c"/></radialGradient><radialGradient id="i0eQ6fb" cx="0" cy="0" r="1" gradientTransform="matrix(-.02888 -2.796 1.23588 -.01277 7.45 24.748)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="got22lb_s"/><stop offset="1" class="m5racngae"/></radialGradient><radialGradient id="ixrbcYc" cx="0" cy="0" r="1" gradientTransform="matrix(.4982 -1.16022 3.58632 1.53998 5.806 25.212)" gradientUnits="userSpaceOnUse"><stop offset=".098" class="yps5thqls"/><stop offset="1" class="aje_gtbfo"/></radialGradient><radialGradient id="iLkdMgc" cx="0" cy="0" r="1" gradientTransform="matrix(1.52841 -2.3289 3.00123 1.96966 3.07 25.48)" gradientUnits="userSpaceOnUse"><stop class="lv9f4sbft"/><stop offset="1" class="gjthckb9a"/></radialGradient><radialGradient id="iNPe5WE" cx="0" cy="0" r="1" gradientTransform="matrix(-.14765 -2.39628 1.0581 -.0652 4.414 26.186)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="p7xh8mbkr"/><stop offset="1" class="so0nfjs_n"/></radialGradient><radialGradient id="iuM2nId" cx="0" cy="0" r="1" gradientTransform="rotate(-48.526 30.658 10.17)scale(1.97399 4.7131)" gradientUnits="userSpaceOnUse"><stop class="o5pi4qbos"/><stop offset="1" class="mrh8oxbyb"/></radialGradient><radialGradient id="iHTWtAe" cx="0" cy="0" r="1" gradientTransform="matrix(1.4011 -3.5602 2.78505 1.09605 3.124 26.651)" gradientUnits="userSpaceOnUse"><stop offset=".786" class="slfwwoboa"/><stop offset="1" class="htek_b-aw"/></radialGradient><radialGradient id="ikdxKqc" cx="0" cy="0" r="1" gradientTransform="rotate(-103.353 12.276 12.872)scale(2.55343 1.41015)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="x4_rgjbgr"/><stop offset="1" class="kyxlbjczl"/></radialGradient><radialGradient id="iMGtXwg" cx="0" cy="0" r="1" gradientTransform="matrix(.64228 -.85953 1.5214 1.13686 1.622 27.845)" gradientUnits="userSpaceOnUse"><stop class="o1u4v1x-w"/><stop offset="1" class="rrdpflbyy"/></radialGradient><radialGradient id="iGUOQge" cx="0" cy="0" r="1" gradientTransform="matrix(.53113 1.91968 -1.32546 .36672 3.298 25.969)" gradientUnits="userSpaceOnUse"><stop offset=".11" class="libnoft0w"/><stop offset="1" class="oi5b6vt4l"/></radialGradient><radialGradient id="iyANPRo" cx="0" cy="0" r="1" gradientTransform="rotate(106.149 4.403 20.77)scale(6.42022 13.0626)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="bxi9tgmwe"/><stop offset="1" class="tn-w78xgx"/></radialGradient><radialGradient id="ioeigbc" cx="0" cy="0" r="1" gradientTransform="matrix(1.93323 -.03101 .0261 1.62651 17.756 27.284)" gradientUnits="userSpaceOnUse"><stop offset=".165" class="gbny4_b4j"/><stop offset="1" class="glfls735f"/></radialGradient><radialGradient id="i8e6EJd" cx="0" cy="0" r="1" gradientTransform="matrix(2.59376 3.78341 -2.47147 1.69434 20.158 25.082)" gradientUnits="userSpaceOnUse"><stop offset=".284" class="oxi0f3b2m"/><stop offset="1" class="vl_ql576y"/></radialGradient><radialGradient id="iZi46hw" cx="0" cy="0" r="1" gradientTransform="rotate(113.738 5.994 22.17)scale(2.83347 1.67501)" gradientUnits="userSpaceOnUse"><stop offset=".546" class="qzo_nkzbd"/><stop offset="1" class="ht552mbaq"/></radialGradient><radialGradient id="iwA1LMb" cx="0" cy="0" r="1" gradientTransform="rotate(116.054 5.43 20.379)scale(3.13062 2.06753)" gradientUnits="userSpaceOnUse"><stop offset=".26" class="jjhcfiagl"/><stop offset="1" class="d2h5kyjkp"/></radialGradient><radialGradient id="i7pkC2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.09375 -3.72984 0 23.545 23.514)" gradientUnits="userSpaceOnUse"><stop class="i-ilo59wi"/><stop offset="1" class="gew0dbs3i"/></radialGradient><radialGradient id="i5cKy7J" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.43452 -1.62962 0 .207 .257)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="s9595bb6g"/><stop offset="1" class="la3tbwntj"/></radialGradient><radialGradient id="iFbacFb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.90968 -2.1392 0 .98 .862)" gradientUnits="userSpaceOnUse"><stop offset=".577" class="o39pnqg0i"/><stop offset="1" class="n3i60zbwo"/></radialGradient><radialGradient id="iAe9aMb" cx="0" cy="0" r="1" gradientTransform="matrix(.07378 3.33306 -1.58148 .035 .381 .326)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="s9595bb6g"/><stop offset="1" class="la3tbwntj"/></radialGradient><radialGradient id="i56EY8b" cx="0" cy="0" r="1" gradientTransform="rotate(97.643 .058 .878)scale(2.7887 2.05026)" gradientUnits="userSpaceOnUse"><stop offset=".577" class="o39pnqg0i"/><stop offset="1" class="n3i60zbwo"/></radialGradient><radialGradient id="iXxxUfc" cx="0" cy="0" r="1" gradientTransform="matrix(.07447 3.3649 -1.59659 .03534 .385 .33)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="s9595bb6g"/><stop offset="1" class="la3tbwntj"/></radialGradient><radialGradient id="iw4dd4c" cx="0" cy="0" r="1" gradientTransform="matrix(-.74734 2.73501 -2.01078 -.54945 1.318 1.001)" gradientUnits="userSpaceOnUse"><stop offset=".577" class="o39pnqg0i"/><stop offset="1" class="n3i60zbwo"/></radialGradient><radialGradient id="ixP16ad" cx="0" cy="0" r="1" gradientTransform="rotate(86.011 .058 .65)scale(2.14376 1.52149)" gradientUnits="userSpaceOnUse"><stop class="xq9watbjp"/><stop offset="1" class="ve2ow0b5f"/></radialGradient><radialGradient id="iWnLhMc" cx="0" cy="0" r="1" gradientTransform="matrix(1.82612 .3373 -.5514 2.98514 .616 .826)" gradientUnits="userSpaceOnUse"><stop offset=".455" class="sl7iwijia"/><stop offset="1" class="sce_y6bah"/></radialGradient><radialGradient id="itioSUc" cx="0" cy="0" r="1" gradientTransform="matrix(-.71567 1.75021 -2.23482 -.91383 1.038 .949)" gradientUnits="userSpaceOnUse"><stop offset=".488" class="es563lbhm"/><stop offset=".926" class="rdi-wfxqd"/></radialGradient><radialGradient id="iWSslae" cx="0" cy="0" r="1" gradientTransform="rotate(-101.325 14.908 .997)scale(4.36627 2.77906)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="e-l33-bot"/><stop offset="1" class="nxovy29zu"/></radialGradient><radialGradient id="iDhOhRd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.04687 3.76333 0 16.037 16.81)" gradientUnits="userSpaceOnUse"><stop class="y7xy7bb_m"/><stop offset="1" class="xjomt31wk"/></radialGradient><radialGradient id="iXBY41H" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.9375 -3.86566 0 16 14.014)" gradientUnits="userSpaceOnUse"><stop offset=".846" class="p0u5ydomu"/><stop offset="1" class="woms0-bkw"/></radialGradient><linearGradient id="iSjNSXd" x1="8.779" x2="10.187" y1="12.576" y2="16.303" gradientUnits="userSpaceOnUse"><stop class="q0bx3-bma"/><stop offset="1" class="q2o6fx2nz"/></linearGradient><linearGradient id="if1zsss" x1="23.436" x2="21.89" y1="12.24" y2="16.67" gradientUnits="userSpaceOnUse"><stop class="lyezpqbcw"/><stop offset="1" class="ppkg-ib8q"/></linearGradient><linearGradient id="ibBGWDb" x1="16.095" x2="16.095" y1="7.541" y2="22.05" gradientUnits="userSpaceOnUse"><stop class="negsnsuet"/><stop offset="1" class="zyd6cdb8l"/></linearGradient><linearGradient id="iYNFiuc" x1="22.132" x2="18.476" y1="17.384" y2="17.228" gradientUnits="userSpaceOnUse"><stop offset=".165" class="m4vrepu0k"/><stop offset="1" class="fqeysxbsz"/></linearGradient><linearGradient id="iSXqPXc" x1="9.834" x2="12.476" y1="15.697" y2="15.791" gradientUnits="userSpaceOnUse"><stop class="xl7yvldha"/><stop offset="1" class="a8q30fbgc"/></linearGradient><linearGradient id="iyg3sde" x1="1.549" x2="1.549" y1="1.191" y2="1.801" gradientUnits="userSpaceOnUse"><stop class="f4-a9nvel"/><stop offset="1" class="gyuwqf8co"/></linearGradient><linearGradient id="ivHpKHe" x1="14.201" x2="14.741" y1="20.045" y2="18.295" gradientUnits="userSpaceOnUse"><stop class="k1gfo1wgd"/><stop offset="1" class="yq3urh0vb"/></linearGradient><linearGradient id="imK6vCc" x1="10.58" x2="11.083" y1="15.714" y2="19.797" gradientUnits="userSpaceOnUse"><stop offset=".765" class="y45ewibqy"/><stop offset=".98" class="whhmayblq"/></linearGradient><linearGradient id="i8KVxLe" x1="21.609" x2="20.421" y1="16.104" y2="19.541" gradientUnits="userSpaceOnUse"><stop offset=".681" class="iup3-2b7t"/><stop offset="1" class="z6kuubbbf"/></linearGradient><linearGradient id="iFCUjAd" x1="8.72" x2="9.342" y1="23.045" y2="23.029" gradientUnits="userSpaceOnUse"><stop class="zbdko4y_s"/><stop offset="1" class="d5osmbc_d"/></linearGradient><linearGradient id="iH2ru6d" x1="5.347" x2="6.407" y1="23.752" y2="23.724" gradientUnits="userSpaceOnUse"><stop class="j614okoao"/><stop offset="1" class="l2cbxb5tg"/></linearGradient><linearGradient id="iIBXVZc" x1="15.854" x2="15.854" y1="13.639" y2="17.014" gradientUnits="userSpaceOnUse"><stop class="odwb5qh_v"/><stop offset="1" class="mneke1b_s"/></linearGradient><linearGradient id="iybPmle" x1="16" x2="16" y1="13.435" y2="14.779" gradientUnits="userSpaceOnUse"><stop class="gfodxacyv"/><stop offset="1" class="cpa1s1b_x"/></linearGradient><linearGradient id="i7xtMae" x1="14.887" x2="15.373" y1="15.67" y2="15.764" gradientUnits="userSpaceOnUse"><stop class="m7a_bec-v"/><stop offset="1" class="th_2jcizb"/></linearGradient><filter id="iDGj9Yb" width="3.209" height="3.209" x="8.582" y="12.667" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2166" stdDeviation=".15"/></filter><filter id="iYmA9Fe" width="3.209" height="3.209" x="20.285" y="12.667" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2166" stdDeviation=".15"/></filter><filter id="iOCpiyd" width="16.62" height="10.603" x="8.455" y="2.976" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.101961 0 0 0 0 0.0823529 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2166"/></filter><filter id="iTsJbjU" width="12.474" height="14.665" x="9.834" y="7.485" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.384314 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2166"/></filter><filter id="i4qSx7c" width="3.885" height="3.935" x="11.447" y="11.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.176471 0 0 0 0 0.0784314 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2166"/></filter><filter id="iMLiW1b" width="3.785" height="3.885" x="16.83" y="11.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.168627 0 0 0 0 0.0784314 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2166"/></filter><filter id="isP9ihc" width="3.799" height="1.588" x="16.873" y="11.869" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.517647 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2166"/></filter><filter id="iqN3aId" width="4.408" height="2.736" x="12.76" y="17.407" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2166" stdDeviation=".05"/></filter><filter id="i51aeCP" width="11.828" height="8.938" x="2.666" y="21.045" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.486275 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2166"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.403922 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_2166" result="effect2_innerShadow_2_2166"/></filter><filter id="iio2uLd" width="11.828" height="8.875" x="17.756" y="21.107" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.486275 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2166"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.403922 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_2166" result="effect2_innerShadow_2_2166"/></filter><filter id="iPuZS3r" width="3.027" height="4.175" x="14.341" y="13.239" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2166" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-zombie" /></template>
<style>
.a7iu9vb1v {
  stop-color: var(--svg-color--4e9191, #4E9191);
}

.a8q30fbgc {
  stop-color: var(--svg-color--75a49f, #75A49F);
  stop-opacity: 0;
}

.aje_gtbfo {
  stop-color: var(--svg-color--608c96, #608C96);
  stop-opacity: 0;
}

.akc2n4bxa {
  stop-color: var(--svg-color--5f969b, #5F969B);
  stop-opacity: 0;
}

.bng_m2b0t {
  stop-color: var(--svg-color--ffaf5a, #FFAF5A);
}

.bw57fdcce {
  stop-color: var(--svg-color--493061, #493061);
}

.bxi9tgmwe {
  stop-color: var(--svg-color--2f5657, #2F5657);
}

.cjzuonbhl {
  fill: var(--svg-color--6a9da1, #6A9DA1);
  d: path("m3.423 27.584l-.757-.68l.703-1.953l.855.648a.1.1 0 0 0 .108.009l.154-.083l-.469-1.777l1.02-1.031l1.164 1.626a.1.1 0 0 0 .134.027l.166-.103l-.218-1.824l1.375-.648l.622 1.427a.226.226 0 0 0 .264.129a.25.25 0 0 0 .181-.231v-.736l1.956.012l.018 3.956c.001.196.092.38.246.5c.167.13.387.166.594.12c.759-.166 1.623-.119 2.048-.013c.422.137.657.451.657.854a.896.896 0 0 1-.896.896h-.62c-.71 0-.945.11-1.648.695c-.563.469-1.443.58-1.813.578H6.173c-1.015 0-1.312-.406-1.64-.773c-.263-.294-.85-1.206-1.11-1.625");
}

.cpa1s1b_x {
  stop-color: var(--svg-color--73a5a5, #73A5A5);
  stop-opacity: 0;
}

.cstpoqe2v {
  d: path("M22.191 15.712a2.2 2.2 0 0 0-.83.241c-.358.19-.67.5-.923.96c-.253.464-.39 1.044-.461 1.568a7.7 7.7 0 0 0-.066 1.313l.45-.021a7 7 0 0 1 .062-1.231c.068-.502.195-1.02.41-1.413c.216-.395.47-.635.74-.779a1.7 1.7 0 0 1 .596-.183z");
}

.cyjy2_b1a {
  fill: var(--svg-color--5f8783, #5F8783);
  d: path("M16 13.436a.51.51 0 0 0-.49.372l-.6 2.18a.65.65 0 0 0 .627.823h.926a.65.65 0 0 0 .627-.823l-.6-2.18a.51.51 0 0 0-.49-.373");
}

.d2h5kyjkp {
  stop-color: var(--svg-color--547986, #547986);
  stop-opacity: 0;
}

.d5osmbc_d {
  stop-color: var(--svg-color--679684, #679684);
  stop-opacity: 0;
}

.dfkyv0s4o {
  stop-color: var(--svg-color--3d567a, #3D567A);
}

.dqs_mibtz {
  stop-color: var(--svg-color--453255, #453255);
  stop-opacity: 0;
}

.dyuoo2b0b {
  cx: 21.89px;
  cy: 14.271px;
  r: 1.305px;
}

.e-l33-bot {
  stop-color: var(--svg-color--81beb9, #81BEB9);
}

.ebc1zfyja {
  stop-color: var(--svg-color--7498a0, #7498A0);
}

.el7r9pbsw {
  r: 1.893px;
}

.enitdihfo {
  stop-color: var(--svg-color--3a2549, #3A2549);
}

.es563lbhm {
  stop-color: var(--svg-color--4f7b7f, #4F7B7F);
  stop-opacity: 0;
}

.exnunbb1a {
  stop-color: var(--svg-color--678ca3, #678CA3);
}

.f4-a9nvel {
  stop-color: var(--svg-color--ffb770, #FFB770);
}

.faf527bpe {
  stop-color: var(--svg-color--63a3a2, #63A3A2);
}

.fk_sd4b3f {
  width: 1.961px;
  height: 3.691px;
  fill: var(--svg-color--5e9886, #5E9886);
  rx: 0.98px;
}

.fq1qgwqrn {
  stop-color: var(--svg-color--476f69, #476F69);
}

.fqeysxbsz {
  stop-color: var(--svg-color--75b8b7, #75B8B7);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fz80s53fc {
  cx: 13.578px;
  cy: 13.527px;
  r: 0.623px;
  fill: var(--svg-color--a01b3c, #A01B3C);
}

.g0ctisbgx {
  width: 1.995px;
  height: 3.756px;
  x: 2.878px;
  y: 22.953px;
  rx: 0.998px;
}

.g3i-1pbcq {
  stop-color: var(--svg-color--e98f43, #E98F43);
}

.gbny4_b4j {
  stop-color: var(--svg-color--74ada5, #74ADA5);
}

.gew0dbs3i {
  stop-color: var(--svg-color--527483, #527483);
  stop-opacity: 0;
}

.gfodxacyv {
  stop-color: var(--svg-color--73a5a5, #73A5A5);
}

.gjthckb9a {
  stop-color: var(--svg-color--6ca895, #6CA895);
}

.gl17utj4l {
  width: 1.995px;
  height: 3.756px;
  rx: 0.998px;
}

.glfls735f {
  stop-color: var(--svg-color--74ada5, #74ADA5);
  stop-opacity: 0;
}

.got22lb_s {
  stop-color: var(--svg-color--7cbcb2, #7CBCB2);
}

.gyuwqf8co {
  stop-color: var(--svg-color--ffb770, #FFB770);
  stop-opacity: 0;
}

.h27flvbap {
  stop-color: var(--svg-color--281b36, #281B36);
}

.h50m5ib7f {
  stop-color: var(--svg-color--ffdf80, #FFDF80);
}

.hbx3qwnwa {
  stop-color: var(--svg-color--e98f43, #E98F43);
  stop-opacity: 0;
}

.hkndu6boi {
  stop-color: var(--svg-color--3d274c, #3D274C);
}

.hq3ckfbkl {
  d: path("M9.148 12.848c.207.651.59.733.743.723l-.058-1.547c0-.293-.014-.684.231-.96s.338-.383.539-.7s.247-1.333.266-1.534s.04-.71.64-.864c3.305-.848 7.636-.38 8.961-.063c.882.211.797.664.914 1.75c.123 1.137.742 1.162.886 1.756c.072.299.021 1.644 0 2.163c.326.05.468-.181.588-.476a9.5 9.5 0 0 0 .593-2.134a.24.24 0 0 1 .331-.189l.341.149a.7.7 0 0 0 .447.034a.67.67 0 0 0 .504-.67c-.059-1.38-.289-2.072-.733-2.645c-.499-.642-1.219-.855-2.215-1.198c-.765-.264-1.88-1.439-1.995-1.563c-.115-.125-.805-.834-1.553-.95c-.748-.114-1.5.128-2.032.23c-.732.142-1.171-.111-2.216-.585c-1.317-.596-2.607-.488-3.671.087c-.675.365-1.113.938-1.395 1.4a.66.66 0 0 0 .168.854c.111.088.247.14.389.149l.243.014l.233.033a.12.12 0 0 1 .03.229c-.67.29-1.716.842-1.845 1.943c-.158 1.342.407 3.749.666 4.563");
}

.ht552mbaq {
  stop-color: var(--svg-color--476676, #476676);
  stop-opacity: 0;
}

.htek_b-aw {
  stop-color: var(--svg-color--72a292, #72A292);
}

.i-ilo59wi {
  stop-color: var(--svg-color--2f545a, #2F545A);
}

.i0xws6gtg {
  width: 1.976px;
  height: 3.721px;
  x: 5.516px;
  y: 21.554px;
  rx: 0.988px;
}

.i2p625zaz {
  stop-color: var(--svg-color--486686, #486686);
}

.i40h4bbfl {
  stop-color: var(--svg-color--4c7684, #4C7684);
}

.i7m2j00fs {
  width: 1.976px;
  height: 3.721px;
  rx: 0.988px;
}

.ij5lprb2c {
  width: 1.988px;
  height: 2.636px;
  rx: 0.994px;
}

.inicu83ai {
  d: path("m28.577 27.584l.757-.68l-.687-1.976l-.87.67a.1.1 0 0 1-.11.01l-.153-.083l.469-1.777l-1.036-1.008l-1.148 1.603a.1.1 0 0 1-.134.027l-.166-.103l.218-1.824l-1.406-.586l-.59 1.365a.226.226 0 0 1-.265.129a.24.24 0 0 1-.175-.225v-.737l-1.962.007l-.018 3.956a.64.64 0 0 1-.246.5a.72.72 0 0 1-.594.12c-.759-.166-1.623-.119-2.048-.013c-.422.137-.657.451-.657.854c0 .495.401.896.896.896h.62c.71 0 .945.11 1.648.695c.563.469 1.443.58 1.813.578h3.094c1.015 0 1.312-.406 1.64-.773c.263-.294.85-1.206 1.11-1.625");
}

.ippisxk_c {
  stop-color: var(--svg-color--679f8d, #679F8D);
}

.iup3-2b7t {
  stop-color: var(--svg-color--5a8092, #5A8092);
}

.iv7v1nb3o {
  stop-color: var(--svg-color--4f8387, #4F8387);
  stop-opacity: 0;
}

.iw38491ye {
  stop-color: var(--svg-color--74ad9d, #74AD9D);
}

.j614okoao {
  stop-color: var(--svg-color--407568, #407568);
}

.ja-c2-y0b {
  cx: 10.187px;
  cy: 14.271px;
  r: 1.305px;
}

.jaguiib4s {
  d: path("M16 13.436a.51.51 0 0 0-.49.372l-.6 2.18a.65.65 0 0 0 .627.823h.926a.65.65 0 0 0 .627-.823l-.6-2.18a.51.51 0 0 0-.49-.373");
}

.jg__x_b3k {
  d: path("m7.5 29.982l-2.077-3.596a11.99 11.99 0 0 1 10.187-5.654h1.375c3.966 0 7.483 1.925 9.668 4.89l-2.517 4.36z");
}

.jjhcfiagl {
  stop-color: var(--svg-color--355d5e, #355D5E);
}

.jmhwzrbhq {
  stop-color: var(--svg-color--678ca3, #678CA3);
  stop-opacity: 0;
}

.ju7pygbji {
  stop-color: var(--svg-color--0d0512, #0D0512);
}

.k1gfo1wgd {
  stop-color: var(--svg-color--678292, #678292);
}

.k589lpbub {
  stop-color: var(--svg-color--79a7af, #79A7AF);
}

.kj71sfbhv {
  width: 1.988px;
  height: 2.636px;
  x: 1.35px;
  y: 25.402px;
  rx: 0.994px;
}

.kyxlbjczl {
  stop-color: var(--svg-color--609180, #609180);
}

.l257jccgu {
  width: 1.976px;
  height: 3.721px;
  fill: var(--svg-color--5e9886, #5E9886);
  rx: 0.988px;
}

.l2cbxb5tg {
  stop-color: var(--svg-color--6c9e8f, #6C9E8F);
  stop-opacity: 0;
}

.la3tbwntj {
  stop-color: var(--svg-color--7cc2b2, #7CC2B2);
  stop-opacity: 0;
}

.libnoft0w {
  stop-color: var(--svg-color--456a60, #456A60);
}

.ll93foxsj {
  cx: 10.187px;
  cy: 14.271px;
  r: 2.031px;
}

.lt6k7o0fo {
  stop-color: var(--svg-color--62a09f, #62A09F);
}

.ltf0tqb9y {
  stop-color: var(--svg-color--684d78, #684D78);
}

.lv9f4sbft {
  stop-color: var(--svg-color--70a196, #70A196);
}

.lvqejss-o {
  width: 1.961px;
  height: 3.691px;
  rx: 0.98px;
}

.lxs7f3b1j {
  stop-color: var(--svg-color--7abfb2, #7ABFB2);
}

.lyezpqbcw {
  stop-color: var(--svg-color--5ba093, #5BA093);
}

.m4vrepu0k {
  stop-color: var(--svg-color--72b6ae, #72B6AE);
}

.m5racngae {
  stop-color: var(--svg-color--76b9a7, #76B9A7);
  stop-opacity: 0;
}

.m7a_bec-v {
  stop-color: var(--svg-color--547b7a, #547B7A);
}

.m7zmv-b2q {
  d: path("M15.854 13.639a.51.51 0 0 0-.49.372l-.6 2.18a.65.65 0 0 0 .627.823h.926a.65.65 0 0 0 .627-.823l-.6-2.18a.51.51 0 0 0-.49-.372");
}

.m8bj1mb9s {
  r: 0.623px;
  fill: var(--svg-color--9e1539, #9E1539);
}

.mneke1b_s {
  stop-color: var(--svg-color--57779e, #57779E);
}

.mrh8oxbyb {
  stop-color: var(--svg-color--5e8a91, #5E8A91);
  stop-opacity: 0;
}

.n3i60zbwo {
  stop-color: var(--svg-color--4c6489, #4C6489);
}

.negsnsuet {
  stop-color: var(--svg-color--7aafac, #7AAFAC);
}

.nrrnwgb2j {
  stop-color: var(--svg-color--291632, #291632);
}

.nxovy29zu {
  stop-color: var(--svg-color--608884, #608884);
  stop-opacity: 0;
}

.o1ng31bsc {
  d: path("m9.89 13.521l-.056-1.497v-.047c-.001-.287-.002-.652.23-.913c.246-.276.338-.383.54-.7c.173-.273.231-1.068.256-1.41l.01-.124l.002-.026c.02-.216.062-.69.637-.838c3.305-.848 7.636-.38 8.961-.063c.77.184.803.552.877 1.364q.015.178.037.386c.074.685.328.966.55 1.212c.146.162.279.308.336.544c.072.299.021 1.644 0 2.163l.028.004l-.242 4.827c-.104 1.188-.898 3.367-3.453 3.57a24 24 0 0 1-2.508.07l-.099.002c-.325.006-1.223.023-2.408-.072c-2.555-.203-3.35-2.382-3.453-3.57z");
}

.o1u4v1x-w {
  stop-color: var(--svg-color--576a91, #576A91);
}

.o39pnqg0i {
  stop-color: var(--svg-color--5c818e, #5C818E);
  stop-opacity: 0;
}

.o5pi4qbos {
  stop-color: var(--svg-color--4d678a, #4D678A);
}

.odwb5qh_v {
  stop-color: var(--svg-color--5c8a89, #5C8A89);
}

.ogpl8rbbb {
  stop-color: var(--svg-color--ffcf77, #FFCF77);
}

.oi5b6vt4l {
  stop-color: var(--svg-color--669688, #669688);
  stop-opacity: 0;
}

.oukb_nb4n {
  stop-color: var(--svg-color--586d77, #586D77);
  stop-opacity: 0;
}

.oxi0f3b2m {
  stop-color: var(--svg-color--72b4aa, #72B4AA);
}

.p-lt9kb3w {
  stop-color: var(--svg-color--546672, #546672);
}

.p0u5ydomu {
  stop-color: var(--svg-color--60829e, #60829E);
  stop-opacity: 0;
}

.p7xh8mbkr {
  stop-color: var(--svg-color--7eb7ae, #7EB7AE);
}

.pkku2fbqv {
  d: path("M12.96 18.775c0-.645.523-1.168 1.168-1.168h.504a2.336 2.336 0 0 1 2.336 2.336h-2.84a1.17 1.17 0 0 1-1.168-1.168");
}

.pky976qgh {
  d: path("m3.423 27.584l-.757-.68l.703-1.953l.855.648a.1.1 0 0 0 .108.009l.154-.083l-.469-1.777l1.02-1.031l1.164 1.626a.1.1 0 0 0 .134.027l.166-.103l-.218-1.824l1.375-.648l.622 1.427a.226.226 0 0 0 .264.129a.25.25 0 0 0 .181-.231v-.736l1.956.012l.018 3.956c.001.196.092.38.246.5c.167.13.387.166.594.12c.759-.166 1.623-.119 2.048-.013c.422.137.657.451.657.854a.896.896 0 0 1-.896.896h-.62c-.71 0-.945.11-1.648.695c-.563.469-1.443.58-1.813.578H6.173c-1.015 0-1.312-.406-1.64-.773c-.263-.294-.85-1.206-1.11-1.625");
}

.ppkg-ib8q {
  stop-color: var(--svg-color--567d99, #567D99);
}

.q0bx3-bma {
  stop-color: var(--svg-color--3c5a52, #3C5A52);
}

.q2o6fx2nz {
  stop-color: var(--svg-color--50608c, #50608C);
}

.q3lmwvq-b {
  stop-color: var(--svg-color--3e244c, #3E244C);
}

.q53_zdbrw {
  stop-color: var(--svg-color--54958b, #54958B);
}

.qhidatbjk {
  stop-color: var(--svg-color--422451, #422451);
}

.qzo_nkzbd {
  stop-color: var(--svg-color--476676, #476676);
}

.r_m0m432l {
  fill: var(--svg-color--618c93, #618C93);
  d: path("m28.577 27.584l.757-.68l-.687-1.976l-.87.67a.1.1 0 0 1-.11.01l-.153-.083l.469-1.777l-1.036-1.008l-1.148 1.603a.1.1 0 0 1-.134.027l-.166-.103l.218-1.824l-1.406-.586l-.59 1.365a.226.226 0 0 1-.265.129a.24.24 0 0 1-.175-.225v-.737l-1.962.007l-.018 3.956a.64.64 0 0 1-.246.5a.72.72 0 0 1-.594.12c-.759-.166-1.623-.119-2.048-.013c-.422.137-.657.451-.657.854c0 .495.401.896.896.896h.62c.71 0 .945.11 1.648.695c.563.469 1.443.58 1.813.578h3.094c1.015 0 1.312-.406 1.64-.773c.263-.294.85-1.206 1.11-1.625");
}

.rdi-wfxqd {
  stop-color: var(--svg-color--586590, #586590);
}

.rrdpflbyy {
  stop-color: var(--svg-color--588290, #588290);
  stop-opacity: 0;
}

.rvq6gmb5w {
  stop-color: var(--svg-color--070608, #070608);
}

.s9595bb6g {
  stop-color: var(--svg-color--7cc2b2, #7CC2B2);
}

.sce_y6bah {
  stop-color: var(--svg-color--396f65, #396F65);
}

.sl7iwijia {
  stop-color: var(--svg-color--396f65, #396F65);
  stop-opacity: 0;
}

.slfwwoboa {
  stop-color: var(--svg-color--6ba18f, #6BA18F);
  stop-opacity: 0;
}

.so0nfjs_n {
  stop-color: var(--svg-color--7eb7ae, #7EB7AE);
  stop-opacity: 0;
}

.svm3t3bnk {
  stop-color: var(--svg-color--476f69, #476F69);
  stop-opacity: 0;
}

.t3gf2pooa {
  width: 4.969px;
  height: 6.172px;
  x: 13.516px;
  y: 18.186px;
  rx: 2.484px;
}

.th_2jcizb {
  stop-color: var(--svg-color--6c9b96, #6C9B96);
  stop-opacity: 0;
}

.tk9x5nw_u {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.96 18.775c0-.645.523-1.168 1.168-1.168h.504a2.336 2.336 0 0 1 2.336 2.336h-2.84a1.17 1.17 0 0 1-1.168-1.168Z");
}

.tn-w78xgx {
  stop-color: var(--svg-color--619299, #619299);
  stop-opacity: 0;
}

.u5uc3vg4f {
  cx: 13.559px;
  cy: 13.527px;
  r: 1.549px;
}

.u84zz4ukw {
  stop-color: var(--svg-color--7abfb2, #7ABFB2);
  stop-opacity: 0;
}

.u8epgmbkl {
  stop-color: var(--svg-color--75b4b1, #75B4B1);
  stop-opacity: 0;
}

.uaafun-3k {
  stop-color: var(--svg-color--422451, #422451);
  stop-opacity: 0;
}

.udi_mfp4v {
  stop-color: var(--svg-color--351c47, #351C47);
}

.ult0y8bvs {
  stop-color: var(--svg-color--586d77, #586D77);
}

.uvhjscb1o {
  width: 1.995px;
  height: 3.756px;
  fill: var(--svg-color--5e9886, #5E9886);
  rx: 0.998px;
}

.v1f5judsg {
  stop-color: var(--svg-color--453255, #453255);
}

.v62k80b2s {
  stroke: var(--svg-color--2f1b37, #2F1B37);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-15px, 1.15px);
  d: path("M11.805 11.54c.284-.244 1.105-.683 2.101-.554m6.289.554c-.284-.244-1.105-.683-2.101-.554");
}

.ve2ow0b5f {
  stop-color: var(--svg-color--508f82, #508F82);
}

.vl_ql576y {
  stop-color: var(--svg-color--659ea4, #659EA4);
  stop-opacity: 0;
}

.vsdiecbqp {
  stop-color: var(--svg-color--4a6171, #4A6171);
}

.w0ry1tv8g {
  stop-color: var(--svg-color--ffb45c, #FFB45C);
}

.whhmayblq {
  stop-color: var(--svg-color--4f6f7e, #4F6F7E);
  stop-opacity: 0;
}

.wjd3pjbpb {
  stop-color: var(--svg-color--5856a4, #5856A4);
}

.woms0-bkw {
  stop-color: var(--svg-color--4d6999, #4D6999);
}

.ws-ofvbpp {
  stop-color: var(--svg-color--608d97, #608D97);
  stop-opacity: 0;
}

.x4_rgjbgr {
  stop-color: var(--svg-color--709d99, #709D99);
}

.x9syn5bsf {
  stop-color: var(--svg-color--6fa293, #6FA293);
}

.xjomt31wk {
  stop-color: var(--svg-color--6c8ea7, #6C8EA7);
  stop-opacity: 0;
}

.xl7yvldha {
  stop-color: var(--svg-color--75a49f, #75A49F);
}

.xq9watbjp {
  stop-color: var(--svg-color--7dc3b4, #7DC3B4);
}

.xtyrtq_4k {
  cx: 21.89px;
  cy: 14.271px;
  r: 2.031px;
}

.y2c1oq0fx {
  r: 1.549px;
}

.y45ewibqy {
  stop-color: var(--svg-color--4f6f7e, #4F6F7E);
}

.y7wl_rbeg {
  cx: 13.34px;
  cy: 13.762px;
  r: 1.893px;
}

.y7xy7bb_m {
  stop-color: var(--svg-color--526c9e, #526C9E);
}

.ydv3enbju {
  fill-rule: evenodd;
  d: path("M10.023 16.178q.292.042.548.176c.27.144.524.384.74.78c.215.392.342.91.41 1.412c.067.498.075.96.062 1.23l.45.021a7.7 7.7 0 0 0-.066-1.312c-.072-.524-.208-1.105-.461-1.568c-.253-.461-.566-.77-.923-.96A2.2 2.2 0 0 0 10 15.72z");
}

.yfpl-j8nb {
  stop-color: var(--svg-color--6688b2, #6688B2);
  stop-opacity: 0;
}

.yps5thqls {
  stop-color: var(--svg-color--466082, #466082);
}

.yq3urh0vb {
  stop-color: var(--svg-color--6182a0, #6182A0);
}

.yqk_xqsqr {
  fill: var(--svg-color--fba65c, #FBA65C);
  d: path("M16.436 18.459h-2.098a.3.3 0 0 1-.3-.3v-.548q.045-.004.09-.004h.504c.726 0 1.375.332 1.804.852");
}

.ywetm9lbn {
  stop-color: var(--svg-color--5f969b, #5F969B);
}

.z2o3bacur {
  width: 1.961px;
  height: 3.691px;
  x: 8.72px;
  y: 21.002px;
  rx: 0.98px;
}

.z6kuubbbf {
  stop-color: var(--svg-color--5a8092, #5A8092);
  stop-opacity: 0;
}

.zbdko4y_s {
  stop-color: var(--svg-color--3e6d60, #3E6D60);
}

.zl7ptbcaa {
  stop-color: var(--svg-color--629f8d, #629F8D);
}

.zm9-51tyy {
  d: path("M20.572 13.357h-3.698a1.893 1.893 0 0 1 3.698 0");
}

.zpxnljbfi {
  d: path("M16.436 18.459h-2.098a.3.3 0 0 1-.3-.3v-.548q.045-.004.09-.004h.504c.726 0 1.375.332 1.804.852");
}

.zyd6cdb8l {
  stop-color: var(--svg-color--719da0, #719DA0);
}

</style>
