<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i6iBL5b)" class="ka8y65brc"/><path fill="url(#iNR9gPc)" class="ka8y65brc"/><path fill="url(#iQbHrle)" class="x7nlr16tt"/><path fill="url(#iTbR8Pb)" class="x7nlr16tt"/><path fill="url(#i2rfXcd)" class="kxilzmbvy"/><path fill="url(#iVRVvyc)" class="kxilzmbvy"/><path fill="url(#imRagKd)" class="kxilzmbvy"/><path fill="url(#ioIW29b)" class="ls3v4_3of"/><path fill="url(#iiKQXhe)" class="ls3v4_3of"/><path fill="url(#i6qt9Lc)" class="ls3v4_3of"/><path fill="url(#iFuzeIc)" class="ls3v4_3of"/><g filter="url(#iL3QYAc)"><path class="rz3b_obgl"/></g><path fill="url(#i5ZjtEb)" class="rgw_qhbte"/><g filter="url(#ilpphIb)"><path class="u4k_nbava"/></g><g filter="url(#ijQqFDb)"><path fill="url(#itJlr4c)" class="gx4c8g7wr"/><path fill="url(#ijWWBde)" class="gx4c8g7wr"/><path fill="url(#iBcr9qc)" class="gx4c8g7wr"/></g><path fill="url(#iqoQ2Cd)" class="gx4c8g7wr"/><g filter="url(#ixUPbYb)"><path class="hmqw7nbre"/></g><g filter="url(#iMv3ySc)"><path fill="url(#icCmq7b)" class="innd1ftrr"/><path fill="url(#ijO2xrd)" class="innd1ftrr"/></g><path fill="url(#ifm1zAq)" class="oldhekbqi"/><path fill="url(#iuBiwNe)" class="oldhekbqi"/><path fill="url(#i2IgAkc)" class="oldhekbqi"/><path fill="url(#iVF54ld)" class="oldhekbqi"/><path fill="url(#ibzCmUR)" class="j0v64o33h"/><circle fill="url(#i812j4M)" class="ajo6d3bof"/><g filter="url(#ixc3sQb)"><circle fill="url(#iWQ62Tb)" class="rg7f1vb8b"/></g><g filter="url(#iWhE4lb)"><circle fill="url(#iik447s)" class="fuvdo9dba"/><circle fill="url(#ijcP58d)" class="fuvdo9dba"/></g><g filter="url(#iB5q7AS)"><circle class="m2htywblo"/><circle fill="url(#ibnwPdb)" class="ve2vn_bdi"/><circle fill="url(#ipSIOlc)" class="ve2vn_bdi"/></g><path fill="url(#i8Z42Lb)" class="k7t32nxif"/><path fill="url(#i2RwTDE)" class="k7t32nxif"/><path fill="url(#iqDH0Tb)" class="k7t32nxif"/><path fill="url(#ijZh6fb)" class="k7t32nxif"/><path fill="url(#ipIZ6rd)" class="k7t32nxif"/><path fill="url(#iuilS1o)" class="k7t32nxif"/><g filter="url(#i5qxRrd)"><path class="gqa088q0k"/><path fill="url(#iNEzGgd)" class="c9i4jabqz"/><path fill="url(#iJOKlNb)" class="c9i4jabqz"/><path fill="url(#i14voQb)" class="c9i4jabqz"/><path fill="url(#iynuj6d)" class="c9i4jabqz"/><path fill="url(#i734fHc)" class="c9i4jabqz"/><path fill="url(#iS6G4Ab)" class="c9i4jabqz"/></g><path fill="url(#iQrPgeb)" class="c9i4jabqz"/><path fill="url(#illXOlc)" class="c9i4jabqz"/><path fill="url(#ibTYEWd)" class="c9i4jabqz"/><path fill="url(#iEPeQCc)" class="c9i4jabqz"/><g filter="url(#iM93uSb)"><path class="qoa6ovvda"/></g><g filter="url(#iJwLksd)"><path class="a3wd1bbwe"/><path fill="url(#ibWuquc)" class="m35awxblz"/><path fill="url(#iQ4eE3c)" class="m35awxblz"/><path fill="url(#iOEAHQe)" class="m35awxblz"/><path fill="url(#iZMYnMe)" class="m35awxblz"/></g><g filter="url(#iybBHce)"><path stroke="url(#iWRaECd)" class="qdmya3bdh"/></g><path class="etnb2bbvc"/><path class="afgy4ccwo"/><path fill="url(#iTmshEc)" class="fykpegb6n"/><path class="gmroupkwz"/><g filter="url(#i4AFVSc)"><path class="kekenabmz"/><path fill="url(#iNxoTNe)" class="u1ryexbrh"/></g><g filter="url(#itkF0jc)"><path fill="url(#i2ayJMc)" class="kf63_jbnw"/></g><path class="ta0dozbyl"/><path fill="url(#i0geuhb)" class="v63qpu3zx"/><path class="jjvm35b5v"/><g filter="url(#iUI0dlb)"><path fill="url(#i1NMGAL)" class="zaowg_8mi"/></g><g filter="url(#iJ9nUBb)"><ellipse transform="rotate(-27.914 13.5 9.765)" class="aca7cbain"/><ellipse fill="url(#imdg2mK)" transform="rotate(-27.914 13.5 9.765)" class="a66olmrmb"/></g><g filter="url(#i9bCaBe)"><path fill="url(#iS6GDMd)" class="tfksx7okm"/></g><g filter="url(#ioZpmsb)"><path class="lm6_trdgy"/></g><g filter="url(#iznCuod)"><path fill="url(#iX8Eymc)" class="ekddxwb3z"/></g><path fill="url(#ig2ymVc)" class="fo-6ebk8r"/><path fill="url(#icC6kWc)" class="fo-6ebk8r"/><path fill="url(#ihiG5jc)" class="fo-6ebk8r"/><g filter="url(#ideyFCd)"><path fill="url(#iT4vKVb)" class="vse7rwbtm"/></g><path fill="url(#i2Sa44d)" class="m5fsy5uld"/><path fill="url(#iY7fauc)" class="m5fsy5uld"/><path fill="url(#iFkux7c)" class="m5fsy5uld"/><g filter="url(#imlVWOc)"><path class="ejnoaybri"/></g><g filter="url(#iwnJ6Vu)"><path fill="url(#iZorvEx)" class="pduqyx0mq"/><path fill="url(#is6qyvc)" class="pduqyx0mq"/></g><g filter="url(#iljQ33b)"><path fill="url(#ipWwmDb)" class="nakrar40o"/></g><g filter="url(#iutPWBc)"><path fill="url(#ixLnjCd)" class="l0wwovb8s"/></g><path fill="url(#is3eXvV)" class="l0wwovb8s"/><defs><radialGradient id="iNR9gPc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.03125 0 0 -12.2293 23.197 24.394)" gradientUnits="userSpaceOnUse"><stop offset=".202" class="s59tlt20i"/><stop offset="1" class="dimomr5au"/></radialGradient><radialGradient id="iQbHrle" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.4916 2.16348 0 25.036 29.991)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="izw19gb1b"/><stop offset="1" class="pk_fxjb0k"/></radialGradient><radialGradient id="iTbR8Pb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.6896 .7187 0 23.104 29.991)" gradientUnits="userSpaceOnUse"><stop offset=".304" class="v7hn87gdb"/><stop offset="1" class="yfv60kbve"/></radialGradient><radialGradient id="i2rfXcd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.94746 4.23507 0 6.589 29.991)" gradientUnits="userSpaceOnUse"><stop offset=".26" class="ydmi_gbdg"/><stop offset="1" class="j_s_0lsgx"/></radialGradient><radialGradient id="imRagKd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.70333 0 0 -15.6939 8.682 29.627)" gradientUnits="userSpaceOnUse"><stop offset=".741" class="kolzjh1uk"/><stop offset="1" class="oqr8hmbdg"/></radialGradient><radialGradient id="ioIW29b" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.91012 -3.40129 0 15.973 23.046)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="w4yfy3zsx"/><stop offset="1" class="b0hon_b8a"/></radialGradient><radialGradient id="iFuzeIc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.1875 .46252 0 18.228 30.206)" gradientUnits="userSpaceOnUse"><stop class="zj0khrbgv"/><stop offset="1" class="rndoiibli"/></radialGradient><radialGradient id="i5ZjtEb" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.70312 -1.55313 0 15.964 21.035)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="g-uemq__p"/><stop offset=".907" class="ny-qt-bge"/></radialGradient><radialGradient id="ijWWBde" cx="0" cy="0" r="1" gradientTransform="rotate(122.782 2.483 11.888)scale(3.60548 4.04568)" gradientUnits="userSpaceOnUse"><stop class="hqfmlmg6f"/><stop offset="1" class="oyco1db5g"/></radialGradient><radialGradient id="iBcr9qc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.08638 -1.3984 0 13.268 23.21)" gradientUnits="userSpaceOnUse"><stop class="n-1p2p9pr"/><stop offset="1" class="v-e2dxczh"/></radialGradient><radialGradient id="ijO2xrd" cx="0" cy="0" r="1" gradientTransform="matrix(.8125 1.37956 -1.6894 .99499 19.01 15.858)" gradientUnits="userSpaceOnUse"><stop class="mgj3nfyon"/><stop offset="1" class="e6sjkybst"/></radialGradient><radialGradient id="ifm1zAq" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.15625 -4.85106 0 15.978 18.68)" gradientUnits="userSpaceOnUse"><stop offset=".519" class="dsfnryq2l"/><stop offset="1" class="e3skdu--u"/></radialGradient><radialGradient id="iuBiwNe" cx="0" cy="0" r="1" gradientTransform="matrix(-1 -.96876 2.18983 -2.26044 15.213 19.675)" gradientUnits="userSpaceOnUse"><stop class="ng9k9ab_a"/><stop offset="1" class="o-y5a1rmp"/></radialGradient><radialGradient id="ibzCmUR" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.0625 -1.9196 0 15.978 17.144)" gradientUnits="userSpaceOnUse"><stop class="sqsfsibnz"/><stop offset="1" class="oipp6lzec"/></radialGradient><radialGradient id="i812j4M" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 9.535 10.544)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="ijcP58d" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 21.1 10.279)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="ibnwPdb" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.687 11.366)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="ipSIOlc" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.728 10.544)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="iqDH0Tb" cx="0" cy="0" r="1" gradientTransform="matrix(-.09376 8.40625 -9.59841 -.10705 16.627 8.832)" gradientUnits="userSpaceOnUse"><stop offset=".703" class="kbhcrw6bx"/><stop offset="1" class="zvkziabgo"/></radialGradient><radialGradient id="ijZh6fb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 18.306 9.271)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="ipIZ6rd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39218 1.7313 0 13.744 9.238)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="iuilS1o" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.28125 -6.40625 0 15.752 7.457)" gradientUnits="userSpaceOnUse"><stop offset=".4" class="ckk71jgrk"/><stop offset="1" class="pa3in2xtx"/></radialGradient><radialGradient id="iNEzGgd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.43982 4.18042 -7.20199 -5.9261 19.654 3.232)" gradientUnits="userSpaceOnUse"><stop class="ck410xb1o"/><stop offset="1" class="qeh0r4bjq"/></radialGradient><radialGradient id="i14voQb" cx="0" cy="0" r="1" gradientTransform="rotate(-95.608 9.118 -1.818)scale(1.88957 .98316)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="euj6xpbnj"/><stop offset="1" class="hchnd0bsx"/></radialGradient><radialGradient id="iynuj6d" cx="0" cy="0" r="1" gradientTransform="rotate(-65.14 17.04 -11.366)scale(2.04551 1.7346)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ghdrqrbfe"/><stop offset="1" class="d7zypgbet"/></radialGradient><radialGradient id="i734fHc" cx="0" cy="0" r="1" gradientTransform="matrix(.99373 1.16264 -1.0377 .88694 15.182 2.394)" gradientUnits="userSpaceOnUse"><stop class="wn92vfpti"/><stop offset="1" class="t4clght5m"/></radialGradient><radialGradient id="iS6G4Ab" cx="0" cy="0" r="1" gradientTransform="matrix(1.45237 -2.86503 1.02604 .52013 20.15 6.53)" gradientUnits="userSpaceOnUse"><stop class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="iQrPgeb" cx="0" cy="0" r="1" gradientTransform="matrix(.26142 .95787 -1.65729 .4523 16.654 2.394)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="s_ha1fylz"/><stop offset="1" class="e0ciekbtt"/></radialGradient><radialGradient id="illXOlc" cx="0" cy="0" r="1" gradientTransform="matrix(1.108 1.50907 -3.2011 2.35032 11.572 3.584)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="pb3_oi83v"/><stop offset="1" class="gt3e5dbiv"/></radialGradient><radialGradient id="ibTYEWd" cx="0" cy="0" r="1" gradientTransform="rotate(156.985 7.905 4.939)scale(7.8382 9.42424)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="gmm-ghbsu"/><stop offset=".959" class="g3s2gbbst"/></radialGradient><radialGradient id="iEPeQCc" cx="0" cy="0" r="1" gradientTransform="matrix(-.5156 2.76686 -2.7644 -.51514 21.97 6.19)" gradientUnits="userSpaceOnUse"><stop class="cpfhw8b0c"/><stop offset="1" class="n6u9ygbrr"/></radialGradient><radialGradient id="iWRaECd" cx="0" cy="0" r="1" gradientTransform="matrix(.02462 -.62786 1.8836 .07386 15.873 14.56)" gradientUnits="userSpaceOnUse"><stop class="zjmwko4fr"/><stop offset="1" class="md9bsbc9k"/></radialGradient><radialGradient id="iTmshEc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90401 -1.06968 0 18.139 10.195)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iNxoTNe" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.91 9.945)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i0geuhb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90406 -1.06973 0 13.772 10.195)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="imdg2mK" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.705 -1.598)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ig2ymVc" cx="0" cy="0" r="1" gradientTransform="matrix(-.31252 4.2792 -11.47135 -.83777 16.458 1.99)" gradientUnits="userSpaceOnUse"><stop offset=".267" class="ucx7riblp"/><stop offset="1" class="fxe3zh8pp"/></radialGradient><radialGradient id="icC6kWc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.625 0 0 -1.29228 20.771 4.3)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="x6mjrexfr"/><stop offset="1" class="pj095ubna"/></radialGradient><radialGradient id="ihiG5jc" cx="0" cy="0" r="1" gradientTransform="matrix(1.75085 0 0 2.31943 9.353 4.738)" gradientUnits="userSpaceOnUse"><stop class="a21-6lr8n"/><stop offset="1" class="ln2o6octk"/></radialGradient><radialGradient id="iT4vKVb" cx="0" cy="0" r="1" gradientTransform="rotate(-96.626 13.245 -3.824)scale(3.52078 14.6419)" gradientUnits="userSpaceOnUse"><stop offset=".064" class="q6gdl1i5d"/><stop offset=".47" class="i99yksbww"/><stop offset="1" class="viu_-ol9y"/></radialGradient><radialGradient id="iY7fauc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.4375 -.53896 .06546 -.53895 21.072 6.05)" gradientUnits="userSpaceOnUse"><stop class="qk2jzhbua"/><stop offset="1" class="nklj5u79d"/></radialGradient><radialGradient id="iFkux7c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.90624 -.5948 .09009 -.59163 21.072 7.051)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="rgck1cbbg"/><stop offset="1" class="k3jqbac6c"/></radialGradient><radialGradient id="is6qyvc" cx="0" cy="0" r="1" gradientTransform="rotate(-135 8.66 -1.205)scale(.62166 .97779)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="hm8qkhptt"/><stop offset="1" class="xy9hyobea"/></radialGradient><radialGradient id="ixLnjCd" cx="0" cy="0" r="1" gradientTransform="matrix(-.9375 .96874 -1.00462 -.97222 16.557 4.035)" gradientUnits="userSpaceOnUse"><stop class="qga7xqb8q"/><stop offset="1" class="pp0fzgbhc"/></radialGradient><radialGradient id="is3eXvV" cx="0" cy="0" r="1" gradientTransform="matrix(.875 -.65625 1.11 1.48 15.854 4.535)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="jsljpd_vj"/><stop offset="1" class="qga7xqb8q"/></radialGradient><linearGradient id="i6iBL5b" x1="15.973" x2="15.973" y1="15.491" y2="29.991" gradientUnits="userSpaceOnUse"><stop class="ka-y4km4d"/><stop offset="1" class="odfguq8mk"/></linearGradient><linearGradient id="iVRVvyc" x1="9.109" x2="6.916" y1="27.808" y2="27.808" gradientUnits="userSpaceOnUse"><stop offset=".124" class="m9kzfz-8h"/><stop offset="1" class="h_4try76x"/></linearGradient><linearGradient id="iiKQXhe" x1="16.478" x2="16.478" y1="30.456" y2="28.988" gradientUnits="userSpaceOnUse"><stop class="cuwamcc7w"/><stop offset="1" class="e9vdenjit"/></linearGradient><linearGradient id="i6qt9Lc" x1="19.041" x2="17.135" y1="26.55" y2="26.55" gradientUnits="userSpaceOnUse"><stop class="hi4tb8d4g"/><stop offset="1" class="l6siijbzt"/></linearGradient><linearGradient id="itJlr4c" x1="13.268" x2="13.268" y1="29.363" y2="15.828" gradientUnits="userSpaceOnUse"><stop class="gxm502ben"/><stop offset="1" class="qg2z49_rr"/></linearGradient><linearGradient id="iqoQ2Cd" x1="13.268" x2="13.268" y1="29.681" y2="23.347" gradientUnits="userSpaceOnUse"><stop offset=".306" class="ke9tt_b-u"/><stop offset="1" class="w784rnm9d"/></linearGradient><linearGradient id="icCmq7b" x1="18.688" x2="19.697" y1="20.738" y2="20.738" gradientUnits="userSpaceOnUse"><stop class="olptj6tus"/><stop offset="1" class="d-3cltoww"/></linearGradient><linearGradient id="i2IgAkc" x1="13.556" x2="15.15" y1="16.55" y2="18.597" gradientUnits="userSpaceOnUse"><stop class="sv13rb7yi"/><stop offset="1" class="k5-d0pb7l"/></linearGradient><linearGradient id="iVF54ld" x1="18.416" x2="17.072" y1="16.488" y2="18.238" gradientUnits="userSpaceOnUse"><stop class="sv13rb7yi"/><stop offset="1" class="k5-d0pb7l"/></linearGradient><linearGradient id="iWQ62Tb" x1="11.206" x2="10.565" y1="10.823" y2="10.823" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="iik447s" x1="21.816" x2="20.996" y1="9.451" y2="11.99" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="i8Z42Lb" x1="19.998" x2="12.354" y1="10.934" y2="12.073" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset=".916" class="as9qb1byz"/></linearGradient><linearGradient id="i2RwTDE" x1="10.557" x2="12.872" y1="13.632" y2="13.33" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="iJOKlNb" x1="11.092" x2="13.746" y1="10.26" y2="5.261" gradientUnits="userSpaceOnUse"><stop class="kyzs66gfi"/><stop offset="1" class="zsx4vmb0f"/></linearGradient><linearGradient id="ibWuquc" x1="15.093" x2="16.032" y1="11.594" y2="11.594" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="iQ4eE3c" x1="16.897" x2="15.871" y1="11.916" y2="11.902" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="iOEAHQe" x1="16.153" x2="16.153" y1="12.659" y2="12.086" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="iZMYnMe" x1="15.958" x2="15.958" y1="9.976" y2="10.988" gradientUnits="userSpaceOnUse"><stop class="v8ctoug8g"/><stop offset="1" class="guzm96b5h"/></linearGradient><linearGradient id="i2ayJMc" x1="18.918" x2="18.604" y1="9.915" y2="10.109" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i1NMGAL" x1="14.516" x2="14.202" y1="9.915" y2="10.109" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iS6GDMd" x1="15.964" x2="15.964" y1="19.216" y2="20.913" gradientUnits="userSpaceOnUse"><stop offset=".006" class="bf4zukp8q"/><stop offset="1" class="i_g168btd"/></linearGradient><linearGradient id="iX8Eymc" x1="21.058" x2="22.853" y1="20.067" y2="20.701" gradientUnits="userSpaceOnUse"><stop class="uns_kgbkm"/><stop offset="1" class="vglr3ibxi"/></linearGradient><linearGradient id="i2Sa44d" x1="17.322" x2="11.103" y1="6.831" y2="6.831" gradientUnits="userSpaceOnUse"><stop class="a_cf-ibqz"/><stop offset="1" class="ayzgumbov"/></linearGradient><linearGradient id="iZorvEx" x1="16.064" x2="14.486" y1="4.152" y2="4.152" gradientUnits="userSpaceOnUse"><stop class="whje1li3v"/><stop offset="1" class="u3hfg3htm"/></linearGradient><linearGradient id="ipWwmDb" x1="18.057" x2="16.57" y1="3.16" y2="4.151" gradientUnits="userSpaceOnUse"><stop class="xgphulxrx"/><stop offset="1" class="cit_-lbel"/></linearGradient><filter id="iL3QYAc" width="7.031" height="7.114" x="12.463" y="14.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2457" stdDeviation=".5"/></filter><filter id="ilpphIb" width="4.951" height="14.36" x="9.091" y="15.453" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2457" stdDeviation=".5"/></filter><filter id="ijQqFDb" width="3.097" height="14.304" x="10.322" y="15.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.356863 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2457"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.290196 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2457" result="effect2_innerShadow_4002_2457"/></filter><filter id="ixUPbYb" width="4.081" height="12.629" x="18.135" y="15.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2457" stdDeviation=".5"/></filter><filter id="iMv3ySc" width="3.042" height="14.123" x="18.438" y="15.858" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.372549 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2457"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.34902 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2457" result="effect2_innerShadow_4002_2457"/></filter><filter id="ixc3sQb" width="2.992" height="2.992" x="9.71" y="9.048" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2457" stdDeviation=".25"/></filter><filter id="iWhE4lb" width="3.592" height="3.592" x="19.057" y="8.623" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2457"/></filter><filter id="iB5q7AS" width="2.992" height="2.992" x="19.232" y="9.048" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2457" stdDeviation=".25"/></filter><filter id="i5qxRrd" width="12.614" height="7.841" x="9.651" y="2.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.584314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2457"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.572549 0 0 0 0 0.0156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2457" result="effect2_innerShadow_4002_2457"/></filter><filter id="iM93uSb" width="3.262" height="4.184" x="14.088" y="9.389" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2457" stdDeviation=".375"/></filter><filter id="iJwLksd" width="2.379" height="3.184" x="14.769" y="9.726" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2457" stdDeviation=".125"/></filter><filter id="iybBHce" width="3.621" height="1.474" x="14.148" y="13.13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2457" stdDeviation=".05"/></filter><filter id="i4AFVSc" width=".787" height=".697" x="17.404" y="9.421" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2457" stdDeviation=".05"/></filter><filter id="itkF0jc" width=".892" height=".914" x="18.245" y="9.496" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2457" stdDeviation=".1"/></filter><filter id="iUI0dlb" width=".987" height="1.041" x="13.799" y="9.433" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2457" stdDeviation=".1"/></filter><filter id="iJ9nUBb" width=".914" height=".705" x="13.044" y="9.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2457" stdDeviation=".05"/></filter><filter id="i9bCaBe" width="2.735" height="2.58" x="14.605" y="18.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.152941 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2457"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.152941 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2457" result="effect2_innerShadow_4002_2457"/></filter><filter id="ioZpmsb" width="3.151" height="1.346" x="20.508" y="19.627" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2457" stdDeviation=".1"/></filter><filter id="iznCuod" width="2.881" height="1.03" x="20.708" y="19.721" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.529412 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2457"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.760784 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2457" result="effect2_innerShadow_4002_2457"/></filter><filter id="ideyFCd" width="10.9" height="2.77" x="10.528" y="6.121" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.168627 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2457"/></filter><filter id="imlVWOc" width="4.831" height="2.64" x="13.563" y="2.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2457" stdDeviation=".125"/></filter><filter id="iwnJ6Vu" width="2.293" height="1.21" x="13.834" y="3.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.65098 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2457"/></filter><filter id="iljQ33b" width="2.298" height="1.22" x="15.917" y="3.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.752941 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2457"/></filter><filter id="iutPWBc" width="1.63" height="1.63" x="15.268" y="3.521" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.4 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2457"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-pilot" /></template>
<style>
.a_cf-ibqz {
  stop-color: var(--svg-color--e3ac3f, #E3AC3F);
}

.a21-6lr8n {
  stop-color: var(--svg-color--5d5a62, #5D5A62);
}

.a3wd1bbwe {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m15.576 10.258l-.532 1.701a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.378-.646-.378-.766 0");
}

.a66olmrmb {
  cx: 13.5px;
  cy: 9.765px;
  rx: 0.39px;
  ry: 0.197px;
}

.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.aca7cbain {
  cx: 13.5px;
  cy: 9.765px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.afgy4ccwo {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.348 9.112c.654 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34h-2.233a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.372-1.128");
}

.ajo6d3bof {
  cx: 11.206px;
  cy: 10.544px;
  r: 1.671px;
}

.as9qb1byz {
  stop-color: var(--svg-color--f9a528, #F9A528);
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.ayzgumbov {
  stop-color: var(--svg-color--b88538, #B88538);
}

.b0hon_b8a {
  stop-color: var(--svg-color--a9a0b2, #A9A0B2);
}

.bf4zukp8q {
  stop-color: var(--svg-color--543555, #543555);
}

.c9i4jabqz {
  d: path("m20.782 4.398l.43.202a1.825 1.825 0 0 1 1.02 2.013l-.591 2.87c-.053.296-.26.495-.573.502c.036-.475.07-1.242.082-1.363c.044-.409-.025-.529-.422-.902c-.215-.201-.376-.503-.376-.805V6.11c0-.252-.215-.453-.43-.504c-.644-.15-1.986-.402-3.919-.402s-3.275.251-3.92.402a.5.5 0 0 0-.429.504v.805c0 .302-.107.604-.376.805l-.16.151c-.215.151-.324.467-.324.719c.014.146.036.992.06 1.344c-.3-.02-.545-.216-.596-.502l-.59-2.87A1.9 1.9 0 0 1 10.742 4.6c1.014-.42 1.384-1.057 2.2-1.712a2.06 2.06 0 0 1 2.202-.302a3.1 3.1 0 0 0 1.664 0c.806-.252 1.719-.05 2.363.503l.805.755c.215.252.483.403.806.554");
}

.cit_-lbel {
  stop-color: var(--svg-color--e09037, #E09037);
}

.ck410xb1o {
  stop-color: var(--svg-color--ffe336, #FFE336);
}

.ckk71jgrk {
  stop-color: var(--svg-color--c1742b, #C1742B);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cpfhw8b0c {
  stop-color: var(--svg-color--ffc32b, #FFC32B);
}

.cuwamcc7w {
  stop-color: var(--svg-color--c2aadc, #C2AADC);
}

.d-3cltoww {
  stop-color: var(--svg-color--625990, #625990);
}

.d7zypgbet {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
  stop-opacity: 0;
}

.dimomr5au {
  stop-color: var(--svg-color--6b629a, #6B629A);
  stop-opacity: 0;
}

.dsfnryq2l {
  stop-color: var(--svg-color--c0aac0, #C0AAC0);
}

.e0ciekbtt {
  stop-color: var(--svg-color--ffc926, #FFC926);
  stop-opacity: 0;
}

.e3skdu--u {
  stop-color: var(--svg-color--928392, #928392);
}

.e6sjkybst {
  stop-color: var(--svg-color--504069, #504069);
  stop-opacity: 0;
}

.e9vdenjit {
  stop-color: var(--svg-color--c2aadc, #C2AADC);
  stop-opacity: 0;
}

.ejnoaybri {
  fill: var(--svg-color--382534, #382534);
  d: path("M16.767 4.342h.633a.2.2 0 0 0 .18-.11l.55-.95c.04-.07-.01-.16-.09-.16h-1.4a.2.2 0 0 0-.18.11l-.275.475a.8.8 0 0 0-.415.006l-.273-.47a.2.2 0 0 0-.18-.11h-1.4c-.08 0-.13.09-.09.16l.54.94c.04.07.1.11.18.11h.66a.79.79 0 1 0 1.559 0");
}

.ekddxwb3z {
  d: path("M23.338 19.771h-.64c-.23 0-.44.13-.54.33c-.01.02-.04.02-.04 0c-.1-.2-.31-.33-.54-.33h-.62c-.13 0-.24.09-.25.22s.1.25.23.25h.16c.04 0 .08.02.1.06l.09.2c.06.12.18.2.32.2h1.07c.14 0 .26-.08.32-.2l.09-.2a.11.11 0 0 1 .1-.06h.15c.13 0 .24-.09.25-.22c-.01-.14-.12-.25-.25-.25");
}

.etnb2bbvc {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M15.958 13.677c-.508 0-.985-.12-1.386-.329c-.137-.07-.285.085-.198.21c.335.507.919.846 1.584.846s1.25-.339 1.585-.847c.086-.13-.061-.279-.198-.209c-.402.21-.874.329-1.387.329");
}

.euj6xpbnj {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.fo-6ebk8r {
  d: path("M21.72 3.541c-2.66-1.66-5.7-1.55-5.74-1.55s-3.14-.01-5.74 1.54c-1 .6-1.19 1.96-.39 2.8l.68.72h10.9l.68-.72c.8-.83.6-2.18-.39-2.79");
}

.ft5dv1b6b {
  fill: none;
}

.fuvdo9dba {
  cx: 20.728px;
  cy: 10.544px;
  r: 1.671px;
}

.fxe3zh8pp {
  stop-color: var(--svg-color--3b3541, #3B3541);
}

.fykpegb6n {
  d: path("M18.141 9.384a.893.893 0 0 1 .86 1.128h-1.725a.897.897 0 0 1 .865-1.129");
}

.g-uemq__p {
  stop-color: var(--svg-color--59416c, #59416C);
}

.g3s2gbbst {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghdrqrbfe {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
}

.gmm-ghbsu {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
  stop-opacity: 0;
}

.gmroupkwz {
  fill: var(--svg-color--000, #000);
  d: path("M17.63 10.277a.51.51 0 0 1 .511-.512a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.061-.235");
}

.gqa088q0k {
  fill: var(--svg-color--ffa91b, #FFA91B);
  d: path("m20.782 4.398l.43.202a1.825 1.825 0 0 1 1.02 2.013l-.591 2.87c-.053.296-.26.495-.573.502c.036-.475.07-1.242.082-1.363c.044-.409-.025-.529-.422-.902c-.215-.201-.376-.503-.376-.805V6.11c0-.252-.215-.453-.43-.504c-.644-.15-1.986-.402-3.919-.402s-3.275.251-3.92.402a.5.5 0 0 0-.429.504v.805c0 .302-.107.604-.376.805l-.16.151c-.215.151-.324.467-.324.719c.014.146.036.992.06 1.344c-.3-.02-.545-.216-.596-.502l-.59-2.87A1.9 1.9 0 0 1 10.742 4.6c1.014-.42 1.384-1.057 2.2-1.712a2.06 2.06 0 0 1 2.202-.302a3.1 3.1 0 0 0 1.664 0c.806-.252 1.719-.05 2.363.503l.805.755c.215.252.483.403.806.554");
}

.gt3e5dbiv {
  stop-color: var(--svg-color--f29322, #F29322);
  stop-opacity: 0;
}

.guzm96b5h {
  stop-color: var(--svg-color--e7a32e, #E7A32E);
  stop-opacity: 0;
}

.gx4c8g7wr {
  d: path("M13.268 15.828q-.691.175-1.345.435l-.035.018l-1.27 2.69c-.09.19.05.41.26.41h1.05c.24 0 .35.29.19.45l-1.36 1.33c-.26.26-.36.65-.23 1l2.73 7.82h.01z");
}

.gxm502ben {
  stop-color: var(--svg-color--605388, #605388);
}

.h_4try76x {
  stop-color: var(--svg-color--524c6a, #524C6A);
  stop-opacity: 0;
}

.hchnd0bsx {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
  stop-opacity: 0;
}

.hi4tb8d4g {
  stop-color: var(--svg-color--80728b, #80728B);
}

.hm8qkhptt {
  stop-color: var(--svg-color--c47c25, #C47C25);
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hmqw7nbre {
  fill: var(--svg-color--44375d, #44375D);
  d: path("m20.029 20.47l.443 1.05c.202.26.272.65.179 1.01l-1.296 4.645l-.22-10.445l.09-.183q.508.173.99.423l.98 2.64c.069.19-.04.41-.203.41h-.816c-.186 0-.28.28-.147.45");
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.hqfmlmg6f {
  stop-color: var(--svg-color--483555, #483555);
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i_g168btd {
  stop-color: var(--svg-color--483a53, #483A53);
}

.i99yksbww {
  stop-color: var(--svg-color--4f3e5f, #4F3E5F);
}

.innd1ftrr {
  d: path("m19.838 19.781l1.36 1.33c.26.26.35.65.23 1.01l-2.74 7.86v-13.94l.117-.183q.653.174 1.272.423l1.261 2.64c.09.19-.05.41-.26.41h-1.05c-.24 0-.36.28-.19.45");
}

.izw19gb1b {
  stop-color: var(--svg-color--7d72a2, #7D72A2);
}

.j_s_0lsgx {
  stop-color: var(--svg-color--524a68, #524A68);
}

.j0v64o33h {
  d: path("M15.978 18.436c1.79-.788 1.932-1.316 1.92-1.7h-3.839c-.013.384.224.97 1.92 1.7");
}

.jjvm35b5v {
  fill: var(--svg-color--000, #000);
  d: path("M14.282 10.277a.51.51 0 0 0-.512-.512a.51.51 0 0 0-.455.747h.906a.5.5 0 0 0 .06-.235");
}

.jsljpd_vj {
  stop-color: var(--svg-color--fcbb51, #FCBB51);
  stop-opacity: 0;
}

.k3jqbac6c {
  stop-color: var(--svg-color--eba026, #EBA026);
  stop-opacity: 0;
}

.k5-d0pb7l {
  stop-color: var(--svg-color--987a8d, #987A8D);
  stop-opacity: 0;
}

.k7t32nxif {
  d: path("M10.854 9.93a30 30 0 0 1-.059-1.44c0-.266.108-.586.322-.747l.161-.16c.269-.213.376-.534.376-.854v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.92-.427c1.932 0 3.274.267 3.919.427c.214.054.43.267.43.534v.854c0 .32.16.64.375.854c.502.352.471.546.43.961c-.013.129-.054 1.196-.09 1.441l-.266 3.963c-.16 1.77-1.553 3.005-3.213 3.005h-3.214c-1.713 0-3.052-1.234-3.213-3.005z");
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.ka-y4km4d {
  stop-color: var(--svg-color--584c78, #584C78);
}

.ka8y65brc {
  d: path("M15.978 15.491c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.kbhcrw6bx {
  stop-color: var(--svg-color--e58a3d, #E58A3D);
  stop-opacity: 0;
}

.ke9tt_b-u {
  stop-color: var(--svg-color--5d4f84, #5D4F84);
}

.kekenabmz {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.075 9.573c.064.085-.069.188-.22.301c-.151.114-.264.193-.327.108c-.064-.085.007-.246.158-.359c.152-.113.326-.136.39-.05");
}

.kf63_jbnw {
  d: path("M18.937 10.16a.84.84 0 0 0-.232-.464l-.26.286l.117.228z");
}

.kolzjh1uk {
  stop-color: var(--svg-color--6e638c, #6E638C);
  stop-opacity: 0;
}

.kxilzmbvy {
  d: path("M8.853 29.991v-11.88a10.97 10.97 0 0 0-3.875 8.38v3.5z");
}

.kyzs66gfi {
  stop-color: var(--svg-color--e07027, #E07027);
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l0wwovb8s {
  d: path("M16.058 5.151a.79.79 0 1 0 0-1.58a.79.79 0 0 0 0 1.58");
}

.l6siijbzt {
  stop-color: var(--svg-color--80728b, #80728B);
  stop-opacity: 0;
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lm6_trdgy {
  fill: var(--svg-color--473a60, #473A60);
  d: path("M23.22 19.827h-.611c-.22 0-.42.13-.516.328c-.01.02-.038.02-.038 0a.57.57 0 0 0-.516-.328h-.592c-.124 0-.23.09-.239.219c-.01.13.096.25.22.25h.153c.179 0 .179.078.212.149c.058.12.172.2.306.2h.239l.539.128c.134 0 .461-.1.518-.219l.086-.2a.11.11 0 0 1 .096-.059h.143c.124 0 .23-.09.239-.22c-.01-.139-.115-.248-.239-.248");
}

.ln2o6octk {
  stop-color: var(--svg-color--3a3340, #3A3340);
  stop-opacity: 0;
}

.ls3v4_3of {
  d: path("M18.678 16.101h-5.41v13.89h5.41z");
}

.m2htywblo {
  cx: 20.728px;
  cy: 10.544px;
  r: 0.996px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.m35awxblz {
  d: path("m15.576 10.258l-.532 1.701a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.378-.646-.378-.766 0");
}

.m5fsy5uld {
  d: path("M15.928 5.511h.1c.39 0 2.27.02 4.56.51c.49.1.84.53.84 1.03c-2.92-.76-5.45-.73-5.45-.73s-2.53-.03-5.45.73c0-.5.35-.93.84-1.03c2.29-.48 4.16-.51 4.56-.51");
}

.m9kzfz-8h {
  stop-color: var(--svg-color--443a60, #443A60);
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

.mgj3nfyon {
  stop-color: var(--svg-color--504069, #504069);
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.n-1p2p9pr {
  stop-color: var(--svg-color--615589, #615589);
}

.n6u9ygbrr {
  stop-color: var(--svg-color--ffc32b, #FFC32B);
  stop-opacity: 0;
}

.nakrar40o {
  d: path("M16.071 4.231h1.4a.2.2 0 0 0 .18-.11l.55-.95c.04-.07-.01-.16-.09-.16h-1.4a.2.2 0 0 0-.18.11l-.55.95c-.04.07.01.16.09.16");
}

.ng9k9ab_a {
  stop-color: var(--svg-color--d0c1d9, #D0C1D9);
}

.nklj5u79d {
  stop-color: var(--svg-color--ffcf55, #FFCF55);
  stop-opacity: 0;
}

.ny-qt-bge {
  stop-color: var(--svg-color--3a3045, #3A3045);
}

.o-y5a1rmp {
  stop-color: var(--svg-color--d0c1d9, #D0C1D9);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odfguq8mk {
  stop-color: var(--svg-color--5a4b85, #5A4B85);
}

.oipp6lzec {
  stop-color: var(--svg-color--b87e1f, #B87E1F);
}

.oldhekbqi {
  d: path("M15.978 15.275h-2.71v4.74c0 .31.36.49.61.29l2.1-1.67l2.1 1.67c.25.2.61.02.61-.29v-4.74z");
}

.olptj6tus {
  stop-color: var(--svg-color--56466e, #56466E);
}

.oqr8hmbdg {
  stop-color: var(--svg-color--6e638c, #6E638C);
}

.oyco1db5g {
  stop-color: var(--svg-color--483555, #483555);
  stop-opacity: 0;
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.pa3in2xtx {
  stop-color: var(--svg-color--d88033, #D88033);
  stop-opacity: 0;
}

.pb3_oi83v {
  stop-color: var(--svg-color--c9993e, #C9993E);
}

.pduqyx0mq {
  d: path("M16.018 4.231h-1.4a.2.2 0 0 1-.18-.11l-.54-.94c-.04-.07.01-.16.09-.16h1.4a.2.2 0 0 1 .18.11l.55.95c.03.06-.02.15-.1.15");
}

.pj095ubna {
  stop-color: var(--svg-color--635870, #635870);
  stop-opacity: 0;
}

.pk_fxjb0k {
  stop-color: var(--svg-color--6e658c, #6E658C);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pp0fzgbhc {
  stop-color: var(--svg-color--ce8634, #CE8634);
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.q6gdl1i5d {
  stop-color: var(--svg-color--695978, #695978);
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qdmya3bdh {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.958 13.677c-.508 0-.985-.12-1.386-.329c-.137-.07-.285.085-.198.21c.335.507.919.846 1.584.846s1.25-.339 1.585-.847c.086-.13-.061-.279-.198-.209c-.402.21-.874.329-1.387.329Z");
}

.qeh0r4bjq {
  stop-color: var(--svg-color--ffe336, #FFE336);
  stop-opacity: 0;
}

.qg2z49_rr {
  stop-color: var(--svg-color--564973, #564973);
}

.qga7xqb8q {
  stop-color: var(--svg-color--fcbb51, #FCBB51);
}

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
  stop-opacity: 0;
}

.qk2jzhbua {
  stop-color: var(--svg-color--ffcf55, #FFCF55);
}

.qoa6ovvda {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m15.683 10.422l-.822 1.7c-.101.35.143.7.489.7h.738c.346 0 .59-.355.488-.7l-.498-1.7c-.107-.377-.284-.377-.395 0");
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.rg7f1vb8b {
  cx: 11.206px;
  cy: 10.544px;
  r: 0.996px;
}

.rgck1cbbg {
  stop-color: var(--svg-color--eba026, #EBA026);
}

.rgw_qhbte {
  d: path("M15.49 21.035a.25.25 0 0 0-.247.212l-1.335 8.744h4.12l-1.33-8.744a.25.25 0 0 0-.247-.212z");
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rndoiibli {
  stop-color: var(--svg-color--ad91ca, #AD91CA);
  stop-opacity: 0;
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.rz3b_obgl {
  fill: var(--svg-color--8f809c, #8F809C);
  d: path("M15.979 15.338h-2.516v4.74c0 .31.334.49.566.29l1.95-1.67l1.949 1.67c.232.2.566.02.566-.29v-4.74z");
}

.s_ha1fylz {
  stop-color: var(--svg-color--ddb13b, #DDB13B);
}

.s59tlt20i {
  stop-color: var(--svg-color--7d77a7, #7D77A7);
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.sqsfsibnz {
  stop-color: var(--svg-color--c77b20, #C77B20);
}

.sv13rb7yi {
  stop-color: var(--svg-color--68565a, #68565A);
}

.t4clght5m {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
  stop-opacity: 0;
}

.ta0dozbyl {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.563 9.112c-.654 0-1.206.45-1.356 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.372-1.128");
}

.tfksx7okm {
  d: path("m14.705 19.652l1.267-1.098l1.268 1.074l-.546 1.265a.24.24 0 0 1-.216.142h-1.022a.24.24 0 0 1-.216-.142z");
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.u1ryexbrh {
  d: path("M18.075 9.573c.064.085-.069.188-.22.301c-.151.114-.264.193-.327.108c-.064-.085.007-.246.158-.359c.152-.113.326-.136.39-.05");
}

.u3hfg3htm {
  stop-color: var(--svg-color--e2a23d, #E2A23D);
}

.u4k_nbava {
  fill: var(--svg-color--44375d, #44375D);
  d: path("M12.769 16.453c-.461.117-.364.098-.8.27c-.54.784-1.546 2.2-1.85 2.874c-.09.19.05.41.26.41l1.179-.175c.24 0 .35.29.19.45l-1.37 1.197c-.26.26-.36.65-.23 1l2.894 6.334z");
}

.ucx7riblp {
  stop-color: var(--svg-color--5d4c6d, #5D4C6D);
}

.uns_kgbkm {
  stop-color: var(--svg-color--e3ab3f, #E3AB3F);
}

.v-e2dxczh {
  stop-color: var(--svg-color--615589, #615589);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v63qpu3zx {
  d: path("M13.77 9.384a.893.893 0 0 0-.86 1.128h1.725a1 1 0 0 0 .032-.235a.9.9 0 0 0-.897-.893");
}

.v7hn87gdb {
  stop-color: var(--svg-color--4f4175, #4F4175);
}

.v8ctoug8g {
  stop-color: var(--svg-color--e7a32e, #E7A32E);
}

.ve2vn_bdi {
  cx: 20.728px;
  cy: 10.544px;
  r: 0.996px;
}

.vglr3ibxi {
  stop-color: var(--svg-color--ecac40, #ECAC40);
}

.viu_-ol9y {
  stop-color: var(--svg-color--362c38, #362C38);
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.vse7rwbtm {
  d: path("M15.978 6.321s-2.53-.03-5.45.73l.4.47c.73.87 1.81 1.37 2.95 1.37h4.19c1.14 0 2.22-.5 2.96-1.37l.4-.47c-2.92-.76-5.45-.73-5.45-.73");
}

.w4yfy3zsx {
  stop-color: var(--svg-color--c7bbd0, #C7BBD0);
}

.w784rnm9d {
  stop-color: var(--svg-color--5d4f84, #5D4F84);
  stop-opacity: 0;
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.whje1li3v {
  stop-color: var(--svg-color--d19b3e, #D19B3E);
}

.wn92vfpti {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.x6mjrexfr {
  stop-color: var(--svg-color--635870, #635870);
}

.x7nlr16tt {
  d: path("M23.104 18.114v11.877h3.864v-3.5c0-3.357-1.5-6.36-3.864-8.377");
}

.xgphulxrx {
  stop-color: var(--svg-color--e6ac3e, #E6AC3E);
}

.xy9hyobea {
  stop-color: var(--svg-color--c47c25, #C47C25);
  stop-opacity: 0;
}

.ydmi_gbdg {
  stop-color: var(--svg-color--5a4b81, #5A4B81);
}

.yfv60kbve {
  stop-color: var(--svg-color--514476, #514476);
  stop-opacity: 0;
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.zaowg_8mi {
  d: path("M14.586 10.172c0-.289-.235-.481-.298-.54l-.289.28l.178.361z");
}

.zj0khrbgv {
  stop-color: var(--svg-color--ad91ca, #AD91CA);
}

.zjmwko4fr {
  stop-color: var(--svg-color--ffd069, #FFD069);
}

.zsx4vmb0f {
  stop-color: var(--svg-color--e07027, #E07027);
  stop-opacity: 0;
}

.zvkziabgo {
  stop-color: var(--svg-color--c87152, #C87152);
}

</style>
