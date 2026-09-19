<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#irCpJWd)"><path fill="url(#iaUsmrb)" class="f1jw_ab3w"/><path fill="url(#iTDnx1x)" class="f1jw_ab3w"/></g><path class="b_qv5du4s"/><path fill="url(#i6KAjab)" class="faisxaclj"/><path fill="url(#i2gSgbe)" class="faisxaclj"/><path fill="url(#idcBZkt)" class="faisxaclj"/><path fill="url(#iiLw8Vb)" class="faisxaclj"/><path fill="url(#iAIO9Yd)" class="faisxaclj"/><path fill="url(#isZrtzc)" class="faisxaclj"/><path fill="url(#iJkm9gA)" class="d_-1b_bzw"/><path fill="url(#ih3vBxb)" class="d_-1b_bzw"/><path fill="url(#iov0n7a)" class="d_-1b_bzw"/><path fill="url(#inI3Unb)" class="vylrb5bvm"/><path fill="url(#i4dn0Mr)" class="vylrb5bvm"/><path fill="url(#iWkx0Sd)" class="ix8bgh62p"/><g filter="url(#ilCzGkd)"><path fill="url(#ibgFUYd)" clip-rule="evenodd" class="zdsg9r3jo"/><path fill="url(#iYgYbde)" clip-rule="evenodd" class="zdsg9r3jo"/><path fill="url(#iSuBe6b)" clip-rule="evenodd" class="zdsg9r3jo"/><path fill="url(#iak8rNL)" clip-rule="evenodd" class="zdsg9r3jo"/></g><path fill="url(#iU4Plhc)" class="v-7fbqiwn"/><path fill="url(#ifQNUod)" class="v-7fbqiwn"/><g filter="url(#iQhSkfe)"><path fill="url(#icL13gd)" class="v-7fbqiwn"/><path fill="url(#i1P7Cub)" class="v-7fbqiwn"/></g><circle fill="url(#izpPp3b)" class="tkhdkpbce"/><circle fill="url(#iD4IhnT)" class="tkhdkpbce"/><g filter="url(#inlbtEe)"><circle class="kukv_4b_b"/></g><g filter="url(#iBwVPAb)"><circle class="l2s-wurxl"/><circle fill="url(#iyFP3te)" class="hsxzvqy4o"/><circle fill="url(#idG2Uyc)" class="hsxzvqy4o"/></g><g filter="url(#icVttSH)"><circle class="qhd5dxcrq"/></g><g filter="url(#ityh45d)"><path fill="url(#iNOSpZz)" class="lm8r1pr4t"/><path fill="url(#i4KBaMd)" class="lm8r1pr4t"/><path fill="url(#iHSqgCb)" class="lm8r1pr4t"/><path fill="url(#imKquuc)" class="lm8r1pr4t"/><path fill="url(#iJM8Psc)" class="lm8r1pr4t"/></g><path fill="url(#iFbGSze)" class="lm8r1pr4t"/><path fill="url(#iIw7yRd)" class="lm8r1pr4t"/><g filter="url(#iCOUn5c)"><path class="zqposzt5c"/></g><g filter="url(#iyL5tDe)"><path class="hmm2c-v5f"/><path fill="url(#iMS3BSx)" class="o1x8h3r2q"/><path fill="url(#iURUeje)" class="o1x8h3r2q"/><path fill="url(#i6osQyH)" class="o1x8h3r2q"/></g><g filter="url(#iUSERXb)"><path stroke="url(#ipYZ4Ib)" class="sxxssefjt"/></g><path class="i15-jieoq"/><path fill="url(#i6HgKEe)" class="a21sivbkm"/><path fill="url(#ijOGFYb)" class="a21sivbkm"/><path fill="url(#i2hRt0c)" class="woypneq9w"/><path fill="url(#iT0oNkb)" class="woypneq9w"/><path class="fi-x3fd2i"/><path fill="url(#iTj44ee)" class="kpuob0boc"/><path class="cbqhwfbtv"/><g filter="url(#izly1eb)"><path class="ulr9nxwkx"/><path fill="url(#iSmMrck)" class="q5yddtbxq"/></g><g filter="url(#iqszfmb)"><path fill="url(#ireYXpd)" class="i8g1is6ei"/></g><path class="ovltyxb-z"/><path fill="url(#iGIkCVd)" class="mydl7xn4h"/><path class="j_11em0kz"/><g filter="url(#ipYrNWz)"><path fill="url(#i8qdxEb)" class="ol0f2wtuo"/></g><g filter="url(#ij5BAbc)"><ellipse transform="rotate(-27.914 11.994 10.006)" class="nml16ybzs"/><ellipse fill="url(#i9jdwta)" transform="rotate(-27.914 11.994 10.006)" class="zaojz1b_o"/></g><path fill="url(#iHZvJfc)" class="hgn0v4h0b"/><path fill="url(#ilxTFMd)" class="hgn0v4h0b"/><path fill="url(#izHz1gd)" class="hgn0v4h0b"/><path fill="url(#iFF74De)" class="hgn0v4h0b"/><path fill="url(#ia6hdgb)" class="hgn0v4h0b"/><path class="d6l_zva3n"/><path fill="url(#inGX0Oc)" class="u_wc6ubhb"/><path fill="url(#iiH6veK)" class="u_wc6ubhb"/><path fill="url(#iI4mEsd)" class="u_wc6ubhb"/><path fill="url(#iN2yeVc)" class="u_wc6ubhb"/><path fill="url(#iMEPogb)" class="w_8w8wqmn"/><path fill="url(#iutMDkb)" class="w_8w8wqmn"/><path fill="url(#ih18itd)" class="w_8w8wqmn"/><g filter="url(#i3hVbBY)"><path fill="url(#iKGw4kt)" class="qv2uf3bxt"/><path fill="url(#iyoBo3i)" class="qv2uf3bxt"/></g><g filter="url(#iJuMYkb)"><path fill="url(#iatOxCb)" class="n4s-q-b8n"/><path fill="url(#iQy6vPz)" class="n4s-q-b8n"/></g><path fill="url(#iqw3Vdd)" class="n4s-q-b8n"/><path fill="url(#iZmNjZb)" class="n4s-q-b8n"/><g filter="url(#iwDVdle)"><path fill="url(#i5b1ojc)" class="rys9ifzwf"/><path fill="url(#ifSfzbe)" class="rys9ifzwf"/><path fill="url(#ih6dC9c)" class="rys9ifzwf"/></g><g filter="url(#imMugFb)"><path fill="url(#ibijqYb)" class="drnn9_b6l"/><path fill="url(#iDqb5ve)" class="drnn9_b6l"/><path fill="url(#iJhoPse)" class="drnn9_b6l"/></g><g filter="url(#i2qy5sb)"><path fill="url(#i9kTuLc)" class="uf71gn07a"/></g><g filter="url(#iOEBSwc)"><path stroke="url(#i2bdjSd)" class="cj_ualb6i"/></g><g filter="url(#i9BaVwd)"><path class="cd1yj8bur"/></g><path fill="url(#iiphUsz)" class="mkmtnejgf"/><path fill="url(#iJLeJDd)" class="yu5aht8rs"/><path fill="url(#i1i1Lbq)" class="m94o2m2wq"/><path fill="url(#izpcbVd)" class="m94o2m2wq"/><path fill="url(#iZ6eZGb)" class="m94o2m2wq"/><path fill="url(#ibPujte)" class="m94o2m2wq"/><path fill="url(#i6qz0xW)" class="m94o2m2wq"/><defs><radialGradient id="i6KAjab" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.43636 -8.2868 0 14.582 15.942)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="ze-km1b7g"/><stop offset="1" class="nfddei0pp"/></radialGradient><radialGradient id="i2gSgbe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -8.375 13.302 26.254)" gradientUnits="userSpaceOnUse"><stop class="ls7-cblkb"/><stop offset="1" class="tbz0q_48a"/></radialGradient><radialGradient id="idcBZkt" cx="0" cy="0" r="1" gradientTransform="matrix(-1.625 0 0 -5.46875 21.646 26.129)" gradientUnits="userSpaceOnUse"><stop class="voemc8h9d"/><stop offset="1" class="osd7ifb8c"/></radialGradient><radialGradient id="iiLw8Vb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.40626 -1.21873 1.72833 -6.24868 19.552 23.941)" gradientUnits="userSpaceOnUse"><stop offset=".273" class="d-ykpkboz"/><stop offset="1" class="f8x3opbgo"/></radialGradient><radialGradient id="iAIO9Yd" cx="0" cy="0" r="1" gradientTransform="matrix(-11.0625 0 0 -16.6672 18.302 22.722)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="eqb1ki6td"/><stop offset="1" class="dmxjdc_5c"/></radialGradient><radialGradient id="isZrtzc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55668 4.16175 -7.47563 -2.79621 19.02 16.26)" gradientUnits="userSpaceOnUse"><stop class="nuif9xlfl"/><stop offset="1" class="o41nkwbqu"/></radialGradient><radialGradient id="iJkm9gA" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.7832 3.37648 0 6.864 29.754)" gradientUnits="userSpaceOnUse"><stop offset=".658" class="q_n5wkbyq"/><stop offset="1" class="x8m9vebtt"/></radialGradient><radialGradient id="iov0n7a" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.8437 2.89364 0 7.607 29.972)" gradientUnits="userSpaceOnUse"><stop class="ygstjnb_e"/><stop offset="1" class="idk0shbpn"/></radialGradient><radialGradient id="inI3Unb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.40144 -2.74144 0 24.114 23.977)" gradientUnits="userSpaceOnUse"><stop class="deg-o6bbc"/><stop offset="1" class="q-uw1wb3b"/></radialGradient><radialGradient id="i4dn0Mr" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.5625 -2.47704 0 21.577 22.973)" gradientUnits="userSpaceOnUse"><stop offset=".036" class="mr8fywmtc"/><stop offset="1" class="bcdc9wb8u"/></radialGradient><radialGradient id="iYgYbde" cx="0" cy="0" r="1" gradientTransform="matrix(1.27004 2.2186 -1.58976 .91006 11.157 16.066)" gradientUnits="userSpaceOnUse"><stop class="hq-8cac3q"/><stop offset="1" class="kiftlkrmt"/></radialGradient><radialGradient id="iSuBe6b" cx="0" cy="0" r="1" gradientTransform="matrix(2.40644 .94026 -.49363 1.26336 12.19 16.067)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><radialGradient id="iak8rNL" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8125 -2.20052 0 13.3 16.854)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="z1374kqmn"/><stop offset="1" class="t3ca9xlms"/></radialGradient><radialGradient id="ifQNUod" cx="0" cy="0" r="1" gradientTransform="matrix(4.58258 0 0 1.4028 13.993 16.065)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><radialGradient id="icL13gd" cx="0" cy="0" r="1" gradientTransform="rotate(136.408 5.786 11.704)scale(4.35086 4.82952)" gradientUnits="userSpaceOnUse"><stop class="dxbo1t_fa"/><stop offset="1" class="kvhp_ip6r"/></radialGradient><radialGradient id="i1P7Cub" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82813 -3.16462 0 14.8 16.87)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="poqt_ebqs"/><stop offset="1" class="yl696wcmm"/></radialGradient><radialGradient id="izpPp3b" cx="0" cy="0" r="1" gradientTransform="matrix(.31248 -1.89063 3.30861 .54685 8.863 11.5)" gradientUnits="userSpaceOnUse"><stop offset=".367" class="ekq35twuc"/><stop offset="1" class="df7f4ogpx"/></radialGradient><radialGradient id="iD4IhnT" cx="0" cy="0" r="1" gradientTransform="matrix(-1.4019 1.10939 -1.2568 -1.58818 9.702 10.702)" gradientUnits="userSpaceOnUse"><stop offset=".835" class="d34nnfb-n"/><stop offset="1" class="rfs_rin6c"/></radialGradient><radialGradient id="iyFP3te" cx="0" cy="0" r="1" gradientTransform="matrix(1.10937 1.64063 -.65427 .44241 20.113 9.249)" gradientUnits="userSpaceOnUse"><stop class="lvo87lomq"/><stop offset="1" class="y2fkb6jnb"/></radialGradient><radialGradient id="idG2Uyc" cx="0" cy="0" r="1" gradientTransform="matrix(1.57813 -.5625 .3712 1.04142 19.44 12.234)" gradientUnits="userSpaceOnUse"><stop class="qrdncac1g"/><stop offset="1" class="u5_5zfb4f"/></radialGradient><radialGradient id="iNOSpZz" cx="0" cy="0" r="1" gradientTransform="rotate(169.919 7.987 6.94)scale(5.7132 6.79758)" gradientUnits="userSpaceOnUse"><stop class="ffchh-jyy"/><stop offset="1" class="dvxio-_1e"/></radialGradient><radialGradient id="i4KBaMd" cx="0" cy="0" r="1" gradientTransform="rotate(94.201 4.36 11.01)scale(10.0896 9.63966)" gradientUnits="userSpaceOnUse"><stop offset=".754" class="q8y_xbdcm"/><stop offset=".985" class="j2dd0um8b"/></radialGradient><radialGradient id="imKquuc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60857 0 16.795 9.512)" gradientUnits="userSpaceOnUse"><stop class="op2kwubyv"/><stop offset="1" class="wvivicznw"/></radialGradient><radialGradient id="iJM8Psc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39075 1.72952 0 12.238 9.479)" gradientUnits="userSpaceOnUse"><stop class="y7nn5tbfc"/><stop offset="1" class="uylyaxbnq"/></radialGradient><radialGradient id="iIw7yRd" cx="0" cy="0" r="1" gradientTransform="matrix(-.92115 -8.21875 14.84644 -1.66398 14.487 16)" gradientUnits="userSpaceOnUse"><stop offset=".679" class="ii8qowb4p"/><stop offset=".977" class="gvam1kukd"/></radialGradient><radialGradient id="i6HgKEe" cx="0" cy="0" r="1" gradientTransform="matrix(-.97032 -.55868 .32287 -.56077 18.269 8.736)" gradientUnits="userSpaceOnUse"><stop class="z6vn4l8jx"/><stop offset="1" class="w9wtfmbvi"/></radialGradient><radialGradient id="ijOGFYb" cx="0" cy="0" r="1" gradientTransform="matrix(.38281 -1.32812 2.30975 .66575 17.222 8.913)" gradientUnits="userSpaceOnUse"><stop offset=".583" class="v4tzru_xz"/><stop offset="1" class="lzzxe0u6x"/></radialGradient><radialGradient id="i2hRt0c" cx="0" cy="0" r="1" gradientTransform="matrix(1.30035 -.9225 .53312 .7515 10.484 9.008)" gradientUnits="userSpaceOnUse"><stop class="z6vn4l8jx"/><stop offset="1" class="w9wtfmbvi"/></radialGradient><radialGradient id="iT0oNkb" cx="0" cy="0" r="1" gradientTransform="matrix(.28906 -1.36277 2.37012 .50273 11.784 8.898)" gradientUnits="userSpaceOnUse"><stop offset=".584" class="v4tzru_xz"/><stop offset="1" class="lzzxe0u6x"/></radialGradient><radialGradient id="iTj44ee" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90308 -1.06858 0 16.628 10.435)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iSmMrck" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 10.694 1.077)scale(.37817 .52064)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iGIkCVd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90312 -1.06863 0 12.266 10.435)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i9jdwta" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.07 -.736)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iHZvJfc" cx="0" cy="0" r="1" gradientTransform="rotate(116.696 8.04 7.094)scale(6.12125 6.5789)" gradientUnits="userSpaceOnUse"><stop class="zraasrypm"/><stop offset="1" class="wt7c97xxx"/></radialGradient><radialGradient id="izHz1gd" cx="0" cy="0" r="1" gradientTransform="matrix(.73215 -3.875 1.71541 .32411 8.289 7.066)" gradientUnits="userSpaceOnUse"><stop class="nl8hdv5-q"/><stop offset="1" class="kmg6h4b5x"/></radialGradient><radialGradient id="iFF74De" cx="0" cy="0" r="1" gradientTransform="matrix(-1.125 1.28124 -3.60476 -3.16519 19.646 3.098)" gradientUnits="userSpaceOnUse"><stop class="iyfczmh7s"/><stop offset="1" class="m2b3l_8kx"/></radialGradient><radialGradient id="ia6hdgb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.73438 4.0625 0 10.833 7.191)" gradientUnits="userSpaceOnUse"><stop class="n4fn3obqp"/><stop offset="1" class="h9dvmcbxu"/></radialGradient><radialGradient id="inGX0Oc" cx="0" cy="0" r="1" gradientTransform="matrix(-14.5563 0 0 -2.0625 21.577 27.816)" gradientUnits="userSpaceOnUse"><stop class="cv6gnzbto"/><stop offset="1" class="wl84mmb3d"/></radialGradient><radialGradient id="iN2yeVc" cx="0" cy="0" r="1" gradientTransform="rotate(104.338 -1.768 20.747)scale(7.1928 1.69685)" gradientUnits="userSpaceOnUse"><stop class="sl-gsib3f"/><stop offset="1" class="mr-s-pbar"/></radialGradient><radialGradient id="iutMDkb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.27624 -.62648 0 14.961 21.755)" gradientUnits="userSpaceOnUse"><stop class="krttc8bap"/><stop offset="1" class="kpneurz6b"/></radialGradient><radialGradient id="ih18itd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.41436 1.45816 0 14.582 25.827)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="ko6eamtic"/><stop offset="1" class="tc4y5tbfa"/></radialGradient><radialGradient id="iKGw4kt" cx="0" cy="0" r="1" gradientTransform="rotate(167.143 8.463 3.484)scale(2.97716 4.69784)" gradientUnits="userSpaceOnUse"><stop class="ism0j8_fd"/><stop offset="1" class="cc4vnjblc"/></radialGradient><radialGradient id="iyoBo3i" cx="0" cy="0" r="1" gradientTransform="matrix(2.81253 -2.28745 2.84526 3.49839 11.927 7.285)" gradientUnits="userSpaceOnUse"><stop class="kx5tbm42q"/><stop offset="1" class="ndetd3gmc"/></radialGradient><radialGradient id="iQy6vPz" cx="0" cy="0" r="1" gradientTransform="rotate(100.623 .526 19.636)scale(1.16051 4.42408)" gradientUnits="userSpaceOnUse"><stop class="pfbpewb0p"/><stop offset="1" class="dutea5bgy"/></radialGradient><radialGradient id="iqw3Vdd" cx="0" cy="0" r="1" gradientTransform="matrix(-.83594 .34375 -.14238 -.34624 23.107 16.395)" gradientUnits="userSpaceOnUse"><stop class="xdf0lfbrm"/><stop offset="1" class="cvnvm48dp"/></radialGradient><radialGradient id="iZmNjZb" cx="0" cy="0" r="1" gradientTransform="matrix(.83594 .17968 -.05863 .27278 21.786 16.332)" gradientUnits="userSpaceOnUse"><stop class="leotspfhb"/><stop offset="1" class="u3sz7tboa"/></radialGradient><radialGradient id="ifSfzbe" cx="0" cy="0" r="1" gradientTransform="matrix(1.3287 1.76599 -.65664 .49404 19.852 16.946)" gradientUnits="userSpaceOnUse"><stop class="qu53-3efb"/><stop offset="1" class="d8vnolbdv"/></radialGradient><radialGradient id="ih6dC9c" cx="0" cy="0" r="1" gradientTransform="matrix(1.46875 .4375 -1.25756 4.22181 18.833 19.379)" gradientUnits="userSpaceOnUse"><stop class="fcewfubec"/><stop offset="1" class="ku_tac4_z"/></radialGradient><radialGradient id="ibijqYb" cx="0" cy="0" r="1" gradientTransform="rotate(135.9 10.028 15.777)scale(4.22106 5.23602)" gradientUnits="userSpaceOnUse"><stop class="ybzdb35ne"/><stop offset="1" class="k-xo7erne"/></radialGradient><radialGradient id="iDqb5ve" cx="0" cy="0" r="1" gradientTransform="matrix(-4 -.68747 1.04434 -6.0764 28.646 22.503)" gradientUnits="userSpaceOnUse"><stop offset=".711" class="d7eq7sb9j"/><stop offset="1" class="pci0oxh-l"/></radialGradient><radialGradient id="iJhoPse" cx="0" cy="0" r="1" gradientTransform="rotate(156.903 12.063 12.55)scale(1.15509 2.08846)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="a6yl-cb9v"/><stop offset="1" class="w_w8qcl3c"/></radialGradient><radialGradient id="iiphUsz" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.5625 1.65625 0 8.894 9.937)" gradientUnits="userSpaceOnUse"><stop offset=".011" class="gtqk7ibwh"/><stop offset="1" class="upz45mbij"/></radialGradient><radialGradient id="iJLeJDd" cx="0" cy="0" r="1" gradientTransform="matrix(.75781 -2.32813 1.10327 .35912 19.488 10)" gradientUnits="userSpaceOnUse"><stop offset=".472" class="l5amp9o6y"/><stop offset="1" class="vifyrqjmy"/></radialGradient><radialGradient id="izpcbVd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.33866 0 0 -.95307 18.703 7.174)" gradientUnits="userSpaceOnUse"><stop offset=".169" class="xr_40cc2f"/><stop offset="1" class="kjxybmb-y"/></radialGradient><radialGradient id="iZ6eZGb" cx="0" cy="0" r="1" gradientTransform="matrix(1.03125 1.48437 -13.62738 9.46743 6.63 8.144)" gradientUnits="userSpaceOnUse"><stop class="ehnthvqoy"/><stop offset="1" class="rzbfz4btw"/></radialGradient><radialGradient id="ibPujte" cx="0" cy="0" r="1" gradientTransform="matrix(-.96093 -.6172 .84322 -1.31284 7.677 9.129)" gradientUnits="userSpaceOnUse"><stop offset=".501" class="rz-l4sb2t"/><stop offset="1" class="nqxo4gbph"/></radialGradient><radialGradient id="i6qz0xW" cx="0" cy="0" r="1" gradientTransform="matrix(.75 -.5625 1.05375 1.405 22.02 9.035)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="euqyawb2g"/><stop offset="1" class="vkwv3acem"/></radialGradient><linearGradient id="iaUsmrb" x1="14.587" x2="14.587" y1="7.972" y2="19.472" gradientUnits="userSpaceOnUse"><stop class="usw0jac_r"/><stop offset="1" class="zhmn0cciw"/></linearGradient><linearGradient id="iTDnx1x" x1="14.587" x2="14.587" y1="7.249" y2="10.843" gradientUnits="userSpaceOnUse"><stop class="l1qje4b6x"/><stop offset="1" class="vx6m-x__v"/></linearGradient><linearGradient id="ih3vBxb" x1="7.607" x2="6.489" y1="26.66" y2="26.629" gradientUnits="userSpaceOnUse"><stop class="gyzg0db3w"/><stop offset="1" class="y28tkbl-n"/></linearGradient><linearGradient id="iWkx0Sd" x1="15.654" x2="15.654" y1="15.025" y2="21.362" gradientUnits="userSpaceOnUse"><stop class="vq76pqe1z"/><stop offset=".456" class="kmmuo7biq"/><stop offset="1" class="c3htxbc9y"/></linearGradient><linearGradient id="ibgFUYd" x1="11.238" x2="13.128" y1="18.01" y2="18.01" gradientUnits="userSpaceOnUse"><stop class="ggy1amtma"/><stop offset="1" class="ctz7grpzo"/></linearGradient><linearGradient id="iU4Plhc" x1="13.277" x2="13.489" y1="18.098" y2="18.098" gradientUnits="userSpaceOnUse"><stop class="lwl8ufbrj"/><stop offset="1" class="i5hn1bqvd"/></linearGradient><linearGradient id="iHSqgCb" x1="9.054" x2="11.366" y1="13.869" y2="13.567" gradientUnits="userSpaceOnUse"><stop class="ls27mhbfe"/><stop offset="1" class="ys1ri2qqc"/></linearGradient><linearGradient id="iFbGSze" x1="19.284" x2="17.847" y1="13.53" y2="13.468" gradientUnits="userSpaceOnUse"><stop class="dkj9a_bqd"/><stop offset="1" class="hgxaawb9n"/></linearGradient><linearGradient id="iMS3BSx" x1="13.585" x2="14.523" y1="11.832" y2="11.832" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="iURUeje" x1="15.388" x2="14.362" y1="12.155" y2="12.14" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="i6osQyH" x1="14.644" x2="14.644" y1="12.897" y2="12.324" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="ipYZ4Ib" x1="13.412" x2="13.847" y1="14.512" y2="13.824" gradientUnits="userSpaceOnUse"><stop class="pn2_jabhi"/><stop offset=".663" class="z9945l-5h"/></linearGradient><linearGradient id="ireYXpd" x1="17.406" x2="17.092" y1="10.155" y2="10.349" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i8qdxEb" x1="13.009" x2="12.695" y1="10.155" y2="10.348" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ilxTFMd" x1="10.646" x2="16.989" y1="6.723" y2="6.723" gradientUnits="userSpaceOnUse"><stop class="ks1omcbjp"/><stop offset="1" class="jk0lbnbnn"/></linearGradient><linearGradient id="iiH6veK" x1="14.592" x2="14.592" y1="30.316" y2="28.723" gradientUnits="userSpaceOnUse"><stop class="s2qawgbpe"/><stop offset="1" class="iu5oamiyf"/></linearGradient><linearGradient id="iI4mEsd" x1="14.592" x2="14.592" y1="26.173" y2="27.441" gradientUnits="userSpaceOnUse"><stop class="tcape2laf"/><stop offset="1" class="gd-vr7bgk"/></linearGradient><linearGradient id="iMEPogb" x1="14.582" x2="14.582" y1="19.605" y2="26.175" gradientUnits="userSpaceOnUse"><stop class="jbzirjbuq"/><stop offset="1" class="s7s75dkrn"/></linearGradient><linearGradient id="iatOxCb" x1="22.021" x2="18.333" y1="16.754" y2="29.973" gradientUnits="userSpaceOnUse"><stop class="ommdktbpj"/><stop offset="1" class="dinvdlb3p"/></linearGradient><linearGradient id="i5b1ojc" x1="20.021" x2="28.208" y1="22.191" y2="18.879" gradientUnits="userSpaceOnUse"><stop class="lf_6el-zz"/><stop offset="1" class="p6qk4rbue"/></linearGradient><linearGradient id="i9kTuLc" x1="14.458" x2="14.458" y1="4.221" y2="6.666" gradientUnits="userSpaceOnUse"><stop class="rx-q5b7rc"/><stop offset="1" class="fz8-ywb6c"/></linearGradient><linearGradient id="i2bdjSd" x1="18.689" x2="20.193" y1="21.647" y2="16.457" gradientUnits="userSpaceOnUse"><stop class="ih4zzfygk"/><stop offset="1" class="bq_18tbdo"/></linearGradient><linearGradient id="i1i1Lbq" x1="14.582" x2="14.582" y1="6.972" y2="11.754" gradientUnits="userSpaceOnUse"><stop offset=".526" class="ffurleovf"/><stop offset=".654" class="oirct-bua"/></linearGradient><filter id="irCpJWd" width="17.197" height="11.9" x="5.989" y="7.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.137255 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2615"/></filter><filter id="ilCzGkd" width="6.88" height="3.666" x="11.157" y="15.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.0470588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2615"/></filter><filter id="iQhSkfe" width="4.97" height="3.828" x="13.277" y="15.815" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.12549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2615"/></filter><filter id="inlbtEe" width="2.49" height="2.49" x="8.457" y="9.539" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2615" stdDeviation=".125"/></filter><filter id="iBwVPAb" width="3.589" height="3.589" x="17.545" y="8.864" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2615"/></filter><filter id="icVttSH" width="2.49" height="2.49" x="17.97" y="9.539" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2615" stdDeviation=".125"/></filter><filter id="ityh45d" width="10.39" height="12.177" x="9.292" y="5.159" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.501961 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2615"/></filter><filter id="iCOUn5c" width="3.26" height="4.181" x="12.581" y="9.629" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2615" stdDeviation=".375"/></filter><filter id="iyL5tDe" width="2.377" height="3.181" x="13.261" y="9.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2615" stdDeviation=".125"/></filter><filter id="iUSERXb" width="3.617" height="1.472" x="12.641" y="13.367" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2615" stdDeviation=".05"/></filter><filter id="izly1eb" width=".787" height=".696" x="15.894" y="9.662" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2615" stdDeviation=".05"/></filter><filter id="iqszfmb" width=".891" height=".913" x="16.734" y="9.737" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2615" stdDeviation=".1"/></filter><filter id="ipYrNWz" width=".986" height="1.04" x="12.292" y="9.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2615" stdDeviation=".1"/></filter><filter id="ij5BAbc" width=".913" height=".704" x="11.538" y="9.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2615" stdDeviation=".05"/></filter><filter id="i3hVbBY" width="5.52" height="4.05" x="11.827" y="3.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.415686 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2615"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.2 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2615" result="effect2_innerShadow_4002_2615"/></filter><filter id="iJuMYkb" width="6.94" height="14.221" x="16.577" y="15.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.270588 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2615"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.266667 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2615" result="effect2_innerShadow_4002_2615"/></filter><filter id="iwDVdle" width="11.012" height="8.855" x="17.86" y="16.47" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.0980392 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2615"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.270588 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2615" result="effect2_innerShadow_4002_2615"/></filter><filter id="imMugFb" width="4.557" height="7.476" x="23.816" y="17.698" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.760784 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2615"/></filter><filter id="i2qy5sb" width="2.509" height="3.213" x="13.154" y="3.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.141176 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_2615"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_2615" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.768627 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_2615"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.337255 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_2615" result="effect3_innerShadow_4002_2615"/></filter><filter id="iOEBSwc" width="1.83" height="4.718" x="18.091" y="17.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2615" stdDeviation=".125"/></filter><filter id="i9BaVwd" width="2.769" height="7.081" x="18.396" y="23.072" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2615" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-firefighter-medium-light" /></template>
<style>
.a21sivbkm {
  d: path("m18.169 8.064l-.002-.001l-.001-.002l-.005-.003l-.012-.01a1.4 1.4 0 0 0-.155-.107c-.1-.063-.24-.14-.42-.211a2.83 2.83 0 0 0-1.492-.158a.534.534 0 0 0 .166 1.054c.398-.063.717.01.934.096a1.5 1.5 0 0 1 .308.166a.534.534 0 0 0 .679-.824");
}

