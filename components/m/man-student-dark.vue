<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="tdspomboy"/><path fill="url(#iShjP1d)" class="lofln44ah"/><path fill="url(#iJCZuse)" class="lofln44ah"/><path fill="url(#i1tMb2c)" class="gt7karm9l"/><path fill="url(#iQ1bxFb)" class="gt7karm9l"/><path fill="url(#iM2KgFb)" class="gt7karm9l"/><path fill="url(#iAxLMnM)" class="gt7karm9l"/><path fill="url(#i3relic)" class="gt7karm9l"/><path fill="url(#iCbDZjb)" class="gt7karm9l"/><g filter="url(#i5Rrpbb)"><path class="iol43dbmc"/></g><path fill="url(#iVmefXb)" class="qzpxx2zfo"/><path fill="url(#iSsq4dd)" class="huv6ahl7x"/><path fill="url(#inS6Nib)" class="huv6ahl7x"/><path fill="url(#iO36YQc)" class="nbjen9ayx"/><path fill="url(#iHBAZZb)" class="nbjen9ayx"/><g filter="url(#if3qUnc)"><path stroke="url(#icQ715d)" class="t-4dqr8wd"/></g><path fill="url(#iBM5Yeb)" class="e_tdnmb5p"/><path fill="url(#i4WF3xe)" class="e_tdnmb5p"/><path fill="url(#iylIXxb)" class="e_tdnmb5p"/><path fill="url(#iYfj3Fe)" class="e_tdnmb5p"/><path fill="url(#ibc2wNd)" class="e_tdnmb5p"/><path fill="url(#iJNu79c)" class="ax7l12irz"/><path fill="url(#i8j7end)" class="ax7l12irz"/><path fill="url(#iCsBhuc)" class="ax7l12irz"/><path fill="url(#iidxf0E)" class="t8woa55ub"/><path fill="url(#igo2Rrd)" class="t8woa55ub"/><g filter="url(#izIFZMc)"><path fill="url(#i6KZEte)" class="vbz233bhb"/><path fill="url(#i6KZEte)" class="u8mt89bic"/><path fill="url(#i6KZEte)" class="i03ojmbde"/></g><g filter="url(#iBJtsIe)"><path stroke="url(#igUsG4c)" class="ifaqb7_nl"/></g><g filter="url(#i9fHehc)"><circle fill="url(#i25Qfpc)" class="rtoowqb1c"/></g><g filter="url(#iCDmxke)"><circle fill="url(#iAX7Bjc)" class="ibw3dsbln"/></g><g filter="url(#icvVhHe)"><circle fill="url(#iHnqmce)" class="d8ahkmbec"/><circle fill="url(#ij8e3Yc)" class="d8ahkmbec"/></g><g filter="url(#igXDT2c)"><circle class="p5y0jzbpk"/><circle fill="url(#iYgu48c)" class="w_89ngnqd"/><circle fill="url(#i4fi1yc)" class="w_89ngnqd"/></g><g filter="url(#iI8VXFt)"><path fill="url(#ir3lCOd)" class="hqjsggb6l"/><path fill="url(#iKRx5Ib)" class="hqjsggb6l"/><path fill="url(#iNiFXcc)" class="hqjsggb6l"/><path fill="url(#igvjBJk)" class="hqjsggb6l"/><path fill="url(#iP4vjTc)" class="hqjsggb6l"/><path fill="url(#i7zHkrd)" class="hqjsggb6l"/></g><g filter="url(#irm0ntD)"><path fill="url(#iYVOxQe)" class="rortc5hfq"/></g><g filter="url(#i8WLpTd)"><path class="p0bhhfiuk"/><path fill="url(#iTUsIqd)" class="ovbc_0adl"/><path fill="url(#ibTK6Dc)" class="ovbc_0adl"/><path fill="url(#iY0X0ue)" class="ovbc_0adl"/><path fill="url(#ieBKeRc)" class="ovbc_0adl"/></g><g filter="url(#iRTqSLe)"><path class="is8j1620z"/></g><g filter="url(#iea90mb)"><path class="q3rw-m17o"/><path fill="url(#iD4Pyse)" class="rsym7yjli"/><path fill="url(#icgRlve)" class="rsym7yjli"/><path fill="url(#icWvbCd)" class="rsym7yjli"/><path fill="url(#igukR7m)" class="rsym7yjli"/></g><path fill="url(#iZc0h7c)" class="rsym7yjli"/><path stroke="url(#ifIjyMC)" class="i7ocd2bwe"/><g filter="url(#i8Mudud)"><path class="yxoweybto"/></g><g filter="url(#iIgkm1O)"><path class="n8kkam5mt"/></g><path class="z_nasnbnz"/><path fill="url(#ia0bFpc)" class="o-57_ub3b"/><path class="w_qp_xmzd"/><g filter="url(#iNX7lIb)"><path class="jx0xfzb3o"/><path fill="url(#iW3WRAd)" class="ktr6gcbdt"/></g><g filter="url(#irgnKsc)"><path fill="url(#ihV0jYc)" class="wf9jlob4s"/></g><path class="ez1jilb9t"/><path fill="url(#i1VA1ZH)" class="hqp65gs-a"/><path class="y8g2vgb8m"/><g filter="url(#i0LPeIb)"><path fill="url(#iHIsHhb)" class="jml85nb4v"/></g><g filter="url(#i9mEeCe)"><ellipse transform="rotate(-27.914 13.053 9.908)" class="l0xz9pthr"/><ellipse fill="url(#iUWylnb)" transform="rotate(-27.914 13.053 9.908)" class="wi9ka9bfh"/></g><g filter="url(#iIJrKVd)"><path stroke="url(#i6TTeie)" class="a9ri8tzeo"/></g><g filter="url(#ihwwpPb)"><path stroke="url(#ibk1OAd)" class="vbj3pvbnr"/></g><g filter="url(#iqDSiyu)"><path stroke="url(#i4uV60c)" class="n344e-04q"/></g><g filter="url(#ibpqfmb)"><path fill="url(#iZxBgNd)" class="xkedue0pq"/><path fill="url(#iGWbOId)" class="xkedue0pq"/></g><path fill="url(#ifxOE4l)" class="h3f4ebbvn"/><path fill="url(#iM2brsc)" class="h3f4ebbvn"/><path fill="url(#i5Zc5kc)" class="h3f4ebbvn"/><defs><radialGradient id="iShjP1d" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.875 -3.65625 0 22.888 23.114)" gradientUnits="userSpaceOnUse"><stop class="qs5b04nop"/><stop offset="1" class="njrkhhlfe"/></radialGradient><radialGradient id="iJCZuse" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 0 0 7.0625 8.295 21.458)" gradientUnits="userSpaceOnUse"><stop class="fx84vub6z"/><stop offset="1" class="z6io75bpj"/></radialGradient><radialGradient id="i1tMb2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.71875 13.6527 0 15.595 21.349)" gradientUnits="userSpaceOnUse"><stop class="xxaet9bhw"/><stop offset="1" class="zvl8nq86d"/></radialGradient><radialGradient id="iQ1bxFb" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.9375 -7.54205 0 15.587 16.895)" gradientUnits="userSpaceOnUse"><stop offset=".932" class="uzp4m_b3p"/><stop offset=".995" class="alc11rbtu"/></radialGradient><radialGradient id="iM2KgFb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.88284 4.0234 -5.54695 -8.11053 15.17 15.552)" gradientUnits="userSpaceOnUse"><stop offset=".928" class="cxkgc8uxn"/><stop offset="1" class="pnxjkfbgy"/></radialGradient><radialGradient id="iAxLMnM" cx="0" cy="0" r="1" gradientTransform="matrix(6.76566 4.60934 -6.35476 9.32761 14.92 15.317)" gradientUnits="userSpaceOnUse"><stop offset=".933" class="cxkgc8uxn"/><stop offset="1" class="e8o_wr2lc"/></radialGradient><radialGradient id="i3relic" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.0625 10.6454 0 15.587 23.614)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="nxet2htkz"/><stop offset="1" class="e7yn8_bej"/></radialGradient><radialGradient id="iCbDZjb" cx="0" cy="0" r="1" gradientTransform="rotate(85.281 -.567 15.525)scale(4.21461 7.75523)" gradientUnits="userSpaceOnUse"><stop offset=".316" class="w7sh5cjwf"/><stop offset="1" class="ddl9sxmqm"/></radialGradient><radialGradient id="iVmefXb" cx="0" cy="0" r="1" gradientTransform="rotate(-163.355 9.974 7.646)scale(1.58191 3.34381)" gradientUnits="userSpaceOnUse"><stop class="sqvts9xow"/><stop offset="1" class="pgbc5zcxn"/></radialGradient><radialGradient id="inS6Nib" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.33473 .18031 0 24.162 11.668)" gradientUnits="userSpaceOnUse"><stop class="ojstgxewy"/><stop offset="1" class="hom78lxtr"/></radialGradient><radialGradient id="iO36YQc" cx="0" cy="0" r="1" gradientTransform="matrix(-.81259 1.10067 -.98646 -.72826 24.42 12.04)" gradientUnits="userSpaceOnUse"><stop class="all-5ubma"/><stop offset=".661" class="fi917n10w"/></radialGradient><radialGradient id="iHBAZZb" cx="0" cy="0" r="1" gradientTransform="matrix(.79636 -.08984 .10538 .93405 23.082 12.43)" gradientUnits="userSpaceOnUse"><stop offset=".087" class="xlrmucced"/><stop offset="1" class="ezx8m4rog"/></radialGradient><radialGradient id="i4WF3xe" cx="0" cy="0" r="1" gradientTransform="rotate(169.33 11.905 8.518)scale(1.11532 5.56401)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="iylIXxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39844 -1.38177 0 23.92 13.106)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="jjb6zku7x"/><stop offset="1" class="dm9f9lb7m"/></radialGradient><radialGradient id="ibc2wNd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.3125 2.89043 0 23.92 16.895)" gradientUnits="userSpaceOnUse"><stop offset=".422" class="irf74zkjs"/><stop offset="1" class="codehtz3g"/></radialGradient><radialGradient id="iJNu79c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.3734 4.36464 0 4.592 29.995)" gradientUnits="userSpaceOnUse"><stop class="yihcw4vuy"/><stop offset=".441" class="kszwqub4g"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="i8j7end" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5202 .82413 0 8.357 29.995)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="iidxf0E" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88274 -10.19308 2.86286 -.5288 24.699 29.995)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="igo2Rrd" cx="0" cy="0" r="1" gradientTransform="matrix(.5437 12.03342 -.70276 .03175 22.647 23.157)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="i25Qfpc" cx="0" cy="0" r="1" gradientTransform="matrix(1.76689 0 0 3.09207 9.065 10.691)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="ij8e3Yc" cx="0" cy="0" r="1" gradientTransform="matrix(.83237 -.6061 .69177 .95004 20.699 10.425)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="iYgu48c" cx="0" cy="0" r="1" gradientTransform="matrix(.82689 -1.52088 .89018 .48398 20.282 11.518)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="i4fi1yc" cx="0" cy="0" r="1" gradientTransform="matrix(.26107 .25841 -.33313 .33655 20.324 10.69)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="iNiFXcc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.76296 -9.18035 0 15.222 10.491)" gradientUnits="userSpaceOnUse"><stop offset=".495" class="l-e1wbf9v"/><stop offset="1" class="i5c5eto6f"/><stop offset="1" class="a6jgqk_tr"/></radialGradient><radialGradient id="igvjBJk" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31603 1.61973 0 17.888 9.411)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="iP4vjTc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.40039 1.74152 0 13.299 9.377)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="i7zHkrd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.15555 -13.19 0 15.555 5.028)" gradientUnits="userSpaceOnUse"><stop offset=".389" class="kw7d_d-jx"/><stop offset="1" class="lkwevabgz"/></radialGradient><radialGradient id="iTUsIqd" cx="0" cy="0" r="1" gradientTransform="matrix(.80328 -2.97688 1.10392 .29788 19.901 6.557)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="ibTK6Dc" cx="0" cy="0" r="1" gradientTransform="matrix(3.85104 .3544 -.19056 2.07068 18.248 4.785)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="iY0X0ue" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.69068 -2.61838 0 15.526 2.031)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="ieBKeRc" cx="0" cy="0" r="1" gradientTransform="matrix(3.095 -2.2681 3.55336 4.84885 9.033 8.896)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="igukR7m" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19825 -.63693 0 15.855 12.309)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="ia0bFpc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81669 -1.29903 0 17.72 10.005)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iW3WRAd" cx="0" cy="0" r="1" gradientTransform="matrix(-.23318 -.30049 .4137 -.32104 17.49 10.09)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i1VA1ZH" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81673 -1.2991 0 13.327 10.005)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iUWylnb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00778 -.49678 .59715 -.00935 13.038 10.225)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iZxBgNd" cx="0" cy="0" r="1" gradientTransform="matrix(-.66315 -3.60046 3.96832 -.7309 18.07 5.905)" gradientUnits="userSpaceOnUse"><stop offset=".11" class="l382wkm5r"/><stop offset="1" class="ym5q1xkkz"/></radialGradient><radialGradient id="iGWbOId" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.99254 -7.09028 0 15.49 2.866)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="vnszicyas"/><stop offset="1" class="j-b5ok87h"/></radialGradient><radialGradient id="iM2brsc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -12.6875 0 21.326 2.396)" gradientUnits="userSpaceOnUse"><stop class="g_-uv52uc"/><stop offset=".867" class="wntqft2su"/></radialGradient><radialGradient id="i5Zc5kc" cx="0" cy="0" r="1" gradientTransform="matrix(7.75 0 0 .875 6.357 3.02)" gradientUnits="userSpaceOnUse"><stop class="it16sbc4j"/><stop offset=".935" class="uo2hv248r"/></radialGradient><linearGradient id="iSsq4dd" x1="23.277" x2="24.463" y1="8.942" y2="8.942" gradientUnits="userSpaceOnUse"><stop class="pk_j5sfiy"/><stop offset="1" class="bqq6maclp"/></linearGradient><linearGradient id="icQ715d" x1="24.523" x2="24.523" y1="3.708" y2="11.476" gradientUnits="userSpaceOnUse"><stop class="r2v6fvpbl"/><stop offset="1" class="k3o8k1bzw"/></linearGradient><linearGradient id="iBM5Yeb" x1="25.071" x2="22.752" y1="14.806" y2="14.806" gradientUnits="userSpaceOnUse"><stop class="clg68gimn"/><stop offset=".897" class="p-vpa1ykp"/></linearGradient><linearGradient id="iYfj3Fe" x1="22.87" x2="23.745" y1="14.485" y2="14.665" gradientUnits="userSpaceOnUse"><stop class="ud98q8dic"/><stop offset="1" class="yn026ikmt"/></linearGradient><linearGradient id="iCsBhuc" x1="8.501" x2="8.076" y1="28.064" y2="28.064" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="i6KZEte" x1="15.587" x2="15.587" y1="29.864" y2="23.431" gradientUnits="userSpaceOnUse"><stop class="gq6-o1bwg"/><stop offset="1" class="uuiv6bbmv"/></linearGradient><linearGradient id="igUsG4c" x1="12.539" x2="13.11" y1="4.446" y2="5.783" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient><linearGradient id="iAX7Bjc" x1="10.746" x2="10.101" y1="10.972" y2="10.972" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="iHnqmce" x1="21.418" x2="20.594" y1="9.592" y2="12.146" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="ir3lCOd" x1="19.59" x2="11.9" y1="11.084" y2="12.229" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="iKRx5Ib" x1="10.093" x2="11.988" y1="13.798" y2="13.73" gradientUnits="userSpaceOnUse"><stop class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="iYVOxQe" x1="16.128" x2="27.155" y1="8.325" y2="4.615" gradientUnits="userSpaceOnUse"><stop offset=".222" class="t60jvjb2i"/><stop offset="1" class="bz5_mab4l"/></linearGradient><linearGradient id="iD4Pyse" x1="14.656" x2="15.601" y1="11.747" y2="11.747" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="icgRlve" x1="16.471" x2="15.438" y1="12.072" y2="12.057" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="icWvbCd" x1="15.722" x2="15.722" y1="12.819" y2="12.242" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="iZc0h7c" x1="15.653" x2="15.653" y1="12.861" y2="12.693" gradientUnits="userSpaceOnUse"><stop class="zoxadnjxe"/><stop offset="1" class="gnvm67mtb"/></linearGradient><linearGradient id="ifIjyMC" x1="14.482" x2="14.92" y1="14.445" y2="13.753" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="ihV0jYc" x1="18.502" x2="18.187" y1="10.059" y2="10.253" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iHIsHhb" x1="14.075" x2="13.76" y1="10.059" y2="10.253" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i6TTeie" x1="18.519" x2="18.096" y1="7.904" y2="7.04" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="ibk1OAd" x1="13.178" x2="11.98" y1="7.776" y2="7.274" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="i4uV60c" x1="10.832" x2="10.832" y1="5.747" y2="7.919" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><linearGradient id="ifxOE4l" x1="17.357" x2="16.076" y1="3.958" y2="-.417" gradientUnits="userSpaceOnUse"><stop class="i2fz9bb0r"/><stop offset="1" class="xp7dwurxx"/></linearGradient><filter id="i5Rrpbb" width="5.32" height="9.565" x="12.913" y="9.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1584" stdDeviation=".2"/></filter><filter id="if3qUnc" width=".65" height="8.268" x="23.698" y="3.458" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1584" stdDeviation=".125"/></filter><filter id="izIFZMc" width="8.964" height="6.734" x="11.105" y="23.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1584" stdDeviation=".075"/></filter><filter id="iBJtsIe" width="1.172" height="2.394" x="12.239" y="3.786" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1584" stdDeviation=".125"/></filter><filter id="i9fHehc" width="3.562" height="3.362" x="9.065" y="9.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1584"/></filter><filter id="iCDmxke" width="3.004" height="3.003" x="9.244" y="9.189" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1584" stdDeviation=".25"/></filter><filter id="icvVhHe" width="3.612" height="3.612" x="18.643" y="8.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1584"/></filter><filter id="igXDT2c" width="3.004" height="3.003" x="18.822" y="9.189" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1584" stdDeviation=".25"/></filter><filter id="iI8VXFt" width="10.445" height="12.21" x="10.333" y="5.028" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1584"/></filter><filter id="irm0ntD" width="8.275" height="7.088" x="13.697" y="3.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1584" stdDeviation="1"/></filter><filter id="i8WLpTd" width="12.688" height="8.599" x="9.182" y="1.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1584"/></filter><filter id="iRTqSLe" width="3.272" height="4.2" x="13.649" y="9.534" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1584" stdDeviation=".375"/></filter><filter id="iea90mb" width="2.39" height="3.2" x="14.331" y="9.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1584" stdDeviation=".125"/></filter><filter id="i8Mudud" width="2.998" height="1.883" x="16.716" y="7.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1584"/></filter><filter id="iIgkm1O" width="2.999" height="1.883" x="11.533" y="7.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1584"/></filter><filter id="iNX7lIb" width=".79" height=".699" x="16.981" y="9.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1584" stdDeviation=".05"/></filter><filter id="irgnKsc" width=".894" height=".916" x="17.828" y="9.639" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1584" stdDeviation=".1"/></filter><filter id="i0LPeIb" width=".99" height="1.044" x="13.355" y="9.575" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1584" stdDeviation=".1"/></filter><filter id="i9mEeCe" width=".917" height=".707" x="12.595" y="9.555" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1584" stdDeviation=".05"/></filter><filter id="iIJrKVd" width="2.762" height="1.334" x="16.748" y="7.324" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1584" stdDeviation=".15"/></filter><filter id="ihwwpPb" width="3.04" height="1.591" x="11.393" y="7.288" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1584" stdDeviation=".15"/></filter><filter id="iqDSiyu" width="1.01" height="2.28" x="10.327" y="5.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1584" stdDeviation=".125"/></filter><filter id="ibpqfmb" width="12.197" height="2.993" x="9.422" y="3.096" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.337255 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1584"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-student-dark" /></template>
<style>
.a6jgqk_tr {
  stop-color: var(--svg-color--2f1820, #2F1820);
}

.a9ri8tzeo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M17.198 7.807c.433-.076 1.277-.054 1.862.4");
}

