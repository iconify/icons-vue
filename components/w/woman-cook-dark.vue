<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iuUH8Nc)"><path fill="url(#irIqlse)" class="r5-szbvjx"/><path fill="url(#i3rIjkb)" class="r5-szbvjx"/><path fill="url(#iDN09nb)" class="r5-szbvjx"/><path fill="url(#iKhdKsd)" class="r5-szbvjx"/><path fill="url(#iaRblhu)" class="r5-szbvjx"/></g><g filter="url(#iSk1Nnv)"><path fill="url(#idc93fe)" class="knts5rvii"/><path fill="url(#indqUPP)" class="knts5rvii"/></g><g filter="url(#i5vVWMb)"><path fill="url(#ineAwuc)" class="cwgu7k_nl"/></g><g filter="url(#iR41Tec)"><path class="mishw9b8d"/><path fill="url(#iwN3ozL)" class="g6g-8s-du"/></g><g filter="url(#iUpuZ9d)"><path class="b2twtwb8b"/><path fill="url(#iZGQtrb)" class="fmeq6lw4s"/></g><path class="z-8m36bgw"/><path fill="url(#i6Q7Arb)" class="d4xmk0b3j"/><path fill="url(#iNxlwTc)" class="s0up2ofes"/><path fill="url(#iuXwEZd)" class="s0up2ofes"/><path fill="url(#iBuEORd)" class="vivl3bbaz"/><path fill="url(#iRGFhLe)" class="vivl3bbaz"/><path fill="url(#iNovYtb)" class="vivl3bbaz"/><g filter="url(#ibxGBic)"><path fill="url(#ivXY0Tc)" class="culjfgb6b"/><path fill="url(#ivlHRoZ)" class="culjfgb6b"/></g><path fill="url(#if8mNmd)" class="culjfgb6b"/><path fill="url(#iPniQ2F)" class="culjfgb6b"/><g filter="url(#iDtHzJb)"><path fill="url(#iRBALDd)" class="zrix05bns"/></g><path fill="url(#iw6GASc)" class="ta097zets"/><path fill="url(#iqRJNvb)" class="ta097zets"/><g filter="url(#iZ34FCs)"><path class="ks6uwgbqn"/></g><g filter="url(#i9SSVod)"><path class="dlorr8a8v"/></g><g filter="url(#iTCGPMc)"><path class="we918tb1b"/></g><g filter="url(#it0Xu8d)"><path fill="url(#iOQP83d)" class="vaajtxp-t"/></g><g filter="url(#iZ9kOEZ)"><path fill="url(#iGIsVnb)" class="pxq1imbec"/></g><g filter="url(#i2jkIOl)"><path fill="url(#iJAwAjb)" class="mm1hckblm"/></g><path fill="url(#iZKFWmb)" class="d782hz2ag"/><path fill="url(#iPjBjRc)" class="d782hz2ag"/><path fill="url(#iGVHtab)" class="o0w2j91ou"/><path fill="url(#ifpwYEd)" class="o0w2j91ou"/><path fill="url(#ifcCE3Z)" class="o0w2j91ou"/><path fill="url(#iLb5BXd)" class="sq4b26tbv"/><path fill="url(#ip8UcMe)" class="sq4b26tbv"/><path fill="url(#inR9CKb)" class="sq4b26tbv"/><path fill="url(#iraMPMe)" class="sq4b26tbv"/><g filter="url(#icoq4Ex)"><path fill="url(#iKuC7od)" class="witvnebrl"/></g><g filter="url(#ig7jneZ)"><path class="tm7_tclbt"/><path fill="url(#ii58Juu)" class="g2m812b4x"/></g><g filter="url(#ieIlIFe)"><ellipse fill="url(#i8q6TLe)" class="fvx2uhr7a"/></g><g filter="url(#iYQzXYF)"><path fill="url(#i4ftnop)" class="xndjovbcx"/><path fill="url(#i50v4dd)" class="xndjovbcx"/><path fill="url(#ic3u5AC)" class="xndjovbcx"/><path fill="url(#i926Srd)" class="xndjovbcx"/><path fill="url(#iTnAw9f)" class="xndjovbcx"/></g><g filter="url(#ivvonRd)"><path stroke="url(#i9SetXd)" class="z9hvqlmkw"/></g><g filter="url(#iggJWkb)"><path stroke="url(#i7rg3Je)" class="nuvoe1kxk"/></g><g filter="url(#iLzpElb)"><path stroke="url(#iuEw1ob)" class="jz3m6rble"/></g><g filter="url(#ibvo8tr)"><path fill="url(#ioviYBb)" class="fz3kmczkm"/><path fill="url(#igxbaNb)" class="fz3kmczkm"/><path fill="url(#intAiSc)" class="fz3kmczkm"/><path fill="url(#il3daed)" class="fz3kmczkm"/><path fill="url(#iXR4PXP)" class="fz3kmczkm"/><path fill="url(#iPOojsc)" class="fz3kmczkm"/><path fill="url(#iq98Anc)" class="fz3kmczkm"/><path fill="url(#iyAB0Jb)" class="fz3kmczkm"/></g><path fill="url(#ioTIYJb)" class="fz3kmczkm"/><path fill="url(#iwVGUFc)" class="fz3kmczkm"/><path fill="url(#icVfPFs)" class="fz3kmczkm"/><path fill="url(#ihGonnc)" class="fz3kmczkm"/><g filter="url(#idowKIb)"><path class="ymjtedccx"/></g><g filter="url(#iNJxzqc)"><path class="d7o4sguoe"/><path fill="url(#izFGFXa)" class="f5ldw_unp"/><path fill="url(#iYTRJ0H)" class="f5ldw_unp"/><path fill="url(#iVOjRPX)" class="f5ldw_unp"/><path fill="url(#irGNvzN)" class="f5ldw_unp"/></g><g filter="url(#iJqMhie)"><path class="e5lem9rhk"/><path fill="url(#imuGxNd)" class="lln0dibai"/><path fill="url(#iPXHunb)" class="lln0dibai"/><path fill="url(#itGUtre)" class="lln0dibai"/><path fill="url(#is9I9pc)" class="lln0dibai"/></g><path stroke="url(#iqRiVVd)" class="thzjqhb9u"/><g filter="url(#iAYmNle)"><path class="n8ow6evna"/></g><g filter="url(#iLiMAse)"><path class="xipfy3bpt"/></g><g filter="url(#i8wEodA)"><path class="btzkekrbz"/></g><g filter="url(#ic2yPcd)"><path class="q45v9k5uz"/></g><g filter="url(#ifIz9FA)"><path fill="url(#i7D3Nve)" class="qyvx9o--i"/><path fill="url(#i48iIee)" class="qyvx9o--i"/></g><path fill="url(#iaPcOOb)" class="mgxw63k1g"/><path fill="url(#ilsPkLd)" class="mgxw63k1g"/><g filter="url(#iF7l7Id)"><path fill="url(#irCon5b)" class="s5yw-y39h"/></g><g filter="url(#ijcsl1b)"><path fill="url(#iadJa9U)" class="rxrf7k7qa"/></g><g filter="url(#iUzBtcb)"><path fill="url(#iGOB6ad)" class="tjpp4ubfg"/></g><g filter="url(#iZNbhhe)"><path class="sux0flb7d"/></g><g filter="url(#ibe1wSb)"><path class="y9x8350wz"/></g><path class="c2ur4cb1j"/><path fill="url(#iHW1lOd)" class="jqt_1oovp"/><path class="u5hst-xdb"/><g filter="url(#i0ft1Fe)"><path class="ak2e_vlpn"/><path fill="url(#iSFvazm)" class="d_x4iobyo"/></g><g filter="url(#iFSlAuc)"><path fill="url(#iLbgK5c)" class="d0wn_9lcq"/></g><path class="sew__yb9v"/><path fill="url(#i3VtJub)" class="cpn4y3bli"/><path class="q10e57bep"/><g filter="url(#iFjT4wb)"><path fill="url(#ialVzue)" class="fhji1r5-q"/></g><g filter="url(#izbPfPb)"><ellipse transform="rotate(-27.914 13.651 9.903)" class="nb__3g1ld"/><ellipse fill="url(#iouQCxd)" transform="rotate(-27.914 13.651 9.903)" class="cydhbw0vk"/></g><defs><radialGradient id="i3rIjkb" cx="0" cy="0" r="1" gradientTransform="rotate(140.889 3.889 5.3)scale(4.24611 1.6566)" gradientUnits="userSpaceOnUse"><stop offset=".267" class="yd_laccri"/><stop offset="1" class="dmf0acl5m"/></radialGradient><radialGradient id="iDN09nb" cx="0" cy="0" r="1" gradientTransform="matrix(2.11985 0 0 3.47579 20.286 7.637)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="w9txrw6kc"/><stop offset="1" class="h-4ghpb7u"/></radialGradient><radialGradient id="iKhdKsd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.90841 -5.85233 0 14.832 12.594)" gradientUnits="userSpaceOnUse"><stop offset=".493" class="dc6jrkblm"/><stop offset="1" class="oy6n6fbyn"/></radialGradient><radialGradient id="iaRblhu" cx="0" cy="0" r="1" gradientTransform="rotate(117.05 7.923 13.539)scale(2.23819 1.04512)" gradientUnits="userSpaceOnUse"><stop class="jsa0_reur"/><stop offset="1" class="j1xr6ccfb"/></radialGradient><radialGradient id="idc93fe" cx="0" cy="0" r="1" gradientTransform="rotate(-43.767 24.376 -21.165)scale(1.62195 2.626)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="indqUPP" cx="0" cy="0" r="1" gradientTransform="matrix(.61918 .73134 -.23906 .2024 21.898 8.878)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="iwN3ozL" cx="0" cy="0" r="1" gradientTransform="matrix(-.46565 0 0 -.83288 10.761 10.542)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="pj2ff5nxp"/><stop offset="1" class="sdufqstmc"/></radialGradient><radialGradient id="iZGQtrb" cx="0" cy="0" r="1" gradientTransform="matrix(.66527 -.09951 .15385 1.02855 21.347 10.638)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="i6Q7Arb" cx="0" cy="0" r="1" gradientTransform="rotate(22.533 -35.296 58.621)scale(3.18029 4.8153)" gradientUnits="userSpaceOnUse"><stop offset=".385" class="rx-3xm54t"/><stop offset="1" class="c55r95ylo"/></radialGradient><radialGradient id="iuXwEZd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.95598 3.29746 0 24.142 30.123)" gradientUnits="userSpaceOnUse"><stop class="q2rhgqb4s"/><stop offset="1" class="fs29nabkl"/><stop offset="1" class="sli_wqbvh"/></radialGradient><radialGradient id="iNovYtb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.375 .96875 0 7.583 30.627)" gradientUnits="userSpaceOnUse"><stop class="g2ynuf2dq"/><stop offset="1" class="ef22fkbzm"/></radialGradient><radialGradient id="ivXY0Tc" cx="0" cy="0" r="1" gradientTransform="matrix(-9.19932 8.68114 -6.69848 -7.09832 21.184 19.598)" gradientUnits="userSpaceOnUse"><stop class="m6lhrcc1m"/><stop offset="1" class="hm5-ozbqx"/></radialGradient><radialGradient id="ivlHRoZ" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.04958 5.03716 0 21.848 32.37)" gradientUnits="userSpaceOnUse"><stop class="fg0e2bc1h"/><stop offset="1" class="qk3h5tshn"/></radialGradient><radialGradient id="if8mNmd" cx="0" cy="0" r="1" gradientTransform="rotate(75.069 -5.22 16.285)scale(4.00951 7.09045)" gradientUnits="userSpaceOnUse"><stop class="kvw7exb6q"/><stop offset="1" class="dbx8xub5a"/></radialGradient><radialGradient id="iw6GASc" cx="0" cy="0" r="1" gradientTransform="rotate(161.865 9.23 10.104)scale(9.17449 5.46828)" gradientUnits="userSpaceOnUse"><stop class="bjmh7ubhg"/><stop offset="1" class="qishm1b5n"/></radialGradient><radialGradient id="iqRJNvb" cx="0" cy="0" r="1" gradientTransform="rotate(165.355 6.837 8.607)scale(4.92754 2.8404)" gradientUnits="userSpaceOnUse"><stop offset=".383" class="arr7-5bxc"/><stop offset="1" class="mejh1wbdq"/></radialGradient><radialGradient id="iZKFWmb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68781 1.6831 -2.07966 -2.08548 28.17 23.242)" gradientUnits="userSpaceOnUse"><stop offset=".493" class="k7qyxzbsl"/><stop offset=".946" class="zdypug-8z"/></radialGradient><radialGradient id="iPjBjRc" cx="0" cy="0" r="1" gradientTransform="matrix(.76222 -.58036 .30308 .39805 27.844 23.459)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="m8ott3b3k"/><stop offset="1" class="zk5cvukoj"/></radialGradient><radialGradient id="iGVHtab" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79689 3.03124 -1.67446 -.9926 15.317 19.205)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="uvk62nj4e"/><stop offset="1" class="xglbqnshq"/></radialGradient><radialGradient id="ifpwYEd" cx="0" cy="0" r="1" gradientTransform="matrix(.6875 2 -1.40698 .48365 15.677 18.08)" gradientUnits="userSpaceOnUse"><stop offset=".337" class="ggu_gwb1x"/><stop offset="1" class="krdg4pblj"/></radialGradient><radialGradient id="ifcCE3Z" cx="0" cy="0" r="1" gradientTransform="matrix(.68561 -1.32812 .78813 .40685 14.788 20.376)" gradientUnits="userSpaceOnUse"><stop class="ntfgudbzu"/><stop offset="1" class="yonw8mbnr"/></radialGradient><radialGradient id="iLb5BXd" cx="0" cy="0" r="1" gradientTransform="matrix(2.02274 3.47509 -2.70205 1.57278 17.654 18.495)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="z9vs4zbzi"/><stop offset="1" class="azczfcb4o"/></radialGradient><radialGradient id="inR9CKb" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 1.07812 -.87238 -.40458 16.208 18.799)" gradientUnits="userSpaceOnUse"><stop class="ggu_gwb1x"/><stop offset="1" class="f5jyocccx"/></radialGradient><radialGradient id="iraMPMe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46875 -2.60938 .90065 -.50695 19.145 21.205)" gradientUnits="userSpaceOnUse"><stop offset=".371" class="yihpasnlf"/><stop offset="1" class="r6w240bct"/></radialGradient><radialGradient id="ii58Juu" cx="0" cy="0" r="1" gradientTransform="rotate(153.435 11.936 11.256)scale(1.57224 3.24929)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="via-_dbpm"/><stop offset="1" class="bt1_2zb2r"/></radialGradient><radialGradient id="i8q6TLe" cx="0" cy="0" r="1" gradientTransform="matrix(2.27907 0 0 3.27907 24.876 17.813)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="uelaalb7d"/><stop offset=".746" class="i5m4wsx9z"/></radialGradient><radialGradient id="i50v4dd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 26.199 25.195)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="ic3u5AC" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 26.199 26.49)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="i926Srd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 26.199 27.74)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iTnAw9f" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 26.199 29.091)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="ioviYBb" cx="0" cy="0" r="1" gradientTransform="rotate(155.407 8.472 7.037)scale(7.36936 9.81575)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="aj61gebdf"/><stop offset="1" class="v2xpqhbrh"/></radialGradient><radialGradient id="igxbaNb" cx="0" cy="0" r="1" gradientTransform="rotate(154.68 7.81 7.412)scale(2.32122 1.60883)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="x7h3p2bdy"/></radialGradient><radialGradient id="intAiSc" cx="0" cy="0" r="1" gradientTransform="matrix(1.10604 -3.5548 4.53832 1.41205 13.913 16.845)" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></radialGradient><radialGradient id="il3daed" cx="0" cy="0" r="1" gradientTransform="rotate(96.777 3.886 12.458)scale(7.00292 7.09189)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="m6mmhsf1n"/><stop offset="1" class="do3fwrbgr"/></radialGradient><radialGradient id="iXR4PXP" cx="0" cy="0" r="1" gradientTransform="scale(6.80233 6.71561)rotate(90 .4 1.935)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="d0fyzsbqc"/><stop offset="1" class="n8ysctycz"/></radialGradient><radialGradient id="iPOojsc" cx="0" cy="0" r="1" gradientTransform="rotate(168.875 8.443 6.717)scale(7.10178 12.1425)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="jwznzqbnr"/><stop offset="1" class="fgjvektso"/></radialGradient><radialGradient id="iq98Anc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17683 1.45515 0 18.53 9.481)" gradientUnits="userSpaceOnUse"><stop class="yv4uycbmh"/><stop offset="1" class="wgpm0ibqw"/></radialGradient><radialGradient id="iyAB0Jb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34224 1.54986 0 14.02 9.248)" gradientUnits="userSpaceOnUse"><stop class="f82mfcbsw"/><stop offset="1" class="xkhh7vb2n"/></radialGradient><radialGradient id="ioTIYJb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.32427 0 0 -6.59153 21.409 11.002)" gradientUnits="userSpaceOnUse"><stop class="jids0zpwm"/><stop offset="1" class="zz4mcgrzh"/></radialGradient><radialGradient id="iwVGUFc" cx="0" cy="0" r="1" gradientTransform="rotate(139.492 7.306 11.297)scale(2.47858 1.65931)" gradientUnits="userSpaceOnUse"><stop class="ybvm9tprh"/><stop offset=".694" class="yxwqgvbem"/></radialGradient><radialGradient id="icVfPFs" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.56254 -7.96563 0 16.159 7.134)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="k1yc-6bgn"/><stop offset="1" class="enui4qbiv"/></radialGradient><radialGradient id="ihGonnc" cx="0" cy="0" r="1" gradientTransform="rotate(78.393 6.182 17.232)scale(3.3615 2.11543)" gradientUnits="userSpaceOnUse"><stop class="rqvudbcva"/><stop offset="1" class="zdd_-i6yb"/></radialGradient><radialGradient id="izFGFXa" cx="0" cy="0" r="1" gradientTransform="rotate(-101.645 13.267 -.963)scale(2.25681 .64762)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="irGNvzN" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.23563 16.65 12.066)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="imuGxNd" cx="0" cy="0" r="1" gradientTransform="matrix(-.7809 -.8176 .59278 -.56618 17.45 14.111)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="is9I9pc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.33612 0 0 -.08716 17.038 14.196)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="i7D3Nve" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.96438 18.8689 0 12.989 5.97)" gradientUnits="userSpaceOnUse"><stop offset=".244" class="ysetj63ow"/><stop offset="1" class="e1v2e-byl"/></radialGradient><radialGradient id="i48iIee" cx="0" cy="0" r="1" gradientTransform="matrix(-15.4062 0 0 -5.61228 24.801 2.814)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="iwq_irb5j"/><stop offset="1" class="hbnhp-b1r"/></radialGradient><radialGradient id="iaPcOOb" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -2.75 8.9809 -.10205 19.27 7.025)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="ox62rwbrf"/><stop offset="1" class="g4wbwbcoe"/></radialGradient><radialGradient id="iHW1lOd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.286 10)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iSFvazm" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.498 .62)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i3VtJub" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.922 10)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iouQCxd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.636 10.218)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iuUH8Nc" width="15.95" height="13.5" x="7.784" y="4.252" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.152941 0 0 0 0 0.101961 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1875"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.337255 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1875" result="effect2_innerShadow_4002_1875"/></filter><filter id="iSk1Nnv" width="1.514" height="3.441" x="21.026" y="8.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1875"/></filter><filter id="i5vVWMb" width="1.671" height="3.2" x="9.668" y="8.941" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1875"/></filter><filter id="iR41Tec" width="1.329" height="2.379" x="10.072" y="9.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1875" stdDeviation=".125"/></filter><filter id="iUpuZ9d" width="1.947" height="2.903" x="20.566" y="9.087" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1875" stdDeviation=".25"/></filter><filter id="ibxGBic" width="14.3" height="12.3" x="8.829" y="17.921" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.972549 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1875"/></filter><filter id="iDtHzJb" width="6.538" height="5.771" x="12.472" y="16.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1875" stdDeviation=".325"/></filter><filter id="iZ34FCs" width="2.5" height="2.5" x="18.92" y="26.946" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1875" stdDeviation=".25"/></filter><filter id="i9SSVod" width="2.5" height="2.5" x="18.92" y="23.306" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1875" stdDeviation=".25"/></filter><filter id="iTCGPMc" width="2.5" height="2.5" x="18.92" y="19.676" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1875" stdDeviation=".25"/></filter><filter id="it0Xu8d" width="1.7" height="1.7" x="19.59" y="27.201" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1875"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1875" result="effect2_innerShadow_4002_1875"/></filter><filter id="iZ9kOEZ" width="1.7" height="1.7" x="19.59" y="23.561" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1875"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1875" result="effect2_innerShadow_4002_1875"/></filter><filter id="i2jkIOl" width="1.7" height="1.7" x="19.59" y="19.931" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.521569 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1875"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.658824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1875" result="effect2_innerShadow_4002_1875"/></filter><filter id="icoq4Ex" width="2.238" height="1.809" x="14.98" y="17.259" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.266667 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1875"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.65098 0 0 0 0 0.176471 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1875" result="effect2_innerShadow_4002_1875"/></filter><filter id="ig7jneZ" width="5.047" height="11.336" x="23.532" y="14.814" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.521569 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1875"/></filter><filter id="ieIlIFe" width="3.672" height="4.703" x="23.995" y="15.258" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.890196 0 0 0 0 0.647059 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1875"/><feGaussianBlur result="effect2_foregroundBlur_4002_1875" stdDeviation=".05"/></filter><filter id="iYQzXYF" width="4.468" height="5.556" x="23.762" y="24.335" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.117647 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1875"/></filter><filter id="ivvonRd" width="2.097" height=".3" x="24.132" y="25.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1875" stdDeviation=".05"/></filter><filter id="iggJWkb" width="2.097" height=".3" x="24.053" y="27.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1875" stdDeviation=".05"/></filter><filter id="iLzpElb" width="2.097" height=".3" x="24.132" y="28.328" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1875" stdDeviation=".05"/></filter><filter id="ibvo8tr" width="10.5" height="11.373" x="10.909" y="5.441" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0901961 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1875"/></filter><filter id="idowKIb" width="2.877" height="3.9" x="14.459" y="9.476" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1875" stdDeviation=".25"/></filter><filter id="iNJxzqc" width="2.377" height="3.4" x="14.916" y="9.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1875" stdDeviation=".125"/></filter><filter id="iJqMhie" width="3.718" height="1.573" x="14.245" y="13.101" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1875" stdDeviation=".125"/></filter><filter id="iAYmNle" width="2.439" height="1.19" x="17.694" y="7.381" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1875"/></filter><filter id="iLiMAse" width="2.439" height="1.176" x="12.437" y="7.388" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1875"/></filter><filter id="i8wEodA" width="2.105" height=".86" x="12.506" y="7.613" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1875" stdDeviation=".075"/></filter><filter id="ic2yPcd" width="2.105" height=".869" x="17.785" y="7.565" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1875" stdDeviation=".075"/></filter><filter id="ifIz9FA" width="14.779" height="5.543" x="8.765" y="2.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.790803 0 0 0 0 0.768636 0 0 0 0 0.790803 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1875"/></filter><filter id="iF7l7Id" width=".675" height="2.047" x="13.012" y="3.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1875" stdDeviation=".05"/></filter><filter id="ijcsl1b" width=".675" height="2.047" x="18.6" y="3.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1875" stdDeviation=".05"/></filter><filter id="iUzBtcb" width=".98" height="2.537" x="15.669" y="3.459" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1875" stdDeviation=".1"/></filter><filter id="iZNbhhe" width="2.611" height="1.227" x="17.394" y="9.033" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.101961 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1875"/></filter><filter id="ibe1wSb" width="2.611" height="1.227" x="12.206" y="9.033" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.101961 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1875"/></filter><filter id="i0ft1Fe" width=".787" height=".696" x="17.552" y="9.559" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1875" stdDeviation=".05"/></filter><filter id="iFSlAuc" width=".891" height=".913" x="18.392" y="9.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1875" stdDeviation=".1"/></filter><filter id="iFjT4wb" width=".986" height="1.04" x="13.949" y="9.571" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1875" stdDeviation=".1"/></filter><filter id="izbPfPb" width=".913" height=".705" x="13.194" y="9.551" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1875" stdDeviation=".05"/></filter><linearGradient id="irIqlse" x1="22.488" x2="15.005" y1="6.409" y2="18.607" gradientUnits="userSpaceOnUse"><stop class="oco3zrb8c"/><stop offset=".862" class="rgx7dt08r"/></linearGradient><linearGradient id="ineAwuc" x1="9.668" x2="11.067" y1="10.628" y2="10.628" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="qenr6bbwz"/></linearGradient><linearGradient id="iNxlwTc" x1="23.287" x2="26.53" y1="25.789" y2="25.789" gradientUnits="userSpaceOnUse"><stop offset=".091" class="hoo7nhmax"/><stop offset="1" class="n_q7hvb5a"/></linearGradient><linearGradient id="iBuEORd" x1="8.27" x2="8.27" y1="30.908" y2="16.845" gradientUnits="userSpaceOnUse"><stop offset=".06" class="rvini-b1k"/><stop offset="1" class="si_znv48i"/><stop offset="1" class="akw2ge0vx"/></linearGradient><linearGradient id="iRGFhLe" x1="9.129" x2="8.551" y1="26.533" y2="26.533" gradientUnits="userSpaceOnUse"><stop class="wfl-8sksi"/><stop offset="1" class="frvthebdh"/></linearGradient><linearGradient id="iPniQ2F" x1="9.129" x2="13.066" y1="27.119" y2="27.119" gradientUnits="userSpaceOnUse"><stop class="fj7z_vbcj"/><stop offset="1" class="zab3c9ypw"/></linearGradient><linearGradient id="iRBALDd" x1="16.738" x2="13.777" y1="22.039" y2="18.654" gradientUnits="userSpaceOnUse"><stop class="d8t95rbxw"/><stop offset="1" class="iaqn2jf-r"/></linearGradient><linearGradient id="iOQP83d" x1="20.958" x2="19.689" y1="27.553" y2="28.959" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="iGIsVnb" x1="20.958" x2="19.689" y1="23.913" y2="25.319" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="iJAwAjb" x1="20.958" x2="19.689" y1="20.283" y2="21.689" gradientUnits="userSpaceOnUse"><stop class="blglnkbti"/><stop offset="1" class="o89su3kwg"/></linearGradient><linearGradient id="ip8UcMe" x1="16.833" x2="17.817" y1="17.908" y2="19.08" gradientUnits="userSpaceOnUse"><stop class="mr2z2cjsz"/><stop offset="1" class="f-058ybfx"/></linearGradient><linearGradient id="iKuC7od" x1="16.348" x2="16.348" y1="18.798" y2="17.359" gradientUnits="userSpaceOnUse"><stop class="mdp-0w-om"/><stop offset="1" class="d9jlp6fce"/><stop offset="1" class="j4tnsxbxg"/></linearGradient><linearGradient id="i4ftnop" x1="27.79" x2="23.762" y1="27.953" y2="27.953" gradientUnits="userSpaceOnUse"><stop offset=".146" class="o3k0towjz"/><stop offset=".861" class="qxb7siz6w"/></linearGradient><linearGradient id="i9SetXd" x1="24.282" x2="25.991" y1="25.947" y2="25.947" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="i7rg3Je" x1="24.203" x2="25.913" y1="27.252" y2="27.252" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="iuEw1ob" x1="24.282" x2="25.991" y1="28.556" y2="28.556" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="iYTRJ0H" x1="15.166" x2="16.104" y1="11.916" y2="11.916" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iVOjRPX" x1="16.104" x2="16.104" y1="12.78" y2="12.12" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="iPXHunb" x1="14.495" x2="16.104" y1="14.14" y2="14.14" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="itGUtre" x1="16.104" x2="16.104" y1="14.46" y2="14.216" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="iqRiVVd" x1="15.067" x2="15.502" y1="14.296" y2="13.608" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="ilsPkLd" x1="16.739" x2="16.739" y1="7.689" y2="7.002" gradientUnits="userSpaceOnUse"><stop class="gjkvqmbnm"/><stop offset="1" class="f1s8bobxq"/></linearGradient><linearGradient id="irCon5b" x1="13.485" x2="12.907" y1="5.542" y2="5.444" gradientUnits="userSpaceOnUse"><stop offset=".297" class="u7axe2baw"/><stop offset="1" class="dv8o3t25w"/></linearGradient><linearGradient id="iadJa9U" x1="19.127" x2="18.494" y1="5.35" y2="5.444" gradientUnits="userSpaceOnUse"><stop offset=".246" class="ahul9kboj"/><stop offset="1" class="ongktybvd"/></linearGradient><linearGradient id="iGOB6ad" x1="16.448" x2="16.448" y1="5.686" y2="3.659" gradientUnits="userSpaceOnUse"><stop offset=".1" class="ztvu2mbem"/><stop offset="1" class="bm3jemb-u"/></linearGradient><linearGradient id="iLbgK5c" x1="19.064" x2="18.751" y1="10.053" y2="10.246" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ialVzue" x1="14.666" x2="14.352" y1="10.053" y2="10.246" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-cook-dark" /></template>
<style>
.ahul9kboj {
  stop-color: var(--svg-color--a499b2, #A499B2);
}

.aj61gebdf {
  stop-color: var(--svg-color--4f322e, #4F322E);
}

.ak2e_vlpn {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.223 9.71c.064.086-.07.19-.22.303c-.152.113-.264.192-.327.107c-.064-.085.007-.246.158-.359s.325-.135.389-.05");
}

.akw2ge0vx {
  stop-color: var(--svg-color--9b9598, #9B9598);
}

.arr7-5bxc {
  stop-color: var(--svg-color--8d0c24, #8D0C24);
}

.ayiod_bfg {
  stop-color: var(--svg-color--493033, #493033);
}

.azczfcb4o {
  stop-color: var(--svg-color--bf2245, #BF2245);
}

.b2twtwb8b {
  fill: var(--svg-color--4c3637, #4C3637);
  d: path("M21.066 11.49q.059-.952.11-1.903a.956.956 0 0 1-.11 1.903");
}

.bjmh7ubhg {
  stop-color: var(--svg-color--e94574, #E94574);
}

.blglnkbti {
  stop-color: var(--svg-color--a698ab, #A698AB);
}

.bm3jemb-u {
  stop-color: var(--svg-color--9c8fab, #9C8FAB);
  stop-opacity: 0;
}

.bt1_2zb2r {
  stop-color: var(--svg-color--eaae7e, #EAAE7E);
  stop-opacity: 0;
}

.btzkekrbz {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.731 8.248c.257-.184.898-.509 1.655-.381");
}

.c2ur4cb1j {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.496 9.25c.653 0 1.204.45 1.354 1.06a.274.274 0 0 1-.267.34h-2.231a.23.23 0 0 1-.228-.272a1.4 1.4 0 0 1 1.372-1.128");
}

.c55r95ylo {
  stop-color: var(--svg-color--dccad4, #DCCAD4);
  stop-opacity: 0;
}

.cctx1cb1y {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cpn4y3bli {
  d: path("M13.92 9.522a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.crde6o_5i {
  stop-color: var(--svg-color--402824, #402824);
  stop-opacity: 0;
}

.culjfgb6b {
  d: path("M9.13 17.92h10.052c2.176 0 3.947 1.797 3.947 4.004v7.997h-14z");
}

.cwgu7k_nl {
  d: path("M11.05 8.941a1.61 1.61 0 0 0 .139 3.2a78 78 0 0 1-.139-3.2");
}

.cydhbw0vk {
  cx: 13.651px;
  cy: 9.903px;
  rx: 0.39px;
  ry: 0.197px;
}

.d_x4iobyo {
  d: path("M18.223 9.71c.064.086-.07.19-.22.303c-.152.113-.264.192-.327.107c-.064-.085.007-.246.158-.359s.325-.135.389-.05");
}

.d0fyzsbqc {
  stop-color: var(--svg-color--3b232b, #3B232B);
  stop-opacity: 0;
}

.d0wn_9lcq {
  d: path("M19.083 10.297a.84.84 0 0 0-.231-.463l-.26.286l.117.228z");
}

.d4xmk0b3j {
  d: path("M16.11 15.39c-6.07 0-10.98 4.92-10.98 10.98v3.55h4v-.06h14v.06h4v-3.5c0-3.422-1.554-6.482-4-8.5v.014a10.92 10.92 0 0 0-7.02-2.543");
}

.d782hz2ag {
  d: path("M27.112 22.978a.97.97 0 0 1 .967.967v2.214h-1.934v-2.214a.976.976 0 0 1 .967-.967");
}

.d7o4sguoe {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("m15.722 10.086l-.531 1.838c-.109.378.151.756.52.756h.787c.368 0 .629-.384.52-.756l-.531-1.838c-.114-.408-.646-.408-.765 0");
}

.d8t95rbxw {
  stop-color: var(--svg-color--aa7aa4, #AA7AA4);
}

.d9jlp6fce {
  stop-color: var(--svg-color--b1203d, #B1203D);
}

.dbx8xub5a {
  stop-color: var(--svg-color--a196a1, #A196A1);
  stop-opacity: 0;
}

.dc6jrkblm {
  stop-color: var(--svg-color--160c19, #160C19);
}

.dlorr8a8v {
  fill: var(--svg-color--bfa9d1, #BFA9D1);
  d: path("M20.17 25.306a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.dmf0acl5m {
  stop-color: var(--svg-color--565252, #565252);
  stop-opacity: 0;
}

.do3fwrbgr {
  stop-color: var(--svg-color--3f243b, #3F243B);
}

.dv8o3t25w {
  stop-color: var(--svg-color--9183a0, #9183A0);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1v2e-byl {
  stop-color: var(--svg-color--cac5ce, #CAC5CE);
}

.e5lem9rhk {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("M16.104 13.697c-.507 0-.984-.12-1.385-.329c-.137-.07-.284.085-.198.21c.335.507.919.845 1.583.845c.665 0 1.249-.338 1.584-.846c.086-.13-.061-.278-.198-.209a3 3 0 0 1-1.386.329");
}

.ef22fkbzm {
  stop-color: var(--svg-color--ac9fb8, #AC9FB8);
  stop-opacity: 0;
}

.entsizubv {
  stop-color: var(--svg-color--5e4745, #5E4745);
}

.enui4qbiv {
  stop-color: var(--svg-color--362028, #362028);
  stop-opacity: 0;
}

.f-058ybfx {
  stop-color: var(--svg-color--c52759, #C52759);
  stop-opacity: 0;
}

.f1s8bobxq {
  stop-color: var(--svg-color--9482a1, #9482A1);
  stop-opacity: 0;
}

.f5jyocccx {
  stop-color: var(--svg-color--9c1931, #9C1931);
  stop-opacity: 0;
}

.f5ldw_unp {
  d: path("m15.722 10.086l-.531 1.838c-.109.378.151.756.52.756h.787c.368 0 .629-.384.52-.756l-.531-1.838c-.114-.408-.646-.408-.765 0");
}

.f82mfcbsw {
  stop-color: var(--svg-color--371e27, #371E27);
}

.fg0e2bc1h {
  stop-color: var(--svg-color--beb0cc, #BEB0CC);
}

.fgjvektso {
  stop-color: var(--svg-color--644d4a, #644D4A);
}

.fhji1r5-q {
  d: path("M14.736 10.31c0-.289-.235-.48-.298-.539l-.289.279l.178.361z");
}

.fj7z_vbcj {
  stop-color: var(--svg-color--958d9d, #958D9D);
}

.fmeq6lw4s {
  d: path("M21.066 11.49q.059-.952.11-1.903a.956.956 0 0 1-.11 1.903");
}

.frvthebdh {
  stop-color: var(--svg-color--a498b2, #A498B2);
  stop-opacity: 0;
}

.fs29nabkl {
  stop-color: var(--svg-color--a78bb9, #A78BB9);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fvx2uhr7a {
  cx: 25.806px;
  cy: 17.634px;
  rx: 1.711px;
  ry: 2.227px;
}

.fz3kmczkm {
  d: path("M20.194 7.218H16.88c-1.314 0-2.508-.595-3.244-1.657a.272.272 0 0 0-.478.049l-.08.195a2.34 2.34 0 0 1-1.234 1.237a.4.4 0 0 1-.11.05c-.248.116-.816.486-.825 1.451l.139 3.236c.12 2.865 2.379 4.785 5.115 4.785c2.738 0 4.997-1.92 5.116-4.785l.13-3.08c-.02-1.355-1.026-1.481-1.215-1.481");
}

.g2m812b4x {
  d: path("M26.509 21.094c0-.405.26-.758.568-1.02c.605-.518 1.002-1.393 1.002-2.385c0-1.588-1.018-2.875-2.273-2.875s-2.274 1.287-2.274 2.875c0 .992.398 1.867 1.003 2.384c.308.263.568.616.568 1.021v5.056h1.406z");
}

.g2ynuf2dq {
  stop-color: var(--svg-color--ac9fb8, #AC9FB8);
}

.g4wbwbcoe {
  stop-color: var(--svg-color--a79da9, #A79DA9);
}

.g6g-8s-du {
  d: path("M11.067 9.602a.956.956 0 0 0 .084 1.88a78 78 0 0 1-.084-1.88");
}

.ggu_gwb1x {
  stop-color: var(--svg-color--9c1931, #9C1931);
}

.gjkvqmbnm {
  stop-color: var(--svg-color--9482a1, #9482A1);
}

.gl9okfban {
  stop-color: var(--svg-color--634d4b, #634D4B);
  stop-opacity: 0;
}

.h-4ghpb7u {
  stop-color: var(--svg-color--150a0d, #150A0D);
  stop-opacity: 0;
}

.hbnhp-b1r {
  stop-color: var(--svg-color--e7ddf2, #E7DDF2);
  stop-opacity: 0;
}

.hm5-ozbqx {
  stop-color: var(--svg-color--cfc5da, #CFC5DA);
}

.hoo7nhmax {
  stop-color: var(--svg-color--cbc3cb, #CBC3CB);
}

.i5m4wsx9z {
  stop-color: var(--svg-color--d68e4a, #D68E4A);
}

.iaqn2jf-r {
  stop-color: var(--svg-color--9c8395, #9C8395);
}

.iwq_irb5j {
  stop-color: var(--svg-color--f9f6fc, #F9F6FC);
}

.j1xr6ccfb {
  stop-color: var(--svg-color--3e3c3d, #3E3C3D);
  stop-opacity: 0;
}

.j4tnsxbxg {
  stop-color: var(--svg-color--ba2946, #BA2946);
}

.jids0zpwm {
  stop-color: var(--svg-color--59403d, #59403D);
}

.jqt_1oovp {
  d: path("M18.289 9.522a.892.892 0 0 1 .86 1.128h-1.725a.896.896 0 0 1 .864-1.128");
}

.jsa0_reur {
  stop-color: var(--svg-color--3e3c3d, #3E3C3D);
}

.jwznzqbnr {
  stop-color: var(--svg-color--644d4a, #644D4A);
  stop-opacity: 0;
}

.jz3m6rble {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.282 28.478h1.796");
}

.k1yc-6bgn {
  stop-color: var(--svg-color--362028, #362028);
}

.k7qyxzbsl {
  stop-color: var(--svg-color--4b312d, #4B312D);
}

.knts5rvii {
  d: path("M21.026 12.141q.1-1.595.185-3.191a1.61 1.61 0 0 1-.185 3.191");
}

.krdg4pblj {
  stop-color: var(--svg-color--c93356, #C93356);
  stop-opacity: 0;
}

.ks6uwgbqn {
  fill: var(--svg-color--c4abda, #C4ABDA);
  d: path("M20.92 28.196a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.kvw7exb6q {
  stop-color: var(--svg-color--a196a1, #A196A1);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lln0dibai {
  d: path("M16.104 13.697c-.507 0-.984-.12-1.385-.329c-.137-.07-.284.085-.198.21c.335.507.919.845 1.583.845c.665 0 1.249-.338 1.584-.846c.086-.13-.061-.278-.198-.209a3 3 0 0 1-1.386.329");
}

.m6lhrcc1m {
  stop-color: var(--svg-color--e1d7df, #E1D7DF);
}

.m6mmhsf1n {
  stop-color: var(--svg-color--3f243b, #3F243B);
  stop-opacity: 0;
}

.m8ott3b3k {
  stop-color: var(--svg-color--675655, #675655);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdp-0w-om {
  stop-color: var(--svg-color--c43656, #C43656);
}

.mejh1wbdq {
  stop-color: var(--svg-color--8d0c24, #8D0C24);
  stop-opacity: 0;
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mgxw63k1g {
  d: path("M22.185 5.846H10.132a.2.2 0 0 1 .028.101V7c0 .248.201.45.45.45h11.099a.45.45 0 0 0 .45-.45V5.944a.2.2 0 0 1 .026-.098");
}

.mishw9b8d {
  fill: var(--svg-color--35252b, #35252B);
  d: path("M11.067 9.602a.956.956 0 0 0 .084 1.88a78 78 0 0 1-.084-1.88");
}

.mm1hckblm {
  d: path("M20.44 21.531a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.mr2z2cjsz {
  stop-color: var(--svg-color--c52759, #C52759);
}

.n_q7hvb5a {
  stop-color: var(--svg-color--e7e2eb, #E7E2EB);
}

.n8ow6evna {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M19.837 8.085a1.85 1.85 0 0 0-.687-.412c-.304-.095-.685-.121-1.213-.057a.277.277 0 0 0 .068.55c.48-.058.776-.027.978.036c.198.063.333.164.49.301a.277.277 0 0 0 .364-.418");
}

.n8ysctycz {
  stop-color: var(--svg-color--2b151b, #2B151B);
}

.nb__3g1ld {
  cx: 13.651px;
  cy: 9.903px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.ntfgudbzu {
  stop-color: var(--svg-color--ea4067, #EA4067);
}

.nuvoe1kxk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.204 27.173H26");
}

.o0w2j91ou {
  d: path("M13.917 18.605c.67-.924 1.704-1.194 2.096-1.246c.206.83.308 2.667-.683 3.564c-.635.574-1.078.722-1.67.787c-.164.017-.27-.165-.222-.322c.03-.1.051-.22.053-.366c.01-.633-.109-1.68.426-2.417");
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.o89su3kwg {
  stop-color: var(--svg-color--9f8aa8, #9F8AA8);
}

.oco3zrb8c {
  stop-color: var(--svg-color--30282c, #30282C);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ongktybvd {
  stop-color: var(--svg-color--a499b2, #A499B2);
  stop-opacity: 0;
}

.ox62rwbrf {
  stop-color: var(--svg-color--e1dbe8, #E1DBE8);
}

.oy6n6fbyn {
  stop-color: var(--svg-color--160c19, #160C19);
  stop-opacity: 0;
}

.pj2ff5nxp {
  stop-color: var(--svg-color--2d181a, #2D181A);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pxq1imbec {
  d: path("M20.44 25.16a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.q10e57bep {
  fill: var(--svg-color--000, #000);
  d: path("M14.432 10.415a.51.51 0 0 0-.512-.511a.51.51 0 0 0-.454.746h.905a.5.5 0 0 0 .06-.235");
}

.q2rhgqb4s {
  stop-color: var(--svg-color--998ba1, #998BA1);
}

.q45v9k5uz {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.665 8.21c-.282-.298-.897-.51-1.655-.382");
}

.qenr6bbwz {
  stop-color: var(--svg-color--2a1c1f, #2A1C1F);
}

.qishm1b5n {
  stop-color: var(--svg-color--b22a4e, #B22A4E);
}

.qk3h5tshn {
  stop-color: var(--svg-color--beb0cc, #BEB0CC);
  stop-opacity: 0;
}

.qm132ccsa {
  stop-color: var(--svg-color--655251, #655251);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxb7siz6w {
  stop-color: var(--svg-color--3f282a, #3F282A);
}

.qyvx9o--i {
  d: path("M10.699 2.006a1.933 1.933 0 0 0-.682 3.743a.215.215 0 0 1 .143.198v1.052c0 .248.201.45.45.45h11.099a.45.45 0 0 0 .45-.45V5.944c0-.09.059-.166.142-.198a1.934 1.934 0 0 0-.69-3.74z");
}

.r5-szbvjx {
  d: path("M23.584 10.667c0-.71-.207-1.36-.562-1.911c-.545-.846-1.488-1.201-1.488-1.862v-.01c0-.92-.138-1.761-.493-2.382H10.724c-.305.62-.394 1.462-.394 2.382v.01c0 .66-1.203 1.128-1.685 1.862a3.5 3.5 0 0 0-.561 1.911c0 .54.118 1.041.335 1.501c.069.15.069.33 0 .48a3.4 3.4 0 0 0-.335 1.482c0 1.861 1.488 3.372 3.32 3.372h8.859c1.833 0 3.32-1.51 3.32-3.372c0-.53-.118-1.03-.334-1.481a.58.58 0 0 1 0-.48c.216-.461.335-.971.335-1.502");
}

.r6w240bct {
  stop-color: var(--svg-color--df3d53, #DF3D53);
  stop-opacity: 0;
}

.rgx7dt08r {
  stop-color: var(--svg-color--18111a, #18111A);
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
}

.rqvudbcva {
  stop-color: var(--svg-color--5c4644, #5C4644);
}

.rvini-b1k {
  stop-color: var(--svg-color--aa99ac, #AA99AC);
}

.rx-3xm54t {
  stop-color: var(--svg-color--dccad4, #DCCAD4);
}

.rxrf7k7qa {
  d: path("m18.7 5.796l.474-1.848v1.848z");
}

.s0up2ofes {
  d: path("M23.13 29.92h4v-3.5c0-3.422-1.554-6.482-4-8.5z");
}

.s5yw-y39h {
  d: path("m13.587 5.796l-.475-1.848v1.848z");
}

.s9u3_wbrp {
  stop-color: var(--svg-color--402824, #402824);
}

.sdufqstmc {
  stop-color: var(--svg-color--2d181a, #2D181A);
}

.sew__yb9v {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.714 9.25c-.654 0-1.205.45-1.356 1.06c-.044.174.09.34.268.34h2.232a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.372-1.128");
}

.si_znv48i {
  stop-color: var(--svg-color--9c979a, #9C979A);
}

.sli_wqbvh {
  stop-color: var(--svg-color--998ba1, #998BA1);
  stop-opacity: 0;
}

.sq4b26tbv {
  d: path("M18.312 18.605c-.67-.924-1.704-1.194-2.096-1.246c-.205.83-.308 2.667.684 3.564c.635.574 1.077.722 1.67.787c.163.017.268-.165.221-.322c-.03-.1-.051-.22-.053-.366c-.01-.633.109-1.68-.426-2.417");
}

.sux0flb7d {
  fill: var(--svg-color--302d32, #302D32);
  d: path("M18.613 9.185c-.766.04-1.099.422-1.219.613l2.012.461c.14.008.484-.086.563-.246a.31.31 0 0 0-.051-.363c-.176-.203-.674-.497-1.305-.465");
}

.t5djkhb4t {
  stop-color: var(--svg-color--655251, #655251);
}

.ta097zets {
  d: path("M23.539 18.276H8.69a10.94 10.94 0 0 1 7.42-2.885c3.483 0 5.152.811 7.429 2.885");
}

.thzjqhb9u {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.742 13.324a2.96 2.96 0 0 0 1.362.323a2.94 2.94 0 0 0 1.363-.323a.2.2 0 0 1 .242.04a.19.19 0 0 1 .02.241m-2.987-.281l2.946.253m-2.946-.253a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24m.262-.282l-.22.253m3.208.028l-.042-.028m.042.028l-.042-.028m.042.028a1.94 1.94 0 0 1-1.626.868c-.681 0-1.28-.347-1.624-.868m3.208-.028a1.9 1.9 0 0 1-1.584.846a1.9 1.9 0 0 1-1.583-.846m-.041.028l.041-.028m-.041.028l.041-.028");
}

.tjpp4ubfg {
  d: path("M15.869 3.659h.58v2.137h-.58z");
}

.tm7_tclbt {
  fill: var(--svg-color--e1a474, #E1A474);
  d: path("M26.509 21.094c0-.405.26-.758.568-1.02c.605-.518 1.002-1.393 1.002-2.385c0-1.588-1.018-2.875-2.273-2.875s-2.274 1.287-2.274 2.875c0 .992.398 1.867 1.003 2.384c.308.263.568.616.568 1.021v5.056h1.406z");
}

.u5hst-xdb {
  fill: var(--svg-color--000, #000);
  d: path("M17.777 10.415c0-.284.227-.511.511-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.235");
}

.u7axe2baw {
  stop-color: var(--svg-color--9183a0, #9183A0);
}

.uelaalb7d {
  stop-color: var(--svg-color--da9766, #DA9766);
}

.ur8e5kbgj {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
  stop-opacity: 0;
}

.uvk62nj4e {
  stop-color: var(--svg-color--de3d65, #DE3D65);
}

.v2xpqhbrh {
  stop-color: var(--svg-color--402a29, #402A29);
}

.vaajtxp-t {
  d: path("M21.19 28.051a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.via-_dbpm {
  stop-color: var(--svg-color--eaae7e, #EAAE7E);
}

.vivl3bbaz {
  d: path("M9.13 17.894a10.96 10.96 0 0 0-4 8.477v3.55h4z");
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w9txrw6kc {
  stop-color: var(--svg-color--150a0d, #150A0D);
}

.wb78_hxsc {
  stop-color: var(--svg-color--6a5956, #6A5956);
}

.we918tb1b {
  fill: var(--svg-color--c1a0c0, #C1A0C0);
  d: path("M20.17 21.676a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.wfl-8sksi {
  stop-color: var(--svg-color--a79eb4, #A79EB4);
}

.wgpm0ibqw {
  stop-color: var(--svg-color--43272a, #43272A);
  stop-opacity: 0;
}

.witvnebrl {
  d: path("M15.442 17.479c.19-.063.44-.12.707-.12s.517.057.707.12a.39.39 0 0 1 .254.45c-.092.486-.269.8-.463.989a.5.5 0 0 1-.268.131a1.5 1.5 0 0 1-.476 0a.43.43 0 0 1-.252-.131c-.194-.189-.371-.503-.464-.99a.39.39 0 0 1 .255-.45");
}

.wj3drmbex {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
}

.wj9mtgody {
  stop-color: var(--svg-color--533531, #533531);
  stop-opacity: 0;
}

.x_sue_b_g {
  stop-color: var(--svg-color--634d4b, #634D4B);
}

.x7h3p2bdy {
  stop-color: var(--svg-color--533632, #533632);
  stop-opacity: 0;
}

.xfmbn4_bb {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
  stop-opacity: 0;
}

.xglbqnshq {
  stop-color: var(--svg-color--b92c4a, #B92C4A);
}

.xipfy3bpt {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M12.694 7.968a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.551a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.091.06l-.003.002a.277.277 0 0 1-.34-.438z");
}

.xkhh7vb2n {
  stop-color: var(--svg-color--371e27, #371E27);
  stop-opacity: 0;
}

.xndjovbcx {
  d: path("M23.762 25.217a.73.73 0 0 1 .726-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.39a.735.735 0 0 1 0-1.313a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.406-.657");
}

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.y9x8350wz {
  fill: var(--svg-color--302d32, #302D32);
  d: path("M13.598 9.185c.766.04 1.1.422 1.219.613l-2.012.461c-.14.008-.484-.086-.562-.246a.31.31 0 0 1 .05-.363c.176-.203.675-.497 1.305-.465");
}

.ybvm9tprh {
  stop-color: var(--svg-color--594d4d, #594D4D);
}

.yd_laccri {
  stop-color: var(--svg-color--565252, #565252);
}

.yihpasnlf {
  stop-color: var(--svg-color--df3d53, #DF3D53);
}

.ymjtedccx {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m15.618 10.281l-.635 1.839c-.108.378.152.756.52.756h.787c.37 0 .63-.384.52-.756l-.53-1.839c-.114-.407-.542-.407-.662 0");
}

.yonw8mbnr {
  stop-color: var(--svg-color--da3158, #DA3158);
  stop-opacity: 0;
}

.ysetj63ow {
  stop-color: var(--svg-color--9785a0, #9785A0);
}

.yv4uycbmh {
  stop-color: var(--svg-color--43272a, #43272A);
}

.yxwqgvbem {
  stop-color: var(--svg-color--594d4d, #594D4D);
  stop-opacity: 0;
}

.z_wfxjr5n {
  stop-color: var(--svg-color--392526, #392526);
}

.z-8m36bgw {
  fill: var(--svg-color--e8e1e9, #E8E1E9);
  d: path("M16.11 15.39c-6.07 0-10.98 4.92-10.98 10.98v3.55h4v-.06h14v.06h4v-3.5c0-3.422-1.554-6.482-4-8.5v.014a10.92 10.92 0 0 0-7.02-2.543");
}

.z9hvqlmkw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.282 25.869h1.796");
}

.z9vs4zbzi {
  stop-color: var(--svg-color--e33964, #E33964);
}

.zab3c9ypw {
  stop-color: var(--svg-color--a8a0af, #A8A0AF);
  stop-opacity: 0;
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zdd_-i6yb {
  stop-color: var(--svg-color--5c4644, #5C4644);
  stop-opacity: 0;
}

.zdypug-8z {
  stop-color: var(--svg-color--2b1820, #2B1820);
}

.zk5cvukoj {
  stop-color: var(--svg-color--675655, #675655);
  stop-opacity: 0;
}

.zrix05bns {
  d: path("M15.843 17.416c-.385.033-1.405.253-2.103 1.143c-.469.599-.498 1.44-.52 2.068q-.004.177-.013.326a1.4 1.4 0 0 1-.07.363c-.054.155.04.342.2.332c.58-.036 1.018-.163 1.664-.705c.492-.414.742-1.063.85-1.717c.044.662.23 1.332.678 1.792c.59.604 1.013.773 1.587.866c.158.026.27-.15.231-.31a1.4 1.4 0 0 1-.034-.368q.007-.15.019-.326c.04-.627.095-1.467-.313-2.11c-.607-.954-1.6-1.274-1.98-1.344a5 5 0 0 0-.127.583a5 5 0 0 0-.07-.593");
}

.ztvu2mbem {
  stop-color: var(--svg-color--9c8fab, #9C8FAB);
}

.zz4mcgrzh {
  stop-color: var(--svg-color--59403d, #59403D);
  stop-opacity: 0;
}

</style>
