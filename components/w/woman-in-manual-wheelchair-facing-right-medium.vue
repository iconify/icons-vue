<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i6QEbxe)"><path class="ihrk5ivyw"/><path fill="url(#ipasKzd)" class="m_-fcub7q"/><path fill="url(#iBOvXGd)" class="m_-fcub7q"/><path fill="url(#idi41Rd)" class="m_-fcub7q"/></g><g filter="url(#iNfbuNd)"><path fill="url(#iXshNBe)" class="xhq7i0bkh"/><path fill="url(#inmGXac)" class="xhq7i0bkh"/><path fill="url(#iZlNVwe)" class="xhq7i0bkh"/><path fill="url(#iRJiopd)" class="xhq7i0bkh"/><path fill="url(#iCoVpvb)" class="xhq7i0bkh"/></g><g filter="url(#ifp5Hhb)"><path class="mu7eh4v_c"/></g><circle fill="url(#iXMqNwc)" transform="matrix(-1 0 0 1 21.995 26.766)" class="fxt2czijw"/><circle fill="url(#iQwKHob)" transform="matrix(-1 0 0 1 21.995 26.766)" class="fxt2czijw"/><g filter="url(#i70yhHd)"><circle fill="url(#ioLCjBe)" transform="matrix(-1 0 0 1 21.823 26.938)" class="ydp5je9ep"/><circle fill="url(#imBPRuo)" transform="matrix(-1 0 0 1 21.823 26.938)" class="ydp5je9ep"/></g><rect transform="matrix(-1 0 0 1 20.893 22.434)" class="s4mm7wj7e"/><rect fill="url(#iEWySdO)" transform="matrix(-1 0 0 1 20.893 22.434)" class="vczf7ubhl"/><rect fill="url(#if1MlHd)" transform="matrix(-1 0 0 1 20.893 22.434)" class="vczf7ubhl"/><rect fill="url(#i7UH9Yb)" transform="matrix(-1 0 0 1 20.893 22.434)" class="vczf7ubhl"/><rect fill="url(#i7VVBrk)" transform="matrix(-1 0 0 1 20.893 22.434)" class="vczf7ubhl"/><rect fill="url(#iaSVYwi)" transform="matrix(-1 0 0 1 20.893 22.434)" class="vczf7ubhl"/><rect fill="url(#iSFHx9b)" transform="matrix(-1 0 0 1 20.893 22.434)" class="vczf7ubhl"/><rect fill="url(#iYNEAZz)" transform="scale(-1 1)rotate(-65.334 8.573 31.68)" class="j7vr7jxtp"/><rect fill="url(#i2GmAFd)" transform="scale(-1 1)rotate(-65.334 8.573 31.68)" class="j7vr7jxtp"/><path fill="url(#i9v55rc)" class="cvqtxmgmy"/><path fill="url(#irct0xb)" class="cvqtxmgmy"/><path fill="url(#iDlDHIb)" class="cvqtxmgmy"/><path fill="url(#ig0zvud)" class="cvqtxmgmy"/><path fill="url(#iOGjN3d)" class="cvqtxmgmy"/><path fill="url(#ijXvRMd)" class="cvqtxmgmy"/><g filter="url(#ijVKQPe)"><path fill="url(#iCfVCvw)" clip-rule="evenodd" class="yaxokabcj"/><path fill="url(#iuh7dye)" clip-rule="evenodd" class="yaxokabcj"/></g><path fill="url(#iYtOhke)" class="ynyobdc8w"/><path fill="url(#iYivwyb)" class="ynyobdc8w"/><path fill="url(#igpk4Db)" transform="scale(-1 1)rotate(16.465 -46.26 -33.047)" class="fbej3eerw"/><g filter="url(#iofxE3b)"><rect transform="scale(-1 1)rotate(24.427 -67.56 -49.109)" class="mkf18fb1r"/></g><rect fill="url(#i6RqGqc)" transform="scale(-1 1)rotate(24.427 -67.56 -49.109)" class="kbsq_bcao"/><g filter="url(#in1WPLc)"><path fill="url(#i21DLve)" clip-rule="evenodd" class="ieoaw0bcr"/><path fill="url(#icnT9Ne)" clip-rule="evenodd" class="ieoaw0bcr"/><path fill="url(#iJ0T6Qj)" clip-rule="evenodd" class="ieoaw0bcr"/></g><path fill="url(#ilA4hJb)" clip-rule="evenodd" class="svkl-3bgp"/><path fill="url(#iaXVihZ)" clip-rule="evenodd" class="svkl-3bgp"/><path fill="url(#it6pl9I)" clip-rule="evenodd" class="svkl-3bgp"/><rect fill="url(#i5Zn9Cb)" transform="matrix(-1 0 0 1 11.33 11.231)" class="szzuw3bbf"/><rect fill="url(#iAXanqd)" transform="matrix(-1 0 0 1 11.33 11.231)" class="szzuw3bbf"/><g filter="url(#i868M0D)"><circle fill="url(#idPuoOc)" transform="matrix(-1 0 0 1 15.37 19.885)" class="gbejtwrll"/></g><g filter="url(#imVeYPb)"><path clip-rule="evenodd" class="gykv57cqb"/></g><path class="hzlclw72u"/><path fill="url(#iqa99Qj)" class="hu5mq1ced"/><path fill="url(#i6cjMsd)" class="hu5mq1ced"/><path fill="url(#iNCaRhe)" class="hu5mq1ced"/><path fill="url(#iEYpF0k)" class="hu5mq1ced"/><path fill="url(#iRXiq0b)" class="hu5mq1ced"/><g filter="url(#iR0zQjc)"><circle fill="url(#ix9EIYc)" transform="matrix(-1 0 0 1 12.448 22.807)" class="ynhlcccje"/></g><g filter="url(#iTIfNKb)"><circle stroke="url(#i8Lpy6d)" transform="matrix(-1 0 0 1 12.284 22.971)" class="v5no8zo2o"/></g><g filter="url(#iohqtOb)"><circle stroke="url(#irdQ4jd)" transform="matrix(-1 0 0 1 15.653 19.334)" class="s6599442t"/></g><g filter="url(#i1Yhtye)"><circle stroke="url(#ieAH43d)" transform="matrix(-1 0 0 1 16.776 18.153)" class="ju5i36bgg"/></g><circle fill="url(#iuj98VS)" transform="matrix(-1 0 0 1 14.636 17.352)" class="jptbwygwk"/><path class="ed2n0rbpd"/><g filter="url(#idokYRd)"><path class="ffz88hbch"/></g><path class="d9__ewb5v"/><path fill="url(#iXqdE0c)" class="cloqvszsb"/><path fill="url(#ieZDGUb)" class="cloqvszsb"/><path fill="url(#il9blxc)" class="cloqvszsb"/><path fill="url(#iAfCeMb)" class="cloqvszsb"/><g filter="url(#i3TRLhb)"><path class="uta33k16w"/></g><g filter="url(#ikBt5By)"><path stroke="url(#i9kL0Qd)" class="k4435esfk"/></g><g filter="url(#i12Tu3d)"><path class="be03fp4ln"/></g><path fill="url(#ihaLkAd)" class="nlxszcchf"/><path fill="url(#ikAi7EC)" class="nlxszcchf"/><g filter="url(#ifnWdKb)"><path fill="url(#iWhrpid)" class="y28p9db6y"/><path fill="url(#iqrh1Pe)" class="y28p9db6y"/><path fill="url(#iPH5NCe)" class="y28p9db6y"/><path fill="url(#iu2LASV)" class="y28p9db6y"/></g><g filter="url(#inVdQRb)"><path class="mh0ys7bkx"/></g><g filter="url(#iaJNJWc)"><path class="wxymobcro"/><path fill="url(#iZaB2cc)" class="y9geofb4u"/></g><path fill="url(#ipnLyZc)" class="zc6u5lbhd"/><path fill="url(#iFTbtib)" class="zc6u5lbhd"/><path fill="url(#iFiGkwd)" class="zc6u5lbhd"/><path clip-rule="evenodd" class="ba4ju4bdt"/><g filter="url(#iARThPd)"><path clip-rule="evenodd" class="diiog7gjn"/></g><path class="gsg9xvp1r"/><path class="gg9-_hbxs"/><path fill="url(#ieHnpJc)" class="yhtwjqbxf"/><path fill="url(#iVvBHVb)" class="zqqbrtbmz"/><ellipse fill="url(#i6uCCss)" transform="scale(-1 1)rotate(12.321 -36.265 -84.5)" class="a9bmddp5j"/><defs><radialGradient id="idi41Rd" cx="0" cy="0" r="1" gradientTransform="matrix(-.7395 -.04827 .083 -1.2714 26.876 23.012)" gradientUnits="userSpaceOnUse"><stop class="bfwbq1bpl"/><stop offset="1" class="ktc-s82to"/></radialGradient><radialGradient id="inmGXac" cx="0" cy="0" r="1" gradientTransform="rotate(70.681 -4.03 25.146)scale(5.76196 2.25923)" gradientUnits="userSpaceOnUse"><stop class="y3ij90b8v"/><stop offset="1" class="qb3gn8bfr"/></radialGradient><radialGradient id="iZlNVwe" cx="0" cy="0" r="1" gradientTransform="matrix(-7.5 0 0 -12.1563 21.002 17.13)" gradientUnits="userSpaceOnUse"><stop offset=".45" class="yutdbcb6i"/><stop offset="1" class="sstiaym3o"/></radialGradient><radialGradient id="iRJiopd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.46875 5.125 0 15.94 18.098)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="yu7wmpb_a"/><stop offset="1" class="zzc1m6bsl"/></radialGradient><radialGradient id="iQwKHob" cx="0" cy="0" r="1" gradientTransform="matrix(1.48438 0 0 3.64062 -.695 1.723)" gradientUnits="userSpaceOnUse"><stop class="answrebhr"/><stop offset="1" class="fzo002mry"/></radialGradient><radialGradient id="ioLCjBe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.80266 4.80004 0 1.55 2.803)" gradientUnits="userSpaceOnUse"><stop class="ja_znnx3a"/><stop offset="1" class="ildpa548e"/></radialGradient><radialGradient id="imBPRuo" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.71875 1.03125 0 1.352 1.254)" gradientUnits="userSpaceOnUse"><stop class="z-rtjcc0y"/><stop offset="1" class="vxrkdvuju"/></radialGradient><radialGradient id="if1MlHd" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.11265 -.46567 0 1.242 1.844)" gradientUnits="userSpaceOnUse"><stop class="a9m8t591o"/><stop offset="1" class="zige1b1kr"/></radialGradient><radialGradient id="i7UH9Yb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.9265 -.24601 0 0 1.03)" gradientUnits="userSpaceOnUse"><stop class="a9m8t591o"/><stop offset="1" class="zige1b1kr"/></radialGradient><radialGradient id="i7VVBrk" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.69196 .27569 0 0 6.205)" gradientUnits="userSpaceOnUse"><stop class="q6suc5ubz"/><stop offset="1" class="erfrsrblk"/></radialGradient><radialGradient id="iaSVYwi" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.94902 .80452 0 .621 6.695)" gradientUnits="userSpaceOnUse"><stop class="ku1djbbcg"/><stop offset="1" class="e3f4ywbbl"/></radialGradient><radialGradient id="iSFHx9b" cx="0" cy="0" r="1" gradientTransform="rotate(38.089 -2.087 2.063)scale(1.46908 .76568)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="n3h2abc_m"/><stop offset="1" class="rgr8nhbdi"/></radialGradient><radialGradient id="iYNEAZz" cx="0" cy="0" r="1" gradientTransform="matrix(-5.01535 -.13834 .02815 -1.0205 5.7 .78)" gradientUnits="userSpaceOnUse"><stop offset=".435" class="rs99u8bqf"/><stop offset="1" class="lvn5-ac9d"/></radialGradient><radialGradient id="iOGjN3d" cx="0" cy="0" r="1" gradientTransform="matrix(2.07812 -.42187 .6015 2.96294 14.409 19.067)" gradientUnits="userSpaceOnUse"><stop class="tis1nnbrp"/><stop offset="1" class="t9-j-pbql"/></radialGradient><radialGradient id="ijXvRMd" cx="0" cy="0" r="1" gradientTransform="matrix(.82813 0 0 2.43007 19.19 18.286)" gradientUnits="userSpaceOnUse"><stop class="r04agib6p"/><stop offset="1" class="mz7wlj55e"/></radialGradient><radialGradient id="iYtOhke" cx="0" cy="0" r="1" gradientTransform="rotate(-128.91 10.565 .892)scale(2.05104 1.96287)" gradientUnits="userSpaceOnUse"><stop offset=".535" class="s03jqe71p"/><stop offset="1" class="rj2ywtb6v"/></radialGradient><radialGradient id="igpk4Db" cx="0" cy="0" r="1" gradientTransform="matrix(.06825 -4.12415 .84696 .01402 .527 3.948)" gradientUnits="userSpaceOnUse"><stop offset=".553" class="w-8ci9bkh"/><stop offset="1" class="dr65abcro"/></radialGradient><radialGradient id="i6RqGqc" cx="0" cy="0" r="1" gradientTransform="matrix(.59496 -.39035 .70458 1.0739 .095 1.168)" gradientUnits="userSpaceOnUse"><stop class="vp5ble8bb"/><stop offset="1" class="g4u-v_bhx"/></radialGradient><radialGradient id="iaXVihZ" cx="0" cy="0" r="1" gradientTransform="rotate(90 -6.316 17.628)scale(5.3418)" gradientUnits="userSpaceOnUse"><stop offset=".754" class="lfwvarbqo"/><stop offset="1" class="z4for55kd"/></radialGradient><radialGradient id="it6pl9I" cx="0" cy="0" r="1" gradientTransform="matrix(9.24998 -8.46874 6.57579 7.1824 7.034 28.536)" gradientUnits="userSpaceOnUse"><stop offset=".921" class="jz-3fab0l"/><stop offset="1" class="fiiks7b8f"/></radialGradient><radialGradient id="iAXanqd" cx="0" cy="0" r="1" gradientTransform="matrix(-.85938 .39452 -.43395 -.94526 4.36 .211)" gradientUnits="userSpaceOnUse"><stop class="roww1df0l"/><stop offset="1" class="ennuonbfb"/></radialGradient><radialGradient id="idPuoOc" cx="0" cy="0" r="1" gradientTransform="matrix(4.09375 -5.53125 9.86398 7.30045 2.21 6.838)" gradientUnits="userSpaceOnUse"><stop offset=".246" class="z3yur8boj"/><stop offset="1" class="c9gtc1bjl"/></radialGradient><radialGradient id="iqa99Qj" cx="0" cy="0" r="1" gradientTransform="rotate(110.816 2.624 11.142)scale(5.09592 1.94315)" gradientUnits="userSpaceOnUse"><stop offset=".148" class="zp_517jgm"/><stop offset="1" class="p9ept44wt"/></radialGradient><radialGradient id="iNCaRhe" cx="0" cy="0" r="1" gradientTransform="matrix(1.60922 1.60922 -4.29661 4.29661 12.715 8.755)" gradientUnits="userSpaceOnUse"><stop class="kn42mcchn"/><stop offset="1" class="kzr6sffft"/></radialGradient><radialGradient id="iEYpF0k" cx="0" cy="0" r="1" gradientTransform="matrix(-.69855 5.125 -2.13812 -.29143 17.308 11.234)" gradientUnits="userSpaceOnUse"><stop class="i24r0nbmv"/><stop offset="1" class="erlv03bqf"/></radialGradient><radialGradient id="iRXiq0b" cx="0" cy="0" r="1" gradientTransform="matrix(2 -6.00932 5.11023 1.70077 14.204 14.234)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="hagwkib2x"/><stop offset="1" class="ip5996ykk"/></radialGradient><radialGradient id="iuj98VS" cx="0" cy="0" r="1" gradientTransform="rotate(-73.593 .548 .247)scale(.73297)" gradientUnits="userSpaceOnUse"><stop class="odw8jmnks"/><stop offset="1" class="dqa0zuk3f"/></radialGradient><radialGradient id="il9blxc" cx="0" cy="0" r="1" gradientTransform="matrix(2.0156 -2.96876 2.35369 1.598 13.565 11.848)" gradientUnits="userSpaceOnUse"><stop offset=".88" class="aew93sw7h"/><stop offset="1" class="a10dt2bqr"/></radialGradient><radialGradient id="iAfCeMb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49998 2.03126 -.62745 -.46334 13.422 10.406)" gradientUnits="userSpaceOnUse"><stop class="tnr6qjbmk"/><stop offset="1" class="c6hrvfqjf"/></radialGradient><radialGradient id="ihaLkAd" cx="0" cy="0" r="1" gradientTransform="matrix(-.47183 .1364 -.19252 -.666 19.7 6.963)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="ng2hgzbhn"/><stop offset=".684" class="nz7jfnb_b"/></radialGradient><radialGradient id="ikAi7EC" cx="0" cy="0" r="1" gradientTransform="matrix(.16258 -.23503 .35273 .244 19.28 7.165)" gradientUnits="userSpaceOnUse"><stop class="av0_6yb2f"/><stop offset="1" class="lhhdsccyq"/></radialGradient><radialGradient id="iqrh1Pe" cx="0" cy="0" r="1" gradientTransform="matrix(.75634 .12127 -.14785 .92213 16.59 5.633)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="pe7odhb7d"/><stop offset="1" class="ao9a_pbsn"/></radialGradient><radialGradient id="iPH5NCe" cx="0" cy="0" r="1" gradientTransform="matrix(1.00087 -4.59449 1.7852 .3889 18.928 7.244)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="vb_gc7b6b"/><stop offset="1" class="rhkf30kvu"/></radialGradient><radialGradient id="iu2LASV" cx="0" cy="0" r="1" gradientTransform="matrix(-.07536 .34597 -.53956 -.11753 18.414 6.075)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="g87nnpbqu"/><stop offset="1" class="igg0ouipp"/></radialGradient><radialGradient id="iZaB2cc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.29217 -.68579 1.46614 -2.76253 19.784 4.274)" gradientUnits="userSpaceOnUse"><stop class="zy9nvz9pf"/><stop offset="1" class="xfcyplbyz"/></radialGradient><radialGradient id="ipnLyZc" cx="0" cy="0" r="1" gradientTransform="matrix(-.6028 -.32701 .1596 -.29422 16.9 5.592)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="desyi4b3l"/><stop offset="1" class="ene2socfu"/></radialGradient><radialGradient id="iFTbtib" cx="0" cy="0" r="1" gradientTransform="matrix(-.42775 1.00129 -1.04338 -.44573 16.93 5.32)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="kplqz4bbv"/><stop offset="1" class="necsq7bka"/></radialGradient><radialGradient id="ieHnpJc" cx="0" cy="0" r="1" gradientTransform="rotate(-167.71 9.667 2.073)scale(.24786 .48155)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iVvBHVb" cx="0" cy="0" r="1" gradientTransform="rotate(-167.714 9.742 2.09)scale(.22633 .48981)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><linearGradient id="ipasKzd" x1="22.886" x2="23.803" y1="24.444" y2="23.962" gradientUnits="userSpaceOnUse"><stop offset=".209" class="id-v9-mic"/><stop offset="1" class="s_nhb9bnh"/></linearGradient><linearGradient id="iBOvXGd" x1="24.125" x2="23.835" y1="24.782" y2="24.026" gradientUnits="userSpaceOnUse"><stop offset=".122" class="oqr4-mbfk"/><stop offset="1" class="s_nhb9bnh"/></linearGradient><linearGradient id="iXshNBe" x1="22.096" x2="15.94" y1="20.692" y2="17.317" gradientUnits="userSpaceOnUse"><stop class="sa2yvrtdg"/><stop offset="1" class="bxntujdns"/></linearGradient><linearGradient id="iCoVpvb" x1="22.94" x2="22.034" y1="19.942" y2="20.004" gradientUnits="userSpaceOnUse"><stop class="d_4otnung"/><stop offset="1" class="gldbv0pab"/></linearGradient><linearGradient id="iXMqNwc" x1="1.914" x2="1.914" y1="3.566" y2="0" gradientUnits="userSpaceOnUse"><stop class="uqxwa8ern"/><stop offset=".596" class="qx2qyypot"/></linearGradient><linearGradient id="iEWySdO" x1="1.242" x2=".505" y1="4.432" y2="4.432" gradientUnits="userSpaceOnUse"><stop class="g6i5vgbtc"/><stop offset="1" class="zuaxx5qad"/></linearGradient><linearGradient id="i2GmAFd" x1="3.696" x2="3.608" y1="1.581" y2=".828" gradientUnits="userSpaceOnUse"><stop class="pyh7r6bag"/><stop offset="1" class="ym5c6ha3r"/></linearGradient><linearGradient id="i9v55rc" x1="19.649" x2="14.741" y1="18.59" y2="18.59" gradientUnits="userSpaceOnUse"><stop class="n0w_cmcuq"/><stop offset="1" class="cjqgdpbwq"/></linearGradient><linearGradient id="irct0xb" x1="16.253" x2="16.253" y1="17.52" y2="17.864" gradientUnits="userSpaceOnUse"><stop class="xb91u7b-b"/><stop offset="1" class="us60yytqw"/></linearGradient><linearGradient id="iDlDHIb" x1="17.174" x2="17.174" y1="19.364" y2="18.317" gradientUnits="userSpaceOnUse"><stop class="x8v8a_bhe"/><stop offset="1" class="g0aomjwhv"/></linearGradient><linearGradient id="ig0zvud" x1="20.893" x2="20.659" y1="19.129" y2="19.129" gradientUnits="userSpaceOnUse"><stop class="xudiynxns"/><stop offset="1" class="h_vbtipyr"/></linearGradient><linearGradient id="iCfVCvw" x1="16.979" x2="16.979" y1="19.082" y2="26.614" gradientUnits="userSpaceOnUse"><stop class="yp_2y0bkd"/><stop offset="1" class="jli-mvbgu"/></linearGradient><linearGradient id="iuh7dye" x1="20.893" x2="20.471" y1="21.377" y2="21.377" gradientUnits="userSpaceOnUse"><stop class="ig81yhx8p"/><stop offset="1" class="sqtinbbgr"/></linearGradient><linearGradient id="iYivwyb" x1="16.654" x2="16.311" y1="9.189" y2="9.036" gradientUnits="userSpaceOnUse"><stop class="p2ahpfb5s"/><stop offset="1" class="k8j-nbbgc"/></linearGradient><linearGradient id="i21DLve" x1="18.643" x2="12.909" y1="19.348" y2="16.098" gradientUnits="userSpaceOnUse"><stop class="x3lzt0c-k"/><stop offset="1" class="cwu_shb3d"/></linearGradient><linearGradient id="icnT9Ne" x1="10.83" x2="11.853" y1="17.475" y2="17.475" gradientUnits="userSpaceOnUse"><stop class="ys8863_0j"/><stop offset="1" class="h0a-qhb0e"/></linearGradient><linearGradient id="iJ0T6Qj" x1="15.262" x2="15.262" y1="16.015" y2="16.348" gradientUnits="userSpaceOnUse"><stop class="io62jp_6h"/><stop offset="1" class="rg3z6xbem"/></linearGradient><linearGradient id="ilA4hJb" x1="7.471" x2="15.565" y1="19.567" y2="28.629" gradientUnits="userSpaceOnUse"><stop class="v06h3pbnx"/><stop offset="1" class="lucd7-9cq"/></linearGradient><linearGradient id="i5Zn9Cb" x1=".344" x2="4.227" y1=".742" y2=".742" gradientUnits="userSpaceOnUse"><stop class="o2t29rbsm"/><stop offset="1" class="laa0aab1b"/></linearGradient><linearGradient id="i6cjMsd" x1="16.223" x2="16.223" y1="15.528" y2="11.49" gradientUnits="userSpaceOnUse"><stop class="dntytqbyu"/><stop offset="1" class="toti2-rqa"/></linearGradient><linearGradient id="ix9EIYc" x1="1.945" x2=".461" y1=".275" y2="2.273" gradientUnits="userSpaceOnUse"><stop class="zax-lz03d"/><stop offset="1" class="zg7ndleiu"/></linearGradient><linearGradient id="i8Lpy6d" x1="1.945" x2=".563" y1="-.053" y2="1.674" gradientUnits="userSpaceOnUse"><stop offset=".139" class="szqa4cczu"/><stop offset=".488" class="i2tkr35ot"/></linearGradient><linearGradient id="irdQ4jd" x1="7.947" x2="1.822" y1="1.045" y2="8.686" gradientUnits="userSpaceOnUse"><stop offset=".066" class="u245iqdps"/><stop offset=".257" class="rijqbwbix"/><stop offset=".803" class="rijqbwbix"/><stop offset=".945" class="br5egpbia"/></linearGradient><linearGradient id="ieAH43d" x1="9.274" x2="1.899" y1="1.152" y2="10.466" gradientUnits="userSpaceOnUse"><stop class="bgt2mc6fp"/><stop offset=".294" class="j5rtt4bpo"/><stop offset=".801" class="x4ldqjsok"/></linearGradient><linearGradient id="iXqdE0c" x1="15.409" x2="14.862" y1="11.415" y2="11.02" gradientUnits="userSpaceOnUse"><stop class="yfcml8bws"/><stop offset="1" class="p_9_i7g9o"/></linearGradient><linearGradient id="ieZDGUb" x1="13.118" x2="14.389" y1="10.283" y2="11.297" gradientUnits="userSpaceOnUse"><stop class="i_sqp4rly"/><stop offset="1" class="psznkgfrn"/></linearGradient><linearGradient id="i9kL0Qd" x1="22.784" x2="27.831" y1="25.707" y2="23.473" gradientUnits="userSpaceOnUse"><stop class="tlllib2dn"/><stop offset="1" class="xrnpsubav"/></linearGradient><linearGradient id="iWhrpid" x1="16.726" x2="19.227" y1="6.351" y2="7.055" gradientUnits="userSpaceOnUse"><stop class="xwzzv0ryq"/><stop offset="1" class="l3_0v7cyw"/></linearGradient><linearGradient id="iFiGkwd" x1="16.935" x2="16.801" y1="5.663" y2="5.645" gradientUnits="userSpaceOnUse"><stop class="yzpor-bup"/><stop offset="1" class="jo-sb289k"/></linearGradient><linearGradient id="i6uCCss" x1="-.006" x2=".162" y1=".045" y2=".1" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><filter id="i6QEbxe" width="4.713" height="2.925" x="22.363" y="22.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.278431 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_7509"/></filter><filter id="iNfbuNd" width="10.328" height="8.578" x="13.034" y="15.372" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.501961 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_7509"/></filter><filter id="ifp5Hhb" width="3.953" height="7.5" x="19.299" y="17.176" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_7509" stdDeviation=".25"/></filter><filter id="i70yhHd" width="3.602" height="3.602" x="18.471" y="26.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_7509" stdDeviation=".125"/></filter><filter id="ijVKQPe" width="7.828" height="7.731" x="13.065" y="19.082" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.0745098 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_7509"/></filter><filter id="iofxE3b" width="4.543" height="3.256" x="22.178" y="23.378" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.360784 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_7509"/></filter><filter id="in1WPLc" width="8.506" height="4.313" x="11.084" y="16.015" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.270588 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_7509"/></filter><filter id="i868M0D" width="8.267" height="8.267" x="7.103" y="19.885" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.611765 0 0 0 0 0.807843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_7509"/></filter><filter id="imVeYPb" width="9.68" height="9.83" x="6.471" y="18.954" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.4 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_7509"/></filter><filter id="iR0zQjc" width="3.273" height="3.273" x="9.574" y="22.407" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.678431 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_2_7509"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_2_7509" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="4"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.207843 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_2_7509"/></filter><filter id="iTIfNKb" width="2.245" height="2.245" x="10.188" y="22.821" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_7509" stdDeviation=".05"/></filter><filter id="iohqtOb" width="9.401" height="9.401" x="6.476" y="19.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_7509" stdDeviation=".075"/></filter><filter id="i1Yhtye" width="12.217" height="12.217" x="5.109" y="17.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_7509" stdDeviation=".15"/></filter><filter id="idokYRd" width="3.238" height="8.483" x="11.304" y="10.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.627451 0 0 0 0 0.392157 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_7509"/></filter><filter id="i3TRLhb" width="4.025" height="1.2" x="7.084" y="11.156" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_7509" stdDeviation=".225"/></filter><filter id="ikBt5By" width="4.231" height="2.622" x="22.184" y="23.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_7509" stdDeviation=".2"/></filter><filter id="i12Tu3d" width="2.78" height="8.181" x="11.329" y="11.242" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_7509" stdDeviation=".25"/></filter><filter id="ifnWdKb" width="4.337" height="5.248" x="15.221" y="3.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.329412 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_7509"/></filter><filter id="inVdQRb" width="6.997" height="6.474" x="13.037" y="2.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.843137 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_7509"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.607843 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_7509" result="effect2_innerShadow_2_7509"/></filter><filter id="iaJNJWc" width="6.997" height="6.474" x="13.037" y="2.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.294118 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_7509"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.172549 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_7509" result="effect2_innerShadow_2_7509"/></filter><filter id="iARThPd" width=".947" height=".435" x="18.087" y="4.942" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.168627 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_7509"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-in-manual-wheelchair-facing-right-medium" /></template>
<style>
.a10dt2bqr {
  stop-color: var(--svg-color--8c6396, #8C6396);
}

.a9bmddp5j {
  cx: 0.058px;
  cy: 0.079px;
  rx: 0.058px;
  ry: 0.079px;
}

.a9m8t591o {
  stop-color: var(--svg-color--5f3b5c, #5F3B5C);
}

.aew93sw7h {
  stop-color: var(--svg-color--8c6396, #8C6396);
  stop-opacity: 0;
}

.answrebhr {
  stop-color: var(--svg-color--79747b, #79747B);
}

.ao9a_pbsn {
  stop-color: var(--svg-color--9c6e67, #9C6E67);
  stop-opacity: 0;
}

.av0_6yb2f {
  stop-color: var(--svg-color--a66d75, #A66D75);
}

.ba4ju4bdt {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M18.037 7.07a.113.113 0 0 0-.033.157c.166.253.46.372.554.403a.113.113 0 0 0 .071-.215c-.081-.027-.313-.126-.435-.312a.113.113 0 0 0-.157-.033");
}

.be03fp4ln {
  stroke: var(--svg-color--bc9682, #BC9682);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m13.034 11.942l-.84 1.272a.98.98 0 0 0-.146.733c.222 1.1.717 3.27 1.36 4.776");
}

.bfwbq1bpl {
  stop-color: var(--svg-color--615f82, #615F82);
}

.bgt2mc6fp {
  stop-color: var(--svg-color--4e4558, #4E4558);
}

.br5egpbia {
  stop-color: var(--svg-color--96909f, #96909F);
}

.bxntujdns {
  stop-color: var(--svg-color--8c8181, #8C8181);
}

.c6hrvfqjf {
  stop-color: var(--svg-color--997fd4, #997FD4);
  stop-opacity: 0;
}

.c9gtc1bjl {
  stop-color: var(--svg-color--c2b1db, #C2B1DB);
}

.cjqgdpbwq {
  stop-color: var(--svg-color--4d3659, #4D3659);
}

.cloqvszsb {
  d: path("M15.811 10.454a1.11 1.11 0 1 0-1.813-1.283l-1.483 2.107c.871.48 1.793 1.289 1.793 1.289z");
}

.cvqtxmgmy {
  d: path("M20.893 17.92a.4.4 0 0 0-.4-.4h-8.881v2.508h9.281z");
}

.cwu_shb3d {
  stop-color: var(--svg-color--bf223d, #BF223D);
}

.d_4otnung {
  stop-color: var(--svg-color--948f93, #948F93);
}

.d9__ewb5v {
  fill: var(--svg-color--7f5dc0, #7F5DC0);
  d: path("M15.811 10.454a1.11 1.11 0 1 0-1.813-1.283l-1.483 2.107c.871.48 1.793 1.289 1.793 1.289z");
}

.desyi4b3l {
  stop-color: var(--svg-color--ba9682, #BA9682);
}

.diiog7gjn {
  fill: var(--svg-color--513a3c, #513A3C);
  fill-rule: evenodd;
  d: path("M18.658 5.214a.7.7 0 0 1 .194.028a.136.136 0 1 0 .09-.257a1 1 0 0 0-.28-.043a.9.9 0 0 0-.395.074a.136.136 0 0 0 .112.249a.7.7 0 0 1 .278-.051");
}

.dntytqbyu {
  stop-color: var(--svg-color--514576, #514576);
}

.dqa0zuk3f {
  stop-color: var(--svg-color--8e5d49, #8E5D49);
}

.dr65abcro {
  stop-color: var(--svg-color--b61f30, #B61F30);
}

.e3f4ywbbl {
  stop-color: var(--svg-color--64487f, #64487F);
  stop-opacity: 0;
}

.ed2n0rbpd {
  fill: var(--svg-color--745182, #745182);
  d: path("M14.311 12.563c-.426-.11-1.248-.693-1.789-1.293c.414.044 1.345.377 1.79 1.293");
}

.ene2socfu {
  stop-color: var(--svg-color--ad8570, #AD8570);
}

.ennuonbfb {
  stop-color: var(--svg-color--675a75, #675A75);
  stop-opacity: 0;
}

.erfrsrblk {
  stop-color: var(--svg-color--7a727f, #7A727F);
  stop-opacity: 0;
}

.erlv03bqf {
  stop-color: var(--svg-color--876eb4, #876EB4);
  stop-opacity: 0;
}

.fbej3eerw {
  d: path("M0 0h1.162v5.449H0z");
}

.ffz88hbch {
  fill: var(--svg-color--a87f6b, #A87F6B);
  d: path("m13.345 13.528l1.025-1.344l-1.418-1.133c-.203.239-.703.942-1.144 1.524c-.452.595-.448 1.383-.352 1.734c.232 1.052.753 3.316.922 3.953c.211.797.461.945.938 1.055s1.285-.313 1.222-.93c-.027-.48-.386-.695-.644-1.484a59 59 0 0 1-.643-2.99a.5.5 0 0 1 .094-.385");
}

.fiiks7b8f {
  stop-color: var(--svg-color--301d2f, #301D2F);
}

.ft5dv1b6b {
  fill: none;
}

.fxt2czijw {
  cx: 1.723px;
  cy: 1.723px;
  r: 1.723px;
}

.fzo002mry {
  stop-color: var(--svg-color--79747b, #79747B);
  stop-opacity: 0;
}

.g0aomjwhv {
  stop-color: var(--svg-color--49344d, #49344D);
  stop-opacity: 0;
}

.g4u-v_bhx {
  stop-color: var(--svg-color--89828d, #89828D);
  stop-opacity: 0;
}

.g6i5vgbtc {
  stop-color: var(--svg-color--7f758d, #7F758D);
}

.g87nnpbqu {
  stop-color: var(--svg-color--a67d65, #A67D65);
}

.gbejtwrll {
  cx: 4.059px;
  cy: 4.059px;
  r: 4.059px;
}

.gg9-_hbxs {
  fill: var(--svg-color--fff, #fff);
  d: path("m18.912 6.228l-.875-.191c.075-.347.333-.585.574-.533c.242.053.377.377.301.724");
}

.gldbv0pab {
  stop-color: var(--svg-color--948f93, #948F93);
  stop-opacity: 0;
}

.gsg9xvp1r {
  fill: var(--svg-color--2f2c2d, #2F2C2D);
  d: path("M18.102 5.577c.142-.09.34-.075.422-.056l-.358.355c-.129-.036-.24-.185-.064-.299");
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gykv57cqb {
  fill: var(--svg-color--8a7e97, #8A7E97);
  fill-rule: evenodd;
  d: path("M11.311 28.784a4.84 4.84 0 1 1 0-9.68a4.84 4.84 0 0 1 0 9.68m0-.782a4.059 4.059 0 1 1 0-8.117a4.059 4.059 0 0 1 0 8.117");
}

.h_vbtipyr {
  stop-color: var(--svg-color--5f5168, #5F5168);
  stop-opacity: 0;
}

.h0a-qhb0e {
  stop-color: var(--svg-color--e35373, #E35373);
  stop-opacity: 0;
}

.hagwkib2x {
  stop-color: var(--svg-color--6a509b, #6A509B);
  stop-opacity: 0;
}

.hu5mq1ced {
  d: path("M16.618 15.376c.31-1.038.936-3.994.588-5.739c-.437-1.445-1.742-1.46-2.375-1.39c-.773.086-1.601.476-2.039 1.836c-.453 1.25-.58 4.08-.633 5.445h.875v-.152z");
}

.hzlclw72u {
  fill: var(--svg-color--755ba9, #755BA9);
  d: path("M16.618 15.376c.31-1.038.936-3.994.588-5.739c-.437-1.445-1.742-1.46-2.375-1.39c-.773.086-1.601.476-2.039 1.836c-.453 1.25-.58 4.08-.633 5.445h.875v-.152z");
}

.i_sqp4rly {
  stop-color: var(--svg-color--9477bc, #9477BC);
}

.i24r0nbmv {
  stop-color: var(--svg-color--876eb4, #876EB4);
}

.i2tkr35ot {
  stop-color: var(--svg-color--524a5b, #524A5B);
  stop-opacity: 0;
}

.id-v9-mic {
  stop-color: var(--svg-color--342252, #342252);
}

.ieoaw0bcr {
  fill-rule: evenodd;
  d: path("M17.514 17.165c.428 0 .776.347.776.775v2.389h1a.15.15 0 0 0 .15-.15V17.94a1.925 1.925 0 0 0-1.926-1.925h-6.18a.25.25 0 0 0-.25.25v2.75h1.15v-1.85z");
}

.ig81yhx8p {
  stop-color: var(--svg-color--cd3945, #CD3945);
}

.igg0ouipp {
  stop-color: var(--svg-color--a67d65, #A67D65);
  stop-opacity: 0;
}

.ihrk5ivyw {
  fill: var(--svg-color--4d4a7f, #4D4A7F);
  d: path("m25.452 22.426l-2.093-.058l-.997.824l.797 1.8l3.498-1.576c.174-.078.278-.274.182-.44c-.242-.42-.748-.55-1.387-.55");
}

.ildpa548e {
  stop-color: var(--svg-color--3b3145, #3B3145);
}

.io62jp_6h {
  stop-color: var(--svg-color--c72b4c, #C72B4C);
}

.ip5996ykk {
  stop-color: var(--svg-color--432e67, #432E67);
}

.j5rtt4bpo {
  stop-color: var(--svg-color--4e4558, #4E4558);
  stop-opacity: 0;
}

.j7vr7jxtp {
  width: 7.832px;
  height: 1.372px;
  rx: 0.686px;
}

.ja_znnx3a {
  stop-color: var(--svg-color--423650, #423650);
}

.jli-mvbgu {
  stop-color: var(--svg-color--ca283c, #CA283C);
}

.jo-sb289k {
  stop-color: var(--svg-color--a17363, #A17363);
  stop-opacity: 0;
}

.jptbwygwk {
  cx: 0.494px;
  cy: 0.494px;
  r: 0.494px;
}

.ju5i36bgg {
  cx: 5.559px;
  cy: 5.559px;
  r: 5.559px;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
}

.jz-3fab0l {
  stop-color: var(--svg-color--301d2f, #301D2F);
  stop-opacity: 0;
}

.k4435esfk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m25.815 24.286l-3.031 1.421");
}

.k8j-nbbgc {
  stop-color: var(--svg-color--a0776e, #A0776E);
  stop-opacity: 0;
}

.kbsq_bcao {
  width: 4.847px;
  height: 1.452px;
  rx: 0.726px;
}

.kn42mcchn {
  stop-color: var(--svg-color--967dc8, #967DC8);
}

.kplqz4bbv {
  stop-color: var(--svg-color--9e6563, #9E6563);
  stop-opacity: 0;
}

.ktc-s82to {
  stop-color: var(--svg-color--615f82, #615F82);
  stop-opacity: 0;
}

.ku1djbbcg {
  stop-color: var(--svg-color--64487f, #64487F);
}

.kzr6sffft {
  stop-color: var(--svg-color--967dc8, #967DC8);
  stop-opacity: 0;
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l3_0v7cyw {
  stop-color: var(--svg-color--ab826c, #AB826C);
}

.laa0aab1b {
  stop-color: var(--svg-color--46295f, #46295F);
}

.lfwvarbqo {
  stop-color: var(--svg-color--1b1423, #1B1423);
}

.lhhdsccyq {
  stop-color: var(--svg-color--a66d75, #A66D75);
  stop-opacity: 0;
}

.lucd7-9cq {
  stop-color: var(--svg-color--3d2c4c, #3D2C4C);
}

.lvn5-ac9d {
  stop-color: var(--svg-color--c62f3a, #C62F3A);
}

.m_-fcub7q {
  d: path("m25.452 22.426l-2.093-.058l-.997.824l.797 1.8l3.498-1.576c.174-.078.278-.274.182-.44c-.242-.42-.748-.55-1.387-.55");
}

.mh0ys7bkx {
  fill: var(--svg-color--ffb629, #FFB629);
  d: path("M19.88 4.452c.23-.33.148-.75.09-.9c-.244-.648-.86-.852-1.286-.766c-.5.101-.719.107-1.353-.193c-.712-.338-1.72-.501-2.385.253s-.315 1.847-.547 2.348s-.595.488-.851 1.07c-.336.875.157 1.556.593 1.781c.437.226 1.443.24 1.923-.467c.785-1.157.543-1.854.792-2.467c.25-.612.696-.687 1.358-.398c.78.34 1.358.179 1.666-.26");
}

.mkf18fb1r {
  width: 4.847px;
  height: 1.452px;
  fill: var(--svg-color--7c767d, #7C767D);
  rx: 0.726px;
}

.mu7eh4v_c {
  fill: var(--svg-color--553750, #553750);
  d: path("m22.753 24.176l-1.922-6.5l-1.032 1.75z");
}

.mz7wlj55e {
  stop-color: var(--svg-color--3f2245, #3F2245);
  stop-opacity: 0;
}

.n0w_cmcuq {
  stop-color: var(--svg-color--523c64, #523C64);
}

.n3h2abc_m {
  stop-color: var(--svg-color--654970, #654970);
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

.nlxszcchf {
  d: path("M19.526 6.519a.9.9 0 0 1-.14-.455l-.159-.034l-.217.996c.164.163.44.203.56.039c.104-.14.094-.346-.044-.546");
}

.nz7jfnb_b {
  stop-color: var(--svg-color--ad7f6d, #AD7F6D);
}

.o2t29rbsm {
  stop-color: var(--svg-color--37213e, #37213E);
}

.odw8jmnks {
  stop-color: var(--svg-color--a17467, #A17467);
}

.oqr4-mbfk {
  stop-color: var(--svg-color--332156, #332156);
}

.p_9_i7g9o {
  stop-color: var(--svg-color--7c5cb9, #7C5CB9);
  stop-opacity: 0;
}

.p2ahpfb5s {
  stop-color: var(--svg-color--a0776e, #A0776E);
}

.p9ept44wt {
  stop-color: var(--svg-color--604098, #604098);
  stop-opacity: 0;
}

.pe7odhb7d {
  stop-color: var(--svg-color--916051, #916051);
}

.psznkgfrn {
  stop-color: var(--svg-color--9477bc, #9477BC);
  stop-opacity: 0;
}

.pyh7r6bag {
  stop-color: var(--svg-color--980a27, #980A27);
}

.q6suc5ubz {
  stop-color: var(--svg-color--7a727f, #7A727F);
}

.qb3gn8bfr {
  stop-color: var(--svg-color--8a7794, #8A7794);
  stop-opacity: 0;
}

.qx2qyypot {
  stop-color: var(--svg-color--2b1e2d, #2B1E2D);
}

.r04agib6p {
  stop-color: var(--svg-color--3f2245, #3F2245);
}

.rg3z6xbem {
  stop-color: var(--svg-color--c72b4c, #C72B4C);
  stop-opacity: 0;
}

.rgr8nhbdi {
  stop-color: var(--svg-color--654970, #654970);
  stop-opacity: 0;
}

.rhkf30kvu {
  stop-color: var(--svg-color--bd927e, #BD927E);
  stop-opacity: 0;
}

.rijqbwbix {
  stop-color: var(--svg-color--938c9b, #938C9B);
  stop-opacity: 0;
}

.rj2ywtb6v {
  stop-color: var(--svg-color--583437, #583437);
}

.roww1df0l {
  stop-color: var(--svg-color--675a75, #675A75);
}

.rs99u8bqf {
  stop-color: var(--svg-color--bb3161, #BB3161);
}

.s_nhb9bnh {
  stop-color: var(--svg-color--4e4b80, #4E4B80);
  stop-opacity: 0;
}

.s03jqe71p {
  stop-color: var(--svg-color--8b6662, #8B6662);
}

.s4mm7wj7e {
  width: 1.242px;
  height: 6.695px;
  fill: var(--svg-color--776a86, #776A86);
  rx: 0.621px;
}

.s6599442t {
  cx: 4.476px;
  cy: 4.476px;
  r: 4.476px;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
}

.sa2yvrtdg {
  stop-color: var(--svg-color--918697, #918697);
}

.sqtinbbgr {
  stop-color: var(--svg-color--cd3945, #CD3945);
  stop-opacity: 0;
}

.sstiaym3o {
  stop-color: var(--svg-color--655558, #655558);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.svkl-3bgp {
  fill-rule: evenodd;
  d: path("M11.311 30.211a6.268 6.268 0 1 1 0-12.535a6.268 6.268 0 0 1 0 12.535m0-1.427a4.84 4.84 0 1 1 0-9.68a4.84 4.84 0 0 1 0 9.68");
}

.szqa4cczu {
  stop-color: var(--svg-color--524a5b, #524A5B);
}

.szzuw3bbf {
  width: 4.227px;
  height: 1.211px;
  rx: 0.605px;
}

.t9-j-pbql {
  stop-color: var(--svg-color--2f1f36, #2F1F36);
  stop-opacity: 0;
}

.tis1nnbrp {
  stop-color: var(--svg-color--2f1f36, #2F1F36);
}

.tlllib2dn {
  stop-color: var(--svg-color--a198a7, #A198A7);
}

.tnr6qjbmk {
  stop-color: var(--svg-color--997fd4, #997FD4);
}

.toti2-rqa {
  stop-color: var(--svg-color--685294, #685294);
  stop-opacity: 0;
}

.u245iqdps {
  stop-color: var(--svg-color--938c9b, #938C9B);
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.uqxwa8ern {
  stop-color: var(--svg-color--3c2053, #3C2053);
}

.us60yytqw {
  stop-color: var(--svg-color--3b223c, #3B223C);
  stop-opacity: 0;
}

.uta33k16w {
  stroke: var(--svg-color--4c3e59, #4C3E59);
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M10.659 11.756H7.534");
}

.v06h3pbnx {
  stop-color: var(--svg-color--3f2c51, #3F2C51);
}

.v5no8zo2o {
  cx: 0.973px;
  cy: 0.973px;
  r: 0.973px;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
}

.vb_gc7b6b {
  stop-color: var(--svg-color--c19382, #C19382);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vczf7ubhl {
  width: 1.242px;
  height: 6.695px;
  rx: 0.621px;
}

.vp5ble8bb {
  stop-color: var(--svg-color--89828d, #89828D);
}

.vxrkdvuju {
  stop-color: var(--svg-color--31223f, #31223F);
  stop-opacity: 0;
}

.w-8ci9bkh {
  stop-color: var(--svg-color--c8325e, #C8325E);
}

.wxymobcro {
  fill: var(--svg-color--52333b, #52333B);
  d: path("M19.88 4.452c.23-.33.148-.75.09-.9c-.244-.648-.86-.852-1.286-.766c-.5.101-.719.107-1.353-.193c-.712-.338-1.72-.501-2.385.253s-.315 1.847-.547 2.348s-.595.488-.851 1.07c-.336.875.157 1.556.593 1.781c.437.226 1.443.24 1.923-.467c.785-1.157.543-1.854.792-2.467c.25-.612.696-.687 1.358-.398c.78.34 1.358.179 1.666-.26");
}

.x3lzt0c-k {
  stop-color: var(--svg-color--d52e59, #D52E59);
}

.x4ldqjsok {
  stop-color: var(--svg-color--484151, #484151);
}

.x8v8a_bhe {
  stop-color: var(--svg-color--49344d, #49344D);
}

.xb91u7b-b {
  stop-color: var(--svg-color--3b223c, #3B223C);
}

.xfcyplbyz {
  stop-color: var(--svg-color--654e4b, #654E4B);
  stop-opacity: 0;
}

.xhq7i0bkh {
  d: path("M20.089 15.372h-7.055v3.156h6.844l2.406 5.172l1.078-1.328c-.156-.797-.593-3.055-.96-4.836c-.376-1.82-1.594-2.164-2.313-2.164");
}

.xrnpsubav {
  stop-color: var(--svg-color--a198a7, #A198A7);
  stop-opacity: 0;
}

.xudiynxns {
  stop-color: var(--svg-color--5f5168, #5F5168);
}

.xwzzv0ryq {
  stop-color: var(--svg-color--a87a72, #A87A72);
}

.y28p9db6y {
  d: path("M19.514 5.622c.12-.717-.035-1.109-.121-1.233l-3.306-.72l-.666 2.79c.358 2.047 2.683 2.637 3.181 2.034s.773-2.04.912-2.87");
}

.y3ij90b8v {
  stop-color: var(--svg-color--8a7794, #8A7794);
}

.y9geofb4u {
  d: path("M19.88 4.452c.23-.33.148-.75.09-.9c-.244-.648-.86-.852-1.286-.766c-.5.101-.719.107-1.353-.193c-.712-.338-1.72-.501-2.385.253s-.315 1.847-.547 2.348s-.595.488-.851 1.07c-.336.875.157 1.556.593 1.781c.437.226 1.443.24 1.923-.467c.785-1.157.543-1.854.792-2.467c.25-.612.696-.687 1.358-.398c.78.34 1.358.179 1.666-.26");
}

.yaxokabcj {
  fill-rule: evenodd;
  d: path("M20.893 19.88c0-.484-.337-.797-.82-.797h-7.008v7.53h4.726a.895.895 0 0 0 .864-.685c.082-.331.269-.659.562-.925c.28-.253.606-.405.928-.461a.896.896 0 0 0 .748-.877zm-1.5.453a.25.25 0 0 1 .25.25v2.488c0 .18-.12.335-.288.4a3.2 3.2 0 0 0-.977.606c-.328.297-.58.647-.752 1.023a.44.44 0 0 1-.39.264h-2.92v-5.032z");
}

.ydp5je9ep {
  cx: 1.551px;
  cy: 1.551px;
  r: 1.551px;
}

.yfcml8bws {
  stop-color: var(--svg-color--866db3, #866DB3);
}

.yhtwjqbxf {
  d: path("M18.376 6.11v-.003c.063-.283.234-.487.384-.454s.222.289.16.573v.003z");
}

.ym5c6ha3r {
  stop-color: var(--svg-color--980a27, #980A27);
  stop-opacity: 0;
}

.ynhlcccje {
  cx: 1.137px;
  cy: 1.137px;
  r: 1.137px;
}

.ynyobdc8w {
  d: path("m17.23 7.572l-1.75-.896l-.753 2.258l1.77.647z");
}

.yp_2y0bkd {
  stop-color: var(--svg-color--d53155, #D53155);
}

.ys8863_0j {
  stop-color: var(--svg-color--e35373, #E35373);
}

.yu7wmpb_a {
  stop-color: var(--svg-color--4b3d47, #4B3D47);
}

.yutdbcb6i {
  stop-color: var(--svg-color--655558, #655558);
  stop-opacity: 0;
}

.yzpor-bup {
  stop-color: var(--svg-color--a17363, #A17363);
}

.z-rtjcc0y {
  stop-color: var(--svg-color--31223f, #31223F);
}

.z3yur8boj {
  stop-color: var(--svg-color--dccaee, #DCCAEE);
}

.z4for55kd {
  stop-color: var(--svg-color--1b1423, #1B1423);
  stop-opacity: 0;
}

.zax-lz03d {
  stop-color: var(--svg-color--463a52, #463A52);
}

.zc6u5lbhd {
  d: path("m16.866 6.394l.1-1.313a.659.659 0 0 0-.1 1.313");
}

.zg7ndleiu {
  stop-color: var(--svg-color--443850, #443850);
}

.zige1b1kr {
  stop-color: var(--svg-color--6e5c72, #6E5C72);
  stop-opacity: 0;
}

.zp_517jgm {
  stop-color: var(--svg-color--604098, #604098);
}

.zqqbrtbmz {
  d: path("m18.55 6.148l.01-.065c.036-.164.134-.282.22-.263s.127.167.09.331l-.017.063z");
}

.zuaxx5qad {
  stop-color: var(--svg-color--7f758d, #7F758D);
  stop-opacity: 0;
}

.zy9nvz9pf {
  stop-color: var(--svg-color--654e4b, #654E4B);
}

.zzc1m6bsl {
  stop-color: var(--svg-color--4b3d47, #4B3D47);
  stop-opacity: 0;
}

</style>