.a6yl-cb9v {
  stop-color: var(--svg-color--eeecf0, #EEECF0);
}

.b_qv5du4s {
  fill: var(--svg-color--dc375e, #DC375E);
  d: path("M14.587 15.472c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.bcdc9wb8u {
  stop-color: var(--svg-color--d54161, #D54161);
  stop-opacity: 0;
}

.bq_18tbdo {
  stop-color: var(--svg-color--cd517b, #CD517B);
  stop-opacity: 0;
}

.c3htxbc9y {
  stop-color: var(--svg-color--ec098c, #EC098C);
}

.cbqhwfbtv {
  fill: var(--svg-color--000, #000);
  d: path("M16.12 10.517c0-.284.226-.51.51-.51a.51.51 0 0 1 .454.745h-.904a.46.46 0 0 1-.06-.235");
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

.cj_ualb6i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m19.546 17.972l-1.08 3.968");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ctz7grpzo {
  stop-color: var(--svg-color--be2450, #BE2450);
}

.cv6gnzbto {
  stop-color: var(--svg-color--fec852, #FEC852);
}

.cvnvm48dp {
  stop-color: var(--svg-color--a17d74, #A17D74);
  stop-opacity: 0;
}

.d_-1b_bzw {
  d: path("M7.607 29.972V17.971a10.98 10.98 0 0 0-4.02 8.501v3.5z");
}

.d-ykpkboz {
  stop-color: var(--svg-color--c6284c, #C6284C);
}

.d34nnfb-n {
  stop-color: var(--svg-color--c48777, #C48777);
  stop-opacity: 0;
}

.d6l_zva3n {
  fill: var(--svg-color--ecb845, #ECB845);
  d: path("M21.577 26.173H7.607v3.8h13.97z");
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

.df7f4ogpx {
  stop-color: var(--svg-color--a5624f, #A5624F);
}

.dinvdlb3p {
  stop-color: var(--svg-color--785253, #785253);
}

.dkj9a_bqd {
  stop-color: var(--svg-color--f0bb98, #F0BB98);
}

.dmxjdc_5c {
  stop-color: var(--svg-color--d0465e, #D0465E);
}

.drnn9_b6l {
  d: path("M25.649 18.01a3.5 3.5 0 0 0 .85-.171l.148-.055c.179-.062.401-.053.555.108c1.071 1.125 1.43 2.62.983 4.235s-1.732 2.764-2.98 3.034c-.084.02-.348.045-.505-.158l-.142-.14a3.5 3.5 0 0 0-.642-.588c1.567-.052 2.817-1.084 3.203-2.53c.39-1.468-.236-3.002-1.472-3.735z");
}

.dutea5bgy {
  stop-color: var(--svg-color--734145, #734145);
  stop-opacity: 0;
}

.dvxio-_1e {
  stop-color: var(--svg-color--cc937f, #CC937F);
}

.dxbo1t_fa {
  stop-color: var(--svg-color--ff547f, #FF547F);
}

.ehnthvqoy {
  stop-color: var(--svg-color--b3576b, #B3576B);
}

.ekq35twuc {
  stop-color: var(--svg-color--ba7467, #BA7467);
}

.eqb1ki6td {
  stop-color: var(--svg-color--d0465e, #D0465E);
  stop-opacity: 0;
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

.fcewfubec {
  stop-color: var(--svg-color--c93271, #C93271);
}

.ffchh-jyy {
  stop-color: var(--svg-color--f8bc9b, #F8BC9B);
}

.ffurleovf {
  stop-color: var(--svg-color--bb2b57, #BB2B57);
}

.fi-x3fd2i {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.837 9.353c.653 0 1.204.45 1.355 1.058a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.27a1.4 1.4 0 0 1 1.371-1.128");
}

.ft5dv1b6b {
  fill: none;
}

.fz8-ywb6c {
  stop-color: var(--svg-color--f48942, #F48942);
}

.gd-vr7bgk {
  stop-color: var(--svg-color--edb63d, #EDB63D);
  stop-opacity: 0;
}

.ggy1amtma {
  stop-color: var(--svg-color--d53260, #D53260);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gs643vbjw {
  stop-color: var(--svg-color--cb9173, #CB9173);
}

.gtqk7ibwh {
  stop-color: var(--svg-color--d09975, #D09975);
}

.gvam1kukd {
  stop-color: var(--svg-color--b77159, #B77159);
}

.gyzg0db3w {
  stop-color: var(--svg-color--bf415a, #BF415A);
}

.h9dvmcbxu {
  stop-color: var(--svg-color--c52632, #C52632);
  stop-opacity: 0;
}

.hgn0v4h0b {
  d: path("M20.885 7.333H8.29v-.378c0-2.734 2.01-4.927 5.02-4.927h2.411c3.329 0 5.165 2.193 5.165 4.927z");
}

.hgxaawb9n {
  stop-color: var(--svg-color--f0bb98, #F0BB98);
  stop-opacity: 0;
}

.hmm2c-v5f {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m14.067 10.498l-.531 1.7a.54.54 0 0 0 .52.699h.786a.54.54 0 0 0 .52-.7l-.53-1.699c-.114-.376-.646-.376-.765 0");
}

.hq-8cac3q {
  stop-color: var(--svg-color--c75567, #C75567);
}

.hsxzvqy4o {
  cx: 19.215px;
  cy: 10.783px;
  r: 1.669px;
}

.i15-jieoq {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M14.45 13.913c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.084-.197.209c.334.507.918.845 1.582.845c.665 0 1.248-.338 1.583-.845c.087-.13-.06-.279-.198-.21c-.4.21-.872.33-1.385.33");
}

.i5hn1bqvd {
  stop-color: var(--svg-color--ca435d, #CA435D);
  stop-opacity: 0;
}

.i8g1is6ei {
  d: path("M17.425 10.4a.84.84 0 0 0-.231-.463l-.26.285l.117.228z");
}

.idk0shbpn {
  stop-color: var(--svg-color--c03959, #C03959);
  stop-opacity: 0;
}

.ih4zzfygk {
  stop-color: var(--svg-color--cd517b, #CD517B);
}

.ii8qowb4p {
  stop-color: var(--svg-color--b57572, #B57572);
  stop-opacity: 0;
}

.ism0j8_fd {
  stop-color: var(--svg-color--675b70, #675B70);
}

.iu5oamiyf {
  stop-color: var(--svg-color--d9a73c, #D9A73C);
  stop-opacity: 0;
}

.ix8bgh62p {
  d: path("M13.277 15.972v2.66c0 .56.45 1.01 1.01 1.01h1.78c1.09 0 1.98-.89 1.98-1.98v-1.69z");
}

.iyfczmh7s {
  stop-color: var(--svg-color--fd5c7c, #FD5C7C);
}

.j_11em0kz {
  fill: var(--svg-color--000, #000);
  d: path("M12.774 10.517a.51.51 0 0 0-.51-.51a.51.51 0 0 0-.455.745h.905a.5.5 0 0 0 .06-.235");
}

.j2dd0um8b {
  stop-color: var(--svg-color--bc5d65, #BC5D65);
}

.j5-d0iboi {
  stop-color: var(--svg-color--c71931, #C71931);
  stop-opacity: 0;
}

.jbzirjbuq {
  stop-color: var(--svg-color--ba2f50, #BA2F50);
}

.jk0lbnbnn {
  stop-color: var(--svg-color--be324c, #BE324C);
  stop-opacity: 0;
}

.k-xo7erne {
  stop-color: var(--svg-color--cdc6d4, #CDC6D4);
}

.kiftlkrmt {
  stop-color: var(--svg-color--c75567, #C75567);
  stop-opacity: 0;
}

.kjxybmb-y {
  stop-color: var(--svg-color--fc5083, #FC5083);
  stop-opacity: 0;
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

.kpuob0boc {
  d: path("M16.63 9.625a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.127");
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

.kukv_4b_b {
  cx: 9.702px;
  cy: 10.784px;
  r: 0.995px;
  fill: var(--svg-color--ac6958, #AC6958);
}

.kvhp_ip6r {
  stop-color: var(--svg-color--df3d67, #DF3D67);
}

.kx5tbm42q {
  stop-color: var(--svg-color--3d2b40, #3D2B40);
}

.l1qje4b6x {
  stop-color: var(--svg-color--710425, #710425);
}

.l2s-wurxl {
  cx: 19.215px;
  cy: 10.783px;
  r: 1.669px;
  fill: var(--svg-color--d19b89, #D19B89);
}

.l5amp9o6y {
  stop-color: var(--svg-color--d39c77, #D39C77);
}

.lemuo5beu {
  stop-color: var(--svg-color--c98583, #C98583);
  stop-opacity: 0;
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

.lm8r1pr4t {
  d: path("M9.292 8.733c0-.403.102-.944.366-1.207c.268-.213.492-.233.492-.553v-.854c0-.266.16-.48.429-.533c.644-.16 1.984-.427 3.915-.427s3.272.267 3.916.427c.214.053.429.267.429.533v.854c0 .32.235.446.45.66c.501.351.396.738.354 1.153c-.18 1.791-.234 3.6-.355 5.398c-.16 1.77-1.551 3.002-3.21 3.002h-3.21c-1.712 0-3.05-1.233-3.21-3.002c-.14-1.825-.2-3.64-.366-5.451");
}

.ls27mhbfe {
  stop-color: var(--svg-color--d99e84, #D99E84);
}

.ls7-cblkb {
  stop-color: var(--svg-color--dd365e, #DD365E);
}

.lvo87lomq {
  stop-color: var(--svg-color--b06b52, #B06B52);
}

.lwl8ufbrj {
  stop-color: var(--svg-color--ca435d, #CA435D);
}

.lzzxe0u6x {
  stop-color: var(--svg-color--672b14, #672B14);
}

.m2b3l_8kx {
  stop-color: var(--svg-color--fd5c7c, #FD5C7C);
  stop-opacity: 0;
}

.m94o2m2wq {
  d: path("M8.659 7.972h11.846c.95 0 1.99.485 1.99 2.68h.69V9.347c0-1.43-.847-2.375-2.456-2.375H8.435c-1.609 0-2.456.946-2.456 2.375v1.305h.69c0-2.195 1.04-2.68 1.99-2.68");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mkmtnejgf {
  d: path("M9.593 7.946h-.908q-.16 0-.321.02c.098.497.322 1.419.428 1.753c.112.357.475.461.621.47c-.016-.321-.065-1.101-.065-1.557c0-.356.13-.574.245-.686");
}

.mr-s-pbar {
  stop-color: var(--svg-color--bc832d, #BC832D);
  stop-opacity: 0;
}

.mr8fywmtc {
  stop-color: var(--svg-color--b91a3e, #B91A3E);
}

.mydl7xn4h {
  d: path("M12.264 9.625a.892.892 0 0 0-.86 1.127h1.723a1 1 0 0 0 .033-.235a.9.9 0 0 0-.896-.892");
}

.n4fn3obqp {
  stop-color: var(--svg-color--c52632, #C52632);
}

.n4s-q-b8n {
  d: path("m22.636 16.137l-1.38-.368a.51.51 0 0 0-.625.358l-3.804 13.846h2.547l3.63-13.212a.53.53 0 0 0-.368-.624");
}

.ndetd3gmc {
  stop-color: var(--svg-color--3d2b40, #3D2B40);
  stop-opacity: 0;
}

.nfddei0pp {
  stop-color: var(--svg-color--c51b40, #C51B40);
  stop-opacity: 0;
}

.nl8hdv5-q {
  stop-color: var(--svg-color--bd585d, #BD585D);
}

.nml16ybzs {
  cx: 11.994px;
  cy: 10.006px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.nqxo4gbph {
  stop-color: var(--svg-color--a21e3e, #A21E3E);
  stop-opacity: 0;
}

.nuif9xlfl {
  stop-color: var(--svg-color--ff385e, #FF385E);
}

.o1x8h3r2q {
  d: path("m14.067 10.498l-.531 1.7a.54.54 0 0 0 .52.699h.786a.54.54 0 0 0 .52-.7l-.53-1.699c-.114-.376-.646-.376-.765 0");
}

.o41nkwbqu {
  stop-color: var(--svg-color--ff385e, #FF385E);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oirct-bua {
  stop-color: var(--svg-color--bb2b57, #BB2B57);
  stop-opacity: 0;
}

.ol0f2wtuo {
  d: path("M13.079 10.412c0-.288-.235-.48-.298-.539l-.289.28l.178.36z");
}

.ommdktbpj {
  stop-color: var(--svg-color--8f5b56, #8F5B56);
}

.op2kwubyv {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
}

.osd7ifb8c {
  stop-color: var(--svg-color--d23b59, #D23B59);
  stop-opacity: 0;
}

.ovltyxb-z {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.057 9.353c-.653 0-1.205.45-1.355 1.058c-.045.175.09.34.268.34h2.23a.23.23 0 0 0 .227-.27a1.4 1.4 0 0 0-1.37-1.128");
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

.pn2_jabhi {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
}

.poqt_ebqs {
  stop-color: var(--svg-color--98072e, #98072E);
}

.q_n5wkbyq {
  stop-color: var(--svg-color--d93b60, #D93B60);
}

.q-uw1wb3b {
  stop-color: var(--svg-color--c7425f, #C7425F);
}

.q5yddtbxq {
  d: path("M16.565 9.814c.063.085-.07.188-.22.301c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.05");
}

.q8y_xbdcm {
  stop-color: var(--svg-color--c27d7d, #C27D7D);
  stop-opacity: 0;
}

.qhd5dxcrq {
  cx: 19.214px;
  cy: 10.784px;
  r: 0.995px;
  fill: var(--svg-color--c48771, #C48771);
}

.qrdncac1g {
  stop-color: var(--svg-color--ce8d78, #CE8D78);
}

.qu53-3efb {
  stop-color: var(--svg-color--fc4b93, #FC4B93);
}

.qv2uf3bxt {
  d: path("M17.247 6.973h-5.32v-1.29c0-1.47 1.19-2.66 2.66-2.66s2.66 1.19 2.66 2.66z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.rfs_rin6c {
  stop-color: var(--svg-color--c48777, #C48777);
}

.rx-q5b7rc {
  stop-color: var(--svg-color--f1b244, #F1B244);
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.rys9ifzwf {
  d: path("m20.012 16.732l4.416 1.16a3.57 3.57 0 0 0 2.071-.053l.148-.055c.179-.062.401-.053.555.108c1.071 1.125 1.43 2.62.983 4.235s-1.732 2.765-2.98 3.034c-.084.02-.348.046-.505-.158l-.142-.14a3.5 3.5 0 0 0-1.745-1.11L18.57 22.55a.61.61 0 0 1-.43-.779l1.25-4.675c.045-.22.37-.43.622-.364");
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

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.sl-gsib3f {
  stop-color: var(--svg-color--bc832d, #BC832D);
}

.sxxssefjt {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.45 13.913c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.084-.197.209c.334.507.918.845 1.582.845c.665 0 1.248-.338 1.583-.845c.087-.13-.06-.279-.198-.21c-.4.21-.872.33-1.385.33Z");
}

.t3ca9xlms {
  stop-color: var(--svg-color--9b0831, #9B0831);
  stop-opacity: 0;
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

.tkhdkpbce {
  cx: 9.702px;
  cy: 10.783px;
  r: 1.669px;
}

.u_wc6ubhb {
  d: path("M21.577 26.173H7.607v3.8h13.97z");
}

.u3sz7tboa {
  stop-color: var(--svg-color--8c5e57, #8C5E57);
  stop-opacity: 0;
}

.u5_5zfb4f {
  stop-color: var(--svg-color--ce8d78, #CE8D78);
  stop-opacity: 0;
}

.uf71gn07a {
  d: path("M13.304 4.91c0-.154.183-.232.293-.126l.155.149a.162.162 0 0 0 .274-.117v-.17c0-.345.179-.665.472-.847l.18-.111a.23.23 0 0 1 .35.195v1.194a.17.17 0 0 0 .278.132l.096-.078a.129.129 0 0 1 .21.1v.333a1.154 1.154 0 0 1-2.308-.052z");
}

.ulr9nxwkx {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.565 9.814c.063.085-.07.188-.22.301c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.05");
}

.upz45mbij {
  stop-color: var(--svg-color--aa7253, #AA7253);
}

.usw0jac_r {
  stop-color: var(--svg-color--a9112c, #A9112C);
}

.uylyaxbnq {
  stop-color: var(--svg-color--c2837a, #C2837A);
  stop-opacity: 0;
}

.v-7fbqiwn {
  d: path("M13.277 16.934v1.699c0 .56.45 1.01 1.01 1.01h1.78c1.09 0 1.98-.89 1.98-1.98v-1.598a3.94 3.94 0 0 1-2.498.887h-1.896q-.19 0-.376-.018");
}

.v4tzru_xz {
  stop-color: var(--svg-color--672b14, #672B14);
  stop-opacity: 0;
}

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vifyrqjmy {
  stop-color: var(--svg-color--ba7e59, #BA7E59);
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

.w9wtfmbvi {
  stop-color: var(--svg-color--763d2d, #763D2D);
}

.wl84mmb3d {
  stop-color: var(--svg-color--fec852, #FEC852);
  stop-opacity: 0;
}

.woypneq9w {
  d: path("m10.676 8.064l.002-.001l.002-.002l.004-.003l.012-.01a1.4 1.4 0 0 1 .155-.107c.1-.063.24-.14.42-.211a2.83 2.83 0 0 1 1.492-.158a.534.534 0 0 1-.166 1.054a1.77 1.77 0 0 0-.934.096a1.5 1.5 0 0 0-.308.166a.534.534 0 0 1-.679-.824");
}

.wt7c97xxx {
  stop-color: var(--svg-color--f44f5a, #F44F5A);
}

.wvivicznw {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
  stop-opacity: 0;
}

.x8m9vebtt {
  stop-color: var(--svg-color--df6277, #DF6277);
}

.xdf0lfbrm {
  stop-color: var(--svg-color--a17d74, #A17D74);
}

.xr_40cc2f {
  stop-color: var(--svg-color--fc5083, #FC5083);
}

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
  stop-opacity: 0;
}

.y28tkbl-n {
  stop-color: var(--svg-color--bf415a, #BF415A);
  stop-opacity: 0;
}

.y2fkb6jnb {
  stop-color: var(--svg-color--b06b52, #B06B52);
  stop-opacity: 0;
}

.y7nn5tbfc {
  stop-color: var(--svg-color--c2837a, #C2837A);
}

.ybzdb35ne {
  stop-color: var(--svg-color--ded9e3, #DED9E3);
}

.ygstjnb_e {
  stop-color: var(--svg-color--99344a, #99344A);
}

.yl696wcmm {
  stop-color: var(--svg-color--98072e, #98072E);
  stop-opacity: 0;
}

.ys1ri2qqc {
  stop-color: var(--svg-color--d99e84, #D99E84);
  stop-opacity: 0;
}

.yu5aht8rs {
  d: path("M19.358 7.972h1.148l.085.002a24 24 0 0 1-.432 1.772c-.112.356-.498.457-.644.465c.016-.32.088-1.085.088-1.553c0-.356-.13-.574-.245-.686");
}

.z1374kqmn {
  stop-color: var(--svg-color--9b0831, #9B0831);
}

.z6vn4l8jx {
  stop-color: var(--svg-color--8c5735, #8C5735);
}

.z9945l-5h {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
  stop-opacity: 0;
}

.zaojz1b_o {
  cx: 11.994px;
  cy: 10.006px;
  rx: 0.389px;
  ry: 0.197px;
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

.zj8ulgbnv {
  stop-color: var(--svg-color--c71931, #C71931);
}

.zqposzt5c {
  fill: var(--svg-color--c68378, #C68378);
  d: path("m14.174 10.662l-.82 1.699c-.102.35.142.7.488.7h.737c.346 0 .59-.356.488-.7l-.498-1.7c-.107-.376-.283-.376-.395 0");
}

.zraasrypm {
  stop-color: var(--svg-color--f0406f, #F0406F);
}

</style>
