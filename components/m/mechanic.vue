<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#igtPXve)" class="m1i1rlbvk"/><g filter="url(#iZEEJJb)"><path class="xk18tyb3e"/></g><path class="duc38e2qw"/><path fill="url(#iCoINWb)" class="zqss5obsp"/><path fill="url(#i6jO4ud)" class="zqss5obsp"/><path fill="url(#iwtLm3r)" class="zqss5obsp"/><path fill="url(#iRlvw5c)" class="zqss5obsp"/><path class="t4w_5-bef"/><path fill="url(#iDWGLzD)" class="xn6dhjjio"/><path fill="url(#if8dKTc)" class="xn6dhjjio"/><path fill="url(#i8g26lb)" class="xn6dhjjio"/><path fill="url(#i8Zzivd)" class="kvfq7h_0m"/><path fill="url(#iE5Ofte)" class="kvfq7h_0m"/><path fill="url(#iE6iQae)" class="kvfq7h_0m"/><path fill="url(#iTdOGsd)" class="vqc4qgzhu"/><path fill="url(#iJIw8ya)" class="vqc4qgzhu"/><g filter="url(#i9liiee)"><path fill="url(#iblgbvb)" class="dvr2s59yl"/></g><path fill="url(#idlbkMe)" class="rom2yrbwh"/><path fill="url(#iIvEVud)" class="rom2yrbwh"/><path fill="url(#iXRw9pd)" class="rom2yrbwh"/><path fill="url(#iz9xh1o)" class="rom2yrbwh"/><path fill="url(#ixge7fe)" class="rom2yrbwh"/><g filter="url(#ifOaL1p)"><path fill="url(#i1uMIud)" class="lwc2zdrqr"/></g><g filter="url(#iFTlCgf)"><path fill="url(#iPXFJHe)" class="momee7bch"/></g><g filter="url(#iSbADyd)"><path class="dhzy4phlk"/></g><path fill="url(#iL8IXEc)" class="edzuk6bqz"/><path fill="url(#i4V360d)" class="isl_72b0c"/><path fill="url(#iuGwndc)" class="p1ceqfquw"/><path fill="url(#iy9qBTc)" class="p1ceqfquw"/><path fill="url(#izKoZGb)" class="qsetjryse"/><path fill="url(#iDyU7Ee)" class="qsetjryse"/><g filter="url(#iPTZqbd)"><path fill="url(#ihlzoOd)" class="ygs5f6bie"/></g><path fill="url(#iPrXDgb)" class="ygs5f6bie"/><path fill="url(#i4g7A3b)" class="ygs5f6bie"/><path fill="url(#i4wVjyZ)" class="ygs5f6bie"/><path fill="url(#ivwqGTb)" class="ygs5f6bie"/><path fill="url(#iDmW2jd)" class="ygs5f6bie"/><path fill="url(#i75Ic0d)" class="ygs5f6bie"/><g filter="url(#ije9eMc)"><path class="zo6sc_dzt"/></g><g filter="url(#ijQhGJb)"><path fill="url(#iBldQee)" class="hdap23b-n"/><path fill="url(#iVclZzd)" class="hdap23b-n"/><path fill="url(#imyF6NC)" class="hdap23b-n"/><path fill="url(#innAeKd)" class="hdap23b-n"/></g><g filter="url(#ikkc1nc)"><path stroke="url(#iHt9cte)" class="x-kd1mbto"/></g><path fill="url(#iOadlfd)" class="su-zxh6ba"/><g filter="url(#i3dQ0To)"><path class="yh6l9kbbh"/></g><g filter="url(#iRgJD6c)"><path class="b7yeihb3x"/></g><path class="n2_xvjdcg"/><path fill="url(#iNiIFie)" class="rf9vqhkak"/><path class="viezl_bba"/><g filter="url(#iLF59Fd)"><path class="vlysgt3-q"/><path fill="url(#iUlyOUc)" class="k57-vzboh"/></g><g filter="url(#iTCAtnZ)"><path fill="url(#iYCysHd)" class="cczjhfu4h"/></g><path class="r_7zco6vk"/><path fill="url(#i8tAcVc)" class="qmyvahb1h"/><path class="xkfkdpb1x"/><g filter="url(#i3eHQod)"><path fill="url(#im7mDib)" class="ywxh07i2r"/></g><g filter="url(#i3ejkpd)"><ellipse transform="rotate(-27.914 13.256 9.668)" class="tjuuvfmso"/><ellipse fill="url(#ioIBi5d)" transform="rotate(-27.914 13.256 9.668)" class="mqzcoevnf"/></g><path fill="url(#iz6vJjc)" class="gx30_upqx"/><path fill="url(#iXV5Rkb)" class="gx30_upqx"/><path fill="url(#ibNkucd)" class="gx30_upqx"/><path fill="url(#iFo9Tvd)" class="b215l7b2u"/><path fill="url(#ij26Cyc)" class="b215l7b2u"/><g filter="url(#i43fPOe)"><path class="vile1msii"/></g><g filter="url(#ibNtCWc)"><path class="ge727yb2f"/></g><g filter="url(#iGX4i7B)"><path class="s10pk7bwx"/></g><g filter="url(#ir8cCqb)"><path class="w__rh9b9y"/></g><g filter="url(#iyoJIOc)"><path fill="url(#i0vaKQd)" class="s2-xryl0i"/></g><g filter="url(#imBtD2b)"><path fill="url(#iIvrIye)" class="psv7auxid"/></g><g filter="url(#iMZBqJe)"><path class="vcv8c754j"/><path fill="url(#iU8Jczd)" class="u1e8ikbzb"/><path fill="url(#ibXRrGc)" class="u1e8ikbzb"/><path fill="url(#i9sxEsb)" class="u1e8ikbzb"/></g><g filter="url(#iHd4W9b)"><path class="z5g21op2e"/></g><g filter="url(#ilBIKhd)"><path fill="url(#iEYHwqd)" class="pimvl5kot"/><path fill="url(#ibrdWNd)" class="pimvl5kot"/><path fill="url(#i024Txd)" class="pimvl5kot"/><path fill="url(#ieWdNxd)" class="pimvl5kot"/><path fill="url(#iqGuoib)" class="pimvl5kot"/></g><g filter="url(#iByLHsd)"><path stroke="url(#izTUB2b)" class="waqwqw1tk"/></g><g filter="url(#ikK1ITc)"><path stroke="url(#i5g22Rd)" class="phyw90buy"/></g><g filter="url(#igcmaZd)"><path stroke="url(#iA5CJKp)" class="vz0qjzgsj"/></g><defs><radialGradient id="iwtLm3r" cx="0" cy="0" r="1" gradientTransform="rotate(135 3.998 12.054)scale(1.81196 3.24827)" gradientUnits="userSpaceOnUse"><stop offset=".281" class="wnf6rgd_w"/><stop offset="1" class="r3cifybsp"/></radialGradient><radialGradient id="iRlvw5c" cx="0" cy="0" r="1" gradientTransform="rotate(147.269 4.65 10.005)scale(2.65864 2.62008)" gradientUnits="userSpaceOnUse"><stop offset=".113" class="f-d4mvczx"/><stop offset="1" class="bwphqzbzj"/></radialGradient><radialGradient id="i8g26lb" cx="0" cy="0" r="1" gradientTransform="rotate(123.951 4.148 12.705)scale(2.98327 2.1547)" gradientUnits="userSpaceOnUse"><stop class="cdn41be_i"/><stop offset="1" class="tziry6b6t"/></radialGradient><radialGradient id="i8Zzivd" cx="0" cy="0" r="1" gradientTransform="matrix(2.70871 0 0 14.0625 6.066 30)" gradientUnits="userSpaceOnUse"><stop class="g21-8bc8z"/><stop offset="1" class="uhp0yeb2h"/></radialGradient><radialGradient id="iE5Ofte" cx="0" cy="0" r="1" gradientTransform="matrix(-2.2813 6.68749 -5.49369 -1.87406 9.223 17.781)" gradientUnits="userSpaceOnUse"><stop class="ghamttb0q"/><stop offset="1" class="z1an05bwi"/></radialGradient><radialGradient id="iE6iQae" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.2187 2.59375 0 9.223 30.438)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="z8optlbcz"/><stop offset="1" class="gmjyv1b7b"/></radialGradient><radialGradient id="iJIw8ya" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.3125 -1.98 0 24.755 21.938)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="cbe6sn2ns"/><stop offset="1" class="gvyr5190s"/></radialGradient><radialGradient id="iblgbvb" cx="0" cy="0" r="1" gradientTransform="rotate(117.802 6.39 19.816)scale(1.95067 1.56677)" gradientUnits="userSpaceOnUse"><stop class="phvlv-hdf"/><stop offset=".828" class="ty_drcd_b"/></radialGradient><radialGradient id="idlbkMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -12.1153 44.4939 0 15.79 29.983)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="s8-qpgb5g"/><stop offset="1" class="o5bua8boy"/></radialGradient><radialGradient id="iIvEVud" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.875 5.37793 0 22.464 32.545)" gradientUnits="userSpaceOnUse"><stop class="zwo8xvbzg"/><stop offset="1" class="c-tzwtb6q"/></radialGradient><radialGradient id="ixge7fe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.59908 3.3973 -1.77851 -1.88415 10.554 15.318)" gradientUnits="userSpaceOnUse"><stop class="hfyjss5uq"/><stop offset="1" class="y9jato2vd"/></radialGradient><radialGradient id="iuGwndc" cx="0" cy="0" r="1" gradientTransform="matrix(-.89046 3.80574 -4.52093 -1.0578 21.423 11.662)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset="1" class="by5wrxbms"/></radialGradient><radialGradient id="iy9qBTc" cx="0" cy="0" r="1" gradientTransform="matrix(.29942 .41063 -.34884 .25436 20.662 11.935)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="izKoZGb" cx="0" cy="0" r="1" gradientTransform="matrix(1.36075 4.00497 -1.82044 .61852 10.097 11.782)" gradientUnits="userSpaceOnUse"><stop class="b9qaylb2c"/><stop offset="1" class="gz8haxb3i"/></radialGradient><radialGradient id="iDyU7Ee" cx="0" cy="0" r="1" gradientTransform="matrix(.32509 1.01801 -.89301 .28517 10.772 11.773)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="n8euy9vjg"/><stop offset=".977" class="z8auuww1t"/></radialGradient><radialGradient id="ihlzoOd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.33647 0 0 -9.44017 18.626 10.7)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="iPrXDgb" cx="0" cy="0" r="1" gradientTransform="matrix(-.414 6.2287 -2.30687 -.15333 21.067 10.464)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="swgfs-c3o"/><stop offset="1" class="lppsh4wvc"/></radialGradient><radialGradient id="i4g7A3b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.44324 1.75055 0 13.612 9.496)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="u7o3559vd"/><stop offset="1" class="kbjuoc3rc"/></radialGradient><radialGradient id="i4wVjyZ" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.56714 2.0478 0 18.323 9.076)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="bija72usz"/><stop offset="1" class="wwr7m_5oe"/></radialGradient><radialGradient id="ivwqGTb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.03044 .319 -.18003 -1.71033 21.352 6.409)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="zzxhreusb"/><stop offset="1" class="fdlwix82n"/></radialGradient><radialGradient id="iDmW2jd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.58914 -7.91051 0 15.812 6.76)" gradientUnits="userSpaceOnUse"><stop offset=".255" class="hvoi08beg"/><stop offset=".941" class="v9o654bxh"/></radialGradient><radialGradient id="i75Ic0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.2238 -10.9675 0 15.812 6.014)" gradientUnits="userSpaceOnUse"><stop offset=".68" class="zzwq52yhk"/><stop offset="1" class="hf_lc49mg"/></radialGradient><radialGradient id="iHt9cte" cx="0" cy="0" r="1" gradientTransform="matrix(.35438 -.63232 1.84007 1.03125 14.61 14.058)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="iOadlfd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.73571 2.95996 0 15.76 14.314)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iNiIFie" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82818 -1.31731 0 17.988 9.766)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iUlyOUc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.29 .578)scale(.38615 .53163)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i8tAcVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82822 -1.31738 0 13.533 9.766)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ioIBi5d" cx="0" cy="0" r="1" gradientTransform="matrix(-.0079 -.50435 .60625 -.0095 13.24 9.99)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iXV5Rkb" cx="0" cy="0" r="1" gradientTransform="matrix(.64159 2.28989 -2.18474 .61213 20.475 9.78)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="ibNkucd" cx="0" cy="0" r="1" gradientTransform="matrix(.80415 -1.10356 .92501 .67404 20.841 10.336)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="ij26Cyc" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 1.11 9.238)scale(2.16066 2.12413)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><radialGradient id="i0vaKQd" cx="0" cy="0" r="1" gradientTransform="rotate(-158.919 10.694 2.553)scale(8.7748 8.41903)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="iodgi0b6i"/><stop offset="1" class="xh-hzrtoi"/></radialGradient><radialGradient id="iIvrIye" cx="0" cy="0" r="1" gradientTransform="rotate(139.529 8.817 5.504)scale(8.95518 9.18704)" gradientUnits="userSpaceOnUse"><stop class="pvjcf1omm"/><stop offset=".682" class="o2y-twbma"/><stop offset="1" class="x2409oaqt"/></radialGradient><radialGradient id="ibXRrGc" cx="0" cy="0" r="1" gradientTransform="matrix(1.26563 -2.32812 2.70524 1.47064 23.707 20.906)" gradientUnits="userSpaceOnUse"><stop class="tdvgs2sbs"/><stop offset="1" class="tz6f6rbmx"/></radialGradient><radialGradient id="i9sxEsb" cx="0" cy="0" r="1" gradientTransform="rotate(53.424 -5.116 34.838)scale(2.25697 2.46612)" gradientUnits="userSpaceOnUse"><stop class="sf2388bnl"/><stop offset="1" class="ganm9fbbs"/></radialGradient><radialGradient id="ibrdWNd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44615 2.39061 -1.97778 -1.19642 27.245 24.594)" gradientUnits="userSpaceOnUse"><stop class="tqgfgwd_y"/><stop offset="1" class="de0rqgbhp"/></radialGradient><radialGradient id="i024Txd" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 0 0 .46609 23.113 25.97)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><radialGradient id="ieWdNxd" cx="0" cy="0" r="1" gradientTransform="matrix(2.59241 0 0 .5225 22.927 27.297)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><radialGradient id="iqGuoib" cx="0" cy="0" r="1" gradientTransform="matrix(2.71875 0 0 .32813 22.832 28.564)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="h97sosa1o"/><stop offset="1" class="bzewrsgmw"/></radialGradient><filter id="iZEEJJb" width="9.938" height="8.021" x="10.364" y="15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1944" stdDeviation=".5"/></filter><filter id="i9liiee" width="2.65" height="3.79" x="25.245" y="22.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.5"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.560784 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1944"/></filter><filter id="ifOaL1p" width="5.33" height="3.88" x="9.765" y="23.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.384314 0 0 0 0 0.823529 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1944"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_1944" result="shape"/></filter><filter id="iFTlCgf" width="4.03" height="2.58" x="10.415" y="24.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.807843 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1944"/></filter><filter id="iSbADyd" width="3.922" height="2.04" x="13.799" y="16.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.54902 0 0 0 0 0.00392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1944"/></filter><filter id="iPTZqbd" width="11.011" height="12.798" x="10.556" y="4.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1944"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1944" result="effect2_innerShadow_4002_1944"/></filter><filter id="ije9eMc" width="3.916" height="4.96" x="13.59" y="8.859" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1944" stdDeviation=".5"/></filter><filter id="ijQhGJb" width="2.116" height="3.16" x="14.702" y="9.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1944" stdDeviation=".05"/></filter><filter id="ikkc1nc" width="3.785" height="1.595" x="13.867" y="13.054" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1944" stdDeviation=".05"/></filter><filter id="i3dQ0To" width="2.385" height="1.211" x="17.382" y="7.215" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1944"/></filter><filter id="iRgJD6c" width="2.385" height="1.196" x="12.017" y="7.222" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1944"/></filter><filter id="iLF59Fd" width=".799" height=".707" x="17.24" y="9.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1944" stdDeviation=".05"/></filter><filter id="iTCAtnZ" width=".901" height=".924" x="18.099" y="9.397" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1944" stdDeviation=".1"/></filter><filter id="i3eHQod" width=".999" height="1.054" x="13.564" y="9.333" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1944" stdDeviation=".1"/></filter><filter id="i3ejkpd" width=".928" height=".715" x="12.792" y="9.31" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1944" stdDeviation=".05"/></filter><filter id="i43fPOe" width="1.346" height="2.418" x="9.607" y="9.228" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1944" stdDeviation=".125"/></filter><filter id="ibNtCWc" width="1.466" height="2.443" x="20.575" y="9.212" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1944" stdDeviation=".125"/></filter><filter id="iGX4i7B" width="2.34" height="1.069" x="11.992" y="7.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1944" stdDeviation=".125"/></filter><filter id="ir8cCqb" width="2.34" height="1.078" x="17.38" y="7.303" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1944" stdDeviation=".125"/></filter><filter id="iyoJIOc" width="11.17" height="3.114" x="10.155" y="5.342" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.560784 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1944"/></filter><filter id="imBtD2b" width="11.355" height="5.77" x="10.062" y="1.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.12549 0 0 0 0 0.431373 0 0 0 0 0.721569 0 0 0 0.5 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1944"/></filter><filter id="iMZBqJe" width="5.15" height="12.15" x="22.255" y="16.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.384314 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1944"/></filter><filter id="iHd4W9b" width="2.08" height="4.962" x="24.105" y="21.001" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1944" stdDeviation=".325"/></filter><filter id="ilBIKhd" width="4.618" height="5.556" x="22.927" y="24.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.521569 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1944"/></filter><filter id="iByLHsd" width="2.047" height=".25" x="23.378" y="25.867" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1944" stdDeviation=".05"/></filter><filter id="ikK1ITc" width="2.047" height=".25" x="23.3" y="27.172" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1944" stdDeviation=".05"/></filter><filter id="igcmaZd" width="2.047" height=".25" x="23.378" y="28.477" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1944" stdDeviation=".05"/></filter><linearGradient id="igtPXve" x1="12.035" x2="21.723" y1="23.156" y2="18.344" gradientUnits="userSpaceOnUse"><stop class="hzctbo64o"/><stop offset="1" class="ncpoyrbpw"/></linearGradient><linearGradient id="iCoINWb" x1="14.633" x2="13.72" y1="19.957" y2="18.965" gradientUnits="userSpaceOnUse"><stop class="aq4-jj3gx"/><stop offset="1" class="f5q4vk1vk"/></linearGradient><linearGradient id="i6jO4ud" x1="11.535" x2="12.504" y1="18.875" y2="18.875" gradientUnits="userSpaceOnUse"><stop class="a969r93lb"/><stop offset="1" class="ovaf-b7lk"/></linearGradient><linearGradient id="iDWGLzD" x1="19.938" x2="18.313" y1="19.527" y2="19.527" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="k3d1ulbgd"/></linearGradient><linearGradient id="if8dKTc" x1="17" x2="17.938" y1="20.105" y2="19.027" gradientUnits="userSpaceOnUse"><stop class="h5mxx_cud"/><stop offset="1" class="c5x-f3bwv"/></linearGradient><linearGradient id="iTdOGsd" x1="23.473" x2="23.473" y1="29.781" y2="23.531" gradientUnits="userSpaceOnUse"><stop class="unsdl8pjp"/><stop offset="1" class="r0l64jbzx"/></linearGradient><linearGradient id="iXRw9pd" x1="8.441" x2="9.059" y1="29.973" y2="29.953" gradientUnits="userSpaceOnUse"><stop offset=".203" class="t2xb9pb8a"/><stop offset="1" class="oh9185bnq"/></linearGradient><linearGradient id="iz9xh1o" x1="23.232" x2="22.627" y1="30" y2="30" gradientUnits="userSpaceOnUse"><stop class="hwgxlbc5v"/><stop offset="1" class="z4q6dwvkw"/></linearGradient><linearGradient id="i1uMIud" x1="12.43" x2="12.43" y1="23.95" y2="27.53" gradientUnits="userSpaceOnUse"><stop class="qcmtsylcx"/><stop offset="1" class="o7pw9mb8f"/></linearGradient><linearGradient id="iPXFJHe" x1="12.43" x2="12.43" y1="24.45" y2="27.03" gradientUnits="userSpaceOnUse"><stop class="d337rwvie"/><stop offset=".752" class="n5xzb8_yo"/></linearGradient><linearGradient id="iL8IXEc" x1="10.482" x2="10.482" y1="7.621" y2="9.757" gradientUnits="userSpaceOnUse"><stop class="ng77g0bfn"/><stop offset="1" class="ya6f3fvsd"/></linearGradient><linearGradient id="i4V360d" x1="21.038" x2="21.038" y1="7.446" y2="9.041" gradientUnits="userSpaceOnUse"><stop class="w_1c4jmvf"/><stop offset="1" class="yzthd-bab"/></linearGradient><linearGradient id="iBldQee" x1="15.76" x2="16.633" y1="11.547" y2="11.547" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="iVclZzd" x1="14.665" x2="15.761" y1="11.388" y2="11.449" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="imyF6NC" x1="15.76" x2="15.76" y1="11.954" y2="12.823" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="innAeKd" x1="15.76" x2="15.76" y1="9.66" y2="11.433" gradientUnits="userSpaceOnUse"><stop offset=".019" class="bloo_t5pv"/><stop offset="1" class="l5m23db_l"/><stop offset="1" class="aczm1xb4z"/></linearGradient><linearGradient id="iYCysHd" x1="18.782" x2="18.461" y1="9.821" y2="10.018" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="im7mDib" x1="14.292" x2="13.972" y1="9.821" y2="10.018" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iz6vJjc" x1="22.33" x2="21.098" y1="9.848" y2="12.07" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="iFo9Tvd" x1="9.789" x2="11.277" y1="10.567" y2="10.437" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient><linearGradient id="iU8Jczd" x1="25.191" x2="23.16" y1="21.906" y2="21.906" gradientUnits="userSpaceOnUse"><stop class="oj6on8fvq"/><stop offset="1" class="fxowcsv6r"/></linearGradient><linearGradient id="iEYHwqd" x1="26.955" x2="22.927" y1="28.063" y2="28.063" gradientUnits="userSpaceOnUse"><stop class="ut7pv-xgw"/><stop offset=".861" class="oltxz8b0t"/></linearGradient><linearGradient id="izTUB2b" x1="25.183" x2="23.348" y1="25.992" y2="25.992" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="i5g22Rd" x1="25.105" x2="23.27" y1="27.297" y2="27.297" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="iA5CJKp" x1="25.183" x2="23.348" y1="28.602" y2="28.602" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:mechanic" /></template>
<style>
.a8tdckb6o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
}

