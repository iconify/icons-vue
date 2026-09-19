<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iSdWyOj)" class="ww5bht_3v"/><path fill="url(#iNHLMDK)" class="ww5bht_3v"/><path fill="url(#ioTOrHc)" class="ww5bht_3v"/><path fill="url(#iPbX5Bc)" class="ww5bht_3v"/><path fill="url(#iBvIIDM)" class="ww5bht_3v"/><path fill="url(#iHvtpWc)" class="ww5bht_3v"/><path fill="url(#iz2eBvf)" class="ww5bht_3v"/><path fill="url(#iU8P3Qb)" class="nhl299aoi"/><path fill="url(#i13hZbc)" class="mynkhl4fq"/><path fill="url(#irsOh4c)" class="p99sz2b_q"/><path fill="url(#iLBLJ5b)" class="p99sz2b_q"/><path fill="url(#iEK27jc)" class="p99sz2b_q"/><path fill="url(#ij3ER5d)" class="kov97cczy"/><path fill="url(#ir6d0de)" class="kov97cczy"/><path fill="url(#isFDcuc)" class="kov97cczy"/><path fill="url(#iHlfI1d)" class="mxdnuacjd"/><path fill="url(#iAl3PUY)" class="mxdnuacjd"/><path fill="url(#iU8P3Qb)" class="nhl299aoi"/><path fill="url(#i13hZbc)" class="mynkhl4fq"/><g filter="url(#ijIClrd)"><path class="q1pxypytt"/></g><g filter="url(#i6HbkXb)"><path fill="url(#iycp6De)" class="pwnrlbcmt"/></g><path fill="url(#ihPU3zc)" class="sy_bn0b4p"/><path fill="url(#iCjNsPc)" class="sy_bn0b4p"/><path fill="url(#iIcfcgd)" class="sy_bn0b4p"/><path fill="url(#inRwpFe)" class="sy_bn0b4p"/><path fill="url(#i6mUqUb)" class="sy_bn0b4p"/><path fill="url(#ivPLVld)" class="sy_bn0b4p"/><path fill="url(#ifngZEb)" class="a91a9v73t"/><path fill="url(#iwx5VGL)" class="a91a9v73t"/><path fill="url(#iqLnouc)" class="a91a9v73t"/><path fill="url(#ikWlLnc)" class="a91a9v73t"/><path fill="url(#iIjhnLb)" class="a91a9v73t"/><path fill="url(#iiaKhXK)" class="a91a9v73t"/><path fill="url(#iAHctVP)" class="x1-tyteku"/><path clip-rule="evenodd" class="k1fg6z23n"/><path fill="url(#iOPfisd)" clip-rule="evenodd" class="xhz29acmr"/><path fill="url(#i1sDDfD)" clip-rule="evenodd" class="xhz29acmr"/><path fill="url(#iXCMaWc)" clip-rule="evenodd" class="xhz29acmr"/><path fill="url(#i2XnTId)" clip-rule="evenodd" class="xhz29acmr"/><g filter="url(#ilFXI7b)"><path class="m8on5ubzt"/></g><path fill="url(#iyA3vte)" class="nz_5iebzt"/><g filter="url(#i42nXCc)"><path fill="url(#iZUVLCe)" class="xvum5ox9z"/></g><g filter="url(#iCdOzte)"><path fill="url(#ilcUZCb)" clip-rule="evenodd" class="w8h9sabep"/></g><g filter="url(#ilPYgvZ)"><path class="pofn6dbhp"/></g><path fill="url(#ial3JTa)" clip-rule="evenodd" class="mnmyf8b0v"/><path fill="url(#iPd0N1s)" clip-rule="evenodd" class="mnmyf8b0v"/><path fill="url(#ia11r8s)" clip-rule="evenodd" class="kej_5uuus"/><path fill="url(#izBeKAb)" clip-rule="evenodd" class="kej_5uuus"/><g filter="url(#iNFCO7c)"><circle fill="url(#iyVT5xr)" class="kx3s7fbec"/></g><g filter="url(#idZYQqg)"><circle fill="url(#ibvBcJb)" class="eyx4z1bne"/></g><g filter="url(#ilndyLc)"><circle fill="url(#iO2TDxd)" class="ned_7choj"/><circle fill="url(#iKdBUGb)" class="ned_7choj"/></g><g filter="url(#ialLt7e)"><circle class="ojm1q_nom"/><circle fill="url(#iFftPSD)" class="e46jexbvs"/><circle fill="url(#iyGms4F)" class="e46jexbvs"/></g><g filter="url(#i61PBid)"><path fill="url(#iEYDxLe)" class="nqypfgb0f"/><path fill="url(#iFX5Ltd)" class="nqypfgb0f"/><path fill="url(#i3DreZc)" class="nqypfgb0f"/><path fill="url(#i24LeAb)" class="nqypfgb0f"/><path fill="url(#iEhGcRQ)" class="nqypfgb0f"/><path fill="url(#ioxuJMb)" class="nqypfgb0f"/></g><g filter="url(#iLkKqwb)"><path fill="url(#iyaFcpd)" class="jeqi0obye"/></g><g filter="url(#i4QQdZc)"><path class="md8ri3q7u"/><path fill="url(#ioGADSb)" class="dyzm_kkqa"/><path fill="url(#ibG3ROc)" class="dyzm_kkqa"/><path fill="url(#izso0eb)" class="dyzm_kkqa"/><path fill="url(#ij7MiIc)" class="dyzm_kkqa"/></g><g filter="url(#i3hqVKd)"><path class="bek-aubcn"/></g><g filter="url(#iYPLMGe)"><path class="xl9r1dorn"/><path fill="url(#irI59ae)" class="ra72ujb7e"/><path fill="url(#ir8IPXb)" class="ra72ujb7e"/><path fill="url(#iycuiec)" class="ra72ujb7e"/><path fill="url(#iVA9ZLH)" class="ra72ujb7e"/></g><path fill="url(#ibccBLd)" class="ra72ujb7e"/><path stroke="url(#i5VVCrd)" class="r2uoufcuc"/><g filter="url(#i61AUme)"><path class="i7b285hgm"/></g><g filter="url(#i0fnHYc)"><path class="kn4zzpbwf"/></g><path class="ayn16ho2x"/><path fill="url(#iq15Sfc)" class="cye5jwbmf"/><path class="s5f86pbvz"/><g filter="url(#ibmrUxe)"><path class="fqyqtxbbg"/><path fill="url(#iOUwiRc)" class="cj1lzpbcp"/></g><g filter="url(#iBTyUqd)"><path fill="url(#iXmCo1d)" class="gabxj4b-x"/></g><path class="qmuxrmb-a"/><path fill="url(#iVBqXcw)" class="jninz1bgx"/><path class="hpz17ozog"/><g filter="url(#iy1Ig4b)"><path fill="url(#iu9BLde)" class="zi5s8lmsp"/></g><g filter="url(#ii7PKSc)"><ellipse transform="rotate(-27.914 13.614 9.94)" class="s0053xbob"/><ellipse fill="url(#i7jahkc)" transform="rotate(-27.914 13.614 9.94)" class="hi99jhz3q"/></g><g filter="url(#iLu49yf)"><path stroke="url(#i4Xarwc)" class="fle309bne"/></g><g filter="url(#iccdGbo)"><path stroke="url(#ihnLWPd)" class="fy4uegjpl"/></g><g filter="url(#iq570Ee)"><path stroke="url(#i6ae6ec)" class="u2j7u-sxc"/></g><defs><radialGradient id="iSdWyOj" cx="0" cy="0" r="1" gradientTransform="matrix(-10.8 0 0 -20.6925 23.34 23.937)" gradientUnits="userSpaceOnUse"><stop class="w-_6jxb_z"/><stop offset="1" class="fr_rdtj9g"/></radialGradient><radialGradient id="iBvIIDM" cx="0" cy="0" r="1" gradientTransform="rotate(-121.204 19.23 8.144)scale(16.5873 16.3485)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="o3tc-dnyn"/><stop offset="1" class="l-etq6b9a"/></radialGradient><radialGradient id="iHvtpWc" cx="0" cy="0" r="1" gradientTransform="matrix(.81252 3.5625 -3.94168 .899 18.197 24.5)" gradientUnits="userSpaceOnUse"><stop class="vgwmt2-9g"/><stop offset="1" class="r24zcwbvl"/></radialGradient><radialGradient id="iz2eBvf" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.97501 .96027 0 16.111 30.006)" gradientUnits="userSpaceOnUse"><stop class="k3g0v3buh"/><stop offset="1" class="afwov9b1d"/></radialGradient><radialGradient id="irsOh4c" cx="0" cy="0" r="1" gradientTransform="rotate(5.185 -270.2 72.84)scale(3.45763 9.59957)" gradientUnits="userSpaceOnUse"><stop class="kzw1yxrkd"/><stop offset="1" class="lnyefdcqm"/></radialGradient><radialGradient id="iLBLJ5b" cx="0" cy="0" r="1" gradientTransform="rotate(107.994 -1.643 12.39)scale(6.67657 7.47746)" gradientUnits="userSpaceOnUse"><stop class="o874sbcxz"/><stop offset="1" class="yqete2_ye"/></radialGradient><radialGradient id="ij3ER5d" cx="0" cy="0" r="1" gradientTransform="matrix(-3.07502 1.40623 -3.71957 -8.13362 26.376 21.969)" gradientUnits="userSpaceOnUse"><stop class="dlt2kgbvz"/><stop offset="1" class="n7ni7rtly"/></radialGradient><radialGradient id="ir6d0de" cx="0" cy="0" r="1" gradientTransform="matrix(0 11 -8.46398 0 24.689 20.344)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="rqdbjlbdw"/><stop offset=".974" class="anyvddbxc"/></radialGradient><radialGradient id="iHlfI1d" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.65625 -3.01125 0 16.145 18.562)" gradientUnits="userSpaceOnUse"><stop offset=".398" class="jwjdg84ax"/><stop offset="1" class="h1aoh3b9a"/></radialGradient><radialGradient id="iAl3PUY" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.53125 2.8605 0 16.509 30.5)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="stn4eib-z"/><stop offset="1" class="z99vy1qwj"/></radialGradient><radialGradient id="inRwpFe" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.1875 -.84559 0 19.284 18.125)" gradientUnits="userSpaceOnUse"><stop class="skz637x0p"/><stop offset="1" class="wxe5vubnr"/></radialGradient><radialGradient id="i6mUqUb" cx="0" cy="0" r="1" gradientTransform="matrix(2.69211 -3.05149 1.0422 .91946 16.591 26.567)" gradientUnits="userSpaceOnUse"><stop class="etbfcvxig"/><stop offset="1" class="oc1bwblbr"/></radialGradient><radialGradient id="ivPLVld" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.84375 .55327 0 19.284 24.875)" gradientUnits="userSpaceOnUse"><stop class="v2gep8uzg"/><stop offset="1" class="r9qw8z0np"/></radialGradient><radialGradient id="ifngZEb" cx="0" cy="0" r="1" gradientTransform="rotate(158.705 5.452 11.297)scale(3.25339 6.38774)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="c9e2npbbn"/><stop offset="1" class="cf3hk9c-f"/></radialGradient><radialGradient id="iwx5VGL" cx="0" cy="0" r="1" gradientTransform="matrix(3.46106 -9.38813 7.62182 2.80989 10.275 24.93)" gradientUnits="userSpaceOnUse"><stop offset=".691" class="x7yaztbkk"/><stop offset="1" class="rl5jhib1q"/></radialGradient><radialGradient id="ikWlLnc" cx="0" cy="0" r="1" gradientTransform="matrix(.3906 -2.76562 2.11886 .29926 10.447 19.5)" gradientUnits="userSpaceOnUse"><stop class="uwchitapr"/><stop offset="1" class="xag1knb5p"/></radialGradient><radialGradient id="iIjhnLb" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 2.20312 -.6764 -.13432 12.243 18.328)" gradientUnits="userSpaceOnUse"><stop offset=".439" class="c-t0maccw"/><stop offset="1" class="w0rhj52ia"/></radialGradient><radialGradient id="iiaKhXK" cx="0" cy="0" r="1" gradientTransform="rotate(49.295 -16.965 24.388)scale(2.80315 .97425)" gradientUnits="userSpaceOnUse"><stop class="azmrtxbft"/><stop offset="1" class="j-efl5b-c"/></radialGradient><radialGradient id="iAHctVP" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.72628 3.2225 0 16.13 18.726)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="t86x-rdvp"/><stop offset=".577" class="pdkl-5bkv"/><stop offset="1" class="pdkl-5bkv"/></radialGradient><radialGradient id="i1sDDfD" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.78125 -1.30438 0 18.65 16.39)" gradientUnits="userSpaceOnUse"><stop offset=".123" class="ad-0z61hw"/><stop offset="1" class="p6pfsuaja"/></radialGradient><radialGradient id="iXCMaWc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.14062 .59375 0 12.727 20.047)" gradientUnits="userSpaceOnUse"><stop class="viff9wbjp"/><stop offset="1" class="t68so1bro"/></radialGradient><radialGradient id="i2XnTId" cx="0" cy="0" r="1" gradientTransform="rotate(117.031 1.887 12.242)scale(1.71903 1.83663)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="s96-1fbmn"/><stop offset="1" class="pvle9ybys"/></radialGradient><radialGradient id="iyA3vte" cx="0" cy="0" r="1" gradientTransform="rotate(121.842 3.224 18.11)scale(1.90409 1.71171)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="ka5t_pbkm"/><stop offset="1" class="y58nhpnsg"/></radialGradient><radialGradient id="iZUVLCe" cx="0" cy="0" r="1" gradientTransform="matrix(.78648 -.78648 .51957 .51957 19.393 25.914)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="h4zbx-g8y"/><stop offset="1" class="bmbim-qcd"/></radialGradient><radialGradient id="iPd0N1s" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.5 -.28074 0 10.275 23.578)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="rognhpd5x"/><stop offset="1" class="f923khbrt"/></radialGradient><radialGradient id="iyVT5xr" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 9.648 10.717)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="iKdBUGb" cx="0" cy="0" r="1" gradientTransform="rotate(-36.06 26.662 -27.36)scale(1.02361 1.16832)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="iFftPSD" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.8 11.54)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="iyGms4F" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.841 10.717)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="i3DreZc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.11187 -9.65399 0 15.77 10.518)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="g0r5sc7jj"/><stop offset="1" class="i5c5eto6f"/></radialGradient><radialGradient id="i24LeAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 18.42 9.445)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="iEhGcRQ" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39218 1.7313 0 13.857 9.411)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="ioxuJMb" cx="0" cy="0" r="1" gradientTransform="rotate(-166.409 11.178 7.23)scale(2.92567 1.71902)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="ph-yb3bws"/><stop offset="1" class="az2la2bjr"/></radialGradient><radialGradient id="ioGADSb" cx="0" cy="0" r="1" gradientTransform="matrix(.79857 -2.95942 1.09745 .29614 20.42 6.608)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="ibG3ROc" cx="0" cy="0" r="1" gradientTransform="matrix(3.82845 .35231 -.18944 2.05853 18.776 4.846)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="izso0eb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68076 -2.60303 0 16.071 2.108)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="ij7MiIc" cx="0" cy="0" r="1" gradientTransform="matrix(3.07685 -2.2548 3.53253 4.82042 9.617 8.933)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="iVA9ZLH" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19709 -.6332 0 16.399 12.326)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="iq15Sfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8119 -1.29142 0 18.252 10.035)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iOUwiRc" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 18.024 10.12)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iVBqXcw" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81194 -1.29148 0 13.885 10.035)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i7jahkc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.847 -1.566)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="iNHLMDK" x1="23.454" x2="23.142" y1="24.617" y2="24.617" gradientUnits="userSpaceOnUse"><stop offset=".225" class="sm4v8rvoi"/><stop offset="1" class="x3e-lhbqh"/></linearGradient><linearGradient id="ioTOrHc" x1="8.876" x2="9.212" y1="24.617" y2="24.617" gradientUnits="userSpaceOnUse"><stop offset=".383" class="k2sjcrc_g"/><stop offset="1" class="v717bwb7u"/></linearGradient><linearGradient id="iPbX5Bc" x1="16.321" x2="16.321" y1="30.968" y2="29.156" gradientUnits="userSpaceOnUse"><stop class="vxx0ssbsk"/><stop offset="1" class="q3wk7p4fa"/></linearGradient><linearGradient id="iU8P3Qb" x1="8.96" x2="23.336" y1="15.446" y2="15.446" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i13hZbc" x1="8.96" x2="23.336" y1="15.415" y2="15.415" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iEK27jc" x1="7.14" x2="7.14" y1="30.782" y2="29.322" gradientUnits="userSpaceOnUse"><stop class="vxx0ssbsk"/><stop offset="1" class="q3wk7p4fa"/></linearGradient><linearGradient id="isFDcuc" x1="22.811" x2="23.59" y1="25.655" y2="25.655" gradientUnits="userSpaceOnUse"><stop offset=".643" class="sm4v8rvoi"/><stop offset="1" class="x3e-lhbqh"/></linearGradient><linearGradient id="iycp6De" x1="16.321" x2="23.946" y1="27" y2="19.406" gradientUnits="userSpaceOnUse"><stop class="e---z_byu"/><stop offset="1" class="dxszyubmb"/></linearGradient><linearGradient id="ihPU3zc" x1="22.035" x2="16.92" y1="18.395" y2="23.914" gradientUnits="userSpaceOnUse"><stop class="xoshv8bzu"/><stop offset="1" class="i4xusnb1i"/></linearGradient><linearGradient id="iCjNsPc" x1="20.189" x2="20.032" y1="15.677" y2="17.739" gradientUnits="userSpaceOnUse"><stop class="fx7jj2m3f"/><stop offset="1" class="foe4l_bip"/></linearGradient><linearGradient id="iIcfcgd" x1="17.727" x2="18.884" y1="18.922" y2="19.406" gradientUnits="userSpaceOnUse"><stop class="kv70nqbkg"/><stop offset="1" class="y2rlftbia"/></linearGradient><linearGradient id="iqLnouc" x1="12.415" x2="12.743" y1="23.219" y2="22.859" gradientUnits="userSpaceOnUse"><stop class="s7vootu_w"/><stop offset="1" class="hou90zp4m"/></linearGradient><linearGradient id="iOPfisd" x1="20.454" x2="19.782" y1="23.687" y2="23.703" gradientUnits="userSpaceOnUse"><stop offset=".294" class="w_l8deb9l"/><stop offset="1" class="xmdmj-dwi"/></linearGradient><linearGradient id="ilcUZCb" x1="12.35" x2="12.35" y1="19.886" y2="28.469" gradientUnits="userSpaceOnUse"><stop class="sp4_sibjj"/><stop offset="1" class="lpc21p-wa"/></linearGradient><linearGradient id="ial3JTa" x1="9.659" x2="10.553" y1="25.285" y2="25.285" gradientUnits="userSpaceOnUse"><stop class="gzrilbbya"/><stop offset="1" class="je8_hbb1l"/></linearGradient><linearGradient id="ia11r8s" x1="14.032" x2="14.704" y1="25.295" y2="25.295" gradientUnits="userSpaceOnUse"><stop class="gzrilbbya"/><stop offset="1" class="je8_hbb1l"/></linearGradient><linearGradient id="izBeKAb" x1="15.095" x2="14.852" y1="24.813" y2="24.813" gradientUnits="userSpaceOnUse"><stop class="pgy4y9bks"/><stop offset="1" class="ll7oxmbau"/></linearGradient><linearGradient id="ibvBcJb" x1="11.319" x2="10.678" y1="10.996" y2="10.996" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="iO2TDxd" x1="21.929" x2="21.109" y1="9.625" y2="12.164" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="iEYDxLe" x1="20.111" x2="12.467" y1="11.107" y2="12.247" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="iFX5Ltd" x1="10.67" x2="12.938" y1="13.806" y2="13.664" gradientUnits="userSpaceOnUse"><stop offset=".283" class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="iyaFcpd" x1="17.031" x2="25.656" y1="7.727" y2="4.758" gradientUnits="userSpaceOnUse"><stop class="cgqcq-bjq"/><stop offset="1" class="o1syipbau"/></linearGradient><linearGradient id="irI59ae" x1="15.206" x2="16.145" y1="11.767" y2="11.767" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="ir8IPXb" x1="17.011" x2="15.984" y1="12.09" y2="12.075" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="iycuiec" x1="16.266" x2="16.266" y1="12.833" y2="12.26" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="ibccBLd" x1="16.197" x2="16.197" y1="12.875" y2="12.707" gradientUnits="userSpaceOnUse"><stop class="zoxadnjxe"/><stop offset="1" class="gnvm67mtb"/></linearGradient><linearGradient id="i5VVCrd" x1="15.033" x2="15.469" y1="14.45" y2="13.761" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="iXmCo1d" x1="19.031" x2="18.717" y1="10.089" y2="10.282" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iu9BLde" x1="14.629" x2="14.315" y1="10.089" y2="10.282" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i4Xarwc" x1="19.046" x2="18.626" y1="7.947" y2="7.088" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="ihnLWPd" x1="13.737" x2="12.546" y1="7.819" y2="7.32" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="i6ae6ec" x1="11.405" x2="11.405" y1="5.803" y2="7.962" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><filter id="ijIClrd" width="7.147" height="11.557" x="9.175" y="15.804" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24146" stdDeviation=".5"/></filter><filter id="i6HbkXb" width="7.147" height="11.557" x="16.069" y="15.804" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24146" stdDeviation=".5"/></filter><filter id="ilFXI7b" width="3.699" height="3.699" x="17.14" y="24.016" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24146" stdDeviation=".375"/></filter><filter id="i42nXCc" width="1.42" height="1.42" x="19.11" y="24.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.411765 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24146"/></filter><filter id="iCdOzte" width="5.381" height="7.171" x="9.659" y="19.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.239216 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24146"/></filter><filter id="ilPYgvZ" width="5.3" height="6.89" x="9.725" y="19.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24146" stdDeviation=".15"/></filter><filter id="iNFCO7c" width="3.542" height="3.342" x="9.648" y="9.046" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24146"/></filter><filter id="idZYQqg" width="2.992" height="2.992" x="9.823" y="9.222" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24146" stdDeviation=".25"/></filter><filter id="ilndyLc" width="3.592" height="3.592" x="19.17" y="8.796" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24146"/></filter><filter id="ialLt7e" width="2.992" height="2.992" x="19.345" y="9.222" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24146" stdDeviation=".25"/></filter><filter id="i61PBid" width="10.383" height="12.189" x="10.908" y="5.088" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24146"/></filter><filter id="iLkKqwb" width="6.25" height="5.07" x="15.241" y="4.088" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24146" stdDeviation=".5"/></filter><filter id="i4QQdZc" width="12.614" height="8.551" x="9.764" y="1.608" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24146"/></filter><filter id="i3hqVKd" width="3.262" height="4.184" x="14.201" y="9.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24146" stdDeviation=".375"/></filter><filter id="iYPLMGe" width="2.379" height="3.184" x="14.882" y="9.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24146" stdDeviation=".125"/></filter><filter id="i61AUme" width="2.982" height="1.874" x="17.255" y="7.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24146"/></filter><filter id="i0fnHYc" width="2.982" height="1.874" x="12.102" y="7.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24146"/></filter><filter id="ibmrUxe" width=".787" height=".697" x="17.518" y="9.595" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24146" stdDeviation=".05"/></filter><filter id="iBTyUqd" width=".892" height=".914" x="18.358" y="9.67" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24146" stdDeviation=".1"/></filter><filter id="iy1Ig4b" width=".987" height="1.041" x="13.912" y="9.607" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24146" stdDeviation=".1"/></filter><filter id="ii7PKSc" width=".914" height=".705" x="13.157" y="9.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24146" stdDeviation=".05"/></filter><filter id="iLu49yf" width="2.701" height="1.282" x="17.308" y="7.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24146" stdDeviation=".15"/></filter><filter id="iccdGbo" width="2.779" height="1.339" x="12.084" y="7.455" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24146" stdDeviation=".15"/></filter><filter id="iq570Ee" width="1.008" height="2.271" x="10.901" y="5.527" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24146" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-health-worker-dark" /></template>
<style>
.a91a9v73t {
  d: path("M15.515 21.697c.262.516.262.942.262 1.306v2.991c0 .17-.208.26-.327.13l-4.818-4.96a.234.234 0 0 1-.01-.32l.754-.83c.119-.13.05-.35-.129-.38l-.783-.14a.23.23 0 0 1-.189-.25l.188-2.059a.25.25 0 0 1 .113-.186a10.5 10.5 0 0 1 2.426-1.135a.3.3 0 0 1 .04.08z");
}

.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.ad-0z61hw {
  stop-color: var(--svg-color--552e54, #552E54);
}

.afwov9b1d {
  stop-color: var(--svg-color--b1909e, #B1909E);
  stop-opacity: 0;
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.anyvddbxc {
  stop-color: var(--svg-color--d1c0e3, #D1C0E3);
}

.ayn16ho2x {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.461 9.286c.654 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34h-2.233a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.372-1.128");
}

.az2la2bjr {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
  stop-opacity: 0;
}

.azmrtxbft {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
}

.bek-aubcn {
  fill: var(--svg-color--332024, #332024);
  d: path("m15.796 10.595l-.821 1.701c-.102.35.142.7.488.7h.738c.346 0 .59-.355.488-.7l-.498-1.7c-.107-.378-.283-.378-.395 0");
}

.bmbim-qcd {
  stop-color: var(--svg-color--2c6dbd, #2C6DBD);
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.c-t0maccw {
  stop-color: var(--svg-color--ada5ab, #ADA5AB);
}

.c9e2npbbn {
  stop-color: var(--svg-color--efe1e3, #EFE1E3);
}

.cdm_o50ho {
  stop-color: var(--svg-color--533531, #533531);
}

.cf3hk9c-f {
  stop-color: var(--svg-color--bdb0d0, #BDB0D0);
}

.cgqcq-bjq {
  stop-color: var(--svg-color--675454, #675454);
}

.cj1lzpbcp {
  d: path("M18.189 9.747c.063.085-.07.188-.221.302s-.263.192-.327.107s.007-.246.159-.359c.15-.113.325-.136.389-.05");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cye5jwbmf {
  d: path("M18.254 9.558a.893.893 0 0 1 .86 1.128H17.39a.897.897 0 0 1 .865-1.129");
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.dlt2kgbvz {
  stop-color: var(--svg-color--fcf9ff, #FCF9FF);
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.dxszyubmb {
  stop-color: var(--svg-color--d3cfda, #D3CFDA);
}

.dyzm_kkqa {
  d: path("m20.895 4.234l.43.213c.75.374 1.18 1.228 1.02 2.136l-.591 3.043c-.053.314-.26.526-.573.533h-.018s.054-.907.107-1.44c.044-.434-.032-.567-.43-.962c-.214-.213-.375-.534-.375-.854V6.05c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.919-.427s-3.275.267-3.92.427a.52.52 0 0 0-.429.534v.854c0 .32-.107.64-.376.854l-.16.16c-.215.16-.323.48-.323.748c.054.587.108 1.441.108 1.441l-.05-.002a.634.634 0 0 1-.595-.532l-.59-3.043c-.108-.854.322-1.708 1.073-2.082l.43-.213a8 8 0 0 0 .805-.587l.967-1.015c.59-.533 1.45-.694 2.201-.32c.537.16 1.128.16 1.665 0c.805-.267 1.718-.053 2.362.534l.805.8c.215.268.484.428.806.588");
}

.e---z_byu {
  stop-color: var(--svg-color--ad9ec2, #AD9EC2);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e46jexbvs {
  cx: 20.841px;
  cy: 10.718px;
  r: 0.996px;
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.etbfcvxig {
  stop-color: var(--svg-color--b7a3cf, #B7A3CF);
}

.eyx4z1bne {
  cx: 11.319px;
  cy: 10.718px;
  r: 0.996px;
}

.f923khbrt {
  stop-color: var(--svg-color--46a4e7, #46A4E7);
  stop-opacity: 0;
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.fle309bne {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.733 7.85c.43-.075 1.27-.054 1.852.398");
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.foe4l_bip {
  stop-color: var(--svg-color--edd8ce, #EDD8CE);
  stop-opacity: 0;
}

.fqyqtxbbg {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.189 9.747c.063.085-.07.188-.221.302s-.263.192-.327.107s.007-.246.159-.359c.15-.113.325-.136.389-.05");
}

.fr_rdtj9g {
  stop-color: var(--svg-color--d4cae9, #D4CAE9);
}

.ft5dv1b6b {
  fill: none;
}

.fx7jj2m3f {
  stop-color: var(--svg-color--edd8ce, #EDD8CE);
}

.fy4uegjpl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.509 8.37c.327-.29 1.043-.595 1.929-.454");
}

.g0r5sc7jj {
  stop-color: var(--svg-color--3d2138, #3D2138);
  stop-opacity: 0;
}

.gabxj4b-x {
  d: path("M19.05 10.333a.84.84 0 0 0-.232-.463l-.26.286l.117.228z");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gnvm67mtb {
  stop-color: var(--svg-color--31171f, #31171F);
  stop-opacity: 0;
}

.gzrilbbya {
  stop-color: var(--svg-color--3a97db, #3A97DB);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h1aoh3b9a {
  stop-color: var(--svg-color--0a4b92, #0A4B92);
}

.h4zbx-g8y {
  stop-color: var(--svg-color--4c7bbf, #4C7BBF);
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.hi99jhz3q {
  cx: 13.614px;
  cy: 9.939px;
  rx: 0.39px;
  ry: 0.197px;
}

.hou90zp4m {
  stop-color: var(--svg-color--b2a6c6, #B2A6C6);
  stop-opacity: 0;
}

.hpz17ozog {
  fill: var(--svg-color--000, #000);
  d: path("M14.395 10.45a.51.51 0 0 0-.512-.511a.51.51 0 0 0-.455.747h.906c.036-.07.06-.15.06-.236");
}

.i4xusnb1i {
  stop-color: var(--svg-color--bdb2d2, #BDB2D2);
}

.i5c5eto6f {
  stop-color: var(--svg-color--3d2138, #3D2138);
}

.i7b285hgm {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m19.794 7.995l-.003-.002l-.004-.004l-.012-.01l-.036-.027a2.6 2.6 0 0 0-.54-.291a2.84 2.84 0 0 0-1.493-.158a.534.534 0 0 0 .166 1.055c.398-.063.717.01.935.096a1.5 1.5 0 0 1 .308.166a.534.534 0 0 0 .68-.825");
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.j-efl5b-c {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
  stop-opacity: 0;
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
}

.je8_hbb1l {
  stop-color: var(--svg-color--49a3e2, #49A3E2);
}

.jeqi0obye {
  d: path("m20.039 5.088l-3.08 1.027a1.048 1.048 0 0 0 .47 2.033l3.062-.41z");
}

.jninz1bgx {
  d: path("M13.883 9.558a.893.893 0 0 0-.86 1.128h1.725a1 1 0 0 0 .032-.235a.9.9 0 0 0-.897-.893");
}

.jwjdg84ax {
  stop-color: var(--svg-color--3072a2, #3072A2);
}

.k1fg6z23n {
  fill: var(--svg-color--5a4b7e, #5A4B7E);
  fill-rule: evenodd;
  d: path("M16.08 15.127a3.24 3.24 0 0 0-3.24 3.24v2.15h-.98v-2.15a4.22 4.22 0 0 1 8.44 0v7.12h-.98v-7.12a3.24 3.24 0 0 0-3.24-3.24");
}

.k2sjcrc_g {
  stop-color: var(--svg-color--b7afc3, #B7AFC3);
}

.k3g0v3buh {
  stop-color: var(--svg-color--b1909e, #B1909E);
}

.ka5t_pbkm {
  stop-color: var(--svg-color--49a3e6, #49A3E6);
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.kej_5uuus {
  fill-rule: evenodd;
  d: path("M15.04 23.736v2.47c0 .361-.29.65-.65.65h-.58v-.98h.25v-2.14z");
}

.kn4zzpbwf {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M12.294 7.996v-.001h.002l.002-.002l.004-.004l.012-.01l.036-.027q.045-.032.119-.08c.1-.063.241-.14.42-.211a2.83 2.83 0 0 1 1.494-.158a.534.534 0 1 1-.166 1.055a1.77 1.77 0 0 0-.935.096a1.5 1.5 0 0 0-.309.166a.534.534 0 0 1-.679-.824");
}

.kov97cczy {
  d: path("M26.971 27.976c.01-1.75-.25-3.49-.77-5.16c-.56-1.8-1.58-3.37-2.9-4.59v11.78h3.65z");
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kv70nqbkg {
  stop-color: var(--svg-color--b49089, #B49089);
}

.kx3s7fbec {
  cx: 11.319px;
  cy: 10.717px;
  r: 1.671px;
}

.kzw1yxrkd {
  stop-color: var(--svg-color--d3d0d5, #D3D0D5);
}

.l-etq6b9a {
  stop-color: var(--svg-color--bebac5, #BEBAC5);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll7oxmbau {
  stop-color: var(--svg-color--3d9ad9, #3D9AD9);
  stop-opacity: 0;
}

.lnyefdcqm {
  stop-color: var(--svg-color--c8bfd6, #C8BFD6);
}

.lpc21p-wa {
  stop-color: var(--svg-color--553c83, #553C83);
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m8on5ubzt {
  fill: var(--svg-color--afa3c5, #AFA3C5);
  d: path("M18.99 26.965a1.1 1.1 0 1 0 0-2.199a1.1 1.1 0 0 0 0 2.199");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.md8ri3q7u {
  fill: var(--svg-color--21181b, #21181B);
  d: path("m20.895 4.234l.43.213c.75.374 1.18 1.228 1.02 2.136l-.591 3.043c-.053.314-.26.526-.573.533h-.018s.054-.907.107-1.44c.044-.434-.032-.567-.43-.962c-.214-.213-.375-.534-.375-.854V6.05c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.919-.427s-3.275.267-3.92.427a.52.52 0 0 0-.429.534v.854c0 .32-.107.64-.376.854l-.16.16c-.215.16-.323.48-.323.748c.054.587.108 1.441.108 1.441l-.05-.002a.634.634 0 0 1-.595-.532l-.59-3.043c-.108-.854.322-1.708 1.073-2.082l.43-.213a8 8 0 0 0 .805-.587l.967-1.015c.59-.533 1.45-.694 2.201-.32c.537.16 1.128.16 1.665 0c.805-.267 1.718-.053 2.362.534l.805.8c.215.268.484.428.806.588");
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mnmyf8b0v {
  fill-rule: evenodd;
  d: path("M9.66 26.196v-2.47h.98v2.14h.25v.98h-.58a.65.65 0 0 1-.65-.65");
}

.mxdnuacjd {
  d: path("M16.638 22.52c0-.04-.01-.203 0-.243l2.662-6.291c.01-.03.03-.06.04-.08c-1.01-.32-2.08-.49-3.18-.49c-1.11 0-2.19.18-3.21.5c.01.02.03.05.04.07l2.64 6.361c.01.03.054.05.054.09l.056 3.599h.01v3.97h.79v-3.97l.078-3.415z");
}

.mynkhl4fq {
  d: path("M16.17 15.416h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.n7ni7rtly {
  stop-color: var(--svg-color--e6ddf3, #E6DDF3);
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.ned_7choj {
  cx: 20.841px;
  cy: 10.717px;
  r: 1.671px;
}

.nhl299aoi {
  d: path("M16.5 15.416c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.nqypfgb0f {
  d: path("m10.967 10.104l.049.002s-.054-.854-.108-1.441c0-.267.108-.588.322-.748l.162-.16c.268-.213.375-.534.375-.854v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.92-.427c1.932 0 3.274.267 3.919.427c.214.053.43.267.43.534v.854c0 .32.16.64.375.854c.503.352.471.546.43.961c-.054.534-.108 1.441-.108 1.441h.018l-.266 3.962c-.16 1.772-1.553 3.006-3.213 3.006h-3.214c-1.713 0-3.052-1.234-3.213-3.006z");
}

.nz_5iebzt {
  d: path("M19.82 26.736a1.26 1.26 0 1 0 0-2.52a1.26 1.26 0 0 0 0 2.52");
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o1syipbau {
  stop-color: var(--svg-color--685654, #685654);
  stop-opacity: 0;
}

.o3tc-dnyn {
  stop-color: var(--svg-color--bebac5, #BEBAC5);
  stop-opacity: 0;
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.o874sbcxz {
  stop-color: var(--svg-color--c4c3c3, #C4C3C3);
}

.oc1bwblbr {
  stop-color: var(--svg-color--b7a3cf, #B7A3CF);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojm1q_nom {
  cx: 20.841px;
  cy: 10.718px;
  r: 0.996px;
  fill: var(--svg-color--463133, #463133);
}

.p6pfsuaja {
  stop-color: var(--svg-color--552e54, #552E54);
  stop-opacity: 0;
}

.p99sz2b_q {
  d: path("m6.071 22.776l-.03.08c-.52 1.65-.79 3.36-.79 5.09v2.06h3.67v-11.75a10.56 10.56 0 0 0-2.85 4.52");
}

.pdkl-5bkv {
  stop-color: var(--svg-color--151428, #151428);
}

.pgy4y9bks {
  stop-color: var(--svg-color--3d9ad9, #3D9AD9);
}

.ph-yb3bws {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pofn6dbhp {
  stroke: var(--svg-color--6a5d85, #6A5D85);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M11.335 26.3h-1c-.09 0-.16-.07-.16-.16v-3.63a2.2 2.2 0 0 1 4.4 0v3.63c0 .09-.07.16-.16.16h-.93");
}

.pvle9ybys {
  stop-color: var(--svg-color--4a2657, #4A2657);
  stop-opacity: 0;
}

.pwnrlbcmt {
  d: path("m22.038 20.16l-.732.13a.213.213 0 0 0-.12.353l.704.77a.216.216 0 0 1-.01.296l-4.505 4.599c-.112.111-.306.037-.306-.12v-3.33c0-.036.009-.064.018-.101l2.54-5.888a.15.15 0 0 1 .038-.065a9.7 9.7 0 0 1 2.364 1.122l.186 2.003a.214.214 0 0 1-.177.232");
}

.q1pxypytt {
  fill: var(--svg-color--a49ea5, #A49EA5);
  d: path("m10.352 20.16l.732.13a.213.213 0 0 1 .12.353l-.704.77a.216.216 0 0 0 .01.296l4.505 4.599c.111.111.306.037.306-.12v-3.33c0-.036-.009-.064-.018-.101l-2.54-5.888a.15.15 0 0 0-.038-.065a9.7 9.7 0 0 0-2.364 1.122l-.186 2.003a.214.214 0 0 0 .176.232");
}

.q3wk7p4fa {
  stop-color: var(--svg-color--c8b7de, #C8B7DE);
  stop-opacity: 0;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qmuxrmb-a {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.676 9.286c-.654 0-1.206.45-1.356 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.372-1.128");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r24zcwbvl {
  stop-color: var(--svg-color--b2a6c7, #B2A6C7);
  stop-opacity: 0;
}

.r2uoufcuc {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.708 13.477c.394.206.863.323 1.363.323c.505 0 .97-.117 1.363-.323a.2.2 0 0 1 .242.04c.058.06.079.155.021.242m-2.99-.282l2.949.254m-2.948-.254a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24m.262-.282l-.221.254m3.21.027l-.041-.027m.041.027l-.041-.027m.041.027a1.95 1.95 0 0 1-1.626.87a1.95 1.95 0 0 1-1.626-.87m3.21-.027c-.335.508-.919.846-1.584.846s-1.25-.338-1.584-.846m-.042.028l.042-.028m-.042.028l.042-.028");
}

.r9qw8z0np {
  stop-color: var(--svg-color--a298b4, #A298B4);
  stop-opacity: 0;
}

.ra72ujb7e {
  d: path("m15.689 10.432l-.532 1.701a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.378-.646-.378-.765 0");
}

.rl5jhib1q {
  stop-color: var(--svg-color--b3a299, #B3A299);
}

.rognhpd5x {
  stop-color: var(--svg-color--46a4e7, #46A4E7);
}

.rqdbjlbdw {
  stop-color: var(--svg-color--d1c0e3, #D1C0E3);
  stop-opacity: 0;
}

.s0053xbob {
  cx: 13.614px;
  cy: 9.939px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.s5f86pbvz {
  fill: var(--svg-color--000, #000);
  d: path("M17.743 10.45a.51.51 0 0 1 .511-.511a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.061-.236");
}

.s7vootu_w {
  stop-color: var(--svg-color--b2a6c6, #B2A6C6);
}

.s96-1fbmn {
  stop-color: var(--svg-color--4a2657, #4A2657);
}

.skz637x0p {
  stop-color: var(--svg-color--aa98a1, #AA98A1);
}

.sm4v8rvoi {
  stop-color: var(--svg-color--d4ccdc, #D4CCDC);
}

.sp4_sibjj {
  stop-color: var(--svg-color--5d4f77, #5D4F77);
}

.stn4eib-z {
  stop-color: var(--svg-color--3865b8, #3865B8);
}

.sy_bn0b4p {
  d: path("M16.794 21.697c-.262.516-.262.942-.262 1.306v2.991c0 .17.208.26.327.13l4.818-4.96c.09-.09.09-.23.01-.32l-.753-.83a.23.23 0 0 1 .129-.38l.783-.14a.23.23 0 0 0 .188-.25l-.187-2.059a.25.25 0 0 0-.113-.186a10.5 10.5 0 0 0-2.426-1.135a.3.3 0 0 0-.04.08z");
}

.t68so1bro {
  stop-color: var(--svg-color--716687, #716687);
  stop-opacity: 0;
}

.t86x-rdvp {
  stop-color: var(--svg-color--301c25, #301C25);
}

.u2j7u-sxc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.534 5.902V6.8c-.008.149-.07.482-.258.623");
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.uwchitapr {
  stop-color: var(--svg-color--cbc5cf, #CBC5CF);
}

.v2gep8uzg {
  stop-color: var(--svg-color--a298b4, #A298B4);
}

.v717bwb7u {
  stop-color: var(--svg-color--b7afc3, #B7AFC3);
  stop-opacity: 0;
}

.vgwmt2-9g {
  stop-color: var(--svg-color--b2a6c7, #B2A6C7);
}

.viff9wbjp {
  stop-color: var(--svg-color--716687, #716687);
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vxx0ssbsk {
  stop-color: var(--svg-color--c8b7de, #C8B7DE);
}

.w_l8deb9l {
  stop-color: var(--svg-color--746992, #746992);
}

.w-_6jxb_z {
  stop-color: var(--svg-color--efeafb, #EFEAFB);
}

.w0rhj52ia {
  stop-color: var(--svg-color--ada5ab, #ADA5AB);
  stop-opacity: 0;
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w8h9sabep {
  fill-rule: evenodd;
  d: path("M12.35 20.867c-.94 0-1.71.762-1.71 1.71v3.299h.67a.49.49 0 0 1 0 .98h-1a.65.65 0 0 1-.65-.65v-3.63a2.69 2.69 0 0 1 5.38 0v3.63c0 .361-.289.65-.65.65h-.93a.49.49 0 0 1 0-.98h.6v-3.3c0-.94-.762-1.71-1.71-1.71");
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.ww5bht_3v {
  d: path("M16.131 15.416c-2.74 0-5.3 1.06-7.21 2.84v11.75h14.38v-11.78a10.54 10.54 0 0 0-7.17-2.81");
}

.wxe5vubnr {
  stop-color: var(--svg-color--dad1e4, #DAD1E4);
  stop-opacity: 0;
}

.x1-tyteku {
  d: path("M16.13 18.726a2.1 2.1 0 0 1-2.1-2.1v-1.38h4.2v1.38a2.1 2.1 0 0 1-2.1 2.1");
}

.x3e-lhbqh {
  stop-color: var(--svg-color--d4ccdc, #D4CCDC);
  stop-opacity: 0;
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.x7yaztbkk {
  stop-color: var(--svg-color--b3a299, #B3A299);
  stop-opacity: 0;
}

.xag1knb5p {
  stop-color: var(--svg-color--bdb1ad, #BDB1AD);
  stop-opacity: 0;
}

.xhz29acmr {
  fill-rule: evenodd;
  d: path("M16.08 15.127a3.24 3.24 0 0 0-3.24 3.24v2.15h-.98v-2.15a4.22 4.22 0 0 1 8.44 0v7.12h-.98v-7.12a3.24 3.24 0 0 0-3.24-3.24");
}

.xl9r1dorn {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m15.689 10.432l-.532 1.701a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.378-.646-.378-.765 0");
}

.xmdmj-dwi {
  stop-color: var(--svg-color--746992, #746992);
  stop-opacity: 0;
}

.xoshv8bzu {
  stop-color: var(--svg-color--fdf6f9, #FDF6F9);
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.xvum5ox9z {
  d: path("M19.82 26.186a.71.71 0 1 0 0-1.42a.71.71 0 0 0 0 1.42");
}

.y2rlftbia {
  stop-color: var(--svg-color--ded4e6, #DED4E6);
  stop-opacity: 0;
}

.y58nhpnsg {
  stop-color: var(--svg-color--2b86dd, #2B86DD);
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yqete2_ye {
  stop-color: var(--svg-color--c4c3c3, #C4C3C3);
  stop-opacity: 0;
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.z99vy1qwj {
  stop-color: var(--svg-color--3865b8, #3865B8);
  stop-opacity: 0;
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zi5s8lmsp {
  d: path("M14.699 10.346c0-.289-.235-.481-.298-.54l-.289.28l.178.361z");
}

.zoxadnjxe {
  stop-color: var(--svg-color--31171f, #31171F);
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
