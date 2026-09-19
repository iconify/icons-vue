<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ig70nFL)"><circle fill="url(#iF2MWQb)" class="w8l-sqdgg"/></g><g filter="url(#i97KqJC)"><circle fill="url(#igi9tlb)" class="ju9_if7ms"/></g><g filter="url(#ixj1EUc)"><circle fill="url(#iKZ0PJd)" class="zmv_7hb2s"/><circle fill="url(#izg2x1b)" class="zmv_7hb2s"/></g><g filter="url(#ivle4Tu)"><circle class="f-9tf1dtv"/><circle fill="url(#iXvHaid)" class="xfh2-qzxa"/><circle fill="url(#i7JuYTb)" class="xfh2-qzxa"/></g><g filter="url(#iTNPMte)"><path fill="url(#idHm8Kc)" class="ebi1hiyto"/><path fill="url(#ibKnUSd)" class="ebi1hiyto"/><path fill="url(#ikEOFcc)" class="ebi1hiyto"/><path fill="url(#il5qyac)" class="ebi1hiyto"/><path fill="url(#iIGnFjc)" class="ebi1hiyto"/><path fill="url(#iDLzy0p)" class="ebi1hiyto"/></g><g filter="url(#ivBvlqc)"><path fill="url(#iHKNUNc)" class="f9w3ozb6m"/></g><g filter="url(#iGQTeLb)"><path class="lpsqm1-8k"/><path fill="url(#iozEBCd)" class="a6nmu-b8a"/><path fill="url(#iE9svqb)" class="a6nmu-b8a"/><path fill="url(#iwaP56c)" class="a6nmu-b8a"/><path fill="url(#iNbZcMc)" class="a6nmu-b8a"/></g><g filter="url(#imLBdne)"><path class="o-np26bws"/></g><g filter="url(#i0dKVab)"><path class="kmpy00bdt"/><path fill="url(#iB7NsNb)" class="fxl0bma3k"/><path fill="url(#inFAPEi)" class="fxl0bma3k"/><path fill="url(#iwgVenc)" class="fxl0bma3k"/><path fill="url(#iQ3wBrb)" class="fxl0bma3k"/></g><path fill="url(#i3ytFyc)" class="fxl0bma3k"/><path class="fc098dtdz"/><path fill="url(#ivySHnb)" class="uqyewjb0q"/><path class="cntdm_bll"/><g filter="url(#iDG83re)"><path class="wzujbiboq"/><path fill="url(#igKqZIc)" class="w5zgysm_j"/></g><g filter="url(#iXhbI4b)"><path fill="url(#iOTdlOd)" class="gee_3eb_v"/></g><path class="y38kxwxbm"/><path fill="url(#iwVE4ze)" class="gel500s8g"/><path class="yel43-ofz"/><g filter="url(#izj460c)"><path fill="url(#iONuX7c)" class="acic12b9t"/></g><g filter="url(#iH058Eb)"><ellipse transform="rotate(-27.914 12.8 12.144)" class="ygpuambzs"/><ellipse fill="url(#iIlXyGc)" transform="rotate(-27.914 12.8 12.144)" class="k2vj51z7b"/></g><g filter="url(#ief72Ab)"><path stroke="url(#iqC3NFe)" class="upm3hac7e"/></g><path class="j9msq8_3v"/><path fill="url(#iIkC8Hc)" class="vdbpvroyq"/><path fill="url(#iGigNPe)" class="vdbpvroyq"/><path fill="url(#ileIKXd)" class="vdbpvroyq"/><path fill="url(#iyZPTre)" class="jus79jbyy"/><path fill="url(#iRlZgYc)" class="jidy2xu-t"/><path fill="url(#iWkgQJe)" class="jidy2xu-t"/><path fill="url(#iYcpe6b)" class="jidy2xu-t"/><path fill="url(#iBOUt9d)" class="jidy2xu-t"/><path fill="url(#iLbTnge)" class="jidy2xu-t"/><path fill="url(#iFWGNob)" class="jidy2xu-t"/><path fill="url(#i6sN0hc)" class="jidy2xu-t"/><path fill="url(#iYD891c)" class="uritxubxy"/><path fill="url(#iUQEvTy)" class="va-dzqbbo"/><path fill="url(#iFlSOTb)" class="va-dzqbbo"/><path fill="url(#iEGCFWd)" class="va-dzqbbo"/><path fill="url(#i08Un9c)" class="va-dzqbbo"/><path fill="url(#itrBxAd)" class="va-dzqbbo"/><path fill="url(#imCSzHb)" class="wymjbgbqv"/><path fill="url(#iHlFETR)" class="wymjbgbqv"/><path fill="url(#iURTNAe)" class="wymjbgbqv"/><path fill="url(#iwPXCHc)" class="yuv68hbvz"/><path fill="url(#iF2ZaIe)" class="yuv68hbvz"/><path fill="url(#iQalMFe)" class="exo5v8bwa"/><path fill="url(#iDcKcrc)" class="exo5v8bwa"/><path fill="url(#i5aLcHe)" class="exo5v8bwa"/><g filter="url(#iVT6hcd)"><path fill="url(#ipC6jLC)" class="rnhytm_ty"/><path fill="url(#ixi1SfI)" class="rnhytm_ty"/></g><path fill="url(#iFXqQgb)" class="rnhytm_ty"/><path clip-rule="evenodd" class="yltgtcbsy"/><path fill="url(#iyr6FFS)" clip-rule="evenodd" class="m-0pf9bfd"/><g filter="url(#iuf9Uod)"><path class="hgxzjfb-p"/></g><path clip-rule="evenodd" class="huczn5opo"/><path fill="url(#iQfgVtI)" clip-rule="evenodd" class="b-kzmsqag"/><g filter="url(#iNJ7Krc)"><path class="hi_h6lxvs"/></g><g filter="url(#iNy9hof)"><path fill="url(#iifDnHX)" class="pnxj8pb1l"/></g><defs><radialGradient id="iF2MWQb" cx="0" cy="0" r="1" gradientTransform="matrix(2.27915 0 0 3.98852 7.654 13.242)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="izg2x1b" cx="0" cy="0" r="1" gradientTransform="matrix(1.07369 -.78181 .89233 1.22547 22.661 12.898)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="iXvHaid" cx="0" cy="0" r="1" gradientTransform="matrix(1.06662 -1.96182 1.14826 .6243 22.124 14.309)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="i7JuYTb" cx="0" cy="0" r="1" gradientTransform="matrix(.33675 .33333 -.42972 .43412 22.178 13.242)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="ikEOFcc" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.22788 -12.5264 0 15.597 12.984)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="g0r5sc7jj"/><stop offset="1" class="i5c5eto6f"/></radialGradient><radialGradient id="il5qyac" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.69758 2.08933 0 19.036 11.59)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="iIGnFjc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.8064 2.24642 0 13.116 11.547)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="iozEBCd" cx="0" cy="0" r="1" gradientTransform="matrix(1.03617 -3.83994 1.5947 .43032 21.632 7.91)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="s08gchr9m"/><stop offset="1" class="hevp37b4w"/></radialGradient><radialGradient id="iE9svqb" cx="0" cy="0" r="1" gradientTransform="matrix(4.96754 .45714 -.3063 3.32853 19.499 5.623)" gradientUnits="userSpaceOnUse"><stop offset=".309" class="s08gchr9m"/><stop offset="1" class="hevp37b4w"/></radialGradient><radialGradient id="iwaP56c" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.18084 -3.37751 0 15.989 2.071)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="iNbZcMc" cx="0" cy="0" r="1" gradientTransform="matrix(3.99232 -2.92567 4.58356 6.25465 7.613 10.926)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="iQ3wBrb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .25572 -.82159 0 16.413 15.029)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="ivySHnb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.05346 -1.67565 0 18.818 12.268)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="igKqZIc" cx="0" cy="0" r="1" gradientTransform="matrix(-.30114 -.38805 .53426 -.41459 18.522 12.377)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iwVE4ze" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.05352 -1.67574 0 13.152 12.268)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iIlXyGc" cx="0" cy="0" r="1" gradientTransform="matrix(-.01004 -.64155 .77117 -.01207 12.78 12.554)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iIkC8Hc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.8125 10.4384 0 16.562 30.332)" gradientUnits="userSpaceOnUse"><stop class="mebiusz6j"/><stop offset=".714" class="tzc2eqbez"/></radialGradient><radialGradient id="iGigNPe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.9375 -6.625 2.9819 -3.12257 26.438 22.366)" gradientUnits="userSpaceOnUse"><stop class="tkk3fh7lv"/><stop offset="1" class="wltqj-b_b"/></radialGradient><radialGradient id="ileIKXd" cx="0" cy="0" r="1" gradientTransform="matrix(2.1875 2.21875 -3.00505 2.96273 6.063 21.148)" gradientUnits="userSpaceOnUse"><stop class="stmwvtbwq"/><stop offset="1" class="mbu8hk88e"/></radialGradient><radialGradient id="iyZPTre" cx="0" cy="0" r="1" gradientTransform="matrix(2.6551 1.32154 -2.0509 4.12044 8.345 17.17)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="lht-5qo7r"/><stop offset="1" class="c83rl0b_v"/></radialGradient><radialGradient id="iRlZgYc" cx="0" cy="0" r="1" gradientTransform="matrix(16.5217 8.52358 -2.95327 5.72447 14.913 18.585)" gradientUnits="userSpaceOnUse"><stop offset=".568" class="a7qi3ibbq"/><stop offset="1" class="isu90b6vd"/></radialGradient><radialGradient id="iWkgQJe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.80476 2.04336 -1.52855 -3.59423 29 24.832)" gradientUnits="userSpaceOnUse"><stop class="bpjtw3boo"/><stop offset="1" class="g_enp1bol"/></radialGradient><radialGradient id="iYcpe6b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.07575 5.3158 -8.32749 -3.25178 14.245 17.613)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="avgknr4aj"/><stop offset="1" class="xp9lv-a7q"/></radialGradient><radialGradient id="iLbTnge" cx="0" cy="0" r="1" gradientTransform="rotate(-32.171 41.318 -3.11)scale(2.28894)" gradientUnits="userSpaceOnUse"><stop class="pe78akl1z"/><stop offset="1" class="epnh4ac5k"/></radialGradient><radialGradient id="i6sN0hc" cx="0" cy="0" r="1" gradientTransform="matrix(8.43038 -3.42291 .46766 1.15182 16.663 24.833)" gradientUnits="userSpaceOnUse"><stop offset=".314" class="mzcr1bvpw"/><stop offset="1" class="ms91oy-xv"/></radialGradient><radialGradient id="iYD891c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45313 .59375 -1.31526 -3.21892 23.405 17.738)" gradientUnits="userSpaceOnUse"><stop class="h3jyzg19k"/><stop offset="1" class="fo5-hs3pv"/></radialGradient><radialGradient id="iUQEvTy" cx="0" cy="0" r="1" gradientTransform="matrix(-22.93743 10.81261 -2.61777 -5.55323 22.313 18.804)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="a6fx42bik"/><stop offset="1" class="lrp5mrmlg"/></radialGradient><radialGradient id="imCSzHb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69235 1.61205 -.40527 -.42545 28.599 16.855)" gradientUnits="userSpaceOnUse"><stop class="thafvacgt"/><stop offset=".615" class="n42kk7pqk"/></radialGradient><radialGradient id="iwPXCHc" cx="0" cy="0" r="1" gradientTransform="rotate(-165.54 4.892 9.096)scale(1.96996 1.63501)" gradientUnits="userSpaceOnUse"><stop class="camp3gbri"/><stop offset=".697" class="d-rprdjqx"/></radialGradient><radialGradient id="iF2ZaIe" cx="0" cy="0" r="1" gradientTransform="matrix(.74865 .58312 -.61233 .78615 5.922 18.055)" gradientUnits="userSpaceOnUse"><stop class="lqt9uqtub"/><stop offset="1" class="off4cm2_g"/></radialGradient><radialGradient id="iQalMFe" cx="0" cy="0" r="1" gradientTransform="rotate(-163.652 15.288 6.317)scale(4.66351 7.27193)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="sq5l9g8_d"/><stop offset="1" class="sst8orbli"/></radialGradient><radialGradient id="iDcKcrc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07812 .5625 -.19373 -.37132 30 13.194)" gradientUnits="userSpaceOnUse"><stop class="kbuu85jbe"/><stop offset="1" class="q59v_vbuo"/></radialGradient><radialGradient id="ixi1SfI" cx="0" cy="0" r="1" gradientTransform="matrix(-2.06198 -1.07487 .61616 -1.18202 8.585 18.209)" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="gxtn60bqm"/></radialGradient><radialGradient id="iFXqQgb" cx="0" cy="0" r="1" gradientTransform="matrix(1.05293 -.08258 .27016 3.4445 4.334 17.934)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="ryyyekfgi"/><stop offset="1" class="bhv0cwbcf"/></radialGradient><linearGradient id="igi9tlb" x1="9.822" x2="8.99" y1="13.604" y2="13.604" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="iKZ0PJd" x1="23.589" x2="22.526" y1="11.825" y2="15.119" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="idHm8Kc" x1="21.23" x2="11.312" y1="13.748" y2="15.226" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="ibKnUSd" x1="8.981" x2="11.424" y1="17.25" y2="17.163" gradientUnits="userSpaceOnUse"><stop class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="iDLzy0p" x1="16.026" x2="16.026" y1="-7.387" y2="21.82" gradientUnits="userSpaceOnUse"><stop offset=".979" class="wvw1ebchz"/><stop offset="1" class="y2xm7ibwq"/></linearGradient><linearGradient id="iHKNUNc" x1="17.012" x2="25.875" y1="9.25" y2="6.085" gradientUnits="userSpaceOnUse"><stop class="ah1agj4tq"/><stop offset="1" class="pzvyv6bhs"/></linearGradient><linearGradient id="iB7NsNb" x1="14.866" x2="16.085" y1="14.304" y2="14.304" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="inFAPEi" x1="17.207" x2="15.875" y1="14.723" y2="14.704" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="iwgVenc" x1="16.241" x2="16.241" y1="15.687" y2="14.943" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="i3ytFyc" x1="16.152" x2="16.152" y1="15.741" y2="15.524" gradientUnits="userSpaceOnUse"><stop class="zoxadnjxe"/><stop offset="1" class="gnvm67mtb"/></linearGradient><linearGradient id="iOTdlOd" x1="19.829" x2="19.421" y1="12.338" y2="12.589" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iONuX7c" x1="14.118" x2="13.71" y1="12.338" y2="12.589" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iqC3NFe" x1="9.934" x2="9.934" y1="6.865" y2="9.667" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><linearGradient id="iBOUt9d" x1="9.156" x2="10.486" y1="18.429" y2="19.052" gradientUnits="userSpaceOnUse"><stop class="y6shzzc0m"/><stop offset="1" class="gvfnv53tr"/></linearGradient><linearGradient id="iFWGNob" x1="17.482" x2="17.906" y1="26.634" y2="25.679" gradientUnits="userSpaceOnUse"><stop class="oo6zkeb_e"/><stop offset=".46" class="bw5w8zblw"/></linearGradient><linearGradient id="iFlSOTb" x1="15.132" x2="14.231" y1="27.489" y2="25.466" gradientUnits="userSpaceOnUse"><stop offset=".205" class="boish7bqf"/><stop offset="1" class="dalry_j2d"/></linearGradient><linearGradient id="iEGCFWd" x1="10.345" x2="11.438" y1="19.38" y2="21.911" gradientUnits="userSpaceOnUse"><stop class="m8jyzebhe"/><stop offset="1" class="h7od31b_t"/></linearGradient><linearGradient id="i08Un9c" x1="22.827" x2="21.613" y1="18.74" y2="19.303" gradientUnits="userSpaceOnUse"><stop class="r_-h96bdp"/><stop offset="1" class="tvrmq9s8w"/></linearGradient><linearGradient id="itrBxAd" x1="3.231" x2="6.517" y1="28.216" y2="26.609" gradientUnits="userSpaceOnUse"><stop class="vxp4qyb9c"/><stop offset="1" class="amr862j1l"/></linearGradient><linearGradient id="iHlFETR" x1="28.127" x2="27.738" y1="17.763" y2="17.522" gradientUnits="userSpaceOnUse"><stop offset=".198" class="jkm4jmgye"/><stop offset="1" class="svnghenix"/></linearGradient><linearGradient id="iURTNAe" x1="26.285" x2="26.829" y1="18.544" y2="18.784" gradientUnits="userSpaceOnUse"><stop offset=".353" class="mfwhtqbpf"/><stop offset="1" class="f2y_cno1u"/></linearGradient><linearGradient id="i5aLcHe" x1="25.489" x2="25.997" y1="14.21" y2="15.11" gradientUnits="userSpaceOnUse"><stop class="xlrzicczw"/><stop offset="1" class="ikzehdbwc"/></linearGradient><linearGradient id="ipC6jLC" x1="8" x2="4.375" y1="15.679" y2="19.929" gradientUnits="userSpaceOnUse"><stop offset=".206" class="gbpxfde5c"/><stop offset="1" class="fz359gsqc"/></linearGradient><linearGradient id="iyr6FFS" x1="13.127" x2="13.127" y1="10.816" y2="10.358" gradientUnits="userSpaceOnUse"><stop class="au2eoit4t"/><stop offset="1" class="qjo6_acuo"/></linearGradient><linearGradient id="iQfgVtI" x1="19.036" x2="19.036" y1="10.816" y2="10.358" gradientUnits="userSpaceOnUse"><stop class="au2eoit4t"/><stop offset="1" class="qjo6_acuo"/></linearGradient><linearGradient id="iifDnHX" x1="29.179" x2="24.036" y1="14.775" y2="17.642" gradientUnits="userSpaceOnUse"><stop class="ept1d-nvv"/><stop offset="1" class="z2eb7q_dp"/></linearGradient><filter id="ig70nFL" width="4.536" height="4.336" x="7.654" y="11.074" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24796"/></filter><filter id="i97KqJC" width="3.584" height="3.584" x="8.03" y="11.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24796" stdDeviation=".25"/></filter><filter id="ixj1EUc" width="4.586" height="4.586" x="20.009" y="10.824" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24796"/></filter><filter id="ivle4Tu" width="3.584" height="3.584" x="20.386" y="11.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24796" stdDeviation=".25"/></filter><filter id="iTNPMte" width="13.473" height="15.771" x="9.29" y="5.937" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24796"/></filter><filter id="ivBvlqc" width="9.515" height="7.983" x="14.209" y="3.937" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24796" stdDeviation="1"/></filter><filter id="iGQTeLb" width="16.366" height="10.947" x="7.805" y="1.571" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24796"/></filter><filter id="imLBdne" width="3.786" height="4.982" x="13.785" y="11.667" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24796" stdDeviation=".375"/></filter><filter id="i0dKVab" width="2.938" height="3.982" x="14.52" y="11.955" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24796" stdDeviation=".125"/></filter><filter id="iDG83re" width=".962" height=".844" x="17.895" y="11.727" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24796" stdDeviation=".05"/></filter><filter id="iXhbI4b" width="1.038" height="1.067" x="19.015" y="11.854" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24796" stdDeviation=".1"/></filter><filter id="izj460c" width="1.161" height="1.231" x="13.247" y="11.772" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24796" stdDeviation=".1"/></filter><filter id="iH058Eb" width="1.126" height=".855" x="12.237" y="11.717" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24796" stdDeviation=".05"/></filter><filter id="ief72Ab" width="1.085" height="2.723" x="9.391" y="6.618" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24796" stdDeviation=".125"/></filter><filter id="iVT6hcd" width="7.3" height="8.016" x="2" y="12.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.137255 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24796"/></filter><filter id="iuf9Uod" width="3.094" height="1.313" x="11.296" y="9.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24796" stdDeviation=".125"/></filter><filter id="iNJ7Krc" width="3.094" height="1.313" x="17.773" y="9.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24796" stdDeviation=".125"/></filter><filter id="iNy9hof" width="5.538" height="5.423" x="24.159" y="13.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24796" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-gesturing-no-dark" /></template>
<style>
.a6fx42bik {
  stop-color: var(--svg-color--1fa4f0, #1FA4F0);
}

.a6nmu-b8a {
  d: path("m22.247 4.83l.558.276c.975.485 1.532 1.593 1.323 2.771l-.766 3.948c-.068.408-.338.682-.743.693h-.023s.07-1.178.139-1.87c.056-.563-.042-.734-.557-1.247c-.28-.277-.488-.693-.488-1.108V7.184c0-.346-.279-.623-.557-.692c-.836-.208-2.578-.555-5.086-.555s-4.25.347-5.086.555c-.348.069-.557.346-.557.692v1.109c0 .415-.14.83-.487 1.108l-.21.208c-.278.207-.417.623-.417.97c.07.761.139 1.87.139 1.87q-.033 0-.064-.003a.82.82 0 0 1-.772-.69l-.766-3.948c-.14-1.109.418-2.217 1.393-2.702l.557-.277c.349-.208.697-.485 1.045-.762l1.254-1.316c.766-.693 1.881-.9 2.856-.415a3.8 3.8 0 0 0 2.16 0c1.045-.347 2.23-.07 3.065.692l1.045 1.04c.279.346.627.553 1.045.761");
}

.a7qi3ibbq {
  stop-color: var(--svg-color--32a6f9, #32A6F9);
}

.acic12b9t {
  d: path("M14.208 12.672c0-.375-.304-.624-.387-.7l-.374.362l.23.47z");
}

.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.ah1agj4tq {
  stop-color: var(--svg-color--655352, #655352);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.amr862j1l {
  stop-color: var(--svg-color--3869b0, #3869B0);
  stop-opacity: 0;
}

.au2eoit4t {
  stop-color: var(--svg-color--252424, #252424);
}

.avgknr4aj {
  stop-color: var(--svg-color--28bbff, #28BBFF);
}

.b-kzmsqag {
  fill-rule: evenodd;
  d: path("M17.54 9.405a.625.625 0 0 0 .462.753l2.344.563a.625.625 0 1 0 .291-1.216l-2.344-.562a.625.625 0 0 0-.753.462");
}

.bhv0cwbcf {
  stop-color: var(--svg-color--53403d, #53403D);
  stop-opacity: 0;
}

.boish7bqf {
  stop-color: var(--svg-color--0d7edf, #0D7EDF);
}

.bpjtw3boo {
  stop-color: var(--svg-color--47bbff, #47BBFF);
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.bw5w8zblw {
  stop-color: var(--svg-color--4466c2, #4466C2);
  stop-opacity: 0;
}

.c83rl0b_v {
  stop-color: var(--svg-color--1f5491, #1F5491);
}

.camp3gbri {
  stop-color: var(--svg-color--402f2d, #402F2D);
}

.cdm_o50ho {
  stop-color: var(--svg-color--533531, #533531);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cntdm_bll {
  fill: var(--svg-color--000, #000);
  d: path("M18.158 12.808a.66.66 0 0 1 .663-.664a.66.66 0 0 1 .59.97h-1.175a.6.6 0 0 1-.079-.306");
}

.d-rprdjqx {
  stop-color: var(--svg-color--311a22, #311A22);
}

.dalry_j2d {
  stop-color: var(--svg-color--0d7edf, #0D7EDF);
  stop-opacity: 0;
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.ebi1hiyto {
  d: path("m9.365 12.446l.064.003s-.07-1.109-.14-1.87c0-.347.14-.763.419-.97l.209-.208c.348-.277.487-.693.487-1.108V7.184c0-.346.21-.623.557-.692c.836-.208 2.578-.555 5.086-.555s4.25.347 5.086.555c.278.069.557.346.557.692v1.109c0 .415.209.83.487 1.108c.653.457.612.708.558 1.247c-.07.692-.14 1.87-.14 1.87h.024l-.345 5.14c-.209 2.299-2.015 3.9-4.17 3.9h-4.17c-2.223 0-3.96-1.601-4.169-3.9z");
}

.epnh4ac5k {
  stop-color: var(--svg-color--527faa, #527FAA);
  stop-opacity: 0;
}

.ept1d-nvv {
  stop-color: var(--svg-color--655351, #655351);
}

.exo5v8bwa {
  d: path("m23 15.999l2.12 4.54l.72-.38c.74-.39 1.27-1.08 1.44-1.9l.29-1.39c.08-.42.29-.8.59-1.1l1.51-1.3a.933.933 0 0 0-1.05-1.53z");
}

.f-9tf1dtv {
  cx: 22.178px;
  cy: 13.242px;
  r: 1.292px;
  fill: var(--svg-color--463133, #463133);
}

.f2y_cno1u {
  stop-color: var(--svg-color--33211e, #33211E);
  stop-opacity: 0;
}

.f9w3ozb6m {
  d: path("M21.136 5.937L17.14 7.27a1.36 1.36 0 0 0 .611 2.638l3.974-.532z");
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.fc098dtdz {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.09 11.296c.848 0 1.564.585 1.759 1.375a.356.356 0 0 1-.348.442h-2.897a.3.3 0 0 1-.295-.352a1.815 1.815 0 0 1 1.78-1.465");
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.fo5-hs3pv {
  stop-color: var(--svg-color--1474c2, #1474C2);
}

.ft5dv1b6b {
  fill: none;
}

.fxl0bma3k {
  d: path("m15.492 12.572l-.69 2.207a.7.7 0 0 0 .676.908h1.021a.702.702 0 0 0 .676-.908l-.69-2.207c-.148-.49-.838-.49-.993 0");
}

.fz359gsqc {
  stop-color: var(--svg-color--391d25, #391D25);
}

.g_enp1bol {
  stop-color: var(--svg-color--309ff1, #309FF1);
  stop-opacity: 0;
}

.g0r5sc7jj {
  stop-color: var(--svg-color--3d2138, #3D2138);
  stop-opacity: 0;
}

.gbpxfde5c {
  stop-color: var(--svg-color--4f312d, #4F312D);
}

.gee_3eb_v {
  d: path("M19.853 12.655a1.1 1.1 0 0 0-.3-.6l-.338.37l.153.296z");
}

.gel500s8g {
  d: path("M13.15 11.649a1.16 1.16 0 0 0-1.117 1.464h2.238q.041-.149.042-.305a1.167 1.167 0 0 0-1.164-1.159");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gnvm67mtb {
  stop-color: var(--svg-color--31171f, #31171F);
  stop-opacity: 0;
}

.gvfnv53tr {
  stop-color: var(--svg-color--047fc0, #047FC0);
  stop-opacity: 0;
}

.gxtn60bqm {
  stop-color: var(--svg-color--635251, #635251);
  stop-opacity: 0;
}

.h3jyzg19k {
  stop-color: var(--svg-color--288dcd, #288DCD);
}

.h7od31b_t {
  stop-color: var(--svg-color--1481b9, #1481B9);
  stop-opacity: 0;
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.hevp37b4w {
  stop-color: var(--svg-color--4f494c, #4F494C);
  stop-opacity: 0;
}

.hgxzjfb-p {
  stroke: var(--svg-color--343334, #343334);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m11.671 9.95l2.344-.563");
}

.hi_h6lxvs {
  stroke: var(--svg-color--343334, #343334);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m20.491 9.95l-2.343-.563");
}

.huczn5opo {
  fill: var(--svg-color--131112, #131112);
  fill-rule: evenodd;
  d: path("M17.54 9.405a.625.625 0 0 0 .462.753l2.344.563a.625.625 0 1 0 .291-1.216l-2.344-.562a.625.625 0 0 0-.753.462");
}

.i5c5eto6f {
  stop-color: var(--svg-color--3d2138, #3D2138);
}

.ikzehdbwc {
  stop-color: var(--svg-color--3a221f, #3A221F);
  stop-opacity: 0;
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.isu90b6vd {
  stop-color: var(--svg-color--1b73d2, #1B73D2);
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
}

.j9msq8_3v {
  fill: var(--svg-color--280017, #280017);
  d: path("M15.989 19.38c.791 0 1.433-.69 1.433-1.538c0-.85-.642-1.538-1.433-1.538s-1.433.688-1.433 1.538c0 .849.642 1.537 1.433 1.537");
}

.jidy2xu-t {
  d: path("m11.56 16.027l15.407 7.178a3.53 3.53 0 0 1 1.7 4.687a3.52 3.52 0 0 1-4.679 1.704L8.581 22.408a1 1 0 0 1-.483-1.34l2.123-4.567a1.004 1.004 0 0 1 1.339-.474");
}

.jkm4jmgye {
  stop-color: var(--svg-color--3e2124, #3E2124);
}

.ju9_if7ms {
  cx: 9.822px;
  cy: 13.242px;
  r: 1.292px;
}

.jus79jbyy {
  d: path("m6.81 20.499l2.28 1.06l2.11-4.52l-2.23-1.05z");
}

.k2vj51z7b {
  cx: 12.8px;
  cy: 12.144px;
  rx: 0.506px;
  ry: 0.256px;
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.kbuu85jbe {
  stop-color: var(--svg-color--624e4c, #624E4C);
}

.kmpy00bdt {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m15.492 12.572l-.69 2.207a.7.7 0 0 0 .676.908h1.021a.702.702 0 0 0 .676-.908l-.69-2.207c-.148-.49-.838-.49-.993 0");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.lht-5qo7r {
  stop-color: var(--svg-color--3592c8, #3592C8);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lpsqm1-8k {
  fill: var(--svg-color--21181b, #21181B);
  d: path("m22.247 4.83l.558.276c.975.485 1.532 1.593 1.323 2.771l-.766 3.948c-.068.408-.338.682-.743.693h-.023s.07-1.178.139-1.87c.056-.563-.042-.734-.557-1.247c-.28-.277-.488-.693-.488-1.108V7.184c0-.346-.279-.623-.557-.692c-.836-.208-2.578-.555-5.086-.555s-4.25.347-5.086.555c-.348.069-.557.346-.557.692v1.109c0 .415-.14.83-.487 1.108l-.21.208c-.278.207-.417.623-.417.97c.07.761.139 1.87.139 1.87q-.033 0-.064-.003a.82.82 0 0 1-.772-.69l-.766-3.948c-.14-1.109.418-2.217 1.393-2.702l.557-.277c.349-.208.697-.485 1.045-.762l1.254-1.316c.766-.693 1.881-.9 2.856-.415a3.8 3.8 0 0 0 2.16 0c1.045-.347 2.23-.07 3.065.692l1.045 1.04c.279.346.627.553 1.045.761");
}

.lqt9uqtub {
  stop-color: var(--svg-color--210f10, #210F10);
}

.lrp5mrmlg {
  stop-color: var(--svg-color--1892ed, #1892ED);
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m-0pf9bfd {
  fill-rule: evenodd;
  d: path("M14.623 9.405a.625.625 0 0 1-.462.753l-2.344.563a.625.625 0 1 1-.292-1.216l2.344-.562a.625.625 0 0 1 .754.462");
}

.m8jyzebhe {
  stop-color: var(--svg-color--1481b9, #1481B9);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbu8hk88e {
  stop-color: var(--svg-color--3b7ea8, #3B7EA8);
  stop-opacity: 0;
}

.mebiusz6j {
  stop-color: var(--svg-color--1f70c6, #1F70C6);
}

.mfwhtqbpf {
  stop-color: var(--svg-color--33211e, #33211E);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.ms91oy-xv {
  stop-color: var(--svg-color--1a62c7, #1A62C7);
  stop-opacity: 0;
}

.mzcr1bvpw {
  stop-color: var(--svg-color--1a62c7, #1A62C7);
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.n42kk7pqk {
  stop-color: var(--svg-color--472c31, #472C31);
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o-np26bws {
  fill: var(--svg-color--332024, #332024);
  d: path("m15.631 12.783l-1.065 2.208c-.132.454.184.908.633.908h.958c.449 0 .766-.461.634-.908l-.647-2.208c-.139-.489-.368-.489-.513 0");
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.off4cm2_g {
  stop-color: var(--svg-color--210f10, #210F10);
  stop-opacity: 0;
}

.oo6zkeb_e {
  stop-color: var(--svg-color--4466c2, #4466C2);
}

.pe78akl1z {
  stop-color: var(--svg-color--527faa, #527FAA);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pnxj8pb1l {
  d: path("M26.653 15.551c.527-.846 1.795-1.664 2.462-1.987a.13.13 0 0 1 .152.034a.132.132 0 0 1-.033.196c-2.06 1.273-1.875 1.784-2.645 3.097c-.355.604-1.177 1.112-1.557 1.284l-.473-.899c.53-.28 1.462-.711 2.094-1.725");
}

.pzvyv6bhs {
  stop-color: var(--svg-color--655352, #655352);
  stop-opacity: 0;
}

.q59v_vbuo {
  stop-color: var(--svg-color--624e4c, #624E4C);
  stop-opacity: 0;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qjo6_acuo {
  stop-color: var(--svg-color--252424, #252424);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_-h96bdp {
  stop-color: var(--svg-color--46c3ff, #46C3FF);
}

.rnhytm_ty {
  d: path("m9 15.999l-2.12 4.54l-.72-.38a2.79 2.79 0 0 1-1.44-1.9l-.29-1.39c-.08-.42-.29-.8-.59-1.1l-1.51-1.3a.933.933 0 0 1 1.05-1.53z");
}

.ryyyekfgi {
  stop-color: var(--svg-color--53403d, #53403D);
}

.s08gchr9m {
  stop-color: var(--svg-color--4f494c, #4F494C);
}

.sq5l9g8_d {
  stop-color: var(--svg-color--533836, #533836);
}

.sst8orbli {
  stop-color: var(--svg-color--432e2b, #432E2B);
}

.stmwvtbwq {
  stop-color: var(--svg-color--3b7ea8, #3B7EA8);
}

.svnghenix {
  stop-color: var(--svg-color--3e2124, #3E2124);
  stop-opacity: 0;
}

.thafvacgt {
  stop-color: var(--svg-color--655452, #655452);
}

.tkk3fh7lv {
  stop-color: var(--svg-color--3fc3ff, #3FC3FF);
}

.tvrmq9s8w {
  stop-color: var(--svg-color--46c3ff, #46C3FF);
  stop-opacity: 0;
}

.tzc2eqbez {
  stop-color: var(--svg-color--075ab5, #075AB5);
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.upm3hac7e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.101 6.993V8.16c-.01.193-.091.625-.335.808");
}

.uqyewjb0q {
  d: path("M18.821 11.65a1.16 1.16 0 0 1 1.117 1.463h-2.239a1.163 1.163 0 0 1 1.122-1.464");
}

.uritxubxy {
  d: path("m25.19 20.499l-2.28 1.06l-2.11-4.52l2.26-1.07z");
}

.va-dzqbbo {
  d: path("M20.44 16.027L5.033 23.2a3.53 3.53 0 0 0-1.7 4.69a3.516 3.516 0 0 0 4.679 1.706l15.407-7.183c.503-.232.724-.837.483-1.342l-2.123-4.57a1.003 1.003 0 0 0-1.339-.474");
}

.vdbpvroyq {
  d: path("M25.5 29.929h-19c-.83 0-1.5-.67-1.5-1.5v-4.33c0-2.3 1.87-4.17 4.17-4.17h13.66c2.3 0 4.17 1.87 4.17 4.17v4.33c0 .83-.67 1.5-1.5 1.5");
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vxp4qyb9c {
  stop-color: var(--svg-color--3869b0, #3869B0);
}

.w5zgysm_j {
  d: path("M18.736 11.894c.082.11-.09.245-.286.392c-.197.146-.342.25-.425.14c-.082-.111.01-.32.206-.466s.422-.176.505-.066");
}

.w8l-sqdgg {
  cx: 9.822px;
  cy: 13.242px;
  r: 2.168px;
}

.wltqj-b_b {
  stop-color: var(--svg-color--3fc3ff, #3FC3FF);
  stop-opacity: 0;
}

.wvw1ebchz {
  stop-color: var(--svg-color--624d68, #624D68);
  stop-opacity: 0;
}

.wymjbgbqv {
  d: path("M24.75 19.732a.885.885 0 0 1 .35-1.203l2.61-1.429a.899.899 0 1 1 .856 1.581l-2.622 1.404a.885.885 0 0 1-1.193-.354");
}

.wzujbiboq {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.736 11.894c.082.11-.09.245-.286.392c-.197.146-.342.25-.425.14c-.082-.111.01-.32.206-.466s.422-.176.505-.066");
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.xfh2-qzxa {
  cx: 22.178px;
  cy: 13.242px;
  r: 1.292px;
}

.xlrzicczw {
  stop-color: var(--svg-color--3a221f, #3A221F);
}

.xp9lv-a7q {
  stop-color: var(--svg-color--28bbff, #28BBFF);
  stop-opacity: 0;
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.y2xm7ibwq {
  stop-color: var(--svg-color--624d68, #624D68);
}

.y38kxwxbm {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.88 11.296c-.847 0-1.564.585-1.759 1.375a.356.356 0 0 0 .348.442h2.897a.3.3 0 0 0 .295-.352a1.82 1.82 0 0 0-1.78-1.465");
}

.y6shzzc0m {
  stop-color: var(--svg-color--047fc0, #047FC0);
}

.yel43-ofz {
  fill: var(--svg-color--000, #000);
  d: path("M13.813 12.808a.66.66 0 0 0-.664-.664a.66.66 0 0 0-.59.97h1.175a.66.66 0 0 0 .079-.306");
}

.ygpuambzs {
  cx: 12.8px;
  cy: 12.144px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.506px;
  ry: 0.256px;
}

.yltgtcbsy {
  fill: var(--svg-color--131112, #131112);
  fill-rule: evenodd;
  d: path("M14.623 9.405a.625.625 0 0 1-.462.753l-2.344.563a.625.625 0 1 1-.292-1.216l2.344-.562a.625.625 0 0 1 .754.462");
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.yuv68hbvz {
  d: path("M7.246 19.702a.885.885 0 0 0-.351-1.204l-2.553-1.397a.899.899 0 1 0-.855 1.58l2.565 1.374a.885.885 0 0 0 1.194-.353");
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.z2eb7q_dp {
  stop-color: var(--svg-color--655351, #655351);
  stop-opacity: 0;
}

.zmv_7hb2s {
  cx: 22.178px;
  cy: 13.242px;
  r: 2.168px;
}

.zoxadnjxe {
  stop-color: var(--svg-color--31171f, #31171F);
}

</style>
