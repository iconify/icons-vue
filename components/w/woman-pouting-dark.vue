<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iixEqkw)"><path fill="url(#ijSn4td)" clip-rule="evenodd" class="v3rowac_k"/><path fill="url(#ir1D5Fc)" clip-rule="evenodd" class="v3rowac_k"/><path fill="url(#iyAODPc)" clip-rule="evenodd" class="v3rowac_k"/><path fill="url(#imlvNme)" clip-rule="evenodd" class="v3rowac_k"/><path fill="url(#iEpoAEq)" clip-rule="evenodd" class="v3rowac_k"/><path fill="url(#iw2s0uy)" clip-rule="evenodd" class="v3rowac_k"/><path fill="url(#iG9uAcb)" clip-rule="evenodd" class="v3rowac_k"/><path fill="url(#iGCsjCe)" clip-rule="evenodd" class="v3rowac_k"/><path fill="url(#i5gO8xb)" clip-rule="evenodd" class="v3rowac_k"/><path fill="url(#ieRFnhe)" clip-rule="evenodd" class="v3rowac_k"/><path fill="url(#ihek5ad)" clip-rule="evenodd" class="v3rowac_k"/></g><path fill="url(#imDCkod)" class="beqqhlb_f"/><path fill="url(#iyHlBUW)" class="beqqhlb_f"/><path fill="url(#irb4BOb)" class="beqqhlb_f"/><path fill="url(#ih7H2lb)" class="beqqhlb_f"/><path fill="url(#iGFKmDc)" class="kqgo56bmw"/><path fill="url(#iHvQtre)" class="kqgo56bmw"/><path fill="url(#ixTGaab)" class="j6gh95b4u"/><path fill="url(#ifiGDFc)" class="j6gh95b4u"/><path fill="url(#imht4nd)" class="j6gh95b4u"/><g filter="url(#iwKm97V)"><path fill="url(#iBKCRue)" class="gt5swb36y"/></g><path fill="url(#iUg0hTb)" class="gt5swb36y"/><path fill="url(#i2TzVac)" class="gt5swb36y"/><g filter="url(#iIgLtRd)"><path fill="url(#iOwoZQZ)" class="hy53dfkqz"/></g><rect fill="url(#i0i15Be)" class="f_fjyw2sp"/><g filter="url(#iEHxpCd)"><path fill="url(#iYy8xMd)" class="c43yre6ms"/></g><g filter="url(#igEfTUc)"><path fill="url(#iiBnSmx)" class="ae7lwvb0w"/><path fill="url(#iJ1f0oc)" class="ae7lwvb0w"/></g><g filter="url(#iyv4hcc)"><path class="r19-0dbfw"/><path fill="url(#iSUu2Sc)" class="wtfu6ybwi"/></g><g filter="url(#iuGLisc)"><path class="kjadygbvu"/><path fill="url(#iugUk0d)" class="e43gvuz0j"/></g><g filter="url(#ia93f8c)"><path fill="url(#iB6CkDv)" class="xrc685bku"/><path fill="url(#i1Rfbee)" class="xrc685bku"/><path fill="url(#iehdSwb)" class="xrc685bku"/><path fill="url(#iwodbOc)" class="xrc685bku"/><path fill="url(#i4DMmpe)" class="xrc685bku"/><path fill="url(#i1Mkivb)" class="xrc685bku"/><path fill="url(#irOU4id)" class="xrc685bku"/><path fill="url(#i2I2RPb)" class="xrc685bku"/></g><path fill="url(#iRlUfae)" class="xrc685bku"/><g filter="url(#ia06bDd)"><path class="umvzhkb3o"/></g><g filter="url(#iKwrNEe)"><path class="s_hc3mbcs"/><path fill="url(#iKdb17b)" class="ad4txxbcb"/><path fill="url(#iUKaDMe)" class="ad4txxbcb"/><path fill="url(#ixV1Khe)" class="ad4txxbcb"/><path fill="url(#iJwB7Rd)" class="ad4txxbcb"/></g><path fill="url(#i0rprad)" class="ad4txxbcb"/><path fill="url(#i7hQ2Id)" class="ad4txxbcb"/><g filter="url(#ihPm4Kc)"><path class="p0zmx1buv"/></g><g filter="url(#ifSROMd)"><path class="rk99r9b6u"/></g><path class="pax1uwbyh"/><path fill="url(#iuYLd7c)" class="v0k6e-7fd"/><path class="rv931jact"/><g filter="url(#iZ7Of7U)"><path class="xlnz7-ytl"/><path fill="url(#iIRawgc)" class="f31dkskld"/></g><g filter="url(#iJ50jFe)"><path fill="url(#idbZUwb)" class="s1vejyimc"/></g><path class="gk8kb_b6f"/><path fill="url(#iGr7rFd)" class="s38cs8btu"/><path class="e5nzk0k2u"/><g filter="url(#ieFQwJu)"><path fill="url(#iWfYC9b)" class="b1eb3dmxj"/></g><g filter="url(#iGzlvJe)"><ellipse transform="rotate(-27.914 13.597 10.09)" class="mz1s3fbbf"/><ellipse fill="url(#if2eSxb)" transform="rotate(-27.914 13.597 10.09)" class="oc68uujfs"/></g><g filter="url(#i4yKcIe)"><path class="brwmv7bzc"/><path fill="url(#ikdMpxc)" class="ixig_pb7k"/></g><g filter="url(#iD7EKzb)"><path class="xr-h2gxoz"/><path fill="url(#ilsTSZb)" class="anuh7absx"/><path fill="url(#iVZVKfe)" class="anuh7absx"/></g><g filter="url(#igZo0vb)"><path stroke="url(#iZSslbd)" class="sxoqe_rna"/></g><g filter="url(#imtnClb)"><path class="fadueh3be"/></g><g filter="url(#iR7Q2Nb)"><path stroke="url(#iPI71pc)" clip-rule="evenodd" class="qgyil5b2a"/><path stroke="url(#iiqDzmp)" clip-rule="evenodd" class="qgyil5b2a"/></g><path clip-rule="evenodd" class="wd8gujbrc"/><g filter="url(#iax1EQc)"><path fill="url(#iyf10rd)" class="t-gb0_mer"/></g><g filter="url(#imyM2nb)"><rect class="s-s5gxbcd"/></g><g filter="url(#i3rjTZQ)"><rect class="yn7loiamt"/></g><g filter="url(#i6lE8re)"><path class="f27dzjbys"/></g><g filter="url(#i9sj9gb)"><path class="m0wjg7jna"/></g><defs><radialGradient id="ir1D5Fc" cx="0" cy="0" r="1" gradientTransform="matrix(-.61102 4.61661 -5.76709 -.76329 15.775 13.325)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iyAODPc" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 4.384 8.774)scale(3.52127 4.62667)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="imlvNme" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.866 8.27)scale(2.17941 1.67348)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iEpoAEq" cx="0" cy="0" r="1" gradientTransform="matrix(-1.30693 2.13857 -1.50644 -.92062 11.634 8.963)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iw2s0uy" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 4.08 11.676)scale(2.99127 4.15234)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iG9uAcb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45957 1.45967 -2.03987 -2.03973 21.987 4.737)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iGCsjCe" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 11.135 6.653)scale(1.94433 4.05475)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="i5gO8xb" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.712 8.117)scale(2.93911 3.744)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="ieRFnhe" cx="0" cy="0" r="1" gradientTransform="matrix(-.91586 -2.6837 2.12266 -.72439 20.873 7.465)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="ihek5ad" cx="0" cy="0" r="1" gradientTransform="matrix(1.5229 .15974 -.25883 2.46753 9.861 9.894)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="imDCkod" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.625 -11.8762 0 16.002 15.916)" gradientUnits="userSpaceOnUse"><stop class="l4nwu-c5t"/><stop offset="1" class="c0giurt9j"/></radialGradient><radialGradient id="iyHlBUW" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.06339 5.05408 0 22.943 23.227)" gradientUnits="userSpaceOnUse"><stop class="kropdjn8m"/><stop offset="1" class="jl9qoxtbg"/></radialGradient><radialGradient id="ih7H2lb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.65625 0 0 -3.18983 15.005 15.448)" gradientUnits="userSpaceOnUse"><stop offset=".225" class="vpya669ti"/><stop offset="1" class="sh_b6m3le"/></radialGradient><radialGradient id="iGFKmDc" cx="0" cy="0" r="1" gradientTransform="matrix(1.4266 -.1154 .41566 5.13875 24.387 23.72)" gradientUnits="userSpaceOnUse"><stop class="cp-d4w76k"/><stop offset="1" class="kbv5awe4z"/></radialGradient><radialGradient id="ixTGaab" cx="0" cy="0" r="1" gradientTransform="matrix(3.29142 1.0992 -1.85676 5.55982 5.897 21.505)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="czk58ibbt"/><stop offset=".965" class="j_bmu-wtk"/></radialGradient><radialGradient id="imht4nd" cx="0" cy="0" r="1" gradientTransform="matrix(.17189 -4.40625 .36187 .01412 8.553 24.54)" gradientUnits="userSpaceOnUse"><stop offset=".419" class="jw1a1w0ab"/><stop offset="1" class="b462b5bvz"/></radialGradient><radialGradient id="iBKCRue" cx="0" cy="0" r="1" gradientTransform="matrix(14.39624 1.34674 -.46749 4.99726 16.668 24.696)" gradientUnits="userSpaceOnUse"><stop class="b2tykvbop"/><stop offset="1" class="plh446hyo"/></radialGradient><radialGradient id="iUg0hTb" cx="0" cy="0" r="1" gradientTransform="matrix(.70684 1.42914 -5.7496 2.8437 17.493 26.471)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="a8hr6q7rp"/><stop offset="1" class="hc2aj54dq"/></radialGradient><radialGradient id="i2TzVac" cx="0" cy="0" r="1" gradientTransform="matrix(-5.59375 2.52356 -.6861 -1.52084 26.47 23.948)" gradientUnits="userSpaceOnUse"><stop class="y1sfxn2th"/><stop offset="1" class="sj79zcqlm"/></radialGradient><radialGradient id="iOwoZQZ" cx="0" cy="0" r="1" gradientTransform="matrix(.54681 2.7031 -23.81541 4.8176 16.266 25.026)" gradientUnits="userSpaceOnUse"><stop offset=".044" class="gfxj8ueth"/><stop offset=".391" class="lqyff2uaf"/><stop offset="1" class="kd80e9bgi"/></radialGradient><radialGradient id="i0i15Be" cx="0" cy="0" r="1" gradientTransform="rotate(52.035 -8.836 24.209)scale(2.78619 3.42691)" gradientUnits="userSpaceOnUse"><stop offset=".538" class="do2dst9_s"/><stop offset=".962" class="hqq661dwl"/></radialGradient><radialGradient id="iiBnSmx" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 36.024 -40.943)scale(2.76863 3.38037)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="iJ1f0oc" cx="0" cy="0" r="1" gradientTransform="matrix(1.33237 .7468 -.21113 .37668 21.215 9.09)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="iSUu2Sc" cx="0" cy="0" r="1" gradientTransform="matrix(1.52895 -.11373 .0889 1.1952 20.528 10.906)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="iugUk0d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.22204 0 0 -.96404 11.422 10.792)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="pj2ff5nxp"/><stop offset="1" class="sdufqstmc"/></radialGradient><radialGradient id="iB6CkDv" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.364 7.206)scale(7.25213 9.70685)" gradientUnits="userSpaceOnUse"><stop class="aj61gebdf"/><stop offset="1" class="v2xpqhbrh"/></radialGradient><radialGradient id="i1Rfbee" cx="0" cy="0" r="1" gradientTransform="rotate(154.513 7.71 7.578)scale(2.28446 1.59086)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="x7h3p2bdy"/></radialGradient><radialGradient id="iehdSwb" cx="0" cy="0" r="1" gradientTransform="matrix(1.08703 -3.51994 4.46616 1.37924 13.874 17.116)" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></radialGradient><radialGradient id="iwodbOc" cx="0" cy="0" r="1" gradientTransform="rotate(96.727 3.688 12.595)scale(6.93356 6.97069)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="m6mmhsf1n"/><stop offset="1" class="do3fwrbgr"/></radialGradient><radialGradient id="i4DMmpe" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.64978 -6.68539 0 15.816 10.643)" gradientUnits="userSpaceOnUse"><stop offset=".858" class="l-0cbacrb"/><stop offset="1" class="tetwumyrr"/></radialGradient><radialGradient id="i1Mkivb" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.374 6.871)scale(7.1262 12.2691)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="f6uv1pf_h"/><stop offset="1" class="fp6zmm73k"/></radialGradient><radialGradient id="irOU4id" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.16529 1.43013 0 18.411 9.824)" gradientUnits="userSpaceOnUse"><stop class="yv4uycbmh"/><stop offset="1" class="wgpm0ibqw"/></radialGradient><radialGradient id="i2I2RPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.32908 1.52321 0 13.978 9.593)" gradientUnits="userSpaceOnUse"><stop class="f82mfcbsw"/><stop offset="1" class="xkhh7vb2n"/></radialGradient><radialGradient id="iRlUfae" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3015 0 0 -6.52692 21.24 11.33)" gradientUnits="userSpaceOnUse"><stop class="jids0zpwm"/><stop offset="1" class="zz4mcgrzh"/></radialGradient><radialGradient id="iKdb17b" cx="0" cy="0" r="1" gradientTransform="matrix(-.4613 -2.06981 .6379 -.14217 16.875 12.067)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="iJwB7Rd" cx="0" cy="0" r="1" gradientTransform="matrix(-.78924 0 0 -.22065 16.633 12.28)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="i7hQ2Id" cx="0" cy="0" r="1" gradientTransform="rotate(145.529 6.42 8.393)scale(1.68425 2.02421)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="i669rlbzr"/><stop offset="1" class="yt9sv1b9n"/></radialGradient><radialGradient id="iuYLd7c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82156 -1.30678 0 18.29 10.188)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iIRawgc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.545 .714)scale(.38306 .52738)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iGr7rFd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82156 -1.30678 0 13.871 10.188)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="if2eSxb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00783 -.5003 .60137 -.00942 13.581 10.41)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ikdMpxc" cx="0" cy="0" r="1" gradientTransform="matrix(1.27795 -2.7902 1.4274 .65377 10.351 8.04)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="ilsTSZb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1386 4.44687 -7.27038 -3.4965 18.016 2.768)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iVZVKfe" cx="0" cy="0" r="1" gradientTransform="matrix(-.213 1.38445 -2.97857 -.45824 16.294 3.142)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="iPI71pc" cx="0" cy="0" r="1" gradientTransform="rotate(116.896 4.016 12.142)scale(.30222 .93391)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="gh80l_-hq"/><stop offset="1" class="p2og3tbhc"/></radialGradient><radialGradient id="iiqDzmp" cx="0" cy="0" r="1" gradientTransform="rotate(-31.372 32.707 -19.487)scale(.18758 .22697)" gradientUnits="userSpaceOnUse"><stop class="gh80l_-hq"/><stop offset="1" class="p2og3tbhc"/></radialGradient><filter id="iixEqkw" width="15.458" height="15.958" x="8.477" y="1.407" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4628"/></filter><filter id="iwKm97V" width="19.161" height="7.244" x="8.163" y="22.599" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.145098 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4628"/></filter><filter id="iIgLtRd" width="19.009" height="7.177" x="5.176" y="22.667" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.168627 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4628"/></filter><filter id="iEHxpCd" width="3.409" height="3.259" x="9.707" y="9.163" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4628"/></filter><filter id="igEfTUc" width="3.259" height="3.509" x="19.34" y="8.913" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4628"/></filter><filter id="iyv4hcc" width="3.175" height="3.175" x="19.381" y="9.205" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4628" stdDeviation=".25"/></filter><filter id="iuGLisc" width="2.675" height="2.675" x="10.018" y="9.455" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4628" stdDeviation=".125"/></filter><filter id="ia93f8c" width="10.319" height="11.414" x="10.921" y="5.824" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0901961 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4628"/></filter><filter id="ia06bDd" width="2.901" height="3.716" x="14.466" y="9.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4628" stdDeviation=".25"/></filter><filter id="iKwrNEe" width="2.401" height="3.216" x="14.881" y="9.891" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4628" stdDeviation=".125"/></filter><filter id="ihPm4Kc" width="3.037" height="1.302" x="17.037" y="9.37" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4628"/></filter><filter id="ifSROMd" width="3.037" height="1.302" x="12.088" y="9.37" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4628"/></filter><filter id="iZ7Of7U" width=".794" height=".703" x="17.548" y="9.744" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4628" stdDeviation=".05"/></filter><filter id="iJ50jFe" width=".897" height=".92" x="18.4" y="9.821" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4628" stdDeviation=".1"/></filter><filter id="ieFQwJu" width=".994" height="1.048" x="13.901" y="9.757" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4628" stdDeviation=".1"/></filter><filter id="iGzlvJe" width=".922" height=".711" x="13.136" y="9.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4628" stdDeviation=".05"/></filter><filter id="i4yKcIe" width="4.948" height="5.236" x="9.309" y="3.443" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4628"/><feGaussianBlur result="effect2_foregroundBlur_13036_4628" stdDeviation=".375"/></filter><filter id="iD7EKzb" width="8.871" height="5.849" x="12.874" y="2.617" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4628"/><feGaussianBlur result="effect2_foregroundBlur_13036_4628" stdDeviation=".125"/></filter><filter id="igZo0vb" width="1.152" height="2.331" x="12.853" y="3.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4628" stdDeviation=".1"/></filter><filter id="imtnClb" width="6.989" height="3.896" x="15.252" y="4.442" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4628" stdDeviation=".5"/></filter><filter id="iR7Q2Nb" width="2.698" height="1.082" x="14.766" y="13.372" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4628" stdDeviation=".05"/></filter><filter id="iax1EQc" width="1.224" height=".712" x="15.456" y="14.278" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4628" stdDeviation=".05"/></filter><filter id="imyM2nb" width="2.848" height=".741" x="12.531" y="8.138" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4628"/></filter><filter id="i3rjTZQ" width="2.848" height=".741" x="17.05" y="8.138" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4628"/></filter><filter id="i6lE8re" width="2.62" height=".55" x="17.123" y="8.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4628" stdDeviation=".075"/></filter><filter id="i9sj9gb" width="2.62" height=".55" x="12.628" y="8.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4628" stdDeviation=".075"/></filter><linearGradient id="ijSn4td" x1="20.833" x2="13.942" y1="3.752" y2="16.516" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="irb4BOb" x1="16.505" x2="16.505" y1="30.289" y2="26.539" gradientUnits="userSpaceOnUse"><stop class="waift8brn"/><stop offset="1" class="qeur-ccno"/></linearGradient><linearGradient id="iHvQtre" x1="22.8" x2="23.56" y1="22.786" y2="22.733" gradientUnits="userSpaceOnUse"><stop class="cyj659bzg"/><stop offset="1" class="jmgn8ibxu"/></linearGradient><linearGradient id="ifiGDFc" x1="9.63" x2="8.474" y1="23.789" y2="23.695" gradientUnits="userSpaceOnUse"><stop class="g27c6tbna"/><stop offset="1" class="jvn9nabmr"/></linearGradient><linearGradient id="iYy8xMd" x1="9.707" x2="12.703" y1="10.881" y2="10.881" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="qenr6bbwz"/></linearGradient><linearGradient id="iUKaDMe" x1="15.131" x2="16.081" y1="12.14" y2="12.14" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="ixV1Khe" x1="16.081" x2="16.081" y1="12.95" y2="12.332" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="i0rprad" x1="16.16" x2="16.16" y1="12.923" y2="12.782" gradientUnits="userSpaceOnUse"><stop class="kos78---c"/><stop offset="1" class="wq1w-qb8s"/></linearGradient><linearGradient id="idbZUwb" x1="19.078" x2="18.761" y1="10.242" y2="10.438" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iWfYC9b" x1="14.625" x2="14.307" y1="10.242" y2="10.438" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iZSslbd" x1="13.153" x2="13.705" y1="4.516" y2="5.806" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="iyf10rd" x1="16.299" x2="15.712" y1="14.378" y2="14.89" gradientUnits="userSpaceOnUse"><stop class="yht9xr-na"/><stop offset=".736" class="l1mbqih3m"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-pouting-dark" /></template>
<style>
.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.a8hr6q7rp {
  stop-color: var(--svg-color--341a29, #341A29);
}

.ad4txxbcb {
  d: path("m15.694 10.427l-.538 1.721a.546.546 0 0 0 .527.708h.796c.374 0 .637-.36.527-.708l-.538-1.721c-.115-.382-.653-.382-.774 0");
}

.ae7lwvb0w {
  d: path("M20.969 12.422a1.63 1.63 0 1 0 0-3.259a1.63 1.63 0 0 0 0 3.259");
}

.aj61gebdf {
  stop-color: var(--svg-color--4f322e, #4F322E);
}

.anuh7absx {
  d: path("M15.47 2.903c-1.147-.253-2.177.892-2.296 1.316c1.065 3.59 3.76 3.393 6.42 3.097c1.593-.177 1.766.55 1.901.9c0-3.982-3.386-4.73-5.996-5.306z");
}

.ayiod_bfg {
  stop-color: var(--svg-color--493033, #493033);
}

.b1eb3dmxj {
  d: path("M14.695 10.502c0-.292-.238-.486-.302-.545l-.292.282l.18.366z");
}

.b2tykvbop {
  stop-color: var(--svg-color--4d3b3a, #4D3B3A);
}

.b462b5bvz {
  stop-color: var(--svg-color--685390, #685390);
  stop-opacity: 0;
}

.beqqhlb_f {
  d: path("m9.157 24.604l-3.906.183c.578-5.253 5.03-9.34 10.437-9.34h.625c5.415 0 9.872 4.099 10.44 9.363l-4.378-.206v5.187H9.157z");
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.brwmv7bzc {
  fill: var(--svg-color--20171a, #20171A);
  d: path("M11.048 4.964c.573-.607 1.557-.843 2.057-.753l.401 1.307c-.256-.04-.484.051-.676.238c-.454 1.276-2.014 1.98-2.738 2.172c-.15-1.51.21-2.174.956-2.964");
}

.c0giurt9j {
  stop-color: var(--svg-color--7c60b2, #7C60B2);
}

.c43yre6ms {
  d: path("M11.336 12.422a1.63 1.63 0 1 0 0-3.259a1.63 1.63 0 0 0 0 3.259");
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cctx1cb1y {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
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

.cp-d4w76k {
  stop-color: var(--svg-color--a285de, #A285DE);
}

.crde6o_5i {
  stop-color: var(--svg-color--402824, #402824);
  stop-opacity: 0;
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cyj659bzg {
  stop-color: var(--svg-color--7555ae, #7555AE);
}

.czk58ibbt {
  stop-color: var(--svg-color--81649d, #81649D);
}

.do2dst9_s {
  stop-color: var(--svg-color--311c29, #311C29);
}

.do3fwrbgr {
  stop-color: var(--svg-color--3f243b, #3F243B);
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e43gvuz0j {
  d: path("M11.356 11.88a1.088 1.088 0 1 0 0-2.175a1.088 1.088 0 0 0 0 2.175");
}

.e5nzk0k2u {
  fill: var(--svg-color--000, #000);
  d: path("M14.387 10.609a.515.515 0 0 0-.518-.518a.515.515 0 0 0-.46.756h.916a.5.5 0 0 0 .062-.239");
}

.f_fjyw2sp {
  width: 4.223px;
  height: 6.028px;
  x: 13.876px;
  y: 12.542px;
  rx: 2.111px;
}

.f27dzjbys {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.398 8.562h2.07");
}

.f31dkskld {
  d: path("M18.226 9.896c.065.086-.07.19-.223.305s-.267.195-.331.11c-.064-.087.008-.25.16-.364c.153-.114.33-.137.394-.051");
}

.f6uv1pf_h {
  stop-color: var(--svg-color--5e4543, #5E4543);
  stop-opacity: 0;
}

.f82mfcbsw {
  stop-color: var(--svg-color--371e27, #371E27);
}

.fadueh3be {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m18.518 6.559l-1.444.265a.697.697 0 1 1-.126-1.382h2.37c1.402 0 1.866 1.413 1.923 1.896a3.19 3.19 0 0 0-2.723-.78");
}

.fp6zmm73k {
  stop-color: var(--svg-color--5e4543, #5E4543);
}

.ft5dv1b6b {
  fill: none;
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g27c6tbna {
  stop-color: var(--svg-color--5f488a, #5F488A);
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gfxj8ueth {
  stop-color: var(--svg-color--5c4542, #5C4542);
}

.gh80l_-hq {
  stop-color: var(--svg-color--5e4f4f, #5E4F4F);
}

.gk8kb_b6f {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.66 9.43c-.662 0-1.22.455-1.372 1.072a.278.278 0 0 0 .27.345h2.26a.233.233 0 0 0 .23-.275A1.42 1.42 0 0 0 13.66 9.43");
}

.gl9okfban {
  stop-color: var(--svg-color--634d4b, #634D4B);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gt5swb36y {
  d: path("M26.374 28.385c.6-1.05.454-2.812.375-3.597l-3.937-.169c-.413.213-1.526.09-2.031 0l-8.898-1.406c-.617-.117-2.096-.231-2.773.133c-.766.412-1 1.193-.938 1.578c4.271 1.532 12.632 4.563 13.757 4.813c1.82.312 3.695-.04 4.445-1.352");
}

.hc2aj54dq {
  stop-color: var(--svg-color--341a29, #341A29);
  stop-opacity: 0;
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hqq661dwl {
  stop-color: var(--svg-color--4f3544, #4F3544);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.hy53dfkqz {
  d: path("M5.626 28.385c-.6-1.05-.454-2.812-.375-3.597l3.937-.169c.413.213 1.526.09 2.031 0l9.672-1.562c.617-.117 1.448-.177 2.125.188c.728.392.7.965.642 1.352a.1.1 0 0 1-.063.077c-4.286 1.54-12.404 4.814-13.524 5.063c-1.82.312-3.695-.04-4.445-1.352");
}

.i669rlbzr {
  stop-color: var(--svg-color--2d151c, #2D151C);
  stop-opacity: 0;
}

.ixig_pb7k {
  d: path("M11.048 4.964c.573-.607 1.557-.843 2.057-.753l.401 1.307c-.256-.04-.484.051-.676.238c-.454 1.276-2.014 1.98-2.738 2.172c-.15-1.51.21-2.174.956-2.964");
}

.j_bmu-wtk {
  stop-color: var(--svg-color--604885, #604885);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j6gh95b4u {
  d: path("m5.251 24.787l3.847-.16l.059.183h.031V17.7a10.5 10.5 0 0 0-3.937 7.087");
}

.jids0zpwm {
  stop-color: var(--svg-color--59403d, #59403D);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jl9qoxtbg {
  stop-color: var(--svg-color--9d80d7, #9D80D7);
  stop-opacity: 0;
}

.jmgn8ibxu {
  stop-color: var(--svg-color--7555ae, #7555AE);
  stop-opacity: 0;
}

.jvn9nabmr {
  stop-color: var(--svg-color--5f488a, #5F488A);
  stop-opacity: 0;
}

.jw1a1w0ab {
  stop-color: var(--svg-color--685390, #685390);
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kbv5awe4z {
  stop-color: var(--svg-color--8f74c8, #8F74C8);
}

.kd80e9bgi {
  stop-color: var(--svg-color--462d2e, #462D2E);
}

.kjadygbvu {
  fill: var(--svg-color--35252b, #35252B);
  d: path("M11.356 11.88a1.088 1.088 0 1 0 0-2.175a1.088 1.088 0 0 0 0 2.175");
}

.kos78---c {
  stop-color: var(--svg-color--311620, #311620);
}

.kqgo56bmw {
  d: path("M22.925 17.79a10.48 10.48 0 0 1 3.827 7.02l-3.827-.18z");
}

.kropdjn8m {
  stop-color: var(--svg-color--9d80d7, #9D80D7);
}

.l-0cbacrb {
  stop-color: var(--svg-color--5c4761, #5C4761);
  stop-opacity: 0;
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l1mbqih3m {
  stop-color: var(--svg-color--493c3c, #493C3C);
}

.l4nwu-c5t {
  stop-color: var(--svg-color--7d5bb9, #7D5BB9);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lqyff2uaf {
  stop-color: var(--svg-color--4c2f34, #4C2F34);
}

.m0wjg7jna {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.903 8.562h2.07");
}

.m6mmhsf1n {
  stop-color: var(--svg-color--3f243b, #3F243B);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.mz1s3fbbf {
  cx: 13.597px;
  cy: 10.091px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.395px;
  ry: 0.2px;
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.oc68uujfs {
  cx: 13.597px;
  cy: 10.091px;
  rx: 0.395px;
  ry: 0.2px;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.p0zmx1buv {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.238 10.216c.268-.473.677-.846 1.556-.846c.385 0 .757.107 1.087.373c.272.22.235.502.024.607l-.562.322c-.66-.214-1.39-.242-2.105-.456");
}

.p2og3tbhc {
  stop-color: var(--svg-color--5e4f4f, #5E4F4F);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pax1uwbyh {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.502 9.43c.661 0 1.22.455 1.372 1.072a.278.278 0 0 1-.271.345h-2.26a.233.233 0 0 1-.23-.275a1.415 1.415 0 0 1 1.389-1.142");
}

.pj2ff5nxp {
  stop-color: var(--svg-color--2d181a, #2D181A);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.plh446hyo {
  stop-color: var(--svg-color--472c32, #472C32);
}

.qenr6bbwz {
  stop-color: var(--svg-color--2a1c1f, #2A1C1F);
}

.qeur-ccno {
  stop-color: var(--svg-color--7150b0, #7150B0);
  stop-opacity: 0;
}

.qgyil5b2a {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.952 14.22a1.54 1.54 0 0 0-1.673 0a.2.2 0 1 1-.226-.33c.616-.424 1.504-.424 2.124-.001a.2.2 0 1 1-.225.33");
}

.qm132ccsa {
  stop-color: var(--svg-color--655251, #655251);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r19-0dbfw {
  fill: var(--svg-color--4c3637, #4C3637);
  d: path("M20.969 11.88a1.088 1.088 0 1 0 0-2.175a1.088 1.088 0 0 0 0 2.175");
}

.rk99r9b6u {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.925 10.216c-.27-.473-.678-.846-1.557-.846c-.385 0-.756.107-1.087.373c-.272.22-.235.502-.024.607l.563.322c.66-.214 1.39-.242 2.105-.456");
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
}

.rv931jact {
  fill: var(--svg-color--000, #000);
  d: path("M17.775 10.609c0-.288.23-.518.518-.518a.515.515 0 0 1 .46.756h-.916a.47.47 0 0 1-.062-.239");
}

.s_hc3mbcs {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("m15.694 10.427l-.538 1.721a.546.546 0 0 0 .527.708h.796c.374 0 .637-.36.527-.708l-.538-1.721c-.115-.382-.653-.382-.774 0");
}

.s-s5gxbcd {
  width: 2.648px;
  height: 0.541px;
  x: 12.531px;
  y: 8.338px;
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  rx: 0.271px;
}

.s1vejyimc {
  d: path("M19.098 10.49a.85.85 0 0 0-.235-.47l-.263.29l.119.23z");
}

.s38cs8btu {
  d: path("M13.87 9.705a.904.904 0 0 0-.872 1.142h1.746a1 1 0 0 0 .033-.239a.91.91 0 0 0-.908-.903");
}

.s9u3_wbrp {
  stop-color: var(--svg-color--402824, #402824);
}

.sdufqstmc {
  stop-color: var(--svg-color--2d181a, #2D181A);
}

.sh_b6m3le {
  stop-color: var(--svg-color--482e57, #482E57);
  stop-opacity: 0;
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sj79zcqlm {
  stop-color: var(--svg-color--5c4441, #5C4441);
  stop-opacity: 0;
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.sxoqe_rna {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.153 4.168c.024.246.238 1.171.552 1.731");
}

.t-gb0_mer {
  d: path("M16.58 14.89a.512.512 0 1 0-1.024 0z");
}

.t5djkhb4t {
  stop-color: var(--svg-color--655251, #655251);
}

.tetwumyrr {
  stop-color: var(--svg-color--5c4761, #5C4761);
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.umvzhkb3o {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m15.683 10.567l-.692 1.721a.546.546 0 0 0 .527.708h.797c.373 0 .637-.36.527-.708l-.538-1.721c-.116-.382-.5-.382-.62 0");
}

.v0k6e-7fd {
  d: path("M18.293 9.705a.904.904 0 0 1 .87 1.142h-1.745a.907.907 0 0 1 .875-1.142");
}

.v2xpqhbrh {
  stop-color: var(--svg-color--402a29, #402A29);
}

.v3rowac_k {
  fill-rule: evenodd;
  d: path("M23.357 12.22c.215-.44.328-.933.328-1.445c0-.473-.098-.917-.272-1.322h.005a3 3 0 0 0-.285-.52l-.002-.003a3.3 3.3 0 0 1-.532-1.793v-.01a3.34 3.34 0 0 0-3.341-3.341a.55.55 0 0 1-.461-.236a3.35 3.35 0 0 0-2.716-1.393a3.35 3.35 0 0 0-2.716 1.393a.57.57 0 0 1-.461.236l-.086.001a3.34 3.34 0 0 0-3.255 3.34v.01A3.3 3.3 0 0 1 9.03 8.93l-.002.004a3.34 3.34 0 0 0-.223 3.286a.52.52 0 0 1 0 .461c-.205.43-.328.912-.328 1.425a3.254 3.254 0 0 0 3.259 3.258h8.69a3.254 3.254 0 0 0 3.259-3.259c0-.512-.123-.994-.328-1.424a.52.52 0 0 1 0-.461M10.942 9.514h-.013l1.214 2.385c.125 2.838 1.233 0 3.938 0s3.885 3.159 4.01.32l1.15-3.237c-.055-1.26-.968-1.349-1.15-1.349H16.83A3.91 3.91 0 0 1 13.6 5.94a.267.267 0 0 0-.467.052l-.083.196a2.33 2.33 0 0 1-1.205 1.25l-.052.02q-.028.013-.051.021c-.24.124-.8.496-.82 1.457l.01.31z");
}

.vpya669ti {
  stop-color: var(--svg-color--482e57, #482E57);
}

.waift8brn {
  stop-color: var(--svg-color--7150b0, #7150B0);
}

.wb78_hxsc {
  stop-color: var(--svg-color--6a5956, #6A5956);
}

.wd8gujbrc {
  fill: var(--svg-color--290018, #290018);
  fill-rule: evenodd;
  d: path("M16.952 14.22a1.54 1.54 0 0 0-1.673 0a.2.2 0 1 1-.226-.33c.616-.424 1.504-.424 2.124-.001a.2.2 0 1 1-.225.33");
}

.wgpm0ibqw {
  stop-color: var(--svg-color--43272a, #43272A);
  stop-opacity: 0;
}

.wq1w-qb8s {
  stop-color: var(--svg-color--311620, #311620);
  stop-opacity: 0;
}

.wtfu6ybwi {
  d: path("M20.969 11.88a1.088 1.088 0 1 0 0-2.175a1.088 1.088 0 0 0 0 2.175");
}

.x_sue_b_g {
  stop-color: var(--svg-color--634d4b, #634D4B);
}

.x7h3p2bdy {
  stop-color: var(--svg-color--533632, #533632);
  stop-opacity: 0;
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xfmbn4_bb {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
  stop-opacity: 0;
}

.xkhh7vb2n {
  stop-color: var(--svg-color--371e27, #371E27);
  stop-opacity: 0;
}

.xlnz7-ytl {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.226 9.896c.065.086-.07.19-.223.305s-.267.195-.331.11c-.064-.087.008-.25.16-.364c.153-.114.33-.137.394-.051");
}

.xr-h2gxoz {
  fill: var(--svg-color--2f2428, #2F2428);
  d: path("M15.47 2.903c-1.147-.253-2.177.892-2.296 1.316c1.065 3.59 3.76 3.393 6.42 3.097c1.593-.177 1.766.55 1.901.9c0-3.982-3.386-4.73-5.996-5.306z");
}

.xrc685bku {
  d: path("M10.93 9.514h.012l-.01-.269l-.01-.31c.02-.96.58-1.333.82-1.457l.051-.02l.052-.02c.54-.249.976-.683 1.205-1.251l.083-.196a.267.267 0 0 1 .467-.052a3.91 3.91 0 0 0 3.23 1.694h3.26c.183 0 1.096.089 1.15 1.35l-.12 3.111c-.125 2.838-2.34 4.744-5.046 4.744c-2.705 0-4.921-1.906-5.046-4.744z");
}

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.y1sfxn2th {
  stop-color: var(--svg-color--5c4441, #5C4441);
}

.yht9xr-na {
  stop-color: var(--svg-color--301a1e, #301A1E);
}

.yn7loiamt {
  width: 2.648px;
  height: 0.541px;
  x: 17.05px;
  y: 8.338px;
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  rx: 0.271px;
}

.yt9sv1b9n {
  stop-color: var(--svg-color--2d151c, #2D151C);
}

.yv4uycbmh {
  stop-color: var(--svg-color--43272a, #43272A);
}

.z_wfxjr5n {
  stop-color: var(--svg-color--392526, #392526);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zz4mcgrzh {
  stop-color: var(--svg-color--59403d, #59403D);
  stop-opacity: 0;
}

</style>
