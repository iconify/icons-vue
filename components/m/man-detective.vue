<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="j_dulcbnt"/><path fill="url(#iAlKUYw)" class="ng-28zxwb"/><path fill="url(#itbtQzd)" class="ng-28zxwb"/><path fill="url(#iOhOn5b)" class="ng-28zxwb"/><path fill="url(#i8ngfnv)" class="ng-28zxwb"/><path fill="url(#ilxDSxc)" class="ng-28zxwb"/><path class="em148031i"/><path fill="url(#iAomAlC)" class="tnef9wrdf"/><path fill="url(#ig9e68k)" class="tnef9wrdf"/><path fill="url(#iB0vApd)" class="tnef9wrdf"/><g filter="url(#iCBBHGb)"><path class="zagiflbwl"/></g><path fill="url(#i27EXBe)" class="g7gmqhncd"/><path fill="url(#im8Vkvd)" class="g7gmqhncd"/><path fill="url(#i39ExJd)" class="g7gmqhncd"/><path fill="url(#iWKZSod)" class="by194g1ei"/><path fill="url(#idsRMlc)" class="by194g1ei"/><g filter="url(#i2ghKzd)"><path fill="url(#ieVAJKD)" class="gemgotgww"/></g><path fill="url(#iOeoa4b)" class="zswbabceh"/><path fill="url(#im9eHqM)" class="zswbabceh"/><path fill="url(#iTudamq)" class="zswbabceh"/><path fill="url(#iEbPnCK)" class="wibdzhbon"/><path fill="url(#itSm4AK)" class="wibdzhbon"/><path fill="url(#iEpqGnc)" class="wibdzhbon"/><path fill="url(#iHu3LFd)" class="wibdzhbon"/><path fill="url(#iP6c0ue)" class="wibdzhbon"/><path class="yyxxh9qfh"/><path fill="url(#iyKMIle)" class="s0-op-jbm"/><path fill="url(#iC6TSsc)" class="s0-op-jbm"/><path fill="url(#i7oZ1zb)" class="s0-op-jbm"/><path fill="url(#ira2lKd)" class="s0-op-jbm"/><path fill="url(#iknlR1o)" class="s0-op-jbm"/><path fill="url(#iagGylc)" class="j-ut2xl5o"/><path fill="url(#izArx6c)" class="j-ut2xl5o"/><g filter="url(#iTAcR2c)"><path fill="url(#i9VYgXa)" class="n3lyoibnh"/><path fill="url(#ixKBBIe)" class="n3lyoibnh"/><path fill="url(#iA7Jkfc)" class="n3lyoibnh"/><path fill="url(#imEendb)" class="n3lyoibnh"/><path fill="url(#idvppfb)" class="n3lyoibnh"/></g><g filter="url(#iUjDYWR)"><path fill="url(#iSfw5wd)" class="f5u9q1n2l"/><path fill="url(#iiIvpQb)" class="f5u9q1n2l"/><path fill="url(#isUiL6c)" class="f5u9q1n2l"/><path fill="url(#iPij2KA)" class="f5u9q1n2l"/></g><g filter="url(#iV3Af7d)"><path fill="url(#izbN4Td)" class="rhxl5gb9p"/><path fill="url(#imTGR8d)" class="rhxl5gb9p"/></g><rect fill="url(#iz2Begd)" class="erhkeibcy"/><rect fill="url(#iWBccNc)" class="erhkeibcy"/><rect fill="url(#ih9GmGc)" class="erhkeibcy"/><rect fill="url(#iJ8MAGd)" class="erhkeibcy"/><g filter="url(#iwaEWBV)"><circle class="k7e504bil"/></g><circle fill="url(#iU1hsCv)" class="vd-u4acdq"/><circle fill="url(#i5Fhu0c)" class="vd-u4acdq"/><g filter="url(#iSUvkub)"><path fill="url(#iIrRcKb)" clip-rule="evenodd" class="g1ovp4bwp"/></g><rect fill="url(#is19MEd)" transform="rotate(-30 25.512 15.977)" class="tjiypub2l"/><g filter="url(#iC32qyd)"><path fill="url(#isY3IOc)" class="quksm7bdn"/><path fill="url(#iFgje2e)" class="quksm7bdn"/><path fill="url(#iGSGsbb)" class="quksm7bdn"/><path fill="url(#iB9gv3c)" class="quksm7bdn"/><path fill="url(#iiPRvHe)" class="quksm7bdn"/></g><g filter="url(#iCfeETV)"><path stroke="url(#iCfmprE)" class="bqtb9rbsu"/></g><g filter="url(#in3k83c)"><path stroke="url(#iUqjLqd)" class="rqg1a3anv"/></g><g filter="url(#i9UlTPN)"><path stroke="url(#iCTLnoq)" class="yu54nqayv"/></g><circle fill="url(#ijgToNe)" class="mh39h7hpm"/><g filter="url(#iIZ6sRh)"><circle fill="url(#iydLx9b)" class="ep1m_ub9u"/></g><g filter="url(#iDKEEWd)"><circle fill="url(#iYhzLfc)" class="n0h_63bcp"/><circle fill="url(#iVHCn3X)" class="n0h_63bcp"/></g><g filter="url(#iydUDBc)"><circle class="s9abuujkb"/><circle fill="url(#i6E2hWu)" class="cenqke63g"/><circle fill="url(#iW6DVMT)" class="cenqke63g"/></g><g filter="url(#iboybRd)"><path fill="url(#iEy3iIb)" class="yhqewxb9n"/></g><path fill="url(#iaNodxc)" class="yhqewxb9n"/><path fill="url(#ibJFaCR)" class="yhqewxb9n"/><path fill="url(#inb7ZSc)" class="yhqewxb9n"/><g filter="url(#iGavTud)"><path class="zlum0zc8n"/></g><g filter="url(#iH3f4Qc)"><path class="pdrrorwco"/><path fill="url(#iBqnAde)" class="sxgpvtb4k"/><path fill="url(#ifmGGtd)" class="sxgpvtb4k"/></g><g filter="url(#iLPL4Wb)"><path fill="url(#ipvJ5Ne)" class="kdvr4u58b"/></g><g filter="url(#iabhXzG)"><path stroke="url(#iDZcqGr)" class="kqcubybll"/></g><path class="sx-22hbhr"/><path class="qbj5mmbvn"/><path fill="url(#iijYZwb)" class="jgjt2xbnj"/><path class="rrgrst12i"/><g filter="url(#i5cV7ke)"><path class="mp8t_zb5c"/><path fill="url(#icmYJFc)" class="l_9dr2bhm"/></g><g filter="url(#iG5Qute)"><path fill="url(#iE5JQae)" class="oor1kvo5l"/></g><path class="hzw4atb3f"/><path fill="url(#iMzVYMb)" class="d6h0d6b8p"/><path class="mibx7d57r"/><g filter="url(#isKlkhe)"><path fill="url(#iN3jgZV)" class="v9c6zoseo"/></g><g filter="url(#iceMD8L)"><ellipse transform="rotate(-27.914 11.99 11.985)" class="dfqbekbrj"/><ellipse fill="url(#iFbcshM)" transform="rotate(-27.914 11.99 11.985)" class="xd4qu1b2a"/></g><path fill="url(#iJcqtje)" class="kdzxr8bcy"/><path fill="url(#iTVvQNd)" class="ijrk-tbbt"/><g filter="url(#iDZdQVN)"><path fill="url(#i8gh6Fe)" class="ivj3pk5jv"/></g><path fill="url(#iBfj5Pd)" class="ivj3pk5jv"/><path fill="url(#ieAjMmb)" class="ivj3pk5jv"/><g filter="url(#ipkDtBd)"><path fill="url(#iodu1md)" class="jpbxw370c"/></g><path fill="url(#iTUCPGc)" class="dnfp-euku"/><path fill="url(#iAJlZRd)" class="dnfp-euku"/><path fill="url(#iLKj4pc)" class="dnfp-euku"/><path fill="url(#iAYhuWd)" class="dnfp-euku"/><defs><radialGradient id="iAlKUYw" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.90625 -2.3125 0 6.773 21.813)" gradientUnits="userSpaceOnUse"><stop class="zy5dj18nw"/><stop offset="1" class="ol5y5gj7m"/></radialGradient><radialGradient id="itbtQzd" cx="0" cy="0" r="1" gradientTransform="rotate(-120.646 14.441 11.476)scale(11.587 1.53635)" gradientUnits="userSpaceOnUse"><stop offset=".336" class="cj2gegbdf"/><stop offset="1" class="cw9lwsb0z"/></radialGradient><radialGradient id="i8ngfnv" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.0625 -2.5 0 22.836 22.157)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="j05e95eeg"/><stop offset="1" class="i7g4iz6bw"/></radialGradient><radialGradient id="ilxDSxc" cx="0" cy="0" r="1" gradientTransform="rotate(20.493 -65.417 66.253)scale(3.30276 13.733)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="fchl8077b"/><stop offset="1" class="nig76no1i"/></radialGradient><radialGradient id="ig9e68k" cx="0" cy="0" r="1" gradientTransform="rotate(103.743 .522 17.985)scale(2.95973 1.64796)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="z_k8o-57c"/><stop offset="1" class="rxpl4qnie"/></radialGradient><radialGradient id="iB0vApd" cx="0" cy="0" r="1" gradientTransform="matrix(.8422 3.48214 -1.84594 .44646 11.586 20.885)" gradientUnits="userSpaceOnUse"><stop offset=".624" class="gi2uz_g9v"/><stop offset="1" class="qasiqcczj"/></radialGradient><radialGradient id="i27EXBe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.3594 4.25 0 6.367 29.922)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="kvzrrwynu"/><stop offset="1" class="nf2o-hpjm"/></radialGradient><radialGradient id="im8Vkvd" cx="0" cy="0" r="1" gradientTransform="rotate(117.646 -2.545 12.698)scale(4.44498 4.85494)" gradientUnits="userSpaceOnUse"><stop class="k1zgefb2d"/><stop offset="1" class="lg14abbip"/></radialGradient><radialGradient id="i39ExJd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.7344 2.803 0 7.023 29.922)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="nzffxlbem"/><stop offset="1" class="pb1ehqpec"/></radialGradient><radialGradient id="iWKZSod" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.45316 -3.24716 0 24.875 23.47)" gradientUnits="userSpaceOnUse"><stop class="j11nupb8y"/><stop offset="1" class="c_gtmdbzk"/></radialGradient><radialGradient id="idsRMlc" cx="0" cy="0" r="1" gradientTransform="matrix(1.96327 -.27323 1.61732 11.6211 22.726 29.921)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="k9h8bsbwk"/><stop offset="1" class="xtl5dn5fo"/></radialGradient><radialGradient id="ieVAJKD" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.2093 -2.72578 0 14.859 22.655)" gradientUnits="userSpaceOnUse"><stop class="fisd__bqs"/><stop offset="1" class="wss6y3b2p"/></radialGradient><radialGradient id="iOeoa4b" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.0625 -.95313 0 14.851 24.782)" gradientUnits="userSpaceOnUse"><stop class="op_u9g8uj"/><stop offset="1" class="asvjbc-zd"/></radialGradient><radialGradient id="iEbPnCK" cx="0" cy="0" r="1" gradientTransform="matrix(-4.18748 2.46878 -3.8188 -6.47736 14.398 20.97)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="e9sv_2buc"/><stop offset="1" class="altutfb8x"/></radialGradient><radialGradient id="iEpqGnc" cx="0" cy="0" r="1" gradientTransform="rotate(104.036 -1.196 14.246)scale(1.84281 2.98915)" gradientUnits="userSpaceOnUse"><stop class="ylkb8lnyx"/><stop offset="1" class="zqbz6fbvb"/></radialGradient><radialGradient id="iHu3LFd" cx="0" cy="0" r="1" gradientTransform="rotate(-132.274 12.135 8.129)scale(.4746 3.14325)" gradientUnits="userSpaceOnUse"><stop class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iP6c0ue" cx="0" cy="0" r="1" gradientTransform="matrix(-.64914 .713 -1.62712 -1.4814 14.048 20.862)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iyKMIle" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 3.20313 -4.95471 3.77041 15.586 20.47)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="o58_qgbus"/><stop offset="1" class="l9k3lrq7u"/></radialGradient><radialGradient id="i7oZ1zb" cx="0" cy="0" r="1" gradientTransform="rotate(75.964 -3.372 20.583)scale(1.84281 2.98915)" gradientUnits="userSpaceOnUse"><stop class="ylkb8lnyx"/><stop offset="1" class="zqbz6fbvb"/></radialGradient><radialGradient id="ira2lKd" cx="0" cy="0" r="1" gradientTransform="matrix(.31925 -.35118 2.32584 2.11435 15.467 22.576)" gradientUnits="userSpaceOnUse"><stop class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iknlR1o" cx="0" cy="0" r="1" gradientTransform="matrix(.64914 .71299 -1.62712 1.4814 15.7 20.862)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iagGylc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.77344 -3.32031 0 14.875 19.875)" gradientUnits="userSpaceOnUse"><stop offset=".229" class="b03y_pbel"/><stop offset="1" class="phm_r04pf"/></radialGradient><radialGradient id="izArx6c" cx="0" cy="0" r="1" gradientTransform="matrix(-4.1875 .68753 -.20052 -1.22128 15.367 19.282)" gradientUnits="userSpaceOnUse"><stop class="efj5ccoqw"/><stop offset="1" class="k_2y5fb4u"/></radialGradient><radialGradient id="iA7Jkfc" cx="0" cy="0" r="1" gradientTransform="rotate(-154.011 8.397 8.282)scale(8.72259 3.48034)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="mw9gk7bly"/><stop offset="1" class="dv70acbut"/></radialGradient><radialGradient id="idvppfb" cx="0" cy="0" r="1" gradientTransform="rotate(33.19 -29.316 21.252)scale(2.48324 .7466)" gradientUnits="userSpaceOnUse"><stop class="foejprbbc"/><stop offset="1" class="kpssiabxl"/></radialGradient><radialGradient id="isUiL6c" cx="0" cy="0" r="1" gradientTransform="matrix(3.20501 -2.78125 1.73626 2.0008 17.148 23.25)" gradientUnits="userSpaceOnUse"><stop class="f87czphzs"/><stop offset="1" class="pwa97nbfq"/></radialGradient><radialGradient id="iPij2KA" cx="0" cy="0" r="1" gradientTransform="rotate(149.744 8.39 12.982)scale(1.73656 .44089)" gradientUnits="userSpaceOnUse"><stop class="mx64gfpes"/><stop offset="1" class="xqc8z1bhj"/></radialGradient><radialGradient id="izbN4Td" cx="0" cy="0" r="1" gradientTransform="rotate(117.802 7.114 19.739)scale(2.05934 1.65405)" gradientUnits="userSpaceOnUse"><stop class="id09adcid"/><stop offset=".828" class="gtmq6ja1j"/></radialGradient><radialGradient id="imTGR8d" cx="0" cy="0" r="1" gradientTransform="matrix(.46055 -.4563 .48587 .4904 26.881 24.065)" gradientUnits="userSpaceOnUse"><stop class="xcc0mcchc"/><stop offset="1" class="lyxdnwxxe"/></radialGradient><radialGradient id="ih9GmGc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38281 .60155 -.43729 -1.00521 25.539 20.227)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="bslse1b3i"/><stop offset="1" class="t11-a9gub"/></radialGradient><radialGradient id="iJ8MAGd" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 .42875 26.523 21.266)" gradientUnits="userSpaceOnUse"><stop offset=".112" class="bc2ld5biv"/><stop offset="1" class="a6yy9-nlq"/></radialGradient><radialGradient id="iU1hsCv" cx="0" cy="0" r="1" gradientTransform="matrix(-3.91576 4.34721 -4.19506 -3.7787 28.15 15.25)" gradientUnits="userSpaceOnUse"><stop offset=".004" class="ig92uxq3u"/><stop offset="1" class="thvbr9biq"/></radialGradient><radialGradient id="i5Fhu0c" cx="0" cy="0" r="1" gradientTransform="matrix(2.157 -2.3893 4.6402 4.18907 23.372 19.73)" gradientUnits="userSpaceOnUse"><stop class="k5i52n_gm"/><stop offset="1" class="vsqgrkwbb"/></radialGradient><radialGradient id="is19MEd" cx="0" cy="0" r="1" gradientTransform="matrix(.07693 -2.02477 3.711 .141 26.096 18.118)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="lcqew7b7f"/><stop offset="1" class="e6z7sjb6l"/></radialGradient><radialGradient id="iFgje2e" cx="0" cy="0" r="1" gradientTransform="matrix(-1.57872 2.60975 -2.15908 -1.3061 27.845 24.02)" gradientUnits="userSpaceOnUse"><stop class="tqgfgwd_y"/><stop offset="1" class="de0rqgbhp"/></radialGradient><radialGradient id="iGSGsbb" cx="0" cy="0" r="1" gradientTransform="matrix(2.52448 0 0 .50881 23.335 25.522)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="gzbsswvik"/><stop offset="1" class="q0u2bl4sa"/></radialGradient><radialGradient id="iB9gv3c" cx="0" cy="0" r="1" gradientTransform="matrix(2.83004 0 0 .5704 23.131 26.97)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="gzbsswvik"/><stop offset="1" class="q0u2bl4sa"/></radialGradient><radialGradient id="iiPRvHe" cx="0" cy="0" r="1" gradientTransform="matrix(2.96797 0 0 .3582 23.028 28.354)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="gzbsswvik"/><stop offset="1" class="q0u2bl4sa"/></radialGradient><radialGradient id="ijgToNe" cx="0" cy="0" r="1" gradientTransform="matrix(2.01636 0 0 3.52864 7.437 12.68)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="iVHCn3X" cx="0" cy="0" r="1" gradientTransform="matrix(.9499 -.69166 .78944 1.08418 20.714 12.376)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="i6E2hWu" cx="0" cy="0" r="1" gradientTransform="matrix(.94364 -1.73561 1.01586 .55231 20.239 13.624)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="iW6DVMT" cx="0" cy="0" r="1" gradientTransform="matrix(.29792 .2949 -.38017 .38407 20.286 12.68)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="iEy3iIb" cx="0" cy="0" r="1" gradientTransform="rotate(134.335 6.74 11.439)scale(7.58659 5.71572)" gradientUnits="userSpaceOnUse"><stop class="zxdg24bmw"/><stop offset=".972" class="t9adju1bf"/></radialGradient><radialGradient id="iaNodxc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.46844 10.6178 0 14.844 20.375)" gradientUnits="userSpaceOnUse"><stop class="nekaomcqh"/><stop offset="1" class="hwp3gmb1f"/></radialGradient><radialGradient id="ibJFaCR" cx="0" cy="0" r="1" gradientTransform="rotate(162.019 6.665 6.6)scale(7.48299 3.32391)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="dlnox371w"/><stop offset="1" class="eh71jcbnk"/></radialGradient><radialGradient id="iBqnAde" cx="0" cy="0" r="1" gradientTransform="rotate(-102.752 13.84 1.032)scale(2.39014 1.38152)" gradientUnits="userSpaceOnUse"><stop offset=".264" class="a_w30i6-q"/><stop offset="1" class="gr1604b2k"/></radialGradient><radialGradient id="iDZcqGr" cx="0" cy="0" r="1" gradientTransform="rotate(-87.754 16.412 1.056)scale(.72129 2.16389)" gradientUnits="userSpaceOnUse"><stop class="zjmwko4fr"/><stop offset="1" class="md9bsbc9k"/></radialGradient><radialGradient id="iijYZwb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03773 -1.22791 0 17.314 12.479)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="if1ve-bkd"/><stop offset="1" class="l94tcm8fr"/></radialGradient><radialGradient id="icmYJFc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.811 11.512 1.92)scale(.43456 .59827)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iMzVYMb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03779 -1.22797 0 12.301 12.479)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="if1ve-bkd"/><stop offset="1" class="l94tcm8fr"/></radialGradient><radialGradient id="iFbcshM" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.064 .28)scale(.56764 .68234)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iTVvQNd" cx="0" cy="0" r="1" gradientTransform="matrix(-.77386 .0032 -.00524 -1.2664 8.844 11.57)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="uyla-fbjv"/><stop offset=".687" class="b7clo7b1x"/></radialGradient><radialGradient id="i8gh6Fe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.90342 3.34379 -2.24881 -4.64278 20.958 3.094)" gradientUnits="userSpaceOnUse"><stop class="ld92_g1my"/><stop offset="1" class="dvhbibcqh"/></radialGradient><radialGradient id="iBfj5Pd" cx="0" cy="0" r="1" gradientTransform="matrix(3.25 -.4375 1.025 7.6143 8.492 6.125)" gradientUnits="userSpaceOnUse"><stop class="t0ozsbnai"/><stop offset="1" class="iqoe-4pvq"/></radialGradient><radialGradient id="ieAjMmb" cx="0" cy="0" r="1" gradientTransform="matrix(.71875 1.89873 -3.57306 1.35256 11.648 2.078)" gradientUnits="userSpaceOnUse"><stop class="uvo3wxbsr"/><stop offset="1" class="vjaj-kz7h"/></radialGradient><radialGradient id="iTUCPGc" cx="0" cy="0" r="1" gradientTransform="rotate(179.635 9.633 3.61)scale(4.90635 4.18652)" gradientUnits="userSpaceOnUse"><stop class="c77y5fbir"/><stop offset="1" class="a4oc_-5ds"/></radialGradient><linearGradient id="iOhOn5b" x1="6.988" x2="7.195" y1="29.407" y2="29.407" gradientUnits="userSpaceOnUse"><stop offset=".151" class="x84cwhbna"/><stop offset="1" class="fk1gregde"/></linearGradient><linearGradient id="iAomAlC" x1="16.932" x2="14.847" y1="28.546" y2="28.12" gradientUnits="userSpaceOnUse"><stop offset=".045" class="o8gobxb3n"/><stop offset="1" class="q-14d3boa"/></linearGradient><linearGradient id="im9eHqM" x1="13.726" x2="14.226" y1="26.766" y2="26.813" gradientUnits="userSpaceOnUse"><stop class="i78i3vbiy"/><stop offset="1" class="la8vvmbhh"/></linearGradient><linearGradient id="iTudamq" x1="16.414" x2="15.153" y1="29.07" y2="29.123" gradientUnits="userSpaceOnUse"><stop offset=".065" class="bt46k-bry"/><stop offset="1" class="d-k16gi6m"/></linearGradient><linearGradient id="itSm4AK" x1="11.675" x2="12.612" y1="21.65" y2="21.469" gradientUnits="userSpaceOnUse"><stop class="bcp6zybsw"/><stop offset="1" class="kte-0sm3k"/></linearGradient><linearGradient id="iC6TSsc" x1="18.074" x2="17.137" y1="21.65" y2="21.469" gradientUnits="userSpaceOnUse"><stop class="bcp6zybsw"/><stop offset="1" class="kte-0sm3k"/></linearGradient><linearGradient id="i9VYgXa" x1="12.219" x2="9.392" y1="26.169" y2="26.806" gradientUnits="userSpaceOnUse"><stop class="rcslxcb9f"/><stop offset="1" class="arpepeb0z"/></linearGradient><linearGradient id="ixKBBIe" x1="9.392" x2="11.085" y1="16.976" y2="22.375" gradientUnits="userSpaceOnUse"><stop class="oh_d1sh7z"/><stop offset="1" class="x2herp8_d"/></linearGradient><linearGradient id="imEendb" x1="12.268" x2="12.268" y1="29.922" y2="24.699" gradientUnits="userSpaceOnUse"><stop class="nw6o4wclj"/><stop offset="1" class="q8ppcjbus"/></linearGradient><linearGradient id="iSfw5wd" x1="18.023" x2="21.304" y1="29.125" y2="16.976" gradientUnits="userSpaceOnUse"><stop offset=".452" class="t-s_cxb3y"/><stop offset="1" class="zpb-61ddc"/></linearGradient><linearGradient id="iiIvpQb" x1="17" x2="17.152" y1="26.539" y2="26.57" gradientUnits="userSpaceOnUse"><stop class="njrd_tayg"/><stop offset="1" class="d1xnqxb5m"/></linearGradient><linearGradient id="iz2Begd" x1="26.981" x2="24.992" y1="21.782" y2="21.782" gradientUnits="userSpaceOnUse"><stop class="x26s0_r_n"/><stop offset="1" class="x__1z6aoh"/></linearGradient><linearGradient id="iWBccNc" x1="26.336" x2="26.336" y1="25.469" y2="22.563" gradientUnits="userSpaceOnUse"><stop class="zuvzebcmo"/><stop offset="1" class="fjaxvnbiy"/></linearGradient><linearGradient id="iIrRcKb" x1="28.179" x2="23.367" y1="14.344" y2="19.782" gradientUnits="userSpaceOnUse"><stop class="tnc_xbdtt"/><stop offset="1" class="n3pyssb7u"/></linearGradient><linearGradient id="isY3IOc" x1="28.258" x2="23.131" y1="27.807" y2="27.807" gradientUnits="userSpaceOnUse"><stop class="ut7pv-xgw"/><stop offset=".755" class="xwbtobibq"/></linearGradient><linearGradient id="iCfmprE" x1="25.534" x2="23.529" y1="25.532" y2="25.532" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="iUqjLqd" x1="25.448" x2="23.444" y1="26.956" y2="26.956" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="iCTLnoq" x1="25.534" x2="23.529" y1="28.379" y2="28.379" gradientUnits="userSpaceOnUse"><stop class="cu_6wobdp"/><stop offset="1" class="glaz8zb9m"/></linearGradient><linearGradient id="iydLx9b" x1="9.356" x2="8.619" y1="13.001" y2="13.001" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="iYhzLfc" x1="21.535" x2="20.594" y1="11.426" y2="14.34" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="inb7ZSc" x1="20.606" x2="19.595" y1="16.129" y2="16.057" gradientUnits="userSpaceOnUse"><stop class="qigbnsbso"/><stop offset="1" class="yzu1b2dtm"/></linearGradient><linearGradient id="ifmGGtd" x1="15.034" x2="15.034" y1="15.378" y2="14.5" gradientUnits="userSpaceOnUse"><stop class="uh9ed9waw"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="ipvJ5Ne" x1="14.672" x2="14.938" y1="12.289" y2="13.58" gradientUnits="userSpaceOnUse"><stop class="of2d2ab_y"/><stop offset="1" class="e3kxqcbnn"/></linearGradient><linearGradient id="iE5JQae" x1="18.208" x2="17.848" y1="12.158" y2="12.38" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iN3jgZV" x1="13.156" x2="12.795" y1="12.158" y2="12.38" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iJcqtje" x1="21.212" x2="20.677" y1="11.586" y2="11.61" gradientUnits="userSpaceOnUse"><stop class="cj3lfzb5j"/><stop offset="1" class="os4nk8eel"/></linearGradient><linearGradient id="iodu1md" x1="23.304" x2="6.367" y1="9.438" y2="9.753" gradientUnits="userSpaceOnUse"><stop class="damj_nbgh"/><stop offset=".519" class="bpzzcwljp"/><stop offset=".98" class="fpxhxfble"/></linearGradient><linearGradient id="iAJlZRd" x1="8.554" x2="9.992" y1="6.877" y2="7.063" gradientUnits="userSpaceOnUse"><stop class="s_d1fy10v"/><stop offset="1" class="gn4fmf85p"/></linearGradient><linearGradient id="iLKj4pc" x1="15.461" x2="15.461" y1="7.93" y2="7.727" gradientUnits="userSpaceOnUse"><stop offset=".038" class="rc26n1b9i"/><stop offset="1" class="m5pcs-93k"/></linearGradient><linearGradient id="iAYhuWd" x1="15.507" x2="15.507" y1="5.848" y2="5.985" gradientUnits="userSpaceOnUse"><stop offset=".038" class="rc26n1b9i"/><stop offset="1" class="m5pcs-93k"/></linearGradient><filter id="iCBBHGb" width="7.346" height="5.139" x="11.201" y="19.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2749" stdDeviation=".25"/></filter><filter id="i2ghKzd" width="3.106" height="2.966" x="13.406" y="21.465" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.133333 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2749"/></filter><filter id="iTAcR2c" width="8.299" height="13.046" x="5.292" y="16.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.396078 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2749"/></filter><filter id="iUjDYWR" width="8.299" height="13.046" x="16.153" y="16.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2749"/></filter><filter id="iV3Af7d" width="2.761" height="3.973" x="26.147" y="21.829" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.5"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.560784 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2749"/></filter><filter id="iwaEWBV" width="6.656" height="6.656" x="22.367" y="13.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2749" stdDeviation=".125"/></filter><filter id="iSUvkub" width="7.206" height="7.206" x="22.067" y="13.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.27451 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2749"/></filter><filter id="iC32qyd" width="5.427" height="6.052" x="23.131" y="23.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.513726 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2749"/></filter><filter id="iCfeETV" width="2.212" height=".25" x="23.574" y="25.407" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2749" stdDeviation=".05"/></filter><filter id="in3k83c" width="2.212" height=".25" x="23.489" y="26.831" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2749" stdDeviation=".05"/></filter><filter id="i9UlTPN" width="2.212" height=".25" x="23.574" y="28.254" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2749" stdDeviation=".05"/></filter><filter id="iIZ6sRh" width="3.286" height="3.286" x="7.712" y="11.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2749" stdDeviation=".25"/></filter><filter id="iDKEEWd" width="4.086" height="4.086" x="18.368" y="10.512" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2749"/></filter><filter id="iydUDBc" width="3.286" height="3.286" x="18.643" y="11.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2749" stdDeviation=".25"/></filter><filter id="iboybRd" width="12.669" height="13.82" x="8.884" y="6.218" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.619608 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2749"/></filter><filter id="iGavTud" width="3.522" height="4.581" x="12.775" y="11.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2749" stdDeviation=".375"/></filter><filter id="iH3f4Qc" width="2.656" height="3.581" x="13.483" y="12.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.521569 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2749"/><feGaussianBlur result="effect2_foregroundBlur_4002_2749" stdDeviation=".125"/></filter><filter id="iLPL4Wb" width="2.656" height="3.581" x="13.483" y="11.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2749" stdDeviation=".125"/></filter><filter id="iabhXzG" width="4.097" height="1.632" x="12.762" y="15.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2749" stdDeviation=".05"/></filter><filter id="i5cV7ke" width=".874" height=".77" x="16.486" y="11.605" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2749" stdDeviation=".05"/></filter><filter id="iG5Qute" width=".964" height=".99" x="17.466" y="11.707" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2749" stdDeviation=".1"/></filter><filter id="isKlkhe" width="1.074" height="1.135" x="12.362" y="11.633" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2749" stdDeviation=".1"/></filter><filter id="iceMD8L" width="1.019" height=".78" x="11.48" y="11.595" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2749" stdDeviation=".05"/></filter><filter id="iDZdQVN" width="12.369" height="3.947" x="8.798" y="2.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2749"/></filter><filter id="ipkDtBd" width="19.912" height="4.003" x="4.916" y="7.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.447059 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2749"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.372549 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2749" result="effect2_innerShadow_4002_2749"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-detective" /></template>
<style>
.a_w30i6-q {
  stop-color: var(--svg-color--ffb931, #FFB931);
}

.a4oc_-5ds {
  stop-color: var(--svg-color--372153, #372153);
}

.a6yy9-nlq {
  stop-color: var(--svg-color--46446d, #46446D);
  stop-opacity: 0;
}

.altutfb8x {
  stop-color: var(--svg-color--ab9ca0, #AB9CA0);
}

.arpepeb0z {
  stop-color: var(--svg-color--665c8a, #665C8A);
}

.asvjbc-zd {
  stop-color: var(--svg-color--b4366c, #B4366C);
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.b03y_pbel {
  stop-color: var(--svg-color--d17c26, #D17C26);
}

.b7clo7b1x {
  stop-color: var(--svg-color--ce8442, #CE8442);
}

.bc2ld5biv {
  stop-color: var(--svg-color--46446d, #46446D);
}

.bcp6zybsw {
  stop-color: var(--svg-color--7c707d, #7C707D);
}

.bpzzcwljp {
  stop-color: var(--svg-color--5b537a, #5B537A);
}

.bqtb9rbsu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.7 25.532h1.96");
}

.bslse1b3i {
  stop-color: var(--svg-color--0d0e30, #0D0E30);
}

.bt46k-bry {
  stop-color: var(--svg-color--810937, #810937);
}

.by194g1ei {
  d: path("M22.727 29.922h4.296a12.16 12.16 0 0 0-4.296-8.538z");
}

.c_gtmdbzk {
  stop-color: var(--svg-color--5e5775, #5E5775);
}

.c77y5fbir {
  stop-color: var(--svg-color--574069, #574069);
}

.cenqke63g {
  cx: 20.286px;
  cy: 12.681px;
  r: 1.143px;
}

.cj2gegbdf {
  stop-color: var(--svg-color--4f4376, #4F4376);
}

.cj3lfzb5j {
  stop-color: var(--svg-color--eea130, #EEA130);
}

.cjc9cqblk {
  stop-color: var(--svg-color--ceadc3, #CEADC3);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cu_6wobdp {
  stop-color: var(--svg-color--c88714, #C88714);
  stop-opacity: 0;
}

.cw9lwsb0z {
  stop-color: var(--svg-color--4f4376, #4F4376);
  stop-opacity: 0;
}

.d-k16gi6m {
  stop-color: var(--svg-color--b6376a, #B6376A);
  stop-opacity: 0;
}

.d1xnqxb5m {
  stop-color: var(--svg-color--573a60, #573A60);
  stop-opacity: 0;
}

.d6h0d6b8p {
  d: path("M12.3 11.547a1.025 1.025 0 0 0-.989 1.296h1.98a1 1 0 0 0 .038-.27a1.03 1.03 0 0 0-1.03-1.026");
}

.damj_nbgh {
  stop-color: var(--svg-color--7577a1, #7577A1);
}

.de0rqgbhp {
  stop-color: var(--svg-color--ffe136, #FFE136);
  stop-opacity: 0;
}

.dfqbekbrj {
  cx: 11.99px;
  cy: 11.985px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.448px;
  ry: 0.227px;
}

.dlnox371w {
  stop-color: var(--svg-color--db7d28, #DB7D28);
}

.dnfp-euku {
  d: path("M8.126 7.748a.1.1 0 0 0 .095.131h13.287a.1.1 0 0 0 .094-.132l-.192-.56l-.429-1.244a.1.1 0 0 0-.094-.068H8.829a.1.1 0 0 0-.095.068c-.19.554-.38 1.12-.531 1.575z");
}

.dv70acbut {
  stop-color: var(--svg-color--534971, #534971);
  stop-opacity: 0;
}

.dvhbibcqh {
  stop-color: var(--svg-color--625783, #625783);
}

.e3kxqcbnn {
  stop-color: var(--svg-color--e08528, #E08528);
  stop-opacity: 0;
}

.e6z7sjb6l {
  stop-color: var(--svg-color--dbf3ff, #DBF3FF);
}

.e9sv_2buc {
  stop-color: var(--svg-color--dbc8d7, #DBC8D7);
}

.efj5ccoqw {
  stop-color: var(--svg-color--ad792e, #AD792E);
}

.eh71jcbnk {
  stop-color: var(--svg-color--db7d28, #DB7D28);
  stop-opacity: 0;
}

.em148031i {
  fill: var(--svg-color--beb2c3, #BEB2C3);
  d: path("m13.445 29.922l-2.328-10.956l3.422-1.2l4.437 1.294l-2.281 10.862z");
}

.ep1m_ub9u {
  cx: 9.356px;
  cy: 12.681px;
  r: 1.143px;
}

.erhkeibcy {
  width: 2.572px;
  height: 5.438px;
  x: 24.409px;
  y: 20.227px;
  rx: 1.286px;
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.f5u9q1n2l {
  d: path("m18.996 16.976l-2.743 12.946h1.797c1.401-2.334 4.288-7.147 4.625-7.735c.422-.734.219-.906.14-1.03c-.077-.126-.374-.36-.671-.47c-.238-.087-.328-.203-.344-.25c-.057-.067-.069-.3.344-.687c.412-.388 1.307-1.068 1.703-1.36c.234-.187.652-.609.602-.984s-.651-.435-.766-.43z");
}

.f87czphzs {
  stop-color: var(--svg-color--5b4361, #5B4361);
}

.fchl8077b {
  stop-color: var(--svg-color--4e4270, #4E4270);
}

.fisd__bqs {
  stop-color: var(--svg-color--ce3657, #CE3657);
}

.fjaxvnbiy {
  stop-color: var(--svg-color--4c3156, #4C3156);
  stop-opacity: 0;
}

.fk1gregde {
  stop-color: var(--svg-color--57497f, #57497F);
  stop-opacity: 0;
}

.foejprbbc {
  stop-color: var(--svg-color--767290, #767290);
}

.fpxhxfble {
  stop-color: var(--svg-color--5c4b6c, #5C4B6C);
}

.ft5dv1b6b {
  fill: none;
}

.g1ovp4bwp {
  fill-rule: evenodd;
  d: path("M25.695 20.672a3.578 3.578 0 1 0 0-7.156a3.578 3.578 0 0 0 0 7.156m0-.593a2.984 2.984 0 1 0 0-5.969a2.984 2.984 0 0 0 0 5.969");
}

.g7gmqhncd {
  d: path("M7.023 29.922H2.727a12.16 12.16 0 0 1 4.296-8.538z");
}

.gemgotgww {
  d: path("m14.098 24.35l-.692-1.334l1.453-1.351l1.453 1.351l-.662 1.331a.15.15 0 0 1-.134.083h-1.285a.15.15 0 0 1-.133-.08");
}

.gi2uz_g9v {
  stop-color: var(--svg-color--514c59, #514C59);
}

.glaz8zb9m {
  stop-color: var(--svg-color--c07200, #C07200);
}

.gn4fmf85p {
  stop-color: var(--svg-color--3e3058, #3E3058);
  stop-opacity: 0;
}

.gr1604b2k {
  stop-color: var(--svg-color--ffb931, #FFB931);
  stop-opacity: 0;
}

.gtmq6ja1j {
  stop-color: var(--svg-color--ffd235, #FFD235);
}

.gzbsswvik {
  stop-color: var(--svg-color--f9a42e, #F9A42E);
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.hwp3gmb1f {
  stop-color: var(--svg-color--e98d38, #E98D38);
  stop-opacity: 0;
}

.hzw4atb3f {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.061 11.236c-.75 0-1.384.517-1.556 1.216c-.052.2.102.392.307.392h2.563c.164 0 .294-.15.261-.313a1.61 1.61 0 0 0-1.575-1.295");
}

.i78i3vbiy {
  stop-color: var(--svg-color--ad254b, #AD254B);
}

.i7g4iz6bw {
  stop-color: var(--svg-color--6f6a93, #6F6A93);
  stop-opacity: 0;
}

.id09adcid {
  stop-color: var(--svg-color--ffe047, #FFE047);
}

.if1ve-bkd {
  stop-color: var(--svg-color--7a4242, #7A4242);
}

.ig92uxq3u {
  stop-color: var(--svg-color--50d5fa, #50D5FA);
}

.ijrk-tbbt {
  d: path("m8.07 10.762l.198.814c.058.35.357.6.701.624c-.014-.226-.046-.631-.058-.978l-.017-.46z");
}

.iqoe-4pvq {
  stop-color: var(--svg-color--766c87, #766C87);
  stop-opacity: 0;
}

.ivj3pk5jv {
  d: path("M8.803 5.743a.1.1 0 0 0 .095.132h11.92a.1.1 0 0 0 .094-.133a87 87 0 0 0-.639-1.789c-.469-1.25-1.637-1.875-2.297-1.875c-.735-.016-1.259.318-1.65.567l-.194.12c-.578.344-.808.4-1.277.4c-.371 0-.762-.15-1.184-.368q-.11-.058-.247-.142c-.436-.26-1.078-.642-1.905-.526c-.956.134-1.66.93-2.097 1.945a29 29 0 0 0-.619 1.669");
}

.j_dulcbnt {
  fill: var(--svg-color--655d95, #655D95);
  d: path("M2.727 29.922H27.01c-.399-6.368-5.682-11.409-12.142-11.409S3.125 23.554 2.727 29.923");
}

.j-ut2xl5o {
  d: path("M12.625 19.547c.026.292.262.988.999 1.438c.736.45 1.14.63 1.25.664c.11-.034.515-.214 1.251-.664c.737-.45.973-1.146 1-1.438z");
}

.j05e95eeg {
  stop-color: var(--svg-color--6f6a93, #6F6A93);
}

.j11nupb8y {
  stop-color: var(--svg-color--696284, #696284);
}

.jgjt2xbnj {
  d: path("M17.317 11.547a1.025 1.025 0 0 1 .988 1.296h-1.98a1.03 1.03 0 0 1 .992-1.295");
}

.jpbxw370c {
  d: path("M6.386 7.879c-.26-.016-.991.034-1.316.36c-.358.357-.055 1.073.508 1.652c.539.554 2.335 1.738 5.18 1.738h8.167c2.873 0 4.689-1.184 5.234-1.738c.568-.58.874-1.295.513-1.653c-.328-.325-1.067-.375-1.33-.359z");
}

.k_2y5fb4u {
  stop-color: var(--svg-color--ad792e, #AD792E);
  stop-opacity: 0;
}

.k1zgefb2d {
  stop-color: var(--svg-color--605a74, #605A74);
}

.k5i52n_gm {
  stop-color: var(--svg-color--2683c8, #2683C8);
}

.k7e504bil {
  cx: 25.695px;
  cy: 17.094px;
  r: 3.078px;
  fill: var(--svg-color--3e2657, #3E2657);
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.k9h8bsbwk {
  stop-color: var(--svg-color--403357, #403357);
}

.kdvr4u58b {
  d: path("m14.372 12.364l-.61 1.953a.62.62 0 0 0 .597.803h.904a.62.62 0 0 0 .598-.803l-.61-1.953c-.132-.433-.742-.433-.88 0");
}

.kdzxr8bcy {
  d: path("m20.76 10.762l-.02.389c-.018.345-.04.777-.063 1.1c.358-.01.597-.252.657-.613l.23-.876z");
}

.kpssiabxl {
  stop-color: var(--svg-color--5c5178, #5C5178);
  stop-opacity: 0;
}

.kqcubybll {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.81 16.4c-.582 0-1.13-.137-1.59-.377c-.158-.08-.327.097-.228.24a2.17 2.17 0 0 0 1.819.972c.764 0 1.434-.389 1.819-.972c.099-.149-.07-.32-.228-.24a3.4 3.4 0 0 1-1.591.377Z");
}

.kte-0sm3k {
  stop-color: var(--svg-color--cfbdc9, #CFBDC9);
  stop-opacity: 0;
}

.kvzrrwynu {
  stop-color: var(--svg-color--6a5e90, #6A5E90);
}

.l_9dr2bhm {
  d: path("M17.242 11.764c.072.098-.08.217-.254.347c-.173.13-.302.22-.375.123c-.073-.098.008-.282.182-.412c.173-.13.373-.156.446-.058");
}

.l94tcm8fr {
  stop-color: var(--svg-color--663531, #663531);
}

.l9k3lrq7u {
  stop-color: var(--svg-color--d1c0d6, #D1C0D6);
}

.la8vvmbhh {
  stop-color: var(--svg-color--ad254b, #AD254B);
  stop-opacity: 0;
}

.lcqew7b7f {
  stop-color: var(--svg-color--dbf3ff, #DBF3FF);
  stop-opacity: 0;
}

.ld92_g1my {
  stop-color: var(--svg-color--7f81b2, #7F81B2);
}

.lg14abbip {
  stop-color: var(--svg-color--605a74, #605A74);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lyxdnwxxe {
  stop-color: var(--svg-color--efa20d, #EFA20D);
  stop-opacity: 0;
}

.m5pcs-93k {
  stop-color: var(--svg-color--2c1840, #2C1840);
  stop-opacity: 0;
}

.md9bsbc9k {
  stop-color: var(--svg-color--ffbe30, #FFBE30);
  stop-opacity: 0;
}

.mh39h7hpm {
  cx: 9.356px;
  cy: 12.68px;
  r: 1.918px;
}

.mibx7d57r {
  fill: var(--svg-color--000, #000);
  d: path("M12.886 12.573a.585.585 0 0 0-.587-.587a.585.585 0 0 0-.522.857h1.04a.6.6 0 0 0 .07-.27");
}

.mp8t_zb5c {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.242 11.764c.072.098-.08.217-.254.347c-.173.13-.302.22-.375.123c-.073-.098.008-.282.182-.412c.173-.13.373-.156.446-.058");
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.mw9gk7bly {
  stop-color: var(--svg-color--3f3050, #3F3050);
}

.mx64gfpes {
  stop-color: var(--svg-color--6a6385, #6A6385);
}

.n0h_63bcp {
  cx: 20.286px;
  cy: 12.68px;
  r: 1.918px;
}

.n3lyoibnh {
  d: path("m10.75 16.976l2.742 12.946h-1.797a1566 1566 0 0 1-4.625-7.735c-.422-.734-.219-.906-.14-1.03c.077-.126.374-.36.671-.47c.238-.087.328-.203.344-.25c.057-.067.069-.3-.344-.687c-.412-.388-1.307-1.068-1.703-1.36c-.234-.187-.652-.609-.602-.984s.652-.435.766-.43z");
}

.n3pyssb7u {
  stop-color: var(--svg-color--452053, #452053);
}

.nekaomcqh {
  stop-color: var(--svg-color--c16e38, #C16E38);
}

.nf2o-hpjm {
  stop-color: var(--svg-color--857da2, #857DA2);
}

.ng-28zxwb {
  d: path("M2.727 29.922H27.01c-.399-6.368-5.682-11.409-12.142-11.409S3.125 23.554 2.727 29.923");
}

.nig76no1i {
  stop-color: var(--svg-color--4e4270, #4E4270);
  stop-opacity: 0;
}

.njrd_tayg {
  stop-color: var(--svg-color--573a60, #573A60);
}

.nw6o4wclj {
  stop-color: var(--svg-color--624c7f, #624C7F);
}

.nzffxlbem {
  stop-color: var(--svg-color--4f456a, #4F456A);
}

.o58_qgbus {
  stop-color: var(--svg-color--dcc8d0, #DCC8D0);
}

.o8gobxb3n {
  stop-color: var(--svg-color--897b8e, #897B8E);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.of2d2ab_y {
  stop-color: var(--svg-color--e08528, #E08528);
}

.oh_d1sh7z {
  stop-color: var(--svg-color--5e5a78, #5E5A78);
}

.ol5y5gj7m {
  stop-color: var(--svg-color--69638b, #69638B);
  stop-opacity: 0;
}

.oor1kvo5l {
  d: path("M18.23 12.438a.97.97 0 0 0-.266-.531l-.298.327l.134.262z");
}

.op_u9g8uj {
  stop-color: var(--svg-color--c03660, #C03660);
}

.os4nk8eel {
  stop-color: var(--svg-color--d7771d, #D7771D);
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.pb1ehqpec {
  stop-color: var(--svg-color--4f456a, #4F456A);
  stop-opacity: 0;
}

.pdrrorwco {
  fill: var(--svg-color--f29e21, #F29E21);
  d: path("m14.372 12.622l-.61 1.953a.62.62 0 0 0 .597.803h.904a.62.62 0 0 0 .598-.803l-.61-1.953c-.132-.433-.742-.433-.88 0");
}

.phm_r04pf {
  stop-color: var(--svg-color--db912b, #DB912B);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pwa97nbfq {
  stop-color: var(--svg-color--5b4361, #5B4361);
  stop-opacity: 0;
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.q-14d3boa {
  stop-color: var(--svg-color--8c7c93, #8C7C93);
  stop-opacity: 0;
}

.q0u2bl4sa {
  stop-color: var(--svg-color--f9a42e, #F9A42E);
  stop-opacity: 0;
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.q8ppcjbus {
  stop-color: var(--svg-color--624c7f, #624C7F);
  stop-opacity: 0;
}

.qasiqcczj {
  stop-color: var(--svg-color--837a8e, #837A8E);
  stop-opacity: 0;
}

.qbj5mmbvn {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.555 11.236c.75 0 1.384.517 1.556 1.216a.315.315 0 0 1-.308.392h-2.562a.264.264 0 0 1-.261-.313a1.606 1.606 0 0 1 1.575-1.295");
}

.qigbnsbso {
  stop-color: var(--svg-color--fcd03d, #FCD03D);
}

.quksm7bdn {
  d: path("M23.132 24.819c0-.438.355-.799.793-.799h3.023c.724 0 1.31.587 1.31 1.31v3.5c0 .603-.488 1.092-1.091 1.092h-3.242a.798.798 0 0 1-.349-1.516a.802.802 0 0 1 0-1.435a.802.802 0 0 1 0-1.435a.8.8 0 0 1-.445-.717");
}

.rc26n1b9i {
  stop-color: var(--svg-color--2c1840, #2C1840);
}

.rcslxcb9f {
  stop-color: var(--svg-color--675685, #675685);
}

.rhxl5gb9p {
  d: path("M27.203 22.329c.58 0 1.055.475 1.055 1.055v2.418h-2.111v-2.418c.01-.58.475-1.055 1.056-1.055");
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rqg1a3anv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.614 26.956h1.962");
}

.rrgrst12i {
  fill: var(--svg-color--000, #000);
  d: path("M16.73 12.573c0-.326.26-.587.587-.587a.585.585 0 0 1 .522.857h-1.04a.53.53 0 0 1-.07-.27");
}

.rxpl4qnie {
  stop-color: var(--svg-color--4e4854, #4E4854);
  stop-opacity: 0;
}

.s_d1fy10v {
  stop-color: var(--svg-color--4c4364, #4C4364);
}

.s0-op-jbm {
  d: path("m17.77 22.747l.814-3.778h-1.852l-1.867 2.485v.437l1.96 1.781c.097.084.327.214.477.07c.15-.143.35-.484.467-.995");
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.s9abuujkb {
  cx: 20.286px;
  cy: 12.681px;
  r: 1.143px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.sx-22hbhr {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M14.81 16.4c-.582 0-1.13-.137-1.59-.377c-.158-.08-.327.097-.228.24a2.17 2.17 0 0 0 1.819.972c.764 0 1.434-.389 1.819-.972c.099-.149-.07-.32-.228-.24a3.4 3.4 0 0 1-1.591.377");
}

.sxgpvtb4k {
  d: path("m14.372 12.622l-.61 1.953a.62.62 0 0 0 .597.803h.904a.62.62 0 0 0 .598-.803l-.61-1.953c-.132-.433-.742-.433-.88 0");
}

.t-s_cxb3y {
  stop-color: var(--svg-color--5b4373, #5B4373);
}

.t0ozsbnai {
  stop-color: var(--svg-color--766c87, #766C87);
}

.t11-a9gub {
  stop-color: var(--svg-color--0d0e30, #0D0E30);
  stop-opacity: 0;
}

.t9adju1bf {
  stop-color: var(--svg-color--f19b29, #F19B29);
}

.thvbr9biq {
  stop-color: var(--svg-color--27a8e3, #27A8E3);
}

.tjiypub2l {
  width: 1.769px;
  height: 2.205px;
  x: 25.512px;
  y: 15.977px;
  rx: 0.885px;
}

.tnc_xbdtt {
  stop-color: var(--svg-color--202d61, #202D61);
}

.tnef9wrdf {
  d: path("m13.445 29.922l-2.328-10.956l3.422-1.2l4.437 1.294l-2.281 10.862z");
}

.tqgfgwd_y {
  stop-color: var(--svg-color--ffe136, #FFE136);
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.uh9ed9waw {
  stop-color: var(--svg-color--ed8e27, #ED8E27);
}

.ut7pv-xgw {
  stop-color: var(--svg-color--ffe132, #FFE132);
}

.uvo3wxbsr {
  stop-color: var(--svg-color--5f577e, #5F577E);
}

.uyla-fbjv {
  stop-color: var(--svg-color--d96523, #D96523);
}

.v9c6zoseo {
  d: path("M13.236 12.452c0-.33-.27-.552-.343-.618l-.33.32l.203.415z");
}

.vd-u4acdq {
  cx: 25.695px;
  cy: 17.094px;
  r: 2.984px;
}

.vjaj-kz7h {
  stop-color: var(--svg-color--5f577e, #5F577E);
  stop-opacity: 0;
}

.vsqgrkwbb {
  stop-color: var(--svg-color--2bace5, #2BACE5);
  stop-opacity: 0;
}

.wibdzhbon {
  d: path("m11.972 22.727l-.806-3.758h1.851l1.867 2.488v.434l-1.96 1.781c-.097.084-.327.214-.477.07c-.15-.143-.357-.503-.475-1.015");
}

.wss6y3b2p {
  stop-color: var(--svg-color--b41945, #B41945);
}

.x__1z6aoh {
  stop-color: var(--svg-color--39304b, #39304B);
}

.x26s0_r_n {
  stop-color: var(--svg-color--443665, #443665);
}

.x2herp8_d {
  stop-color: var(--svg-color--5e5a78, #5E5A78);
  stop-opacity: 0;
}

.x84cwhbna {
  stop-color: var(--svg-color--57497f, #57497F);
}

.xcc0mcchc {
  stop-color: var(--svg-color--efa20d, #EFA20D);
}

.xd4qu1b2a {
  cx: 11.99px;
  cy: 11.985px;
  rx: 0.448px;
  ry: 0.227px;
}

.xqc8z1bhj {
  stop-color: var(--svg-color--6a6385, #6A6385);
  stop-opacity: 0;
}

.xtl5dn5fo {
  stop-color: var(--svg-color--403357, #403357);
  stop-opacity: 0;
}

.xwbtobibq {
  stop-color: var(--svg-color--ffae37, #FFAE37);
}

.yhqewxb9n {
  d: path("M8.951 11.977c-.03-.36-.067-1.389-.067-1.653c0-.306.124-.674.37-.858l.185-.184c.308-.245.432-.612.432-.98v-.98c0-.307.184-.552.493-.613c.74-.184 2.28-.49 4.499-.49s3.76.306 4.499.49c.246.06.493.306.493.612v.98c0 .369.185.736.431.981c.577.405.541.627.493 1.103c-.014.148-.061 1.373-.102 1.655l-.305 4.548c-.185 2.033-1.783 3.45-3.69 3.45h-3.688c-1.967 0-3.504-1.417-3.689-3.45z");
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.ylkb8lnyx {
  stop-color: var(--svg-color--988b89, #988B89);
}

.yu54nqayv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M23.7 28.38h1.96");
}

.yyxxh9qfh {
  fill: var(--svg-color--f7a936, #F7A936);
  d: path("m17.77 22.747l.814-3.778h-1.852l-1.867 2.485v.437l1.96 1.781c.097.084.327.214.477.07c.15-.143.35-.484.467-.995");
}

.yzu1b2dtm {
  stop-color: var(--svg-color--fcd03d, #FCD03D);
  stop-opacity: 0;
}

.z_k8o-57c {
  stop-color: var(--svg-color--4e4854, #4E4854);
}

.z_rbfc5vy {
  stop-color: var(--svg-color--ceadc3, #CEADC3);
}

.zagiflbwl {
  fill: var(--svg-color--927d95, #927D95);
  d: path("m11.701 19.668l.69 3.215c.1.437.278.745.407.868s.325.011.407-.06l1.67-1.516l1.669 1.516c.082.072.28.183.408.06s.299-.414.4-.852l.696-3.232h-1.584l-1.59 2.116l-1.588-2.116z");
}

.zjmwko4fr {
  stop-color: var(--svg-color--ffd069, #FFD069);
}

.zlum0zc8n {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m14.495 12.81l-.943 1.952c-.117.402.164.804.56.804h.848c.397 0 .678-.408.56-.804l-.572-1.953c-.123-.432-.325-.432-.453 0");
}

.zpb-61ddc {
  stop-color: var(--svg-color--645d7e, #645D7E);
}

.zqbz6fbvb {
  stop-color: var(--svg-color--988b89, #988B89);
  stop-opacity: 0;
}

.zswbabceh {
  d: path("m13.289 29.922l.854-5.407a.1.1 0 0 1 .098-.085h1.247a.1.1 0 0 1 .099.085l.827 5.407z");
}

.zuvzebcmo {
  stop-color: var(--svg-color--4c3156, #4C3156);
}

.zxdg24bmw {
  stop-color: var(--svg-color--ffd22f, #FFD22F);
}

.zy5dj18nw {
  stop-color: var(--svg-color--69638b, #69638B);
}

</style>
