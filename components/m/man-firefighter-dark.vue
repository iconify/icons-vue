<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i5dTnUb)"><path fill="url(#iaUsmrb)" class="f1jw_ab3w"/><path fill="url(#iTDnx1x)" class="f1jw_ab3w"/></g><path class="b_qv5du4s"/><path fill="url(#i6KAjab)" class="faisxaclj"/><path fill="url(#iQYOIic)" class="faisxaclj"/><path fill="url(#iapQnke)" class="faisxaclj"/><path fill="url(#iiLw8Vb)" class="faisxaclj"/><path fill="url(#iAIO9Yd)" class="faisxaclj"/><path fill="url(#isZrtzc)" class="faisxaclj"/><path fill="url(#iJkm9gA)" class="cmsbox5av"/><path fill="url(#ih3vBxb)" class="cmsbox5av"/><path fill="url(#iov0n7a)" class="cmsbox5av"/><path fill="url(#inI3Unb)" class="vylrb5bvm"/><path fill="url(#iAOYtlU)" class="vylrb5bvm"/><path fill="url(#iWkx0Sd)" class="ix8bgh62p"/><g filter="url(#iaJDsMe)"><path clip-rule="evenodd" class="m8ff6u6wf"/><path fill="url(#iYgYbde)" clip-rule="evenodd" class="zdsg9r3jo"/><path fill="url(#iSuBe6b)" clip-rule="evenodd" class="zdsg9r3jo"/></g><path fill="url(#ixIpvFe)" class="re3g0rbfm"/><path fill="url(#ivW1LDc)" class="re3g0rbfm"/><g filter="url(#iu5QAZd)"><path fill="url(#icL13gd)" class="re3g0rbfm"/></g><g filter="url(#i9woRRC)"><circle fill="url(#izytkme)" class="jbixgesah"/></g><g filter="url(#iGvCm8b)"><circle fill="url(#iUvJtqd)" class="l3kcz_nzf"/></g><g filter="url(#iVcSwKw)"><circle fill="url(#iYfpgib)" class="uvhdvfbmh"/><circle fill="url(#isKpRvb)" class="uvhdvfbmh"/><circle fill="url(#ipY9Gme)" class="uvhdvfbmh"/></g><g filter="url(#i1hB8ld)"><circle fill="url(#ib3j3Vd)" class="tvi46ubab"/></g><g filter="url(#i4b6Z1d)"><path fill="url(#iT4RRre)" class="yctctdblc"/><path fill="url(#irnhBGx)" class="yctctdblc"/><path fill="url(#i9YhkVc)" class="yctctdblc"/><path fill="url(#iLEWLme)" class="yctctdblc"/><path fill="url(#iqA6Qzb)" class="yctctdblc"/><path fill="url(#iCKZwke)" class="yctctdblc"/></g><path fill="url(#i77XwZc)" class="yctctdblc"/><path fill="url(#ikJwECy)" class="yctctdblc"/><g filter="url(#iZI7Xpc)"><path class="s8j3qcb6d"/></g><g filter="url(#iDKBcoe)"><path class="iwpw-ubaa"/><path fill="url(#ib1kaGc)" class="bn5nbxdoc"/><path fill="url(#iGOs7sb)" class="bn5nbxdoc"/><path fill="url(#iHg1gab)" class="bn5nbxdoc"/><path fill="url(#i7cTJWb)" class="bn5nbxdoc"/></g><path fill="url(#iQfnS1L)" class="bn5nbxdoc"/><path stroke="url(#i2zdcMc)" class="fqsj8pbqd"/><path fill="url(#idGaYuO)" class="j2rc25bnh"/><path fill="url(#i9EOk8Q)" class="zhw1sbg1u"/><path class="maq1pudnw"/><path fill="url(#iFnxCHe)" class="kk7bxdzlm"/><path class="dr3hwgbeb"/><g filter="url(#iWoUUhe)"><path class="iscmujbth"/><path fill="url(#iTGmnvJ)" class="v75y37bpp"/></g><g filter="url(#iANbBBb)"><path fill="url(#ij1JdQc)" class="ssb7y629c"/></g><path class="jmsq5jc_t"/><path fill="url(#iuEIRrc)" class="kzz0wjbba"/><path class="gcbgjmd6q"/><g filter="url(#i1cIwnc)"><path fill="url(#iryFoKZ)" class="m_t8iw6rg"/></g><g filter="url(#izqGiPc)"><ellipse transform="rotate(-27.914 11.987 10.023)" class="xweobbcdr"/><ellipse fill="url(#i3XHD5d)" transform="rotate(-27.914 11.987 10.023)" class="hzlw7-kex"/></g><path fill="url(#iHZvJfc)" class="v5pkyqbhx"/><path fill="url(#ih5nvHe)" class="v5pkyqbhx"/><path fill="url(#izHz1gd)" class="v5pkyqbhx"/><path fill="url(#iEsU6Jd)" class="v5pkyqbhx"/><path fill="url(#ia6hdgb)" class="v5pkyqbhx"/><path class="e3e67-bvh"/><path fill="url(#inGX0Oc)" class="oyh5fnr6n"/><path fill="url(#i9mB5Mc)" class="oyh5fnr6n"/><path fill="url(#iUnDHVd)" class="oyh5fnr6n"/><path fill="url(#iKjUOTb)" class="oyh5fnr6n"/><path fill="url(#i1i1Lbq)" class="m94o2m2wq"/><path fill="url(#izpcbVd)" class="m94o2m2wq"/><path fill="url(#iZ6eZGb)" class="m94o2m2wq"/><path fill="url(#ibPujte)" class="m94o2m2wq"/><path fill="url(#i6qz0xW)" class="m94o2m2wq"/><path fill="url(#iMEPogb)" class="w_8w8wqmn"/><path fill="url(#iutMDkb)" class="w_8w8wqmn"/><path fill="url(#ih18itd)" class="w_8w8wqmn"/><g filter="url(#iCX6Prx)"><path fill="url(#iKGw4kt)" class="recb7tbvt"/><path fill="url(#iyoBo3i)" class="recb7tbvt"/></g><g filter="url(#i5n3J5b)"><path fill="url(#ibeddjd)" class="alecchcgl"/><path fill="url(#iO3rDAc)" class="alecchcgl"/></g><path fill="url(#iiVeO6c)" class="alecchcgl"/><path fill="url(#iZmNjZb)" class="alecchcgl"/><g filter="url(#iyLrWJc)"><path fill="url(#ibalbKd)" class="ow60pscre"/><path fill="url(#ifSfzbe)" class="ow60pscre"/><path fill="url(#iIi68Gb)" class="ow60pscre"/></g><g filter="url(#i2SElkb)"><path fill="url(#ibijqYb)" class="pqnwfi0qk"/><path fill="url(#iyoK4Kd)" class="pqnwfi0qk"/><path fill="url(#iJhoPse)" class="pqnwfi0qk"/></g><g filter="url(#iV1Bdjc)"><path fill="url(#iksW66c)" class="bo2opnr1i"/></g><g filter="url(#iFnuzLY)"><path stroke="url(#i2bdjSd)" class="cj_ualb6i"/></g><g filter="url(#iPqCKNe)"><path class="cd1yj8bur"/></g><path fill="url(#i0RrKOF)" class="jrru2bboo"/><path fill="url(#iVMDejt)" class="gdgw88t-a"/><defs><radialGradient id="i6KAjab" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.43636 -8.2868 0 14.582 15.942)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="ze-km1b7g"/><stop offset="1" class="nfddei0pp"/></radialGradient><radialGradient id="iQYOIic" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -8.375 13.302 26.253)" gradientUnits="userSpaceOnUse"><stop class="ls7-cblkb"/><stop offset="1" class="tbz0q_48a"/></radialGradient><radialGradient id="iapQnke" cx="0" cy="0" r="1" gradientTransform="matrix(-1.625 0 0 -5.46875 21.646 26.128)" gradientUnits="userSpaceOnUse"><stop class="voemc8h9d"/><stop offset="1" class="osd7ifb8c"/></radialGradient><radialGradient id="iiLw8Vb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.40626 -1.21873 1.72833 -6.24868 19.552 23.941)" gradientUnits="userSpaceOnUse"><stop offset=".273" class="d-ykpkboz"/><stop offset="1" class="f8x3opbgo"/></radialGradient><radialGradient id="iAIO9Yd" cx="0" cy="0" r="1" gradientTransform="matrix(-11.0625 0 0 -16.6672 18.302 22.722)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="eqb1ki6td"/><stop offset="1" class="dmxjdc_5c"/></radialGradient><radialGradient id="isZrtzc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55668 4.16175 -7.47563 -2.79621 19.02 16.26)" gradientUnits="userSpaceOnUse"><stop class="nuif9xlfl"/><stop offset="1" class="o41nkwbqu"/></radialGradient><radialGradient id="iJkm9gA" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.7832 3.37648 0 6.864 29.754)" gradientUnits="userSpaceOnUse"><stop offset=".658" class="q_n5wkbyq"/><stop offset="1" class="x8m9vebtt"/></radialGradient><radialGradient id="iov0n7a" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.8437 2.89364 0 7.607 29.972)" gradientUnits="userSpaceOnUse"><stop class="ygstjnb_e"/><stop offset="1" class="idk0shbpn"/></radialGradient><radialGradient id="inI3Unb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.40144 -2.74144 0 24.114 23.977)" gradientUnits="userSpaceOnUse"><stop class="deg-o6bbc"/><stop offset="1" class="q-uw1wb3b"/></radialGradient><radialGradient id="iAOYtlU" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.5625 -2.47704 0 21.577 22.972)" gradientUnits="userSpaceOnUse"><stop offset=".036" class="mr8fywmtc"/><stop offset="1" class="bcdc9wb8u"/></radialGradient><radialGradient id="iYgYbde" cx="0" cy="0" r="1" gradientTransform="matrix(1.27004 2.2186 -1.58976 .91006 11.157 16.066)" gradientUnits="userSpaceOnUse"><stop class="hq-8cac3q"/><stop offset="1" class="kiftlkrmt"/></radialGradient><radialGradient id="iSuBe6b" cx="0" cy="0" r="1" gradientTransform="matrix(2.40644 .94026 -.49363 1.26336 12.19 16.067)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><radialGradient id="ivW1LDc" cx="0" cy="0" r="1" gradientTransform="matrix(4.58258 0 0 1.4028 13.993 16.064)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><radialGradient id="icL13gd" cx="0" cy="0" r="1" gradientTransform="rotate(136.408 5.786 11.704)scale(4.35086 4.82952)" gradientUnits="userSpaceOnUse"><stop class="dxbo1t_fa"/><stop offset="1" class="kvhp_ip6r"/></radialGradient><radialGradient id="izytkme" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 8.021 10.802)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="isKpRvb" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 19.587 10.536)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="ipY9Gme" cx="0" cy="0" r="1" gradientTransform="rotate(128.073 7.975 9.627)scale(.59544 2.34217)" gradientUnits="userSpaceOnUse"><stop class="i00bm0a3x"/><stop offset="1" class="m0vjiyb4m"/></radialGradient><radialGradient id="ib3j3Vd" cx="0" cy="0" r="1" gradientTransform="matrix(.83594 .13978 -.10543 .6305 19.527 10.802)" gradientUnits="userSpaceOnUse"><stop offset=".305" class="euma_wpik"/><stop offset="1" class="lkizgebfg"/></radialGradient><radialGradient id="i9YhkVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.11187 -9.65399 0 14.143 10.602)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="g0r5sc7jj"/><stop offset="1" class="i5c5eto6f"/></radialGradient><radialGradient id="iLEWLme" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 16.793 9.529)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="iqA6Qzb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39218 1.7313 0 12.23 9.495)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="ikJwECy" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.25 12.31 0 14.47 15.535)" gradientUnits="userSpaceOnUse"><stop offset=".792" class="sq_vbdcff"/><stop offset="1" class="i3bem2dul"/></radialGradient><radialGradient id="i7cTJWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19709 -.6332 0 14.772 12.41)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="idGaYuO" cx="0" cy="0" r="1" gradientTransform="rotate(-152.286 10.134 1.986)scale(.82071 .62396)" gradientUnits="userSpaceOnUse"><stop class="l47dhac1k"/><stop offset="1" class="xj_ycu8_e"/></radialGradient><radialGradient id="i9EOk8Q" cx="0" cy="0" r="1" gradientTransform="rotate(-152.288 7.558 2.621)scale(.82075 .62396)" gradientUnits="userSpaceOnUse"><stop class="l47dhac1k"/><stop offset="1" class="xj_ycu8_e"/></radialGradient><radialGradient id="iFnxCHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8119 -1.29142 0 16.625 10.119)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iTGmnvJ" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 16.397 10.203)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iuEIRrc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81194 -1.29148 0 12.258 10.119)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i3XHD5d" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.075 -.724)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iHZvJfc" cx="0" cy="0" r="1" gradientTransform="rotate(116.696 8.04 7.094)scale(6.12125 6.5789)" gradientUnits="userSpaceOnUse"><stop class="zraasrypm"/><stop offset="1" class="wt7c97xxx"/></radialGradient><radialGradient id="izHz1gd" cx="0" cy="0" r="1" gradientTransform="matrix(.73215 -3.875 1.71541 .32411 8.289 7.066)" gradientUnits="userSpaceOnUse"><stop class="nl8hdv5-q"/><stop offset="1" class="kmg6h4b5x"/></radialGradient><radialGradient id="iEsU6Jd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.125 1.28124 -3.60476 -3.16519 19.646 3.097)" gradientUnits="userSpaceOnUse"><stop class="iyfczmh7s"/><stop offset="1" class="m2b3l_8kx"/></radialGradient><radialGradient id="ia6hdgb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.73438 4.0625 0 10.833 7.191)" gradientUnits="userSpaceOnUse"><stop class="n4fn3obqp"/><stop offset="1" class="h9dvmcbxu"/></radialGradient><radialGradient id="inGX0Oc" cx="0" cy="0" r="1" gradientTransform="matrix(-14.5563 0 0 -2.0625 21.577 27.816)" gradientUnits="userSpaceOnUse"><stop class="cv6gnzbto"/><stop offset="1" class="wl84mmb3d"/></radialGradient><radialGradient id="iKjUOTb" cx="0" cy="0" r="1" gradientTransform="rotate(104.338 -1.767 20.747)scale(7.1928 1.69685)" gradientUnits="userSpaceOnUse"><stop class="sl-gsib3f"/><stop offset="1" class="mr-s-pbar"/></radialGradient><radialGradient id="izpcbVd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.33866 0 0 -.95307 18.703 7.174)" gradientUnits="userSpaceOnUse"><stop offset=".169" class="xr_40cc2f"/><stop offset="1" class="kjxybmb-y"/></radialGradient><radialGradient id="iZ6eZGb" cx="0" cy="0" r="1" gradientTransform="matrix(1.03125 1.48437 -13.62738 9.46743 6.63 8.144)" gradientUnits="userSpaceOnUse"><stop class="ehnthvqoy"/><stop offset="1" class="rzbfz4btw"/></radialGradient><radialGradient id="ibPujte" cx="0" cy="0" r="1" gradientTransform="matrix(-.96093 -.6172 .84322 -1.31284 7.677 9.129)" gradientUnits="userSpaceOnUse"><stop offset=".501" class="rz-l4sb2t"/><stop offset="1" class="nqxo4gbph"/></radialGradient><radialGradient id="i6qz0xW" cx="0" cy="0" r="1" gradientTransform="matrix(.75 -.5625 1.05375 1.405 22.02 9.035)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="euqyawb2g"/><stop offset="1" class="vkwv3acem"/></radialGradient><radialGradient id="iutMDkb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.27624 -.62648 0 14.961 21.755)" gradientUnits="userSpaceOnUse"><stop class="krttc8bap"/><stop offset="1" class="kpneurz6b"/></radialGradient><radialGradient id="ih18itd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.41436 1.45816 0 14.582 25.827)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="ko6eamtic"/><stop offset="1" class="tc4y5tbfa"/></radialGradient><radialGradient id="iKGw4kt" cx="0" cy="0" r="1" gradientTransform="rotate(167.143 8.463 3.484)scale(2.97716 4.69784)" gradientUnits="userSpaceOnUse"><stop class="ism0j8_fd"/><stop offset="1" class="cc4vnjblc"/></radialGradient><radialGradient id="iyoBo3i" cx="0" cy="0" r="1" gradientTransform="matrix(2.81253 -2.28745 2.84526 3.49839 11.927 7.285)" gradientUnits="userSpaceOnUse"><stop class="kx5tbm42q"/><stop offset="1" class="ndetd3gmc"/></radialGradient><radialGradient id="iO3rDAc" cx="0" cy="0" r="1" gradientTransform="rotate(100.623 .526 19.635)scale(1.16051 4.42408)" gradientUnits="userSpaceOnUse"><stop class="pfbpewb0p"/><stop offset="1" class="dutea5bgy"/></radialGradient><radialGradient id="iiVeO6c" cx="0" cy="0" r="1" gradientTransform="matrix(-.83594 .34375 -.14238 -.34624 23.107 16.394)" gradientUnits="userSpaceOnUse"><stop class="xdf0lfbrm"/><stop offset="1" class="cvnvm48dp"/></radialGradient><radialGradient id="iZmNjZb" cx="0" cy="0" r="1" gradientTransform="matrix(.83594 .17968 -.05863 .27278 21.786 16.332)" gradientUnits="userSpaceOnUse"><stop class="leotspfhb"/><stop offset="1" class="u3sz7tboa"/></radialGradient><radialGradient id="ifSfzbe" cx="0" cy="0" r="1" gradientTransform="matrix(1.3287 1.76599 -.65664 .49404 19.852 16.946)" gradientUnits="userSpaceOnUse"><stop class="qu53-3efb"/><stop offset="1" class="d8vnolbdv"/></radialGradient><radialGradient id="iIi68Gb" cx="0" cy="0" r="1" gradientTransform="matrix(1.46875 .4375 -1.25756 4.22181 18.833 19.378)" gradientUnits="userSpaceOnUse"><stop class="fcewfubec"/><stop offset="1" class="ku_tac4_z"/></radialGradient><radialGradient id="ibijqYb" cx="0" cy="0" r="1" gradientTransform="rotate(135.9 10.028 15.777)scale(4.22106 5.23602)" gradientUnits="userSpaceOnUse"><stop class="ybzdb35ne"/><stop offset="1" class="k-xo7erne"/></radialGradient><radialGradient id="iyoK4Kd" cx="0" cy="0" r="1" gradientTransform="matrix(-4 -.68747 1.04434 -6.0764 28.646 22.504)" gradientUnits="userSpaceOnUse"><stop offset=".711" class="d7eq7sb9j"/><stop offset="1" class="pci0oxh-l"/></radialGradient><radialGradient id="iJhoPse" cx="0" cy="0" r="1" gradientTransform="rotate(156.903 12.063 12.55)scale(1.15509 2.08846)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="a6yl-cb9v"/><stop offset="1" class="w_w8qcl3c"/></radialGradient><radialGradient id="i0RrKOF" cx="0" cy="0" r="1" gradientTransform="rotate(-88.046 9.496 .427)scale(2.97829 .2991)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="o4001ccri"/><stop offset="1" class="ldoh6m8qh"/></radialGradient><radialGradient id="iVMDejt" cx="0" cy="0" r="1" gradientTransform="matrix(.45312 -1.90641 .64964 .15441 19.878 9.879)" gradientUnits="userSpaceOnUse"><stop class="g6vlzzbhl"/><stop offset="1" class="ug2jj9grv"/></radialGradient><linearGradient id="iaUsmrb" x1="14.587" x2="14.587" y1="7.972" y2="19.472" gradientUnits="userSpaceOnUse"><stop class="usw0jac_r"/><stop offset="1" class="zhmn0cciw"/></linearGradient><linearGradient id="iTDnx1x" x1="14.587" x2="14.587" y1="7.249" y2="10.843" gradientUnits="userSpaceOnUse"><stop class="l1qje4b6x"/><stop offset="1" class="vx6m-x__v"/></linearGradient><linearGradient id="ih3vBxb" x1="7.607" x2="6.489" y1="26.66" y2="26.629" gradientUnits="userSpaceOnUse"><stop class="gyzg0db3w"/><stop offset="1" class="y28tkbl-n"/></linearGradient><linearGradient id="iWkx0Sd" x1="15.654" x2="15.654" y1="15.025" y2="21.362" gradientUnits="userSpaceOnUse"><stop class="vq76pqe1z"/><stop offset=".456" class="kmmuo7biq"/><stop offset="1" class="c3htxbc9y"/></linearGradient><linearGradient id="ixIpvFe" x1="13.277" x2="13.489" y1="18.097" y2="18.097" gradientUnits="userSpaceOnUse"><stop class="lwl8ufbrj"/><stop offset="1" class="i5hn1bqvd"/></linearGradient><linearGradient id="iUvJtqd" x1="9.692" x2="9.051" y1="11.08" y2="11.08" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="iYfpgib" x1="20.302" x2="19.482" y1="9.709" y2="12.248" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="iT4RRre" x1="18.484" x2="10.84" y1="11.191" y2="12.331" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="irnhBGx" x1="9.043" x2="11.311" y1="13.89" y2="13.748" gradientUnits="userSpaceOnUse"><stop offset=".283" class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="iCKZwke" x1="14.473" x2="14.473" y1="-5.097" y2="17.412" gradientUnits="userSpaceOnUse"><stop offset=".979" class="wvw1ebchz"/><stop offset="1" class="y2xm7ibwq"/></linearGradient><linearGradient id="i77XwZc" x1="19.248" x2="18.428" y1="14.691" y2="14.613" gradientUnits="userSpaceOnUse"><stop class="nisg8c79u"/><stop offset="1" class="a2ma_0bsp"/></linearGradient><linearGradient id="ib1kaGc" x1="13.579" x2="14.518" y1="11.851" y2="11.851" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iGOs7sb" x1="15.384" x2="14.357" y1="12.174" y2="12.159" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="iHg1gab" x1="14.639" x2="14.639" y1="12.917" y2="12.343" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="iQfnS1L" x1="14.57" x2="14.57" y1="12.959" y2="12.791" gradientUnits="userSpaceOnUse"><stop class="zoxadnjxe"/><stop offset="1" class="gnvm67mtb"/></linearGradient><linearGradient id="i2zdcMc" x1="13.406" x2="13.842" y1="14.534" y2="13.845" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="ij1JdQc" x1="17.404" x2="17.09" y1="10.173" y2="10.366" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iryFoKZ" x1="13.003" x2="12.689" y1="10.173" y2="10.366" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ih5nvHe" x1="10.646" x2="16.989" y1="6.722" y2="6.722" gradientUnits="userSpaceOnUse"><stop class="ks1omcbjp"/><stop offset="1" class="jk0lbnbnn"/></linearGradient><linearGradient id="i9mB5Mc" x1="14.592" x2="14.592" y1="30.316" y2="28.722" gradientUnits="userSpaceOnUse"><stop class="s2qawgbpe"/><stop offset="1" class="iu5oamiyf"/></linearGradient><linearGradient id="iUnDHVd" x1="14.592" x2="14.592" y1="26.172" y2="27.441" gradientUnits="userSpaceOnUse"><stop class="tcape2laf"/><stop offset="1" class="gd-vr7bgk"/></linearGradient><linearGradient id="i1i1Lbq" x1="14.582" x2="14.582" y1="6.972" y2="11.754" gradientUnits="userSpaceOnUse"><stop offset=".526" class="ffurleovf"/><stop offset=".654" class="oirct-bua"/></linearGradient><linearGradient id="iMEPogb" x1="14.582" x2="14.582" y1="19.605" y2="26.175" gradientUnits="userSpaceOnUse"><stop class="jbzirjbuq"/><stop offset="1" class="s7s75dkrn"/></linearGradient><linearGradient id="ibeddjd" x1="22.021" x2="18.333" y1="16.754" y2="29.972" gradientUnits="userSpaceOnUse"><stop class="ommdktbpj"/><stop offset="1" class="dinvdlb3p"/></linearGradient><linearGradient id="ibalbKd" x1="20.021" x2="28.208" y1="22.191" y2="18.878" gradientUnits="userSpaceOnUse"><stop class="lf_6el-zz"/><stop offset="1" class="p6qk4rbue"/></linearGradient><linearGradient id="iksW66c" x1="14.458" x2="14.458" y1="4.22" y2="6.666" gradientUnits="userSpaceOnUse"><stop class="rx-q5b7rc"/><stop offset="1" class="fz8-ywb6c"/></linearGradient><linearGradient id="i2bdjSd" x1="18.689" x2="20.193" y1="21.647" y2="16.457" gradientUnits="userSpaceOnUse"><stop class="ih4zzfygk"/><stop offset="1" class="bq_18tbdo"/></linearGradient><filter id="i5dTnUb" width="17.197" height="11.9" x="5.989" y="7.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.137255 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2606"/></filter><filter id="iaJDsMe" width="6.88" height="3.666" x="11.157" y="15.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.0470588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2606"/></filter><filter id="iu5QAZd" width="4.97" height="3.828" x="13.277" y="15.814" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.12549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2606"/></filter><filter id="i9woRRC" width="3.542" height="3.342" x="8.021" y="9.13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2606"/></filter><filter id="iGvCm8b" width="2.992" height="2.992" x="8.196" y="9.306" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2606" stdDeviation=".25"/></filter><filter id="iVcSwKw" width="3.592" height="3.592" x="17.543" y="8.88" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2606"/></filter><filter id="i1hB8ld" width="2.492" height="2.492" x="17.968" y="9.556" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2606" stdDeviation=".125"/></filter><filter id="i4b6Z1d" width="10.378" height="12.189" x="9.281" y="5.172" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2606"/></filter><filter id="iZI7Xpc" width="3.262" height="4.184" x="12.574" y="9.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2606" stdDeviation=".375"/></filter><filter id="iDKBcoe" width="2.379" height="3.184" x="13.255" y="9.983" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2606" stdDeviation=".125"/></filter><filter id="iWoUUhe" width=".787" height=".697" x="15.891" y="9.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2606" stdDeviation=".05"/></filter><filter id="iANbBBb" width=".892" height=".914" x="16.731" y="9.754" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2606" stdDeviation=".1"/></filter><filter id="i1cIwnc" width=".987" height="1.041" x="12.285" y="9.691" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2606" stdDeviation=".1"/></filter><filter id="izqGiPc" width=".914" height=".705" x="11.53" y="9.671" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2606" stdDeviation=".05"/></filter><filter id="iCX6Prx" width="5.52" height="4.05" x="11.827" y="3.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.415686 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2606"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.2 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2606" result="effect2_innerShadow_4002_2606"/></filter><filter id="i5n3J5b" width="6.94" height="14.221" x="16.577" y="15.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.270588 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2606"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.266667 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2606" result="effect2_innerShadow_4002_2606"/></filter><filter id="iyLrWJc" width="11.012" height="8.855" x="17.86" y="16.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.0980392 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2606"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.270588 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2606" result="effect2_innerShadow_4002_2606"/></filter><filter id="i2SElkb" width="4.557" height="7.476" x="23.816" y="17.698" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.760784 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2606"/></filter><filter id="iV1Bdjc" width="2.509" height="3.213" x="13.154" y="3.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.141176 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_2606"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_2606" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.768627 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_2606"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.337255 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_2606" result="effect3_innerShadow_4002_2606"/></filter><filter id="iFnuzLY" width="1.83" height="4.718" x="18.091" y="17.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2606" stdDeviation=".125"/></filter><filter id="iPqCKNe" width="2.769" height="7.081" x="18.396" y="23.072" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2606" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-firefighter-dark" /></template>
<style>
.a2ma_0bsp {
  stop-color: var(--svg-color--513530, #513530);
  stop-opacity: 0;
}

.a6yl-cb9v {
  stop-color: var(--svg-color--eeecf0, #EEECF0);
}

.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.alecchcgl {
  d: path("m22.636 16.137l-1.38-.369a.51.51 0 0 0-.625.358l-3.804 13.846h2.547l3.63-13.211a.53.53 0 0 0-.368-.624");
}

.b_qv5du4s {
  fill: var(--svg-color--dc375e, #DC375E);
  d: path("M14.587 15.472c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.bcdc9wb8u {
  stop-color: var(--svg-color--d54161, #D54161);
  stop-opacity: 0;
}

.bn5nbxdoc {
  d: path("m14.062 10.516l-.532 1.701a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .52-.7l-.531-1.701c-.114-.377-.646-.377-.765 0");
}

.bo2opnr1i {
  d: path("M13.304 4.91c0-.154.183-.232.293-.126l.155.149a.162.162 0 0 0 .274-.117v-.17c0-.345.179-.665.472-.847l.18-.111a.23.23 0 0 1 .35.195v1.194a.17.17 0 0 0 .278.132l.096-.078a.129.129 0 0 1 .21.1v.333a1.154 1.154 0 0 1-2.308-.053z");
}

.bq_18tbdo {
  stop-color: var(--svg-color--cd517b, #CD517B);
  stop-opacity: 0;
}

.c3htxbc9y {
  stop-color: var(--svg-color--ec098c, #EC098C);
}

.cc4vnjblc {
  stop-color: var(--svg-color--524361, #524361);
}

.cd1yj8bur {
  stroke: var(--svg-color--87625e, #87625E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.921 29.629c0-.2 1.146-4.105 1.719-6.032");
}

.cdm_o50ho {
  stop-color: var(--svg-color--533531, #533531);
}

.cj_ualb6i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m19.546 17.972l-1.08 3.968");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cmsbox5av {
  d: path("M7.607 29.972V17.97a10.98 10.98 0 0 0-4.02 8.502v3.5z");
}

.cv6gnzbto {
  stop-color: var(--svg-color--fec852, #FEC852);
}

.cvnvm48dp {
  stop-color: var(--svg-color--a17d74, #A17D74);
  stop-opacity: 0;
}

.d-ykpkboz {
  stop-color: var(--svg-color--c6284c, #C6284C);
}

.d7eq7sb9j {
  stop-color: var(--svg-color--bab3b6, #BAB3B6);
  stop-opacity: 0;
}

.d8vnolbdv {
  stop-color: var(--svg-color--ed2e7c, #ED2E7C);
  stop-opacity: 0;
}

.deg-o6bbc {
  stop-color: var(--svg-color--f94d70, #F94D70);
}

.dinvdlb3p {
  stop-color: var(--svg-color--785253, #785253);
}

.dmxjdc_5c {
  stop-color: var(--svg-color--d0465e, #D0465E);
}

.dr3hwgbeb {
  fill: var(--svg-color--000, #000);
  d: path("M16.116 10.535a.51.51 0 0 1 .511-.512a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.061-.235");
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.dutea5bgy {
  stop-color: var(--svg-color--734145, #734145);
  stop-opacity: 0;
}

.dxbo1t_fa {
  stop-color: var(--svg-color--ff547f, #FF547F);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e3e67-bvh {
  fill: var(--svg-color--ecb845, #ECB845);
  d: path("M21.577 26.172H7.607v3.8h13.97z");
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.ehnthvqoy {
  stop-color: var(--svg-color--b3576b, #B3576B);
}

.eqb1ki6td {
  stop-color: var(--svg-color--d0465e, #D0465E);
  stop-opacity: 0;
}

.euma_wpik {
  stop-color: var(--svg-color--3f2a2b, #3F2A2B);
}

.euqyawb2g {
  stop-color: var(--svg-color--be1e3b, #BE1E3B);
}

.f1jw_ab3w {
  d: path("M22.174 7.972H7.152c-.395.32-.78 1.337-1.163 1.657v1.343c0 4.69 3.854 8.5 8.598 8.5s8.598-3.81 8.598-8.5V9.63c-.354-.42-.687-1.207-1.011-1.657");
}

.f8x3opbgo {
  stop-color: var(--svg-color--c6284c, #C6284C);
  stop-opacity: 0;
}

.faisxaclj {
  d: path("M14.587 15.472c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.fcewfubec {
  stop-color: var(--svg-color--c93271, #C93271);
}

.ffurleovf {
  stop-color: var(--svg-color--bb2b57, #BB2B57);
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.fqsj8pbqd {
  fill: var(--svg-color--2a0219, #2A0219);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.081 13.561c.394.206.863.323 1.363.323c.505 0 .97-.117 1.364-.323a.2.2 0 0 1 .242.04a.19.19 0 0 1 .02.242m-2.989-.282l2.948.254m-2.948-.254a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24m.262-.282l-.221.254m3.21.028l-.041-.028m.041.028l-.041-.028m.041.028a1.95 1.95 0 0 1-1.626.868a1.95 1.95 0 0 1-1.626-.868m3.21-.028a1.89 1.89 0 0 1-1.584.847c-.665 0-1.249-.34-1.584-.847m-.042.028l.042-.028m-.042.028l.042-.028");
}

.ft5dv1b6b {
  fill: none;
}

.fz8-ywb6c {
  stop-color: var(--svg-color--f48942, #F48942);
}

.g0r5sc7jj {
  stop-color: var(--svg-color--3d2138, #3D2138);
  stop-opacity: 0;
}

.g6vlzzbhl {
  stop-color: var(--svg-color--272324, #272324);
}

.gcbgjmd6q {
  fill: var(--svg-color--000, #000);
  d: path("M12.768 10.535a.51.51 0 0 0-.512-.512a.51.51 0 0 0-.454.747h.905a.5.5 0 0 0 .06-.235");
}

.gd-vr7bgk {
  stop-color: var(--svg-color--edb63d, #EDB63D);
  stop-opacity: 0;
}

.gdgw88t-a {
  d: path("M19.358 7.972h1.148l.085.002a24 24 0 0 1-.432 1.772c-.112.356-.455.457-.601.465c.016-.32.045-1.097.045-1.553c0-.356-.13-.574-.245-.686");
}

.gnvm67mtb {
  stop-color: var(--svg-color--31171f, #31171F);
  stop-opacity: 0;
}

.gyzg0db3w {
  stop-color: var(--svg-color--bf415a, #BF415A);
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.h9dvmcbxu {
  stop-color: var(--svg-color--c52632, #C52632);
  stop-opacity: 0;
}

.hq-8cac3q {
  stop-color: var(--svg-color--c75567, #C75567);
}

.hzlw7-kex {
  cx: 11.987px;
  cy: 10.023px;
  rx: 0.39px;
  ry: 0.197px;
}

.i00bm0a3x {
  stop-color: var(--svg-color--361919, #361919);
}

.i3bem2dul {
  stop-color: var(--svg-color--331b23, #331B23);
}

.i5c5eto6f {
  stop-color: var(--svg-color--3d2138, #3D2138);
}

.i5hn1bqvd {
  stop-color: var(--svg-color--ca435d, #CA435D);
  stop-opacity: 0;
}

.idk0shbpn {
  stop-color: var(--svg-color--c03959, #C03959);
  stop-opacity: 0;
}

.ih4zzfygk {
  stop-color: var(--svg-color--cd517b, #CD517B);
}

.iscmujbth {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.562 9.83c.063.085-.07.19-.22.302c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.36c.151-.112.325-.135.389-.05");
}

.ism0j8_fd {
  stop-color: var(--svg-color--675b70, #675B70);
}

.iu5oamiyf {
  stop-color: var(--svg-color--d9a73c, #D9A73C);
  stop-opacity: 0;
}

.iwpw-ubaa {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m14.062 10.516l-.532 1.701a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .52-.7l-.531-1.701c-.114-.377-.646-.377-.765 0");
}

.ix8bgh62p {
  d: path("M13.277 15.972v2.66c0 .56.45 1.01 1.01 1.01h1.78c1.09 0 1.98-.89 1.98-1.98v-1.69z");
}

.iyfczmh7s {
  stop-color: var(--svg-color--fd5c7c, #FD5C7C);
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j2rc25bnh {
  d: path("M18.168 7.867h-.002l-.002-.002l-.004-.004l-.012-.01a1.4 1.4 0 0 0-.155-.107c-.1-.062-.241-.14-.42-.21a2.84 2.84 0 0 0-1.494-.16a.534.534 0 1 0 .166 1.056c.398-.063.717.01.935.097a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .68-.825");
}

.j5-d0iboi {
  stop-color: var(--svg-color--c71931, #C71931);
  stop-opacity: 0;
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
}

.jbixgesah {
  cx: 9.692px;
  cy: 10.802px;
  r: 1.671px;
}

.jbzirjbuq {
  stop-color: var(--svg-color--ba2f50, #BA2F50);
}

.jk0lbnbnn {
  stop-color: var(--svg-color--be324c, #BE324C);
  stop-opacity: 0;
}

.jmsq5jc_t {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.05 9.37c-.654 0-1.207.45-1.357 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.272A1.4 1.4 0 0 0 12.05 9.37");
}

.jrru2bboo {
  d: path("M9.566 7.972h-.908q-.16 0-.321.02c.098.497.322 1.419.428 1.754a.67.67 0 0 0 .578.468c-.016-.32-.022-1.1-.022-1.556c0-.356.13-.574.245-.686");
}

.k-xo7erne {
  stop-color: var(--svg-color--cdc6d4, #CDC6D4);
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.kiftlkrmt {
  stop-color: var(--svg-color--c75567, #C75567);
  stop-opacity: 0;
}

.kjxybmb-y {
  stop-color: var(--svg-color--fc5083, #FC5083);
  stop-opacity: 0;
}

.kk7bxdzlm {
  d: path("M16.627 9.641a.893.893 0 0 1 .861 1.129h-1.725a.897.897 0 0 1 .865-1.129");
}

.kmg6h4b5x {
  stop-color: var(--svg-color--bd585d, #BD585D);
  stop-opacity: 0;
}

.kmmuo7biq {
  stop-color: var(--svg-color--ed1452, #ED1452);
}

.ko6eamtic {
  stop-color: var(--svg-color--ab0d36, #AB0D36);
  stop-opacity: 0;
}

.kpneurz6b {
  stop-color: var(--svg-color--c1415c, #C1415C);
  stop-opacity: 0;
}

.krttc8bap {
  stop-color: var(--svg-color--c1415c, #C1415C);
}

.ks1omcbjp {
  stop-color: var(--svg-color--be324c, #BE324C);
}

.ku_tac4_z {
  stop-color: var(--svg-color--c93271, #C93271);
  stop-opacity: 0;
}

.kvhp_ip6r {
  stop-color: var(--svg-color--df3d67, #DF3D67);
}

.kx5tbm42q {
  stop-color: var(--svg-color--3d2b40, #3D2B40);
}

.kzz0wjbba {
  d: path("M12.256 9.641a.893.893 0 0 0-.86 1.13h1.725a1 1 0 0 0 .032-.236a.9.9 0 0 0-.897-.894");
}

.l1qje4b6x {
  stop-color: var(--svg-color--710425, #710425);
}

.l3kcz_nzf {
  cx: 9.692px;
  cy: 10.802px;
  r: 0.996px;
}

.l47dhac1k {
  stop-color: var(--svg-color--222022, #222022);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.ldoh6m8qh {
  stop-color: var(--svg-color--10070e, #10070E);
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.leotspfhb {
  stop-color: var(--svg-color--8c5e57, #8C5E57);
}

.lf_6el-zz {
  stop-color: var(--svg-color--ee2f8c, #EE2F8C);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkizgebfg {
  stop-color: var(--svg-color--341b1e, #341B1E);
}

.ls7-cblkb {
  stop-color: var(--svg-color--dd365e, #DD365E);
}

.lwl8ufbrj {
  stop-color: var(--svg-color--ca435d, #CA435D);
}

.m_t8iw6rg {
  d: path("M13.072 10.43c0-.289-.235-.481-.298-.54l-.289.28l.178.361z");
}

.m0vjiyb4m {
  stop-color: var(--svg-color--361919, #361919);
  stop-opacity: 0;
}

.m2b3l_8kx {
  stop-color: var(--svg-color--fd5c7c, #FD5C7C);
  stop-opacity: 0;
}

.m8ff6u6wf {
  fill: var(--svg-color--d53260, #D53260);
  fill-rule: evenodd;
  d: path("M11.157 16.066v1.586c0 1.09.89 1.98 1.98 1.98h2.92c1.09 0 1.98-.88 1.98-1.98v-1.58a3.94 3.94 0 0 1-2.488.88h-1.896c-.942 0-1.813-.33-2.496-.886");
}

.m94o2m2wq {
  d: path("M8.659 7.972h11.846c.95 0 1.99.485 1.99 2.68h.69V9.347c0-1.43-.847-2.375-2.456-2.375H8.435c-1.609 0-2.456.946-2.456 2.375v1.305h.69c0-2.195 1.04-2.68 1.99-2.68");
}

.maq1pudnw {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.834 9.37c.654 0 1.206.45 1.356 1.059a.274.274 0 0 1-.268.341H15.69a.23.23 0 0 1-.228-.272a1.4 1.4 0 0 1 1.372-1.128");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mr-s-pbar {
  stop-color: var(--svg-color--bc832d, #BC832D);
  stop-opacity: 0;
}

.mr8fywmtc {
  stop-color: var(--svg-color--b91a3e, #B91A3E);
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n4fn3obqp {
  stop-color: var(--svg-color--c52632, #C52632);
}

.ndetd3gmc {
  stop-color: var(--svg-color--3d2b40, #3D2B40);
  stop-opacity: 0;
}

.nfddei0pp {
  stop-color: var(--svg-color--c51b40, #C51B40);
  stop-opacity: 0;
}

.nisg8c79u {
  stop-color: var(--svg-color--5e4744, #5E4744);
}

.nl8hdv5-q {
  stop-color: var(--svg-color--bd585d, #BD585D);
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.nqxo4gbph {
  stop-color: var(--svg-color--a21e3e, #A21E3E);
  stop-opacity: 0;
}

.nuif9xlfl {
  stop-color: var(--svg-color--ff385e, #FF385E);
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o4001ccri {
  stop-color: var(--svg-color--362b29, #362B29);
}

.o41nkwbqu {
  stop-color: var(--svg-color--ff385e, #FF385E);
  stop-opacity: 0;
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oirct-bua {
  stop-color: var(--svg-color--bb2b57, #BB2B57);
  stop-opacity: 0;
}

.ommdktbpj {
  stop-color: var(--svg-color--8f5b56, #8F5B56);
}

.osd7ifb8c {
  stop-color: var(--svg-color--d23b59, #D23B59);
  stop-opacity: 0;
}

.ow60pscre {
  d: path("m20.012 16.732l4.416 1.16a3.56 3.56 0 0 0 2.071-.053l.148-.055c.179-.062.401-.053.555.108c1.071 1.125 1.43 2.62.983 4.235s-1.732 2.765-2.98 3.034c-.084.02-.348.045-.505-.158l-.142-.14a3.5 3.5 0 0 0-1.745-1.11L18.57 22.55a.61.61 0 0 1-.43-.78l1.25-4.674c.045-.22.37-.43.622-.364");
}

.oyh5fnr6n {
  d: path("M21.577 26.172H7.607v3.8h13.97z");
}

.p6qk4rbue {
  stop-color: var(--svg-color--fc3d5f, #FC3D5F);
}

.pci0oxh-l {
  stop-color: var(--svg-color--a39ba9, #A39BA9);
}

.pfbpewb0p {
  stop-color: var(--svg-color--734145, #734145);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pqnwfi0qk {
  d: path("M25.649 18.01a3.5 3.5 0 0 0 .85-.171l.148-.055c.179-.062.401-.053.555.108c1.071 1.125 1.43 2.62.983 4.235s-1.732 2.765-2.98 3.034c-.084.02-.348.045-.505-.158l-.142-.14a3.5 3.5 0 0 0-.642-.588c1.567-.052 2.817-1.084 3.203-2.53c.39-1.468-.236-3.002-1.472-3.735z");
}

.q_n5wkbyq {
  stop-color: var(--svg-color--d93b60, #D93B60);
}

.q-uw1wb3b {
  stop-color: var(--svg-color--c7425f, #C7425F);
}

.qu53-3efb {
  stop-color: var(--svg-color--fc4b93, #FC4B93);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.re3g0rbfm {
  d: path("M13.277 16.934v1.698c0 .56.45 1.01 1.01 1.01h1.78c1.09 0 1.98-.89 1.98-1.98v-1.598a3.94 3.94 0 0 1-2.498.887h-1.896q-.19 0-.376-.017");
}

.recb7tbvt {
  d: path("M17.247 6.972h-5.32v-1.29c0-1.47 1.19-2.66 2.66-2.66s2.66 1.19 2.66 2.66z");
}

.rx-q5b7rc {
  stop-color: var(--svg-color--f1b244, #F1B244);
}

.rz-l4sb2t {
  stop-color: var(--svg-color--a21e3e, #A21E3E);
}

.rzbfz4btw {
  stop-color: var(--svg-color--b3576b, #B3576B);
  stop-opacity: 0;
}

.s2qawgbpe {
  stop-color: var(--svg-color--b78426, #B78426);
}

.s7s75dkrn {
  stop-color: var(--svg-color--b93054, #B93054);
}

.s8j3qcb6d {
  fill: var(--svg-color--332024, #332024);
  d: path("m14.169 10.68l-.821 1.7c-.102.35.142.7.488.7h.738c.346 0 .59-.355.489-.7l-.5-1.7c-.106-.378-.282-.378-.394 0");
}

.sl-gsib3f {
  stop-color: var(--svg-color--bc832d, #BC832D);
}

.sq_vbdcff {
  stop-color: var(--svg-color--331b23, #331B23);
  stop-opacity: 0;
}

.ssb7y629c {
  d: path("M17.423 10.417a.84.84 0 0 0-.232-.463l-.26.285l.118.229z");
}

.tbz0q_48a {
  stop-color: var(--svg-color--dd365e, #DD365E);
  stop-opacity: 0;
}

.tc4y5tbfa {
  stop-color: var(--svg-color--ab0d36, #AB0D36);
}

.tcape2laf {
  stop-color: var(--svg-color--edb63d, #EDB63D);
}

.tvi46ubab {
  cx: 19.214px;
  cy: 10.802px;
  r: 0.996px;
}

.u3sz7tboa {
  stop-color: var(--svg-color--8c5e57, #8C5E57);
  stop-opacity: 0;
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.ug2jj9grv {
  stop-color: var(--svg-color--160508, #160508);
}

.usw0jac_r {
  stop-color: var(--svg-color--a9112c, #A9112C);
}

.uvhdvfbmh {
  cx: 19.214px;
  cy: 10.802px;
  r: 1.671px;
}

.v5pkyqbhx {
  d: path("M20.885 7.332H8.29v-.377c0-2.734 2.01-4.928 5.02-4.928h2.411c3.329 0 5.165 2.194 5.165 4.928z");
}

.v75y37bpp {
  d: path("M16.562 9.83c.063.085-.07.19-.22.302c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.36c.151-.112.325-.135.389-.05");
}

.vkwv3acem {
  stop-color: var(--svg-color--be1e3b, #BE1E3B);
  stop-opacity: 0;
}

.voemc8h9d {
  stop-color: var(--svg-color--d23b59, #D23B59);
}

.vq76pqe1z {
  stop-color: var(--svg-color--ed1c26, #ED1C26);
}

.vx6m-x__v {
  stop-color: var(--svg-color--a81330, #A81330);
  stop-opacity: 0;
}

.vylrb5bvm {
  d: path("M21.577 17.982v11.99h4v-3.5a10.98 10.98 0 0 0-4-8.49");
}

.w_8w8wqmn {
  d: path("M15.167 19.605h-1.17v6.57h1.17z");
}

.w_w8qcl3c {
  stop-color: var(--svg-color--eeecf0, #EEECF0);
  stop-opacity: 0;
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.wl84mmb3d {
  stop-color: var(--svg-color--fec852, #FEC852);
  stop-opacity: 0;
}

.wt7c97xxx {
  stop-color: var(--svg-color--f44f5a, #F44F5A);
}

.wvw1ebchz {
  stop-color: var(--svg-color--624d68, #624D68);
  stop-opacity: 0;
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.x8m9vebtt {
  stop-color: var(--svg-color--df6277, #DF6277);
}

.xdf0lfbrm {
  stop-color: var(--svg-color--a17d74, #A17D74);
}

.xj_ycu8_e {
  stop-color: var(--svg-color--140b19, #140B19);
}

.xr_40cc2f {
  stop-color: var(--svg-color--fc5083, #FC5083);
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.xweobbcdr {
  cx: 11.987px;
  cy: 10.023px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.y28tkbl-n {
  stop-color: var(--svg-color--bf415a, #BF415A);
  stop-opacity: 0;
}

.y2xm7ibwq {
  stop-color: var(--svg-color--624d68, #624D68);
}

.ybzdb35ne {
  stop-color: var(--svg-color--ded9e3, #DED9E3);
}

.yctctdblc {
  d: path("M9.281 8.749c0-.267.108-.722.323-.882l.16-.16c.27-.214.377-.4.377-.72v-.854a.52.52 0 0 1 .43-.534c.643-.16 1.986-.427 3.919-.427c1.932 0 3.275.267 3.919.427c.215.053.43.267.43.534v.854c0 .32.16.64.375.854c.503.352.459.545.43.96c-.125 1.804-.235 3.606-.356 5.404c-.16 1.771-1.553 3.006-3.213 3.006h-3.213c-1.714 0-3.053-1.234-3.214-3.006c-.14-1.818-.309-3.748-.367-5.456");
}

.ygstjnb_e {
  stop-color: var(--svg-color--99344a, #99344A);
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zdsg9r3jo {
  fill-rule: evenodd;
  d: path("M11.157 16.066v1.586c0 1.09.89 1.98 1.98 1.98h2.92c1.09 0 1.98-.88 1.98-1.98v-1.58a3.94 3.94 0 0 1-2.488.88h-1.896c-.942 0-1.813-.33-2.496-.886");
}

.ze-km1b7g {
  stop-color: var(--svg-color--c51b40, #C51B40);
}

.zhmn0cciw {
  stop-color: var(--svg-color--a11339, #A11339);
}

.zhw1sbg1u {
  d: path("M10.667 7.868v-.002l.003-.001l.004-.004l.012-.01a1.3 1.3 0 0 1 .155-.107c.1-.062.241-.14.42-.21c.36-.143.873-.257 1.494-.16a.534.534 0 0 1-.166 1.056a1.77 1.77 0 0 0-.935.097a1.5 1.5 0 0 0-.3.16l-.008.005a.534.534 0 0 1-.68-.824");
}

.zj8ulgbnv {
  stop-color: var(--svg-color--c71931, #C71931);
}

.zoxadnjxe {
  stop-color: var(--svg-color--31171f, #31171F);
}

.zraasrypm {
  stop-color: var(--svg-color--f0406f, #F0406F);
}

</style>
