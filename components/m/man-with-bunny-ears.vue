<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#in15wee)"><path fill="url(#iusgBEb)" class="brrxxpb5x"/><path fill="url(#iL1zbGc)" class="brrxxpb5x"/></g><g filter="url(#ibheBjN)"><path class="cbjvd6bfp"/></g><path fill="url(#iK0guUd)" class="an43ig2dc"/><path fill="url(#iWPNwhe)" class="an43ig2dc"/><path fill="url(#ilHHAwe)" class="s_1wbibnw"/><path fill="url(#iEfQumc)" class="s_1wbibnw"/><circle fill="url(#imuLy1d)" class="dm-e7pbsf"/><g filter="url(#iyYCI9c)"><path clip-rule="evenodd" class="qc6e_vbqu"/></g><circle fill="url(#i9ZTklb)" transform="matrix(-1 0 0 1 12.14 16.731)" class="kr_eiac3t"/><g filter="url(#iRYkk9i)"><path clip-rule="evenodd" class="t80vbiwix"/><path fill="url(#imSChvc)" clip-rule="evenodd" class="khv0hdcnj"/></g><path fill="url(#iOnZyCd)" class="yarz8ebrl"/><path fill="url(#iK4HDlr)" class="yarz8ebrl"/><path class="awypomszi"/><path fill="url(#izdN3IZ)" class="p-tbh5bdk"/><g filter="url(#i3SVlne)"><path class="bsl85jbne"/></g><path fill="url(#i4SRekd)" class="pm1fjwbdg"/><path fill="url(#i3FDIcb)" class="pm1fjwbdg"/><path fill="url(#icBjbZP)" class="pm1fjwbdg"/><path fill="url(#iPaW7Zc)" class="pm1fjwbdg"/><path fill="url(#ivTlAve)" class="pm1fjwbdg"/><path fill="url(#iYTqfOd)" class="gb9g1sbbs"/><circle fill="url(#iFO4Nud)" class="zqknkwbaq"/><g filter="url(#ijfwSdb)"><circle fill="url(#ic4dZTd)" class="f-u6jnbie"/></g><g filter="url(#itJY2xc)"><circle fill="url(#iYo38od)" class="ft_glm9rw"/><circle fill="url(#iwwBN6c)" class="ft_glm9rw"/></g><g filter="url(#iFLPuNb)"><circle class="boenmsspw"/><circle fill="url(#iQpBZCl)" class="a5d_u7_mf"/><circle fill="url(#iINozlv)" class="a5d_u7_mf"/></g><path fill="url(#iFVlQbb)" class="jumsgg5gx"/><path fill="url(#iomqGCe)" class="jumsgg5gx"/><path fill="url(#iWXOoLe)" class="jumsgg5gx"/><path fill="url(#icGTe4s)" class="jumsgg5gx"/><path fill="url(#inQaZse)" class="jumsgg5gx"/><g filter="url(#i3GSdog)"><path class="r2j9o_b7i"/><path fill="url(#iGuG1rb)" class="ilej3xkay"/><path fill="url(#i5byI6d)" class="ilej3xkay"/><path fill="url(#iX81LvX)" class="ilej3xkay"/><path fill="url(#iJ59ZKb)" class="ilej3xkay"/><path fill="url(#iPUCRCe)" class="ilej3xkay"/><path fill="url(#iCuemeb)" class="ilej3xkay"/></g><path fill="url(#iyyaA2S)" class="ilej3xkay"/><path fill="url(#iH6lJfd)" class="ilej3xkay"/><path fill="url(#i3F60Hb)" class="ilej3xkay"/><g filter="url(#iYBSdzb)"><path class="zrgnhm-5r"/></g><g filter="url(#ijmizxe)"><path class="uqz7zzb0h"/><path fill="url(#icLnfGc)" class="ahzvfhb1d"/><path fill="url(#iFrQW6d)" class="ahzvfhb1d"/><path fill="url(#i1KAIWc)" class="ahzvfhb1d"/></g><g filter="url(#i8YIxte)"><path stroke="url(#iqAa5mb)" class="unnml7jea"/></g><path class="vamdvcc5h"/><path class="arkdf5som"/><path fill="url(#iu9VOEI)" class="g28tvhbkp"/><path class="t83nmbbof"/><g filter="url(#iA7u6QF)"><path class="qmmthhojw"/><path fill="url(#io7u4Nb)" class="lfrhmwbkx"/></g><g filter="url(#iHzMD2H)"><path fill="url(#iAEWwKA)" class="hdgpgibvh"/></g><path class="k0u-ngcft"/><path fill="url(#i1Ut7Cc)" class="ritxrqbjd"/><path class="xeubqybnz"/><g filter="url(#iyDTyeb)"><path fill="url(#ic9iA1c)" class="g3trc2bfy"/></g><g filter="url(#i2vnlBb)"><ellipse transform="rotate(-27.914 7.768 7.487)" class="ks9m3_o4x"/><ellipse fill="url(#ikr9Rjq)" transform="rotate(-27.914 7.768 7.487)" class="o-8wqwbso"/></g><g filter="url(#igSENPb)"><path fill="url(#iVqZ3ub)" clip-rule="evenodd" class="eijp2bb6m"/></g><g filter="url(#iE4HRTb)"><path class="awoaelpse"/></g><g filter="url(#iz9n79d)"><path fill="url(#in20eGb)" clip-rule="evenodd" class="ne0rkjb6s"/></g><g filter="url(#i6dchpg)"><path class="dn9e2obcx"/></g><g filter="url(#ioJzPRd)"><path class="b51tlg1tn"/></g><g filter="url(#iGsl3ec)"><path class="fev3nnbhi"/></g><g filter="url(#iTQIlAQ)"><path fill="url(#ith6kPc)" class="ntw0_ssgv"/></g><g filter="url(#iqOqImd)"><path fill="url(#iRoB8fc)" class="fc_exf_ux"/><path fill="url(#iWTYxQe)" class="fc_exf_ux"/></g><g filter="url(#iDSzLod)"><path class="dghob6b2s"/></g><path fill="url(#iGvqf1d)" class="tl25mccse"/><path fill="url(#iYUoUJe)" class="tl25mccse"/><path fill="url(#iRgiT5A)" class="le113obmu"/><path fill="url(#iAv9Hit)" class="le113obmu"/><circle fill="url(#iYdP88c)" class="m4xmd9byr"/><g filter="url(#ivg8x6b)"><path clip-rule="evenodd" class="vk-vr3rwm"/></g><circle fill="url(#i9ZTklb)" transform="matrix(-1 0 0 1 25.185 16.747)" class="kr_eiac3t"/><g filter="url(#i4gWXie)"><path clip-rule="evenodd" class="jiz4nib7l"/><path fill="url(#itpZHpN)" clip-rule="evenodd" class="asik_rzpr"/></g><path fill="url(#iDczzQc)" class="rq9ikuarg"/><path fill="url(#iTslcab)" class="rq9ikuarg"/><path class="bm-7_963g"/><path fill="url(#i4x8gPS)" class="blu9w_bya"/><g filter="url(#ityEIxf)"><path class="jq7yl7bwq"/></g><path fill="url(#i94zAAc)" class="cflzptfun"/><path fill="url(#iIkBPMd)" class="cflzptfun"/><path fill="url(#iWGcIac)" class="cflzptfun"/><path fill="url(#iKZ3cWd)" class="cflzptfun"/><path fill="url(#i3sSymd)" class="cflzptfun"/><path fill="url(#iso2GKe)" class="l3u4k68ne"/><circle fill="url(#i5jIzLb)" class="xp5ahtq7f"/><g filter="url(#i0mzfuW)"><circle fill="url(#iyaNa5X)" class="e-4fkcbuz"/></g><g filter="url(#i0oEeAv)"><circle fill="url(#i9K35ac)" class="q33dm1bxk"/><circle fill="url(#ieVF7fb)" class="q33dm1bxk"/></g><g filter="url(#iLwGmNd)"><circle class="l-1sr9v5g"/><circle fill="url(#iVplUgb)" class="nn449xd3x"/><circle fill="url(#iRvDf2c)" class="nn449xd3x"/></g><path fill="url(#i8upvTo)" class="tcadiacmd"/><path fill="url(#iw3Tsjb)" class="tcadiacmd"/><path fill="url(#iwN6WWd)" class="tcadiacmd"/><path fill="url(#iN2cJOe)" class="tcadiacmd"/><path fill="url(#iq7TFrv)" class="tcadiacmd"/><g filter="url(#iRN9NYc)"><path class="i9dibbcni"/><path fill="url(#iFAH9Vd)" class="rxmh5dbys"/><path fill="url(#immQK9c)" class="rxmh5dbys"/><path fill="url(#i8FFpxe)" class="rxmh5dbys"/><path fill="url(#iLINLKe)" class="rxmh5dbys"/><path fill="url(#iP81Bee)" class="rxmh5dbys"/><path fill="url(#iltA3sc)" class="rxmh5dbys"/></g><path fill="url(#iS5jy9c)" class="rxmh5dbys"/><path fill="url(#iBe47ac)" class="rxmh5dbys"/><path fill="url(#i0kElOc)" class="rxmh5dbys"/><g filter="url(#ij5jFnb)"><path class="yis-dacff"/></g><g filter="url(#iwrBlll)"><path class="zxe6b7bzn"/><path fill="url(#iXMwdic)" class="c1oxi8b6y"/><path fill="url(#i0cG0qe)" class="c1oxi8b6y"/><path fill="url(#ipD6s2d)" class="c1oxi8b6y"/></g><g filter="url(#iz0D1Ub)"><path stroke="url(#iHQkLPy)" class="xgwnb0pce"/></g><path class="uwq9-p5ja"/><path class="r7v_erozj"/><path fill="url(#iHWzf0b)" class="oa5f3obxv"/><path class="iwnj_w_tn"/><g filter="url(#ij1tytb)"><path class="jkapuhb9x"/><path fill="url(#isKs4Be)" class="qo7j3eaav"/></g><g filter="url(#iCnaPyd)"><path fill="url(#i13U7OV)" class="z583t6gmm"/></g><path class="hp9rm1xmx"/><path fill="url(#iGpOcgb)" class="ejpudlexg"/><path class="cjr7xf-5f"/><g filter="url(#iTMta2d)"><path fill="url(#i7PH2Qc)" class="zoc58ibqw"/></g><g filter="url(#iSxOyBc)"><ellipse transform="rotate(-27.914 20.813 7.503)" class="rc7e5toqp"/><ellipse fill="url(#izxEczb)" transform="rotate(-27.914 20.813 7.503)" class="dn8isehio"/></g><g filter="url(#iNYW2de)"><path fill="url(#idReFGe)" clip-rule="evenodd" class="i97urpjhs"/></g><g filter="url(#igOHXqd)"><path class="nhm3vwygr"/></g><g filter="url(#iJzwyib)"><path fill="url(#ii5VPHd)" clip-rule="evenodd" class="yw8xc6b7t"/></g><g filter="url(#iS6aXqe)"><path class="qe4ydsf1g"/></g><g filter="url(#i6dDRac)"><path class="aw7q5kbkv"/></g><g filter="url(#if25Hwd)"><path class="v47p2u02b"/></g><g filter="url(#i1ADwPj)"><path fill="url(#izwTnnO)" class="j--a27bat"/></g><defs><radialGradient id="iK0guUd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04689 2.23436 -1.0009 -.46896 7.541 28.106)" gradientUnits="userSpaceOnUse"><stop class="i7j8_4zgt"/><stop offset="1" class="g4nv9obue"/></radialGradient><radialGradient id="iWPNwhe" cx="0" cy="0" r="1" gradientTransform="rotate(51.34 -26.577 21.05)scale(1.30063 3.1796)" gradientUnits="userSpaceOnUse"><stop offset=".522" class="enwi01lgk"/><stop offset="1" class="mta_69bbu"/></radialGradient><radialGradient id="ilHHAwe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3576 -2.25 .95212 -.57449 16.203 29.856)" gradientUnits="userSpaceOnUse"><stop class="kuw77jfnz"/><stop offset="1" class="boon_rjzq"/></radialGradient><radialGradient id="iEfQumc" cx="0" cy="0" r="1" gradientTransform="matrix(-.81249 1.26563 -2.71996 -1.74612 15.494 28.403)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="hi3bu5i6r"/><stop offset="1" class="atfd_nb4o"/></radialGradient><radialGradient id="imuLy1d" cx="0" cy="0" r="1" gradientTransform="rotate(67.546 -9.814 12.187)scale(.82843)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="u61ql_uag"/><stop offset="1" class="x_wj4vl5i"/></radialGradient><radialGradient id="i9ZTklb" cx="0" cy="0" r="1" gradientTransform="rotate(38.794 -1.108 .325)scale(1.30308)" gradientUnits="userSpaceOnUse"><stop class="stug43bab"/><stop offset="1" class="kmwt4ebda"/></radialGradient><radialGradient id="imSChvc" cx="0" cy="0" r="1" gradientTransform="matrix(2.74585 1.47356 -.61307 1.1424 13.192 12.304)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="p_drcebab"/><stop offset="1" class="tdgu1u54k"/></radialGradient><radialGradient id="i4SRekd" cx="0" cy="0" r="1" gradientTransform="matrix(-.36017 -5.09375 2.6333 -.1862 9.51 21.84)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="gjropwo4q"/><stop offset="1" class="agepe-_9u"/></radialGradient><radialGradient id="icBjbZP" cx="0" cy="0" r="1" gradientTransform="rotate(-114.905 11.968 7.274)scale(2.97425 .93316)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eox5rpbuq"/><stop offset="1" class="g1mnylbkn"/></radialGradient><radialGradient id="iPaW7Zc" cx="0" cy="0" r="1" gradientTransform="rotate(140.681 3.763 7.834)scale(3.2691 3.07426)" gradientUnits="userSpaceOnUse"><stop class="k0aq2sbpu"/><stop offset="1" class="a3709fbcn"/></radialGradient><radialGradient id="ivTlAve" cx="0" cy="0" r="1" gradientTransform="rotate(-80.342 16.493 5.685)scale(2.72794 1.1406)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="vobictbgt"/><stop offset="1" class="f97z0ccja"/></radialGradient><radialGradient id="iYTqfOd" cx="0" cy="0" r="1" gradientTransform="matrix(.39369 1.63031 -2.125 .51315 8.334 10.262)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="cbz98_bgl"/><stop offset=".902" class="jtnx86cjw"/></radialGradient><radialGradient id="iFO4Nud" cx="0" cy="0" r="1" gradientTransform="matrix(.74518 0 0 1.30407 6.086 7.817)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="iwwBN6c" cx="0" cy="0" r="1" gradientTransform="matrix(.35105 -.25562 .29175 .40068 10.993 7.705)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="iQpBZCl" cx="0" cy="0" r="1" gradientTransform="matrix(.34874 -.64143 .37543 .20412 10.817 8.166)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="iINozlv" cx="0" cy="0" r="1" gradientTransform="matrix(.1101 .10899 -.1405 .14194 10.835 7.817)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="iWXOoLe" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.64577 -4.16281 0 9.02 7.142)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="l58-idrcp"/><stop offset="1" class="kcal37bgz"/></radialGradient><radialGradient id="icGTe4s" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.55503 .68312 0 9.807 7.277)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="inQaZse" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.59061 .73448 0 7.872 7.263)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="iGuG1rb" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 4.077 4.813)scale(2.38059 4.04841)" gradientUnits="userSpaceOnUse"><stop class="ck410xb1o"/><stop offset="1" class="qeh0r4bjq"/></radialGradient><radialGradient id="iX81LvX" cx="0" cy="0" r="1" gradientTransform="matrix(-.07834 -.8461 .41554 -.03848 7.055 6.272)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="euj6xpbnj"/><stop offset="1" class="hchnd0bsx"/></radialGradient><radialGradient id="iJ59ZKb" cx="0" cy="0" r="1" gradientTransform="matrix(.36482 -.83504 .68104 .29754 10.606 7.08)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ghdrqrbfe"/><stop offset="1" class="d7zypgbet"/></radialGradient><radialGradient id="iPUCRCe" cx="0" cy="0" r="1" gradientTransform="rotate(51.134 -.112 10.947)scale(.67183 .59317)" gradientUnits="userSpaceOnUse"><stop class="wn92vfpti"/><stop offset="1" class="t4clght5m"/></radialGradient><radialGradient id="iCuemeb" cx="0" cy="0" r="1" gradientTransform="matrix(.61615 -1.28904 .44538 .21289 10.59 6.026)" gradientUnits="userSpaceOnUse"><stop class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="iyyaA2S" cx="0" cy="0" r="1" gradientTransform="rotate(75.569 1.867 7.956)scale(.44501 .73161)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="s_ha1fylz"/><stop offset="1" class="e0ciekbtt"/></radialGradient><radialGradient id="iH6lJfd" cx="0" cy="0" r="1" gradientTransform="matrix(.47005 .67897 -1.4129 .97816 6.95 4.7)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="pb3_oi83v"/><stop offset="1" class="gt3e5dbiv"/></radialGradient><radialGradient id="i3F60Hb" cx="0" cy="0" r="1" gradientTransform="rotate(155.748 4.01 3.981)scale(3.3568 4.20032)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="gmm-ghbsu"/><stop offset=".959" class="g3s2gbbst"/></radialGradient><radialGradient id="iqAa5mb" cx="0" cy="0" r="1" gradientTransform="rotate(-87.754 9.338 .198)scale(.26657 .79969)" gradientUnits="userSpaceOnUse"><stop class="zjmwko4fr"/><stop offset="1" class="md9bsbc9k"/></radialGradient><radialGradient id="iu9VOEI" cx="0" cy="0" r="1" gradientTransform="matrix(0 .38351 -.4538 0 9.736 7.67)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="io7u4Nb" cx="0" cy="0" r="1" gradientTransform="matrix(-.09822 -.12656 .17425 -.13523 9.64 7.563)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i1Ut7Cc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .38353 -.45382 0 7.884 7.67)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ikr9Rjq" cx="0" cy="0" r="1" gradientTransform="matrix(-.00328 -.20924 .25152 -.00394 7.762 7.62)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iVqZ3ub" cx="0" cy="0" r="1" gradientTransform="matrix(.08356 -.3447 .75623 .18333 9.852 6.883)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><radialGradient id="in20eGb" cx="0" cy="0" r="1" gradientTransform="rotate(-103.627 6.592 .386)scale(.35469 .77813)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><radialGradient id="iGvqf1d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04689 2.23436 -1.0009 -.46896 20.586 28.122)" gradientUnits="userSpaceOnUse"><stop class="i7j8_4zgt"/><stop offset="1" class="g4nv9obue"/></radialGradient><radialGradient id="iYUoUJe" cx="0" cy="0" r="1" gradientTransform="rotate(51.34 -20.07 34.629)scale(1.30063 3.1796)" gradientUnits="userSpaceOnUse"><stop offset=".522" class="enwi01lgk"/><stop offset="1" class="mta_69bbu"/></radialGradient><radialGradient id="iRgiT5A" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3576 -2.25 .95212 -.57449 29.249 29.872)" gradientUnits="userSpaceOnUse"><stop class="kuw77jfnz"/><stop offset="1" class="boon_rjzq"/></radialGradient><radialGradient id="iAv9Hit" cx="0" cy="0" r="1" gradientTransform="matrix(-.81249 1.26563 -2.71996 -1.74612 28.54 28.419)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="hi3bu5i6r"/><stop offset="1" class="atfd_nb4o"/></radialGradient><radialGradient id="iYdP88c" cx="0" cy="0" r="1" gradientTransform="rotate(67.546 -3.303 21.948)scale(.82843)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="u61ql_uag"/><stop offset="1" class="x_wj4vl5i"/></radialGradient><radialGradient id="itpZHpN" cx="0" cy="0" r="1" gradientTransform="matrix(2.74585 1.47356 -.61307 1.1424 26.237 12.32)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="p_drcebab"/><stop offset="1" class="tdgu1u54k"/></radialGradient><radialGradient id="i94zAAc" cx="0" cy="0" r="1" gradientTransform="matrix(-.36017 -5.09375 2.6333 -.1862 22.556 21.856)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="gjropwo4q"/><stop offset="1" class="agepe-_9u"/></radialGradient><radialGradient id="iWGcIac" cx="0" cy="0" r="1" gradientTransform="rotate(-114.905 18.495 3.119)scale(2.97425 .93316)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eox5rpbuq"/><stop offset="1" class="g1mnylbkn"/></radialGradient><radialGradient id="iKZ3cWd" cx="0" cy="0" r="1" gradientTransform="rotate(140.681 10.283 10.172)scale(3.2691 3.07426)" gradientUnits="userSpaceOnUse"><stop class="k0aq2sbpu"/><stop offset="1" class="a3709fbcn"/></radialGradient><radialGradient id="i3sSymd" cx="0" cy="0" r="1" gradientTransform="rotate(-80.342 23.025 -2.033)scale(2.72794 1.1406)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="vobictbgt"/><stop offset="1" class="f97z0ccja"/></radialGradient><radialGradient id="iso2GKe" cx="0" cy="0" r="1" gradientTransform="matrix(.39369 1.63031 -2.125 .51315 21.38 10.278)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="cbz98_bgl"/><stop offset=".902" class="jtnx86cjw"/></radialGradient><radialGradient id="i5jIzLb" cx="0" cy="0" r="1" gradientTransform="matrix(.74518 0 0 1.30407 19.131 7.833)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="ieVF7fb" cx="0" cy="0" r="1" gradientTransform="matrix(.35105 -.25562 .29175 .40068 24.038 7.72)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="iVplUgb" cx="0" cy="0" r="1" gradientTransform="matrix(.34874 -.64143 .37543 .20412 23.863 8.182)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="iRvDf2c" cx="0" cy="0" r="1" gradientTransform="matrix(.1101 .10899 -.1405 .14194 23.88 7.833)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="iwN6WWd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.64577 -4.16281 0 22.065 7.157)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="l58-idrcp"/><stop offset="1" class="kcal37bgz"/></radialGradient><radialGradient id="iN2cJOe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.55503 .68312 0 22.852 7.293)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="iq7TFrv" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.59061 .73448 0 20.917 7.279)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="iFAH9Vd" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 10.596 8.016)scale(2.38059 4.04841)" gradientUnits="userSpaceOnUse"><stop class="ck410xb1o"/><stop offset="1" class="qeh0r4bjq"/></radialGradient><radialGradient id="i8FFpxe" cx="0" cy="0" r="1" gradientTransform="matrix(-.07834 -.8461 .41554 -.03848 20.1 6.288)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="euj6xpbnj"/><stop offset="1" class="hchnd0bsx"/></radialGradient><radialGradient id="iLINLKe" cx="0" cy="0" r="1" gradientTransform="matrix(.36482 -.83504 .68104 .29754 23.651 7.095)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ghdrqrbfe"/><stop offset="1" class="d7zypgbet"/></radialGradient><radialGradient id="iP81Bee" cx="0" cy="0" r="1" gradientTransform="rotate(51.134 6.394 24.589)scale(.67183 .59317)" gradientUnits="userSpaceOnUse"><stop class="wn92vfpti"/><stop offset="1" class="t4clght5m"/></radialGradient><radialGradient id="iltA3sc" cx="0" cy="0" r="1" gradientTransform="matrix(.61615 -1.28904 .44538 .21289 23.635 6.041)" gradientUnits="userSpaceOnUse"><stop class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="iS5jy9c" cx="0" cy="0" r="1" gradientTransform="rotate(75.569 8.38 16.377)scale(.44501 .73161)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="s_ha1fylz"/><stop offset="1" class="e0ciekbtt"/></radialGradient><radialGradient id="iBe47ac" cx="0" cy="0" r="1" gradientTransform="rotate(55.305 5.498 21.44)scale(.8258 1.71846)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="pb3_oi83v"/><stop offset="1" class="gt3e5dbiv"/></radialGradient><radialGradient id="i0kElOc" cx="0" cy="0" r="1" gradientTransform="rotate(155.748 10.53 5.39)scale(3.3568 4.20032)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="gmm-ghbsu"/><stop offset=".959" class="g3s2gbbst"/></radialGradient><radialGradient id="iHQkLPy" cx="0" cy="0" r="1" gradientTransform="rotate(-87.754 15.87 -6.578)scale(.26657 .79969)" gradientUnits="userSpaceOnUse"><stop class="zjmwko4fr"/><stop offset="1" class="md9bsbc9k"/></radialGradient><radialGradient id="iHWzf0b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .38351 -.4538 0 22.781 7.685)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="isKs4Be" cx="0" cy="0" r="1" gradientTransform="matrix(-.09822 -.12656 .17425 -.13523 22.685 7.578)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iGpOcgb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .38353 -.45382 0 20.929 7.685)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="izxEczb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00328 -.20924 .25152 -.00394 20.807 7.636)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="idReFGe" cx="0" cy="0" r="1" gradientTransform="matrix(.08356 -.3447 .75623 .18333 22.897 6.899)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><radialGradient id="ii5VPHd" cx="0" cy="0" r="1" gradientTransform="rotate(-103.627 13.12 -4.737)scale(.35469 .77813)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><filter id="in15wee" width="3.097" height="9.794" x="5.815" y="20.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.717647 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_705"/></filter><filter id="ibheBjN" width="7.428" height="10.091" x="8.776" y="19.934" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.901961 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_705"/></filter><filter id="iyYCI9c" width="5.896" height="7.11" x="2.751" y="10.148" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.541176 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_705"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.541176 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_705" result="effect2_innerShadow_4002_705"/></filter><filter id="iRYkk9i" width="5.996" height="6.96" x="9.267" y="10.298" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.588235 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_705"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.588235 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_705" result="effect2_innerShadow_4002_705"/></filter><filter id="i3SVlne" width="9.692" height="11.056" x="4.665" y="9.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.196078 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_705"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.32549 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_705" result="effect2_innerShadow_4002_705"/></filter><filter id="ijfwSdb" width="1.845" height="1.845" x="5.873" y="6.895" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_705" stdDeviation=".25"/></filter><filter id="itJY2xc" width="1.668" height="1.668" x="10.126" y="6.858" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_705"/></filter><filter id="iFLPuNb" width="1.845" height="1.845" x="9.912" y="6.895" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_705" stdDeviation=".25"/></filter><filter id="i3GSdog" width="5.351" height="3.516" x="6.136" y="4.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.584314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_705"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.572549 0 0 0 0 0.0156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_705" result="effect2_innerShadow_4002_705"/></filter><filter id="iYBSdzb" width="2.247" height="2.639" x="7.586" y="6.895" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_705" stdDeviation=".375"/></filter><filter id="ijmizxe" width=".897" height="1.239" x="8.363" y="7.526" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_705" stdDeviation=".025"/></filter><filter id="i8YIxte" width="1.766" height=".856" x="7.928" y="8.799" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_705" stdDeviation=".05"/></filter><filter id="iA7u6QF" width=".449" height=".41" x="9.367" y="7.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_705" stdDeviation=".05"/></filter><filter id="iHzMD2H" width=".608" height=".617" x="9.666" y="7.258" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_705" stdDeviation=".1"/></filter><filter id="iyDTyeb" width=".648" height=".671" x="7.78" y="7.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_705" stdDeviation=".1"/></filter><filter id="i2vnlBb" width=".502" height=".414" x="7.517" y="7.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_705" stdDeviation=".05"/></filter><filter id="igSENPb" width="1.105" height=".843" x="9.348" y="6.225" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_705"/></filter><filter id="iE4HRTb" width="1.104" height=".592" x="9.348" y="6.429" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_705" stdDeviation=".075"/></filter><filter id="iz9n79d" width="1.105" height=".843" x="7.17" y="6.225" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_705"/></filter><filter id="i6dchpg" width="1.104" height=".592" x="7.17" y="6.429" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_705" stdDeviation=".075"/></filter><filter id="ioJzPRd" width="1.73" height="2.911" x="6.683" y="1.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_705"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_705" result="effect2_innerShadow_4002_705"/></filter><filter id="iGsl3ec" width="1.73" height="2.911" x="9.394" y="1.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_705"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_705" result="effect2_innerShadow_4002_705"/></filter><filter id="iTQIlAQ" width="4.792" height="2.36" x="6.658" y="3.741" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.180392 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_705"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.219608 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_705" result="effect2_innerShadow_4002_705"/></filter><filter id="iqOqImd" width="3.097" height="9.794" x="18.86" y="20.247" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.717647 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_705"/></filter><filter id="iDSzLod" width="7.428" height="10.091" x="21.821" y="19.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.901961 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_705"/></filter><filter id="ivg8x6b" width="5.896" height="7.11" x="15.796" y="10.164" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.541176 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_705"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.541176 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_705" result="effect2_innerShadow_4002_705"/></filter><filter id="i4gWXie" width="5.996" height="6.96" x="22.312" y="10.314" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.588235 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_705"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.588235 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_705" result="effect2_innerShadow_4002_705"/></filter><filter id="ityEIxf" width="9.692" height="11.056" x="17.71" y="9.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.196078 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_705"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.32549 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_705" result="effect2_innerShadow_4002_705"/></filter><filter id="i0mzfuW" width="1.845" height="1.845" x="18.918" y="6.91" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_705" stdDeviation=".25"/></filter><filter id="i0oEeAv" width="1.668" height="1.668" x="23.171" y="6.874" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_705"/></filter><filter id="iLwGmNd" width="1.845" height="1.845" x="22.957" y="6.91" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_705" stdDeviation=".25"/></filter><filter id="iRN9NYc" width="5.351" height="3.516" x="19.181" y="4.081" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.584314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_705"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.572549 0 0 0 0 0.0156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_705" result="effect2_innerShadow_4002_705"/></filter><filter id="ij5jFnb" width="2.247" height="2.639" x="20.631" y="6.911" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_705" stdDeviation=".375"/></filter><filter id="iwrBlll" width=".897" height="1.239" x="21.408" y="7.542" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_705" stdDeviation=".025"/></filter><filter id="iz0D1Ub" width="1.766" height=".856" x="20.973" y="8.815" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_705" stdDeviation=".05"/></filter><filter id="ij1tytb" width=".449" height=".41" x="22.412" y="7.299" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_705" stdDeviation=".05"/></filter><filter id="iCnaPyd" width=".608" height=".617" x="22.711" y="7.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_705" stdDeviation=".1"/></filter><filter id="iTMta2d" width=".648" height=".671" x="20.825" y="7.246" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_705" stdDeviation=".1"/></filter><filter id="iSxOyBc" width=".502" height=".414" x="20.562" y="7.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_705" stdDeviation=".05"/></filter><filter id="iNYW2de" width="1.105" height=".843" x="22.393" y="6.241" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_705"/></filter><filter id="igOHXqd" width="1.104" height=".592" x="22.393" y="6.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_705" stdDeviation=".075"/></filter><filter id="iJzwyib" width="1.105" height=".843" x="20.215" y="6.241" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_705"/></filter><filter id="iS6aXqe" width="1.104" height=".592" x="20.215" y="6.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_705" stdDeviation=".075"/></filter><filter id="i6dDRac" width="1.73" height="2.911" x="19.728" y="1.775" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_705"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_705" result="effect2_innerShadow_4002_705"/></filter><filter id="if25Hwd" width="1.73" height="2.911" x="22.439" y="1.775" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_705"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_705" result="effect2_innerShadow_4002_705"/></filter><filter id="i1ADwPj" width="4.792" height="2.36" x="19.703" y="3.757" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.180392 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_705"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.219608 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_705" result="effect2_innerShadow_4002_705"/></filter><linearGradient id="iusgBEb" x1="5.915" x2="7.807" y1="24.122" y2="24.309" gradientUnits="userSpaceOnUse"><stop class="ffo_sl6yt"/><stop offset="1" class="c9hzilbuh"/></linearGradient><linearGradient id="iL1zbGc" x1="5.807" x2="6.354" y1="24.809" y2="24.809" gradientUnits="userSpaceOnUse"><stop class="iwqqxcc-f"/><stop offset="1" class="ws-68yb9o"/></linearGradient><linearGradient id="iOnZyCd" x1="5.338" x2="6.26" y1="11.45" y2="13.382" gradientUnits="userSpaceOnUse"><stop class="f56564bqg"/><stop offset=".527" class="b7vrc56qi"/></linearGradient><linearGradient id="iK4HDlr" x1="5.854" x2="5.494" y1="13.169" y2="12.544" gradientUnits="userSpaceOnUse"><stop class="b9gdpcb9a"/><stop offset="1" class="exo3i6t1h"/></linearGradient><linearGradient id="izdN3IZ" x1="12.088" x2="12.526" y1="13.168" y2="12.075" gradientUnits="userSpaceOnUse"><stop class="g8x7j95jh"/><stop offset="1" class="t8-ux1zkq"/></linearGradient><linearGradient id="i3FDIcb" x1="5.729" x2="6.401" y1="19.247" y2="19.231" gradientUnits="userSpaceOnUse"><stop offset=".262" class="mlh1k8r8i"/><stop offset="1" class="tigrkbwnp"/></linearGradient><linearGradient id="ic4dZTd" x1="6.795" x2="6.523" y1="7.935" y2="7.935" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="iYo38od" x1="11.296" x2="10.949" y1="7.354" y2="8.431" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="iFVlQbb" x1="10.525" x2="7.282" y1="7.983" y2="8.466" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset=".916" class="as9qb1byz"/></linearGradient><linearGradient id="iomqGCe" x1="6.52" x2="7.502" y1="9.127" y2="8.999" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="i5byI6d" x1="6.747" x2="7.979" y1="7.704" y2="5.515" gradientUnits="userSpaceOnUse"><stop class="kyzs66gfi"/><stop offset="1" class="zsx4vmb0f"/></linearGradient><linearGradient id="icLnfGc" x1="8.444" x2="8.843" y1="8.263" y2="8.263" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="iFrQW6d" x1="9.21" x2="8.774" y1="8.4" y2="8.393" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="i1KAIWc" x1="8.894" x2="8.894" y1="8.715" y2="8.471" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="iAEWwKA" x1="10.066" x2="9.933" y1="7.55" y2="7.632" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ic9iA1c" x1="8.199" x2="8.066" y1="7.55" y2="7.632" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ith6kPc" x1="10.697" x2="7.197" y1="5.2" y2="5.387" gradientUnits="userSpaceOnUse"><stop class="ak32k0b7k"/><stop offset="1" class="cgzrukeil"/></linearGradient><linearGradient id="iRoB8fc" x1="18.96" x2="20.852" y1="24.137" y2="24.325" gradientUnits="userSpaceOnUse"><stop class="ffo_sl6yt"/><stop offset="1" class="c9hzilbuh"/></linearGradient><linearGradient id="iWTYxQe" x1="18.852" x2="19.399" y1="24.825" y2="24.825" gradientUnits="userSpaceOnUse"><stop class="iwqqxcc-f"/><stop offset="1" class="ws-68yb9o"/></linearGradient><linearGradient id="iDczzQc" x1="18.383" x2="19.305" y1="11.466" y2="13.398" gradientUnits="userSpaceOnUse"><stop class="f56564bqg"/><stop offset=".527" class="b7vrc56qi"/></linearGradient><linearGradient id="iTslcab" x1="18.899" x2="18.539" y1="13.184" y2="12.559" gradientUnits="userSpaceOnUse"><stop class="b9gdpcb9a"/><stop offset="1" class="exo3i6t1h"/></linearGradient><linearGradient id="i4x8gPS" x1="25.133" x2="25.571" y1="13.184" y2="12.09" gradientUnits="userSpaceOnUse"><stop class="g8x7j95jh"/><stop offset="1" class="t8-ux1zkq"/></linearGradient><linearGradient id="iIkBPMd" x1="18.774" x2="19.446" y1="19.262" y2="19.247" gradientUnits="userSpaceOnUse"><stop offset=".262" class="mlh1k8r8i"/><stop offset="1" class="tigrkbwnp"/></linearGradient><linearGradient id="iyaNa5X" x1="19.84" x2="19.568" y1="7.951" y2="7.951" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="i9K35ac" x1="24.341" x2="23.994" y1="7.369" y2="8.446" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="i8upvTo" x1="23.57" x2="20.327" y1="7.998" y2="8.481" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset=".916" class="as9qb1byz"/></linearGradient><linearGradient id="iw3Tsjb" x1="19.565" x2="20.547" y1="9.143" y2="9.015" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="immQK9c" x1="19.792" x2="21.024" y1="7.72" y2="5.531" gradientUnits="userSpaceOnUse"><stop class="kyzs66gfi"/><stop offset="1" class="zsx4vmb0f"/></linearGradient><linearGradient id="iXMwdic" x1="21.489" x2="21.888" y1="8.278" y2="8.278" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="i0cG0qe" x1="22.255" x2="21.819" y1="8.415" y2="8.409" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="ipD6s2d" x1="21.939" x2="21.939" y1="8.73" y2="8.487" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="i13U7OV" x1="23.111" x2="22.979" y1="7.566" y2="7.648" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i7PH2Qc" x1="21.244" x2="21.111" y1="7.566" y2="7.648" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="izwTnnO" x1="23.743" x2="20.243" y1="5.215" y2="5.403" gradientUnits="userSpaceOnUse"><stop class="ak32k0b7k"/><stop offset="1" class="cgzrukeil"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-with-bunny-ears" /></template>
<style>
.a3709fbcn {
  stop-color: var(--svg-color--6f597b, #6F597B);
  stop-opacity: 0;
}

.a5d_u7_mf {
  cx: 10.835px;
  cy: 7.817px;
  r: 0.423px;
}

.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.agepe-_9u {
  stop-color: var(--svg-color--472263, #472263);
  stop-opacity: 0;
}

.ahzvfhb1d {
  d: path("m8.649 7.696l-.226.722a.23.23 0 0 0 .221.297h.334a.23.23 0 0 0 .221-.297l-.226-.722c-.048-.16-.274-.16-.324 0");
}

.ak32k0b7k {
  stop-color: var(--svg-color--695d73, #695D73);
}

.an43ig2dc {
  d: path("m7.883 28.184l-.034.258a1.83 1.83 0 0 1-1.812 1.583a.12.12 0 0 1-.122-.122v-1.719z");
}

.arkdf5som {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.825 7.21c.277 0 .512.191.575.45a.116.116 0 0 1-.113.144H9.34a.098.098 0 0 1-.097-.115a.59.59 0 0 1 .582-.48");
}

.as9qb1byz {
  stop-color: var(--svg-color--f9a528, #F9A528);
}

.asik_rzpr {
  fill-rule: evenodd;
  d: path("M22.414 10.723a.8.8 0 0 0 .308 1.09l3.527 1.977a.2.2 0 0 1 .034.325l-1.9 1.763a.8.8 0 0 0 1.068 1.19l1.973-1.72c.93-.82.856-2.148-.347-2.918l-3.574-2.014a.8.8 0 0 0-1.09.307");
}

.atfd_nb4o {
  stop-color: var(--svg-color--4c266b, #4C266B);
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.aw7q5kbkv {
  fill: var(--svg-color--62476a, #62476A);
  d: path("M19.981 3.281c.222.71.522 1.165.645 1.305l.633-.242c-.014-.183-.097-.709-.325-1.356c-.285-.808-.578-1.09-.875-.996c-.21.086-.355.402-.078 1.29");
}

.awoaelpse {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M10.252 6.82c-.089-.081-.34-.22-.704-.186");
}

.awypomszi {
  fill: var(--svg-color--675074, #675074);
  d: path("m12.504 13.382l-2.828-1.586a.8.8 0 0 1-.307-1.088c.216-.386.36-.72.747-.504l3.202 1.808z");
}

.b51tlg1tn {
  fill: var(--svg-color--62476a, #62476A);
  d: path("M6.936 3.265c.222.71.522 1.166.645 1.305l.633-.242c-.013-.182-.096-.709-.325-1.356c-.285-.808-.578-1.09-.875-.996c-.21.086-.355.403-.078 1.29");
}

.b7vrc56qi {
  stop-color: var(--svg-color--5b3c65, #5B3C65);
}

.b9gdpcb9a {
  stop-color: var(--svg-color--472162, #472162);
}

.blu9w_bya {
  d: path("m25.549 13.397l-2.827-1.585a.8.8 0 0 1-.308-1.089c.216-.385.361-.72.747-.504l3.202 1.809z");
}

.bm-7_963g {
  fill: var(--svg-color--675074, #675074);
  d: path("m25.549 13.397l-2.827-1.585a.8.8 0 0 1-.308-1.089c.216-.385.361-.72.747-.504l3.202 1.809z");
}

.boenmsspw {
  cx: 10.835px;
  cy: 7.817px;
  r: 0.423px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.boon_rjzq {
  stop-color: var(--svg-color--4c2d62, #4C2D62);
}

.brrxxpb5x {
  d: path("m5.915 20.231l2.997.27l-1.063 7.94a1.83 1.83 0 0 1-1.812 1.584a.12.12 0 0 1-.122-.122z");
}

.bsl85jbne {
  fill: var(--svg-color--654470, #654470);
  d: path("M8.787 9.935a2.87 2.87 0 0 0-2.872 2.871v8.185h2.932l.207-1.55a.175.175 0 0 1 .33-.055l.79 1.605h2.933l-1.33-3.705a2 2 0 0 1-.118-.676v-3.803a2.87 2.87 0 0 0-2.872-2.872");
}

.c1oxi8b6y {
  d: path("m21.694 7.712l-.226.722a.23.23 0 0 0 .221.296h.334a.23.23 0 0 0 .221-.296l-.225-.722c-.049-.16-.274-.16-.325 0");
}

.c9hzilbuh {
  stop-color: var(--svg-color--ffd142, #FFD142);
}

.cbjvd6bfp {
  fill: var(--svg-color--ec9534, #EC9534);
  d: path("m12.729 19.934l-2.703.719l3.604 7.839a2.64 2.64 0 0 0 2.397 1.533c.122 0 .207-.12.167-.234z");
}

.cbz98_bgl {
  stop-color: var(--svg-color--eb840b, #EB840B);
}

.cflzptfun {
  d: path("M21.832 9.95a2.87 2.87 0 0 0-2.872 2.872v8.185h2.932l.207-1.551a.175.175 0 0 1 .33-.054l.791 1.605h2.932l-1.33-3.705a2 2 0 0 1-.118-.676v-3.804a2.87 2.87 0 0 0-2.872-2.872");
}

.cgzrukeil {
  stop-color: var(--svg-color--5a3e62, #5A3E62);
}

.cjr7xf-5f {
  fill: var(--svg-color--000, #000);
  d: path("M21.145 7.72a.216.216 0 0 0-.217-.217a.216.216 0 0 0-.193.316h.384a.2.2 0 0 0 .026-.1");
}

.ck410xb1o {
  stop-color: var(--svg-color--ffe336, #FFE336);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d7zypgbet {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
  stop-opacity: 0;
}

.dghob6b2s {
  fill: var(--svg-color--ec9534, #EC9534);
  d: path("m25.774 19.95l-2.703.719l3.604 7.838a2.64 2.64 0 0 0 2.398 1.534c.121 0 .206-.12.166-.234z");
}

.dm-e7pbsf {
  cx: 5.514px;
  cy: 16.602px;
  r: 0.766px;
}

.dn8isehio {
  cx: 20.813px;
  cy: 7.503px;
  rx: 0.165px;
  ry: 0.084px;
}

.dn9e2obcx {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M7.37 6.82c.09-.081.341-.22.704-.186");
}

.e-4fkcbuz {
  cx: 19.84px;
  cy: 7.833px;
  r: 0.423px;
}

.e0ciekbtt {
  stop-color: var(--svg-color--ffc926, #FFC926);
  stop-opacity: 0;
}

.eijp2bb6m {
  fill-rule: evenodd;
  d: path("M9.567 6.88c.306-.028.502.091.55.135a.2.2 0 0 0 .271-.295c-.13-.12-.438-.278-.858-.239a.2.2 0 1 0 .037.4");
}

.ejpudlexg {
  d: path("M20.928 7.34a.38.38 0 0 0-.365.48h.732a.38.38 0 0 0-.367-.479");
}

.enwi01lgk {
  stop-color: var(--svg-color--522e71, #522E71);
  stop-opacity: 0;
}

.eox5rpbuq {
  stop-color: var(--svg-color--463049, #463049);
}

.euj6xpbnj {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
}

.exo3i6t1h {
  stop-color: var(--svg-color--472162, #472162);
  stop-opacity: 0;
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.f-u6jnbie {
  cx: 6.795px;
  cy: 7.817px;
  r: 0.423px;
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.f56564bqg {
  stop-color: var(--svg-color--4d364f, #4D364F);
}

.f97z0ccja {
  stop-color: var(--svg-color--5c4c68, #5C4C68);
  stop-opacity: 0;
}

.fc_exf_ux {
  d: path("m18.96 20.247l2.997.27l-1.063 7.94a1.83 1.83 0 0 1-1.812 1.584a.12.12 0 0 1-.122-.122z");
}

.fev3nnbhi {
  fill: var(--svg-color--62476a, #62476A);
  d: path("M10.771 3.265c-.222.71-.522 1.166-.644 1.305l-.633-.242c.013-.182.096-.709.324-1.356c.285-.808.578-1.09.875-.996c.211.086.356.403.078 1.29");
}

.ffo_sl6yt {
  stop-color: var(--svg-color--e79f2e, #E79F2E);
}

.ft_glm9rw {
  cx: 10.835px;
  cy: 7.817px;
  r: 0.709px;
}

.ft5dv1b6b {
  fill: none;
}

.g1mnylbkn {
  stop-color: var(--svg-color--463049, #463049);
  stop-opacity: 0;
}

.g28tvhbkp {
  d: path("M9.737 7.325a.38.38 0 0 1 .365.479H9.37a.38.38 0 0 1 .367-.479");
}

.g3s2gbbst {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
}

.g3trc2bfy {
  d: path("M8.228 7.659c0-.122-.099-.204-.126-.228l-.122.118l.075.153z");
}

.g4nv9obue {
  stop-color: var(--svg-color--44384d, #44384D);
}

.g8x7j95jh {
  stop-color: var(--svg-color--461e67, #461E67);
}

.gb9g1sbbs {
  d: path("m8.617 11.767l-.865-1.505h2.125l-.825 1.501a.25.25 0 0 1-.435.004");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghdrqrbfe {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
}

.gjropwo4q {
  stop-color: var(--svg-color--472263, #472263);
}

.gmm-ghbsu {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
  stop-opacity: 0;
}

.gt3e5dbiv {
  stop-color: var(--svg-color--f29322, #F29322);
  stop-opacity: 0;
}

.hchnd0bsx {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
  stop-opacity: 0;
}

.hdgpgibvh {
  d: path("M10.074 7.654a.36.36 0 0 0-.098-.196l-.11.12l.05.097z");
}

.hi3bu5i6r {
  stop-color: var(--svg-color--4c266b, #4C266B);
  stop-opacity: 0;
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.hp9rm1xmx {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.84 7.225a.59.59 0 0 0-.575.45a.116.116 0 0 0 .114.145h.947c.06 0 .108-.055.096-.116a.595.595 0 0 0-.582-.479");
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i7j8_4zgt {
  stop-color: var(--svg-color--59436a, #59436A);
}

.i97urpjhs {
  fill-rule: evenodd;
  d: path("M22.612 6.896c.306-.028.502.091.55.135a.2.2 0 0 0 .27-.295c-.13-.12-.437-.278-.857-.239a.2.2 0 0 0 .037.4");
}

.i9dibbcni {
  fill: var(--svg-color--ffa91b, #FFA91B);
  d: path("m23.903 5.082l.182.09c.319.16.5.522.432.907l-.25 1.29c-.022.134-.11.224-.243.227c.015-.214.03-.559.035-.613c.018-.184-.01-.238-.18-.406a.53.53 0 0 1-.159-.362v-.363a.24.24 0 0 0-.182-.226a7 7 0 0 0-1.663-.181c-.82 0-1.39.113-1.662.18a.22.22 0 0 0-.183.227v.363a.45.45 0 0 1-.16.362l-.067.068c-.091.068-.137.21-.137.323c.006.066.014.446.025.605a.27.27 0 0 1-.253-.226l-.25-1.29a.87.87 0 0 1 .455-.884c.43-.189.587-.475.934-.77a.83.83 0 0 1 .934-.136c.228.068.478.068.706 0a1.02 1.02 0 0 1 1.002.226l.342.34a.95.95 0 0 0 .341.25");
}

.ilej3xkay {
  d: path("m10.858 5.067l.182.09c.319.159.5.521.433.906l-.251 1.291c-.022.133-.11.223-.243.226c.015-.213.03-.558.035-.613c.018-.184-.01-.238-.18-.406a.53.53 0 0 1-.159-.362v-.362a.244.244 0 0 0-.182-.227a7 7 0 0 0-1.663-.18c-.82 0-1.389.113-1.662.181a.22.22 0 0 0-.183.227V6.2a.45.45 0 0 1-.159.362l-.068.068c-.091.068-.137.21-.137.323c.006.066.015.447.025.605a.27.27 0 0 1-.253-.226l-.25-1.29a.87.87 0 0 1 .455-.884c.43-.188.588-.475.934-.77a.83.83 0 0 1 .934-.136c.228.068.478.068.706 0a1.02 1.02 0 0 1 1.002.227l.342.34a.95.95 0 0 0 .342.249");
}

.iwnj_w_tn {
  fill: var(--svg-color--000, #000);
  d: path("M22.565 7.72c0-.121.097-.217.217-.217a.216.216 0 0 1 .193.316h-.384a.2.2 0 0 1-.026-.1");
}

.iwqqxcc-f {
  stop-color: var(--svg-color--d9a14c, #D9A14C);
}

.j--a27bat {
  d: path("M24.093 5.759c.019.096-.102.144-.167.07c-.453-.513-1.132-1.011-2.022-1.011c-.84 0-1.554.533-2.034 1.064c-.064.072-.182.025-.166-.07a2.231 2.231 0 0 1 4.389-.053");
}

.jiz4nib7l {
  fill: var(--svg-color--ffc93a, #FFC93A);
  fill-rule: evenodd;
  d: path("M22.414 10.723a.8.8 0 0 0 .308 1.09l3.527 1.977a.2.2 0 0 1 .034.325l-1.9 1.763a.8.8 0 0 0 1.068 1.19l1.973-1.72c.93-.82.856-2.148-.347-2.918l-3.574-2.014a.8.8 0 0 0-1.09.307");
}

.jkapuhb9x {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M22.754 7.421c.027.036-.03.08-.094.128s-.11.081-.138.045c-.027-.036.003-.104.067-.151c.064-.048.138-.058.165-.022");
}

.jq7yl7bwq {
  fill: var(--svg-color--654470, #654470);
  d: path("M21.832 9.95a2.87 2.87 0 0 0-2.872 2.872v8.185h2.932l.207-1.551a.175.175 0 0 1 .33-.054l.791 1.605h2.932l-1.33-3.705a2 2 0 0 1-.118-.676v-3.804a2.87 2.87 0 0 0-2.872-2.872");
}

.jtnx86cjw {
  stop-color: var(--svg-color--ffc737, #FFC737);
}

.jumsgg5gx {
  d: path("M6.646 7.557a13 13 0 0 1-.025-.61c0-.114.045-.25.137-.318l.068-.068a.45.45 0 0 0 .16-.362v-.363a.22.22 0 0 1 .182-.226a7 7 0 0 1 1.662-.181c.82 0 1.39.113 1.663.181a.24.24 0 0 1 .182.226V6.2c0 .136.068.272.16.362c.213.15.2.232.182.408c-.006.054-.023.507-.038.611l-.113 1.681c-.068.752-.659 1.275-1.363 1.275H8.14c-.727 0-1.295-.523-1.364-1.275z");
}

.k0aq2sbpu {
  stop-color: var(--svg-color--6f597b, #6F597B);
}

.k0u-ngcft {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.795 7.21a.59.59 0 0 0-.575.45a.116.116 0 0 0 .113.144h.948c.06 0 .108-.055.096-.115a.595.595 0 0 0-.582-.48");
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.kcal37bgz {
  stop-color: var(--svg-color--d07f50, #D07F50);
}

.khv0hdcnj {
  fill-rule: evenodd;
  d: path("M9.369 10.708a.8.8 0 0 0 .308 1.089l3.527 1.977a.2.2 0 0 1 .034.325l-1.9 1.763a.8.8 0 1 0 1.068 1.191l1.973-1.72c.93-.82.856-2.149-.347-2.918L10.458 10.4a.8.8 0 0 0-1.089.308");
}

.kmwt4ebda {
  stop-color: var(--svg-color--cf7d4f, #CF7D4F);
}

.kr_eiac3t {
  r: 0.766px;
}

.ks9m3_o4x {
  cx: 7.768px;
  cy: 7.487px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.165px;
  ry: 0.084px;
}

.kuw77jfnz {
  stop-color: var(--svg-color--645a6f, #645A6F);
}

.kyzs66gfi {
  stop-color: var(--svg-color--e07027, #E07027);
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l-1sr9v5g {
  cx: 23.88px;
  cy: 7.833px;
  r: 0.423px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.l3u4k68ne {
  d: path("m21.662 11.783l-.865-1.505h2.125l-.824 1.5a.25.25 0 0 1-.436.005");
}

.l58-idrcp {
  stop-color: var(--svg-color--f49a3e, #F49A3E);
  stop-opacity: 0;
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.le113obmu {
  d: path("M28.675 28.2h-2.142l.142.307a2.64 2.64 0 0 0 2.398 1.534c.12 0 .206-.12.166-.234z");
}

.lfrhmwbkx {
  d: path("M9.709 7.405c.027.036-.03.08-.094.128s-.111.082-.138.046s.003-.104.067-.152s.138-.058.165-.022");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.m4xmd9byr {
  cx: 18.559px;
  cy: 16.618px;
  r: 0.766px;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbmro29rs {
  stop-color: var(--svg-color--ffe833, #FFE833);
}

.md9bsbc9k {
  stop-color: var(--svg-color--ffbe30, #FFBE30);
  stop-opacity: 0;
}

.mlh1k8r8i {
  stop-color: var(--svg-color--656069, #656069);
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.mrt-5h0hn {
  stop-color: var(--svg-color--c64f38, #C64F38);
}

.mta_69bbu {
  stop-color: var(--svg-color--522e71, #522E71);
}

.ne0rkjb6s {
  fill-rule: evenodd;
  d: path("M8.056 6.88c-.306-.028-.502.091-.55.135a.2.2 0 0 1-.271-.295c.13-.12.438-.278.858-.239a.2.2 0 1 1-.037.4");
}

.nhm3vwygr {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.297 6.836c-.089-.081-.34-.22-.704-.186");
}

.nn449xd3x {
  cx: 23.88px;
  cy: 7.833px;
  r: 0.423px;
}

.ntw0_ssgv {
  d: path("M11.048 5.743c.018.097-.102.144-.167.07c-.453-.513-1.133-1.01-2.023-1.01c-.838 0-1.553.532-2.033 1.064c-.064.071-.182.025-.166-.07a2.231 2.231 0 0 1 4.389-.054");
}

.o-8wqwbso {
  cx: 7.768px;
  cy: 7.487px;
  rx: 0.165px;
  ry: 0.084px;
}

.oa5f3obxv {
  d: path("M22.782 7.34a.38.38 0 0 1 .365.48h-.732a.38.38 0 0 1 .367-.479");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.p_drcebab {
  stop-color: var(--svg-color--ffdb40, #FFDB40);
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p-tbh5bdk {
  d: path("m12.504 13.382l-2.828-1.586a.8.8 0 0 1-.307-1.088c.216-.386.36-.72.747-.504l3.202 1.808z");
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.pb3_oi83v {
  stop-color: var(--svg-color--c9993e, #C9993E);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pm1fjwbdg {
  d: path("M8.787 9.935a2.87 2.87 0 0 0-2.872 2.871v8.185h2.932l.207-1.55a.175.175 0 0 1 .33-.055l.79 1.605h2.933l-1.33-3.705a2 2 0 0 1-.118-.676v-3.803a2.87 2.87 0 0 0-2.872-2.872");
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.q33dm1bxk {
  cx: 23.88px;
  cy: 7.833px;
  r: 0.709px;
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qc6e_vbqu {
  fill: var(--svg-color--ffbc3b, #FFBC3B);
  fill-rule: evenodd;
  d: path("M8.395 10.708a.8.8 0 0 1-.307 1.089L4.56 13.774a.2.2 0 0 0-.035.325l1.9 1.763a.8.8 0 0 1-1.068 1.191l-1.973-1.72c-.93-.82-.855-2.149.347-2.918L7.307 10.4a.8.8 0 0 1 1.088.308");
}

.qe4ydsf1g {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M20.416 6.836c.088-.081.34-.22.703-.186");
}

.qeh0r4bjq {
  stop-color: var(--svg-color--ffe336, #FFE336);
  stop-opacity: 0;
}

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
  stop-opacity: 0;
}

.qmmthhojw {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M9.709 7.405c.027.036-.03.08-.094.128s-.111.082-.138.046s.003-.104.067-.152s.138-.058.165-.022");
}

.qo7j3eaav {
  d: path("M22.754 7.421c.027.036-.03.08-.094.128s-.11.081-.138.045c-.027-.036.003-.104.067-.151c.064-.048.138-.058.165-.022");
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r2j9o_b7i {
  fill: var(--svg-color--ffa91b, #FFA91B);
  d: path("m10.858 5.067l.182.09c.319.159.5.521.433.906l-.251 1.291c-.022.133-.11.223-.243.226c.015-.213.03-.558.035-.613c.018-.184-.01-.238-.18-.406a.53.53 0 0 1-.159-.362v-.362a.244.244 0 0 0-.182-.227a7 7 0 0 0-1.663-.18c-.82 0-1.389.113-1.662.181a.22.22 0 0 0-.183.227V6.2a.45.45 0 0 1-.159.362l-.068.068c-.091.068-.137.21-.137.323c.006.066.015.447.025.605a.27.27 0 0 1-.253-.226l-.25-1.29a.87.87 0 0 1 .455-.884c.43-.188.588-.475.934-.77a.83.83 0 0 1 .934-.136c.228.068.478.068.706 0a1.02 1.02 0 0 1 1.002.227l.342.34a.95.95 0 0 0 .342.249");
}

.r7v_erozj {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.87 7.225c.278 0 .512.192.575.45a.116.116 0 0 1-.113.145h-.947a.098.098 0 0 1-.097-.116a.59.59 0 0 1 .582-.479");
}

.rc7e5toqp {
  cx: 20.813px;
  cy: 7.503px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.165px;
  ry: 0.084px;
}

.ritxrqbjd {
  d: path("M7.883 7.325a.38.38 0 0 0-.365.479h.732a.38.38 0 0 0-.367-.479");
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rq9ikuarg {
  d: path("m18.306 13.398l2.827-1.586a.8.8 0 0 0-.781-1.396l-2.86 1.612z");
}

.rxmh5dbys {
  d: path("m23.903 5.082l.182.09c.319.16.5.522.432.907l-.25 1.29c-.022.134-.11.224-.243.227c.015-.214.03-.559.035-.613c.018-.184-.01-.238-.18-.406a.53.53 0 0 1-.159-.362v-.363a.24.24 0 0 0-.182-.226a7 7 0 0 0-1.663-.181c-.82 0-1.39.113-1.662.18a.22.22 0 0 0-.183.227v.363a.45.45 0 0 1-.16.362l-.067.068c-.091.068-.137.21-.137.323c.006.066.014.446.025.605a.27.27 0 0 1-.253-.226l-.25-1.29a.87.87 0 0 1 .455-.884c.43-.189.587-.475.934-.77a.83.83 0 0 1 .934-.136c.228.068.478.068.706 0a1.02 1.02 0 0 1 1.002.226l.342.34a.95.95 0 0 0 .341.25");
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.s_1wbibnw {
  d: path("M15.63 28.184h-2.142l.142.308a2.64 2.64 0 0 0 2.397 1.533c.122 0 .207-.12.166-.234z");
}

.s_ha1fylz {
  stop-color: var(--svg-color--ddb13b, #DDB13B);
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.stug43bab {
  stop-color: var(--svg-color--ebb432, #EBB432);
}

.t4clght5m {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
  stop-opacity: 0;
}

.t8-ux1zkq {
  stop-color: var(--svg-color--461e67, #461E67);
  stop-opacity: 0;
}

.t80vbiwix {
  fill: var(--svg-color--ffc93a, #FFC93A);
  fill-rule: evenodd;
  d: path("M9.369 10.708a.8.8 0 0 0 .308 1.089l3.527 1.977a.2.2 0 0 1 .034.325l-1.9 1.763a.8.8 0 1 0 1.068 1.191l1.973-1.72c.93-.82.856-2.149-.347-2.918L10.458 10.4a.8.8 0 0 0-1.089.308");
}

.t83nmbbof {
  fill: var(--svg-color--000, #000);
  d: path("M9.52 7.704c0-.12.097-.217.217-.217a.216.216 0 0 1 .193.317h-.384a.2.2 0 0 1-.026-.1");
}

.tcadiacmd {
  d: path("M19.69 7.573a13 13 0 0 1-.024-.611c0-.113.046-.25.137-.317l.068-.068a.45.45 0 0 0 .16-.363v-.362a.22.22 0 0 1 .182-.226a7 7 0 0 1 1.662-.182c.82 0 1.39.114 1.663.182a.24.24 0 0 1 .182.226v.362c0 .136.069.272.16.363c.213.15.2.231.182.407c-.005.055-.023.508-.038.612l-.113 1.68c-.068.752-.659 1.276-1.363 1.276h-1.363c-.727 0-1.295-.524-1.363-1.275z");
}

.tdgu1u54k {
  stop-color: var(--svg-color--ffdb40, #FFDB40);
  stop-opacity: 0;
}

.tigrkbwnp {
  stop-color: var(--svg-color--47364e, #47364E);
  stop-opacity: 0;
}

.tl25mccse {
  d: path("m20.929 28.2l-.035.257a1.83 1.83 0 0 1-1.812 1.584a.12.12 0 0 1-.122-.122V28.2z");
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.u61ql_uag {
  stop-color: var(--svg-color--db8723, #DB8723);
}

.unnml7jea {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M8.811 9.146a1.26 1.26 0 0 1-.588-.14c-.058-.029-.12.037-.084.09c.142.215.39.359.672.359s.53-.144.672-.36c.037-.054-.026-.118-.084-.088c-.17.089-.37.14-.588.14Z");
}

.uqz7zzb0h {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m8.649 7.696l-.226.722a.23.23 0 0 0 .221.297h.334a.23.23 0 0 0 .221-.297l-.226-.722c-.048-.16-.274-.16-.324 0");
}

.uwq9-p5ja {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M21.856 9.162a1.26 1.26 0 0 1-.588-.14c-.058-.029-.12.036-.084.09c.142.215.39.358.672.358s.53-.143.672-.359c.037-.055-.025-.118-.084-.088c-.17.088-.37.139-.588.139");
}

.v47p2u02b {
  fill: var(--svg-color--62476a, #62476A);
  d: path("M23.816 3.281c-.221.71-.522 1.165-.644 1.305l-.633-.242c.013-.183.096-.709.324-1.356c.285-.808.578-1.09.875-.996c.211.086.356.402.078 1.29");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vamdvcc5h {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M8.811 9.146a1.26 1.26 0 0 1-.588-.14c-.058-.029-.12.037-.084.09c.142.215.39.359.672.359s.53-.144.672-.36c.037-.054-.026-.118-.084-.088c-.17.089-.37.14-.588.14");
}

.vk-vr3rwm {
  fill: var(--svg-color--ffbc3b, #FFBC3B);
  fill-rule: evenodd;
  d: path("M21.44 10.723a.8.8 0 0 1-.307 1.09l-3.527 1.977a.2.2 0 0 0-.034.325l1.9 1.763a.8.8 0 0 1-1.069 1.19l-1.973-1.72c-.93-.82-.855-2.148.348-2.918l3.574-2.014a.8.8 0 0 1 1.089.307");
}

.vobictbgt {
  stop-color: var(--svg-color--5c4c68, #5C4C68);
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.wn92vfpti {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.ws-68yb9o {
  stop-color: var(--svg-color--f6a928, #F6A928);
  stop-opacity: 0;
}

.x_wj4vl5i {
  stop-color: var(--svg-color--ce7557, #CE7557);
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.xaad_wcir {
  stop-color: var(--svg-color--bb4f29, #BB4F29);
}

.xeubqybnz {
  fill: var(--svg-color--000, #000);
  d: path("M8.1 7.704a.216.216 0 0 0-.217-.217a.216.216 0 0 0-.193.317h.384a.2.2 0 0 0 .026-.1");
}

.xgwnb0pce {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M21.856 9.162a1.26 1.26 0 0 1-.588-.14c-.058-.029-.12.036-.084.09c.142.215.39.358.672.358s.53-.143.672-.359c.037-.055-.025-.118-.084-.088c-.17.088-.37.139-.588.139Z");
}

.xp5ahtq7f {
  cx: 19.84px;
  cy: 7.833px;
  r: 0.709px;
}

.yarz8ebrl {
  d: path("m5.26 13.382l2.828-1.585a.8.8 0 0 0-.781-1.397l-2.86 1.612z");
}

.yis-dacff {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m21.74 7.78l-.349.723c-.043.148.06.297.207.297h.313c.147 0 .25-.151.208-.297l-.212-.722c-.045-.16-.12-.16-.168 0");
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.yw8xc6b7t {
  fill-rule: evenodd;
  d: path("M21.1 6.896c-.305-.028-.501.091-.549.135a.2.2 0 0 1-.271-.295c.13-.12.438-.278.858-.239a.2.2 0 0 1-.038.4");
}

.z583t6gmm {
  d: path("M23.12 7.67a.36.36 0 0 0-.099-.197l-.11.121l.05.097z");
}

.zjmwko4fr {
  stop-color: var(--svg-color--ffd069, #FFD069);
}

.zoc58ibqw {
  d: path("M21.274 7.675c0-.123-.1-.204-.127-.229l-.122.119l.075.153z");
}

.zqknkwbaq {
  cx: 6.795px;
  cy: 7.817px;
  r: 0.709px;
}

.zrgnhm-5r {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m8.694 7.765l-.348.722c-.043.148.06.297.207.297h.313c.147 0 .25-.15.207-.297l-.211-.722c-.046-.16-.12-.16-.168 0");
}

.zsx4vmb0f {
  stop-color: var(--svg-color--e07027, #E07027);
  stop-opacity: 0;
}

.zxe6b7bzn {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m21.694 7.712l-.226.722a.23.23 0 0 0 .221.296h.334a.23.23 0 0 0 .221-.296l-.225-.722c-.049-.16-.274-.16-.325 0");
}

</style>
