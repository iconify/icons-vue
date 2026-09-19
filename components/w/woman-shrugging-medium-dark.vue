<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i4kzbsd)" clip-rule="evenodd" class="x3lw1rboi"/><path fill="url(#i4YPUZd)" clip-rule="evenodd" class="x3lw1rboi"/><g filter="url(#iqk54Ok)"><path stroke="url(#itziHcb)" class="d1lp4wbpb"/></g><path fill="url(#iUxX4Ed)" clip-rule="evenodd" class="wtu7i7zxm"/><path fill="url(#iguenIe)" clip-rule="evenodd" class="wtu7i7zxm"/><g filter="url(#iVGLHDd)"><path stroke="url(#ipW0ApS)" class="ejudldebc"/></g><path fill="url(#iEdDfWA)" clip-rule="evenodd" class="us02a8j1k"/><path fill="url(#ixj2c1f)" clip-rule="evenodd" class="us02a8j1k"/><g filter="url(#iAqenOc)"><path stroke="url(#iHb6W2c)" class="geqjdr7rf"/></g><path fill="url(#i99xcDe)" clip-rule="evenodd" class="v5txmjb-r"/><path fill="url(#iwNuYbe)" clip-rule="evenodd" class="v5txmjb-r"/><path class="dd_oh5bup"/><path fill="url(#ieJW2Cs)" class="pv6p8qbkg"/><path fill="url(#i6LeXge)" class="pv6p8qbkg"/><path fill="url(#i77mk8d)" class="pv6p8qbkg"/><path fill="url(#iMoU1rb)" class="pv6p8qbkg"/><g filter="url(#iaUUyZc)"><path class="oc3yxvrel"/><path fill="url(#iXI89qd)" class="rj-4hxb-k"/><path fill="url(#iFbYzYd)" class="rj-4hxb-k"/></g><path fill="url(#iMMUQBc)" clip-rule="evenodd" class="ruilo6-op"/><path fill="url(#iH1hBIb)" clip-rule="evenodd" class="ruilo6-op"/><path fill="url(#iNFxTim)" clip-rule="evenodd" class="ruilo6-op"/><path fill="url(#i7dOrUk)" clip-rule="evenodd" class="ruilo6-op"/><path fill="url(#ivYk4Ob)" clip-rule="evenodd" class="m-59bub6h"/><path fill="url(#i4CqWOA)" clip-rule="evenodd" class="m-59bub6h"/><path fill="url(#iFLp9wd)" clip-rule="evenodd" class="m-59bub6h"/><path fill="url(#iiGZWMc)" clip-rule="evenodd" class="m-59bub6h"/><path fill="url(#irTFbTd)" clip-rule="evenodd" class="kek0nw1ry"/><path fill="url(#igMrv3d)" clip-rule="evenodd" class="kek0nw1ry"/><path fill="url(#ik8LFxi)" clip-rule="evenodd" class="kek0nw1ry"/><path fill="url(#iJbrkVc)" clip-rule="evenodd" class="kek0nw1ry"/><path fill="url(#iccndpb)" clip-rule="evenodd" class="qmfslybba"/><path fill="url(#i4sG3Or)" clip-rule="evenodd" class="qmfslybba"/><path fill="url(#iyutuBF)" clip-rule="evenodd" class="qmfslybba"/><path fill="url(#iU6YIPe)" clip-rule="evenodd" class="qmfslybba"/><g filter="url(#ijAMJub)"><path stroke="url(#iuJQnOe)" class="q1exkrh0e"/></g><g filter="url(#i7EHNju)"><path stroke="url(#iYt1nOd)" class="ftwkfbb_k"/></g><g filter="url(#i6s6yHm)"><path class="evur8nbpn"/></g><g filter="url(#iU50hcD)"><path fill="url(#ioLkjMT)" clip-rule="evenodd" class="zcmdavrrk"/><path fill="url(#iTtbBRb)" clip-rule="evenodd" class="zcmdavrrk"/><path fill="url(#iuRTzAb)" clip-rule="evenodd" class="zcmdavrrk"/><path fill="url(#igF5Izc)" clip-rule="evenodd" class="zcmdavrrk"/><path fill="url(#iPM0TrG)" clip-rule="evenodd" class="zcmdavrrk"/><path fill="url(#i8J2VFd)" clip-rule="evenodd" class="zcmdavrrk"/><path fill="url(#igfDTue)" clip-rule="evenodd" class="zcmdavrrk"/><path fill="url(#itnM06c)" clip-rule="evenodd" class="zcmdavrrk"/><path fill="url(#iu657Hb)" clip-rule="evenodd" class="zcmdavrrk"/><path fill="url(#iFaaICc)" clip-rule="evenodd" class="zcmdavrrk"/><path fill="url(#i3HhqFe)" clip-rule="evenodd" class="zcmdavrrk"/></g><path fill="url(#iGEoCve)" class="pi7duoxhr"/><path fill="url(#iti7mEe)" class="pi7duoxhr"/><path fill="url(#iClJVfd)" class="op6qopbgt"/><g filter="url(#iBNq9Sd)"><path fill="url(#i8OkU2j)" class="rc5cp_z9s"/><path fill="url(#iOuDGRd)" class="rc5cp_z9s"/><path fill="url(#i8DP3Bc)" class="rc5cp_z9s"/><path fill="url(#iknTBJc)" class="rc5cp_z9s"/><path fill="url(#iW6mndb)" class="rc5cp_z9s"/><path fill="url(#itIje2d)" class="rc5cp_z9s"/><path fill="url(#i2JIfIb)" class="rc5cp_z9s"/></g><path fill="url(#iOPVX4b)" class="z-lhhmboj"/><g filter="url(#iwzAv5W)"><path class="zux03vusp"/></g><g filter="url(#icXi6lT)"><path class="nn7f1_b3w"/></g><g filter="url(#isFIm3c)"><path stroke="url(#iWYle9c)" class="gqxi-n8lm"/></g><g filter="url(#iLYJ9Fd)"><path fill="url(#ieYAPod)" class="cuh1jzbvw"/></g><g filter="url(#iUYrA0d)"><path fill="url(#iwbzvUb)" class="koj8teb_r"/><path fill="url(#iAcE02d)" class="koj8teb_r"/></g><g filter="url(#iadFSac)"><path class="d7ohxlb0m"/><path fill="url(#i7f5OTc)" class="j_8b-3bfi"/></g><g filter="url(#iawLTjd)"><path class="sr2hw6zyj"/><path fill="url(#itbXg3l)" class="dhcu9eopb"/></g><g filter="url(#iLHlLoe)"><path fill="url(#iUd4E7m)" class="k2ax94brg"/><path fill="url(#iRV5bcd)" class="k2ax94brg"/><path fill="url(#igyTMNc)" class="k2ax94brg"/><path fill="url(#iKqb7ve)" class="k2ax94brg"/><path fill="url(#itSg49F)" class="k2ax94brg"/><path fill="url(#ijoEV4b)" class="k2ax94brg"/><path fill="url(#ix311lb)" class="k2ax94brg"/><path fill="url(#iCxPqOc)" class="k2ax94brg"/><path fill="url(#ixQZSmd)" class="k2ax94brg"/></g><path fill="url(#id084Gc)" class="k2ax94brg"/><g filter="url(#iPw3v6P)"><path class="gjg37o-si"/></g><path fill="url(#ivgzTEe)" class="cs4s5nqzd"/><path fill="url(#i61sAtc)" class="cs4s5nqzd"/><g filter="url(#iTsyUQR)"><path class="xqzy-pb-b"/></g><g filter="url(#i7O9SKe)"><path class="zw5j5tz7b"/></g><g filter="url(#ibbzRXc)"><path class="g-v29ub8g"/></g><g filter="url(#ixkChfd)"><path clip-rule="evenodd" class="oxtmm3bov"/></g><path class="pjep0ccsv"/><path fill="url(#iNQMXue)" class="v9-iaf48c"/><g filter="url(#iciUmpv)"><path class="qy75pwbto"/><path fill="url(#iavKzCE)" class="cs4s5nqzd"/><path fill="url(#imGSTue)" class="cs4s5nqzd"/><path fill="url(#i1hVoDe)" class="cs4s5nqzd"/><path fill="url(#iO3NPZd)" class="cs4s5nqzd"/></g><path class="yka3mun3y"/><g filter="url(#iqv4Jxe)"><path class="r627y3knv"/><path fill="url(#iZWIgJc)" class="jf611ut_v"/></g><g filter="url(#iQ3MeGu)"><path fill="url(#i99Ic3n)" class="ze2zbibwf"/></g><path class="t-qnx68mg"/><path fill="url(#iZ7u7Cc)" class="ljs5mcbsi"/><path class="yg46jyodv"/><g filter="url(#iuqjAwd)"><path fill="url(#iuZ26Wd)" class="zkep4n0kj"/></g><g filter="url(#i9CkZPd)"><ellipse transform="rotate(-32.076 13.33 12.06)" class="rkveklbfy"/><ellipse fill="url(#ijjXNoK)" transform="rotate(-32.076 13.33 12.06)" class="fsi6a2b6c"/></g><g filter="url(#icXzShg)"><path class="zir-0dbzc"/></g><g filter="url(#iWtNkud)"><path class="a-c4v2wkr"/></g><g filter="url(#iAHNVJb)"><path class="d3a4sbctm"/><path fill="url(#ih37Uud)" class="lkrq2ognz"/></g><g filter="url(#iu1j2Xd)"><path class="r8i4zibkb"/><path fill="url(#izMQOXu)" class="lvyln3byu"/><path fill="url(#ibvd3xb)" class="lvyln3byu"/></g><g filter="url(#i2Vs12b)"><path stroke="url(#iSlARpd)" class="g05tdtcqd"/></g><g filter="url(#iIzayze)"><path class="h-q0zqtfr"/></g><g filter="url(#iZkKchb)"><ellipse stroke="url(#ilQOTSb)" class="mxn-azb9t"/></g><ellipse class="pjwibpeww"/><defs><radialGradient id="i4YPUZd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34374 1.85938 -2.52303 -1.82335 5.651 12.178)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="qhfqembfy"/><stop offset="1" class="vzjrnw-cv"/></radialGradient><radialGradient id="iguenIe" cx="0" cy="0" r="1" gradientTransform="matrix(-.63638 2.0037 -2.32192 -.73745 3.968 12.542)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="qhfqembfy"/><stop offset="1" class="vzjrnw-cv"/></radialGradient><radialGradient id="ixj2c1f" cx="0" cy="0" r="1" gradientTransform="rotate(112.256 -2.403 8.162)scale(1.93501 2.72441)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="qhfqembfy"/><stop offset="1" class="vzjrnw-cv"/></radialGradient><radialGradient id="iwNuYbe" cx="0" cy="0" r="1" gradientTransform="matrix(-.73438 1.57812 -2.42466 -1.12832 4.557 14.428)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="qhfqembfy"/><stop offset="1" class="vzjrnw-cv"/></radialGradient><radialGradient id="i6LeXge" cx="0" cy="0" r="1" gradientTransform="matrix(-.52138 .86916 -1.0215 -.61276 6.873 11.255)" gradientUnits="userSpaceOnUse"><stop class="jxld5cbuj"/><stop offset="1" class="sye3wn7xw"/></radialGradient><radialGradient id="iMoU1rb" cx="0" cy="0" r="1" gradientTransform="matrix(1.71875 2.186 -.55483 .43624 5.089 11.647)" gradientUnits="userSpaceOnUse"><stop class="ruye5_bma"/><stop offset="1" class="m9mhbtnio"/></radialGradient><radialGradient id="iFbYzYd" cx="0" cy="0" r="1" gradientTransform="matrix(.85157 -.55469 .26705 .40998 26.089 11.505)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="cfz60ruqm"/><stop offset="1" class="e6new6blv"/></radialGradient><radialGradient id="iH1hBIb" cx="0" cy="0" r="1" gradientTransform="matrix(1.0788 .95928 -3.2774 3.68572 26.774 12.706)" gradientUnits="userSpaceOnUse"><stop offset=".715" class="zrx8b2rln"/><stop offset="1" class="awsv0y4ii"/></radialGradient><radialGradient id="iNFxTim" cx="0" cy="0" r="1" gradientTransform="rotate(-136.326 16.523 1.073)scale(1.45051 1.63903)" gradientUnits="userSpaceOnUse"><stop class="jhtwa6huv"/><stop offset="1" class="dpkf-rbcv"/></radialGradient><radialGradient id="i7dOrUk" cx="0" cy="0" r="1" gradientTransform="matrix(.45312 -.60937 .35181 .2616 28.409 11.755)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="lzb5fjb9e"/><stop offset="1" class="b7j-pnyza"/></radialGradient><radialGradient id="i4CqWOA" cx="0" cy="0" r="1" gradientTransform="rotate(45.859 -1.567 39.577)scale(1.46299 5.0306)" gradientUnits="userSpaceOnUse"><stop offset=".715" class="zrx8b2rln"/><stop offset="1" class="awsv0y4ii"/></radialGradient><radialGradient id="iFLp9wd" cx="0" cy="0" r="1" gradientTransform="matrix(-.98438 -1.01562 1.32742 -1.28659 28.636 13.553)" gradientUnits="userSpaceOnUse"><stop class="jhtwa6huv"/><stop offset="1" class="dpkf-rbcv"/></radialGradient><radialGradient id="iiGZWMc" cx="0" cy="0" r="1" gradientTransform="matrix(.42795 -.66693 .3655 .23453 29.47 12.098)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="lzb5fjb9e"/><stop offset="1" class="b7j-pnyza"/></radialGradient><radialGradient id="igMrv3d" cx="0" cy="0" r="1" gradientTransform="matrix(1.10937 .9375 -3.17994 3.76294 27.779 14.01)" gradientUnits="userSpaceOnUse"><stop offset=".715" class="zrx8b2rln"/><stop offset="1" class="awsv0y4ii"/></radialGradient><radialGradient id="ik8LFxi" cx="0" cy="0" r="1" gradientTransform="matrix(-.9375 -1.15624 1.30176 -1.0555 28.48 14.506)" gradientUnits="userSpaceOnUse"><stop class="jhtwa6huv"/><stop offset="1" class="dpkf-rbcv"/></radialGradient><radialGradient id="iJbrkVc" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 -.5 .29258 .32915 29.557 13.1)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="lzb5fjb9e"/><stop offset="1" class="b7j-pnyza"/></radialGradient><radialGradient id="i4sG3Or" cx="0" cy="0" r="1" gradientTransform="matrix(1.11164 .82615 -2.72127 3.66166 27.462 14.898)" gradientUnits="userSpaceOnUse"><stop offset=".715" class="zrx8b2rln"/><stop offset="1" class="awsv0y4ii"/></radialGradient><radialGradient id="iyutuBF" cx="0" cy="0" r="1" gradientTransform="rotate(-141.412 16.916 2.707)scale(1.38306 1.52547)" gradientUnits="userSpaceOnUse"><stop class="jhtwa6huv"/><stop offset="1" class="dpkf-rbcv"/></radialGradient><radialGradient id="iU6YIPe" cx="0" cy="0" r="1" gradientTransform="matrix(.57812 -.5625 .3368 .34616 29.276 14.162)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="lzb5fjb9e"/><stop offset="1" class="b7j-pnyza"/></radialGradient><radialGradient id="iTtbBRb" cx="0" cy="0" r="1" gradientTransform="matrix(-.25483 4.31746 -5.39337 -.31833 15.567 14.91)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iuRTzAb" cx="0" cy="0" r="1" gradientTransform="rotate(141.843 3.817 9.915)scale(3.2703 4.29692)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="igF5Izc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.10961 1.69283 -1.29985 -.85203 11.15 13.081)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iPM0TrG" cx="0" cy="0" r="1" gradientTransform="rotate(117.268 2.32 9.06)scale(2.32767 1.63964)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="i8J2VFd" cx="0" cy="0" r="1" gradientTransform="matrix(1.46762 2.35876 -3.27433 2.03729 11.827 5.224)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="igfDTue" cx="0" cy="0" r="1" gradientTransform="rotate(130.837 8.876 8.012)scale(1.9171 2.67911)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="itnM06c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6927 .6289 -1.31153 -3.53 22.664 11.232)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iu657Hb" cx="0" cy="0" r="1" gradientTransform="rotate(161.802 10.006 9.028)scale(2.72964 3.47715)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iFaaICc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.02923 -2.42413 1.91735 -.81406 19.894 9.138)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="i3HhqFe" cx="0" cy="0" r="1" gradientTransform="matrix(1.4214 .04533 -.07344 2.30307 9.857 12.13)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iGEoCve" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.94297 -2.39063 0 26.006 16.154)" gradientUnits="userSpaceOnUse"><stop class="j0u7-u3qa"/><stop offset="1" class="w06d_xbwd"/></radialGradient><radialGradient id="iClJVfd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.24766 -2.29189 0 7.171 16.286)" gradientUnits="userSpaceOnUse"><stop class="hk2gombwq"/><stop offset="1" class="zgf54gbaa"/></radialGradient><radialGradient id="i8OkU2j" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.4411 10.6867 0 19.724 29.139)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="bfh6fzlxi"/><stop offset="1" class="lea4hbl2x"/></radialGradient><radialGradient id="iOuDGRd" cx="0" cy="0" r="1" gradientTransform="rotate(130.485 .253 12.094)scale(4.64639 1.15364)" gradientUnits="userSpaceOnUse"><stop class="k9011xajc"/><stop offset="1" class="upmwye1mi"/></radialGradient><radialGradient id="i8DP3Bc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5323 -4.48916 1.47345 -.83116 24.319 26.815)" gradientUnits="userSpaceOnUse"><stop class="jlublfbcv"/><stop offset="1" class="h3d7w4j4j"/></radialGradient><radialGradient id="iknTBJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.46944 -4.08022 0 26.817 16.7)" gradientUnits="userSpaceOnUse"><stop class="vio74z7fz"/><stop offset="1" class="ey8rcibsm"/></radialGradient><radialGradient id="iW6mndb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.2344 3.40893 -.52728 -.3456 9.522 19.878)" gradientUnits="userSpaceOnUse"><stop class="cgtm3g8-v"/><stop offset="1" class="dol2bxb1e"/></radialGradient><radialGradient id="itIje2d" cx="0" cy="0" r="1" gradientTransform="matrix(-5.37502 3.24997 -1.62756 -2.69176 14.396 17.027)" gradientUnits="userSpaceOnUse"><stop class="p1da4obcx"/><stop offset="1" class="rqpemmbby"/></radialGradient><radialGradient id="i2JIfIb" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 6.13908 -2.38453 1.00746 22.428 16.7)" gradientUnits="userSpaceOnUse"><stop class="xy4qbsbbs"/><stop offset="1" class="loe_0kbli"/></radialGradient><radialGradient id="iOPVX4b" cx="0" cy="0" r="1" gradientTransform="matrix(3.09375 2.20253 -3.34177 4.69396 14.381 18.003)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="jzh4i0bqe"/><stop offset="1" class="ixgzu8b8m"/></radialGradient><radialGradient id="iwbzvUb" cx="0" cy="0" r="1" gradientTransform="matrix(2.25744 -1.23108 1.5031 2.75623 19.498 12.68)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="iAcE02d" cx="0" cy="0" r="1" gradientTransform="matrix(1.28448 .60195 -.17018 .36314 20.32 10.62)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="i7f5OTc" cx="0" cy="0" r="1" gradientTransform="matrix(1.40857 -.2084 .1629 1.1011 19.806 12.349)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="itbXg3l" cx="0" cy="0" r="1" gradientTransform="rotate(175.836 5.448 6.635)scale(.99308)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="iUd4E7m" cx="0" cy="0" r="1" gradientTransform="matrix(-5.8955 3.25678 -4.35914 -7.89104 18.324 11.844)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="iRV5bcd" cx="0" cy="0" r="1" gradientTransform="rotate(152.087 7.196 8.533)scale(2.24017 1.56002)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="igyTMNc" cx="0" cy="0" r="1" gradientTransform="rotate(-75.994 18.736 .147)scale(3.88827 4.93349)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="iKqb7ve" cx="0" cy="0" r="1" gradientTransform="matrix(-.70178 7.0035 -8.75429 -.87722 16.573 11.579)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="ermiffb8a"/><stop offset="1" class="d5lrpr21j"/></radialGradient><radialGradient id="itSg49F" cx="0" cy="0" r="1" gradientTransform="matrix(.42787 5.87985 -5.91134 .43016 15.423 12.422)" gradientUnits="userSpaceOnUse"><stop offset=".911" class="plx9t1yez"/><stop offset="1" class="tcn1mccqj"/></radialGradient><radialGradient id="ijoEV4b" cx="0" cy="0" r="1" gradientTransform="rotate(164.735 7.822 7.94)scale(6.6183 11.3947)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="ix311lb" cx="0" cy="0" r="1" gradientTransform="matrix(-.07854 -1.07939 1.3247 -.09639 17.772 11.49)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="iCxPqOc" cx="0" cy="0" r="1" gradientTransform="matrix(-.08959 -1.2311 1.41092 -.10267 13.65 11.573)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="ixQZSmd" cx="0" cy="0" r="1" gradientTransform="rotate(100.93 4.506 11.604)scale(3.14299 2.51491)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="id084Gc" cx="0" cy="0" r="1" gradientTransform="rotate(175.838 10.017 6.72)scale(1.20874 6.06172)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="i61sAtc" cx="0" cy="0" r="1" gradientTransform="rotate(141.368 5.709 9.49)scale(1.56421 1.87994)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="wln98ypvp"/><stop offset="1" class="p13423bzd"/></radialGradient><radialGradient id="iNQMXue" cx="0" cy="0" r="1" gradientTransform="rotate(85.838 2.48 15.426)scale(.763 1.21364)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iavKzCE" cx="0" cy="0" r="1" gradientTransform="matrix(-.56673 -1.88615 .5813 -.17466 16.5 13.67)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iO3NPZd" cx="0" cy="0" r="1" gradientTransform="matrix(-.73105 .05324 -.01488 -.20438 16.29 13.884)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iZWIgJc" cx="0" cy="0" r="1" gradientTransform="rotate(-131.973 11.395 2.071)scale(.3554 .4893)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iZ7u7Cc" cx="0" cy="0" r="1" gradientTransform="matrix(.05538 .761 -1.21044 .08808 13.591 12.132)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ijjXNoK" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.74 -.376)scale(.46423 .55802)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ih37Uud" cx="0" cy="0" r="1" gradientTransform="matrix(.99569 -2.67064 1.36623 .50937 10.186 10.38)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="izMQOXu" cx="0" cy="0" r="1" gradientTransform="rotate(111.522 6.77 8.251)scale(4.58271 7.49247)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="ibvd3xb" cx="0" cy="0" r="1" gradientTransform="matrix(-.10398 1.29675 -2.78988 -.2237 15.36 5.442)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="ilQOTSb" cx="0" cy="0" r="1" gradientTransform="matrix(.141 -.95434 .42047 .06212 15.797 16.177)" gradientUnits="userSpaceOnUse"><stop class="iwubtczjk"/><stop offset="1" class="k-gh6ccuj"/></radialGradient><filter id="iqk54Ok" width="3.052" height="2.539" x="3.379" y="11.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4186" stdDeviation=".15"/></filter><filter id="iVGLHDd" width="3.127" height="2.723" x="2.3" y="11.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4186" stdDeviation=".15"/></filter><filter id="iAqenOc" width="3.267" height="2.534" x="2.23" y="12.779" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4186" stdDeviation=".15"/></filter><filter id="iaUUyZc" width="3.408" height="5.156" x="23.611" y="11.255" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.32549 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4186"/></filter><filter id="ijAMJub" width="3.431" height="2.258" x="2.528" y="13.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4186" stdDeviation=".15"/></filter><filter id="i7EHNju" width="2.543" height="1.191" x="5.706" y="15.239" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4186" stdDeviation=".15"/></filter><filter id="i6s6yHm" width="2.847" height=".977" x="25.079" y="15.073" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4186" stdDeviation=".15"/></filter><filter id="iU50hcD" width="14.578" height="15.146" x="8.626" y="3.786" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4186"/></filter><filter id="iBNq9Sd" width="23.107" height="13.423" x="4.427" y="16.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.498039 0 0 0 0 0.278431 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4186"/></filter><filter id="iwzAv5W" width="8.199" height="8.945" x="4.912" y="16.471" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4186" stdDeviation=".75"/></filter><filter id="icXi6lT" width="7.102" height="7.913" x="20.265" y="17.003" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4186" stdDeviation=".625"/></filter><filter id="isFIm3c" width="3.956" height="6.956" x="9.012" y="19.097" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4186" stdDeviation=".25"/></filter><filter id="iLYJ9Fd" width="3.177" height="3.027" x="9.771" y="11.35" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4186"/></filter><filter id="iUYrA0d" width="3.027" height="3.277" x="18.693" y="10.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4186"/></filter><filter id="iadFSac" width="3.02" height="3.02" x="18.697" y="10.704" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4186" stdDeviation=".25"/></filter><filter id="iawLTjd" width="2.52" height="2.52" x="10.042" y="11.601" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4186" stdDeviation=".125"/></filter><filter id="iLHlLoe" width="9.665" height="10.135" x="10.771" y="8.122" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4186"/></filter><filter id="iPw3v6P" width="2.763" height="3.55" x="14.257" y="11.574" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4186" stdDeviation=".25"/></filter><filter id="iTsyUQR" width="2.82" height="1.174" x="16.511" y="11.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4186"/></filter><filter id="i7O9SKe" width="2.837" height="1.25" x="11.932" y="11.401" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4186"/></filter><filter id="ibbzRXc" width="2.292" height="1.134" x="11.97" y="10.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4186"/></filter><filter id="ixkChfd" width="2.336" height=".952" x="17.029" y="9.717" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4186"/></filter><filter id="iciUmpv" width="2.263" height="3.045" x="14.65" y="11.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4186" stdDeviation=".125"/></filter><filter id="iqv4Jxe" width=".731" height=".69" x="16.993" y="11.428" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4186" stdDeviation=".05"/></filter><filter id="iQ3MeGu" width=".872" height=".891" x="17.78" y="11.441" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4186" stdDeviation=".1"/></filter><filter id="iuqjAwd" width=".967" height="1.008" x="13.608" y="11.683" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4186" stdDeviation=".1"/></filter><filter id="i9CkZPd" width=".851" height=".7" x="12.905" y="11.711" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4186" stdDeviation=".05"/></filter><filter id="icXzShg" width="2.181" height=".871" x="17.036" y="9.824" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4186" stdDeviation=".1"/></filter><filter id="iWtNkud" width="2.134" height="1.049" x="11.946" y="10.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4186" stdDeviation=".1"/></filter><filter id="iAHNVJb" width="4.002" height="4.559" x="9.436" y="6.235" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.262745 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4186"/><feGaussianBlur result="effect2_foregroundBlur_4002_4186" stdDeviation=".2"/></filter><filter id="iu1j2Xd" width="8.527" height="5.03" x="12.243" y="5.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4186"/><feGaussianBlur result="effect2_foregroundBlur_4002_4186" stdDeviation=".125"/></filter><filter id="i2Vs12b" width="1.228" height="2.167" x="12.22" y="6.304" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4186" stdDeviation=".1"/></filter><filter id="iIzayze" width="6.704" height="3.631" x="14.521" y="6.364" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4186" stdDeviation=".5"/></filter><filter id="iZkKchb" width="1.709" height="1.724" x="15.146" y="14.699" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4186" stdDeviation=".05"/></filter><linearGradient id="i4kzbsd" x1="3.575" x2="5.779" y1="12.148" y2="12.894" gradientUnits="userSpaceOnUse"><stop class="tl886ijok"/><stop offset="1" class="mqcv30bps"/></linearGradient><linearGradient id="itziHcb" x1="4.079" x2="6.235" y1="11.944" y2="14.093" gradientUnits="userSpaceOnUse"><stop class="yq63iy86j"/><stop offset="1" class="fpybawbbv"/></linearGradient><linearGradient id="iUxX4Ed" x1="2.48" x2="4.518" y1="12.528" y2="13.091" gradientUnits="userSpaceOnUse"><stop class="tl886ijok"/><stop offset="1" class="mqcv30bps"/></linearGradient><linearGradient id="ipW0ApS" x1="3.012" x2="5.422" y1="12.213" y2="14.427" gradientUnits="userSpaceOnUse"><stop class="yq63iy86j"/><stop offset="1" class="fpybawbbv"/></linearGradient><linearGradient id="iEdDfWA" x1="2.527" x2="4.769" y1="13.465" y2="14.263" gradientUnits="userSpaceOnUse"><stop class="tl886ijok"/><stop offset="1" class="mqcv30bps"/></linearGradient><linearGradient id="iHb6W2c" x1="2.936" x2="5.527" y1="13.204" y2="15.204" gradientUnits="userSpaceOnUse"><stop class="yq63iy86j"/><stop offset="1" class="fpybawbbv"/></linearGradient><linearGradient id="i99xcDe" x1="2.84" x2="5.015" y1="14.417" y2="15.298" gradientUnits="userSpaceOnUse"><stop class="tl886ijok"/><stop offset="1" class="mqcv30bps"/></linearGradient><linearGradient id="ieJW2Cs" x1="8.571" x2="7.73" y1="15.488" y2="15.488" gradientUnits="userSpaceOnUse"><stop offset=".005" class="eivezvbjc"/><stop offset="1" class="dunk4xw2z"/></linearGradient><linearGradient id="i77mk8d" x1="5.667" x2="5.667" y1="16.411" y2="15.631" gradientUnits="userSpaceOnUse"><stop class="vzjrnw-cv"/><stop offset="1" class="qhfqembfy"/></linearGradient><linearGradient id="iXI89qd" x1="23.611" x2="24.409" y1="15.387" y2="15.387" gradientUnits="userSpaceOnUse"><stop class="jcizzuyvv"/><stop offset="1" class="n2lvbybdz"/></linearGradient><linearGradient id="iMMUQBc" x1="28.207" x2="25.514" y1="13.645" y2="13.604" gradientUnits="userSpaceOnUse"><stop class="h6_tp9bfn"/><stop offset="1" class="yd1eqqb2n"/></linearGradient><linearGradient id="ivYk4Ob" x1="29.28" x2="26.736" y1="14.167" y2="14.133" gradientUnits="userSpaceOnUse"><stop class="h6_tp9bfn"/><stop offset="1" class="yd1eqqb2n"/></linearGradient><linearGradient id="irTFbTd" x1="29.253" x2="26.483" y1="14.928" y2="14.883" gradientUnits="userSpaceOnUse"><stop class="h6_tp9bfn"/><stop offset="1" class="yd1eqqb2n"/></linearGradient><linearGradient id="iccndpb" x1="28.939" x2="26.164" y1="15.706" y2="15.656" gradientUnits="userSpaceOnUse"><stop class="h6_tp9bfn"/><stop offset="1" class="yd1eqqb2n"/></linearGradient><linearGradient id="iuJQnOe" x1="3.224" x2="6.032" y1="14.232" y2="15.913" gradientUnits="userSpaceOnUse"><stop class="yq63iy86j"/><stop offset="1" class="fpybawbbv"/></linearGradient><linearGradient id="iYt1nOd" x1="8.057" x2="7.268" y1="15.739" y2="14.691" gradientUnits="userSpaceOnUse"><stop class="kmsi1fbim"/><stop offset="1" class="h205h2lxp"/></linearGradient><linearGradient id="ioLkjMT" x1="19.607" x2="14.084" y1="5.701" y2="17.988" gradientUnits="userSpaceOnUse"><stop class="c1nwhtznm"/><stop offset="1" class="ogqxd-bue"/></linearGradient><linearGradient id="iti7mEe" x1="23.465" x2="23.951" y1="17.136" y2="17.128" gradientUnits="userSpaceOnUse"><stop class="ccx8jtb2j"/><stop offset="1" class="p1-vnac8k"/></linearGradient><linearGradient id="iWYle9c" x1="9.662" x2="12.662" y1="25.872" y2="20.216" gradientUnits="userSpaceOnUse"><stop class="g8oi3mbhp"/><stop offset="1" class="ynqid7b9h"/></linearGradient><linearGradient id="ieYAPod" x1="9.829" x2="10.992" y1="13.051" y2="12.966" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="ivgzTEe" x1="15.896" x2="15.886" y1="14.511" y2="14.38" gradientUnits="userSpaceOnUse"><stop class="p13423bzd"/><stop offset="1" class="wln98ypvp"/></linearGradient><linearGradient id="imGSTue" x1="14.889" x2="15.77" y1="13.856" y2="13.792" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="i1hVoDe" x1="15.824" x2="15.783" y1="14.541" y2="13.969" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="i99Ic3n" x1="18.418" x2="18.137" y1="11.831" y2="12.034" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iuZ26Wd" x1="14.292" x2="14.011" y1="12.131" y2="12.334" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iSlARpd" x1="12.544" x2="13.142" y1="6.927" y2="8.084" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-shrugging-medium-dark" /></template>
<style>
.a-c4v2wkr {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.78 10.444c-.308-.052-1.057.04-1.534.436");
}

.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.awsv0y4ii {
  stop-color: var(--svg-color--6f4738, #6F4738);
}

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
}

.b7j-pnyza {
  stop-color: var(--svg-color--876d65, #876D65);
  stop-opacity: 0;
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.bfh6fzlxi {
  stop-color: var(--svg-color--a27be8, #A27BE8);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.c1nwhtznm {
  stop-color: var(--svg-color--45363a, #45363A);
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.ccx8jtb2j {
  stop-color: var(--svg-color--493577, #493577);
}

.cfz60ruqm {
  stop-color: var(--svg-color--93776d, #93776D);
}

.cgtm3g8-v {
  stop-color: var(--svg-color--9a71e1, #9A71E1);
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crj44uotj {
  stop-color: var(--svg-color--996b5e, #996B5E);
}

.cs4s5nqzd {
  d: path("m15.296 12.23l-.383 1.631a.507.507 0 0 0 .536.62l.738-.053a.51.51 0 0 0 .44-.692l-.614-1.558c-.133-.345-.631-.309-.717.052");
}

.cuh1jzbvw {
  d: path("M11.394 14.372a1.513 1.513 0 1 0-.22-3.018a1.513 1.513 0 0 0 .22 3.018");
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.d1lp4wbpb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M3.879 11.99c.196.501 1.017 1.387 2.052 1.538");
}

.d3a4sbctm {
  fill: var(--svg-color--2a191e, #2A191E);
  d: path("M10.516 7.272c.49-.6 1.493-.674 1.963-.624l.46 1.183c-.24-.02-.445.08-.61.266c-.335 1.213-1.733 1.97-2.39 2.197c-.241-1.39-.06-2.24.577-3.022");
}

.d5lrpr21j {
  stop-color: var(--svg-color--793e68, #793E68);
}

.d7ohxlb0m {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M20.28 13.221a1.01 1.01 0 1 0-.147-2.015a1.01 1.01 0 0 0 .147 2.015");
}

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
  stop-opacity: 0;
}

.dd_oh5bup {
  fill: var(--svg-color--6e5147, #6E5147);
  d: path("M5.83 11.41a.75.75 0 0 1 1.051.138l.805 1.047c.369.48.57 1.07.57 1.675v2.14h-3.26v-2.697h1.627a1.3 1.3 0 0 0-.128-.204l-.804-1.047a.75.75 0 0 1 .137-1.052");
}

.dhcu9eopb {
  d: path("M11.375 13.869a1.01 1.01 0 1 0-.147-2.015a1.01 1.01 0 0 0 .147 2.015");
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.dol2bxb1e {
  stop-color: var(--svg-color--9a71e1, #9A71E1);
  stop-opacity: 0;
}

.dpkf-rbcv {
  stop-color: var(--svg-color--6a413e, #6A413E);
  stop-opacity: 0;
}

.dunk4xw2z {
  stop-color: var(--svg-color--725953, #725953);
  stop-opacity: 0;
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e6new6blv {
  stop-color: var(--svg-color--93776d, #93776D);
  stop-opacity: 0;
}

.eivezvbjc {
  stop-color: var(--svg-color--725953, #725953);
}

.ejudldebc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M2.8 12.27c.196.501.845 1.458 2.127 1.723");
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.ermiffb8a {
  stop-color: var(--svg-color--793e68, #793E68);
  stop-opacity: 0;
}

.evur8nbpn {
  stroke: var(--svg-color--94716a, #94716A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M25.48 15.645h1.515a.7.7 0 0 0 .531-.172");
}

.ey8rcibsm {
  stop-color: var(--svg-color--a980f0, #A980F0);
  stop-opacity: 0;
}

.fpybawbbv {
  stop-color: var(--svg-color--856661, #856661);
  stop-opacity: 0;
}

.fsi6a2b6c {
  cx: 13.33px;
  cy: 12.061px;
  rx: 0.366px;
  ry: 0.185px;
}

.ft5dv1b6b {
  fill: none;
}

.ftwkfbb_k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M6.206 15.739h.998c.226 0 .443.09.603.25v0");
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
}

.g-v29ub8g {
  fill: var(--svg-color--352827, #352827);
  d: path("m12.37 11.107l-.003.003a.252.252 0 0 1-.29-.413h.001l.003-.002l.008-.006l.03-.02q.037-.024.104-.062c.09-.051.217-.117.374-.18a2.64 2.64 0 0 1 1.238-.193a.252.252 0 0 1-.051.502a2.1 2.1 0 0 0-1 .16a2.6 2.6 0 0 0-.413.211");
}

.g05tdtcqd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.52 6.604c.039.227.3 1.069.628 1.567");
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.g8oi3mbhp {
  stop-color: var(--svg-color--7346c5, #7346C5);
}

.gcfqr7bfg {
  stop-color: var(--svg-color--714350, #714350);
  stop-opacity: 0;
}

.geqjdr7rf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M2.73 13.279c.239.483.967 1.38 2.267 1.534");
}

.gjg37o-si {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m15.296 12.36l-.526 1.642a.507.507 0 0 0 .536.62l.738-.053a.51.51 0 0 0 .44-.692l-.614-1.558c-.132-.345-.488-.32-.574.042");
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gqxi-n8lm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M9.662 25.404c.177-1.146.956-3.882 2.656-5.657");
}

.h-q0zqtfr {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m17.65 8.457l-1.319.343a.647.647 0 1 1-.21-1.271l2.196-.16c1.298-.094 1.823 1.183 1.908 1.626a2.96 2.96 0 0 0-2.574-.538");
}

.h205h2lxp {
  stop-color: var(--svg-color--735450, #735450);
  stop-opacity: 0;
}

.h3d7w4j4j {
  stop-color: var(--svg-color--783edb, #783EDB);
  stop-opacity: 0;
}

.h6_tp9bfn {
  stop-color: var(--svg-color--7c5e52, #7C5E52);
}

.hk2gombwq {
  stop-color: var(--svg-color--8364b6, #8364B6);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.iwubtczjk {
  stop-color: var(--svg-color--866166, #866166);
}

.ixgzu8b8m {
  stop-color: var(--svg-color--8f6560, #8F6560);
}

.j_8b-3bfi {
  d: path("M20.28 13.221a1.01 1.01 0 1 0-.147-2.015a1.01 1.01 0 0 0 .147 2.015");
}

.j0u7-u3qa {
  stop-color: var(--svg-color--9d7ad7, #9D7AD7);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jcizzuyvv {
  stop-color: var(--svg-color--734840, #734840);
}

.jf611ut_v {
  d: path("M17.605 11.568c.065.076-.052.182-.186.298s-.233.198-.299.123s-.01-.23.124-.347s.296-.15.361-.074");
}

.jhtwa6huv {
  stop-color: var(--svg-color--6a413e, #6A413E);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jlublfbcv {
  stop-color: var(--svg-color--783edb, #783EDB);
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.jxld5cbuj {
  stop-color: var(--svg-color--775b50, #775B50);
}

.jzh4i0bqe {
  stop-color: var(--svg-color--5e383b, #5E383B);
}

.k-gh6ccuj {
  stop-color: var(--svg-color--866166, #866166);
  stop-opacity: 0;
}

.k2ax94brg {
  d: path("m10.821 11.706l.012-.001l-.028-.248l-.03-.287c-.046-.89.448-1.273.661-1.404l.047-.023q.024-.013.046-.022a2.17 2.17 0 0 0 1.032-1.24l.064-.187a.248.248 0 0 1 .43-.08a3.63 3.63 0 0 0 3.105 1.352l3.02-.22c.169-.012 1.021.009 1.156 1.173l.099 2.89c.075 2.637-1.85 4.552-4.355 4.734s-4.687-1.433-4.994-4.054z");
}

.k9011xajc {
  stop-color: var(--svg-color--895fc7, #895FC7);
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kek0nw1ry {
  fill-rule: evenodd;
  d: path("M29.589 12.94a.7.7 0 0 0-.98.143l-.086.118c-.302.42-.763 1.061-1.779 1.061a.7.7 0 1 0 0 1.4c1.776 0 2.637-1.24 2.925-1.654q.036-.054.062-.087a.7.7 0 0 0-.142-.98");
}

.kmsi1fbim {
  stop-color: var(--svg-color--735450, #735450);
}

.koj8teb_r {
  d: path("M20.317 13.723a1.513 1.513 0 1 0-.22-3.018a1.513 1.513 0 0 0 .22 3.018");
}

.l__dw9bpv {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
  stop-opacity: 0;
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lea4hbl2x {
  stop-color: var(--svg-color--7954b7, #7954B7);
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljs5mcbsi {
  d: path("M13.557 11.685a.84.84 0 0 0-.73 1.116l1.617-.117a1 1 0 0 0 .015-.223a.845.845 0 0 0-.902-.776");
}

.lkrq2ognz {
  d: path("M10.516 7.272c.49-.6 1.493-.674 1.963-.624l.46 1.183c-.24-.02-.445.08-.61.266c-.335 1.213-1.733 1.97-2.39 2.197c-.241-1.39-.06-2.24.577-3.022");
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.loe_0kbli {
  stop-color: var(--svg-color--563a92, #563A92);
  stop-opacity: 0;
}

.lvyln3byu {
  d: path("M14.581 5.277c-1.08-.157-1.956.972-2.037 1.373c1.228 3.253 3.71 2.89 6.155 2.437c1.463-.272 1.672.389 1.821.705c-.268-3.689-3.455-4.153-5.911-4.511z");
}

.lzb5fjb9e {
  stop-color: var(--svg-color--876d65, #876D65);
}

.m-59bub6h {
  fill-rule: evenodd;
  d: path("M29.557 11.919a.7.7 0 0 0-.978.157q-.05.071-.115.168c-.261.39-.92 1.113-1.732 1.46c-.356.153-.503.45-.32.876c.152.355.733.502 1.088.35c1.246-.533 1.935-1.603 2.155-1.945l.059-.089a.7.7 0 0 0-.157-.977");
}

.m9mhbtnio {
  stop-color: var(--svg-color--673e35, #673E35);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mqcv30bps {
  stop-color: var(--svg-color--715146, #715146);
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.mxn-azb9t {
  cx: 16px;
  cy: 15.561px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  rx: 0.654px;
  ry: 0.662px;
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n2lvbybdz {
  stop-color: var(--svg-color--734840, #734840);
  stop-opacity: 0;
}

.nn7f1_b3w {
  stroke: var(--svg-color--a57cec, #A57CEC);
  stroke-linecap: square;
  d: path("M25.617 18.753v3.41a1 1 0 0 1-1.567.824l-1.84-1.266");
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.oc3yxvrel {
  fill: var(--svg-color--816052, #816052);
  d: path("M26.037 11.41a.75.75 0 0 0-1.052.138l-.804 1.047a2.75 2.75 0 0 0-.57 1.675v2.14h3.258v-2.697h-1.626a1.3 1.3 0 0 1 .127-.204l.805-1.047a.75.75 0 0 0-.138-1.052");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ogqxd-bue {
  stop-color: var(--svg-color--1c151f, #1C151F);
}

.olqyf7fmb {
  stop-color: var(--svg-color--875e5e, #875E5E);
}

.op6qopbgt {
  d: path("M4.96 16.404a.25.25 0 0 1 .25-.25h2.93a.25.25 0 0 1 .25.25v1.13H4.96z");
}

.opgioqbtx {
  stop-color: var(--svg-color--805c54, #805C54);
  stop-opacity: 0;
}

.osxg47drp {
  stop-color: var(--svg-color--743f5a, #743F5A);
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.oxtmm3bov {
  fill: var(--svg-color--352827, #352827);
  fill-rule: evenodd;
  d: path("m19.026 10.192l-.113.225za.252.252 0 0 1-.227.45l-.004-.002l-.022-.01l-.088-.037a3 3 0 0 0-.33-.103a2.1 2.1 0 0 0-1.012-.013a.252.252 0 1 1-.124-.49c.475-.12.927-.066 1.253.012a3 3 0 0 1 .54.186l.01.004l.003.002z");
}

.p1-vnac8k {
  stop-color: var(--svg-color--493577, #493577);
  stop-opacity: 0;
}

.p13423bzd {
  stop-color: var(--svg-color--693b40, #693B40);
}

.p1da4obcx {
  stop-color: var(--svg-color--362457, #362457);
}

.p88c31myn {
  stop-color: var(--svg-color--815a5b, #815A5B);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pi7duoxhr {
  d: path("M26.895 16.404a.25.25 0 0 0-.25-.25h-2.93a.25.25 0 0 0-.25.25v1.317h3.43z");
}

.pjep0ccsv {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.83 11.118c.612-.045 1.16.34 1.343.9a.258.258 0 0 1-.228.338l-2.093.152a.216.216 0 0 1-.231-.24a1.31 1.31 0 0 1 1.209-1.15");
}

.pjwibpeww {
  cx: 16px;
  cy: 15.561px;
  fill: var(--svg-color--87014d, #87014D);
  rx: 0.654px;
  ry: 0.662px;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.plx9t1yez {
  stop-color: var(--svg-color--885485, #885485);
  stop-opacity: 0;
}

.pv6p8qbkg {
  d: path("M5.83 11.41a.75.75 0 0 1 1.051.138l.805 1.047c.369.48.57 1.07.57 1.675v2.14h-3.26v-2.697h1.627a1.3 1.3 0 0 0-.128-.204l-.804-1.047a.75.75 0 0 1 .137-1.052");
}

.q1exkrh0e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M3.029 14.33c.293.451 1.121 1.257 2.431 1.257");
}

.qhfqembfy {
  stop-color: var(--svg-color--734251, #734251);
  stop-opacity: 0;
}

.qmfslybba {
  fill-rule: evenodd;
  d: path("M29.276 13.972a.7.7 0 0 0-.98.142c-.18.242-.653.84-1.872.84a.7.7 0 1 0 0 1.4c1.827 0 2.667-.965 2.994-1.402a.7.7 0 0 0-.142-.98");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.qy75pwbto {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m15.296 12.23l-.383 1.631a.507.507 0 0 0 .536.62l.738-.053a.51.51 0 0 0 .44-.692l-.614-1.558c-.133-.345-.631-.309-.717.052");
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r627y3knv {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.605 11.568c.065.076-.052.182-.186.298s-.233.198-.299.123s-.01-.23.124-.347s.296-.15.361-.074");
}

.r8i4zibkb {
  fill: var(--svg-color--2f1920, #2F1920);
  d: path("M14.581 5.277c-1.08-.157-1.956.972-2.037 1.373c1.228 3.253 3.71 2.89 6.155 2.437c1.463-.272 1.672.389 1.821.705c-.268-3.689-3.455-4.153-5.911-4.511z");
}

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.rc5cp_z9s {
  d: path("M9.287 20.632a.25.25 0 0 1-.376-.216v-2.563a.6.6 0 0 0-.6-.6H5.027a.6.6 0 0 0-.6.6v4.286c-.005.849.112 2.507 1.484 3.382c1.149.733 2.5.57 3.214.348c.1-.032.208.041.208.147v3.707c0 .083.067.15.15.15h12.994a.15.15 0 0 0 .15-.15v-3.707c0-.106.108-.18.209-.147c.712.222 2.064.385 3.213-.348c1.372-.875 1.49-2.533 1.484-3.382v-4.286a.6.6 0 0 0-.6-.6H23.65a.6.6 0 0 0-.6.6v2.563a.25.25 0 0 1-.375.216L15.98 16.7z");
}

.rj-4hxb-k {
  d: path("M26.037 11.41a.75.75 0 0 0-1.052.138l-.804 1.047a2.75 2.75 0 0 0-.57 1.675v2.14h3.258v-2.697h-1.626a1.3 1.3 0 0 1 .127-.204l.805-1.047a.75.75 0 0 0-.138-1.052");
}

.rkveklbfy {
  cx: 13.33px;
  cy: 12.061px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.366px;
  ry: 0.185px;
}

.rqpemmbby {
  stop-color: var(--svg-color--362457, #362457);
  stop-opacity: 0;
}

.ruilo6-op {
  fill-rule: evenodd;
  d: path("M28.518 11.602a.7.7 0 0 0-.978.157a2 2 0 0 0-.115.183l-.006.01v.002a5 5 0 0 1-.105.174c-.077.12-.171.249-.294.37c-.233.228-.608.468-1.267.5a.7.7 0 1 0 .068 1.398c1.025-.05 1.718-.447 2.179-.899c.223-.219.382-.44.495-.617a6 6 0 0 0 .178-.298l.002-.002a.7.7 0 0 0-.157-.978");
}

.ruye5_bma {
  stop-color: var(--svg-color--673e35, #673E35);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sr2hw6zyj {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M11.375 13.869a1.01 1.01 0 1 0-.147-2.015a1.01 1.01 0 0 0 .147 2.015");
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.sye3wn7xw {
  stop-color: var(--svg-color--775b50, #775B50);
  stop-opacity: 0;
}

.t-qnx68mg {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.344 11.444a1.31 1.31 0 0 0-1.198 1.085a.258.258 0 0 0 .274.302l2.093-.153a.216.216 0 0 0 .194-.27a1.32 1.32 0 0 0-1.363-.964");
}

.t9k87pm2r {
  stop-color: var(--svg-color--875555, #875555);
}

.tcn1mccqj {
  stop-color: var(--svg-color--885485, #885485);
}

.tl886ijok {
  stop-color: var(--svg-color--6e5147, #6E5147);
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.uj7hgsb3u {
  stop-color: var(--svg-color--815a5b, #815A5B);
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.upmwye1mi {
  stop-color: var(--svg-color--8358c9, #8358C9);
  stop-opacity: 0;
}

.us02a8j1k {
  fill-rule: evenodd;
  d: path("M2.278 12.94a.7.7 0 0 1 .98.143l.086.118c.301.42.763 1.061 1.778 1.061a.7.7 0 1 1 0 1.4c-1.775 0-2.636-1.24-2.924-1.654l-.062-.087a.7.7 0 0 1 .142-.98");
}

.v5txmjb-r {
  fill-rule: evenodd;
  d: path("M2.59 13.972a.7.7 0 0 1 .98.142c.18.242.653.84 1.873.84a.7.7 0 1 1 0 1.4c-1.828 0-2.668-.965-2.995-1.402a.7.7 0 0 1 .142-.98");
}

.v9-iaf48c {
  d: path("M17.654 11.387a.84.84 0 0 1 .884.999l-1.617.117a.842.842 0 0 1 .733-1.117");
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.vio74z7fz {
  stop-color: var(--svg-color--a980f0, #A980F0);
}

.vzjrnw-cv {
  stop-color: var(--svg-color--734251, #734251);
}

.w06d_xbwd {
  stop-color: var(--svg-color--6745a2, #6745A2);
}

.wg3eepbwp {
  stop-color: var(--svg-color--805c54, #805C54);
}

.wln98ypvp {
  stop-color: var(--svg-color--693b40, #693B40);
  stop-opacity: 0;
}

.wrh2b4bbx {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
}

.wtu7i7zxm {
  fill-rule: evenodd;
  d: path("M2.31 11.919a.7.7 0 0 1 .977.157q.05.071.115.168c.262.39.704 1.052 1.515 1.4a.7.7 0 0 1-.55 1.286c-1.246-.533-1.935-1.603-2.156-1.945l-.058-.089a.7.7 0 0 1 .157-.977");
}

.x_ik4kbfh {
  stop-color: var(--svg-color--714350, #714350);
}

.x3lw1rboi {
  fill-rule: evenodd;
  d: path("M3.349 11.602a.7.7 0 0 1 .977.157c.045.062.088.137.115.183l.006.01l.001.002c.034.057.066.113.105.174c.077.12.17.249.294.37c.232.228.607.468 1.266.5a.7.7 0 1 1-.068 1.398c-1.024-.05-1.718-.447-2.178-.899a3.5 3.5 0 0 1-.495-.617a6 6 0 0 1-.134-.223l-.045-.075l-.001-.002a.7.7 0 0 1 .157-.978");
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xqzy-pb-b {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M16.711 11.931c.218-.455.57-.829 1.385-.888c.357-.026.708.048 1.032.272c.267.186.252.449.064.56l-.5.337c-.626-.154-1.304-.131-1.98-.28");
}

.xy4qbsbbs {
  stop-color: var(--svg-color--563a92, #563A92);
}

.yamoh3dov {
  stop-color: var(--svg-color--764e4c, #764E4C);
}

.ycrcotb4u {
  stop-color: var(--svg-color--986f60, #986F60);
  stop-opacity: 0;
}

.yd1eqqb2n {
  stop-color: var(--svg-color--816052, #816052);
}

.yg46jyodv {
  fill: var(--svg-color--000, #000);
  d: path("M14.095 12.486a.48.48 0 0 0-.513-.444a.478.478 0 0 0-.375.73l.847-.062a.5.5 0 0 0 .041-.224");
}

.yka3mun3y {
  fill: var(--svg-color--000, #000);
  d: path("M17.236 12.258a.48.48 0 0 1 .443-.514a.478.478 0 0 1 .476.668l-.846.062a.43.43 0 0 1-.073-.216");
}

.ynqid7b9h {
  stop-color: var(--svg-color--7346c5, #7346C5);
  stop-opacity: 0;
}

.yq63iy86j {
  stop-color: var(--svg-color--856661, #856661);
}

.z-lhhmboj {
  d: path("M15.796 20.205c-1.104 0-2-.744-2-1.661v-1.963c0-.917.896-1.661 2-1.661s2 .744 2 1.661v1.963c0 .917-.895 1.661-2 1.661");
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zcmdavrrk {
  fill-rule: evenodd;
  d: path("M22.515 13.375c.17-.423.24-.886.206-1.36a3.1 3.1 0 0 0-.341-1.207h.005a3 3 0 0 0-.299-.462l-.002-.003a3.05 3.05 0 0 1-.614-1.625l-.001-.01a3.103 3.103 0 0 0-3.32-2.869a.5.5 0 0 1-.443-.187a3.11 3.11 0 0 0-2.61-1.108a3.11 3.11 0 0 0-2.42 1.474a.53.53 0 0 1-.412.25l-.08.006a3.103 3.103 0 0 0-2.79 3.313l.001.01a3.05 3.05 0 0 1-.372 1.697l-.002.003a3.1 3.1 0 0 0 .015 3.059c.076.128.087.29.03.427a3.022 3.022 0 0 0 3.03 4.14l8.05-.585a3.022 3.022 0 0 0 2.4-4.536a.48.48 0 0 1-.031-.427m-11.682-1.67h-.012l1.285 2.129c.307 2.62 1.142-.084 3.647-.266s3.812 2.664 3.736.027l.847-3.076c-.135-1.164-.987-1.185-1.156-1.172l-3.02.22a3.63 3.63 0 0 1-3.106-1.352a.248.248 0 0 0-.43.079l-.063.187a2.17 2.17 0 0 1-1.078 1.262l-.047.023c-.213.13-.707.513-.662 1.405l.03.286z");
}

.ze2zbibwf {
  d: path("M18.452 12.059a.8.8 0 0 0-.248-.418l-.224.285l.125.206z");
}

.zgf54gbaa {
  stop-color: var(--svg-color--614396, #614396);
}

.zir-0dbzc {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.336 10.185c.298-.095 1.052-.113 1.582.21");
}

.zkep4n0kj {
  d: path("M14.375 12.367c-.02-.27-.253-.434-.316-.484l-.251.28l.19.327z");
}

.zoq8fuaif {
  stop-color: var(--svg-color--986f60, #986F60);
}

.zrx8b2rln {
  stop-color: var(--svg-color--6f4738, #6F4738);
  stop-opacity: 0;
}

.zux03vusp {
  stroke: var(--svg-color--9465e3, #9465E3);
  stroke-linecap: square;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.162 18.721v3.442a1 1 0 0 0 1.567.824l1.84-1.266");
}

.zw5j5tz7b {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.569 12.087c-.28-.42-.684-.738-1.499-.679c-.357.026-.693.15-.981.42c-.237.222-.185.48.018.563l.543.26c.597-.242 1.271-.318 1.919-.564");
}

</style>
