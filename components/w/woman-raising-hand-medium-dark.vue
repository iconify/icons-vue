<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iYLyiwd)" class="mytsuknfz"/><path fill="url(#iO99DCb)" class="mytsuknfz"/><path fill="url(#is9W90d)" class="mytsuknfz"/><path fill="url(#i2nSEEd)" class="mytsuknfz"/><path fill="url(#iRSx90y)" class="mytsuknfz"/><path fill="url(#ib4f4xd)" class="mytsuknfz"/><path fill="url(#i7smcrm)" class="mytsuknfz"/><path fill="url(#iwMImEd)" class="mytsuknfz"/><path fill="url(#i4lXIBb)" class="mytsuknfz"/><path fill="url(#ikcz3ld)" class="mytsuknfz"/><path fill="url(#ipRLXKc)" class="mytsuknfz"/><g filter="url(#iPSte3b)"><path stroke="url(#iZOMrOe)" class="avwk89bpw"/></g><g filter="url(#iJhp3pb)"><path stroke="url(#iqzAIYd)" class="glqqg7rlr"/></g><g filter="url(#iPE9tkz)"><path stroke="url(#iehSYlr)" class="mnlku6pnw"/></g><g filter="url(#iwJnIKd)"><path stroke="url(#ibjZ2wd)" class="be8q09bem"/></g><g filter="url(#iJmKoye)"><path stroke="url(#iSPkpne)" class="iz1fm9urn"/></g><g filter="url(#imdi6ee)"><path stroke="url(#iS0C0De)" class="z_k4ifbuw"/></g><g filter="url(#iC3Zfxe)"><path stroke="url(#ijpgHpr)" class="a81slgj_v"/></g><g filter="url(#ig7fDOe)"><path stroke="url(#idMTose)" class="x66g42y5k"/></g><g filter="url(#ifp60ic)"><path stroke="url(#iLgtWEc)" class="kq4oiwbmh"/></g><g filter="url(#i82WVnP)"><path stroke="url(#iVMMgFc)" class="jbz6lebzj"/></g><g filter="url(#inKddKb)"><path fill="url(#iZdelTg)" clip-rule="evenodd" class="wqmzgbb4x"/><path fill="url(#iWPpZQc)" clip-rule="evenodd" class="wqmzgbb4x"/><path fill="url(#ipcaDcc)" clip-rule="evenodd" class="wqmzgbb4x"/><path fill="url(#iQCLcBb)" clip-rule="evenodd" class="wqmzgbb4x"/><path fill="url(#ie6D04d)" clip-rule="evenodd" class="wqmzgbb4x"/><path fill="url(#iwAhe8Y)" clip-rule="evenodd" class="wqmzgbb4x"/><path fill="url(#iIOuhCc)" clip-rule="evenodd" class="wqmzgbb4x"/><path fill="url(#ibeBams)" clip-rule="evenodd" class="wqmzgbb4x"/><path fill="url(#iYsHp6b)" clip-rule="evenodd" class="wqmzgbb4x"/><path fill="url(#iXvl2je)" clip-rule="evenodd" class="wqmzgbb4x"/><path fill="url(#iRd1Nxb)" clip-rule="evenodd" class="wqmzgbb4x"/></g><path fill="url(#iNJBdkU)" class="b5g3i3mag"/><path fill="url(#iidsVGS)" class="b5g3i3mag"/><path fill="url(#injsPjF)" class="b5g3i3mag"/><path fill="url(#i72TxPd)" class="zar_-tbdp"/><path fill="url(#i2Q42Cd)" class="zar_-tbdp"/><path fill="url(#ierll2n)" class="zar_-tbdp"/><path fill="url(#iJUJ9ne)" class="vkuy99wyx"/><path fill="url(#icmm0cu)" class="vkuy99wyx"/><path fill="url(#i4DZjQb)" class="vkuy99wyx"/><path fill="url(#iP23HTo)" class="vkuy99wyx"/><path fill="url(#ioV72pd)" class="vkuy99wyx"/><path fill="url(#i3mPSAb)" class="vkuy99wyx"/><path fill="url(#ijcHdGF)" class="ld1wwbc5m"/><g filter="url(#ivheC5m)"><path stroke="url(#iAXZo0S)" class="phx3m2o6y"/></g><g filter="url(#iUAGbrd)"><path fill="url(#iuj8WEb)" class="vj-ji9bgo"/></g><g filter="url(#i4Q8SJc)"><path fill="url(#isqgH1c)" class="f5295wb0w"/><path fill="url(#iQIRKoe)" class="f5295wb0w"/></g><g filter="url(#iDGovtc)"><path class="gvx383b6f"/><path fill="url(#iuWbXBd)" class="t1kgzsbog"/></g><g filter="url(#iyTrhlz)"><path class="fp5cjjbst"/><path fill="url(#iuAjnec)" class="tw121vbkw"/></g><g filter="url(#iO5Acwv)"><path fill="url(#irOojqc)" class="vwyklu7ge"/><path fill="url(#i21Xgru)" class="vwyklu7ge"/><path fill="url(#irxGjec)" class="vwyklu7ge"/><path fill="url(#iKbr90d)" class="vwyklu7ge"/><path fill="url(#i7O26Cb)" class="vwyklu7ge"/><path fill="url(#i8racne)" class="vwyklu7ge"/><path fill="url(#iHlzADe)" class="vwyklu7ge"/><path fill="url(#i3joHGb)" class="vwyklu7ge"/></g><path fill="url(#i2XEdTb)" class="vwyklu7ge"/><g filter="url(#iHTyyjd)"><path class="q1i04-wtq"/></g><g filter="url(#i11KsCd)"><path class="ojnk7r2ge"/><path fill="url(#iEUEKid)" class="rxks21fwn"/><path fill="url(#iVuyTxB)" class="rxks21fwn"/><path fill="url(#iXCMBkd)" class="rxks21fwn"/><path fill="url(#ilTBJJb)" class="rxks21fwn"/></g><path fill="url(#ixktD2c)" class="rxks21fwn"/><path fill="url(#iF0jTEw)" class="rxks21fwn"/><path stroke="url(#iD2xRYd)" class="pq-52xb7w"/><g filter="url(#i8joSpd)"><path class="hddoqrb5g"/></g><g filter="url(#itfnGib)"><path class="ztw57ybxa"/></g><g filter="url(#iuPXVne)"><path class="tvegm0b0e"/></g><g filter="url(#iRixG9b)"><path clip-rule="evenodd" class="ukbi9ibdy"/></g><path class="zluqs36rc"/><path fill="url(#iVr9Pcb)" class="w-nzz0bfc"/><path class="l2h2_dbku"/><g filter="url(#izQ1rfc)"><path class="vafozdblv"/><path fill="url(#iKMnImG)" class="rrwt_sybr"/></g><g filter="url(#ipfFPvb)"><path fill="url(#iDzmSIe)" class="saqt6rgiq"/></g><path class="mjdr6drfp"/><path fill="url(#i6O9hwe)" class="yqfikzbff"/><path class="nq3ktcbti"/><g filter="url(#ictWaeb)"><path fill="url(#izPZLBb)" class="cxp0cubbh"/></g><g filter="url(#iv2mzbd)"><ellipse transform="rotate(-27.914 15.706 13.133)" class="xhd6cwn_k"/><ellipse fill="url(#iAbbGwe)" transform="rotate(-27.914 15.706 13.133)" class="t99xpcb5c"/></g><g filter="url(#iPeYvhd)"><path class="tvr4njqri"/></g><g filter="url(#ipH7S0y)"><path class="m-mz3ctqo"/></g><g filter="url(#iDu0FzZ)"><path class="nzppnkb9d"/><path fill="url(#ieqzyrc)" class="k822heuyp"/></g><g filter="url(#iM54nrb)"><path class="t94fnz15t"/><path fill="url(#iaRKKuS)" class="ikraylbjd"/><path fill="url(#iVNzpqY)" class="ikraylbjd"/></g><g filter="url(#iLNvRjh)"><path stroke="url(#iqtzgpu)" class="jho8whtqw"/></g><g filter="url(#iPkUANe)"><path class="xbtprf59j"/></g><defs><radialGradient id="iYLyiwd" cx="0" cy="0" r="1" gradientTransform="matrix(2.33335 -6.04232 7.22855 2.79144 5.57 11.48)" gradientUnits="userSpaceOnUse"><stop offset=".475" class="o-iirh5hj"/><stop offset="1" class="b4grpcbtk"/></radialGradient><radialGradient id="iO99DCb" cx="0" cy="0" r="1" gradientTransform="rotate(130.764 2.719 7.05)scale(9.5721 2.30417)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="nui0_5bvt"/><stop offset="1" class="aijb2v7yw"/></radialGradient><radialGradient id="i2nSEEd" cx="0" cy="0" r="1" gradientTransform="matrix(.19531 2.2578 -.27074 .02342 4.295 4.668)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="tvgnczn8r"/><stop offset="1" class="fj2hmbbmv"/></radialGradient><radialGradient id="iRSx90y" cx="0" cy="0" r="1" gradientTransform="matrix(-.04685 3.40625 -.266 -.00366 5.944 3.504)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="tvgnczn8r"/><stop offset="1" class="fj2hmbbmv"/></radialGradient><radialGradient id="ib4f4xd" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 3.96875 -.56716 -.09602 7.912 2.738)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="tvgnczn8r"/><stop offset="1" class="fj2hmbbmv"/></radialGradient><radialGradient id="i7smcrm" cx="0" cy="0" r="1" gradientTransform="matrix(-.6629 .73793 -.64825 -.58233 9.411 3.097)" gradientUnits="userSpaceOnUse"><stop class="jx7ffbcje"/><stop offset="1" class="i3e9u7gak"/></radialGradient><radialGradient id="iwMImEd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6504 1.06501 -.658 -.40183 7.484 2.071)" gradientUnits="userSpaceOnUse"><stop class="jx7ffbcje"/><stop offset="1" class="i3e9u7gak"/></radialGradient><radialGradient id="i4lXIBb" cx="0" cy="0" r="1" gradientTransform="rotate(99.841 1.591 3.611)scale(1.24402 .95461)" gradientUnits="userSpaceOnUse"><stop class="jx7ffbcje"/><stop offset="1" class="i3e9u7gak"/></radialGradient><radialGradient id="ikcz3ld" cx="0" cy="0" r="1" gradientTransform="matrix(-.13758 .96306 -.68465 -.0978 3.67 3.886)" gradientUnits="userSpaceOnUse"><stop class="jx7ffbcje"/><stop offset="1" class="i3e9u7gak"/></radialGradient><radialGradient id="ipRLXKc" cx="0" cy="0" r="1" gradientTransform="matrix(-.88951 .77545 -.60682 -.69608 11.451 6.738)" gradientUnits="userSpaceOnUse"><stop class="bq0xhibbj"/><stop offset="1" class="khbnhvbup"/></radialGradient><radialGradient id="iWPpZQc" cx="0" cy="0" r="1" gradientTransform="rotate(97.539 1.701 16.566)scale(5.64508 7.05185)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="ipcaDcc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.53891 2.38667 -3.1359 -4.64985 14.891 17.383)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iQCLcBb" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.864 10.283)scale(2.64189 2.0286)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="ie6D04d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.58426 2.59239 -1.8261 -1.11597 13.327 11.766)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iwAhe8Y" cx="0" cy="0" r="1" gradientTransform="matrix(1.68712 3.20963 -4.45545 2.34197 14.397 4.091)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iIOuhCc" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 11.563 8.681)scale(2.50226 3.49686)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="ibeBams" cx="0" cy="0" r="1" gradientTransform="matrix(-2.2631 .6584 -1.37302 -4.71952 27.935 12.938)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iYsHp6b" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 12.542 10.242)scale(3.56281 4.53849)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iXvl2je" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1102 -3.2532 2.5731 -.87811 24.527 9.95)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iRd1Nxb" cx="0" cy="0" r="1" gradientTransform="matrix(1.84606 .19364 -.31375 2.99116 11.178 12.894)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iidsVGS" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.10937 -1.15625 0 6.835 12.039)" gradientUnits="userSpaceOnUse"><stop class="vm40c2rnb"/><stop offset="1" class="in_wled_m"/></radialGradient><radialGradient id="i2Q42Cd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.05789 2.36576 -2.0517 -6.98818 25.18 27.22)" gradientUnits="userSpaceOnUse"><stop class="cedqx2rkm"/><stop offset="1" class="xi0shyhbu"/></radialGradient><radialGradient id="ierll2n" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.62502 2.65624 0 10.595 29.586)" gradientUnits="userSpaceOnUse"><stop class="fp2gw167u"/><stop offset="1" class="rnij5z0qd"/></radialGradient><radialGradient id="icmm0cu" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.65451 -5.4375 0 2.685 12.586)" gradientUnits="userSpaceOnUse"><stop class="rz1t4jbgv"/><stop offset="1" class="xkxmx1bvv"/></radialGradient><radialGradient id="i4DZjQb" cx="0" cy="0" r="1" gradientTransform="matrix(-10.10928 -2.13275 .90224 -4.27661 17.408 19.859)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="m2mta8b_j"/><stop offset="1" class="tx_pqhb7h"/></radialGradient><radialGradient id="iP23HTo" cx="0" cy="0" r="1" gradientTransform="matrix(-5.69115 0 0 -5.6259 11.455 15.446)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="m2mta8b_j"/><stop offset="1" class="tx_pqhb7h"/></radialGradient><radialGradient id="ijcHdGF" cx="0" cy="0" r="1" gradientTransform="matrix(1.96875 3.9375 -4.4375 2.21876 17.875 19.344)" gradientUnits="userSpaceOnUse"><stop offset=".492" class="y9yel1bup"/><stop offset="1" class="l_gp-_bkz"/></radialGradient><radialGradient id="isqgH1c" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 45.361 -47.391)scale(3.35614 4.0977)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="iQIRKoe" cx="0" cy="0" r="1" gradientTransform="matrix(1.6151 .90528 -.25594 .45661 24.942 11.92)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="iuWbXBd" cx="0" cy="0" r="1" gradientTransform="matrix(1.8534 -.13786 .10777 1.44884 24.108 14.121)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="iuAjnec" cx="0" cy="0" r="1" gradientTransform="rotate(-180 6.535 6.992)scale(1.2962)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="irOojqc" cx="0" cy="0" r="1" gradientTransform="matrix(-7.98316 3.6813 -4.92736 -10.68533 22.228 13.324)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="i21Xgru" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 9.057 9.408)scale(2.92395 2.03619)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="irxGjec" cx="0" cy="0" r="1" gradientTransform="rotate(-71.832 22.744 -.433)scale(5.07509 6.43934)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="iKbr90d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.57695 9.05062 -11.31316 -1.97117 19.974 12.813)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="ermiffb8a"/><stop offset="1" class="d5lrpr21j"/></radialGradient><radialGradient id="i7O26Cb" cx="0" cy="0" r="1" gradientTransform="matrix(-8.47672 1.66353 -2.86409 -14.59432 20.94 15.449)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="i8racne" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.41257 1.73361 0 21.543 12.81)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="iHlzADe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.61111 1.84644 0 16.17 12.53)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="i3joHGb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.06812 3.96084 -3.16932 -.85467 20.416 9.967)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="i2XEdTb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.57769 0 0 -7.91196 24.973 14.636)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="iEUEKid" cx="0" cy="0" r="1" gradientTransform="rotate(-102.564 16.065 -.125)scale(2.57059 .79223)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="ilTBJJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.95672 0 0 -.26747 19.387 15.788)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iF0jTEw" cx="0" cy="0" r="1" gradientTransform="rotate(145.529 7.255 10.504)scale(2.04165 2.45375)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="wln98ypvp"/><stop offset="1" class="p13423bzd"/></radialGradient><radialGradient id="iVr9Pcb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9959 -1.58408 0 21.396 13.25)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iKMnImG" cx="0" cy="0" r="1" gradientTransform="matrix(-.28468 -.36685 .50506 -.39193 21.116 13.354)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i6O9hwe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9959 -1.58409 0 16.04 13.25)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iAbbGwe" cx="0" cy="0" r="1" gradientTransform="matrix(-.0095 -.60646 .72899 -.01141 15.688 13.52)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ieqzyrc" cx="0" cy="0" r="1" gradientTransform="matrix(1.54917 -3.38228 1.73029 .79252 11.772 10.648)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iaRKKuS" cx="0" cy="0" r="1" gradientTransform="matrix(-2.59243 5.39052 -8.81319 -4.23847 21.064 4.256)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iVNzpqY" cx="0" cy="0" r="1" gradientTransform="matrix(-.25819 1.67824 -3.61064 -.55548 18.976 4.71)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="iPSte3b" width=".423" height="2.22" x="4.15" y="4.694" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3866" stdDeviation=".05"/></filter><filter id="iJhp3pb" width=".345" height="2.572" x="5.704" y="4.265" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3866" stdDeviation=".05"/></filter><filter id="iPE9tkz" width=".509" height="1.681" x="7.181" y="4.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3866" stdDeviation=".05"/></filter><filter id="iwJnIKd" width="1.556" height="3.487" x="3.015" y="4.044" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3866" stdDeviation=".2"/></filter><filter id="iJmKoye" width="1.2" height="3.889" x="4.701" y="3.115" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3866" stdDeviation=".2"/></filter><filter id="imdi6ee" width="1.488" height="4.773" x="6.248" y="2.189" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3866" stdDeviation=".2"/></filter><filter id="iC3Zfxe" width="2.002" height="4.299" x="7.652" y="3.204" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3866" stdDeviation=".2"/></filter><filter id="ig7fDOe" width="1.412" height="1.358" x="3.305" y="6.562" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3866" stdDeviation=".1"/></filter><filter id="ifp60ic" width="1.118" height=".999" x="4.954" y="6.354" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3866" stdDeviation=".1"/></filter><filter id="i82WVnP" width="1.312" height="1.023" x="6.22" y="6.162" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3866" stdDeviation=".1"/></filter><filter id="inKddKb" width="18.685" height="19.185" x="9.5" y="2.765" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3866"/></filter><filter id="ivheC5m" width="9.217" height="11.911" x="5.06" y="12.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3866" stdDeviation=".75"/></filter><filter id="iUAGbrd" width="4.1" height="3.95" x="10.991" y="12.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3866"/></filter><filter id="i4Q8SJc" width="3.95" height="4.2" x="22.668" y="11.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3866"/></filter><filter id="iDGovtc" width="3.637" height="3.637" x="22.825" y="12.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3866" stdDeviation=".25"/></filter><filter id="iyTrhlz" width="3.137" height="3.137" x="11.421" y="12.415" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3866" stdDeviation=".125"/></filter><filter id="iO5Acwv" width="12.509" height="13.751" x="12.463" y="7.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3866"/></filter><filter id="iHTyyjd" width="3.304" height="4.292" x="16.866" y="12.864" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3866" stdDeviation=".25"/></filter><filter id="i11KsCd" width="2.804" height="3.792" x="17.316" y="12.944" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3866" stdDeviation=".125"/></filter><filter id="i8joSpd" width="3.639" height="1.578" x="19.92" y="12.259" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3866"/></filter><filter id="itfnGib" width="3.639" height="1.578" x="13.878" y="12.259" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3866"/></filter><filter id="iuPXVne" width="2.965" height="1.294" x="14.043" y="10.558" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3866"/></filter><filter id="iRixG9b" width="2.965" height="1.294" x="20.693" y="10.558" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3866"/></filter><filter id="izQ1rfc" width=".92" height=".809" x="20.518" y="12.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3866" stdDeviation=".05"/></filter><filter id="ipfFPvb" width="1.003" height="1.03" x="21.572" y="12.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3866" stdDeviation=".1"/></filter><filter id="ictWaeb" width="1.12" height="1.186" x="16.118" y="12.771" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3866" stdDeviation=".1"/></filter><filter id="iv2mzbd" width="1.075" height=".819" x="15.169" y="12.724" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3866" stdDeviation=".05"/></filter><filter id="iPeYvhd" width="3.239" height="1.664" x="20.499" y="10.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3866" stdDeviation=".2"/></filter><filter id="ipH7S0y" width="3.239" height="1.664" x="13.807" y="10.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3866" stdDeviation=".2"/></filter><filter id="iDu0FzZ" width="5.088" height="5.458" x="11.009" y="5.554" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.262745 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3866"/><feGaussianBlur result="effect2_foregroundBlur_4002_3866" stdDeviation=".2"/></filter><filter id="iM54nrb" width="10.637" height="6.984" x="14.895" y="4.127" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3866"/><feGaussianBlur result="effect2_foregroundBlur_4002_3866" stdDeviation=".125"/></filter><filter id="iLNvRjh" width="1.269" height="2.699" x="14.869" y="5.653" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3866" stdDeviation=".1"/></filter><filter id="iPkUANe" width="8.048" height="4.298" x="17.925" y="6.498" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3866" stdDeviation=".5"/></filter><linearGradient id="is9W90d" x1="6.053" x2="6.053" y1="12.142" y2="10.438" gradientUnits="userSpaceOnUse"><stop class="yt_0wt3yl"/><stop offset="1" class="eujvqlb2y"/></linearGradient><linearGradient id="iZOMrOe" x1="4.543" x2="4.552" y1="4.835" y2="6.837" gradientUnits="userSpaceOnUse"><stop class="z0iyhs38d"/><stop offset="1" class="l7n7uk6bh"/></linearGradient><linearGradient id="iqzAIYd" x1="5.963" x2="5.99" y1="4.406" y2="6.769" gradientUnits="userSpaceOnUse"><stop class="z0iyhs38d"/><stop offset="1" class="l7n7uk6bh"/></linearGradient><linearGradient id="iehSYlr" x1="7.722" x2="7.725" y1="5.006" y2="6.453" gradientUnits="userSpaceOnUse"><stop class="z0iyhs38d"/><stop offset="1" class="l7n7uk6bh"/></linearGradient><linearGradient id="ibjZ2wd" x1="3.309" x2="3.728" y1="4.948" y2="7.555" gradientUnits="userSpaceOnUse"><stop class="wug9f7p2x"/><stop offset="1" class="ct57ro4xv"/></linearGradient><linearGradient id="iSPkpne" x1="4.453" x2="4.665" y1="4.074" y2="7.198" gradientUnits="userSpaceOnUse"><stop class="wug9f7p2x"/><stop offset="1" class="ct57ro4xv"/></linearGradient><linearGradient id="iS0C0De" x1="6.603" x2="7.705" y1="3.318" y2="6.994" gradientUnits="userSpaceOnUse"><stop class="wug9f7p2x"/><stop offset="1" class="ct57ro4xv"/></linearGradient><linearGradient id="ijpgHpr" x1="7.557" x2="7.873" y1="4.267" y2="7.699" gradientUnits="userSpaceOnUse"><stop class="wug9f7p2x"/><stop offset="1" class="ct57ro4xv"/></linearGradient><linearGradient id="idMTose" x1="4.603" x2="3.511" y1="6.815" y2="6.746" gradientUnits="userSpaceOnUse"><stop class="s6abn5boy"/><stop offset="1" class="q7h19xvvk"/></linearGradient><linearGradient id="iLgtWEc" x1="5.875" x2="5.311" y1="6.643" y2="6.502" gradientUnits="userSpaceOnUse"><stop class="s6abn5boy"/><stop offset="1" class="q7h19xvvk"/></linearGradient><linearGradient id="iVMMgFc" x1="7.376" x2="6.573" y1="6.456" y2="6.243" gradientUnits="userSpaceOnUse"><stop class="s6abn5boy"/><stop offset="1" class="q7h19xvvk"/></linearGradient><linearGradient id="iZdelTg" x1="24.479" x2="16.126" y1="5.449" y2="20.921" gradientUnits="userSpaceOnUse"><stop class="c1nwhtznm"/><stop offset="1" class="ogqxd-bue"/></linearGradient><linearGradient id="iNJBdkU" x1="3.904" x2="8.279" y1="12.149" y2="12.149" gradientUnits="userSpaceOnUse"><stop class="u-9w58unm"/><stop offset=".743" class="gv7qteejy"/></linearGradient><linearGradient id="injsPjF" x1="6.174" x2="6.174" y1="11.563" y2="11.821" gradientUnits="userSpaceOnUse"><stop class="s68njbc8b"/><stop offset="1" class="ha46_3b_b"/></linearGradient><linearGradient id="i72TxPd" x1="18.688" x2="5.165" y1="28.764" y2="12.586" gradientUnits="userSpaceOnUse"><stop class="dkttnh3ka"/><stop offset=".751" class="j0qmv8b6d"/></linearGradient><linearGradient id="iJUJ9ne" x1="9.17" x2="11.063" y1="26.009" y2="19.818" gradientUnits="userSpaceOnUse"><stop offset=".1" class="nrxnoi8to"/><stop offset="1" class="o8-s5pjlc"/></linearGradient><linearGradient id="ioV72pd" x1="13.509" x2="12.724" y1="24.32" y2="22.688" gradientUnits="userSpaceOnUse"><stop class="hzm5vwgac"/><stop offset=".732" class="yy_71ub6o"/></linearGradient><linearGradient id="i3mPSAb" x1="6.7" x2="6.7" y1="12.586" y2="13.608" gradientUnits="userSpaceOnUse"><stop class="ignlpnblb"/><stop offset="1" class="a8kog2b_j"/></linearGradient><linearGradient id="iAXZo0S" x1="6.717" x2="12.467" y1="14.294" y2="22.575" gradientUnits="userSpaceOnUse"><stop class="ius0mclhc"/><stop offset="1" class="f3d24-ppq"/></linearGradient><linearGradient id="iuj8WEb" x1="11.054" x2="12.576" y1="14.091" y2="14.091" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="iVuyTxB" x1="17.566" x2="18.718" y1="15.618" y2="15.618" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="iXCMBkd" x1="18.718" x2="18.718" y1="16.599" y2="15.849" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="ixktD2c" x1="18.814" x2="18.814" y1="16.566" y2="16.395" gradientUnits="userSpaceOnUse"><stop class="p13423bzd"/><stop offset="1" class="wln98ypvp"/></linearGradient><linearGradient id="iD2xRYd" x1="17.411" x2="17.977" y1="18.329" y2="17.455" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="iDzmSIe" x1="22.351" x2="21.966" y1="13.317" y2="13.554" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="izPZLBb" x1="16.953" x2="16.567" y1="13.317" y2="13.554" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iqtzgpu" x1="15.169" x2="15.838" y1="6.375" y2="7.939" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-raising-hand-medium-dark" /></template>
<style>
.a81slgj_v {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m9.059 3.65l-.813 3.407");
}

.a8kog2b_j {
  stop-color: var(--svg-color--6a51a2, #6A51A2);
  stop-opacity: 0;
}

.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.aijb2v7yw {
  stop-color: var(--svg-color--6a413b, #6A413B);
  stop-opacity: 0;
}

.avwk89bpw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m4.287 4.832l.149 1.945");
}

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
}

.b4grpcbtk {
  stop-color: var(--svg-color--7a544a, #7A544A);
}

.b5g3i3mag {
  d: path("M4.068 11.763c0-.11.09-.2.2-.2H8.08c.11 0 .2.09.2.2v1.714H4.07z");
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.be8q09bem {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m3.613 4.471l.36 2.633");
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.bq0xhibbj {
  stop-color: var(--svg-color--866a60, #866A60);
}

.c1nwhtznm {
  stop-color: var(--svg-color--45363a, #45363A);
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cedqx2rkm {
  stop-color: var(--svg-color--9e7fdf, #9E7FDF);
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

.ct57ro4xv {
  stop-color: var(--svg-color--95766f, #95766F);
  stop-opacity: 0;
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cxp0cubbh {
  d: path("M17.038 13.632c0-.354-.288-.59-.366-.661l-.354.342l.218.444z");
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.d5lrpr21j {
  stop-color: var(--svg-color--793e68, #793E68);
}

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
  stop-opacity: 0;
}

.dkttnh3ka {
  stop-color: var(--svg-color--8663c9, #8663C9);
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.ermiffb8a {
  stop-color: var(--svg-color--793e68, #793E68);
  stop-opacity: 0;
}

.eujvqlb2y {
  stop-color: var(--svg-color--724130, #724130);
  stop-opacity: 0;
}

.f3d24-ppq {
  stop-color: var(--svg-color--9478ce, #9478CE);
  stop-opacity: 0;
}

.f5295wb0w {
  d: path("M24.643 15.959a1.975 1.975 0 1 0 0-3.95a1.975 1.975 0 0 0 0 3.95");
}

.fj2hmbbmv {
  stop-color: var(--svg-color--714131, #714131);
  stop-opacity: 0;
}

.fp2gw167u {
  stop-color: var(--svg-color--8969ba, #8969BA);
}

.fp5cjjbst {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M12.99 15.302a1.318 1.318 0 1 0 0-2.637a1.318 1.318 0 0 0 0 2.637");
}

.ft5dv1b6b {
  fill: none;
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gcfqr7bfg {
  stop-color: var(--svg-color--714350, #714350);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.glqqg7rlr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m5.912 4.402l-.07 2.297");
}

.gv7qteejy {
  stop-color: var(--svg-color--463168, #463168);
}

.gvx383b6f {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M24.643 15.302a1.318 1.318 0 1 0 0-2.637a1.318 1.318 0 0 0 0 2.637");
}

.ha46_3b_b {
  stop-color: var(--svg-color--4f396f, #4F396F);
  stop-opacity: 0;
}

.hddoqrb5g {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M20.12 13.285c.326-.573.82-1.026 1.887-1.026c.467 0 .917.13 1.317.453c.33.267.286.608.03.736l-.682.39c-.8-.26-1.685-.294-2.552-.553");
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

.hzm5vwgac {
  stop-color: var(--svg-color--8967cb, #8967CB);
}

.i3e9u7gak {
  stop-color: var(--svg-color--997a6f, #997A6F);
  stop-opacity: 0;
}

.ignlpnblb {
  stop-color: var(--svg-color--6a51a2, #6A51A2);
}

.ikraylbjd {
  d: path("M17.977 4.42c-1.39-.306-2.638 1.08-2.782 1.595c1.29 4.352 4.557 4.113 7.782 3.755c1.93-.214 2.14.665 2.304 1.09c0-4.827-4.105-5.733-7.268-6.432z");
}

.in_wled_m {
  stop-color: var(--svg-color--655188, #655188);
  stop-opacity: 0;
}

.ius0mclhc {
  stop-color: var(--svg-color--9478ce, #9478CE);
}

.iz1fm9urn {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M5.3 3.515v3.089");
}

.j0qmv8b6d {
  stop-color: var(--svg-color--7a5fb3, #7A5FB3);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jbz6lebzj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M7.232 6.462c-.13.165-.501.36-.712.423");
}

.jho8whtqw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.169 5.953c.028.299.288 1.42.669 2.099");
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.jx7ffbcje {
  stop-color: var(--svg-color--997a6f, #997A6F);
}

.k822heuyp {
  d: path("M12.496 6.633c.694-.736 2.008-.737 2.615-.627l.486 1.584c-.31-.048-.587.062-.82.288c-.55 1.547-2.442 2.4-3.319 2.634c-.182-1.831.134-2.922 1.038-3.879");
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.khbnhvbup {
  stop-color: var(--svg-color--866a60, #866A60);
  stop-opacity: 0;
}

.kq4oiwbmh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M5.773 6.654c-.13.165-.333.3-.519.4");
}

.l__dw9bpv {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
  stop-opacity: 0;
}

.l_gp-_bkz {
  stop-color: var(--svg-color--8e655d, #8E655D);
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l2h2_dbku {
  fill: var(--svg-color--000, #000);
  d: path("M20.772 13.76c0-.348.278-.627.627-.627a.625.625 0 0 1 .558.917h-1.11a.57.57 0 0 1-.076-.29");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l7n7uk6bh {
  stop-color: var(--svg-color--331c1a, #331C1A);
  stop-opacity: 0;
}

.ld1wwbc5m {
  d: path("M18.718 23.692c-1.268 0-2.296-.985-2.296-2.2v-2.6c0-1.214 1.028-2.2 2.296-2.2s2.296.986 2.296 2.2v2.6c0 1.215-1.028 2.2-2.296 2.2");
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

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.m-mz3ctqo {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.445 11.071c-.396-.096-1.38-.048-2.038.423");
}

.m2mta8b_j {
  stop-color: var(--svg-color--362659, #362659);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mjdr6drfp {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.783 12.332c-.802 0-1.479.552-1.663 1.3a.336.336 0 0 0 .329.418h2.738c.174 0 .314-.16.28-.334a1.72 1.72 0 0 0-1.684-1.384");
}

.mnlku6pnw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("M7.553 5.004L7.318 6.41");
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.mytsuknfz {
  d: path("M2.99 8.845c-.125-1.922-.28-2.959-.328-3.641c-.035-.512.024-1.066.711-1.191c.598-.075.883.451.907.66c-.003-.2 0-.68 0-.805c0-.21.007-.976.859-.976c.601 0 .816.587.8.863c.011-.102.023-.413.036-.707c.018-.434.251-.99.945-.977c.598.04.793.613.766.977l-.117 1.867c.023-.188.102-.665.277-1.34s.702-.72.957-.683c.326.046.88.36.648 1.273c-.275 1.156-.462 2.644-.527 3.285c.324-.133.642-.412 1.002-.787s.886-.383 1.183-.16c.34.292.522.967.12 1.369c-.463.425-2.13 2.405-2.957 3.395c-.23.291-.997.875-2.235.875c-2.203-.094-2.941-1.677-3.047-3.297");
}

.nq3ktcbti {
  fill: var(--svg-color--000, #000);
  d: path("M16.664 13.76a.625.625 0 0 0-.627-.627a.625.625 0 0 0-.558.917h1.11a.6.6 0 0 0 .075-.29");
}

.nrxnoi8to {
  stop-color: var(--svg-color--6b45ad, #6B45AD);
}

.nui0_5bvt {
  stop-color: var(--svg-color--67383d, #67383D);
}

.nzppnkb9d {
  fill: var(--svg-color--2a191e, #2A191E);
  d: path("M12.496 6.633c.694-.736 2.008-.737 2.615-.627l.486 1.584c-.31-.048-.587.062-.82.288c-.55 1.547-2.442 2.4-3.319 2.634c-.182-1.831.134-2.922 1.038-3.879");
}

.o-iirh5hj {
  stop-color: var(--svg-color--815854, #815854);
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.o8-s5pjlc {
  stop-color: var(--svg-color--6b45ad, #6B45AD);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ogqxd-bue {
  stop-color: var(--svg-color--1c151f, #1C151F);
}

.ojnk7r2ge {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m18.249 13.54l-.653 2.087a.662.662 0 0 0 .64.858h.965a.664.664 0 0 0 .639-.858l-.653-2.087c-.14-.462-.792-.462-.938 0");
}

.olqyf7fmb {
  stop-color: var(--svg-color--875e5e, #875E5E);
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

.p13423bzd {
  stop-color: var(--svg-color--693b40, #693B40);
}

.p88c31myn {
  stop-color: var(--svg-color--815a5b, #815A5B);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.phx3m2o6y {
  d: path("M7.06 13.514v5.172a2 2 0 0 0 1.38 1.901l4.183 1.363");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pq-52xb7w {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.996 17.09a3.66 3.66 0 0 0 1.722.418c.637 0 1.224-.152 1.721-.418a.24.24 0 0 1 .29.049a.23.23 0 0 1 .025.292l-.042-.027a2.372 2.372 0 0 1-3.988 0zm0 0a.24.24 0 0 0-.29.051a.23.23 0 0 0-.024.29z");
}

.q1i04-wtq {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m18.236 13.71l-.84 2.087a.662.662 0 0 0 .64.858h.965a.664.664 0 0 0 .64-.858l-.653-2.087c-.14-.462-.605-.462-.752 0");
}

.q7h19xvvk {
  stop-color: var(--svg-color--8e6e66, #8E6E66);
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

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.rnij5z0qd {
  stop-color: var(--svg-color--8969ba, #8969BA);
  stop-opacity: 0;
}

.rrwt_sybr {
  d: path("M21.318 12.897c.078.104-.085.231-.27.37c-.186.139-.323.236-.401.132s.009-.301.194-.44c.186-.139.4-.167.477-.062");
}

.rxks21fwn {
  d: path("m18.249 13.54l-.653 2.087a.662.662 0 0 0 .64.858h.965a.664.664 0 0 0 .639-.858l-.653-2.087c-.14-.462-.792-.462-.938 0");
}

.rz1t4jbgv {
  stop-color: var(--svg-color--8b6ebc, #8B6EBC);
}

.s68njbc8b {
  stop-color: var(--svg-color--4f396f, #4F396F);
}

.s6abn5boy {
  stop-color: var(--svg-color--8e6e66, #8E6E66);
}

.saqt6rgiq {
  d: path("M22.375 13.616a1.03 1.03 0 0 0-.284-.567l-.32.35l.145.28z");
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.t1kgzsbog {
  d: path("M24.643 15.302a1.318 1.318 0 1 0 0-2.637a1.318 1.318 0 0 0 0 2.637");
}

.t94fnz15t {
  fill: var(--svg-color--2f1920, #2F1920);
  d: path("M17.977 4.42c-1.39-.306-2.638 1.08-2.782 1.595c1.29 4.352 4.557 4.113 7.782 3.755c1.93-.214 2.14.665 2.304 1.09c0-4.827-4.105-5.733-7.268-6.432z");
}

.t99xpcb5c {
  cx: 15.706px;
  cy: 13.133px;
  rx: 0.478px;
  ry: 0.242px;
}

.t9k87pm2r {
  stop-color: var(--svg-color--875555, #875555);
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tvegm0b0e {
  fill: var(--svg-color--352827, #352827);
  d: path("m14.547 11.801l-.005.003a.33.33 0 0 1-.338-.564l.001-.002l.004-.002l.012-.006a2 2 0 0 1 .182-.095a4 4 0 0 1 .503-.198c.417-.133 1-.245 1.63-.134a.33.33 0 0 1-.114.648c-.49-.086-.96 0-1.316.113a3.4 3.4 0 0 0-.559.237");
}

.tvgnczn8r {
  stop-color: var(--svg-color--714131, #714131);
}

.tvr4njqri {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M21.099 11.071c.396-.096 1.38-.048 2.038.423");
}

.tw121vbkw {
  d: path("M12.99 15.302a1.318 1.318 0 1 0 0-2.637a1.318 1.318 0 0 0 0 2.637");
}

.tx_pqhb7h {
  stop-color: var(--svg-color--5e4490, #5E4490);
  stop-opacity: 0;
}

.u-9w58unm {
  stop-color: var(--svg-color--745c92, #745C92);
}

.uj7hgsb3u {
  stop-color: var(--svg-color--815a5b, #815A5B);
}

.ukbi9ibdy {
  fill: var(--svg-color--352827, #352827);
  fill-rule: evenodd;
  d: path("m23.298 11.24l-.169.282za.33.33 0 0 1-.338.565h-.001l-.006-.004l-.026-.014l-.112-.057c-.1-.048-.244-.11-.42-.166c-.357-.114-.827-.2-1.316-.113a.33.33 0 0 1-.115-.648c.63-.111 1.213 0 1.63.134a4 4 0 0 1 .686.293l.012.006l.003.002z");
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.vafozdblv {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M21.318 12.897c.078.104-.085.231-.27.37c-.186.139-.323.236-.401.132s.009-.301.194-.44c.186-.139.4-.167.477-.062");
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.vj-ji9bgo {
  d: path("M12.966 15.959a1.975 1.975 0 1 0 0-3.95a1.975 1.975 0 0 0 0 3.95");
}

.vkuy99wyx {
  d: path("m18.076 20.55l-7.874 5.152a.65.65 0 0 0-.4-.472l-3.084-1.35c-2.5-.982-3.5-3.437-3.5-5.105v-5.192c0-.554.425-.997.935-.997h4.13c.52 0 .935.453.935.997v3.914c0 1.278 1 1.473 1 1.473l6 1.473z");
}

.vm40c2rnb {
  stop-color: var(--svg-color--655188, #655188);
}

.vwyklu7ge {
  d: path("M12.473 12.434h.016l-.013-.326l-.013-.376c.026-1.164.705-1.615.995-1.766q.029-.01.063-.025l.063-.025a2.83 2.83 0 0 0 1.46-1.515l.1-.238a.324.324 0 0 1 .567-.063a4.74 4.74 0 0 0 3.915 2.054h3.952c.221 0 1.329.108 1.395 1.636l-.146 3.772c-.151 3.44-2.838 5.75-6.117 5.75s-5.966-2.31-6.117-5.75z");
}

.w-nzz0bfc {
  d: path("M21.399 12.665a1.096 1.096 0 0 1 1.056 1.385h-2.117a1.1 1.1 0 0 1 1.06-1.384");
}

.wg3eepbwp {
  stop-color: var(--svg-color--805c54, #805C54);
}

.wln98ypvp {
  stop-color: var(--svg-color--693b40, #693B40);
  stop-opacity: 0;
}

.wqmzgbb4x {
  fill-rule: evenodd;
  d: path("M27.538 15.714a4 4 0 0 0 .397-1.751a4 4 0 0 0-.33-1.603h.007a4 4 0 0 0-.345-.63l-.002-.004a4 4 0 0 1-.646-2.173V9.54a4.05 4.05 0 0 0-4.05-4.05a.66.66 0 0 1-.56-.285a4.06 4.06 0 0 0-3.291-1.69c-1.354 0-2.56.671-3.292 1.69a.7.7 0 0 1-.56.285l-.104.002a4.05 4.05 0 0 0-3.945 4.048v.013c0 .77-.223 1.527-.646 2.173l-.003.005a4.05 4.05 0 0 0-.27 3.983a.63.63 0 0 1 0 .56A4 4 0 0 0 9.5 18a3.944 3.944 0 0 0 3.95 3.95h10.535a3.944 3.944 0 0 0 3.95-3.95c0-.621-.149-1.205-.397-1.727a.63.63 0 0 1 0-.559m-15.05-3.28h-.015l1.472 2.891c.151 3.44 1.494 0 4.773 0s4.709 3.83 4.86.39l1.395-3.925c-.066-1.528-1.174-1.636-1.395-1.636h-3.952A4.74 4.74 0 0 1 15.71 8.1a.324.324 0 0 0-.567.063l-.1.238a2.83 2.83 0 0 1-1.523 1.54l-.063.025c-.29.15-.97.602-.995 1.766l.013.376z");
}

.wrh2b4bbx {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
}

.wug9f7p2x {
  stop-color: var(--svg-color--95766f, #95766F);
}

.x_ik4kbfh {
  stop-color: var(--svg-color--714350, #714350);
}

.x66g42y5k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M3.605 7.62c.11-.063.618-.38.813-.758");
}

.xbtprf59j {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m21.672 8.852l-1.75.321a.845.845 0 1 1-.153-1.675h2.873c1.7 0 2.262 1.713 2.33 2.298a3.86 3.86 0 0 0-3.3-.944");
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xhd6cwn_k {
  cx: 15.706px;
  cy: 13.133px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.478px;
  ry: 0.242px;
}

.xi0shyhbu {
  stop-color: var(--svg-color--9e7fdf, #9E7FDF);
  stop-opacity: 0;
}

.xkxmx1bvv {
  stop-color: var(--svg-color--8b6ebc, #8B6EBC);
  stop-opacity: 0;
}

.y9yel1bup {
  stop-color: var(--svg-color--72434c, #72434C);
}

.yamoh3dov {
  stop-color: var(--svg-color--764e4c, #764E4C);
}

.ycrcotb4u {
  stop-color: var(--svg-color--986f60, #986F60);
  stop-opacity: 0;
}

.yqfikzbff {
  d: path("M16.037 12.665a1.095 1.095 0 0 0-1.056 1.385h2.117q.038-.141.04-.29a1.103 1.103 0 0 0-1.101-1.095");
}

.yt_0wt3yl {
  stop-color: var(--svg-color--724130, #724130);
}

.yy_71ub6o {
  stop-color: var(--svg-color--8967cb, #8967CB);
  stop-opacity: 0;
}

.z_k4ifbuw {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m7.137 2.604l-.29 3.944");
}

.z0iyhs38d {
  stop-color: var(--svg-color--331c1a, #331C1A);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zar_-tbdp {
  d: path("M19.683 20.586h.97c2.49 0 7.472 3.5 7.472 9H10.192v-3.5a.67.67 0 0 0-.414-.625l-3.073-1.375c-2.49-1-3.487-3.5-3.487-5.198v-5.287c0-.564.423-1.015.932-1.015h4.114c.517 0 .932.461.932 1.015v3.985c0 1.302.996 1.5.996 1.5l5.977 1.5z");
}

.zluqs36rc {
  fill: var(--svg-color--fff, #fff);
  d: path("M21.653 12.332c.802 0 1.479.552 1.663 1.3a.336.336 0 0 1-.329.418H20.25a.283.283 0 0 1-.28-.334a1.716 1.716 0 0 1 1.684-1.384");
}

.zoq8fuaif {
  stop-color: var(--svg-color--986f60, #986F60);
}

.ztw57ybxa {
  fill: var(--svg-color--272528, #272528);
  d: path("M17.316 13.285c-.325-.573-.82-1.026-1.887-1.026c-.467 0-.917.13-1.317.453c-.33.267-.286.608-.03.736l.683.39c.8-.26 1.685-.294 2.551-.553");
}

</style>
