<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ivCOAAc)" class="u-fne8bwx"/><path fill="url(#i4DzNre)" class="u-fne8bwx"/><path fill="url(#i2x6gIb)" class="ems5cpbom"/><path fill="url(#i7imyWb)" class="ems5cpbom"/><path fill="url(#ipLlk7j)" class="ems5cpbom"/><path fill="url(#iOPK1He)" class="ems5cpbom"/><path fill="url(#iEUzkWh)" class="ems5cpbom"/><g filter="url(#i0psl8d)"><path class="ldu426b8x"/></g><path fill="url(#irvJ6zt)" class="h0drrmbyw"/><path fill="url(#i35zy3d)" class="h0drrmbyw"/><path fill="url(#if6PVOd)" class="h0drrmbyw"/><g filter="url(#iEhPiab)"><path fill="url(#ibhQNUc)" class="bsiog7b5a"/></g><path fill="url(#itPfbpd)" clip-rule="evenodd" class="q5087sbmq"/><g filter="url(#iR6f4cd)"><path stroke="url(#i0Mn64c)" class="cd3t91bxc"/></g><path fill="url(#iSB8q1d)" class="dpb8nmb_i"/><path fill="url(#iCetv2J)" class="dpb8nmb_i"/><path fill="url(#inwybnb)" class="dpb8nmb_i"/><g filter="url(#iUF4j8m)"><path fill="url(#iLES4Cb)" class="rn-t0rb0y"/></g><g filter="url(#idEBaVc)"><path fill="url(#iSewEFc)" class="uagq7j3nj"/></g><path fill="url(#ijn3Wkd)" class="hdqy_ks_x"/><path fill="url(#iqoQe1b)" class="jkxz01uwy"/><path fill="url(#iT7aiAc)" class="jkxz01uwy"/><path fill="url(#iM0IAGd)" class="jkxz01uwy"/><path fill="url(#i0kwS2b)" transform="rotate(7.73 23.43 10.855)" class="awio_2bar"/><g filter="url(#iy1y4vc)"><path fill="url(#iBjIhId)" class="qz7rikoqh"/><path fill="url(#itYn3qe)" class="qz7rikoqh"/></g><path fill="url(#inbVbMd)" clip-rule="evenodd" class="b-1q4qbml"/><path fill="url(#irQdbAc)" clip-rule="evenodd" class="lkkvj6btb"/><path fill="url(#if8BLse)" clip-rule="evenodd" class="lkkvj6btb"/><path clip-rule="evenodd" class="eiq4kwpiv"/><g filter="url(#ifwZnwb)"><path class="tur7wrfly"/><path fill="url(#i2OoXrq)" class="g2a7rn75y"/></g><path class="va9cd6b6q"/><path class="brl2tm-6u"/><path fill="url(#i46VoPe)" class="woj4y6m6m"/><path fill="url(#itiUJKc)" class="woj4y6m6m"/><path class="b4obhqdys"/><path fill="url(#imm3tCW)" class="aqvrw7bju"/><path fill="url(#iNc8Onc)" class="aqvrw7bju"/><path fill="url(#i84T8Hc)" class="aqvrw7bju"/><path fill="url(#iLgoP8c)" class="aqvrw7bju"/><path fill="url(#ibAIcrd)" class="etm0d-24x"/><path class="dof33bbqn"/><circle class="adasqxbiy"/><path fill="url(#ioBpkbe)" class="kf9kmgbpk"/><path fill="url(#iaSjFvF)" class="kf9kmgbpk"/><path fill="url(#iuR5zBb)" class="kf9kmgbpk"/><path fill="url(#iaQhSzc)" class="kf9kmgbpk"/><path fill="url(#iovicNe)" class="kf9kmgbpk"/><g filter="url(#iv7DbNb)"><path class="i9ep8rbrn"/><path fill="url(#iBzdIhe)" class="no0-xjbmh"/><path fill="url(#ibAVctc)" class="no0-xjbmh"/><path fill="url(#ip3qFuc)" class="no0-xjbmh"/></g><g filter="url(#iwRb2Be)"><path class="o3cxmzbrw"/><path fill="url(#i8aInDe)" class="ipt6hdesj"/></g><g filter="url(#i1mYqOb)"><path class="hopfogb6a"/><path fill="url(#i06I5zc)" class="v1low-dfl"/><path fill="url(#izd9syd)" class="v1low-dfl"/><path fill="url(#iBkVrGT)" class="v1low-dfl"/></g><g filter="url(#i2zhBeA)"><path class="bva5w7bnk"/><path fill="url(#i06I5zc)" class="v1low-dfl"/><path fill="url(#izd9syd)" class="v1low-dfl"/><path fill="url(#iBkVrGT)" class="v1low-dfl"/></g><g filter="url(#ir3wzhe)"><path class="rmq-p8bwk"/><path fill="url(#i5x0fGL)" class="kxfk1zmbn"/></g><path fill="url(#iu7w5pt)" clip-rule="evenodd" class="z6c-cwb3w"/><path fill="url(#iWIFrqd)" clip-rule="evenodd" class="z6c-cwb3w"/><path fill="url(#ieh0ffp)" clip-rule="evenodd" class="z6c-cwb3w"/><path class="z460z2cnm"/><path fill="url(#iQFPIHd)" class="tc6eb3_7m"/><path class="x2qxulb2k"/><path fill="url(#iiYlCcd)" class="vc966g90j"/><path class="jpfpjd-4z"/><path fill="url(#if8ekld)" class="fi7tv3bhp"/><path class="hgd30nbxf"/><path fill="url(#iUxFype)" class="c36r2-bpd"/><circle fill="url(#in897ke)" class="llwjz8b5t"/><path clip-rule="evenodd" class="g8e5hfbak"/><path fill="url(#i3CWbSd)" clip-rule="evenodd" class="t931osbxo"/><path fill="url(#ioxO5Cc)" clip-rule="evenodd" class="t931osbxo"/><path fill="url(#iKJ7Wad)" clip-rule="evenodd" class="t931osbxo"/><g filter="url(#ia2dkgd)"><path fill="url(#iEN3YUd)" class="fq8v5ccfv"/></g><g filter="url(#isWUJbc)"><path fill="url(#iGqohLb)" class="po5p7izon"/></g><path class="oyx3ieb6e"/><path fill="url(#idGjpBd)" class="dgu55jodb"/><g filter="url(#iKgaIFx)"><path clip-rule="evenodd" class="yiv1s6b4r"/></g><path fill="url(#iwUqwFd)" class="wj6zzlb9k"/><path fill="url(#iGJwTnb)" class="wj6zzlb9k"/><path fill="url(#i4nVrAd)" class="wj6zzlb9k"/><path fill="url(#il76bOb)" class="ad54zqbdl"/><path fill="url(#iWtoccc)" class="ad54zqbdl"/><path fill="url(#i3u19Nd)" class="ad54zqbdl"/><path class="woxmm4b5l"/><path class="y_9n-yf2a"/><defs><radialGradient id="ivCOAAc" cx="0" cy="0" r="1" gradientTransform="matrix(1.4063 -8.03125 17.4103 3.0486 7.205 28.553)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="t-qeblb7d"/><stop offset="1" class="nkzm4gb5h"/></radialGradient><radialGradient id="ipLlk7j" cx="0" cy="0" r="1" gradientTransform="rotate(-83.29 17.074 5.38)scale(2.67447 5.21781)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="mmu9u7bsf"/><stop offset="1" class="tylpo8bot"/></radialGradient><radialGradient id="iOPK1He" cx="0" cy="0" r="1" gradientTransform="rotate(155.431 2.997 10.63)scale(1.5806 2.92056)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="n7r2-292q"/><stop offset=".695" class="n_3yhnb8a"/></radialGradient><radialGradient id="iEUzkWh" cx="0" cy="0" r="1" gradientTransform="matrix(5.21875 -2.75 .52109 .98889 3.611 21.427)" gradientUnits="userSpaceOnUse"><stop offset=".457" class="vp6yj4xxl"/><stop offset="1" class="rdr27y14e"/></radialGradient><radialGradient id="if6PVOd" cx="0" cy="0" r="1" gradientTransform="rotate(174.89 9.339 5.28)scale(3.85909 10.4756)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="nmynr_cvx"/><stop offset="1" class="p2417ob0x"/></radialGradient><radialGradient id="itPfbpd" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 5.5625 -3.9363 .81822 20.018 7.24)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="q4ysocc-i"/><stop offset=".884" class="q264kdbup"/></radialGradient><radialGradient id="iCetv2J" cx="0" cy="0" r="1" gradientTransform="matrix(9.95983 -3.00679 4.88716 16.18849 2.054 8.59)" gradientUnits="userSpaceOnUse"><stop offset=".897" class="sf7z4ybcf"/><stop offset=".982" class="bpm5gvbdi"/></radialGradient><radialGradient id="iLES4Cb" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 -.8125 1.05147 3.72059 12.861 7.427)" gradientUnits="userSpaceOnUse"><stop offset=".275" class="reex3410h"/><stop offset="1" class="wlyubdb4v"/></radialGradient><radialGradient id="ijn3Wkd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00002 .65234 -.82062 -.00003 22.572 8.13)" gradientUnits="userSpaceOnUse"><stop offset=".515" class="gbpc64bji"/><stop offset="1" class="ovz69fb_x"/></radialGradient><radialGradient id="iT7aiAc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17188 1.40443 0 25.252 21.63)" gradientUnits="userSpaceOnUse"><stop class="amik16rrq"/><stop offset="1" class="ibka94bwi"/></radialGradient><radialGradient id="iM0IAGd" cx="0" cy="0" r="1" gradientTransform="matrix(.39063 .6836 -1.70288 .97308 24.174 19.15)" gradientUnits="userSpaceOnUse"><stop class="nwhi_fa4f"/><stop offset="1" class="vps27w8pe"/></radialGradient><radialGradient id="i0kwS2b" cx="0" cy="0" r="1" gradientTransform="matrix(.00508 -1.12418 .93572 .00423 24.738 11.924)" gradientUnits="userSpaceOnUse"><stop class="vx6_akbll"/><stop offset="1" class="crx2hg4yh"/></radialGradient><radialGradient id="iBjIhId" cx="0" cy="0" r="1" gradientTransform="matrix(2.03124 1.96875 -2.04192 2.10673 22.862 8.724)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="b8g00zlka"/><stop offset="1" class="z7m9rdbog"/></radialGradient><radialGradient id="itYn3qe" cx="0" cy="0" r="1" gradientTransform="rotate(119.268 10.177 11.917)scale(1.62995 1.31525)" gradientUnits="userSpaceOnUse"><stop class="iooxo1wql"/><stop offset="1" class="hlbcv5m7e"/></radialGradient><radialGradient id="if8BLse" cx="0" cy="0" r="1" gradientTransform="matrix(-.05078 .15625 -1.00516 -.32667 25.709 19.521)" gradientUnits="userSpaceOnUse"><stop class="tslw4_1qu"/><stop offset="1" class="ijj8_s6sp"/></radialGradient><radialGradient id="i2OoXrq" cx="0" cy="0" r="1" gradientTransform="matrix(-.7533 -.625 .19855 -.2393 25.82 10.813)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="jsa0_reur"/><stop offset="1" class="l-nb061ot"/></radialGradient><radialGradient id="itiUJKc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.23438 -.90624 .39526 -.97452 21.344 22)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="m1yqw3kzt"/><stop offset="1" class="afdr7o0yz"/></radialGradient><radialGradient id="imm3tCW" cx="0" cy="0" r="1" gradientTransform="rotate(-144.462 16.075 9.97)scale(.80647 2.46844)" gradientUnits="userSpaceOnUse"><stop class="kt6hdg08n"/><stop offset="1" class="j-c4i6bgu"/></radialGradient><radialGradient id="iNc8Onc" cx="0" cy="0" r="1" gradientTransform="rotate(-171.191 12.694 13.273)scale(2.03585 4.1214)" gradientUnits="userSpaceOnUse"><stop offset=".54" class="ylvew1phe"/><stop offset="1" class="rlbn0jwxx"/></radialGradient><radialGradient id="iLgoP8c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.85938 -.29686 .97701 -6.1195 22.799 28.24)" gradientUnits="userSpaceOnUse"><stop offset=".604" class="uuc-lrj5h"/><stop offset="1" class="shmkg3ete"/></radialGradient><radialGradient id="iaSjFvF" cx="0" cy="0" r="1" gradientTransform="rotate(136.273 9.993 11.696)scale(2.98384 2.4723)" gradientUnits="userSpaceOnUse"><stop class="qksuzsbug"/><stop offset="1" class="se__e0blq"/></radialGradient><radialGradient id="iuR5zBb" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 1.35937 -3.85802 .79821 23.549 11.724)" gradientUnits="userSpaceOnUse"><stop class="jfz0xgwum"/><stop offset="1" class="k2u_13bdd"/></radialGradient><radialGradient id="iaQhSzc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.06251 1.12498 -.6497 -1.19113 22.627 14.1)" gradientUnits="userSpaceOnUse"><stop class="n_geicc-w"/><stop offset="1" class="bn_1vkbwm"/></radialGradient><radialGradient id="iovicNe" cx="0" cy="0" r="1" gradientTransform="matrix(.98437 .46875 -1.87887 3.94563 21.205 15.255)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="nvv1klhll"/><stop offset="1" class="ilft87v6y"/></radialGradient><radialGradient id="iBzdIhe" cx="0" cy="0" r="1" gradientTransform="matrix(1.64062 -2.32812 1.8984 1.3378 20.393 21.771)" gradientUnits="userSpaceOnUse"><stop class="mr6mdpt1g"/><stop offset="1" class="jbbp6_bdq"/></radialGradient><radialGradient id="ibAVctc" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 .48438 -1.05948 1.43542 19.94 19.646)" gradientUnits="userSpaceOnUse"><stop class="pids_pbns"/><stop offset="1" class="xzhs54baa"/></radialGradient><radialGradient id="ip3qFuc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.875 1.75 -.85312 -.91406 21.814 19.568)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="tvjmrrbpc"/><stop offset="1" class="ahho1w97n"/></radialGradient><radialGradient id="i06I5zc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.25 -1.34374 .47918 -1.15897 22.299 17.834)" gradientUnits="userSpaceOnUse"><stop class="kao1--wwn"/><stop offset="1" class="lykybbi9r"/></radialGradient><radialGradient id="iBkVrGT" cx="0" cy="0" r="1" gradientTransform="matrix(-.29687 .53125 -3.08778 -1.7255 23.002 17.177)" gradientUnits="userSpaceOnUse"><stop class="ws0t5un5c"/><stop offset="1" class="t20d06bem"/></radialGradient><radialGradient id="i5x0fGL" cx="0" cy="0" r="1" gradientTransform="matrix(.92186 -1.28125 2.36816 1.7039 10.236 19.333)" gradientUnits="userSpaceOnUse"><stop offset=".68" class="ps4wek9uf"/><stop offset=".964" class="mwbu5sbnw"/></radialGradient><radialGradient id="ieh0ffp" cx="0" cy="0" r="1" gradientTransform="matrix(1.21875 .67969 -.21221 .38051 20.658 16.13)" gradientUnits="userSpaceOnUse"><stop class="uubye-mwc"/><stop offset="1" class="gu1w6obkb"/></radialGradient><radialGradient id="iQFPIHd" cx="0" cy="0" r="1" gradientTransform="matrix(.70312 -.09375 .03207 .24052 19.68 6.734)" gradientUnits="userSpaceOnUse"><stop class="z4zbxthsh"/><stop offset="1" class="egb5_lbyf"/></radialGradient><radialGradient id="in897ke" cx="0" cy="0" r="1" gradientTransform="rotate(83.69 7.388 18.684)scale(.81745)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="p1xawgtbo"/><stop offset="1" class="xoq-ina2u"/></radialGradient><radialGradient id="iKJ7Wad" cx="0" cy="0" r="1" gradientTransform="matrix(.13672 .11328 -.664 .80138 24.65 9.63)" gradientUnits="userSpaceOnUse"><stop class="pav55masc"/><stop offset="1" class="egqy8jbwr"/></radialGradient><radialGradient id="iEN3YUd" cx="0" cy="0" r="1" gradientTransform="rotate(129.693 11.552 9.88)scale(2.03059 2.38667)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="w9h_a4buy"/><stop offset=".919" class="jvvv5bmeo"/></radialGradient><radialGradient id="iGqohLb" cx="0" cy="0" r="1" gradientTransform="matrix(.36719 -.45312 1.162 .94164 25.36 8.334)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="chmofghwi"/><stop offset="1" class="tn7myqe_j"/></radialGradient><radialGradient id="iwUqwFd" cx="0" cy="0" r="1" gradientTransform="rotate(-160.017 12.389 6.898)scale(3.29195 1.49462)" gradientUnits="userSpaceOnUse"><stop class="zf7t0yb1u"/><stop offset="1" class="jpzdg-bwz"/></radialGradient><radialGradient id="iGJwTnb" cx="0" cy="0" r="1" gradientTransform="matrix(1.15626 -3.3125 9.2644 3.23382 19.44 19.585)" gradientUnits="userSpaceOnUse"><stop offset=".771" class="nuwcoob-p"/><stop offset="1" class="gzdogx1hl"/></radialGradient><radialGradient id="i4nVrAd" cx="0" cy="0" r="1" gradientTransform="rotate(78.869 -2.136 19.705)scale(2.50907 .7401)" gradientUnits="userSpaceOnUse"><stop class="r8uyz9bqp"/><stop offset="1" class="f2xkzabrk"/></radialGradient><radialGradient id="il76bOb" cx="0" cy="0" r="1" gradientTransform="rotate(98.903 6.254 16.083)scale(2.42307 5.69158)" gradientUnits="userSpaceOnUse"><stop offset=".274" class="o6w7f1w7w"/><stop offset="1" class="v5m-xebtg"/></radialGradient><radialGradient id="i3u19Nd" cx="0" cy="0" r="1" gradientTransform="matrix(-.92187 .21875 -.25309 -1.06657 24.393 13.052)" gradientUnits="userSpaceOnUse"><stop class="xapik5b0z"/><stop offset="1" class="npx64-mvq"/></radialGradient><linearGradient id="i4DzNre" x1="11.136" x2="11.136" y1="30.099" y2="28.804" gradientUnits="userSpaceOnUse"><stop class="c3098ubep"/><stop offset="1" class="hujbubc9t"/></linearGradient><linearGradient id="i2x6gIb" x1="5.018" x2="6.174" y1="17.677" y2="20.959" gradientUnits="userSpaceOnUse"><stop offset=".373" class="gpdazcbld"/><stop offset="1" class="afg7wtasa"/></linearGradient><linearGradient id="i7imyWb" x1="5.518" x2="5.861" y1="17.677" y2="18.646" gradientUnits="userSpaceOnUse"><stop offset=".142" class="f2yuiwowd"/><stop offset="1" class="zp0x88wix"/></linearGradient><linearGradient id="irvJ6zt" x1="13.111" x2="11.268" y1="1.99" y2="15.115" gradientUnits="userSpaceOnUse"><stop offset=".518" class="bpm5gvbdi"/><stop offset="1" class="njdjvcttb"/></linearGradient><linearGradient id="i35zy3d" x1="2.299" x2="12.83" y1="17.865" y2="13.709" gradientUnits="userSpaceOnUse"><stop offset=".293" class="boi6lnlog"/><stop offset="1" class="ybn2mcbio"/></linearGradient><linearGradient id="ibhQNUc" x1="13.967" x2="16.568" y1="10.816" y2="15.334" gradientUnits="userSpaceOnUse"><stop offset=".368" class="d6jlrzbaa"/><stop offset="1" class="w5vd7udwg"/></linearGradient><linearGradient id="i0Mn64c" x1="19.16" x2="21.086" y1="8.243" y2="11.402" gradientUnits="userSpaceOnUse"><stop class="y6k--c7ym"/><stop offset="1" class="v26q47bkt"/></linearGradient><linearGradient id="iSB8q1d" x1="4.205" x2="6.58" y1="5.396" y2="13.677" gradientUnits="userSpaceOnUse"><stop class="mn787q_6r"/><stop offset="1" class="mzz_2wq-t"/></linearGradient><linearGradient id="inwybnb" x1="5.486" x2="5.205" y1="14.287" y2="13.287" gradientUnits="userSpaceOnUse"><stop class="t20fa7b7o"/><stop offset="1" class="e2k-esbpn"/></linearGradient><linearGradient id="iSewEFc" x1="19.274" x2="20.633" y1="11.098" y2="15.758" gradientUnits="userSpaceOnUse"><stop class="eky141x3a"/><stop offset="1" class="dfv3zlvmf"/></linearGradient><linearGradient id="iqoQe1b" x1="24.799" x2="26.205" y1="20.443" y2="20.443" gradientUnits="userSpaceOnUse"><stop class="v5_ahxl8w"/><stop offset="1" class="os32btykc"/></linearGradient><linearGradient id="inbVbMd" x1="24.573" x2="24.299" y1="18.705" y2="18.705" gradientUnits="userSpaceOnUse"><stop offset=".269" class="x9rbvhxej"/><stop offset="1" class="biyiff5mh"/></linearGradient><linearGradient id="irQdbAc" x1="26.189" x2="24.173" y1="19.983" y2="19.146" gradientUnits="userSpaceOnUse"><stop class="dnpfueb4s"/><stop offset="1" class="e_59tbbed"/></linearGradient><linearGradient id="i46VoPe" x1="22.5" x2="21.375" y1="25.438" y2="26" gradientUnits="userSpaceOnUse"><stop offset=".267" class="bnldzacmr"/><stop offset="1" class="e9dmvq9mi"/></linearGradient><linearGradient id="i84T8Hc" x1="22.959" x2="22.854" y1="28.064" y2="27.982" gradientUnits="userSpaceOnUse"><stop class="fiw9fyalo"/><stop offset="1" class="n7jws8bws"/></linearGradient><linearGradient id="ibAIcrd" x1="23.357" x2="23.604" y1="8.388" y2="7.951" gradientUnits="userSpaceOnUse"><stop class="bie0h0-8q"/><stop offset="1" class="fwnzc4ctw"/></linearGradient><linearGradient id="ioBpkbe" x1="24.58" x2="22.393" y1="15.958" y2="12.146" gradientUnits="userSpaceOnUse"><stop class="af5ecjb0e"/><stop offset="1" class="bg5vqlb1m"/></linearGradient><linearGradient id="i8aInDe" x1="13.875" x2="14.5" y1="17" y2="17.999" gradientUnits="userSpaceOnUse"><stop class="ti929abbi"/><stop offset="1" class="nerh9eh2b"/></linearGradient><linearGradient id="izd9syd" x1="19.83" x2="20.799" y1="20.247" y2="17.271" gradientUnits="userSpaceOnUse"><stop class="msti5wbjw"/><stop offset="1" class="gepa-4uov"/></linearGradient><linearGradient id="iu7w5pt" x1="22.801" x2="22.801" y1="16.834" y2="18.271" gradientUnits="userSpaceOnUse"><stop class="b06izibxm"/><stop offset="1" class="jn6chbb5g"/></linearGradient><linearGradient id="iWIFrqd" x1="23.994" x2="24.225" y1="18.361" y2="17.916" gradientUnits="userSpaceOnUse"><stop offset=".457" class="qd-f9ooxs"/><stop offset="1" class="fy9sosv6u"/></linearGradient><linearGradient id="iiYlCcd" x1="15.315" x2="15.643" y1="11.857" y2="11.474" gradientUnits="userSpaceOnUse"><stop offset=".002" class="zbfwxqbqy"/><stop offset="1" class="foshnm2dn"/></linearGradient><linearGradient id="if8ekld" x1="15.523" x2="15.918" y1="11.428" y2="10.967" gradientUnits="userSpaceOnUse"><stop offset=".002" class="zbfwxqbqy"/><stop offset="1" class="foshnm2dn"/></linearGradient><linearGradient id="iUxFype" x1="15.789" x2="16.226" y1="11.032" y2="10.513" gradientUnits="userSpaceOnUse"><stop offset=".002" class="zbfwxqbqy"/><stop offset="1" class="foshnm2dn"/></linearGradient><linearGradient id="i3CWbSd" x1="24.643" x2="24.322" y1="9.984" y2="9.74" gradientUnits="userSpaceOnUse"><stop class="zcigs7bii"/><stop offset="1" class="nr87if9lw"/></linearGradient><linearGradient id="ioxO5Cc" x1="23.189" x2="23.627" y1="10.537" y2="10.826" gradientUnits="userSpaceOnUse"><stop offset=".324" class="x0zx5qyer"/><stop offset="1" class="k6zficbhz"/></linearGradient><linearGradient id="idGjpBd" x1="16.207" x2="16.651" y1="10.804" y2="10.359" gradientUnits="userSpaceOnUse"><stop offset=".002" class="zbfwxqbqy"/><stop offset="1" class="foshnm2dn"/></linearGradient><linearGradient id="iWtoccc" x1="22.908" x2="22.783" y1="14.865" y2="13.943" gradientUnits="userSpaceOnUse"><stop class="wd5xhxb1x"/><stop offset="1" class="r_k29qxtj"/></linearGradient><filter id="i0psl8d" width="8.743" height="7.346" x="1.654" y="23.154" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.607843 0 0 0 0 0.670588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_852"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.831373 0 0 0 0 0.862745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_852" result="effect2_innerShadow_4002_852"/></filter><filter id="iEhPiab" width="4.276" height="5.599" x="13.043" y="9.473" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_852" stdDeviation=".375"/></filter><filter id="iR6f4cd" width="2.679" height="4.12" x="18.714" y="7.398" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_852" stdDeviation=".15"/></filter><filter id="iUF4j8m" width="3.479" height="7.738" x="13.618" y="2.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.02" dy="-.06"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.792157 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_852"/></filter><filter id="idEBaVc" width="2.822" height="15.029" x="18.984" y="2.154" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.47451 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_852"/></filter><filter id="iy1y4vc" width="4.68" height="4.407" x="21.69" y="7.138" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.0980392 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_852"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.278431 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_852" result="effect2_innerShadow_4002_852"/></filter><filter id="ifwZnwb" width="2.054" height="2.454" x="25.067" y="9.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0156863 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_852"/></filter><filter id="iv7DbNb" width="5.527" height="3.544" x="18.662" y="18.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.4 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_852"/></filter><filter id="iwRb2Be" width="9.577" height="5.489" x="9.343" y="15.129" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.152941 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_852"/></filter><filter id="i1mYqOb" width="6.672" height="5.002" x="17.83" y="15.246" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.372549 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_852"/></filter><filter id="i2zhBeA" width="6.922" height="5.002" x="17.83" y="15.246" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.364706 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_852"/></filter><filter id="ir3wzhe" width="2.568" height="3.646" x="9.32" y="16.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.247059 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_852"/></filter><filter id="ia2dkgd" width="4.913" height="4.647" x="23.084" y="5.562" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.556863 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_852"/></filter><filter id="isWUJbc" width="1.588" height="1.361" x="24.746" y="7.424" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.482353 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_852"/></filter><filter id="iKgaIFx" width="6.514" height="4.796" x="15.307" y="10.186" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.180392 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_852"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-climbing-dark" /></template>
<style>
.ad54zqbdl {
  d: path("m21.218 15.138l-.547-2.156c.64-.154 1.85-.479 2.09-.535c.45-.106 1.266-.154 1.465.816c.183.895-.518 1.18-.86 1.281z");
}

.adasqxbiy {
  cx: 23.462px;
  cy: 8.032px;
  r: 0.072px;
  fill: var(--svg-color--dfdfdf, #DFDFDF);
}

.af5ecjb0e {
  stop-color: var(--svg-color--ff712f, #FF712F);
}

.afdr7o0yz {
  stop-color: var(--svg-color--3f282f, #3F282F);
  stop-opacity: 0;
}

.afg7wtasa {
  stop-color: var(--svg-color--a5a2a8, #A5A2A8);
}

.ahho1w97n {
  stop-color: var(--svg-color--5e505b, #5E505B);
  stop-opacity: 0;
}

.amik16rrq {
  stop-color: var(--svg-color--5a3c98, #5A3C98);
}

.aqvrw7bju {
  d: path("m22.738 26.303l.799.575a.2.2 0 0 1 .046.278l-1.753 2.486c-.06.087-.171.128-.263.075c-.178-.101-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203l-.002-.002z");
}

.awio_2bar {
  d: path("M23.43 10.855h1.905v1.844H23.43z");
}

.b-1q4qbml {
  fill-rule: evenodd;
  d: path("M24.373 18.063c.11 0 .2.09.2.2v.883a.2.2 0 0 1-.4 0v-.883c0-.11.09-.2.2-.2");
}

.b06izibxm {
  stop-color: var(--svg-color--8bad3a, #8BAD3A);
}

.b4obhqdys {
  fill: var(--svg-color--544583, #544583);
  d: path("m22.738 26.303l.799.575a.2.2 0 0 1 .046.278l-1.753 2.486c-.06.087-.171.128-.263.075c-.178-.101-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203l-.002-.002z");
}

.b8g00zlka {
  stop-color: var(--svg-color--402e2d, #402E2D);
}

.bg5vqlb1m {
  stop-color: var(--svg-color--ff2f0b, #FF2F0B);
}

.bie0h0-8q {
  stop-color: var(--svg-color--6f443d, #6F443D);
}

.biyiff5mh {
  stop-color: var(--svg-color--333061, #333061);
}

.bn_1vkbwm {
  stop-color: var(--svg-color--f52715, #F52715);
  stop-opacity: 0;
}

.bnldzacmr {
  stop-color: var(--svg-color--635050, #635050);
}

.boi6lnlog {
  stop-color: var(--svg-color--9c93a5, #9C93A5);
}

.bpm5gvbdi {
  stop-color: var(--svg-color--e5e3e5, #E5E3E5);
}

.brl2tm-6u {
  fill: var(--svg-color--40262e, #40262E);
  d: path("m18.893 21.1l.39-.407l2.11 1.187l-.493.5l1.836 3.922l.8.576a.2.2 0 0 1 .047.277l-1.753 2.487c-.06.087-.171.128-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203c-.662-.94-2.138-3.045-2.75-3.945s-.167-1.636.133-1.89");
}

.bsiog7b5a {
  d: path("m16.568 12.409l-.06.425c-.113.802-.39 1.194-.87 1.488l-.857-1.286l-.946-1.329a.232.232 0 0 1 .324-.323l-.127-.178a.28.28 0 0 1 .291-.433l-.023-.033a.28.28 0 1 1 .455-.324l.106.147a.28.28 0 0 1 .5-.223l.5.819l.026-.229a.293.293 0 0 1 .345-.254a.3.3 0 0 1 .238.345a4 4 0 0 0-.06.6c.001.39.072.613.158.788");
}

.bva5w7bnk {
  fill: var(--svg-color--9f97a9, #9F97A9);
  d: path("m20.791 16.529l.195-.438l3.516 2.024c-.034.107-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.258-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
}

.c3098ubep {
  stop-color: var(--svg-color--d2cdd5, #D2CDD5);
}

.c36r2-bpd {
  d: path("M14.89 10.3a.28.28 0 0 1 .368-.421l1.754 1.506l-.368.42z");
}

.cd3t91bxc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.264 7.948c.07.492.482 1.784 1.58 3.02");
}

.chmofghwi {
  stop-color: var(--svg-color--4b89d0, #4B89D0);
}

.crx2hg4yh {
  stop-color: var(--svg-color--321f20, #321F20);
}

.d6jlrzbaa {
  stop-color: var(--svg-color--908790, #908790);
}

.dfv3zlvmf {
  stop-color: var(--svg-color--648431, #648431);
}

.dgu55jodb {
  d: path("M15.463 10.069a.28.28 0 1 1 .367-.42l1.41 1.419l-.226.512z");
}

.dnpfueb4s {
  stop-color: var(--svg-color--40347f, #40347F);
}

.dof33bbqn {
  fill: var(--svg-color--414141, #414141);
  d: path("m23.37 8.392l.053-.07c.073-.12.081-.25.019-.288c-.064-.038-.174.028-.247.148l-.035.071z");
}

.dpb8nmb_i {
  d: path("M9.918 2.154c.551 1.054 1.37 2.957 1.85 4.836c.78 3.062-.25 5.281-3.75 6.312a881 881 0 0 1-5.964 1.725V2.154z");
}

.e_59tbbed {
  stop-color: var(--svg-color--292557, #292557);
}

.e2k-esbpn {
  stop-color: var(--svg-color--c3c0c6, #C3C0C6);
  stop-opacity: 0;
}

.e9dmvq9mi {
  stop-color: var(--svg-color--635050, #635050);
  stop-opacity: 0;
}

.egb5_lbyf {
  stop-color: var(--svg-color--5f4f4d, #5F4F4D);
  stop-opacity: 0;
}

.egqy8jbwr {
  stop-color: var(--svg-color--4d3a6e, #4D3A6E);
  stop-opacity: 0;
}

.eiq4kwpiv {
  fill: var(--svg-color--290017, #290017);
  fill-rule: evenodd;
  d: path("M22.375 9.294a.1.1 0 0 1 .139-.028c.085.055.25.102.52.04a.1.1 0 1 1 .045.195c-.308.071-.533.025-.675-.068a.1.1 0 0 1-.029-.139");
}

.eky141x3a {
  stop-color: var(--svg-color--489778, #489778);
}

.ems5cpbom {
  d: path("M9.29 17.093a.93.93 0 0 1 .456-.698l-7.692 2.651v2.661c.68-.275 2.227-.92 3.284-1.415c.886-.414 1.715-.409 2.178-.289l3.341.924l-1.32-2.768c-.248-.52-.303-.66-.248-1.066");
}

.etm0d-24x {
  d: path("m23.528 8.496l.026-.04c.132-.216.144-.448.027-.519c-.116-.07-.317.047-.448.263l-.015.026z");
}

.f2xkzabrk {
  stop-color: var(--svg-color--ada2a2, #ADA2A2);
  stop-opacity: 0;
}

.f2yuiwowd {
  stop-color: var(--svg-color--948b99, #948B99);
}

.fi7tv3bhp {
  d: path("M14.738 10.815a.28.28 0 0 1 .367-.42l1.5 1.31l-.367.42z");
}

.fiw9fyalo {
  stop-color: var(--svg-color--4b4386, #4B4386);
}

.foshnm2dn {
  stop-color: var(--svg-color--432e34, #432E34);
  stop-opacity: 0;
}

.fq8v5ccfv {
  d: path("M26.808 10.16L23.18 7.464a.22.22 0 0 1-.069-.288a4.8 4.8 0 0 1 .655-.866c.906-.957 1.909-.492 2.055-.438c.21.078.754.313 1.5 1.024c.875.834.742 1.703.476 2.226c-.167.33-.457.742-.663 1a.235.235 0 0 1-.326.038");
}

.ft5dv1b6b {
  fill: none;
}

.fwnzc4ctw {
  stop-color: var(--svg-color--5a332d, #5A332D);
}

.fy9sosv6u {
  stop-color: var(--svg-color--417c62, #417C62);
  stop-opacity: 0;
}

.g2a7rn75y {
  d: path("m25.127 10.525l.488-1.367l1.356 1.015c-.2.301-.727.563-.938.625a.435.435 0 0 1-.074.657c-.14.09-.508.105-.758-.203c-.2-.247-.133-.588-.074-.727");
}

.g8e5hfbak {
  fill: var(--svg-color--4d3771, #4D3771);
  fill-rule: evenodd;
  d: path("M25.412 8.594a.25.25 0 0 1 .032.353l-1.992 2.394a.25.25 0 0 1-.384-.32l1.992-2.394a.25.25 0 0 1 .352-.033");
}

.gbpc64bji {
  stop-color: var(--svg-color--463736, #463736);
}

.gepa-4uov {
  stop-color: var(--svg-color--8c7786, #8C7786);
  stop-opacity: 0;
}

.gpdazcbld {
  stop-color: var(--svg-color--a9a5ad, #A9A5AD);
}

.gu1w6obkb {
  stop-color: var(--svg-color--a6ca7d, #A6CA7D);
  stop-opacity: 0;
}

.gzdogx1hl {
  stop-color: var(--svg-color--7e7776, #7E7776);
}

.h0drrmbyw {
  d: path("M14.501 14.834L2.054 19.196V2.154h15.944c-.4 2.851-1.233 8.86-1.49 10.68c-.183 1.303-.801 1.523-2.007 2");
}

.hdqy_ks_x {
  d: path("M22.15 8.388c.032-.207.153-.27.45-.351a.7.7 0 0 0 .387-.248l-.458.994c-.21 0-.41-.188-.379-.395");
}

.hgd30nbxf {
  fill: var(--svg-color--4d3c3d, #4D3C3D);
  d: path("M14.89 10.3a.28.28 0 0 1 .368-.421l1.754 1.506l-.368.42z");
}

.hlbcv5m7e {
  stop-color: var(--svg-color--2b1a25, #2B1A25);
  stop-opacity: 0;
}

.hopfogb6a {
  fill: var(--svg-color--a7959b, #A7959B);
  d: path("m20.791 16.529l.195-.438l3.516 2.024c-.034.107-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.258-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
}

.hujbubc9t {
  stop-color: var(--svg-color--e3e1e5, #E3E1E5);
  stop-opacity: 0;
}

.i9ep8rbrn {
  fill: var(--svg-color--67636c, #67636C);
  d: path("m19.162 20.812l.969-1.17l4.058-.988c-.765 1.394-2 3.052-2.187 3.277c-.235.281-.555.34-.89.176c-.813-.4-1.61-.947-1.95-1.295");
}

.ibka94bwi {
  stop-color: var(--svg-color--5a3c98, #5A3C98);
  stop-opacity: 0;
}

.ijj8_s6sp {
  stop-color: var(--svg-color--63608c, #63608C);
  stop-opacity: 0;
}

.ilft87v6y {
  stop-color: var(--svg-color--f8736b, #F8736B);
  stop-opacity: 0;
}

.iooxo1wql {
  stop-color: var(--svg-color--2b1a25, #2B1A25);
}

.ipt6hdesj {
  d: path("m18.123 15.51l.797.32l-.836 2.25l-.834-.52a.25.25 0 0 0-.245-.01l-6.036 3.047a.2.2 0 0 1-.27-.091l-1.33-2.759c-.047-.095-.03-.215.06-.272c.24-.153.505-.097.905.112c.381.2 1.143.895 1.492 1.215c1.1-.765 3.307-2.392 4.05-2.945c.837-.621 1.846-.517 2.247-.348");
}

.j-c4i6bgu {
  stop-color: var(--svg-color--5e598c, #5E598C);
  stop-opacity: 0;
}

.jbbp6_bdq {
  stop-color: var(--svg-color--716170, #716170);
  stop-opacity: 0;
}

.jfz0xgwum {
  stop-color: var(--svg-color--e2452b, #E2452B);
}

.jkxz01uwy {
  d: path("m24.299 19.15l1.906.63v.73a.953.953 0 0 1-1.906 0z");
}

.jn6chbb5g {
  stop-color: var(--svg-color--337267, #337267);
}

.jpfpjd-4z {
  fill: var(--svg-color--4d3c3d, #4D3C3D);
  d: path("M14.738 10.815a.28.28 0 0 1 .367-.42l1.5 1.31l-.367.42z");
}

.jpzdg-bwz {
  stop-color: var(--svg-color--aea0a4, #AEA0A4);
  stop-opacity: 0;
}

.jsa0_reur {
  stop-color: var(--svg-color--3e3c3d, #3E3C3D);
}

.jvvv5bmeo {
  stop-color: var(--svg-color--52abe4, #52ABE4);
}

.k2u_13bdd {
  stop-color: var(--svg-color--e2452b, #E2452B);
  stop-opacity: 0;
}

.k6zficbhz {
  stop-color: var(--svg-color--72687c, #72687C);
  stop-opacity: 0;
}

.kao1--wwn {
  stop-color: var(--svg-color--aea0a5, #AEA0A5);
}

.kf9kmgbpk {
  d: path("m22.322 13.052l-1.25 2.82l3.39 2.258c.563-.726 1.267-2.851 1.243-4.242c-.018-1.055-.436-1.404-1.101-1.765c-.317-.172-1.026-.28-1.399-.16s-.73.663-.883 1.09");
}

.kt6hdg08n {
  stop-color: var(--svg-color--5e598c, #5E598C);
}

.kxfk1zmbn {
  d: path("m11.838 20.158l-.91.455a.2.2 0 0 1-.27-.092l-1.32-2.758c-.046-.096 0-.23.09-.288c.241-.153.506-.097.906.112c.381.2 1.143.895 1.492 1.215l.012-.008z");
}

.l-nb061ot {
  stop-color: var(--svg-color--1d191c, #1D191C);
  stop-opacity: 0;
}

.ldu426b8x {
  fill: var(--svg-color--a29ea7, #A29EA7);
  d: path("M2.054 23.154v6.945h8.343a169 169 0 0 1-2.973-1.578c-1.038-.575-1.31-1.146-1.485-1.524c-.065-.14-.186-.45-.371-.924l-.285-.724c-.322-.816-.953-1.219-1.437-1.422z");
}

.lkkvj6btb {
  fill-rule: evenodd;
  d: path("M24.184 19.112a.2.2 0 0 1 .255-.124l1.742.606a.2.2 0 1 1-.131.378l-1.743-.606a.2.2 0 0 1-.123-.254");
}

.llwjz8b5t {
  cx: 25.146px;
  cy: 9.445px;
  r: 0.559px;
}

.lykybbi9r {
  stop-color: var(--svg-color--aea0a5, #AEA0A5);
  stop-opacity: 0;
}

.m1yqw3kzt {
  stop-color: var(--svg-color--3f282f, #3F282F);
}

.mmu9u7bsf {
  stop-color: var(--svg-color--bcb9be, #BCB9BE);
}

.mn787q_6r {
  stop-color: var(--svg-color--c7c5c9, #C7C5C9);
}

.mr6mdpt1g {
  stop-color: var(--svg-color--716170, #716170);
}

.msti5wbjw {
  stop-color: var(--svg-color--8c7786, #8C7786);
}

.mwbu5sbnw {
  stop-color: var(--svg-color--4a4476, #4A4476);
}

.mzz_2wq-t {
  stop-color: var(--svg-color--c2bfc5, #C2BFC5);
}

.n_3yhnb8a {
  stop-color: var(--svg-color--958e9b, #958E9B);
  stop-opacity: 0;
}

.n_geicc-w {
  stop-color: var(--svg-color--f52715, #F52715);
}

.n7jws8bws {
  stop-color: var(--svg-color--4b4386, #4B4386);
  stop-opacity: 0;
}

.n7r2-292q {
  stop-color: var(--svg-color--958e9b, #958E9B);
}

.nerh9eh2b {
  stop-color: var(--svg-color--564748, #564748);
  stop-opacity: 0;
}

.njdjvcttb {
  stop-color: var(--svg-color--ae9ea8, #AE9EA8);
}

.nkzm4gb5h {
  stop-color: var(--svg-color--a297ad, #A297AD);
}

.nmynr_cvx {
  stop-color: var(--svg-color--e3d5d2, #E3D5D2);
}

.no0-xjbmh {
  d: path("m19.162 20.812l.969-1.17l4.058-.988c-.765 1.394-2 3.052-2.187 3.277c-.235.281-.555.34-.89.176c-.813-.4-1.61-.947-1.95-1.295");
}

.npx64-mvq {
  stop-color: var(--svg-color--ff9057, #FF9057);
  stop-opacity: 0;
}

.nr87if9lw {
  stop-color: var(--svg-color--37234c, #37234C);
  stop-opacity: 0;
}

.nuwcoob-p {
  stop-color: var(--svg-color--a49ba8, #A49BA8);
  stop-opacity: 0;
}

.nvv1klhll {
  stop-color: var(--svg-color--f8736b, #F8736B);
}

.nwhi_fa4f {
  stop-color: var(--svg-color--413b69, #413B69);
}

.o3cxmzbrw {
  fill: var(--svg-color--432b2a, #432B2A);
  d: path("m18.123 15.51l.797.32l-.836 2.25l-.834-.52a.25.25 0 0 0-.245-.01l-6.036 3.047a.2.2 0 0 1-.27-.091l-1.33-2.759c-.047-.095-.03-.215.06-.272c.24-.153.505-.097.905.112c.381.2 1.143.895 1.492 1.215c1.1-.765 3.307-2.392 4.05-2.945c.837-.621 1.846-.517 2.247-.348");
}

.o6w7f1w7w {
  stop-color: var(--svg-color--ff722c, #FF722C);
}

.os32btykc {
  stop-color: var(--svg-color--66619b, #66619B);
}

.ovz69fb_x {
  stop-color: var(--svg-color--483637, #483637);
}

.oyx3ieb6e {
  fill: var(--svg-color--4d3c3d, #4D3C3D);
  d: path("M15.463 10.069a.28.28 0 1 1 .367-.42l1.41 1.419l-.226.512z");
}

.p1xawgtbo {
  stop-color: var(--svg-color--402d2f, #402D2F);
}

.p2417ob0x {
  stop-color: var(--svg-color--e3d5d2, #E3D5D2);
  stop-opacity: 0;
}

.pav55masc {
  stop-color: var(--svg-color--564975, #564975);
}

.pids_pbns {
  stop-color: var(--svg-color--948f8f, #948F8F);
}

.po5p7izon {
  d: path("M24.809 7.542a.3.3 0 0 1 .423-.055l.984.757a.302.302 0 0 1-.368.479l-.984-.758a.3.3 0 0 1-.055-.423");
}

.ps4wek9uf {
  stop-color: var(--svg-color--4a4476, #4A4476);
  stop-opacity: 0;
}

.q264kdbup {
  stop-color: var(--svg-color--382125, #382125);
}

.q4ysocc-i {
  stop-color: var(--svg-color--3e2829, #3E2829);
}

.q5087sbmq {
  fill-rule: evenodd;
  d: path("M23.362 13.914c-3.618-1.712-4.891-4.456-5.481-6.545c-.111-.427.035-.996.59-1.09l.693-.157a.41.41 0 0 1 .476.341c.33 2.085 1.175 4.09 4.47 5.869z");
}

.qd-f9ooxs {
  stop-color: var(--svg-color--3a5669, #3A5669);
}

.qksuzsbug {
  stop-color: var(--svg-color--ff7857, #FF7857);
}

.qz7rikoqh {
  d: path("M22.01 9.576c.277-.875.95-1.815 1.21-2.188l2.9 1.867l-.594 2.047a4.5 4.5 0 0 1-1.813 0c-.945-.21-2.067-.578-1.703-1.726");
}

.r_k29qxtj {
  stop-color: var(--svg-color--fb5139, #FB5139);
  stop-opacity: 0;
}

.r8uyz9bqp {
  stop-color: var(--svg-color--ada2a2, #ADA2A2);
}

.rdr27y14e {
  stop-color: var(--svg-color--9f9ca3, #9F9CA3);
  stop-opacity: 0;
}

.reex3410h {
  stop-color: var(--svg-color--e2dfe2, #E2DFE2);
}

.rlbn0jwxx {
  stop-color: var(--svg-color--4d407b, #4D407B);
}

.rmq-p8bwk {
  fill: var(--svg-color--5c5089, #5C5089);
  d: path("m11.838 20.158l-.91.455a.2.2 0 0 1-.27-.092l-1.32-2.758c-.046-.096 0-.23.09-.288c.241-.153.506-.097.906.112c.381.2 1.143.895 1.492 1.215l.012-.008z");
}

.rn-t0rb0y {
  d: path("M13.638 2.11c.393 1.553.85 4.693.134 7.329a.276.276 0 0 0 .165.331a.23.23 0 0 0 .144.01c.378-.105.836-.512 1.153-1.287c.567-1.385 1.18-3.75 1.637-5.515l.226-.868z");
}

.se__e0blq {
  stop-color: var(--svg-color--ff7857, #FF7857);
  stop-opacity: 0;
}

.sf7z4ybcf {
  stop-color: var(--svg-color--d1cfd2, #D1CFD2);
  stop-opacity: 0;
}

.shmkg3ete {
  stop-color: var(--svg-color--7a7996, #7A7996);
}

.t-qeblb7d {
  stop-color: var(--svg-color--e2e0e4, #E2E0E4);
}

.t20d06bem {
  stop-color: var(--svg-color--816878, #816878);
  stop-opacity: 0;
}

.t20fa7b7o {
  stop-color: var(--svg-color--9d94a6, #9D94A6);
}

.t931osbxo {
  fill-rule: evenodd;
  d: path("M25.412 8.594a.25.25 0 0 1 .032.353l-1.992 2.394a.25.25 0 0 1-.384-.32l1.992-2.394a.25.25 0 0 1 .352-.033");
}

.tc6eb3_7m {
  d: path("M20.182 7.029a1.4 1.4 0 0 1-.25.816l-.282-.695l-.27.07c-.316.078-.437-.094-.456-.191c-.02-.098-.043-.387.37-.469c.415-.082.884-.023.888.469");
}

.ti929abbi {
  stop-color: var(--svg-color--564748, #564748);
}

.tn7myqe_j {
  stop-color: var(--svg-color--337bcd, #337BCD);
}

.tslw4_1qu {
  stop-color: var(--svg-color--63608c, #63608C);
}

.tur7wrfly {
  fill: var(--svg-color--1b131d, #1B131D);
  d: path("m25.127 10.525l.488-1.367l1.356 1.015c-.2.301-.727.563-.938.625a.435.435 0 0 1-.074.657c-.14.09-.508.105-.758-.203c-.2-.247-.133-.588-.074-.727");
}

.tvjmrrbpc {
  stop-color: var(--svg-color--5e505b, #5E505B);
}

.tylpo8bot {
  stop-color: var(--svg-color--bcb9be, #BCB9BE);
  stop-opacity: 0;
}

.u-fne8bwx {
  d: path("M2.054 30.1v-8.954l5.204-1.977l2.513 1.29c-.22-.383.6-.538 1.07.43c.235.48-.112 1.812-.597 2.421l-1.32 1.48a.4.4 0 0 0 .023.557l5 4.752z");
}

.uagq7j3nj {
  d: path("M18.984 2.154v9.588c0 .132.027.263.079.384l1.706 3.989l.42.137c.05.114.166.978.28.929a.225.225 0 0 0 .119-.295l-2.112-4.937a.5.5 0 0 1-.042-.207V2.154z");
}

.uubye-mwc {
  stop-color: var(--svg-color--a6ca7d, #A6CA7D);
}

.uuc-lrj5h {
  stop-color: var(--svg-color--7a7996, #7A7996);
  stop-opacity: 0;
}

.v1low-dfl {
  d: path("m20.791 16.529l.195-.438l3.516 2.024c-.034.107-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.258-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
}

.v26q47bkt {
  stop-color: var(--svg-color--584949, #584949);
  stop-opacity: 0;
}

.v5_ahxl8w {
  stop-color: var(--svg-color--554682, #554682);
}

.v5m-xebtg {
  stop-color: var(--svg-color--f94b3a, #F94B3A);
}

.va9cd6b6q {
  fill: var(--svg-color--fff, #fff);
  d: path("M23.502 7.904c-.201.031-.326.221-.387.32l.735.485c.257-.625-.075-.848-.348-.805");
}

.vc966g90j {
  d: path("M14.663 11.348a.232.232 0 0 1 .305-.349l1.245 1.088l-.305.35z");
}

.vp6yj4xxl {
  stop-color: var(--svg-color--9f9ca3, #9F9CA3);
}

.vps27w8pe {
  stop-color: var(--svg-color--413b69, #413B69);
  stop-opacity: 0;
}

.vx6_akbll {
  stop-color: var(--svg-color--493234, #493234);
}

.w5vd7udwg {
  stop-color: var(--svg-color--908790, #908790);
  stop-opacity: 0;
}

.w9h_a4buy {
  stop-color: var(--svg-color--4fbdff, #4FBDFF);
}

.wd5xhxb1x {
  stop-color: var(--svg-color--e43e1c, #E43E1C);
}

.wj6zzlb9k {
  d: path("M20.793 16.524c.654.302 1.479.99 2.021 2.231c.195.446.143.899-.041 1.322c-.619.264-1.291.183-2.013.014c-.906-.21-1.484-.406-1.85-.53q-.12-.042-.213-.071c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012l2.02.782z");
}

.wlyubdb4v {
  stop-color: var(--svg-color--d6d4d7, #D6D4D7);
}

.woj4y6m6m {
  d: path("m18.893 21.1l.39-.407l2.11 1.187l-.493.5l1.836 3.922l.8.576a.2.2 0 0 1 .047.277l-1.753 2.487c-.06.087-.171.128-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203c-.662-.94-2.138-3.045-2.75-3.945s-.167-1.636.133-1.89");
}

.woxmm4b5l {
  fill: var(--svg-color--4d3c3d, #4D3C3D);
  d: path("m16.478 10.116l.079.643l.34 1.149l.69-.367c-.175-.184-.309-.336-.44-.875a4 4 0 0 1-.08-.598a.3.3 0 0 0-.312-.28a.293.293 0 0 0-.277.328");
}

.ws0t5un5c {
  stop-color: var(--svg-color--816878, #816878);
}

.x0zx5qyer {
  stop-color: var(--svg-color--72687c, #72687C);
}

.x2qxulb2k {
  fill: var(--svg-color--4d3c3d, #4D3C3D);
  d: path("M14.663 11.348a.232.232 0 0 1 .305-.349l1.245 1.088l-.305.35z");
}

.x9rbvhxej {
  stop-color: var(--svg-color--535478, #535478);
}

.xapik5b0z {
  stop-color: var(--svg-color--ff9057, #FF9057);
}

.xoq-ina2u {
  stop-color: var(--svg-color--2e1018, #2E1018);
}

.xzhs54baa {
  stop-color: var(--svg-color--948f8f, #948F8F);
  stop-opacity: 0;
}

.y_9n-yf2a {
  fill: var(--svg-color--472f32, #472F32);
  d: path("m16.478 10.116l.079.643l.34 1.149l.69-.367c-.175-.184-.309-.336-.44-.875a4 4 0 0 1-.08-.598a.3.3 0 0 0-.312-.28a.293.293 0 0 0-.277.328");
}

.y6k--c7ym {
  stop-color: var(--svg-color--584949, #584949);
}

.ybn2mcbio {
  stop-color: var(--svg-color--9c93a5, #9C93A5);
  stop-opacity: 0;
}

.yiv1s6b4r {
  fill: var(--svg-color--472f32, #472F32);
  fill-rule: evenodd;
  d: path("m17.962 14.343l-2.655-2.435l1.259-1.372l2.59 2.527a.63.63 0 0 0 .581.15l1.65-.423l.433 1.696l-1.65.422a2.38 2.38 0 0 1-2.208-.565");
}

.ylvew1phe {
  stop-color: var(--svg-color--4d407b, #4D407B);
  stop-opacity: 0;
}

.z460z2cnm {
  fill: var(--svg-color--3f292a, #3F292A);
  d: path("M20.182 7.029a1.4 1.4 0 0 1-.25.816l-.282-.695l-.27.07c-.316.078-.437-.094-.456-.191c-.02-.098-.043-.387.37-.469c.415-.082.884-.023.888.469");
}

.z4zbxthsh {
  stop-color: var(--svg-color--5f4f4d, #5F4F4D);
}

.z6c-cwb3w {
  fill-rule: evenodd;
  d: path("M20.77 15.896a.25.25 0 0 1 .341-.092l3.629 2.09a.25.25 0 1 1-.25.434l-3.628-2.09a.25.25 0 0 1-.092-.342");
}

.z7m9rdbog {
  stop-color: var(--svg-color--41292d, #41292D);
}

.zbfwxqbqy {
  stop-color: var(--svg-color--432e34, #432E34);
}

.zcigs7bii {
  stop-color: var(--svg-color--37234c, #37234C);
}

.zf7t0yb1u {
  stop-color: var(--svg-color--aea0a4, #AEA0A4);
}

.zp0x88wix {
  stop-color: var(--svg-color--aaa6ae, #AAA6AE);
  stop-opacity: 0;
}

</style>
