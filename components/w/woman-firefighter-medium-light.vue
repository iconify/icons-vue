<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ioRL4cb)"><path fill="url(#iaUsmrb)" class="wow_zkb9s"/><path fill="url(#i1ptMxc)" class="wow_zkb9s"/></g><path fill="url(#i0ofdFb)" clip-rule="evenodd" class="vu_hqmbug"/><path fill="url(#iV6Tnid)" clip-rule="evenodd" class="vu_hqmbug"/><path fill="url(#inGR2Wb)" clip-rule="evenodd" class="vu_hqmbug"/><path fill="url(#iAH3JJb)" clip-rule="evenodd" class="vu_hqmbug"/><path fill="url(#ilALHwe)" clip-rule="evenodd" class="vu_hqmbug"/><path fill="url(#iKt6z0c)" clip-rule="evenodd" class="vu_hqmbug"/><path fill="url(#izlG5dc)" clip-rule="evenodd" class="vu_hqmbug"/><path fill="url(#ivullPH)" clip-rule="evenodd" class="vu_hqmbug"/><path fill="url(#iIqPkJd)" clip-rule="evenodd" class="vu_hqmbug"/><path fill="url(#i85G4ad)" clip-rule="evenodd" class="vu_hqmbug"/><path class="b_qv5du4s"/><path fill="url(#i6KAjab)" class="faisxaclj"/><path fill="url(#i2gSgbe)" class="faisxaclj"/><path fill="url(#idcBZkt)" class="faisxaclj"/><path fill="url(#iiLw8Vb)" class="faisxaclj"/><path fill="url(#iAIO9Yd)" class="faisxaclj"/><path fill="url(#isZrtzc)" class="faisxaclj"/><path fill="url(#iJkm9gA)" class="d_-1b_bzw"/><path fill="url(#ih3vBxb)" class="d_-1b_bzw"/><path fill="url(#iov0n7a)" class="d_-1b_bzw"/><path fill="url(#inI3Unb)" class="vylrb5bvm"/><path fill="url(#i4dn0Mr)" class="vylrb5bvm"/><path fill="url(#i0i1YkC)" class="dbj0sjb-p"/><path fill="url(#iI325ic)" class="ja-6i29rv"/><path fill="url(#iJe4SFj)" class="n4wu3h9rb"/><path fill="url(#irTl7Kb)" class="n4wu3h9rb"/><g filter="url(#inEg4qd)"><path fill="url(#inniGRJ)" class="o1z42mbzo"/><path fill="url(#iA8ZMom)" class="o1z42mbzo"/><path fill="url(#iAPgRxc)" class="o1z42mbzo"/></g><g filter="url(#i8175gd)"><path class="e3fuicbbj"/><path fill="url(#ix3Vm9b)" class="ogeiazbnd"/></g><g filter="url(#ioA6zMc)"><path fill="url(#iSAk0Yc)" class="mb3jp1v8b"/></g><g filter="url(#iHwfK7a)"><path fill="url(#ii4bTab)" class="tvc8pfc3q"/><path fill="url(#iiPmtab)" class="tvc8pfc3q"/><path fill="url(#ikH1PDe)" class="tvc8pfc3q"/><path fill="url(#ie4WeDc)" class="tvc8pfc3q"/><path fill="url(#itqFTKb)" class="tvc8pfc3q"/><path fill="url(#iKzRXwe)" class="tvc8pfc3q"/><path fill="url(#iySBGMb)" class="tvc8pfc3q"/></g><path fill="url(#ioxFwdZ)" class="tvc8pfc3q"/><path fill="url(#i4Q9qNe)" class="tvc8pfc3q"/><path fill="url(#iQiAJwb)" class="tvc8pfc3q"/><g filter="url(#ieIIv5b)"><path class="cehcmrgdp"/></g><g filter="url(#iUdNmoh)"><path class="gsj9ur0da"/><path fill="url(#iBYZPVc)" class="fpbtup0si"/><path fill="url(#iZUS8zn)" class="fpbtup0si"/><path fill="url(#iEZgiod)" class="fpbtup0si"/></g><g filter="url(#ihF5kic)"><path stroke="url(#ibDvXxd)" class="i7oravbrz"/></g><path class="qfttj6irk"/><g filter="url(#imvhurJ)"><path class="xywzy8ndz"/></g><g filter="url(#iZwzX4d)"><path class="bkko43bzn"/></g><g filter="url(#iXmNBpe)"><path fill="url(#iI2LXbb)" class="cpiqqqbun"/></g><g filter="url(#iunDHuc)"><path fill="url(#iDQSWIC)" clip-rule="evenodd" class="ys-qt6bso"/></g><path class="akbxqtdqb"/><path fill="url(#i8Dqt3V)" class="nzwwulvqt"/><path class="c46klzb_q"/><g filter="url(#iERRPUc)"><path class="vj8wpab3w"/><path fill="url(#iTlyUPU)" class="r_igwxbib"/></g><g filter="url(#iOCFI3d)"><path fill="url(#i9TrwHc)" class="p6m80wacn"/></g><path class="oul1uklww"/><path fill="url(#ifvhBxe)" class="xjp5tobqs"/><path class="pgid_yb4z"/><g filter="url(#iC2TbAb)"><path fill="url(#iLFL9Cb)" class="u24ulrb-c"/></g><g filter="url(#i27XHfx)"><ellipse transform="rotate(-27.914 12.13 10.066)" class="in1yifh9k"/><ellipse fill="url(#i8ZQjwb)" transform="rotate(-27.914 12.13 10.066)" class="eeu386bau"/></g><path fill="url(#iHZvJfc)" class="hgn0v4h0b"/><path fill="url(#ilxTFMd)" class="hgn0v4h0b"/><path fill="url(#izHz1gd)" class="hgn0v4h0b"/><path fill="url(#iFF74De)" class="hgn0v4h0b"/><path fill="url(#ia6hdgb)" class="hgn0v4h0b"/><path class="d6l_zva3n"/><path fill="url(#inGX0Oc)" class="u_wc6ubhb"/><path fill="url(#iiH6veK)" class="u_wc6ubhb"/><path fill="url(#iI4mEsd)" class="u_wc6ubhb"/><path fill="url(#iN2yeVc)" class="u_wc6ubhb"/><path fill="url(#i1i1Lbq)" class="fw2o80b7i"/><path fill="url(#izpcbVd)" class="fw2o80b7i"/><path fill="url(#iZ6eZGb)" class="fw2o80b7i"/><path fill="url(#ibPujte)" class="fw2o80b7i"/><path fill="url(#i6qz0xW)" class="fw2o80b7i"/><path fill="url(#iMEPogb)" class="w_8w8wqmn"/><path fill="url(#iutMDkb)" class="w_8w8wqmn"/><path fill="url(#ih18itd)" class="w_8w8wqmn"/><g filter="url(#ie3B7Zc)"><path fill="url(#iKGw4kt)" class="qv2uf3bxt"/><path fill="url(#iyoBo3i)" class="qv2uf3bxt"/></g><g filter="url(#iPb19sd)"><path fill="url(#iatOxCb)" class="n4s-q-b8n"/><path fill="url(#iQy6vPz)" class="n4s-q-b8n"/></g><path fill="url(#iqw3Vdd)" class="n4s-q-b8n"/><path fill="url(#iZmNjZb)" class="n4s-q-b8n"/><g filter="url(#idp3bHz)"><path fill="url(#i5b1ojc)" class="e460wb-gs"/><path fill="url(#ifSfzbe)" class="e460wb-gs"/><path fill="url(#ih6dC9c)" class="e460wb-gs"/></g><g filter="url(#igK0aXb)"><path fill="url(#ibijqYb)" class="ghwogkbly"/><path fill="url(#iDqb5ve)" class="ghwogkbly"/><path fill="url(#iJhoPse)" class="ghwogkbly"/></g><g filter="url(#ioc3RQc)"><path fill="url(#i9kTuLc)" class="e0_2kpbjh"/></g><g filter="url(#iiuiWFe)"><path stroke="url(#iJ67e8c)" class="cj_ualb6i"/></g><g filter="url(#iT6L4eb)"><path class="cd1yj8bur"/></g><g filter="url(#iwMUkLe)"><path class="n3iibdccw"/><path fill="url(#iYgYbde)" class="eg6wwebxo"/><path fill="url(#iuLQ4mb)" class="eg6wwebxo"/></g><g filter="url(#ixto1mb)"><path fill="url(#icL13gd)" class="lcpiqzbvu"/></g><path fill="url(#iHtsopb)" class="lcpiqzbvu"/><path fill="url(#i0XH97d)" class="lcpiqzbvu"/><defs><radialGradient id="iV6Tnid" cx="0" cy="0" r="1" gradientTransform="rotate(106.702 1.578 7.218)scale(6.46003 8.13551)" gradientUnits="userSpaceOnUse"><stop class="yq9vgcc5u"/><stop offset="1" class="ltf10zbnq"/></radialGradient><radialGradient id="inGR2Wb" cx="0" cy="0" r="1" gradientTransform="rotate(109.654 1.042 6.393)scale(4.18108 1.99279)" gradientUnits="userSpaceOnUse"><stop offset=".427" class="u-hhbu3-q"/><stop offset="1" class="y_1578bkp"/></radialGradient><radialGradient id="iAH3JJb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.15625 -1.03125 0 10.038 8.624)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="jnxif700h"/><stop offset="1" class="bd3jihbsh"/></radialGradient><radialGradient id="ilALHwe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.28125 1.02507 0 7.088 12.937)" gradientUnits="userSpaceOnUse"><stop class="uf-8immry"/><stop offset="1" class="crdl31bat"/></radialGradient><radialGradient id="iKt6z0c" cx="0" cy="0" r="1" gradientTransform="rotate(-127.694 9.69 5.19)scale(5.21304 7.34861)" gradientUnits="userSpaceOnUse"><stop offset=".074" class="y811obbkp"/><stop offset="1" class="z7finb01k"/></radialGradient><radialGradient id="izlG5dc" cx="0" cy="0" r="1" gradientTransform="matrix(4.15627 -3.40623 3.31557 4.04565 17.694 16.374)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="x1a5p7bxz"/><stop offset="1" class="av1bb6bnt"/></radialGradient><radialGradient id="ivullPH" cx="0" cy="0" r="1" gradientTransform="matrix(1.53125 2.34375 -1.64728 1.07622 21.57 8.468)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="dy0k4hb5y"/><stop offset="1" class="epk82vsff"/></radialGradient><radialGradient id="iIqPkJd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.71875 1.21875 0 19.35 9.374)" gradientUnits="userSpaceOnUse"><stop class="rr357_h_e"/><stop offset="1" class="k28383b4e"/></radialGradient><radialGradient id="i85G4ad" cx="0" cy="0" r="1" gradientTransform="rotate(162.78 10.074 8.142)scale(1.47781 3.41625)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="cw1qesbgk"/><stop offset="1" class="qpiq3sr_w"/></radialGradient><radialGradient id="i6KAjab" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.43636 -8.2868 0 14.582 15.942)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="ze-km1b7g"/><stop offset="1" class="nfddei0pp"/></radialGradient><radialGradient id="i2gSgbe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.15625 0 0 -8.375 13.302 26.254)" gradientUnits="userSpaceOnUse"><stop class="ls7-cblkb"/><stop offset="1" class="tbz0q_48a"/></radialGradient><radialGradient id="idcBZkt" cx="0" cy="0" r="1" gradientTransform="matrix(-1.625 0 0 -5.46875 21.646 26.129)" gradientUnits="userSpaceOnUse"><stop class="voemc8h9d"/><stop offset="1" class="osd7ifb8c"/></radialGradient><radialGradient id="iiLw8Vb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.40626 -1.21873 1.72833 -6.24868 19.552 23.941)" gradientUnits="userSpaceOnUse"><stop offset=".273" class="d-ykpkboz"/><stop offset="1" class="f8x3opbgo"/></radialGradient><radialGradient id="iAIO9Yd" cx="0" cy="0" r="1" gradientTransform="matrix(-11.0625 0 0 -16.6672 18.302 22.722)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="eqb1ki6td"/><stop offset="1" class="dmxjdc_5c"/></radialGradient><radialGradient id="isZrtzc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55668 4.16175 -7.47563 -2.79621 19.02 16.26)" gradientUnits="userSpaceOnUse"><stop class="nuif9xlfl"/><stop offset="1" class="o41nkwbqu"/></radialGradient><radialGradient id="iJkm9gA" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.7832 3.37648 0 6.864 29.754)" gradientUnits="userSpaceOnUse"><stop offset=".658" class="q_n5wkbyq"/><stop offset="1" class="x8m9vebtt"/></radialGradient><radialGradient id="iov0n7a" cx="0" cy="0" r="1" gradientTransform="matrix(0 -11.8437 2.89364 0 7.607 29.972)" gradientUnits="userSpaceOnUse"><stop class="ygstjnb_e"/><stop offset="1" class="idk0shbpn"/></radialGradient><radialGradient id="inI3Unb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.40144 -2.74144 0 24.114 23.977)" gradientUnits="userSpaceOnUse"><stop class="deg-o6bbc"/><stop offset="1" class="q-uw1wb3b"/></radialGradient><radialGradient id="i4dn0Mr" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.5625 -2.47704 0 21.577 22.973)" gradientUnits="userSpaceOnUse"><stop offset=".036" class="mr8fywmtc"/><stop offset="1" class="bcdc9wb8u"/></radialGradient><radialGradient id="irTl7Kb" cx="0" cy="0" r="1" gradientTransform="rotate(154.511 3.705 6.618)scale(1.78259 1.99723)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="fk7yhmb2b"/><stop offset=".954" class="m__mqhxkh"/></radialGradient><radialGradient id="inniGRJ" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 18.623 11.437)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="iA8ZMom" cx="0" cy="0" r="1" gradientTransform="matrix(.9973 .28494 -.1498 .52432 19.645 9.216)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="iAPgRxc" cx="0" cy="0" r="1" gradientTransform="matrix(1.65677 1.30025 -.78028 .99422 19.76 9.212)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="l-wvb_5cy"/><stop offset="1" class="j7eo66bps"/></radialGradient><radialGradient id="ix3Vm9b" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 40.972 -47.945)scale(1.30459)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="iSAk0Yc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .89882 -1.25831 0 9.547 10.998)" gradientUnits="userSpaceOnUse"><stop offset=".323" class="px6vm6bxx"/><stop offset="1" class="thgnp9bsd"/></radialGradient><radialGradient id="ii4bTab" cx="0" cy="0" r="1" gradientTransform="rotate(165.171 8.081 6.914)scale(5.01064 5.13449)" gradientUnits="userSpaceOnUse"><stop class="nazz0ebnc"/><stop offset="1" class="gvh2bspmv"/></radialGradient><radialGradient id="iiPmtab" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10973 1.11592 -.94678 -1.78996 16.484 11.158)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="ikH1PDe" cx="0" cy="0" r="1" gradientTransform="matrix(.8369 -4.04513 5.13253 1.06187 12.404 17.243)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="ie4WeDc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.4375 -10.082 0 14.589 10.167)" gradientUnits="userSpaceOnUse"><stop offset=".684" class="sgt5sn5oc"/><stop offset="1" class="gxm-dc6uw"/></radialGradient><radialGradient id="itqFTKb" cx="0" cy="0" r="1" gradientTransform="rotate(172.34 7.182 6.907)scale(5.78399 9.95825)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="iKzRXwe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.65436 0 16.885 10.042)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="mt3h7fbpd"/><stop offset="1" class="wcr1klbjh"/></radialGradient><radialGradient id="iySBGMb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36 1.55865 0 12.665 10.13)" gradientUnits="userSpaceOnUse"><stop class="r-jog4w_t"/><stop offset="1" class="xjkdvxqyn"/></radialGradient><radialGradient id="ioxFwdZ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.35099 0 0 -4.43421 19.71 11.53)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="i4Q9qNe" cx="0" cy="0" r="1" gradientTransform="matrix(1.15972 4.21875 -8.7403 2.40267 12.091 4.954)" gradientUnits="userSpaceOnUse"><stop class="mih5kfbap"/><stop offset="1" class="kqfxh5bnm"/></radialGradient><radialGradient id="iQiAJwb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.3125 11.2521 0 14.599 15.718)" gradientUnits="userSpaceOnUse"><stop offset=".703" class="pa9r43ilj"/><stop offset=".966" class="ur-cqp2us"/></radialGradient><radialGradient id="iBYZPVc" cx="0" cy="0" r="1" gradientTransform="matrix(-.69746 -2.44974 1.40177 -.3991 15.368 12.021)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="iI2LXbb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79687 -.53902 .12266 -.4089 12.918 8.601)" gradientUnits="userSpaceOnUse"><stop class="ii4xdxbjp"/><stop offset="1" class="d34xtabjk"/></radialGradient><radialGradient id="iDQSWIC" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79687 -.53905 .12267 -.40892 18.335 8.601)" gradientUnits="userSpaceOnUse"><stop class="ii4xdxbjp"/><stop offset="1" class="d34xtabjk"/></radialGradient><radialGradient id="i8Dqt3V" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 16.765 10.162)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="f2mvkvbzb"/><stop offset="1" class="c-90s0tkg"/></radialGradient><radialGradient id="iTlyUPU" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 16.537 10.246)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ifvhBxe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 12.401 10.162)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="f2mvkvbzb"/><stop offset="1" class="c-90s0tkg"/></radialGradient><radialGradient id="i8ZQjwb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.167 -.773)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iHZvJfc" cx="0" cy="0" r="1" gradientTransform="rotate(116.696 8.04 7.094)scale(6.12125 6.5789)" gradientUnits="userSpaceOnUse"><stop class="zraasrypm"/><stop offset="1" class="wt7c97xxx"/></radialGradient><radialGradient id="izHz1gd" cx="0" cy="0" r="1" gradientTransform="matrix(.73215 -3.875 1.71541 .32411 8.289 7.066)" gradientUnits="userSpaceOnUse"><stop class="nl8hdv5-q"/><stop offset="1" class="kmg6h4b5x"/></radialGradient><radialGradient id="iFF74De" cx="0" cy="0" r="1" gradientTransform="matrix(-1.125 1.28124 -3.60476 -3.16519 19.646 3.098)" gradientUnits="userSpaceOnUse"><stop class="iyfczmh7s"/><stop offset="1" class="m2b3l_8kx"/></radialGradient><radialGradient id="ia6hdgb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.73438 4.0625 0 10.833 7.191)" gradientUnits="userSpaceOnUse"><stop class="n4fn3obqp"/><stop offset="1" class="h9dvmcbxu"/></radialGradient><radialGradient id="inGX0Oc" cx="0" cy="0" r="1" gradientTransform="matrix(-14.5563 0 0 -2.0625 21.577 27.816)" gradientUnits="userSpaceOnUse"><stop class="cv6gnzbto"/><stop offset="1" class="wl84mmb3d"/></radialGradient><radialGradient id="iN2yeVc" cx="0" cy="0" r="1" gradientTransform="rotate(104.338 -1.768 20.747)scale(7.1928 1.69685)" gradientUnits="userSpaceOnUse"><stop class="sl-gsib3f"/><stop offset="1" class="mr-s-pbar"/></radialGradient><radialGradient id="izpcbVd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.33866 0 0 -.95307 18.703 7.174)" gradientUnits="userSpaceOnUse"><stop offset=".169" class="xr_40cc2f"/><stop offset="1" class="kjxybmb-y"/></radialGradient><radialGradient id="iZ6eZGb" cx="0" cy="0" r="1" gradientTransform="matrix(1.03125 1.48437 -13.62738 9.46743 6.63 8.144)" gradientUnits="userSpaceOnUse"><stop class="ehnthvqoy"/><stop offset="1" class="rzbfz4btw"/></radialGradient><radialGradient id="ibPujte" cx="0" cy="0" r="1" gradientTransform="matrix(-.96093 -.6172 .84322 -1.31284 7.677 9.129)" gradientUnits="userSpaceOnUse"><stop offset=".501" class="rz-l4sb2t"/><stop offset="1" class="nqxo4gbph"/></radialGradient><radialGradient id="i6qz0xW" cx="0" cy="0" r="1" gradientTransform="matrix(.75 -.5625 1.05375 1.405 22.02 9.035)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="euqyawb2g"/><stop offset="1" class="vkwv3acem"/></radialGradient><radialGradient id="iutMDkb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.27624 -.62648 0 14.961 21.755)" gradientUnits="userSpaceOnUse"><stop class="krttc8bap"/><stop offset="1" class="kpneurz6b"/></radialGradient><radialGradient id="ih18itd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.41436 1.45816 0 14.582 25.827)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="ko6eamtic"/><stop offset="1" class="tc4y5tbfa"/></radialGradient><radialGradient id="iKGw4kt" cx="0" cy="0" r="1" gradientTransform="rotate(167.143 8.463 3.484)scale(2.97716 4.69784)" gradientUnits="userSpaceOnUse"><stop class="ism0j8_fd"/><stop offset="1" class="cc4vnjblc"/></radialGradient><radialGradient id="iyoBo3i" cx="0" cy="0" r="1" gradientTransform="matrix(2.81253 -2.28745 2.84526 3.49839 11.927 7.285)" gradientUnits="userSpaceOnUse"><stop class="kx5tbm42q"/><stop offset="1" class="ndetd3gmc"/></radialGradient><radialGradient id="iQy6vPz" cx="0" cy="0" r="1" gradientTransform="rotate(100.623 .526 19.636)scale(1.16051 4.42408)" gradientUnits="userSpaceOnUse"><stop class="pfbpewb0p"/><stop offset="1" class="dutea5bgy"/></radialGradient><radialGradient id="iqw3Vdd" cx="0" cy="0" r="1" gradientTransform="matrix(-.83594 .34375 -.14238 -.34624 23.107 16.395)" gradientUnits="userSpaceOnUse"><stop class="xdf0lfbrm"/><stop offset="1" class="cvnvm48dp"/></radialGradient><radialGradient id="iZmNjZb" cx="0" cy="0" r="1" gradientTransform="matrix(.83594 .17968 -.05863 .27278 21.786 16.332)" gradientUnits="userSpaceOnUse"><stop class="leotspfhb"/><stop offset="1" class="u3sz7tboa"/></radialGradient><radialGradient id="ifSfzbe" cx="0" cy="0" r="1" gradientTransform="matrix(1.3287 1.76599 -.65664 .49404 19.852 16.946)" gradientUnits="userSpaceOnUse"><stop class="qu53-3efb"/><stop offset="1" class="d8vnolbdv"/></radialGradient><radialGradient id="ih6dC9c" cx="0" cy="0" r="1" gradientTransform="matrix(1.46875 .4375 -1.25756 4.22181 18.833 19.379)" gradientUnits="userSpaceOnUse"><stop class="fcewfubec"/><stop offset="1" class="ku_tac4_z"/></radialGradient><radialGradient id="ibijqYb" cx="0" cy="0" r="1" gradientTransform="rotate(135.9 10.028 15.777)scale(4.22106 5.23602)" gradientUnits="userSpaceOnUse"><stop class="ybzdb35ne"/><stop offset="1" class="k-xo7erne"/></radialGradient><radialGradient id="iDqb5ve" cx="0" cy="0" r="1" gradientTransform="matrix(-4 -.68747 1.04434 -6.0764 28.646 22.503)" gradientUnits="userSpaceOnUse"><stop offset=".711" class="d7eq7sb9j"/><stop offset="1" class="pci0oxh-l"/></radialGradient><radialGradient id="iJhoPse" cx="0" cy="0" r="1" gradientTransform="rotate(156.903 12.063 12.55)scale(1.15509 2.08846)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="a6yl-cb9v"/><stop offset="1" class="w_w8qcl3c"/></radialGradient><radialGradient id="iYgYbde" cx="0" cy="0" r="1" gradientTransform="matrix(1.27004 2.2186 -1.58976 .91006 11.157 16.066)" gradientUnits="userSpaceOnUse"><stop class="hq-8cac3q"/><stop offset="1" class="kiftlkrmt"/></radialGradient><radialGradient id="iuLQ4mb" cx="0" cy="0" r="1" gradientTransform="matrix(2.31645 1.18733 -.41625 .81209 12.19 16.066)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><radialGradient id="icL13gd" cx="0" cy="0" r="1" gradientTransform="rotate(136.408 5.786 11.704)scale(4.35086 4.82952)" gradientUnits="userSpaceOnUse"><stop class="dxbo1t_fa"/><stop offset="1" class="kvhp_ip6r"/></radialGradient><radialGradient id="i0XH97d" cx="0" cy="0" r="1" gradientTransform="matrix(4.45572 0 0 1.56463 13.974 15.652)" gradientUnits="userSpaceOnUse"><stop offset=".296" class="zj8ulgbnv"/><stop offset="1" class="j5-d0iboi"/></radialGradient><filter id="ioRL4cb" width="17.197" height="11.9" x="5.988" y="7.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.137255 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2614"/></filter><filter id="inEg4qd" width="3.218" height="3.468" x="17.802" y="9.139" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2614"/></filter><filter id="i8175gd" width="3.148" height="3.148" x="17.837" y="9.424" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2614" stdDeviation=".25"/></filter><filter id="ioA6zMc" width="2.648" height="2.648" x="8.593" y="9.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2614" stdDeviation=".125"/></filter><filter id="iHwfK7a" width="10.221" height="11.127" x="9.488" y="6.091" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2614"/></filter><filter id="ieIIv5b" width="2.877" height="3.682" x="12.982" y="9.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2614" stdDeviation=".25"/></filter><filter id="iUdNmoh" width="2.377" height="3.182" x="13.395" y="9.869" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2614" stdDeviation=".125"/></filter><filter id="ihF5kic" width="3.702" height="1.526" x="12.732" y="13.346" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2614" stdDeviation=".05"/></filter><filter id="imvhurJ" width="3.001" height="1.285" x="15.525" y="9.354" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2614"/></filter><filter id="iZwzX4d" width="3.001" height="1.285" x="10.64" y="9.354" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2614"/></filter><filter id="iXmNBpe" width="2.253" height=".991" x="10.764" y="7.922" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.152941 0 0 0 0 0.0666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2614"/></filter><filter id="iunDHuc" width="2.253" height=".991" x="16.181" y="7.922" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.152941 0 0 0 0 0.0666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2614"/></filter><filter id="iERRPUc" width=".787" height=".696" x="16.031" y="9.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2614" stdDeviation=".05"/></filter><filter id="iOCFI3d" width=".891" height=".913" x="16.871" y="9.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2614" stdDeviation=".1"/></filter><filter id="iC2TbAb" width=".986" height="1.04" x="12.428" y="9.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2614" stdDeviation=".1"/></filter><filter id="i27XHfx" width=".913" height=".704" x="11.674" y="9.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2614" stdDeviation=".05"/></filter><filter id="ie3B7Zc" width="5.52" height="4.05" x="11.827" y="3.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.415686 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2614"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.2 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2614" result="effect2_innerShadow_4002_2614"/></filter><filter id="iPb19sd" width="6.94" height="14.221" x="16.577" y="15.752" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.270588 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2614"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.266667 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2614" result="effect2_innerShadow_4002_2614"/></filter><filter id="idp3bHz" width="11.012" height="8.855" x="17.86" y="16.47" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.0980392 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2614"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.270588 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2614" result="effect2_innerShadow_4002_2614"/></filter><filter id="igK0aXb" width="4.557" height="7.476" x="23.816" y="17.698" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.760784 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2614"/></filter><filter id="ioc3RQc" width="2.509" height="3.213" x="13.154" y="3.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.141176 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_2614"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_2614" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.768627 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_2614"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.337255 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_2614" result="effect3_innerShadow_4002_2614"/></filter><filter id="iiuiWFe" width="1.83" height="4.718" x="18.091" y="17.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2614" stdDeviation=".125"/></filter><filter id="iT6L4eb" width="2.769" height="7.081" x="18.396" y="23.072" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2614" stdDeviation=".2"/></filter><filter id="iwMUkLe" width="6.88" height="4.067" x="11.157" y="15.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.0470588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2614"/></filter><filter id="ixto1mb" width="4.97" height="4.254" x="13.277" y="15.388" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.12549 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2614"/></filter><linearGradient id="iaUsmrb" x1="14.587" x2="14.587" y1="7.972" y2="19.472" gradientUnits="userSpaceOnUse"><stop class="usw0jac_r"/><stop offset="1" class="zhmn0cciw"/></linearGradient><linearGradient id="i1ptMxc" x1="14.587" x2="14.587" y1="7.249" y2="10.843" gradientUnits="userSpaceOnUse"><stop offset=".184" class="l1qje4b6x"/><stop offset="1" class="vx6m-x__v"/></linearGradient><linearGradient id="i0ofdFb" x1="17.194" x2="14.319" y1="7.843" y2="19.781" gradientUnits="userSpaceOnUse"><stop class="udu4bzufn"/><stop offset="1" class="gj1bl9kfl"/></linearGradient><linearGradient id="ih3vBxb" x1="7.607" x2="6.489" y1="26.66" y2="26.629" gradientUnits="userSpaceOnUse"><stop class="gyzg0db3w"/><stop offset="1" class="y28tkbl-n"/></linearGradient><linearGradient id="i0i1YkC" x1="7.407" x2="21.783" y1="15.862" y2="15.862" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iI325ic" x1="7.407" x2="21.783" y1="15.832" y2="15.832" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iJe4SFj" x1="9.002" x2="9.757" y1="9.59" y2="12.607" gradientUnits="userSpaceOnUse"><stop offset=".005" class="wcmxn-bgl"/><stop offset=".643" class="ft_s_k_3c"/></linearGradient><linearGradient id="iZUS8zn" x1="13.537" x2="14.391" y1="12.039" y2="12.143" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="iEZgiod" x1="14.583" x2="14.583" y1="12.893" y2="12.283" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="ibDvXxd" x1="13.854" x2="14.307" y1="14.605" y2="13.733" gradientUnits="userSpaceOnUse"><stop class="b1eb00egl"/><stop offset="1" class="t5ewf8b-q"/></linearGradient><linearGradient id="i9TrwHc" x1="17.543" x2="17.23" y1="10.216" y2="10.409" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iLFL9Cb" x1="13.145" x2="12.831" y1="10.216" y2="10.409" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ilxTFMd" x1="10.646" x2="16.989" y1="6.723" y2="6.723" gradientUnits="userSpaceOnUse"><stop class="ks1omcbjp"/><stop offset="1" class="jk0lbnbnn"/></linearGradient><linearGradient id="iiH6veK" x1="14.592" x2="14.592" y1="30.316" y2="28.723" gradientUnits="userSpaceOnUse"><stop class="s2qawgbpe"/><stop offset="1" class="iu5oamiyf"/></linearGradient><linearGradient id="iI4mEsd" x1="14.592" x2="14.592" y1="26.173" y2="27.441" gradientUnits="userSpaceOnUse"><stop class="tcape2laf"/><stop offset="1" class="gd-vr7bgk"/></linearGradient><linearGradient id="i1i1Lbq" x1="14.582" x2="14.582" y1="6.972" y2="11.754" gradientUnits="userSpaceOnUse"><stop offset=".526" class="ffurleovf"/><stop offset=".654" class="oirct-bua"/></linearGradient><linearGradient id="iMEPogb" x1="14.582" x2="14.582" y1="19.605" y2="26.175" gradientUnits="userSpaceOnUse"><stop class="jbzirjbuq"/><stop offset="1" class="s7s75dkrn"/></linearGradient><linearGradient id="iatOxCb" x1="22.021" x2="18.333" y1="16.754" y2="29.973" gradientUnits="userSpaceOnUse"><stop class="ommdktbpj"/><stop offset="1" class="dinvdlb3p"/></linearGradient><linearGradient id="i5b1ojc" x1="20.021" x2="28.208" y1="22.191" y2="18.879" gradientUnits="userSpaceOnUse"><stop class="lf_6el-zz"/><stop offset="1" class="p6qk4rbue"/></linearGradient><linearGradient id="i9kTuLc" x1="14.458" x2="14.458" y1="4.221" y2="6.666" gradientUnits="userSpaceOnUse"><stop class="rx-q5b7rc"/><stop offset="1" class="fz8-ywb6c"/></linearGradient><linearGradient id="iJ67e8c" x1="18.689" x2="20.192" y1="21.647" y2="16.457" gradientUnits="userSpaceOnUse"><stop class="ih4zzfygk"/><stop offset="1" class="bq_18tbdo"/></linearGradient><linearGradient id="iHtsopb" x1="13.277" x2="13.484" y1="17.919" y2="17.919" gradientUnits="userSpaceOnUse"><stop class="lwl8ufbrj"/><stop offset="1" class="i5hn1bqvd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-firefighter-medium-light" /></template>
<style>
.a6yl-cb9v {
  stop-color: var(--svg-color--eeecf0, #EEECF0);
}

.akbxqtdqb {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.974 9.413c.653 0 1.205.45 1.355 1.06a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.272a1.4 1.4 0 0 1 1.371-1.128");
}

.aso-vybjw {
  stop-color: var(--svg-color--d59566, #D59566);
}

.av1bb6bnt {
  stop-color: var(--svg-color--db8960, #DB8960);
  stop-opacity: 0;
}

.b_qv5du4s {
  fill: var(--svg-color--dc375e, #DC375E);
  d: path("M14.587 15.472c-6.07 0-11 4.92-11 11v3.5h21.99v-3.5c0-6.08-4.92-11-10.99-11");
}

.b1eb00egl {
  stop-color: var(--svg-color--ce9591, #CE9591);
}

.bcdc9wb8u {
  stop-color: var(--svg-color--d54161, #D54161);
  stop-opacity: 0;
}

.bd3jihbsh {
  stop-color: var(--svg-color--ae815d, #AE815D);
  stop-opacity: 0;
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.bkko43bzn {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M13.442 10.19c-.266-.467-.67-.836-1.538-.836c-.38 0-.747.106-1.073.369c-.268.217-.232.495-.024.6l.556.317c.652-.211 1.372-.24 2.079-.45");
}

.bq_18tbdo {
  stop-color: var(--svg-color--cd517b, #CD517B);
  stop-opacity: 0;
}

.c-90s0tkg {
  stop-color: var(--svg-color--704b3f, #704B3F);
}

.c46klzb_q {
  fill: var(--svg-color--000, #000);
  d: path("M16.256 10.577c0-.284.227-.51.511-.51a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.236");
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

.cehcmrgdp {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m14.19 10.54l-.683 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.377-.494-.377-.613 0");
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

.cpiqqqbun {
  d: path("m11.174 8.772l-.004.002a.268.268 0 0 1-.276-.46h.002l.002-.002l.01-.006a2 2 0 0 1 .148-.077a3 3 0 0 1 .41-.161c.34-.109.816-.2 1.329-.11a.268.268 0 1 1-.094.529a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.433.18z");
}

.crdl31bat {
  stop-color: var(--svg-color--eaba8d, #EABA8D);
  stop-opacity: 0;
}

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.cv6gnzbto {
  stop-color: var(--svg-color--fec852, #FEC852);
}

.cvnvm48dp {
  stop-color: var(--svg-color--a17d74, #A17D74);
  stop-opacity: 0;
}

.cw1qesbgk {
  stop-color: var(--svg-color--ffe3b1, #FFE3B1);
}

.d_-1b_bzw {
  d: path("M7.607 29.972V17.971a10.98 10.98 0 0 0-4.02 8.501v3.5z");
}

.d-ykpkboz {
  stop-color: var(--svg-color--c6284c, #C6284C);
}

.d34xtabjk {
  stop-color: var(--svg-color--733d2a, #733D2A);
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

.dbj0sjb-p {
  d: path("M14.947 15.833c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
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

.dutea5bgy {
  stop-color: var(--svg-color--734145, #734145);
  stop-opacity: 0;
}

.dvyniwihb {
  stop-color: var(--svg-color--c57f82, #C57F82);
}

.dxbo1t_fa {
  stop-color: var(--svg-color--ff547f, #FF547F);
}

.dy0k4hb5y {
  stop-color: var(--svg-color--bc8357, #BC8357);
}

.e0_2kpbjh {
  d: path("M13.304 4.91c0-.154.183-.232.293-.126l.155.149a.162.162 0 0 0 .274-.117v-.17c0-.345.178-.665.472-.847l.18-.111a.23.23 0 0 1 .35.195v1.194a.17.17 0 0 0 .278.132l.096-.078a.13.13 0 0 1 .21.1v.333a1.154 1.154 0 0 1-2.308-.052z");
}

.e3fuicbbj {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M19.41 12.072a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.e460wb-gs {
  d: path("m20.012 16.732l4.416 1.16a3.57 3.57 0 0 0 2.071-.053l.148-.055c.178-.062.401-.053.554.108c1.072 1.125 1.43 2.62.984 4.235c-.447 1.615-1.733 2.765-2.98 3.034c-.084.02-.348.046-.506-.158l-.141-.14a3.5 3.5 0 0 0-1.745-1.11L18.57 22.55a.61.61 0 0 1-.43-.779l1.25-4.675c.045-.22.37-.43.622-.364");
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.eeu386bau {
  cx: 12.13px;
  cy: 10.066px;
  rx: 0.39px;
  ry: 0.197px;
}

.eg6wwebxo {
  d: path("M11.157 15.678v1.974c0 1.09.89 1.98 1.98 1.98h2.92c1.09 0 1.98-.88 1.98-1.98v-1.986c-.896.82-2.111 1.29-3.447 1.29c-1.329 0-2.538-.465-3.433-1.278");
}

.ehnthvqoy {
  stop-color: var(--svg-color--b3576b, #B3576B);
}

.epk82vsff {
  stop-color: var(--svg-color--bc8357, #BC8357);
  stop-opacity: 0;
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.eqb1ki6td {
  stop-color: var(--svg-color--d0465e, #D0465E);
  stop-opacity: 0;
}

.euqyawb2g {
  stop-color: var(--svg-color--be1e3b, #BE1E3B);
}

.f2mvkvbzb {
  stop-color: var(--svg-color--775146, #775146);
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

.ffurleovf {
  stop-color: var(--svg-color--bb2b57, #BB2B57);
}

.fk7yhmb2b {
  stop-color: var(--svg-color--cd9380, #CD9380);
  stop-opacity: 0;
}

.fpbtup0si {
  d: path("m14.2 10.402l-.53 1.7a.54.54 0 0 0 .52.7h.786a.54.54 0 0 0 .521-.7l-.531-1.7c-.114-.377-.646-.377-.765 0");
}

.ft_s_k_3c {
  stop-color: var(--svg-color--be7a6e, #BE7A6E);
}

.ft5dv1b6b {
  fill: none;
}

.fw2o80b7i {
  d: path("M8.659 7.972h11.847c.948 0 1.988.485 1.988 2.68h.692V9.347c0-1.43-.848-2.375-2.457-2.375H8.435c-1.609 0-2.456.946-2.456 2.375v1.305h.69c0-2.195 1.04-2.68 1.99-2.68");
}

.fz8-ywb6c {
  stop-color: var(--svg-color--f48942, #F48942);
}

.g1fw3-bff {
  stop-color: var(--svg-color--f4c099, #F4C099);
  stop-opacity: 0;
}

.gd-vr7bgk {
  stop-color: var(--svg-color--edb63d, #EDB63D);
  stop-opacity: 0;
}

.ghwogkbly {
  d: path("M25.649 18.01q.435-.032.85-.171l.148-.055c.178-.062.401-.053.554.108c1.072 1.125 1.43 2.62.984 4.235c-.447 1.615-1.733 2.764-2.98 3.034c-.084.02-.348.045-.506-.158l-.141-.14a3.5 3.5 0 0 0-.642-.588c1.567-.052 2.817-1.084 3.203-2.53c.39-1.468-.236-3.002-1.472-3.735z");
}

.gj1bl9kfl {
  stop-color: var(--svg-color--e7946c, #E7946C);
}

.gsj9ur0da {
  fill: var(--svg-color--da9f84, #DA9F84);
  d: path("m14.2 10.402l-.53 1.7a.54.54 0 0 0 .52.7h.786a.54.54 0 0 0 .521-.7l-.531-1.7c-.114-.377-.646-.377-.765 0");
}

.gvh2bspmv {
  stop-color: var(--svg-color--d39b88, #D39B88);
}

.gxm-dc6uw {
  stop-color: var(--svg-color--a46e69, #A46E69);
}

.gyzg0db3w {
  stop-color: var(--svg-color--bf415a, #BF415A);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h9dvmcbxu {
  stop-color: var(--svg-color--c52632, #C52632);
  stop-opacity: 0;
}

.hgn0v4h0b {
  d: path("M20.885 7.333H8.29v-.378c0-2.734 2.01-4.927 5.02-4.927h2.411c3.329 0 5.165 2.193 5.165 4.927z");
}

.hq-8cac3q {
  stop-color: var(--svg-color--c75567, #C75567);
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.i5hn1bqvd {
  stop-color: var(--svg-color--ca435d, #CA435D);
  stop-opacity: 0;
}

.i7oravbrz {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.583 13.91a3 3 0 0 1-1.421-.345c-.14-.073-.292.088-.203.22a1.932 1.932 0 0 0 3.249 0c.089-.137-.062-.293-.203-.22c-.411.22-.896.345-1.422.345Z");
}

.idk0shbpn {
  stop-color: var(--svg-color--c03959, #C03959);
  stop-opacity: 0;
}

.ih4zzfygk {
  stop-color: var(--svg-color--cd517b, #CD517B);
}

.ii4xdxbjp {
  stop-color: var(--svg-color--865032, #865032);
}

.in1yifh9k {
  cx: 12.13px;
  cy: 10.066px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.ism0j8_fd {
  stop-color: var(--svg-color--675b70, #675B70);
}

.iu5oamiyf {
  stop-color: var(--svg-color--d9a73c, #D9A73C);
  stop-opacity: 0;
}

.iyfczmh7s {
  stop-color: var(--svg-color--fd5c7c, #FD5C7C);
}

.j5-d0iboi {
  stop-color: var(--svg-color--c71931, #C71931);
  stop-opacity: 0;
}

.j7eo66bps {
  stop-color: var(--svg-color--b77557, #B77557);
  stop-opacity: 0;
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.ja-6i29rv {
  d: path("M14.617 15.833h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.jbzirjbuq {
  stop-color: var(--svg-color--ba2f50, #BA2F50);
}

.jk0lbnbnn {
  stop-color: var(--svg-color--be324c, #BE324C);
  stop-opacity: 0;
}

.jnxif700h {
  stop-color: var(--svg-color--ae815d, #AE815D);
}

.k-xo7erne {
  stop-color: var(--svg-color--cdc6d4, #CDC6D4);
}

.k28383b4e {
  stop-color: var(--svg-color--bb8a5f, #BB8A5F);
  stop-opacity: 0;
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

.ko6eamtic {
  stop-color: var(--svg-color--ab0d36, #AB0D36);
  stop-opacity: 0;
}

.kpneurz6b {
  stop-color: var(--svg-color--c1415c, #C1415C);
  stop-opacity: 0;
}

.kqfxh5bnm {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
  stop-opacity: 0;
}

.krttc8bap {
  stop-color: var(--svg-color--c1415c, #C1415C);
}

.krvd34mtu {
  stop-color: var(--svg-color--d59566, #D59566);
  stop-opacity: 0;
}

.ks1omcbjp {
  stop-color: var(--svg-color--be324c, #BE324C);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
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

.l-wvb_5cy {
  stop-color: var(--svg-color--b77557, #B77557);
}

.l1qje4b6x {
  stop-color: var(--svg-color--710425, #710425);
}

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.lcpiqzbvu {
  d: path("M13.277 16.798v1.834c0 .56.45 1.01 1.01 1.01h1.78c1.09 0 1.98-.89 1.98-1.98v-2.024c-.898.826-2.116 1.318-3.457 1.318q-.683-.001-1.313-.158");
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

.ls7-cblkb {
  stop-color: var(--svg-color--dd365e, #DD365E);
}

.ltf10zbnq {
  stop-color: var(--svg-color--ba8d6b, #BA8D6B);
  stop-opacity: 0;
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.lwl8ufbrj {
  stop-color: var(--svg-color--ca435d, #CA435D);
}

.m__mqhxkh {
  stop-color: var(--svg-color--cd9380, #CD9380);
}

.m2b3l_8kx {
  stop-color: var(--svg-color--fd5c7c, #FD5C7C);
  stop-opacity: 0;
}

.mb3jp1v8b {
  d: path("M9.917 12.072a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.mih5kfbap {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
}

.mr-s-pbar {
  stop-color: var(--svg-color--bc832d, #BC832D);
  stop-opacity: 0;
}

.mr8fywmtc {
  stop-color: var(--svg-color--b91a3e, #B91A3E);
}

.mt3h7fbpd {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
}

.n3iibdccw {
  fill: var(--svg-color--d53260, #D53260);
  d: path("M11.157 15.678v1.974c0 1.09.89 1.98 1.98 1.98h2.92c1.09 0 1.98-.88 1.98-1.98v-1.986c-.896.82-2.111 1.29-3.447 1.29c-1.329 0-2.538-.465-3.433-1.278");
}

.n4fn3obqp {
  stop-color: var(--svg-color--c52632, #C52632);
}

.n4s-q-b8n {
  d: path("m22.636 16.137l-1.38-.368a.51.51 0 0 0-.625.358l-3.804 13.846h2.547l3.63-13.212a.53.53 0 0 0-.368-.624");
}

.n4wu3h9rb {
  d: path("M9.898 12.607a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.nazz0ebnc {
  stop-color: var(--svg-color--f7bd9b, #F7BD9B);
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

.nqxo4gbph {
  stop-color: var(--svg-color--a21e3e, #A21E3E);
  stop-opacity: 0;
}

.nuif9xlfl {
  stop-color: var(--svg-color--ff385e, #FF385E);
}

.nzwwulvqt {
  d: path("M16.767 9.685a.893.893 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.128");
}

.o1z42mbzo {
  d: path("M19.41 12.607a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.o41nkwbqu {
  stop-color: var(--svg-color--ff385e, #FF385E);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ogeiazbnd {
  d: path("M19.41 12.072a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
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

.oul1uklww {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.192 9.413c-.653 0-1.204.45-1.355 1.06c-.044.173.09.34.268.34h2.231a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.37-1.128");
}

.p6m80wacn {
  d: path("M17.562 10.46a.84.84 0 0 0-.231-.463l-.26.286l.117.228z");
}

.p6qk4rbue {
  stop-color: var(--svg-color--fc3d5f, #FC3D5F);
}

.pa9r43ilj {
  stop-color: var(--svg-color--b06c65, #B06C65);
  stop-opacity: 0;
}

.pci0oxh-l {
  stop-color: var(--svg-color--a39ba9, #A39BA9);
}

.pfbpewb0p {
  stop-color: var(--svg-color--734145, #734145);
}

.pgid_yb4z {
  fill: var(--svg-color--000, #000);
  d: path("M12.91 10.577a.51.51 0 0 0-.51-.51a.51.51 0 0 0-.455.746h.904a.5.5 0 0 0 .061-.236");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.px6vm6bxx {
  stop-color: var(--svg-color--b17160, #B17160);
}

.q_n5wkbyq {
  stop-color: var(--svg-color--d93b60, #D93B60);
}

.q-uw1wb3b {
  stop-color: var(--svg-color--c7425f, #C7425F);
}

.qfttj6irk {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M14.583 13.91a3 3 0 0 1-1.421-.345c-.14-.073-.292.088-.203.22a1.932 1.932 0 0 0 3.249 0c.089-.137-.062-.293-.203-.22c-.411.22-.896.345-1.422.345");
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qpiq3sr_w {
  stop-color: var(--svg-color--f5be91, #F5BE91);
  stop-opacity: 0;
}

.qu53-3efb {
  stop-color: var(--svg-color--fc4b93, #FC4B93);
}

.qv2uf3bxt {
  d: path("M17.247 6.973h-5.32v-1.29c0-1.47 1.19-2.66 2.66-2.66s2.66 1.19 2.66 2.66z");
}

.r_igwxbib {
  d: path("M16.702 9.873c.063.086-.07.19-.22.302c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.359s.325-.136.389-.05");
}

.r-jog4w_t {
  stop-color: var(--svg-color--c2847a, #C2847A);
}

.rr357_h_e {
  stop-color: var(--svg-color--bb8a5f, #BB8A5F);
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

.sgt5sn5oc {
  stop-color: var(--svg-color--bd8381, #BD8381);
  stop-opacity: 0;
}

.sl-gsib3f {
  stop-color: var(--svg-color--bc832d, #BC832D);
}

.t5ewf8b-q {
  stop-color: var(--svg-color--ce9591, #CE9591);
  stop-opacity: 0;
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
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

.thgnp9bsd {
  stop-color: var(--svg-color--b57564, #B57564);
}

.tvc8pfc3q {
  d: path("m9.498 9.47l-.01-.306c.02-.949.574-1.316.81-1.439l.051-.02l.051-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .462-.051c.717 1.05 1.917 1.217 3.189 1.217h3.22c.18 0 1.113-.057 1.166 1.187l-.149 3.675c-.123 2.802-2.312 4.684-4.983 4.684c-2.672 0-4.86-1.882-4.984-4.684z");
}

.u_wc6ubhb {
  d: path("M21.577 26.173H7.607v3.8h13.97z");
}

.u-hhbu3-q {
  stop-color: var(--svg-color--ab7751, #AB7751);
}

.u24ulrb-c {
  d: path("M13.215 10.473c0-.289-.235-.481-.298-.54l-.289.28l.178.361z");
}

.u3sz7tboa {
  stop-color: var(--svg-color--8c5e57, #8C5E57);
  stop-opacity: 0;
}

.udu4bzufn {
  stop-color: var(--svg-color--fbc799, #FBC799);
}

.uf-8immry {
  stop-color: var(--svg-color--eaba8d, #EABA8D);
}

.ur-cqp2us {
  stop-color: var(--svg-color--b06c65, #B06C65);
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.usw0jac_r {
  stop-color: var(--svg-color--a9112c, #A9112C);
}

.vj8wpab3w {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.702 9.873c.063.086-.07.19-.22.302c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.359s.325-.136.389-.05");
}

.vkwv3acem {
  stop-color: var(--svg-color--be1e3b, #BE1E3B);
  stop-opacity: 0;
}

.voemc8h9d {
  stop-color: var(--svg-color--d23b59, #D23B59);
}

.vu_hqmbug {
  fill-rule: evenodd;
  d: path("M21.782 12.501c.213-.435.324-.92.324-1.427c0-.467-.096-.906-.269-1.305h.006a3 3 0 0 0-.282-.513l-.002-.003a3.24 3.24 0 0 1-.526-1.771l-.167-.01c0-1.822-1.31-3.3-3.132-3.3a.54.54 0 0 1-.455-.232a3.3 3.3 0 0 0-2.682-1.377a3.3 3.3 0 0 0-2.682 1.377a.56.56 0 0 1-.455.232l-.085.001C9.592 4.22 8.49 5.688 8.49 7.482h-.33a3.24 3.24 0 0 1-.527 1.77l-.002.004a3.3 3.3 0 0 0-.22 3.245c.07.142.07.314 0 .456c-.93 1.953.83 4.167 2.894 4.167h8.582c1.78 0 3.218-1.453 3.218-2.906c0-.506-.122-.836-.324-1.261a.52.52 0 0 1 0-.456M9.934 9.871H9.92l.787 2.313c.124 2.803 1.217 0 3.889 0s3.836 3.12 3.96.317l.997-3.202c-.054-1.245-.817-1.327-.997-1.327h-3.22a3.86 3.86 0 0 1-3.19-1.674a.264.264 0 0 0-.461.051l-.082.194a2.3 2.3 0 0 1-1.241 1.255q-.028.013-.051.02c-.236.123-.378.532-.399 1.481l.01.306z");
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

.wcmxn-bgl {
  stop-color: var(--svg-color--ad6e5e, #AD6E5E);
}

.wcr1klbjh {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
  stop-opacity: 0;
}

.wl84mmb3d {
  stop-color: var(--svg-color--fec852, #FEC852);
  stop-opacity: 0;
}

.wow_zkb9s {
  d: path("M22.174 7.972H7.152c-.395.32-.78 1.337-1.164 1.657v1.343c0 4.69 3.855 8.5 8.599 8.5s8.598-3.81 8.598-8.5V9.63c-.354-.42-.687-1.207-1.011-1.657");
}

.wt7c97xxx {
  stop-color: var(--svg-color--f44f5a, #F44F5A);
}

.x1a5p7bxz {
  stop-color: var(--svg-color--db8960, #DB8960);
}

.x8m9vebtt {
  stop-color: var(--svg-color--df6277, #DF6277);
}

.xdf0lfbrm {
  stop-color: var(--svg-color--a17d74, #A17D74);
}

.xjkdvxqyn {
  stop-color: var(--svg-color--c2847a, #C2847A);
  stop-opacity: 0;
}

.xjp5tobqs {
  d: path("M12.4 9.685a.892.892 0 0 0-.86 1.128h1.723a1 1 0 0 0 .033-.236a.9.9 0 0 0-.897-.892");
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.xr_40cc2f {
  stop-color: var(--svg-color--fc5083, #FC5083);
}

.xywzy8ndz {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M15.725 10.19c.266-.467.67-.836 1.538-.836c.38 0 .747.106 1.073.369c.268.217.232.495.024.6l-.556.317c-.652-.211-1.372-.24-2.079-.45");
}

.y_1578bkp {
  stop-color: var(--svg-color--ab7751, #AB7751);
  stop-opacity: 0;
}

.y28tkbl-n {
  stop-color: var(--svg-color--bf415a, #BF415A);
  stop-opacity: 0;
}

.y811obbkp {
  stop-color: var(--svg-color--b4714f, #B4714F);
}

.ybzdb35ne {
  stop-color: var(--svg-color--ded9e3, #DED9E3);
}

.ygstjnb_e {
  stop-color: var(--svg-color--99344a, #99344A);
}

.yhs2bn2id {
  stop-color: var(--svg-color--f4c099, #F4C099);
}

.yq9vgcc5u {
  stop-color: var(--svg-color--ba8d6b, #BA8D6B);
}

.ys-qt6bso {
  fill-rule: evenodd;
  d: path("m18.303 8.314l-.138.23za.268.268 0 0 1-.275.46l-.005-.002l-.022-.012l-.09-.046a3 3 0 0 0-.343-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 1 1-.093-.528c.513-.091.988 0 1.328.109a3.3 3.3 0 0 1 .558.238l.01.006l.003.001z");
}

.z7finb01k {
  stop-color: var(--svg-color--b4714f, #B4714F);
  stop-opacity: 0;
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

.zraasrypm {
  stop-color: var(--svg-color--f0406f, #F0406F);
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
