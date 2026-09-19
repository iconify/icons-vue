<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iHtPXGe)"><path fill="url(#iOF8mTc)" clip-rule="evenodd" class="ofew38o4j"/><path fill="url(#isU8JEH)" clip-rule="evenodd" class="ofew38o4j"/><path fill="url(#ie64lDc)" clip-rule="evenodd" class="ofew38o4j"/><path fill="url(#iaU479d)" clip-rule="evenodd" class="ofew38o4j"/><path fill="url(#iXNLStj)" clip-rule="evenodd" class="ofew38o4j"/><path fill="url(#iNAg7He)" clip-rule="evenodd" class="ofew38o4j"/><path fill="url(#ijqKEHc)" clip-rule="evenodd" class="ofew38o4j"/><path fill="url(#ioOQsMc)" clip-rule="evenodd" class="ofew38o4j"/><path fill="url(#inFg2hb)" clip-rule="evenodd" class="ofew38o4j"/><path fill="url(#i2WiCIb)" clip-rule="evenodd" class="ofew38o4j"/><path fill="url(#iq8PG9b)" clip-rule="evenodd" class="ofew38o4j"/></g><path class="wd1nojbmw"/><path fill="url(#iTmwjtc)" class="wx9hitk-a"/><path fill="url(#iUaQ1bE)" class="wx9hitk-a"/><path fill="url(#ikWcU9d)" class="q9pn2c2pp"/><path fill="url(#iqG556F)" class="q9pn2c2pp"/><path fill="url(#izaMMOb)" class="q9pn2c2pp"/><path fill="url(#iK7nXqd)" class="q9pn2c2pp"/><path fill="url(#iaTNpjc)" class="q9pn2c2pp"/><path fill="url(#ioMwWRX)" class="q9pn2c2pp"/><path fill="url(#ik958po)" class="uxkj8zbvq"/><path fill="url(#iqqUGHc)" class="ixey29z3v"/><path fill="url(#ieboXJV)" class="ixey29z3v"/><path fill="url(#iaE4Qzb)" class="amgml5b7z"/><path fill="url(#iK9hqsQ)" class="amgml5b7z"/><g filter="url(#iK9oyBR)"><path stroke="url(#iEJEnzb)" class="tslki-kuz"/></g><path fill="url(#iGp7ZBe)" class="fq_0q_bkd"/><path fill="url(#i9JGCKc)" class="fq_0q_bkd"/><path fill="url(#ivZ1t2d)" class="fq_0q_bkd"/><path fill="url(#ifMMs0D)" class="fq_0q_bkd"/><path fill="url(#ikNuOAe)" class="fq_0q_bkd"/><path fill="url(#iivadGb)" class="xs166rhme"/><path fill="url(#iiJps4k)" class="xs166rhme"/><path fill="url(#iUGe4Dt)" class="xs166rhme"/><path fill="url(#iUDJpnd)" class="jmnxccc1f"/><path fill="url(#iOEOGUR)" class="jmnxccc1f"/><g filter="url(#i6Zklnd)"><path fill="url(#i77AYhe)" class="p8zuh31xg"/><path fill="url(#i77AYhe)" class="fss96wb2l"/><path fill="url(#i77AYhe)" class="ydajvlb5g"/></g><g filter="url(#io5YCEc)"><path fill="url(#igQeIme)" class="nxnd1ibet"/></g><g filter="url(#iK9vidd)"><path fill="url(#i99tfDc)" class="r4jd8ka-r"/></g><g filter="url(#iBWxVMh)"><path class="hpnxp2cle"/><path fill="url(#iBMMfrb)" class="hemoeqr9g"/></g><g filter="url(#iWbzPXd)"><path class="qilq-wckb"/><path fill="url(#idEF2Ku)" class="ooaytekqc"/></g><g filter="url(#imKCZIe)"><path fill="url(#iDEXe1c)" class="aip85hkmt"/><path fill="url(#i0v3Spb)" class="aip85hkmt"/><path fill="url(#iw1hdTd)" class="aip85hkmt"/><path fill="url(#i1tob1M)" class="aip85hkmt"/><path fill="url(#iAapLPz)" class="aip85hkmt"/><path fill="url(#irzIKId)" class="aip85hkmt"/><path fill="url(#iQkrhsX)" class="aip85hkmt"/></g><path fill="url(#idHDo9b)" class="aip85hkmt"/><path fill="url(#ieKnjXd)" class="aip85hkmt"/><g filter="url(#ivm9SSu)"><path class="xo-fpccvi"/></g><g filter="url(#i9mxxke)"><path fill="url(#iuBe9Rp)" class="l9zd-2bfp"/><path fill="url(#iyRmPqe)" class="l9zd-2bfp"/><path fill="url(#ieFJBYo)" class="l9zd-2bfp"/><path fill="url(#iUAJDhe)" class="l9zd-2bfp"/></g><path fill="url(#iXHrAge)" class="l9zd-2bfp"/><path fill="url(#iQqo8Ub)" class="l9zd-2bfp"/><path stroke="url(#it5GrVb)" class="bc76d05co"/><g filter="url(#igaKM3c)"><path class="msusf1bgx"/></g><g filter="url(#iZKJACd)"><path class="lzdx5rcqp"/></g><g filter="url(#i81egse)"><path class="txssswzwf"/></g><g filter="url(#ickGSnO)"><path clip-rule="evenodd" class="jb3o0db-v"/></g><path class="tsugr2bel"/><path fill="url(#iLadMYc)" class="lno-4xb0k"/><path class="g635plbpw"/><g filter="url(#iGsZOMb)"><path class="t3u7ugodp"/><path fill="url(#ikWDZod)" class="wgs8pcw7o"/></g><g filter="url(#ieB0aae)"><path fill="url(#ipRLdsc)" class="m1288m2fn"/></g><path class="q0yj0-b_g"/><path fill="url(#iwrRfzP)" class="cdy57vbcp"/><path class="p40r72cdo"/><g filter="url(#iBCZRNb)"><path fill="url(#iXQGYgd)" class="x9irakh7s"/></g><g filter="url(#i54SAyc)"><ellipse transform="rotate(-27.914 13.416 10.219)" class="vz7481bzf"/><ellipse fill="url(#inhMrbb)" transform="rotate(-27.914 13.416 10.219)" class="apaluibxx"/></g><g filter="url(#i0ac1Ob)"><path class="jbclcibzp"/></g><g filter="url(#iuAXeLc)"><path class="pf_fn77-l"/></g><g filter="url(#izyCVue)"><path fill="url(#iVTkvDb)" class="imokeebna"/><path fill="url(#i0a8xtb)" class="imokeebna"/><path fill="url(#iLAvRse)" class="imokeebna"/></g><g filter="url(#i4ofaSc)"><path fill="url(#iFgkwpc)" class="ale3mwb1s"/><path fill="url(#ijHg98c)" class="ale3mwb1s"/><path fill="url(#ibE0j0b)" class="ale3mwb1s"/></g><g filter="url(#iXowNZc)"><path stroke="url(#igwAPvc)" class="p38w1vy6u"/></g><path fill="url(#iPdzXfe)" class="oa5gwac6c"/><path fill="url(#izAokfc)" class="k45a0bb_x"/><path fill="url(#itr2gqb)" class="k45a0bb_x"/><path fill="url(#ijbtOcb)" class="k45a0bb_x"/><defs><radialGradient id="isU8JEH" cx="0" cy="0" r="1" gradientTransform="rotate(28.301 -18.573 46.875)scale(3.34735 4.74136)" gradientUnits="userSpaceOnUse"><stop offset=".616" class="w3-vy4c8j"/><stop offset="1" class="w72oynbwi"/></radialGradient><radialGradient id="ie64lDc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.67693 -2.8177 0 11.194 13.08)" gradientUnits="userSpaceOnUse"><stop class="lcrdwk1fj"/><stop offset="1" class="denqa3bda"/></radialGradient><radialGradient id="iaU479d" cx="0" cy="0" r="1" gradientTransform="scale(6.09031 5.84661)rotate(90 .186 2.44)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="ag6fa4z4y"/><stop offset="1" class="qir_1cb0f"/></radialGradient><radialGradient id="iXNLStj" cx="0" cy="0" r="1" gradientTransform="rotate(127.617 2.644 8.307)scale(2.13331 2.07134)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="ha2cq84sa"/><stop offset="1" class="p4wkjrbae"/></radialGradient><radialGradient id="iNAg7He" cx="0" cy="0" r="1" gradientTransform="rotate(100.537 2.103 9.124)scale(2.68339 2.79425)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="tgqxysbgm"/><stop offset="1" class="p1xq25bjq"/></radialGradient><radialGradient id="ijqKEHc" cx="0" cy="0" r="1" gradientTransform="rotate(62.605 3.425 11.984)scale(2.49876 4.76008)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="esx41hbqq"/><stop offset=".921" class="v9rq5jjti"/></radialGradient><radialGradient id="ioOQsMc" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 9.8 7.244)scale(1.71812 2.40105)" gradientUnits="userSpaceOnUse"><stop class="duwob45dr"/><stop offset="1" class="v61l3jbat"/></radialGradient><radialGradient id="inFg2hb" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 11.22 6.727)scale(2.01509 4.38457)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="hottnizrg"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="i2WiCIb" cx="0" cy="0" r="1" gradientTransform="rotate(-133.315 14.88 4.38)scale(4.89281 7.02664)" gradientUnits="userSpaceOnUse"><stop class="yqk-2gbyp"/><stop offset="1" class="oaxszm67z"/></radialGradient><radialGradient id="iq8PG9b" cx="0" cy="0" r="1" gradientTransform="matrix(-.00885 -1.44236 .4729 -.0029 13.153 6.047)" gradientUnits="userSpaceOnUse"><stop offset=".295" class="sufhn4bec"/><stop offset="1" class="kpf8h5ohf"/></radialGradient><radialGradient id="iTmwjtc" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.875 -3.65625 0 23.307 23.11)" gradientUnits="userSpaceOnUse"><stop class="qs5b04nop"/><stop offset="1" class="njrkhhlfe"/></radialGradient><radialGradient id="iUaQ1bE" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 0 0 7.0625 8.713 21.453)" gradientUnits="userSpaceOnUse"><stop class="fx84vub6z"/><stop offset="1" class="z6io75bpj"/></radialGradient><radialGradient id="ikWcU9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.71875 13.6527 0 16.013 21.344)" gradientUnits="userSpaceOnUse"><stop class="xxaet9bhw"/><stop offset="1" class="zvl8nq86d"/></radialGradient><radialGradient id="iqG556F" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.9375 -7.54205 0 16.005 16.89)" gradientUnits="userSpaceOnUse"><stop offset=".932" class="uzp4m_b3p"/><stop offset=".995" class="alc11rbtu"/></radialGradient><radialGradient id="izaMMOb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.88284 4.0234 -5.54695 -8.11053 15.588 15.547)" gradientUnits="userSpaceOnUse"><stop offset=".928" class="cxkgc8uxn"/><stop offset="1" class="pnxjkfbgy"/></radialGradient><radialGradient id="iK7nXqd" cx="0" cy="0" r="1" gradientTransform="matrix(6.76566 4.60934 -6.35476 9.32761 15.338 15.312)" gradientUnits="userSpaceOnUse"><stop offset=".933" class="cxkgc8uxn"/><stop offset="1" class="e8o_wr2lc"/></radialGradient><radialGradient id="iaTNpjc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.0625 10.6454 0 16.005 23.61)" gradientUnits="userSpaceOnUse"><stop offset=".506" class="nxet2htkz"/><stop offset="1" class="e7yn8_bej"/></radialGradient><radialGradient id="ioMwWRX" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.85937 -5.04205 0 16.005 15.313)" gradientUnits="userSpaceOnUse"><stop offset=".316" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="ik958po" cx="0" cy="0" r="1" gradientTransform="rotate(-163.355 10.182 7.613)scale(1.58191 3.34381)" gradientUnits="userSpaceOnUse"><stop class="zy5hoab9j"/><stop offset="1" class="fdcdqxcao"/></radialGradient><radialGradient id="ieboXJV" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.33473 .18031 0 24.58 11.663)" gradientUnits="userSpaceOnUse"><stop class="ojstgxewy"/><stop offset="1" class="hom78lxtr"/></radialGradient><radialGradient id="iaE4Qzb" cx="0" cy="0" r="1" gradientTransform="matrix(-.81259 1.10067 -.98646 -.72826 24.838 12.034)" gradientUnits="userSpaceOnUse"><stop class="all-5ubma"/><stop offset=".661" class="fi917n10w"/></radialGradient><radialGradient id="iK9hqsQ" cx="0" cy="0" r="1" gradientTransform="matrix(.79636 -.08984 .10538 .93405 23.5 12.426)" gradientUnits="userSpaceOnUse"><stop offset=".087" class="xlrmucced"/><stop offset="1" class="ezx8m4rog"/></radialGradient><radialGradient id="i9JGCKc" cx="0" cy="0" r="1" gradientTransform="rotate(169.33 12.115 8.535)scale(1.11532 5.56401)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="ivZ1t2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39844 -1.38177 0 24.338 13.101)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="jjb6zku7x"/><stop offset="1" class="dm9f9lb7m"/></radialGradient><radialGradient id="ikNuOAe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.3125 2.89043 0 24.338 16.89)" gradientUnits="userSpaceOnUse"><stop offset=".422" class="irf74zkjs"/><stop offset="1" class="codehtz3g"/></radialGradient><radialGradient id="iivadGb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.3734 4.36464 0 5.01 29.99)" gradientUnits="userSpaceOnUse"><stop class="yihcw4vuy"/><stop offset=".441" class="kszwqub4g"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="iiJps4k" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5202 .82413 0 8.775 29.99)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="iUDJpnd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88274 -10.19308 2.86286 -.5288 25.117 29.99)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="iOEOGUR" cx="0" cy="0" r="1" gradientTransform="matrix(.5437 12.03342 -.70276 .03175 23.067 23.151)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="i99tfDc" cx="0" cy="0" r="1" gradientTransform="matrix(2.6122 -1.18736 1.44972 3.18937 20.23 11.407)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="iBMMfrb" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 41.678 -52.532)scale(1.36913)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="idEF2Ku" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12725 0 0 -1.07829 11.094 10.946)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="iDEXe1c" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.357 7.275)scale(7.51607 10.0601)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="m45oyzb-o"/></radialGradient><radialGradient id="i0v3Spb" cx="0" cy="0" r="1" gradientTransform="rotate(152.124 7.614 7.789)scale(2.50476 2.12511)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="iw1hdTd" cx="0" cy="0" r="1" gradientTransform="matrix(.87833 -4.24526 5.38644 1.11444 13.704 17.5)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="i1tob1M" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.83638 -10.6752 0 15.717 9.53)" gradientUnits="userSpaceOnUse"><stop offset=".619" class="arskx5c5m"/><stop offset="1" class="hu7qgofpu"/></radialGradient><radialGradient id="iAapLPz" cx="0" cy="0" r="1" gradientTransform="matrix(-5.69083 1.57372 -2.70946 -9.79787 16.65 12.12)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="irzIKId" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.2077 1.48218 0 18.407 9.943)" gradientUnits="userSpaceOnUse"><stop class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="iQkrhsX" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.42729 1.63577 0 13.978 10.034)" gradientUnits="userSpaceOnUse"><stop class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="idHDo9b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.41359 0 0 -4.65359 21.339 11.504)" gradientUnits="userSpaceOnUse"><stop class="f902gfhfn"/><stop offset="1" class="jh40i5bvl"/></radialGradient><radialGradient id="ieKnjXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.15625 -3.5 0 13.601 5.293)" gradientUnits="userSpaceOnUse"><stop class="i8-khtb0t"/><stop offset="1" class="tzi44uqjw"/></radialGradient><radialGradient id="iyRmPqe" cx="0" cy="0" r="1" gradientTransform="matrix(-.73196 -2.57094 1.47113 -.41884 16.814 12.267)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="iQqo8Ub" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34493 .96068 -1.28676 -1.80144 16.293 11.892)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="e6-lebcyw"/><stop offset="1" class="b8os9sbcy"/></radialGradient><radialGradient id="iLadMYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85145 -1.35433 0 18.281 10.32)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ikWDZod" cx="0" cy="0" r="1" gradientTransform="matrix(-.2432 -.31339 .43147 -.33482 18.042 10.408)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iwrRfzP" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85146 -1.35434 0 13.701 10.32)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="inhMrbb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00811 -.51809 .62275 -.00975 13.401 10.549)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iVTkvDb" cx="0" cy="0" r="1" gradientTransform="rotate(129.554 5.711 4.92)scale(5.63516 2.45766)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="esh4v5qtq"/><stop offset=".911" class="nria2ku7r"/></radialGradient><radialGradient id="i0a8xtb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.25627 2.32628 -1.14968 -1.6093 12.995 4.224)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="dpv-wxbjb"/><stop offset="1" class="abu2lcc5n"/><stop offset="1" class="sxoxd_kke"/></radialGradient><radialGradient id="iFgkwpc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.29346 4.7804 -6.78737 -3.25633 17.871 2.419)" gradientUnits="userSpaceOnUse"><stop offset=".627" class="crfaaqblp"/><stop offset="1" class="ehjghj3fe"/></radialGradient><radialGradient id="ijHg98c" cx="0" cy="0" r="1" gradientTransform="rotate(105.909 7.903 8.896)scale(3.61023 7.5659)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="z-gx2rb2w"/><stop offset="1" class="gbpc14bxe"/></radialGradient><radialGradient id="ibE0j0b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.58586 -6.7874 6.06752 -3.20554 17.198 9.644)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="s3t3owbgt"/><stop offset="1" class="yehxt3bls"/></radialGradient><radialGradient id="iPdzXfe" cx="0" cy="0" r="1" gradientTransform="rotate(-102.428 11.849 -4.481)scale(3.92058 20.9164)" gradientUnits="userSpaceOnUse"><stop class="pok8-dbcp"/><stop offset="1" class="x49zttk2i"/></radialGradient><radialGradient id="itr2gqb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -12.6875 0 21.744 2.39)" gradientUnits="userSpaceOnUse"><stop class="g_-uv52uc"/><stop offset=".867" class="wntqft2su"/></radialGradient><radialGradient id="ijbtOcb" cx="0" cy="0" r="1" gradientTransform="matrix(7.75 0 0 .875 6.775 3.016)" gradientUnits="userSpaceOnUse"><stop class="it16sbc4j"/><stop offset=".935" class="uo2hv248r"/></radialGradient><filter id="iHtPXGe" width="16.011" height="16.261" x="8.111" y="1.496" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.486275 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1580"/></filter><filter id="iK9oyBR" width=".65" height="8.268" x="24.116" y="3.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1580" stdDeviation=".125"/></filter><filter id="i6Zklnd" width="8.964" height="6.734" x="11.523" y="23.276" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1580" stdDeviation=".075"/></filter><filter id="io5YCEc" width="3.477" height="3.377" x="9.385" y="9.257" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.501961 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1580"/></filter><filter id="iK9vidd" width="3.377" height="3.627" x="19.369" y="9.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1580"/></filter><filter id="iBWxVMh" width="3.255" height="3.254" x="19.43" y="9.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1580" stdDeviation=".25"/></filter><filter id="iWbzPXd" width="2.755" height="2.754" x="9.717" y="9.569" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1580" stdDeviation=".125"/></filter><filter id="imKCZIe" width="10.695" height="11.815" x="10.644" y="5.796" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1580"/></filter><filter id="ivm9SSu" width="2.97" height="3.814" x="14.336" y="9.916" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1580" stdDeviation=".25"/></filter><filter id="i9mxxke" width="2.47" height="3.314" x="14.756" y="10.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1580" stdDeviation=".125"/></filter><filter id="igaKM3c" width="3.14" height="1.349" x="16.99" y="9.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1580"/></filter><filter id="iZKJACd" width="3.14" height="1.349" x="11.853" y="9.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1580"/></filter><filter id="i81egse" width="2.564" height="1.135" x="11.995" y="7.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1580"/></filter><filter id="ickGSnO" width="2.564" height="1.135" x="17.68" y="7.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1580"/></filter><filter id="iGsZOMb" width=".815" height=".721" x="17.516" y="9.863" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1580" stdDeviation=".05"/></filter><filter id="ieB0aae" width=".915" height=".938" x="18.402" y="9.946" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1580" stdDeviation=".1"/></filter><filter id="iBCZRNb" width="1.015" height="1.071" x="13.74" y="9.88" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1580" stdDeviation=".1"/></filter><filter id="i54SAyc" width=".948" height=".729" x="12.942" y="9.855" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1580" stdDeviation=".05"/></filter><filter id="i0ac1Ob" width="2.743" height="1.397" x="17.527" y="7.921" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1580" stdDeviation=".2"/></filter><filter id="iuAXeLc" width="2.743" height="1.397" x="11.805" y="7.921" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1580" stdDeviation=".2"/></filter><filter id="izyCVue" width="5.158" height="5.397" x="8.989" y="3.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1580" stdDeviation=".375"/></filter><filter id="i4ofaSc" width="9.83" height="6.542" x="12.272" y="2.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1580" stdDeviation=".25"/></filter><filter id="iXowNZc" width="1.172" height="2.394" x="12.657" y="3.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1580" stdDeviation=".125"/></filter><linearGradient id="iOF8mTc" x1="20.917" x2="13.317" y1="3.65" y2="17.757" gradientUnits="userSpaceOnUse"><stop class="yr1vjkbzu"/><stop offset="1" class="btu9i2bec"/></linearGradient><linearGradient id="iqqUGHc" x1="23.695" x2="24.881" y1="8.936" y2="8.936" gradientUnits="userSpaceOnUse"><stop class="pk_j5sfiy"/><stop offset="1" class="bqq6maclp"/></linearGradient><linearGradient id="iEJEnzb" x1="24.941" x2="24.941" y1="3.704" y2="11.471" gradientUnits="userSpaceOnUse"><stop class="r2v6fvpbl"/><stop offset="1" class="k3o8k1bzw"/></linearGradient><linearGradient id="iGp7ZBe" x1="25.489" x2="23.17" y1="14.801" y2="14.801" gradientUnits="userSpaceOnUse"><stop class="clg68gimn"/><stop offset=".897" class="p-vpa1ykp"/></linearGradient><linearGradient id="ifMMs0D" x1="23.289" x2="24.164" y1="14.48" y2="14.66" gradientUnits="userSpaceOnUse"><stop class="ud98q8dic"/><stop offset="1" class="yn026ikmt"/></linearGradient><linearGradient id="iUGe4Dt" x1="8.92" x2="8.494" y1="28.059" y2="28.059" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="i77AYhe" x1="16.005" x2="16.005" y1="29.859" y2="23.426" gradientUnits="userSpaceOnUse"><stop class="gq6-o1bwg"/><stop offset="1" class="uuiv6bbmv"/></linearGradient><linearGradient id="igQeIme" x1="9.385" x2="12.491" y1="11.037" y2="11.037" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="iuBe9Rp" x1="15.991" x2="15.991" y1="13.085" y2="10.271" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="ieFJBYo" x1="14.893" x2="15.79" y1="12.285" y2="12.395" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="iUAJDhe" x1="15.991" x2="15.991" y1="13.182" y2="12.541" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="iXHrAge" x1="16.073" x2="16.073" y1="13.154" y2="13.008" gradientUnits="userSpaceOnUse"><stop class="b8os9sbcy"/><stop offset="1" class="e6-lebcyw"/></linearGradient><linearGradient id="it5GrVb" x1="15.226" x2="15.701" y1="14.732" y2="13.817" gradientUnits="userSpaceOnUse"><stop class="tpesn5blm"/><stop offset="1" class="umcd3ubyj"/></linearGradient><linearGradient id="ipRLdsc" x1="19.097" x2="18.768" y1="10.376" y2="10.578" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iXQGYgd" x1="14.482" x2="14.152" y1="10.376" y2="10.579" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iLAvRse" x1="12.383" x2="12.008" y1="5.793" y2="6.605" gradientUnits="userSpaceOnUse"><stop offset=".313" class="vdzvc-bry"/><stop offset="1" class="zjei445oy"/></linearGradient><linearGradient id="igwAPvc" x1="12.957" x2="13.529" y1="4.441" y2="5.778" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient><linearGradient id="izAokfc" x1="17.775" x2="16.494" y1="3.953" y2="-.422" gradientUnits="userSpaceOnUse"><stop class="i2fz9bb0r"/><stop offset="1" class="xp7dwurxx"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-student" /></template>
<style>
.a9dfe182j {
  stop-color: var(--svg-color--d4993e, #D4993E);
}

.abu2lcc5n {
  stop-color: var(--svg-color--ffe134, #FFE134);
  stop-opacity: 0;
}

.ag6fa4z4y {
  stop-color: var(--svg-color--e26b25, #E26B25);
}

.aip85hkmt {
  d: path("M10.652 9.62h.013l-.01-.278l-.011-.32c.021-.997.602-1.382.85-1.51l.054-.022q.028-.013.054-.021a2.42 2.42 0 0 0 1.248-1.296l.086-.204a.277.277 0 0 1 .484-.053a4.05 4.05 0 0 0 3.347 1.756h3.38c.189 0 1.136.092 1.192 1.398l-.125 3.225c-.13 2.941-2.426 4.916-5.23 4.916c-2.803 0-5.1-1.975-5.23-4.916z");
}

.alc11rbtu {
  stop-color: var(--svg-color--342542, #342542);
}

.ale3mwb1s {
  d: path("M15.358 2.77c-1.189-.263-2.463 1.003-2.586 1.442c1.619 3.8 4.104 3.438 6.86 3.131c1.651-.183 1.83.57 1.97.933c-.457-4.257-3.535-4.908-6.244-5.506");
}

.all-5ubma {
  stop-color: var(--svg-color--686071, #686071);
}

.amgml5b7z {
  d: path("M23.938 11.64a.837.837 0 1 0 .8 0z");
}

.apaluibxx {
  cx: 13.416px;
  cy: 10.219px;
  rx: 0.409px;
  ry: 0.207px;
}

.arskx5c5m {
  stop-color: var(--svg-color--d39126, #D39126);
  stop-opacity: 0;
}

.b8os9sbcy {
  stop-color: var(--svg-color--e2802f, #E2802F);
}

.bc76d05co {
  fill: var(--svg-color--8a004f, #8A004F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.523 13.596a.21.21 0 0 0-.257.045a.2.2 0 0 0-.021.257a2.078 2.078 0 0 0 3.493 0a.206.206 0 0 0-.022-.26a.21.21 0 0 0-.256-.042a3.1 3.1 0 0 1-1.469.356a3.1 3.1 0 0 1-1.468-.356Z");
}

.bqq6maclp {
  stop-color: var(--svg-color--61546d, #61546D);
}

.btu9i2bec {
  stop-color: var(--svg-color--e37923, #E37923);
}

.cdy57vbcp {
  d: path("M13.7 9.819a.937.937 0 0 0-.903 1.183h1.809a1 1 0 0 0 .034-.247a.943.943 0 0 0-.94-.936");
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

.crfaaqblp {
  stop-color: var(--svg-color--f49523, #F49523);
  stop-opacity: 0;
}

.cxkgc8uxn {
  stop-color: var(--svg-color--6a656f, #6A656F);
  stop-opacity: 0;
}

.denqa3bda {
  stop-color: var(--svg-color--d77117, #D77117);
  stop-opacity: 0;
}

.dm9f9lb7m {
  stop-color: var(--svg-color--eba429, #EBA429);
  stop-opacity: 0;
}

.dpv-wxbjb {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
}

.duwob45dr {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
}

.e0lgwbeaw {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.e6-lebcyw {
  stop-color: var(--svg-color--e2802f, #E2802F);
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

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.ehjghj3fe {
  stop-color: var(--svg-color--f49523, #F49523);
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.esh4v5qtq {
  stop-color: var(--svg-color--ee971b, #EE971B);
  stop-opacity: 0;
}

.esx41hbqq {
  stop-color: var(--svg-color--cba140, #CBA140);
}

.ezx8m4rog {
  stop-color: var(--svg-color--685352, #685352);
  stop-opacity: 0;
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.f902gfhfn {
  stop-color: var(--svg-color--ffda39, #FFDA39);
}

.fdcdqxcao {
  stop-color: var(--svg-color--b57a1d, #B57A1D);
}

.fi917n10w {
  stop-color: var(--svg-color--402a4c, #402A4C);
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.fkdj3ejgt {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
}

.fq_0q_bkd {
  d: path("m23.484 13.6l-.516 2.239a.45.45 0 0 0 .445.55h1.863a.45.45 0 0 0 .43-.556l-.542-2.24a.5.5 0 0 0-.485-.38h-.707a.5.5 0 0 0-.488.387");
}

.fss96wb2l {
  d: path("M15.66 23.766c0-.188.154-.34.345-.34s.346.152.346.34v6.093h-.692z");
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

.g635plbpw {
  fill: var(--svg-color--000, #000);
  d: path("M17.747 10.756c0-.298.238-.537.536-.537a.534.534 0 0 1 .477.784h-.95a.5.5 0 0 1-.063-.247");
}

.gbpc14bxe {
  stop-color: var(--svg-color--ffe337, #FFE337);
  stop-opacity: 0;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gq6-o1bwg {
  stop-color: var(--svg-color--3f3748, #3F3748);
}

.gsggv-b-p {
  stop-color: var(--svg-color--f09429, #F09429);
  stop-opacity: 0;
}

.h11_utkon {
  stop-color: var(--svg-color--b96201, #B96201);
}

.ha2cq84sa {
  stop-color: var(--svg-color--c9681c, #C9681C);
}

.hemoeqr9g {
  d: path("M21.057 12.073a1.127 1.127 0 1 0 0-2.254a1.127 1.127 0 0 0 0 2.254");
}

.hom78lxtr {
  stop-color: var(--svg-color--70635d, #70635D);
  stop-opacity: 0;
}

.hottnizrg {
  stop-color: var(--svg-color--ffd336, #FFD336);
  stop-opacity: 0;
}

.hpnxp2cle {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M21.057 12.073a1.127 1.127 0 1 0 0-2.254a1.127 1.127 0 0 0 0 2.254");
}

.hu7qgofpu {
  stop-color: var(--svg-color--9f6810, #9F6810);
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i2fz9bb0r {
  stop-color: var(--svg-color--3d294b, #3D294B);
}

.i8-khtb0t {
  stop-color: var(--svg-color--d1710b, #D1710B);
}

.imokeebna {
  d: path("M10.855 4.635c.652-.58 1.592-.587 2.12-.493l.422 1.355c-.27-.041-.51.052-.713.246c-.478 1.323-2.122 2.052-2.884 2.251c-.159-1.565-.07-2.357 1.055-3.36");
}

.irf74zkjs {
  stop-color: var(--svg-color--a16739, #A16739);
}

.it16sbc4j {
  stop-color: var(--svg-color--75707b, #75707B);
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.ixey29z3v {
  d: path("M24.738 11.663V2.8h-.8v8.863z");
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.jb3o0db-v {
  fill: var(--svg-color--bd4f26, #BD4F26);
  fill-rule: evenodd;
  d: path("m19.908 8.6l-.145.242za.282.282 0 0 1-.288.483l-.006-.003a1 1 0 0 0-.118-.06a3 3 0 0 0-.36-.142a2.4 2.4 0 0 0-1.125-.097a.281.281 0 0 1-.097-.554c.538-.095 1.037 0 1.394.114a3.4 3.4 0 0 1 .586.25l.01.006l.003.002z");
}

.jbclcibzp {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.027 8.456c.338-.082 1.18-.041 1.743.361");
}

.jh40i5bvl {
  stop-color: var(--svg-color--ffda39, #FFDA39);
  stop-opacity: 0;
}

.jjb6zku7x {
  stop-color: var(--svg-color--845d03, #845D03);
}

.jmnxccc1f {
  d: path("M23.235 29.99V18.204A10.97 10.97 0 0 1 27 26.49v3.5z");
}

.k3o8k1bzw {
  stop-color: var(--svg-color--504b55, #504B55);
}

.k45a0bb_x {
  d: path("M23.948 3.6H7.978c-.44 0-.8-.36-.8-.8s.36-.8.8-.8h15.96c.44 0 .8.36.8.8c.01.44-.35.8-.79.8");
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.kpf8h5ohf {
  stop-color: var(--svg-color--db6009, #DB6009);
  stop-opacity: 0;
}

.kszwqub4g {
  stop-color: var(--svg-color--58496a, #58496A);
}

.l9zd-2bfp {
  d: path("m15.59 10.567l-.558 1.784a.566.566 0 0 0 .547.734h.825c.387 0 .66-.373.546-.734l-.558-1.784c-.119-.395-.677-.395-.802 0");
}

.lcrdwk1fj {
  stop-color: var(--svg-color--c9641b, #C9641B);
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lno-4xb0k {
  d: path("M18.284 9.819a.937.937 0 0 1 .902 1.183h-1.81a.94.94 0 0 1 .907-1.184");
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.lzdx5rcqp {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.793 10.349c-.279-.49-.702-.877-1.613-.877c-.4 0-.784.11-1.126.387c-.283.228-.245.52-.026.629l.583.333c.684-.22 1.44-.25 2.182-.472");
}

.m1288m2fn {
  d: path("M19.117 10.631a.9.9 0 0 0-.243-.485l-.272.3l.123.238z");
}

.m45oyzb-o {
  stop-color: var(--svg-color--eb9235, #EB9235);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.msusf1bgx {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.19 10.349c.278-.49.702-.877 1.613-.877c.4 0 .784.11 1.126.387c.282.228.245.52.026.629l-.583.333c-.685-.22-1.441-.25-2.182-.472");
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.njrkhhlfe {
  stop-color: var(--svg-color--70647f, #70647F);
  stop-opacity: 0;
}

.nria2ku7r {
  stop-color: var(--svg-color--d8772c, #D8772C);
}

.nxet2htkz {
  stop-color: var(--svg-color--57525d, #57525D);
  stop-opacity: 0;
}

.nxnd1ibet {
  d: path("M11.074 12.635a1.689 1.689 0 1 0 0-3.378a1.689 1.689 0 0 0 0 3.378");
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.o2uld0acg {
  stop-color: var(--svg-color--433850, #433850);
}

.oa5gwac6c {
  d: path("m9.771 5.242l1.254-1.992l9.75-.11l1.36 2.063c-4.664 1.61-10.274.774-12.364.04");
}

.oaxszm67z {
  stop-color: var(--svg-color--cb6325, #CB6325);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofew38o4j {
  fill-rule: evenodd;
  d: path("M23.532 12.426c.223-.457.34-.967.34-1.498c0-.49-.101-.95-.282-1.37h.006c-.085-.19-.18-.37-.296-.538l-.002-.004a3.4 3.4 0 0 1-.552-1.858v-.01a3.463 3.463 0 0 0-3.462-3.463a.57.57 0 0 1-.478-.244a3.47 3.47 0 0 0-2.815-1.445a3.47 3.47 0 0 0-2.814 1.445a.6.6 0 0 1-.478.244h-.09a3.463 3.463 0 0 0-3.373 3.462v.01a3.4 3.4 0 0 1-.552 1.86l-.002.003a3.46 3.46 0 0 0-.231 3.406a.54.54 0 0 1 0 .478a3.372 3.372 0 0 0 3.038 4.854h9.005a3.37 3.37 0 0 0 3.378-3.378a3.4 3.4 0 0 0-.34-1.476a.54.54 0 0 1 0-.478M10.665 9.62h-.013l1.258 2.472c.13 2.941 1.278 0 4.081 0s4.026 3.274 4.156.333l1.192-3.356c-.056-1.306-1.003-1.398-1.192-1.398h-3.38a4.05 4.05 0 0 1-3.347-1.756a.277.277 0 0 0-.484.054l-.086.203a2.42 2.42 0 0 1-1.302 1.317l-.054.022c-.248.128-.829.514-.85 1.51l.01.32z");
}

.ojstgxewy {
  stop-color: var(--svg-color--70635d, #70635D);
}

.ooaytekqc {
  d: path("M11.094 12.073a1.127 1.127 0 1 0 0-2.254a1.127 1.127 0 0 0 0 2.254");
}

.p-vpa1ykp {
  stop-color: var(--svg-color--faac28, #FAAC28);
}

.p1xq25bjq {
  stop-color: var(--svg-color--d76a18, #D76A18);
  stop-opacity: 0;
}

.p38w1vy6u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.957 4.08c.024.256.246 1.214.572 1.795");
}

.p40r72cdo {
  fill: var(--svg-color--000, #000);
  d: path("M14.236 10.756a.534.534 0 0 0-.537-.537a.534.534 0 0 0-.477.784h.95a.5.5 0 0 0 .064-.247");
}

.p4wkjrbae {
  stop-color: var(--svg-color--c9681c, #C9681C);
  stop-opacity: 0;
}

.p8zuh31xg {
  d: path("M11.673 23.766c0-.188.155-.34.346-.34s.345.152.345.34v6.093h-.691z");
}

.pb_rvfc5z {
  stop-color: var(--svg-color--ffe842, #FFE842);
}

.pf_fn77-l {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.048 8.456c-.338-.082-1.18-.041-1.743.361");
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

.pok8-dbcp {
  stop-color: var(--svg-color--534d5b, #534D5B);
}

.pts6vr7ld {
  stop-color: var(--svg-color--433850, #433850);
  stop-opacity: 0;
}

.q0yj0-b_g {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.482 9.534c-.685 0-1.264.472-1.422 1.11a.288.288 0 0 0 .281.358h2.342a.242.242 0 0 0 .238-.285a1.47 1.47 0 0 0-1.439-1.183");
}

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.q9pn2c2pp {
  d: path("M23.026 18.09a.24.24 0 0 0-.059-.29c-1.856-1.603-4.346-2.488-6.954-2.488s-5.113.894-6.97 2.487a.24.24 0 0 0-.06.29c1.276 2.6 3.756 4.614 7.03 4.614s5.73-2.014 7.013-4.614");
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qilq-wckb {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M11.094 12.073a1.127 1.127 0 1 0 0-2.254a1.127 1.127 0 0 0 0 2.254");
}

.qir_1cb0f {
  stop-color: var(--svg-color--e26b25, #E26B25);
  stop-opacity: 0;
}

.qs5b04nop {
  stop-color: var(--svg-color--70647f, #70647F);
}

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwjswe-rp {
  stop-color: var(--svg-color--e48538, #E48538);
  stop-opacity: 0;
}

.r2v6fvpbl {
  stop-color: var(--svg-color--60546c, #60546C);
}

.r4jd8ka-r {
  d: path("M21.058 12.635a1.689 1.689 0 1 0 0-3.378a1.689 1.689 0 0 0 0 3.378");
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.s3t3owbgt {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
  stop-opacity: 0;
}

.sufhn4bec {
  stop-color: var(--svg-color--db6009, #DB6009);
}

.sxoxd_kke {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
  stop-opacity: 0;
}

.t3u7ugodp {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.214 10.017c.067.09-.073.198-.231.317c-.159.118-.276.201-.343.112s.008-.257.166-.376c.159-.118.341-.142.408-.053");
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.tgqxysbgm {
  stop-color: var(--svg-color--d76a18, #D76A18);
}

.tpesn5blm {
  stop-color: var(--svg-color--eeac32, #EEAC32);
}

.tslki-kuz {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M24.441 3.704v7.767");
}

.tsugr2bel {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.5 9.534c.686 0 1.265.472 1.422 1.11a.288.288 0 0 1-.28.358H17.3a.242.242 0 0 1-.238-.285A1.47 1.47 0 0 1 18.5 9.534");
}

.txssswzwf {
  fill: var(--svg-color--bd4f26, #BD4F26);
  d: path("m12.426 9.08l-.005.003a.282.282 0 0 1-.29-.483h.002l.003-.003l.01-.005a2 2 0 0 1 .156-.08c.103-.05.25-.113.43-.17a2.9 2.9 0 0 1 1.394-.115a.281.281 0 1 1-.097.554c-.419-.074-.82 0-1.125.097a3 3 0 0 0-.478.202");
}

.tzi44uqjw {
  stop-color: var(--svg-color--d1710b, #D1710B);
  stop-opacity: 0;
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.ud98q8dic {
  stop-color: var(--svg-color--c57e10, #C57E10);
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.umcd3ubyj {
  stop-color: var(--svg-color--eeac32, #EEAC32);
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

.uxkj8zbvq {
  d: path("M15.711 18.86c.063.043.17.08.28.084a.56.56 0 0 0 .28-.084c1.017-.696 1.78-1.39 1.78-2.587V12.64c0-1.14-.92-2.06-2.06-2.06s-2.06.92-2.06 2.06v3.633c0 1.198.763 1.891 1.78 2.587");
}

.uzp4m_b3p {
  stop-color: var(--svg-color--342542, #342542);
  stop-opacity: 0;
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v61l3jbat {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
  stop-opacity: 0;
}

.v9rq5jjti {
  stop-color: var(--svg-color--cba140, #CBA140);
  stop-opacity: 0;
}

.vdzvc-bry {
  stop-color: var(--svg-color--d2771d, #D2771D);
}

.vsluyubzo {
  stop-color: var(--svg-color--f8a322, #F8A322);
  stop-opacity: 0;
}

.vz7481bzf {
  cx: 13.416px;
  cy: 10.219px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.409px;
  ry: 0.207px;
}

.w2e_edyjl {
  stop-color: var(--svg-color--f09429, #F09429);
}

.w3-vy4c8j {
  stop-color: var(--svg-color--e38923, #E38923);
}

.w72oynbwi {
  stop-color: var(--svg-color--e38923, #E38923);
  stop-opacity: 0;
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.wd1nojbmw {
  fill: var(--svg-color--56436b, #56436B);
  d: path("M16.01 15.49c-6.07 0-11 4.92-11 11v3.5H27v-3.5c0-6.08-4.92-11-10.99-11");
}

.wgs8pcw7o {
  d: path("M18.214 10.017c.067.09-.073.198-.231.317c-.159.118-.276.201-.343.112s.008-.257.166-.376c.159-.118.341-.142.408-.053");
}

.wntqft2su {
  stop-color: var(--svg-color--696070, #696070);
  stop-opacity: 0;
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.wx9hitk-a {
  d: path("M16.01 15.49c-6.07 0-11 4.92-11 11v3.5H27v-3.5c0-6.08-4.92-11-10.99-11");
}

.x49zttk2i {
  stop-color: var(--svg-color--2b2135, #2B2135);
}

.x9irakh7s {
  d: path("M14.554 10.645c0-.302-.245-.504-.312-.565l-.302.293l.186.378z");
}

.xlrmucced {
  stop-color: var(--svg-color--685352, #685352);
}

.xo-fpccvi {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m15.58 10.712l-.718 1.784a.566.566 0 0 0 .546.734h.825c.387 0 .66-.372.547-.734l-.558-1.784c-.12-.395-.518-.395-.643 0");
}

.xp7dwurxx {
  stop-color: var(--svg-color--433a4d, #433A4D);
}

.xs166rhme {
  d: path("M8.775 29.99V18.204A10.97 10.97 0 0 0 5.01 26.49v3.5z");
}

.xxaet9bhw {
  stop-color: var(--svg-color--47404d, #47404D);
}

.y7n0ymbzx {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
  stop-opacity: 0;
}

.ydajvlb5g {
  d: path("M19.646 23.766c0-.188.154-.34.345-.34s.346.152.346.34v6.093h-.691z");
}

.yehxt3bls {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
}

.yihcw4vuy {
  stop-color: var(--svg-color--766c83, #766C83);
}

.yn026ikmt {
  stop-color: var(--svg-color--df8f14, #DF8F14);
  stop-opacity: 0;
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.yqk-2gbyp {
  stop-color: var(--svg-color--cb6325, #CB6325);
}

.yr1vjkbzu {
  stop-color: var(--svg-color--ffd93c, #FFD93C);
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.z-gx2rb2w {
  stop-color: var(--svg-color--ffe337, #FFE337);
}

.z6io75bpj {
  stop-color: var(--svg-color--5d516a, #5D516A);
  stop-opacity: 0;
}

.zjei445oy {
  stop-color: var(--svg-color--d2771d, #D2771D);
  stop-opacity: 0;
}

.zvl8nq86d {
  stop-color: var(--svg-color--3b2d3a, #3B2D3A);
}

.zy5hoab9j {
  stop-color: var(--svg-color--dcad1e, #DCAD1E);
}

</style>