.a969r93lb {
  stop-color: var(--svg-color--d3c8dc, #D3C8DC);
}

.a9f7swmqb {
  stop-color: var(--svg-color--e39726, #E39726);
}

.abomb1boi {
  stop-color: var(--svg-color--f49f22, #F49F22);
}

.aczm1xb4z {
  stop-color: var(--svg-color--f2ac33, #F2AC33);
  stop-opacity: 0;
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.aq4-jj3gx {
  stop-color: var(--svg-color--f1d5ff, #F1D5FF);
}

.b215l7b2u {
  d: path("M10.601 8.804a1.643 1.643 0 0 0 .141 3.266a80 80 0 0 1-.14-3.266");
}

.b7yeihb3x {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M12.278 7.81a2.83 2.83 0 0 1 1.775-.367a.283.283 0 1 1-.069.563a2.27 2.27 0 0 0-1.415.29a1 1 0 0 0-.094.061l-.002.002a.283.283 0 0 1-.347-.447z");
}

.b9qaylb2c {
  stop-color: var(--svg-color--d57a26, #D57A26);
}

.bija72usz {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
}

.bjbw-ir7e {
  stop-color: var(--svg-color--ffb534, #FFB534);
  stop-opacity: 0;
}

.bloo_t5pv {
  stop-color: var(--svg-color--f2ac33, #F2AC33);
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.bwphqzbzj {
  stop-color: var(--svg-color--e298b3, #E298B3);
  stop-opacity: 0;
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.bzewrsgmw {
  stop-color: var(--svg-color--df9728, #DF9728);
  stop-opacity: 0;
}

.c-tzwtb6q {
  stop-color: var(--svg-color--345cbf, #345CBF);
  stop-opacity: 0;
}

.c5x-f3bwv {
  stop-color: var(--svg-color--ffe4f7, #FFE4F7);
  stop-opacity: 0;
}

.cbe6sn2ns {
  stop-color: var(--svg-color--d2c9de, #D2C9DE);
}

.cczjhfu4h {
  d: path("M18.8 10.07a.86.86 0 0 0-.235-.473l-.266.292l.12.232z");
}

.cdn41be_i {
  stop-color: var(--svg-color--e49da8, #E49DA8);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cu_6wobdp {
  stop-color: var(--svg-color--c88714, #C88714);
  stop-opacity: 0;
}

.d337rwvie {
  stop-color: var(--svg-color--e0ccf0, #E0CCF0);
}

.de0rqgbhp {
  stop-color: var(--svg-color--ffe136, #FFE136);
  stop-opacity: 0;
}

.dhzy4phlk {
  fill: var(--svg-color--f0a32b, #F0A32B);
  d: path("M15.71 18.676c-1.524-.508-1.825-1.445-1.91-1.84h3.921c-.356 1.237-1.494 1.738-2.012 1.84");
}

.duc38e2qw {
  fill: var(--svg-color--ffe9ff, #FFE9FF);
  d: path("M11.736 16.236v4.905c0 .433.418.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076v-1.322l-1.699-1.775c-.787.123-1.547.329-2.27.61");
}

.dvr2s59yl {
  d: path("M26.245 23.1c.55 0 1 .45 1 1v2.29h-2V24.1c0-.55.45-1 1-1");
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.edzuk6bqz {
  d: path("M10.191 7.095h.78v2.662h-.98z");
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.f-d4mvczx {
  stop-color: var(--svg-color--e298b3, #E298B3);
}

.f5q4vk1vk {
  stop-color: var(--svg-color--f1d5ff, #F1D5FF);
  stop-opacity: 0;
}

.fdlwix82n {
  stop-color: var(--svg-color--c09040, #C09040);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fxowcsv6r {
  stop-color: var(--svg-color--847596, #847596);
}

.g21-8bc8z {
  stop-color: var(--svg-color--c7acea, #C7ACEA);
}

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.ganm9fbbs {
  stop-color: var(--svg-color--bab5c6, #BAB5C6);
  stop-opacity: 0;
}

.ge727yb2f {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("M20.825 11.405q.06-.97.113-1.943a.975.975 0 0 1-.113 1.943");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghamttb0q {
  stop-color: var(--svg-color--99959a, #99959A);
}

.glaz8zb9m {
  stop-color: var(--svg-color--c07200, #C07200);
}

.gmjyv1b7b {
  stop-color: var(--svg-color--aba1bb, #ABA1BB);
  stop-opacity: 0;
}

.gvyr5190s {
  stop-color: var(--svg-color--d2c9de, #D2C9DE);
  stop-opacity: 0;
}

.gx30_upqx {
  d: path("M20.784 12.07q.102-1.63.189-3.258a1.643 1.643 0 0 1-.189 3.258");
}

.gz8haxb3i {
  stop-color: var(--svg-color--d06a3c, #D06A3C);
}

.h5mxx_cud {
  stop-color: var(--svg-color--dbbaf9, #DBBAF9);
}

.h97sosa1o {
  stop-color: var(--svg-color--df9728, #DF9728);
}

.hdap23b-n {
  d: path("m15.37 9.971l-.543 1.877c-.11.386.155.772.532.772h.802c.377 0 .643-.392.532-.772l-.543-1.877c-.116-.415-.658-.415-.78 0");
}

.hf_lc49mg {
  stop-color: var(--svg-color--f28a6b, #F28A6B);
}

.hfyjss5uq {
  stop-color: var(--svg-color--3f8aad, #3F8AAD);
}

.hvoi08beg {
  stop-color: var(--svg-color--d87f35, #D87F35);
}

.hwgxlbc5v {
  stop-color: var(--svg-color--2b5fb7, #2B5FB7);
}

.hzctbo64o {
  stop-color: var(--svg-color--d6c6ed, #D6C6ED);
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.iodgi0b6i {
  stop-color: var(--svg-color--47c4ff, #47C4FF);
}

.isl_72b0c {
  d: path("M20.549 7.095h.728l.251 2.662h-.98z");
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.k3d1ulbgd {
  stop-color: var(--svg-color--fee6ff, #FEE6FF);
  stop-opacity: 0;
}

.k57-vzboh {
  d: path("M17.922 9.471c.065.087-.07.193-.225.308c-.154.116-.268.197-.333.11s.007-.25.162-.366c.154-.115.332-.138.396-.052");
}

.kbjuoc3rc {
  stop-color: var(--svg-color--f59632, #F59632);
  stop-opacity: 0;
}

.kc3wm8i6w {
  stop-color: var(--svg-color--ffc92f, #FFC92F);
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.kvfq7h_0m {
  d: path("M8.775 30V17.99a10.98 10.98 0 0 0-4.03 8.51V30z");
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lppsh4wvc {
  stop-color: var(--svg-color--ffd930, #FFD930);
  stop-opacity: 0;
}

.lwc2zdrqr {
  d: path("M13.155 24.45c.71 0 1.29.58 1.29 1.29s-.58 1.29-1.29 1.29h-1.45c-.71 0-1.29-.58-1.29-1.29s.58-1.29 1.29-1.29zm0-.5h-1.45c-.99 0-1.79.8-1.79 1.79s.8 1.79 1.79 1.79h1.45c.99 0 1.79-.8 1.79-1.79s-.8-1.79-1.79-1.79");
}

.m1i1rlbvk {
  d: path("M15.745 15.5c-6.07 0-11 4.92-11 11V30h21.08l.91-3.5c0-6.08-4.92-11-10.99-11");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.momee7bch {
  d: path("M13.155 27.03h-1.45c-.71 0-1.29-.58-1.29-1.29s.58-1.29 1.29-1.29h1.45c.71 0 1.29.58 1.29 1.29c0 .72-.57 1.29-1.29 1.29");
}

.mqzcoevnf {
  cx: 13.256px;
  cy: 9.668px;
  rx: 0.398px;
  ry: 0.201px;
}

.n2_xvjdcg {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.2 9.001c.668 0 1.23.46 1.384 1.081a.28.28 0 0 1-.273.348h-2.278a.235.235 0 0 1-.232-.277A1.43 1.43 0 0 1 18.201 9");
}

.n5xzb8_yo {
  stop-color: var(--svg-color--e0c6f6, #E0C6F6);
}

.n8euy9vjg {
  stop-color: var(--svg-color--be691e, #BE691E);
}

.ncpoyrbpw {
  stop-color: var(--svg-color--cdb2d2, #CDB2D2);
}

.ng77g0bfn {
  stop-color: var(--svg-color--d8891e, #D8891E);
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.o2y-twbma {
  stop-color: var(--svg-color--2780b8, #2780B8);
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

.oltxz8b0t {
  stop-color: var(--svg-color--df9e26, #DF9E26);
}

.ovaf-b7lk {
  stop-color: var(--svg-color--ffeaff, #FFEAFF);
  stop-opacity: 0;
}

.p1ceqfquw {
  d: path("M20.722 11.977c.342-.011.663-.127.924-.315v.95c0 .912-.544 1.724-1.37 2.06q.263-.556.354-1.204z");
}

.phvlv-hdf {
  stop-color: var(--svg-color--ffdf46, #FFDF46);
}

.phyw90buy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.425 27.297h1.797");
}

.pimvl5kot {
  d: path("M22.927 25.326a.73.73 0 0 1 .727-.732h2.39a1.2 1.2 0 0 1 1.2 1.2V29a1 1 0 0 1-1 1h-2.59a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.psv7auxid {
  d: path("M16.795 2c1.44 0 2.82.43 3.73 1.51c.7.83 1.08 2.36.8 4.06c-.6-.57-1.21-.99-1.89-1.31a8.76 8.76 0 0 0-7.39 0c-.68.31-1.29.74-1.89 1.31c-.28-1.71.1-3.23.8-4.06c.91-1.08 2.29-1.51 3.73-1.51z");
}

.pvjcf1omm {
  stop-color: var(--svg-color--4fbfff, #4FBFFF);
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.qcmtsylcx {
  stop-color: var(--svg-color--e73c75, #E73C75);
}

.qmyvahb1h {
  d: path("M13.53 9.279a.91.91 0 0 0-.877 1.151h1.76a1 1 0 0 0 .033-.24a.917.917 0 0 0-.915-.911");
}

.qsetjryse {
  d: path("M10.798 11.977a1.67 1.67 0 0 1-.924-.315v.95c0 .912.543 1.724 1.37 2.06a4.2 4.2 0 0 1-.354-1.204z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_7zco6vk {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.32 9.001c-.667 0-1.23.46-1.384 1.081a.28.28 0 0 0 .274.348h2.277a.235.235 0 0 0 .232-.278a1.43 1.43 0 0 0-1.4-1.15");
}

.r0l64jbzx {
  stop-color: var(--svg-color--b7a9c2, #B7A9C2);
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r3cifybsp {
  stop-color: var(--svg-color--edc3c1, #EDC3C1);
  stop-opacity: 0;
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.rf9vqhkak {
  d: path("M17.99 9.279a.91.91 0 0 1 .877 1.151h-1.76a.915.915 0 0 1 .882-1.151");
}

.rom2yrbwh {
  d: path("M20.735 16.696v5.877c0 .23-.18.41-.41.41h-9.07c-.23 0-.41-.18-.41-.41v-5.92q-.21.101-.413.213a11 11 0 0 0-1.657 1.127V30h14.03V18.068a11 11 0 0 0-2.07-1.372");
}

.s10pk7bwx {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.317 8.096c.262-.188.916-.52 1.69-.39");
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

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.su-zxh6ba {
  d: path("M15.76 13.658a3.1 3.1 0 0 1-1.414-.336c-.14-.07-.29.087-.202.214c.341.518.937.863 1.616.863s1.274-.345 1.616-.863c.088-.132-.062-.285-.202-.214a3.05 3.05 0 0 1-1.414.336");
}

.swgfs-c3o {
  stop-color: var(--svg-color--ffd930, #FFD930);
}

.t2xb9pb8a {
  stop-color: var(--svg-color--2860c0, #2860C0);
}

.t4w_5-bef {
  fill: var(--svg-color--ffe3f6, #FFE3F6);
  d: path("M19.674 16.233v4.908c0 .433-.418.668-.813.379L15.74 18.8a.1.1 0 0 1-.034-.076v-1.322l1.7-1.776c.787.122 1.546.327 2.269.607");
}

.tdvgs2sbs {
  stop-color: var(--svg-color--9872bb, #9872BB);
}

.tjuuvfmso {
  cx: 13.256px;
  cy: 9.668px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.398px;
  ry: 0.201px;
}

.tqgfgwd_y {
  stop-color: var(--svg-color--ffe136, #FFE136);
}

.ty_drcd_b {
  stop-color: var(--svg-color--f9c116, #F9C116);
}

.tz6f6rbmx {
  stop-color: var(--svg-color--9872bb, #9872BB);
  stop-opacity: 0;
}

.tziry6b6t {
  stop-color: var(--svg-color--e49da8, #E49DA8);
  stop-opacity: 0;
}

.u1e8ikbzb {
  d: path("M25.93 17.043c-.191-.1-.432.03-.432.25v1.551c0 .42-.341.77-.763.76a.746.746 0 0 1-.733-.75v-1.561c0-.22-.24-.36-.432-.26a2.48 2.48 0 0 0-1.315 2.171c-.01.97.552 1.821 1.366 2.241c.09.05.15.15.15.25V28a1.005 1.005 0 0 0 2.008.001v-6.324c0-.1.06-.2.15-.25a2.49 2.49 0 0 0 1.326-2.202a2.52 2.52 0 0 0-1.325-2.181");
}

.u7o3559vd {
  stop-color: var(--svg-color--f59632, #F59632);
}

.uhp0yeb2h {
  stop-color: var(--svg-color--c6b9db, #C6B9DB);
}

.unsdl8pjp {
  stop-color: var(--svg-color--9b80b4, #9B80B4);
}

.ut7pv-xgw {
  stop-color: var(--svg-color--ffe132, #FFE132);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v9o654bxh {
  stop-color: var(--svg-color--e98b2a, #E98B2A);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vcv8c754j {
  fill: var(--svg-color--9e88ad, #9E88AD);
  d: path("M25.93 17.043c-.191-.1-.432.03-.432.25v1.551c0 .42-.341.77-.763.76a.746.746 0 0 1-.733-.75v-1.561c0-.22-.24-.36-.432-.26a2.48 2.48 0 0 0-1.315 2.171c-.01.97.552 1.821 1.366 2.241c.09.05.15.15.15.25V28a1.005 1.005 0 0 0 2.008.001v-6.324c0-.1.06-.2.15-.25a2.49 2.49 0 0 0 1.326-2.202a2.52 2.52 0 0 0-1.325-2.181");
}

.viezl_bba {
  fill: var(--svg-color--000, #000);
  d: path("M17.468 10.19a.52.52 0 0 1 .521-.522a.52.52 0 0 1 .464.762h-.923a.5.5 0 0 1-.062-.24");
}

.vile1msii {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M10.618 9.478a.976.976 0 0 0 .085 1.919a79 79 0 0 1-.085-1.919");
}

.vlysgt3-q {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.922 9.471c.065.087-.07.193-.225.308c-.154.116-.268.197-.333.11s.007-.25.162-.366c.154-.115.332-.138.396-.052");
}

.vqc4qgzhu {
  d: path("M22.775 18.043V30h2.979l.981-3.5c0-3.402-1.54-6.44-3.96-8.457");
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.vz0qjzgsj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.503 28.602H25.3");
}

.w__rh9b9y {
  stroke: var(--svg-color--c96953, #C96953);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.395 8.056c-.288-.303-.916-.519-1.69-.389");
}

.w_1c4jmvf {
  stop-color: var(--svg-color--ffda33, #FFDA33);
}

.waqwqw1tk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.503 25.992H25.3");
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wnf6rgd_w {
  stop-color: var(--svg-color--edc3c1, #EDC3C1);
}

.wwr7m_5oe {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
  stop-opacity: 0;
}

.x-kd1mbto {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.38 13.256c.398.207.874.327 1.38.327c.511 0 .981-.12 1.38-.327a.23.23 0 0 1 .275.045c.065.068.09.177.024.276m-3.059-.321l2.996.28m-2.996-.28a.23.23 0 0 0-.275.047a.215.215 0 0 0-.024.275m.3-.322l-.237.28m3.295.041l-.063-.041m.063.041l-.063-.041m.063.041a2.01 2.01 0 0 1-1.68.897a2.01 2.01 0 0 1-1.678-.896m3.295-.042a1.93 1.93 0 0 1-1.616.863a1.93 1.93 0 0 1-1.616-.863m-.062.042l.062-.042m-.062.042l-.001-.001l.063-.041");
}

.x2409oaqt {
  stop-color: var(--svg-color--3a69a2, #3A69A2);
}

.xh-hzrtoi {
  stop-color: var(--svg-color--2f83be, #2F83BE);
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.xk18tyb3e {
  fill: var(--svg-color--caadc8, #CAADC8);
  d: path("M19.301 21.515v-4.908A11 11 0 0 0 17.033 16l-1.7 1.776l-1.7-1.775c-.787.123-1.546.329-2.27.609v4.905c0 .433.419.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076a.1.1 0 0 0 .035.076l3.122 2.72c.394.289.812.054.812-.38");
}

.xkfkdpb1x {
  fill: var(--svg-color--000, #000);
  d: path("M14.052 10.19a.52.52 0 0 0-.521-.522a.52.52 0 0 0-.464.762h.923a.5.5 0 0 0 .062-.24");
}

.xn6dhjjio {
  d: path("M19.674 16.233v4.908c0 .433-.418.668-.813.379L15.74 18.8a.1.1 0 0 1-.034-.076v-1.322l1.7-1.776c.787.122 1.546.327 2.269.607");
}

.y9jato2vd {
  stop-color: var(--svg-color--3f8aad, #3F8AAD);
  stop-opacity: 0;
}

.ya6f3fvsd {
  stop-color: var(--svg-color--cb9440, #CB9440);
}

.ygs5f6bie {
  d: path("M10.835 13.523A4 4 0 0 0 14.8 17h1.926a4 4 0 0 0 3.966-3.477c.12-1.922.284-4.479.374-6.4c-.011-.783-.67-.788-1.45-.821h-1.43a2.47 2.47 0 0 1-2.257-1.473a.68.68 0 0 0-.628-.427h-1.3c-1.884 0-3.446.815-3.446 2.72c0 1.9.154 4.497.279 6.401");
}

.yh6l9kbbh {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M19.57 7.93a1.85 1.85 0 0 0-.701-.42c-.31-.098-.7-.125-1.238-.059a.283.283 0 1 0 .069.562c.49-.06.792-.029.999.036c.202.064.339.167.5.307a.283.283 0 0 0 .371-.427");
}

.ywxh07i2r {
  d: path("M14.363 10.083c0-.295-.24-.491-.304-.55l-.295.284l.181.37z");
}

.yzthd-bab {
  stop-color: var(--svg-color--ffc11f, #FFC11F);
}

.z1an05bwi {
  stop-color: var(--svg-color--99959a, #99959A);
  stop-opacity: 0;
}

.z4q6dwvkw {
  stop-color: var(--svg-color--2b5fb7, #2B5FB7);
  stop-opacity: 0;
}

.z5g21op2e {
  fill: var(--svg-color--b3a4c6, #B3A4C6);
  d: path("M24.755 21.651h.78v3.662h-.78z");
}

.z8auuww1t {
  stop-color: var(--svg-color--be691e, #BE691E);
  stop-opacity: 0;
}

.z8optlbcz {
  stop-color: var(--svg-color--9680b0, #9680B0);
}

.zo6sc_dzt {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m15.264 10.171l-.648 1.877c-.111.386.155.772.53.772h.804c.376 0 .642-.392.531-.772l-.542-1.877c-.117-.416-.554-.416-.675 0");
}

.zqss5obsp {
  d: path("M11.736 16.236v4.905c0 .433.418.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076v-1.322l-1.699-1.775c-.787.123-1.547.329-2.27.61");
}

.zwo8xvbzg {
  stop-color: var(--svg-color--345cbf, #345CBF);
}

.zzwq52yhk {
  stop-color: var(--svg-color--fe9f40, #FE9F40);
  stop-opacity: 0;
}

.zzxhreusb {
  stop-color: var(--svg-color--c09040, #C09040);
}

</style>
