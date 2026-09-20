<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":389};
const content = `<linearGradient id="SVGkr3bbcXS" x1="-385.773" x2="-385.773" y1="802.013" y2="802.832" gradientTransform="matrix(359.4979 0 0 -51.2998 138810.64 41533.422)" gradientUnits="userSpaceOnUse"><stop offset="0" class="lhlrr7b_a"/><stop offset="1" class="qzac3ebvh"/></linearGradient><ellipse fill="url(#SVGkr3bbcXS)" class="skwexac4a"/><linearGradient id="SVGOYb1jesO" x1="-385.702" x2="-385.702" y1="808.094" y2="808.91" gradientTransform="matrix(327.5602 0 0 -28.3446 126466.719 23288.629)" gradientUnits="userSpaceOnUse"><stop offset="0" class="lhlrr7b_a"/><stop offset="1" class="qzac3ebvh"/></linearGradient><path fill="url(#SVGOYb1jesO)" class="d_6e_9rzc"/><radialGradient id="SVGd4bcIeHo" cx="-383.193" cy="798.008" r=".219" gradientTransform="matrix(51.699 0 0 -39.7224 20040.693 31807.137)" gradientUnits="userSpaceOnUse"><stop offset="0" class="spvvurj_v"/><stop offset="1" class="e6ar6bcaa"/></radialGradient><ellipse fill="url(#SVGd4bcIeHo)" class="ti7gz-x3j"/><linearGradient id="SVGgpiSge8V" x1="225.498" x2="228.282" y1="110.502" y2="102.32" gradientTransform="translate(0 8)" gradientUnits="userSpaceOnUse"><stop offset="0" class="iqihhm3xx"/><stop offset="0" class="j10joqrqo"/><stop offset="1" class="krq1wfbqn"/></linearGradient><path fill="url(#SVGgpiSge8V)" class="zaymdcbpv"/><path class="kl3bj60_y"/><radialGradient id="SVGD0ECEboe" cx="-379.687" cy="798.002" r=".215" gradientTransform="matrix(51.699 0 0 -39.7224 19651.356 31807.137)" gradientUnits="userSpaceOnUse"><stop offset="0" class="spvvurj_v"/><stop offset="1" class="e6ar6bcaa"/></radialGradient><ellipse fill="url(#SVGD0ECEboe)" class="uv7wtfbjk"/><linearGradient id="SVGiOVgMc4y" x1="23.893" x2="23.782" y1="110.787" y2="102.661" gradientTransform="translate(0 8)" gradientUnits="userSpaceOnUse"><stop offset="0" class="iqihhm3xx"/><stop offset="0" class="j10joqrqo"/><stop offset="1" class="krq1wfbqn"/></linearGradient><path fill="url(#SVGiOVgMc4y)" class="hi232obuj"/><path class="xlhhzm9tf"/><radialGradient id="SVGIOqPVbcf" cx="-386.001" cy="795.295" r=".258" gradientTransform="matrix(511.0235 0 0 -725.8977 197379.047 577344)" gradientUnits="userSpaceOnUse"><stop offset="0" class="q93vr20uh"/><stop offset="1" class="on-tyliru"/></radialGradient><path fill="url(#SVGIOqPVbcf)" class="r0gxasogg"/><linearGradient id="SVGaeZSIdPY" x1="127.984" x2="127.984" y1="785.133" y2="643.419" gradientTransform="matrix(1 0 0 -1 0 794)" gradientUnits="userSpaceOnUse"><stop offset="0" class="p2j3rrbdy"/><stop offset="1" class="l5v4ro8da"/></linearGradient><path fill="url(#SVGaeZSIdPY)" class="yhb84sheq"/><path class="eyxpksb8d"/><path class="jhk4c4bjk"/><linearGradient id="SVGtcWxSgPR" x1="-383.976" x2="-383.976" y1="796.135" y2="795.872" gradientTransform="matrix(118.1692 0 0 -70.0185 45463.254 55805.137)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="upkhzxfvf"/></linearGradient><path fill="url(#SVGtcWxSgPR)" class="uq6gdfi3o"/><radialGradient id="SVGgwk3UOZL" cx="-383.418" cy="796.301" r=".239" gradientTransform="matrix(92.1201 0 0 -59.9196 35408.29 47783.66)" gradientUnits="userSpaceOnUse"><stop offset="0" class="cd4bz3_pa"/><stop offset=".33" class="d2kcls_hr"/><stop offset=".61" class="m8ieighnv"/><stop offset=".871" class="oate1m4sr"/><stop offset="1" class="cua_02b8g"/></radialGradient><path fill="url(#SVGgwk3UOZL)" class="yutklr1qw"/><path class="fvh01-dan"/><path class="flt-q6b2k"/><linearGradient id="SVGGvvniecq" x1="-384.549" x2="-384.549" y1="796.232" y2="795.951" gradientTransform="matrix(114.676 0 0 -67.9978 44262.39 54197.594)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="upkhzxfvf"/></linearGradient><path fill="url(#SVGGvvniecq)" class="lx9s9rb_k"/><radialGradient id="SVGeag7MbgK" cx="-383.843" cy="796.327" r=".207" gradientTransform="matrix(89.4254 0 0 -58.0704 34490.395 46312.176)" gradientUnits="userSpaceOnUse"><stop offset="0" class="cd4bz3_pa"/><stop offset=".33" class="d2kcls_hr"/><stop offset=".61" class="m8ieighnv"/><stop offset=".871" class="oate1m4sr"/><stop offset="1" class="cua_02b8g"/></radialGradient><path fill="url(#SVGeag7MbgK)" class="dl0d0giuy"/><linearGradient id="SVGnvAX8bkX" x1="-385.657" x2="-385.657" y1="795.828" y2="795.544" gradientTransform="matrix(309.5371 0 0 -204.8136 119501.828 163105.531)" gradientUnits="userSpaceOnUse"><stop offset="0" class="yf-h1sbsv"/><stop offset="1" class="qidcyvbrp"/></linearGradient><path fill="url(#SVGnvAX8bkX)" class="y_ua2ol9p"/><radialGradient id="SVGMaoERdSN" cx="-385.665" cy="795.713" r=".52" gradientTransform="matrix(309.5371 0 0 -193.8552 119501.828 154390.297)" gradientUnits="userSpaceOnUse"><stop offset="0" class="j8wmvbblq"/><stop offset="1" class="p2s2y7xde"/></radialGradient><path fill="url(#SVGMaoERdSN)" class="woux2eriq"/><radialGradient id="SVGSneTJbXX" cx="-385.567" cy="795.814" r=".216" gradientTransform="matrix(278.6017 0 0 -157.6357 107547.195 125597.703)" gradientUnits="userSpaceOnUse"><stop offset="0" class="j8wmvbblq"/><stop offset="1" class="p2s2y7xde"/></radialGradient><path fill="url(#SVGSneTJbXX)" class="jhwk3o8kq"/><path class="ry0sb8bor"/><path class="ro5urobma"/><linearGradient id="SVGh04RBdbI" x1="-379.783" x2="-379.433" y1="799.929" y2="799.929" gradientTransform="matrix(43.9187 0 0 -26.7078 16755.05 21490.367)" gradientUnits="userSpaceOnUse"><stop offset="0" class="m60tnh72q"/><stop offset=".047" class="b8ob7j9jt"/><stop offset=".124" class="r_1h74b_y"/><stop offset=".205" class="lo3nw-btp"/><stop offset=".294" class="hdm-w8b2j"/><stop offset=".393" class="ksgr-sjui"/><stop offset=".527" class="vc--wpv5i"/><stop offset=".661" class="ksgr-sjui"/><stop offset=".749" class="kefn7j15c"/><stop offset=".823" class="xedpx5hcq"/><stop offset=".89" class="ynuatpbgy"/><stop offset=".951" class="d6xb94hnb"/><stop offset="1" class="m60tnh72q"/></linearGradient><path fill="url(#SVGh04RBdbI)" class="pgb0ecc4l"/><linearGradient id="SVGDf5OoOgD" x1="-381.898" x2="-381.53" y1="798.58" y2="798.58" gradientTransform="matrix(44.3134 0 0 -34.2383 17088.955 27460.602)" gradientUnits="userSpaceOnUse"><stop offset="0" class="m60tnh72q"/><stop offset=".047" class="b8ob7j9jt"/><stop offset=".124" class="r_1h74b_y"/><stop offset=".205" class="lo3nw-btp"/><stop offset=".294" class="hdm-w8b2j"/><stop offset=".393" class="ksgr-sjui"/><stop offset=".527" class="vc--wpv5i"/><stop offset=".661" class="ksgr-sjui"/><stop offset=".749" class="kefn7j15c"/><stop offset=".823" class="xedpx5hcq"/><stop offset=".89" class="ynuatpbgy"/><stop offset=".951" class="d6xb94hnb"/><stop offset="1" class="m60tnh72q"/></linearGradient><path fill="url(#SVGDf5OoOgD)" class="xyjufeb6e"/><path class="dy58n2b9u"/><path class="mztxbxjic"/><path class="x96c30b1f"/><linearGradient id="SVGmhJWPc4Z" x1="-1663.756" x2="-1663.256" y1="795.264" y2="795.264" gradientTransform="matrix(58.4858 0 0 -52.4975 97416.344 41762.54)" gradientUnits="userSpaceOnUse"><stop offset="0" class="m60tnh72q"/><stop offset=".527" class="vc--wpv5i"/><stop offset="1" class="m60tnh72q"/></linearGradient><path fill="url(#SVGmhJWPc4Z)" class="iamfvu8eu"/><linearGradient id="SVGtnl9Hb1z" x1="-1660.348" x2="-1660.348" y1="795.261" y2="795.598" gradientTransform="matrix(34.3329 0 0 -40.3218 57129.406 32083.4)" gradientUnits="userSpaceOnUse"><stop offset="0" class="stui2mbih"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGtnl9Hb1z)" class="v--cy9kie"/><linearGradient id="SVGuE1Rubds" x1="192.143" x2="85.006" y1="613.325" y2="492.398" gradientTransform="matrix(1 0 0 -1 0 794)" gradientUnits="userSpaceOnUse"><stop offset="0" class="a5pnjz2fv"/><stop offset=".068" class="ipvviw_kz"/><stop offset=".478" class="joem90b-n"/><stop offset="1" class="tmtgi_bwb"/></linearGradient><path fill="url(#SVGuE1Rubds)" class="he8awtrxj"/><linearGradient id="SVGHaAqacUv" x1="-385.497" x2="-385.497" y1="796.585" y2="796.084" gradientTransform="matrix(299.5021 0 0 -166.3488 115543.68 132713.953)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ltd7azb0q"/><stop offset=".91" class="gn1rebc9e"/><stop offset="1" class="vtt9_00mv"/></linearGradient><path fill="url(#SVGHaAqacUv)" class="uj44h2bgu"/><path class="xulqtvbwy"/><linearGradient id="SVG4SqtRbSN" x1="-385.998" x2="-385.956" y1="795.654" y2="795.824" gradientTransform="matrix(473.8713 0 0 -325.8868 183038.313 259615.406)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ufhb4tbas"/><stop offset="1" class="q4o0gep5w"/></linearGradient><path fill="url(#SVG4SqtRbSN)" class="qcf_42l9r"/><path class="z3s9awblp"/><path class="bey1ynbnr"/><linearGradient id="SVGcFItWdST" x1="89.102" x2="89.102" y1="46.176" y2="81.271" gradientTransform="translate(0 8)" gradientUnits="userSpaceOnUse"><stop offset="0" class="xxrtqdb0g"/><stop offset=".071" class="w2qflcbqj"/><stop offset=".246" class="d41pdjt1d"/><stop offset=".426" class="gssf6rp5q"/><stop offset=".609" class="i6r9q5bvb"/><stop offset=".797" class="dy0c9xbto"/><stop offset="1" class="f879uyr1i"/></linearGradient><path fill="url(#SVGcFItWdST)" class="e-j-hbant"/><path class="bnoblqesl"/><linearGradient id="SVGv7qf3L5I" x1="163.929" x2="163.929" y1="45.928" y2="79.945" gradientTransform="translate(0 8)" gradientUnits="userSpaceOnUse"><stop offset="0" class="xxrtqdb0g"/><stop offset=".071" class="w2qflcbqj"/><stop offset=".246" class="d41pdjt1d"/><stop offset=".426" class="gssf6rp5q"/><stop offset=".609" class="i6r9q5bvb"/><stop offset=".797" class="dy0c9xbto"/><stop offset="1" class="f879uyr1i"/></linearGradient><path fill="url(#SVGv7qf3L5I)" class="d0fa7cc3k"/><linearGradient id="SVGn1Lzfdye" x1="-375.132" x2="-375.132" y1="796.804" y2="796.269" gradientTransform="matrix(22.9552 0 0 -53.0963 8737.788 42368.332)" gradientUnits="userSpaceOnUse"><stop offset="0" class="t-uqshodi"/><stop offset="1" class="z9-sc7eyt"/></linearGradient><path fill="url(#SVGn1Lzfdye)" class="zm48t9h0p"/><path class="yfq1p6bjt"/><path class="zd4-rib9f"/><path class="qc116l8po"/><path class="bdf6sh3nd"/><path class="c0dl7kb3q"/><path class="mh2d8vb3b"/><radialGradient id="SVG9tBJIeHs" cx="-385.603" cy="795.896" r=".214" gradientTransform="matrix(283.646 0 0 -156.7657 109507.64 124930.063)" gradientUnits="userSpaceOnUse"><stop offset="0" class="j8wmvbblq"/><stop offset="1" class="p2s2y7xde"/></radialGradient><path fill="url(#SVG9tBJIeHs)" class="enrb6v0wr"/><g transform="translate(112.78 217.575)"><radialGradient id="SVGWk1TrdMS" cx="-1400.601" cy="578.239" r=".218" gradientTransform="matrix(283.3736 0 0 -166.8517 396908.125 96420.96)" gradientUnits="userSpaceOnUse"><stop offset="0" class="j8wmvbblq"/><stop offset="1" class="p2s2y7xde"/></radialGradient><path fill="url(#SVGWk1TrdMS)" class="d83i_4z2s"/><radialGradient id="SVGE7PLKbUj" cx="-1400.365" cy="581.86" r=".189" gradientTransform="matrix(220.2698 0 0 -27.4445 308479.031 15867.629)" gradientUnits="userSpaceOnUse"><stop offset="0" class="j8wmvbblq"/><stop offset="1" class="p2s2y7xde"/></radialGradient><path fill="url(#SVGE7PLKbUj)" class="lniqdljbz"/></g><radialGradient id="SVGlUsYncFi" cx="-385.378" cy="796.381" r=".208" gradientTransform="matrix(229.0526 0 0 -108.8605 88402.367 86855.695)" gradientUnits="userSpaceOnUse"><stop offset="0" class="j8wmvbblq"/><stop offset="1" class="p2s2y7xde"/></radialGradient><path fill="url(#SVGlUsYncFi)" class="hoxnxop8a"/><path class="y3ekq7bsc"/><linearGradient id="SVGXbhlCbPi" x1="-385.378" x2="-385.378" y1="796.396" y2="797.13" gradientTransform="matrix(229.352 0 0 -99.336 88517.75 79290.18)" gradientUnits="userSpaceOnUse"><stop offset="0" class="bmqf4y-5r"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGXbhlCbPi)" class="vgg3jibvp"/><radialGradient id="SVGo6odm0po" cx="-386.294" cy="794.814" r=".064" gradientTransform="matrix(0 108.8605 1713.9268 0 -1362122.375 42213.414)" gradientUnits="userSpaceOnUse"><stop offset="0" class="z71a5ib_d"/><stop offset="1" class="pf5ykbbgi"/></radialGradient><path fill="url(#SVGo6odm0po)" class="qjx2o_lyz"/><linearGradient id="SVG39bwzVNZ" x1="-363.42" x2="-363.42" y1="797.874" y2="797.373" gradientTransform="matrix(11.1957 0 0 -56.6893 4197.847 45366.047)" gradientUnits="userSpaceOnUse"><stop offset="0" class="tk6kjuvmm"/><stop offset="1" class="p2s2y7xde"/></linearGradient><path fill="url(#SVG39bwzVNZ)" class="sy6a77him"/><linearGradient id="SVGaUjuIcLj" x1="-385.333" x2="-385.333" y1="799.954" y2="798.749" gradientTransform="matrix(227.2561 0 0 -25.7273 87691.656 20687.57)" gradientUnits="userSpaceOnUse"><stop offset="0" class="stui2mbih"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGaUjuIcLj)" class="a1bb7orwu"/><linearGradient id="SVGgRBhVdXf" x1="-385.421" x2="-385.421" y1="796.537" y2="796.068" gradientTransform="matrix(239.7318 0 0 -99.4105 92526.523 79368.477)" gradientUnits="userSpaceOnUse"><stop offset="0" class="stui2mbih"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGgRBhVdXf)" class="j65_oobtf"/><linearGradient id="SVGrHMDhcht" x1="-385.323" x2="-385.323" y1="797.115" y2="797.947" gradientTransform="matrix(255.5011 0 0 -86.6308 98536.844 69287.328)" gradientUnits="userSpaceOnUse"><stop offset="0" class="stui2mbih"/><stop offset="1" class="pnjr8_b7e"/></linearGradient><path fill="url(#SVGrHMDhcht)" class="n85kfev4w"/><linearGradient id="SVGz689AcQV" x1="-381.002" x2="-381.002" y1="797.406" y2="797.815" gradientTransform="matrix(46.2602 0 0 -84.2048 17758.268 67414.563)" gradientUnits="userSpaceOnUse"><stop offset="0" class="yf-h1sbsv"/><stop offset="1" class="v9u8nhb5n"/></linearGradient><path fill="url(#SVGz689AcQV)" class="hwncey1bz"/><g transform="translate(357.302 325.365)"><path class="dzpiiobrd"/><linearGradient id="SVG0XMnjdaH" x1="-3596.948" x2="-3597.298" y1="472.034" y2="472.037" gradientTransform="matrix(39.0922 0 0 -73.9556 140451.266 34765.941)" gradientUnits="userSpaceOnUse"><stop offset="0" class="a0z7efbhn"/><stop offset="1" class="x0kxpybge"/></linearGradient><path fill="url(#SVG0XMnjdaH)" class="cha1nn1rs"/><linearGradient id="SVGyzabIdqA" x1="-3595.353" x2="-3595.353" y1="473.48" y2="473.107" gradientTransform="matrix(28.9715 0 0 -47.6624 103994.305 22410.176)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="xflly4r9p"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGyzabIdqA)" class="dox2pwbvl"/><linearGradient id="SVGAtJHDd2T" x1="-3596.311" x2="-3596.311" y1="472.965" y2="472.546" gradientTransform="matrix(33.6359 0 0 -54.5934 120796.734 25682.729)" gradientUnits="userSpaceOnUse"><stop offset="0" class="stui2mbih"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGAtJHDd2T)" class="pxiy7oyva"/></g><path class="x-qw4nb-c"/><path class="ck85svbhu"/><path class="aljrg8j_w"/><path class="utq5d8b9h"/><path class="sb6dfuivy"/><path class="uaz5glfiq"/><path class="ooo3xybde"/><linearGradient id="SVGryQ1sc8X" x1="-385.377" x2="-385.377" y1="796.49" y2="796.822" gradientTransform="matrix(228.7532 0 0 -93.9605 88286.82 75020.54)" gradientUnits="userSpaceOnUse"><stop offset="0" class="f-c80ro0i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGryQ1sc8X)" class="mtl_dn34k"/><linearGradient id="SVGBoF5jcWx" x1="127.475" x2="126.678" y1="104.842" y2="89.723" gradientTransform="translate(0 8)" gradientUnits="userSpaceOnUse"><stop offset="0" class="b8nallb2t"/><stop offset=".999" class="byj4sdb9t"/><stop offset="1" class="byj4sdb9t"/></linearGradient><path fill="url(#SVGBoF5jcWx)" class="h14skgbgp"/><linearGradient id="SVGfAvBLcVh" x1="-381.293" x2="-381.293" y1="800.235" y2="799.502" gradientTransform="matrix(50.0023 0 0 -24.3524 19192.55 19580.295)" gradientUnits="userSpaceOnUse"><stop offset="0" class="p_qts-b_r"/><stop offset="1" class="c9cd37btj"/></linearGradient><path fill="url(#SVGfAvBLcVh)" class="zt38e9bld"/><radialGradient id="SVG9ygWOdif" cx="-385.378" cy="796.38" r=".437" gradientTransform="matrix(229.0526 0 0 -108.8325 88402.367 86833.36)" gradientUnits="userSpaceOnUse"><stop offset="0" class="kvdgcfbzw"/><stop offset="1" class="mrugtqc0j"/></radialGradient><path fill="url(#SVG9ygWOdif)" class="yh6k42ohu"/><path class="t7y383bis"/><radialGradient id="SVGciSpbdVU" cx="-382.486" cy="796.519" r=".449" gradientTransform="matrix(63.1559 0 0 -120.0655 24290.285 95817.07)" gradientUnits="userSpaceOnUse"><stop offset="0" class="k05n1gbkm"/><stop offset="1"/></radialGradient><path fill="url(#SVGciSpbdVU)" class="c1hc9s8ws"/><g transform="translate(239.532 432.156)"><linearGradient id="SVGwHWEDQtx" x1="-2537.27" x2="-2536.729" y1="365.595" y2="365.595" gradientTransform="matrix(48.3641 0 0 -84.2048 122593.25 30590.684)" gradientUnits="userSpaceOnUse"><stop offset="0" class="arzb1snoy"/><stop offset="1" class="d_59i2lmq"/></linearGradient><path fill="url(#SVGwHWEDQtx)" class="we6yfovwq"/><linearGradient id="SVGAuQbEsVm" x1="-2537.433" x2="-2536.931" y1="370.173" y2="370.173" gradientTransform="matrix(49.8908 0 0 -31.239 126475.258 11356.35)" gradientUnits="userSpaceOnUse"><stop offset="0" class="h2wr6dozo"/><stop offset=".385" class="dosrsbbxv"/><stop offset=".651" class="mmamd3dnx"/><stop offset="1" class="dosrsbbxv"/></linearGradient><path fill="url(#SVGAuQbEsVm)" class="b4hsl0-lx"/><g transform="translate(7.984 32.936)"><linearGradient id="SVGmTgJxcRe" x1="-2590.132" x2="-2589.626" y1="345.213" y2="345.213" gradientTransform="matrix(10.4346 0 0 -16.2682 26911.154 5392.686)" gradientUnits="userSpaceOnUse"><stop offset="0" class="cd4bz3_pa"/><stop offset="1" class="cua_02b8g"/></linearGradient><path fill="url(#SVGmTgJxcRe)" class="f7d6g6xrk"/><linearGradient id="SVG2dtQ0cJQ" x1="-2590.652" x2="-2590.152" y1="339.601" y2="339.601" gradientTransform="matrix(10.9786 0 0 -25.2812 28318.268 8360.066)" gradientUnits="userSpaceOnUse"><stop offset="0" class="cd4bz3_pa"/><stop offset="1" class="cua_02b8g"/></linearGradient><path fill="url(#SVG2dtQ0cJQ)" class="f94ycccrc"/></g><g transform="translate(6.986 18.963)"><linearGradient id="SVGywDtFNdz" x1="-2571.527" x2="-2571.031" y1="364.296" y2="364.296" gradientTransform="matrix(7.2858 0 0 -11.8768 18627.996 4109.95)" gradientUnits="userSpaceOnUse"><stop offset="0" class="x-0n5b0re"/><stop offset="1" class="qtbsoqboy"/></linearGradient><path fill="url(#SVGywDtFNdz)" class="whg7vubcp"/><linearGradient id="SVGsq7kIdqM" x1="-2578.687" x2="-2578.185" y1="357.292" y2="357.292" gradientTransform="matrix(9.4815 0 0 -17.9984 24334.986 6214.113)" gradientUnits="userSpaceOnUse"><stop offset="0" class="x-0n5b0re"/><stop offset="1" class="qtbsoqboy"/></linearGradient><path fill="url(#SVGsq7kIdqM)" class="n9t-n_dcx"/><linearGradient id="SVGYYXZrblh" x1="-2584.059" x2="-2583.557" y1="354.074" y2="354.074" gradientTransform="matrix(12.2162 0 0 -23.3544 31444.402 8050.336)" gradientUnits="userSpaceOnUse"><stop offset="0" class="x-0n5b0re"/><stop offset="1" class="qtbsoqboy"/></linearGradient><path fill="url(#SVGYYXZrblh)" class="y4gopsb7n"/></g><path class="wo_pay7oo"/></g><linearGradient id="SVG0j8suemS" x1="-382.194" x2="-381.693" y1="796.548" y2="796.548" gradientTransform="matrix(55.6064 0 0 -113.5782 21372.644 90658.383)" gradientUnits="userSpaceOnUse"><stop offset="0" class="arzb1snoy"/><stop offset=".385" class="d_59i2lmq"/><stop offset=".651" class="arzb1snoy"/><stop offset="1" class="d_59i2lmq"/></linearGradient><path fill="url(#SVG0j8suemS)" class="qh-v03bmu"/><linearGradient id="SVGosvgNbHb" x1="-381.912" x2="-381.912" y1="810.237" y2="811.139" gradientTransform="matrix(55.1922 0 0 -13.5735 21212.865 11224.676)" gradientUnits="userSpaceOnUse"><stop offset="0" class="k9q_m2sdz"/><stop offset="1" class="bn854uv_r"/></linearGradient><path fill="url(#SVGosvgNbHb)" class="srwcfyr4x"/><linearGradient id="SVGZn5Iqe4d" x1="-382.199" x2="-381.699" y1="802.634" y2="802.634" gradientTransform="matrix(55.6912 0 0 -27.0886 21405.326 21943.723)" gradientUnits="userSpaceOnUse"><stop offset="0" class="cd4bz3_pa"/><stop offset=".385" class="cua_02b8g"/><stop offset=".651" class="cd4bz3_pa"/><stop offset="1" class="cua_02b8g"/></linearGradient><path fill="url(#SVGZn5Iqe4d)" class="he0m7tite"/><linearGradient id="SVGjVxdXc4B" x1="-382.162" x2="-381.661" y1="810.753" y2="810.753" gradientTransform="matrix(55.1922 0 0 -13.3022 21212.715 10986.427)" gradientUnits="userSpaceOnUse"><stop offset="0" class="j8u17yhai"/><stop offset=".385" class="agmzqnb8d"/><stop offset=".651" class="j8u17yhai"/><stop offset="1" class="agmzqnb8d"/></linearGradient><path fill="url(#SVGjVxdXc4B)" class="h90xyg1im"/><linearGradient id="SVGoRkzEddf" x1="-381.853" x2="-381.353" y1="797.942" y2="797.942" gradientTransform="matrix(51.699 0 0 -58.7348 19862.742 47040.793)" gradientUnits="userSpaceOnUse"><stop offset="0" class="h2wr6dozo"/><stop offset=".385" class="dosrsbbxv"/><stop offset=".651" class="mmamd3dnx"/><stop offset="1" class="dosrsbbxv"/></linearGradient><path fill="url(#SVGoRkzEddf)" class="njg5--byg"/><linearGradient id="SVGEDtiwbcM" x1="-382.058" x2="-381.558" y1="801.679" y2="801.679" gradientTransform="matrix(53.9945 0 0 -29.3011 20749.705 23680.887)" gradientUnits="userSpaceOnUse"><stop offset="0" class="x-0n5b0re"/><stop offset=".385" class="qtbsoqboy"/><stop offset=".651" class="x-0n5b0re"/><stop offset="1" class="qtbsoqboy"/></linearGradient><path fill="url(#SVGEDtiwbcM)" class="d8_7kkbnl"/><path fill="url(#SVGEDtiwbcM)" class="d8_7kkbnl"/><path class="cm4w8497n"/><g transform="translate(242 325)"><radialGradient id="SVG5OvHzeeJ" cx="-2489.869" cy="504.594" r=".364" gradientTransform="matrix(3.5179 0 0 -5.8555 8642.059 2822.885)" gradientUnits="userSpaceOnUse"><stop offset="0" class="stui2mbih"/><stop offset=".917" class="vvcil5b3r"/><stop offset="1" class="vc--wpv5i"/></radialGradient><path fill="url(#SVG5OvHzeeJ)" class="zt10s4bll"/><path class="w5zndcn8u"/><path class="o3nlen8zw"/><radialGradient id="SVGI2XPoeeK" cx="-2522.95" cy="527.563" r=".216" gradientTransform="matrix(6.0182 0 0 -3.4868 15079.142 1705.3)" gradientUnits="userSpaceOnUse"><stop offset="0" class="stui2mbih"/><stop offset=".917" class="vvcil5b3r"/><stop offset="1" class="vc--wpv5i"/></radialGradient><path fill="url(#SVGI2XPoeeK)" class="xuptg5buq"/><path class="nr7rmf-ng"/><path class="nz2b2-gnb"/><radialGradient id="SVGPbzY6cpg" cx="-2515.624" cy="487.661" r=".47" gradientTransform="matrix(4.9922 0 0 -11.432 12460.1 5443.598)" gradientUnits="userSpaceOnUse"><stop offset="0" class="stui2mbih"/><stop offset=".917" class="vvcil5b3r"/><stop offset="1" class="vc--wpv5i"/></radialGradient><path fill="url(#SVGPbzY6cpg)" class="bb9eckbmg"/><path class="b5fyytdrw"/><path class="rw744qbyj"/><radialGradient id="SVGvaXR2c1t" cx="-2516.292" cy="506.205" r=".284" gradientTransform="matrix(5.0729 0 0 -5.7462 12665.905 2782.308)" gradientUnits="userSpaceOnUse"><stop offset="0" class="stui2mbih"/><stop offset=".917" class="vvcil5b3r"/><stop offset="1" class="vc--wpv5i"/></radialGradient><path fill="url(#SVGvaXR2c1t)" class="fs4byuhds"/><path class="nabbi62sn"/><path class="jc_wq3b0v"/><radialGradient id="SVG1WKWvdYX" cx="-2504.816" cy="489.621" r=".486" gradientTransform="matrix(4.4096 0 0 -10.6382 10927.634 5083.951)" gradientUnits="userSpaceOnUse"><stop offset="0" class="stui2mbih"/><stop offset=".917" class="vvcil5b3r"/><stop offset="1" class="vc--wpv5i"/></radialGradient><path fill="url(#SVG1WKWvdYX)" class="ol6stibsk"/><path class="mpm03gbpd"/><path class="pj9f--b4l"/><radialGradient id="SVGgILghcml" cx="-2489.648" cy="507.247" r=".372" gradientTransform="matrix(3.3232 0 0 -5.6997 8170.308 2769.062)" gradientUnits="userSpaceOnUse"><stop offset="0" class="stui2mbih"/><stop offset=".917" class="vvcil5b3r"/><stop offset="1" class="vc--wpv5i"/></radialGradient><path fill="url(#SVGgILghcml)" class="xraz3vbse"/><path class="kakqz1q1n"/><path class="m1kpl7blk"/><radialGradient id="SVG2YMKfumu" cx="-2516.615" cy="495.509" r=".352" gradientTransform="matrix(5.4095 0 0 -8.5634 13500.17 4127.838)" gradientUnits="userSpaceOnUse"><stop offset="0" class="stui2mbih"/><stop offset=".917" class="vvcil5b3r"/><stop offset="1" class="vc--wpv5i"/></radialGradient><path fill="url(#SVG2YMKfumu)" class="pufh1g2sv"/><path class="jq2w2ihje"/><path class="ddy6pbelv"/><radialGradient id="SVG39EzEcQF" cx="-2462.251" cy="549.19" r=".28" gradientTransform="matrix(2.5115 0 0 -2.7619 6072.725 1400.572)" gradientUnits="userSpaceOnUse"><stop offset="0" class="stui2mbih"/><stop offset=".917" class="vvcil5b3r"/><stop offset="1" class="vc--wpv5i"/></radialGradient><path fill="url(#SVG39EzEcQF)" class="dx0utn0co"/><path class="r_3uws2px"/><path class="kpdw4er0f"/><radialGradient id="SVGkeOk2dzB" cx="-2509.154" cy="514.484" r=".28" gradientTransform="matrix(4.4348 0 0 -4.9154 11027.668 2412.976)" gradientUnits="userSpaceOnUse"><stop offset="0" class="stui2mbih"/><stop offset=".917" class="vvcil5b3r"/><stop offset="1" class="vc--wpv5i"/></radialGradient><path fill="url(#SVGkeOk2dzB)" class="krnlykzva"/><path class="crbw4tbed"/><path class="elza3oq2w"/><radialGradient id="SVGSgrXpela" cx="-2492.54" cy="506.647" r=".385" gradientTransform="matrix(3.4038 0 0 -6.0991 8384.792 2979.387)" gradientUnits="userSpaceOnUse"><stop offset="0" class="stui2mbih"/><stop offset=".917" class="vvcil5b3r"/><stop offset="1" class="vc--wpv5i"/></radialGradient><path fill="url(#SVGSgrXpela)" class="vkq9u98sh"/><path class="rbbs3pn7c"/><path class="us61mrb8y"/><radialGradient id="SVGj4qLAE9N" cx="-2541.496" cy="489.438" r=".238" gradientTransform="matrix(11.2598 0 0 -8.9589 28503.16 4225.142)" gradientUnits="userSpaceOnUse"><stop offset="0" class="stui2mbih"/><stop offset=".917" class="vvcil5b3r"/><stop offset="1" class="vc--wpv5i"/></radialGradient><path fill="url(#SVGj4qLAE9N)" class="uuhsu48rh"/><path class="t89m0lbfi"/><path class="m50f9ybxw"/><radialGradient id="SVGzBw0VcLA" cx="-2496.112" cy="506.818" r=".31" gradientTransform="matrix(3.7686 0 0 -4.9671 9294.663 2365.571)" gradientUnits="userSpaceOnUse"><stop offset="0" class="stui2mbih"/><stop offset=".917" class="vvcil5b3r"/><stop offset="1" class="vc--wpv5i"/></radialGradient><path fill="url(#SVGzBw0VcLA)" class="uo8qktbls"/><path class="wq9g5ilqy"/><path class="b8pcjzubi"/><radialGradient id="SVG2PHGeeiD" cx="-2467.6" cy="505.886" r=".408" gradientTransform="matrix(2.7391 0 0 -5.2897 6639.116 2531.234)" gradientUnits="userSpaceOnUse"><stop offset="0" class="stui2mbih"/><stop offset=".917" class="vvcil5b3r"/><stop offset="1" class="vc--wpv5i"/></radialGradient><path fill="url(#SVG2PHGeeiD)" class="ph_a4lq_p"/><path class="mw9qzk31d"/><path class="xp0eq4ynx"/><radialGradient id="SVGegTpiIKj" cx="-2511.555" cy="507.65" r=".271" gradientTransform="matrix(4.7548 0 0 -4.9511 11835.71 2365.169)" gradientUnits="userSpaceOnUse"><stop offset="0" class="stui2mbih"/><stop offset=".917" class="vvcil5b3r"/><stop offset="1" class="vc--wpv5i"/></radialGradient><path fill="url(#SVGegTpiIKj)" class="rue-_yb9l"/><path class="s9r2zub6m"/><path class="colkp1rlr"/><radialGradient id="SVGMebJmbBt" cx="-2487.713" cy="507.569" r=".343" gradientTransform="matrix(3.2032 0 0 -4.9754 7868.248 2377.624)" gradientUnits="userSpaceOnUse"><stop offset="0" class="stui2mbih"/><stop offset=".917" class="vvcil5b3r"/><stop offset="1" class="vc--wpv5i"/></radialGradient><path fill="url(#SVGMebJmbBt)" class="yzoivvpbr"/><path class="n47-8nc8m"/><path class="ca_bq02_r"/><radialGradient id="SVGe8a1Xbgt" cx="-2512.622" cy="512.922" r=".252" gradientTransform="matrix(5.0484 0 0 -4.5061 12568.333 2169.994)" gradientUnits="userSpaceOnUse"><stop offset="0" class="stui2mbih"/><stop offset=".917" class="vvcil5b3r"/><stop offset="1" class="vc--wpv5i"/></radialGradient><path fill="url(#SVGe8a1Xbgt)" class="xa9_vkbhq"/><path class="s1lgr3b3s"/><path class="bnvdhuywe"/><radialGradient id="SVGsALUhyuu" cx="-2471.009" cy="511.142" r=".377" gradientTransform="matrix(2.7125 0 0 -4.6908 6594.565 2255.991)" gradientUnits="userSpaceOnUse"><stop offset="0" class="stui2mbih"/><stop offset=".917" class="vvcil5b3r"/><stop offset="1" class="vc--wpv5i"/></radialGradient><path fill="url(#SVGsALUhyuu)" class="as5eecbtw"/><path class="nky0xp0jv"/><path class="e84y0va9v"/><radialGradient id="SVG77ZhtbZR" cx="-2524.448" cy="506.523" r=".249" gradientTransform="matrix(6.0957 0 0 -5.2211 15289.724 2500.768)" gradientUnits="userSpaceOnUse"><stop offset="0" class="stui2mbih"/><stop offset=".917" class="vvcil5b3r"/><stop offset="1" class="vc--wpv5i"/></radialGradient><path fill="url(#SVG77ZhtbZR)" class="z1gbl_b-h"/><path class="qu23p31xv"/><path class="l11b221hb"/></g><g transform="translate(260.491 431.158)"><linearGradient id="SVGBNhQEctr" x1="-2711.975" x2="-2711.975" y1="377.656" y2="377.741" gradientTransform="matrix(13.3739 0 0 -16.6674 36143.344 6081.417)" gradientUnits="userSpaceOnUse"><stop offset="0" class="h-1xy4lyx"/><stop offset="1" class="y0kh1ab9h"/></linearGradient><path fill="url(#SVGBNhQEctr)" class="t7nwvhbve"/><path class="k5xovztmq"/><path class="j8j3z8b3o"/></g><g transform="translate(261.489 437.146)"><radialGradient id="SVGl4qSNe3Q" cx="-2712.29" cy="381.454" r=".276" gradientTransform="matrix(9.1893 0 0 -9.7554 24796.414 3505.687)" gradientUnits="userSpaceOnUse"><stop offset="0" class="stui2mbih"/><stop offset=".917" class="vvcil5b3r"/><stop offset="1" class="vc--wpv5i"/></radialGradient><path fill="url(#SVGl4qSNe3Q)" class="a306n446l"/><path class="r_52pwbii"/><path class="pi06cccls"/></g><path class="r-57a4b3t"/><path class="ho0x6fbwr"/><linearGradient id="SVG3Z200b2d" x1="-383.333" x2="-383.333" y1="799.201" y2="798.7" gradientTransform="matrix(92.1201 0 0 -23.2912 35408.29 18689.565)" gradientUnits="userSpaceOnUse"><stop offset="0" class="sf3u6-8dg"/><stop offset=".888" class="iogt4f9jv"/><stop offset="1" class="sll_zg-uo"/></linearGradient><path fill="url(#SVG3Z200b2d)" class="x4ila6b7b"/><circle class="y42hhujkb"/><circle class="gwvhz2blz"/><linearGradient id="SVGwjhQxwyq" x1="-383.931" x2="-383.931" y1="799.33" y2="798.879" gradientTransform="matrix(89.5252 0 0 -22.4786 34528.93 18041.637)" gradientUnits="userSpaceOnUse"><stop offset="0" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></linearGradient><path fill="url(#SVGwjhQxwyq)" class="bli_3eiwt"/><circle class="sv656ewjo"/><circle class="clpby4b5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:tastejs" /></template>
<style>
.a0z7efbhn {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0.786;
}

.a1bb7orwu {
  d: path("M65.4 114.4s65.3 8.4 113.9-6.5c-.1 0-52.2 24-113.9 6.5");
}

.a306n446l {
  d: path("M-128.6-217.2s-.7-.7-1.2-.1c-.5.5 0 1.8 1.1 1.5c0 0 .3.3.3.7s-.4 1-.4 1.5s1.4 1.2 1.3-.1c0 0 1.1-1.4.5-2c0 0 .4-.6.8-.6s1.2-.5.8-1s-.8-1.1-1.9-.1c-1.2.9-1.3.2-1.3.2");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.a5pnjz2fv {
  stop-color: var(--svg-color--961307, #961307);
  stop-opacity: 0.2;
}

.agmzqnb8d {
  stop-color: var(--svg-color--71b612, #71b612);
}

.aljrg8j_w {
  fill: var(--svg-color--95110a, #95110a);
  d: path("M122.542 101.604c-1.9.1-4.3 1.2-4.7 2.1c.8.3 3.6 1.3 7.3.3l1 1.1c-.1-.2.3-3.8-3.6-3.5");
}

.arzb1snoy {
  stop-color: var(--svg-color--3ed8bb, #3ed8bb);
}

.as5eecbtw {
  d: path("M-107.6-142.9c-.7 0-.9.7-1 1.3c-.1.4-.3 1.1.4 1.1c.6 0 1.2-2 .6-2.4");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.b4hsl0-lx {
  d: path("M-118.2-215.2v.7c-4.1 2.4 4.3 3.3 1.7 6.5c2.5-.4 2.1 1.5 1.5 3c.1 0 .2-.1.3-.1c1.2-.1 1.2.5 2.1.8c.3.1 1.3.1 1.5.3c.5.4.2 1.4.5 1.8c.1.1.2.2.4.3c.2-.4.3-.4.6-1c.6-.9 1.7-2.3 2.8-1.5c.9.7.4 2.1.4 3.3c.8-.2 1.4-.5 2.4-.5c.3.3.5.6.7.8c.9-1.9 2.3-2.9 2.9.1c.1.4.2.8.2 1.1c.8-.3 1.6-.6 2.5-.5c.1-.2.1-.4.1-.6c.4-2.6 6.3-5.7 2.2-7.6c-8.2-3-16.5-5.3-22.6-7.1c-.2.1-.2.2-.2.2");
}

.b5fyytdrw {
  fill: var(--svg-color--fff, #fff);
  d: path("M-98.9-133.9c0-.1-.1-.1-.2-.1c-.1.3-.6 1.9-.1 1.9l.3-.9c.1-.3.3-.4.3-.8c-.1-.1-.2-.1-.3-.1");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.b8nallb2t {
  stop-color: var(--svg-color--a6261a, #a6261a);
  stop-opacity: 0.5;
}

.b8ob7j9jt {
  stop-color: var(--svg-color--d8caaf, #d8caaf);
}

.b8pcjzubi {
  fill: var(--svg-color--fbb316, #fbb316);
  d: path("M-112.2-150.7c-.5.2-.9 0-.9-.5h-.1c0 .6.6 1 1.2.8c.5-.2.7-.9.7-1.4c-.1.5-.5.9-.9 1.1");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.bb9eckbmg {
  d: path("M-98-133.6c.1-.5-.5-.7-.9-.7c-.6.1-.5.8-.6 1.2s-.3.9-.1 1.4c.1.4.5.8.7 1.2c.2.5.1 1 .2 1.5s.6.7 1.1.5c.8-.4.6-2.1.3-2.7c-.2-.4-.4-.6-.5-1c-.1-.3.1-1.2-.1-1.4");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.bdf6sh3nd {
  fill: var(--svg-color--660300, #660300);
  d: path("M254.5 272.5c-8.4 18.8-19 27.5-19 27.5c.4-3.7.7-9.2.9-13.6c-1 1-2.1 2-3.3 2.8c0 0 .1-2 .1-5.4c-2.5 19-6.5 31.3-6.5 31.3s22-12.1 27.8-42.6");
  opacity: var(--svg-opacity--0-4, 0.4);
}

.bey1ynbnr {
  fill: var(--svg-color--4a0100, #4a0100);
  d: path("M143.513 278.722c.4.2.6.4.6.4c-.1-.1-.3-.3-.6-.4m0 0c-2.3-1.4-10.4-5.6-18.4 2.7c0 0 9 1.4 13.6-3.1l1.8.7c.1-.1 1.8-.7 3-.3");
}

.bli_3eiwt {
  d: path("M167 87.6c5.3-.5 9.5-1.1 12.8-1.7c.1-.8.1-1.5.1-2.3c0-2.4-.4-4.7-1-6.9c-16.4 3.5-35.9 1.4-42.8.4c-1 4.1-1 7.1-1 7.1s9.1 5.3 31.9 3.4");
}

.bmqf4y-5r {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0.4;
}

.bn854uv_r {
  stop-color: var(--svg-color--2cab98, #2cab98);
}

.bnoblqesl {
  fill: var(--svg-color--020202, #020202);
  d: path("M140.2 86c-.1-.8-.2-1.7-.2-2.5c0-7.8 6.3-14 14-14s14 6.3 14 14c0 1.4-.2 2.8-.6 4c-.2 0-.4.1-.5.1c-13.2 1.1-21.8-.3-26.7-1.6");
}

.bnvdhuywe {
  fill: var(--svg-color--fbb316, #fbb316);
  d: path("M-117.4-140.5c-.2-.2-.3-.3-.3-.5c-.1.3 0 .6.3.8c.6.5 2.1.6 2.3-.4v-.3c-.3.9-1.8.8-2.3.4");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.byj4sdb9t {
  stop-color: var(--svg-color--ab2015, #ab2015);
  stop-opacity: 0.5;
}

.c0dl7kb3q {
  fill: var(--svg-color--fff, #fff);
  d: path("M130.9 285.9s7.8.7 11.2-4.3c0 0 2.9 8.9-11.2 4.3");
  opacity: var(--svg-opacity--0-15, 0.15);
}

.c1hc9s8ws {
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M141.4 219.2s7.8-.1 8.4-6.5c.6-6.6-3.5-44.4-3.5-44.4s-.3-9.3-12.2-9.3c-11.8 0-12.2 9.3-12.2 9.3s-4 37.8-3.7 44.4c.4 6.5 8.5 6.5 8.5 6.5z");
}

.c9cd37btj {
  stop-color: var(--svg-color--b82c1e, #b82c1e);
  stop-opacity: 0.8;
}

.ca_bq02_r {
  fill: var(--svg-color--fbb316, #fbb316);
  d: path("M-100.3-146.6c-.5.3-.8-.1-.9-.5v.1c-.1.6.3 1.1.9.8c.5-.2.7-.8.7-1.3v-.2c-.1.4-.3.9-.7 1.1");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.cd4bz3_pa {
  stop-color: var(--svg-color--6caf11, #6caf11);
}

.cha1nn1rs {
  d: path("M-168.9-162.1c0 .7-8.1 12.7-9 19.8c-.7 5.2-1.3 17.1 9.9 17.1s9.3-16.1 9.3-16.1s-.6-9.1-10.2-20.8v-.2z");
}

.ck85svbhu {
  fill: var(--svg-color--af2419, #af2419);
  d: path("M126.042 104.904s.4-3.6-3.5-3.4c-3.8.3-10 4.3 3.5 3.4");
}

.clpby4b5o {
  cx: 157.1px;
  cy: 77.9px;
  r: 4.3px;
  fill: var(--svg-color--fff, #fff);
}

.cm4w8497n {
  fill: var(--svg-color--3fb5ba, #3fb5ba);
  d: path("M127.7 210.2c-.1-.1-.2-.3-.3-.5c-.1-.1-.1-.3-.2-.4c-.1.3 0 .6.2.8c.1.1.3.2.3.5v.1z");
}

.colkp1rlr {
  fill: var(--svg-color--fbb316, #fbb316);
  d: path("M-105.3-147.7c-.4.5-.8.8-1.4.7c-.4-.1-.7-.2-.7-.5c-.1.4.1.8.7.8c.6.1 1-.2 1.4-.7c.2-.3.4-.8.3-1.1c-.1.3-.2.6-.3.8");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.crbw4tbed {
  fill: var(--svg-color--fff, #fff);
  d: path("M-99.4-116.9c-.5-.3-1.9 1.3-1.3 1.6c.3-.2.5-.4.7-.7c.1-.2.2-.3.4-.5c0-.1.1-.3.2-.4");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.cua_02b8g {
  stop-color: var(--svg-color--52840a, #52840a);
}

.d_59i2lmq {
  stop-color: var(--svg-color--3fb5ba, #3fb5ba);
}

.d_6e_9rzc {
  d: path("M158.6 368.1c-12.5 0-23.8.7-32.5 1.8c-8.7-1.1-20.1-1.8-32.5-1.8c-27.4 0-49.6 3.2-49.6 7.1s22.2 7.1 49.6 7.1c12.5 0 23.8-.6 32.5-1.8c8.7 1.1 20.1 1.8 32.5 1.8c27.4 0 49.6-3.2 49.6-7.1c-.1-3.9-22.2-7.1-49.6-7.1");
  opacity: var(--svg-opacity--0-46, 0.46);
}

.d0fa7cc3k {
  d: path("M161.3 54c25.6-1.7 31.4 26.7 31.4 26.7s-2.8 5-25.6 6.9s-31.9-3.5-31.9-3.5s.5-28.4 26.1-30.1m5.5 32.5c21.3-1.8 24-6.4 24-6.4s-5.4-26.6-29.4-25S137 83.3 137 83.3s8.5 5 29.8 3.2");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.d2kcls_hr {
  stop-color: var(--svg-color--6aac10, #6aac10);
}

.d41pdjt1d {
  stop-color: var(--svg-color--7e647b, #7e647b);
  stop-opacity: 0.975;
}

.d6xb94hnb {
  stop-color: var(--svg-color--dbceb5, #dbceb5);
}

.d8_7kkbnl {
  d: path("M147.1 186.4c0 .2 0 .4.1.6c-1.3-.6-2.6-.9-3.7-.4c-2.4 1.2-4.2 3.1-9.2 1.6s-5.4.8-8.9-.5c-1.6-.5-3-2.3-4.1-4.1c-.3 4.5-.5 9.2-.7 13.2c1.8-.7 4.2-1.3 6.5-.4c4.4 1.6 8.8 2.7 12.7 1c3-1.4 5.6-1.9 7.9-.7c-.2-3.4-.4-6.8-.6-10.3");
}

.d83i_4z2s {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M84.6-100.9c-.5 15.4-23.8 69.4-66.1 71.8c-46.4 2.6-63.7-37.6-72.1-56.2c0 0-3.6-8.7.7-12.2c1.4-1.2 2.5-1.8 3.8-2c0 0-8.7-1.9-6.7 16.6c.7 6.6 1.7 14.7 4.5 23.4c13.9 24.7 37.4 43.1 73.6 42.1c17-.5 34.4-14.2 47.6-31.3C80-65.6 89.3-86.5 84.6-100.9");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.ddy6pbelv {
  fill: var(--svg-color--3fb5ba, #3fb5ba);
  d: path("M-112.2-114.2c-.4.9-1.9 1.5-2.2.2v.4c.3 1.3 1.8.7 2.2-.2c.1-.2.1-.4.1-.5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.dl0d0giuy {
  d: path("M144.1 61.5c3.4-1.7 7.1-2.7 11.1-2.7c13.6 0 24.8 11.1 24.8 24.8c0 .8-.1 1.5-.1 2.3c-3.4.7-7.6 1.3-12.8 1.7c-22.8 1.9-31.9-3.5-31.9-3.5s.2-13.7 8.9-22.6");
}

.dosrsbbxv {
  stop-color: var(--svg-color--fbb316, #fbb316);
}

.dox2pwbvl {
  fill-opacity: var(--svg-fill-opacity--0-7, 0.7);
  d: path("M-168.2-138.2c8.3 0 6.9-9.8 6.9-9.8s-.5-7-7.6-14.1c0 0-5.5 9.5-6.6 13.5c-.5 3.1-.9 10.4 7.3 10.4");
}

.dx0utn0co {
  d: path("M-111.3-116.9c-.7-.2-.8 1.6.3 1.4c.4-.1.6-.5.5-.9c-.1-.3-.5-.5-.8-.5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.dy0c9xbto {
  stop-color: var(--svg-color--463844, #463844);
  stop-opacity: 0.92;
}

.dy58n2b9u {
  fill: var(--svg-color--e04c89, #e04c89);
  d: path("m173.609 165.495l-.5.5c2.2 2.6 4.7 4.8 6.7 6.4c.2-.2.3-.4.4-.5c-2-1.5-4.5-3.7-6.6-6.4m20.6-54.8c.2.1.4.3.6.4c1-1.6 2.2-3.7 3-6l-.6-.3c-.8 2.3-1.9 4.4-3 5.9m-13.1.7c.2-.1.4-.2.7-.3c-.2-2.5-.5-4.9-.7-6.8c-.2.1-.4.1-.7.2c.2 2 .5 4.5.7 6.9m7.5 31.8l-.3.6c3.6 2.4 6 3.4 7.8 3.7l.3-.6c-1.7-.3-4.2-1.3-7.8-3.7m-33.5-23.6c.2-.1.4-.1.7-.2l-.8-9.6c-.2.1-.5.1-.7.1zm-12.4 2c.2-.1.5-.1.7-.1l-.9-10c-.2 0-.5.1-.7.1zm18.8 55.2c-.2.2-.4.3-.6.4c1.1 2.8 2.8 6.1 5.5 8.9c.2-.2.4-.3.5-.4c-2.7-2.8-4.4-6.2-5.4-8.9m20.6-22.4c-.2.2-.3.4-.4.6c1.5 1.9 3.7 4.4 6.6 6.2c.1-.2.3-.4.4-.6c-2.9-1.8-5.2-4.3-6.6-6.2m-13.4-38.3c.2-.1.4-.2.7-.2l-.4-8.6c-.2.1-.5.1-.7.2zm-41.4 6.9l-.4-10.1c-.2 0-.5 0-.7.1l.4 10.1c.2-.1.5-.1.7-.1m69.2-.8c-.1.2-.1.5-.2.7c3.9-.5 6.3-2 7.8-3.7v-1c-1.3 1.7-3.5 3.4-7.6 4m-3 9.8c-.1.2-.1.4-.3.6c1.5.8 4.4 1.8 8.2 1.5c.1-.2.1-.5.2-.7c-3.8.4-6.6-.7-8.1-1.4m-112.1-11.3c.3.1.5.1.7.1c-.8-3-1.1-5.8-1.3-8.3c-.2 0-.5-.1-.7-.1c.2 2.6.5 5.4 1.3 8.3m-17.8-2.6c.3-.1.5-.1.8-.1c-1.2-1.6-2.5-4.1-3-7.7h-.7c.5 3.6 1.7 6.1 2.9 7.8m15.3 62.3c.2.2.4.3.5.5c1.9-2.5 4.3-5.2 7.1-7.2c-.2-.2-.4-.3-.5-.5c-2.8 2.1-5.2 4.8-7.1 7.2m20.4 1.9l-.6-.3c-1.6 2.4-3.4 5.5-5.1 9l.6.3c1.7-3.6 3.5-6.7 5.1-9m-.2-59.7h.6c-.6-2.6-1.3-5.9-1.7-9.3h-.7c.5 3.4 1.2 6.7 1.8 9.3m15.1 64.7c-.2-.1-.5-.1-.7-.1c-1.3 3.9-2.1 7.6-2.5 10.6c.2.1.4.1.7.2c.5-3.1 1.2-6.7 2.5-10.7m30-1.3c1.6 4.6 3.8 8.1 5.8 10.7l.6-.3c-2-2.5-4.3-6.1-5.8-10.6c-.2 0-.4.1-.6.2m-86.4-60.7c-3.1-.8-6.2-2.3-8.7-3.8c0 .3 0 .5-.1.8c2.5 1.5 5.6 3 8.7 3.7v-.7zm9.2 23.3l-.3-.6c-3.6 1.4-6.1 3.4-7.9 5.3l.3.6c1.8-1.9 4.3-3.9 7.9-5.3m47.5-25.4h.7l-1-9.8h-.7zm16.9 65.2h-.6c-.4 3.6-.7 7.9-.8 11.8h.7c.1-3.9.4-8.2.7-11.8m-71-53.5c-.1-.2-.2-.5-.3-.7c-2.1.2-4.8.8-8.2 2c.1.2.2.4.2.6c3.5-1.2 6.2-1.7 8.3-1.9m15.4 27.3c-.2-.2-.3-.4-.4-.6c-2.5 1-5.6 2.7-8.3 5.4c.2.2.3.4.4.6c2.8-2.7 5.9-4.4 8.3-5.4");
}

.dzpiiobrd {
  fill: var(--svg-color--920b04, #920b04);
  fill-opacity: var(--svg-fill-opacity--0-779, 0.779);
  d: path("M-175.6-142.4c-.7 5.2-1.5 20 9.7 20s9.3-16.1 9.3-16.1s-.2-12.6-12.3-23.7c-.2.8-5.7 12.7-6.7 19.8");
}

.e-j-hbant {
  d: path("M91.9 54.3c-26.4-1.8-32.4 27.5-32.4 27.5s2.9 5.2 26.4 7.1s32.8-3.6 32.8-3.6s-.5-29.3-26.8-31m-5.8 33.4c-21.9-1.8-24.6-6.6-24.6-6.6s5.6-27.4 30.2-25.7s25.1 29 25.1 29s-8.7 5.1-30.7 3.3");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.e6ar6bcaa {
  stop-color: var(--svg-color--ce4920, #ce4920);
}

.e84y0va9v {
  fill: var(--svg-color--fbb316, #fbb316);
  d: path("M-108.3-140.5c-.3 0-.4-.2-.5-.4c-.1.4 0 .7.5.7s1-1.2.9-1.9c0 .7-.4 1.6-.9 1.6");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.elza3oq2w {
  fill: var(--svg-color--3fb5ba, #3fb5ba);
  d: path("M-98.9-116.5c0 .4-.2.8-.4 1.1c-.2.4-.8.8-1.2.8s-.6-.3-.7-.5c-.1.5.2.9.7.9s1-.4 1.2-.8c.4-.6.5-1 .4-1.5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.enrb6v0wr {
  d: path("M129.2 197.1C94 195.8 73.3 175.9 62 158.8c14 24.3 37.3 42.3 73.1 41.3c32.4-.8 66.8-50.5 68.9-78.5c-7 26.4-29.7 77.2-74.8 75.5");
}

.eyxpksb8d {
  fill: var(--svg-color--ad1813, #ad1813);
  d: path("M119.7 71.3S114 46.5 88 46.5S56.3 81.7 56.3 81.7s0 20.3 24.8 25c0 0-12.1-4.4-18.4-13.8c0 0 6 4.8 20.3 5.5c0 0-22.2-4.8-25.3-16.6c0 0 5.8-32.4 30.4-33.3c24.7-1 31.6 22.8 31.6 22.8");
}

.f-c80ro0i {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0.7;
}

.f7d6g6xrk {
  d: path("M-111.8-219.5c.4.1.8.2 1.2.2c.1-1.1-.9-1.6-1.1-2.9c-.2-1 .5-1.5.6-2.4c.1-1.3-.1-1.1-.3-2.1c-.1-.2-.1-.4-.2-.6c-1.4-.2-2.8-.2-4.2-.3c-.1.1-.1.2-.1.3c-.2 1.5 1.2 1.8 1.4 3.1c.2 1.1-.4 1.7-.7 2.5c1.5-.1 3 1 3.4 2.2");
}

.f879uyr1i {
  stop-color: var(--svg-color--423540, #423540);
  stop-opacity: 0.9;
}

.f94ycccrc {
  d: path("M-122.4-231.2c-.4-.3-.7-.5-1.1-.6l.2.4c1 2.2.9 3.1.9 5.5c0 1 .4 1.9.3 2.8s-.9 1.6-1 2.4v.1c.1 0 .1 0 .1-.1c1.7-.5 2.5 2.1 4.4 1.6c.2-.1.3-.1.5-.2c-.3-.5-.5-1-.8-1.6c-.9-2.6 1-3.7 1-6.2c0-.2 0-.3-.1-.5c-.6-.1-1.2-.2-1.8-.4c-.8-.8-1.6-2.4-2.6-3.2");
}

.flt-q6b2k {
  fill: var(--svg-color--ad1813, #ad1813);
  d: path("m134.1 83.5l.5.6s-.5-29.7 27-31.1s31.7 27.5 31.7 27.5s-.8 7.5-27 8.9c-16.4.9-24.6-1.4-28.6-3.3c-2.5-.8-2.6 1.1-2.6 1.1c8.1 7.8 26.7 10.3 26.7 10.3c-15.3.8-24.4-4.7-24.4-4.7c5.2 8.9 19.2 12.4 19.2 12.4c-19.8-.2-24.8-17.7-24.8-17.7z");
}

.fs4byuhds {
  d: path("M-98.6-126.9c-.1-.2-.1-.5-.1-.7c-.1-.5-.9-.3-1.1-.1c-.3.3-.6.8-.5 1.2c.2.8 1.4 1.7 2.2 1.4c.5-.2.5-.8.1-1.1c-.3-.2-.7-.4-.7-.8");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.fvh01-dan {
  fill: var(--svg-color--ad1813, #ad1813);
  d: path("M134.2 70.5s5.5-24.1 30.8-24.1s30.8 34.2 30.8 34.2s0 19.7-24.1 24.2c0 0 11.7-4.2 17.8-13.4c0 0-5.8 4.7-19.7 5.3c0 0 21.6-4.7 24.5-16.1c0 0-5.6-31.4-29.5-32.3c-23.9-.8-30.6 22.2-30.6 22.2");
}

.gn1rebc9e {
  stop-color: var(--svg-color--710300, #710300);
  stop-opacity: 0.91;
}

.gssf6rp5q {
  stop-color: var(--svg-color--644f61, #644f61);
  stop-opacity: 0.957;
}

.gwvhz2blz {
  cx: 95.5px;
  cy: 77.3px;
  r: 4.3px;
  fill: var(--svg-color--fff, #fff);
}

.h-1xy4lyx {
  stop-color: var(--svg-color--e3c091, #e3c091);
}

.h14skgbgp {
  d: path("M120.5 113.3c4.6-.2 9.2-.5 14-.9c2-1 3.8-2.2 4.7-3.6c1.8-2.9-.1-6.2-1.1-7.7c.9 1.7.6 4.8-1.4 5.7c-2.4 1.1-15.5 1.9-19.1-.3c-3.6-2.1-1.2-5.7-1.2-5.7c-4.7 6.9-.4 10.6 4.1 12.5");
}

.h2wr6dozo {
  stop-color: var(--svg-color--f6d62c, #f6d62c);
}

.h90xyg1im {
  d: path("M144 204.7c2 .2 3.3.2 4.1.1c-.1-1.8-.2-4-.3-6.5c-.7 0-1.4 0-1.9-.1c-1-.1-2.9.4-3.9.8c-1 .5-2 .4-3.2.2s-1.5-.7-3.1-.1c-1.7.6-3.3.8-3.3.8s-.4-.2-1.1-.1s-2.4-.1-2.4-.1l-2.2.2c-1.8.9-5.1.3-6.3.1c-.1 1.1-.1 2.2-.2 3.1c3.4-.5 5.2 1.5 5.2 1.5c3.1-1 4.9.4 4.9.4c4.5-1.3 9.4-.6 13.7-.3");
}

.hdm-w8b2j {
  stop-color: var(--svg-color--f9f7f3, #f9f7f3);
}

.he0m7tite {
  d: path("M147.5 194.7c.1.6.1 1.2.1 1.8c-2.4-1.2-4.9-.6-7.9.7c-3.9 1.8-8.3.6-12.7-1c-2.3-.9-4.8-.3-6.5.4c-.2 4-.4 7.5-.5 9.7c1.1.5 2.7.8 4.4.2c0 0 4.2 1.2 6.3.9c0 0 .8-.2 2 .4s2.7.6 3.5.1c0 0 2.5.1 3.4-.5c0 0 1.6-.1 2.2-.5c0 0 2.4-.1 3.7-1.3c0 0 1.3 0 2.6-.1c-.2-2.4-.4-6.3-.6-10.8");
}

.he8awtrxj {
  d: path("M240.3 198s-10.4-24-18.9-60.9c-2.6 13.6-8 46.8-5.2 66.8c3.5 25.7 13.4 131-32.4 147.1c0 0-13.8 2.2-31.4-17.7c-17.5-19.9-41.3-43.6-41.3-43.6l12-5.3s6.2 8.2 18.7 4.4c0 0-8.2 1.5-14-4.7c0 0 8.5 2.9 14-4.1c0 0 3.8 1.2 2.7 3.8c0 0 4.4-3.5 1.2-7.9c0 0 24.5-21.3 14.6-45.6l-7-9.4s5.9-5 6.2-6.4c.3-1.5-1.8-16.1-1.8-16.1s17.6-17.3 29.9-36.3c-13.4 20-33.2 37.4-52.3 37.9c-43.6 1.2-68.7-25.8-81-57.9H54l.3.9c2.1 6 15.4 40.8 47.6 55.8l-18.7 4.1s66.8 19.6 69.7 35.1s-107.2 40.6-140.7 14.6c-10.6-8.2-10.8-23-9.8-35.5c-4.5 17.6-3.5 32 9.3 49.6c0 0 0 56 47.1 103.6c0 0 18.1 14.7 30.8-3.6c12.8-18.4 30.1-28.8 44.8-25s28.3 22.4 33.9 28.5s29 25.2 58.6-55.3c-.1.2 55.4-30.4 13.4-116.9");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.hi232obuj {
  d: path("M17 109.9s7.3-6.5 13.5-.5c0 0-5 1.3-4.5 4.4s4.7 4.2 4.7 4.2s-14.5 4.1-13.7-8.1");
}

.ho0x6fbwr {
  fill: var(--svg-color--ea6709, #ea6709);
  d: path("M128 220.6c6.8 4.8 6.1 3.8 12.7 5.3c-1-1-2.2-1.9-3.2-2.6c-.3.3-.1.9-.7.9c-1.7-.3-5-1.9-5.9-2.4c-.2-.2.1-1.1-.1-1.3c-1.8-.3-2.9-.1-2.9-.1c0 .2.1.2.1.2");
}

.hoxnxop8a {
  d: path("M73.2 158.4c11.2 16.3 28.9 31.6 58.1 30c26.9-1.5 46.1-23.9 56.7-43.9c-57.3-26.6-103 4.5-114.8 13.9");
}

.hwncey1bz {
  d: path("M142.5 235.4c-.2-.8.3-2 .4-2.8c.4-2.6 2.1-3.2 1.8-6.8c-8.1-3-16.1-6-22.1-7.8l.1.1v.7c-4.1 2.4 4.3 3.3 1.7 6.5c3.2-.4 1.6 2.7 1.1 4c-.8 2.2-.8 3.6.1 5.6c1 2.2.9 3.1.9 5.5c0 1 .4 1.9.3 2.8s-.9 1.6-1 2.4c-.2 2.4 1.7 2 2.9 3.8c1.3 1.8.1 3.4-.6 5.2c-.5 1.2-1.9 4.2-.4 5.4c1.9 1.6 3.1-1 3.3-2.3c.2-1.2-.4-2.3-.4-3.3c0-1.5.5-1.8.9-3.1c.9-2.9-.6-3.3-1.5-5.8c-.9-2.6 1-3.7 1-6.2c0-1.6-2.4-4.9-.3-5.7c.1-.5-.4-1.6-.2-1.8c.3-.9.3-.6.8-1.4c.6-.9 1.7-2.3 2.8-1.5s.2 2.6.5 3.8s1.5 2 .9 3.8c-.4 1.1-2.1 1.6-2.3 2.8c-.2 1.5 1.2 1.8 1.4 3.1c.3 1.6-1.1 2.2-1 3.8c.1 1.4 1.4 2.2 1.2 3.7c1.6.7 2.6-.1 3.3-1.6c1-2.1-.5-2.3-.8-4.1c-.1-1 .5-1.5.6-2.4c.1-1.3-.1-1.1-.3-2.1c-.4-1.5-.7-2.8-.7-4.5c0-2.7 2.6-7 3.5-2.6c.4 1.6.1 2.5.8 4.2c.6 1.6.5 2.5.5 4.3c1.9 1.1 2.7-2 2.3-3.5c-.5-1-1.3-1.4-1.5-2.2");
  opacity: var(--svg-opacity--0-4, 0.4);
}

.i6r9q5bvb {
  stop-color: var(--svg-color--51414f, #51414f);
  stop-opacity: 0.939;
}

.iamfvu8eu {
  d: path("M124.9 0c-7.6 0-13.8 11.6-14.6 22.5c0 0 1.5 3.9 15.1 3.9c12.1 0 14.1-3.9 14.1-3.9c-.8-10.9-7.1-22.5-14.6-22.5");
}

.iogt4f9jv {
  stop-opacity: 0.448;
}

.ipvviw_kz {
  stop-color: var(--svg-color--961307, #961307);
  stop-opacity: 0.214;
}

.iqihhm3xx {
  stop-color: var(--svg-color--b2251a, #b2251a);
  stop-opacity: 0.069;
}

.j10joqrqo {
  stop-color: var(--svg-color--b32000, #b32000);
}

.j65_oobtf {
  d: path("M68.8 159.2s22.7 34.8 61.6 32.1s58.6-43 58.6-43s-15.7 49.5-60.5 49.8c-44.9.3-59.7-38.9-59.7-38.9");
}

.j8j3z8b3o {
  fill: var(--svg-color--cb9257, #cb9257);
  d: path("M-129.302-208s.1 0 0 0l.1-6.8l-.1-1.1zm4.5 1.4l.1-8.3h-.1zm-2 .1h.6v-8.4h-.6zm2.9-.3c.1-.1.2-.1.3-.1v-8h-.3zm-4.9 0l.1-8.1h-.1zm.9 0c.1 0 .2.1.3.1v-8.1h-.3v8.3zm2.1.3l.1-8.4h-.1z");
}

.j8u17yhai {
  stop-color: var(--svg-color--81c819, #81c819);
}

.j8wmvbblq {
  stop-color: var(--svg-color--e04c89, #e04c89);
}

.jc_wq3b0v {
  fill: var(--svg-color--6caf11, #6caf11);
  d: path("M-98.1-125.1c-.8.4-2-.6-2.2-1.4v.4c.2.8 1.4 1.7 2.2 1.4c.3-.2.4-.5.4-.8c-.1.2-.3.3-.4.4");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.jhk4c4bjk {
  fill: var(--svg-color--ad1813, #ad1813);
  d: path("m119.8 84.7l-.5.7s.5-30.6-27.8-32c-28.3-1.5-32.7 28.3-32.7 28.3s.8 7.7 27.8 9.2c16.9.9 25.4-1.5 29.4-3.4c2.6-.8 2.6 1.1 2.6 1.1c-8.4 8.1-27.5 10.6-27.5 10.6c15.8.8 25.1-4.8 25.1-4.8c-5.2 9.1-19.7 12.6-19.7 12.6c20.4-.2 25.6-18.2 25.6-18.2z");
}

.jhwk3o8kq {
  d: path("M71.9 119.2s61.6 12.7 107-6.9c0 0 13.7-6.9 18 1.1s-19.3 72.5-65.6 75c-46.3 2.6-63.7-37.5-72-56.2c0 0-3.6-8.7.7-12.2c3.1-2.6 4.6-2.3 11.9-.8");
}

.joem90b-n {
  stop-color: var(--svg-color--961307, #961307);
  stop-opacity: 0.3;
}

.jq2w2ihje {
  fill: var(--svg-color--fff, #fff);
  d: path("M-113.9-117.3s-.8 1.2-.3 1.1c.3-.1.8-1.1.3-1.1m-.3 3c.3.3.8.4 1.1.2c.2-.1.3-.4.5-.4c.3-.1.2.2.1.4c-.2.4-.5.6-.9.7s-.9-.1-.8-.6");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k5xovztmq {
  fill: var(--svg-color--cb9257, #cb9257);
  d: path("M-124-214.8v7.2c0 .5-1.5.9-3.4.9c-.7 0-.8-.4-1.3-.5c.6.2 1.1.8 2.3.8c1.9 0 3.4-.4 3.4-.9v-7.5z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.k9q_m2sdz {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0.339;
}

.kakqz1q1n {
  fill: var(--svg-color--fff, #fff);
  d: path("M-103.3-123.2c-.4-.2-.6 1.5-.5 1.8c.2 0 .4-.7.5-.9s.5-.5.4-.8c-.1-.1-.3-.2-.4-.1");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.kefn7j15c {
  stop-color: var(--svg-color--faf8f4, #faf8f4);
}

.kl3bj60_y {
  fill: var(--svg-color--7f1e0b, #7f1e0b);
  d: path("M225.8 113.8c.5-3.1-4.5-4.4-4.5-4.4c6.3-6 13.5.5 13.5.5l.1.6c-2.7-.7-9.5-1.6-8.4 8.1c-2.9.1-5.5-.7-5.5-.7s4.3-1.1 4.8-4.1");
}

.kpdw4er0f {
  fill: var(--svg-color--3fb5ba, #3fb5ba);
  d: path("M-111.1-115.6c-.5.1-.7-.2-.8-.6c-.1.5.2 1 .8.9c.4-.1.6-.5.5-.8c-.1.3-.2.5-.5.5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.krnlykzva {
  d: path("M-98.9-116.8c-.2-.5-.9-.4-1.3-.1s-.8.9-.9 1.4s.2.9.7.9s1-.4 1.2-.8c.3-.5.4-1 .3-1.4");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.krq1wfbqn {
  stop-color: var(--svg-color--c7392e, #c7392e);
}

.ksgr-sjui {
  stop-color: var(--svg-color--fefdfc, #fefdfc);
}

.kvdgcfbzw {
  stop-color: var(--svg-color--b3174b, #b3174b);
}

.l11b221hb {
  fill: var(--svg-color--fbb316, #fbb316);
  d: path("M-97.1-143.6c-.1.5-.5.8-.8 1c-.8.3-2.1-.4-2.2-1.2v.2c0 1 1.4 1.7 2.2 1.4c.5-.2.9-.8.8-1.4q0 .15 0 0");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.l5v4ro8da {
  stop-color: var(--svg-color--b11a0a, #b11a0a);
}

.lhlrr7b_a {
  stop-color: var(--svg-color--e6e7e8, #e6e7e8);
}

.lniqdljbz {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M66-105.2s5.1-2.6 10-2.8c-3.4-.3-8-.1-12.7 2.2c-8.1 3.9-57.8 12.6-97.7 8.6c17.2 2.5 64 7.6 100.4-8");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.lo3nw-btp {
  stop-color: var(--svg-color--f1ece2, #f1ece2);
}

.ltd7azb0q {
  stop-color: var(--svg-color--7a0400, #7a0400);
  stop-opacity: 0;
}

.lx9s9rb_k {
  d: path("M192.6 80.7s-5.8-28.4-31.4-26.7s-26.1 30.2-26.1 30.2s9.1 5.3 31.9 3.5c22.8-2 25.6-7 25.6-7");
}

.m1kpl7blk {
  fill: var(--svg-color--6caf11, #6caf11);
  d: path("M-102.7-121.5c-.1.6-.2.9-.9.8c-.4 0-.5-.4-.5-.7c-.1.5 0 1 .5 1c.6.1.8-.3.9-.8c0-.4.4-1 .3-1.4c-.1.5-.3.9-.3 1.1");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.m50f9ybxw {
  fill: var(--svg-color--fbb316, #fbb316);
  d: path("M-110.99-160.241c-.7.8-2.1 0-2.9-.1v.4c.8.1 2.1.8 2.8 0c.2-.2.2-.4.2-.6c0 .2 0 .2-.1.3m-4.4.8c.1-.2-.1-.6-.2-1v.1c0 .2.1.6.2.9m1.2.6c-.2.1-.6.1-.7.2c-.2.3-.1.6-.3.9c-.4.5-1.1.2-1.2-.3v.3c.1.6.8.9 1.2.4c.3-.3.1-.6.3-.9c.1-.1.6-.1.7-.2c.4-.3.5-.8.5-1.2c-.1.3-.3.6-.5.8");
}

.m60tnh72q {
  stop-color: var(--svg-color--cebc99, #cebc99);
}

.m8ieighnv {
  stop-color: var(--svg-color--64a10f, #64a10f);
}

.mh2d8vb3b {
  fill: var(--svg-color--fff, #fff);
  d: path("M52.8 130.9s-7.5-20.4 9.3-18.7s63 5.3 96.9-1.7c34.1-6.9 36.2-7.7 42.3.4c0 0-6.4-7.1-18.1-3.3c-11.8 3.9-59.4 16-120.9 6.9c0 .1-12-1.8-9.5 16.4");
  opacity: var(--svg-opacity--0-25, 0.25);
}

.mmamd3dnx {
  stop-color: var(--svg-color--f6d60e, #f6d60e);
}

.mpm03gbpd {
  fill: var(--svg-color--fff, #fff);
  d: path("M-117.4-127.1c-.3-.4-1.6.8-.9 1.4c.5.5.3-.3.4-.6c.1-.2.6-.7.5-.8m-.2 2.4c.1-.2.3-.3.4 0c.1.2-.2.4-.3.5c-.1.2-.3.3-.3.5c-.1.2.1.5-.1.7c-.4.5-.5-.4-.4-.6c.2-.5.7-.6.7-1.1");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.mrugtqc0j {
  stop-color: var(--svg-color--2b0011, #2b0011);
}

.mtl_dn34k {
  d: path("M131.2 188.4c26.9-1.5 46.1-23.9 56.7-43.9c-2.4-1.2-4.8-2.2-7.2-3.1c.1 2-.3 3.9-1.9 4.5c-2.4.8-2.8-1.3-3.7 1.8c-.8 2.4-1.6 1.1-3.6 1.7c-1.9.5-1.3 2.1-1.2 3.6c.2 4-.2 8.4-5 8.4c-1.9 0-3.7-1.2-5.6-1c-.8.1-1 .1-1.6.6c-.7.5-1.1 2-1.8 2.1c-1.2.1-1.8-2.8-3.4-1.3c-1.4 1.3.6 4.2-1.9 4.8c-1.8.5-2.9-1.8-4.8-1.3c-1.8.5-1.2 2.6-1.3 4.3c-.2 2.6-1 2.7-3.4 1.9c-1-.4-1.3-.5-2.2-.4s-1.8.6-2.8 0c-1.2-.7-1.1-2.1-2.2-3c-.8-.7-3.3-2.3-4.2-1.3c-.8.8.4 4 .4 5.2c-.1 1.4.8 4.8-.5 5.4c-.9.4-3.8-.2-4.5-.8c-1.3-1.1-1.6-3.5-2.9-4.8c-1.2-1.1-3.4-1.5-4.6-.3s0 3.7-.8 5.2c-.8 1.7-3 2.1-4.6 1.5c-1.8-.7-1.7-2.4-2.8-3.4c-1.5-1.4-4.3.1-5.7-1.2s-.4-3.4-1-5c-.2-.4-1-1.8-1.4-1.9c-1-.3-1.2.6-1.9.9c-.5.3-1.6.2-2.1.7c-.8.7-.4 1.4-.6 2.3c-.6 2.4-2.7 1.9-4.5 1.1c-1.6-.6-1.7-1.4-1.7-3.1c0-1.3-.1-3.5-1-4.5c-1-1.2-2.6-.4-4-.9c-.3-1.6 1.6-2.9.4-4.1c-.7-.7-1.5-.3-1.9-1.2c-.4-.7.2-1.9-.1-2.7c-.7-2.6-2.4-.4-3.4-1.7c-.2-.3-.2-.7-.1-1.2c-3.7 2.4-6.5 4.5-8.4 6c11.9 16.4 29.6 31.8 58.8 30.1");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mw9qzk31d {
  fill: var(--svg-color--fff, #fff);
  d: path("M-120.3-145.8s-.1-.1 0 0c.2.3.2.6.7.6c.1-.4-.4-.8-.8-.7");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.mztxbxjic {
  fill: var(--svg-color--ce4920, #ce4920);
  d: path("M107.3 25.3s1.4 7.4 18.2 7.4s16.2-7.9 16.2-7.9s-2.9 6-16 6s-18.4-5.5-18.4-5.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.n47-8nc8m {
  fill: var(--svg-color--fff, #fff);
  d: path("M-100.4-148.7c-.3.1-.6.8-.5 1.1c.3.2.9-1.1.5-1.1");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.n85kfev4w {
  d: path("M22.5 189.6s87.8 13.5 128 43.4c.1 0-61.6-24.1-128-43.4");
}

.n9t-n_dcx {
  d: path("M-111.1-217.1c0-1.1.5-2.6 1.1-3.5c-.4-.3-.8-.5-1.4-.5c-.8-.1-1.4.1-2.1.2c-.1.5-.1.9 0 1.3c.3 1.2 1.5 2 .9 3.8c-.4 1.1-2.1 1.6-2.3 2.8v.2c.8 0 1.1.3 1.8.5c.7.3 1.7.3 2.7.2c0-.1 0-.2-.1-.4c-.3-1.5-.6-2.9-.6-4.6");
}

.nabbi62sn {
  fill: var(--svg-color--fff, #fff);
  d: path("M-99.5-127.5c-.3.1-.9.7-.2.8c.1-.2.3-.3.4-.5s.1-.4-.2-.3");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.njg5--byg {
  d: path("M145.9 167.8c-1-8.8-11.6-8.7-11.6-8.7s-10.9-.2-11.9 8.7c-.4 3.1-.8 9.2-1.1 15.7c1.1 1.8 2.6 3.6 4.1 4.1c3.6 1.2 3.9-1.1 8.9.5c5 1.5 6.8-.5 9.2-1.6c1.1-.5 2.5-.2 3.7.4c-.5-7.8-.9-15.5-1.3-19.1");
}

.nky0xp0jv {
  fill: var(--svg-color--fff, #fff);
  d: path("M-107.9-142.6c-.4.1-.6 1-.5 1.3c.3.1.5-.4.5-.6s.3-.8 0-.7");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.nr7rmf-ng {
  fill: var(--svg-color--fff, #fff);
  d: path("M-105.4-134.2c-.2-.1-.1-.3.1-.4s.5-.1.7-.2c.4-.1.9-.2 1.2.1c-.4 0-.8 0-1.1.2c-.1 0-.8.6-.9.3");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.nz2b2-gnb {
  fill: var(--svg-color--fe980e, #fe980e);
  d: path("M-103-134.1c-.2.4-.8.6-1.2.7c-.6.1-.9.1-1.4-.2c-.2-.1-.4-.2-.5-.4c-.1.1-.1.2-.1.3c.1.2.3.4.5.5c.5.3.8.4 1.4.2c.4-.1 1-.3 1.2-.7c.2-.2.1-.3.1-.4");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.o3nlen8zw {
  fill: var(--svg-color--fe980e, #fe980e);
  d: path("M-117.2-130.4c-.5-.1-.7-.7-.7-1.2c-.1.7.2 1.4.7 1.6c.9.2 1.1-.9 1.1-1.7c-.1.7-.4 1.5-1.1 1.3");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.oate1m4sr {
  stop-color: var(--svg-color--59900c, #59900c);
}

.ol6stibsk {
  d: path("M-116.9-125.5c-.1-.2.1-.5.1-.7s.1-.6 0-.8c-.2-.5-.8-.6-1.2-.4c-1.2.7-.8 2.2.3 2.7c-.4.4-.8.8-.8 1.4c0 .5.4 1.1 1 1.2c.7.1.8-.7.5-1.1c-.2-.3-.2-.4.1-.7c.2-.2.4-.3.5-.6s-.1-.4-.3-.5s-.2-.2-.2-.5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.on-tyliru {
  stop-color: var(--svg-color--bf441e, #bf441e);
}

.ooo3xybde {
  fill: var(--svg-color--6e0301, #6e0301);
  d: path("M128.802 103.104c.4-.9 1.3-1.6 3.1-1.5s4.2 1.1 4.7 2c-1.5.1-5.6.5-7.8-.5");
}

.p_qts-b_r {
  stop-opacity: 0.3;
}

.p2j3rrbdy {
  stop-color: var(--svg-color--b11a0a, #b11a0a);
  stop-opacity: 0.25;
}

.p2s2y7xde {
  stop-color: var(--svg-color--96003a, #96003a);
}

.pf5ykbbgi {
  stop-color: var(--svg-color--7d002f, #7d002f);
}

.pgb0ecc4l {
  d: path("M94.9 122.3c-11.2-1-19.3-2.4-22-2.9c-.1 2.9.7 12.2 11 13.3c8.4.9 10.5-6 11-10.4");
}

.ph_a4lq_p {
  d: path("M-120.4-146.1c-.1.9-.2 1.8-.2 2.7c.2-.1.5-.1.7-.1c.2-.1.4-.2.5-.4c.2-.4.3-1 .2-1.4c-.3-.5-.7-.8-1.2-.8");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.pi06cccls {
  fill: var(--svg-color--cb9257, #cb9257);
  d: path("M-128.4-215.104v-.2c0-.4-.3-.7-.3-.7c-.7.2-1.2-.3-1.3-.8c-.1.6.4 1.4 1.3 1.2c0 .1.2.3.3.5m2.2-1.4c-.4 0-.8.6-.8.6c.1.1.1.1.1.2c.2-.1.4-.5.7-.5s1.1-.5.8-.9c-.1.4-.6.6-.8.6m-.6 1.2c-.1.7-.7 1.4-.7 1.4c.1 1.2-1.1.7-1.3.2v.3c0 .5 1.4 1.2 1.3-.1c0 0 .8-1.1.7-1.8");
}

.pj9f--b4l {
  fill: var(--svg-color--6caf11, #6caf11);
  d: path("m-118-124.3l.3-.3c-.7-.4-1.1-1.2-.9-2c-.5.8-.2 1.8.6 2.3m.4 2.2c-.5-.1-1-.7-1-1.2c0-.2.1-.3.1-.5c-.2.2-.3.5-.3.8c0 .5.4 1.1.9 1.2c.4.1.6-.2.6-.5c.1.2-.1.2-.3.2");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.pnjr8_b7e {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0.3;
}

.pufh1g2sv {
  d: path("M-113.1-116.1c.2-.5.3-1.1-.2-1.3c-.6-.3-1 .1-1.3.6c-.2.5-.4 1.2-.1 1.6c.1.2.3.3.3.5c.1.3 0 .6.1.8c.3 1.3 1.8.7 2.2-.2c.2-.5 0-.9-.4-1.1c-.4-.3-.8-.6-.6-.9");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.pxiy7oyva {
  d: path("M-160.1-141.6s-.2-5.4-4.8-12.8c3 6 3.2 10 3.2 10s1.7 14.5-8.4 14.5c-3.3 0-5.4-1.1-6.8-2.8c1.1 3.1 3.5 5.6 8.4 5.6c10.1.1 8.4-14.5 8.4-14.5");
}

.q4o0gep5w {
  stop-color: var(--svg-color--991000, #991000);
}

.q93vr20uh {
  stop-color: var(--svg-color--f28567, #f28567);
}

.qc116l8po {
  fill: var(--svg-color--fff, #fff);
  d: path("M140.5 95.2s21.7 9.9 43.7.3c.1 0-20 17.4-43.7-.3M66.7 61.7s9.2-12.6 23.6-12.2s21.3 9.3 24.4 14.2c-.1.1-20.7-25.6-48-2m74.1-.7s19-24.8 42.8-1.5c0-.1-21.1-17-42.8 1.5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.qcf_42l9r {
  d: path("M250.2 222.7c1.4 19.6.9 53.3-17.1 66.4c0 0 2.4-47.6-12.6-75.6c0 0 26.3 64.2-19 136.9c0 0-12.8 32.1-41.7 2.7c-28.9-29.5-67.5-14-67.5-14l14.9 2.1s-14.9 3.8-20.8 16.1c-5.8 12.1-34.4 11.7-68-53.2c6.2 19.4 17.9 43.8 40.2 66.3c0 0 18.1 14.7 30.8-3.6c12.8-18.4 30.1-28.8 44.8-25s28.3 22.4 33.9 28.5s29 25.2 58.6-55.3c.1.1 44.8-24.5 23.5-92.3");
}

.qh-v03bmu {
  d: path("M134.2 216.4h7.1s6.3-.1 6.8-6.2c.6-6.2-2.2-42-2.2-42s-.3-8.8-11.8-8.8h.1c-11.4 0-11.8 8.8-11.8 8.8s-2.5 35.8-2.2 42c.4 6.2 6.8 6.2 6.8 6.2z");
}

.qidcyvbrp {
  stop-color: var(--svg-color--9c1710, #9c1710);
}

.qjx2o_lyz {
  d: path("M73.2 158.4c11.2 16.3 28.9 31.6 58.1 30c26.9-1.5 46.1-23.9 56.7-43.9c-57.3-26.6-103 4.5-114.8 13.9m32.9 9.7c-17.8-16.3 13.2-30 18.2-29.2s8 27.7 8 27.7l.4-28.5s19.4-1.9 26.9 12.9s-35.7 33.4-53.5 17.1");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.qtbsoqboy {
  stop-color: var(--svg-color--ff5906, #ff5906);
}

.qu23p31xv {
  fill: var(--svg-color--fff, #fff);
  d: path("M-97.7-144.5c-.4-.4-1.9-.5-2 .3c-.2.6.7.2.9.1c.3-.2.8-.1 1.1-.4");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.qzac3ebvh {
  stop-color: var(--svg-color--a7a9ac, #a7a9ac);
}

.r_1h74b_y {
  stop-color: var(--svg-color--e6ddcc, #e6ddcc);
}

.r_3uws2px {
  fill: var(--svg-color--fff, #fff);
  d: path("M-111.4-116.6c-.4-.1-.3.4.1.3s.1-.4-.1-.3");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.r_52pwbii {
  fill: var(--svg-color--fff, #fff);
  d: path("M-129.1-217.3c-.2 0-.4-.1-.5 0c-.1.2.1.3.2.4s.4.2.4 0c.1-.1 0-.3-.1-.4m.7.6c.3-.1.6-.2 1-.4v-.1c.2-.1.4-.1.5-.2c.2-.1.3-.2.4-.3c.3-.2.8.2.4.4c-.4.1-.7.2-1 .4c-.4.1-.8.2-1.1.2m.2 1.6c0 .2-.5.9-.2.9c.2 0 .4-.7.2-.9");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.r-57a4b3t {
  fill: var(--svg-color--fbb040, #fbb040);
  d: path("M130.8 220.7c.2.1.1.3.1 1.3c1.4 1 3.8 2 6.3 2.5c.2.1.3-1 .4-.9c1 .7 2.1 1.5 3.1 2.5c0 0-8.7.8-12.9-5.5c0 0 1.2-.1 3.1.2z");
}

.r0gxasogg {
  d: path("M124.7 13.2s-69.2-6.6-87.1 89.6s-57.2 120.9-25.9 164c0 0 0 56 47.1 103.6c0 0 18.1 14.7 30.8-3.6c12.8-18.4 30.1-28.8 44.8-25s28.3 22.4 33.9 28.5s29 25.2 58.6-55.3c0 0 55.5-30.6 13.5-117.1c0 0-16.1-36.9-24.5-89.6c-8.5-52.5-34.9-94.3-91.2-95.1");
}

.rbbs3pn7c {
  fill: var(--svg-color--fff, #fff);
  d: path("M-99.6-111.9c-.4-.1-.5 1.5-.1 1.7s.4-.7.4-.9c0-.4-.2-.6-.5-.7");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ro5urobma {
  fill: var(--svg-color--250000, #250000);
  d: path("M110.8 138.9c11.8-3.7 25.7-5.8 41.1-4.3c3.2-7 2.3-12.5 1.7-14.6c-6.2 1.2-12.4 2.1-18.6 2.6c1.5 3.7-1.1 7.3-6.7 6.8c-5.3-.5-4.9-4.1-4.1-6.2c-6.3.2-12.3.2-17.9-.1c-3.1 9.9 2.2 14.4 4.5 15.8");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.rue-_yb9l {
  d: path("M-105.4-149.5c-1.1-.3-3.1 2.3-1.3 2.5c.6.1 1-.2 1.4-.7c.3-.4.4-1 .3-1.4c-.1-.1-.2-.4-.4-.4");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.rw744qbyj {
  fill: var(--svg-color--fe980e, #fe980e);
  d: path("M-97.7-128.6c-.4.2-1-.1-1.1-.5c-.1-.5 0-1-.2-1.5c-.2-.4-.5-.8-.7-1.2c-.2-.5 0-1 .1-1.4c0-.2 0-.5.1-.7c-.3.2-.2.7-.3 1c-.1.4-.3 1-.1 1.4c.1.4.5.8.7 1.2c.2.5.1 1 .2 1.5s.6.7 1.1.5c.2-.1.4-.3.5-.6q-.15.3-.3.3");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ry0sb8bor {
  fill: var(--svg-color--590d00, #590d00);
  d: path("M71.9 119.2s61.6 12.7 107-6.9c0 0 13.7-6.9 18 1.1s-19.3 72.5-65.6 75c-46.3 2.6-63.7-37.5-72-56.2c0 0-3.6-8.7.7-12.2c3.1-2.6 4.6-2.3 11.9-.8");
}

.s1lgr3b3s {
  fill: var(--svg-color--fff, #fff);
  d: path("M-117-141.9c-.2-.1-.4.1-.4.3c.3.1.4-.1.6-.2c.3-.1.5 0 .8-.1c.1-.6-1.1-.3-1.3 0");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.s9r2zub6m {
  fill: var(--svg-color--fff, #fff);
  d: path("M-105.6-149.3c-.4 0-1.4.7-1.3 1.2c.4 0 1.3-.9 1.3-1.2");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.sb6dfuivy {
  fill: var(--svg-color--af2419, #af2419);
  d: path("M128.402 104.904s-.4-3.6 3.5-3.4c3.8.3 10 4.3-3.5 3.4");
}

.sf3u6-8dg {
  stop-opacity: 0.03;
}

.skwexac4a {
  cx: 126.1px;
  cy: 375.1px;
  opacity: var(--svg-opacity--0-39, 0.39);
  rx: 90px;
  ry: 12.8px;
}

.sll_zg-uo {
  stop-opacity: 0.5;
}

.spvvurj_v {
  stop-color: var(--svg-color--ff8b6c, #ff8b6c);
}

.srwcfyr4x {
  fill-opacity: var(--svg-fill-opacity--0-7, 0.7);
  d: path("M134.1 216.4h6.4c6.4 0 7.7-4.4 7.7-6.8c-2.2 2.4-5.9 3.1-8 3.9c-2.8 1.2-5.3 1-6.7.7c-1.4-.2-1.5-1.1-6.1-.5c-2.4.3-5-1-7-2.2c.8 2.9 2.6 4.9 7.3 4.9z");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.sv656ewjo {
  cx: 164.6px;
  cy: 69.7px;
  r: 7.8px;
  fill: var(--svg-color--fff, #fff);
}

.sy6a77him {
  d: path("M130.4 135.1s2.2 16.1 1.4 28.4c0 0-1-22.3-5.5-27.2z");
  opacity: var(--svg-opacity--0-4, 0.4);
}

.t-uqshodi {
  stop-color: var(--svg-color--ce4920, #ce4920);
  stop-opacity: 0.3;
}

.t7nwvhbve {
  d: path("M-126.3-214.8h-3.4v6.7c0 .5 1.5 1.7 3.4 1.7s3.4-.4 3.4-.9v-7.5z");
}

.t7y383bis {
  fill: var(--svg-color--fff, #fff);
  d: path("M117.6 100s8.9-3.6 19.5 0c0 0-9.6-6.7-19.5 0");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.t89m0lbfi {
  fill: var(--svg-color--fff, #fff);
  d: path("M-115.2-159.1c-.2.1-.7.4-.4.6c.3 0 .5-.4.4-.6m0-1.9v.2c.3.2.5-.4.7-.4c.3-.1.8 0 1.1.1c.4.1.7.2 1 .3c.2 0 .4 0 .5.1c.2 0 .3.1.5.1v-.1c-.6-.4-1.3-.4-1.9-.6c-.5-.2-1.7-.4-1.8.4");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ti7gz-x3j {
  cx: 223.4px;
  cy: 112.5px;
  rx: 12.9px;
  ry: 10px;
}

.tk6kjuvmm {
  stop-color: var(--svg-color--361221, #361221);
}

.tmtgi_bwb {
  stop-color: var(--svg-color--8c1306, #8c1306);
}

.uaz5glfiq {
  fill: var(--svg-color--95110a, #95110a);
  d: path("M131.902 101.604c1.9.1 4.3 1.2 4.7 2.1c-.8.3-3.6 1.3-7.3.3l-1 1.1c.1-.2-.2-3.8 3.6-3.5");
}

.ufhb4tbas {
  stop-color: var(--svg-color--770501, #770501);
}

.uj44h2bgu {
  d: path("M95.4 284.5c58.4-8.8 71.5-38.3 64.8-54c-6.7-15.8-77.1-27.5-77.1-27.5s72.6 14.3 74.7 34.2c2.9 27.5-80.9 58.2-146.1 29.6c0 0 0 2.4.4 6.5c12.7 6.5 41.3 17.5 83.3 11.2");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.uo8qktbls {
  d: path("M-111.9-153.1c-.6.4-1.2 1-1.3 1.8c-.1.6.4.9.9.7s.9-.7 1-1.2c.1-.4 0-1.2-.6-1.1");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.upkhzxfvf {
  stop-color: var(--svg-color--ddc48c, #ddc48c);
}

.uq6gdfi3o {
  d: path("M59.6 81.8s6-29.3 32.4-27.5s26.9 31.1 26.9 31.1s-9.4 5.5-32.8 3.6c-23.6-2.1-26.5-7.2-26.5-7.2");
}

.us61mrb8y {
  fill: var(--svg-color--3fb5ba, #3fb5ba);
  d: path("M-99-109.3c-1 .6-1.3-1.2-1.3-1.8c0-.2.1-.4.1-.6q-.3.45-.3.9c-.1.6.3 2.4 1.3 1.8c.2-.1.3-.3.4-.5c0 .1-.1.2-.2.2");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.utq5d8b9h {
  fill: var(--svg-color--6e0301, #6e0301);
  d: path("M125.742 103.104c-.4-.9-1.3-1.6-3.1-1.5s-4.2 1.1-4.7 2c1.5.1 5.6.5 7.8-.5");
}

.uuhsu48rh {
  d: path("M-115.5-159.3c-.5.2-1 .6-.9 1.2s.8.9 1.2.4c.3-.3.1-.6.3-.9c.1-.1.6-.1.7-.2c.4-.4.6-.9.4-1.5c.8.1 2.2.8 2.9.1c.7-.8-.9-1.2-1.5-1.4c-.9-.2-1.9-.8-2.6-.1c-.3.3-.5.5-.6.9s.3 1.1.2 1.3c0 .1-.1.1-.1.1");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.uv7wtfbjk {
  cx: 28.5px;
  cy: 112.5px;
  rx: 12.9px;
  ry: 10px;
}

.v--cy9kie {
  d: path("M133.5 13.8c0 4.7-3.9 8.5-8.6 8.5c-4.8 0-8.6-3.8-8.6-8.5s3.9-11.7 8.6-11.7s8.6 7 8.6 11.7");
}

.v9u8nhb5n {
  stop-opacity: 0.8;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vgg3jibvp {
  d: path("M188 144.6c-5.2-2.4-10.3-4.4-15.2-5.9c0 .7 0 1.4-.1 2c-1.5.6-3.3-.1-4.8.8c2.8 4-2.5 3.5-5 3.7c-.4 2.5 1.9 3.3 2.3 5.4c.5 2.6-1 5.8-3.4 5.2c-2-.5-3.5-3.3-5.2-4.4c-3.4-2.4-4.3-1.6-4.9 1.5c-.5 2.9-.5 4.9-3.9 3.6c-2-.8-5.1-5.2-7.6-3.1c-2.2 1.8 1.2 8.5-1.6 9.9c-2.7 1.3-4-3.6-4.5-5c-1.2-3.7-4.5-4-6.9-.6c-1.7 2.3-1.1 11.5-6 9.4c-2.3-1-2.8-6-6-3.6c-2.3 1.7-1.3 8.3-5.4 8.3c-2 0-1.7-.9-2.3-2.5c-.3-.7-.4-1.7-.9-2.4c-.4-.6-1-.3-1.3-.7c-1.7-2.4-.4-5.3-1.9-7.5c-2.5-3.5-4.4.1-4.7 2.8c-.3 2.5-.1 6.9-3.8 5.3c-.1-1.7.7-3.5 0-5.1c-1-2.7-2.9-2-5.2-2.9c-.5-2.7 2.5-4.5 2.3-6.7c-.3-2.4-2.7-.4-4.1-1.6c-.1-.8 0-1.5.1-2.2c-7.1 3.9-12.4 7.8-15.4 10.2c11.2 16.3 28.9 31.6 58.1 30c27.5-1.5 46.7-23.8 57.3-43.9");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.vkq9u98sh {
  d: path("M-98.6-111.5c.1-.4-.6-.8-.9-.8c-.6 0-.7.7-.7 1.2c0 .6.3 2.4 1.3 1.8c.3-.2.4-.6.4-.9c0-.2.1-.4.1-.6c-.1-.3-.3-.4-.2-.7");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.vtt9_00mv {
  stop-color: var(--svg-color--700300, #700300);
}

.vvcil5b3r {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0.917;
}

.w2qflcbqj {
  stop-color: var(--svg-color--a07f9b, #a07f9b);
  stop-opacity: 0.993;
}

.w5zndcn8u {
  fill: var(--svg-color--fff, #fff);
  d: path("M-116.9-132.9c-.9-.3-.3.9-.2 1.3c.4.1.4-.9.3-1.1");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.we6yfovwq {
  d: path("M-98.3-197.9c-.2-.8.3-2 .4-2.8c.4-2.6 2-4.6 2.9-7.1c-8.1-3-17.2-5.8-23.2-7.6l.1.1v.7c-4.1 2.4 4.3 3.3 1.7 6.5c3.2-.4 1.6 2.7 1.1 4c-.8 2.2-.8 3.6.1 5.6c1 2.2.9 3.1.9 5.5c0 1 .4 1.9.3 2.8s-.9 1.6-1 2.4c-.2 2.4 1.7 2 2.9 3.8c1.3 1.8.1 3.4-.6 5.2c-.5 1.2-1.9 4.2-.4 5.4c1.9 1.6 3.1-1 3.3-2.3c.2-1.2-.4-2.3-.4-3.4c0-1.5.5-1.8.9-3.1c.9-2.9-.6-3.3-1.5-5.8c-.9-2.6 1-3.7 1-6.2c0-1.6-2.4-4.9-.3-5.7c.1-.5-.4-1.6-.3-1.8c.3-.9.3-.6.8-1.4c.6-.9 1.7-2.3 2.8-1.5s.2 2.6.5 3.8s1.5 2 .9 3.8c-.4 1.1-2.1 1.6-2.3 2.8c-.2 1.5 1.2 1.8 1.4 3.1c.3 1.6-1.1 2.2-1 3.8c.1 1.4 1.4 2.2 1.2 3.7c1.6.7 2.6-.1 3.3-1.6c1-2.1-.5-2.3-.8-4.1c-.2-1 .5-1.5.6-2.4c.1-1.3-.1-1.1-.3-2.1c-.4-1.5-.7-2.8-.7-4.5c0-2.7 2.6-7 3.5-2.6c.4 1.6.1 2.5.8 4.2c.6 1.6.5 2.5.5 4.3c1.9 1.1 2.7-2 2.3-3.5c-.5-.7-1.2-1.1-1.4-2");
}

.whg7vubcp {
  d: path("M-104.1-213.9c0-.3 0-.6-.1-.9c-.2-.8-1-1.2-1.2-2.1c-.2-.8.3-2 .4-2.8v-.1c-.9 0-1.9.1-2.8 0v.1c.4 1.6.1 2.5.8 4.2c.3.7.4 1.2.5 1.8c.8-.3 1.7-.3 2.4-.2");
}

.wo_pay7oo {
  fill: var(--svg-color--fff, #fff);
  d: path("M-105.7-206.7c.6.2.9.5.9 1.1c0 .4 0 .9.1 1.3c0 .4 0 .4.3.4s1.3-.3 1.3.1c.4.1.8-.8 1.1-1c.4-.2.8.1 1 .4c.2.2.1.6.4.7s.4-.1.6-.1c.3 0 .2.2.4.3c.3.1.3-.3.4-.5c.2-.4.5-.7.8-.9c.2-.1.5-.2.8-.2c.1 0 .3.2.4.1c.3-.2.3-1.2.2-1.5c-.2-.5-.8-.8-1.3-.7q-.3 0-.6.3c-.1.1-.2.4-.2.5c-.4.3-.7-.2-.8-.5c-.2-.4-.3-.8-.6-1c-.6-.5-1.5-.4-2 .2c-.4.3-.4.9-.7 1.2s-.4-.4-.7-.6c-.6-.5-1.4 0-2 .2m-7.7 2.8c-.4.1-.7.8-.7 1.2c0 .6.6.7.7 1.2c.2.8-.7 1.3-.9 2c-.3 1.2 1.2 1 1.3 2c0 .2-.1.4.1.5c.2.2.7.3.9.2c.3-.2.5-.8.6-1.1c.2-.5.3-1 .4-1.5c.2-.6.6-1.2.3-1.9c-.3-.6-.8-.8-1.2-1.1c-.3-.3-.5-.7-.8-.9c-.4-.2-.4-.3-.5-.7m.5 10.4c-.1.5.5.8.4 1.3c-.1.4-.4.8-.4 1.2s.4 1 .2 1.4c-.1.5-.7.8-1 1.2c-.3.5-.5.8-.2 1.3s.8.8 1.4.6c1.2-.4.7-1.9.6-2.7c0-.4 0-.7.1-1.1c.2-.5.1-.7-.1-1.2c-.2-.6.2-1.8-.7-1.8m.8 15c-.5.6-1 1.3-1.2 2c-.1.3-.2.8-.1 1.1c.3.8 1 .8 1.5.3s.8-1.2.9-1.9c.1-.5 0-.7-.3-.9c-.2-.2-.3-.5-.5-.7m6.2-17c-.1.3-.5.6-.7.8c-.3.3-.7.6-.9.9c-.3.4-.6 1.2-.3 1.5c.2.2.4.2.6.4s.4.5.5.7c.2.3.2 1 .5 1.2c.4.2.8-.2.8-.6c.1-.5-.1-1 .2-1.5s.4-1 .3-1.6c0-.2-.2-.4-.3-.6s-.3-.3-.5-.5c-.1-.1-.1-.2-.1-.3m-.9 6.5c-.3.3-.5.9-.6 1.3c-.1.6.5.7.9 1c.4.4.2.6.4 1s.6.3.8.1c.8-.5 1-2.1.3-2.7c-.2-.2-.5-.5-.7-.6c-.3-.1-.7-.1-.9-.2m6.7-7.9c.4.4.5 1.6.4 2.1c-.1.4-.2.7-.3 1c-.2.8.6 1 1 .3c.3-.4.5-1 .5-1.5c-.1-.5-.4-.6-.6-.9c-.2-.2-.2-.4-.4-.6c-.2-.1-.3-.2-.4-.4");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.woux2eriq {
  d: path("M66.6 111s57.8 8.8 113.6-6.4c55.8-15.1 3.2 94.3-45 95.6c-48.3 1.3-73.8-31.8-84.6-68.2c0 0-8.8-25.6 16-21");
}

.wq9g5ilqy {
  fill: var(--svg-color--fff, #fff);
  d: path("M-112-152.8c-.3.1-.8.8-.8 1c.3.1.9-.7.8-1");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.x-0n5b0re {
  stop-color: var(--svg-color--fe980e, #fe980e);
}

.x-qw4nb-c {
  fill: var(--svg-color--fff, #fff);
  d: path("M81.3 38.7s28.1-3.4 37.4 18c0 0-2.8-12.7-.4-13.7c2.3-1.1 5.7 19.4 5.7 19.4s1.3-11.2 2.1-11.4c.9-.2.9 8.3.9 8.3s1.7-19.4 5.3-19.6s.4 20.7.4 20.7s6.4-22 34-21.1c0 0-18.6-4.5-30.8 8c0 0 1.3-12.5-3-12.5s-6.4 12.7-6.4 12.7s-.2-3-.9-3s-1.5 8.7-1.5 8.7s-4.5-16.7-7-16.1c-2.6.7-1.5 9.7-1.5 9.7s-11.3-12.5-34.3-8.1");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.x0kxpybge {
  stop-color: var(--svg-color--ffada6, #ffada6);
  stop-opacity: 0.69;
}

.x4ila6b7b {
  d: path("M117.5 77.6c-16.1 5.3-35.9 2.5-44.2.9c-.5 2-.8 4.1-.8 6.3c0 .8.1 1.6.1 2.4c3.5.7 7.8 1.3 13.2 1.8c23.5 2 32.8-3.6 32.8-3.6s0-3.4-1.1-7.8");
}

.x96c30b1f {
  fill: var(--svg-color--c62619, #c62619);
  d: path("M141 22.9c0 2.9-7.3 5.1-16.2 5.1s-16.2-2.3-16.2-5.1c0-2.9 7.3-5.1 16.2-5.1s16.2 2.3 16.2 5.1");
}

.xa9_vkbhq {
  d: path("M-116.1-142.4c-.9-.1-2.1 1.2-1.3 1.9c.6.5 2.1.6 2.3-.4c.1-.5-.6-1.5-1-1.5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.xedpx5hcq {
  stop-color: var(--svg-color--f2eee5, #f2eee5);
}

.xflly4r9p {
  stop-color: var(--svg-color--85211b, #85211b);
}

.xlhhzm9tf {
  fill: var(--svg-color--7f1e0b, #7f1e0b);
  d: path("M26 113.8c-.5-3.1 4.5-4.4 4.5-4.4c-6.3-6-13.5.5-13.5.5l-.1.6c2.7-.7 9.5-1.6 8.4 8.1c2.9.1 5.5-.7 5.5-.7s-4.2-1.1-4.8-4.1");
}

.xp0eq4ynx {
  fill: var(--svg-color--fbb316, #fbb316);
  d: path("M-119.2-144.9c0 .4 0 .8-.2 1c-.1.2-.3.4-.5.4c-.2.1-.5.1-.7.1c0 .2 0 .4-.1.7c.2-.1.4-.1.4-.1q.6-.3.9-.9c.3-.3.4-.9.2-1.2");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.xraz3vbse {
  d: path("M-103.1-123.5c-.8 0-.9 1-.9 1.6c-.1.5-.1 1.2.5 1.3s.8-.3.9-.8c0-.4.4-1.1.3-1.5c-.1-.2-.4-.5-.6-.6");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.xulqtvbwy {
  fill: var(--svg-color--020202, #020202);
  d: path("M113.5 87.2c.2-.9.3-1.7.3-2.6c0-8-6.5-14.4-14.4-14.4S85 76.8 85 84.7c0 1.5.2 2.8.6 4.2c.2 0 .4.1.5.1c13.5.9 22.4-.4 27.4-1.8");
}

.xuptg5buq {
  d: path("M-104.2-135.1c-.5 0-1.2.2-1.6.5c-.2.1-.3.3-.3.5c.1.3.3.4.5.5c.5.3.8.4 1.4.2c.4-.1 1-.3 1.2-.7c.3-.5-.7-1-1.2-1");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.xxrtqdb0g {
  stop-color: var(--svg-color--b08bab, #b08bab);
}

.xyjufeb6e {
  d: path("M178.8 112.4c-4.9 2.1-10 3.9-15.2 5.3c.8 3.3 3.8 9.7 9.7 9.6c7.5-.2 12.5-9.2 12.6-17.2c-3.8.7-7.1 2.3-7.1 2.3");
}

.y_ua2ol9p {
  d: path("M66.6 111.5s57.8 9.3 113.6-6.8s3.2 99.6-45 101c-48.3 1.4-73.7-33.6-84.5-72c-.1 0-8.9-27.2 15.9-22.2");
}

.y0kh1ab9h {
  stop-color: var(--svg-color--7f5327, #7f5327);
}

.y3ekq7bsc {
  fill: var(--svg-color--fff, #fff);
  d: path("M65 148.7s18.4 44.5 64.9 41.9c46.6-2.6 66.7-64.3 66.7-64.3s-16.9 67.5-67.5 68.1C78.4 195 65 148.7 65 148.7");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.y42hhujkb {
  cx: 88px;
  cy: 69.1px;
  r: 7.8px;
  fill: var(--svg-color--fff, #fff);
}

.y4gopsb7n {
  d: path("M-117.3-218.8c.1-.5-.4-1.6-.3-1.8c.3-.8.3-.7.7-1.2c-.2-.3-.2-.6-.4-1.1c-.3-.9-.6-1.1-1.5-1.2c-.4 0-.8.2-1.2.1s-.8-.5-1.2-.7c-.3-.1-.5-.2-.7-.2c-.2.7-.5 1.4-.7 1.8c-.8 2.2-.8 3.6.1 5.6c.2.3.3.6.4.9c.6.5 1.2 1 1.6 1.6c1 1.5 1.4 1.8 3.2 1.9h.3v-.1c0-1.4-2.3-4.7-.3-5.6");
}

.yf-h1sbsv {
  stop-color: var(--svg-color--ce4920, #ce4920);
  stop-opacity: 0;
}

.yfq1p6bjt {
  fill: var(--svg-color--fff, #fff);
  d: path("M60.4 85.6s23 13.7 55.5 2.8c-.1 0-29.1 20.5-55.5-2.8");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.yh6k42ohu {
  d: path("M114.3 137.8c-20.5 5.6-35.2 15.9-41.1 20.7c11.2 16.3 28.9 31.6 58.1 30c26.9-1.5 46.1-23.9 56.7-43.9c-17.7-8.3-34.3-11-49.1-10.5c7.4 1 28.5 4.8 32.8 15.2c5.3 12.7-24.2 24.6-39.3 26.3c-15.2 1.7-40.6-2-39.8-18.4c.3-9.4 11.9-15.8 21.7-19.4");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.yhb84sheq {
  d: path("M240.3 198s-16.1-36.9-24.5-89.6c-6.6-41.2-24.2-75.7-58.5-89.2C170.9 29.5 168.9 44 168.9 44c-31-2.9-39.7 31.3-39.7 31.3s3.5-28.9 2.4-28.6c-1.2.3-4.7 24.3-4.7 24.3l-1.5-11.4l-.6 11.4l-5.2-22l3.8 27.8c-6.2-39-45.3-32.1-45.3-32.1c-1.6-11.5 8.6-20.6 18.2-26.5c-21.3 8.1-48.4 29.5-58.7 84.7c-17.8 96.2-57.3 120.8-26 163.9c0 0 0 56 47.1 103.6c0 0 18.1 14.7 30.8-3.6c12.8-18.4 30.1-28.8 44.8-25s28.3 22.4 33.9 28.5s29 25.2 58.6-55.3c0 .1 55.5-30.5 13.5-117");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.ynuatpbgy {
  stop-color: var(--svg-color--e8e0d0, #e8e0d0);
}

.yutklr1qw {
  d: path("M109.5 62c-3.5-1.8-7.4-2.7-11.5-2.7c-14.1 0-25.5 11.4-25.5 25.5c0 .8.1 1.6.1 2.4c3.5.7 7.8 1.3 13.2 1.8c23.5 2 32.8-3.6 32.8-3.6s-.2-14.3-9.1-23.4");
}

.yzoivvpbr {
  d: path("M-100.2-149c-.6-.1-1 1.2-1 1.6c-.1.6.3 1.1.9.8c.5-.3.7-.8.7-1.3c0-.3-.2-1.2-.6-1.1c0 0 0 .1 0 0");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.z1gbl_b-h {
  d: path("M-97.9-145c-.8-.4-2.2.1-2.2 1.1s1.4 1.7 2.2 1.4c.5-.1.9-.7.9-1.3c-.1-.5-.5-1-.9-1.2");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.z3s9awblp {
  fill: var(--svg-color--8c0000, #8c0000);
  d: path("M125.3 281.5s8.9 5 15.5-2.5c0 0 2.5-1 3.6.2c-.2 0-9.8-7.4-19.1 2.3");
}

.z71a5ib_d {
  stop-color: var(--svg-color--a33665, #a33665);
}

.z9-sc7eyt {
  stop-color: var(--svg-color--ad1813, #ad1813);
}

.zaymdcbpv {
  d: path("M234.8 109.9s-7.3-6.5-13.5-.5c0 0 5 1.3 4.5 4.4s-4.7 4.2-4.7 4.2s14.5 4.1 13.7-8.1");
}

.zd4-rib9f {
  fill: var(--svg-color--fff, #fff);
  d: path("M65.9 95.7s20.8 11.9 46.6 1.1c0-.1-23.2 19.7-46.6-1.1m71.3-8.6s27.8 11.2 54.3-2.6c0 .1-23.3 22-54.3 2.6");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.zm48t9h0p {
  d: path("m120.8 74.6l3.7 6l-.6-7.1l2.2 4.7l-.2-9.9l1.6 8.3l1.6-11.6l.2 14.7l3.2-7.7s-4.4 13.9-4.4 19.5L127 81v9l-1.6-7.3l.2 6.5z");
}

.zt10s4bll {
  d: path("M-116.9-133.2c-1.2-.2-1.4 2.6-.3 2.9s1.3-1.5 1-2.1c-.2-.4-.4-.8-.8-.8");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.zt38e9bld {
  d: path("M116.3 107.3c2.7 2.9 5.2 4.7 6.9 5.9c3.3-.2 6.7-.4 10.2-.7c2.1-1.5 6.2-4.8 6.3-8.4c-.4-1.2-1-2.3-1.5-2.9c.9 1.7.6 4.8-1.4 5.7c-2.4 1.1-15.5 1.9-19.1-.3c-3.6-2.1-1.2-5.7-1.2-5.7c-1.1 1.5-1.7 2.9-2 4.1c.5.7 1 1.5 1.8 2.3");
}

</style>
