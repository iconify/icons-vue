<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iLikite)"><path fill="url(#i9TFyxF)" class="yb7xsubhw"/><path fill="url(#imJrkkd)" class="yb7xsubhw"/><path fill="url(#iwAClXq)" class="yb7xsubhw"/><path fill="url(#iDjhZFe)" class="yb7xsubhw"/><path fill="url(#iPTBYmc)" class="yb7xsubhw"/></g><path fill="url(#igtPXve)" class="m1i1rlbvk"/><g filter="url(#iuuBJuc)"><path class="xk18tyb3e"/></g><path class="m3se_ob2r"/><path fill="url(#i4RHwye)" class="zqss5obsp"/><path fill="url(#i86fP2c)" class="zqss5obsp"/><path fill="url(#i23ntQe)" class="zqss5obsp"/><path class="jse2phbtg"/><path fill="url(#i2nIhZb)" class="om0oq7b1v"/><path fill="url(#ivP9Jjb)" class="om0oq7b1v"/><path fill="url(#i77Ytid)" class="om0oq7b1v"/><path fill="url(#i8Zzivd)" class="kvfq7h_0m"/><path fill="url(#iE5Ofte)" class="kvfq7h_0m"/><path fill="url(#iE6iQae)" class="kvfq7h_0m"/><path fill="url(#i1B5pTu)" class="biuac8r4x"/><path fill="url(#iJIw8ya)" class="biuac8r4x"/><path fill="url(#iwZFu8W)" class="dvr2s59yl"/><path fill="url(#iP7E3xc)" class="dvr2s59yl"/><path fill="url(#idlbkMe)" class="sp6_o9bxd"/><path fill="url(#iIvEVud)" class="sp6_o9bxd"/><path fill="url(#iXRw9pd)" class="sp6_o9bxd"/><path fill="url(#iz9xh1o)" class="sp6_o9bxd"/><path fill="url(#i6G3R0c)" class="sp6_o9bxd"/><g filter="url(#iNB2Qwd)"><path fill="url(#i1uMIud)" class="lwc2zdrqr"/></g><g filter="url(#igowGfe)"><path fill="url(#iPXFJHe)" class="momee7bch"/></g><g filter="url(#iZvwGDo)"><path fill="url(#iaz5sEW)" class="d2s-wtuyq"/></g><g filter="url(#izqCDIe)"><path class="vcv8c754j"/><path fill="url(#iU8Jczd)" class="u1e8ikbzb"/><path fill="url(#ibXRrGc)" class="u1e8ikbzb"/><path fill="url(#ixaGDYd)" class="u1e8ikbzb"/></g><g filter="url(#iiHHwed)"><path class="z5g21op2e"/></g><g filter="url(#iuPY6Ce)"><path fill="url(#iBVZlGV)" class="pv8cx5b7o"/><path fill="url(#i5oGPfb)" class="pv8cx5b7o"/><path fill="url(#ioQSTVd)" class="pv8cx5b7o"/><path fill="url(#iqH81bx)" class="pv8cx5b7o"/><path fill="url(#i4TNoOd)" class="pv8cx5b7o"/></g><g filter="url(#iASPQhb)"><path stroke="url(#icCtmNd)" class="cjq4b16bn"/></g><g filter="url(#isj8Tic)"><path stroke="url(#i8rhfrd)" class="luyfkt2yj"/></g><g filter="url(#ixVM0Sd)"><path stroke="url(#ic9kcre)" class="eqaszhbhb"/></g><g filter="url(#iisOCve)"><path fill="url(#i7WxSHe)" class="c230v9qll"/><path fill="url(#ifl4R2h)" class="c230v9qll"/></g><g filter="url(#iZFu5Kc)"><path fill="url(#ilj4o6d)" class="gwjnm0b5l"/></g><g filter="url(#i0YquFd)"><path class="tvy0a_bwh"/><path fill="url(#iL5WIFT)" class="xvpsbsbam"/></g><g filter="url(#iDfhDVe)"><path class="yygq1svpn"/><path fill="url(#iLXmoeb)" class="be93etbkd"/></g><g filter="url(#iQOe1ve)"><path fill="url(#iGmD1sc)" class="kr61v_sfd"/><path fill="url(#i7vi4Bb)" class="kr61v_sfd"/><path fill="url(#iJ2V6Td)" class="kr61v_sfd"/><path fill="url(#i6P3e9c)" class="kr61v_sfd"/><path fill="url(#iX2sh9d)" class="kr61v_sfd"/><path fill="url(#i2vUIWd)" class="kr61v_sfd"/><path fill="url(#idXGvXz)" class="kr61v_sfd"/><path fill="url(#icxMfjc)" class="kr61v_sfd"/></g><path fill="url(#i38YHpd)" class="kr61v_sfd"/><path fill="url(#iME4dFd)" class="kr61v_sfd"/><path fill="url(#i15PqVc)" class="kr61v_sfd"/><g filter="url(#iLxprYb)"><path class="ioxecjbjq"/></g><g filter="url(#iP3rTfc)"><path class="o0jeiob3a"/><path fill="url(#iWm6Aie)" class="cgh3_wbed"/><path fill="url(#ihzoVAb)" class="cgh3_wbed"/><path fill="url(#iTiggVb)" class="cgh3_wbed"/><path fill="url(#iq1I2nc)" class="cgh3_wbed"/><path fill="url(#ilnxXFc)" class="cgh3_wbed"/></g><g filter="url(#i08XxqZ)"><path stroke="url(#iwypcUq)" class="ptrn2nbeb"/></g><path class="x79uj10ff"/><g filter="url(#iUdTbFT)"><path class="q5e3l-wal"/></g><g filter="url(#iqEHSnY)"><path class="birn6lbkk"/></g><g filter="url(#ioRnrjd)"><path class="tru2658_b"/></g><g filter="url(#iuwGEGe)"><path class="z7l2_l5ut"/></g><g filter="url(#iOvm6hc)"><path class="i4syfobqj"/></g><g filter="url(#iDeab5K)"><path class="wqiol886i"/></g><path class="vy91i9bft"/><path fill="url(#iy4s2Xc)" class="kj5kxbbbl"/><path class="hx6yvt1fd"/><g filter="url(#iIWiCwz)"><path class="dpf88hj0u"/><path fill="url(#iUmVuje)" class="qea3jle_i"/></g><g filter="url(#iFRBdEc)"><path fill="url(#i9W7DLc)" class="r2qtbmb9n"/></g><path class="wn0fm3b_g"/><path fill="url(#ixyOlwc)" class="tf7b5e2qz"/><path class="mlnj98vrv"/><g filter="url(#iXD14Bc)"><path fill="url(#i0hsthe)" class="w4n-ob-5e"/></g><g filter="url(#iD2U1Je)"><ellipse transform="rotate(-27.914 13.307 9.992)" class="qb053jydf"/><ellipse fill="url(#iI0jKXc)" transform="rotate(-27.914 13.307 9.992)" class="qyd2qob8y"/></g><g filter="url(#iIbXpLQ)"><path fill="url(#i0vaKQd)" class="s2-xryl0i"/></g><g filter="url(#iHO1a4c)"><path fill="url(#iIvrIye)" class="psv7auxid"/></g><defs><radialGradient id="imJrkkd" cx="0" cy="0" r="1" gradientTransform="rotate(140.889 3.842 5.316)scale(4.24611 1.6566)" gradientUnits="userSpaceOnUse"><stop offset=".267" class="yd_laccri"/><stop offset="1" class="dmf0acl5m"/></radialGradient><radialGradient id="iwAClXq" cx="0" cy="0" r="1" gradientTransform="matrix(2.11985 0 0 3.47579 20.212 7.694)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="w9txrw6kc"/><stop offset="1" class="h-4ghpb7u"/></radialGradient><radialGradient id="iDjhZFe" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.90841 -5.85233 0 14.758 12.65)" gradientUnits="userSpaceOnUse"><stop offset=".493" class="dc6jrkblm"/><stop offset="1" class="oy6n6fbyn"/></radialGradient><radialGradient id="iPTBYmc" cx="0" cy="0" r="1" gradientTransform="rotate(117.05 7.869 13.545)scale(2.23819 1.04512)" gradientUnits="userSpaceOnUse"><stop class="jsa0_reur"/><stop offset="1" class="j1xr6ccfb"/></radialGradient><radialGradient id="i23ntQe" cx="0" cy="0" r="1" gradientTransform="rotate(135.74 4.223 11.079)scale(3.58199 4.84976)" gradientUnits="userSpaceOnUse"><stop class="qunsngokg"/><stop offset="1" class="zsyglhsdv"/></radialGradient><radialGradient id="i77Ytid" cx="0" cy="0" r="1" gradientTransform="rotate(123.951 4.148 12.705)scale(2.98327 2.1547)" gradientUnits="userSpaceOnUse"><stop class="f7vxzf2re"/><stop offset="1" class="bjz-35bmd"/></radialGradient><radialGradient id="i8Zzivd" cx="0" cy="0" r="1" gradientTransform="matrix(2.70871 0 0 14.0625 6.066 30)" gradientUnits="userSpaceOnUse"><stop class="g21-8bc8z"/><stop offset="1" class="uhp0yeb2h"/></radialGradient><radialGradient id="iE5Ofte" cx="0" cy="0" r="1" gradientTransform="matrix(-2.2813 6.68749 -5.49369 -1.87406 9.223 17.781)" gradientUnits="userSpaceOnUse"><stop class="ghamttb0q"/><stop offset="1" class="z1an05bwi"/></radialGradient><radialGradient id="iE6iQae" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.2187 2.59375 0 9.223 30.438)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="z8optlbcz"/><stop offset="1" class="gmjyv1b7b"/></radialGradient><radialGradient id="iJIw8ya" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.3125 -1.98 0 24.755 21.938)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="cbe6sn2ns"/><stop offset="1" class="gvyr5190s"/></radialGradient><radialGradient id="iwZFu8W" cx="0" cy="0" r="1" gradientTransform="rotate(140.585 9.368 16.757)scale(2.13884 2.10129)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="kieesbm_x"/><stop offset="1" class="w58utkb1j"/></radialGradient><radialGradient id="iP7E3xc" cx="0" cy="0" r="1" gradientTransform="matrix(.78818 -.60013 .3134 .41161 27.001 23.598)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="hmj-ymbzq"/><stop offset="1" class="ekxsm__ep"/></radialGradient><radialGradient id="idlbkMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -12.1153 44.4939 0 15.79 29.983)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="s8-qpgb5g"/><stop offset="1" class="o5bua8boy"/></radialGradient><radialGradient id="iIvEVud" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.875 5.37793 0 22.464 32.545)" gradientUnits="userSpaceOnUse"><stop class="zwo8xvbzg"/><stop offset="1" class="c-tzwtb6q"/></radialGradient><radialGradient id="i6G3R0c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.59908 3.3973 -1.77851 -1.88415 10.553 15.318)" gradientUnits="userSpaceOnUse"><stop class="hfyjss5uq"/><stop offset="1" class="y9jato2vd"/></radialGradient><radialGradient id="iaz5sEW" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.875 -3.15122 0 15.915 16.444)" gradientUnits="userSpaceOnUse"><stop class="kp5c5xx5n"/><stop offset="1" class="a57_dibjf"/></radialGradient><radialGradient id="ibXRrGc" cx="0" cy="0" r="1" gradientTransform="matrix(1.26563 -2.32812 2.70524 1.47064 23.707 20.906)" gradientUnits="userSpaceOnUse"><stop class="tdvgs2sbs"/><stop offset="1" class="tz6f6rbmx"/></radialGradient><radialGradient id="ixaGDYd" cx="0" cy="0" r="1" gradientTransform="rotate(53.424 -5.116 34.839)scale(2.25697 2.46612)" gradientUnits="userSpaceOnUse"><stop class="sf2388bnl"/><stop offset="1" class="ganm9fbbs"/></radialGradient><radialGradient id="i5oGPfb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.364 25.305)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="ioQSTVd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.364 26.6)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iqH81bx" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.364 27.85)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="i4TNoOd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.364 29.2)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="i7WxSHe" cx="0" cy="0" r="1" gradientTransform="rotate(-43.767 24.314 -20.692)scale(1.62195 2.626)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="ifl4R2h" cx="0" cy="0" r="1" gradientTransform="matrix(.61918 .73134 -.23906 .2024 21.553 8.967)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="iL5WIFT" cx="0" cy="0" r="1" gradientTransform="matrix(-.40745 0 0 -.9238 10.417 10.63)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="iLXmoeb" cx="0" cy="0" r="1" gradientTransform="matrix(.66527 -.09951 .15385 1.02855 21.003 10.726)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="iGmD1sc" cx="0" cy="0" r="1" gradientTransform="rotate(155.407 8.29 7.043)scale(7.36936 9.81575)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="i7vi4Bb" cx="0" cy="0" r="1" gradientTransform="rotate(156.406 7.787 7.299)scale(2.45132 1.69842)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="iJ2V6Td" cx="0" cy="0" r="1" gradientTransform="matrix(1.32825 -4.01732 5.12803 1.69549 13.587 16.653)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="i6P3e9c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3237 7.54015 -9.49173 -1.6663 16.869 9.573)" gradientUnits="userSpaceOnUse"><stop offset=".571" class="tprmu492y"/><stop offset="1" class="dn4-9bb2l"/></radialGradient><radialGradient id="iX2sh9d" cx="0" cy="0" r="1" gradientTransform="rotate(168.978 8.272 6.737)scale(7.24885 12.394)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="i2vUIWd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17683 1.45515 0 18.185 9.57)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="idXGvXz" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34224 1.54986 0 13.675 9.336)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="icxMfjc" cx="0" cy="0" r="1" gradientTransform="rotate(105.2 5.867 10.191)scale(3.41944 2.75387)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="i38YHpd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.32427 0 0 -6.59153 21.064 11.091)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="iME4dFd" cx="0" cy="0" r="1" gradientTransform="matrix(1.80308 -1.59788 1.89562 2.13905 11.656 15.857)" gradientUnits="userSpaceOnUse"><stop class="z26rrllgi"/><stop offset="1" class="fs9pa7bci"/></radialGradient><radialGradient id="i15PqVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.45229 -7.10638 0 15.814 7.269)" gradientUnits="userSpaceOnUse"><stop offset=".123" class="nn35f9jys"/><stop offset="1" class="cetybpb2i"/></radialGradient><radialGradient id="iWm6Aie" cx="0" cy="0" r="1" gradientTransform="rotate(-101.645 13.131 -.779)scale(2.25681 .64762)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iq1I2nc" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.23563 16.305 12.154)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iy4s2Xc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 17.942 10.088)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iUmVuje" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.348 .748)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ixyOlwc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.578 10.088)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iI0jKXc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.292 10.308)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i0vaKQd" cx="0" cy="0" r="1" gradientTransform="rotate(-158.919 10.694 2.553)scale(8.7748 8.41903)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="iodgi0b6i"/><stop offset="1" class="xh-hzrtoi"/></radialGradient><radialGradient id="iIvrIye" cx="0" cy="0" r="1" gradientTransform="rotate(139.529 8.817 5.504)scale(8.95518 9.18704)" gradientUnits="userSpaceOnUse"><stop class="pvjcf1omm"/><stop offset=".682" class="o2y-twbma"/><stop offset="1" class="x2409oaqt"/></radialGradient><filter id="iLikite" width="15.95" height="13.5" x="7.71" y="4.309" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.152941 0 0 0 0 0.101961 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1951"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.337255 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1951" result="effect2_innerShadow_4002_1951"/></filter><filter id="iuuBJuc" width="9.938" height="8.021" x="10.364" y="15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1951" stdDeviation=".5"/></filter><filter id="iNB2Qwd" width="5.33" height="3.88" x="9.765" y="23.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.384314 0 0 0 0 0.823529 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1951"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_1951" result="shape"/></filter><filter id="igowGfe" width="4.03" height="2.58" x="10.415" y="24.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.807843 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1951"/></filter><filter id="iZvwGDo" width="4.352" height="2.789" x="13.564" y="15.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.427451 0 0 0 0 0.262745 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1951"/></filter><filter id="izqCDIe" width="5.15" height="12.15" x="22.255" y="16.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.384314 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1951"/></filter><filter id="iiHHwed" width="2.08" height="4.962" x="24.105" y="21.001" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1951" stdDeviation=".325"/></filter><filter id="iuPY6Ce" width="4.468" height="5.556" x="22.927" y="24.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.211765 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1951"/></filter><filter id="iASPQhb" width="2.097" height=".3" x="23.353" y="25.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1951" stdDeviation=".05"/></filter><filter id="isj8Tic" width="2.097" height=".3" x="23.275" y="27.147" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1951" stdDeviation=".05"/></filter><filter id="ixVM0Sd" width="2.097" height=".3" x="23.353" y="28.451" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1951" stdDeviation=".05"/></filter><filter id="iisOCve" width="1.514" height="3.441" x="20.682" y="8.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1951"/></filter><filter id="iZFu5Kc" width="1.671" height="3.2" x="9.324" y="9.03" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1951"/></filter><filter id="i0YquFd" width="1.329" height="2.379" x="9.728" y="9.441" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1951" stdDeviation=".125"/></filter><filter id="iDfhDVe" width="1.947" height="2.903" x="20.222" y="9.175" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1951" stdDeviation=".25"/></filter><filter id="iQOe1ve" width="10.5" height="11.373" x="10.564" y="5.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1951"/></filter><filter id="iLxprYb" width="2.877" height="3.9" x="14.114" y="9.564" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1951" stdDeviation=".25"/></filter><filter id="iP3rTfc" width="2.377" height="3.4" x="14.572" y="9.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1951" stdDeviation=".125"/></filter><filter id="i08XxqZ" width="3.518" height="1.373" x="14.001" y="13.289" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1951" stdDeviation=".05"/></filter><filter id="iUdTbFT" width="2.439" height="1.19" x="17.349" y="7.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1951"/></filter><filter id="iqEHSnY" width="2.439" height="1.176" x="12.093" y="7.477" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1951"/></filter><filter id="ioRnrjd" width="2.655" height="1.379" x="11.887" y="7.458" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1951" stdDeviation=".2"/></filter><filter id="iuwGEGe" width="2.655" height="1.387" x="17.166" y="7.414" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1951" stdDeviation=".2"/></filter><filter id="iOvm6hc" width="2.611" height="1.227" x="17.05" y="9.121" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.101961 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1951"/></filter><filter id="iDeab5K" width="2.611" height="1.227" x="11.861" y="9.121" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.101961 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1951"/></filter><filter id="iIWiCwz" width=".787" height=".696" x="17.208" y="9.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1951" stdDeviation=".05"/></filter><filter id="iFRBdEc" width=".891" height=".913" x="18.048" y="9.723" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1951" stdDeviation=".1"/></filter><filter id="iXD14Bc" width=".986" height="1.04" x="13.605" y="9.66" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1951" stdDeviation=".1"/></filter><filter id="iD2U1Je" width=".913" height=".705" x="12.85" y="9.64" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1951" stdDeviation=".05"/></filter><filter id="iIbXpLQ" width="11.17" height="3.114" x="10.155" y="5.342" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.560784 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1951"/></filter><filter id="iHO1a4c" width="11.355" height="5.77" x="10.062" y="1.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.12549 0 0 0 0 0.431373 0 0 0 0 0.721569 0 0 0 0.5 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1951"/></filter><linearGradient id="i9TFyxF" x1="22.414" x2="14.931" y1="6.466" y2="18.664" gradientUnits="userSpaceOnUse"><stop class="cd2w3_-kd"/><stop offset=".862" class="cl0gv76ti"/></linearGradient><linearGradient id="igtPXve" x1="12.035" x2="21.723" y1="23.156" y2="18.344" gradientUnits="userSpaceOnUse"><stop class="hzctbo64o"/><stop offset="1" class="ncpoyrbpw"/></linearGradient><linearGradient id="i4RHwye" x1="14.633" x2="13.974" y1="19.957" y2="19.239" gradientUnits="userSpaceOnUse"><stop class="ptx8-dg4d"/><stop offset="1" class="m1cydckkt"/></linearGradient><linearGradient id="i86fP2c" x1="11.699" x2="12.504" y1="18.875" y2="18.875" gradientUnits="userSpaceOnUse"><stop class="a969r93lb"/><stop offset="1" class="zsyglhsdv"/></linearGradient><linearGradient id="i2nIhZb" x1="19.937" x2="18.312" y1="19.527" y2="19.527" gradientUnits="userSpaceOnUse"><stop class="z9cu3vbra"/><stop offset="1" class="ul2cu2h0c"/></linearGradient><linearGradient id="ivP9Jjb" x1="17" x2="17.937" y1="20.105" y2="19.027" gradientUnits="userSpaceOnUse"><stop class="h5mxx_cud"/><stop offset="1" class="c5x-f3bwv"/></linearGradient><linearGradient id="i1B5pTu" x1="23.473" x2="23.473" y1="29.782" y2="23.532" gradientUnits="userSpaceOnUse"><stop class="unsdl8pjp"/><stop offset="1" class="r0l64jbzx"/></linearGradient><linearGradient id="iXRw9pd" x1="8.441" x2="9.059" y1="29.973" y2="29.953" gradientUnits="userSpaceOnUse"><stop offset=".203" class="t2xb9pb8a"/><stop offset="1" class="oh9185bnq"/></linearGradient><linearGradient id="iz9xh1o" x1="23.232" x2="22.627" y1="30" y2="30" gradientUnits="userSpaceOnUse"><stop class="hwgxlbc5v"/><stop offset="1" class="z4q6dwvkw"/></linearGradient><linearGradient id="i1uMIud" x1="12.43" x2="12.43" y1="23.95" y2="27.53" gradientUnits="userSpaceOnUse"><stop class="qcmtsylcx"/><stop offset="1" class="o7pw9mb8f"/></linearGradient><linearGradient id="iPXFJHe" x1="12.43" x2="12.43" y1="24.45" y2="27.03" gradientUnits="userSpaceOnUse"><stop class="d337rwvie"/><stop offset=".752" class="n5xzb8_yo"/></linearGradient><linearGradient id="iU8Jczd" x1="25.191" x2="23.16" y1="21.906" y2="21.906" gradientUnits="userSpaceOnUse"><stop class="oj6on8fvq"/><stop offset="1" class="fxowcsv6r"/></linearGradient><linearGradient id="iBVZlGV" x1="26.955" x2="22.927" y1="28.063" y2="28.063" gradientUnits="userSpaceOnUse"><stop offset=".146" class="pxu01k21v"/><stop offset=".861" class="fusa66-jk"/></linearGradient><linearGradient id="icCtmNd" x1="23.503" x2="25.212" y1="26.07" y2="26.07" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="i8rhfrd" x1="23.425" x2="25.134" y1="27.375" y2="27.375" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="ic9kcre" x1="23.503" x2="25.212" y1="28.68" y2="28.68" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="ilj4o6d" x1="9.348" x2="9.934" y1="10.716" y2="10.716" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="ihzoVAb" x1="14.822" x2="15.76" y1="12.004" y2="12.004" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="iTiggVb" x1="15.76" x2="15.76" y1="12.868" y2="12.208" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="ilnxXFc" x1="15.76" x2="15.76" y1="9.628" y2="11.319" gradientUnits="userSpaceOnUse"><stop class="d27f-vbbu"/><stop offset="1" class="y-pal718y"/></linearGradient><linearGradient id="iwypcUq" x1="14.828" x2="15.093" y1="14.274" y2="13.774" gradientUnits="userSpaceOnUse"><stop class="nvlbbobzu"/><stop offset="1" class="ixkv46_0d"/></linearGradient><linearGradient id="i9W7DLc" x1="18.72" x2="18.406" y1="10.142" y2="10.335" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i0hsthe" x1="14.322" x2="14.008" y1="10.142" y2="10.335" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-mechanic-medium-dark" /></template>
<style>
.a57_dibjf {
  stop-color: var(--svg-color--88605d, #88605D);
}

.a969r93lb {
  stop-color: var(--svg-color--d3c8dc, #D3C8DC);
}

.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.ar7lpj8pp {
  stop-color: var(--svg-color--7a4b42, #7A4B42);
  stop-opacity: 0;
}

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.be93etbkd {
  d: path("M20.722 11.579q.058-.953.11-1.904a.956.956 0 0 1-.11 1.904");
}

.birn6lbkk {
  fill: var(--svg-color--352827, #352827);
  d: path("M12.35 8.057a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.551a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.092.06l-.002.002a.277.277 0 0 1-.34-.439z");
}

.biuac8r4x {
  d: path("M22.775 18.043V30h2.979l.981-3.5c0-3.401-1.54-6.44-3.96-8.457");
}

.bjz-35bmd {
  stop-color: var(--svg-color--d6cbdf, #D6CBDF);
  stop-opacity: 0;
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.c-tzwtb6q {
  stop-color: var(--svg-color--345cbf, #345CBF);
  stop-opacity: 0;
}

.c230v9qll {
  d: path("M20.682 12.23q.101-1.597.184-3.192a1.61 1.61 0 0 1-.184 3.191");
}

.c5x-f3bwv {
  stop-color: var(--svg-color--ffe4f7, #FFE4F7);
  stop-opacity: 0;
}

.cbe6sn2ns {
  stop-color: var(--svg-color--d2c9de, #D2C9DE);
}

.cd2w3_-kd {
  stop-color: var(--svg-color--2f1d25, #2F1D25);
}

.cetybpb2i {
  stop-color: var(--svg-color--57324a, #57324A);
  stop-opacity: 0;
}

.cgh3_wbed {
  d: path("m15.378 10.174l-.532 1.838c-.108.379.152.757.521.757h.786c.37 0 .63-.384.521-.757l-.532-1.838c-.113-.407-.645-.407-.764 0");
}

.cjq4b16bn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.503 25.992H25.3");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cl0gv76ti {
  stop-color: var(--svg-color--1a0e1c, #1A0E1C);
}

.crj44uotj {
  stop-color: var(--svg-color--996b5e, #996B5E);
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.d27f-vbbu {
  stop-color: var(--svg-color--704951, #704951);
}

.d2s-wtuyq {
  d: path("M15.717 18.637c-1.523-.508-1.95-1.488-2.153-2.59h4.352c-.367 2.017-1.68 2.488-2.199 2.59");
}

.d337rwvie {
  stop-color: var(--svg-color--e0ccf0, #E0CCF0);
}

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
  stop-opacity: 0;
}

.dc6jrkblm {
  stop-color: var(--svg-color--160c19, #160C19);
}

.dcb4tlblp {
  stop-color: var(--svg-color--986e66, #986E66);
  stop-opacity: 0;
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.dmf0acl5m {
  stop-color: var(--svg-color--565252, #565252);
  stop-opacity: 0;
}

.dn4-9bb2l {
  stop-color: var(--svg-color--854573, #854573);
}

.dpf88hj0u {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.879 9.8c.063.085-.07.188-.22.301c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.359c.15-.113.325-.136.389-.05");
}

.dvr2s59yl {
  d: path("M26.245 23.1c.55 0 1 .45 1 1v2.29h-2V24.1c0-.55.45-1 1-1");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.ekxsm__ep {
  stop-color: var(--svg-color--93776e, #93776E);
  stop-opacity: 0;
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.eqaszhbhb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.503 28.602H25.3");
}

.f7vxzf2re {
  stop-color: var(--svg-color--8e7f98, #8E7F98);
}

.fs9pa7bci {
  stop-color: var(--svg-color--6e494b, #6E494B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fusa66-jk {
  stop-color: var(--svg-color--704b4b, #704B4B);
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
}

.fxowcsv6r {
  stop-color: var(--svg-color--847596, #847596);
}

.g21-8bc8z {
  stop-color: var(--svg-color--c7acea, #C7ACEA);
}

.ganm9fbbs {
  stop-color: var(--svg-color--bab5c6, #BAB5C6);
  stop-opacity: 0;
}

.gcfqr7bfg {
  stop-color: var(--svg-color--714350, #714350);
  stop-opacity: 0;
}

.ghamttb0q {
  stop-color: var(--svg-color--99959a, #99959A);
}

.gmjyv1b7b {
  stop-color: var(--svg-color--aba1bb, #ABA1BB);
  stop-opacity: 0;
}

.gvyr5190s {
  stop-color: var(--svg-color--d2c9de, #D2C9DE);
  stop-opacity: 0;
}

.gwjnm0b5l {
  d: path("M10.706 9.03a1.61 1.61 0 0 0 .139 3.2a78 78 0 0 1-.139-3.2");
}

.h-4ghpb7u {
  stop-color: var(--svg-color--150a0d, #150A0D);
  stop-opacity: 0;
}

.h5mxx_cud {
  stop-color: var(--svg-color--dbbaf9, #DBBAF9);
}

.hfyjss5uq {
  stop-color: var(--svg-color--3f8aad, #3F8AAD);
}

.hmj-ymbzq {
  stop-color: var(--svg-color--93776e, #93776E);
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.hwgxlbc5v {
  stop-color: var(--svg-color--2b5fb7, #2B5FB7);
}

.hx6yvt1fd {
  fill: var(--svg-color--000, #000);
  d: path("M17.433 10.503c0-.284.227-.51.511-.51a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.236");
}

.hzctbo64o {
  stop-color: var(--svg-color--d6c6ed, #D6C6ED);
}

.i4syfobqj {
  fill: var(--svg-color--302d32, #302D32);
  d: path("M18.269 9.274c-.766.039-1.1.422-1.22.613l2.013.461c.14.008.484-.086.562-.246a.31.31 0 0 0-.05-.363c-.176-.203-.675-.497-1.305-.465");
}

.iodgi0b6i {
  stop-color: var(--svg-color--47c4ff, #47C4FF);
}

.ioxecjbjq {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m15.274 10.37l-.635 1.838c-.108.378.152.756.52.756h.787c.369 0 .629-.383.52-.756l-.53-1.838c-.115-.407-.543-.407-.662 0");
}

.ixkv46_0d {
  stop-color: var(--svg-color--845c60, #845C60);
  stop-opacity: 0;
}

.j1xr6ccfb {
  stop-color: var(--svg-color--3e3c3d, #3E3C3D);
  stop-opacity: 0;
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.jsa0_reur {
  stop-color: var(--svg-color--3e3c3d, #3E3C3D);
}

.jse2phbtg {
  fill: var(--svg-color--f4e6ff, #F4E6FF);
  d: path("M19.674 16.233v4.908c0 .433-.418.668-.813.379L15.74 18.8a.1.1 0 0 1-.034-.076v-1.322l1.7-1.776q1.182.185 2.269.607");
}

.kieesbm_x {
  stop-color: var(--svg-color--815f52, #815F52);
}

.kj5kxbbbl {
  d: path("M17.944 9.61a.892.892 0 0 1 .86 1.129H17.08a.896.896 0 0 1 .864-1.128");
}

.kp5c5xx5n {
  stop-color: var(--svg-color--834e60, #834E60);
}

.kr61v_sfd {
  d: path("M19.85 7.306h-3.314c-1.314 0-2.508-.594-3.245-1.656a.272.272 0 0 0-.478.048l-.08.195A2.34 2.34 0 0 1 11.5 7.131a.4.4 0 0 1-.11.049c-.248.117-.816.487-.826 1.452l.14 3.235c.119 2.866 2.378 4.786 5.115 4.786s4.996-1.92 5.116-4.786l.13-3.08c-.02-1.354-1.026-1.48-1.215-1.48");
}

.kvfq7h_0m {
  d: path("M8.775 30V17.99a10.98 10.98 0 0 0-4.03 8.51V30z");
}

.l__dw9bpv {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lf8a5e78i {
  stop-color: var(--svg-color--664139, #664139);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.luyfkt2yj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.425 27.297h1.797");
}

.lwc2zdrqr {
  d: path("M13.155 24.45c.71 0 1.29.58 1.29 1.29s-.58 1.29-1.29 1.29h-1.45c-.71 0-1.29-.58-1.29-1.29s.58-1.29 1.29-1.29zm0-.5h-1.45c-.99 0-1.79.8-1.79 1.79s.8 1.79 1.79 1.79h1.45c.99 0 1.79-.8 1.79-1.79s-.8-1.79-1.79-1.79");
}

.m1cydckkt {
  stop-color: var(--svg-color--e0c7fa, #E0C7FA);
  stop-opacity: 0;
}

.m1i1rlbvk {
  d: path("M15.745 15.5c-6.07 0-11 4.92-11 11V30h21.08l.91-3.5c0-6.08-4.92-11-10.99-11");
}

.m3se_ob2r {
  fill: var(--svg-color--eddffd, #EDDFFD);
  d: path("M11.736 16.236v4.905c0 .433.418.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076v-1.322l-1.699-1.775c-.787.123-1.547.329-2.27.61");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mlnj98vrv {
  fill: var(--svg-color--000, #000);
  d: path("M14.087 10.503a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.236");
}

.momee7bch {
  d: path("M13.155 27.03h-1.45c-.71 0-1.29-.58-1.29-1.29s.58-1.29 1.29-1.29h1.45c.71 0 1.29.58 1.29 1.29c0 .72-.57 1.29-1.29 1.29");
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.n5xzb8_yo {
  stop-color: var(--svg-color--e0c6f6, #E0C6F6);
}

.ncpoyrbpw {
  stop-color: var(--svg-color--cdb2d2, #CDB2D2);
}

.nn35f9jys {
  stop-color: var(--svg-color--57324a, #57324A);
}

.nvlbbobzu {
  stop-color: var(--svg-color--845c60, #845C60);
}

.o0jeiob3a {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m15.378 10.174l-.532 1.838c-.108.379.152.757.521.757h.786c.37 0 .63-.384.521-.757l-.532-1.838c-.113-.407-.645-.407-.764 0");
}

.o2y-twbma {
  stop-color: var(--svg-color--2780b8, #2780B8);
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.o5bua8boy {
  stop-color: var(--svg-color--45c0ff, #45C0FF);
}

.o7pw9mb8f {
  stop-color: var(--svg-color--f03a62, #F03A62);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oh9185bnq {
  stop-color: var(--svg-color--2860c0, #2860C0);
  stop-opacity: 0;
}

.oj6on8fvq {
  stop-color: var(--svg-color--847596, #847596);
  stop-opacity: 0;
}

.olqyf7fmb {
  stop-color: var(--svg-color--875e5e, #875E5E);
}

.om0oq7b1v {
  d: path("M19.674 16.233v4.908c0 .433-.418.668-.813.379L15.74 18.8a.1.1 0 0 1-.034-.076v-1.322l1.7-1.776q1.182.185 2.269.607");
}

.opgioqbtx {
  stop-color: var(--svg-color--805c54, #805C54);
  stop-opacity: 0;
}

.osxg47drp {
  stop-color: var(--svg-color--743f5a, #743F5A);
}

.oy6n6fbyn {
  stop-color: var(--svg-color--160c19, #160C19);
  stop-opacity: 0;
}

.p88c31myn {
  stop-color: var(--svg-color--815a5b, #815A5B);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.psv7auxid {
  d: path("M16.795 2c1.44 0 2.82.43 3.73 1.51c.7.83 1.08 2.36.8 4.06c-.6-.57-1.21-.99-1.89-1.31a8.76 8.76 0 0 0-7.39 0c-.68.31-1.29.74-1.89 1.31c-.28-1.71.1-3.23.8-4.06c.91-1.08 2.29-1.51 3.73-1.51z");
}

.ptrn2nbeb {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M15.76 13.785c-.507 0-.984-.12-1.385-.328c-.137-.07-.284.084-.198.209c.335.507.918.846 1.583.846s1.249-.339 1.583-.846c.087-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33Z");
}

.ptx8-dg4d {
  stop-color: var(--svg-color--e0c7fa, #E0C7FA);
}

.pv8cx5b7o {
  d: path("M22.927 25.326a.73.73 0 0 1 .727-.732h2.391a1.2 1.2 0 0 1 1.2 1.2V29a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.pvjcf1omm {
  stop-color: var(--svg-color--4fbfff, #4FBFFF);
}

.pxu01k21v {
  stop-color: var(--svg-color--976c5f, #976C5F);
}

.q5e3l-wal {
  fill: var(--svg-color--352827, #352827);
  d: path("M19.493 8.173a1.85 1.85 0 0 0-.687-.411c-.305-.096-.686-.121-1.213-.057a.277.277 0 1 0 .067.55c.482-.058.776-.028.979.036c.198.062.332.164.49.3a.277.277 0 1 0 .364-.418");
}

.qb053jydf {
  cx: 13.307px;
  cy: 9.992px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.qcmtsylcx {
  stop-color: var(--svg-color--e73c75, #E73C75);
}

.qea3jle_i {
  d: path("M17.879 9.8c.063.085-.07.188-.22.301c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.359c.15-.113.325-.136.389-.05");
}

.qunsngokg {
  stop-color: var(--svg-color--7c6987, #7C6987);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qyd2qob8y {
  cx: 13.307px;
  cy: 9.992px;
  rx: 0.39px;
  ry: 0.197px;
}

.r0i0_6b9f {
  stop-color: var(--svg-color--947068, #947068);
}

.r0l64jbzx {
  stop-color: var(--svg-color--b7a9c2, #B7A9C2);
}

.r2qtbmb9n {
  d: path("M18.739 10.386a.84.84 0 0 0-.231-.463l-.26.285l.117.229z");
}

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.s2-xryl0i {
  d: path("M12.045 6.26c-.68.31-1.29.74-1.89 1.31l.41.51c.31.38.85.49 1.28.25c.76-.42 2.11-.99 3.9-.99s3.14.57 3.9.99a1 1 0 0 0 1.27-.25l.41-.51c-.6-.57-1.21-.99-1.89-1.31a8.76 8.76 0 0 0-7.39 0");
}

.s8-qpgb5g {
  stop-color: var(--svg-color--3b71d9, #3B71D9);
}

.sf2388bnl {
  stop-color: var(--svg-color--bab5c6, #BAB5C6);
}

.sp6_o9bxd {
  d: path("M20.735 16.696v5.877c0 .23-.18.41-.41.41h-9.07c-.23 0-.41-.18-.41-.41v-5.92q-.21.102-.413.213a11 11 0 0 0-1.657 1.127V30h14.03V18.068a11 11 0 0 0-2.07-1.372");
}

.t2xb9pb8a {
  stop-color: var(--svg-color--2860c0, #2860C0);
}

.t9k87pm2r {
  stop-color: var(--svg-color--875555, #875555);
}

.tdvgs2sbs {
  stop-color: var(--svg-color--9872bb, #9872BB);
}

.tf7b5e2qz {
  d: path("M13.576 9.61a.892.892 0 0 0-.86 1.129h1.724a1 1 0 0 0 .033-.236a.9.9 0 0 0-.897-.892");
}

.tprmu492y {
  stop-color: var(--svg-color--7c4962, #7C4962);
  stop-opacity: 0;
}

.tru2658_b {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.387 8.337a2.46 2.46 0 0 1 1.655-.352");
}

.tvy0a_bwh {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M10.723 9.69a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.tz6f6rbmx {
  stop-color: var(--svg-color--9872bb, #9872BB);
  stop-opacity: 0;
}

.u1e8ikbzb {
  d: path("M25.93 17.043c-.191-.1-.432.03-.432.25v1.551c0 .42-.341.77-.763.76a.746.746 0 0 1-.733-.75v-1.561c0-.22-.24-.36-.432-.26a2.48 2.48 0 0 0-1.315 2.171c-.01.97.552 1.821 1.366 2.241c.09.05.15.15.15.25V28a1.005 1.005 0 0 0 2.008.001v-6.324c0-.1.06-.2.15-.25a2.49 2.49 0 0 0 1.326-2.202a2.52 2.52 0 0 0-1.325-2.181");
}

.uhp0yeb2h {
  stop-color: var(--svg-color--c6b9db, #C6B9DB);
}

.uj7hgsb3u {
  stop-color: var(--svg-color--815a5b, #815A5B);
}

.ul2cu2h0c {
  stop-color: var(--svg-color--f0e1ff, #F0E1FF);
  stop-opacity: 0;
}

.unsdl8pjp {
  stop-color: var(--svg-color--9b80b4, #9B80B4);
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.vcv8c754j {
  fill: var(--svg-color--9e88ad, #9E88AD);
  d: path("M25.93 17.043c-.191-.1-.432.03-.432.25v1.551c0 .42-.341.77-.763.76a.746.746 0 0 1-.733-.75v-1.561c0-.22-.24-.36-.432-.26a2.48 2.48 0 0 0-1.315 2.171c-.01.97.552 1.821 1.366 2.241c.09.05.15.15.15.25V28a1.005 1.005 0 0 0 2.008.001v-6.324c0-.1.06-.2.15-.25a2.49 2.49 0 0 0 1.326-2.202a2.52 2.52 0 0 0-1.325-2.181");
}

.vy91i9bft {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.151 9.34c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.w4n-ob-5e {
  d: path("M14.391 10.398c0-.288-.234-.48-.297-.538l-.289.279l.178.36z");
}

.w58utkb1j {
  stop-color: var(--svg-color--643838, #643838);
}

.w9txrw6kc {
  stop-color: var(--svg-color--150a0d, #150A0D);
}

.wg3eepbwp {
  stop-color: var(--svg-color--805c54, #805C54);
}

.wn0fm3b_g {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.37 9.339c-.654 0-1.206.45-1.356 1.059c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.37-1.128");
}

.wqiol886i {
  fill: var(--svg-color--302d32, #302D32);
  d: path("M13.254 9.274c.765.039 1.099.422 1.219.613l-2.012.461c-.14.008-.485-.086-.563-.246a.31.31 0 0 1 .051-.363c.176-.203.674-.497 1.305-.465");
}

.wrh2b4bbx {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
}

.x_ik4kbfh {
  stop-color: var(--svg-color--714350, #714350);
}

.x2409oaqt {
  stop-color: var(--svg-color--3a69a2, #3A69A2);
}

.x79uj10ff {
  fill: var(--svg-color--88014f, #88014F);
  d: path("M15.76 13.785c-.507 0-.984-.12-1.385-.328c-.137-.07-.284.084-.198.209c.335.507.918.846 1.583.846s1.249-.339 1.583-.846c.087-.13-.06-.279-.198-.21a3 3 0 0 1-1.385.33");
}

.xh-hzrtoi {
  stop-color: var(--svg-color--2f83be, #2F83BE);
}

.xk18tyb3e {
  fill: var(--svg-color--caadc8, #CAADC8);
  d: path("M19.301 21.515v-4.908A11 11 0 0 0 17.033 16l-1.7 1.776l-1.7-1.775c-.787.123-1.546.329-2.27.609v4.905c0 .433.419.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076a.1.1 0 0 0 .035.076l3.122 2.72c.394.289.812.054.812-.38");
}

.xvpsbsbam {
  d: path("M10.723 9.69a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.y-pal718y {
  stop-color: var(--svg-color--704951, #704951);
  stop-opacity: 0;
}

.y9jato2vd {
  stop-color: var(--svg-color--3f8aad, #3F8AAD);
  stop-opacity: 0;
}

.yamoh3dov {
  stop-color: var(--svg-color--764e4c, #764E4C);
}

.yb7xsubhw {
  d: path("M23.51 10.724c0-1.721-2.299-2.453-2.299-3.474l-.14-.68c0-.92.252-1.39-.103-2.01H10.65c-.306.62-.394 1.783-.394 2.704v.01c0 1.047-2.247 1.351-2.247 3.45c0 .54.118 1.04.335 1.501c.069.15.069.33 0 .48c-.217.45-.335.951-.335 1.482c0 1.86 1.488 3.372 3.32 3.372h8.86c1.832 0 3.32-1.511 3.32-3.373c0-.53-.118-1.03-.335-1.48a.58.58 0 0 1 0-.481c.217-.46.335-.97.335-1.501");
}

.ycrcotb4u {
  stop-color: var(--svg-color--986f60, #986F60);
  stop-opacity: 0;
}

.yd_laccri {
  stop-color: var(--svg-color--565252, #565252);
}

.yygq1svpn {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M20.722 11.579q.058-.953.11-1.904a.956.956 0 0 1-.11 1.904");
}

.z1an05bwi {
  stop-color: var(--svg-color--99959a, #99959A);
  stop-opacity: 0;
}

.z26rrllgi {
  stop-color: var(--svg-color--6e494b, #6E494B);
}

.z4q6dwvkw {
  stop-color: var(--svg-color--2b5fb7, #2B5FB7);
  stop-opacity: 0;
}

.z5g21op2e {
  fill: var(--svg-color--b3a4c6, #B3A4C6);
  d: path("M24.755 21.651h.78v3.662h-.78z");
}

.z7l2_l5ut {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M19.321 8.3c-.282-.273-.898-.469-1.655-.351");
}

.z8optlbcz {
  stop-color: var(--svg-color--9680b0, #9680B0);
}

.z9cu3vbra {
  stop-color: var(--svg-color--fff7ff, #FFF7FF);
}

.zoq8fuaif {
  stop-color: var(--svg-color--986f60, #986F60);
}

.zqss5obsp {
  d: path("M11.736 16.236v4.905c0 .433.418.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076v-1.322l-1.699-1.775c-.787.123-1.547.329-2.27.61");
}

.zsyglhsdv {
  stop-color: var(--svg-color--eee0fe, #EEE0FE);
  stop-opacity: 0;
}

.zwo8xvbzg {
  stop-color: var(--svg-color--345cbf, #345CBF);
}

</style>