.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.alc11rbtu {
  stop-color: var(--svg-color--342542, #342542);
}

.all-5ubma {
  stop-color: var(--svg-color--686071, #686071);
}

.ax7l12irz {
  d: path("M8.357 29.995V18.21a10.97 10.97 0 0 0-3.765 8.286v3.5z");
}

.bqq6maclp {
  stop-color: var(--svg-color--61546d, #61546D);
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.bz5_mab4l {
  stop-color: var(--svg-color--5e4d4c, #5E4D4C);
  stop-opacity: 0;
}

.cdm_o50ho {
  stop-color: var(--svg-color--533531, #533531);
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

.cxkgc8uxn {
  stop-color: var(--svg-color--6a656f, #6A656F);
  stop-opacity: 0;
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.d8ahkmbec {
  cx: 20.324px;
  cy: 10.691px;
  r: 1.681px;
}

.ddl9sxmqm {
  stop-color: var(--svg-color--1c1026, #1C1026);
  stop-opacity: 0;
}

.dm9f9lb7m {
  stop-color: var(--svg-color--eba429, #EBA429);
  stop-opacity: 0;
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.e_tdnmb5p {
  d: path("m23.066 13.605l-.516 2.238a.45.45 0 0 0 .444.552h1.863a.45.45 0 0 0 .431-.557l-.542-2.24a.5.5 0 0 0-.486-.38h-.707a.5.5 0 0 0-.487.387");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e7yn8_bej {
  stop-color: var(--svg-color--57525d, #57525D);
}

.e8o_wr2lc {
  stop-color: var(--svg-color--615b67, #615B67);
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.ebol5nf6u {
  stop-color: var(--svg-color--4f445b, #4F445B);
  stop-opacity: 0;
}

.ez1jilb9t {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.117 9.25c-.658 0-1.213.454-1.364 1.066a.276.276 0 0 0 .27.343h2.245c.143 0 .257-.13.229-.273a1.41 1.41 0 0 0-1.38-1.136");
}

.ezx8m4rog {
  stop-color: var(--svg-color--685352, #685352);
  stop-opacity: 0;
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.fi917n10w {
  stop-color: var(--svg-color--402a4c, #402A4C);
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fx84vub6z {
  stop-color: var(--svg-color--5d516a, #5D516A);
}

.g_-uv52uc {
  stop-color: var(--svg-color--696070, #696070);
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gnvm67mtb {
  stop-color: var(--svg-color--31171f, #31171F);
  stop-opacity: 0;
}

.gq6-o1bwg {
  stop-color: var(--svg-color--3f3748, #3F3748);
}

.gt7karm9l {
  d: path("M22.608 18.094a.24.24 0 0 0-.06-.29c-1.855-1.602-4.346-2.487-6.953-2.487s-5.113.894-6.97 2.487a.24.24 0 0 0-.06.29c1.275 2.6 3.756 4.614 7.03 4.614c3.273 0 5.73-2.014 7.013-4.614");
}

.h3f4ebbvn {
  d: path("M23.53 3.605H7.56c-.44 0-.8-.36-.8-.8s.36-.8.8-.8h15.96c.44 0 .8.36.8.8c.01.44-.35.8-.79.8");
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.hom78lxtr {
  stop-color: var(--svg-color--70635d, #70635D);
  stop-opacity: 0;
}

.hqjsggb6l {
  d: path("m10.391 10.074l.05.002s-.054-.86-.108-1.45c0-.268.108-.59.324-.752l.162-.16c.27-.216.378-.538.378-.86v-.86c0-.268.162-.482.432-.536c.648-.161 1.998-.43 3.942-.43s3.295.269 3.943.43c.216.054.432.268.432.537v.86c0 .321.162.643.378.858c.505.355.474.55.432.967c-.054.537-.108 1.45-.108 1.45h.018l-.268 3.985c-.161 1.782-1.562 3.024-3.232 3.024h-3.232c-1.724 0-3.071-1.242-3.233-3.024z");
}

.hqp65gs-a {
  d: path("M13.325 9.524a.898.898 0 0 0-.866 1.136h1.736a1 1 0 0 0 .032-.237a.905.905 0 0 0-.902-.899");
}

.huv6ahl7x {
  d: path("M24.32 11.668V2.805h-.8v8.863z");
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i03ojmbde {
  d: path("M19.227 23.771c0-.188.155-.34.346-.34s.346.152.346.34v6.093h-.692z");
}

.i2fz9bb0r {
  stop-color: var(--svg-color--3d294b, #3D294B);
}

.i5c5eto6f {
  stop-color: var(--svg-color--3d2138, #3D2138);
}

.i7ocd2bwe {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.155 13.468a3 3 0 0 0 1.371.325a2.96 2.96 0 0 0 1.372-.325a.204.204 0 0 1 .242.04a.19.19 0 0 1 .021.242m-3.007-.282l2.966.254m-2.966-.254a.204.204 0 0 0-.243.041a.19.19 0 0 0-.02.241m.264-.282l-.223.254m3.23.028l-.042-.028m.041.028l-.041-.028m.041.028c-.346.524-.949.874-1.635.874s-1.29-.35-1.635-.874m3.229-.028a1.9 1.9 0 0 1-1.594.852c-.67 0-1.257-.34-1.594-.852m-.041.028l.041-.028m-.041.028l.041-.028");
}

.ibw3dsbln {
  cx: 10.746px;
  cy: 10.691px;
  r: 1.002px;
}

.ifaqb7_nl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.539 4.085c.024.256.246 1.214.571 1.795");
}

.iol43dbmc {
  stroke: var(--svg-color--1f0f21, #1F0F21);
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M15.293 18.865c.063.043.17.08.28.084a.56.56 0 0 0 .28-.084c1.017-.696 1.78-1.39 1.78-2.587v-3.633c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.633c0 1.198.763 1.891 1.78 2.587Z");
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.irf74zkjs {
  stop-color: var(--svg-color--a16739, #A16739);
}

.is8j1620z {
  fill: var(--svg-color--332024, #332024);
  d: path("m15.249 10.568l-.826 1.711c-.103.352.143.704.491.704h.743c.348 0 .593-.357.491-.704l-.502-1.711c-.107-.38-.285-.38-.397 0");
}

.it16sbc4j {
  stop-color: var(--svg-color--75707b, #75707B);
}

.j-b5ok87h {
  stop-color: var(--svg-color--160c20, #160C20);
  stop-opacity: 0;
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
}

.jjb6zku7x {
  stop-color: var(--svg-color--845d03, #845D03);
}

.jml85nb4v {
  d: path("M14.145 10.317c0-.29-.236-.484-.3-.542l-.29.28l.179.364z");
}

.jx0xfzb3o {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.655 9.715c.064.085-.07.19-.222.303c-.152.114-.264.193-.328.108s.007-.247.16-.36c.151-.114.326-.137.39-.051");
}

.k3o8k1bzw {
  stop-color: var(--svg-color--504b55, #504B55);
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.kszwqub4g {
  stop-color: var(--svg-color--58496a, #58496A);
}

.ktr6gcbdt {
  d: path("M17.655 9.715c.064.085-.07.19-.222.303c-.152.114-.264.193-.328.108s.007-.247.16-.36c.151-.114.326-.137.39-.051");
}

.kw7d_d-jx {
  stop-color: var(--svg-color--291418, #291418);
}

.l-e1wbf9v {
  stop-color: var(--svg-color--2f1820, #2F1820);
  stop-opacity: 0;
}

.l0xz9pthr {
  cx: 13.053px;
  cy: 9.908px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.392px;
  ry: 0.198px;
}

.l382wkm5r {
  stop-color: var(--svg-color--595260, #595260);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkwevabgz {
  stop-color: var(--svg-color--291418, #291418);
  stop-opacity: 0;
}

.lofln44ah {
  d: path("M15.592 15.495c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n344e-04q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.962 5.847v.903c-.008.15-.07.485-.26.626");
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.n8kkam5mt {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m11.727 7.953l.001-.002l.002-.001l.005-.004l.012-.01a2 2 0 0 1 .156-.108c.1-.062.242-.14.422-.212a2.85 2.85 0 0 1 1.503-.16a.537.537 0 0 1-.167 1.062a1.77 1.77 0 0 0-.94.098a1.5 1.5 0 0 0-.311.166a.537.537 0 0 1-.683-.83");
}

.nbjen9ayx {
  d: path("M23.52 11.644a.838.838 0 1 0 .8 0z");
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.njrkhhlfe {
  stop-color: var(--svg-color--70647f, #70647F);
  stop-opacity: 0;
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.nxet2htkz {
  stop-color: var(--svg-color--57525d, #57525D);
  stop-opacity: 0;
}

.o-57_ub3b {
  d: path("M17.722 9.524a.898.898 0 0 1 .866 1.136h-1.736a.902.902 0 0 1 .87-1.135");
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o2uld0acg {
  stop-color: var(--svg-color--433850, #433850);
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojstgxewy {
  stop-color: var(--svg-color--70635d, #70635D);
}

.ovbc_0adl {
  d: path("m20.378 4.17l.432.214c.756.376 1.188 1.235 1.026 2.148l-.594 3.06c-.053.317-.262.53-.576.538h-.018s.054-.913.108-1.45c.044-.436-.032-.57-.432-.967c-.216-.214-.378-.537-.378-.859v-.859c0-.268-.216-.483-.432-.537c-.648-.161-1.998-.43-3.943-.43c-1.944 0-3.294.269-3.942.43a.524.524 0 0 0-.432.537v.86c0 .321-.108.644-.378.858l-.162.162c-.216.16-.324.483-.324.751c.054.591.108 1.45.108 1.45l-.05-.002a.64.64 0 0 1-.598-.535l-.594-3.06c-.108-.86.324-1.719 1.08-2.095l.432-.215c.27-.16.54-.376.81-.59l.972-1.02c.594-.538 1.458-.699 2.214-.323a2.96 2.96 0 0 0 1.674 0c.81-.268 1.729-.054 2.377.537l.81.806c.216.268.486.43.81.59");
}

.p-vpa1ykp {
  stop-color: var(--svg-color--faac28, #FAAC28);
}

.p0bhhfiuk {
  fill: var(--svg-color--21181b, #21181B);
  d: path("m20.378 4.17l.432.214c.756.376 1.188 1.235 1.026 2.148l-.594 3.06c-.053.317-.262.53-.576.538h-.018s.054-.913.108-1.45c.044-.436-.032-.57-.432-.967c-.216-.214-.378-.537-.378-.859v-.859c0-.268-.216-.483-.432-.537c-.648-.161-1.998-.43-3.943-.43c-1.944 0-3.294.269-3.942.43a.524.524 0 0 0-.432.537v.86c0 .321-.108.644-.378.858l-.162.162c-.216.16-.324.483-.324.751c.054.591.108 1.45.108 1.45l-.05-.002a.64.64 0 0 1-.598-.535l-.594-3.06c-.108-.86.324-1.719 1.08-2.095l.432-.215c.27-.16.54-.376.81-.59l.972-1.02c.594-.538 1.458-.699 2.214-.323a2.96 2.96 0 0 0 1.674 0c.81-.268 1.729-.054 2.377.537l.81.806c.216.268.486.43.81.59");
}

.p5y0jzbpk {
  cx: 20.324px;
  cy: 10.691px;
  r: 1.002px;
  fill: var(--svg-color--463133, #463133);
}

.pgbc5zcxn {
  stop-color: var(--svg-color--2e181b, #2E181B);
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

.pts6vr7ld {
  stop-color: var(--svg-color--433850, #433850);
  stop-opacity: 0;
}

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.q3rw-m17o {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m15.141 10.404l-.535 1.711a.543.543 0 0 0 .524.704h.792a.545.545 0 0 0 .524-.704l-.535-1.711c-.115-.38-.65-.38-.77 0");
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qs5b04nop {
  stop-color: var(--svg-color--70647f, #70647F);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qzpxx2zfo {
  d: path("M15.293 18.865c.063.043.17.08.28.084a.56.56 0 0 0 .28-.084c1.017-.696 1.78-1.39 1.78-2.587v-3.633c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.633c0 1.198.763 1.891 1.78 2.587");
}

.r2v6fvpbl {
  stop-color: var(--svg-color--60546c, #60546C);
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.rortc5hfq {
  d: path("m19.517 5.636l-3.099 1.033a1.054 1.054 0 0 0 .474 2.045l3.08-.412z");
}

.rsym7yjli {
  d: path("m15.141 10.404l-.535 1.711a.543.543 0 0 0 .524.704h.792a.545.545 0 0 0 .524-.704l-.535-1.711c-.115-.38-.65-.38-.77 0");
}

.rtoowqb1c {
  cx: 10.746px;
  cy: 10.691px;
  r: 1.681px;
}

.sqvts9xow {
  stop-color: var(--svg-color--432c2b, #432C2B);
}

.t-4dqr8wd {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M24.023 3.709v7.767");
}

.t60jvjb2i {
  stop-color: var(--svg-color--5e4d4c, #5E4D4C);
}

.t8woa55ub {
  d: path("M22.816 29.995V18.21a10.97 10.97 0 0 1 3.766 8.286v3.5z");
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.tdspomboy {
  fill: var(--svg-color--56436b, #56436B);
  d: path("M15.592 15.495c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.u8mt89bic {
  d: path("M15.241 23.771c0-.188.155-.34.346-.34s.345.152.345.34v6.093h-.691z");
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.ud98q8dic {
  stop-color: var(--svg-color--c57e10, #C57E10);
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.uo2hv248r {
  stop-color: var(--svg-color--75707b, #75707B);
  stop-opacity: 0;
}

.uuiv6bbmv {
  stop-color: var(--svg-color--3f3748, #3F3748);
  stop-opacity: 0;
}

.uzp4m_b3p {
  stop-color: var(--svg-color--342542, #342542);
  stop-opacity: 0;
}

.vbj3pvbnr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M11.943 8.33c.33-.292 1.048-.598 1.94-.456");
}

.vbz233bhb {
  d: path("M11.255 23.771c0-.188.154-.34.345-.34s.346.152.346.34v6.093h-.691z");
}

.vnszicyas {
  stop-color: var(--svg-color--160c20, #160C20);
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.w_89ngnqd {
  cx: 20.324px;
  cy: 10.691px;
  r: 1.002px;
}

.w_qp_xmzd {
  fill: var(--svg-color--000, #000);
  d: path("M17.207 10.423c0-.286.23-.515.515-.515a.512.512 0 0 1 .457.752h-.91a.47.47 0 0 1-.062-.237");
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w7sh5cjwf {
  stop-color: var(--svg-color--1c1026, #1C1026);
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.wf9jlob4s {
  d: path("M18.522 10.304a.84.84 0 0 0-.233-.465l-.261.287l.117.23z");
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wi9ka9bfh {
  cx: 13.053px;
  cy: 9.908px;
  rx: 0.392px;
  ry: 0.198px;
}

.wntqft2su {
  stop-color: var(--svg-color--696070, #696070);
  stop-opacity: 0;
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.xkedue0pq {
  d: path("m9.422 5.208l1.185-1.953l9.75-.11l1.262 2.019c-4.664 1.61-10.107.778-12.197.044");
}

.xlrmucced {
  stop-color: var(--svg-color--685352, #685352);
}

.xp7dwurxx {
  stop-color: var(--svg-color--433a4d, #433A4D);
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.xxaet9bhw {
  stop-color: var(--svg-color--47404d, #47404D);
}

.y8g2vgb8m {
  fill: var(--svg-color--000, #000);
  d: path("M13.84 10.423a.51.51 0 0 0-.515-.515a.512.512 0 0 0-.457.752h.91a.5.5 0 0 0 .061-.237");
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
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

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.yxoweybto {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M19.271 7.952h-.001l-.002-.002l-.005-.004l-.012-.01a2 2 0 0 0-.156-.108a2.6 2.6 0 0 0-.422-.212a2.85 2.85 0 0 0-1.503-.16a.537.537 0 0 0 .167 1.062c.401-.063.722.011.94.098a1.5 1.5 0 0 1 .311.166a.537.537 0 0 0 .683-.83");
}

.z_nasnbnz {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.93 9.251c.657 0 1.213.453 1.364 1.066a.276.276 0 0 1-.27.343H16.78a.232.232 0 0 1-.23-.274a1.41 1.41 0 0 1 1.381-1.135");
}

.z6io75bpj {
  stop-color: var(--svg-color--5d516a, #5D516A);
  stop-opacity: 0;
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zoxadnjxe {
  stop-color: var(--svg-color--31171f, #31171F);
}

.zvl8nq86d {
  stop-color: var(--svg-color--3b2d3a, #3B2D3A);
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
