<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iCT71jW)" clip-rule="evenodd" class="lawgp1bzz"/><path fill="url(#i1m5HBd)" clip-rule="evenodd" class="lawgp1bzz"/><g filter="url(#i1gNd2d)"><path stroke="url(#iWHTeKO)" class="pl-e-cm4d"/></g><path fill="url(#isPUtLb)" clip-rule="evenodd" class="c8iu-6btl"/><path fill="url(#i9xm2ac)" clip-rule="evenodd" class="c8iu-6btl"/><g filter="url(#idNTBrd)"><path stroke="url(#i0Hsmgb)" class="tjlaau_ls"/></g><path fill="url(#iI7Fm3c)" clip-rule="evenodd" class="m_o7n74cj"/><path fill="url(#iqYtR6D)" clip-rule="evenodd" class="m_o7n74cj"/><g filter="url(#iVBS24b)"><path stroke="url(#i2umZac)" class="mu9k5d6_d"/></g><path fill="url(#ihj2NQb)" clip-rule="evenodd" class="gp72b5b8k"/><path fill="url(#iZqUNrb)" clip-rule="evenodd" class="gp72b5b8k"/><path class="mwarx4bjn"/><path fill="url(#iGL0SHe)" class="f99ud5nzx"/><path fill="url(#iMO17Pe)" class="f99ud5nzx"/><path fill="url(#iQLBTed)" class="f99ud5nzx"/><path fill="url(#iI360qb)" class="f99ud5nzx"/><g filter="url(#ispavfe)"><path class="rbdc6haoq"/><path fill="url(#iJm1XQd)" class="wtt6wibxb"/><path fill="url(#ia7Skqe)" class="wtt6wibxb"/></g><path fill="url(#iBWmSlc)" clip-rule="evenodd" class="r20vy5b-j"/><path fill="url(#iexgs9c)" clip-rule="evenodd" class="r20vy5b-j"/><path fill="url(#iVGZWlQ)" clip-rule="evenodd" class="r20vy5b-j"/><path fill="url(#i2gBF4c)" clip-rule="evenodd" class="r20vy5b-j"/><path fill="url(#ioJU3pc)" clip-rule="evenodd" class="g2giumbme"/><path fill="url(#izTaFpK)" clip-rule="evenodd" class="g2giumbme"/><path fill="url(#izM7zvd)" clip-rule="evenodd" class="g2giumbme"/><path fill="url(#isfz4Md)" clip-rule="evenodd" class="g2giumbme"/><path fill="url(#izpiIsd)" clip-rule="evenodd" class="ycmmgabqw"/><path fill="url(#iZbRevc)" clip-rule="evenodd" class="ycmmgabqw"/><path fill="url(#ilPsu7b)" clip-rule="evenodd" class="ycmmgabqw"/><path fill="url(#iWAqdlb)" clip-rule="evenodd" class="ycmmgabqw"/><path fill="url(#icJlJVd)" clip-rule="evenodd" class="ql45_sqyc"/><path fill="url(#ivBijyb)" clip-rule="evenodd" class="ql45_sqyc"/><path fill="url(#iHA9WXb)" clip-rule="evenodd" class="ql45_sqyc"/><path fill="url(#iuDdMVU)" clip-rule="evenodd" class="ql45_sqyc"/><path fill="url(#iy9NlMG)" class="yc61kdroy"/><path fill="url(#ifs5DAd)" class="tlqalkb7x"/><g filter="url(#iIPGHFb)"><path fill="url(#iZNcJjb)" class="i4u5xtbba"/><path fill="url(#iLaKLMb)" class="i4u5xtbba"/><path fill="url(#iYB5Y8d)" class="i4u5xtbba"/><path fill="url(#iwnY7lc)" class="i4u5xtbba"/><path fill="url(#idvEQXb)" class="i4u5xtbba"/><path fill="url(#iop3jKg)" class="i4u5xtbba"/></g><path fill="url(#irfkRsc)" class="e2xjecc1w"/><path fill="url(#imMqyge)" class="ad0rjgbuv"/><path fill="url(#i0sIMuc)" class="lkhmbxpmm"/><g filter="url(#ifdiOKd)"><path fill="url(#iPdEQCH)" class="nc25adc0b"/></g><path fill="url(#i8X1Hwd)" class="nc25adc0b"/><path fill="url(#iR9Qinb)" class="nc25adc0b"/><path fill="url(#ibvrqnB)" class="nc25adc0b"/><path fill="url(#iRO3Axb)" class="nc25adc0b"/><path fill="url(#ihZX1kd)" class="nc25adc0b"/><path fill="url(#ilFyVCc)" class="nc25adc0b"/><path fill="url(#i1bN1Dc)" class="nc25adc0b"/><g filter="url(#i87ppMt)"><path class="cwsltxb-v"/></g><g filter="url(#iWYh8xd)"><path fill="url(#iaYqzGc)" class="rsu15obyt"/><path fill="url(#iVq7SrL)" class="rsu15obyt"/><path fill="url(#ibViRwe)" class="rsu15obyt"/><path fill="url(#irGKpIe)" class="rsu15obyt"/></g><g filter="url(#iFdhJTb)"><path class="fxzrd2b9f"/><path fill="url(#izPyIZb)" class="rsu15obyt"/><path fill="url(#iiFxjWZ)" class="rsu15obyt"/><path fill="url(#iEVaYpd)" class="rsu15obyt"/><path fill="url(#iNxKo6b)" class="rsu15obyt"/><path fill="url(#i6n9Sod)" class="rsu15obyt"/></g><g filter="url(#iJ969qx)"><path fill="url(#i9HSjnb)" class="t3uxa4qxo"/><path fill="url(#iWyvnge)" class="t3uxa4qxo"/><path fill="url(#iOZ8v8b)" class="t3uxa4qxo"/><path fill="url(#i35dwRB)" class="t3uxa4qxo"/><path fill="url(#igO1Fud)" class="t3uxa4qxo"/></g><g filter="url(#iB4dLQd)"><path class="tcu5qdrym"/></g><g filter="url(#iUfMwNl)"><path class="zmqd8sbwf"/></g><g filter="url(#iGisAxd)"><path class="p4yp4sodz"/><path fill="url(#iVp66rb)" class="f5j3gmo1k"/><path fill="url(#i7SJCge)" class="f5j3gmo1k"/></g><g filter="url(#iHLxKAb)"><path class="otp2k4yuq"/><path fill="url(#id2Kk4C)" class="rj7ll6b2x"/></g><path class="ciyxn3-wq"/><path fill="url(#ibdFFqq)" class="yjyvunbkc"/><path class="tcv5-6bnf"/><g filter="url(#igCCzuc)"><path class="o_1ircb0e"/><path fill="url(#iV15nac)" class="r-5qfsbcc"/></g><g filter="url(#iKmmd2d)"><path fill="url(#igs45Zc)" class="tnb12be6j"/></g><path class="l-b5apb1u"/><path fill="url(#iWg95Bb)" class="fftjp_1ik"/><path class="r_61u0beb"/><g filter="url(#iUZ4Yie)"><path fill="url(#ix3GCWc)" class="yvaupwppj"/></g><g filter="url(#iCDwfNA)"><ellipse transform="rotate(-32.532 13.25 12.839)" class="lubjwvb3q"/><ellipse fill="url(#iqbAsye)" transform="rotate(-32.532 13.25 12.839)" class="nj_gpxbaf"/></g><path fill="url(#iyXjJyd)" class="bcx0ztbqy"/><path fill="url(#ibEfkzB)" class="bcx0ztbqy"/><path fill="url(#iY3BQDe)" class="bcx0ztbqy"/><path fill="url(#irIhODx)" class="bcx0ztbqy"/><path fill="url(#iGAfIfe)" class="s7s03-bva"/><path fill="url(#i8xe73b)" class="s7s03-bva"/><g filter="url(#iCTtzMb)"><path fill="url(#iNcVIcx)" class="fxct8lf8b"/></g><g filter="url(#iHx8PMe)"><path fill="url(#iyqmeud)" class="df3h-rb9k"/></g><g filter="url(#i7Cmatb)"><path class="qtv5znvtr"/></g><g filter="url(#iuzLF5c)"><path class="qtx4-5fdn"/></g><g filter="url(#izt9WYc)"><path stroke="url(#ijbkdBb)" class="pgps4wohd"/></g><g filter="url(#iXrgvme)"><ellipse stroke="url(#iVFEUgd)" class="vkkig2qdu"/></g><ellipse class="l9egxq44p"/><g filter="url(#irUnJlb)"><path stroke="url(#iz6v8jd)" class="gscvhsb0h"/></g><g filter="url(#ignSJAe)"><path class="h7o6cfbua"/></g><defs><radialGradient id="i1m5HBd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6217 1.72506 -3.88088 -1.39866 4.928 13.162)" gradientUnits="userSpaceOnUse"><stop offset=".399" class="c8j_43f8m"/><stop offset=".85" class="c6i37ubuj"/></radialGradient><radialGradient id="i9xm2ac" cx="0" cy="0" r="1" gradientTransform="rotate(106.399 -3.244 8.172)scale(1.96628 3.75623)" gradientUnits="userSpaceOnUse"><stop offset=".399" class="c8j_43f8m"/><stop offset=".85" class="c6i37ubuj"/></radialGradient><radialGradient id="iqYtR6D" cx="0" cy="0" r="1" gradientTransform="rotate(110.767 -3.033 8.587)scale(1.80306 4.21624)" gradientUnits="userSpaceOnUse"><stop offset=".399" class="c8j_43f8m"/><stop offset=".85" class="c6i37ubuj"/></radialGradient><radialGradient id="iZqUNrb" cx="0" cy="0" r="1" gradientTransform="rotate(113.326 -2.933 9.073)scale(1.61789 4.14912)" gradientUnits="userSpaceOnUse"><stop offset=".399" class="c8j_43f8m"/><stop offset=".85" class="c6i37ubuj"/></radialGradient><radialGradient id="iMO17Pe" cx="0" cy="0" r="1" gradientTransform="matrix(-.52138 .86916 -1.0215 -.61276 6.787 11.745)" gradientUnits="userSpaceOnUse"><stop class="d154ezdcq"/><stop offset="1" class="bpksruhej"/></radialGradient><radialGradient id="iQLBTed" cx="0" cy="0" r="1" gradientTransform="matrix(-2.70312 0 0 -.65716 6.644 16.901)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="jg3xmccpx"/><stop offset="1" class="iw0p3zb-d"/></radialGradient><radialGradient id="iI360qb" cx="0" cy="0" r="1" gradientTransform="rotate(34.711 -20.228 14.86)scale(2.38638 3.8706)" gradientUnits="userSpaceOnUse"><stop class="ma9i0_bmw"/><stop offset="1" class="c1kbbgt7z"/></radialGradient><radialGradient id="iJm1XQd" cx="0" cy="0" r="1" gradientTransform="matrix(.19531 -1.22657 .626 .09968 25.862 13.71)" gradientUnits="userSpaceOnUse"><stop class="v0kluxbau"/><stop offset="1" class="a62m2bb9r"/></radialGradient><radialGradient id="ia7Skqe" cx="0" cy="0" r="1" gradientTransform="matrix(.60156 -.63281 .3758 .35725 25.87 12.062)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="djjhgqb7v"/><stop offset="1" class="jo2k47b8i"/></radialGradient><radialGradient id="iexgs9c" cx="0" cy="0" r="1" gradientTransform="rotate(54.429 .865 32.11)scale(2.23711 3.89575)" gradientUnits="userSpaceOnUse"><stop offset=".674" class="k3dnepbgq"/><stop offset="1" class="ss9et8bev"/></radialGradient><radialGradient id="iVGZWlQ" cx="0" cy="0" r="1" gradientTransform="matrix(.54588 -.47662 .26438 .3028 28.433 12.436)" gradientUnits="userSpaceOnUse"><stop class="ow3dahbnn"/><stop offset="1" class="hw9415bma"/></radialGradient><radialGradient id="i2gBF4c" cx="0" cy="0" r="1" gradientTransform="matrix(.93522 1.28125 -1.53792 1.12257 26.862 12.61)" gradientUnits="userSpaceOnUse"><stop class="i5-oiwb9h"/><stop offset="1" class="a0v3z_9ye"/></radialGradient><radialGradient id="izTaFpK" cx="0" cy="0" r="1" gradientTransform="rotate(74.107 5.136 24.865)scale(2.45789 3.78855)" gradientUnits="userSpaceOnUse"><stop offset=".674" class="k3dnepbgq"/><stop offset="1" class="ss9et8bev"/></radialGradient><radialGradient id="izM7zvd" cx="0" cy="0" r="1" gradientTransform="matrix(.51556 -.52165 .292 .2886 29.489 12.798)" gradientUnits="userSpaceOnUse"><stop class="ow3dahbnn"/><stop offset="1" class="hw9415bma"/></radialGradient><radialGradient id="isfz4Md" cx="0" cy="0" r="1" gradientTransform="matrix(1.37499 1.70313 -1.31573 1.06223 27.328 13.125)" gradientUnits="userSpaceOnUse"><stop class="i5-oiwb9h"/><stop offset="1" class="a0v3z_9ye"/></radialGradient><radialGradient id="iZbRevc" cx="0" cy="0" r="1" gradientTransform="rotate(70.854 3.87 26.335)scale(2.23451 4.05178)" gradientUnits="userSpaceOnUse"><stop offset=".674" class="k3dnepbgq"/><stop offset="1" class="ss9et8bev"/></radialGradient><radialGradient id="ilPsu7b" cx="0" cy="0" r="1" gradientTransform="matrix(.56135 -.46582 .2563 .30886 29.488 13.758)" gradientUnits="userSpaceOnUse"><stop class="ow3dahbnn"/><stop offset="1" class="hw9415bma"/></radialGradient><radialGradient id="iWAqdlb" cx="0" cy="0" r="1" gradientTransform="rotate(54.253 .364 34.155)scale(1.28989 1.66703)" gradientUnits="userSpaceOnUse"><stop class="i5-oiwb9h"/><stop offset="1" class="a0v3z_9ye"/></radialGradient><radialGradient id="ivBijyb" cx="0" cy="0" r="1" gradientTransform="matrix(.73437 1.86015 -3.71825 1.46794 27.162 14.984)" gradientUnits="userSpaceOnUse"><stop offset=".674" class="k3dnepbgq"/><stop offset="1" class="ss9et8bev"/></radialGradient><radialGradient id="iHA9WXb" cx="0" cy="0" r="1" gradientTransform="rotate(-36.12 37.18 -37.37)scale(.69635 .37124)" gradientUnits="userSpaceOnUse"><stop class="ow3dahbnn"/><stop offset="1" class="hw9415bma"/></radialGradient><radialGradient id="iuDdMVU" cx="0" cy="0" r="1" gradientTransform="matrix(.42188 .76563 -.90043 .49616 27.862 14.687)" gradientUnits="userSpaceOnUse"><stop class="i5-oiwb9h"/><stop offset="1" class="a0v3z_9ye"/></radialGradient><radialGradient id="iy9NlMG" cx="0" cy="0" r="1" gradientTransform="matrix(-2.59375 0 0 -2.7696 26.255 17.234)" gradientUnits="userSpaceOnUse"><stop class="oliv2bcuo"/><stop offset="1" class="k1yfa1pxl"/></radialGradient><radialGradient id="ifs5DAd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.32031 0 6.99 16.82)" gradientUnits="userSpaceOnUse"><stop class="byn2s1bln"/><stop offset="1" class="gno4tuy0h"/></radialGradient><radialGradient id="iZNcJjb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.75 8.9375 0 19.568 29.562)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="finomov8p"/><stop offset="1" class="qfj8esbtd"/></radialGradient><radialGradient id="iLaKLMb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.1875 3.5231 -.87474 -.79141 9.63 20.187)" gradientUnits="userSpaceOnUse"><stop class="xo_dbbcrk"/><stop offset="1" class="fipf36vin"/></radialGradient><radialGradient id="iYB5Y8d" cx="0" cy="0" r="1" gradientTransform="matrix(5.31253 3.28121 -.93453 1.51307 19.786 20.593)" gradientUnits="userSpaceOnUse"><stop class="zk2mfu__s"/><stop offset="1" class="xx0si6etu"/></radialGradient><radialGradient id="iwnY7lc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.50001 -3.65624 1.29065 -.8825 24.13 26.406)" gradientUnits="userSpaceOnUse"><stop class="wz_ov4j-l"/><stop offset="1" class="a7wya1e_a"/><stop offset="1" class="khy4tkbbd"/></radialGradient><radialGradient id="idvEQXb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.46944 -4.08022 0 26.662 17.124)" gradientUnits="userSpaceOnUse"><stop class="tg0z2qhwd"/><stop offset="1" class="hpe9ehb7d"/></radialGradient><radialGradient id="iop3jKg" cx="0" cy="0" r="1" gradientTransform="matrix(-3.96875 2.34375 -1.44391 -2.44503 13.38 18.656)" gradientUnits="userSpaceOnUse"><stop offset=".221" class="fni_1r5pr"/><stop offset="1" class="rx-90_bsr"/></radialGradient><radialGradient id="imMqyge" cx="0" cy="0" r="1" gradientTransform="rotate(65.039 -.993 22.886)scale(2.03143 2.41318)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="i0sIMuc" cx="0" cy="0" r="1" gradientTransform="matrix(1.42324 .32412 -.99992 4.3908 10.05 15.41)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="iPdEQCH" cx="0" cy="0" r="1" gradientTransform="matrix(-4.91463 .39698 -.70225 -8.69394 18.274 13.39)" gradientUnits="userSpaceOnUse"><stop class="yzaj_tb_p"/><stop offset="1" class="ny0rq0bux"/></radialGradient><radialGradient id="iR9Qinb" cx="0" cy="0" r="1" gradientTransform="matrix(.03116 12.07876 -10.00267 .0258 16.672 7.925)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="krmomebyg"/><stop offset="1" class="c0317ln8x"/></radialGradient><radialGradient id="ibvrqnB" cx="0" cy="0" r="1" gradientTransform="matrix(-.0872 -1.07955 1.33594 -.10791 17.834 12.184)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="h739mqb_c"/><stop offset="1" class="px0sb7ebt"/></radialGradient><radialGradient id="iRO3Axb" cx="0" cy="0" r="1" gradientTransform="rotate(-94.412 12.515 .102)scale(1.03207 1.12314)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kxaprmbjh"/><stop offset="1" class="vgn1hf8dm"/></radialGradient><radialGradient id="ihZX1kd" cx="0" cy="0" r="1" gradientTransform="rotate(171.77 8.955 7.817)scale(8.02893 20.5099)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="uwe7yhbem"/><stop offset="1" class="snpr2ctwr"/></radialGradient><radialGradient id="ilFyVCc" cx="0" cy="0" r="1" gradientTransform="rotate(-61.259 13.488 -3.608)scale(4.00932 1.23137)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="mqqgujbcq"/><stop offset="1" class="fki8vhbsq"/></radialGradient><radialGradient id="i1bN1Dc" cx="0" cy="0" r="1" gradientTransform="rotate(116.541 6.067 9.791)scale(3.17745 2.62325)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="lombttb9q"/><stop offset="1" class="bvf2i9bjf"/></radialGradient><radialGradient id="iiFxjWZ" cx="0" cy="0" r="1" gradientTransform="matrix(.01854 .22948 -.72122 .05825 16.176 14.848)" gradientUnits="userSpaceOnUse"><stop class="t40345qox"/><stop offset="1" class="mrnsdcbqx"/></radialGradient><radialGradient id="iNxKo6b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37705 .77115 -1.2393 -2.21303 16.242 14.303)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="o0aif1l1c"/><stop offset="1" class="vni43obah"/></radialGradient><radialGradient id="iWyvnge" cx="0" cy="0" r="1" gradientTransform="matrix(-.26587 -3.29155 8.32395 -.67235 10.498 11.282)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iOZ8v8b" cx="0" cy="0" r="1" gradientTransform="matrix(-.08357 -2.37067 4.20036 -.14807 20.083 11.748)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="i35dwRB" cx="0" cy="0" r="1" gradientTransform="matrix(-2.33531 -1.27934 .9391 -1.71424 18.898 5.905)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="igO1Fud" cx="0" cy="0" r="1" gradientTransform="matrix(.9629 1.3179 -3.05162 2.2296 14.065 4.788)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="iVp66rb" cx="0" cy="0" r="1" gradientTransform="rotate(175.382 7.431 3.646)scale(2.07599 .77048)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="i7SJCge" cx="0" cy="0" r="1" gradientTransform="matrix(2.63845 -5.03453 5.57774 2.92313 10.088 10.82)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="id2Kk4C" cx="0" cy="0" r="1" gradientTransform="matrix(3.02862 .11461 -.04882 1.29015 16.915 8.734)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="ibdFFqq" cx="0" cy="0" r="1" gradientTransform="matrix(.0616 .76271 -1.21318 .098 17.616 12.577)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iV15nac" cx="0" cy="0" r="1" gradientTransform="matrix(-.24011 -.26268 .36165 -.33058 17.407 12.673)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iWg95Bb" cx="0" cy="0" r="1" gradientTransform="rotate(85.382 -.24 13.778)scale(.76523 1.2172)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iqbAsye" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 13.083 .053)scale(.46489 .5588)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ibEfkzB" cx="0" cy="0" r="1" gradientTransform="matrix(.76121 2.06115 -1.9665 .72626 19.906 12.406)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="uuzk4vb7h"/><stop offset="1" class="yor2p9b5i"/></radialGradient><radialGradient id="iY3BQDe" cx="0" cy="0" r="1" gradientTransform="matrix(.6585 -1.07615 .90203 .55195 20.287 12.89)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="iz6q0pbtm"/><stop offset="1" class="wmov6-bei"/></radialGradient><radialGradient id="irIhODx" cx="0" cy="0" r="1" gradientTransform="matrix(.4341 -1.5021 2.00702 .58002 20.407 13.043)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="r8tuldb4n"/><stop offset="1" class="c_6967ufg"/></radialGradient><radialGradient id="i8xe73b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53148 -.06277 .06737 -1.64369 10.994 13.734)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="o8wr4h7sd"/><stop offset="1" class="t0w03e0rr"/></radialGradient><radialGradient id="iNcVIcx" cx="0" cy="0" r="1" gradientTransform="matrix(-.84962 .2175 -.26688 -1.04253 11.04 13.73)" gradientUnits="userSpaceOnUse"><stop class="ab9g3hmui"/><stop offset="1" class="bwc1tpbev"/></radialGradient><radialGradient id="iVFEUgd" cx="0" cy="0" r="1" gradientTransform="matrix(.41255 -.92529 .86435 .38538 15.335 17.151)" gradientUnits="userSpaceOnUse"><stop class="vgnjz5laj"/><stop offset="1" class="jms8n_bap"/></radialGradient><linearGradient id="iCT71jW" x1="3.687" x2="5.867" y1="13.326" y2="13.775" gradientUnits="userSpaceOnUse"><stop class="yuy9i0bza"/><stop offset=".711" class="q55qtubqg"/></linearGradient><linearGradient id="iWHTeKO" x1="3.993" x2="6.149" y1="12.434" y2="14.583" gradientUnits="userSpaceOnUse"><stop class="fj808to9g"/><stop offset="1" class="dd15d9ljr"/></linearGradient><linearGradient id="isPUtLb" x1="2.571" x2="4.545" y1="13.77" y2="14.102" gradientUnits="userSpaceOnUse"><stop class="yuy9i0bza"/><stop offset=".711" class="q55qtubqg"/></linearGradient><linearGradient id="i0Hsmgb" x1="2.926" x2="5.336" y1="12.703" y2="14.917" gradientUnits="userSpaceOnUse"><stop class="fj808to9g"/><stop offset="1" class="dd15d9ljr"/></linearGradient><linearGradient id="iI7Fm3c" x1="2.645" x2="4.876" y1="14.627" y2="15.111" gradientUnits="userSpaceOnUse"><stop class="yuy9i0bza"/><stop offset=".711" class="q55qtubqg"/></linearGradient><linearGradient id="i2umZac" x1="2.85" x2="5.442" y1="13.695" y2="15.694" gradientUnits="userSpaceOnUse"><stop class="fj808to9g"/><stop offset="1" class="dd15d9ljr"/></linearGradient><linearGradient id="ihj2NQb" x1="2.959" x2="5.166" y1="15.5" y2="16.044" gradientUnits="userSpaceOnUse"><stop class="yuy9i0bza"/><stop offset=".711" class="q55qtubqg"/></linearGradient><linearGradient id="iGL0SHe" x1="8.486" x2="7.645" y1="15.978" y2="15.978" gradientUnits="userSpaceOnUse"><stop offset=".005" class="lleg3ob-y"/><stop offset="1" class="u73ul6u6q"/></linearGradient><linearGradient id="iBWmSlc" x1="28.122" x2="25.428" y1="14.135" y2="14.094" gradientUnits="userSpaceOnUse"><stop class="rxxbes5zu"/><stop offset="1" class="raz5lvbzt"/></linearGradient><linearGradient id="ioJU3pc" x1="29.194" x2="26.65" y1="14.657" y2="14.624" gradientUnits="userSpaceOnUse"><stop class="rxxbes5zu"/><stop offset="1" class="raz5lvbzt"/></linearGradient><linearGradient id="izpiIsd" x1="29.167" x2="26.398" y1="15.418" y2="15.373" gradientUnits="userSpaceOnUse"><stop class="rxxbes5zu"/><stop offset="1" class="raz5lvbzt"/></linearGradient><linearGradient id="icJlJVd" x1="28.853" x2="26.078" y1="16.196" y2="16.146" gradientUnits="userSpaceOnUse"><stop class="rxxbes5zu"/><stop offset="1" class="raz5lvbzt"/></linearGradient><linearGradient id="irfkRsc" x1="14.818" x2="16.752" y1="19.906" y2="21.522" gradientUnits="userSpaceOnUse"><stop class="mrdwr2nvn"/><stop offset="1" class="fg3-p40eh"/></linearGradient><linearGradient id="i8X1Hwd" x1="20.61" x2="16.518" y1="14.797" y2="15.127" gradientUnits="userSpaceOnUse"><stop class="z1p__59we"/><stop offset="1" class="y6b283b4c"/></linearGradient><linearGradient id="iaYqzGc" x1="15.697" x2="16.501" y1="14.383" y2="14.318" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="iVq7SrL" x1="14.677" x2="15.691" y1="14.318" y2="14.292" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="ibViRwe" x1="15.727" x2="15.792" y1="14.758" y2="15.559" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="irGKpIe" x1="15.557" x2="15.589" y1="12.645" y2="13.039" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="izPyIZb" x1="16.473" x2="15.688" y1="14.175" y2="14.271" gradientUnits="userSpaceOnUse"><stop offset=".36" class="af2d-kbww"/><stop offset="1" class="fkbu2fb2z"/></linearGradient><linearGradient id="iEVaYpd" x1="15.772" x2="15.737" y1="15.309" y2="14.872" gradientUnits="userSpaceOnUse"><stop class="y8u9aob3m"/><stop offset="1" class="w22vs7beb"/></linearGradient><linearGradient id="i6n9Sod" x1="15.557" x2="15.608" y1="12.645" y2="13.28" gradientUnits="userSpaceOnUse"><stop class="au2s26bkj"/><stop offset="1" class="e0f0u6bhi"/></linearGradient><linearGradient id="i9HSjnb" x1="21.646" x2="10.729" y1="7.76" y2="8.642" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="igs45Zc" x1="18.351" x2="18.071" y1="12.568" y2="12.774" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ix3GCWc" x1="14.215" x2="13.936" y1="12.902" y2="13.107" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iyXjJyd" x1="21.621" x2="20.652" y1="12.33" y2="14.467" gradientUnits="userSpaceOnUse"><stop class="r7o08-b3s"/><stop offset="1" class="g6f16-bty"/></linearGradient><linearGradient id="iGAfIfe" x1="10.125" x2="11.486" y1="13.925" y2="13.694" gradientUnits="userSpaceOnUse"><stop class="mlsv8jb5y"/><stop offset="1" class="l7gss9bru"/></linearGradient><linearGradient id="iyqmeud" x1="20.651" x2="20.796" y1="12.05" y2="13.84" gradientUnits="userSpaceOnUse"><stop class="q26gyrbrn"/><stop offset="1" class="ihk5xnqly"/></linearGradient><linearGradient id="ijbkdBb" x1="3.139" x2="5.946" y1="14.722" y2="16.403" gradientUnits="userSpaceOnUse"><stop class="fj808to9g"/><stop offset="1" class="dd15d9ljr"/></linearGradient><linearGradient id="iz6v8jd" x1="9.349" x2="12.349" y1="26.375" y2="20.718" gradientUnits="userSpaceOnUse"><stop class="uwc1wf0xf"/><stop offset="1" class="mpi5j3bwz"/></linearGradient><filter id="i1gNd2d" width="3.652" height="3.139" x="2.993" y="11.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4194" stdDeviation=".25"/></filter><filter id="idNTBrd" width="3.727" height="3.323" x="1.914" y="11.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4194" stdDeviation=".25"/></filter><filter id="iVBS24b" width="3.867" height="3.135" x="1.845" y="12.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4194" stdDeviation=".25"/></filter><filter id="ispavfe" width="3.508" height="5.156" x="23.526" y="11.745" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.627451 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4194"/></filter><filter id="iIPGHFb" width="23.107" height="13.423" x="4.271" y="16.874" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.294118 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4194"/></filter><filter id="ifdiOKd" width="10.736" height="11.854" x="10.652" y="7.835" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.686275 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4194"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.568627 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4194" result="effect2_innerShadow_4002_4194"/></filter><filter id="i87ppMt" width="3.768" height="4.763" x="13.668" y="11.84" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4194" stdDeviation=".5"/></filter><filter id="iWYh8xd" width="1.968" height="2.959" x="14.748" y="12.544" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4194" stdDeviation=".05"/></filter><filter id="iFdhJTb" width="2.168" height="3.159" x="14.649" y="12.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4194" stdDeviation=".1"/></filter><filter id="iJ969qx" width="12.116" height="8.445" x="9.241" y="4.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4194"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4194" result="effect2_innerShadow_4002_4194"/></filter><filter id="iB4dLQd" width="2.237" height="1.051" x="16.886" y="9.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4194"/></filter><filter id="iUfMwNl" width="2.176" height="1.231" x="11.976" y="10.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4194"/></filter><filter id="iGisAxd" width="6.617" height="6.502" x="9.133" y="5.478" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4194"/><feGaussianBlur result="effect2_foregroundBlur_4002_4194" stdDeviation=".25"/></filter><filter id="iHLxKAb" width="6.52" height="5.529" x="14.79" y="5.798" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.305882 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4194"/><feGaussianBlur result="effect2_foregroundBlur_4002_4194" stdDeviation=".25"/></filter><filter id="igCCzuc" width=".729" height=".693" x="16.922" y="12.172" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4194" stdDeviation=".05"/></filter><filter id="iKmmd2d" width=".875" height=".893" x="17.712" y="12.179" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4194" stdDeviation=".1"/></filter><filter id="iUZ4Yie" width=".97" height="1.009" x="13.53" y="12.455" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4194" stdDeviation=".1"/></filter><filter id="iCDwfNA" width=".85" height=".703" x="12.825" y="12.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4194" stdDeviation=".05"/></filter><filter id="iCTtzMb" width="1.354" height="2.26" x="9.925" y="12.61" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4194" stdDeviation=".125"/></filter><filter id="iHx8PMe" width="1.861" height="2.798" x="19.811" y="11.578" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4194" stdDeviation=".25"/></filter><filter id="i7Cmatb" width="2.077" height="1.041" x="11.975" y="10.453" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4194" stdDeviation=".075"/></filter><filter id="iuzLF5c" width="2.135" height=".843" x="16.905" y="10.081" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4194" stdDeviation=".075"/></filter><filter id="izt9WYc" width="4.031" height="2.858" x="2.143" y="14.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4194" stdDeviation=".25"/></filter><filter id="iXrgvme" width="1.88" height="1.863" x="14.878" y="15.668" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4194" stdDeviation=".05"/></filter><filter id="irUnJlb" width="4.656" height="7.656" x="8.349" y="19.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4194" stdDeviation=".4"/></filter><filter id="ignSJAe" width="5.216" height="2.806" x="15.504" y="6.245" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4194" stdDeviation=".3"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-shrugging-light" /></template>
<style>
.a0v3z_9ye {
  stop-color: var(--svg-color--dea98c, #DEA98C);
  stop-opacity: 0;
}

.a62m2bb9r {
  stop-color: var(--svg-color--daa890, #DAA890);
  stop-opacity: 0;
}

.a7wya1e_a {
  stop-color: var(--svg-color--ff4412, #FF4412);
  stop-opacity: 0;
}

.ab9g3hmui {
  stop-color: var(--svg-color--c18472, #C18472);
}

.ad0rjgbuv {
  d: path("M20.3 14.41c.313-.036.6-.167.826-.359l.07.875a2.05 2.05 0 0 1-1.107 2q.2-.532.236-1.135z");
}

.af2d-kbww {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
}

.au2s26bkj {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.bcx0ztbqy {
  d: path("M20.363 14.49q-.027-1.507-.069-3.014a1.518 1.518 0 0 1 .069 3.015");
}

.bpksruhej {
  stop-color: var(--svg-color--d9ab93, #D9AB93);
  stop-opacity: 0;
}

.bvf2i9bjf {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
  stop-opacity: 0;
}

.bwc1tpbev {
  stop-color: var(--svg-color--ca8b7a, #CA8B7A);
}

.byn2s1bln {
  stop-color: var(--svg-color--d45533, #D45533);
}

.c_6967ufg {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
}

.c0317ln8x {
  stop-color: var(--svg-color--c9747e, #C9747E);
}

.c1kbbgt7z {
  stop-color: var(--svg-color--d5a288, #D5A288);
  stop-opacity: 0;
}

.c6i37ubuj {
  stop-color: var(--svg-color--d48e86, #D48E86);
}

.c8iu-6btl {
  fill-rule: evenodd;
  d: path("M2.224 12.409a.7.7 0 0 1 .978.157q.051.071.114.168c.262.391.704 1.052 1.516 1.4a.7.7 0 0 1-.551 1.287c-1.246-.534-1.935-1.603-2.156-1.946l-.058-.089a.7.7 0 0 1 .157-.977");
}

.c8j_43f8m {
  stop-color: var(--svg-color--d48e86, #D48E86);
  stop-opacity: 0;
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.ciyxn3-wq {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.756 11.857a1.32 1.32 0 0 1 1.354.892a.26.26 0 0 1-.226.341l-2.098.17a.217.217 0 0 1-.234-.239a1.32 1.32 0 0 1 1.204-1.164");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cwsltxb-v {
  fill: var(--svg-color--d69790, #D69790);
  d: path("m15.138 13.153l-.458 1.777c-.073.363.2.699.547.67l.74-.059c.346-.028.562-.409.432-.75l-.64-1.688c-.138-.374-.54-.342-.621.05");
}

.d154ezdcq {
  stop-color: var(--svg-color--d9ab93, #D9AB93);
}

.dd15d9ljr {
  stop-color: var(--svg-color--eab7a5, #EAB7A5);
  stop-opacity: 0;
}

.df3h-rb9k {
  d: path("M20.351 13.876q-.018-.9-.04-1.798a.901.901 0 0 1 .04 1.798");
}

.djjhgqb7v {
  stop-color: var(--svg-color--f9cdb6, #F9CDB6);
}

.donh02dkd {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
  stop-opacity: 0;
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e0f0u6bhi {
  stop-color: var(--svg-color--e8bba8, #E8BBA8);
  stop-opacity: 0;
}

.e2xjecc1w {
  d: path("M15.818 21.148c-1.104 0-2-.802-2-1.79v-2.114c0-.989.896-1.79 2-1.79s2 .801 2 1.79v2.114c0 .988-.896 1.79-2 1.79");
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f5j3gmo1k {
  d: path("M15.232 8.165a2 2 0 0 1-.073-.124a.63.63 0 0 0-.61-.346l-1.197.096c-1.735.14-3.026 1.676-2.884 3.43l.02.26c-.339-.218-.782-.699-.85-1.53c-.08-1.007.744-1.438 1.186-1.8c.125-.103.23-.189.292-.264l.086-.106c.3-.375.705-1.18 1.705-1.535c.471-.166.956-.24 1.359-.267c.472-.03.837.35.875.821l.11 1.35z");
}

.f6ma3ccql {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
}

.f99ud5nzx {
  d: path("M5.744 11.9a.75.75 0 0 1 1.051.138l.805 1.047c.37.48.57 1.07.57 1.676v2.14H4.911v-2.448a.25.25 0 0 1 .25-.25h1.376A1.3 1.3 0 0 0 6.411 14l-.805-1.047a.75.75 0 0 1 .138-1.052");
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fftjp_1ik {
  d: path("M13.475 12.46a.842.842 0 0 0-.723 1.125l1.621-.13a.847.847 0 0 0-.898-.995");
}

.fg3-p40eh {
  stop-color: var(--svg-color--f4b193, #F4B193);
}

.finomov8p {
  stop-color: var(--svg-color--ff7e34, #FF7E34);
}

.fipf36vin {
  stop-color: var(--svg-color--ff6f3a, #FF6F3A);
  stop-opacity: 0;
}

.fj808to9g {
  stop-color: var(--svg-color--eab7a5, #EAB7A5);
}

.fkbu2fb2z {
  stop-color: var(--svg-color--ffdfc7, #FFDFC7);
  stop-opacity: 0;
}

.fki8vhbsq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
  stop-opacity: 0;
}

.fni_1r5pr {
  stop-color: var(--svg-color--c94829, #C94829);
}

.ft5dv1b6b {
  fill: none;
}

.fxct8lf8b {
  d: path("M10.808 12.86a.902.902 0 0 0 .221 1.76a73 73 0 0 1-.221-1.76");
}

.fxzrd2b9f {
  fill: var(--svg-color--f6bfab, #F6BFAB);
  d: path("m15.22 12.96l-.36 1.77c-.073.363.2.699.547.671l.74-.06c.346-.028.562-.409.432-.75l-.64-1.688c-.138-.374-.637-.334-.719.058");
}

.g2giumbme {
  fill-rule: evenodd;
  d: path("M29.471 12.409a.7.7 0 0 0-.977.157q-.05.071-.115.168c-.262.391-.921 1.114-1.733 1.46c-.355.153-.503.45-.32.876c.152.355.733.503 1.088.35c1.246-.533 1.935-1.602 2.156-1.945l.058-.089a.7.7 0 0 0-.157-.977");
}

.g6f16-bty {
  stop-color: var(--svg-color--f0b8a6, #F0B8A6);
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gno4tuy0h {
  stop-color: var(--svg-color--cc4525, #CC4525);
}

.gp72b5b8k {
  fill-rule: evenodd;
  d: path("M2.504 14.462a.7.7 0 0 1 .98.142c.181.242.653.84 1.873.84a.7.7 0 1 1 0 1.4c-1.827 0-2.668-.965-2.994-1.402a.7.7 0 0 1 .141-.98");
}

.gscvhsb0h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M9.35 25.906c.176-1.146.955-3.881 2.655-5.656");
}

.h739mqb_c {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
}

.h7o6cfbua {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M18.838 7.877h-2.22a.515.515 0 1 1 .083-1.025c.576.092 1.34.22 1.853.346c1.158.287 1.477.851 1.567 1.253a1.61 1.61 0 0 0-1.283-.574");
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hpe9ehb7d {
  stop-color: var(--svg-color--ff8a36, #FF8A36);
  stop-opacity: 0;
}

.hw9415bma {
  stop-color: var(--svg-color--fbcebb, #FBCEBB);
  stop-opacity: 0;
}

.i4u5xtbba {
  d: path("M9.13 21.056a.25.25 0 0 1-.375-.217v-2.864a.6.6 0 0 0-.6-.6H4.871a.6.6 0 0 0-.6.6v4.587c-.005.85.112 2.507 1.484 3.383c1.149.733 2.501.57 3.214.347a.16.16 0 0 1 .208.148v3.707c0 .082.067.15.15.15h12.994a.15.15 0 0 0 .15-.15V26.44c0-.106.108-.18.209-.148c.713.223 2.064.386 3.213-.347c1.372-.876 1.49-2.534 1.485-3.383v-4.587a.6.6 0 0 0-.6-.6h-3.285a.6.6 0 0 0-.6.6v2.864a.25.25 0 0 1-.375.217l-6.694-3.932z");
}

.i5-oiwb9h {
  stop-color: var(--svg-color--dea98c, #DEA98C);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ihk5xnqly {
  stop-color: var(--svg-color--f6bba0, #F6BBA0);
}

.iw0p3zb-d {
  stop-color: var(--svg-color--d18e72, #D18E72);
  stop-opacity: 0;
}

.iz6q0pbtm {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
}

.jg3xmccpx {
  stop-color: var(--svg-color--d18e72, #D18E72);
}

.jms8n_bap {
  stop-color: var(--svg-color--e6b2ac, #E6B2AC);
  stop-opacity: 0;
}

.jo2k47b8i {
  stop-color: var(--svg-color--f9cdb6, #F9CDB6);
  stop-opacity: 0;
}

.k1yfa1pxl {
  stop-color: var(--svg-color--dc4724, #DC4724);
}

.k3dnepbgq {
  stop-color: var(--svg-color--d9a096, #D9A096);
  stop-opacity: 0;
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.khy4tkbbd {
  stop-color: var(--svg-color--fb4b61, #FB4B61);
  stop-opacity: 0;
}

.krmomebyg {
  stop-color: var(--svg-color--c9747e, #C9747E);
  stop-opacity: 0;
}

.kxaprmbjh {
  stop-color: var(--svg-color--d39991, #D39991);
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l-b5apb1u {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.26 12.22a1.32 1.32 0 0 0-1.193 1.098a.26.26 0 0 0 .277.3l2.098-.169a.217.217 0 0 0 .193-.273a1.32 1.32 0 0 0-1.375-.956");
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l7gss9bru {
  stop-color: var(--svg-color--c9887d, #C9887D);
}

.l9egxq44p {
  cx: 15.818px;
  cy: 16.6px;
  fill: var(--svg-color--87004d, #87004D);
  rx: 0.74px;
  ry: 0.732px;
}

.lawgp1bzz {
  fill-rule: evenodd;
  d: path("M3.263 12.093a.7.7 0 0 1 .978.157a2 2 0 0 1 .12.192l.001.002q.05.086.105.174c.077.12.17.25.294.37c.233.228.608.468 1.267.5a.7.7 0 0 1-.068 1.398c-1.025-.05-1.718-.446-2.179-.898a3.5 3.5 0 0 1-.495-.618a6 6 0 0 1-.13-.216l-.004-.006c-.029-.05-.04-.07-.045-.076v-.002a.7.7 0 0 1 .156-.978");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkhmbxpmm {
  d: path("M11.159 15.148a1.55 1.55 0 0 1-.874-.221l.07.875c.069.84.63 1.547 1.415 1.796a3.9 3.9 0 0 1-.415-1.083z");
}

.lleg3ob-y {
  stop-color: var(--svg-color--c29684, #C29684);
}

.lombttb9q {
  stop-color: var(--svg-color--f6c3b0, #F6C3B0);
}

.lubjwvb3q {
  cx: 13.25px;
  cy: 12.839px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.367px;
  ry: 0.186px;
}

.m_o7n74cj {
  fill-rule: evenodd;
  d: path("M2.192 13.431a.7.7 0 0 1 .98.142l.086.118c.301.42.763 1.062 1.779 1.062a.7.7 0 1 1 0 1.4c-1.776 0-2.637-1.24-2.925-1.654q-.037-.055-.062-.088a.7.7 0 0 1 .142-.98");
}

.ma9i0_bmw {
  stop-color: var(--svg-color--d9a793, #D9A793);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mlsv8jb5y {
  stop-color: var(--svg-color--d19787, #D19787);
}

.mpi5j3bwz {
  stop-color: var(--svg-color--c13318, #C13318);
  stop-opacity: 0;
}

.mqqgujbcq {
  stop-color: var(--svg-color--9f6d5c, #9F6D5C);
}

.mrdwr2nvn {
  stop-color: var(--svg-color--bc716b, #BC716B);
}

.mrnsdcbqx {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
  stop-opacity: 0;
}

.mu9k5d6_d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M2.645 13.769c.238.483.966 1.38 2.267 1.534");
}

.mwarx4bjn {
  fill: var(--svg-color--d1a38b, #D1A38B);
  d: path("M5.744 11.9a.75.75 0 0 1 1.051.138l.805 1.047c.37.48.57 1.07.57 1.676v2.14H4.911v-2.448a.25.25 0 0 1 .25-.25h1.376A1.3 1.3 0 0 0 6.411 14l-.805-1.047a.75.75 0 0 1 .138-1.052");
}

.nc25adc0b {
  d: path("M11.308 16.57a3.69 3.69 0 0 0 3.912 2.906l1.773-.143a3.69 3.69 0 0 0 3.395-3.497c-.033-1.78-.063-3.552-.124-5.329a1.367 1.367 0 0 0-1.405-1.241l-1.317.106a2.29 2.29 0 0 1-2.188-1.189a.63.63 0 0 0-.61-.346l-1.197.097c-1.735.14-3.026 1.675-2.885 3.43c.142 1.75.39 3.461.646 5.206");
}

.nj_gpxbaf {
  cx: 13.25px;
  cy: 12.839px;
  rx: 0.367px;
  ry: 0.186px;
}

.ny0rq0bux {
  stop-color: var(--svg-color--d6a195, #D6A195);
}

.o_1ircb0e {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.533 12.311c.066.075-.051.183-.184.3s-.232.2-.299.125c-.066-.074-.011-.23.122-.348s.295-.152.36-.077");
}

.o0aif1l1c {
  stop-color: var(--svg-color--d3968c, #D3968C);
  stop-opacity: 0;
}

.o8wr4h7sd {
  stop-color: var(--svg-color--e8af99, #E8AF99);
  stop-opacity: 0;
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oliv2bcuo {
  stop-color: var(--svg-color--fe7047, #FE7047);
}

.otp2k4yuq {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m20.341 10.827l-.075-.59a1.38 1.38 0 0 0-1.416-1.235l-1.302.105a2.26 2.26 0 0 1-2.072-1.025s-.046-.086-.104-.24c-.359-.938.515-1.731 1.494-1.505c.808.187 1.703.49 2.447.897c1.71.94 1.81 2.616 1.028 3.593");
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.ow3dahbnn {
  stop-color: var(--svg-color--fbcebb, #FBCEBB);
}

.p4yp4sodz {
  fill: var(--svg-color--23181c, #23181C);
  d: path("M15.232 8.165a2 2 0 0 1-.073-.124a.63.63 0 0 0-.61-.346l-1.197.096c-1.735.14-3.026 1.676-2.884 3.43l.02.26c-.339-.218-.782-.699-.85-1.53c-.08-1.007.744-1.438 1.186-1.8c.125-.103.23-.189.292-.264l.086-.106c.3-.375.705-1.18 1.705-1.535c.471-.166.956-.24 1.359-.267c.472-.03.837.35.875.821l.11 1.35z");
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.pgps4wohd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M2.943 14.82c.293.452 1.122 1.258 2.431 1.258");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pl-e-cm4d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M3.793 12.48c.196.501 1.018 1.387 2.052 1.538");
}

.px0sb7ebt {
  stop-color: var(--svg-color--f6b8a8, #F6B8A8);
  stop-opacity: 0;
}

.q26gyrbrn {
  stop-color: var(--svg-color--f9bb9e, #F9BB9E);
}

.q53v6mhsp {
  stop-color: var(--svg-color--1b141e, #1B141E);
}

.q55qtubqg {
  stop-color: var(--svg-color--d1a38b, #D1A38B);
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qfj8esbtd {
  stop-color: var(--svg-color--f05419, #F05419);
}

.ql45_sqyc {
  fill-rule: evenodd;
  d: path("M29.19 14.462a.7.7 0 0 0-.979.142c-.18.242-.653.84-1.873.84a.7.7 0 1 0 0 1.4c1.828 0 2.668-.965 2.995-1.402a.7.7 0 0 0-.142-.98");
}

.qtv5znvtr {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.25 11.22a2.18 2.18 0 0 1 1.527-.485");
}

.qtx4-5fdn {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.765 10.65a2.18 2.18 0 0 0-1.585-.234");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_61u0beb {
  fill: var(--svg-color--000, #000);
  d: path("M14.023 13.26a.48.48 0 0 0-.519-.442a.48.48 0 0 0-.37.737l.85-.07a.5.5 0 0 0 .04-.225");
}

.r-5qfsbcc {
  d: path("M17.533 12.311c.066.075-.051.183-.184.3s-.232.2-.299.125c-.066-.074-.011-.23.122-.348s.295-.152.36-.077");
}

.r20vy5b-j {
  fill-rule: evenodd;
  d: path("M28.432 12.093a.7.7 0 0 0-.977.157a2 2 0 0 0-.115.182l-.006.01l-.001.002c-.034.058-.066.114-.105.174c-.077.12-.17.25-.294.37c-.232.228-.607.468-1.267.5a.7.7 0 0 0 .069 1.398c1.024-.05 1.717-.446 2.178-.898a3.4 3.4 0 0 0 .495-.618a5 5 0 0 0 .13-.216l.004-.006c.029-.05.04-.07.045-.076l.001-.002a.7.7 0 0 0-.157-.978");
}

.r7o08-b3s {
  stop-color: var(--svg-color--ffd6bd, #FFD6BD);
}

.r8tuldb4n {
  stop-color: var(--svg-color--ebbb9d, #EBBB9D);
  stop-opacity: 0;
}

.raz5lvbzt {
  stop-color: var(--svg-color--f2bea6, #F2BEA6);
}

.rbdc6haoq {
  fill: var(--svg-color--f2bea6, #F2BEA6);
  d: path("M25.951 11.9a.75.75 0 0 0-1.051.138l-.805 1.047a2.75 2.75 0 0 0-.57 1.676v2.14h3.259v-2.698h-1.627q.053-.107.128-.204l.804-1.047a.75.75 0 0 0-.138-1.052");
}

.rj7ll6b2x {
  d: path("m20.341 10.827l-.075-.59a1.38 1.38 0 0 0-1.416-1.235l-1.302.105a2.26 2.26 0 0 1-2.072-1.025s-.046-.086-.104-.24c-.359-.938.515-1.731 1.494-1.505c.808.187 1.703.49 2.447.897c1.71.94 1.81 2.616 1.028 3.593");
}

.rra4r9bnq {
  stop-color: var(--svg-color--3c3b3c, #3C3B3C);
}

.rsu15obyt {
  d: path("m15.22 12.96l-.36 1.77c-.073.363.2.699.547.671l.74-.06c.346-.028.562-.409.432-.75l-.64-1.688c-.138-.374-.637-.334-.719.058");
}

.rx-90_bsr {
  stop-color: var(--svg-color--c94829, #C94829);
  stop-opacity: 0;
}

.rxxbes5zu {
  stop-color: var(--svg-color--f0c2aa, #F0C2AA);
}

.s7s03-bva {
  d: path("M10.746 12.235a1.53 1.53 0 0 0-1.183 1.608a1.52 1.52 0 0 0 1.552 1.395c-.142-1-.268-2-.369-3.003");
}

.snpr2ctwr {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
}

.ss9et8bev {
  stop-color: var(--svg-color--d9a096, #D9A096);
}

.t0w03e0rr {
  stop-color: var(--svg-color--e8af99, #E8AF99);
}

.t3uxa4qxo {
  d: path("M19.694 6.99c.497.128.958.43 1.271.892c.501.736.511 1.664.092 2.383a1.47 1.47 0 0 0-.188.843l.09 1.117a1.65 1.65 0 0 0-.647-.202l-.048-1.516a1.367 1.367 0 0 0-1.405-1.241l-1.317.106a2.29 2.29 0 0 1-2.188-1.189a.63.63 0 0 0-.61-.346l-1.197.097c-1.735.14-3.026 1.675-2.885 3.43l.146 1.443a1.6 1.6 0 0 0-.657.302l-.091-1.128a1.47 1.47 0 0 0-.32-.801a2.26 2.26 0 0 1-.321-2.289c.232-.541.646-.94 1.136-1.157a2.53 2.53 0 0 0 1.217-1.15a2.19 2.19 0 0 1 2.648-1.076c.372.127.775.095 1.122-.09c.255-.133.539-.222.843-.246a2.19 2.19 0 0 1 1.956.913c.328.455.81.767 1.353.905");
}

.t40345qox {
  stop-color: var(--svg-color--ffddc7, #FFDDC7);
}

.tcu5qdrym {
  fill: var(--svg-color--202020, #202020);
  d: path("M18.917 10.52a1.75 1.75 0 0 0-.677-.335c-.294-.067-.654-.062-1.145.038a.261.261 0 1 0 .106.513c.447-.092.727-.086.922-.041c.191.043.325.128.483.245a.261.261 0 1 0 .311-.42");
}

.tcv5-6bnf {
  fill: var(--svg-color--000, #000);
  d: path("M17.169 13.006a.48.48 0 0 1 .441-.52a.48.48 0 0 1 .484.668l-.85.069a.44.44 0 0 1-.075-.217");
}

.tg0z2qhwd {
  stop-color: var(--svg-color--ff8a36, #FF8A36);
}

.tjlaau_ls {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M2.715 12.76c.196.501.844 1.458 2.127 1.723");
}

.tlqalkb7x {
  d: path("M4.779 16.937a.25.25 0 0 1 .25-.25h2.93a.25.25 0 0 1 .25.25v.844h-3.43z");
}

.tnb12be6j {
  d: path("M18.388 12.796a.8.8 0 0 0-.253-.417l-.223.288l.128.205z");
}

.u73ul6u6q {
  stop-color: var(--svg-color--c29684, #C29684);
  stop-opacity: 0;
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.uuzk4vb7h {
  stop-color: var(--svg-color--ce978e, #CE978E);
  stop-opacity: 0;
}

.uwc1wf0xf {
  stop-color: var(--svg-color--c13318, #C13318);
}

.uwe7yhbem {
  stop-color: var(--svg-color--e6ad97, #E6AD97);
  stop-opacity: 0;
}

.v0kluxbau {
  stop-color: var(--svg-color--daa890, #DAA890);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vgn1hf8dm {
  stop-color: var(--svg-color--d39991, #D39991);
  stop-opacity: 0;
}

.vgnjz5laj {
  stop-color: var(--svg-color--e6b2ac, #E6B2AC);
}

.vkkig2qdu {
  cx: 15.818px;
  cy: 16.6px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  rx: 0.74px;
  ry: 0.732px;
}

.vni43obah {
  stop-color: var(--svg-color--d3968c, #D3968C);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w22vs7beb {
  stop-color: var(--svg-color--d89793, #D89793);
  stop-opacity: 0;
}

.wmov6-bei {
  stop-color: var(--svg-color--f7b99c, #F7B99C);
  stop-opacity: 0;
}

.wtt6wibxb {
  d: path("M25.951 11.9a.75.75 0 0 0-1.051.138l-.805 1.047a2.75 2.75 0 0 0-.57 1.676v2.14h3.259v-2.698h-1.627q.053-.107.128-.204l.804-1.047a.75.75 0 0 0-.138-1.052");
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.wz_ov4j-l {
  stop-color: var(--svg-color--fb4b61, #FB4B61);
}

.xo_dbbcrk {
  stop-color: var(--svg-color--ff6f3a, #FF6F3A);
}

.xx0si6etu {
  stop-color: var(--svg-color--ff7e32, #FF7E32);
  stop-opacity: 0;
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y6b283b4c {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
  stop-opacity: 0;
}

.y8u9aob3m {
  stop-color: var(--svg-color--d89793, #D89793);
}

.yc61kdroy {
  d: path("M26.916 16.937a.25.25 0 0 0-.25-.25h-2.93a.25.25 0 0 0-.25.25v.844h3.43z");
}

.ycmmgabqw {
  fill-rule: evenodd;
  d: path("M29.503 13.431a.7.7 0 0 0-.98.142l-.086.118c-.301.42-.763 1.16-1.779 1.16c-.386 0-.7.215-.7.602a.7.7 0 0 0 .7.7c1.776 0 2.637-1.24 2.925-1.654l.062-.088a.7.7 0 0 0-.142-.98");
}

.yjyvunbkc {
  d: path("M17.582 12.128a.842.842 0 0 1 .894.995l-1.621.131a.845.845 0 0 1 .727-1.126");
}

.yor2p9b5i {
  stop-color: var(--svg-color--ce978e, #CE978E);
}

.yuy9i0bza {
  stop-color: var(--svg-color--e3ad95, #E3AD95);
}

.yvaupwppj {
  d: path("M14.3 13.137c-.022-.27-.256-.433-.32-.482l-.25.283l.194.325z");
}

.yzaj_tb_p {
  stop-color: var(--svg-color--ffdcc0, #FFDCC0);
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z1p__59we {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.zk2mfu__s {
  stop-color: var(--svg-color--ff7e32, #FF7E32);
}

.zmqd8sbwf {
  fill: var(--svg-color--202020, #202020);
  d: path("M12.193 10.96a2.6 2.6 0 0 1 1.607-.47a.262.262 0 1 1-.021.522a2.1 2.1 0 0 0-1.282.373q-.046.033-.067.05l-.015.013l-.002.002a.262.262 0 0 1-.353-.386z");
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

</style>
