<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iImgrLd)"><rect fill="url(#iIk56Pc)" transform="rotate(-45 12.963 13.403)" class="etm0labvf"/></g><g filter="url(#iELilte)"><rect fill="url(#i96BfVc)" transform="scale(-1 1)rotate(-45 -3.014 35.5)" class="ffese-y7m"/></g><rect fill="url(#iIRexfS)" transform="scale(-1 1)rotate(-45 -3.014 35.5)" class="ffese-y7m"/><g filter="url(#icmxHHr)"><path fill="url(#im3tg0d)" class="is89u6ban"/><path fill="url(#iX1BTZW)" class="is89u6ban"/></g><g filter="url(#iyR7Xwd)"><rect fill="url(#i8mbSfd)" transform="scale(-1 1)rotate(-45 6.585 29.734)" class="z_5s59bdn"/></g><g filter="url(#igOOdhc)"><path class="g11vnob-s"/></g><g filter="url(#i4HBB7b)"><path class="ytl8wkbiv"/></g><g filter="url(#i6qbLvh)"><path class="s99p66ikg"/></g><g filter="url(#i7qK1nX)"><path class="pv3dgeoha"/></g><g filter="url(#icUHmid)"><path fill="url(#iy14VSd)" clip-rule="evenodd" class="czaodob9u"/><path fill="url(#iY14sze)" clip-rule="evenodd" class="czaodob9u"/><path fill="url(#iO4d07d)" clip-rule="evenodd" class="czaodob9u"/><path fill="url(#iYvOV4b)" clip-rule="evenodd" class="czaodob9u"/><path fill="url(#ieVk89Z)" clip-rule="evenodd" class="czaodob9u"/><path fill="url(#idtJvTW)" clip-rule="evenodd" class="czaodob9u"/><path fill="url(#izFcl1d)" clip-rule="evenodd" class="czaodob9u"/><path fill="url(#iDlhdjb)" clip-rule="evenodd" class="czaodob9u"/><path fill="url(#i52Bp6d)" clip-rule="evenodd" class="czaodob9u"/><path fill="url(#iAWXTac)" clip-rule="evenodd" class="czaodob9u"/><path fill="url(#i4ZiVsd)" clip-rule="evenodd" class="czaodob9u"/><path fill="url(#iTUkbFc)" clip-rule="evenodd" class="czaodob9u"/></g><g filter="url(#iZVmyud)"><rect class="vsr9738qr"/><rect fill="url(#i8a16yi)" class="kq9b5xnhm"/></g><g filter="url(#i9wvQme)"><path fill="url(#ioitlCc)" class="dv6-6mbxj"/></g><path fill="url(#ipQ5Pnc)" class="dv6-6mbxj"/><path fill="url(#i8KfH3d)" class="dv6-6mbxj"/><path fill="url(#iEdEbnd)" class="dv6-6mbxj"/><path class="dxabh57cr"/><path fill="url(#i7QnpSd)" class="mh57-sx2c"/><path fill="url(#iJU4nte)" class="mh57-sx2c"/><g filter="url(#iPEdLcZ)"><path fill="url(#iHHd2Hc)" class="j-tweow-u"/><path fill="url(#iDg3KJe)" class="j-tweow-u"/><path fill="url(#iCaH14s)" class="j-tweow-u"/></g><path fill="url(#iuP6NMd)" class="eayua2tob"/><path fill="url(#iDv7Hjb)" class="eayua2tob"/><g filter="url(#iPYLYcH)"><path class="b_cb9kpgv"/><path fill="url(#ifCnSIe)" class="l99mnwbez"/><path fill="url(#iSigaRb)" class="l99mnwbez"/></g><path fill="url(#iqP8udb)" class="z45oacyxz"/><path fill="url(#ihvNS4d)" class="z45oacyxz"/><circle class="ar7i_ib9g"/><g filter="url(#iSyBETz)"><path class="ly32g8bmi"/><path fill="url(#ifE2E6b)" class="k-27-x9ja"/></g><g filter="url(#ipv33zc)"><path class="m3bis1bwo"/></g><g filter="url(#i4Z3Zhb)"><path class="kq400vgbe"/><path fill="url(#iJKHnVb)" class="xgq6w0b8s"/><path fill="url(#iaLzn5A)" class="xgq6w0b8s"/></g><g filter="url(#iwo20Xd)"><path class="tl5_xodfm"/></g><path fill="url(#iWroyTd)" class="js5y7fb5r"/><path fill="url(#izNTKdc)" class="js5y7fb5r"/><path fill="url(#iiD6wCc)" class="js5y7fb5r"/><path fill="url(#iKByDMe)" class="js5y7fb5r"/><path fill="url(#iBJnkMe)" class="js5y7fb5r"/><path fill="url(#i01Vulc)" class="b6pcaeboe"/><path fill="url(#ik92wpc)" class="b6pcaeboe"/><g filter="url(#iaZiyBE)"><path class="zepkmwb6a"/><path fill="url(#iaToRcc)" class="uw9pt0beg"/><path fill="url(#i4dfdjc)" class="uw9pt0beg"/><path fill="url(#ihLxlKX)" class="uw9pt0beg"/></g><g filter="url(#iSm0sTc)"><path stroke="url(#iyrq4bd)" class="iqsdfibon"/></g><path fill="url(#irGgnec)" class="b-q2f27bj"/><path fill="url(#iHeluSb)" class="ju-3ieb_x"/><g filter="url(#i5o9fHX)"><path fill="url(#ifvowfb)" class="qfmwt0nrd"/></g><g filter="url(#iFbUk8c)"><path fill="url(#iWNqnMd)" class="r0uc7tbuz"/><path fill="url(#i39PGBe)" class="r0uc7tbuz"/></g><g filter="url(#irRKYwb)"><path class="nlre6gbtg"/><path fill="url(#i3cTi4I)" class="qifxuzb2b"/></g><g filter="url(#i8FZO1d)"><path class="a8t1w-bte"/><path fill="url(#iY18dGM)" class="jhq-1e83t"/></g><g filter="url(#icAiJwb)"><path fill="url(#ivB9WCf)" class="agnalsw3x"/><path fill="url(#idfRFCe)" class="agnalsw3x"/><path fill="url(#iGX6tdm)" class="agnalsw3x"/><path fill="url(#iQjoAYd)" class="agnalsw3x"/><path fill="url(#iv6lQ2b)" class="agnalsw3x"/><path fill="url(#ij3ZhOc)" class="agnalsw3x"/><path fill="url(#iyT9Qob)" class="agnalsw3x"/><path fill="url(#iuwq5oe)" class="agnalsw3x"/></g><path fill="url(#ia6ovDc)" class="agnalsw3x"/><path fill="url(#iihxc0b)" class="agnalsw3x"/><g filter="url(#i3gvaUb)"><path class="hqteaxb2x"/></g><g filter="url(#ivz8AJb)"><path class="yh6bisb1t"/><path fill="url(#iXW3RCc)" class="vq70dfbyz"/><path fill="url(#ighB7mc)" class="vq70dfbyz"/><path fill="url(#itjV36d)" class="vq70dfbyz"/><path fill="url(#iL1GBed)" class="vq70dfbyz"/></g><g filter="url(#iizLj2a)"><path stroke="url(#i05CRQb)" class="f3pmx5b1m"/></g><path class="u8xbwmbok"/><g filter="url(#iztpVwd)"><path class="fc_njqbaz"/></g><g filter="url(#itS336c)"><path class="i8juusb_c"/></g><g filter="url(#ilSnfZf)"><path class="mcm-9la-u"/></g><g filter="url(#inbmpdb)"><path clip-rule="evenodd" class="qiwrt2b8t"/></g><path class="kcqbm14sw"/><path fill="url(#iMAMZXc)" class="erjdcuj5j"/><path class="t4tw68b8v"/><g filter="url(#iNICldY)"><path class="gupqheews"/><path fill="url(#iLMXlqd)" class="j35o8ab8g"/></g><g filter="url(#iEp56Qa)"><path fill="url(#iYkzGVS)" class="t3m0otqyu"/></g><path class="dgo34nb2r"/><path fill="url(#iHndqij)" class="bx25pugxo"/><path class="fr09aig7e"/><g filter="url(#iSPxk4d)"><path fill="url(#iNFJEyS)" class="i35jrcm4a"/></g><g filter="url(#iyJuRfe)"><ellipse transform="rotate(-27.914 15.018 7.595)" class="yjx7cpa9w"/><ellipse fill="url(#ixFbOIh)" transform="rotate(-27.914 15.018 7.595)" class="e62chdcyu"/></g><g filter="url(#irnFLYb)"><path class="wixqc6-nu"/><path fill="url(#iLlPtMc)" class="r64c98kht"/><path fill="url(#iaGrnLc)" class="r64c98kht"/></g><g filter="url(#iPha5Oc)"><path stroke="url(#i8VLgWc)" class="k87urc_ak"/></g><g filter="url(#iWhIEWb)"><path class="zgul-bc_h"/></g><defs><radialGradient id="iIk56Pc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87825 -2.80633 3.32449 -2.22505 16.838 21.301)" gradientUnits="userSpaceOnUse"><stop class="vvvf-bx0b"/><stop offset="1" class="rivz2obdn"/></radialGradient><radialGradient id="i96BfVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.75045 -10.1868 0 3.092 .28)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="vm1_cbcaw"/><stop offset="1" class="k356i5yuc"/></radialGradient><radialGradient id="iIRexfS" cx="0" cy="0" r="1" gradientTransform="rotate(-58.508 8.125 5.097)scale(2.87644 1.6899)" gradientUnits="userSpaceOnUse"><stop offset=".419" class="uodqeubaz"/><stop offset="1" class="pha_6_rva"/></radialGradient><radialGradient id="i8mbSfd" cx="0" cy="0" r="1" gradientTransform="matrix(.46404 .88388 -1.60027 .84014 1.815 6.289)" gradientUnits="userSpaceOnUse"><stop class="x6_m96bez"/><stop offset="1" class="s2ceddo5o"/></radialGradient><radialGradient id="iY14sze" cx="0" cy="0" r="1" gradientTransform="matrix(-.26534 2.0048 -2.50441 -.33146 15.964 8.999)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iO4d07d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26777 .855 -1.1234 -1.66576 14.726 9.117)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iYvOV4b" cx="0" cy="0" r="1" gradientTransform="matrix(-.5749 .7518 -.57728 -.44145 13.967 7.997)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="ieVk89Z" cx="0" cy="0" r="1" gradientTransform="matrix(-.56754 .9287 -.65418 -.39979 14.166 7.105)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="idtJvTW" cx="0" cy="0" r="1" gradientTransform="matrix(.60439 1.14982 -1.59612 .83898 14.55 4.355)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="izFcl1d" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 8.24 6.5)scale(.89641 1.2527)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iDlhdjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.81073 .23585 -.49184 -1.69073 19.398 7.526)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="i52Bp6d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.23823 .30957 -.39435 -1.57732 19.133 9.028)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iAWXTac" cx="0" cy="0" r="1" gradientTransform="matrix(-.39772 -1.16542 .92178 -.31457 18.178 6.454)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="i4ZiVsd" cx="0" cy="0" r="1" gradientTransform="matrix(.66133 .06937 -.1124 1.07155 13.396 7.509)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iTUkbFc" cx="0" cy="0" r="1" gradientTransform="matrix(-.38356 1.22529 -1.12948 -.35357 13.62 6.15)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="gcrmpdfop"/><stop offset="1" class="nd--cppfl"/></radialGradient><radialGradient id="ioitlCc" cx="0" cy="0" r="1" gradientTransform="rotate(141.509 11.379 5.864)scale(3.31383 3.4775)" gradientUnits="userSpaceOnUse"><stop class="nw_aknb7y"/><stop offset="1" class="pt-h1ccpi"/></radialGradient><radialGradient id="ipQ5Pnc" cx="0" cy="0" r="1" gradientTransform="matrix(.35156 .89062 -.53122 .2097 23.217 2.575)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="vw5e4lbve"/><stop offset="1" class="v_k-57lgf"/></radialGradient><radialGradient id="i8KfH3d" cx="0" cy="0" r="1" gradientTransform="rotate(78.781 8.915 17.107)scale(1.04377 .3506)" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="qlfye6p8o"/></radialGradient><radialGradient id="iEdEbnd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6346 .22 -.12993 -.3748 24.731 3.528)" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="qlfye6p8o"/></radialGradient><radialGradient id="iCaH14s" cx="0" cy="0" r="1" gradientTransform="matrix(-.17187 3.50443 -.50958 -.025 15.44 24.97)" gradientUnits="userSpaceOnUse"><stop offset=".085" class="zx20zqh8j"/><stop offset="1" class="j807r45wk"/></radialGradient><radialGradient id="iDv7Hjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.07031 -.19922 1.40814 -.49699 14.503 29.465)" gradientUnits="userSpaceOnUse"><stop class="p5u-_cblu"/><stop offset="1" class="uowu7rarb"/></radialGradient><radialGradient id="iSigaRb" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 2.2133 -.98624 .20888 19.32 18.972)" gradientUnits="userSpaceOnUse"><stop offset=".091" class="uz8dj8b7c"/><stop offset="1" class="z5e-1sbyl"/></radialGradient><radialGradient id="ihvNS4d" cx="0" cy="0" r="1" gradientTransform="matrix(.28516 -.16406 .55035 .95656 16.253 27.216)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="s3hklabia"/><stop offset="1" class="n5igrlbfw"/></radialGradient><radialGradient id="ifE2E6b" cx="0" cy="0" r="1" gradientTransform="rotate(-38.729 27.876 -1.303)scale(8.09176 6.39568)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="lh4nfkb5q"/><stop offset="1" class="zz3980hzg"/></radialGradient><radialGradient id="iJKHnVb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.16876 .9375 -.156 -.19448 8.314 14.542)" gradientUnits="userSpaceOnUse"><stop class="ev6-__b2a"/><stop offset="1" class="rsfgarwma"/></radialGradient><radialGradient id="iaLzn5A" cx="0" cy="0" r="1" gradientTransform="matrix(.8047 -.67969 .45175 .53484 7.442 15.269)" gradientUnits="userSpaceOnUse"><stop offset=".644" class="asecgoboj"/><stop offset=".986" class="e5m3cbc6k"/></radialGradient><radialGradient id="iiD6wCc" cx="0" cy="0" r="1" gradientTransform="matrix(.10937 1.0625 -3.8587 .39722 15.607 10.59)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="g7dj32byf"/><stop offset="1" class="mv_j9hb5m"/></radialGradient><radialGradient id="i01Vulc" cx="0" cy="0" r="1" gradientTransform="matrix(.54687 1.25508 -2.35578 1.02647 15.148 10.137)" gradientUnits="userSpaceOnUse"><stop class="qlvkqabeg"/><stop offset="1" class="o9iemhbma"/></radialGradient><radialGradient id="ik92wpc" cx="0" cy="0" r="1" gradientTransform="matrix(-.82013 .35725 -.19955 -.45811 16.848 10.618)" gradientUnits="userSpaceOnUse"><stop class="u66aotmpr"/><stop offset="1" class="dqp3b0bfm"/></radialGradient><radialGradient id="iWNqnMd" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 27.616 -37.21)scale(1.2023 1.46796)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="i39PGBe" cx="0" cy="0" r="1" gradientTransform="matrix(.5786 .3243 -.09169 .16358 18.326 7.16)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="i3cTi4I" cx="0" cy="0" r="1" gradientTransform="rotate(-4.249 116 -238.729)scale(.66579 .52047)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="iY18dGM" cx="0" cy="0" r="1" gradientTransform="matrix(-.53068 0 0 -.41864 14.074 7.9)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="pj2ff5nxp"/><stop offset="1" class="sdufqstmc"/></radialGradient><radialGradient id="ivB9WCf" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 7.836 5.736)scale(3.14931 4.21529)" gradientUnits="userSpaceOnUse"><stop class="aj61gebdf"/><stop offset="1" class="v2xpqhbrh"/></radialGradient><radialGradient id="idfRFCe" cx="0" cy="0" r="1" gradientTransform="matrix(-.8955 .42688 -.29728 -.62362 16.9 8.033)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="x7h3p2bdy"/></radialGradient><radialGradient id="iGX6tdm" cx="0" cy="0" r="1" gradientTransform="matrix(.47205 -1.52857 1.93947 .59895 15.138 10.646)" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></radialGradient><radialGradient id="iQjoAYd" cx="0" cy="0" r="1" gradientTransform="rotate(96.727 4.73 11.126)scale(3.01096 3.02709)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="m6mmhsf1n"/><stop offset="1" class="do3fwrbgr"/></radialGradient><radialGradient id="iv6lQ2b" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.88773 -2.90319 0 15.982 7.834)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="d0fyzsbqc"/><stop offset="1" class="n8ysctycz"/></radialGradient><radialGradient id="ij3ZhOc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.0367 .59594 -1.02603 -5.22825 16.893 8.424)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="f6uv1pf_h"/><stop offset="1" class="fp6zmm73k"/></radialGradient><radialGradient id="iyT9Qob" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.50604 .62105 0 17.109 7.479)" gradientUnits="userSpaceOnUse"><stop class="yv4uycbmh"/><stop offset="1" class="wgpm0ibqw"/></radialGradient><radialGradient id="iuwq5oe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.57716 .66147 0 15.184 7.378)" gradientUnits="userSpaceOnUse"><stop class="f82mfcbsw"/><stop offset="1" class="xkhh7vb2n"/></radialGradient><radialGradient id="ia6ovDc" cx="0" cy="0" r="1" gradientTransform="matrix(-.56519 0 0 -2.83437 18.337 8.133)" gradientUnits="userSpaceOnUse"><stop class="jids0zpwm"/><stop offset="1" class="zz4mcgrzh"/></radialGradient><radialGradient id="iihxc0b" cx="0" cy="0" r="1" gradientTransform="matrix(-.80428 .6923 -.464 -.53905 17.821 9.913)" gradientUnits="userSpaceOnUse"><stop class="ybvm9tprh"/><stop offset=".694" class="yxwqgvbem"/></radialGradient><radialGradient id="iXW3RCc" cx="0" cy="0" r="1" gradientTransform="rotate(-102.564 11.609 -2.364)scale(.92089 .28381)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="iL1GBed" cx="0" cy="0" r="1" gradientTransform="matrix(-.34273 0 0 -.09582 16.336 8.546)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="iMAMZXc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35677 -.56748 0 17.056 7.637)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iLMXlqd" cx="0" cy="0" r="1" gradientTransform="matrix(-.10198 -.13142 .18093 -.1404 16.955 7.674)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iHndqij" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35677 -.56748 0 15.137 7.637)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ixFbOIh" cx="0" cy="0" r="1" gradientTransform="matrix(-.0034 -.21726 .26115 -.00409 15.011 7.733)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iLlPtMc" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 7.08 7.532)scale(2.14281 3.50337)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iaGrnLc" cx="0" cy="0" r="1" gradientTransform="matrix(-.0925 .60121 -1.29347 -.199 16.19 4.577)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="iImgrLd" width="7.335" height="7.37" x="13.891" y="10.901" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.075" dy=".08"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.662745 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1145"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.08"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.745098 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1145" result="effect2_innerShadow_4002_1145"/></filter><filter id="iELilte" width="10.517" height="10.517" x="14.14" y="4.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1145"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1145" result="effect2_innerShadow_4002_1145"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.788235 0 0 0 0 0.827451 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1145" result="effect3_innerShadow_4002_1145"/></filter><filter id="icmxHHr" width="9.391" height="10.922" x="7.466" y="4.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1145"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.811765 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1145" result="effect2_innerShadow_4002_1145"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.521569 0 0 0 0 0.662745 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1145" result="effect3_innerShadow_4002_1145"/></filter><filter id="iyR7Xwd" width="7.298" height="7.298" x="10.845" y="10.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.654902 0 0 0 0 0.905882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1145"/></filter><filter id="igOOdhc" width="3.908" height="3.642" x="9.545" y="9.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1145"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1145" result="effect2_dropShadow_4002_1145"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1145" result="shape"/></filter><filter id="i4HBB7b" width="6.45" height="6.548" x="9.62" y="5.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1145"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1145" result="effect2_dropShadow_4002_1145"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1145" result="shape"/></filter><filter id="i6qbLvh" width="3.908" height="3.642" x="18.631" y="9.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1145"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.968627 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1145" result="effect2_dropShadow_4002_1145"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1145" result="shape"/></filter><filter id="i7qK1nX" width="6.45" height="6.548" x="16.014" y="5.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1145"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.968627 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1145" result="effect2_dropShadow_4002_1145"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1145" result="shape"/></filter><filter id="icUHmid" width="6.854" height="7.354" x="12.795" y="3.399" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1145"/></filter><filter id="iZVmyud" width=".989" height="4.833" x="22.355" y="4.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".35" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.254902 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1145"/></filter><filter id="i9wvQme" width="4.084" height="3.799" x="20.732" y="2.116" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.05"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.639216 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1145"/></filter><filter id="iPEdLcZ" width="2.97" height="9.929" x="13.318" y="19.905" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.262745 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1145"/></filter><filter id="iPYLYcH" width="5.091" height="8.843" x="15.749" y="18.772" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.168627 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1145"/></filter><filter id="iSyBETz" width="7.578" height="5.434" x="6.015" y="10.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.129412 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1145"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.188235 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1145" result="effect2_innerShadow_4002_1145"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.188235 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1145" result="effect3_innerShadow_4002_1145"/></filter><filter id="ipv33zc" width="1.692" height="1.561" x="6.722" y="14.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.592157 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1145"/></filter><filter id="i4Z3Zhb" width="1.692" height="1.561" x="6.722" y="14.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.211765 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1145"/></filter><filter id="iwo20Xd" width="5.398" height="7.21" x="18.218" y="7.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.6"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.121569 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1145"/></filter><filter id="iaZiyBE" width="6.349" height="5.065" x="13.14" y="16.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.329412 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1145"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.415686 0 0 0 0 0.717647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1145" result="effect2_innerShadow_4002_1145"/></filter><filter id="iSm0sTc" width="4.609" height="5.161" x="18.951" y="9.386" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1145" stdDeviation=".25"/></filter><filter id="i5o9fHX" width="1.565" height="1.415" x="13.329" y="7.192" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1145"/></filter><filter id="iFbUk8c" width="1.415" height="1.665" x="17.512" y="6.942" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1145"/></filter><filter id="irRKYwb" width="1.945" height="1.945" x="17.247" y="6.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1145" stdDeviation=".25"/></filter><filter id="i8FZO1d" width="1.445" height="1.445" x="13.322" y="7.177" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1145" stdDeviation=".125"/></filter><filter id="icAiJwb" width="4.481" height="4.883" x="13.856" y="5.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0901961 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1145"/></filter><filter id="i3gvaUb" width="1.826" height="2.179" x="15.113" y="7.177" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1145" stdDeviation=".25"/></filter><filter id="ivz8AJb" width="1.026" height="1.379" x="15.584" y="7.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1145" stdDeviation=".05"/></filter><filter id="iizLj2a" width="1.652" height=".695" x="15.271" y="8.92" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1145" stdDeviation=".025"/></filter><filter id="iztpVwd" width="1.432" height=".565" x="16.399" y="7.282" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1145"/></filter><filter id="itS336c" width="1.432" height=".565" x="14.363" y="7.282" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1145"/></filter><filter id="ilSnfZf" width="1.191" height=".592" x="14.422" y="6.544" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1145"/></filter><filter id="inbmpdb" width="1.191" height=".592" x="16.804" y="6.544" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1145"/></filter><filter id="iNICldY" width=".458" height=".418" x="16.677" y="7.387" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1145" stdDeviation=".05"/></filter><filter id="iEp56Qa" width=".616" height=".626" x="16.991" y="7.364" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1145" stdDeviation=".1"/></filter><filter id="iSPxk4d" width=".658" height=".682" x="15.037" y="7.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1145" stdDeviation=".1"/></filter><filter id="iyJuRfe" width=".514" height=".422" x="14.761" y="7.384" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1145" stdDeviation=".05"/></filter><filter id="irnFLYb" width="4.063" height="2.673" x="14.535" y="4.308" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1145"/><feGaussianBlur result="effect2_foregroundBlur_4002_1145" stdDeviation=".075"/></filter><filter id="iPha5Oc" width=".84" height="1.352" x="14.525" y="4.723" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1145" stdDeviation=".1"/></filter><filter id="iWhIEWb" width="2.967" height="1.623" x="15.771" y="5.176" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1145" stdDeviation=".2"/></filter><linearGradient id="im3tg0d" x1="8.529" x2="12.668" y1="5.843" y2="9.982" gradientUnits="userSpaceOnUse"><stop class="tx327ubjh"/><stop offset="1" class="vxhtc9kgk"/></linearGradient><linearGradient id="iX1BTZW" x1="11.132" x2="10.694" y1="12.966" y2="9.06" gradientUnits="userSpaceOnUse"><stop class="ubeqdvb2g"/><stop offset="1" class="redus_bqs"/></linearGradient><linearGradient id="iy14VSd" x1="18.16" x2="15.168" y1="4.842" y2="10.385" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="i8a16yi" x1="22.921" x2="22.547" y1="5.345" y2="6.127" gradientUnits="userSpaceOnUse"><stop offset=".167" class="zqax3vbfg"/><stop offset="1" class="z0_tnl66g"/></linearGradient><linearGradient id="i7QnpSd" x1="18.792" x2="16.991" y1="16.247" y2="16.247" gradientUnits="userSpaceOnUse"><stop class="utipi7g6i"/><stop offset="1" class="edfwaihfg"/></linearGradient><linearGradient id="iJU4nte" x1="13.267" x2="15.007" y1="16.431" y2="16.431" gradientUnits="userSpaceOnUse"><stop class="bjaenibkq"/><stop offset="1" class="louyt9b7g"/></linearGradient><linearGradient id="iHHd2Hc" x1="15.345" x2="12.939" y1="24.348" y2="24.374" gradientUnits="userSpaceOnUse"><stop offset=".113" class="yf70htb_x"/><stop offset="1" class="j2t0-ibcg"/></linearGradient><linearGradient id="iDg3KJe" x1="15.517" x2="15.017" y1="26.035" y2="26.009" gradientUnits="userSpaceOnUse"><stop class="jfv9nbbub"/><stop offset="1" class="syp0_bc6o"/></linearGradient><linearGradient id="iuP6NMd" x1="15.197" x2="13.71" y1="28.891" y2="28.891" gradientUnits="userSpaceOnUse"><stop class="q54t2dj5c"/><stop offset=".159" class="wiovp2snp"/><stop offset=".453" class="wiovp2snp"/><stop offset="1" class="em6gbkb2t"/></linearGradient><linearGradient id="ifCnSIe" x1="18.825" x2="18.304" y1="23.645" y2="23.388" gradientUnits="userSpaceOnUse"><stop class="j834f-b0x"/><stop offset="1" class="t0ieoim-m"/></linearGradient><linearGradient id="iqP8udb" x1="15.835" x2="17.116" y1="26.357" y2="27.044" gradientUnits="userSpaceOnUse"><stop class="wu3iwcc6r"/><stop offset="1" class="evpxnsbrs"/></linearGradient><linearGradient id="iWroyTd" x1="16.03" x2="16.03" y1="10.709" y2="15.544" gradientUnits="userSpaceOnUse"><stop class="z9-ns_cqv"/><stop offset="1" class="voshhcbhx"/></linearGradient><linearGradient id="izNTKdc" x1="13.267" x2="15.139" y1="15.544" y2="15.544" gradientUnits="userSpaceOnUse"><stop class="w8z9c1bqk"/><stop offset="1" class="d1stbzbsu"/></linearGradient><linearGradient id="iKByDMe" x1="18.792" x2="16.607" y1="13.948" y2="13.948" gradientUnits="userSpaceOnUse"><stop class="eo1g38slj"/><stop offset="1" class="s89mq5-5f"/></linearGradient><linearGradient id="iBJnkMe" x1="18.96" x2="17.959" y1="14.225" y2="14.225" gradientUnits="userSpaceOnUse"><stop offset=".049" class="bpn-u35sy"/><stop offset="1" class="ukj380brt"/></linearGradient><linearGradient id="iaToRcc" x1="13.14" x2="15.351" y1="18.9" y2="18.9" gradientUnits="userSpaceOnUse"><stop class="c2g5jlmdp"/><stop offset="1" class="j9-ktqfbw"/></linearGradient><linearGradient id="i4dfdjc" x1="19.255" x2="16.729" y1="18.309" y2="18.9" gradientUnits="userSpaceOnUse"><stop offset=".349" class="hta3d8bay"/><stop offset="1" class="yezlp2beb"/></linearGradient><linearGradient id="ihLxlKX" x1="19.489" x2="18.607" y1="18.386" y2="18.614" gradientUnits="userSpaceOnUse"><stop class="wg5i7s-vd"/><stop offset="1" class="pql-90wca"/></linearGradient><linearGradient id="iyrq4bd" x1="22.451" x2="19.857" y1="11.683" y2="13.527" gradientUnits="userSpaceOnUse"><stop offset=".453" class="pcb1i7bpl"/><stop offset="1" class="c84uw1bwv"/></linearGradient><linearGradient id="irGgnec" x1="12.937" x2="19.259" y1="10.014" y2="10.014" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iHeluSb" x1="12.937" x2="19.259" y1="10.001" y2="10.001" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="ifvowfb" x1="13.329" x2="14.63" y1="7.938" y2="7.938" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="qenr6bbwz"/></linearGradient><linearGradient id="ighB7mc" x1="15.684" x2="16.097" y1="8.485" y2="8.485" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="itjV36d" x1="16.097" x2="16.097" y1="8.836" y2="8.568" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="i05CRQb" x1="15.629" x2="15.832" y1="9.456" y2="9.143" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="iYkzGVS" x1="17.398" x2="17.26" y1="7.66" y2="7.745" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iNFJEyS" x1="15.464" x2="15.326" y1="7.66" y2="7.745" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i8VLgWc" x1="14.825" x2="15.065" y1="5.174" y2="5.734" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-fairy-dark" /></template>
<style>
.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.a8t1w-bte {
  fill: var(--svg-color--35252b, #35252B);
  d: path("M14.045 8.372a.472.472 0 1 0 0-.945a.472.472 0 0 0 0 .945");
}

.agnalsw3x {
  d: path("M13.86 7.344h.005l-.004-.117l-.005-.134c.01-.417.253-.579.356-.633l.023-.009l.023-.009c.234-.107.423-.296.523-.543l.036-.085a.116.116 0 0 1 .203-.022c.315.462.843.735 1.402.735h1.416c.08 0 .476.039.5.586l-.053 1.352c-.054 1.232-1.016 2.06-2.191 2.06s-2.137-.828-2.191-2.06z");
}

.aj61gebdf {
  stop-color: var(--svg-color--4f322e, #4F322E);
}

.ar7i_ib9g {
  cx: 6.572px;
  cy: 15.685px;
  r: 0.438px;
  fill: var(--svg-color--371d2d, #371D2D);
}

.asecgoboj {
  stop-color: var(--svg-color--422c2d, #422C2D);
  stop-opacity: 0;
}

.ayiod_bfg {
  stop-color: var(--svg-color--493033, #493033);
}

.b_cb9kpgv {
  fill: var(--svg-color--51383b, #51383B);
  d: path("m17.672 21.275l-.596-1.31l2.266-.993c.02.062.673 1.888.798 2.307c.125.418-.01.773-.094.898l-3.269 5.344c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l1.85-4.032a.6.6 0 0 0 .019-.453");
}

.b-q2f27bj {
  d: path("M16.253 10.001q.166.008.338.022a10 10 0 0 0-.338-.022");
}

.b6pcaeboe {
  d: path("M15.07 10.136v.699a.24.24 0 0 0 .065.157c.135.147.326.443.456.87c.06.195.233.342.437.342a.47.47 0 0 0 .437-.342c.13-.427.322-.723.457-.87a.24.24 0 0 0 .065-.157v-.699z");
}

.bjaenibkq {
  stop-color: var(--svg-color--839927, #839927);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bpn-u35sy {
  stop-color: var(--svg-color--9771bf, #9771BF);
}

.bx25pugxo {
  d: path("M15.136 7.427a.392.392 0 0 0-.378.496h.758a.395.395 0 0 0-.38-.496");
}

.c2g5jlmdp {
  stop-color: var(--svg-color--67568f, #67568F);
}

.c84uw1bwv {
  stop-color: var(--svg-color--5a4544, #5A4544);
  stop-opacity: 0;
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

.crde6o_5i {
  stop-color: var(--svg-color--402824, #402824);
  stop-opacity: 0;
}

.czaodob9u {
  fill-rule: evenodd;
  d: path("M19.256 8.52a1.44 1.44 0 0 0 .024-1.202h.003a1.4 1.4 0 0 0-.124-.226v-.001a1.43 1.43 0 0 1-.232-.78v-.004c0-.8-.65-1.45-1.45-1.45a.24.24 0 0 1-.201-.103a1.454 1.454 0 0 0-2.359 0a.25.25 0 0 1-.2.103h-.037a1.45 1.45 0 0 0-1.414 1.45v.005c0 .276-.08.547-.231.779l-.001.001a1.45 1.45 0 0 0-.097 1.427a.23.23 0 0 1 0 .2a1.413 1.413 0 0 0 1.273 2.034h3.774a1.413 1.413 0 0 0 1.272-2.034a.23.23 0 0 1 0-.2m-5.39-1.176h-.006l.527 1.036c.054 1.232.535 0 1.71 0s1.687 1.371 1.74.14l.5-1.407c-.023-.547-.42-.586-.5-.586h-1.415c-.56 0-1.087-.273-1.402-.735a.116.116 0 0 0-.203.022l-.037.085a1 1 0 0 1-.523.543l-.022.01l-.023.008c-.103.054-.347.215-.356.633l.005.134z");
}

.d0fyzsbqc {
  stop-color: var(--svg-color--3b232b, #3B232B);
  stop-opacity: 0;
}

.d1stbzbsu {
  stop-color: var(--svg-color--8664c8, #8664C8);
  stop-opacity: 0;
}

.dgo34nb2r {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.045 7.307a.614.614 0 0 0-.595.466a.12.12 0 0 0 .117.15h.982a.1.1 0 0 0 .1-.12a.616.616 0 0 0-.604-.496");
}

.do3fwrbgr {
  stop-color: var(--svg-color--3f243b, #3F243B);
}

.dqp3b0bfm {
  stop-color: var(--svg-color--523f3d, #523F3D);
  stop-opacity: 0;
}

.dv6-6mbxj {
  d: path("M22.5 2.293a.22.22 0 0 1 .4.001l.414.896a.22.22 0 0 0 .174.126l.983.115a.22.22 0 0 1 .129.376l-.735.716a.22.22 0 0 0-.062.2l.185.926a.22.22 0 0 1-.319.237l-.864-.459a.22.22 0 0 0-.207 0l-.87.462a.22.22 0 0 1-.319-.235l.177-.932a.22.22 0 0 0-.062-.198l-.726-.718a.22.22 0 0 1 .129-.375l.98-.115a.22.22 0 0 0 .174-.125z");
}

.dxabh57cr {
  fill: var(--svg-color--aed62f, #AED62F);
  d: path("M13.267 16.39v-.861h5.525v.82a49 49 0 0 1-5.525.041");
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e5m3cbc6k {
  stop-color: var(--svg-color--422c2d, #422C2D);
}

.e62chdcyu {
  cx: 15.018px;
  cy: 7.595px;
  rx: 0.171px;
  ry: 0.087px;
}

.eayua2tob {
  d: path("m13.312 28.098l.006 1.49c0 .169.164.288.322.231a7 7 0 0 0 1.287-.603a.47.47 0 0 0 .215-.373l.055-.894z");
}

.edfwaihfg {
  stop-color: var(--svg-color--bff332, #BFF332);
  stop-opacity: 0;
}

.em6gbkb2t {
  stop-color: var(--svg-color--4c3866, #4C3866);
}

.eo1g38slj {
  stop-color: var(--svg-color--ac8de6, #AC8DE6);
}

.erjdcuj5j {
  d: path("M17.057 7.427a.393.393 0 0 1 .379.496h-.759a.394.394 0 0 1 .38-.496");
}

.etm0labvf {
  width: 4.843px;
  height: 8.191px;
  x: 12.963px;
  y: 13.403px;
  rx: 2.422px;
}

.ev6-__b2a {
  stop-color: var(--svg-color--5c4a49, #5C4A49);
}

.evpxnsbrs {
  stop-color: var(--svg-color--66488c, #66488C);
}

.f3pmx5b1m {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.097 9.18c-.23 0-.444-.056-.625-.152c-.062-.032-.128.039-.09.096a.85.85 0 0 0 1.43 0c.038-.06-.028-.128-.09-.096c-.18.096-.394.152-.625.152Z");
}

.f6uv1pf_h {
  stop-color: var(--svg-color--5e4543, #5E4543);
  stop-opacity: 0;
}

.f82mfcbsw {
  stop-color: var(--svg-color--371e27, #371E27);
}

.fc_njqbaz {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M16.599 7.649c.117-.205.294-.367.676-.367a.73.73 0 0 1 .472.162c.118.095.102.218.01.263l-.244.14c-.287-.093-.604-.105-.914-.198");
}

.ffese-y7m {
  width: 6.894px;
  height: 11.735px;
  rx: 3.447px;
}

.fp6zmm73k {
  stop-color: var(--svg-color--5e4543, #5E4543);
}

.fr09aig7e {
  fill: var(--svg-color--000, #000);
  d: path("M15.361 7.82c0-.126-.1-.225-.225-.225a.224.224 0 0 0-.2.328h.398a.2.2 0 0 0 .027-.104");
}

.ft5dv1b6b {
  fill: none;
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g11vnob-s {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.047 9.264a.21.21 0 1 0-.284.31l1.82 1.667l-.84.086a.21.21 0 1 0 .043.418l1.21-.124l.955.875a.21.21 0 1 0 .284-.31z");
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.g7dj32byf {
  stop-color: var(--svg-color--402d65, #402D65);
}

.gcrmpdfop {
  stop-color: var(--svg-color--585352, #585352);
}

.gl9okfban {
  stop-color: var(--svg-color--634d4b, #634D4B);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gupqheews {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.028 7.51c.028.037-.03.083-.097.133c-.066.05-.115.084-.143.047s.003-.108.07-.158c.066-.05.142-.06.17-.022");
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hqteaxb2x {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m15.924 7.801l-.3.748a.237.237 0 0 0 .229.307h.345a.238.238 0 0 0 .23-.307l-.234-.748c-.05-.165-.217-.165-.27 0");
}

.hta3d8bay {
  stop-color: var(--svg-color--9882d5, #9882D5);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i35jrcm4a {
  d: path("M15.495 7.773c0-.127-.103-.211-.131-.237l-.127.123l.078.159z");
}

.i8juusb_c {
  fill: var(--svg-color--272528, #272528);
  d: path("M15.595 7.649c-.117-.205-.295-.367-.676-.367a.73.73 0 0 0-.472.162c-.118.095-.102.218-.011.263l.245.14c.286-.093.603-.105.914-.198");
}

.iqsdfibon {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m19.701 12.745l2.672 1.045a.1.1 0 0 0 .136-.084l.302-3.57");
}

.is89u6ban {
  d: path("M8.523 10.723a3.454 3.454 0 0 1 .006-4.88a3.454 3.454 0 0 1 4.88-.006l1.19 1.19c.338.337.602.742.775 1.188l1.2 3.086c.154.398.233.822.233 1.249v.56a2.443 2.443 0 0 1-4.17 1.727z");
}

.j-tweow-u {
  d: path("M13.318 29.589v-9.484l2.32.062l-.495 8.676a.47.47 0 0 1-.216.373a7 7 0 0 1-1.287.603a.242.242 0 0 1-.322-.23");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j2t0-ibcg {
  stop-color: var(--svg-color--493032, #493032);
}

.j35o8ab8g {
  d: path("M17.028 7.51c.028.037-.03.083-.097.133c-.066.05-.115.084-.143.047s.003-.108.07-.158c.066-.05.142-.06.17-.022");
}

.j807r45wk {
  stop-color: var(--svg-color--3f2628, #3F2628);
  stop-opacity: 0;
}

.j834f-b0x {
  stop-color: var(--svg-color--584249, #584249);
}

.j9-ktqfbw {
  stop-color: var(--svg-color--8266c3, #8266C3);
  stop-opacity: 0;
}

.jfv9nbbub {
  stop-color: var(--svg-color--473534, #473534);
}

.jhq-1e83t {
  d: path("M14.045 8.372a.472.472 0 1 0 0-.945a.472.472 0 0 0 0 .945");
}

.jids0zpwm {
  stop-color: var(--svg-color--59403d, #59403D);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.js5y7fb5r {
  d: path("M16.017 10.71a24 24 0 0 0-1.985.162c-.722.102-.765.711-.765.992v3.68h5.525v-3.68c0-.28-.043-.89-.764-.992a24 24 0 0 0-1.985-.163h-.026");
}

.ju-3ieb_x {
  d: path("M16.108 10.001h-.018q.064-.001.128.005q-.056-.006-.11-.005");
}

.k-27-x9ja {
  d: path("M13.28 11.279c.194-.188.29-.23.313-.227v2.59c-.399.557-1.783 1.92-3.508 2.176c-1.615.24-2.64-.206-2.883-.47a4 4 0 0 0-.448.378a.44.44 0 0 1-.556.045a.444.444 0 0 1-.133-.56c.558-1.027 1.462-1.373 2.887-1.33c1.256.037 2.117-.522 2.39-.806c.566-.52 1.744-1.609 1.938-1.796");
}

.k356i5yuc {
  stop-color: var(--svg-color--91deff, #91DEFF);
}

.k87urc_ak {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.825 5.023c.01.106.104.508.24.751");
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kcqbm14sw {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.148 7.307c.288 0 .53.198.596.466a.12.12 0 0 1-.118.15h-.98a.1.1 0 0 1-.1-.12a.615.615 0 0 1 .602-.496");
}

.kq400vgbe {
  fill: var(--svg-color--47302d, #47302D);
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.637-.217.723-.129c.1.103.145.418-.093.696c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.014-.561.256-.764");
}

.kq9b5xnhm {
  width: 0.689px;
  height: 4.633px;
  x: 22.355px;
  y: 4.997px;
  rx: 0.345px;
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l99mnwbez {
  d: path("m17.672 21.275l-.596-1.31l2.266-.993c.02.062.673 1.888.798 2.307c.125.418-.01.773-.094.898l-3.269 5.344c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l1.85-4.032a.6.6 0 0 0 .019-.453");
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lh4nfkb5q {
  stop-color: var(--svg-color--382223, #382223);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.louyt9b7g {
  stop-color: var(--svg-color--afd730, #AFD730);
  stop-opacity: 0;
}

.ly32g8bmi {
  fill: var(--svg-color--422c2d, #422C2D);
  d: path("M13.28 11.279c.194-.188.29-.23.313-.227v2.59c-.399.557-1.783 1.92-3.508 2.176c-1.615.24-2.64-.206-2.883-.47a4 4 0 0 0-.448.378a.44.44 0 0 1-.556.045a.444.444 0 0 1-.133-.56c.558-1.027 1.462-1.373 2.887-1.33c1.256.037 2.117-.522 2.39-.806c.566-.52 1.744-1.609 1.938-1.796");
}

.m3bis1bwo {
  fill: var(--svg-color--ffbd3b, #FFBD3B);
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.637-.217.723-.129c.1.103.145.418-.093.696c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.014-.561.256-.764");
}

.m6mmhsf1n {
  stop-color: var(--svg-color--3f243b, #3F243B);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mcm-9la-u {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m14.603 7.117l-.002.002a.118.118 0 0 1-.122-.203h.002l.005-.003l.014-.008l.05-.026c.044-.02.106-.047.181-.071c.15-.048.359-.088.584-.048a.118.118 0 1 1-.04.232a1 1 0 0 0-.472.04a1 1 0 0 0-.19.08z");
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mh57-sx2c {
  d: path("M13.267 16.39v-.861h5.525v.82a49 49 0 0 1-5.525.041");
}

.mv_j9hb5m {
  stop-color: var(--svg-color--634990, #634990);
  stop-opacity: 0;
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n5igrlbfw {
  stop-color: var(--svg-color--593569, #593569);
  stop-opacity: 0;
}

.n8ysctycz {
  stop-color: var(--svg-color--2b151b, #2B151B);
}

.nd--cppfl {
  stop-color: var(--svg-color--585352, #585352);
  stop-opacity: 0;
}

.nlre6gbtg {
  fill: var(--svg-color--4c3637, #4C3637);
  d: path("M18.22 8.372a.472.472 0 1 0 0-.945a.472.472 0 0 0 0 .945");
}

.nw_aknb7y {
  stop-color: var(--svg-color--ffc736, #FFC736);
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.o9iemhbma {
  stop-color: var(--svg-color--4a2f2f, #4A2F2F);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.p5u-_cblu {
  stop-color: var(--svg-color--603b8b, #603B8B);
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pcb1i7bpl {
  stop-color: var(--svg-color--5a4544, #5A4544);
}

.pha_6_rva {
  stop-color: var(--svg-color--94d8ff, #94D8FF);
  stop-opacity: 0;
}

.pj2ff5nxp {
  stop-color: var(--svg-color--2d181a, #2D181A);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pql-90wca {
  stop-color: var(--svg-color--9f8cca, #9F8CCA);
  stop-opacity: 0;
}

.pt-h1ccpi {
  stop-color: var(--svg-color--febb35, #FEBB35);
}

.pv3dgeoha {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.68 6.325a.21.21 0 0 1 .418.048l-.159 1.385l1.024-.928a.21.21 0 1 1 .282.311l-5.73 5.192a.21.21 0 0 1-.282-.312l4.234-3.836z");
}

.q54t2dj5c {
  stop-color: var(--svg-color--664c88, #664C88);
}

.qenr6bbwz {
  stop-color: var(--svg-color--2a1c1f, #2A1C1F);
}

.qfmwt0nrd {
  d: path("M14.036 8.607a.708.708 0 1 0 0-1.415a.708.708 0 0 0 0 1.415");
}

.qifxuzb2b {
  d: path("M18.22 8.372a.472.472 0 1 0 0-.945a.472.472 0 0 0 0 .945");
}

.qiwrt2b8t {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m17.738 6.916l-.06.101za.118.118 0 0 1-.121.202l-.003-.002l-.05-.025a1 1 0 0 0-.15-.06a1 1 0 0 0-.471-.04a.118.118 0 1 1-.041-.232c.226-.04.434 0 .584.048a1.4 1.4 0 0 1 .246.105l.004.002h.001z");
}

.qlfye6p8o {
  stop-color: var(--svg-color--ffd545, #FFD545);
  stop-opacity: 0;
}

.qlvkqabeg {
  stop-color: var(--svg-color--331e1e, #331E1E);
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

.r0uc7tbuz {
  d: path("M18.22 8.607a.708.708 0 1 0 0-1.415a.708.708 0 0 0 0 1.415");
}

.r64c98kht {
  d: path("M15.832 4.473c-.498-.11-.946.387-.997.572c.462 1.559 1.633 1.473 2.788 1.345c.691-.077.766.238.825.39c0-1.729-1.47-2.054-2.604-2.304z");
}

.redus_bqs {
  stop-color: var(--svg-color--87c9fb, #87C9FB);
  stop-opacity: 0;
}

.rivz2obdn {
  stop-color: var(--svg-color--91e5ff, #91E5FF);
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
}

.rsfgarwma {
  stop-color: var(--svg-color--5c4a49, #5C4A49);
  stop-opacity: 0;
}

.s_et88bec {
  stop-color: var(--svg-color--ffd545, #FFD545);
}

.s2ceddo5o {
  stop-color: var(--svg-color--80caf3, #80CAF3);
}

.s3hklabia {
  stop-color: var(--svg-color--593569, #593569);
}

.s89mq5-5f {
  stop-color: var(--svg-color--9673d5, #9673D5);
  stop-opacity: 0;
}

.s99p66ikg {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.037 9.264a.21.21 0 1 1 .283.31l-1.819 1.667l.84.086a.21.21 0 1 1-.043.418l-1.211-.124l-.954.875a.21.21 0 1 1-.284-.31z");
}

.s9u3_wbrp {
  stop-color: var(--svg-color--402824, #402824);
}

.sdufqstmc {
  stop-color: var(--svg-color--2d181a, #2D181A);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.syp0_bc6o {
  stop-color: var(--svg-color--473534, #473534);
  stop-opacity: 0;
}

.t0ieoim-m {
  stop-color: var(--svg-color--584249, #584249);
  stop-opacity: 0;
}

.t3m0otqyu {
  d: path("M17.407 7.768a.37.37 0 0 0-.102-.204l-.114.126l.051.1z");
}

.t4tw68b8v {
  fill: var(--svg-color--000, #000);
  d: path("M16.833 7.82c0-.126.1-.225.224-.225a.224.224 0 0 1 .2.328h-.398a.2.2 0 0 1-.027-.104");
}

.t5djkhb4t {
  stop-color: var(--svg-color--655251, #655251);
}

.tl5_xodfm {
  fill: var(--svg-color--452c2c, #452C2C);
  d: path("m21.499 12.27l-3.144-1.206l-.137 2.175l3.578 1.368c.185.083.652.2 1.039 0s.516-.72.531-.953l.249-4.56a.433.433 0 0 0-.433-.456h-.007a.137.137 0 0 0-.137.137v.48a.344.344 0 0 1-.687 0v-.744a.404.404 0 0 0-.805-.036c-.013.162-.03.366-.047.6c-.037.494.276.836.438.961z");
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tx327ubjh {
  stop-color: var(--svg-color--8eefff, #8EEFFF);
}

.u66aotmpr {
  stop-color: var(--svg-color--523f3d, #523F3D);
}

.u8xbwmbok {
  fill: var(--svg-color--2a0219, #2A0219);
  d: path("M16.097 9.18c-.23 0-.444-.056-.625-.152c-.062-.032-.128.039-.09.096a.85.85 0 0 0 1.43 0c.038-.06-.028-.128-.09-.096c-.18.096-.394.152-.625.152");
}

.ubeqdvb2g {
  stop-color: var(--svg-color--87c9fb, #87C9FB);
}

.ukj380brt {
  stop-color: var(--svg-color--a585e1, #A585E1);
  stop-opacity: 0;
}

.uodqeubaz {
  stop-color: var(--svg-color--94d8ff, #94D8FF);
}

.uowu7rarb {
  stop-color: var(--svg-color--603b8b, #603B8B);
  stop-opacity: 0;
}

.utipi7g6i {
  stop-color: var(--svg-color--bff332, #BFF332);
}

.uw9pt0beg {
  d: path("M13.14 20.535c.012-.367.07-2.827.1-4.093a.1.1 0 0 1 .088-.096c1.341-.13 4.082-.09 5.365-.052c.043.001.08.03.091.073c.237.855.655 2.465.692 2.605c.037.144-.016.237-.047.266c-.398.03-.937.539-2.336 1.054c-1.398.516-2.742.61-3.195.594c-.363-.012-.517.012-.584.086c-.034-.013-.174-.144-.174-.437");
}

.uz8dj8b7c {
  stop-color: var(--svg-color--5f4a49, #5F4A49);
}

.v_k-57lgf {
  stop-color: var(--svg-color--ffdd49, #FFDD49);
  stop-opacity: 0;
}

.v2xpqhbrh {
  stop-color: var(--svg-color--402a29, #402A29);
}

.vm1_cbcaw {
  stop-color: var(--svg-color--90eeff, #90EEFF);
}

.voshhcbhx {
  stop-color: var(--svg-color--8466c6, #8466C6);
}

.vq70dfbyz {
  d: path("m15.929 7.74l-.234.748a.237.237 0 0 0 .229.308h.346a.238.238 0 0 0 .229-.308l-.234-.748c-.05-.165-.284-.165-.336 0");
}

.vsr9738qr {
  width: 0.689px;
  height: 4.633px;
  x: 22.355px;
  y: 4.997px;
  fill: var(--svg-color--9a6159, #9A6159);
  rx: 0.345px;
}

.vvvf-bx0b {
  stop-color: var(--svg-color--93efff, #93EFFF);
}

.vw5e4lbve {
  stop-color: var(--svg-color--ffdd49, #FFDD49);
}

.vxhtc9kgk {
  stop-color: var(--svg-color--8bd2ff, #8BD2FF);
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w8z9c1bqk {
  stop-color: var(--svg-color--6f5187, #6F5187);
}

.wb78_hxsc {
  stop-color: var(--svg-color--6a5956, #6A5956);
}

.wg5i7s-vd {
  stop-color: var(--svg-color--8569c7, #8569C7);
}

.wgpm0ibqw {
  stop-color: var(--svg-color--43272a, #43272A);
  stop-opacity: 0;
}

.wiovp2snp {
  stop-color: var(--svg-color--6d5191, #6D5191);
}

.wixqc6-nu {
  fill: var(--svg-color--2f2428, #2F2428);
  d: path("M15.832 4.473c-.498-.11-.946.387-.997.572c.462 1.559 1.633 1.473 2.788 1.345c.691-.077.766.238.825.39c0-1.729-1.47-2.054-2.604-2.304z");
}

.wu3iwcc6r {
  stop-color: var(--svg-color--543556, #543556);
}

.x_sue_b_g {
  stop-color: var(--svg-color--634d4b, #634D4B);
}

.x6_m96bez {
  stop-color: var(--svg-color--85d1fb, #85D1FB);
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

.xgq6w0b8s {
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.637-.217.723-.129c.1.103.145.418-.093.696c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.014-.561.256-.764");
}

.xkhh7vb2n {
  stop-color: var(--svg-color--371e27, #371E27);
  stop-opacity: 0;
}

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.ybvm9tprh {
  stop-color: var(--svg-color--594d4d, #594D4D);
}

.yezlp2beb {
  stop-color: var(--svg-color--8467c6, #8467C6);
  stop-opacity: 0;
}

.yf70htb_x {
  stop-color: var(--svg-color--5a4343, #5A4343);
}

.yh6bisb1t {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("m15.929 7.74l-.234.748a.237.237 0 0 0 .229.308h.346a.238.238 0 0 0 .229-.308l-.234-.748c-.05-.165-.284-.165-.336 0");
}

.yjx7cpa9w {
  cx: 15.018px;
  cy: 7.595px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.171px;
  ry: 0.087px;
}

.ytl8wkbiv {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.403 6.325a.21.21 0 0 0-.417.048l.159 1.385l-1.024-.928a.21.21 0 1 0-.282.311l5.73 5.192a.21.21 0 0 0 .282-.312l-4.235-3.836z");
}

.yv4uycbmh {
  stop-color: var(--svg-color--43272a, #43272A);
}

.yxwqgvbem {
  stop-color: var(--svg-color--594d4d, #594D4D);
  stop-opacity: 0;
}

.z_5s59bdn {
  width: 4.843px;
  height: 8.244px;
  rx: 2.422px;
}

.z_wfxjr5n {
  stop-color: var(--svg-color--392526, #392526);
}

.z0_tnl66g {
  stop-color: var(--svg-color--6c2d29, #6C2D29);
  stop-opacity: 0;
}

.z45oacyxz {
  d: path("m17.397 26.507l-.62 1.014c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l.466-1.017z");
}

.z5e-1sbyl {
  stop-color: var(--svg-color--5f4a49, #5F4A49);
  stop-opacity: 0;
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.z9-ns_cqv {
  stop-color: var(--svg-color--916ed5, #916ED5);
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zepkmwb6a {
  fill: var(--svg-color--8569c7, #8569C7);
  d: path("M13.14 20.535c.012-.367.07-2.827.1-4.093a.1.1 0 0 1 .088-.096c1.341-.13 4.082-.09 5.365-.052c.043.001.08.03.091.073c.237.855.655 2.465.692 2.605c.037.144-.016.237-.047.266c-.398.03-.937.539-2.336 1.054c-1.398.516-2.742.61-3.195.594c-.363-.012-.517.012-.584.086c-.034-.013-.174-.144-.174-.437");
}

.zgul-bc_h {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m17.155 6.06l-.627.116a.303.303 0 1 1-.055-.6h1.03c.608 0 .81.613.835.823a1.38 1.38 0 0 0-1.183-.338");
}

.zqax3vbfg {
  stop-color: var(--svg-color--6c2d29, #6C2D29);
}

.zx20zqh8j {
  stop-color: var(--svg-color--3f2628, #3F2628);
}

.zz3980hzg {
  stop-color: var(--svg-color--382223, #382223);
}

.zz4mcgrzh {
  stop-color: var(--svg-color--59403d, #59403D);
  stop-opacity: 0;
}

</style>
