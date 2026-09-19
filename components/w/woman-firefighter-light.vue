<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ilRo1id)"><path fill="url(#i4a0pNb)" class="linpwzqhe"/><path fill="url(#i1ptMxc)" class="linpwzqhe"/></g><g filter="url(#iexSDnb)"><path fill="url(#iP57O3b)" clip-rule="evenodd" class="bkd5s605t"/><path fill="url(#iCzAxDb)" clip-rule="evenodd" class="bkd5s605t"/><path fill="url(#irxCdob)" clip-rule="evenodd" class="bkd5s605t"/><path fill="url(#i6ssShe)" clip-rule="evenodd" class="bkd5s605t"/></g><path class="vwc2t-btp"/><path fill="url(#iqN6V4b)" class="kngw6fbep"/><path fill="url(#i2gSgbe)" class="kngw6fbep"/><path fill="url(#idcBZkt)" class="kngw6fbep"/><path fill="url(#iiLw8Vb)" class="kngw6fbep"/><path fill="url(#ilGajNb)" class="kngw6fbep"/><path fill="url(#isZrtzc)" class="kngw6fbep"/><path fill="url(#iJkm9gA)" class="ajcn8-ycn"/><path fill="url(#ih3vBxb)" class="ajcn8-ycn"/><path fill="url(#i9JMave)" class="ajcn8-ycn"/><path fill="url(#inI3Unb)" class="vylrb5bvm"/><path fill="url(#iAOYtlU)" class="vylrb5bvm"/><path fill="url(#irfAPUC)" class="dbj0sjb-p"/><path fill="url(#iI325ic)" class="ja-6i29rv"/><g filter="url(#iK8jGpe)"><path fill="url(#ij2w2Ad)" class="n4wu3h9rb"/></g><g filter="url(#iYBftcb)"><path fill="url(#inniGRJ)" class="o1z42mbzo"/><path fill="url(#iA8ZMom)" class="o1z42mbzo"/></g><g filter="url(#iciNQac)"><path class="e3fuicbbj"/><path fill="url(#itR2gHe)" class="ogeiazbnd"/></g><g filter="url(#iH3EzNA)"><path class="c6c-ztbag"/><path fill="url(#iUWdpQe)" class="mb3jp1v8b"/></g><path fill="url(#iRx3Sgd)" class="n4wu3h9rb"/><path fill="url(#irZkzhd)" class="n4wu3h9rb"/><g filter="url(#i9pyfZc)"><path fill="url(#iIg5xFb)" class="o1z42mbzo"/><path fill="url(#ipKRtEe)" class="o1z42mbzo"/><path fill="url(#i6Gqfpc)" class="o1z42mbzo"/></g><g filter="url(#iRkJuHc)"><path class="ogiwwtbff"/></g><g filter="url(#iz8G0jW)"><path class="vlu36uddq"/></g><g filter="url(#iHhiJnc)"><path fill="url(#im15Szd)" class="j-oh5nkfx"/><path fill="url(#iJnCIXF)" class="j-oh5nkfx"/><path fill="url(#i2S5myb)" class="j-oh5nkfx"/><path fill="url(#itutMPb)" class="j-oh5nkfx"/><path fill="url(#ifdG7ZS)" class="j-oh5nkfx"/><path fill="url(#iuS4csd)" class="j-oh5nkfx"/><path fill="url(#i2xEaMc)" class="j-oh5nkfx"/></g><path fill="url(#iVUU1rX)" class="j-oh5nkfx"/><path fill="url(#im6NePb)" class="j-oh5nkfx"/><path fill="url(#iVUU1rX)" class="j-oh5nkfx"/><path fill="url(#im6NePb)" class="j-oh5nkfx"/><path fill="url(#iHiG8jd)" class="j-oh5nkfx"/><g filter="url(#i3PcKgd)"><path class="la-qn6bfl"/></g><g filter="url(#iHRvqAd)"><path class="tz8-2cckd"/><path fill="url(#ixiScye)" class="kr3_qi-9c"/><path fill="url(#iqT8trb)" class="kr3_qi-9c"/><path fill="url(#iiVGcpe)" class="kr3_qi-9c"/><path fill="url(#i4SU0cd)" class="kr3_qi-9c"/></g><path stroke="url(#iSkPpGb)" class="gxfmc-q1q"/><g filter="url(#i3M8rEc)"><path class="oyr8gxaci"/></g><g filter="url(#iXKiWDb)"><path class="l9d2msbgp"/></g><g filter="url(#i4NZosw)"><path class="dvybz7bcd"/></g><g filter="url(#ilQn8Eb)"><path clip-rule="evenodd" class="e2tiqybzr"/></g><path class="cmn7xo6lx"/><path fill="url(#iZ5YIPc)" class="gky-wnwiz"/><path class="t56q3abaj"/><g filter="url(#iAqaFtc)"><path class="vb_6e0-eb"/><path fill="url(#inBJCge)" class="x01c9dvva"/></g><g filter="url(#inpbJ6c)"><path fill="url(#iRMdPib)" class="pl04ozb6c"/></g><path class="l-xt2yl6d"/><path fill="url(#icanrEd)" class="cx0xfhbrr"/><path class="i1kk6cv0u"/><g filter="url(#iXqbtde)"><path fill="url(#iuC9Kfb)" class="pmefcq5-m"/></g><g filter="url(#i16Zuac)"><ellipse transform="rotate(-27.914 12.13 10.101)" class="juwb30xpp"/><ellipse fill="url(#iB4rrTb)" transform="rotate(-27.914 12.13 10.101)" class="wqbwr3bsq"/></g><path fill="url(#ipeIwwd)" class="v5pkyqbhx"/><path fill="url(#ih5nvHe)" class="v5pkyqbhx"/><path fill="url(#izHz1gd)" class="v5pkyqbhx"/><path fill="url(#iEsU6Jd)" class="v5pkyqbhx"/><path fill="url(#ia6hdgb)" class="v5pkyqbhx"/><path class="e3e67-bvh"/><path fill="url(#inGX0Oc)" class="oyh5fnr6n"/><path fill="url(#i9mB5Mc)" class="oyh5fnr6n"/><path fill="url(#iUnDHVd)" class="oyh5fnr6n"/><path fill="url(#iKjUOTb)" class="oyh5fnr6n"/><path fill="url(#ivHTDTb)" class="acylf0bup"/><path fill="url(#izpcbVd)" class="acylf0bup"/><path fill="url(#idR7qVz)" class="acylf0bup"/><path fill="url(#ibPujte)" class="acylf0bup"/><path fill="url(#i6qz0xW)" class="acylf0bup"/><path fill="url(#ij2mDJd)" class="onmhnc-bl"/><path fill="url(#ij0qnyb)" class="onmhnc-bl"/><path fill="url(#iTdENFb)" class="onmhnc-bl"/><g filter="url(#iDJn8Fb)"><path fill="url(#iKGw4kt)" class="recb7tbvt"/><path fill="url(#iyoBo3i)" class="recb7tbvt"/></g><g filter="url(#i5v4vkc)"><path fill="url(#ibeddjd)" class="alecchcgl"/><path fill="url(#iO3rDAc)" class="alecchcgl"/></g><path fill="url(#iiVeO6c)" class="alecchcgl"/><path fill="url(#i7W12qd)" class="alecchcgl"/><g filter="url(#i4E1EZd)"><path fill="url(#i5b1ojc)" class="jyz4ivbym"/><path fill="url(#ifSfzbe)" class="jyz4ivbym"/><path fill="url(#ih6dC9c)" class="jyz4ivbym"/></g><g filter="url(#iSAtSac)"><path fill="url(#ibijqYb)" class="xfqkuki0h"/><path fill="url(#iyoK4Kd)" class="xfqkuki0h"/><path fill="url(#iJhoPse)" class="xfqkuki0h"/></g><g filter="url(#i1YaM1H)"><path fill="url(#i9kTuLc)" class="npvir-bzx"/></g><g filter="url(#iTuIhbc)"><path stroke="url(#iJ67e8c)" class="cj_ualb6i"/></g><g filter="url(#iZOi0fe)"><path class="f64lk-nyh"/></g><g filter="url(#iVudaFc)"><path class="bulogvb1g"/><path fill="url(#irUvMbp)" class="ph5kwxbvm"/><path fill="url(#iuLQ4mb)" class="ph5kwxbvm"/></g><g filter="url(#iJTcE5c)"><path fill="url(#icL13gd)" class="vg3v5gbvt"/></g><path fill="url(#iHtsopb)" class="vg3v5gbvt"/><path fill="url(#i0XH97d)" class="vg3v5gbvt"/><defs><radialGradient id="iCzAxDb" cx="0" cy="0" r="1" gradientTransform="matrix(1.95312 -4.20313 .66692 .3099 7.194 12.066)" gradientUnits="userSpaceOnUse"><stop class="niybxc2uq"/><stop offset="1" class="kyuvy4bbj"/></radialGradient><radialGradient id="irxCdob" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.55404 -9.91719 0 14.597 9.843)" gradientUnits="userSpaceOnUse"><stop offset=".931" class="i8--_db9h"/><stop offset=".995" class="tw2yr-3fp"/></radialGradient><radialGradient id="i6ssShe" cx="0" cy="0" r="1" gradientTransform="rotate(173.648 10.7 6.981)scale(1.60475 1.63343)" gradientUnits="userSpaceOnUse"><stop class="nfcjmccxh"/><stop offset="1" class="h3fma_n5f"/></radialGradient><radialGradient id="iqN6V4b" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.43636 -8.2868 0 14.582 15.943)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="ze-km1b7g"/><stop offset="1" class="nfddei0pp"/></radialGradient><radialGradient id="i2gSgbe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -8.375 13.302 26.254)" gradientUnits="userSpaceOnUse"><stop class="ls7-cblkb"/><stop offset="1" class="tbz0q_48a"/></radialGradient><radialGradient id="idcBZkt" cx="0" cy="0" r="1" gradientTransform="matrix(-1.625 0 0 -5.46875 21.646 26.129)" gradientUnits="userSpaceOnUse"><stop class="voemc8h9d"/><stop offset="1" class="osd7ifb8c"/></radialGradient><radialGradient id="iiLw8Vb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.40626 -1.21873 1.72833 -6.24868 19.552 23.941)" gradientUnits="userSpaceOnUse"><stop offset=".273" class="d-ykpkboz"/><stop offset="1" class="f8x3opbgo"/></radialGradient><radialGradient id="ilGajNb" cx="0" cy="0" r="1" gradientTransform="matrix(-11.0625 0 0 -16.6672 18.302 22.723)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="eqb1ki6td"/><stop offset="1" class="dmxjdc_5c"/></radialGradient><radialGradient id="isZrtzc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55668 4.16175 -7.47563 -2.79621 19.02 16.26)" gradientUnits="userSpaceOnUse"><stop class="nuif9xlfl"/><stop offset="1" class="o41nkwbqu"/></radialGradient><radialGradient id="iJkm9gA" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.7832 3.37648 0 6.864 29.754)" gradientUnits="userSpaceOnUse"><stop offset=".658" class="q_n5wkbyq"/><stop offset="1" class="x8m9vebtt"/></radialGradient><radialGradient id="i9JMave" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.8437 2.89364 0 7.607 29.973)" gradientUnits="userSpaceOnUse"><stop class="ygstjnb_e"/><stop offset="1" class="idk0shbpn"/></radialGradient><radialGradient id="inI3Unb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.40144 -2.74144 0 24.114 23.977)" gradientUnits="userSpaceOnUse"><stop class="deg-o6bbc"/><stop offset="1" class="q-uw1wb3b"/></radialGradient><radialGradient id="iAOYtlU" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.5625 -2.47704 0 21.577 22.972)" gradientUnits="userSpaceOnUse"><stop offset=".036" class="mr8fywmtc"/><stop offset="1" class="bcdc9wb8u"/></radialGradient><radialGradient id="inniGRJ" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 18.623 11.437)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="iA8ZMom" cx="0" cy="0" r="1" gradientTransform="matrix(.9973 .28494 -.1498 .52432 19.645 9.216)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="itR2gHe" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 40.972 -47.944)scale(1.30459)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="iUWdpQe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21686 0 0 -1.164 9.917 10.998)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="irZkzhd" cx="0" cy="0" r="1" gradientTransform="rotate(139.201 2.966 7.315)scale(1.96086)" gradientUnits="userSpaceOnUse"><stop offset=".784" class="uc4j85bvv"/><stop offset="1" class="nal4e_0hy"/></radialGradient><radialGradient id="iIg5xFb" cx="0" cy="0" r="1" gradientTransform="rotate(-48.104 22.96 -15.402)scale(2.73591 3.34042)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="ipKRtEe" cx="0" cy="0" r="1" gradientTransform="matrix(1.31576 .7375 -.2085 .37199 19.654 9.317)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="i6Gqfpc" cx="0" cy="0" r="1" gradientTransform="matrix(2.28386 1.78125 -.98827 1.26713 19.41 9.038)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="ls935lkhb"/><stop offset="1" class="al5ersbzq"/></radialGradient><radialGradient id="im15Szd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.125 1.57166 -1.43353 -4.67456 16.882 11.53)" gradientUnits="userSpaceOnUse"><stop class="zco4q0bhr"/><stop offset=".819" class="qes9fmppr"/></radialGradient><radialGradient id="iJnCIXF" cx="0" cy="0" r="1" gradientTransform="matrix(-3.46116 .45112 -.49796 -3.82051 17.835 11.822)" gradientUnits="userSpaceOnUse"><stop class="z-rzt8b_f"/><stop offset="1" class="tk20gvbnd"/></radialGradient><radialGradient id="i2S5myb" cx="0" cy="0" r="1" gradientTransform="matrix(1.30737 -3.78806 4.80634 1.6588 12.203 17.788)" gradientUnits="userSpaceOnUse"><stop class="fvm07vbkd"/><stop offset="1" class="n1w64orcn"/></radialGradient><radialGradient id="itutMPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.72467 -7.78405 0 14.583 10.243)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="j-6z4ebeh"/><stop offset="1" class="mevfg8o-k"/></radialGradient><radialGradient id="ifdG7ZS" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 7.604 6.892)scale(7.03738 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="brg8dbpny"/><stop offset="1" class="d_t8kfbgb"/></radialGradient><radialGradient id="iuS4csd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 16.885 10.042)" gradientUnits="userSpaceOnUse"><stop class="e2earo80w"/><stop offset="1" class="xl9xm7bnj"/></radialGradient><radialGradient id="i2xEaMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 12.507 9.813)" gradientUnits="userSpaceOnUse"><stop class="suybu51ug"/><stop offset="1" class="intda8ekf"/></radialGradient><radialGradient id="iVUU1rX" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28627 0 0 -6.44557 19.687 11.53)" gradientUnits="userSpaceOnUse"><stop class="sqxrh1b6n"/><stop offset="1" class="eodwsybla"/></radialGradient><radialGradient id="im6NePb" cx="0" cy="0" r="1" gradientTransform="matrix(1.3135 4 -6.9728 2.28971 12.4 4.462)" gradientUnits="userSpaceOnUse"><stop class="f_q-3cc4h"/><stop offset="1" class="s44y8_wdc"/></radialGradient><radialGradient id="iHiG8jd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.8125 11.1071 0 14.587 16.288)" gradientUnits="userSpaceOnUse"><stop offset=".738" class="loyjok-ls"/><stop offset=".979" class="y1g164b_h"/></radialGradient><radialGradient id="ixiScye" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 15.367 12.096)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="i4SU0cd" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 15.128 12.307)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="iZ5YIPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 16.765 10.197)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="inBJCge" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 16.537 10.28)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="icanrEd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 12.401 10.197)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iB4rrTb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.185 -.755)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ipeIwwd" cx="0" cy="0" r="1" gradientTransform="rotate(116.696 8.04 7.093)scale(6.12125 6.5789)" gradientUnits="userSpaceOnUse"><stop class="zraasrypm"/><stop offset="1" class="wt7c97xxx"/></radialGradient><radialGradient id="izHz1gd" cx="0" cy="0" r="1" gradientTransform="matrix(.73215 -3.875 1.71541 .32411 8.289 7.066)" gradientUnits="userSpaceOnUse"><stop class="nl8hdv5-q"/><stop offset="1" class="kmg6h4b5x"/></radialGradient><radialGradient id="iEsU6Jd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.125 1.28124 -3.60476 -3.16519 19.646 3.097)" gradientUnits="userSpaceOnUse"><stop class="iyfczmh7s"/><stop offset="1" class="m2b3l_8kx"/></radialGradient><radialGradient id="ia6hdgb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.73438 4.0625 0 10.833 7.191)" gradientUnits="userSpaceOnUse"><stop class="n4fn3obqp"/><stop offset="1" class="h9dvmcbxu"/></radialGradient><radialGradient id="inGX0Oc" cx="0" cy="0" r="1" gradientTransform="matrix(-14.5563 0 0 -2.0625 21.577 27.816)" gradientUnits="userSpaceOnUse"><stop class="cv6gnzbto"/><stop offset="1" class="wl84mmb3d"/></radialGradient><radialGradient id="iKjUOTb" cx="0" cy="0" r="1" gradientTransform="rotate(104.338 -1.767 20.747)scale(7.1928 1.69685)" gradientUnits="userSpaceOnUse"><stop class="sl-gsib3f"/><stop offset="1" class="mr-s-pbar"/></radialGradient><radialGradient id="izpcbVd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.33866 0 0 -.95307 18.703 7.174)" gradientUnits="userSpaceOnUse"><stop offset=".169" class="xr_40cc2f"/><stop offset="1" class="kjxybmb-y"/></radialGradient><radialGradient id="idR7qVz" cx="0" cy="0" r="1" gradientTransform="matrix(1.03125 1.48437 -13.62738 9.46743 6.63 8.145)" gradientUnits="userSpaceOnUse"><stop class="ehnthvqoy"/><stop offset="1" class="rzbfz4btw"/></radialGradient><radialGradient id="ibPujte" cx="0" cy="0" r="1" gradientTransform="matrix(-.96093 -.6172 .84322 -1.31284 7.677 9.129)" gradientUnits="userSpaceOnUse"><stop offset=".501" class="rz-l4sb2t"/><stop offset="1" class="nqxo4gbph"/></radialGradient><radialGradient id="i6qz0xW" cx="0" cy="0" r="1" gradientTransform="matrix(.75 -.5625 1.05375 1.405 22.02 9.035)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="euqyawb2g"/><stop offset="1" class="vkwv3acem"/></radialGradient><radialGradient id="ij0qnyb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.27624 -.62648 0 14.961 21.756)" gradientUnits="userSpaceOnUse"><stop class="krttc8bap"/><stop offset="1" class="kpneurz6b"/></radialGradient><radialGradient id="iTdENFb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.41436 1.45816 0 14.582 25.828)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="ko6eamtic"/><stop offset="1" class="tc4y5tbfa"/></radialGradient><radialGradient id="iKGw4kt" cx="0" cy="0" r="1" gradientTransform="rotate(167.143 8.463 3.484)scale(2.97716 4.69784)" gradientUnits="userSpaceOnUse"><stop class="ism0j8_fd"/><stop offset="1" class="cc4vnjblc"/></radialGradient><radialGradient id="iyoBo3i" cx="0" cy="0" r="1" gradientTransform="matrix(2.81253 -2.28745 2.84526 3.49839 11.927 7.285)" gradientUnits="userSpaceOnUse"><stop class="kx5tbm42q"/><stop offset="1" class="ndetd3gmc"/></radialGradient><radialGradient id="iO3rDAc" cx="0" cy="0" r="1" gradientTransform="rotate(100.623 .526 19.635)scale(1.16051 4.42408)" gradientUnits="userSpaceOnUse"><stop class="pfbpewb0p"/><stop offset="1" class="dutea5bgy"/></radialGradient><radialGradient id="iiVeO6c" cx="0" cy="0" r="1" gradientTransform="matrix(-.83594 .34375 -.14238 -.34624 23.107 16.394)" gradientUnits="userSpaceOnUse"><stop class="xdf0lfbrm"/><stop offset="1" class="cvnvm48dp"/></radialGradient><radialGradient id="i7W12qd" cx="0" cy="0" r="1" gradientTransform="matrix(.83594 .17968 -.05863 .27278 21.786 16.331)" gradientUnits="userSpaceOnUse"><stop class="leotspfhb"/><stop offset="1" class="u3sz7tboa"/></radialGradient><radialGradient id="ifSfzbe" cx="0" cy="0" r="1" gradientTransform="matrix(1.3287 1.76599 -.65664 .49404 19.852 16.946)" gradientUnits="userSpaceOnUse"><stop class="qu53-3efb"/><stop offset="1" class="d8vnolbdv"/></radialGradient><radialGradient id="ih6dC9c" cx="0" cy="0" r="1" gradientTransform="matrix(1.46875 .4375 -1.25756 4.22181 18.833 19.379)" gradientUnits="userSpaceOnUse"><stop class="fcewfubec"/><stop offset="1" class="ku_tac4_z"/></radialGradient><radialGradient id="ibijqYb" cx="0" cy="0" r="1" gradientTransform="rotate(135.9 10.028 15.777)scale(4.22106 5.23602)" gradientUnits="userSpaceOnUse"><stop class="ybzdb35ne"/><stop offset="1" class="k-xo7erne"/></radialGradient><radialGradient id="iyoK4Kd" cx="0" cy="0" r="1" gradientTransform="matrix(-4 -.68747 1.04434 -6.0764 28.646 22.504)" gradientUnits="userSpaceOnUse"><stop offset=".711" class="d7eq7sb9j"/><stop offset="1" class="pci0oxh-l"/></radialGradient><radialGradient id="iJhoPse" cx="0" cy="0" r="1" gradientTransform="rotate(156.903 12.063 12.55)scale(1.15509 2.08846)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="a6yl-cb9v"/><stop offset="1" class="w_w8qcl3c"/></radialGradient><radialGradient id="irUvMbp" cx="0" cy="0" r="1" gradientTransform="matrix(1.27004 2.2186 -1.58976 .91006 11.157 16.067)" gradientUnits="userSpaceOnUse"><stop class="hq-8cac3q"/><stop offset="1" class="kiftlkrmt"/></radialGradient><radialGradient id="iuLQ4mb" cx="0" cy="0" r="1" gradientTransform="matrix(2.31645 1.18733 -.41625 .81209 12.19 16.066)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><radialGradient id="icL13gd" cx="0" cy="0" r="1" gradientTransform="rotate(136.408 5.786 11.704)scale(4.35086 4.82952)" gradientUnits="userSpaceOnUse"><stop class="dxbo1t_fa"/><stop offset="1" class="kvhp_ip6r"/></radialGradient><radialGradient id="i0XH97d" cx="0" cy="0" r="1" gradientTransform="matrix(4.45572 0 0 1.56463 13.974 15.652)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><filter id="ilRo1id" width="17.197" height="11.9" x="5.988" y="7.573" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.137255 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2617"/></filter><filter id="iexSDnb" width="15.118" height="14.561" x="6.988" y="2.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.254902 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2617"/></filter><filter id="iK8jGpe" width="3.368" height="3.468" x="8.289" y="9.389" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2617"/></filter><filter id="iYBftcb" width="3.218" height="3.468" x="17.802" y="9.139" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2617"/></filter><filter id="iciNQac" width="3.148" height="3.148" x="17.837" y="9.424" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2617" stdDeviation=".25"/></filter><filter id="iH3EzNA" width="2.948" height="2.948" x="8.443" y="9.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2617" stdDeviation=".2"/></filter><filter id="i9pyfZc" width="3.218" height="3.468" x="17.802" y="9.139" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2617"/></filter><filter id="iRkJuHc" width="2.648" height="2.648" x="18.087" y="9.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2617" stdDeviation=".125"/></filter><filter id="iz8G0jW" width="2.648" height="2.648" x="8.593" y="9.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2617" stdDeviation=".125"/></filter><filter id="iHhiJnc" width="10.199" height="11.277" x="9.488" y="6.091" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2617"/></filter><filter id="i3PcKgd" width="2.877" height="3.682" x="12.982" y="9.833" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2617" stdDeviation=".25"/></filter><filter id="iHRvqAd" width="2.377" height="3.182" x="13.395" y="9.944" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2617" stdDeviation=".125"/></filter><filter id="i3M8rEc" width="3.001" height="1.285" x="15.525" y="9.389" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2617"/></filter><filter id="iXKiWDb" width="3.001" height="1.285" x="10.64" y="9.389" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2617"/></filter><filter id="i4NZosw" width="2.453" height="1.091" x="10.775" y="7.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2617"/></filter><filter id="ilQn8Eb" width="2.453" height="1.091" x="16.192" y="7.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2617"/></filter><filter id="iAqaFtc" width=".787" height=".696" x="16.031" y="9.757" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2617" stdDeviation=".05"/></filter><filter id="inpbJ6c" width=".891" height=".913" x="16.871" y="9.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2617" stdDeviation=".1"/></filter><filter id="iXqbtde" width=".986" height="1.04" x="12.428" y="9.768" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2617" stdDeviation=".1"/></filter><filter id="i16Zuac" width=".913" height=".704" x="11.674" y="9.749" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2617" stdDeviation=".05"/></filter><filter id="iDJn8Fb" width="5.52" height="4.05" x="11.827" y="3.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.415686 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2617"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.2 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2617" result="effect2_innerShadow_4002_2617"/></filter><filter id="i5v4vkc" width="6.94" height="14.221" x="16.577" y="15.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.270588 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2617"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.266667 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2617" result="effect2_innerShadow_4002_2617"/></filter><filter id="i4E1EZd" width="11.012" height="8.855" x="17.86" y="16.47" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.0980392 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2617"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.270588 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2617" result="effect2_innerShadow_4002_2617"/></filter><filter id="iSAtSac" width="4.557" height="7.476" x="23.816" y="17.698" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.760784 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2617"/></filter><filter id="i1YaM1H" width="2.509" height="3.213" x="13.154" y="3.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.141176 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_2617"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_2617" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.768627 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_2617"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.337255 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_2617" result="effect3_innerShadow_4002_2617"/></filter><filter id="iTuIhbc" width="1.83" height="4.718" x="18.091" y="17.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2617" stdDeviation=".125"/></filter><filter id="iZOi0fe" width="2.769" height="7.081" x="18.396" y="23.073" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2617" stdDeviation=".2"/></filter><filter id="iVudaFc" width="6.88" height="4.067" x="11.157" y="15.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.0470588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2617"/></filter><filter id="iJTcE5c" width="4.97" height="4.254" x="13.277" y="15.388" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.12549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2617"/></filter><linearGradient id="i4a0pNb" x1="14.587" x2="14.587" y1="7.973" y2="19.473" gradientUnits="userSpaceOnUse"><stop class="usw0jac_r"/><stop offset="1" class="zhmn0cciw"/></linearGradient><linearGradient id="i1ptMxc" x1="14.587" x2="14.587" y1="7.249" y2="10.843" gradientUnits="userSpaceOnUse"><stop offset=".184" class="l1qje4b6x"/><stop offset="1" class="vx6m-x__v"/></linearGradient><linearGradient id="iP57O3b" x1="14.597" x2="14.597" y1="8.004" y2="17.124" gradientUnits="userSpaceOnUse"><stop class="o2xqgmbjp"/><stop offset="1" class="v2ky7trsz"/></linearGradient><linearGradient id="ih3vBxb" x1="7.607" x2="6.489" y1="26.66" y2="26.629" gradientUnits="userSpaceOnUse"><stop class="gyzg0db3w"/><stop offset="1" class="y28tkbl-n"/></linearGradient><linearGradient id="irfAPUC" x1="7.407" x2="21.783" y1="15.863" y2="15.863" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iI325ic" x1="7.407" x2="21.783" y1="15.832" y2="15.832" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="ij2w2Ad" x1="8.289" x2="11.248" y1="11.085" y2="11.085" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="iRx3Sgd" x1="9.898" x2="8.96" y1="9.389" y2="12.164" gradientUnits="userSpaceOnUse"><stop class="m5stmvb4q"/><stop offset="1" class="lqietk8gw"/></linearGradient><linearGradient id="iqT8trb" x1="13.645" x2="14.583" y1="12.169" y2="12.169" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="iiVGcpe" x1="14.583" x2="14.583" y1="12.968" y2="12.357" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="iSkPpGb" x1="13.519" x2="13.98" y1="14.538" y2="13.825" gradientUnits="userSpaceOnUse"><stop class="wl-j51biu"/><stop offset=".663" class="i-vkeo5mo"/></linearGradient><linearGradient id="iRMdPib" x1="17.543" x2="17.23" y1="10.25" y2="10.444" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iuC9Kfb" x1="13.145" x2="12.831" y1="10.25" y2="10.444" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ih5nvHe" x1="10.646" x2="16.989" y1="6.722" y2="6.722" gradientUnits="userSpaceOnUse"><stop class="ks1omcbjp"/><stop offset="1" class="jk0lbnbnn"/></linearGradient><linearGradient id="i9mB5Mc" x1="14.592" x2="14.592" y1="30.316" y2="28.722" gradientUnits="userSpaceOnUse"><stop class="s2qawgbpe"/><stop offset="1" class="iu5oamiyf"/></linearGradient><linearGradient id="iUnDHVd" x1="14.592" x2="14.592" y1="26.172" y2="27.441" gradientUnits="userSpaceOnUse"><stop class="tcape2laf"/><stop offset="1" class="gd-vr7bgk"/></linearGradient><linearGradient id="ivHTDTb" x1="14.582" x2="14.582" y1="6.973" y2="11.754" gradientUnits="userSpaceOnUse"><stop offset=".526" class="ffurleovf"/><stop offset=".654" class="oirct-bua"/></linearGradient><linearGradient id="ij2mDJd" x1="14.582" x2="14.582" y1="19.605" y2="26.176" gradientUnits="userSpaceOnUse"><stop class="jbzirjbuq"/><stop offset="1" class="s7s75dkrn"/></linearGradient><linearGradient id="ibeddjd" x1="22.021" x2="18.333" y1="16.754" y2="29.972" gradientUnits="userSpaceOnUse"><stop class="ommdktbpj"/><stop offset="1" class="dinvdlb3p"/></linearGradient><linearGradient id="i5b1ojc" x1="20.021" x2="28.208" y1="22.191" y2="18.879" gradientUnits="userSpaceOnUse"><stop class="lf_6el-zz"/><stop offset="1" class="p6qk4rbue"/></linearGradient><linearGradient id="i9kTuLc" x1="14.458" x2="14.458" y1="4.221" y2="6.666" gradientUnits="userSpaceOnUse"><stop class="rx-q5b7rc"/><stop offset="1" class="fz8-ywb6c"/></linearGradient><linearGradient id="iJ67e8c" x1="18.689" x2="20.192" y1="21.647" y2="16.457" gradientUnits="userSpaceOnUse"><stop class="ih4zzfygk"/><stop offset="1" class="bq_18tbdo"/></linearGradient><linearGradient id="iHtsopb" x1="13.277" x2="13.484" y1="17.919" y2="17.919" gradientUnits="userSpaceOnUse"><stop class="lwl8ufbrj"/><stop offset="1" class="i5hn1bqvd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-firefighter-light" /></template>
<style>
.a6yl-cb9v {
  stop-color: var(--svg-color--eeecf0, #EEECF0);
}

.acylf0bup {
  d: path("M8.659 7.973h11.847c.948 0 1.988.484 1.988 2.68h.692V9.348c0-1.43-.848-2.375-2.457-2.375H8.435c-1.609 0-2.456.945-2.456 2.375v1.305h.69c0-2.196 1.04-2.68 1.99-2.68");
}

.ajcn8-ycn {
  d: path("M7.607 29.973V17.97a10.98 10.98 0 0 0-4.02 8.502v3.5z");
}

.al5ersbzq {
  stop-color: var(--svg-color--c1836d, #C1836D);
  stop-opacity: 0;
}

.alecchcgl {
  d: path("m22.636 16.137l-1.38-.369a.51.51 0 0 0-.625.358l-3.804 13.846h2.547l3.63-13.211a.53.53 0 0 0-.368-.624");
}

.aps1jhbfc {
  stop-color: var(--svg-color--b47860, #B47860);
}

.aso-vybjw {
  stop-color: var(--svg-color--d59566, #D59566);
}

.bcdc9wb8u {
  stop-color: var(--svg-color--d54161, #D54161);
  stop-opacity: 0;
}

.bkd5s605t {
  fill-rule: evenodd;
  d: path("M21.782 12.5c.213-.434.324-.92.324-1.426c0-.467-.096-.906-.269-1.306h.006a3 3 0 0 0-.282-.513l-.002-.003a3.24 3.24 0 0 1-.526-1.77l-.167-.01c0-1.822-1.31-3.3-3.132-3.3a.54.54 0 0 1-.455-.233a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.455.233l-.085.001C9.592 4.218 8.49 5.688 8.49 7.481h-.33a3.24 3.24 0 0 1-.527 1.771l-.002.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455c-.93 1.953.83 4.168 2.894 4.168h8.582c1.78 0 3.218-1.453 3.218-2.906c0-.506-.122-.837-.324-1.262a.52.52 0 0 1 0-.455M9.934 9.87H9.92l.787 2.314c.124 2.803 1.217 0 3.889 0s3.836 3.12 3.96.317l.997-3.202c-.054-1.245-.817-1.327-.997-1.327h-3.22a3.86 3.86 0 0 1-3.19-1.674a.264.264 0 0 0-.461.051l-.082.194a2.3 2.3 0 0 1-1.241 1.255l-.051.02c-.236.123-.378.532-.399 1.481l.01.306z");
}

.bq_18tbdo {
  stop-color: var(--svg-color--cd517b, #CD517B);
  stop-opacity: 0;
}

.brg8dbpny {
  stop-color: var(--svg-color--e2a895, #E2A895);
  stop-opacity: 0;
}

.bulogvb1g {
  fill: var(--svg-color--d53260, #D53260);
  d: path("M11.157 15.678v1.975c0 1.09.89 1.98 1.98 1.98h2.92c1.09 0 1.98-.88 1.98-1.98v-1.987c-.896.82-2.111 1.29-3.447 1.29c-1.329 0-2.538-.465-3.433-1.278");
}

.c6c-ztbag {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M9.917 12.072a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.cc4vnjblc {
  stop-color: var(--svg-color--524361, #524361);
}

.cj_ualb6i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m19.546 17.972l-1.08 3.968");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cmn7xo6lx {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.974 9.448c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.cv6gnzbto {
  stop-color: var(--svg-color--fec852, #FEC852);
}

.cvnvm48dp {
  stop-color: var(--svg-color--a17d74, #A17D74);
  stop-opacity: 0;
}

.cx0xfhbrr {
  d: path("M12.4 9.72a.892.892 0 0 0-.86 1.127h1.723a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.892");
}

.d_t8kfbgb {
  stop-color: var(--svg-color--e2a895, #E2A895);
}

.d-ykpkboz {
  stop-color: var(--svg-color--c6284c, #C6284C);
}

.d7eq7sb9j {
  stop-color: var(--svg-color--bab3b6, #BAB3B6);
  stop-opacity: 0;
}

.d8vnolbdv {
  stop-color: var(--svg-color--ed2e7c, #ED2E7C);
  stop-opacity: 0;
}

.dbj0sjb-p {
  d: path("M14.947 15.833c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.deg-o6bbc {
  stop-color: var(--svg-color--f94d70, #F94D70);
}

.dinvdlb3p {
  stop-color: var(--svg-color--785253, #785253);
}

.dmxjdc_5c {
  stop-color: var(--svg-color--d0465e, #D0465E);
}

.dutea5bgy {
  stop-color: var(--svg-color--734145, #734145);
  stop-opacity: 0;
}

.dvybz7bcd {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m11.186 8.765l-.005.003a.268.268 0 0 1-.275-.46l.001-.001l.003-.002l.01-.005a2 2 0 0 1 .148-.077a3 3 0 0 1 .41-.162c.34-.108.815-.2 1.328-.109a.268.268 0 1 1-.093.528a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.455.193");
}

.dxbo1t_fa {
  stop-color: var(--svg-color--ff547f, #FF547F);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2earo80w {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
}

.e2tiqybzr {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m18.315 8.308l-.138.23za.268.268 0 0 1-.276.46l-.004-.003l-.022-.012l-.091-.046a3 3 0 0 0-.343-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 1 1-.093-.528c.513-.09.988 0 1.328.11a3.3 3.3 0 0 1 .559.238l.01.005l.002.002z");
}

.e3e67-bvh {
  fill: var(--svg-color--ecb845, #ECB845);
  d: path("M21.577 26.172H7.607v3.8h13.97z");
}

.e3fuicbbj {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M19.41 12.072a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.ehnthvqoy {
  stop-color: var(--svg-color--b3576b, #B3576B);
}

.eodwsybla {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
  stop-opacity: 0;
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.eqb1ki6td {
  stop-color: var(--svg-color--d0465e, #D0465E);
  stop-opacity: 0;
}

.euqyawb2g {
  stop-color: var(--svg-color--be1e3b, #BE1E3B);
}

.f_q-3cc4h {
  stop-color: var(--svg-color--a47463, #A47463);
}

.f64lk-nyh {
  stroke: var(--svg-color--87625e, #87625E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.921 29.629c0-.2 1.146-4.104 1.719-6.031");
}

.f8x3opbgo {
  stop-color: var(--svg-color--c6284c, #C6284C);
  stop-opacity: 0;
}

.fcewfubec {
  stop-color: var(--svg-color--c93271, #C93271);
}

.ffurleovf {
  stop-color: var(--svg-color--bb2b57, #BB2B57);
}

.ft5dv1b6b {
  fill: none;
}

.fvm07vbkd {
  stop-color: var(--svg-color--b87c92, #B87C92);
}

.fz8-ywb6c {
  stop-color: var(--svg-color--f48942, #F48942);
}

.gd-vr7bgk {
  stop-color: var(--svg-color--edb63d, #EDB63D);
  stop-opacity: 0;
}

.gky-wnwiz {
  d: path("M16.767 9.72a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.gxfmc-q1q {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.185 13.52a.204.204 0 0 0-.247.044a.196.196 0 0 0-.021.247a1.982 1.982 0 0 0 3.333 0a.2.2 0 0 0-.021-.25a.205.205 0 0 0-.247-.04a3 3 0 0 1-1.399.338a3 3 0 0 1-1.398-.339Z");
}

.gyzg0db3w {
  stop-color: var(--svg-color--bf415a, #BF415A);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h3fma_n5f {
  stop-color: var(--svg-color--3f3c3d, #3F3C3D);
  stop-opacity: 0;
}

.h9dvmcbxu {
  stop-color: var(--svg-color--c52632, #C52632);
  stop-opacity: 0;
}

.hq-8cac3q {
  stop-color: var(--svg-color--c75567, #C75567);
}

.i-vkeo5mo {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
  stop-opacity: 0;
}

.i1kk6cv0u {
  fill: var(--svg-color--000, #000);
  d: path("M12.91 10.612a.51.51 0 0 0-.51-.51a.51.51 0 0 0-.455.745h.905a.5.5 0 0 0 .06-.235");
}

.i5hn1bqvd {
  stop-color: var(--svg-color--ca435d, #CA435D);
  stop-opacity: 0;
}

.i8--_db9h {
  stop-color: var(--svg-color--483c3d, #483C3D);
  stop-opacity: 0;
}

.idk0shbpn {
  stop-color: var(--svg-color--c03959, #C03959);
  stop-opacity: 0;
}

.ih4zzfygk {
  stop-color: var(--svg-color--cd517b, #CD517B);
}

.intda8ekf {
  stop-color: var(--svg-color--d09790, #D09790);
  stop-opacity: 0;
}

.ism0j8_fd {
  stop-color: var(--svg-color--675b70, #675B70);
}

.iu5oamiyf {
  stop-color: var(--svg-color--d9a73c, #D9A73C);
  stop-opacity: 0;
}

.iyfczmh7s {
  stop-color: var(--svg-color--fd5c7c, #FD5C7C);
}

.j-6z4ebeh {
  stop-color: var(--svg-color--e4a49f, #E4A49F);
  stop-opacity: 0;
}

.j-oh5nkfx {
  d: path("M9.496 9.735h.012l-.01-.265l-.01-.306c.02-.95.574-1.317.81-1.439l.051-.02l.051-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .462-.051c.717 1.05 1.917 1.318 3.189 1.318h3.22c.18 0 1.245 0 1.136 1.687l-.119 3.073c-.123 2.803-2.312 4.685-4.983 4.685c-2.672 0-4.86-1.882-4.984-4.685z");
}

.j5-d0iboi {
  stop-color: var(--svg-color--c71931, #C71931);
  stop-opacity: 0;
}

.ja-6i29rv {
  d: path("M14.617 15.833h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.jbzirjbuq {
  stop-color: var(--svg-color--ba2f50, #BA2F50);
}

.jk0lbnbnn {
  stop-color: var(--svg-color--be324c, #BE324C);
  stop-opacity: 0;
}

.juwb30xpp {
  cx: 12.13px;
  cy: 10.101px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.jyz4ivbym {
  d: path("m20.012 16.732l4.416 1.16a3.57 3.57 0 0 0 2.071-.053l.148-.054c.178-.063.401-.054.554.107c1.072 1.125 1.43 2.621.984 4.236c-.447 1.614-1.733 2.764-2.98 3.033c-.084.02-.348.046-.506-.157l-.141-.14a3.5 3.5 0 0 0-1.745-1.111L18.57 22.55a.61.61 0 0 1-.43-.779l1.25-4.674c.045-.22.37-.43.622-.365");
}

.k-xo7erne {
  stop-color: var(--svg-color--cdc6d4, #CDC6D4);
}

.kiftlkrmt {
  stop-color: var(--svg-color--c75567, #C75567);
  stop-opacity: 0;
}

.kjxybmb-y {
  stop-color: var(--svg-color--fc5083, #FC5083);
  stop-opacity: 0;
}

.kmg6h4b5x {
  stop-color: var(--svg-color--bd585d, #BD585D);
  stop-opacity: 0;
}

.kngw6fbep {
  d: path("M14.587 15.473c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.ko6eamtic {
  stop-color: var(--svg-color--ab0d36, #AB0D36);
  stop-opacity: 0;
}

.kpneurz6b {
  stop-color: var(--svg-color--c1415c, #C1415C);
  stop-opacity: 0;
}

.kr3_qi-9c {
  d: path("m14.201 10.476l-.532 1.7a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.646-.376-.765 0");
}

.krttc8bap {
  stop-color: var(--svg-color--c1415c, #C1415C);
}

.krvd34mtu {
  stop-color: var(--svg-color--d59566, #D59566);
  stop-opacity: 0;
}

.ks1omcbjp {
  stop-color: var(--svg-color--be324c, #BE324C);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.ku_tac4_z {
  stop-color: var(--svg-color--c93271, #C93271);
  stop-opacity: 0;
}

.kvhp_ip6r {
  stop-color: var(--svg-color--df3d67, #DF3D67);
}

.kx5tbm42q {
  stop-color: var(--svg-color--3d2b40, #3D2B40);
}

.kyuvy4bbj {
  stop-color: var(--svg-color--3a312e, #3A312E);
  stop-opacity: 0;
}

.l-xt2yl6d {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.192 9.448c-.653 0-1.204.45-1.355 1.059c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.37-1.128");
}

.l1qje4b6x {
  stop-color: var(--svg-color--710425, #710425);
}

.l38p1-72g {
  stop-color: var(--svg-color--dfa791, #DFA791);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l9d2msbgp {
  fill: var(--svg-color--272528, #272528);
  d: path("M13.442 10.225c-.266-.467-.67-.836-1.538-.836c-.38 0-.747.106-1.073.369c-.268.217-.232.495-.024.6l.556.317c.652-.211 1.372-.24 2.079-.45");
}

.la-qn6bfl {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m14.19 10.615l-.683 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.494-.377-.613 0");
}

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.leotspfhb {
  stop-color: var(--svg-color--8c5e57, #8C5E57);
}

.lf_6el-zz {
  stop-color: var(--svg-color--ee2f8c, #EE2F8C);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.linpwzqhe {
  d: path("M22.174 7.973H7.152c-.395.32-.78 1.336-1.164 1.656v1.344c0 4.69 3.855 8.5 8.599 8.5s8.598-3.81 8.598-8.5V9.629c-.354-.42-.687-1.206-1.011-1.656");
}

.loyjok-ls {
  stop-color: var(--svg-color--c3827d, #C3827D);
  stop-opacity: 0;
}

.lqietk8gw {
  stop-color: var(--svg-color--c8897e, #C8897E);
}

.ls7-cblkb {
  stop-color: var(--svg-color--dd365e, #DD365E);
}

.ls935lkhb {
  stop-color: var(--svg-color--c1836d, #C1836D);
}

.lwl8ufbrj {
  stop-color: var(--svg-color--ca435d, #CA435D);
}

.m2b3l_8kx {
  stop-color: var(--svg-color--fd5c7c, #FD5C7C);
  stop-opacity: 0;
}

.m5stmvb4q {
  stop-color: var(--svg-color--ac7063, #AC7063);
}

.mb3jp1v8b {
  d: path("M9.917 12.072a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mevfg8o-k {
  stop-color: var(--svg-color--cc7f81, #CC7F81);
}

.mr-s-pbar {
  stop-color: var(--svg-color--bc832d, #BC832D);
  stop-opacity: 0;
}

.mr8fywmtc {
  stop-color: var(--svg-color--b91a3e, #B91A3E);
}

.n1w64orcn {
  stop-color: var(--svg-color--b87c92, #B87C92);
  stop-opacity: 0;
}

.n4fn3obqp {
  stop-color: var(--svg-color--c52632, #C52632);
}

.n4wu3h9rb {
  d: path("M9.898 12.607a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.nal4e_0hy {
  stop-color: var(--svg-color--d39a8c, #D39A8C);
}

.ndetd3gmc {
  stop-color: var(--svg-color--3d2b40, #3D2B40);
  stop-opacity: 0;
}

.nfcjmccxh {
  stop-color: var(--svg-color--3f3c3d, #3F3C3D);
}

.nfddei0pp {
  stop-color: var(--svg-color--c51b40, #C51B40);
  stop-opacity: 0;
}

.niybxc2uq {
  stop-color: var(--svg-color--3a312e, #3A312E);
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.nl8hdv5-q {
  stop-color: var(--svg-color--bd585d, #BD585D);
}

.npvir-bzx {
  d: path("M13.304 4.91c0-.153.183-.231.293-.125l.155.148a.162.162 0 0 0 .274-.117v-.17c0-.344.178-.665.472-.846l.18-.112a.23.23 0 0 1 .35.195v1.194a.17.17 0 0 0 .278.133l.096-.079a.13.13 0 0 1 .21.1v.334a1.154 1.154 0 0 1-2.308-.053z");
}

.nqxo4gbph {
  stop-color: var(--svg-color--a21e3e, #A21E3E);
  stop-opacity: 0;
}

.nuif9xlfl {
  stop-color: var(--svg-color--ff385e, #FF385E);
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.o1z42mbzo {
  d: path("M19.41 12.607a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.o2xqgmbjp {
  stop-color: var(--svg-color--1e0106, #1E0106);
}

.o41nkwbqu {
  stop-color: var(--svg-color--ff385e, #FF385E);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ogeiazbnd {
  d: path("M19.41 12.072a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.ogiwwtbff {
  fill: var(--svg-color--e3a793, #E3A793);
  d: path("M19.41 12.072a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.oirct-bua {
  stop-color: var(--svg-color--bb2b57, #BB2B57);
  stop-opacity: 0;
}

.ommdktbpj {
  stop-color: var(--svg-color--8f5b56, #8F5B56);
}

.onmhnc-bl {
  d: path("M15.167 19.606h-1.17v6.57h1.17z");
}

.osd7ifb8c {
  stop-color: var(--svg-color--d23b59, #D23B59);
  stop-opacity: 0;
}

.oyh5fnr6n {
  d: path("M21.577 26.172H7.607v3.8h13.97z");
}

.oyr8gxaci {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M15.725 10.225c.266-.467.67-.836 1.538-.836c.38 0 .747.106 1.073.369c.268.217.232.495.024.6l-.556.317c-.652-.211-1.372-.24-2.079-.45");
}

.p6qk4rbue {
  stop-color: var(--svg-color--fc3d5f, #FC3D5F);
}

.pci0oxh-l {
  stop-color: var(--svg-color--a39ba9, #A39BA9);
}

.pfbpewb0p {
  stop-color: var(--svg-color--734145, #734145);
}

.ph5kwxbvm {
  d: path("M11.157 15.678v1.975c0 1.09.89 1.98 1.98 1.98h2.92c1.09 0 1.98-.88 1.98-1.98v-1.987c-.896.82-2.111 1.29-3.447 1.29c-1.329 0-2.538-.465-3.433-1.278");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pl04ozb6c {
  d: path("M17.562 10.494a.84.84 0 0 0-.231-.462l-.26.285l.117.228z");
}

.pmefcq5-m {
  d: path("M13.215 10.507c0-.288-.235-.48-.298-.539l-.289.28l.178.36z");
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.q_n5wkbyq {
  stop-color: var(--svg-color--d93b60, #D93B60);
}

.q-uw1wb3b {
  stop-color: var(--svg-color--c7425f, #C7425F);
}

.qes9fmppr {
  stop-color: var(--svg-color--d69f94, #D69F94);
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
}

.qu53-3efb {
  stop-color: var(--svg-color--fc4b93, #FC4B93);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.recb7tbvt {
  d: path("M17.247 6.972h-5.32v-1.29c0-1.47 1.19-2.66 2.66-2.66s2.66 1.19 2.66 2.66z");
}

.rx-q5b7rc {
  stop-color: var(--svg-color--f1b244, #F1B244);
}

.rz-l4sb2t {
  stop-color: var(--svg-color--a21e3e, #A21E3E);
}

.rzbfz4btw {
  stop-color: var(--svg-color--b3576b, #B3576B);
  stop-opacity: 0;
}

.s2qawgbpe {
  stop-color: var(--svg-color--b78426, #B78426);
}

.s44y8_wdc {
  stop-color: var(--svg-color--a47463, #A47463);
  stop-opacity: 0;
}

.s7s75dkrn {
  stop-color: var(--svg-color--b93054, #B93054);
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
}

.sl-gsib3f {
  stop-color: var(--svg-color--bc832d, #BC832D);
}

.sqxrh1b6n {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
}

.suybu51ug {
  stop-color: var(--svg-color--d09790, #D09790);
}

.t56q3abaj {
  fill: var(--svg-color--000, #000);
  d: path("M16.256 10.612c0-.284.227-.51.511-.51a.51.51 0 0 1 .455.745h-.905a.46.46 0 0 1-.06-.235");
}

.tbz0q_48a {
  stop-color: var(--svg-color--dd365e, #DD365E);
  stop-opacity: 0;
}

.tc4y5tbfa {
  stop-color: var(--svg-color--ab0d36, #AB0D36);
}

.tcape2laf {
  stop-color: var(--svg-color--edb63d, #EDB63D);
}

.tddz0-g7t {
  stop-color: var(--svg-color--d29394, #D29394);
  stop-opacity: 0;
}

.tk20gvbnd {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
  stop-opacity: 0;
}

.tw2yr-3fp {
  stop-color: var(--svg-color--483c3d, #483C3D);
}

.tz8-2cckd {
  fill: var(--svg-color--e8ae9a, #E8AE9A);
  d: path("m14.201 10.476l-.532 1.7a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.646-.376-.765 0");
}

.u3sz7tboa {
  stop-color: var(--svg-color--8c5e57, #8C5E57);
  stop-opacity: 0;
}

.uc4j85bvv {
  stop-color: var(--svg-color--d39a8c, #D39A8C);
  stop-opacity: 0;
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.usw0jac_r {
  stop-color: var(--svg-color--a9112c, #A9112C);
}

.v-9tn59hb {
  stop-color: var(--svg-color--dba98b, #DBA98B);
  stop-opacity: 0;
}

.v2ky7trsz {
  stop-color: var(--svg-color--170810, #170810);
}

.v5pkyqbhx {
  d: path("M20.885 7.332H8.29v-.377c0-2.734 2.01-4.928 5.02-4.928h2.411c3.329 0 5.165 2.194 5.165 4.928z");
}

.vb_6e0-eb {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.702 9.908c.063.085-.07.19-.22.302c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.359s.325-.136.389-.05");
}

.vdvey0c5l {
  stop-color: var(--svg-color--d29394, #D29394);
}

.vg3v5gbvt {
  d: path("M13.277 16.798v1.835c0 .56.45 1.01 1.01 1.01h1.78c1.09 0 1.98-.89 1.98-1.98v-2.025c-.898.826-2.116 1.319-3.457 1.319a5.4 5.4 0 0 1-1.313-.159");
}

.vkwv3acem {
  stop-color: var(--svg-color--be1e3b, #BE1E3B);
  stop-opacity: 0;
}

.vlu36uddq {
  fill: var(--svg-color--bc7e70, #BC7E70);
  d: path("M9.917 12.072a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.voemc8h9d {
  stop-color: var(--svg-color--d23b59, #D23B59);
}

.vwc2t-btp {
  fill: var(--svg-color--dc375e, #DC375E);
  d: path("M14.587 15.473c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.vx6m-x__v {
  stop-color: var(--svg-color--a81330, #A81330);
  stop-opacity: 0;
}

.vylrb5bvm {
  d: path("M21.577 17.982v11.99h4v-3.5a10.98 10.98 0 0 0-4-8.49");
}

.w_w8qcl3c {
  stop-color: var(--svg-color--eeecf0, #EEECF0);
  stop-opacity: 0;
}

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.wl-j51biu {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
}

.wl84mmb3d {
  stop-color: var(--svg-color--fec852, #FEC852);
  stop-opacity: 0;
}

.wqbwr3bsq {
  cx: 12.13px;
  cy: 10.101px;
  rx: 0.39px;
  ry: 0.197px;
}

.wt7c97xxx {
  stop-color: var(--svg-color--f44f5a, #F44F5A);
}

.x01c9dvva {
  d: path("M16.702 9.908c.063.085-.07.19-.22.302c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.359s.325-.136.389-.05");
}

.x8m9vebtt {
  stop-color: var(--svg-color--df6277, #DF6277);
}

.xbgj88f0b {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
}

.xdf0lfbrm {
  stop-color: var(--svg-color--a17d74, #A17D74);
}

.xfqkuki0h {
  d: path("M25.649 18.01a3.5 3.5 0 0 0 .85-.171l.148-.055c.178-.062.401-.053.554.108c1.072 1.125 1.43 2.621.984 4.236c-.447 1.614-1.733 2.764-2.98 3.033c-.084.02-.348.046-.506-.157l-.141-.14a3.5 3.5 0 0 0-.642-.589c1.567-.052 2.817-1.084 3.203-2.53c.39-1.468-.236-3.002-1.472-3.734z");
}

.xl9xm7bnj {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
  stop-opacity: 0;
}

.xr_40cc2f {
  stop-color: var(--svg-color--fc5083, #FC5083);
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
  stop-opacity: 0;
}

.y1g164b_h {
  stop-color: var(--svg-color--c3827d, #C3827D);
}

.y28tkbl-n {
  stop-color: var(--svg-color--bf415a, #BF415A);
  stop-opacity: 0;
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.ybzdb35ne {
  stop-color: var(--svg-color--ded9e3, #DED9E3);
}

.ygstjnb_e {
  stop-color: var(--svg-color--99344a, #99344A);
}

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.z-rzt8b_f {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
}

.zco4q0bhr {
  stop-color: var(--svg-color--ffd0b9, #FFD0B9);
}

.ze-km1b7g {
  stop-color: var(--svg-color--c51b40, #C51B40);
}

.zhmn0cciw {
  stop-color: var(--svg-color--a11339, #A11339);
}

.zj8ulgbnv {
  stop-color: var(--svg-color--c71931, #C71931);
}

.zraasrypm {
  stop-color: var(--svg-color--f0406f, #F0406F);
}

</style>
