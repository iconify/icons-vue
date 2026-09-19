<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="j_dulcbnt"/><path fill="url(#iAlKUYw)" class="ng-28zxwb"/><path fill="url(#itbtQzd)" class="ng-28zxwb"/><path fill="url(#iOhOn5b)" class="ng-28zxwb"/><path fill="url(#i8ngfnv)" class="ng-28zxwb"/><path fill="url(#ilxDSxc)" class="ng-28zxwb"/><path class="t9v2librs"/><path fill="url(#imSQI2c)" class="cej917bjj"/><path fill="url(#i4d8iJd)" class="cej917bjj"/><path fill="url(#iHdaBGb)" class="cej917bjj"/><g filter="url(#i9w7ipc)"><path class="zagiflbwl"/></g><path fill="url(#i27EXBe)" class="g7gmqhncd"/><path fill="url(#im8Vkvd)" class="g7gmqhncd"/><path fill="url(#i39ExJd)" class="g7gmqhncd"/><path fill="url(#iWKZSod)" class="by194g1ei"/><path fill="url(#idsRMlc)" class="by194g1ei"/><g filter="url(#iWAps0m)"><path fill="url(#i20eBKe)" class="hazfh8b2v"/></g><path fill="url(#iollnke)" class="vi7fu79ul"/><path fill="url(#im9eHqM)" class="vi7fu79ul"/><path fill="url(#i4hNkDe)" class="vi7fu79ul"/><path fill="url(#i8KloTQ)" class="agjep-b6f"/><path fill="url(#iMIg2ZO)" class="agjep-b6f"/><path fill="url(#iEpqGnc)" class="agjep-b6f"/><path fill="url(#iHu3LFd)" class="agjep-b6f"/><path fill="url(#iIipaHv)" class="agjep-b6f"/><path class="y411x-6nn"/><path fill="url(#iY8ko2d)" class="wgl1mtbjd"/><path fill="url(#iGkGbCb)" class="wgl1mtbjd"/><path fill="url(#imdlgvc)" class="wgl1mtbjd"/><path fill="url(#ira2lKd)" class="wgl1mtbjd"/><path fill="url(#iknlR1o)" class="wgl1mtbjd"/><path fill="url(#iEEyH8D)" class="t08-s2dqp"/><path fill="url(#idc0uiu)" class="t08-s2dqp"/><g filter="url(#iRAVP2c)"><path fill="url(#iimzjsu)" class="mop_zlbnl"/><path fill="url(#iwOdF4c)" class="mop_zlbnl"/><path fill="url(#iMAGDRc)" class="mop_zlbnl"/><path fill="url(#i2jMWwb)" class="mop_zlbnl"/><path fill="url(#isZI5dk)" class="mop_zlbnl"/></g><g filter="url(#ipKYOud)"><path fill="url(#i1VflDU)" class="xhfhhvoed"/><path fill="url(#iEAfnnc)" class="xhfhhvoed"/><path fill="url(#isUiL6c)" class="xhfhhvoed"/><path fill="url(#iVjF54c)" class="xhfhhvoed"/></g><path fill="url(#iXGLOGd)" class="qy2xrui7g"/><path fill="url(#iejYbrc)" class="qy2xrui7g"/><rect fill="url(#iGFxt3d)" class="erhkeibcy"/><rect fill="url(#iWBccNc)" class="erhkeibcy"/><rect fill="url(#ih9GmGc)" class="erhkeibcy"/><rect fill="url(#iJ8MAGd)" class="erhkeibcy"/><g filter="url(#i8GENiL)"><circle class="k7e504bil"/></g><circle fill="url(#iU1hsCv)" class="vd-u4acdq"/><circle fill="url(#i5Fhu0c)" class="vd-u4acdq"/><g filter="url(#iuAD9Db)"><path fill="url(#irI5LDd)" clip-rule="evenodd" class="hx_wmlsuf"/></g><rect fill="url(#ihSbEiX)" transform="rotate(-30 25.512 15.977)" class="tjiypub2l"/><g filter="url(#iWbtIOa)"><path fill="url(#iVQ1G1c)" class="quksm7bdn"/><path fill="url(#i4p48ob)" class="quksm7bdn"/><path fill="url(#iZmJ6cd)" class="quksm7bdn"/><path fill="url(#iMY7ere)" class="quksm7bdn"/><path fill="url(#iO1rLsd)" class="quksm7bdn"/></g><g filter="url(#ikh2hDj)"><path stroke="url(#iXiyPSb)" class="fkavrburz"/></g><g filter="url(#iiL1PSb)"><path stroke="url(#iEmyyOd)" class="tnviirb6b"/></g><g filter="url(#iOTj7zb)"><path stroke="url(#i5CGbMd)" class="bc7i0ongh"/></g><g filter="url(#ix2FcGc)"><circle class="lldgadc0f"/></g><g filter="url(#igTrbAb)"><circle fill="url(#iimjsfe)" class="yzf80p4jc"/></g><g filter="url(#i54dNRc)"><circle class="hox-jgbyg"/><circle fill="url(#i4PBkIe)" class="n0h_63bcp"/><circle fill="url(#ifGSGEb)" class="n0h_63bcp"/></g><g filter="url(#iVBeBHb)"><circle fill="url(#iSRywOc)" class="hqp1wu_he"/></g><g filter="url(#iwHnbae)"><path fill="url(#i2ChXpb)" class="hknh16mic"/></g><path fill="url(#ijTvxUb)" class="hknh16mic"/><path fill="url(#iSiVpFk)" class="hknh16mic"/><path fill="url(#iqsBszc)" class="hknh16mic"/><path fill="url(#iXWyppc)" class="hknh16mic"/><path fill="url(#iqVn5ue)" class="hknh16mic"/><path fill="url(#iYEQSYb)" class="hknh16mic"/><g filter="url(#icurQfx)"><path class="ttuoqj4wj"/></g><g filter="url(#iw1QXJq)"><path class="ipzl6eb6x"/><path fill="url(#i3EnENg)" class="sxgpvtb4k"/><path fill="url(#iSQRRGe)" class="sxgpvtb4k"/><path fill="url(#ifDWPbh)" class="sxgpvtb4k"/></g><g filter="url(#iYhbH1S)"><path fill="url(#iGskQPe)" class="vwddzbb7h"/></g><g filter="url(#ii0EEHc)"><path stroke="url(#i26wo4B)" class="kqcubybll"/></g><path class="x2je5736g"/><path class="n3m4ul9nu"/><path fill="url(#iyOGulJ)" class="jgjt2xbnj"/><path class="ctc_opbat"/><g filter="url(#ivxwm2c)"><path class="mp8t_zb5c"/><path fill="url(#icmYJFc)" class="l_9dr2bhm"/></g><g filter="url(#ikMzVmd)"><path fill="url(#iE5JQae)" class="f-gl8-mln"/></g><path class="x8vyagemg"/><path fill="url(#i18vOii)" class="d6h0d6b8p"/><path class="mibx7d57r"/><g filter="url(#iJAp5le)"><path fill="url(#iN3jgZV)" class="v9c6zoseo"/></g><g filter="url(#itKioSm)"><ellipse transform="rotate(-27.914 11.99 11.986)" class="y-v21bc8n"/><ellipse fill="url(#iFbcshM)" transform="rotate(-27.914 11.99 11.986)" class="ljhgv1b3v"/></g><path fill="url(#i6dlANQ)" class="kdzxr8bcy"/><path fill="url(#iRhuwwe)" class="kdzxr8bcy"/><path fill="url(#irLEf8c)" class="ijrk-tbbt"/><g filter="url(#igkA1Sp)"><path fill="url(#i8gh6Fe)" class="ivj3pk5jv"/></g><path fill="url(#iBfj5Pd)" class="ivj3pk5jv"/><path fill="url(#ieAjMmb)" class="ivj3pk5jv"/><g filter="url(#ir8krEd)"><path fill="url(#iodu1md)" class="jpbxw370c"/></g><path fill="url(#iQFwsnd)" class="tq2a2nban"/><path fill="url(#iAJlZRd)" class="tq2a2nban"/><path fill="url(#iLKj4pc)" class="tq2a2nban"/><path fill="url(#invRgge)" class="tq2a2nban"/><defs><radialGradient id="iAlKUYw" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.90625 -2.3125 0 6.773 21.813)" gradientUnits="userSpaceOnUse"><stop class="zy5dj18nw"/><stop offset="1" class="ol5y5gj7m"/></radialGradient><radialGradient id="itbtQzd" cx="0" cy="0" r="1" gradientTransform="rotate(-120.646 14.441 11.476)scale(11.587 1.53635)" gradientUnits="userSpaceOnUse"><stop offset=".336" class="cj2gegbdf"/><stop offset="1" class="cw9lwsb0z"/></radialGradient><radialGradient id="i8ngfnv" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.0625 -2.5 0 22.836 22.157)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="j05e95eeg"/><stop offset="1" class="i7g4iz6bw"/></radialGradient><radialGradient id="ilxDSxc" cx="0" cy="0" r="1" gradientTransform="rotate(20.493 -65.417 66.253)scale(3.30276 13.733)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="fchl8077b"/><stop offset="1" class="nig76no1i"/></radialGradient><radialGradient id="i4d8iJd" cx="0" cy="0" r="1" gradientTransform="rotate(103.743 .523 17.985)scale(2.95973 1.64796)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="z_k8o-57c"/><stop offset="1" class="rxpl4qnie"/></radialGradient><radialGradient id="iHdaBGb" cx="0" cy="0" r="1" gradientTransform="matrix(.8422 3.48214 -1.84594 .44646 11.586 20.884)" gradientUnits="userSpaceOnUse"><stop offset=".624" class="gi2uz_g9v"/><stop offset="1" class="qasiqcczj"/></radialGradient><radialGradient id="i27EXBe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.3594 4.25 0 6.367 29.922)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="kvzrrwynu"/><stop offset="1" class="nf2o-hpjm"/></radialGradient><radialGradient id="im8Vkvd" cx="0" cy="0" r="1" gradientTransform="rotate(117.646 -2.545 12.698)scale(4.44498 4.85494)" gradientUnits="userSpaceOnUse"><stop class="k1zgefb2d"/><stop offset="1" class="lg14abbip"/></radialGradient><radialGradient id="i39ExJd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.7344 2.803 0 7.023 29.922)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="nzffxlbem"/><stop offset="1" class="pb1ehqpec"/></radialGradient><radialGradient id="iWKZSod" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.45316 -3.24716 0 24.875 23.47)" gradientUnits="userSpaceOnUse"><stop class="j11nupb8y"/><stop offset="1" class="c_gtmdbzk"/></radialGradient><radialGradient id="idsRMlc" cx="0" cy="0" r="1" gradientTransform="matrix(1.96327 -.27323 1.61732 11.6211 22.726 29.921)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="k9h8bsbwk"/><stop offset="1" class="xtl5dn5fo"/></radialGradient><radialGradient id="i20eBKe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.2093 -2.72578 0 14.859 22.654)" gradientUnits="userSpaceOnUse"><stop class="fisd__bqs"/><stop offset="1" class="wss6y3b2p"/></radialGradient><radialGradient id="iollnke" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.0625 -.95313 0 14.851 24.781)" gradientUnits="userSpaceOnUse"><stop class="op_u9g8uj"/><stop offset="1" class="asvjbc-zd"/></radialGradient><radialGradient id="i8KloTQ" cx="0" cy="0" r="1" gradientTransform="matrix(-4.18748 2.46878 -3.8188 -6.47736 14.398 20.969)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="e9sv_2buc"/><stop offset="1" class="altutfb8x"/></radialGradient><radialGradient id="iEpqGnc" cx="0" cy="0" r="1" gradientTransform="rotate(104.036 -1.196 14.246)scale(1.84281 2.98915)" gradientUnits="userSpaceOnUse"><stop class="ylkb8lnyx"/><stop offset="1" class="zqbz6fbvb"/></radialGradient><radialGradient id="iHu3LFd" cx="0" cy="0" r="1" gradientTransform="rotate(-132.274 12.135 8.129)scale(.4746 3.14325)" gradientUnits="userSpaceOnUse"><stop class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iIipaHv" cx="0" cy="0" r="1" gradientTransform="matrix(-.64914 .713 -1.62712 -1.4814 14.05 20.861)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iY8ko2d" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 3.20313 -4.95471 3.77041 15.586 20.469)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="o58_qgbus"/><stop offset="1" class="l9k3lrq7u"/></radialGradient><radialGradient id="imdlgvc" cx="0" cy="0" r="1" gradientTransform="rotate(75.964 -3.371 20.582)scale(1.84281 2.98915)" gradientUnits="userSpaceOnUse"><stop class="ylkb8lnyx"/><stop offset="1" class="zqbz6fbvb"/></radialGradient><radialGradient id="ira2lKd" cx="0" cy="0" r="1" gradientTransform="matrix(.31925 -.35118 2.32584 2.11435 15.467 22.576)" gradientUnits="userSpaceOnUse"><stop class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iknlR1o" cx="0" cy="0" r="1" gradientTransform="matrix(.64914 .71299 -1.62712 1.4814 15.7 20.862)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="z_rbfc5vy"/><stop offset="1" class="cjc9cqblk"/></radialGradient><radialGradient id="iEEyH8D" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.77344 -3.32031 0 14.875 19.875)" gradientUnits="userSpaceOnUse"><stop offset=".229" class="he0pvmbuq"/><stop offset="1" class="p1ua1lbjw"/></radialGradient><radialGradient id="idc0uiu" cx="0" cy="0" r="1" gradientTransform="matrix(-2.2201 -.31957 .0932 -.64749 16.928 20.17)" gradientUnits="userSpaceOnUse"><stop class="ufw0a8b9t"/><stop offset="1" class="at62vfs6d"/></radialGradient><radialGradient id="iMAGDRc" cx="0" cy="0" r="1" gradientTransform="rotate(-154.011 8.398 8.283)scale(8.72259 3.48034)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="mw9gk7bly"/><stop offset="1" class="dv70acbut"/></radialGradient><radialGradient id="isZI5dk" cx="0" cy="0" r="1" gradientTransform="rotate(33.19 -29.317 21.252)scale(2.48324 .7466)" gradientUnits="userSpaceOnUse"><stop class="foejprbbc"/><stop offset="1" class="kpssiabxl"/></radialGradient><radialGradient id="isUiL6c" cx="0" cy="0" r="1" gradientTransform="matrix(3.20501 -2.78125 1.73626 2.0008 17.148 23.25)" gradientUnits="userSpaceOnUse"><stop class="f87czphzs"/><stop offset="1" class="pwa97nbfq"/></radialGradient><radialGradient id="iVjF54c" cx="0" cy="0" r="1" gradientTransform="rotate(149.744 8.39 12.983)scale(1.73656 .44089)" gradientUnits="userSpaceOnUse"><stop class="mx64gfpes"/><stop offset="1" class="xqc8z1bhj"/></radialGradient><radialGradient id="iXGLOGd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84252 1.83738 -2.2703 -2.27664 28.357 22.616)" gradientUnits="userSpaceOnUse"><stop offset=".493" class="k7qyxzbsl"/><stop offset=".946" class="zdypug-8z"/></radialGradient><radialGradient id="iejYbrc" cx="0" cy="0" r="1" gradientTransform="matrix(.8321 -.63357 .33086 .43454 28.001 22.853)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="m8ott3b3k"/><stop offset="1" class="zk5cvukoj"/></radialGradient><radialGradient id="ih9GmGc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38281 .60155 -.43729 -1.00521 25.539 20.227)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="bslse1b3i"/><stop offset="1" class="t11-a9gub"/></radialGradient><radialGradient id="iJ8MAGd" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 .42875 26.523 21.266)" gradientUnits="userSpaceOnUse"><stop offset=".112" class="bc2ld5biv"/><stop offset="1" class="a6yy9-nlq"/></radialGradient><radialGradient id="iU1hsCv" cx="0" cy="0" r="1" gradientTransform="matrix(-3.91576 4.34721 -4.19506 -3.7787 28.15 15.25)" gradientUnits="userSpaceOnUse"><stop offset=".004" class="ig92uxq3u"/><stop offset="1" class="thvbr9biq"/></radialGradient><radialGradient id="i5Fhu0c" cx="0" cy="0" r="1" gradientTransform="matrix(2.157 -2.3893 4.6402 4.18907 23.372 19.73)" gradientUnits="userSpaceOnUse"><stop class="k5i52n_gm"/><stop offset="1" class="vsqgrkwbb"/></radialGradient><radialGradient id="ihSbEiX" cx="0" cy="0" r="1" gradientTransform="matrix(.07693 -2.02477 3.711 .141 26.096 18.119)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="lcqew7b7f"/><stop offset="1" class="e6z7sjb6l"/></radialGradient><radialGradient id="i4p48ob" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8752 -1.60814 0 26.025 24.796)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iZmJ6cd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .93815 -1.72383 0 26.025 26.21)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iMY7ere" cx="0" cy="0" r="1" gradientTransform="matrix(0 .78463 -1.44175 0 26.025 27.574)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iO1rLsd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87265 -2.05091 0 26.025 29.05)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iimjsfe" cx="0" cy="0" r="1" gradientTransform="matrix(-.56385 0 0 -1.00365 8.997 12.72)" gradientUnits="userSpaceOnUse"><stop class="ugkpvccwk"/><stop offset="1" class="r1j6u814z"/></radialGradient><radialGradient id="i4PBkIe" cx="0" cy="0" r="1" gradientTransform="rotate(150.173 9.425 8.78)scale(1.41063 1.31947)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="p09v-ib0x"/><stop offset="1" class="odrizw4-e"/></radialGradient><radialGradient id="ifGSGEb" cx="0" cy="0" r="1" gradientTransform="matrix(1.2564 -.84872 .734 1.08658 20.68 14.599)" gradientUnits="userSpaceOnUse"><stop class="gq4ypdk9l"/><stop offset="1" class="ig3v-_bcn"/></radialGradient><radialGradient id="iSRywOc" cx="0" cy="0" r="1" gradientTransform="matrix(.93042 0 0 .9847 20.5 12.761)" gradientUnits="userSpaceOnUse"><stop offset=".417" class="rnqqsfb4k"/><stop offset="1" class="ix33g7bfn"/></radialGradient><radialGradient id="i2ChXpb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.09082 4.20865 -6.92602 -8.37778 19.115 14.8)" gradientUnits="userSpaceOnUse"><stop class="rh-5aqr4q"/><stop offset="1" class="cliinab_v"/></radialGradient><radialGradient id="ijTvxUb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.71703 -9.71861 0 14.844 12.32)" gradientUnits="userSpaceOnUse"><stop offset=".827" class="p_us1bcmz"/><stop offset="1" class="hnzo5vbxo"/></radialGradient><radialGradient id="iSiVpFk" cx="0" cy="0" r="1" gradientTransform="matrix(.37643 3.73465 -9.33831 .94126 14.468 10.512)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="msi2xwmia"/><stop offset="1" class="op2cr7b6k"/></radialGradient><radialGradient id="iqsBszc" cx="0" cy="0" r="1" gradientTransform="matrix(.2185 -.97737 2.76663 .6185 13.216 19.96)" gradientUnits="userSpaceOnUse"><stop class="ogth-vbau"/><stop offset="1" class="b9_unlbjk"/></radialGradient><radialGradient id="iXWyppc" cx="0" cy="0" r="1" gradientTransform="matrix(-.11567 -.95795 2.9398 -.35498 17.007 20.038)" gradientUnits="userSpaceOnUse"><stop class="ogth-vbau"/><stop offset="1" class="b9_unlbjk"/></radialGradient><radialGradient id="iqVn5ue" cx="0" cy="0" r="1" gradientTransform="rotate(94.315 5.222 14.662)scale(4.2555 1.33779)" gradientUnits="userSpaceOnUse"><stop class="pmsl8cbsg"/><stop offset="1" class="ua8pt3btf"/></radialGradient><radialGradient id="i3EnENg" cx="0" cy="0" r="1" gradientTransform="rotate(90 .283 15)scale(.33984 .80079)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="u-0u9ed1s"/><stop offset="1" class="djh-26h2g"/></radialGradient><radialGradient id="i26wo4B" cx="0" cy="0" r="1" gradientTransform="matrix(.38443 -.69734 2.09203 1.1533 13.703 17.156)" gradientUnits="userSpaceOnUse"><stop class="ooeyopb3c"/><stop offset="1" class="q47tddchj"/></radialGradient><radialGradient id="iyOGulJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03773 -1.22791 0 17.314 12.479)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="mrtz5_gxn"/><stop offset="1" class="um4p__bni"/></radialGradient><radialGradient id="icmYJFc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.811 11.512 1.92)scale(.43456 .59827)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i18vOii" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.03779 -1.22797 0 12.301 12.479)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="mrtz5_gxn"/><stop offset="1" class="um4p__bni"/></radialGradient><radialGradient id="iFbcshM" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.064 .28)scale(.56764 .68234)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iRhuwwe" cx="0" cy="0" r="1" gradientTransform="matrix(-.1875 .74219 -.13122 -.03315 21.407 11.326)" gradientUnits="userSpaceOnUse"><stop class="alegm0bhy"/><stop offset="1" class="p_nkfzbsb"/></radialGradient><radialGradient id="irLEf8c" cx="0" cy="0" r="1" gradientTransform="matrix(-.77386 .0032 -.00524 -1.2664 8.844 11.57)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="ascgmfalu"/><stop offset=".687" class="o301vhxpn"/></radialGradient><radialGradient id="i8gh6Fe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.90342 3.34379 -2.24881 -4.64278 20.958 3.094)" gradientUnits="userSpaceOnUse"><stop class="ld92_g1my"/><stop offset="1" class="dvhbibcqh"/></radialGradient><radialGradient id="iBfj5Pd" cx="0" cy="0" r="1" gradientTransform="matrix(3.25 -.4375 1.025 7.6143 8.492 6.125)" gradientUnits="userSpaceOnUse"><stop class="t0ozsbnai"/><stop offset="1" class="iqoe-4pvq"/></radialGradient><radialGradient id="ieAjMmb" cx="0" cy="0" r="1" gradientTransform="matrix(.71875 1.89873 -3.57306 1.35256 11.648 2.078)" gradientUnits="userSpaceOnUse"><stop class="uvo3wxbsr"/><stop offset="1" class="vjaj-kz7h"/></radialGradient><radialGradient id="iQFwsnd" cx="0" cy="0" r="1" gradientTransform="rotate(179.635 9.633 3.609)scale(4.90635 4.18652)" gradientUnits="userSpaceOnUse"><stop class="c77y5fbir"/><stop offset="1" class="a4oc_-5ds"/></radialGradient><linearGradient id="iOhOn5b" x1="6.988" x2="7.195" y1="29.407" y2="29.407" gradientUnits="userSpaceOnUse"><stop offset=".151" class="x84cwhbna"/><stop offset="1" class="fk1gregde"/></linearGradient><linearGradient id="imSQI2c" x1="16.932" x2="14.847" y1="28.545" y2="28.119" gradientUnits="userSpaceOnUse"><stop offset=".045" class="o8gobxb3n"/><stop offset="1" class="q-14d3boa"/></linearGradient><linearGradient id="im9eHqM" x1="13.726" x2="14.226" y1="26.766" y2="26.813" gradientUnits="userSpaceOnUse"><stop class="i78i3vbiy"/><stop offset="1" class="la8vvmbhh"/></linearGradient><linearGradient id="i4hNkDe" x1="16.414" x2="15.153" y1="29.069" y2="29.122" gradientUnits="userSpaceOnUse"><stop offset=".065" class="bt46k-bry"/><stop offset="1" class="d-k16gi6m"/></linearGradient><linearGradient id="iMIg2ZO" x1="11.675" x2="12.612" y1="21.649" y2="21.468" gradientUnits="userSpaceOnUse"><stop class="bcp6zybsw"/><stop offset="1" class="kte-0sm3k"/></linearGradient><linearGradient id="iGkGbCb" x1="18.074" x2="17.137" y1="21.649" y2="21.468" gradientUnits="userSpaceOnUse"><stop class="bcp6zybsw"/><stop offset="1" class="kte-0sm3k"/></linearGradient><linearGradient id="iimzjsu" x1="12.219" x2="9.392" y1="26.17" y2="26.807" gradientUnits="userSpaceOnUse"><stop class="rcslxcb9f"/><stop offset="1" class="arpepeb0z"/></linearGradient><linearGradient id="iwOdF4c" x1="9.392" x2="11.085" y1="16.977" y2="22.375" gradientUnits="userSpaceOnUse"><stop class="oh_d1sh7z"/><stop offset="1" class="x2herp8_d"/></linearGradient><linearGradient id="i2jMWwb" x1="12.268" x2="12.268" y1="29.922" y2="24.7" gradientUnits="userSpaceOnUse"><stop class="nw6o4wclj"/><stop offset="1" class="q8ppcjbus"/></linearGradient><linearGradient id="i1VflDU" x1="18.023" x2="21.304" y1="29.125" y2="16.977" gradientUnits="userSpaceOnUse"><stop offset=".452" class="t-s_cxb3y"/><stop offset="1" class="zpb-61ddc"/></linearGradient><linearGradient id="iEAfnnc" x1="17" x2="17.152" y1="26.539" y2="26.571" gradientUnits="userSpaceOnUse"><stop class="njrd_tayg"/><stop offset="1" class="d1xnqxb5m"/></linearGradient><linearGradient id="iGFxt3d" x1="26.981" x2="24.992" y1="21.781" y2="21.781" gradientUnits="userSpaceOnUse"><stop class="x26s0_r_n"/><stop offset="1" class="x__1z6aoh"/></linearGradient><linearGradient id="iWBccNc" x1="26.336" x2="26.336" y1="25.469" y2="22.563" gradientUnits="userSpaceOnUse"><stop class="zuvzebcmo"/><stop offset="1" class="fjaxvnbiy"/></linearGradient><linearGradient id="irI5LDd" x1="28.179" x2="23.367" y1="14.344" y2="19.781" gradientUnits="userSpaceOnUse"><stop class="tnc_xbdtt"/><stop offset="1" class="n3pyssb7u"/></linearGradient><linearGradient id="iVQ1G1c" x1="27.914" x2="23.131" y1="27.807" y2="27.807" gradientUnits="userSpaceOnUse"><stop offset=".146" class="o3k0towjz"/><stop offset=".861" class="qxb7siz6w"/></linearGradient><linearGradient id="iXiyPSb" x1="23.699" x2="25.565" y1="25.609" y2="25.609" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="iEmyyOd" x1="23.614" x2="25.48" y1="27.034" y2="27.034" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="i5CGbMd" x1="23.699" x2="25.565" y1="28.458" y2="28.458" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="iYEQSYb" x1="20.532" x2="19.718" y1="15.15" y2="15.075" gradientUnits="userSpaceOnUse"><stop offset=".104" class="n58_dtv9g"/><stop offset="1" class="qcpu47v1y"/></linearGradient><linearGradient id="iSQRRGe" x1="15.034" x2="15.034" y1="15.378" y2="14.5" gradientUnits="userSpaceOnUse"><stop class="n2an33x5n"/><stop offset="1" class="wkf83e0qz"/></linearGradient><linearGradient id="ifDWPbh" x1="15.889" x2="15.313" y1="14.607" y2="14.732" gradientUnits="userSpaceOnUse"><stop offset=".167" class="qjo8hdbly"/><stop offset="1" class="ay3b1rx8x"/></linearGradient><linearGradient id="iGskQPe" x1="14.672" x2="14.938" y1="12.289" y2="13.579" gradientUnits="userSpaceOnUse"><stop class="ma_eytbbu"/><stop offset="1" class="bkmy2g1ea"/></linearGradient><linearGradient id="iE5JQae" x1="18.208" x2="17.848" y1="12.158" y2="12.38" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iN3jgZV" x1="13.156" x2="12.795" y1="12.158" y2="12.38" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i6dlANQ" x1="21.212" x2="20.677" y1="11.586" y2="11.61" gradientUnits="userSpaceOnUse"><stop class="bookipbew"/><stop offset="1" class="vo-fv2-ue"/></linearGradient><linearGradient id="iodu1md" x1="23.304" x2="6.367" y1="9.438" y2="9.753" gradientUnits="userSpaceOnUse"><stop class="damj_nbgh"/><stop offset=".519" class="bpzzcwljp"/><stop offset=".98" class="fpxhxfble"/></linearGradient><linearGradient id="iAJlZRd" x1="8.554" x2="9.992" y1="6.877" y2="7.063" gradientUnits="userSpaceOnUse"><stop class="s_d1fy10v"/><stop offset="1" class="gn4fmf85p"/></linearGradient><linearGradient id="iLKj4pc" x1="15.461" x2="15.461" y1="7.93" y2="7.727" gradientUnits="userSpaceOnUse"><stop offset=".038" class="rc26n1b9i"/><stop offset="1" class="m5pcs-93k"/></linearGradient><linearGradient id="invRgge" x1="15.507" x2="15.507" y1="5.848" y2="5.984" gradientUnits="userSpaceOnUse"><stop offset=".038" class="rc26n1b9i"/><stop offset="1" class="m5pcs-93k"/></linearGradient><filter id="i9w7ipc" width="7.346" height="5.139" x="11.201" y="19.168" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2752" stdDeviation=".25"/></filter><filter id="iWAps0m" width="3.106" height="2.966" x="13.406" y="21.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.133333 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2752"/></filter><filter id="iRAVP2c" width="8.299" height="13.046" x="5.292" y="16.877" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.396078 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2752"/></filter><filter id="ipKYOud" width="8.299" height="13.046" x="16.153" y="16.877" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.215686 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2752"/></filter><filter id="i8GENiL" width="6.656" height="6.656" x="22.367" y="13.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2752" stdDeviation=".125"/></filter><filter id="iuAD9Db" width="7.206" height="7.206" x="22.067" y="13.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.27451 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2752"/></filter><filter id="iWbtIOa" width="5.277" height="6.052" x="23.131" y="23.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.117647 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2752"/></filter><filter id="ikh2hDj" width="2.262" height=".3" x="23.549" y="25.381" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2752" stdDeviation=".05"/></filter><filter id="iiL1PSb" width="2.262" height=".3" x="23.464" y="26.806" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2752" stdDeviation=".05"/></filter><filter id="iOTj7zb" width="2.262" height=".3" x="23.549" y="28.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2752" stdDeviation=".05"/></filter><filter id="ix2FcGc" width="3.936" height="3.836" x="7.437" y="10.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.399183 0 0 0 0 0.30229 0 0 0 0 0.291525 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2752"/></filter><filter id="igTrbAb" width="2.786" height="2.786" x="7.962" y="11.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2752" stdDeviation=".125"/></filter><filter id="i54dNRc" width="3.886" height="3.886" x="18.318" y="10.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.305882 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2752"/></filter><filter id="iVBeBHb" width="2.786" height="2.786" x="18.893" y="11.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2752" stdDeviation=".125"/></filter><filter id="iwHnbae" width="12.519" height="13.82" x="8.884" y="6.218" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".8"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.317647 0 0 0 0 0.247059 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2752"/></filter><filter id="icurQfx" width="3.522" height="4.581" x="12.775" y="11.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2752" stdDeviation=".375"/></filter><filter id="iw1QXJq" width="2.656" height="3.581" x="13.483" y="12.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0862745 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2752"/><feGaussianBlur result="effect2_foregroundBlur_4002_2752" stdDeviation=".125"/></filter><filter id="iYhbH1S" width="2.656" height="3.581" x="13.483" y="11.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2752" stdDeviation=".125"/></filter><filter id="ii0EEHc" width="4.097" height="1.632" x="12.762" y="15.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2752" stdDeviation=".05"/></filter><filter id="ivxwm2c" width=".874" height=".77" x="16.486" y="11.605" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2752" stdDeviation=".05"/></filter><filter id="ikMzVmd" width=".964" height=".99" x="17.466" y="11.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2752" stdDeviation=".1"/></filter><filter id="iJAp5le" width="1.074" height="1.135" x="12.362" y="11.633" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2752" stdDeviation=".1"/></filter><filter id="itKioSm" width="1.019" height=".78" x="11.48" y="11.596" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2752" stdDeviation=".05"/></filter><filter id="igkA1Sp" width="12.369" height="3.947" x="8.798" y="2.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2752"/></filter><filter id="ir8krEd" width="19.912" height="4.003" x="4.916" y="7.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.447059 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2752"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.372549 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2752" result="effect2_innerShadow_4002_2752"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-detective-dark" /></template>
<style>
.a4oc_-5ds {
  stop-color: var(--svg-color--372153, #372153);
}

.a6yy9-nlq {
  stop-color: var(--svg-color--46446d, #46446D);
  stop-opacity: 0;
}

.agjep-b6f {
  d: path("m11.972 22.727l-.806-3.758h1.851l1.867 2.488v.434l-1.96 1.78c-.097.084-.327.215-.477.071s-.357-.504-.475-1.015");
}

.alegm0bhy {
  stop-color: var(--svg-color--494848, #494848);
}

.altutfb8x {
  stop-color: var(--svg-color--ab9ca0, #AB9CA0);
}

.arpepeb0z {
  stop-color: var(--svg-color--665c8a, #665C8A);
}

.ascgmfalu {
  stop-color: var(--svg-color--140b1a, #140B1A);
}

.asvjbc-zd {
  stop-color: var(--svg-color--b4366c, #B4366C);
}

.at62vfs6d {
  stop-color: var(--svg-color--3f3337, #3F3337);
  stop-opacity: 0;
}

.ay3b1rx8x {
  stop-color: var(--svg-color--4a3634, #4A3634);
  stop-opacity: 0;
}

.b9_unlbjk {
  stop-color: var(--svg-color--44373d, #44373D);
  stop-opacity: 0;
}

.bc2ld5biv {
  stop-color: var(--svg-color--46446d, #46446D);
}

.bc7i0ongh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.7 28.38h1.96");
}

.bcp6zybsw {
  stop-color: var(--svg-color--7c707d, #7C707D);
}

.bkmy2g1ea {
  stop-color: var(--svg-color--2d1b23, #2D1B23);
  stop-opacity: 0;
}

.bookipbew {
  stop-color: var(--svg-color--343233, #343233);
}

.bpzzcwljp {
  stop-color: var(--svg-color--5b537a, #5B537A);
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

.cej917bjj {
  d: path("m13.445 29.922l-2.328-10.956l3.422-1.2l4.437 1.293l-2.281 10.863z");
}

.cj2gegbdf {
  stop-color: var(--svg-color--4f4376, #4F4376);
}

.cjc9cqblk {
  stop-color: var(--svg-color--ceadc3, #CEADC3);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cliinab_v {
  stop-color: var(--svg-color--362224, #362224);
}

.ctc_opbat {
  fill: var(--svg-color--000, #000);
  d: path("M16.73 12.573c0-.327.26-.588.587-.588a.585.585 0 0 1 .522.858h-1.04a.53.53 0 0 1-.07-.27");
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

.djh-26h2g {
  stop-color: var(--svg-color--544444, #544444);
  stop-opacity: 0;
}

.dv70acbut {
  stop-color: var(--svg-color--534971, #534971);
  stop-opacity: 0;
}

.dvhbibcqh {
  stop-color: var(--svg-color--625783, #625783);
}

.e6z7sjb6l {
  stop-color: var(--svg-color--dbf3ff, #DBF3FF);
}

.e9sv_2buc {
  stop-color: var(--svg-color--dbc8d7, #DBC8D7);
}

.entsizubv {
  stop-color: var(--svg-color--5e4745, #5E4745);
}

.erhkeibcy {
  width: 2.572px;
  height: 5.438px;
  x: 24.409px;
  y: 20.227px;
  rx: 1.286px;
}

.f-gl8-mln {
  d: path("M18.23 12.438a.97.97 0 0 0-.266-.532l-.298.328l.134.262z");
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

.fkavrburz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.7 25.531h1.96");
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

.g7gmqhncd {
  d: path("M7.023 29.922H2.727a12.16 12.16 0 0 1 4.296-8.538z");
}

.gi2uz_g9v {
  stop-color: var(--svg-color--514c59, #514C59);
}

.gn4fmf85p {
  stop-color: var(--svg-color--3e3058, #3E3058);
  stop-opacity: 0;
}

.gq4ypdk9l {
  stop-color: var(--svg-color--352029, #352029);
}

.hazfh8b2v {
  d: path("m14.098 24.349l-.692-1.333l1.453-1.352l1.453 1.352l-.662 1.33a.15.15 0 0 1-.134.084h-1.285a.15.15 0 0 1-.133-.081");
}

.he0pvmbuq {
  stop-color: var(--svg-color--341721, #341721);
}

.hknh16mic {
  d: path("M8.951 11.976c-.03-.36-.067-1.388-.067-1.652c0-.307.124-.674.37-.858l.185-.184c.308-.245.432-.613.432-.98V7.32c0-.307.184-.552.493-.613c.74-.184 2.28-.49 4.499-.49s3.76.306 4.499.49c.246.061.493.306.493.613v.98c0 .368.185.736.431.98c.577.405.541.627.493 1.104c-.014.148-.061 1.372-.102 1.654l-.305 4.549c-.185 2.033-1.783 3.45-3.69 3.45h-3.688c-1.967 0-3.504-1.417-3.689-3.45z");
}

.hnzo5vbxo {
  stop-color: var(--svg-color--3f333a, #3F333A);
}

.hox-jgbyg {
  cx: 20.286px;
  cy: 12.68px;
  r: 1.918px;
  fill: var(--svg-color--4a3231, #4A3231);
}

.hqp1wu_he {
  cx: 20.286px;
  cy: 12.68px;
  r: 1.143px;
}

.hx_wmlsuf {
  fill-rule: evenodd;
  d: path("M25.695 20.672a3.578 3.578 0 1 0 0-7.156a3.578 3.578 0 0 0 0 7.156m0-.594a2.984 2.984 0 1 0 0-5.969a2.984 2.984 0 0 0 0 5.97");
}

.i78i3vbiy {
  stop-color: var(--svg-color--ad254b, #AD254B);
}

.i7g4iz6bw {
  stop-color: var(--svg-color--6f6a93, #6F6A93);
  stop-opacity: 0;
}

.ig3v-_bcn {
  stop-color: var(--svg-color--352029, #352029);
  stop-opacity: 0;
}

.ig92uxq3u {
  stop-color: var(--svg-color--50d5fa, #50D5FA);
}

.ijrk-tbbt {
  d: path("m8.07 10.762l.198.814c.058.35.357.6.701.624c-.014-.226-.046-.631-.058-.978l-.017-.46z");
}

.ipzl6eb6x {
  fill: var(--svg-color--351f20, #351F20);
  d: path("m14.372 12.622l-.61 1.953a.62.62 0 0 0 .597.803h.904a.62.62 0 0 0 .598-.803l-.61-1.953c-.132-.433-.742-.433-.88 0");
}

.iqoe-4pvq {
  stop-color: var(--svg-color--766c87, #766C87);
  stop-opacity: 0;
}

.ivj3pk5jv {
  d: path("M8.803 5.743a.1.1 0 0 0 .095.132h11.92a.1.1 0 0 0 .094-.133a87 87 0 0 0-.639-1.789c-.469-1.25-1.637-1.875-2.297-1.875c-.735-.016-1.259.318-1.65.567l-.194.12c-.578.344-.808.4-1.277.4c-.371 0-.762-.15-1.184-.368q-.11-.058-.247-.142c-.436-.26-1.078-.642-1.905-.526c-.956.134-1.66.93-2.097 1.945a29 29 0 0 0-.619 1.669");
}

.ix33g7bfn {
  stop-color: var(--svg-color--361d1f, #361D1F);
}

.j_dulcbnt {
  fill: var(--svg-color--655d95, #655D95);
  d: path("M2.727 29.922H27.01c-.399-6.368-5.682-11.409-12.142-11.409S3.125 23.554 2.727 29.923");
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

.k7qyxzbsl {
  stop-color: var(--svg-color--4b312d, #4B312D);
}

.k9h8bsbwk {
  stop-color: var(--svg-color--403357, #403357);
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

.ljhgv1b3v {
  cx: 11.99px;
  cy: 11.986px;
  rx: 0.448px;
  ry: 0.227px;
}

.lldgadc0f {
  cx: 9.356px;
  cy: 12.68px;
  r: 1.918px;
  fill: var(--svg-color--311f22, #311F22);
}

.m5pcs-93k {
  stop-color: var(--svg-color--2c1840, #2C1840);
  stop-opacity: 0;
}

.m8ott3b3k {
  stop-color: var(--svg-color--675655, #675655);
}

.ma_eytbbu {
  stop-color: var(--svg-color--2d1b23, #2D1B23);
}

.mibx7d57r {
  fill: var(--svg-color--000, #000);
  d: path("M12.886 12.573a.585.585 0 0 0-.587-.587a.585.585 0 0 0-.522.857h1.04a.6.6 0 0 0 .07-.27");
}

.mop_zlbnl {
  d: path("m10.75 16.977l2.742 12.945h-1.797a1566 1566 0 0 1-4.625-7.734c-.422-.735-.219-.906-.14-1.031c.077-.125.374-.36.671-.47c.238-.087.328-.202.344-.25c.057-.067.069-.3-.344-.687c-.412-.387-1.307-1.067-1.703-1.36c-.234-.187-.652-.608-.602-.983s.652-.435.766-.43z");
}

.mp8t_zb5c {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.242 11.764c.072.098-.08.217-.254.347c-.173.13-.302.22-.375.123c-.073-.098.008-.282.182-.412c.173-.13.373-.156.446-.058");
}

.mrtz5_gxn {
  stop-color: var(--svg-color--5a3c37, #5A3C37);
}

.msi2xwmia {
  stop-color: var(--svg-color--2c1a22, #2C1A22);
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

.n2an33x5n {
  stop-color: var(--svg-color--3c202e, #3C202E);
}

.n3m4ul9nu {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.555 11.235c.75 0 1.384.518 1.556 1.217a.315.315 0 0 1-.308.391h-2.562a.264.264 0 0 1-.261-.312a1.606 1.606 0 0 1 1.575-1.296");
}

.n3pyssb7u {
  stop-color: var(--svg-color--452053, #452053);
}

.n58_dtv9g {
  stop-color: var(--svg-color--56413f, #56413F);
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

.o301vhxpn {
  stop-color: var(--svg-color--494645, #494645);
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
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

.odrizw4-e {
  stop-color: var(--svg-color--615251, #615251);
  stop-opacity: 0;
}

.ogth-vbau {
  stop-color: var(--svg-color--44373d, #44373D);
}

.oh_d1sh7z {
  stop-color: var(--svg-color--5e5a78, #5E5A78);
}

.ol5y5gj7m {
  stop-color: var(--svg-color--69638b, #69638B);
  stop-opacity: 0;
}

.ooeyopb3c {
  stop-color: var(--svg-color--554748, #554748);
}

.op_u9g8uj {
  stop-color: var(--svg-color--c03660, #C03660);
}

.op2cr7b6k {
  stop-color: var(--svg-color--2c1a22, #2C1A22);
  stop-opacity: 0;
}

.p_nkfzbsb {
  stop-color: var(--svg-color--494848, #494848);
  stop-opacity: 0;
}

.p_us1bcmz {
  stop-color: var(--svg-color--3b202d, #3B202D);
  stop-opacity: 0;
}

.p09v-ib0x {
  stop-color: var(--svg-color--615251, #615251);
}

.p1ua1lbjw {
  stop-color: var(--svg-color--3e292e, #3E292E);
}

.pb1ehqpec {
  stop-color: var(--svg-color--4f456a, #4F456A);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmsl8cbsg {
  stop-color: var(--svg-color--4e3a38, #4E3A38);
}

.pwa97nbfq {
  stop-color: var(--svg-color--5b4361, #5B4361);
  stop-opacity: 0;
}

.q-14d3boa {
  stop-color: var(--svg-color--8c7c93, #8C7C93);
  stop-opacity: 0;
}

.q47tddchj {
  stop-color: var(--svg-color--554748, #554748);
  stop-opacity: 0;
}

.q8ppcjbus {
  stop-color: var(--svg-color--624c7f, #624C7F);
  stop-opacity: 0;
}

.qasiqcczj {
  stop-color: var(--svg-color--837a8e, #837A8E);
  stop-opacity: 0;
}

.qcpu47v1y {
  stop-color: var(--svg-color--56413f, #56413F);
  stop-opacity: 0;
}

.qjo8hdbly {
  stop-color: var(--svg-color--4a3634, #4A3634);
}

.quksm7bdn {
  d: path("M23.132 24.819c0-.438.355-.799.793-.799h3.023c.724 0 1.31.587 1.31 1.31v3.5c0 .603-.488 1.092-1.091 1.092h-3.242a.798.798 0 0 1-.349-1.516a.802.802 0 0 1 0-1.435a.802.802 0 0 1 0-1.435a.8.8 0 0 1-.445-.717");
}

.qxb7siz6w {
  stop-color: var(--svg-color--3f282a, #3F282A);
}

.qy2xrui7g {
  d: path("M27.203 22.328c.58 0 1.055.475 1.055 1.056V25.8h-2.111v-2.417c.01-.58.475-1.056 1.056-1.056");
}

.r1j6u814z {
  stop-color: var(--svg-color--251217, #251217);
}

.rc26n1b9i {
  stop-color: var(--svg-color--2c1840, #2C1840);
}

.rcslxcb9f {
  stop-color: var(--svg-color--675685, #675685);
}

.rh-5aqr4q {
  stop-color: var(--svg-color--4a2e2c, #4A2E2C);
}

.rnqqsfb4k {
  stop-color: var(--svg-color--412d2e, #412D2E);
}

.rxpl4qnie {
  stop-color: var(--svg-color--4e4854, #4E4854);
  stop-opacity: 0;
}

.s_d1fy10v {
  stop-color: var(--svg-color--4c4364, #4C4364);
}

.sxgpvtb4k {
  d: path("m14.372 12.622l-.61 1.953a.62.62 0 0 0 .597.803h.904a.62.62 0 0 0 .598-.803l-.61-1.953c-.132-.433-.742-.433-.88 0");
}

.t-s_cxb3y {
  stop-color: var(--svg-color--5b4373, #5B4373);
}

.t08-s2dqp {
  d: path("M12.625 19.547c.026.291.262.987.999 1.437c.736.45 1.14.63 1.25.664c.11-.033.515-.214 1.251-.664c.737-.45.973-1.146 1-1.437z");
}

.t0ozsbnai {
  stop-color: var(--svg-color--766c87, #766C87);
}

.t11-a9gub {
  stop-color: var(--svg-color--0d0e30, #0D0E30);
  stop-opacity: 0;
}

.t9v2librs {
  fill: var(--svg-color--beb2c3, #BEB2C3);
  d: path("m13.445 29.922l-2.328-10.956l3.422-1.2l4.437 1.293l-2.281 10.863z");
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

.tnviirb6b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.614 26.956h1.962");
}

.tq2a2nban {
  d: path("M8.126 7.748a.1.1 0 0 0 .095.13h13.287a.1.1 0 0 0 .094-.132l-.192-.559l-.429-1.245a.1.1 0 0 0-.094-.067H8.829a.1.1 0 0 0-.095.067c-.19.554-.38 1.12-.531 1.575z");
}

.ttuoqj4wj {
  fill: var(--svg-color--361d28, #361D28);
  d: path("m14.495 12.809l-.943 1.953c-.117.401.164.803.56.803h.848c.397 0 .678-.408.56-.803l-.572-1.953c-.123-.433-.325-.433-.453 0");
}

.u-0u9ed1s {
  stop-color: var(--svg-color--544444, #544444);
}

.ua8pt3btf {
  stop-color: var(--svg-color--4e3a38, #4E3A38);
  stop-opacity: 0;
}

.ufw0a8b9t {
  stop-color: var(--svg-color--3f3337, #3F3337);
}

.ugkpvccwk {
  stop-color: var(--svg-color--291a20, #291A20);
}

.um4p__bni {
  stop-color: var(--svg-color--442e33, #442E33);
}

.ur8e5kbgj {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
  stop-opacity: 0;
}

.uvo3wxbsr {
  stop-color: var(--svg-color--5f577e, #5F577E);
}

.v9c6zoseo {
  d: path("M13.236 12.452c0-.33-.27-.552-.343-.618l-.33.32l.203.415z");
}

.vd-u4acdq {
  cx: 25.695px;
  cy: 17.094px;
  r: 2.984px;
}

.vi7fu79ul {
  d: path("m13.289 29.922l.854-5.408a.1.1 0 0 1 .098-.084h1.247a.1.1 0 0 1 .099.085l.827 5.407z");
}

.vjaj-kz7h {
  stop-color: var(--svg-color--5f577e, #5F577E);
  stop-opacity: 0;
}

.vo-fv2-ue {
  stop-color: var(--svg-color--100917, #100917);
}

.vsqgrkwbb {
  stop-color: var(--svg-color--2bace5, #2BACE5);
  stop-opacity: 0;
}

.vwddzbb7h {
  d: path("m14.372 12.364l-.61 1.952a.62.62 0 0 0 .597.804h.904a.62.62 0 0 0 .598-.804l-.61-1.953c-.132-.432-.742-.432-.88 0");
}

.wgl1mtbjd {
  d: path("m17.77 22.746l.814-3.777h-1.852l-1.867 2.484v.438l1.96 1.78c.097.084.327.215.477.071s.35-.484.467-.996");
}

.wj3drmbex {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
}

.wj9mtgody {
  stop-color: var(--svg-color--533531, #533531);
  stop-opacity: 0;
}

.wkf83e0qz {
  stop-color: var(--svg-color--3c202e, #3C202E);
  stop-opacity: 0;
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

.x2je5736g {
  fill: var(--svg-color--290018, #290018);
  d: path("M14.81 16.4c-.582 0-1.13-.137-1.59-.377c-.158-.08-.327.097-.228.24a2.17 2.17 0 0 0 1.819.972c.764 0 1.434-.389 1.819-.972c.099-.149-.07-.32-.228-.24a3.4 3.4 0 0 1-1.591.377");
}

.x84cwhbna {
  stop-color: var(--svg-color--57497f, #57497F);
}

.x8vyagemg {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.061 11.235c-.75 0-1.384.518-1.556 1.217c-.052.2.102.391.307.391h2.563a.264.264 0 0 0 .261-.312a1.61 1.61 0 0 0-1.575-1.296");
}

.xhfhhvoed {
  d: path("m18.996 16.977l-2.743 12.945h1.797c1.401-2.333 4.288-7.147 4.625-7.734c.422-.735.219-.906.14-1.031c-.077-.125-.374-.36-.671-.47c-.238-.087-.328-.202-.344-.25c-.057-.067-.069-.3.344-.687c.412-.387 1.307-1.067 1.703-1.36c.234-.187.652-.608.602-.983s-.651-.435-.766-.43z");
}

.xqc8z1bhj {
  stop-color: var(--svg-color--6a6385, #6A6385);
  stop-opacity: 0;
}

.xtl5dn5fo {
  stop-color: var(--svg-color--403357, #403357);
  stop-opacity: 0;
}

.y-v21bc8n {
  cx: 11.99px;
  cy: 11.986px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.448px;
  ry: 0.227px;
}

.y411x-6nn {
  fill: var(--svg-color--f7a936, #F7A936);
  d: path("m17.77 22.746l.814-3.777h-1.852l-1.867 2.484v.438l1.96 1.78c.097.084.327.215.477.071s.35-.484.467-.996");
}

.ylkb8lnyx {
  stop-color: var(--svg-color--988b89, #988B89);
}

.yzf80p4jc {
  cx: 9.356px;
  cy: 12.68px;
  r: 1.143px;
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

.zdypug-8z {
  stop-color: var(--svg-color--2b1820, #2B1820);
}

.zk5cvukoj {
  stop-color: var(--svg-color--675655, #675655);
  stop-opacity: 0;
}

.zpb-61ddc {
  stop-color: var(--svg-color--645d7e, #645D7E);
}

.zqbz6fbvb {
  stop-color: var(--svg-color--988b89, #988B89);
  stop-opacity: 0;
}

.zuvzebcmo {
  stop-color: var(--svg-color--4c3156, #4C3156);
}

.zy5dj18nw {
  stop-color: var(--svg-color--69638b, #69638B);
}

</style>
