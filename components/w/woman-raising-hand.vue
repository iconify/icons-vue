<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iL3QLGd)"><path fill="url(#inNEZnc)" clip-rule="evenodd" class="jtesigb6i"/><path fill="url(#iXmXG1v)" clip-rule="evenodd" class="jtesigb6i"/><path fill="url(#iaU6VBc)" clip-rule="evenodd" class="jtesigb6i"/><path fill="url(#iyHQSuI)" clip-rule="evenodd" class="jtesigb6i"/><path fill="url(#i6Zt1qd)" clip-rule="evenodd" class="jtesigb6i"/><path fill="url(#iClhRFe)" clip-rule="evenodd" class="jtesigb6i"/><path fill="url(#iKdLotb)" clip-rule="evenodd" class="jtesigb6i"/><path fill="url(#iVfGzyo)" clip-rule="evenodd" class="jtesigb6i"/><path fill="url(#iAkMHBb)" clip-rule="evenodd" class="jtesigb6i"/><path fill="url(#i6Kwf5d)" clip-rule="evenodd" class="jtesigb6i"/><path fill="url(#isVW4sV)" clip-rule="evenodd" class="jtesigb6i"/><path fill="url(#iRSYQuc)" clip-rule="evenodd" class="jtesigb6i"/></g><path fill="url(#ihaTe0c)" class="bfjz1h9ck"/><path fill="url(#iNLNkee)" class="bfjz1h9ck"/><path fill="url(#ieRwlHb)" class="bfjz1h9ck"/><path fill="url(#iRLsjwT)" class="bfjz1h9ck"/><path fill="url(#ijxiPCc)" class="bfjz1h9ck"/><path fill="url(#ip8Pw2p)" class="bfjz1h9ck"/><path fill="url(#iU3ngBc)" class="bfjz1h9ck"/><path fill="url(#ipWW4Yo)" class="bfjz1h9ck"/><path fill="url(#idRN4ue)" class="bfjz1h9ck"/><path fill="url(#izu1WOd)" class="bfjz1h9ck"/><path fill="url(#iNuvVGc)" class="bfjz1h9ck"/><path fill="url(#iaucIWb)" class="ibj-i65gx"/><path fill="url(#iU4EiAd)" class="ibj-i65gx"/><path fill="url(#iLO5Q3d)" class="ibj-i65gx"/><path fill="url(#i00jbqd)" class="tw8grib3t"/><path fill="url(#iRchgFe)" class="tw8grib3t"/><path fill="url(#i1WNtqb)" class="tw8grib3t"/><path fill="url(#ioL2qkd)" class="f5uud1zrg"/><path fill="url(#iBRUlhe)" class="f5uud1zrg"/><path fill="url(#ikGxzqd)" class="f5uud1zrg"/><path fill="url(#iEB6gDb)" class="f5uud1zrg"/><path fill="url(#i3UTTEe)" class="f5uud1zrg"/><path fill="url(#iqEorgd)" class="f5uud1zrg"/><path fill="url(#iCb6CIe)" class="bk7st7jpk"/><path fill="url(#ivhZgDc)" class="bk7st7jpk"/><g filter="url(#iL7K6zc)"><path stroke="url(#ikc7v5d)" class="nnx_zhdyy"/></g><g filter="url(#iI30bVm)"><path stroke="url(#ipyvYEe)" class="de3dbtgwp"/></g><g filter="url(#iCqaR8d)"><path stroke="url(#ii2ZHQd)" class="jv_k29bga"/></g><g filter="url(#iB7eOSd)"><path stroke="url(#iRfTTlM)" class="j-u0i-3nk"/></g><g filter="url(#ierFMqe)"><path fill="url(#id6I7ze)" class="rz5yb1b4g"/></g><g filter="url(#isutMub)"><path fill="url(#iBdCvRd)" class="njgcvv0wz"/></g><g filter="url(#i84TSne)"><path class="qz5cyfb_z"/><path fill="url(#iXgeeEc)" class="mjferkb4a"/></g><g filter="url(#ib7Daxe)"><path class="baxqq4bch"/><path fill="url(#iWTYDqe)" class="ep7_ocbek"/></g><g filter="url(#ipj8btc)"><path fill="url(#ipaLjSd)" class="t15q6w3yg"/><path fill="url(#iNB2i9b)" class="t15q6w3yg"/><path fill="url(#iXuXQcp)" class="t15q6w3yg"/><path fill="url(#iAaAvwe)" class="t15q6w3yg"/><path fill="url(#iSaMqab)" class="t15q6w3yg"/><path fill="url(#icMYlJc)" class="t15q6w3yg"/><path fill="url(#iL2oUxb)" class="t15q6w3yg"/></g><path fill="url(#iD7LKUc)" class="t15q6w3yg"/><g filter="url(#iiC5zQc)"><path class="yv0tpg85m"/></g><g filter="url(#ijIT3yH)"><path fill="url(#iKVzUYY)" class="fqp-b0b3a"/><path fill="url(#ilVM1Yc)" class="fqp-b0b3a"/><path fill="url(#iyplEig)" class="fqp-b0b3a"/><path fill="url(#iynGE6c)" class="fqp-b0b3a"/></g><path fill="url(#iXZCpye)" class="fqp-b0b3a"/><path fill="url(#iezk0tb)" class="fqp-b0b3a"/><path stroke="url(#i7Vhewc)" class="eot1fccil"/><g filter="url(#itqFp2d)"><path class="vvr4s2bpx"/></g><g filter="url(#iirdtTc)"><path class="kfu3-qrmk"/></g><g filter="url(#iISmAWd)"><path class="po26regef"/></g><g filter="url(#ifWMFdd)"><path clip-rule="evenodd" class="r6-xa-gst"/></g><path class="y6udnebbh"/><path fill="url(#iiQ8ned)" class="asusy4-bj"/><path class="v3wv1vqzi"/><g filter="url(#iDyV9vb)"><path class="ej0ojac9f"/><path fill="url(#iYX2Hgh)" class="bosjgkvxq"/></g><g filter="url(#ihF5Xid)"><path fill="url(#ikW7nle)" class="uwvmppbhh"/></g><path class="ks6o3vbfj"/><path fill="url(#iI88xGd)" class="brbky6b8s"/><path class="m64yxqbam"/><g filter="url(#iRPjhfb)"><path fill="url(#ipLfRHc)" class="er56yac3k"/></g><g filter="url(#ioqysqc)"><ellipse transform="rotate(-27.914 16.602 13.634)" class="kqvlaif6e"/><ellipse fill="url(#i02lNad)" transform="rotate(-27.914 16.602 13.634)" class="rf9pl1b2z"/></g><g filter="url(#iut6Tkc)"><path class="kvb_xrbwj"/></g><g filter="url(#i7oCxOe)"><path class="ligx0o9-z"/></g><g filter="url(#iLHEHCc)"><path fill="url(#iu4o3ie)" class="e-j2kmbah"/><path fill="url(#iL07UZT)" class="e-j2kmbah"/></g><g filter="url(#iH9OFyc)"><path fill="url(#iDUhh1d)" class="ew2hdfbns"/><path fill="url(#idnPMNd)" class="ew2hdfbns"/><path fill="url(#iG4BwBd)" class="ew2hdfbns"/></g><g filter="url(#ieYeEDd)"><path stroke="url(#imEso2d)" class="d7-fl-bcx"/></g><defs><radialGradient id="iXmXG1v" cx="0" cy="0" r="1" gradientTransform="matrix(3.42333 1.84334 -2.611 4.84898 24.254 18.5)" gradientUnits="userSpaceOnUse"><stop offset=".616" class="w3-vy4c8j"/><stop offset="1" class="w72oynbwi"/></radialGradient><radialGradient id="iaU6VBc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.43242 -3.27286 0 14.021 16.958)" gradientUnits="userSpaceOnUse"><stop class="lcrdwk1fj"/><stop offset="1" class="denqa3bda"/></radialGradient><radialGradient id="iyHQSuI" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.79105 -7.07411 0 19.593 17.07)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="ag6fa4z4y"/><stop offset="1" class="qir_1cb0f"/></radialGradient><radialGradient id="i6Zt1qd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51247 1.96278 -1.90576 -1.46853 13.607 14.87)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="ha2cq84sa"/><stop offset="1" class="p4wkjrbae"/></radialGradient><radialGradient id="iClhRFe" cx="0" cy="0" r="1" gradientTransform="matrix(-.56998 3.0643 -3.19089 -.59353 14.328 11.9)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="tgqxysbgm"/><stop offset="1" class="p1xq25bjq"/></radialGradient><radialGradient id="iKdLotb" cx="0" cy="0" r="1" gradientTransform="matrix(1.33548 2.5769 -4.90894 2.54406 15.526 5.747)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="esx41hbqq"/><stop offset=".921" class="v9rq5jjti"/></radialGradient><radialGradient id="iVfGzyo" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 11.504 9.521)scale(1.99566 2.7889)" gradientUnits="userSpaceOnUse"><stop class="duwob45dr"/><stop offset="1" class="v61l3jbat"/></radialGradient><radialGradient id="iAkMHBb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.24742 .65383 -1.42265 -4.8901 28.747 13.44)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="hottnizrg"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="i6Kwf5d" cx="0" cy="0" r="1" gradientTransform="rotate(-133.315 18.175 5.749)scale(5.68317 8.16169)" gradientUnits="userSpaceOnUse"><stop class="yqk-2gbyp"/><stop offset="1" class="oaxszm67z"/></radialGradient><radialGradient id="isVW4sV" cx="0" cy="0" r="1" gradientTransform="matrix(-.0103 -1.67535 .54929 -.00337 16.296 8.788)" gradientUnits="userSpaceOnUse"><stop offset=".295" class="sufhn4bec"/><stop offset="1" class="kpf8h5ohf"/></radialGradient><radialGradient id="iRSYQuc" cx="0" cy="0" r="1" gradientTransform="rotate(-134.119 13.937 7.098)scale(10.1929 9.02205)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="lkm9aabxa"/><stop offset="1" class="tq56jpbfq"/></radialGradient><radialGradient id="ihaTe0c" cx="0" cy="0" r="1" gradientTransform="matrix(2.33335 -6.04232 7.22855 2.79144 6.453 11.91)" gradientUnits="userSpaceOnUse"><stop offset=".475" class="wkdez3bsl"/><stop offset="1" class="uovxktaxm"/><stop offset="1" class="ptqby1bwa"/></radialGradient><radialGradient id="iNLNkee" cx="0" cy="0" r="1" gradientTransform="rotate(130.764 3.062 7.467)scale(9.5721 2.30417)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="qqqtnz_cz"/><stop offset="1" class="tljjnprhh"/></radialGradient><radialGradient id="iRLsjwT" cx="0" cy="0" r="1" gradientTransform="matrix(.19531 2.2578 -.27074 .02342 5.178 5.097)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="uzy68hb9o"/><stop offset="1" class="q-_hp3b8x"/></radialGradient><radialGradient id="ijxiPCc" cx="0" cy="0" r="1" gradientTransform="matrix(-.04685 3.40625 -.266 -.00366 6.827 3.932)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="gk2jlbbkx"/><stop offset="1" class="q-_hp3b8x"/></radialGradient><radialGradient id="ip8Pw2p" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 3.96875 -.56716 -.09602 8.795 3.167)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="gk2jlbbkx"/><stop offset="1" class="q-_hp3b8x"/></radialGradient><radialGradient id="iU3ngBc" cx="0" cy="0" r="1" gradientTransform="matrix(-.89063 .84376 -.848 -.8951 10.14 3.714)" gradientUnits="userSpaceOnUse"><stop class="v3jqojv9j"/><stop offset="1" class="oih2nzbsq"/></radialGradient><radialGradient id="ipWW4Yo" cx="0" cy="0" r="1" gradientTransform="rotate(138.965 3.67 2.974)scale(1.11858 .93215)" gradientUnits="userSpaceOnUse"><stop class="v3jqojv9j"/><stop offset="1" class="oih2nzbsq"/></radialGradient><radialGradient id="idRN4ue" cx="0" cy="0" r="1" gradientTransform="matrix(-.46875 .71876 -.65233 -.42542 6.266 3.37)" gradientUnits="userSpaceOnUse"><stop class="v3jqojv9j"/><stop offset="1" class="oih2nzbsq"/></radialGradient><radialGradient id="izu1WOd" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 .60938 -.55306 -.45379 4.686 4.651)" gradientUnits="userSpaceOnUse"><stop class="v3jqojv9j"/><stop offset="1" class="oih2nzbsq"/></radialGradient><radialGradient id="iNuvVGc" cx="0" cy="0" r="1" gradientTransform="rotate(85.723 -.471 5.152)scale(2.30438 .44699)" gradientUnits="userSpaceOnUse"><stop class="z_yn3vbua"/><stop offset="1" class="j6lbcibwa"/></radialGradient><radialGradient id="iU4EiAd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.10937 -1.15625 0 7.71 12.479)" gradientUnits="userSpaceOnUse"><stop class="n6xb1lbrp"/><stop offset="1" class="dw_ks814f"/></radialGradient><radialGradient id="iRchgFe" cx="0" cy="0" r="1" gradientTransform="matrix(-8.68288 2.79847 -2.9931 -9.28678 26.68 27.228)" gradientUnits="userSpaceOnUse"><stop class="w5d8oacwp"/><stop offset="1" class="lj6gy_bpx"/></radialGradient><radialGradient id="i1WNtqb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.62502 2.65624 0 11.47 30.026)" gradientUnits="userSpaceOnUse"><stop class="hg8hi1xei"/><stop offset="1" class="lerw6n44i"/></radialGradient><radialGradient id="iBRUlhe" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.8125 -5.4375 0 3.56 13.026)" gradientUnits="userSpaceOnUse"><stop class="pwjmzpbsg"/><stop offset="1" class="em0canjqu"/></radialGradient><radialGradient id="ikGxzqd" cx="0" cy="0" r="1" gradientTransform="rotate(-167.876 10.227 9.245)scale(10.3399 4.20474)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="dm9wa-bnr"/><stop offset="1" class="x6dke3bsb"/></radialGradient><radialGradient id="iEB6gDb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.69115 0 0 -5.7286 12.33 15.939)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="dm9wa-bnr"/><stop offset="1" class="x6dke3bsb"/></radialGradient><radialGradient id="ivhZgDc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.15625 -2.61254 0 19.593 21.32)" gradientUnits="userSpaceOnUse"><stop class="jt0cc3bxg"/><stop offset="1" class="kq1evibhh"/></radialGradient><radialGradient id="iBdCvRd" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 46.916 -49.087)scale(3.3329 4.06932)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="iXgeeEc" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 53.848 -62.982)scale(1.59029)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="iWTYDqe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.30934 0 0 -1.25247 13.905 14.479)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="ipaLjSd" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 10.023 9.444)scale(8.73018 11.6852)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="m45oyzb-o"/></radialGradient><radialGradient id="iNB2i9b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.57177 1.3603 -1.15412 -2.18196 21.91 14.674)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="iXuXQcp" cx="0" cy="0" r="1" gradientTransform="rotate(-78.311 22.033 .646)scale(5.03546 6.38906)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="iAaAvwe" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.07009 -14.4058 0 19.274 13.234)" gradientUnits="userSpaceOnUse"><stop offset=".593" class="ajxs5ri3z"/><stop offset="1" class="x05md6_2b"/></radialGradient><radialGradient id="iSaMqab" cx="0" cy="0" r="1" gradientTransform="matrix(-6.6101 1.82793 -3.14713 -11.38057 20.358 15.843)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="icMYlJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.40279 1.72161 0 22.399 13.313)" gradientUnits="userSpaceOnUse"><stop class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="iL2oUxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.65784 1.9 0 17.255 13.42)" gradientUnits="userSpaceOnUse"><stop class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="iD7LKUc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64194 0 0 -5.40531 25.805 15.127)" gradientUnits="userSpaceOnUse"><stop class="f902gfhfn"/><stop offset="1" class="jh40i5bvl"/></radialGradient><radialGradient id="ilVM1Yc" cx="0" cy="0" r="1" gradientTransform="matrix(-.8502 -2.98624 1.70876 -.4865 20.55 16.013)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="iezk0tb" cx="0" cy="0" r="1" gradientTransform="rotate(144.462 7.476 10.984)scale(1.91979 2.57142)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="e6-lebcyw"/><stop offset="1" class="b8os9sbcy"/></radialGradient><radialGradient id="iiQ8ned" cx="0" cy="0" r="1" gradientTransform="matrix(0 .989 -1.57311 0 22.253 13.75)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iYX2Hgh" cx="0" cy="0" r="1" gradientTransform="matrix(-.28248 -.36401 .50116 -.3889 21.975 13.853)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iI88xGd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .989 -1.57312 0 16.933 13.75)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i02lNad" cx="0" cy="0" r="1" gradientTransform="matrix(-.00942 -.60178 .72335 -.01133 16.584 14.018)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iu4o3ie" cx="0" cy="0" r="1" gradientTransform="matrix(-4.16817 5.0467 -2.20102 -1.81787 16.284 6.004)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="esh4v5qtq"/><stop offset=".911" class="nria2ku7r"/></radialGradient><radialGradient id="iL07UZT" cx="0" cy="0" r="1" gradientTransform="matrix(-3.78228 2.70206 -1.3354 -1.86926 16.113 6.67)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="dpv-wxbjb"/><stop offset="1" class="abu2lcc5n"/><stop offset="1" class="sxoxd_kke"/></radialGradient><radialGradient id="iDUhh1d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.66394 5.5526 -7.88377 -3.78235 21.777 4.574)" gradientUnits="userSpaceOnUse"><stop offset=".627" class="crfaaqblp"/><stop offset="1" class="ehjghj3fe"/></radialGradient><radialGradient id="idnPMNd" cx="0" cy="0" r="1" gradientTransform="rotate(105.909 9.023 11.6)scale(4.19341 8.78806)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="z-gx2rb2w"/><stop offset="1" class="gbpc14bxe"/></radialGradient><radialGradient id="iG4BwBd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.16511 -7.88382 7.04765 -3.72335 20.995 12.967)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="s3t3owbgt"/><stop offset="1" class="yehxt3bls"/></radialGradient><filter id="iL3QLGd" width="18.557" height="18.557" x="10.44" y="3.833" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.537255 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3860"/></filter><filter id="iL7K6zc" width="9.217" height="11.911" x="5.936" y="12.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3860" stdDeviation=".75"/></filter><filter id="iI30bVm" width=".407" height="1.694" x="5.049" y="5.076" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3860" stdDeviation=".05"/></filter><filter id="iCqaR8d" width=".369" height="2.337" x="6.588" y="4.162" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3860" stdDeviation=".05"/></filter><filter id="iB7eOSd" width=".431" height="1.478" x="8.135" y="5.295" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3860" stdDeviation=".05"/></filter><filter id="ierFMqe" width="4.023" height="3.923" x="11.92" y="12.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.501961 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3860"/></filter><filter id="isutMub" width="3.923" height="4.173" x="23.516" y="12.267" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3860"/></filter><filter id="i84TSne" width="3.619" height="3.619" x="23.669" y="12.669" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3860" stdDeviation=".25"/></filter><filter id="ib7Daxe" width="3.119" height="3.119" x="12.346" y="12.919" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3860" stdDeviation=".125"/></filter><filter id="ipj8btc" width="12.423" height="13.659" x="13.382" y="8.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3860"/></filter><filter id="iiC5zQc" width="3.288" height="4.269" x="17.751" y="13.363" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3860" stdDeviation=".25"/></filter><filter id="ijIT3yH" width="2.788" height="3.769" x="18.199" y="13.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3860" stdDeviation=".125"/></filter><filter id="itqFp2d" width="3.615" height="1.567" x="20.786" y="12.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3860"/></filter><filter id="iirdtTc" width="3.615" height="1.567" x="14.787" y="12.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3860"/></filter><filter id="iISmAWd" width="2.946" height="1.286" x="14.951" y="11.075" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3860"/></filter><filter id="ifWMFdd" width="2.946" height="1.286" x="21.555" y="11.075" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3860"/></filter><filter id="iDyV9vb" width=".915" height=".805" x="21.38" y="13.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3860" stdDeviation=".05"/></filter><filter id="ihF5Xid" width=".998" height="1.025" x="22.426" y="13.35" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3860" stdDeviation=".1"/></filter><filter id="iRPjhfb" width="1.114" height="1.18" x="17.01" y="13.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3860" stdDeviation=".1"/></filter><filter id="ioqysqc" width="1.069" height=".814" x="16.068" y="13.227" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3860" stdDeviation=".05"/></filter><filter id="iut6Tkc" width="3.225" height="1.66" x="21.358" y="10.946" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3860" stdDeviation=".2"/></filter><filter id="i7oCxOe" width="3.225" height="1.66" x="14.712" y="10.946" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3860" stdDeviation=".2"/></filter><filter id="iLHEHCc" width="5.749" height="6.027" x="11.581" y="5.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3860" stdDeviation=".375"/></filter><filter id="iH9OFyc" width="11.257" height="7.436" x="15.354" y="4.441" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3860" stdDeviation=".25"/></filter><filter id="ieYeEDd" width="1.264" height="2.684" x="15.769" y="6.204" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3860" stdDeviation=".125"/></filter><linearGradient id="inNEZnc" x1="25.315" x2="16.487" y1="6.004" y2="22.39" gradientUnits="userSpaceOnUse"><stop class="yr1vjkbzu"/><stop offset="1" class="btu9i2bec"/></linearGradient><linearGradient id="ieRwlHb" x1="6.936" x2="6.936" y1="12.57" y2="10.867" gradientUnits="userSpaceOnUse"><stop class="oeyur9bet"/><stop offset="1" class="wez3-gbsw"/></linearGradient><linearGradient id="iaucIWb" x1="4.78" x2="9.155" y1="12.589" y2="12.589" gradientUnits="userSpaceOnUse"><stop class="lxmd97b0u"/><stop offset=".743" class="uokhptbdi"/></linearGradient><linearGradient id="iLO5Q3d" x1="7.049" x2="7.049" y1="12.003" y2="12.261" gradientUnits="userSpaceOnUse"><stop class="eq3barbte"/><stop offset="1" class="t9grd_b1a"/></linearGradient><linearGradient id="i00jbqd" x1="13.978" x2="6.04" y1="24.513" y2="13.026" gradientUnits="userSpaceOnUse"><stop class="ql4h4w3wf"/><stop offset="1" class="u0tebcbmi"/></linearGradient><linearGradient id="ioL2qkd" x1="10.046" x2="12.002" y1="26.694" y2="20.41" gradientUnits="userSpaceOnUse"><stop offset=".1" class="bv9ik6bnv"/><stop offset="1" class="gjgbs4bmp"/></linearGradient><linearGradient id="i3UTTEe" x1="14.315" x2="13.576" y1="24.719" y2="23.323" gradientUnits="userSpaceOnUse"><stop offset=".213" class="ql4h4w3wf"/><stop offset=".732" class="uphj9jblf"/></linearGradient><linearGradient id="iqEorgd" x1="7.575" x2="7.575" y1="13.026" y2="14.066" gradientUnits="userSpaceOnUse"><stop class="e5gfjqb4s"/><stop offset="1" class="ss3ej3_3n"/></linearGradient><linearGradient id="iCb6CIe" x1="17.904" x2="19.904" y1="20.757" y2="24.132" gradientUnits="userSpaceOnUse"><stop class="z-nk_efhm"/><stop offset="1" class="xbhzvqb7t"/></linearGradient><linearGradient id="ikc7v5d" x1="7.592" x2="13.342" y1="14.734" y2="23.015" gradientUnits="userSpaceOnUse"><stop class="u8s8n3e7l"/><stop offset="1" class="k-1337bil"/></linearGradient><linearGradient id="ipyvYEe" x1="5.187" x2="5.339" y1="5.213" y2="6.729" gradientUnits="userSpaceOnUse"><stop class="v55yv8mfw"/><stop offset="1" class="y2zvm24uz"/></linearGradient><linearGradient id="ii2ZHQd" x1="6.773" x2="7.256" y1="4.424" y2="6.536" gradientUnits="userSpaceOnUse"><stop class="v55yv8mfw"/><stop offset="1" class="y2zvm24uz"/></linearGradient><linearGradient id="iRfTTlM" x1="8.351" x2="8.454" y1="5.505" y2="6.793" gradientUnits="userSpaceOnUse"><stop class="v55yv8mfw"/><stop offset="1" class="y2zvm24uz"/></linearGradient><linearGradient id="id6I7ze" x1="11.92" x2="15.528" y1="14.585" y2="14.585" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="iKVzUYY" x1="19.593" x2="19.593" y1="16.963" y2="13.694" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="iyplEig" x1="18.318" x2="19.359" y1="16.034" y2="16.162" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="iynGE6c" x1="19.593" x2="19.593" y1="17.075" y2="16.331" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="iXZCpye" x1="19.689" x2="19.689" y1="17.044" y2="16.873" gradientUnits="userSpaceOnUse"><stop class="b8os9sbcy"/><stop offset="1" class="e6-lebcyw"/></linearGradient><linearGradient id="i7Vhewc" x1="18.705" x2="19.256" y1="18.876" y2="17.813" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="ikW7nle" x1="23.201" x2="22.819" y1="13.816" y2="14.052" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ipLfRHc" x1="17.84" x2="17.457" y1="13.816" y2="14.052" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="imEso2d" x1="16.069" x2="16.733" y1="6.923" y2="8.476" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-raising-hand" /></template>
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

.ajxs5ri3z {
  stop-color: var(--svg-color--f3943b, #F3943B);
  stop-opacity: 0;
}

.asusy4-bj {
  d: path("M22.256 13.17a1.088 1.088 0 0 1 1.048 1.374h-2.101a1.092 1.092 0 0 1 1.053-1.375");
}

.b8os9sbcy {
  stop-color: var(--svg-color--e2802f, #E2802F);
}

.baxqq4bch {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M13.905 15.788a1.31 1.31 0 1 0 0-2.619a1.31 1.31 0 0 0 0 2.62");
}

.bfjz1h9ck {
  d: path("M3.874 9.274c-.125-1.922-.282-2.959-.329-3.641c-.035-.512.024-1.066.711-1.191c.598-.075.883.451.907.66c-.003-.2 0-.68 0-.805c0-.21.007-.976.859-.976c.601 0 .816.587.8.863c.011-.102.023-.413.036-.707c.018-.434.251-.99.945-.977c.598.04.793.613.766.977l-.117 1.867c.023-.188.102-.665.277-1.34s.702-.72.957-.683c.326.046.88.36.649 1.273c-.276 1.156-.463 2.644-.528 3.285c.32-.13.605-.429.957-.796l.016-.016c.36-.375.933-.332 1.172-.106c.363.235.562.938.16 1.34c-.463.425-2.13 2.405-2.957 3.394c-.23.292-.997.875-2.235.875c-2.203-.093-2.941-1.676-3.046-3.296");
}

.bk7st7jpk {
  d: path("M19.593 24.132c-1.267 0-2.296-.985-2.296-2.2v-2.6c0-1.215 1.029-2.2 2.296-2.2c1.268 0 2.297.985 2.297 2.2v2.6c0 1.215-1.029 2.2-2.297 2.2");
}

.bosjgkvxq {
  d: path("M22.175 13.4c.078.103-.084.23-.268.367c-.184.138-.32.235-.398.131s.009-.3.193-.437s.396-.165.473-.061");
}

.brbky6b8s {
  d: path("M16.93 13.17a1.088 1.088 0 0 0-1.047 1.374h2.101q.039-.14.04-.287a1.095 1.095 0 0 0-1.093-1.088");
}

.btu9i2bec {
  stop-color: var(--svg-color--e37923, #E37923);
}

.bv9ik6bnv {
  stop-color: var(--svg-color--8751e0, #8751E0);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crfaaqblp {
  stop-color: var(--svg-color--f49523, #F49523);
  stop-opacity: 0;
}

.d7-fl-bcx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.069 6.504c.028.296.286 1.41.664 2.084");
}

.de3dbtgwp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m5.187 5.213l.132 1.42");
}

.denqa3bda {
  stop-color: var(--svg-color--d77117, #D77117);
  stop-opacity: 0;
}

.dm9wa-bnr {
  stop-color: var(--svg-color--522a56, #522A56);
}

.dpv-wxbjb {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
}

.duwob45dr {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
}

.dw_ks814f {
  stop-color: var(--svg-color--6e5098, #6E5098);
  stop-opacity: 0;
}

.e-j2kmbah {
  d: path("M13.627 7.148c.757-.675 1.85-.681 2.462-.572l.49 1.573c-.313-.048-.592.061-.827.286c-.556 1.536-2.465 2.384-3.35 2.615c-.184-1.818-.082-2.738 1.225-3.902");
}

.e0lgwbeaw {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.e5gfjqb4s {
  stop-color: var(--svg-color--7354a3, #7354A3);
}

.e6-lebcyw {
  stop-color: var(--svg-color--e2802f, #E2802F);
  stop-opacity: 0;
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.ehjghj3fe {
  stop-color: var(--svg-color--f49523, #F49523);
}

.ej0ojac9f {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M22.175 13.4c.078.103-.084.23-.268.367c-.184.138-.32.235-.398.131s.009-.3.193-.437s.396-.165.473-.061");
}

.em0canjqu {
  stop-color: var(--svg-color--8f75c7, #8F75C7);
  stop-opacity: 0;
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.eot1fccil {
  fill: var(--svg-color--8a004f, #8A004F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.884 17.564a3.64 3.64 0 0 0 1.71.414c.633 0 1.215-.151 1.709-.414a.24.24 0 0 1 .288.048a.23.23 0 0 1 .025.29m-3.732-.338l3.69.311m-3.69-.311a.24.24 0 0 0-.289.05a.23.23 0 0 0-.024.289m.313-.34l-.271.312m4.003.027l-.042-.027m.042.027l-.042-.027m.042.027a2.405 2.405 0 0 1-4.045 0m4.003-.027a2.355 2.355 0 0 1-3.961 0m-.042.028l.042-.028m-.042.028l.042-.028");
}

.ep7_ocbek {
  d: path("M13.905 15.788a1.31 1.31 0 1 0 0-2.619a1.31 1.31 0 0 0 0 2.62");
}

.eq3barbte {
  stop-color: var(--svg-color--674a85, #674A85);
}

.er56yac3k {
  d: path("M17.924 14.129c0-.351-.285-.585-.363-.656l-.35.34l.215.44z");
}

.esh4v5qtq {
  stop-color: var(--svg-color--ee971b, #EE971B);
  stop-opacity: 0;
}

.esx41hbqq {
  stop-color: var(--svg-color--cba140, #CBA140);
}

.ew2hdfbns {
  d: path("M18.858 4.982c-1.38-.305-2.86 1.165-3.004 1.675c1.88 4.414 4.767 3.993 7.969 3.637c1.917-.213 2.125.66 2.288 1.083c-.53-4.944-4.107-5.7-7.253-6.395");
}

.f5uud1zrg {
  d: path("m18.951 21.136l-7.873 5.245a.66.66 0 0 0-.4-.48l-3.085-1.375c-2.5-1-3.5-3.5-3.5-5.198v-5.287c0-.564.425-1.015.936-1.015h4.129c.52 0 .935.462.935 1.015v3.985c0 1.302 1 1.5 1 1.5l6 1.5z");
}

.f902gfhfn {
  stop-color: var(--svg-color--ffda39, #FFDA39);
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.fkdj3ejgt {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
}

.fqp-b0b3a {
  d: path("m19.127 14.038l-.647 2.073a.657.657 0 0 0 .634.852h.959a.66.66 0 0 0 .634-.852l-.648-2.073c-.138-.459-.786-.459-.932 0");
}

.ft5dv1b6b {
  fill: none;
}

.gbpc14bxe {
  stop-color: var(--svg-color--ffe337, #FFE337);
  stop-opacity: 0;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gjgbs4bmp {
  stop-color: var(--svg-color--8751e0, #8751E0);
  stop-opacity: 0;
}

.gk2jlbbkx {
  stop-color: var(--svg-color--eaaa15, #EAAA15);
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

.hg8hi1xei {
  stop-color: var(--svg-color--9473d7, #9473D7);
}

.hottnizrg {
  stop-color: var(--svg-color--ffd336, #FFD336);
  stop-opacity: 0;
}

.ibj-i65gx {
  d: path("M4.944 12.203c0-.11.09-.2.2-.2h3.81a.2.2 0 0 1 .2.2v1.714h-4.21z");
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.j-u0i-3nk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m8.429 5.432l-.156 1.203");
}

.j6lbcibwa {
  stop-color: var(--svg-color--ffcc3d, #FFCC3D);
  stop-opacity: 0;
}

.jh40i5bvl {
  stop-color: var(--svg-color--ffda39, #FFDA39);
  stop-opacity: 0;
}

.jt0cc3bxg {
  stop-color: var(--svg-color--e97e36, #E97E36);
}

.jtesigb6i {
  fill-rule: evenodd;
  d: path("M28.352 16.197c.26-.53.395-1.122.395-1.74c0-.569-.117-1.103-.327-1.59h.006a4 4 0 0 0-.343-.626l-.002-.004a3.95 3.95 0 0 1-.642-2.159v-.012a4.02 4.02 0 0 0-4.021-4.022a.66.66 0 0 1-.555-.283a4.03 4.03 0 0 0-3.27-1.678a4.03 4.03 0 0 0-3.269 1.678a.69.69 0 0 1-.555.283l-.104.002a4.02 4.02 0 0 0-3.917 4.02v.012a3.95 3.95 0 0 1-.642 2.16l-.003.004a4.02 4.02 0 0 0-.268 3.955a.63.63 0 0 1 0 .555a4 4 0 0 0-.395 1.715a3.917 3.917 0 0 0 3.923 3.923h10.461a3.917 3.917 0 0 0 3.923-3.923c0-.617-.148-1.197-.395-1.715a.63.63 0 0 1 0-.555M13.407 12.94h-.015l1.461 2.87c.15 3.417 1.484 0 4.74 0s4.677 3.803 4.827.387l1.385-3.897c-.066-1.518-1.165-1.624-1.385-1.624h-3.925a4.71 4.71 0 0 1-3.888-2.04a.321.321 0 0 0-.562.062l-.1.237a2.8 2.8 0 0 1-1.513 1.53q-.033.014-.062.024c-.288.15-.963.597-.988 1.754l.013.373z");
}

.jv_k29bga {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m6.82 4.3l-.094 2.062");
}

.k-1337bil {
  stop-color: var(--svg-color--9d74e7, #9D74E7);
  stop-opacity: 0;
}

.kfu3-qrmk {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M18.202 13.785c-.324-.569-.816-1.018-1.875-1.018c-.463 0-.91.128-1.307.449c-.328.265-.284.604-.03.73l.678.388c.794-.257 1.673-.292 2.534-.549");
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.kpf8h5ohf {
  stop-color: var(--svg-color--db6009, #DB6009);
  stop-opacity: 0;
}

.kq1evibhh {
  stop-color: var(--svg-color--e97e36, #E97E36);
  stop-opacity: 0;
}

.kqvlaif6e {
  cx: 16.602px;
  cy: 13.634px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.475px;
  ry: 0.24px;
}

.ks6o3vbfj {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.679 12.838c-.796 0-1.469.549-1.652 1.29a.334.334 0 0 0 .327.416h2.72a.28.28 0 0 0 .276-.331a1.71 1.71 0 0 0-1.671-1.375");
}

.kvb_xrbwj {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M21.958 11.586c.393-.095 1.37-.047 2.024.42");
}

.lcrdwk1fj {
  stop-color: var(--svg-color--c9641b, #C9641B);
}

.lerw6n44i {
  stop-color: var(--svg-color--9473d7, #9473D7);
  stop-opacity: 0;
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ligx0o9-z {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M17.337 11.586c-.393-.095-1.371-.047-2.025.42");
}

.lj6gy_bpx {
  stop-color: var(--svg-color--a47ff0, #A47FF0);
  stop-opacity: 0;
}

.lkm9aabxa {
  stop-color: var(--svg-color--803706, #803706);
}

.lxmd97b0u {
  stop-color: var(--svg-color--77639c, #77639C);
}

.m45oyzb-o {
  stop-color: var(--svg-color--eb9235, #EB9235);
}

.m64yxqbam {
  fill: var(--svg-color--000, #000);
  d: path("M17.554 14.257a.62.62 0 0 0-.623-.623a.62.62 0 0 0-.554.91h1.103a.6.6 0 0 0 .074-.287");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.mjferkb4a {
  d: path("M25.478 15.788a1.31 1.31 0 1 0 0-2.619a1.31 1.31 0 0 0 0 2.62");
}

.n6xb1lbrp {
  stop-color: var(--svg-color--6e5098, #6E5098);
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.njgcvv0wz {
  d: path("M25.478 16.44a1.962 1.962 0 1 0 0-3.923a1.962 1.962 0 0 0 0 3.923");
}

.nnx_zhdyy {
  d: path("M7.936 13.954v5.172a2 2 0 0 0 1.38 1.901l4.182 1.363");
}

.nria2ku7r {
  stop-color: var(--svg-color--d8772c, #D8772C);
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.oaxszm67z {
  stop-color: var(--svg-color--cb6325, #CB6325);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oeyur9bet {
  stop-color: var(--svg-color--c77505, #C77505);
}

.oih2nzbsq {
  stop-color: var(--svg-color--ffdc45, #FFDC45);
  stop-opacity: 0;
}

.p1xq25bjq {
  stop-color: var(--svg-color--d76a18, #D76A18);
  stop-opacity: 0;
}

.p4wkjrbae {
  stop-color: var(--svg-color--c9681c, #C9681C);
  stop-opacity: 0;
}

.pb_rvfc5z {
  stop-color: var(--svg-color--ffe842, #FFE842);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.po26regef {
  fill: var(--svg-color--bd4f26, #BD4F26);
  d: path("m15.452 12.312l-.006.003a.327.327 0 0 1-.336-.561l.002-.001l.004-.002l.011-.007a2 2 0 0 1 .181-.094c.12-.057.291-.13.5-.197c.414-.132.994-.243 1.62-.133a.327.327 0 0 1-.114.644c-.486-.086-.953-.001-1.307.112a3.4 3.4 0 0 0-.555.236");
}

.ptqby1bwa {
  stop-color: var(--svg-color--eeb32a, #EEB32A);
}

.pwjmzpbsg {
  stop-color: var(--svg-color--8f75c7, #8F75C7);
}

.q-_hp3b8x {
  stop-color: var(--svg-color--eaaa15, #EAAA15);
  stop-opacity: 0;
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qir_1cb0f {
  stop-color: var(--svg-color--e26b25, #E26B25);
  stop-opacity: 0;
}

.ql4h4w3wf {
  stop-color: var(--svg-color--8f63e1, #8F63E1);
}

.qqqtnz_cz {
  stop-color: var(--svg-color--d27c28, #D27C28);
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

.qz5cyfb_z {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M25.478 15.788a1.31 1.31 0 1 0 0-2.619a1.31 1.31 0 0 0 0 2.62");
}

.r6-xa-gst {
  fill: var(--svg-color--bd4f26, #BD4F26);
  fill-rule: evenodd;
  d: path("m24.142 11.754l-.168.28za.327.327 0 0 1-.335.56h-.001l-.005-.002a2 2 0 0 0-.138-.072a3 3 0 0 0-.418-.164c-.354-.113-.82-.198-1.306-.112a.327.327 0 0 1-.114-.644c.626-.11 1.205 0 1.62.133a4 4 0 0 1 .68.29l.012.008l.003.002z");
}

.rf9pl1b2z {
  cx: 16.602px;
  cy: 13.634px;
  rx: 0.475px;
  ry: 0.24px;
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.rz5yb1b4g {
  d: path("M13.882 16.44a1.962 1.962 0 1 0 0-3.923a1.962 1.962 0 0 0 0 3.923");
}

.s3t3owbgt {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
  stop-opacity: 0;
}

.ss3ej3_3n {
  stop-color: var(--svg-color--7354a3, #7354A3);
  stop-opacity: 0;
}

.sufhn4bec {
  stop-color: var(--svg-color--db6009, #DB6009);
}

.sxoxd_kke {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
  stop-opacity: 0;
}

.t15q6w3yg {
  d: path("M13.392 12.94h.015l-.012-.324l-.013-.373c.025-1.157.7-1.604.988-1.754l.062-.025l.063-.024a2.8 2.8 0 0 0 1.45-1.505l.1-.237a.321.321 0 0 1 .562-.062a4.71 4.71 0 0 0 3.888 2.04h3.925c.22 0 1.32.106 1.385 1.624l-.145 3.746c-.15 3.416-2.818 5.71-6.075 5.71c-3.256 0-5.924-2.294-6.074-5.71z");
}

.t9grd_b1a {
  stop-color: var(--svg-color--674a85, #674A85);
  stop-opacity: 0;
}

.tgqxysbgm {
  stop-color: var(--svg-color--d76a18, #D76A18);
}

.tljjnprhh {
  stop-color: var(--svg-color--e9aa33, #E9AA33);
  stop-opacity: 0;
}

.tq56jpbfq {
  stop-color: var(--svg-color--d96d24, #D96D24);
  stop-opacity: 0;
}

.tw8grib3t {
  d: path("M20.558 21.026h.97c2.49 0 7.472 3.5 7.472 9H11.067v-3.5a.67.67 0 0 0-.414-.625L7.58 24.526c-2.49-1-3.487-3.5-3.487-5.198v-5.287c0-.564.424-1.015.932-1.015H9.14c.518 0 .932.462.932 1.015v3.985c0 1.302.996 1.5.996 1.5l5.978 1.5z");
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.u0tebcbmi {
  stop-color: var(--svg-color--855fcf, #855FCF);
}

.u8s8n3e7l {
  stop-color: var(--svg-color--9d74e7, #9D74E7);
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.uokhptbdi {
  stop-color: var(--svg-color--5f3b73, #5F3B73);
}

.uovxktaxm {
  stop-color: var(--svg-color--f2b830, #F2B830);
}

.uphj9jblf {
  stop-color: var(--svg-color--8f63e1, #8F63E1);
  stop-opacity: 0;
}

.uwvmppbhh {
  d: path("M23.224 14.114a1.02 1.02 0 0 0-.282-.564l-.316.347l.143.278z");
}

.uzy68hb9o {
  stop-color: var(--svg-color--e5a70f, #E5A70F);
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v3jqojv9j {
  stop-color: var(--svg-color--ffdc45, #FFDC45);
}

.v3wv1vqzi {
  fill: var(--svg-color--000, #000);
  d: path("M21.633 14.257a.62.62 0 0 1 .623-.623a.62.62 0 0 1 .554.91h-1.103a.56.56 0 0 1-.074-.287");
}

.v55yv8mfw {
  stop-color: var(--svg-color--bb7401, #BB7401);
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

.vsluyubzo {
  stop-color: var(--svg-color--f8a322, #F8A322);
  stop-opacity: 0;
}

.vvr4s2bpx {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M20.986 13.785c.323-.569.815-1.018 1.874-1.018c.463 0 .91.128 1.308.449c.327.265.283.604.03.73l-.678.388c-.795-.257-1.674-.292-2.534-.549");
}

.w2e_edyjl {
  stop-color: var(--svg-color--f09429, #F09429);
}

.w3-vy4c8j {
  stop-color: var(--svg-color--e38923, #E38923);
}

.w5d8oacwp {
  stop-color: var(--svg-color--a47ff0, #A47FF0);
}

.w72oynbwi {
  stop-color: var(--svg-color--e38923, #E38923);
  stop-opacity: 0;
}

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.wez3-gbsw {
  stop-color: var(--svg-color--efb234, #EFB234);
  stop-opacity: 0;
}

.wkdez3bsl {
  stop-color: var(--svg-color--f4b937, #F4B937);
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.x05md6_2b {
  stop-color: var(--svg-color--d97c39, #D97C39);
}

.x6dke3bsb {
  stop-color: var(--svg-color--7952b0, #7952B0);
  stop-opacity: 0;
}

.xbhzvqb7t {
  stop-color: var(--svg-color--ffc436, #FFC436);
}

.y2zvm24uz {
  stop-color: var(--svg-color--edad18, #EDAD18);
}

.y6udnebbh {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.508 12.838c.796 0 1.469.549 1.652 1.29a.334.334 0 0 1-.327.416h-2.72a.28.28 0 0 1-.276-.331a1.704 1.704 0 0 1 1.671-1.375");
}

.y7n0ymbzx {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
  stop-opacity: 0;
}

.yehxt3bls {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
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

.yv0tpg85m {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m19.115 14.207l-.833 2.072a.657.657 0 0 0 .634.853h.959a.66.66 0 0 0 .634-.853l-.648-2.072c-.138-.459-.6-.459-.746 0");
}

.z_yn3vbua {
  stop-color: var(--svg-color--ffcc3d, #FFCC3D);
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.z-gx2rb2w {
  stop-color: var(--svg-color--ffe337, #FFE337);
}

.z-nk_efhm {
  stop-color: var(--svg-color--d16c15, #D16C15);
}

</style>
