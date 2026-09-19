<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iHBMbIe)" class="ic62vub6d"/><path fill="url(#incFVde)" class="r7_51rhvn"/><path fill="url(#iGNkSpb)" class="r7_51rhvn"/><rect fill="url(#iQcgjLd)" class="ndfe_mbxn"/><g filter="url(#iTuoo8b)"><path fill="url(#iFQscsc)" class="sd2t_cbsx"/></g><path fill="url(#i7DRfVb)" class="sd2t_cbsx"/><path fill="url(#iqguO8c)" class="sd2t_cbsx"/><path fill="url(#iS4Yfxb)" class="sd2t_cbsx"/><path fill="url(#iYKckkb)" class="sd2t_cbsx"/><g filter="url(#ie5j4wd)"><path class="dk3a3ccve"/></g><g filter="url(#i8qSYub)"><path fill="url(#iyhGTzb)" class="six73iixf"/><path fill="url(#iCD0czd)" class="six73iixf"/><path fill="url(#iPnBnoF)" class="six73iixf"/><path fill="url(#i13cYRb)" class="six73iixf"/></g><g filter="url(#ihtnoOd)"><path fill="url(#iAdA8nZ)" class="o9jbu96ji"/><path fill="url(#iRn6Tte)" class="o9jbu96ji"/><path fill="url(#i1hhEYd)" class="o9jbu96ji"/></g><g filter="url(#i1Rq98I)"><path class="vdnt3rb5p"/><path fill="url(#i7iGtre)" class="arq00wbxa"/><path fill="url(#iKPFGYb)" class="arq00wbxa"/></g><g filter="url(#igh0Bac)"><path class="u8_2n4b4n"/><path fill="url(#iQnUHwg)" class="d357yfbjj"/><path fill="url(#iiQng4b)" class="d357yfbjj"/><path fill="url(#iGHrFBd)" class="d357yfbjj"/><path fill="url(#imQtP7c)" class="d357yfbjj"/></g><path class="mepywd5ec"/><path fill="url(#i8LleZf)" class="vik2xmvjh"/><path class="dvh6sr_-b"/><g filter="url(#iALC78c)"><path class="tvze-lbke"/><path fill="url(#isHoUCe)" class="oh07ifbww"/></g><g filter="url(#iJGJmne)"><path fill="url(#iSxU6Uu)" class="c4fwxkeyz"/></g><path class="zca_mdy1y"/><path fill="url(#iPymy2d)" class="r1epb9vkn"/><path class="wrt_z3bum"/><g filter="url(#iQDglqe)"><path fill="url(#ia3pMjc)" class="tu8w3ebaf"/></g><g filter="url(#i8D4X9d)"><ellipse transform="rotate(-27.914 13.278 14.768)" class="qxb44vbzx"/><ellipse fill="url(#iK2VMce)" transform="rotate(-27.914 13.278 14.768)" class="vkbtw3twt"/></g><path fill="url(#i6INNnb)" class="mqlp12d1r"/><path fill="url(#iOLXmqe)" class="mqlp12d1r"/><path fill="url(#i40y5fc)" class="lc2vbwt6n"/><path fill="url(#ieDboqd)" class="lc2vbwt6n"/><g filter="url(#i9utgtb)"><path class="r4mmzix7f"/></g><g filter="url(#iUyioIc)"><path class="m6rjd1bzx"/></g><g filter="url(#il6CzWE)"><path clip-rule="evenodd" class="lk74nfb1g"/></g><g filter="url(#iJA6yid)"><path stroke="url(#iw8wlwe)" class="fn6ihcc7i"/></g><g filter="url(#iBBKVqc)"><path clip-rule="evenodd" class="qxdr41lmo"/></g><g filter="url(#iQAzmOc)"><path stroke="url(#iXznDlc)" class="hy2-e6lon"/></g><path stroke="url(#i2l0sfz)" class="zzzw2cchg"/><path class="wkxq-bjsc"/><path fill="url(#i6CepCd)" class="krb79obir"/><path fill="url(#i1sL72c)" class="krb79obir"/><path fill="url(#iTCk0Db)" class="krb79obir"/><path fill="url(#iFYRVOc)" class="krb79obir"/><path fill="url(#iLSRrkd)" class="krb79obir"/><path fill="url(#iTrVwOc)" class="krb79obir"/><path fill="url(#i3P2SVc)" class="krb79obir"/><path fill="url(#iJo9vqc)" class="a_ex1hboc"/><path fill="url(#ixZV9vd)" class="a_ex1hboc"/><path fill="url(#iz4EQ1j)" class="bvpcmdbpa"/><path fill="url(#ip8P7Me)" class="bvpcmdbpa"/><path fill="url(#iB3jSMu)" class="bvpcmdbpa"/><path fill="url(#iG2Umfe)" class="dph6anb-e"/><path fill="url(#ieIFpXk)" class="dph6anb-e"/><path fill="url(#iGtpw6b)" class="yr79k9src"/><path fill="url(#iQInCtb)" class="yr79k9src"/><g filter="url(#iJZsANb)"><path fill="url(#iaXr4nb)" class="pe1y1gbgg"/></g><g filter="url(#ics92Cd)"><path stroke="url(#iBEThke)" class="bznr9j1-f"/></g><path class="j161udblr"/><path stroke="url(#iuMb2nc)" class="dyshkgb1w"/><path stroke="url(#iY3aIyc)" class="dyshkgb1w"/><path stroke="url(#iN4CCgb)" class="dyshkgb1w"/><path stroke="url(#iKUULbZ)" class="x5fl8bb9z"/><path stroke="url(#imkuhMb)" class="x5fl8bb9z"/><path stroke="url(#iuFiWhi)" class="x5fl8bb9z"/><path class="uuua36bph"/><path stroke="url(#iwNwnId)" class="r7hr49baf"/><path stroke="url(#ihl9lUO)" class="r7hr49baf"/><path stroke="url(#i7YjXwd)" class="r7hr49baf"/><path stroke="url(#i9AaQve)" class="o6lz2aclp"/><path stroke="url(#iEoEqsd)" class="o6lz2aclp"/><path stroke="url(#inY7xje)" class="o6lz2aclp"/><path stroke="url(#imNenad)" class="map2p9bzf"/><path class="erxx862yp"/><path stroke="url(#iEVml0l)" class="map2p9bzf"/><path stroke="url(#iXAwmke)" class="map2p9bzf"/><path stroke="url(#iweHFMc)" class="map2p9bzf"/><path stroke="url(#i88rSQd)" class="c3tt5y9ub"/><path stroke="url(#iEw9Q5d)" class="c3tt5y9ub"/><path stroke="url(#iFwuKne)" class="c3tt5y9ub"/><path class="zdjlj62cy"/><path stroke="url(#igEQFic)" class="ygt1ak-zz"/><path stroke="url(#i3FclXt)" class="ygt1ak-zz"/><path stroke="url(#i5lSxRd)" class="bu_xyhfxn"/><path stroke="url(#i5xsNnM)" class="bu_xyhfxn"/><path stroke="url(#i9PGoLc)" class="bu_xyhfxn"/><path fill="url(#i1r78Ob)" class="yr79k9src"/><path fill="url(#iZhMIxd)" class="dph6anb-e"/><defs><radialGradient id="iHBMbIe" cx="0" cy="0" r="1" gradientTransform="matrix(-.83944 3.44902 -4.09716 -.99719 21.99 16.74)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="r8d5udbxl"/><stop offset=".837" class="f55mrubdg"/></radialGradient><radialGradient id="incFVde" cx="0" cy="0" r="1" gradientTransform="matrix(1.3869 2.9198 -1.32719 .63041 9.909 16.869)" gradientUnits="userSpaceOnUse"><stop class="gxq3n8btl"/><stop offset="1" class="k41qw1b_j"/></radialGradient><radialGradient id="iGNkSpb" cx="0" cy="0" r="1" gradientTransform="matrix(-.20941 .71875 -1.43107 -.41695 10.61 17.012)" gradientUnits="userSpaceOnUse"><stop offset=".345" class="borrk8vyp"/><stop offset="1" class="p32iuoeum"/></radialGradient><radialGradient id="iQcgjLd" cx="0" cy="0" r="1" gradientTransform="rotate(-124.695 15.037 7.633)scale(2.96464 6.15655)" gradientUnits="userSpaceOnUse"><stop offset=".187" class="npixnyb9v"/><stop offset="1" class="qd-1m5bst"/></radialGradient><radialGradient id="iFQscsc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.69178 0 0 -10.0687 19.006 15.716)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="iqguO8c" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.1905 -11.7515 0 16.427 9.2)" gradientUnits="userSpaceOnUse"><stop offset=".751" class="jfo6z-bud"/><stop offset=".952" class="g7vim1bgz"/></radialGradient><radialGradient id="iS4Yfxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.4599 1.80663 0 18.613 14.496)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="qtwfj5bch"/><stop offset="1" class="wtzd4lbuc"/></radialGradient><radialGradient id="iYKckkb" cx="0" cy="0" r="1" gradientTransform="matrix(-.01824 -1.4599 1.58872 -.01985 13.467 14.606)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="yq9cl_lgn"/><stop offset="1" class="sw1t1obly"/></radialGradient><radialGradient id="iRn6Tte" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.69214 5.50698 0 16.11 10.36)" gradientUnits="userSpaceOnUse"><stop offset=".78" class="q5loxgbuq"/><stop offset=".986" class="gpdgpl4qm"/></radialGradient><radialGradient id="i1hhEYd" cx="0" cy="0" r="1" gradientTransform="matrix(1.6875 1.22339 -2.53932 3.50266 9.61 9.137)" gradientUnits="userSpaceOnUse"><stop class="cgmkvcbsf"/><stop offset="1" class="fa128uz1k"/></radialGradient><radialGradient id="i7iGtre" cx="0" cy="0" r="1" gradientTransform="matrix(-5.23927 1.89018 -1.06584 -2.95435 16.225 6.997)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="b6ai19bel"/><stop offset="1" class="ijcelgbiw"/></radialGradient><radialGradient id="iKPFGYb" cx="0" cy="0" r="1" gradientTransform="matrix(3.50375 -5.54762 8.14343 5.14321 10.037 12.179)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="filnodb0j"/><stop offset=".22" class="jteqbw4wj"/></radialGradient><radialGradient id="iQnUHwg" cx="0" cy="0" r="1" gradientTransform="rotate(13.157 -24.26 87.087)scale(4.50858 2.52989)" gradientUnits="userSpaceOnUse"><stop offset=".279" class="da8sh5f1a"/><stop offset="1" class="lguy1wbep"/></radialGradient><radialGradient id="iiQng4b" cx="0" cy="0" r="1" gradientTransform="rotate(-113.651 15.297 -.74)scale(4.90749 4.6594)" gradientUnits="userSpaceOnUse"><stop offset=".014" class="lmu7vkr7n"/><stop offset="1" class="e7ap5jbhs"/></radialGradient><radialGradient id="iGHrFBd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22424 1.25336 -1.35493 -5.64761 21.168 7.836)" gradientUnits="userSpaceOnUse"><stop offset=".679" class="q8kwjlr2l"/><stop offset="1" class="y42awybvc"/></radialGradient><radialGradient id="imQtP7c" cx="0" cy="0" r="1" gradientTransform="matrix(-.78125 .53125 -1.69418 -2.49141 22.298 9.387)" gradientUnits="userSpaceOnUse"><stop offset=".526" class="v7axozgfh"/><stop offset="1" class="a92dt6njx"/></radialGradient><radialGradient id="i8LleZf" cx="0" cy="0" r="1" gradientTransform="matrix(0 .88332 -1.40502 0 18.325 14.872)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="isHoUCe" cx="0" cy="0" r="1" gradientTransform="matrix(-.2525 -.32538 .44797 -.34763 18.076 14.963)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iPymy2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .88336 -1.40509 0 13.573 14.872)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iK2VMce" cx="0" cy="0" r="1" gradientTransform="matrix(-.00842 -.53793 .64661 -.01012 13.262 15.11)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iOLXmqe" cx="0" cy="0" r="1" gradientTransform="matrix(.82442 2.38254 -2.68125 .92778 21.308 14.793)" gradientUnits="userSpaceOnUse"><stop offset=".757" class="wc2d54euw"/><stop offset=".96" class="ntf_h0bkc"/></radialGradient><radialGradient id="ieDboqd" cx="0" cy="0" r="1" gradientTransform="matrix(-.44951 2.26025 -2.22203 -.4419 10.219 14.916)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="fkf3rcivf"/><stop offset="1" class="ov282fbso"/></radialGradient><radialGradient id="i6CepCd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.40625 -6.38209 0 16 21.043)" gradientUnits="userSpaceOnUse"><stop offset=".468" class="l-pepacun"/><stop offset="1" class="t-37x237r"/></radialGradient><radialGradient id="i1sL72c" cx="0" cy="0" r="1" gradientTransform="rotate(150.852 12.961 8.247)scale(11.1637 29.6846)" gradientUnits="userSpaceOnUse"><stop class="h9fb5bbiv"/><stop offset="1" class="j1090kf1c"/></radialGradient><radialGradient id="iTCk0Db" cx="0" cy="0" r="1" gradientTransform="matrix(-4.5 .31246 -.61167 -8.80909 8.986 14.575)" gradientUnits="userSpaceOnUse"><stop class="hiycpfc4f"/><stop offset="1" class="mqq2pckgy"/></radialGradient><radialGradient id="iFYRVOc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.24998 6.93751 -7.49713 -4.5928 9.173 6.762)" gradientUnits="userSpaceOnUse"><stop class="ew56wjbup"/><stop offset="1" class="qd38sjb7e"/></radialGradient><radialGradient id="iLSRrkd" cx="0" cy="0" r="1" gradientTransform="rotate(123.092 2.58 5.63)scale(1.65986 2.90522)" gradientUnits="userSpaceOnUse"><stop offset=".428" class="jbd_cz55y"/><stop offset="1" class="by6guy4wy"/></radialGradient><radialGradient id="iTrVwOc" cx="0" cy="0" r="1" gradientTransform="rotate(151.39 2.514 10.732)scale(1.56625 3.69365)" gradientUnits="userSpaceOnUse"><stop class="qedffdbsn"/><stop offset="1" class="v725rxb4n"/></radialGradient><radialGradient id="i3P2SVc" cx="0" cy="0" r="1" gradientTransform="matrix(.32813 .71875 -2.2725 1.03746 23.548 6.137)" gradientUnits="userSpaceOnUse"><stop class="ze5ugdbxr"/><stop offset="1" class="pr8brkb_h"/></radialGradient><radialGradient id="iJo9vqc" cx="0" cy="0" r="1" gradientTransform="matrix(-.5625 1 -2.31305 -1.3011 9.064 6.262)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="ym0brebyc"/><stop offset="1" class="f-iegb-dq"/></radialGradient><radialGradient id="ixZV9vd" cx="0" cy="0" r="1" gradientTransform="rotate(123.118 3.123 5.625)scale(.58626 1.5796)" gradientUnits="userSpaceOnUse"><stop offset=".492" class="qso4uy3-n"/><stop offset="1" class="b_rfybbbi"/></radialGradient><radialGradient id="iz4EQ1j" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 1 -2.31306 1.3011 23.094 6.262)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="ym0brebyc"/><stop offset="1" class="f-iegb-dq"/></radialGradient><radialGradient id="ip8P7Me" cx="0" cy="0" r="1" gradientTransform="matrix(1.2431 1.58204 -3.03843 2.38745 24.037 4.95)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="j26seachc"/><stop offset=".74" class="rsdjdrd8e"/></radialGradient><radialGradient id="iB3jSMu" cx="0" cy="0" r="1" gradientTransform="matrix(1.64397 -.80986 .45783 .92938 23.231 5.157)" gradientUnits="userSpaceOnUse"><stop offset=".565" class="vj5muxz_t"/><stop offset="1" class="tdhijwbfm"/></radialGradient><radialGradient id="iG2Umfe" cx="0" cy="0" r="1" gradientTransform="matrix(8.002 -4.48996 1.2352 2.20138 9.236 5.856)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="fhunrr5ci"/><stop offset="1" class="as1blab4r"/></radialGradient><radialGradient id="ieIFpXk" cx="0" cy="0" r="1" gradientTransform="matrix(1.25052 1.35191 -6.0911 5.63427 8.079 2.819)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="kwxb4ppbb"/><stop offset="1" class="hj20s6zvr"/></radialGradient><radialGradient id="iGtpw6b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.568 1.57046 -2.49003 -4.07165 24.46 4.38)" gradientUnits="userSpaceOnUse"><stop class="x278nyb7a"/><stop offset=".469" class="bakx-_beg"/></radialGradient><radialGradient id="iQInCtb" cx="0" cy="0" r="1" gradientTransform="matrix(.27173 1.15625 -2.42824 .57066 20.11 1.84)" gradientUnits="userSpaceOnUse"><stop class="nc8kb9b6x"/><stop offset="1" class="xn68z7b1j"/></radialGradient><radialGradient id="iaXr4nb" cx="0" cy="0" r="1" gradientTransform="rotate(145.941 7.214 16.598)scale(7.39327 7.04413)" gradientUnits="userSpaceOnUse"><stop class="gw79ssb0g"/><stop offset="1" class="rpkzo309w"/></radialGradient><radialGradient id="iuMb2nc" cx="0" cy="0" r="1" gradientTransform="rotate(-107.313 7.847 -2.965)scale(1.33912 9.90691)" gradientUnits="userSpaceOnUse"><stop offset=".586" class="bf57i6byh"/><stop offset="1" class="c5ffxnbso"/></radialGradient><radialGradient id="iN4CCgb" cx="0" cy="0" r="1" gradientTransform="rotate(45.373 5.603 13.924)scale(4.51976 4.41679)" gradientUnits="userSpaceOnUse"><stop offset=".819" class="hsn8dgk7l"/><stop offset=".956" class="bcebw6bhr"/></radialGradient><radialGradient id="iuFiWhi" cx="0" cy="0" r="1" gradientTransform="rotate(96.905 7.717 9.339)scale(.37774 1.72952)" gradientUnits="userSpaceOnUse"><stop class="w9m3_8gbd"/><stop offset="1" class="hd06z0qdg"/></radialGradient><radialGradient id="iwNwnId" cx="0" cy="0" r="1" gradientTransform="matrix(-.20247 -1.22554 7.88755 -1.30309 14.119 4.118)" gradientUnits="userSpaceOnUse"><stop offset=".586" class="bf57i6byh"/><stop offset="1" class="c5ffxnbso"/></radialGradient><radialGradient id="i7YjXwd" cx="0" cy="0" r="1" gradientTransform="matrix(2.1943 3.64127 -3.57342 2.15341 13.307 1.068)" gradientUnits="userSpaceOnUse"><stop offset=".776" class="hsn8dgk7l"/><stop offset=".956" class="bcebw6bhr"/></radialGradient><radialGradient id="inY7xje" cx="0" cy="0" r="1" gradientTransform="rotate(90.318 6.68 10.198)scale(.52757 2.91495)" gradientUnits="userSpaceOnUse"><stop class="w9m3_8gbd"/><stop offset="1" class="hd06z0qdg"/></radialGradient><radialGradient id="imNenad" cx="0" cy="0" r="1" gradientTransform="matrix(-.21094 -.90625 8.05091 -1.87395 13.97 4.434)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="bf57i6byh"/><stop offset="1" class="c5ffxnbso"/></radialGradient><radialGradient id="iEVml0l" cx="0" cy="0" r="1" gradientTransform="matrix(-.04687 -.85937 7.6275 -.41603 14.002 4.543)" gradientUnits="userSpaceOnUse"><stop offset=".463" class="bf57i6byh"/><stop offset="1" class="c5ffxnbso"/></radialGradient><radialGradient id="iweHFMc" cx="0" cy="0" r="1" gradientTransform="matrix(1.89062 2.59375 -2.74078 1.9978 13.251 2.575)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="hsn8dgk7l"/><stop offset=".956" class="bcebw6bhr"/></radialGradient><radialGradient id="iFwuKne" cx="0" cy="0" r="1" gradientTransform="matrix(.03906 .35156 -1.87014 .2078 17.486 4.676)" gradientUnits="userSpaceOnUse"><stop class="w9m3_8gbd"/><stop offset="1" class="hd06z0qdg"/></radialGradient><radialGradient id="igEQFic" cx="0" cy="0" r="1" gradientTransform="matrix(-.16967 -1.41407 6.69427 -.80322 13.556 6.107)" gradientUnits="userSpaceOnUse"><stop offset=".586" class="bf57i6byh"/><stop offset="1" class="c5ffxnbso"/></radialGradient><radialGradient id="i9PGoLc" cx="0" cy="0" r="1" gradientTransform="matrix(.03693 .64802 -1.4536 .08285 17.954 6.078)" gradientUnits="userSpaceOnUse"><stop class="w9m3_8gbd"/><stop offset="1" class="hd06z0qdg"/></radialGradient><radialGradient id="i1r78Ob" cx="0" cy="0" r="1" gradientTransform="rotate(104.241 9.592 9.804)scale(4.3577 15.5483)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="bfp_ecc-c"/><stop offset=".936" class="d9wzjmbdf"/></radialGradient><radialGradient id="iZhMIxd" cx="0" cy="0" r="1" gradientTransform="rotate(-107.186 8.997 -1.343)scale(1.58646 3.37754)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="a7d-k3bmr"/><stop offset="1" class="q3wz7tzyo"/></radialGradient><linearGradient id="i7DRfVb" x1="21.564" x2="16.825" y1="17.551" y2="17.551" gradientUnits="userSpaceOnUse"><stop class="aflrgacjk"/><stop offset="1" class="pp1jb50uj"/></linearGradient><linearGradient id="iyhGTzb" x1="15.949" x2="16.88" y1="16.618" y2="16.618" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="iCD0czd" x1="14.781" x2="15.95" y1="16.449" y2="16.513" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="iPnBnoF" x1="15.949" x2="15.949" y1="17.052" y2="17.98" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="i13cYRb" x1="15.949" x2="15.949" y1="14.605" y2="15.062" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="iAdA8nZ" x1="16.611" x2="16.611" y1="5.731" y2="13.793" gradientUnits="userSpaceOnUse"><stop class="n8d2wdipi"/><stop offset=".783" class="y08wiwbty"/></linearGradient><linearGradient id="iSxU6Uu" x1="19.172" x2="18.83" y1="14.931" y2="15.141" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ia3pMjc" x1="14.383" x2="14.042" y1="14.931" y2="15.141" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i6INNnb" x1="22.548" x2="21.673" y1="14.418" y2="17.731" gradientUnits="userSpaceOnUse"><stop class="t4vs15bmo"/><stop offset="1" class="goisaqbuc"/></linearGradient><linearGradient id="i40y5fc" x1="9.58" x2="11.168" y1="15.573" y2="15.434" gradientUnits="userSpaceOnUse"><stop class="xliscob2g"/><stop offset="1" class="xk1gy-y2d"/></linearGradient><linearGradient id="iw8wlwe" x1="13.939" x2="10.634" y1="12.371" y2="13.262" gradientUnits="userSpaceOnUse"><stop offset=".146" class="q_stynbcc"/><stop offset="1" class="amxgxcvbx"/></linearGradient><linearGradient id="iXznDlc" x1="19.611" x2="15.954" y1="12.747" y2="11.887" gradientUnits="userSpaceOnUse"><stop class="q_stynbcc"/><stop offset="1" class="amxgxcvbx"/></linearGradient><linearGradient id="i2l0sfz" x1="15.183" x2="15.658" y1="19.473" y2="18.537" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="iBEThke" x1="11.267" x2="7.298" y1="23.512" y2="27.637" gradientUnits="userSpaceOnUse"><stop class="qcs9a9jeh"/><stop offset="1" class="hza0l88wn"/></linearGradient><linearGradient id="iY3aIyc" x1="10.522" x2="12.654" y1="3.62" y2="2.256" gradientUnits="userSpaceOnUse"><stop offset=".249" class="la4rvxbid"/><stop offset="1" class="j0gi-81kw"/></linearGradient><linearGradient id="iKUULbZ" x1="18.298" x2="21.642" y1="2.387" y2="3.176" gradientUnits="userSpaceOnUse"><stop offset=".664" class="bakx-_beg"/><stop offset="1" class="itvn9lbuv"/></linearGradient><linearGradient id="imkuhMb" x1="17.251" x2="18.704" y1="2.434" y2="2.578" gradientUnits="userSpaceOnUse"><stop class="m5wur4bob"/><stop offset="1" class="jh81_obba"/></linearGradient><linearGradient id="ihl9lUO" x1="12.267" x2="14.049" y1="3.887" y2="3.045" gradientUnits="userSpaceOnUse"><stop offset=".224" class="xw2qhwj5i"/><stop offset="1" class="qg4fklbdo"/></linearGradient><linearGradient id="i9AaQve" x1="17.184" x2="20.002" y1="3.095" y2="3.435" gradientUnits="userSpaceOnUse"><stop offset=".664" class="bakx-_beg"/><stop offset="1" class="itvn9lbuv"/></linearGradient><linearGradient id="iEoEqsd" x1="16.173" x2="17.798" y1="3.481" y2="3.287" gradientUnits="userSpaceOnUse"><stop class="m5wur4bob"/><stop offset="1" class="jh81_obba"/></linearGradient><linearGradient id="iXAwmke" x1="12.228" x2="13.705" y1="4.514" y2="3.628" gradientUnits="userSpaceOnUse"><stop offset=".249" class="qc6cxsufz"/><stop offset="1" class="qg4fklbdo"/></linearGradient><linearGradient id="i88rSQd" x1="17.422" x2="19.359" y1="4.083" y2="4.478" gradientUnits="userSpaceOnUse"><stop offset=".664" class="bakx-_beg"/><stop offset="1" class="itvn9lbuv"/></linearGradient><linearGradient id="iEw9Q5d" x1="16.298" x2="17.789" y1="4.825" y2="3.788" gradientUnits="userSpaceOnUse"><stop class="m5wur4bob"/><stop offset="1" class="jh81_obba"/></linearGradient><linearGradient id="i3FclXt" x1="11.892" x2="13.626" y1="5.778" y2="5.244" gradientUnits="userSpaceOnUse"><stop offset=".249" class="la4rvxbid"/><stop offset="1" class="j0gi-81kw"/></linearGradient><linearGradient id="i5lSxRd" x1="17.894" x2="19.781" y1="4.984" y2="5.181" gradientUnits="userSpaceOnUse"><stop offset=".664" class="bakx-_beg"/><stop offset="1" class="itvn9lbuv"/></linearGradient><linearGradient id="i5xsNnM" x1="16.832" x2="18.687" y1="6.351" y2="5.689" gradientUnits="userSpaceOnUse"><stop class="m5wur4bob"/><stop offset="1" class="jh81_obba"/></linearGradient><filter id="iTuoo8b" width="11.877" height="13.637" x="10.437" y="8.998" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.482353 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3713"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.54902 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3713" result="effect2_innerShadow_4002_3713"/></filter><filter id="ie5j4wd" width="4.044" height="5.157" x="13.701" y="13.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3713" stdDeviation=".5"/></filter><filter id="i8qSYub" width="2.244" height="3.357" x="14.827" y="14.505" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3713" stdDeviation=".05"/></filter><filter id="ihtnoOd" width="14.015" height="9.054" x="8.941" y="5.584" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.890196 0 0 0 0 0.490196 0 0 0 0 0.0784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3713"/></filter><filter id="i1Rq98I" width="7.25" height="6.272" x="9.301" y="6.697" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.372549 0 0 0 0 0.101961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3713"/><feGaussianBlur result="effect2_foregroundBlur_4002_3713" stdDeviation=".15"/></filter><filter id="igh0Bac" width="6.725" height="6.181" x="15.979" y="7.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3713" stdDeviation=".15"/></filter><filter id="iALC78c" width=".839" height=".74" x="17.534" y="14.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3713" stdDeviation=".05"/></filter><filter id="iJGJmne" width=".935" height=".959" x="18.457" y="14.493" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3713" stdDeviation=".1"/></filter><filter id="iQDglqe" width="1.038" height="1.097" x="13.621" y="14.424" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3713" stdDeviation=".1"/></filter><filter id="i8D4X9d" width=".976" height=".749" x="12.79" y="14.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3713" stdDeviation=".05"/></filter><filter id="i9utgtb" width="1.402" height="2.546" x="9.403" y="14.162" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3713" stdDeviation=".125"/></filter><filter id="iUyioIc" width="1.531" height="2.572" x="21.101" y="14.145" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3713" stdDeviation=".125"/></filter><filter id="il6CzWE" width="2.544" height="1.086" x="11.844" y="11.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.317647 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3713"/></filter><filter id="iJA6yid" width="2.594" height="1.136" x="11.769" y="11.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3713" stdDeviation=".125"/></filter><filter id="iBBKVqc" width="2.544" height="1.086" x="17.61" y="11.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.317647 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3713"/></filter><filter id="iQAzmOc" width="2.594" height="1.136" x="17.535" y="11.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3713" stdDeviation=".125"/></filter><filter id="iJZsANb" width="16.188" height="8.656" x="9.173" y="21.981" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3713" stdDeviation=".5"/></filter><filter id="ics92Cd" width="4.094" height="4.656" x="7.923" y="22.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3713" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-gesturing-ok" /></template>
<style>
.a_ex1hboc {
  d: path("m7.398 4.625l-.428.666a.24.24 0 0 0 .01.279c.898 1.155 2.373 1.8 3.283 2.087a.244.244 0 0 0 .28-.108c.151-.247.354-.584.41-.69c.068-.13-.03-.231-.087-.265L7.851 4.766l.125-.274c-.35-.106-.531.045-.578.133");
}

.a7d-k3bmr {
  stop-color: var(--svg-color--f59522, #F59522);
}

.a92dt6njx {
  stop-color: var(--svg-color--b03100, #B03100);
  stop-opacity: 0;
}

.abomb1boi {
  stop-color: var(--svg-color--f49f22, #F49F22);
}

.aflrgacjk {
  stop-color: var(--svg-color--ffd93b, #FFD93B);
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.amxgxcvbx {
  stop-color: var(--svg-color--db7e6a, #DB7E6A);
  stop-opacity: 0;
}

.arq00wbxa {
  d: path("M16.228 9.295a3 3 0 0 1-.073-.149a.72.72 0 0 0-.67-.455H14.1c-2.01 0-3.823 1.646-3.823 3.679v.3c-.37-.283-.676-.57-.676-1.531c0-1.61 2.705-3.589 4.105-3.96A6 6 0 0 1 15.429 7c.468.017.8.42.805.888l.016 1.391z");
}

.as1blab4r {
  stop-color: var(--svg-color--f4bc2d, #F4BC2D);
}

.b_rfybbbi {
  stop-color: var(--svg-color--ff7f40, #FF7F40);
  stop-opacity: 0;
}

.b6ai19bel {
  stop-color: var(--svg-color--ffdc2b, #FFDC2B);
}

.bakx-_beg {
  stop-color: var(--svg-color--ffc53a, #FFC53A);
}

.bcebw6bhr {
  stop-color: var(--svg-color--eca107, #ECA107);
}

.bf57i6byh {
  stop-color: var(--svg-color--ffd843, #FFD843);
  stop-opacity: 0;
}

.bfp_ecc-c {
  stop-color: var(--svg-color--eb8b05, #EB8B05);
  stop-opacity: 0;
}

.borrk8vyp {
  stop-color: var(--svg-color--d05112, #D05112);
}

.bu_xyhfxn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.858 5.371c-.274-.101-1.102-.304-2.172-.242");
}

.bvpcmdbpa {
  d: path("m24.76 4.625l.428.666a.24.24 0 0 1-.01.279c-.898 1.155-2.373 1.8-3.283 2.087a.244.244 0 0 1-.28-.108a22 22 0 0 1-.41-.69c-.068-.13.03-.231.087-.265l3.015-1.828l-.125-.274c.35-.106.532.045.579.133");
}

.by6guy4wy {
  stop-color: var(--svg-color--ff8d29, #FF8D29);
  stop-opacity: 0;
}

.bznr9j1-f {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M8.673 26.668c.48-.448 1.669-1.706 2.594-3.156");
}

.c3tt5y9ub {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.498 4.293c-.43-.11-1.28-.203-2.297-.078");
}

.c4fwxkeyz {
  d: path("M19.192 15.196a.9.9 0 0 0-.252-.503l-.283.31l.128.248z");
}

.c5ffxnbso {
  stop-color: var(--svg-color--ffdd45, #FFDD45);
}

.cgmkvcbsf {
  stop-color: var(--svg-color--a54522, #A54522);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d357yfbjj {
  d: path("m21.624 12.976l-.032-.687c-.011-.831-.698-1.517-1.53-1.552h-1.524c-1.109 0-1.785-.721-2.157-1.628c-.43-1.052.574-1.961 1.668-1.654c1 .282 2.109.71 2.952 1.26c1.9 1.239 1.623 3.21.623 4.261");
}

.d9wzjmbdf {
  stop-color: var(--svg-color--eb8b05, #EB8B05);
}

.da8sh5f1a {
  stop-color: var(--svg-color--ffe137, #FFE137);
}

.dk3a3ccve {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m15.42 15.151l-.691 2.002c-.119.411.165.823.566.823h.856c.402 0 .685-.418.567-.823l-.578-2.002c-.124-.443-.59-.443-.72 0");
}

.dph6anb-e {
  d: path("M9.515 3.075a61 61 0 0 0-1.79 1.61a.08.08 0 0 0-.026.054c-.033.574 1.968 1.625 3.038 2.013q.016.006.034.006c.941-.004 1.105-.372 1.736-.664c.727-.336 1.477-.309 1.867-.309c.391 0 .602-.218.696-.414c.063-.132.064-.316-.03-.523a.63.63 0 0 0 .442-.281a.64.64 0 0 0 .057-.625c.156-.063.336-.304.312-.649c-.038-.537-.562-.661-.781-.656h-.164c.012-.55-.586-.6-.815-.574l-1.717.097a.98.98 0 0 0-.765-.132c-.432.122-1.264.338-2.094 1.047");
}

.dvh6sr_-b {
  fill: var(--svg-color--000, #000);
  d: path("M17.77 15.324c0-.309.248-.556.557-.556a.554.554 0 0 1 .495.812h-.985a.5.5 0 0 1-.067-.256");
}

.dyshkgb1w {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M11.082 3.176c.68-.344 2.47-.57 3.188-.523");
}

.e7ap5jbhs {
  stop-color: var(--svg-color--d55b24, #D55B24);
  stop-opacity: 0;
}

.erxx862yp {
  stroke: var(--svg-color--f9c530, #F9C530);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.66 4.293c.43-.11 1.281-.203 2.297-.078");
}

.ew56wjbup {
  stop-color: var(--svg-color--ff7532, #FF7532);
}

.f-iegb-dq {
  stop-color: var(--svg-color--ff5930, #FF5930);
}

.f55mrubdg {
  stop-color: var(--svg-color--c84a37, #C84A37);
}

.fa128uz1k {
  stop-color: var(--svg-color--a54522, #A54522);
  stop-opacity: 0;
}

.fhunrr5ci {
  stop-color: var(--svg-color--ffd234, #FFD234);
}

.filnodb0j {
  stop-color: var(--svg-color--de602c, #DE602C);
}

.fkf3rcivf {
  stop-color: var(--svg-color--d25c1e, #D25C1E);
  stop-opacity: 0;
}

.fn6ihcc7i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.12 12.747c.265-.193 1.015-.544 1.893-.404");
}

.ft5dv1b6b {
  fill: none;
}

.g7vim1bgz {
  stop-color: var(--svg-color--ed7b14, #ED7B14);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.goisaqbuc {
  stop-color: var(--svg-color--e17615, #E17615);
}

.gpdgpl4qm {
  stop-color: var(--svg-color--c18637, #C18637);
}

.gw79ssb0g {
  stop-color: var(--svg-color--ff8540, #FF8540);
}

.gxq3n8btl {
  stop-color: var(--svg-color--dc5c1a, #DC5C1A);
}

.h9fb5bbiv {
  stop-color: var(--svg-color--ffa143, #FFA143);
}

.hd06z0qdg {
  stop-color: var(--svg-color--d5a136, #D5A136);
  stop-opacity: 0;
}

.hiycpfc4f {
  stop-color: var(--svg-color--ff711c, #FF711C);
}

.hj20s6zvr {
  stop-color: var(--svg-color--d1a345, #D1A345);
  stop-opacity: 0;
}

.hsn8dgk7l {
  stop-color: var(--svg-color--eca107, #ECA107);
  stop-opacity: 0;
}

.hy2-e6lon {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M19.779 12.747c-.266-.193-1.017-.544-1.894-.404");
}

.hza0l88wn {
  stop-color: var(--svg-color--ff6e3a, #FF6E3A);
  stop-opacity: 0;
}

.ic62vub6d {
  d: path("M21.242 17.077c.365-.012.706-.136.985-.336v1.014c0 .972-.58 1.838-1.46 2.198q.279-.594.376-1.285z");
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.ijcelgbiw {
  stop-color: var(--svg-color--ffdc2b, #FFDC2B);
  stop-opacity: 0;
}

.itvn9lbuv {
  stop-color: var(--svg-color--ffc53a, #FFC53A);
  stop-opacity: 0;
}

.j0gi-81kw {
  stop-color: var(--svg-color--fbc831, #FBC831);
  stop-opacity: 0;
}

.j1090kf1c {
  stop-color: var(--svg-color--ff6428, #FF6428);
  stop-opacity: 0;
}

.j161udblr {
  stroke: var(--svg-color--f9c530, #F9C530);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M11.082 3.176c.68-.344 2.47-.57 3.188-.523");
}

.j26seachc {
  stop-color: var(--svg-color--ff8547, #FF8547);
}

.jbd_cz55y {
  stop-color: var(--svg-color--ff8d29, #FF8D29);
}

.jfo6z-bud {
  stop-color: var(--svg-color--fca33b, #FCA33B);
  stop-opacity: 0;
}

.jh81_obba {
  stop-color: var(--svg-color--d29e3b, #D29E3B);
  stop-opacity: 0;
}

.jteqbw4wj {
  stop-color: var(--svg-color--de602c, #DE602C);
  stop-opacity: 0;
}

.k41qw1b_j {
  stop-color: var(--svg-color--cc4322, #CC4322);
}

.kc3wm8i6w {
  stop-color: var(--svg-color--ffc92f, #FFC92F);
}

.krb79obir {
  d: path("M7.313 5.356c-.203-.058-.677-.155-.946-.086c-.335.086-.593.328-.812.687a958 958 0 0 0-2.094 3.54c-.562.822-1.625 3.087-1.375 5.562c.1 1.662.781 3.339 1.11 3.969l4.132 7.854c.173.33.187.719.08 1.076c-.158.529-.322 1.28-.322 2.023h17.828c0-.743-.164-1.494-.322-2.023a1.43 1.43 0 0 1 .08-1.076l4.133-7.854c.328-.63 1.01-2.307 1.11-3.97c.25-2.474-.813-4.739-1.376-5.562a914 914 0 0 0-2.093-3.539c-.22-.359-.477-.601-.813-.687c-.269-.069-.742.028-.945.086L21.5 7.52c-.351.414-.19.966-.054 1.18l2.075 3.511a4.5 4.5 0 0 1 .11 4.382l-2.96 5.634a.37.37 0 0 1-.493.152a14 14 0 0 0-1.12-.483a4.3 4.3 0 0 1-.775.336v.023a2.307 2.307 0 1 1-4.614 0v-.009a4.3 4.3 0 0 1-.782-.329c-.395.155-.763.312-1.064.462a.37.37 0 0 1-.493-.152l-2.96-5.634a4.5 4.5 0 0 1 .11-4.382L10.555 8.7c.135-.214.297-.766-.055-1.18z");
}

.kwxb4ppbb {
  stop-color: var(--svg-color--d1a345, #D1A345);
}

.l-pepacun {
  stop-color: var(--svg-color--da3b1c, #DA3B1C);
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.la4rvxbid {
  stop-color: var(--svg-color--fbc831, #FBC831);
}

.lc2vbwt6n {
  d: path("M10.446 13.692a1.752 1.752 0 0 0 .151 3.484a85 85 0 0 1-.15-3.484");
}

.lguy1wbep {
  stop-color: var(--svg-color--ffe137, #FFE137);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lk74nfb1g {
  fill: var(--svg-color--c75c21, #C75C21);
  fill-rule: evenodd;
  d: path("M13.97 12.615c-.79-.127-1.468.194-1.69.354a.275.275 0 1 1-.323-.444c.31-.226 1.134-.608 2.1-.453a.275.275 0 0 1-.087.543");
}

.lmu7vkr7n {
  stop-color: var(--svg-color--d55b24, #D55B24);
}

.m5wur4bob {
  stop-color: var(--svg-color--d29e3b, #D29E3B);
}

.m6rjd1bzx {
  fill: var(--svg-color--e17f21, #E17F21);
  d: path("M21.351 16.467q.064-1.035.12-2.072a1.04 1.04 0 0 1-.12 2.072");
}

.map2p9bzf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.66 4.293c.43-.11 1.281-.203 2.297-.078");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mepywd5ec {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.552 14.057c.711 0 1.312.49 1.475 1.152a.298.298 0 0 1-.291.371h-2.43a.25.25 0 0 1-.247-.296a1.52 1.52 0 0 1 1.493-1.227");
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.mqlp12d1r {
  d: path("M21.308 17.176q.108-1.738.2-3.475a1.752 1.752 0 0 1-.2 3.475");
}

.mqq2pckgy {
  stop-color: var(--svg-color--ff711c, #FF711C);
  stop-opacity: 0;
}

.n8d2wdipi {
  stop-color: var(--svg-color--ffbf1d, #FFBF1D);
}

.nc8kb9b6x {
  stop-color: var(--svg-color--d4ab3c, #D4AB3C);
}

.ndfe_mbxn {
  width: 4.615px;
  height: 6.587px;
  x: 13.669px;
  y: 17.976px;
  rx: 2.307px;
}

.npixnyb9v {
  stop-color: var(--svg-color--ffc93f, #FFC93F);
}

.ntf_h0bkc {
  stop-color: var(--svg-color--cd5e18, #CD5E18);
}

.o6lz2aclp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M20.126 3.598c-.43-.11-2.375-.477-3.254-.266");
}

.o9jbu96ji {
  d: path("M21.235 8.484c.56.192 1.062.584 1.38 1.144a2.58 2.58 0 0 1-.116 2.75c-.19.281-.294.614-.294.953v1.293a1.9 1.9 0 0 0-.727-.292l.086-1.749a1.58 1.58 0 0 0-1.502-1.56h-1.524c-1.04 0-1.98-.612-2.408-1.57a.72.72 0 0 0-.67-.455h-1.386c-2.01 0-3.638 1.646-3.638 3.679l.034 1.673c-.277.04-.566.133-.784.287v-1.306c0-.34-.104-.672-.295-.952a2.6 2.6 0 0 1-.156-2.663a2.55 2.55 0 0 1 1.415-1.227c.624-.221 1.026-.607 1.378-1.173c.45-.719 1.37-1.232 2.277-1.232c.352 0 .687.045.999.173c.415.181.883.181 1.299 0c.306-.128.641-.173.994-.173c.918 0 1.72.496 2.165 1.232c.335.554.86.957 1.473 1.168");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oh07ifbww {
  d: path("M18.255 14.558c.07.093-.075.206-.24.329c-.164.122-.286.209-.355.117c-.07-.093.008-.268.172-.39c.165-.124.354-.149.423-.056");
}

.ov282fbso {
  stop-color: var(--svg-color--d25c1e, #D25C1E);
}

.p32iuoeum {
  stop-color: var(--svg-color--d05112, #D05112);
  stop-opacity: 0;
}

.pe1y1gbgg {
  d: path("M23.939 27.137c-1.95-1.2-3.037-3.417-3.36-4.156c-5.174 0-9.28 1.968-10.406 6.656h14.188c0-.9-.157-1.937-.422-2.5");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pp1jb50uj {
  stop-color: var(--svg-color--ffd93b, #FFD93B);
  stop-opacity: 0;
}

.pr8brkb_h {
  stop-color: var(--svg-color--ff7840, #FF7840);
  stop-opacity: 0;
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.q_stynbcc {
  stop-color: var(--svg-color--db7e6a, #DB7E6A);
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.q3wz7tzyo {
  stop-color: var(--svg-color--f59522, #F59522);
  stop-opacity: 0;
}

.q5loxgbuq {
  stop-color: var(--svg-color--c18637, #C18637);
  stop-opacity: 0;
}

.q8kwjlr2l {
  stop-color: var(--svg-color--ee8d0c, #EE8D0C);
  stop-opacity: 0;
}

.qc6cxsufz {
  stop-color: var(--svg-color--fdcd33, #FDCD33);
}

.qcs9a9jeh {
  stop-color: var(--svg-color--ff6e3a, #FF6E3A);
}

.qd-1m5bst {
  stop-color: var(--svg-color--e06801, #E06801);
}

.qd38sjb7e {
  stop-color: var(--svg-color--ff7532, #FF7532);
  stop-opacity: 0;
}

.qedffdbsn {
  stop-color: var(--svg-color--e53a03, #E53A03);
}

.qg4fklbdo {
  stop-color: var(--svg-color--fdcd33, #FDCD33);
  stop-opacity: 0;
}

.qso4uy3-n {
  stop-color: var(--svg-color--ff7f40, #FF7F40);
}

.qtwfj5bch {
  stop-color: var(--svg-color--ffbd38, #FFBD38);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxb44vbzx {
  cx: 13.278px;
  cy: 14.768px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.424px;
  ry: 0.215px;
}

.qxdr41lmo {
  fill: var(--svg-color--c75c21, #C75C21);
  fill-rule: evenodd;
  d: path("M17.928 12.615c.79-.127 1.468.194 1.689.354a.275.275 0 0 0 .323-.444c-.31-.226-1.133-.608-2.099-.453a.275.275 0 1 0 .087.543");
}

.r1epb9vkn {
  d: path("M13.571 14.353a.972.972 0 0 0-.936 1.227h1.877a1 1 0 0 0 .035-.256a.98.98 0 0 0-.976-.972");
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r4mmzix7f {
  fill: var(--svg-color--e36d21, #E36D21);
  d: path("M10.465 14.412a1.04 1.04 0 0 0 .09 2.046a85 85 0 0 1-.09-2.046");
}

.r7_51rhvn {
  d: path("M10.656 17.077a1.8 1.8 0 0 1-.985-.336v1.014c0 .972.58 1.838 1.46 2.198a4.5 4.5 0 0 1-.376-1.285z");
}

.r7hr49baf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-4px, 1.4px);
  d: path("M12.62 3.48c.43-.109 1.65-.273 2.667-.148");
}

.r8d5udbxl {
  stop-color: var(--svg-color--e7771f, #E7771F);
}

.rpkzo309w {
  stop-color: var(--svg-color--ff8540, #FF8540);
  stop-opacity: 0;
}

.rsdjdrd8e {
  stop-color: var(--svg-color--ff8547, #FF8547);
  stop-opacity: 0;
}

.sd2t_cbsx {
  d: path("M10.696 18.726a4.26 4.26 0 0 0 4.23 3.709h2.054a4.26 4.26 0 0 0 4.231-3.709c.129-2.05.258-4.093.353-6.143a1.58 1.58 0 0 0-1.501-1.56h-1.525c-1.04 0-1.98-.612-2.408-1.57a.72.72 0 0 0-.67-.455h-1.386c-2.009 0-3.637 1.646-3.637 3.679c0 2.025.126 4.018.259 6.05");
}

.six73iixf {
  d: path("m15.533 14.938l-.579 2.001c-.118.412.165.824.567.824h.856c.402 0 .685-.418.567-.824l-.579-2.001c-.124-.444-.702-.444-.832 0");
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.sw1t1obly {
  stop-color: var(--svg-color--ef9330, #EF9330);
  stop-opacity: 0;
}

.t-37x237r {
  stop-color: var(--svg-color--da3b1c, #DA3B1C);
  stop-opacity: 0;
}

.t4vs15bmo {
  stop-color: var(--svg-color--df9238, #DF9238);
}

.tdhijwbfm {
  stop-color: var(--svg-color--ff6f33, #FF6F33);
  stop-opacity: 0;
}

.tu8w3ebaf {
  d: path("M14.459 15.21c0-.314-.255-.523-.324-.587l-.314.304l.193.393z");
}

.tvze-lbke {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.255 14.558c.07.093-.075.206-.24.329c-.164.122-.286.209-.355.117c-.07-.093.008-.268.172-.39c.165-.124.354-.149.423-.056");
}

.u8_2n4b4n {
  fill: var(--svg-color--ffb72f, #FFB72F);
  d: path("m21.624 12.976l-.032-.687c-.011-.831-.698-1.517-1.53-1.552h-1.524c-1.109 0-1.785-.721-2.157-1.628c-.43-1.052.574-1.961 1.668-1.654c1 .282 2.109.71 2.952 1.26c1.9 1.239 1.623 3.21.623 4.261");
}

.uuua36bph {
  stroke: var(--svg-color--f9c530, #F9C530);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-4px, 1.4px);
  d: path("M12.62 3.48c.43-.109 1.65-.273 2.667-.148");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v725rxb4n {
  stop-color: var(--svg-color--e53a03, #E53A03);
  stop-opacity: 0;
}

.v7axozgfh {
  stop-color: var(--svg-color--b03100, #B03100);
}

.vdnt3rb5p {
  fill: var(--svg-color--ff8e25, #FF8E25);
  d: path("M16.228 9.295a3 3 0 0 1-.073-.149a.72.72 0 0 0-.67-.455H14.1c-2.01 0-3.823 1.646-3.823 3.679v.3c-.37-.283-.676-.57-.676-1.531c0-1.61 2.705-3.589 4.105-3.96A6 6 0 0 1 15.429 7c.468.017.8.42.805.888l.016 1.391z");
}

.vik2xmvjh {
  d: path("M18.327 14.353a.972.972 0 0 1 .936 1.227h-1.877a.975.975 0 0 1 .94-1.228");
}

.vj5muxz_t {
  stop-color: var(--svg-color--ff6f33, #FF6F33);
}

.vkbtw3twt {
  cx: 13.278px;
  cy: 14.768px;
  rx: 0.424px;
  ry: 0.215px;
}

.w9m3_8gbd {
  stop-color: var(--svg-color--d5a136, #D5A136);
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wc2d54euw {
  stop-color: var(--svg-color--cd5e18, #CD5E18);
  stop-opacity: 0;
}

.wkxq-bjsc {
  fill: var(--svg-color--ff5918, #FF5918);
  d: path("M7.313 5.356c-.203-.058-.677-.155-.946-.086c-.335.086-.593.328-.812.687a958 958 0 0 0-2.094 3.54c-.562.822-1.625 3.087-1.375 5.562c.1 1.662.781 3.339 1.11 3.969l4.132 7.854c.173.33.187.719.08 1.076c-.158.529-.322 1.28-.322 2.023h17.828c0-.743-.164-1.494-.322-2.023a1.43 1.43 0 0 1 .08-1.076l4.133-7.854c.328-.63 1.01-2.307 1.11-3.97c.25-2.474-.813-4.739-1.376-5.562a914 914 0 0 0-2.093-3.539c-.22-.359-.477-.601-.813-.687c-.269-.069-.742.028-.945.086L21.5 7.52c-.351.414-.19.966-.054 1.18l2.075 3.511a4.5 4.5 0 0 1 .11 4.382l-2.96 5.634a.37.37 0 0 1-.493.152a14 14 0 0 0-1.12-.483a4.3 4.3 0 0 1-.775.336v.023a2.307 2.307 0 1 1-4.614 0v-.009a4.3 4.3 0 0 1-.782-.329c-.395.155-.763.312-1.064.462a.37.37 0 0 1-.493-.152l-2.96-5.634a4.5 4.5 0 0 1 .11-4.382L10.555 8.7c.135-.214.297-.766-.055-1.18z");
}

.wrt_z3bum {
  fill: var(--svg-color--000, #000);
  d: path("M14.128 15.324a.554.554 0 0 0-.557-.556a.554.554 0 0 0-.495.813h.986a.55.55 0 0 0 .066-.257");
}

.wtzd4lbuc {
  stop-color: var(--svg-color--ffbd38, #FFBD38);
  stop-opacity: 0;
}

.x278nyb7a {
  stop-color: var(--svg-color--ffe23e, #FFE23E);
}

.x5fl8bb9z {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M21.076 3.176c-.68-.344-2.47-.57-3.188-.523");
}

.xk1gy-y2d {
  stop-color: var(--svg-color--dd6f17, #DD6F17);
}

.xliscob2g {
  stop-color: var(--svg-color--e57a18, #E57A18);
}

.xn68z7b1j {
  stop-color: var(--svg-color--d4ab3c, #D4AB3C);
  stop-opacity: 0;
}

.xw2qhwj5i {
  stop-color: var(--svg-color--fbca32, #FBCA32);
}

.y08wiwbty {
  stop-color: var(--svg-color--cd7537, #CD7537);
}

.y42awybvc {
  stop-color: var(--svg-color--ee8d0c, #EE8D0C);
}

.ygt1ak-zz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.3 5.371c.274-.101 1.102-.304 2.172-.242");
}

.ym0brebyc {
  stop-color: var(--svg-color--ff6a31, #FF6A31);
}

.yq9cl_lgn {
  stop-color: var(--svg-color--ef9330, #EF9330);
}

.yr79k9src {
  d: path("M22.643 3.075a61 61 0 0 1 1.79 1.61a.08.08 0 0 1 .027.054c.032.574-1.969 1.625-3.039 2.013a.1.1 0 0 1-.034.006c-.941-.004-1.105-.372-1.736-.664c-.727-.336-1.477-.309-1.867-.309s-.602-.218-.696-.414c-.063-.132-.064-.316.03-.523a.63.63 0 0 1-.442-.281a.64.64 0 0 1-.056-.625c-.157-.063-.337-.304-.313-.649c.038-.537.563-.661.781-.656h.165c-.013-.55.585-.6.814-.574l1.717.097a.98.98 0 0 1 .765-.132c.433.122 1.264.338 2.094 1.047");
}

.zav_leb7s {
  stop-color: var(--svg-color--fac137, #FAC137);
}

.zca_mdy1y {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.346 14.057a1.52 1.52 0 0 0-1.475 1.152a.298.298 0 0 0 .291.371h2.43a.25.25 0 0 0 .247-.296a1.526 1.526 0 0 0-1.493-1.227");
}

.zdjlj62cy {
  stroke: var(--svg-color--f9c530, #F9C530);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.3 5.371c.274-.101 1.102-.304 2.172-.242");
}

.ze5ugdbxr {
  stop-color: var(--svg-color--ff7840, #FF7840);
}

.zzzw2cchg {
  fill: var(--svg-color--8a004f, #8A004F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.452 18.322c.44.23.965.361 1.524.361c.565 0 1.084-.131 1.524-.36v-.001a.22.22 0 0 1 .263.043a.205.205 0 0 1 .023.263m-3.334-.306l3.292.278m-3.292-.278a.22.22 0 0 0-.263.046a.2.2 0 0 0-.023.26m.286-.306l-.244.278m3.578.028l-.042-.028m.042.028l-.042-.028m.042.028c-.383.58-1.05.967-1.81.967s-1.427-.387-1.81-.967m3.578-.028a2.11 2.11 0 0 1-1.768.945a2.11 2.11 0 0 1-1.768-.945m-.042.028l.042-.028m-.042.028l.042-.028");
}

</style>
