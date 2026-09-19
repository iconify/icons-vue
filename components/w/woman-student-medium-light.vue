<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iqlhBCz)"><path fill="url(#io2lA4I)" clip-rule="evenodd" class="fxtkhbbke"/><path fill="url(#ilzE80c)" clip-rule="evenodd" class="fxtkhbbke"/><path fill="url(#iYwmL2b)" clip-rule="evenodd" class="fxtkhbbke"/><path fill="url(#i7Bll9d)" clip-rule="evenodd" class="fxtkhbbke"/><path fill="url(#iWbovZe)" clip-rule="evenodd" class="fxtkhbbke"/><path fill="url(#i38KZ4c)" clip-rule="evenodd" class="fxtkhbbke"/><path fill="url(#i4oBoae)" clip-rule="evenodd" class="fxtkhbbke"/><path fill="url(#ibxsH7b)" clip-rule="evenodd" class="fxtkhbbke"/><path fill="url(#iBhcX9b)" clip-rule="evenodd" class="fxtkhbbke"/><path fill="url(#inpGkRd)" clip-rule="evenodd" class="fxtkhbbke"/></g><path fill="url(#iK2fzTd)" clip-rule="evenodd" class="fxtkhbbke"/><path fill="url(#iwCYpQb)" clip-rule="evenodd" class="fxtkhbbke"/><path fill="url(#if9vtRc)" clip-rule="evenodd" class="fxtkhbbke"/><path class="r7selubyf"/><path fill="url(#iYxrmDb)" class="z7xukho-o"/><path fill="url(#isL9vQe)" class="z7xukho-o"/><path fill="url(#iByU1dd)" class="u0gj58p9u"/><path fill="url(#iDWbfjb)" class="u0gj58p9u"/><path fill="url(#izRngeN)" class="u0gj58p9u"/><path fill="url(#iGkbbHc)" class="u0gj58p9u"/><path fill="url(#ihAL4bD)" class="u0gj58p9u"/><path fill="url(#ieVSmvb)" class="u0gj58p9u"/><g filter="url(#iixHqpz)"><path class="vxeaf7beg"/></g><path fill="url(#i0wsCSb)" class="bmx5v--2s"/><path fill="url(#ip1dkVc)" class="bmx5v--2s"/><path fill="url(#i2jaJxd)" class="bmx5v--2s"/><path fill="url(#igFbE6c)" class="jc92x5j2j"/><path fill="url(#ihz7M2d)" class="jc92x5j2j"/><path fill="url(#iBABucc)" class="qf8jcy72s"/><path fill="url(#isfgDQe)" class="qf8jcy72s"/><g filter="url(#iTVpQhb)"><path stroke="url(#inRlCrA)" class="gfkvk0bib"/></g><path fill="url(#i0kFQac)" class="hmhlr1w3c"/><path fill="url(#iZJoEXc)" class="hmhlr1w3c"/><path fill="url(#id3lwDb)" class="hmhlr1w3c"/><path fill="url(#iFFVERw)" class="hmhlr1w3c"/><path fill="url(#iKTWUZb)" class="hmhlr1w3c"/><path fill="url(#iHiigDe)" class="iyrnnezud"/><path fill="url(#iWyolYd)" class="iyrnnezud"/><path fill="url(#iKcQVGb)" class="iyrnnezud"/><path fill="url(#iEmeMOd)" class="hneev9bsk"/><path fill="url(#iqrQGFb)" class="hneev9bsk"/><g filter="url(#iZWA10M)"><path fill="url(#iOsXDib)" class="wzj86ub5h"/><path fill="url(#iOsXDib)" class="qjc5hlbod"/><path fill="url(#iOsXDib)" class="p0_cxvb5r"/></g><g filter="url(#iRY7hFb)"><path stroke="url(#i6NE5mb)" class="v9zstkjlw"/></g><g filter="url(#ilpO6Vo)"><path fill="url(#iE8ygbd)" class="qug8uobre"/></g><g filter="url(#iAHG8Hc)"><path fill="url(#iKa5LpE)" class="ak3a6gb_a"/><path fill="url(#ipSOQlb)" class="ak3a6gb_a"/></g><g filter="url(#i3lzqco)"><path class="pihdi6b6y"/><path fill="url(#iYfikZN)" class="bu8467fsx"/></g><g filter="url(#izkYLYc)"><path class="gd63t6bgg"/><path fill="url(#i6SS8Ld)" class="rqa4zqbgs"/></g><g filter="url(#ihe1mpO)"><path fill="url(#icNDQPb)" class="kchfkekxb"/><path fill="url(#ii5qWfe)" class="kchfkekxb"/><path fill="url(#iMgRPye)" class="kchfkekxb"/><path fill="url(#itvKftU)" class="kchfkekxb"/><path fill="url(#ipObsMj)" class="kchfkekxb"/><path fill="url(#iLnLj1b)" class="kchfkekxb"/><path fill="url(#iznPrIc)" class="kchfkekxb"/></g><path fill="url(#iiL0Txb)" class="ugp09kblg"/><g filter="url(#i04exIQ)"><path class="kjd6s50kk"/></g><g filter="url(#igYUb4d)"><path class="zwa3gh7uz"/><path fill="url(#iUpzZic)" class="o_x20brsq"/><path fill="url(#iV8D9kd)" class="o_x20brsq"/><path fill="url(#iYSMf2b)" class="o_x20brsq"/></g><path fill="url(#iVddiwb)" class="o_x20brsq"/><path fill="url(#iArnDHt)" class="o_x20brsq"/><path stroke="url(#i3VleCe)" class="eni3pebtv"/><g filter="url(#itKAoBb)"><path class="tjn9n03bv"/></g><g filter="url(#iMo5qld)"><path class="rxtdreblr"/></g><g filter="url(#io2VNPb)"><path class="j7vcw3bhc"/></g><g filter="url(#imeKdZq)"><path clip-rule="evenodd" class="kz_alab4a"/></g><path class="doaeixblm"/><path fill="url(#iXnUcxc)" class="gwemxwb2f"/><path class="f6o39wbbx"/><g filter="url(#iIogMHc)"><path class="rdlx2yyju"/><path fill="url(#iG3Znze)" class="znate9w9p"/></g><g filter="url(#iVjkiGe)"><path fill="url(#iqhgWud)" class="gch1ycr_h"/></g><path class="llafqni9f"/><path fill="url(#irJRjGb)" class="za9vcfmjh"/><path class="ovnjvmr2p"/><g filter="url(#izuXScd)"><path fill="url(#iqKLMkc)" class="u00fdvbgz"/></g><g filter="url(#ibI6tdb)"><ellipse transform="rotate(-27.914 13.849 10.231)" class="fxwrjtoyw"/><ellipse fill="url(#iMMVGEd)" transform="rotate(-27.914 13.849 10.231)" class="eu0y59b1z"/></g><g filter="url(#intstdd)"><path class="qn1fgfb4u"/></g><g filter="url(#ilxZ4nc)"><path class="l2oytfjhx"/></g><g filter="url(#iMiIYrd)"><path fill="url(#iV9uJTc)" class="soq4ax0au"/><path fill="url(#iCqdOLb)" class="soq4ax0au"/></g><g filter="url(#idUa5fe)"><path fill="url(#i5yruZf)" class="mu78_5yfl"/><path fill="url(#iTK4kvb)" class="mu78_5yfl"/><path fill="url(#ib7ozhb)" class="mu78_5yfl"/></g><g filter="url(#iejcKod)"><path stroke="url(#itnj7Je)" class="p_n49bb2s"/></g><g filter="url(#iDMM5gc)"><path fill="url(#iy1YHxc)" class="npo8dko2g"/><path fill="url(#it3pbJe)" class="npo8dko2g"/></g><path fill="url(#iMKKzUd)" class="o_plwnvwa"/><path fill="url(#ib7vfWg)" class="o_plwnvwa"/><path fill="url(#imKMawy)" class="o_plwnvwa"/><defs><radialGradient id="ilzE80c" cx="0" cy="0" r="1" gradientTransform="matrix(1.82792 -3.79645 8.65615 4.16779 21.343 17.06)" gradientUnits="userSpaceOnUse"><stop class="rjxj417_v"/><stop offset="1" class="p1sg1mumi"/></radialGradient><radialGradient id="iYwmL2b" cx="0" cy="0" r="1" gradientTransform="matrix(-.1406 5.80014 -5.4293 -.13162 15.718 12.807)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="ta36f8b7v"/><stop offset="1" class="hcuenbefp"/></radialGradient><radialGradient id="i7Bll9d" cx="0" cy="0" r="1" gradientTransform="rotate(142.167 4.201 9.184)scale(4.18372 5.14993)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="hxuphr-8h"/><stop offset="1" class="v-9s4u7ch"/></radialGradient><radialGradient id="iWbovZe" cx="0" cy="0" r="1" gradientTransform="rotate(125.038 2.76 8.545)scale(1.8676 1.69756)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="ybvptdnhb"/><stop offset="1" class="ue-yx0baa"/></radialGradient><radialGradient id="i38KZ4c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.4431 -.54484 .80092 -3.59136 11.904 9.626)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="sqmgyf2vi"/><stop offset="1" class="mvuactshi"/></radialGradient><radialGradient id="i4oBoae" cx="0" cy="0" r="1" gradientTransform="matrix(2.2674 3.32189 -5.79716 3.95694 12.396 3.017)" gradientUnits="userSpaceOnUse"><stop class="vrnylccvf"/><stop offset="1" class="b442o21cz"/></radialGradient><radialGradient id="ibxsH7b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.16001 1.26549 -1.7685 -1.6211 22.186 4.933)" gradientUnits="userSpaceOnUse"><stop class="di6ktzbyk"/><stop offset="1" class="ejv935bph"/></radialGradient><radialGradient id="iBhcX9b" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 11.43 6.764)scale(2.01344 4.38098)" gradientUnits="userSpaceOnUse"><stop class="kdig6mnba"/><stop offset="1" class="him6rrbhz"/></radialGradient><radialGradient id="inpGkRd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.30433 1.40608 -2.2403 -5.2648 24.014 12.983)" gradientUnits="userSpaceOnUse"><stop class="c2fnpwywz"/><stop offset="1" class="c5g3vhi-m"/></radialGradient><radialGradient id="iwCYpQb" cx="0" cy="0" r="1" gradientTransform="matrix(3.16384 -5.00737 4.9618 3.13505 20.275 17.763)" gradientUnits="userSpaceOnUse"><stop offset=".345" class="jjuf3rb5e"/><stop offset="1" class="edfa78b2t"/></radialGradient><radialGradient id="if9vtRc" cx="0" cy="0" r="1" gradientTransform="matrix(0 12.9163 -17.5805 0 16.622 7.276)" gradientUnits="userSpaceOnUse"><stop offset=".77" class="n4q03-1wn"/><stop offset=".944" class="wmtmv1hbb"/></radialGradient><radialGradient id="iYxrmDb" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.875 -3.65625 0 23.737 23.124)" gradientUnits="userSpaceOnUse"><stop class="qs5b04nop"/><stop offset="1" class="njrkhhlfe"/></radialGradient><radialGradient id="isL9vQe" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 0 0 7.0625 9.143 21.468)" gradientUnits="userSpaceOnUse"><stop class="fx84vub6z"/><stop offset="1" class="z6io75bpj"/></radialGradient><radialGradient id="iByU1dd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.71875 13.6527 0 16.443 21.359)" gradientUnits="userSpaceOnUse"><stop class="xxaet9bhw"/><stop offset="1" class="zvl8nq86d"/></radialGradient><radialGradient id="iDWbfjb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.9375 -7.54205 0 16.435 16.906)" gradientUnits="userSpaceOnUse"><stop offset=".932" class="uzp4m_b3p"/><stop offset=".995" class="alc11rbtu"/></radialGradient><radialGradient id="izRngeN" cx="0" cy="0" r="1" gradientTransform="matrix(-5.88284 4.0234 -5.54695 -8.11053 16.018 15.562)" gradientUnits="userSpaceOnUse"><stop offset=".928" class="cxkgc8uxn"/><stop offset="1" class="pnxjkfbgy"/></radialGradient><radialGradient id="iGkbbHc" cx="0" cy="0" r="1" gradientTransform="matrix(6.76566 4.60934 -6.35476 9.32761 15.768 15.327)" gradientUnits="userSpaceOnUse"><stop offset=".933" class="cxkgc8uxn"/><stop offset="1" class="e8o_wr2lc"/></radialGradient><radialGradient id="ihAL4bD" cx="0" cy="0" r="1" gradientTransform="rotate(-80.136 21.106 2.75)scale(9.65407 14.837)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="nxet2htkz"/><stop offset="1" class="e7yn8_bej"/></radialGradient><radialGradient id="ieVSmvb" cx="0" cy="0" r="1" gradientTransform="rotate(91.544 .342 14.341)scale(4.63875 7.3062)" gradientUnits="userSpaceOnUse"><stop offset=".436" class="q8_1e9bvu"/><stop offset="1" class="bh-nd0_an"/></radialGradient><radialGradient id="i0wsCSb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.96875 -1.42188 1.19716 -2.49957 17.739 18.23)" gradientUnits="userSpaceOnUse"><stop class="dn_8aox9x"/><stop offset="1" class="ws5zlibzm"/></radialGradient><radialGradient id="ip1dkVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -2.06 0 16.421 16.995)" gradientUnits="userSpaceOnUse"><stop class="etclelb-u"/><stop offset="1" class="syayv9bph"/></radialGradient><radialGradient id="i2jaJxd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.5407 -4.26182 0 16.421 14.553)" gradientUnits="userSpaceOnUse"><stop offset=".81" class="f8avqachq"/><stop offset="1" class="k-u3pqb_i"/></radialGradient><radialGradient id="ihz7M2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.33473 .18031 0 25.01 11.678)" gradientUnits="userSpaceOnUse"><stop class="ojstgxewy"/><stop offset="1" class="hom78lxtr"/></radialGradient><radialGradient id="iBABucc" cx="0" cy="0" r="1" gradientTransform="matrix(-.81259 1.10067 -.98646 -.72826 25.268 12.049)" gradientUnits="userSpaceOnUse"><stop class="all-5ubma"/><stop offset=".661" class="fi917n10w"/></radialGradient><radialGradient id="isfgDQe" cx="0" cy="0" r="1" gradientTransform="matrix(.79636 -.08984 .10538 .93405 23.93 12.44)" gradientUnits="userSpaceOnUse"><stop offset=".087" class="xlrmucced"/><stop offset="1" class="ezx8m4rog"/></radialGradient><radialGradient id="iZJoEXc" cx="0" cy="0" r="1" gradientTransform="rotate(169.33 12.33 8.563)scale(1.11532 5.56401)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="id3lwDb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39844 -1.38177 0 24.768 13.117)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="jjb6zku7x"/><stop offset="1" class="dm9f9lb7m"/></radialGradient><radialGradient id="iKTWUZb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.3125 2.89043 0 24.768 16.906)" gradientUnits="userSpaceOnUse"><stop offset=".422" class="irf74zkjs"/><stop offset="1" class="codehtz3g"/></radialGradient><radialGradient id="iHiigDe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.3734 4.36464 0 5.44 30.005)" gradientUnits="userSpaceOnUse"><stop class="yihcw4vuy"/><stop offset=".441" class="kszwqub4g"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="iWyolYd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5202 .82413 0 9.206 30.005)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="iEmeMOd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88274 -10.19308 2.86286 -.5288 25.547 30.005)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="iqrQGFb" cx="0" cy="0" r="1" gradientTransform="matrix(.5437 12.03342 -.70276 .03175 23.496 23.166)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="iKa5LpE" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 36.685 -41.974)scale(2.86704 3.50053)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="ipSOQlb" cx="0" cy="0" r="1" gradientTransform="matrix(1.04578 .2988 -.15709 .5498 21.73 9.09)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="iYfikZN" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 41.923 -53.716)scale(1.36801)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="i6SS8Ld" cx="0" cy="0" r="1" gradientTransform="matrix(-1.27602 0 0 -1.22059 11.528 10.958)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="icNDQPb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.81974 3.14481 -4.20928 -9.12812 19.42 10.394)" gradientUnits="userSpaceOnUse"><stop class="uy3z2gbbp"/><stop offset="1" class="gvh2bspmv"/></radialGradient><radialGradient id="ii5qWfe" cx="0" cy="0" r="1" gradientTransform="rotate(152.124 7.826 7.848)scale(2.50271 2.12337)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="iMgRPye" cx="0" cy="0" r="1" gradientTransform="matrix(.87758 -4.24179 5.38204 1.11349 14.137 17.507)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="itvKftU" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.15625 -11.0046 0 16.656 8.463)" gradientUnits="userSpaceOnUse"><stop offset=".59" class="warh7idvl"/><stop offset=".925" class="di0w0acwj"/></radialGradient><radialGradient id="ipObsMj" cx="0" cy="0" r="1" gradientTransform="matrix(-6.01105 .80845 -1.39191 -10.34922 17.09 12.842)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="iLnLj1b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.20672 1.73479 0 18.835 9.955)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="mt3h7fbpd"/><stop offset="1" class="wcr1klbjh"/></radialGradient><radialGradient id="iznPrIc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.42612 1.63443 0 14.41 10.047)" gradientUnits="userSpaceOnUse"><stop class="r-jog4w_t"/><stop offset="1" class="xjkdvxqyn"/></radialGradient><radialGradient id="iiL0Txb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.41243 0 0 -4.64978 21.765 11.515)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="iUpzZic" cx="0" cy="0" r="1" gradientTransform="rotate(-105.892 13.257 -.371)scale(2.67092 1.52833)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="iArnDHt" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34383 .9599 -1.2857 -1.79997 16.723 11.902)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="atsjj9bsj"/><stop offset="1" class="vyevcqbzs"/></radialGradient><radialGradient id="iXnUcxc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85076 -1.35323 0 18.71 10.332)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iG3Znze" cx="0" cy="0" r="1" gradientTransform="matrix(-.2432 -.31339 .43145 -.33481 18.47 10.42)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="irJRjGb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85076 -1.35323 0 14.133 10.332)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iMMVGEd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00811 -.51808 .62275 -.00975 13.832 10.562)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iV9uJTc" cx="0" cy="0" r="1" gradientTransform="matrix(2.02893 2.81219 -5.58781 4.03148 10.174 4.405)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="hi5yi9bqv"/><stop offset="1" class="d8y_5zbge"/></radialGradient><radialGradient id="iCqdOLb" cx="0" cy="0" r="1" gradientTransform="rotate(127.118 5.63 5.7)scale(3.26222 2.55843)" gradientUnits="userSpaceOnUse"><stop class="g6mu4o3fz"/><stop offset="1" class="dx30lgbdy"/></radialGradient><radialGradient id="i5yruZf" cx="0" cy="0" r="1" gradientTransform="matrix(-2.21463 4.60494 -6.54803 -3.1491 18.425 2.648)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="iz4jcxg0j"/><stop offset="1" class="qflnpfbur"/></radialGradient><radialGradient id="iTK4kvb" cx="0" cy="0" r="1" gradientTransform="rotate(104.957 7.934 9.176)scale(3.48108 6.21382)" gradientUnits="userSpaceOnUse"><stop class="mv8kv7beo"/><stop offset="1" class="g_ulzrbqz"/></radialGradient><radialGradient id="ib7ozhb" cx="0" cy="0" r="1" gradientTransform="rotate(-119.068 11.713 -.424)scale(7.561 6.76817)" gradientUnits="userSpaceOnUse"><stop offset=".891" class="w58maet4h"/><stop offset=".979" class="drxq29wnr"/></radialGradient><radialGradient id="iy1YHxc" cx="0" cy="0" r="1" gradientTransform="matrix(-.6722 -3.65216 4.02251 -.74037 18.968 5.954)" gradientUnits="userSpaceOnUse"><stop offset=".11" class="l382wkm5r"/><stop offset="1" class="ym5q1xkkz"/></radialGradient><radialGradient id="it3pbJe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.02116 -7.18676 0 16.352 2.873)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="vnszicyas"/><stop offset="1" class="j-b5ok87h"/></radialGradient><radialGradient id="ib7vfWg" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -12.6875 0 22.174 2.406)" gradientUnits="userSpaceOnUse"><stop class="g_-uv52uc"/><stop offset=".867" class="wntqft2su"/></radialGradient><radialGradient id="imKMawy" cx="0" cy="0" r="1" gradientTransform="matrix(7.75 0 0 .875 7.205 3.03)" gradientUnits="userSpaceOnUse"><stop class="it16sbc4j"/><stop offset=".935" class="uo2hv248r"/></radialGradient><filter id="iqlhBCz" width="15.998" height="16.498" x="8.547" y="1.265" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.698039 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1592"/></filter><filter id="iixHqpz" width="5.32" height="9.565" x="13.761" y="9.995" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1592" stdDeviation=".2"/></filter><filter id="iTVpQhb" width=".65" height="8.268" x="24.546" y="3.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1592" stdDeviation=".125"/></filter><filter id="iZWA10M" width="8.964" height="6.734" x="11.953" y="23.291" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1592" stdDeviation=".075"/></filter><filter id="iRY7hFb" width="1.172" height="2.394" x="13.087" y="3.796" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1592" stdDeviation=".125"/></filter><filter id="ilpO6Vo" width="3.525" height="3.625" x="9.821" y="9.271" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1592"/></filter><filter id="iAHG8Hc" width="3.375" height="3.625" x="19.796" y="9.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1592"/></filter><filter id="i3lzqco" width="3.253" height="3.252" x="19.857" y="9.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1592" stdDeviation=".25"/></filter><filter id="izkYLYc" width="3.053" height="3.052" x="10.002" y="9.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1592" stdDeviation=".2"/></filter><filter id="ihe1mpO" width="10.686" height="11.606" x="11.078" y="5.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1592"/></filter><filter id="i04exIQ" width="2.969" height="3.812" x="14.767" y="9.928" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1592" stdDeviation=".25"/></filter><filter id="igYUb4d" width="2.469" height="3.312" x="15.187" y="10.033" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1592" stdDeviation=".125"/></filter><filter id="itKAoBb" width="3.138" height="1.348" x="17.419" y="9.485" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1592"/></filter><filter id="iMo5qld" width="3.138" height="1.348" x="12.286" y="9.485" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1592"/></filter><filter id="io2VNPb" width="2.562" height="1.134" x="12.428" y="8.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1592"/></filter><filter id="imeKdZq" width="2.562" height="1.135" x="18.109" y="8.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1592"/></filter><filter id="iIogMHc" width=".815" height=".721" x="17.945" y="9.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1592" stdDeviation=".05"/></filter><filter id="iVjkiGe" width=".915" height=".939" x="18.83" y="9.959" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1592" stdDeviation=".1"/></filter><filter id="izuXScd" width="1.015" height="1.071" x="14.171" y="9.892" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1592" stdDeviation=".1"/></filter><filter id="ibI6tdb" width=".948" height=".729" x="13.375" y="9.867" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1592" stdDeviation=".05"/></filter><filter id="intstdd" width="2.742" height="1.396" x="17.955" y="7.934" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1592" stdDeviation=".2"/></filter><filter id="ilxZ4nc" width="2.742" height="1.396" x="12.239" y="7.934" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1592" stdDeviation=".2"/></filter><filter id="iMiIYrd" width="4.947" height="5.957" x="9.632" y="3.364" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1592" stdDeviation=".375"/></filter><filter id="idUa5fe" width="9.623" height="6.337" x="12.805" y="2.353" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1592" stdDeviation=".2"/></filter><filter id="iejcKod" width="1.171" height="2.393" x="13.089" y="3.798" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1592" stdDeviation=".1"/></filter><filter id="iDMM5gc" width="12.363" height="3.035" x="10.201" y="3.106" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.337255 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1592"/></filter><linearGradient id="io2lA4I" x1="21.343" x2="14.207" y1="3.667" y2="16.885" gradientUnits="userSpaceOnUse"><stop class="p6otu2-6b"/><stop offset="1" class="q5mih6mme"/></linearGradient><linearGradient id="iK2fzTd" x1="16.421" x2="16.421" y1="18.15" y2="16.674" gradientUnits="userSpaceOnUse"><stop class="hqpka7yim"/><stop offset="1" class="jj4p15bbx"/></linearGradient><linearGradient id="igFbE6c" x1="24.125" x2="25.311" y1="8.952" y2="8.952" gradientUnits="userSpaceOnUse"><stop class="pk_j5sfiy"/><stop offset="1" class="bqq6maclp"/></linearGradient><linearGradient id="inRlCrA" x1="25.371" x2="25.371" y1="3.718" y2="11.486" gradientUnits="userSpaceOnUse"><stop class="r2v6fvpbl"/><stop offset="1" class="k3o8k1bzw"/></linearGradient><linearGradient id="i0kFQac" x1="25.919" x2="23.6" y1="14.816" y2="14.816" gradientUnits="userSpaceOnUse"><stop class="clg68gimn"/><stop offset=".897" class="p-vpa1ykp"/></linearGradient><linearGradient id="iFFVERw" x1="23.719" x2="24.594" y1="14.495" y2="14.675" gradientUnits="userSpaceOnUse"><stop class="ud98q8dic"/><stop offset="1" class="yn026ikmt"/></linearGradient><linearGradient id="iKcQVGb" x1="9.35" x2="8.924" y1="28.074" y2="28.074" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="iOsXDib" x1="16.435" x2="16.435" y1="29.875" y2="23.441" gradientUnits="userSpaceOnUse"><stop class="gq6-o1bwg"/><stop offset="1" class="uuiv6bbmv"/></linearGradient><linearGradient id="i6NE5mb" x1="13.387" x2="13.959" y1="4.456" y2="5.793" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient><linearGradient id="iE8ygbd" x1="9.821" x2="12.924" y1="11.049" y2="11.049" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="iV8D9kd" x1="15.324" x2="16.22" y1="12.296" y2="12.405" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="iYSMf2b" x1="16.421" x2="16.421" y1="13.191" y2="12.552" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="iVddiwb" x1="16.503" x2="16.503" y1="13.164" y2="13.018" gradientUnits="userSpaceOnUse"><stop class="vyevcqbzs"/><stop offset="1" class="atsjj9bsj"/></linearGradient><linearGradient id="i3VleCe" x1="15.657" x2="16.131" y1="14.74" y2="13.826" gradientUnits="userSpaceOnUse"><stop class="b1eb00egl"/><stop offset="1" class="t5ewf8b-q"/></linearGradient><linearGradient id="iqhgWud" x1="19.525" x2="19.196" y1="10.388" y2="10.591" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iqKLMkc" x1="14.913" x2="14.584" y1="10.388" y2="10.591" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="itnj7Je" x1="13.389" x2="13.961" y1="4.458" y2="5.794" gradientUnits="userSpaceOnUse"><stop class="gjbrx7i8b"/><stop offset="1" class="zcr9jykfw"/></linearGradient><linearGradient id="iMKKzUd" x1="18.205" x2="16.924" y1="3.968" y2="-.407" gradientUnits="userSpaceOnUse"><stop class="i2fz9bb0r"/><stop offset="1" class="xp7dwurxx"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-student-medium-light" /></template>
<style>
.ak3a6gb_a {
  d: path("M21.483 12.645a1.687 1.687 0 1 0 0-3.374a1.687 1.687 0 0 0 0 3.374");
}

.alc11rbtu {
  stop-color: var(--svg-color--342542, #342542);
}

.all-5ubma {
  stop-color: var(--svg-color--686071, #686071);
}

.aps1jhbfc {
  stop-color: var(--svg-color--b47860, #B47860);
}

.aso-vybjw {
  stop-color: var(--svg-color--d59566, #D59566);
}

.atsjj9bsj {
  stop-color: var(--svg-color--c27b7c, #C27B7C);
  stop-opacity: 0;
}

.b1eb00egl {
  stop-color: var(--svg-color--ce9591, #CE9591);
}

.b442o21cz {
  stop-color: var(--svg-color--dcc893, #DCC893);
  stop-opacity: 0;
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.bh-nd0_an {
  stop-color: var(--svg-color--1c0e20, #1C0E20);
  stop-opacity: 0;
}

.bmx5v--2s {
  d: path("M16.141 18.875c.063.043.17.08.28.084a.56.56 0 0 0 .28-.084c1.017-.696 1.78-1.39 1.78-2.587v-3.633c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.633c0 1.197.763 1.89 1.78 2.587");
}

.bqq6maclp {
  stop-color: var(--svg-color--61546d, #61546D);
}

.bu8467fsx {
  d: path("M21.483 12.084a1.126 1.126 0 1 0 0-2.252a1.126 1.126 0 0 0 0 2.252");
}

.c2fnpwywz {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
}

.c5g3vhi-m {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.clg68gimn {
  stop-color: var(--svg-color--f9b72a, #F9B72A);
}

.codehtz3g {
  stop-color: var(--svg-color--db9820, #DB9820);
  stop-opacity: 0;
}

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.cxkgc8uxn {
  stop-color: var(--svg-color--6a656f, #6A656F);
  stop-opacity: 0;
}

.d8y_5zbge {
  stop-color: var(--svg-color--daa88f, #DAA88F);
}

.di0w0acwj {
  stop-color: var(--svg-color--9f6467, #9F6467);
}

.di6ktzbyk {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
}

.dm9f9lb7m {
  stop-color: var(--svg-color--eba429, #EBA429);
  stop-opacity: 0;
}

.dn_8aox9x {
  stop-color: var(--svg-color--bd8a7b, #BD8A7B);
}

.doaeixblm {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.929 9.546c.684 0 1.263.473 1.42 1.11a.287.287 0 0 1-.28.358h-2.34a.24.24 0 0 1-.238-.285a1.466 1.466 0 0 1 1.438-1.183");
}

.drxq29wnr {
  stop-color: var(--svg-color--dac493, #DAC493);
}

.dvyniwihb {
  stop-color: var(--svg-color--c57f82, #C57F82);
}

.dx30lgbdy {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
  stop-opacity: 0;
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.e7yn8_bej {
  stop-color: var(--svg-color--57525d, #57525D);
}

.e8o_wr2lc {
  stop-color: var(--svg-color--615b67, #615B67);
}

.ebol5nf6u {
  stop-color: var(--svg-color--4f445b, #4F445B);
  stop-opacity: 0;
}

.edfa78b2t {
  stop-color: var(--svg-color--eeb69b, #EEB69B);
  stop-opacity: 0;
}

.ejv935bph {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
  stop-opacity: 0;
}

.eni3pebtv {
  fill: var(--svg-color--88014e, #88014E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.954 13.605a.21.21 0 0 0-.257.045a.2.2 0 0 0-.021.257a2.076 2.076 0 0 0 3.49 0a.206.206 0 0 0-.021-.259a.21.21 0 0 0-.256-.043a3.1 3.1 0 0 1-1.468.356c-.538 0-1.043-.13-1.467-.356Z");
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.etclelb-u {
  stop-color: var(--svg-color--a76b71, #A76B71);
}

.eu0y59b1z {
  cx: 13.849px;
  cy: 10.231px;
  rx: 0.409px;
  ry: 0.207px;
}

.ezx8m4rog {
  stop-color: var(--svg-color--685352, #685352);
  stop-opacity: 0;
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.f6o39wbbx {
  fill: var(--svg-color--000, #000);
  d: path("M18.176 10.767c0-.298.238-.536.536-.536a.534.534 0 0 1 .476.783h-.949a.5.5 0 0 1-.064-.247");
}

.f8avqachq {
  stop-color: var(--svg-color--a57050, #A57050);
  stop-opacity: 0;
}

.fi917n10w {
  stop-color: var(--svg-color--402a4c, #402A4C);
}

.ft5dv1b6b {
  fill: none;
}

.fx84vub6z {
  stop-color: var(--svg-color--5d516a, #5D516A);
}

.fxtkhbbke {
  fill-rule: evenodd;
  d: path("M23.956 12.436c.223-.456.34-.966.34-1.496c0-.49-.101-.95-.282-1.37h.006a3.5 3.5 0 0 0-.295-.537l-.003-.003a3.4 3.4 0 0 1-.551-1.857v-.011a3.46 3.46 0 0 0-3.46-3.46a.57.57 0 0 1-.477-.244a3.47 3.47 0 0 0-2.813-1.443a3.47 3.47 0 0 0-2.812 1.443a.6.6 0 0 1-.477.244l-.09.002a3.46 3.46 0 0 0-3.37 3.458v.01c0 .659-.191 1.306-.552 1.858l-.002.004a3.46 3.46 0 0 0-.231 3.402a.54.54 0 0 1 0 .478a3.37 3.37 0 0 0 3.035 4.85h8.999a3.37 3.37 0 0 0 3.375-3.375c0-.53-.128-1.03-.34-1.475a.54.54 0 0 1 0-.478M11.1 9.634h-.013l1.257 2.47c.13 2.939 1.276 0 4.077 0s4.023 3.27 4.152.332l1.192-3.352c-.057-1.306-1.003-1.397-1.192-1.397h-3.376a4.05 4.05 0 0 1-3.344-1.755a.277.277 0 0 0-.484.053l-.086.204a2.42 2.42 0 0 1-1.355 1.337c-.248.129-.828.514-.85 1.509l.011.32z");
}

.fxwrjtoyw {
  cx: 13.849px;
  cy: 10.231px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.409px;
  ry: 0.207px;
}

.g_-uv52uc {
  stop-color: var(--svg-color--696070, #696070);
}

.g_ulzrbqz {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
  stop-opacity: 0;
}

.g1fw3-bff {
  stop-color: var(--svg-color--f4c099, #F4C099);
  stop-opacity: 0;
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
}

.g6mu4o3fz {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
}

.gch1ycr_h {
  d: path("M19.545 10.644a.9.9 0 0 0-.243-.485l-.272.299l.123.24z");
}

.gd63t6bgg {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M11.528 12.084a1.126 1.126 0 1 0 0-2.252a1.126 1.126 0 0 0 0 2.252");
}

.gfkvk0bib {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M24.871 3.718v7.768");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gjbrx7i8b {
  stop-color: var(--svg-color--ebce91, #EBCE91);
}

.gq6-o1bwg {
  stop-color: var(--svg-color--3f3748, #3F3748);
}

.gvh2bspmv {
  stop-color: var(--svg-color--d39b88, #D39B88);
}

.gwemxwb2f {
  d: path("M18.712 9.832a.936.936 0 0 1 .901 1.182h-1.808a.94.94 0 0 1 .906-1.183");
}

.hcuenbefp {
  stop-color: var(--svg-color--c7897d, #C7897D);
  stop-opacity: 0;
}

.hi5yi9bqv {
  stop-color: var(--svg-color--daa88f, #DAA88F);
  stop-opacity: 0;
}

.him6rrbhz {
  stop-color: var(--svg-color--fffabe, #FFFABE);
  stop-opacity: 0;
}

.hmhlr1w3c {
  d: path("m23.914 13.615l-.516 2.239a.45.45 0 0 0 .445.55h1.863a.45.45 0 0 0 .43-.556l-.542-2.24a.5.5 0 0 0-.485-.38h-.707a.5.5 0 0 0-.488.387");
}

.hneev9bsk {
  d: path("M23.665 30.005V18.219a10.97 10.97 0 0 1 3.765 8.286v3.5z");
}

.hom78lxtr {
  stop-color: var(--svg-color--70635d, #70635D);
  stop-opacity: 0;
}

.hqpka7yim {
  stop-color: var(--svg-color--d08d9c, #D08D9C);
}

.hxuphr-8h {
  stop-color: var(--svg-color--cf987b, #CF987B);
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i2fz9bb0r {
  stop-color: var(--svg-color--3d294b, #3D294B);
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.irf74zkjs {
  stop-color: var(--svg-color--a16739, #A16739);
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.it16sbc4j {
  stop-color: var(--svg-color--75707b, #75707B);
}

.iyrnnezud {
  d: path("M9.206 30.005V18.219a10.97 10.97 0 0 0-3.766 8.286v3.5z");
}

.iz4jcxg0j {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
  stop-opacity: 0;
}

.j-b5ok87h {
  stop-color: var(--svg-color--160c20, #160C20);
  stop-opacity: 0;
}

.j7vcw3bhc {
  fill: var(--svg-color--9f6836, #9F6836);
  d: path("m12.859 9.093l-.005.003a.281.281 0 0 1-.29-.482h.001l.002-.001l.003-.002l.01-.006l.034-.019q.043-.024.121-.062c.103-.049.25-.112.43-.17a2.94 2.94 0 0 1 1.393-.114a.281.281 0 0 1-.098.554a2.4 2.4 0 0 0-1.124.097a3 3 0 0 0-.477.202");
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.jc92x5j2j {
  d: path("M25.168 11.678V2.815h-.8v8.863z");
}

.jj4p15bbx {
  stop-color: var(--svg-color--d08d9c, #D08D9C);
  stop-opacity: 0;
}

.jjb6zku7x {
  stop-color: var(--svg-color--845d03, #845D03);
}

.jjuf3rb5e {
  stop-color: var(--svg-color--eeb69b, #EEB69B);
}

.k-u3pqb_i {
  stop-color: var(--svg-color--a57050, #A57050);
}

.k3o8k1bzw {
  stop-color: var(--svg-color--504b55, #504B55);
}

.kchfkekxb {
  d: path("m11.089 9.356l-.01-.321c.02-.995.601-1.38.849-1.509q.025-.008.053-.021l.054-.022a2.42 2.42 0 0 0 1.248-1.294l.086-.204a.277.277 0 0 1 .484-.053a4.05 4.05 0 0 0 3.344 1.755h3.377c.188 0 1.134.091 1.19 1.397l-.124 3.222c-.13 2.939-2.424 4.912-5.225 4.912c-2.802 0-5.097-1.973-5.226-4.912z");
}

.kdig6mnba {
  stop-color: var(--svg-color--fffabe, #FFFABE);
}

.kjd6s50kk {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m16.01 10.724l-.717 1.783a.565.565 0 0 0 .546.733h.824c.387 0 .66-.372.546-.733l-.557-1.783c-.12-.395-.517-.395-.642 0");
}

.krvd34mtu {
  stop-color: var(--svg-color--d59566, #D59566);
  stop-opacity: 0;
}

.kszwqub4g {
  stop-color: var(--svg-color--58496a, #58496A);
}

.kz_alab4a {
  fill: var(--svg-color--9f6836, #9F6836);
  fill-rule: evenodd;
  d: path("m20.334 8.614l-.144.24za.281.281 0 0 1-.288.482l-.006-.003l-.022-.012l-.096-.049a3 3 0 0 0-.36-.141a2.4 2.4 0 0 0-1.123-.097a.281.281 0 0 1-.098-.554a2.94 2.94 0 0 1 1.393.115a3.4 3.4 0 0 1 .586.25l.01.006z");
}

.l2oytfjhx {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.48 8.47c-.338-.083-1.18-.042-1.742.36");
}

.l382wkm5r {
  stop-color: var(--svg-color--595260, #595260);
}

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.llafqni9f {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.914 9.546c-.685 0-1.263.473-1.42 1.11a.288.288 0 0 0 .28.358h2.34a.24.24 0 0 0 .238-.285a1.47 1.47 0 0 0-1.438-1.183");
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mt3h7fbpd {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
}

.mu78_5yfl {
  d: path("M15.789 2.788C14.6 2.526 13.328 3.79 13.205 4.23c1.617 3.796 4.1 3.434 6.855 3.128c1.649-.183 1.828.568 1.968.932c-.457-4.254-3.533-4.904-6.24-5.502");
}

.mv8kv7beo {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
}

.mvuactshi {
  stop-color: var(--svg-color--c49070, #C49070);
  stop-opacity: 0;
}

.n4q03-1wn {
  stop-color: var(--svg-color--a4746c, #A4746C);
  stop-opacity: 0;
}

.njrkhhlfe {
  stop-color: var(--svg-color--70647f, #70647F);
  stop-opacity: 0;
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.npo8dko2g {
  d: path("m10.202 5.257l1.253-1.992l9.75-.11l1.36 2.063c-4.664 1.61-10.274.774-12.364.04");
}

.nxet2htkz {
  stop-color: var(--svg-color--57525d, #57525D);
  stop-opacity: 0;
}

.o_plwnvwa {
  d: path("M24.378 3.615H8.408c-.44 0-.8-.36-.8-.8s.36-.8.8-.8h15.96c.44 0 .8.36.8.8c.01.44-.35.8-.79.8");
}

.o_x20brsq {
  d: path("m16.02 10.579l-.557 1.782a.565.565 0 0 0 .546.734h.825c.386 0 .66-.372.546-.734l-.558-1.782c-.12-.395-.676-.395-.802 0");
}

.o2uld0acg {
  stop-color: var(--svg-color--433850, #433850);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojstgxewy {
  stop-color: var(--svg-color--70635d, #70635D);
}

.ovnjvmr2p {
  fill: var(--svg-color--000, #000);
  d: path("M14.667 10.767a.534.534 0 0 0-.536-.536a.534.534 0 0 0-.476.783h.948a.5.5 0 0 0 .064-.247");
}

.p_n49bb2s {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.39 4.098c.024.255.246 1.212.57 1.792");
}

.p-vpa1ykp {
  stop-color: var(--svg-color--faac28, #FAAC28);
}

.p0_cxvb5r {
  d: path("M20.076 23.782c0-.189.154-.341.345-.341s.346.152.346.34v6.094h-.691z");
}

.p1sg1mumi {
  stop-color: var(--svg-color--ffc3a8, #FFC3A8);
  stop-opacity: 0;
}

.p6otu2-6b {
  stop-color: var(--svg-color--ffffbe, #FFFFBE);
}

.pihdi6b6y {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M21.483 12.084a1.126 1.126 0 1 0 0-2.252a1.126 1.126 0 0 0 0 2.252");
}

.pk_j5sfiy {
  stop-color: var(--svg-color--33203c, #33203C);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pnxjkfbgy {
  stop-color: var(--svg-color--6a656f, #6A656F);
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.pts6vr7ld {
  stop-color: var(--svg-color--433850, #433850);
  stop-opacity: 0;
}

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.q5mih6mme {
  stop-color: var(--svg-color--e5ae90, #E5AE90);
}

.q8_1e9bvu {
  stop-color: var(--svg-color--1c0e20, #1C0E20);
}

.qf8jcy72s {
  d: path("M24.368 11.654a.838.838 0 1 0 .8 0z");
}

.qflnpfbur {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
}

.qjc5hlbod {
  d: path("M16.09 23.782c0-.189.154-.341.345-.341s.346.152.346.34v6.094h-.692z");
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qn1fgfb4u {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.455 8.47c.338-.083 1.18-.042 1.742.36");
}

.qs5b04nop {
  stop-color: var(--svg-color--70647f, #70647F);
}

.qug8uobre {
  d: path("M11.508 12.645a1.687 1.687 0 1 0 0-3.375a1.687 1.687 0 0 0 0 3.375");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-jog4w_t {
  stop-color: var(--svg-color--c2847a, #C2847A);
}

.r2v6fvpbl {
  stop-color: var(--svg-color--60546c, #60546C);
}

.r7selubyf {
  fill: var(--svg-color--56436b, #56436B);
  d: path("M16.44 15.505c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.rdlx2yyju {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.643 10.03c.066.088-.073.197-.231.316c-.159.118-.276.201-.343.112s.008-.257.166-.376c.159-.118.341-.142.408-.053");
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.rjxj417_v {
  stop-color: var(--svg-color--f9bfa4, #F9BFA4);
}

.rqa4zqbgs {
  d: path("M11.528 12.084a1.126 1.126 0 1 0 0-2.252a1.126 1.126 0 0 0 0 2.252");
}

.rxtdreblr {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M15.224 10.361c-.278-.49-.701-.876-1.612-.876c-.399 0-.783.11-1.125.386c-.282.228-.244.52-.026.629l.583.333c.684-.221 1.44-.251 2.18-.472");
}

.soq4ax0au {
  d: path("M11.29 4.651c.65-.58 1.59-.586 2.117-.492l.422 1.354c-.27-.041-.51.052-.712.246c-.475 1.757-2.267 1.494-2.619 2.812c-.158-1.564-.334-2.918.791-3.92");
}

.sqmgyf2vi {
  stop-color: var(--svg-color--c49070, #C49070);
}

.syayv9bph {
  stop-color: var(--svg-color--a76b71, #A76B71);
  stop-opacity: 0;
}

.t5ewf8b-q {
  stop-color: var(--svg-color--ce9591, #CE9591);
  stop-opacity: 0;
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.ta36f8b7v {
  stop-color: var(--svg-color--c7897d, #C7897D);
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.tjn9n03bv {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.619 10.361c.278-.49.701-.876 1.612-.876c.399 0 .783.11 1.125.386c.282.228.244.52.026.629l-.583.333c-.684-.221-1.44-.251-2.18-.472");
}

.u00fdvbgz {
  d: path("M14.986 10.657c0-.302-.246-.504-.312-.565l-.303.293l.186.379z");
}

.u0gj58p9u {
  d: path("M23.456 18.104a.24.24 0 0 0-.059-.29c-1.856-1.602-4.346-2.486-6.954-2.486s-5.113.893-6.97 2.487a.24.24 0 0 0-.06.29c1.276 2.6 3.756 4.613 7.03 4.613s5.73-2.014 7.013-4.614");
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.ud98q8dic {
  stop-color: var(--svg-color--c57e10, #C57E10);
}

.ue-yx0baa {
  stop-color: var(--svg-color--c58e72, #C58E72);
  stop-opacity: 0;
}

.ugp09kblg {
  d: path("M11.087 9.634h.013l-.011-.278l-.01-.321c.02-.995.601-1.38.849-1.509q.025-.008.053-.021l.054-.022a2.42 2.42 0 0 0 1.248-1.294l.086-.204a.277.277 0 0 1 .484-.053a4.05 4.05 0 0 0 3.344 1.755h3.377c.188 0 1.134.091 1.19 1.397l-.124 3.222c-.13 2.939-2.424 4.912-5.225 4.912c-2.802 0-5.097-1.973-5.226-4.912z");
}

.uo2hv248r {
  stop-color: var(--svg-color--75707b, #75707B);
  stop-opacity: 0;
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.uuiv6bbmv {
  stop-color: var(--svg-color--3f3748, #3F3748);
  stop-opacity: 0;
}

.uy3z2gbbp {
  stop-color: var(--svg-color--ffc59d, #FFC59D);
}

.uzp4m_b3p {
  stop-color: var(--svg-color--342542, #342542);
  stop-opacity: 0;
}

.v-9s4u7ch {
  stop-color: var(--svg-color--cf987b, #CF987B);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v9zstkjlw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.387 4.096c.024.255.246 1.213.572 1.794");
}

.vnszicyas {
  stop-color: var(--svg-color--160c20, #160C20);
}

.vrnylccvf {
  stop-color: var(--svg-color--dcc893, #DCC893);
}

.vxeaf7beg {
  stroke: var(--svg-color--1f0f21, #1F0F21);
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.141 18.875c.063.043.17.08.28.084a.56.56 0 0 0 .28-.084c1.017-.696 1.78-1.39 1.78-2.587v-3.633c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.633c0 1.197.763 1.89 1.78 2.587Z");
}

.vyevcqbzs {
  stop-color: var(--svg-color--c27b7c, #C27B7C);
}

.w58maet4h {
  stop-color: var(--svg-color--dac493, #DAC493);
  stop-opacity: 0;
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.warh7idvl {
  stop-color: var(--svg-color--b87c7e, #B87C7E);
  stop-opacity: 0;
}

.wcr1klbjh {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
  stop-opacity: 0;
}

.wmtmv1hbb {
  stop-color: var(--svg-color--a4746c, #A4746C);
}

.wntqft2su {
  stop-color: var(--svg-color--696070, #696070);
  stop-opacity: 0;
}

.ws5zlibzm {
  stop-color: var(--svg-color--a56d67, #A56D67);
}

.wzj86ub5h {
  d: path("M12.103 23.782c0-.189.155-.341.346-.341s.345.152.345.34v6.094h-.691z");
}

.xjkdvxqyn {
  stop-color: var(--svg-color--c2847a, #C2847A);
  stop-opacity: 0;
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.xlrmucced {
  stop-color: var(--svg-color--685352, #685352);
}

.xp7dwurxx {
  stop-color: var(--svg-color--433a4d, #433A4D);
}

.xxaet9bhw {
  stop-color: var(--svg-color--47404d, #47404D);
}

.ybvptdnhb {
  stop-color: var(--svg-color--c58e72, #C58E72);
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.yhs2bn2id {
  stop-color: var(--svg-color--f4c099, #F4C099);
}

.yihcw4vuy {
  stop-color: var(--svg-color--766c83, #766C83);
}

.ym5q1xkkz {
  stop-color: var(--svg-color--372e41, #372E41);
}

.yn026ikmt {
  stop-color: var(--svg-color--df8f14, #DF8F14);
  stop-opacity: 0;
}

.z6io75bpj {
  stop-color: var(--svg-color--5d516a, #5D516A);
  stop-opacity: 0;
}

.z7xukho-o {
  d: path("M16.44 15.505c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.za9vcfmjh {
  d: path("M14.131 9.832a.936.936 0 0 0-.902 1.182h1.808a1 1 0 0 0 .034-.247a.94.94 0 0 0-.94-.935");
}

.zcr9jykfw {
  stop-color: var(--svg-color--e6bd9f, #E6BD9F);
}

.znate9w9p {
  d: path("M18.643 10.03c.066.088-.073.197-.231.316c-.159.118-.276.201-.343.112s.008-.257.166-.376c.159-.118.341-.142.408-.053");
}

.zvl8nq86d {
  stop-color: var(--svg-color--3b2d3a, #3B2D3A);
}

.zwa3gh7uz {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m16.02 10.579l-.557 1.782a.565.565 0 0 0 .546.734h.825c.386 0 .66-.372.546-.734l-.558-1.782c-.12-.395-.676-.395-.802 0");
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
