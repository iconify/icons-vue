<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-rule="evenodd" filter="url(#iqPcxWb)" class="d2kvgvbvc"><path fill="url(#if37vng)" class="bgu-wppft"/><path fill="url(#i1752ab)" class="bgu-wppft"/><path fill="url(#iwAlyjb)" class="bgu-wppft"/><path fill="url(#iKlVwDc)" class="bgu-wppft"/><path fill="url(#iUoPrUd)" class="bgu-wppft"/><path fill="url(#iJkJ3be)" class="bgu-wppft"/><path fill="url(#ikpbhkb)" class="bgu-wppft"/><path fill="url(#igIRTGb)" class="bgu-wppft"/><path fill="url(#iHK2gZd)" class="bgu-wppft"/><path fill="url(#iLdZsFd)" class="bgu-wppft"/><path fill="url(#iqSLjTd)" class="bgu-wppft"/><path fill="url(#iTYYcAc)" class="bgu-wppft"/></g><path fill="url(#imTZFte)" class="c723gdbru"/><path fill="url(#iaLRKze)" class="c723gdbru"/><path fill="url(#i6xU0ze)" class="s0czm0m0d"/><path fill="url(#idDXzmR)" class="s0czm0m0d"/><g filter="url(#iLNf4fe)"><path fill="url(#idj3lje)" class="la6anvnfv"/></g><g filter="url(#iLUczGd)"><path fill="url(#iCxqvsc)" class="ucqc4tbff"/><path fill="url(#i8BWa9b)" class="ucqc4tbff"/></g><g filter="url(#iBsCRpb)"><path class="ldbnk6ogt"/><path fill="url(#i1QIYKd)" class="l1frur-bm"/></g><g filter="url(#iriNaod)"><path class="cak2zib2f"/><path fill="url(#ikGPidc)" class="r7ne7db4d"/></g><g filter="url(#iOzvctb)"><path fill="url(#izK5mnd)" class="ay-7q2jga"/><path fill="url(#iswadkb)" class="ay-7q2jga"/><path fill="url(#ixudYde)" class="ay-7q2jga"/><path fill="url(#ielbTMb)" class="ay-7q2jga"/><path fill="url(#iBcx89c)" class="ay-7q2jga"/></g><path fill="url(#iv0F2Jb)" class="ymidocb-e"/><path fill="url(#i4lCBvb)" class="ymidocb-e"/><g filter="url(#iNDD3qe)"><path class="s1z0g59pt"/></g><g filter="url(#iwWaTFd)"><path class="hx8phqbfz"/><path fill="url(#i83eNWc)" class="m1p0iqb0j"/><path fill="url(#isXWd2d)" class="m1p0iqb0j"/><path fill="url(#iRPpU7c)" class="m1p0iqb0j"/></g><g filter="url(#iYHgEhK)"><path fill="url(#iipUz9b)" class="iq1xl0byh"/></g><g filter="url(#iZh7nId)"><path stroke="url(#i97qSdc)" class="rlkxcjbek"/></g><path class="qbj7jig8q"/><g filter="url(#ikeeFGd)"><path class="wv-vkgbpx"/></g><g filter="url(#itvUqoh)"><path class="lgr3tsbdq"/></g><g filter="url(#ihArUMe)"><path fill="url(#iHAwaYd)" class="y-e90cbvt"/><path fill="url(#itPdsme)" class="y-e90cbvt"/></g><g filter="url(#iqmy0bb)"><path fill="url(#impSfob)" class="adtex6bqi"/><path fill="url(#ipj0sCd)" class="adtex6bqi"/><path fill="url(#iwvArDc)" class="adtex6bqi"/></g><g filter="url(#ifunmfe)"><path stroke="url(#iOlvz4c)" class="dqt437r8o"/></g><g filter="url(#iL5NS3b)"><path fill="url(#iq9JBGe)" class="x3-dq7n1x"/></g><g filter="url(#iiI9BIc)"><path fill="url(#i7mHBWb)" class="lz8ivtecs"/></g><path fill="url(#iJaxaob)" class="z-0xo4bpn"/><path fill="url(#iCCBk4c)" class="by-r3et3v"/><g filter="url(#iIu7l1b)" class="tryqaac1t"><path stroke="url(#i07g6Je)" class="hi3ka0bpk"/><path stroke="url(#idNTC3d)" class="hi3ka0bpk"/></g><g filter="url(#iClNXrc)" class="tryqaac1t"><path stroke="url(#irT8t0c)" class="qa8u2ebfn"/><path stroke="url(#i27H3Yd)" class="qa8u2ebfn"/></g><g filter="url(#ivjQWkd)"><path clip-rule="evenodd" class="h-exvsxip"/></g><g filter="url(#iTbpHod)"><path class="c4nwy9mhc"/></g><path class="edbi1ib2g"/><path fill="url(#iyRmQPe)" class="j0lymcp5d"/><path fill="url(#izxftWc)" class="j0lymcp5d"/><path fill="url(#iCOuGie)" class="j0lymcp5d"/><path fill="url(#ijSbhre)" class="j0lymcp5d"/><path fill="url(#ivHoDpc)" class="j0lymcp5d"/><path fill="url(#iPBG4Zd)" class="j0lymcp5d"/><path fill="url(#ir0Shvd)" class="j0lymcp5d"/><g filter="url(#iFkhanJ)"><path fill="url(#im8rVox)" class="lzuhtkbmu"/><path fill="url(#iiqxDtb)" class="lzuhtkbmu"/><path fill="url(#i2LMlIe)" class="lzuhtkbmu"/></g><path fill="url(#igsDegd)" class="ee70nabjp"/><g filter="url(#iWZuhTd)"><path fill="url(#iwMnVlc)" class="mdfm2pbfq"/><path fill="url(#isznxje)" class="mdfm2pbfq"/></g><g filter="url(#iAeVIde)"><path class="azwbilbkt"/><path fill="url(#iMeOWgc)" class="e_nsx25xe"/><path fill="url(#i2cAfUb)" class="e_nsx25xe"/><path fill="url(#iZkHDBb)" class="e_nsx25xe"/><path fill="url(#iWVYXHe)" class="e_nsx25xe"/></g><path fill="url(#i26Sduz)" class="c-xn1hpqp"/><path fill="url(#iCVqPpc)" class="c-xn1hpqp"/><path fill="url(#i7K3wIe)" class="zi044qmod"/><path fill="url(#iFG0Q0L)" class="zi044qmod"/><path fill="url(#ijooSPL)" class="z_ej81lhd"/><path fill="url(#iLcy3Dd)" class="z_ej81lhd"/><path fill="url(#iFe6Avb)" class="z_ej81lhd"/><path fill="url(#ijSOv4t)" class="z_ej81lhd"/><path fill="url(#i8tV5Lb)" class="z_ej81lhd"/><path fill="url(#i9al3pi)" class="fhnbafbir"/><path fill="url(#iHapy0c)" class="gw7tuorde"/><path fill="url(#iLMBpdc)" class="h8ckk2b2m"/><path fill="url(#iuyQgEe)" class="h8ckk2b2m"/><path fill="url(#im7kFed)" class="h8ckk2b2m"/><g filter="url(#i8Wqe3d)"><path stroke="url(#ivUH7oe)" class="anickvn2b"/></g><path fill="url(#iI7H0Cd)" class="jpk0vvtmk"/><path fill="url(#irUt5Gn)" class="jpk0vvtmk"/><path fill="url(#iSzC7rb)" class="g6lnibn2h"/><g filter="url(#ieh44Me)"><path fill="url(#iA2TIDc)" class="i85grmbtl"/><path fill="url(#iSohqnb)" class="i85grmbtl"/><path fill="url(#iXBybad)" class="i85grmbtl"/></g><path fill="url(#i7WGgxe)" class="q6xuj5bcq"/><path fill="url(#iVxkvRd)" class="q6xuj5bcq"/><path fill="url(#i49NPfd)" class="q6xuj5bcq"/><path fill="url(#iFu8etd)" class="q6xuj5bcq"/><path fill="url(#i1RjTAe)" class="q6xuj5bcq"/><path class="jppjnwbry"/><path fill="url(#ib5aaPb)" class="rgj3eviuu"/><path fill="url(#ijNHkXc)" class="rgj3eviuu"/><path class="gve5e0nxd"/><path fill="url(#ixvKXid)" class="euvncsbod"/><path fill="url(#iXu7Une)" class="euvncsbod"/><path fill="url(#iXHBdAe)" class="skpmm1_2p"/><path fill="url(#iHwtmXc)" class="skpmm1_2p"/><path fill="url(#ivZWVuc)" class="skpmm1_2p"/><path fill="url(#i2ib0uc)" class="skpmm1_2p"/><path fill="url(#iHjmPhb)" class="zl0m7hb-l"/><path fill="url(#ibOJGde)" class="zl0m7hb-l"/><path fill="url(#igmmlic)" class="zl0m7hb-l"/><path fill="url(#iRlP4lc)" class="zl0m7hb-l"/><path fill="url(#iO4y5tb)" class="v4sppzb3c"/><path fill="url(#iHEhwUc)" class="v4sppzb3c"/><path fill="url(#i4LlWSI)" class="v4sppzb3c"/><path fill="url(#i78CRmX)" class="v4sppzb3c"/><g filter="url(#iKLg2Sc)"><path stroke="url(#iJpfxxe)" class="hwci58euz"/></g><g filter="url(#iB99hdb)" class="mc2zb0bvp"><path class="mmhc2bhnh"/></g><g filter="url(#ioAe8Fb)" class="mc2zb0bvp"><path class="e5lh0tbhf"/></g><defs><radialGradient id="i1752ab" cx="0" cy="0" r="1" gradientTransform="rotate(-74.596 20.722 -4.946)scale(4.1071 9.36445)" gradientUnits="userSpaceOnUse"><stop class="rjxj417_v"/><stop offset="1" class="p1sg1mumi"/></radialGradient><radialGradient id="iwAlyjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.90035 5.8375 -5.46427 -.84279 13.851 13.248)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="ta36f8b7v"/><stop offset="1" class="hcuenbefp"/></radialGradient><radialGradient id="iKlVwDc" cx="0" cy="0" r="1" gradientTransform="rotate(131.861 2.502 9.938)scale(4.07798 5.01977)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="hxuphr-8h"/><stop offset="1" class="v-9s4u7ch"/></radialGradient><radialGradient id="iUoPrUd" cx="0" cy="0" r="1" gradientTransform="rotate(114.733 .696 9.23)scale(1.82039 1.65466)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="ybvptdnhb"/><stop offset="1" class="ue-yx0baa"/></radialGradient><radialGradient id="iJkJ3be" cx="0" cy="0" r="1" gradientTransform="rotate(-177.733 4.926 5.335)scale(2.43984 3.58659)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="sqmgyf2vi"/><stop offset="1" class="mvuactshi"/></radialGradient><radialGradient id="ikpbhkb" cx="0" cy="0" r="1" gradientTransform="matrix(2.75372 2.7903 -4.86946 4.80563 8.957 4.438)" gradientUnits="userSpaceOnUse"><stop class="vrnylccvf"/><stop offset="1" class="b442o21cz"/></radialGradient><radialGradient id="igIRTGb" cx="0" cy="0" r="1" gradientTransform="rotate(122.205 8.08 7.44)scale(1.67333 2.33845)" gradientUnits="userSpaceOnUse"><stop class="di6ktzbyk"/><stop offset="1" class="ejv935bph"/></radialGradient><radialGradient id="iHK2gZd" cx="0" cy="0" r="1" gradientTransform="rotate(153.473 9.724 7.107)scale(1.96256 4.27026)" gradientUnits="userSpaceOnUse"><stop class="kdig6mnba"/><stop offset="1" class="him6rrbhz"/></radialGradient><radialGradient id="iLdZsFd" cx="0" cy="0" r="1" gradientTransform="rotate(146.643 9.125 9.256)scale(3.50029 5.57703)" gradientUnits="userSpaceOnUse"><stop class="c2fnpwywz"/><stop offset="1" class="c5g3vhi-m"/></radialGradient><radialGradient id="iqSLjTd" cx="0" cy="0" r="1" gradientTransform="rotate(25.641 -22.605 46.66)scale(4.33294)" gradientUnits="userSpaceOnUse"><stop offset=".495" class="dw94g7b4q"/><stop offset="1" class="h_pvkdb-a"/></radialGradient><radialGradient id="iTYYcAc" cx="0" cy="0" r="1" gradientTransform="rotate(131.915 2.185 10.174)scale(3.69557)" gradientUnits="userSpaceOnUse"><stop class="pkd_tvbsd"/><stop offset="1" class="pqpdkgb0y"/></radialGradient><radialGradient id="iaLRKze" cx="0" cy="0" r="1" gradientTransform="matrix(2.19471 3.52472 -6.20084 3.86104 16.045 16.108)" gradientUnits="userSpaceOnUse"><stop offset=".31" class="wcbvx-n_a"/><stop offset="1" class="sbx2zkbbn"/></radialGradient><radialGradient id="idDXzmR" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.04 -2.59498 0 15.685 16.088)" gradientUnits="userSpaceOnUse"><stop offset=".83" class="e7jhv6bqi"/><stop offset="1" class="shxh5dbbc"/></radialGradient><radialGradient id="iCxqvsc" cx="0" cy="0" r="1" gradientTransform="matrix(2.29616 -1.5929 1.94486 2.8035 18.345 11.054)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="i8BWa9b" cx="0" cy="0" r="1" gradientTransform="matrix(1.055 .10418 -.05477 .55466 18.967 8.634)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="i1QIYKd" cx="0" cy="0" r="1" gradientTransform="rotate(-30.603 29.08 -29.099)scale(1.33343)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="ikGPidc" cx="0" cy="0" r="1" gradientTransform="rotate(169.694 4.204 6.531)scale(1.24377 1.18974)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="izK5mnd" cx="0" cy="0" r="1" gradientTransform="rotate(146.03 6.918 7.737)scale(6.35331 6.77683)" gradientUnits="userSpaceOnUse"><stop class="uy3z2gbbp"/><stop offset="1" class="o2dl4_b2z"/></radialGradient><radialGradient id="iswadkb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.91757 1.50795 -1.27939 -1.62692 16.142 11.165)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="ixudYde" cx="0" cy="0" r="1" gradientTransform="matrix(.10195 -4.22092 5.35556 .12935 13.152 18.03)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="ielbTMb" cx="0" cy="0" r="1" gradientTransform="matrix(-.90631 7.53124 -10.20904 -1.22856 15.433 10.253)" gradientUnits="userSpaceOnUse"><stop offset=".636" class="yxf64pxyp"/><stop offset=".969" class="ammr7dben"/></radialGradient><radialGradient id="iBcx89c" cx="0" cy="0" r="1" gradientTransform="rotate(162.034 6.555 7.72)scale(5.91189 10.1785)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="iv0F2Jb" cx="0" cy="0" r="1" gradientTransform="rotate(169.694 9.218 6.353)scale(1.37674 4.53226)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="i4lCBvb" cx="0" cy="0" r="1" gradientTransform="matrix(1.93418 4.03104 -8.32995 3.99689 10.583 5.731)" gradientUnits="userSpaceOnUse"><stop class="mih5kfbap"/><stop offset="1" class="kqfxh5bnm"/></radialGradient><radialGradient id="i83eNWc" cx="0" cy="0" r="1" gradientTransform="rotate(-116.197 11.493 1.5)scale(2.60341 1.48971)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="iHAwaYd" cx="0" cy="0" r="1" gradientTransform="matrix(2.43614 2.34309 -4.65571 4.8406 7.068 6.157)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="hi5yi9bqv"/><stop offset="1" class="d8y_5zbge"/></radialGradient><radialGradient id="itPdsme" cx="0" cy="0" r="1" gradientTransform="matrix(-1.43428 2.83792 -2.22567 -1.12485 10.372 5.8)" gradientUnits="userSpaceOnUse"><stop class="g6mu4o3fz"/><stop offset="1" class="dx30lgbdy"/></radialGradient><radialGradient id="impSfob" cx="0" cy="0" r="1" gradientTransform="rotate(105.378 6.182 7.108)scale(4.98066 7.08229)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="iz4jcxg0j"/><stop offset="1" class="qflnpfbur"/></radialGradient><radialGradient id="ipj0sCd" cx="0" cy="0" r="1" gradientTransform="matrix(-.27516 3.38192 -6.03683 -.49117 15.294 4.14)" gradientUnits="userSpaceOnUse"><stop class="mv8kv7beo"/><stop offset="1" class="g_ulzrbqz"/></radialGradient><radialGradient id="iwvArDc" cx="0" cy="0" r="1" gradientTransform="rotate(-129.374 9.955 1.3)scale(7.3699 6.59712)" gradientUnits="userSpaceOnUse"><stop offset=".891" class="w58maet4h"/><stop offset=".979" class="drxq29wnr"/></radialGradient><radialGradient id="idNTC3d" cx="0" cy="0" r="1" gradientTransform="matrix(-.11847 .20477 -.19778 -.11443 17.206 10.493)" gradientUnits="userSpaceOnUse"><stop class="kjki5ab4n"/><stop offset="1" class="ql2-nbc9p"/></radialGradient><radialGradient id="i27H3Yd" cx="0" cy="0" r="1" gradientTransform="matrix(-.11847 .20477 -.19778 -.11443 12.908 11.216)" gradientUnits="userSpaceOnUse"><stop class="kjki5ab4n"/><stop offset="1" class="ql2-nbc9p"/></radialGradient><radialGradient id="iCOuGie" cx="0" cy="0" r="1" gradientTransform="matrix(.28711 3.40925 -4.12958 .34777 8.64 21.223)" gradientUnits="userSpaceOnUse"><stop offset=".604" class="v442oubmz"/><stop offset="1" class="p_ew-572a"/></radialGradient><radialGradient id="ijSbhre" cx="0" cy="0" r="1" gradientTransform="matrix(-.75 3.4375 -2.71722 -.59285 6.39 19.942)" gradientUnits="userSpaceOnUse"><stop offset=".518" class="m0rm-m-qv"/><stop offset="1" class="wi8a08bum"/></radialGradient><radialGradient id="ivHoDpc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15508 -.34883 1.8893 -6.25609 8.598 30.598)" gradientUnits="userSpaceOnUse"><stop class="wagk6dfaq"/><stop offset="1" class="hfzkti_ts"/></radialGradient><radialGradient id="ir0Shvd" cx="0" cy="0" r="1" gradientTransform="rotate(86.386 -7.52 15.924)scale(1.85287 2.95057)" gradientUnits="userSpaceOnUse"><stop offset=".6" class="k5vtewq9k"/><stop offset="1" class="z1zjblq2q"/></radialGradient><radialGradient id="im8rVox" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0785 6 -4.46735 -1.54757 16.937 25.378)" gradientUnits="userSpaceOnUse"><stop class="v2wkn2ras"/><stop offset="1" class="yxmxw0ard"/></radialGradient><radialGradient id="iiqxDtb" cx="0" cy="0" r="1" gradientTransform="rotate(-132.901 14.991 10.444)scale(4.22338 6.72611)" gradientUnits="userSpaceOnUse"><stop class="bji58ac7a"/><stop offset="1" class="eqapwmsga"/></radialGradient><radialGradient id="i2LMlIe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.62501 -3.8277 2.0945 -1.4364 21.109 26.316)" gradientUnits="userSpaceOnUse"><stop offset=".393" class="c8r1g2bnk"/><stop offset="1" class="kyl8adb5j"/></radialGradient><radialGradient id="igsDegd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.038 1.01561 -1.51165 -8.987 27.271 23.427)" gradientUnits="userSpaceOnUse"><stop class="z3zsa5bpu"/><stop offset="1" class="c_p6lvbtv"/></radialGradient><radialGradient id="iwMnVlc" cx="0" cy="0" r="1" gradientTransform="rotate(164.954 9.019 13.02)scale(3.00943 4.47011)" gradientUnits="userSpaceOnUse"><stop class="dyh_p3bsl"/><stop offset="1" class="acgtzjb8q"/></radialGradient><radialGradient id="isznxje" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66156 -1.3125 1.73451 -2.1958 22.802 26.098)" gradientUnits="userSpaceOnUse"><stop class="fo4qq4q_b"/><stop offset="1" class="a6ayzxb8w"/></radialGradient><radialGradient id="iMeOWgc" cx="0" cy="0" r="1" gradientTransform="rotate(33.14 -38.819 40.73)scale(2.25791 .79383)" gradientUnits="userSpaceOnUse"><stop class="h47r5ibay"/><stop offset="1" class="jjp_mfbio"/></radialGradient><radialGradient id="i2cAfUb" cx="0" cy="0" r="1" gradientTransform="matrix(6.57813 0 0 1.16319 12.924 30.597)" gradientUnits="userSpaceOnUse"><stop class="nbcoryb1h"/><stop offset="1" class="r8owzxbqs"/></radialGradient><radialGradient id="iWVYXHe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.02913 0 0 -3.40472 19.265 29.535)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="uxh2dv17l"/><stop offset="1" class="u1zlaqbml"/></radialGradient><radialGradient id="i26Sduz" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.02344 -.68462 0 19.607 28.616)" gradientUnits="userSpaceOnUse"><stop offset=".372" class="rntqzsbvm"/><stop offset="1" class="kn6547brm"/></radialGradient><radialGradient id="iFG0Q0L" cx="0" cy="0" r="1" gradientTransform="matrix(-8.5625 1.81252 -.47277 -2.23342 29.083 27.069)" gradientUnits="userSpaceOnUse"><stop class="o7yf4tl0b"/><stop offset="1" class="x9s6ceaht"/></radialGradient><radialGradient id="ijooSPL" cx="0" cy="0" r="1" gradientTransform="matrix(.84205 2.73 -2.93117 .9041 6.766 20.473)" gradientUnits="userSpaceOnUse"><stop class="h0nz-rbjw"/><stop offset="1" class="kfbnffbzx"/></radialGradient><radialGradient id="iFe6Avb" cx="0" cy="0" r="1" gradientTransform="rotate(110.854 -3.01 13.336)scale(2.10677 2.16117)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="jz746dbzd"/><stop offset="1" class="dzs1febsk"/></radialGradient><radialGradient id="ijSOv4t" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 .87171 -.46263 -.67998 9.906 21.445)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="cwu2h0blp"/><stop offset="1" class="f9-tluqmj"/></radialGradient><radialGradient id="i8tV5Lb" cx="0" cy="0" r="1" gradientTransform="matrix(.32031 .75 -.43392 .18532 7.163 21.082)" gradientUnits="userSpaceOnUse"><stop offset=".827" class="yyn9swbvh"/><stop offset="1" class="pviihufyn"/></radialGradient><radialGradient id="im7kFed" cx="0" cy="0" r="1" gradientTransform="matrix(-.3711 1.25391 -.1532 -.04534 16.01 19.073)" gradientUnits="userSpaceOnUse"><stop class="tomvu1bgl"/><stop offset="1" class="sinn-3bvk"/></radialGradient><radialGradient id="ivUH7oe" cx="0" cy="0" r="1" gradientTransform="matrix(-.20313 -.60156 1.71998 -.58078 9.312 23.613)" gradientUnits="userSpaceOnUse"><stop class="ut4bgvb0y"/><stop offset="1" class="gngaedcou"/></radialGradient><radialGradient id="irUt5Gn" cx="0" cy="0" r="1" gradientTransform="matrix(-.64063 2 -.16496 -.05284 15.822 18.413)" gradientUnits="userSpaceOnUse"><stop class="njdbcpw8w"/><stop offset="1" class="p6n8nbb9p"/></radialGradient><radialGradient id="iSohqnb" cx="0" cy="0" r="1" gradientTransform="matrix(1.42187 .6875 -.62811 1.29906 11.455 19.1)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="l8v5z5bog"/><stop offset="1" class="ll6ec2bpd"/></radialGradient><radialGradient id="iVxkvRd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0156 3.18752 -2.63101 -1.6637 9.455 19.06)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="b1a3scalr"/><stop offset="1" class="z_gh6vsyy"/></radialGradient><radialGradient id="i49NPfd" cx="0" cy="0" r="1" gradientTransform="rotate(119.595 -.223 12.027)scale(3.70167 1.33422)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="ie-bysyvv"/><stop offset="1" class="bpneozbdy"/></radialGradient><radialGradient id="iFu8etd" cx="0" cy="0" r="1" gradientTransform="matrix(-.1359 3.04807 -.73147 -.03261 7.275 18.714)" gradientUnits="userSpaceOnUse"><stop class="uxpb5qzbn"/><stop offset="1" class="ip8fcq0ak"/></radialGradient><radialGradient id="i1RjTAe" cx="0" cy="0" r="1" gradientTransform="matrix(.15625 1.04772 -1.07633 .16051 9.01 21.24)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="ohwd33b2n"/><stop offset="1" class="y0dl1gblq"/></radialGradient><radialGradient id="ib5aaPb" cx="0" cy="0" r="1" gradientTransform="matrix(.03125 -.93275 3.89243 .13041 12.72 18.122)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="nu_77rrcl"/><stop offset="1" class="dnayrdbzp"/></radialGradient><radialGradient id="ijNHkXc" cx="0" cy="0" r="1" gradientTransform="rotate(153.435 5.197 10.115)scale(.78612 .35637)" gradientUnits="userSpaceOnUse"><stop class="sok9f40_l"/><stop offset="1" class="jg12b2kug"/></radialGradient><radialGradient id="ixvKXid" cx="0" cy="0" r="1" gradientTransform="rotate(-80.715 17.566 2.583)scale(.83681 3.75171)" gradientUnits="userSpaceOnUse"><stop offset=".09" class="sg8a2viwh"/><stop offset="1" class="vsvz-xe_v"/></radialGradient><radialGradient id="iXu7Une" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 .41406 -.20022 -.51377 13.814 18.12)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="dzyo4sbbn"/><stop offset="1" class="o-ef0ac2e"/></radialGradient><radialGradient id="iXHBdAe" cx="0" cy="0" r="1" gradientTransform="matrix(-.8125 1.51562 -5.32458 -2.85442 11.143 19.371)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="zx-utrb8d"/><stop offset="1" class="rb5pqrony"/></radialGradient><radialGradient id="iHwtmXc" cx="0" cy="0" r="1" gradientTransform="matrix(2.29688 1.78687 -.45885 .58982 11.518 19.642)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="kaygmvbyu"/><stop offset="1" class="zq2cu-lqa"/></radialGradient><radialGradient id="ivZWVuc" cx="0" cy="0" r="1" gradientTransform="rotate(136.002 2.307 12.13)scale(.96996 1.97716)" gradientUnits="userSpaceOnUse"><stop offset=".139" class="kwfaklb2u"/><stop offset="1" class="a3cf45xpc"/></radialGradient><radialGradient id="i2ib0uc" cx="0" cy="0" r="1" gradientTransform="matrix(.48047 -.3496 .60677 .83392 8.94 19.45)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="kss7lepmr"/><stop offset="1" class="z8oy8ibbe"/></radialGradient><radialGradient id="iHjmPhb" cx="0" cy="0" r="1" gradientTransform="matrix(1.09945 -1.69165 1.88005 1.2219 8.869 22.067)" gradientUnits="userSpaceOnUse"><stop offset=".407" class="fjk2vysly"/><stop offset="1" class="pll5kd_nw"/></radialGradient><radialGradient id="ibOJGde" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 .84935 -.34383 .46806 10.768 20.621)" gradientUnits="userSpaceOnUse"><stop offset=".06" class="tjgs2ub-w"/><stop offset="1" class="jtvtg3bqw"/></radialGradient><radialGradient id="igmmlic" cx="0" cy="0" r="1" gradientTransform="rotate(97.522 -3.92 14.757)scale(2.32995 4.84987)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="aiyo-ztfk"/><stop offset=".962" class="tlxyqtbtq"/></radialGradient><radialGradient id="iRlP4lc" cx="0" cy="0" r="1" gradientTransform="matrix(.54646 -.48802 1.62742 1.82231 7.87 21.384)" gradientUnits="userSpaceOnUse"><stop class="j4c7dkb7m"/><stop offset="1" class="gt-69vbgu"/></radialGradient><radialGradient id="iHEhwUc" cx="0" cy="0" r="1" gradientTransform="rotate(105.675 .805 16.097)scale(1.31451 .34383)" gradientUnits="userSpaceOnUse"><stop class="cn05xwrkd"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="i4LlWSI" cx="0" cy="0" r="1" gradientTransform="rotate(105.036 .686 16.573)scale(.54206 .1592)" gradientUnits="userSpaceOnUse"><stop class="em3lc9y5i"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="i78CRmX" cx="0" cy="0" r="1" gradientTransform="rotate(174.906 8.34 10.59)scale(.43997 .38553)" gradientUnits="userSpaceOnUse"><stop class="tzj34xnjq"/><stop offset="1" class="ugbytbngn"/></radialGradient><radialGradient id="iJpfxxe" cx="0" cy="0" r="1" gradientTransform="matrix(-.26365 -2.21465 3.37212 -.40144 7.768 22.413)" gradientUnits="userSpaceOnUse"><stop class="zbwshaccu"/><stop offset="1" class="piz2rbc3b"/></radialGradient><linearGradient id="if37vng" x1="17.65" x2="13.112" y1="3.502" y2="17.421" gradientUnits="userSpaceOnUse"><stop class="p6otu2-6b"/><stop offset="1" class="q5mih6mme"/></linearGradient><linearGradient id="imTZFte" x1="19.224" x2="12.336" y1="19.202" y2="30.879" gradientUnits="userSpaceOnUse"><stop class="q9xywcr7e"/><stop offset="1" class="jvlxembhy"/></linearGradient><linearGradient id="i6xU0ze" x1="15.027" x2="16.996" y1="17.596" y2="18.752" gradientUnits="userSpaceOnUse"><stop class="hytkilb8f"/><stop offset="1" class="x_lm5vbjz"/></linearGradient><linearGradient id="idj3lje" x1="7.888" x2="10.864" y1="12.591" y2="12.049" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="isXWd2d" x1="13.383" x2="14.261" y1="12.826" y2="12.775" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="iRPpU7c" x1="14.591" x2="14.48" y1="13.494" y2="12.88" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="iipUz9b" x1="14.04" x2="14.285" y1="10.607" y2="11.955" gradientUnits="userSpaceOnUse"><stop class="s7k33p2vn"/><stop offset="1" class="npl7d4bom"/></linearGradient><linearGradient id="i97qSdc" x1="14.129" x2="14.425" y1="15.112" y2="14.153" gradientUnits="userSpaceOnUse"><stop class="hvrv4iryz"/><stop offset="1" class="u1r8ksb5m"/></linearGradient><linearGradient id="iOlvz4c" x1="10.161" x2="10.942" y1="5.647" y2="6.829" gradientUnits="userSpaceOnUse"><stop class="gjbrx7i8b"/><stop offset="1" class="zcr9jykfw"/></linearGradient><linearGradient id="iq9JBGe" x1="12.595" x2="10.011" y1="10.642" y2="10.362" gradientUnits="userSpaceOnUse"><stop class="sv4maabhu"/><stop offset="1" class="hoafb6buw"/></linearGradient><linearGradient id="i7mHBWb" x1="17.156" x2="13.814" y1="10.132" y2="9.021" gradientUnits="userSpaceOnUse"><stop offset=".394" class="hdettxboa"/><stop offset="1" class="rf88abbhx"/></linearGradient><linearGradient id="iJaxaob" x1="15.897" x2="17.371" y1="11.555" y2="10.473" gradientUnits="userSpaceOnUse"><stop offset=".048" class="zft5ozi2a"/><stop offset="1" class="zs6y5wbab"/></linearGradient><linearGradient id="iCCBk4c" x1="11.57" x2="13.05" y1="12.289" y2="11.209" gradientUnits="userSpaceOnUse"><stop offset=".048" class="zft5ozi2a"/><stop offset="1" class="zs6y5wbab"/></linearGradient><linearGradient id="i07g6Je" x1="15.147" x2="17.387" y1="10.935" y2="11.091" gradientUnits="userSpaceOnUse"><stop class="ytn_p5bjt"/><stop offset="1" class="sel15-yew"/></linearGradient><linearGradient id="irT8t0c" x1="10.849" x2="13.089" y1="11.659" y2="11.814" gradientUnits="userSpaceOnUse"><stop class="ytn_p5bjt"/><stop offset="1" class="sel15-yew"/></linearGradient><linearGradient id="iyRmQPe" x1="9.109" x2="3.64" y1="26.91" y2="25.442" gradientUnits="userSpaceOnUse"><stop class="g1c-6jb6y"/><stop offset="1" class="hkdf97w8c"/></linearGradient><linearGradient id="izxftWc" x1="3.333" x2="5.328" y1="26.538" y2="27.192" gradientUnits="userSpaceOnUse"><stop class="da95trp0k"/><stop offset="1" class="feoz1vgta"/></linearGradient><linearGradient id="iPBG4Zd" x1="9.229" x2="8.836" y1="28.928" y2="28.803" gradientUnits="userSpaceOnUse"><stop class="rehc034in"/><stop offset="1" class="psvt8ubmu"/></linearGradient><linearGradient id="iZkHDBb" x1="18.227" x2="17.566" y1="26.872" y2="27.767" gradientUnits="userSpaceOnUse"><stop offset=".175" class="jl9fiab1w"/><stop offset="1" class="j9aoxmbfm"/></linearGradient><linearGradient id="iCVqPpc" x1="19.395" x2="19.395" y1="27.23" y2="28.069" gradientUnits="userSpaceOnUse"><stop class="y-ymn0bhn"/><stop offset="1" class="he69lvb0i"/></linearGradient><linearGradient id="i7K3wIe" x1="26.546" x2="26.984" y1="27.378" y2="31.097" gradientUnits="userSpaceOnUse"><stop class="tnk2b_bjh"/><stop offset="1" class="p40qzpbtf"/></linearGradient><linearGradient id="iLcy3Dd" x1="5.833" x2="6.912" y1="20.351" y2="22.054" gradientUnits="userSpaceOnUse"><stop class="j4n7g28_w"/><stop offset="1" class="laie_nbgc"/></linearGradient><linearGradient id="i9al3pi" x1="11.144" x2="10.997" y1="22.67" y2="20.027" gradientUnits="userSpaceOnUse"><stop class="fu3c0cblo"/><stop offset="1" class="pdon63boo"/></linearGradient><linearGradient id="iHapy0c" x1="12.351" x2="11.964" y1="20.861" y2="18.879" gradientUnits="userSpaceOnUse"><stop class="fu3c0cblo"/><stop offset="1" class="pdon63boo"/></linearGradient><linearGradient id="iLMBpdc" x1="16.078" x2="15.296" y1="18.66" y2="21.646" gradientUnits="userSpaceOnUse"><stop class="e6bcurcdv"/><stop offset="1" class="jxwnoqbqn"/></linearGradient><linearGradient id="iuyQgEe" x1="15.205" x2="15.428" y1="21.866" y2="20.975" gradientUnits="userSpaceOnUse"><stop class="w_57dfb5m"/><stop offset="1" class="t78i98bfv"/></linearGradient><linearGradient id="iI7H0Cd" x1="14.953" x2="13.828" y1="17.895" y2="22.223" gradientUnits="userSpaceOnUse"><stop class="nn3wh7bnm"/><stop offset="1" class="tbs366q3s"/></linearGradient><linearGradient id="iSzC7rb" x1="15.265" x2="14.156" y1="18.27" y2="17.91" gradientUnits="userSpaceOnUse"><stop class="h94nvm15h"/><stop offset="1" class="qtvy6rbzh"/></linearGradient><linearGradient id="iA2TIDc" x1="14.453" x2="13.223" y1="17.785" y2="22.535" gradientUnits="userSpaceOnUse"><stop class="qic_n_blg"/><stop offset="1" class="qh-ows9fr"/></linearGradient><linearGradient id="iXBybad" x1="12.549" x2="12.768" y1="21.601" y2="20.523" gradientUnits="userSpaceOnUse"><stop class="e122-lbju"/><stop offset="1" class="grqmao4rm"/></linearGradient><linearGradient id="i7WGgxe" x1="8.421" x2="8.964" y1="17.285" y2="21.785" gradientUnits="userSpaceOnUse"><stop class="rvz7hrbgf"/><stop offset="1" class="c6pq05twi"/></linearGradient><linearGradient id="iO4y5tb" x1="16.521" x2="15.937" y1="19.159" y2="21.659" gradientUnits="userSpaceOnUse"><stop class="neym138jd"/><stop offset="1" class="kmp3a3cnr"/></linearGradient><filter id="iqPcxWb" width="16.063" height="16.746" x="6.592" y="1.971" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.698039 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3542"/></filter><filter id="iLNf4fe" width="3.44" height="3.54" x="7.845" y="10.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3542"/></filter><filter id="iLUczGd" width="3.29" height="3.54" x="17.412" y="8.573" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3542"/></filter><filter id="iBsCRpb" width="3.196" height="3.196" x="17.459" y="8.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3542" stdDeviation=".25"/></filter><filter id="iriNaod" width="2.996" height="2.996" x="8.011" y="10.707" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3542" stdDeviation=".2"/></filter><filter id="iOzvctb" width="10.78" height="10.798" x="8.714" y="6.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3542"/></filter><filter id="iNDD3qe" width="2.905" height="3.796" x="12.886" y="10.355" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3542" stdDeviation=".25"/></filter><filter id="iwWaTFd" width="2.405" height="3.285" x="13.274" y="10.447" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3542" stdDeviation=".125"/></filter><filter id="iYHgEhK" width="2.405" height="3.285" x="13.23" y="10.35" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3542" stdDeviation=".125"/></filter><filter id="iZh7nId" width="3.725" height="1.84" x="12.834" y="13.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3542" stdDeviation=".05"/></filter><filter id="ikeeFGd" width="2.415" height="1.386" x="10.002" y="8.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4 0 0 0 0 0.25098 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3542"/></filter><filter id="itvUqoh" width="2.207" height="1.252" x="9.999" y="9.003" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3542" stdDeviation=".1"/></filter><filter id="ihArUMe" width="4.129" height="5.738" x="7.138" y="4.857" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3542" stdDeviation=".25"/></filter><filter id="iqmy0bb" width="9.669" height="4.811" x="9.694" y="3.376" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3542" stdDeviation=".125"/></filter><filter id="ifunmfe" width="1.46" height="2.22" x="9.798" y="5.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3542" stdDeviation=".1"/></filter><filter id="iL5NS3b" width="3.788" height="2.92" x="9.853" y="9.17" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3542" stdDeviation=".3"/></filter><filter id="iiI9BIc" width="3.588" height="2.85" x="14.539" y="8.216" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3542" stdDeviation=".3"/></filter><filter id="iIu7l1b" width="2.503" height="1.208" x="15.04" y="10.185" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3542" stdDeviation=".075"/></filter><filter id="iClNXrc" width="2.503" height="1.208" x="10.742" y="10.909" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3542" stdDeviation=".075"/></filter><filter id="ivjQWkd" width="2.533" height=".902" x="15.075" y="8.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4 0 0 0 0 0.25098 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3542"/></filter><filter id="iTbpHod" width="2.333" height=".782" x="15.103" y="8.216" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3542" stdDeviation=".1"/></filter><filter id="iFkhanJ" width="11.192" height="8.359" x="11.466" y="22.488" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.607843 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3542"/></filter><filter id="iWZuhTd" width="7.407" height="8.444" x="19.048" y="19.317" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3542"/></filter><filter id="iAeVIde" width="8.208" height="4.667" x="12.416" y="25.93" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.505882 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3542"/></filter><filter id="i8Wqe3d" width="3.456" height="1.701" x="7.381" y="22.401" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3542" stdDeviation=".1"/></filter><filter id="ieh44Me" width="4.309" height="4.662" x="11.043" y="17.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.552941 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3542"/></filter><filter id="iKLg2Sc" width="3.647" height="2.753" x="6.263" y="20.148" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3542" stdDeviation=".05"/></filter><filter id="iB99hdb" width="2.634" height="2.141" x="16.374" y="26.388" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3542" stdDeviation=".125"/></filter><filter id="ioAe8Fb" width="4.536" height="1" x="12.746" y="29.193" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3542" stdDeviation=".15"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-feeding-baby-medium-light" /></template>
<style>
.a3cf45xpc {
  stop-color: var(--svg-color--bf8a6b, #BF8A6B);
  stop-opacity: 0;
}

.a6ayzxb8w {
  stop-color: var(--svg-color--289d47, #289D47);
  stop-opacity: 0;
}

.acgtzjb8q {
  stop-color: var(--svg-color--3ba055, #3BA055);
}

.adtex6bqi {
  d: path("M12.17 3.627c-1.184-.044-2.184 1.39-2.226 1.833c2.213 3.359 4.531 2.579 7.12 1.805c1.55-.463 1.852.226 2.05.55c-1.18-4-4.243-4.087-6.943-4.188");
}

.aiyo-ztfk {
  stop-color: var(--svg-color--b56e74, #B56E74);
  stop-opacity: 0;
}

.ammr7dben {
  stop-color: var(--svg-color--996375, #996375);
}

.anickvn2b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M7.78 23.629c.579.14 1.92.172 2.657-.828");
}

.aps1jhbfc {
  stop-color: var(--svg-color--b47860, #B47860);
}

.aso-vybjw {
  stop-color: var(--svg-color--d59566, #D59566);
}

.ay-7q2jga {
  d: path("m8.809 10.745l-.066-.306c-.153-.958.336-1.429.551-1.595l.048-.03l.048-.03c.491-.344.846-.853.97-1.459l.048-.21a.27.27 0 0 1 .454-.136a3.95 3.95 0 0 0 3.513 1.1l3.238-.589c.182-.033 1.105-.11 1.386 1.132l.443 3.112c.388 2.841-1.468 5.134-4.155 5.622c-2.686.488-5.231-1.004-5.868-3.8z");
}

.azwbilbkt {
  fill: var(--svg-color--d29d8b, #D29D8B);
  d: path("M17.18 26.28a.937.937 0 0 0-1.12 1.497l.931.802a.1.1 0 0 1-.063.175l-3.644.072a.886.886 0 0 0 .018 1.771h6.06v-1l1.062-1.227z");
}

.b1a3scalr {
  stop-color: var(--svg-color--b57176, #B57176);
  stop-opacity: 0;
}

.b442o21cz {
  stop-color: var(--svg-color--dcc893, #DCC893);
  stop-opacity: 0;
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.bgu-wppft {
  d: path("M21.685 11.455c.135-.476.158-.985.065-1.494a3.35 3.35 0 0 0-.509-1.264h.006a3.3 3.3 0 0 0-.377-.465l-.003-.003a3.3 3.3 0 0 1-.852-1.685l-.002-.01a3.373 3.373 0 0 0-3.921-2.714a.55.55 0 0 1-.5-.151a3.38 3.38 0 0 0-2.95-.894a3.38 3.38 0 0 0-2.445 1.875a.58.58 0 0 1-.415.317q-.043.007-.085.017a3.373 3.373 0 0 0-2.63 3.904l.002.01a3.3 3.3 0 0 1-.205 1.877l-.002.005a3.37 3.37 0 0 0 .372 3.303c.097.13.129.303.083.458a3.3 3.3 0 0 0-.068 1.474a3.284 3.284 0 0 0 3.825 2.648l8.63-1.57a3.284 3.284 0 0 0 2.648-3.824a3.3 3.3 0 0 0-.583-1.356a.53.53 0 0 1-.084-.458M8.868 11.01l-.013.002l1.636 2.15c.637 2.795 1.224-.223 3.91-.712c2.687-.488 4.43 2.436 4.04-.405L19 8.622c-.281-1.242-1.204-1.165-1.386-1.132l-3.238.59a3.95 3.95 0 0 1-3.513-1.1a.27.27 0 0 0-.455.135l-.047.21a2.36 2.36 0 0 1-1.018 1.49l-.048.029c-.215.166-.704.637-.551 1.595l.066.306z");
}

.bji58ac7a {
  stop-color: var(--svg-color--208d47, #208D47);
}

.bpneozbdy {
  stop-color: var(--svg-color--dbac8a, #DBAC8A);
  stop-opacity: 0;
}

.by-r3et3v {
  d: path("M12.841 10.996c-.077.01-.134.057-.182.125a1.06 1.06 0 0 1-.712.49a1.02 1.02 0 0 1-.828-.211a.24.24 0 0 0-.211-.058a.257.257 0 0 0-.116.452c.337.28.789.414 1.25.327a1.54 1.54 0 0 0 1.069-.74c.105-.183-.058-.414-.27-.385");
}

.c_p6lvbtv {
  stop-color: var(--svg-color--31be7d, #31BE7D);
}

.c-xn1hpqp {
  d: path("M18.998 27.38a.15.15 0 0 1 .15-.15h.643v3.368h-.793z");
}

.c2fnpwywz {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
}

.c4nwy9mhc {
  stroke: var(--svg-color--98693e, #98693E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.403 8.655c.31-.138 1.124-.245 1.733.042");
}

.c5g3vhi-m {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
  stop-opacity: 0;
}

.c6pq05twi {
  stop-color: var(--svg-color--be8777, #BE8777);
}

.c723gdbru {
  d: path("M7.155 30.597c-1.05 0-1.9-.85-1.89-1.9l.01-2.13c0-5.77 4.79-10.46 10.69-10.46c5.91 0 10.69 4.68 10.69 10.46l.17 4.03z");
}

.c8r1g2bnk {
  stop-color: var(--svg-color--148c3e, #148C3E);
}

.cak2zib2f {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M9.706 13.285a1.098 1.098 0 1 0-.393-2.16a1.098 1.098 0 0 0 .393 2.16");
}

.cn05xwrkd {
  stop-color: var(--svg-color--fed466, #FED466);
}

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.cwu2h0blp {
  stop-color: var(--svg-color--6b3d8e, #6B3D8E);
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d8y_5zbge {
  stop-color: var(--svg-color--daa88f, #DAA88F);
}

.da95trp0k {
  stop-color: var(--svg-color--8f73b3, #8F73B3);
}

.di6ktzbyk {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
}

.dnayrdbzp {
  stop-color: var(--svg-color--c7977a, #C7977A);
  stop-opacity: 0;
}

.dqt437r8o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M10.098 5.302c.068.24.448 1.12.86 1.62");
}

.drxq29wnr {
  stop-color: var(--svg-color--dac493, #DAC493);
}

.dvyniwihb {
  stop-color: var(--svg-color--c57f82, #C57F82);
}

.dw94g7b4q {
  stop-color: var(--svg-color--e3ae90, #E3AE90);
}

.dx30lgbdy {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
  stop-opacity: 0;
}

.dyh_p3bsl {
  stop-color: var(--svg-color--279f64, #279F64);
}

.dzs1febsk {
  stop-color: var(--svg-color--6f409a, #6F409A);
  stop-opacity: 0;
}

.dzyo4sbbn {
  stop-color: var(--svg-color--eabea3, #EABEA3);
}

.e_nsx25xe {
  d: path("M17.18 26.28a.937.937 0 0 0-1.12 1.497l.931.802a.1.1 0 0 1-.063.175l-3.644.072a.886.886 0 0 0 .018 1.771h6.06v-1l1.062-1.227z");
}

.e122-lbju {
  stop-color: var(--svg-color--8b72aa, #8B72AA);
}

.e5lh0tbhf {
  stroke: var(--svg-color--e1ae9b, #E1AE9B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.246 29.693h3.536");
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.e6bcurcdv {
  stop-color: var(--svg-color--6cd9f5, #6CD9F5);
}

.e7jhv6bqi {
  stop-color: var(--svg-color--ab767c, #AB767C);
  stop-opacity: 0;
}

.edbi1ib2g {
  fill: var(--svg-color--9c84d0, #9C84D0);
  d: path("m29.145 25.938l-4.94-6.05l-3.16 8.57z");
}

.ee70nabjp {
  d: path("M23.695 27.727a4.3 4.3 0 1 0 0-8.6a4.3 4.3 0 0 0 0 8.6");
}

.ejv935bph {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
  stop-opacity: 0;
}

.em3lc9y5i {
  stop-color: var(--svg-color--fed064, #FED064);
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.eqapwmsga {
  stop-color: var(--svg-color--208d47, #208D47);
  stop-opacity: 0;
}

.euvncsbod {
  d: path("M9.67 17.98c.243.25.33.526.343.633l.485.469l2.34.407a.89.89 0 0 0 1.025-.693a.9.9 0 0 0-.774-1.078c-1.09-.133-2.42-.306-2.779-.347c-.613-.07-.945.297-.64.61");
}

.f9-tluqmj {
  stop-color: var(--svg-color--6b3d8e, #6B3D8E);
  stop-opacity: 0;
}

.feoz1vgta {
  stop-color: var(--svg-color--8f73b3, #8F73B3);
  stop-opacity: 0;
}

.fhnbafbir {
  d: path("m11.845 21.197l-.46-.5c-.28-.3-.68-.48-1.09-.49c-.42-.01-.82.16-1.11.46l-.17.18l.53-.95c.22-.39.59-.66 1.02-.74s.88.03 1.23.3l.99.8c.33.27.38.75.12 1.09c-.21.26-.56.35-.85.24a.9.9 0 0 0-.21-.39");
}

.fjk2vysly {
  stop-color: var(--svg-color--ba7a7c, #BA7A7C);
}

.fo4qq4q_b {
  stop-color: var(--svg-color--289d47, #289D47);
}

.ft5dv1b6b {
  fill: none;
}

.fu3c0cblo {
  stop-color: var(--svg-color--f38820, #F38820);
}

.g_ulzrbqz {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
  stop-opacity: 0;
}

.g1c-6jb6y {
  stop-color: var(--svg-color--8a4fe4, #8A4FE4);
}

.g1fw3-bff {
  stop-color: var(--svg-color--f4c099, #F4C099);
  stop-opacity: 0;
}

.g6lnibn2h {
  d: path("m14.826 17.695l-2.636-.734l-1.073 3.895l2.6.734c.408.11.755-.065.85-.394l.78-2.703c.123-.391-.164-.694-.521-.798");
}

.g6mu4o3fz {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
}

.gjbrx7i8b {
  stop-color: var(--svg-color--ebce91, #EBCE91);
}

.gngaedcou {
  stop-color: var(--svg-color--8a68c3, #8A68C3);
  stop-opacity: 0;
}

.grqmao4rm {
  stop-color: var(--svg-color--b59cc2, #B59CC2);
  stop-opacity: 0;
}

.gt-69vbgu {
  stop-color: var(--svg-color--bb8072, #BB8072);
  stop-opacity: 0;
}

.gve5e0nxd {
  fill: var(--svg-color--d8a888, #D8A888);
  d: path("M9.67 17.98c.243.25.33.526.343.633l.485.469l2.34.407a.89.89 0 0 0 1.025-.693a.9.9 0 0 0-.774-1.078c-1.09-.133-2.42-.306-2.779-.347c-.613-.07-.945.297-.64.61");
}

.gw7tuorde {
  d: path("M10.565 19.167c-.28.05-.54.19-.74.38c.01-.05.02-.1.04-.15l.12-.33c.28-.78 1.09-1.27 1.91-1.15l1.66.23c.42.06.72.45.66.87s-.45.72-.87.66l-1.57-.22c-.34-.26-.78-.37-1.21-.29");
}

.h_pvkdb-a {
  stop-color: var(--svg-color--e3ae90, #E3AE90);
  stop-opacity: 0;
}

.h-exvsxip {
  fill: var(--svg-color--966333, #966333);
  fill-rule: evenodd;
  d: path("m17.23 8.465l-.096.256za.274.274 0 0 1-.193.513l-.005-.002a1 1 0 0 0-.124-.038a3 3 0 0 0-.37-.073a2.3 2.3 0 0 0-1.094.104a.274.274 0 1 1-.19-.514c.5-.185.994-.18 1.356-.133a3.4 3.4 0 0 1 .605.137l.01.004l.003.001z");
}

.h0nz-rbjw {
  stop-color: var(--svg-color--7f5499, #7F5499);
}

.h47r5ibay {
  stop-color: var(--svg-color--bd8677, #BD8677);
}

.h8ckk2b2m {
  d: path("m15.53 18.463l.554.16a.15.15 0 0 1 .103.185l-.784 2.73a.15.15 0 0 1-.185.102l-.555-.159z");
}

.h94nvm15h {
  stop-color: var(--svg-color--43b1db, #43B1DB);
}

.hcuenbefp {
  stop-color: var(--svg-color--c7897d, #C7897D);
  stop-opacity: 0;
}

.hdettxboa {
  stop-color: var(--svg-color--f1b493, #F1B493);
}

.he69lvb0i {
  stop-color: var(--svg-color--755994, #755994);
  stop-opacity: 0;
}

.hfzkti_ts {
  stop-color: var(--svg-color--8e5de1, #8E5DE1);
  stop-opacity: 0;
}

.hi3ka0bpk {
  d: path("M15.29 10.849c.125.117.498.34.982.287c.485-.053.911-.523 1.02-.7");
}

.hi5yi9bqv {
  stop-color: var(--svg-color--daa88f, #DAA88F);
  stop-opacity: 0;
}

.him6rrbhz {
  stop-color: var(--svg-color--fffabe, #FFFABE);
  stop-opacity: 0;
}

.hkdf97w8c {
  stop-color: var(--svg-color--804ec1, #804EC1);
}

.hoafb6buw {
  stop-color: var(--svg-color--c78979, #C78979);
  stop-opacity: 0;
}

.hvrv4iryz {
  stop-color: var(--svg-color--d8a29e, #D8A29E);
}

.hwci58euz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.593 20.348c-.206.432-.319 1.448.875 2.054c1.194.607 1.992.149 2.242-.156");
}

.hx8phqbfz {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m13.752 11.058l-.224 1.807a.55.55 0 0 0 .651.608l.791-.144a.553.553 0 0 0 .396-.798l-.846-1.613c-.183-.357-.717-.26-.768.14");
}

.hxuphr-8h {
  stop-color: var(--svg-color--cf987b, #CF987B);
}

.hytkilb8f {
  stop-color: var(--svg-color--9f676c, #9F676C);
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.i85grmbtl {
  d: path("m12.167 17.063l2.635.734c.357.104.645.406.521.797l-.779 2.704c-.096.329-.442.504-.851.393l-2.6-.733z");
}

.ie-bysyvv {
  stop-color: var(--svg-color--dbac8a, #DBAC8A);
}

.ip8fcq0ak {
  stop-color: var(--svg-color--cd9b7f, #CD9B7F);
  stop-opacity: 0;
}

.iq1xl0byh {
  d: path("m13.707 10.96l-.223 1.807a.55.55 0 0 0 .651.609l.791-.144a.553.553 0 0 0 .396-.799l-.846-1.612c-.183-.358-.718-.26-.769.14");
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.iz4jcxg0j {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
  stop-opacity: 0;
}

.j0lymcp5d {
  d: path("m2.201 30.598l2.93-9.156c.351-1.414 2.07-2.104 3.65-1.614s2.49 2.332 2.006 3.692l-2.216 7.078z");
}

.j4c7dkb7m {
  stop-color: var(--svg-color--b97d70, #B97D70);
}

.j4n7g28_w {
  stop-color: var(--svg-color--8e72a9, #8E72A9);
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.j9aoxmbfm {
  stop-color: var(--svg-color--cfae8c, #CFAE8C);
  stop-opacity: 0;
}

.jg12b2kug {
  stop-color: var(--svg-color--efc3a5, #EFC3A5);
  stop-opacity: 0;
}

.jjp_mfbio {
  stop-color: var(--svg-color--bd8677, #BD8677);
  stop-opacity: 0;
}

.jl9fiab1w {
  stop-color: var(--svg-color--cfae8c, #CFAE8C);
}

.jpk0vvtmk {
  d: path("m11.939 16.632l3.172.884c.43.125.744.558.627.96l-.9 3.085c-.115.397-.532.607-1.024.474l-3.129-.883z");
}

.jppjnwbry {
  fill: var(--svg-color--d9aa86, #D9AA86);
  d: path("M10.099 17.059c.356.125.482.33.515.453l.446.39l2.291.362a.92.92 0 0 0 1.062-.871a.913.913 0 0 0-.922-.95c-1.175.013-2.687.035-3.044.026c-.586-.016-.793.433-.348.59");
}

.jtvtg3bqw {
  stop-color: var(--svg-color--efc3a7, #EFC3A7);
  stop-opacity: 0;
}

.jvlxembhy {
  stop-color: var(--svg-color--7d49d2, #7D49D2);
}

.jxwnoqbqn {
  stop-color: var(--svg-color--3782ce, #3782CE);
}

.jz746dbzd {
  stop-color: var(--svg-color--6f409a, #6F409A);
}

.k_pdrlblj {
  stop-color: var(--svg-color--ebb830, #EBB830);
  stop-opacity: 0;
}

.k5vtewq9k {
  stop-color: var(--svg-color--8b5dd1, #8B5DD1);
}

.kaygmvbyu {
  stop-color: var(--svg-color--e3b69c, #E3B69C);
}

.kdig6mnba {
  stop-color: var(--svg-color--fffabe, #FFFABE);
}

.kfbnffbzx {
  stop-color: var(--svg-color--7a45b3, #7A45B3);
}

.kjki5ab4n {
  stop-color: var(--svg-color--9a6b40, #9A6B40);
}

.kmp3a3cnr {
  stop-color: var(--svg-color--ce953a, #CE953A);
}

.kn6547brm {
  stop-color: var(--svg-color--8259a4, #8259A4);
}

.kqfxh5bnm {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
  stop-opacity: 0;
}

.krvd34mtu {
  stop-color: var(--svg-color--d59566, #D59566);
  stop-opacity: 0;
}

.kss7lepmr {
  stop-color: var(--svg-color--d1a082, #D1A082);
}

.kwfaklb2u {
  stop-color: var(--svg-color--bf8a6b, #BF8A6B);
}

.kyl8adb5j {
  stop-color: var(--svg-color--148c3e, #148C3E);
  stop-opacity: 0;
}

.l1frur-bm {
  d: path("M19.253 11.549a1.098 1.098 0 1 0-.393-2.16a1.098 1.098 0 0 0 .393 2.16");
}

.l8v5z5bog {
  stop-color: var(--svg-color--6e574e, #6E574E);
}

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.la6anvnfv {
  d: path("M9.784 13.827a1.645 1.645 0 1 0-.588-3.236a1.645 1.645 0 0 0 .588 3.236");
}

.laie_nbgc {
  stop-color: var(--svg-color--8e72a9, #8E72A9);
  stop-opacity: 0;
}

.ldbnk6ogt {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M19.253 11.549a1.098 1.098 0 1 0-.393-2.16a1.098 1.098 0 0 0 .393 2.16");
}

.lgr3tsbdq {
  stroke: var(--svg-color--98693e, #98693E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M11.907 9.304c-.34-.02-1.139.166-1.607.65");
}

.ll6ec2bpd {
  stop-color: var(--svg-color--6e574e, #6E574E);
  stop-opacity: 0;
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.lz8ivtecs {
  d: path("M15.217 8.903c1.002-.315 2.31.226 2.31 1.563c-.646-.36-1.931-.5-2.388-.36z");
}

.lzuhtkbmu {
  d: path("M21.835 24.617c-1.17-2.04-3.78-2.73-5.81-1.56l-2.43 1.4c-2.04 1.17-2.73 3.78-1.56 5.81l.21.33h7.73l.3-.18a4.23 4.23 0 0 0 1.56-5.8");
}

.m0rm-m-qv {
  stop-color: var(--svg-color--785191, #785191);
}

.m1p0iqb0j {
  d: path("m13.752 11.058l-.224 1.807a.55.55 0 0 0 .651.608l.791-.144a.553.553 0 0 0 .396-.798l-.846-1.613c-.183-.357-.717-.26-.768.14");
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mdfm2pbfq {
  d: path("M21.575 24.537a4.3 4.3 0 0 1 .71-5.22a4.31 4.31 0 0 0-2.61 6.21a4.304 4.304 0 0 0 6.78 1.01c-1.84.51-3.87-.26-4.88-2");
}

.mih5kfbap {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
}

.mmhc2bhnh {
  stroke: var(--svg-color--e2b79f, #E2B79F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m16.874 26.888l1.634 1.14");
}

.mv8kv7beo {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
}

.mvuactshi {
  stop-color: var(--svg-color--c49070, #C49070);
  stop-opacity: 0;
}

.n8jici3hn {
  stop-color: var(--svg-color--fed466, #FED466);
  stop-opacity: 0;
}

.nbcoryb1h {
  stop-color: var(--svg-color--bf7c89, #BF7C89);
}

.neym138jd {
  stop-color: var(--svg-color--f3c22a, #F3C22A);
}

.njdbcpw8w {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.nn3wh7bnm {
  stop-color: var(--svg-color--58d4f5, #58D4F5);
}

.npl7d4bom {
  stop-color: var(--svg-color--eeb696, #EEB696);
  stop-opacity: 0;
}

.nu_77rrcl {
  stop-color: var(--svg-color--c7977a, #C7977A);
}

.o-ef0ac2e {
  stop-color: var(--svg-color--d8a788, #D8A788);
  stop-opacity: 0;
}

.o2dl4_b2z {
  stop-color: var(--svg-color--cd9682, #CD9682);
}

.o7yf4tl0b {
  stop-color: var(--svg-color--b087f9, #B087F9);
}

.ohwd33b2n {
  stop-color: var(--svg-color--b8757a, #B8757A);
}

.p_ew-572a {
  stop-color: var(--svg-color--8152c8, #8152C8);
  stop-opacity: 0;
}

.p1sg1mumi {
  stop-color: var(--svg-color--ffc3a8, #FFC3A8);
  stop-opacity: 0;
}

.p40qzpbtf {
  stop-color: var(--svg-color--985ef1, #985EF1);
}

.p6n8nbb9p {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
  stop-opacity: 0;
}

.p6otu2-6b {
  stop-color: var(--svg-color--ffffbe, #FFFFBE);
}

.pdon63boo {
  stop-color: var(--svg-color--f38820, #F38820);
  stop-opacity: 0;
}

.piz2rbc3b {
  stop-color: var(--svg-color--875ab4, #875AB4);
  stop-opacity: 0;
}

.pkd_tvbsd {
  stop-color: var(--svg-color--bf8a73, #BF8A73);
}

.pll5kd_nw {
  stop-color: var(--svg-color--dfae8f, #DFAE8F);
}

.pqpdkgb0y {
  stop-color: var(--svg-color--bf8a73, #BF8A73);
  stop-opacity: 0;
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.psvt8ubmu {
  stop-color: var(--svg-color--8356d1, #8356D1);
  stop-opacity: 0;
}

.pviihufyn {
  stop-color: var(--svg-color--784787, #784787);
  stop-opacity: 0;
}

.q5mih6mme {
  stop-color: var(--svg-color--e5ae90, #E5AE90);
}

.q6xuj5bcq {
  d: path("M8.13 17.84c1.031-1.086 1.92-1.37 2.32-1.375l.797.867l-.93 3.516c-.179.315-.563.996-.695 1.152c-.164.195-.734.63-1.765.238c-.888-.337-1.15-.898-1.176-1.148c.234-1.168.649-2.358 1.45-3.25");
}

.q9xywcr7e {
  stop-color: var(--svg-color--9c6ed3, #9C6ED3);
}

.qa8u2ebfn {
  d: path("M10.992 11.573c.125.117.498.339.983.286c.485-.052.91-.522 1.02-.7");
}

.qbj7jig8q {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M14.735 14.28a3.1 3.1 0 0 1-1.493-.087c-.155-.048-.277.142-.164.257a1.975 1.975 0 0 0 3.268-.594c.064-.153-.117-.283-.245-.183a3.1 3.1 0 0 1-1.366.606");
}

.qflnpfbur {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
}

.qh-ows9fr {
  stop-color: var(--svg-color--a07cb6, #A07CB6);
}

.qic_n_blg {
  stop-color: var(--svg-color--d2c9d1, #D2C9D1);
}

.ql2-nbc9p {
  stop-color: var(--svg-color--9a6b40, #9A6B40);
  stop-opacity: 0;
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qtvy6rbzh {
  stop-color: var(--svg-color--42b8e0, #42B8E0);
}

.r7ne7db4d {
  d: path("M9.706 13.285a1.098 1.098 0 1 0-.393-2.16a1.098 1.098 0 0 0 .393 2.16");
}

.r8owzxbqs {
  stop-color: var(--svg-color--bf7c89, #BF7C89);
  stop-opacity: 0;
}

.rb5pqrony {
  stop-color: var(--svg-color--d5a079, #D5A079);
}

.rehc034in {
  stop-color: var(--svg-color--8356d1, #8356D1);
}

.rf88abbhx {
  stop-color: var(--svg-color--f1b493, #F1B493);
  stop-opacity: 0;
}

.rgj3eviuu {
  d: path("M10.099 17.059c.356.125.482.33.515.453l.446.39l2.291.362a.92.92 0 0 0 1.062-.871a.913.913 0 0 0-.922-.95c-1.175.013-2.687.035-3.044.026c-.586-.016-.793.433-.348.59");
}

.rjxj417_v {
  stop-color: var(--svg-color--f9bfa4, #F9BFA4);
}

.rlkxcjbek {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.735 14.28a3.1 3.1 0 0 1-1.493-.087c-.155-.048-.277.142-.164.257a1.975 1.975 0 0 0 3.268-.594c.064-.153-.117-.283-.245-.183a3.1 3.1 0 0 1-1.366.606Z");
}

.rntqzsbvm {
  stop-color: var(--svg-color--925cbe, #925CBE);
}

.rvz7hrbgf {
  stop-color: var(--svg-color--cb9c79, #CB9C79);
}

.s0czm0m0d {
  d: path("M15.685 19.128c1.06 0 1.91-.86 1.91-1.91v-2.26a1.91 1.91 0 1 0-3.82 0v2.26c-.01 1.06.85 1.91 1.91 1.91");
}

.s1z0g59pt {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m13.767 11.2l-.377 1.834a.55.55 0 0 0 .652.608l.79-.144a.553.553 0 0 0 .396-.798l-.845-1.613c-.183-.357-.565-.288-.616.112");
}

.s7k33p2vn {
  stop-color: var(--svg-color--eeb696, #EEB696);
}

.sbx2zkbbn {
  stop-color: var(--svg-color--89579c, #89579C);
  stop-opacity: 0;
}

.sel15-yew {
  stop-color: var(--svg-color--95663c, #95663C);
  stop-opacity: 0;
}

.sg8a2viwh {
  stop-color: var(--svg-color--c58b71, #C58B71);
}

.shxh5dbbc {
  stop-color: var(--svg-color--ab767c, #AB767C);
}

.sinn-3bvk {
  stop-color: var(--svg-color--6cd8f5, #6CD8F5);
  stop-opacity: 0;
}

.skpmm1_2p {
  d: path("M8.521 19.078a.28.28 0 0 1 .133-.27c.981-.69 2.005-.304 2.383 0c.304.236 1 .79 1.363 1.082c.446.36.372.961.043 1.317c-.276.297-.751.24-.93.148l-2.097-1.312c-.055-.313-.235-.563-.48-.637c-.247-.074-.403-.133-.415-.328");
}

.sok9f40_l {
  stop-color: var(--svg-color--efc3a5, #EFC3A5);
}

.sqmgyf2vi {
  stop-color: var(--svg-color--c49070, #C49070);
}

.sv4maabhu {
  stop-color: var(--svg-color--c78979, #C78979);
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.t78i98bfv {
  stop-color: var(--svg-color--735caf, #735CAF);
  stop-opacity: 0;
}

.ta36f8b7v {
  stop-color: var(--svg-color--c7897d, #C7897D);
}

.tbs366q3s {
  stop-color: var(--svg-color--4760c0, #4760C0);
}

.tjgs2ub-w {
  stop-color: var(--svg-color--efc3a7, #EFC3A7);
}

.tlxyqtbtq {
  stop-color: var(--svg-color--b56e74, #B56E74);
}

.tnk2b_bjh {
  stop-color: var(--svg-color--a078e0, #A078E0);
}

.tomvu1bgl {
  stop-color: var(--svg-color--78e0ff, #78E0FF);
}

.tryqaac1t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.tzj34xnjq {
  stop-color: var(--svg-color--ffd267, #FFD267);
}

.u1r8ksb5m {
  stop-color: var(--svg-color--d8a29e, #D8A29E);
  stop-opacity: 0;
}

.u1zlaqbml {
  stop-color: var(--svg-color--bc7b6b, #BC7B6B);
  stop-opacity: 0;
}

.ucqc4tbff {
  d: path("M19.35 12.087a1.645 1.645 0 1 0-.588-3.237a1.645 1.645 0 0 0 .589 3.237");
}

.ue-yx0baa {
  stop-color: var(--svg-color--c58e72, #C58E72);
  stop-opacity: 0;
}

.ugbytbngn {
  stop-color: var(--svg-color--ffd267, #FFD267);
  stop-opacity: 0;
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.ut4bgvb0y {
  stop-color: var(--svg-color--8a68c3, #8A68C3);
}

.uxh2dv17l {
  stop-color: var(--svg-color--bc7b6b, #BC7B6B);
}

.uxpb5qzbn {
  stop-color: var(--svg-color--cd9b7f, #CD9B7F);
}

.uy3z2gbbp {
  stop-color: var(--svg-color--ffc59d, #FFC59D);
}

.v-9s4u7ch {
  stop-color: var(--svg-color--cf987b, #CF987B);
  stop-opacity: 0;
}

.v2wkn2ras {
  stop-color: var(--svg-color--31ae6a, #31AE6A);
}

.v442oubmz {
  stop-color: var(--svg-color--7c4ca4, #7C4CA4);
}

.v4sppzb3c {
  d: path("m15.454 21.362l.227.069a.5.5 0 0 0 .492-.12l.363-.353a.13.13 0 0 1 .128-.033l.315.084a.484.484 0 0 0 .253-.935l-.304-.083a.13.13 0 0 1-.097-.109l-.069-.44a.5.5 0 0 0-.36-.404l-.26-.071z");
}

.vrnylccvf {
  stop-color: var(--svg-color--dcc893, #DCC893);
}

.vsvz-xe_v {
  stop-color: var(--svg-color--c58b71, #C58B71);
  stop-opacity: 0;
}

.w_57dfb5m {
  stop-color: var(--svg-color--735caf, #735CAF);
}

.w58maet4h {
  stop-color: var(--svg-color--dac493, #DAC493);
  stop-opacity: 0;
}

.wagk6dfaq {
  stop-color: var(--svg-color--966be0, #966BE0);
}

.wcbvx-n_a {
  stop-color: var(--svg-color--89579c, #89579C);
}

.wi8a08bum {
  stop-color: var(--svg-color--785191, #785191);
  stop-opacity: 0;
}

.wv-vkgbpx {
  fill: var(--svg-color--966333, #966333);
  d: path("m10.46 10.185l-.004.004a.274.274 0 0 1-.361-.413h.001l.003-.003l.008-.007a2 2 0 0 1 .136-.105c.09-.065.22-.151.383-.237c.322-.172.783-.35 1.315-.353a.274.274 0 1 1 .003.548a2.3 2.3 0 0 0-1.061.289a3 3 0 0 0-.423.277");
}

.x_lm5vbjz {
  stop-color: var(--svg-color--c99d90, #C99D90);
}

.x3-dq7n1x {
  d: path("M10.453 9.816c1.323-.253 2.318.58 2.589 1.317c-1.36.201-1.98.13-2.4.356z");
}

.x9s6ceaht {
  stop-color: var(--svg-color--b087f9, #B087F9);
  stop-opacity: 0;
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.y-e90cbvt {
  d: path("M8.18 6.199c.524-.67 1.424-.84 1.946-.842l.64 1.225c-.265.007-.48.14-.64.36c-.148 1.768-1.913 1.828-2.02 3.153c-.425-1.472-.83-2.74.075-3.896");
}

.y-ymn0bhn {
  stop-color: var(--svg-color--755994, #755994);
}

.y0dl1gblq {
  stop-color: var(--svg-color--b8757a, #B8757A);
  stop-opacity: 0;
}

.ybvptdnhb {
  stop-color: var(--svg-color--c58e72, #C58E72);
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.yhs2bn2id {
  stop-color: var(--svg-color--f4c099, #F4C099);
}

.ymidocb-e {
  d: path("m8.855 11.012l.013-.003l-.06-.264l-.065-.306c-.153-.958.336-1.429.551-1.595l.048-.03l.048-.03c.491-.344.846-.853.97-1.459l.048-.21a.27.27 0 0 1 .454-.136a3.95 3.95 0 0 0 3.513 1.1l3.238-.589c.182-.033 1.105-.11 1.386 1.132l.443 3.112c.388 2.841-1.468 5.134-4.155 5.622c-2.686.488-5.231-1.004-5.868-3.8z");
}

.ytn_p5bjt {
  stop-color: var(--svg-color--95663c, #95663C);
}

.yxf64pxyp {
  stop-color: var(--svg-color--b4837b, #B4837B);
  stop-opacity: 0;
}

.yxmxw0ard {
  stop-color: var(--svg-color--32996b, #32996B);
}

.yyn9swbvh {
  stop-color: var(--svg-color--784787, #784787);
}

.z_ej81lhd {
  d: path("M10.214 22.284c-.284.88-1.448 1.292-2.6.92c-1.152-.37-1.793-1.177-1.573-2.265c.18-.888.884-1.75 2.738-1.24c1.153.372 1.719 1.705 1.435 2.585");
}

.z_gh6vsyy {
  stop-color: var(--svg-color--ab6850, #AB6850);
}

.z-0xo4bpn {
  d: path("M17.169 10.272c-.077.01-.135.058-.183.125a1.06 1.06 0 0 1-.712.49a.98.98 0 0 1-.827-.22a.28.28 0 0 0-.212-.058a.257.257 0 0 0-.115.452c.336.279.789.413 1.25.327a1.54 1.54 0 0 0 1.068-.741c.106-.183-.057-.414-.27-.375");
}

.z1zjblq2q {
  stop-color: var(--svg-color--8b5dd1, #8B5DD1);
  stop-opacity: 0;
}

.z3zsa5bpu {
  stop-color: var(--svg-color--53f595, #53F595);
}

.z8oy8ibbe {
  stop-color: var(--svg-color--d1a082, #D1A082);
  stop-opacity: 0;
}

.zbwshaccu {
  stop-color: var(--svg-color--875ab4, #875AB4);
}

.zcr9jykfw {
  stop-color: var(--svg-color--e6bd9f, #E6BD9F);
}

.zft5ozi2a {
  stop-color: var(--svg-color--724520, #724520);
}

.zi044qmod {
  d: path("M20.615 26.375c1.598-.231 4.567-.81 6.543-1.27c1.522-.263 2.641 1.203 2.641 2.78c0 1.372-1.022 2.237-1.747 2.62a.86.86 0 0 1-.403.092h-8.014v-3.086c0-.797.281-1 .98-1.136");
}

.zl0m7hb-l {
  d: path("M8.857 21.527c-.315.22-.723.211-.906-.11c-.391-.947.72-1.579 1.5-1.597c1.167-.027 1.75.63 1.937 1.121c.188.492.227 1.477-.672 1.54c-.803.055-.847-.5-.98-.743c-.133-.242-.594-.41-.879-.21");
}

.zq2cu-lqa {
  stop-color: var(--svg-color--dcaa8a, #DCAA8A);
  stop-opacity: 0;
}

.zs6y5wbab {
  stop-color: var(--svg-color--9f6a39, #9F6A39);
}

.zx-utrb8d {
  stop-color: var(--svg-color--dcab8c, #DCAB8C);
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
