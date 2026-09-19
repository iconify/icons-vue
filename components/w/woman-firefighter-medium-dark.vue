<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iODB3ve)"><path fill="url(#iaUsmrb)" class="wow_zkb9s"/><path fill="url(#i1ptMxc)" class="wow_zkb9s"/></g><g filter="url(#iqbaXys)"><path fill="url(#iP57O3b)" clip-rule="evenodd" class="dtg7ku1fk"/><path fill="url(#iCzAxDb)" clip-rule="evenodd" class="dtg7ku1fk"/><path fill="url(#irxCdob)" clip-rule="evenodd" class="dtg7ku1fk"/><path fill="url(#i6ssShe)" clip-rule="evenodd" class="dtg7ku1fk"/></g><path class="b_qv5du4s"/><path fill="url(#i6KAjab)" class="faisxaclj"/><path fill="url(#i2gSgbe)" class="faisxaclj"/><path fill="url(#idcBZkt)" class="faisxaclj"/><path fill="url(#iiLw8Vb)" class="faisxaclj"/><path fill="url(#iAIO9Yd)" class="faisxaclj"/><path fill="url(#isZrtzc)" class="faisxaclj"/><path fill="url(#iJkm9gA)" class="d_-1b_bzw"/><path fill="url(#ih3vBxb)" class="d_-1b_bzw"/><path fill="url(#iov0n7a)" class="d_-1b_bzw"/><path fill="url(#inI3Unb)" class="vylrb5bvm"/><path fill="url(#i4dn0Mr)" class="vylrb5bvm"/><path fill="url(#i0i1YkC)" class="dbj0sjb-p"/><path fill="url(#iI325ic)" class="ja-6i29rv"/><path fill="url(#iw1JEud)" class="vq7q2tbpw"/><path fill="url(#i8VHrfb)" class="vq7q2tbpw"/><g filter="url(#iZPWkte)"><path fill="url(#iONQhJd)" class="snc90qx2m"/><path fill="url(#iymXAON)" class="snc90qx2m"/><path fill="url(#i17eMBc)" class="snc90qx2m"/></g><g filter="url(#iQmUBOQ)"><path class="o1y7r8lbo"/><path fill="url(#iOn5rWY)" class="xn49zlb4v"/></g><g filter="url(#iGTkFob)"><path class="p1b0865rd"/><path fill="url(#i5QVC5b)" class="z38homb3o"/></g><g filter="url(#iaNUZud)"><path fill="url(#ik58dCb)" class="qging0bua"/><path fill="url(#iniTaBb)" class="qging0bua"/><path fill="url(#iQEVXdd)" class="qging0bua"/><path fill="url(#iws3H3d)" class="qging0bua"/><path fill="url(#i0A2HKc)" class="qging0bua"/><path fill="url(#iMRU1ad)" class="qging0bua"/><path fill="url(#icKNeid)" class="qging0bua"/><path fill="url(#im9J3ve)" class="qging0bua"/></g><path fill="url(#inRcWmc)" class="qging0bua"/><path fill="url(#inmj7Jd)" class="qging0bua"/><path fill="url(#ic43Z2c)" class="qging0bua"/><g filter="url(#iXEvchc)"><path class="y8sfvyb_m"/></g><g filter="url(#izk1kJe)"><path class="ns8uxjbrq"/><path fill="url(#iWWBpJe)" class="nxde922ww"/><path fill="url(#iqZQ5te)" class="nxde922ww"/><path fill="url(#iNLbCOd)" class="nxde922ww"/><path fill="url(#i7scFJc)" class="nxde922ww"/></g><g filter="url(#ipbVFRb)"><path stroke="url(#i2nYnco)" class="r4ivgmbgz"/></g><path class="erxr74bkf"/><g filter="url(#ihqFakc)"><path class="ztsl-cc-b"/></g><g filter="url(#iyh1und)"><path class="mv2od5z8x"/></g><g filter="url(#i0Va2Td)"><path class="n4yp-siqi"/></g><g filter="url(#iyxWhIb)"><path clip-rule="evenodd" class="mzvb6ccyl"/></g><path class="cpg_yds5t"/><path fill="url(#iW7ouXG)" class="o-dqgx1iv"/><path class="zm5b7hm_o"/><g filter="url(#iyrUkmd)"><path class="o1qh5ebyv"/><path fill="url(#itPh8OF)" class="boaowqb5j"/></g><g filter="url(#ijGmKAe)"><path fill="url(#iZqrxQd)" class="obi765bgs"/></g><path class="dw66imbcr"/><path fill="url(#ixqefOB)" class="tfuwfjb_f"/><path class="ssn5xcb0b"/><g filter="url(#iIC1sEN)"><path fill="url(#ihNmjOb)" class="s_1fdg8-f"/></g><g filter="url(#iaopTtd)"><ellipse transform="rotate(-27.914 12.053 10.36)" class="cifdjacwb"/><ellipse fill="url(#iPRYuBk)" transform="rotate(-27.914 12.053 10.36)" class="j2la80nsc"/></g><path fill="url(#iHZvJfc)" class="hgn0v4h0b"/><path fill="url(#ilxTFMd)" class="hgn0v4h0b"/><path fill="url(#izHz1gd)" class="hgn0v4h0b"/><path fill="url(#iFF74De)" class="hgn0v4h0b"/><path fill="url(#ia6hdgb)" class="hgn0v4h0b"/><path class="d6l_zva3n"/><path fill="url(#inGX0Oc)" class="u_wc6ubhb"/><path fill="url(#iiH6veK)" class="u_wc6ubhb"/><path fill="url(#iI4mEsd)" class="u_wc6ubhb"/><path fill="url(#iN2yeVc)" class="u_wc6ubhb"/><path fill="url(#i1i1Lbq)" class="fw2o80b7i"/><path fill="url(#izpcbVd)" class="fw2o80b7i"/><path fill="url(#iZ6eZGb)" class="fw2o80b7i"/><path fill="url(#ibPujte)" class="fw2o80b7i"/><path fill="url(#i6qz0xW)" class="fw2o80b7i"/><path fill="url(#iMEPogb)" class="w_8w8wqmn"/><path fill="url(#iutMDkb)" class="w_8w8wqmn"/><path fill="url(#ih18itd)" class="w_8w8wqmn"/><g filter="url(#i36TyJv)"><path fill="url(#iKGw4kt)" class="recb7tbvt"/><path fill="url(#iyoBo3i)" class="recb7tbvt"/></g><g filter="url(#iNGyfsb)"><path fill="url(#iatOxCb)" class="n4s-q-b8n"/><path fill="url(#iQy6vPz)" class="n4s-q-b8n"/></g><path fill="url(#iqw3Vdd)" class="n4s-q-b8n"/><path fill="url(#iZmNjZb)" class="n4s-q-b8n"/><g filter="url(#i2iJZDe)"><path fill="url(#i5b1ojc)" class="e460wb-gs"/><path fill="url(#ifSfzbe)" class="e460wb-gs"/><path fill="url(#ih6dC9c)" class="e460wb-gs"/></g><g filter="url(#iafgUnd)"><path fill="url(#ibijqYb)" class="s7lp4rbzh"/><path fill="url(#iyoK4Kd)" class="s7lp4rbzh"/><path fill="url(#iJhoPse)" class="s7lp4rbzh"/></g><g filter="url(#i4DRpPd)"><path fill="url(#i9kTuLc)" class="e0_2kpbjh"/></g><g filter="url(#iu41h8b)"><path stroke="url(#iJ67e8c)" class="cj_ualb6i"/></g><g filter="url(#inuqAee)"><path class="cd1yj8bur"/></g><g filter="url(#iIiBa4c)"><path class="n3iibdccw"/><path fill="url(#iYgYbde)" class="eg6wwebxo"/><path fill="url(#iuLQ4mb)" class="eg6wwebxo"/></g><g filter="url(#iZSaTrd)"><path fill="url(#icL13gd)" class="bgen5d6rb"/></g><path fill="url(#ib5u9Je)" class="bgen5d6rb"/><path fill="url(#iT9eoCe)" class="bgen5d6rb"/><defs><radialGradient id="iCzAxDb" cx="0" cy="0" r="1" gradientTransform="matrix(1.95312 -4.20313 .66692 .3099 7.194 12.066)" gradientUnits="userSpaceOnUse"><stop class="niybxc2uq"/><stop offset="1" class="kyuvy4bbj"/></radialGradient><radialGradient id="irxCdob" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.55404 -9.91719 0 14.597 9.843)" gradientUnits="userSpaceOnUse"><stop offset=".931" class="i8--_db9h"/><stop offset=".995" class="tw2yr-3fp"/></radialGradient><radialGradient id="i6ssShe" cx="0" cy="0" r="1" gradientTransform="rotate(173.648 10.7 6.981)scale(1.60475 1.63343)" gradientUnits="userSpaceOnUse"><stop class="nfcjmccxh"/><stop offset="1" class="h3fma_n5f"/></radialGradient><radialGradient id="i6KAjab" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.43636 -8.2868 0 14.582 15.942)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="ze-km1b7g"/><stop offset="1" class="nfddei0pp"/></radialGradient><radialGradient id="i2gSgbe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -8.375 13.302 26.254)" gradientUnits="userSpaceOnUse"><stop class="ls7-cblkb"/><stop offset="1" class="tbz0q_48a"/></radialGradient><radialGradient id="idcBZkt" cx="0" cy="0" r="1" gradientTransform="matrix(-1.625 0 0 -5.46875 21.646 26.129)" gradientUnits="userSpaceOnUse"><stop class="voemc8h9d"/><stop offset="1" class="osd7ifb8c"/></radialGradient><radialGradient id="iiLw8Vb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.40626 -1.21873 1.72833 -6.24868 19.552 23.941)" gradientUnits="userSpaceOnUse"><stop offset=".273" class="d-ykpkboz"/><stop offset="1" class="f8x3opbgo"/></radialGradient><radialGradient id="iAIO9Yd" cx="0" cy="0" r="1" gradientTransform="matrix(-11.0625 0 0 -16.6672 18.302 22.722)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="eqb1ki6td"/><stop offset="1" class="dmxjdc_5c"/></radialGradient><radialGradient id="isZrtzc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55668 4.16175 -7.47563 -2.79621 19.02 16.26)" gradientUnits="userSpaceOnUse"><stop class="nuif9xlfl"/><stop offset="1" class="o41nkwbqu"/></radialGradient><radialGradient id="iJkm9gA" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.7832 3.37648 0 6.864 29.754)" gradientUnits="userSpaceOnUse"><stop offset=".658" class="q_n5wkbyq"/><stop offset="1" class="x8m9vebtt"/></radialGradient><radialGradient id="iov0n7a" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.8437 2.89364 0 7.607 29.972)" gradientUnits="userSpaceOnUse"><stop class="ygstjnb_e"/><stop offset="1" class="idk0shbpn"/></radialGradient><radialGradient id="inI3Unb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.40144 -2.74144 0 24.114 23.977)" gradientUnits="userSpaceOnUse"><stop class="deg-o6bbc"/><stop offset="1" class="q-uw1wb3b"/></radialGradient><radialGradient id="i4dn0Mr" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.5625 -2.47704 0 21.577 22.973)" gradientUnits="userSpaceOnUse"><stop offset=".036" class="mr8fywmtc"/><stop offset="1" class="bcdc9wb8u"/></radialGradient><radialGradient id="i8VHrfb" cx="0" cy="0" r="1" gradientTransform="rotate(153.895 3.457 6.625)scale(1.2876 2.64446)" gradientUnits="userSpaceOnUse"><stop offset=".928" class="uqtt7sb-u"/><stop offset="1" class="rdnstubca"/></radialGradient><radialGradient id="iONQhJd" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 18.546 11.492)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="iymXAON" cx="0" cy="0" r="1" gradientTransform="matrix(1.31577 .7375 -.2085 .37199 19.576 9.372)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="i17eMBc" cx="0" cy="0" r="1" gradientTransform="matrix(2.0625 .81627 -.34476 .87113 19.46 9.444)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="j5x1e5b7h"/><stop offset="1" class="fd2qmhv5e"/></radialGradient><radialGradient id="iOn5rWY" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0619 .83219 18.898 11.165)" gradientUnits="userSpaceOnUse"><stop offset=".696" class="l__dw9bpv"/><stop offset=".8" class="e5rms23te"/></radialGradient><radialGradient id="i5QVC5b" cx="0" cy="0" r="1" gradientTransform="rotate(180 4.953 5.526)scale(1.05596)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="ik58dCb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 17.365 10.515)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="iniTaBb" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 7.043 7.417)scale(2.38203 1.65881)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="iQEVXdd" cx="0" cy="0" r="1" gradientTransform="matrix(1.28915 -3.92836 4.98436 1.6357 12.344 17.023)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="iws3H3d" cx="0" cy="0" r="1" gradientTransform="scale(9.10147 7.28125)rotate(90 .104 1.49)" gradientUnits="userSpaceOnUse"><stop offset=".708" class="r7k0u1wka"/><stop offset=".953" class="x8tnpcbsd"/></radialGradient><radialGradient id="i0A2HKc" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 7.563 6.916)scale(7.03739 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="iMRU1ad" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 16.807 10.097)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="icKNeid" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 12.43 9.868)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="im9J3ve" cx="0" cy="0" r="1" gradientTransform="matrix(-.87016 3.22674 -2.58193 -.69627 15.89 7.78)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="inRcWmc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28601 0 0 -6.44557 19.607 11.584)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="inmj7Jd" cx="0" cy="0" r="1" gradientTransform="matrix(1.751 -1.5625 1.85515 2.07895 10.47 16.244)" gradientUnits="userSpaceOnUse"><stop class="z26rrllgi"/><stop offset="1" class="fs9pa7bci"/></radialGradient><radialGradient id="ic43Z2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.90625 10.1535 0 14.509 15.182)" gradientUnits="userSpaceOnUse"><stop offset=".636" class="fc6ewdb6j"/><stop offset=".917" class="o1-54wbpb"/></radialGradient><radialGradient id="iWWBpJe" cx="0" cy="0" r="1" gradientTransform="rotate(-101.441 12.644 -.068)scale(2.08546 .58856)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="i7scFJc" cx="0" cy="0" r="1" gradientTransform="matrix(-.7078 0 0 -.2179 15 12.523)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iW7ouXG" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 16.688 10.456)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="itPh8OF" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 16.46 10.54)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ixqefOB" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 12.324 10.456)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iPRYuBk" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.273 -.588)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iHZvJfc" cx="0" cy="0" r="1" gradientTransform="rotate(116.696 8.04 7.094)scale(6.12125 6.5789)" gradientUnits="userSpaceOnUse"><stop class="zraasrypm"/><stop offset="1" class="wt7c97xxx"/></radialGradient><radialGradient id="izHz1gd" cx="0" cy="0" r="1" gradientTransform="matrix(.73215 -3.875 1.71541 .32411 8.289 7.066)" gradientUnits="userSpaceOnUse"><stop class="nl8hdv5-q"/><stop offset="1" class="kmg6h4b5x"/></radialGradient><radialGradient id="iFF74De" cx="0" cy="0" r="1" gradientTransform="matrix(-1.125 1.28124 -3.60476 -3.16519 19.646 3.098)" gradientUnits="userSpaceOnUse"><stop class="iyfczmh7s"/><stop offset="1" class="m2b3l_8kx"/></radialGradient><radialGradient id="ia6hdgb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.73438 4.0625 0 10.833 7.191)" gradientUnits="userSpaceOnUse"><stop class="n4fn3obqp"/><stop offset="1" class="h9dvmcbxu"/></radialGradient><radialGradient id="inGX0Oc" cx="0" cy="0" r="1" gradientTransform="matrix(-14.5563 0 0 -2.0625 21.577 27.816)" gradientUnits="userSpaceOnUse"><stop class="cv6gnzbto"/><stop offset="1" class="wl84mmb3d"/></radialGradient><radialGradient id="iN2yeVc" cx="0" cy="0" r="1" gradientTransform="rotate(104.338 -1.768 20.747)scale(7.1928 1.69685)" gradientUnits="userSpaceOnUse"><stop class="sl-gsib3f"/><stop offset="1" class="mr-s-pbar"/></radialGradient><radialGradient id="izpcbVd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.33866 0 0 -.95307 18.703 7.174)" gradientUnits="userSpaceOnUse"><stop offset=".169" class="xr_40cc2f"/><stop offset="1" class="kjxybmb-y"/></radialGradient><radialGradient id="iZ6eZGb" cx="0" cy="0" r="1" gradientTransform="matrix(1.03125 1.48437 -13.62738 9.46743 6.63 8.144)" gradientUnits="userSpaceOnUse"><stop class="ehnthvqoy"/><stop offset="1" class="rzbfz4btw"/></radialGradient><radialGradient id="ibPujte" cx="0" cy="0" r="1" gradientTransform="matrix(-.96093 -.6172 .84322 -1.31284 7.677 9.129)" gradientUnits="userSpaceOnUse"><stop offset=".501" class="rz-l4sb2t"/><stop offset="1" class="nqxo4gbph"/></radialGradient><radialGradient id="i6qz0xW" cx="0" cy="0" r="1" gradientTransform="matrix(.75 -.5625 1.05375 1.405 22.02 9.035)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="euqyawb2g"/><stop offset="1" class="vkwv3acem"/></radialGradient><radialGradient id="iutMDkb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.27624 -.62648 0 14.961 21.755)" gradientUnits="userSpaceOnUse"><stop class="krttc8bap"/><stop offset="1" class="kpneurz6b"/></radialGradient><radialGradient id="ih18itd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.41436 1.45816 0 14.582 25.827)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="ko6eamtic"/><stop offset="1" class="tc4y5tbfa"/></radialGradient><radialGradient id="iKGw4kt" cx="0" cy="0" r="1" gradientTransform="rotate(167.143 8.463 3.484)scale(2.97716 4.69784)" gradientUnits="userSpaceOnUse"><stop class="ism0j8_fd"/><stop offset="1" class="cc4vnjblc"/></radialGradient><radialGradient id="iyoBo3i" cx="0" cy="0" r="1" gradientTransform="matrix(2.81253 -2.28745 2.84526 3.49839 11.927 7.285)" gradientUnits="userSpaceOnUse"><stop class="kx5tbm42q"/><stop offset="1" class="ndetd3gmc"/></radialGradient><radialGradient id="iQy6vPz" cx="0" cy="0" r="1" gradientTransform="rotate(100.623 .526 19.636)scale(1.16051 4.42408)" gradientUnits="userSpaceOnUse"><stop class="pfbpewb0p"/><stop offset="1" class="dutea5bgy"/></radialGradient><radialGradient id="iqw3Vdd" cx="0" cy="0" r="1" gradientTransform="matrix(-.83594 .34375 -.14238 -.34624 23.107 16.395)" gradientUnits="userSpaceOnUse"><stop class="xdf0lfbrm"/><stop offset="1" class="cvnvm48dp"/></radialGradient><radialGradient id="iZmNjZb" cx="0" cy="0" r="1" gradientTransform="matrix(.83594 .17968 -.05863 .27278 21.786 16.332)" gradientUnits="userSpaceOnUse"><stop class="leotspfhb"/><stop offset="1" class="u3sz7tboa"/></radialGradient><radialGradient id="ifSfzbe" cx="0" cy="0" r="1" gradientTransform="matrix(1.3287 1.76599 -.65664 .49404 19.852 16.946)" gradientUnits="userSpaceOnUse"><stop class="qu53-3efb"/><stop offset="1" class="d8vnolbdv"/></radialGradient><radialGradient id="ih6dC9c" cx="0" cy="0" r="1" gradientTransform="matrix(1.46875 .4375 -1.25756 4.22181 18.833 19.379)" gradientUnits="userSpaceOnUse"><stop class="fcewfubec"/><stop offset="1" class="ku_tac4_z"/></radialGradient><radialGradient id="ibijqYb" cx="0" cy="0" r="1" gradientTransform="rotate(135.9 10.028 15.777)scale(4.22106 5.23602)" gradientUnits="userSpaceOnUse"><stop class="ybzdb35ne"/><stop offset="1" class="k-xo7erne"/></radialGradient><radialGradient id="iyoK4Kd" cx="0" cy="0" r="1" gradientTransform="matrix(-4 -.68747 1.04434 -6.0764 28.646 22.504)" gradientUnits="userSpaceOnUse"><stop offset=".711" class="d7eq7sb9j"/><stop offset="1" class="pci0oxh-l"/></radialGradient><radialGradient id="iJhoPse" cx="0" cy="0" r="1" gradientTransform="rotate(156.903 12.063 12.55)scale(1.15509 2.08846)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="a6yl-cb9v"/><stop offset="1" class="w_w8qcl3c"/></radialGradient><radialGradient id="iYgYbde" cx="0" cy="0" r="1" gradientTransform="matrix(1.27004 2.2186 -1.58976 .91006 11.157 16.066)" gradientUnits="userSpaceOnUse"><stop class="hq-8cac3q"/><stop offset="1" class="kiftlkrmt"/></radialGradient><radialGradient id="iuLQ4mb" cx="0" cy="0" r="1" gradientTransform="matrix(2.31645 1.18733 -.41625 .81209 12.19 16.066)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><radialGradient id="icL13gd" cx="0" cy="0" r="1" gradientTransform="rotate(136.408 5.786 11.704)scale(4.35086 4.82952)" gradientUnits="userSpaceOnUse"><stop class="dxbo1t_fa"/><stop offset="1" class="kvhp_ip6r"/></radialGradient><radialGradient id="iT9eoCe" cx="0" cy="0" r="1" gradientTransform="matrix(4.58258 0 0 1.41506 13.993 16.033)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><filter id="iODB3ve" width="17.197" height="11.9" x="5.988" y="7.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.137255 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2608"/></filter><filter id="iqbaXys" width="15.118" height="14.561" x="6.988" y="2.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.254902 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2608"/></filter><filter id="iZPWkte" width="3.218" height="3.468" x="17.724" y="9.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2608"/></filter><filter id="iQmUBOQ" width="3.148" height="3.148" x="17.759" y="9.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2608" stdDeviation=".25"/></filter><filter id="iGTkFob" width="2.648" height="2.648" x="8.516" y="9.729" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2608" stdDeviation=".125"/></filter><filter id="iaNUZud" width="10.197" height="11.127" x="9.411" y="6.146" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2608"/></filter><filter id="iXEvchc" width="2.877" height="3.682" x="12.905" y="10.048" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2608" stdDeviation=".25"/></filter><filter id="izk1kJe" width="2.205" height="3.182" x="13.404" y="10.159" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2608" stdDeviation=".125"/></filter><filter id="ipbVFRb" width="3.702" height="1.526" x="12.655" y="13.401" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2608" stdDeviation=".05"/></filter><filter id="ihqFakc" width="3.001" height="1.285" x="15.448" y="9.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2608"/></filter><filter id="iyh1und" width="3.001" height="1.285" x="10.563" y="9.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2608"/></filter><filter id="i0Va2Td" width="2.453" height="1.091" x="10.698" y="7.779" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2608"/></filter><filter id="iyxWhIb" width="2.453" height="1.091" x="16.115" y="7.779" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2608"/></filter><filter id="iyrUkmd" width=".787" height=".696" x="15.954" y="10.016" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2608" stdDeviation=".05"/></filter><filter id="ijGmKAe" width=".891" height=".913" x="16.794" y="10.091" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2608" stdDeviation=".1"/></filter><filter id="iIC1sEN" width=".986" height="1.04" x="12.351" y="10.027" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2608" stdDeviation=".1"/></filter><filter id="iaopTtd" width=".913" height=".704" x="11.596" y="10.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2608" stdDeviation=".05"/></filter><filter id="i36TyJv" width="5.52" height="4.05" x="11.827" y="3.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.415686 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2608"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.2 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2608" result="effect2_innerShadow_4002_2608"/></filter><filter id="iNGyfsb" width="6.94" height="14.221" x="16.577" y="15.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.270588 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2608"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.266667 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2608" result="effect2_innerShadow_4002_2608"/></filter><filter id="i2iJZDe" width="11.012" height="8.855" x="17.86" y="16.47" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.0980392 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2608"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.270588 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2608" result="effect2_innerShadow_4002_2608"/></filter><filter id="iafgUnd" width="4.557" height="7.476" x="23.816" y="17.699" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.760784 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2608"/></filter><filter id="i4DRpPd" width="2.509" height="3.213" x="13.154" y="3.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.141176 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_2608"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_2608" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.768627 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_2608"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.337255 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_2608" result="effect3_innerShadow_4002_2608"/></filter><filter id="iu41h8b" width="1.83" height="4.718" x="18.091" y="17.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2608" stdDeviation=".125"/></filter><filter id="inuqAee" width="2.769" height="7.081" x="18.396" y="23.072" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2608" stdDeviation=".2"/></filter><filter id="iIiBa4c" width="6.88" height="4.067" x="11.157" y="15.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.0470588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2608"/></filter><filter id="iZSaTrd" width="4.97" height="4.236" x="13.277" y="15.406" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.12549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2608"/></filter><linearGradient id="iaUsmrb" x1="14.587" x2="14.587" y1="7.972" y2="19.472" gradientUnits="userSpaceOnUse"><stop class="usw0jac_r"/><stop offset="1" class="zhmn0cciw"/></linearGradient><linearGradient id="i1ptMxc" x1="14.587" x2="14.587" y1="7.249" y2="10.843" gradientUnits="userSpaceOnUse"><stop offset=".184" class="l1qje4b6x"/><stop offset="1" class="vx6m-x__v"/></linearGradient><linearGradient id="iP57O3b" x1="14.597" x2="14.597" y1="8.004" y2="17.124" gradientUnits="userSpaceOnUse"><stop class="o2xqgmbjp"/><stop offset="1" class="v2ky7trsz"/></linearGradient><linearGradient id="ih3vBxb" x1="7.607" x2="6.489" y1="26.66" y2="26.629" gradientUnits="userSpaceOnUse"><stop class="gyzg0db3w"/><stop offset="1" class="y28tkbl-n"/></linearGradient><linearGradient id="i0i1YkC" x1="7.407" x2="21.783" y1="15.862" y2="15.862" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iI325ic" x1="7.407" x2="21.783" y1="15.832" y2="15.832" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iw1JEud" x1="8.262" x2="9.503" y1="11.14" y2="11.14" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="iqZQ5te" x1="13.654" x2="14.506" y1="12.384" y2="12.384" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="iNLbCOd" x1="14.506" x2="14.506" y1="13.183" y2="12.573" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="i2nYnco" x1="13.442" x2="13.903" y1="14.593" y2="13.88" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="iZqrxQd" x1="17.466" x2="17.152" y1="10.51" y2="10.703" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ihNmjOb" x1="13.068" x2="12.754" y1="10.51" y2="10.703" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ilxTFMd" x1="10.646" x2="16.989" y1="6.723" y2="6.723" gradientUnits="userSpaceOnUse"><stop class="ks1omcbjp"/><stop offset="1" class="jk0lbnbnn"/></linearGradient><linearGradient id="iiH6veK" x1="14.592" x2="14.592" y1="30.316" y2="28.723" gradientUnits="userSpaceOnUse"><stop class="s2qawgbpe"/><stop offset="1" class="iu5oamiyf"/></linearGradient><linearGradient id="iI4mEsd" x1="14.592" x2="14.592" y1="26.173" y2="27.441" gradientUnits="userSpaceOnUse"><stop class="tcape2laf"/><stop offset="1" class="gd-vr7bgk"/></linearGradient><linearGradient id="i1i1Lbq" x1="14.582" x2="14.582" y1="6.972" y2="11.754" gradientUnits="userSpaceOnUse"><stop offset=".526" class="ffurleovf"/><stop offset=".654" class="oirct-bua"/></linearGradient><linearGradient id="iMEPogb" x1="14.582" x2="14.582" y1="19.605" y2="26.175" gradientUnits="userSpaceOnUse"><stop class="jbzirjbuq"/><stop offset="1" class="s7s75dkrn"/></linearGradient><linearGradient id="iatOxCb" x1="22.021" x2="18.333" y1="16.754" y2="29.973" gradientUnits="userSpaceOnUse"><stop class="ommdktbpj"/><stop offset="1" class="dinvdlb3p"/></linearGradient><linearGradient id="i5b1ojc" x1="20.021" x2="28.208" y1="22.191" y2="18.879" gradientUnits="userSpaceOnUse"><stop class="lf_6el-zz"/><stop offset="1" class="p6qk4rbue"/></linearGradient><linearGradient id="i9kTuLc" x1="14.458" x2="14.458" y1="4.221" y2="6.666" gradientUnits="userSpaceOnUse"><stop class="rx-q5b7rc"/><stop offset="1" class="fz8-ywb6c"/></linearGradient><linearGradient id="iJ67e8c" x1="18.689" x2="20.192" y1="21.647" y2="16.457" gradientUnits="userSpaceOnUse"><stop class="ih4zzfygk"/><stop offset="1" class="bq_18tbdo"/></linearGradient><linearGradient id="ib5u9Je" x1="13.277" x2="13.489" y1="18.084" y2="18.084" gradientUnits="userSpaceOnUse"><stop class="lwl8ufbrj"/><stop offset="1" class="i5hn1bqvd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-firefighter-medium-dark" /></template>
<style>
.a6yl-cb9v {
  stop-color: var(--svg-color--eeecf0, #EEECF0);
}

.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
}

.b_qv5du4s {
  fill: var(--svg-color--dc375e, #DC375E);
  d: path("M14.587 15.472c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.bcdc9wb8u {
  stop-color: var(--svg-color--d54161, #D54161);
  stop-opacity: 0;
}

.bgen5d6rb {
  d: path("M13.277 16.798v1.834c0 .56.45 1.01 1.01 1.01h1.78c1.09 0 1.98-.89 1.98-1.98v-2.005c-.898.826-2.116 1.3-3.457 1.3q-.683-.001-1.313-.16");
}

.boaowqb5j {
  d: path("M16.625 10.167c.063.085-.07.19-.22.302c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.359c.15-.113.325-.136.389-.05");
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.bq_18tbdo {
  stop-color: var(--svg-color--cd517b, #CD517B);
  stop-opacity: 0;
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.cc4vnjblc {
  stop-color: var(--svg-color--524361, #524361);
}

.cd1yj8bur {
  stroke: var(--svg-color--87625e, #87625E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.921 29.629c0-.2 1.146-4.105 1.719-6.032");
}

.cifdjacwb {
  cx: 12.053px;
  cy: 10.36px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
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

.cpg_yds5t {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.897 9.707c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.crj44uotj {
  stop-color: var(--svg-color--996b5e, #996B5E);
}

.cv6gnzbto {
  stop-color: var(--svg-color--fec852, #FEC852);
}

.cvnvm48dp {
  stop-color: var(--svg-color--a17d74, #A17D74);
  stop-opacity: 0;
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.d_-1b_bzw {
  d: path("M7.607 29.972V17.971a10.98 10.98 0 0 0-4.02 8.501v3.5z");
}

.d-ykpkboz {
  stop-color: var(--svg-color--c6284c, #C6284C);
}

.d6l_zva3n {
  fill: var(--svg-color--ecb845, #ECB845);
  d: path("M21.577 26.173H7.607v3.8h13.97z");
}

.d7eq7sb9j {
  stop-color: var(--svg-color--bab3b6, #BAB3B6);
  stop-opacity: 0;
}

.d8vnolbdv {
  stop-color: var(--svg-color--ed2e7c, #ED2E7C);
  stop-opacity: 0;
}

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
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

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.dmxjdc_5c {
  stop-color: var(--svg-color--d0465e, #D0465E);
}

.dtg7ku1fk {
  fill-rule: evenodd;
  d: path("M21.782 12.5c.213-.434.324-.92.324-1.426c0-.467-.096-.906-.269-1.306h.006a3 3 0 0 0-.282-.513l-.002-.003a3.24 3.24 0 0 1-.526-1.77l-.167-.01c0-1.822-1.31-3.3-3.132-3.3a.54.54 0 0 1-.455-.233a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.455.233l-.085.001C9.592 4.218 8.49 5.688 8.49 7.481h-.33a3.24 3.24 0 0 1-.527 1.771l-.002.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455c-.93 1.953.83 4.168 2.894 4.168h8.582c1.78 0 3.218-1.453 3.218-2.906c0-.506-.122-.837-.324-1.262a.52.52 0 0 1 0-.455M9.522 9.829H9.51l1.198 2.356c.124 2.803 1.217 0 3.889 0s3.836 3.12 3.96.317l.997-3.202c-.054-1.245-.817-1.327-.997-1.327h-3.22a3.86 3.86 0 0 1-3.19-1.674a.264.264 0 0 0-.461.051l-.082.194a2.3 2.3 0 0 1-1.241 1.255l-.051.02c-.236.123-.79.49-.81 1.44l.01.305z");
}

.dutea5bgy {
  stop-color: var(--svg-color--734145, #734145);
  stop-opacity: 0;
}

.dw66imbcr {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.115 9.707c-.653 0-1.205.45-1.355 1.059c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.37-1.128");
}

.dxbo1t_fa {
  stop-color: var(--svg-color--ff547f, #FF547F);
}

.e0_2kpbjh {
  d: path("M13.304 4.91c0-.154.183-.232.293-.126l.155.149a.162.162 0 0 0 .274-.117v-.17c0-.345.178-.665.472-.847l.18-.111a.23.23 0 0 1 .35.195v1.194a.17.17 0 0 0 .278.132l.096-.078a.13.13 0 0 1 .21.1v.333a1.154 1.154 0 0 1-2.308-.052z");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e460wb-gs {
  d: path("m20.012 16.732l4.416 1.16a3.57 3.57 0 0 0 2.071-.053l.148-.055c.178-.062.401-.053.554.108c1.072 1.125 1.43 2.62.984 4.235c-.447 1.615-1.733 2.765-2.98 3.034c-.084.02-.348.046-.506-.158l-.141-.14a3.5 3.5 0 0 0-1.745-1.11L18.57 22.55a.61.61 0 0 1-.43-.779l1.25-4.675c.045-.22.37-.43.622-.364");
}

.e5rms23te {
  stop-color: var(--svg-color--6f4544, #6F4544);
}

.eg6wwebxo {
  d: path("M11.157 15.678v1.974c0 1.09.89 1.98 1.98 1.98h2.92c1.09 0 1.98-.88 1.98-1.98v-1.986c-.896.82-2.111 1.29-3.447 1.29c-1.329 0-2.538-.465-3.433-1.278");
}

.ehnthvqoy {
  stop-color: var(--svg-color--b3576b, #B3576B);
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.eqb1ki6td {
  stop-color: var(--svg-color--d0465e, #D0465E);
  stop-opacity: 0;
}

.erxr74bkf {
  fill: var(--svg-color--88014f, #88014F);
  d: path("M14.506 13.964a3 3 0 0 1-1.421-.344c-.141-.073-.292.089-.204.22a1.932 1.932 0 0 0 3.25 0c.088-.137-.063-.293-.203-.22c-.412.22-.896.344-1.422.344");
}

.euqyawb2g {
  stop-color: var(--svg-color--be1e3b, #BE1E3B);
}

.f8x3opbgo {
  stop-color: var(--svg-color--c6284c, #C6284C);
  stop-opacity: 0;
}

.faisxaclj {
  d: path("M14.587 15.472c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.fc6ewdb6j {
  stop-color: var(--svg-color--673643, #673643);
  stop-opacity: 0;
}

.fcewfubec {
  stop-color: var(--svg-color--c93271, #C93271);
}

.fd2qmhv5e {
  stop-color: var(--svg-color--653d37, #653D37);
  stop-opacity: 0;
}

.ffurleovf {
  stop-color: var(--svg-color--bb2b57, #BB2B57);
}

.fs9pa7bci {
  stop-color: var(--svg-color--6e494b, #6E494B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fw2o80b7i {
  d: path("M8.659 7.972h11.847c.948 0 1.988.485 1.988 2.68h.692V9.347c0-1.43-.848-2.375-2.457-2.375H8.435c-1.609 0-2.456.946-2.456 2.375v1.305h.69c0-2.195 1.04-2.68 1.99-2.68");
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
}

.fz8-ywb6c {
  stop-color: var(--svg-color--f48942, #F48942);
}

.gcfqr7bfg {
  stop-color: var(--svg-color--714350, #714350);
  stop-opacity: 0;
}

.gd-vr7bgk {
  stop-color: var(--svg-color--edb63d, #EDB63D);
  stop-opacity: 0;
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

.hgn0v4h0b {
  d: path("M20.885 7.333H8.29v-.378c0-2.734 2.01-4.927 5.02-4.927h2.411c3.329 0 5.165 2.193 5.165 4.927z");
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.hq-8cac3q {
  stop-color: var(--svg-color--c75567, #C75567);
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

.j2la80nsc {
  cx: 12.053px;
  cy: 10.36px;
  rx: 0.39px;
  ry: 0.197px;
}

.j5-d0iboi {
  stop-color: var(--svg-color--c71931, #C71931);
  stop-opacity: 0;
}

.j5x1e5b7h {
  stop-color: var(--svg-color--653d37, #653D37);
}

.ja-6i29rv {
  d: path("M14.617 15.833h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jbzirjbuq {
  stop-color: var(--svg-color--ba2f50, #BA2F50);
}

.jk0lbnbnn {
  stop-color: var(--svg-color--be324c, #BE324C);
  stop-opacity: 0;
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
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

.ko6eamtic {
  stop-color: var(--svg-color--ab0d36, #AB0D36);
  stop-opacity: 0;
}

.kpneurz6b {
  stop-color: var(--svg-color--c1415c, #C1415C);
  stop-opacity: 0;
}

.krttc8bap {
  stop-color: var(--svg-color--c1415c, #C1415C);
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

.l__dw9bpv {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
  stop-opacity: 0;
}

.l1qje4b6x {
  stop-color: var(--svg-color--710425, #710425);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
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

.ls7-cblkb {
  stop-color: var(--svg-color--dd365e, #DD365E);
}

.lwl8ufbrj {
  stop-color: var(--svg-color--ca435d, #CA435D);
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.m2b3l_8kx {
  stop-color: var(--svg-color--fd5c7c, #FD5C7C);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mr-s-pbar {
  stop-color: var(--svg-color--bc832d, #BC832D);
  stop-opacity: 0;
}

.mr8fywmtc {
  stop-color: var(--svg-color--b91a3e, #B91A3E);
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.mv2od5z8x {
  fill: var(--svg-color--272528, #272528);
  d: path("M13.364 10.484c-.265-.467-.669-.836-1.537-.836c-.38 0-.747.106-1.073.369c-.269.217-.233.495-.025.6l.556.317c.652-.211 1.373-.24 2.08-.45");
}

.mzvb6ccyl {
  fill: var(--svg-color--352827, #352827);
  fill-rule: evenodd;
  d: path("m18.238 8.372l-.138.23za.268.268 0 0 1-.276.46l-.005-.003l-.021-.012l-.092-.046a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 1 1-.093-.528c.513-.09.988 0 1.328.11a3.3 3.3 0 0 1 .559.238l.009.005l.003.002z");
}

.n3iibdccw {
  fill: var(--svg-color--d53260, #D53260);
  d: path("M11.157 15.678v1.974c0 1.09.89 1.98 1.98 1.98h2.92c1.09 0 1.98-.88 1.98-1.98v-1.986c-.896.82-2.111 1.29-3.447 1.29c-1.329 0-2.538-.465-3.433-1.278");
}

.n4fn3obqp {
  stop-color: var(--svg-color--c52632, #C52632);
}

.n4s-q-b8n {
  d: path("m22.636 16.137l-1.38-.368a.51.51 0 0 0-.625.358l-3.804 13.846h2.547l3.63-13.212a.53.53 0 0 0-.368-.624");
}

.n4yp-siqi {
  fill: var(--svg-color--352827, #352827);
  d: path("m11.109 8.83l-.005.002a.268.268 0 0 1-.276-.46l.002-.001l.003-.002l.01-.005l.032-.018q.04-.023.116-.06c.098-.046.239-.106.41-.16c.34-.11.815-.2 1.328-.11a.268.268 0 0 1-.093.528a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.456.193");
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

.nl8hdv5-q {
  stop-color: var(--svg-color--bd585d, #BD585D);
}

.nqxo4gbph {
  stop-color: var(--svg-color--a21e3e, #A21E3E);
  stop-opacity: 0;
}

.ns8uxjbrq {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m14.159 10.692l-.483 1.7c-.098.35.138.699.473.699h.714c.335 0 .571-.355.473-.7l-.483-1.7c-.103-.376-.586-.376-.694 0");
}

.nuif9xlfl {
  stop-color: var(--svg-color--ff385e, #FF385E);
}

.nxde922ww {
  d: path("m14.159 10.692l-.483 1.7c-.098.35.138.699.473.699h.714c.335 0 .571-.355.473-.7l-.483-1.7c-.103-.376-.586-.376-.694 0");
}

.o-dqgx1iv {
  d: path("M16.69 9.979a.893.893 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.o1-54wbpb {
  stop-color: var(--svg-color--673643, #673643);
}

.o1qh5ebyv {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.625 10.167c.063.085-.07.19-.22.302c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.359c.15-.113.325-.136.389-.05");
}

.o1y7r8lbo {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M19.333 12.127a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.o2xqgmbjp {
  stop-color: var(--svg-color--1e0106, #1E0106);
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.o41nkwbqu {
  stop-color: var(--svg-color--ff385e, #FF385E);
  stop-opacity: 0;
}

.obi765bgs {
  d: path("M17.485 10.754a.84.84 0 0 0-.231-.463l-.26.285l.117.228z");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oirct-bua {
  stop-color: var(--svg-color--bb2b57, #BB2B57);
  stop-opacity: 0;
}

.olqyf7fmb {
  stop-color: var(--svg-color--875e5e, #875E5E);
}

.ommdktbpj {
  stop-color: var(--svg-color--8f5b56, #8F5B56);
}

.opgioqbtx {
  stop-color: var(--svg-color--805c54, #805C54);
  stop-opacity: 0;
}

.osd7ifb8c {
  stop-color: var(--svg-color--d23b59, #D23B59);
  stop-opacity: 0;
}

.osxg47drp {
  stop-color: var(--svg-color--743f5a, #743F5A);
}

.p1b0865rd {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M9.84 12.127a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.p6qk4rbue {
  stop-color: var(--svg-color--fc3d5f, #FC3D5F);
}

.p88c31myn {
  stop-color: var(--svg-color--815a5b, #815A5B);
  stop-opacity: 0;
}

.pci0oxh-l {
  stop-color: var(--svg-color--a39ba9, #A39BA9);
}

.pfbpewb0p {
  stop-color: var(--svg-color--734145, #734145);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.q_n5wkbyq {
  stop-color: var(--svg-color--d93b60, #D93B60);
}

.q-uw1wb3b {
  stop-color: var(--svg-color--c7425f, #C7425F);
}

.qging0bua {
  d: path("M9.419 9.79h.012l-.01-.265l-.01-.306c.02-.95.574-1.316.81-1.439l.051-.02l.051-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.051c.718 1.05 1.918 1.36 3.19 1.36h3.22c.18 0 1.228.16 1.136 1.645l-.12 3.073c-.123 2.803-2.311 4.685-4.982 4.685s-4.86-1.882-4.984-4.684z");
}

.qu53-3efb {
  stop-color: var(--svg-color--fc4b93, #FC4B93);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r4ivgmbgz {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.506 13.964a3 3 0 0 1-1.421-.344c-.141-.073-.292.089-.204.22a1.932 1.932 0 0 0 3.25 0c.088-.137-.063-.293-.203-.22c-.412.22-.896.344-1.422.344Z");
}

.r7k0u1wka {
  stop-color: var(--svg-color--7a414f, #7A414F);
  stop-opacity: 0;
}

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.rdnstubca {
  stop-color: var(--svg-color--644844, #644844);
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

.s_1fdg8-f {
  d: path("M13.137 10.766c0-.288-.234-.48-.298-.539l-.288.28l.177.36z");
}

.s2qawgbpe {
  stop-color: var(--svg-color--b78426, #B78426);
}

.s7lp4rbzh {
  d: path("M25.649 18.01q.435-.031.85-.17l.148-.055c.178-.063.401-.054.554.107c1.072 1.125 1.43 2.621.984 4.236c-.447 1.614-1.733 2.764-2.98 3.033c-.084.02-.348.046-.506-.157l-.141-.14a3.5 3.5 0 0 0-.642-.589c1.567-.052 2.817-1.084 3.203-2.529c.39-1.469-.236-3.003-1.472-3.735z");
}

.s7s75dkrn {
  stop-color: var(--svg-color--b93054, #B93054);
}

.sl-gsib3f {
  stop-color: var(--svg-color--bc832d, #BC832D);
}

.snc90qx2m {
  d: path("M19.333 12.662a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.ssn5xcb0b {
  fill: var(--svg-color--000, #000);
  d: path("M12.833 10.871a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.454.745h.904a.5.5 0 0 0 .061-.235");
}

.t9k87pm2r {
  stop-color: var(--svg-color--875555, #875555);
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

.tfuwfjb_f {
  d: path("M12.322 9.979a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.236a.9.9 0 0 0-.897-.892");
}

.tw2yr-3fp {
  stop-color: var(--svg-color--483c3d, #483C3D);
}

.u_wc6ubhb {
  d: path("M21.577 26.173H7.607v3.8h13.97z");
}

.u3sz7tboa {
  stop-color: var(--svg-color--8c5e57, #8C5E57);
  stop-opacity: 0;
}

.uj7hgsb3u {
  stop-color: var(--svg-color--815a5b, #815A5B);
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.uqtt7sb-u {
  stop-color: var(--svg-color--644844, #644844);
  stop-opacity: 0;
}

.usw0jac_r {
  stop-color: var(--svg-color--a9112c, #A9112C);
}

.v2ky7trsz {
  stop-color: var(--svg-color--170810, #170810);
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.vkwv3acem {
  stop-color: var(--svg-color--be1e3b, #BE1E3B);
  stop-opacity: 0;
}

.voemc8h9d {
  stop-color: var(--svg-color--d23b59, #D23B59);
}

.vq7q2tbpw {
  d: path("M9.82 12.662a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.vx6m-x__v {
  stop-color: var(--svg-color--a81330, #A81330);
  stop-opacity: 0;
}

.vylrb5bvm {
  d: path("M21.577 17.982v11.99h4v-3.5a10.98 10.98 0 0 0-4-8.49");
}

.w_8w8wqmn {
  d: path("M15.167 19.605h-1.17v6.57h1.17z");
}

.w_w8qcl3c {
  stop-color: var(--svg-color--eeecf0, #EEECF0);
  stop-opacity: 0;
}

.wg3eepbwp {
  stop-color: var(--svg-color--805c54, #805C54);
}

.wl84mmb3d {
  stop-color: var(--svg-color--fec852, #FEC852);
  stop-opacity: 0;
}

.wow_zkb9s {
  d: path("M22.174 7.972H7.152c-.395.32-.78 1.337-1.164 1.657v1.343c0 4.69 3.855 8.5 8.599 8.5s8.598-3.81 8.598-8.5V9.63c-.354-.42-.687-1.207-1.011-1.657");
}

.wt7c97xxx {
  stop-color: var(--svg-color--f44f5a, #F44F5A);
}

.x_ik4kbfh {
  stop-color: var(--svg-color--714350, #714350);
}

.x8m9vebtt {
  stop-color: var(--svg-color--df6277, #DF6277);
}

.x8tnpcbsd {
  stop-color: var(--svg-color--783644, #783644);
}

.xdf0lfbrm {
  stop-color: var(--svg-color--a17d74, #A17D74);
}

.xn49zlb4v {
  d: path("M19.333 12.127a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.xr_40cc2f {
  stop-color: var(--svg-color--fc5083, #FC5083);
}

.y28tkbl-n {
  stop-color: var(--svg-color--bf415a, #BF415A);
  stop-opacity: 0;
}

.y8sfvyb_m {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m14.114 10.83l-.684 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.494-.377-.614 0");
}

.yamoh3dov {
  stop-color: var(--svg-color--764e4c, #764E4C);
}

.ybzdb35ne {
  stop-color: var(--svg-color--ded9e3, #DED9E3);
}

.ycrcotb4u {
  stop-color: var(--svg-color--986f60, #986F60);
  stop-opacity: 0;
}

.ygstjnb_e {
  stop-color: var(--svg-color--99344a, #99344A);
}

.z26rrllgi {
  stop-color: var(--svg-color--6e494b, #6E494B);
}

.z38homb3o {
  d: path("M9.84 12.127a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
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

.zm5b7hm_o {
  fill: var(--svg-color--000, #000);
  d: path("M16.179 10.871c0-.284.227-.51.511-.51a.51.51 0 0 1 .454.745h-.904a.46.46 0 0 1-.061-.235");
}

.zoq8fuaif {
  stop-color: var(--svg-color--986f60, #986F60);
}

.zraasrypm {
  stop-color: var(--svg-color--f0406f, #F0406F);
}

.ztsl-cc-b {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M15.648 10.484c.266-.467.669-.836 1.538-.836c.38 0 .746.106 1.072.369c.27.217.233.495.025.6l-.556.317c-.652-.211-1.373-.24-2.079-.45");
}

</style>
