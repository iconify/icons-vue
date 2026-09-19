<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iPrEtea)"><path fill="url(#iHL20zb)" clip-rule="evenodd" class="djcb-hbvn"/><path fill="url(#iR8QgQB)" clip-rule="evenodd" class="djcb-hbvn"/><path fill="url(#i9dh5Xc)" clip-rule="evenodd" class="djcb-hbvn"/><path fill="url(#isu1sRH)" clip-rule="evenodd" class="djcb-hbvn"/><path fill="url(#inNvMVb)" clip-rule="evenodd" class="djcb-hbvn"/><path fill="url(#iL0upgb)" clip-rule="evenodd" class="djcb-hbvn"/><path fill="url(#ivCCxNe)" clip-rule="evenodd" class="djcb-hbvn"/><path fill="url(#iKMBOJr)" clip-rule="evenodd" class="djcb-hbvn"/><path fill="url(#i1paSLJ)" clip-rule="evenodd" class="djcb-hbvn"/><path fill="url(#i0P9REd)" clip-rule="evenodd" class="djcb-hbvn"/><path fill="url(#iIyFBQl)" clip-rule="evenodd" class="djcb-hbvn"/></g><g filter="url(#idghNVd)"><path class="snv-j0a8h"/><path fill="url(#iKfFFpr)" class="ny1yt7bte"/></g><path fill="url(#iYE7kIH)" class="r-_s-i5-u"/><path fill="url(#iq7MTlc)" class="r-_s-i5-u"/><path fill="url(#iVAFKzd)" class="yuduhkbqj"/><path fill="url(#iR4dqJe)" class="yuduhkbqj"/><path fill="url(#iSZhhvh)" class="ea2ja2b1t"/><path fill="url(#iZMWN4X)" class="re3nr4uqt"/><path fill="url(#i3YSigY)" class="re3nr4uqt"/><path fill="url(#ium4auc)" class="re3nr4uqt"/><path fill="url(#iDPpHEe)" class="re3nr4uqt"/><path fill="url(#irOJjFe)" class="nhgfpgzvz"/><path fill="url(#iFK4ehe)" class="nhgfpgzvz"/><path fill="url(#iPdWxbb)" class="nhgfpgzvz"/><path fill="url(#iosBV5g)" class="sc-44pt6z"/><path fill="url(#ivMMdUb)" class="sc-44pt6z"/><path fill="url(#iOE8cnb)" class="eofi_c1vp"/><path fill="url(#iSZ3mGd)" class="eofi_c1vp"/><path fill="url(#iGv4e4b)" class="eofi_c1vp"/><g filter="url(#i7spzoc)"><path stroke="url(#iQJVEFe)" class="d7mm9-y3t"/></g><path fill="url(#ir4WJcd)" class="kfpclxljk"/><path fill="url(#ilAizvl)" class="kfpclxljk"/><path fill="url(#iWiQKpc)" class="kfpclxljk"/><path fill="url(#irR8p7b)" class="kfpclxljk"/><path fill="url(#igaMT1d)" class="pc7s4vb5y"/><path fill="url(#in8oiGe)" class="pc7s4vb5y"/><path fill="url(#iNLxA8y)" class="wcrnnd4jc"/><path fill="url(#idyRbLb)" class="wcrnnd4jc"/><path fill="url(#iKjN87D)" class="wcrnnd4jc"/><path fill="url(#inSRzae)" class="wcrnnd4jc"/><g filter="url(#idLDVyN)"><path fill="url(#iF2PaIe)" class="xl1ms8kso"/><path fill="url(#i7CdC8l)" class="xl1ms8kso"/><path fill="url(#ioBYsTd)" class="xl1ms8kso"/></g><path fill="url(#iGgyPQd)" class="jtog1o7zs"/><path fill="url(#ix0qB9c)" class="jtog1o7zs"/><path fill="url(#iHMRVge)" class="jtog1o7zs"/><g filter="url(#iLnCGDe)"><path fill="url(#iLrfofc)" class="piak5gbhn"/></g><g filter="url(#iIFXqne)"><path fill="url(#i9GMbPc)" class="ub38yepez"/><path fill="url(#ix6ux0d)" class="ub38yepez"/><path fill="url(#iPDTwWa)" class="ub38yepez"/><path fill="url(#i79FIpb)" class="ub38yepez"/><path fill="url(#is0sqwc)" class="ub38yepez"/></g><g filter="url(#iUMS0kb)"><path stroke="url(#ir1sfAc)" class="h8pexlirq"/></g><g filter="url(#igHZ5bc)"><path stroke="url(#inCORPd)" class="adcdi2gkj"/></g><g filter="url(#iYfmtPJ)"><path stroke="url(#iiZASEb)" class="r5_wwnbua"/></g><path fill="url(#iF7lxLd)" class="hgq1rqbch"/><path fill="url(#iX9d9ae)" class="rtfknebzn"/><g filter="url(#iG63wsc)"><path fill="url(#i6zyo1H)" class="ppyl6zexo"/></g><g filter="url(#iHB49ae)"><path fill="url(#ih0eF9b)" class="al5vh38vm"/><path fill="url(#i4d3rvc)" class="al5vh38vm"/></g><g filter="url(#ivj0Y1c)"><path class="k9e2sdbos"/><path fill="url(#ic3BxMe)" class="cppimvoqe"/></g><g filter="url(#i1Kg5sd)"><path class="xebb-1bkw"/><path fill="url(#iN0zIab)" class="czib5v_5u"/></g><g filter="url(#iuQ1noc)"><path fill="url(#iH4GPjk)" class="uo2pcyp2i"/><path fill="url(#izyevnb)" class="uo2pcyp2i"/><path fill="url(#ieorBXb)" class="uo2pcyp2i"/><path fill="url(#i0azEoj)" class="uo2pcyp2i"/><path fill="url(#iaNzfke)" class="uo2pcyp2i"/><path fill="url(#iTmC6Ob)" class="uo2pcyp2i"/><path fill="url(#ibEpE7W)" class="uo2pcyp2i"/><path fill="url(#i8D2Hdb)" class="uo2pcyp2i"/></g><path fill="url(#iXhpkjo)" class="uo2pcyp2i"/><path fill="url(#iBih7De)" class="uo2pcyp2i"/><path fill="url(#inE5XWU)" class="uo2pcyp2i"/><g filter="url(#iOknjRb)"><path class="dzeb11auv"/></g><g filter="url(#igxf7xf)"><path class="uo3v1mbpg"/><path fill="url(#i7BvYIb)" class="b51dn8bjc"/><path fill="url(#i40caoc)" class="b51dn8bjc"/><path fill="url(#iLlVtje)" class="b51dn8bjc"/><path fill="url(#ieGKfzZ)" class="b51dn8bjc"/></g><path fill="url(#iOxRAre)" class="b51dn8bjc"/><path fill="url(#i6nxIwb)" class="b51dn8bjc"/><path fill="url(#iz6ohpb)" class="tbza5h01s"/><path fill="url(#ialUTPe)" class="tbza5h01s"/><path stroke="url(#iZp0Gkb)" class="zshlrwcnu"/><g filter="url(#in3p4lb)"><path class="ct4squauu"/></g><g filter="url(#i8CitAb)"><path class="cgk2pcbil"/></g><g filter="url(#idttgMc)"><path class="jwusffuhd"/></g><g filter="url(#iRrRYUl)"><path clip-rule="evenodd" class="x9wt4leow"/></g><path class="vhp19bbtt"/><path fill="url(#iTlRENd)" class="gm2bmhb8g"/><path class="ouj1rxh2n"/><g filter="url(#iw9PoDu)"><path class="ja78n5bxd"/><path fill="url(#irJH6rH)" class="u1gu0_owu"/></g><g filter="url(#iuWYuod)"><path fill="url(#iV7k1jc)" class="lhbcd9a-b"/></g><path class="b6sx-ib_e"/><path fill="url(#ikVxwBc)" class="dtj58qbcg"/><path class="ool15ygio"/><g filter="url(#iEK9SKd)"><path fill="url(#iz2AiFc)" class="jo_fnxxtb"/></g><g filter="url(#iROpCPd)"><ellipse transform="rotate(-27.914 12.463 11.222)" class="t2ncgvb3t"/><ellipse fill="url(#i6Yf0Jb)" transform="rotate(-27.914 12.463 11.222)" class="f5kvmebif"/></g><g filter="url(#iVErKje)"><path class="dtwymc7_s"/></g><g filter="url(#ibzhkoc)"><path class="sss616buf"/></g><g filter="url(#ixrFD6c)"><path class="n1ccf-zwi"/><path fill="url(#iEs6kbd)" class="b66adgb6w"/></g><g filter="url(#ibIzAtA)"><path class="sa1amxacz"/><path fill="url(#ifV5nnc)" class="xmgz7acza"/><path fill="url(#i0KKxxb)" class="xmgz7acza"/></g><g filter="url(#iAzKFPj)"><path stroke="url(#iJfG52Z)" class="cqqfc-bef"/></g><g filter="url(#iaFLJQe)"><path class="sispk3-wg"/></g><defs><radialGradient id="iR8QgQB" cx="0" cy="0" r="1" gradientTransform="matrix(-.61764 4.66662 -5.82956 -.77156 14.665 14.491)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="i9dh5Xc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.95103 1.9902 -2.61496 -3.87742 11.783 14.766)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="isu1sRH" cx="0" cy="0" r="1" gradientTransform="matrix(-1.33821 1.75 -1.34375 -1.02756 10.016 12.158)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="inNvMVb" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 2.412 7.98)scale(2.53345 1.78459)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iL0upgb" cx="0" cy="0" r="1" gradientTransform="matrix(1.40685 2.67644 -3.71532 1.95293 11.371 3.683)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="ivCCxNe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.47538 1.47549 -2.06197 -2.06182 20.945 5.81)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iKMBOJr" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 10.542 7.145)scale(1.96539 4.09868)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="i1paSLJ" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.125 8.637)scale(2.97095 3.78456)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="i0P9REd" cx="0" cy="0" r="1" gradientTransform="matrix(-.92578 -2.71278 2.14566 -.73224 19.818 8.569)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iIyFBQl" cx="0" cy="0" r="1" gradientTransform="rotate(5.988 -101.03 88.559)scale(1.54784 2.50795)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iYE7kIH" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 1 -2.08207 6.50646 3.6 25.896)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="li28y9bsf"/><stop offset="1" class="o1jwunhtj"/></radialGradient><radialGradient id="iVAFKzd" cx="0" cy="0" r="1" gradientTransform="rotate(110.288 4.515 19.65)scale(5.49596 3.74438)" gradientUnits="userSpaceOnUse"><stop class="oe2xm9ikp"/><stop offset="1" class="d6d59o0ou"/></radialGradient><radialGradient id="iDPpHEe" cx="0" cy="0" r="1" gradientTransform="rotate(44.502 -14.63 38.402)scale(2.54126 2.34764)" gradientUnits="userSpaceOnUse"><stop class="apsa9cl1l"/><stop offset="1" class="ji3tmwq8i"/></radialGradient><radialGradient id="iPdWxbb" cx="0" cy="0" r="1" gradientTransform="rotate(127.231 1.504 11.219)scale(5.01003 5.42155)" gradientUnits="userSpaceOnUse"><stop offset=".054" class="mi2y_fs0q"/><stop offset="1" class="l1asq8nfe"/></radialGradient><radialGradient id="iOE8cnb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.19791 -5.21858 0 14.99 21.087)" gradientUnits="userSpaceOnUse"><stop class="f61vgy4jo"/><stop offset="1" class="jmfddwijl"/></radialGradient><radialGradient id="iSZ3mGd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.03341 12.2744 0 14.99 24.488)" gradientUnits="userSpaceOnUse"><stop offset=".689" class="gvngxry3c"/><stop offset="1" class="bc3cihb0h"/></radialGradient><radialGradient id="iQJVEFe" cx="0" cy="0" r="1" gradientTransform="rotate(-134.697 12.249 6.64)scale(2.35978 2.2583)" gradientUnits="userSpaceOnUse"><stop class="dxy_xb2lj"/><stop offset="1" class="vwp8f39qz"/></radialGradient><radialGradient id="ir4WJcd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.44554 -3.83658 0 14.99 17.603)" gradientUnits="userSpaceOnUse"><stop class="wszl1wbzf"/><stop offset=".736" class="zcmw7p3ld"/></radialGradient><radialGradient id="ilAizvl" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.08555 -.86564 0 13.087 17.502)" gradientUnits="userSpaceOnUse"><stop offset=".435" class="kw23nbc5m"/><stop offset="1" class="z8cfpebzk"/></radialGradient><radialGradient id="iWiQKpc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.875 -.46875 0 17.16 17.44)" gradientUnits="userSpaceOnUse"><stop class="p5i_qib6t"/><stop offset="1" class="ml7cjacfa"/></radialGradient><radialGradient id="irR8p7b" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.92907 -4.23791 0 14.99 18.042)" gradientUnits="userSpaceOnUse"><stop offset=".622" class="uem2to-3r"/><stop offset="1" class="hj12bbb7e"/></radialGradient><radialGradient id="igaMT1d" cx="0" cy="0" r="1" gradientTransform="rotate(140.588 10.213 15.964)scale(2.28848 2.24827)" gradientUnits="userSpaceOnUse"><stop offset=".354" class="b5vuh20co"/><stop offset="1" class="hrswh-pmg"/></radialGradient><radialGradient id="in8oiGe" cx="0" cy="0" r="1" gradientTransform="matrix(.84335 -.64209 .3353 .44041 27.978 21.644)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="wyf8ygbxi"/><stop offset="1" class="i6hs9gb9s"/></radialGradient><radialGradient id="idyRbLb" cx="0" cy="0" r="1" gradientTransform="rotate(148.849 11.206 12.207)scale(4.17157)" gradientUnits="userSpaceOnUse"><stop offset=".838" class="wc1l7vbis"/><stop offset="1" class="oa317xagd"/></radialGradient><radialGradient id="iKjN87D" cx="0" cy="0" r="1" gradientTransform="matrix(1.26514 1.24827 -2.90348 2.94272 23.734 15.493)" gradientUnits="userSpaceOnUse"><stop class="ky_indbcd"/><stop offset="1" class="s_ufbeclz"/></radialGradient><radialGradient id="inSRzae" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37479 2.10625 0 26.804 16.85)" gradientUnits="userSpaceOnUse"><stop class="qkb33eb6n"/><stop offset="1" class="q-0s8ibrs"/></radialGradient><radialGradient id="i7CdC8l" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4408 -2.66861 0 27.398 17.242)" gradientUnits="userSpaceOnUse"><stop class="zxhnj4bqq"/><stop offset="1" class="hf-5q38gm"/></radialGradient><radialGradient id="iLrfofc" cx="0" cy="0" r="1" gradientTransform="matrix(-.4998 .66245 -.66245 -.4998 25.873 21.113)" gradientUnits="userSpaceOnUse"><stop class="dg3rcdvoo"/><stop offset="1" class="r0tyikbvd"/></radialGradient><radialGradient id="ix6ux0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8787 -1.6371 0 25.965 23.651)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iPDTwWa" cx="0" cy="0" r="1" gradientTransform="matrix(0 .94192 -1.75486 0 25.965 25.07)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="i79FIpb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .78779 -1.4677 0 25.965 26.44)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="is0sqwc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87616 -2.08784 0 25.965 27.921)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="ih0eF9b" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 38.134 -37.919)scale(2.79862 3.41699)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="i4d3rvc" cx="0" cy="0" r="1" gradientTransform="rotate(29.271 -9.468 43.713)scale(1.54394 .4365)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="ic3BxMe" cx="0" cy="0" r="1" gradientTransform="matrix(1.54551 -.11496 .08987 1.20816 19.47 12.046)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="iN0zIab" cx="0" cy="0" r="1" gradientTransform="rotate(-180 5.132 5.966)scale(1.08087)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="iH4GPjk" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 7.702 7.655)scale(7.33069 9.81201)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="izyevnb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.23171 .98202 -.68387 -1.55413 16.991 12.255)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="ieorBXb" cx="0" cy="0" r="1" gradientTransform="matrix(1.31956 -4.02104 5.10194 1.67428 12.761 18.042)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="i0azEoj" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.38342 -9.22918 0 14.979 10.654)" gradientUnits="userSpaceOnUse"><stop offset=".618" class="fpzu2w87z"/><stop offset="1" class="h1bladxio"/></radialGradient><radialGradient id="iaNzfke" cx="0" cy="0" r="1" gradientTransform="matrix(-7.06857 1.38718 -2.3883 -12.16987 16.827 13.153)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="iTmC6Ob" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17792 1.44563 0 17.33 10.953)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="ibEpE7W" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.34348 1.53971 0 12.849 10.719)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="i8D2Hdb" cx="0" cy="0" r="1" gradientTransform="rotate(105.092 4.908 10.569)scale(3.42085 2.73725)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="iXhpkjo" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3156 0 0 -6.59762 20.19 12.476)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="iBih7De" cx="0" cy="0" r="1" gradientTransform="rotate(-121.569 14.174 3.403)scale(1.55804 1.65556)" gradientUnits="userSpaceOnUse"><stop class="ni-4se4rm"/><stop offset="1" class="wsh5tsbcf"/></radialGradient><radialGradient id="inE5XWU" cx="0" cy="0" r="1" gradientTransform="matrix(1.79129 -1.59935 1.89901 2.12692 10.843 17.246)" gradientUnits="userSpaceOnUse"><stop class="z26rrllgi"/><stop offset="1" class="fs9pa7bci"/></radialGradient><radialGradient id="i7BvYIb" cx="0" cy="0" r="1" gradientTransform="matrix(-.46629 -2.09223 .6448 -.1437 15.777 13.22)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="ieGKfzZ" cx="0" cy="0" r="1" gradientTransform="matrix(-.79779 0 0 -.22304 15.532 13.436)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="i6nxIwb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40355 .9636 -1.1581 -1.68686 15.36 12.827)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="wln98ypvp"/><stop offset="1" class="p13423bzd"/></radialGradient><radialGradient id="iz6ohpb" cx="0" cy="0" r="1" gradientTransform="rotate(159.839 6.592 6.629)scale(6.89096 6.0187)" gradientUnits="userSpaceOnUse"><stop class="pw_9rdbbc"/><stop offset="1" class="w6le0vxed"/><stop offset="1" class="c-bi66bbs"/></radialGradient><radialGradient id="ialUTPe" cx="0" cy="0" r="1" gradientTransform="rotate(131.12 4.972 6.88)scale(.66525 2.54787)" gradientUnits="userSpaceOnUse"><stop offset=".203" class="ri6vfobjz"/><stop offset="1" class="vslufkb1d"/></radialGradient><radialGradient id="iTlRENd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .83046 -1.32093 0 17.208 11.32)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="irJH6rH" cx="0" cy="0" r="1" gradientTransform="matrix(-.23739 -.3059 .42116 -.32683 16.974 11.406)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ikVxwBc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .83046 -1.32094 0 12.74 11.32)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i6Yf0Jb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.906 -.355)scale(.50578 .60796)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iEs6kbd" cx="0" cy="0" r="1" gradientTransform="matrix(1.2918 -2.82043 1.44286 .66085 9.183 9.15)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="ifV5nnc" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 7.264 7.232)scale(4.98786 8.15485)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="i0KKxxb" cx="0" cy="0" r="1" gradientTransform="rotate(98.746 5.794 8.615)scale(1.41591 3.04626)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><linearGradient id="iHL20zb" x1="19.778" x2="12.813" y1="4.815" y2="17.717" gradientUnits="userSpaceOnUse"><stop class="c1nwhtznm"/><stop offset="1" class="ogqxd-bue"/></linearGradient><linearGradient id="iKfFFpr" x1="16.794" x2="15.396" y1="26.418" y2="26.115" gradientUnits="userSpaceOnUse"><stop class="k6k-6oblx"/><stop offset="1" class="l5x5or5jn"/></linearGradient><linearGradient id="iq7MTlc" x1="7.091" x2="5.919" y1="26.217" y2="26.217" gradientUnits="userSpaceOnUse"><stop class="xfetrrneo"/><stop offset="1" class="n0fg5jb7h"/></linearGradient><linearGradient id="iR4dqJe" x1="23.02" x2="23.662" y1="26.302" y2="26.271" gradientUnits="userSpaceOnUse"><stop offset=".478" class="g2cjljmej"/><stop offset="1" class="h5gp5h3ar"/></linearGradient><linearGradient id="iSZhhvh" x1="23.287" x2="21.506" y1="26.334" y2="26.334" gradientUnits="userSpaceOnUse"><stop class="tsgwb3b4a"/><stop offset="1" class="nvk1b4bey"/></linearGradient><linearGradient id="iZMWN4X" x1="22.662" x2="18.287" y1="16.288" y2="28.798" gradientUnits="userSpaceOnUse"><stop class="p3s97ubgt"/><stop offset="1" class="uhr48tggx"/></linearGradient><linearGradient id="i3YSigY" x1="17.378" x2="17.847" y1="23.056" y2="23.142" gradientUnits="userSpaceOnUse"><stop class="n-07uqbej"/><stop offset="1" class="k5vnjbbpd"/></linearGradient><linearGradient id="ium4auc" x1="23.393" x2="22.722" y1="20.642" y2="20.361" gradientUnits="userSpaceOnUse"><stop offset=".258" class="e6ztocy0u"/><stop offset="1" class="tjnac7b5i"/></linearGradient><linearGradient id="irOJjFe" x1="8.847" x2="11.787" y1="16.809" y2="29.178" gradientUnits="userSpaceOnUse"><stop class="yhs78-b2s"/><stop offset="1" class="ou99nli7g"/></linearGradient><linearGradient id="iFK4ehe" x1="13.3" x2="12.753" y1="25.876" y2="25.986" gradientUnits="userSpaceOnUse"><stop class="tyg1xhaog"/><stop offset="1" class="wn22vh-9z"/></linearGradient><linearGradient id="iosBV5g" x1="8.006" x2="10.287" y1="28.146" y2="26.99" gradientUnits="userSpaceOnUse"><stop class="h1snaz72e"/><stop offset="1" class="kvxpklbcz"/></linearGradient><linearGradient id="ivMMdUb" x1="9.769" x2="8.905" y1="26.166" y2="26.68" gradientUnits="userSpaceOnUse"><stop class="a9i5gdgdq"/><stop offset="1" class="qrkl270nd"/></linearGradient><linearGradient id="iGv4e4b" x1="17.752" x2="16.432" y1="22.682" y2="22.523" gradientUnits="userSpaceOnUse"><stop offset=".061" class="k6iyw5bmd"/><stop offset="1" class="vt6827o2o"/></linearGradient><linearGradient id="iNLxA8y" x1="25.631" x2="25.631" y1="15.984" y2="20.04" gradientUnits="userSpaceOnUse"><stop offset=".313" class="wprwrdbxj"/><stop offset=".562" class="ax-d4eb4u"/></linearGradient><linearGradient id="iF2PaIe" x1="25.826" x2="25.684" y1="16.92" y2="18.123" gradientUnits="userSpaceOnUse"><stop offset=".12" class="qcwm1i13v"/><stop offset="1" class="s0eee-boz"/></linearGradient><linearGradient id="ioBYsTd" x1="23.128" x2="23.255" y1="16.857" y2="17.293" gradientUnits="userSpaceOnUse"><stop class="wtu393bab"/><stop offset="1" class="ce_wr9jxr"/></linearGradient><linearGradient id="iGgyPQd" x1="26.828" x2="24.541" y1="21.427" y2="21.427" gradientUnits="userSpaceOnUse"><stop class="j-x55pbxn"/><stop offset="1" class="zg05wl6cw"/></linearGradient><linearGradient id="ix0qB9c" x1="24.358" x2="24.739" y1="21.269" y2="21.241" gradientUnits="userSpaceOnUse"><stop class="fs7-dablt"/><stop offset="1" class="zg97ljbvw"/></linearGradient><linearGradient id="iHMRVge" x1="26.976" x2="26.714" y1="21.141" y2="21.117" gradientUnits="userSpaceOnUse"><stop class="qna0z9q7a"/><stop offset="1" class="toldersuv"/></linearGradient><linearGradient id="i9GMbPc" x1="27.888" x2="23.02" y1="26.674" y2="26.674" gradientUnits="userSpaceOnUse"><stop offset=".146" class="pxu01k21v"/><stop offset=".861" class="mrmriqoyy"/></linearGradient><linearGradient id="ir1sfAc" x1="23.634" x2="25.555" y1="24.471" y2="24.471" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="inCORPd" x1="23.634" x2="25.555" y1="25.913" y2="25.913" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="iiZASEb" x1="23.634" x2="25.555" y1="27.343" y2="27.343" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="iF7lxLd" x1="7.635" x2="22.351" y1="16.855" y2="16.855" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iX9d9ae" x1="7.635" x2="22.35" y1="16.823" y2="16.823" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i6zyo1H" x1="8.583" x2="9.853" y1="12.021" y2="12.021" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="i40caoc" x1="14.013" x2="14.974" y1="13.294" y2="13.294" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="iLlVtje" x1="14.974" x2="14.974" y1="14.112" y2="13.487" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="iOxRAre" x1="15.054" x2="15.054" y1="14.085" y2="13.942" gradientUnits="userSpaceOnUse"><stop class="p13423bzd"/><stop offset="1" class="wln98ypvp"/></linearGradient><linearGradient id="iZp0Gkb" x1="13.885" x2="14.357" y1="15.555" y2="14.826" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="iV7k1jc" x1="18.004" x2="17.683" y1="11.375" y2="11.573" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iz2AiFc" x1="13.502" x2="13.181" y1="11.376" y2="11.573" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iJfG52Z" x1="12.015" x2="12.572" y1="5.587" y2="6.891" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><filter id="iPrEtea" width="15.622" height="16.122" x="7.288" y="2.452" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2316"/></filter><filter id="idghNVd" width="5.513" height="4.74" x="12.74" y="24.048" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.780392 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2316"/></filter><filter id="i7spzoc" width="5.221" height="5.427" x="12.379" y="15.329" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2316" stdDeviation=".1"/></filter><filter id="idLDVyN" width="6.102" height="1.228" x="22.683" y="16.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.47451 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2316"/></filter><filter id="iLnCGDe" width="1.075" height="1.075" x="25.09" y="20.891" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.560784 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2316"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.87451 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2316" result="effect2_innerShadow_4002_2316"/></filter><filter id="iIFXqne" width="5.369" height="6.076" x="23.02" y="22.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.211765 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2316"/></filter><filter id="iUMS0kb" width="2.319" height=".3" x="23.484" y="24.243" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2316" stdDeviation=".05"/></filter><filter id="igHZ5bc" width="2.319" height=".3" x="23.484" y="25.685" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2316" stdDeviation=".05"/></filter><filter id="iYfmtPJ" width="2.319" height=".3" x="23.484" y="27.115" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2316" stdDeviation=".05"/></filter><filter id="iG63wsc" width="3.444" height="3.294" x="8.531" y="10.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2316"/></filter><filter id="iHB49ae" width="3.294" height="3.544" x="18.268" y="10.034" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2316"/></filter><filter id="ivj0Y1c" width="3.199" height="3.199" x="18.316" y="10.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2316" stdDeviation=".25"/></filter><filter id="i1Kg5sd" width="2.699" height="2.699" x="8.848" y="10.582" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2316" stdDeviation=".125"/></filter><filter id="iuQ1noc" width="10.431" height="11.233" x="9.758" y="6.909" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2316"/></filter><filter id="iOknjRb" width="2.922" height="3.745" x="13.347" y="10.915" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2316" stdDeviation=".25"/></filter><filter id="igxf7xf" width="2.422" height="3.245" x="13.763" y="11.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2316" stdDeviation=".125"/></filter><filter id="in3p4lb" width="3.067" height="1.316" x="15.943" y="10.494" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2316"/></filter><filter id="i8CitAb" width="3.067" height="1.316" x="10.938" y="10.494" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2316"/></filter><filter id="idttgMc" width="2.506" height="1.112" x="11.076" y="9.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2316"/></filter><filter id="iRrRYUl" width="2.506" height="1.112" x="16.621" y="9.041" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2316"/></filter><filter id="iw9PoDu" width=".801" height=".708" x="16.459" y="10.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2316" stdDeviation=".05"/></filter><filter id="iuWYuod" width=".903" height=".926" x="17.321" y="10.952" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2316" stdDeviation=".1"/></filter><filter id="iEK9SKd" width="1" height="1.055" x="12.773" y="10.887" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2316" stdDeviation=".1"/></filter><filter id="iROpCPd" width=".93" height=".716" x="11.998" y="10.864" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2316" stdDeviation=".05"/></filter><filter id="iVErKje" width="2.3" height=".987" x="16.659" y="9.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2316" stdDeviation=".1"/></filter><filter id="ibzhkoc" width="2.3" height=".987" x="11.079" y="9.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2316" stdDeviation=".1"/></filter><filter id="ixrFD6c" width="4.392" height="4.701" x="8.479" y="4.835" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.262745 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2316"/><feGaussianBlur result="effect2_foregroundBlur_4002_2316" stdDeviation=".2"/></filter><filter id="ibIzAtA" width="8.961" height="5.907" x="11.736" y="3.671" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2316"/><feGaussianBlur result="effect2_foregroundBlur_4002_2316" stdDeviation=".125"/></filter><filter id="iAzKFPj" width="1.158" height="2.35" x="11.715" y="4.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2316" stdDeviation=".1"/></filter><filter id="iaFLJQe" width="7.043" height="3.916" x="14.146" y="5.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2316" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-singer-medium-dark" /></template>
<style>
.a9i5gdgdq {
  stop-color: var(--svg-color--55447c, #55447C);
}

.adcdi2gkj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.634 25.835h2.02");
}

.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.al5vh38vm {
  d: path("M19.915 13.579a1.647 1.647 0 1 0 0-3.295a1.647 1.647 0 0 0 0 3.294");
}

.apsa9cl1l {
  stop-color: var(--svg-color--7955b5, #7955B5);
}

.ar7lpj8pp {
  stop-color: var(--svg-color--7a4b42, #7A4B42);
  stop-opacity: 0;
}

.ax-d4eb4u {
  stop-color: var(--svg-color--562d79, #562D79);
}

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
}

.b51dn8bjc {
  d: path("m14.583 11.562l-.544 1.74a.552.552 0 0 0 .533.716h.805a.554.554 0 0 0 .532-.716l-.544-1.74c-.116-.386-.66-.386-.782 0");
}

.b5vuh20co {
  stop-color: var(--svg-color--8b655b, #8B655B);
}

.b66adgb6w {
  d: path("M9.785 5.802c.58-.613 1.675-.614 2.182-.523l.405 1.321c-.26-.04-.49.052-.684.24c-.459 1.29-2.036 2.002-2.767 2.196c-.152-1.527.11-2.436.864-3.234");
}

.b6sx-ib_e {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.527 10.554a1.43 1.43 0 0 0-1.387 1.084a.28.28 0 0 0 .274.348h2.284a.236.236 0 0 0 .232-.278a1.434 1.434 0 0 0-1.403-1.154");
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.bc3cihb0h {
  stop-color: var(--svg-color--422522, #422522);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.c-bi66bbs {
  stop-color: var(--svg-color--c93859, #C93859);
}

.c1nwhtznm {
  stop-color: var(--svg-color--45363a, #45363A);
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.ce_wr9jxr {
  stop-color: var(--svg-color--b19a83, #B19A83);
  stop-opacity: 0;
}

.cgk2pcbil {
  fill: var(--svg-color--272528, #272528);
  d: path("M13.805 11.35c-.271-.479-.684-.856-1.573-.856c-.39 0-.765.108-1.098.377c-.276.223-.239.507-.026.614l.57.325c.667-.216 1.404-.245 2.127-.46");
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cppimvoqe {
  d: path("M19.915 13.03a1.1 1.1 0 1 0 0-2.198a1.1 1.1 0 0 0 0 2.199");
}

.cqqfc-bef {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.015 5.235c.024.25.24 1.184.557 1.75");
}

.crj44uotj {
  stop-color: var(--svg-color--996b5e, #996B5E);
}

.ct4squauu {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M16.143 11.35c.272-.479.685-.856 1.574-.856a1.7 1.7 0 0 1 1.098.377c.275.223.238.507.025.614l-.569.325c-.667-.216-1.405-.245-2.128-.46");
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.czib5v_5u {
  d: path("M10.198 13.03a1.1 1.1 0 1 0 0-2.198a1.1 1.1 0 0 0 0 2.199");
}

.d6d59o0ou {
  stop-color: var(--svg-color--4d396f, #4D396F);
}

.d7mm9-y3t {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.704 15.654h4.571v2.8c0 1.262-1.023 1.977-2.285 1.977s-2.286-.715-2.286-1.978z");
}

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
  stop-opacity: 0;
}

.dcb4tlblp {
  stop-color: var(--svg-color--986e66, #986E66);
  stop-opacity: 0;
}

.dg3rcdvoo {
  stop-color: var(--svg-color--d2bfe7, #D2BFE7);
}

.djcb-hbvn {
  fill-rule: evenodd;
  d: path("M22.329 13.375a3.3 3.3 0 0 0 .331-1.461c0-.479-.098-.927-.274-1.336h.005a3.3 3.3 0 0 0-.288-.525l-.002-.004a3.3 3.3 0 0 1-.539-1.812v-.01a3.38 3.38 0 0 0-3.377-3.378a.55.55 0 0 1-.466-.238a3.38 3.38 0 0 0-2.745-1.409c-1.129 0-2.134.56-2.745 1.409a.58.58 0 0 1-.466.238l-.087.001a3.38 3.38 0 0 0-3.29 3.376v.01c0 .643-.187 1.275-.539 1.813l-.002.004a3.38 3.38 0 0 0-.226 3.321a.53.53 0 0 1 0 .467a3.34 3.34 0 0 0-.331 1.44a3.29 3.29 0 0 0 3.294 3.294h8.784a3.29 3.29 0 0 0 3.294-3.294a3.34 3.34 0 0 0-.331-1.44a.53.53 0 0 1 0-.466m-12.55-2.736h-.012l1.227 2.411c.126 2.869 1.246 0 3.98 0s3.927 3.193 4.053.324l1.163-3.272c-.055-1.274-.979-1.364-1.163-1.364h-3.296a3.95 3.95 0 0 1-3.264-1.712a.27.27 0 0 0-.473.052l-.084.198a2.36 2.36 0 0 1-1.27 1.285q-.028.012-.052.02c-.242.126-.808.502-.83 1.473l.011.313z");
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.dtj58qbcg {
  d: path("M12.739 10.832a.914.914 0 0 0-.88 1.154h1.764a1 1 0 0 0 .033-.24a.92.92 0 0 0-.917-.914");
}

.dtwymc7_s {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.96 9.503c.33-.08 1.15-.04 1.7.352");
}

.dxy_xb2lj {
  stop-color: var(--svg-color--7e5c5b, #7E5C5B);
}

.dzeb11auv {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m14.572 11.704l-.7 1.74a.552.552 0 0 0 .533.716h.805a.554.554 0 0 0 .533-.716l-.544-1.74c-.116-.386-.505-.386-.627 0");
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e6ztocy0u {
  stop-color: var(--svg-color--876bc0, #876BC0);
}

.ea2ja2b1t {
  d: path("M23.02 28.788v-7.303l-3.52 7.303z");
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.eofi_c1vp {
  d: path("M15.01 17.688c-1.16 0-2.298.171-3.378.491l1.098 5.869c.72.28 1.5.44 2.32.44c.77 0 1.51-.14 2.19-.38l1.11-5.92c-1.05-.33-2.18-.5-3.34-.5");
}

.f5kvmebif {
  cx: 12.463px;
  cy: 11.222px;
  rx: 0.399px;
  ry: 0.202px;
}

.f61vgy4jo {
  stop-color: var(--svg-color--825b56, #825B56);
}

.fpzu2w87z {
  stop-color: var(--svg-color--7f495f, #7F495F);
  stop-opacity: 0;
}

.fs7-dablt {
  stop-color: var(--svg-color--a0768f, #A0768F);
}

.fs9pa7bci {
  stop-color: var(--svg-color--6e494b, #6E494B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g2cjljmej {
  stop-color: var(--svg-color--604e83, #604E83);
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gcfqr7bfg {
  stop-color: var(--svg-color--714350, #714350);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gm2bmhb8g {
  d: path("M17.21 10.832a.914.914 0 0 1 .88 1.154h-1.765a.917.917 0 0 1 .885-1.154");
}

.gvngxry3c {
  stop-color: var(--svg-color--422522, #422522);
  stop-opacity: 0;
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h1bladxio {
  stop-color: var(--svg-color--753f56, #753F56);
}

.h1snaz72e {
  stop-color: var(--svg-color--665395, #665395);
}

.h5gp5h3ar {
  stop-color: var(--svg-color--604e83, #604E83);
  stop-opacity: 0;
}

.h8pexlirq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.634 24.393h2.02");
}

.hf-5q38gm {
  stop-color: var(--svg-color--c1bcc8, #C1BCC8);
  stop-opacity: 0;
}

.hgq1rqbch {
  d: path("M15.353 16.824c.256.01.522.03.788.051c-.266-.02-.522-.04-.788-.05");
}

.hj12bbb7e {
  stop-color: var(--svg-color--66383f, #66383F);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.hrswh-pmg {
  stop-color: var(--svg-color--673a32, #673A32);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i6hs9gb9s {
  stop-color: var(--svg-color--997c73, #997C73);
  stop-opacity: 0;
}

.j-x55pbxn {
  stop-color: var(--svg-color--d9cbea, #D9CBEA);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.ja78n5bxd {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.143 11.025c.064.087-.072.193-.226.309s-.27.197-.335.11s.008-.251.162-.367c.155-.116.333-.139.398-.052");
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.ji3tmwq8i {
  stop-color: var(--svg-color--7955b5, #7955B5);
  stop-opacity: 0;
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jmfddwijl {
  stop-color: var(--svg-color--563335, #563335);
}

.jo_fnxxtb {
  d: path("M13.573 11.638c0-.295-.24-.492-.305-.551l-.295.285l.182.37z");
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.jtog1o7zs {
  d: path("M25.618 26.628a.784.784 0 0 1-.782-.711l-.67-6.428l2.975.01l-.731 6.428a.8.8 0 0 1-.792.7");
}

.jwusffuhd {
  fill: var(--svg-color--352827, #352827);
  d: path("m11.496 10.112l-.004.002a.275.275 0 0 1-.283-.47h.001l.001-.001l.003-.002l.01-.006a2 2 0 0 1 .152-.078c.1-.049.244-.11.42-.166a2.9 2.9 0 0 1 1.36-.112a.274.274 0 1 1-.096.54c-.408-.071-.8 0-1.098.095a3 3 0 0 0-.466.198");
}

.k5vnjbbpd {
  stop-color: var(--svg-color--845ebf, #845EBF);
  stop-opacity: 0;
}

.k6iyw5bmd {
  stop-color: var(--svg-color--583136, #583136);
}

.k6k-6oblx {
  stop-color: var(--svg-color--c296bf, #C296BF);
}

.k9e2sdbos {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M19.915 13.03a1.1 1.1 0 1 0 0-2.198a1.1 1.1 0 0 0 0 2.199");
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kfpclxljk {
  d: path("M12.704 15.654h4.571v2.8c0 1.262-1.023 1.977-2.285 1.977s-2.286-.715-2.286-1.978z");
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kvxpklbcz {
  stop-color: var(--svg-color--5d4c7d, #5D4C7D);
}

.kw23nbc5m {
  stop-color: var(--svg-color--734a4e, #734A4E);
}

.ky_indbcd {
  stop-color: var(--svg-color--7b5e40, #7B5E40);
}

.l__dw9bpv {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
  stop-opacity: 0;
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l1asq8nfe {
  stop-color: var(--svg-color--815eb7, #815EB7);
  stop-opacity: 0;
}

.l5x5or5jn {
  stop-color: var(--svg-color--e7c1f5, #E7C1F5);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lf8a5e78i {
  stop-color: var(--svg-color--664139, #664139);
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhbcd9a-b {
  d: path("M18.023 11.625a.86.86 0 0 0-.236-.473l-.266.292l.12.233z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.li28y9bsf {
  stop-color: var(--svg-color--675890, #675890);
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mi2y_fs0q {
  stop-color: var(--svg-color--6c3b70, #6C3B70);
}

.ml7cjacfa {
  stop-color: var(--svg-color--70504c, #70504C);
  stop-opacity: 0;
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mrmriqoyy {
  stop-color: var(--svg-color--744950, #744950);
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n-07uqbej {
  stop-color: var(--svg-color--8e5280, #8E5280);
}

.n0fg5jb7h {
  stop-color: var(--svg-color--504665, #504665);
  stop-opacity: 0;
}

.n1ccf-zwi {
  fill: var(--svg-color--2a191e, #2A191E);
  d: path("M9.785 5.802c.58-.613 1.675-.614 2.182-.523l.405 1.321c-.26-.04-.49.052-.684.24c-.459 1.29-2.036 2.002-2.767 2.196c-.152-1.527.11-2.436.864-3.234");
}

.nhgfpgzvz {
  d: path("M5.297 16.81h5.256a1 1 0 0 1 .983.815l2.095 11.173h-2.79l-5.88-11.529c-.086-.125-.07-.46.336-.46");
}

.ni-4se4rm {
  stop-color: var(--svg-color--836462, #836462);
}

.nvk1b4bey {
  stop-color: var(--svg-color--5f4b8a, #5F4B8A);
}

.ny1yt7bte {
  d: path("M12.74 24.048v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.o1jwunhtj {
  stop-color: var(--svg-color--58497e, #58497E);
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.oa317xagd {
  stop-color: var(--svg-color--673d45, #673D45);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oe2xm9ikp {
  stop-color: var(--svg-color--746b8d, #746B8D);
}

.ogqxd-bue {
  stop-color: var(--svg-color--1c151f, #1C151F);
}

.olqyf7fmb {
  stop-color: var(--svg-color--875e5e, #875E5E);
}

.ool15ygio {
  fill: var(--svg-color--000, #000);
  d: path("M13.262 11.746a.52.52 0 0 0-.524-.524a.52.52 0 0 0-.465.764h.926a.5.5 0 0 0 .063-.24");
}

.opgioqbtx {
  stop-color: var(--svg-color--805c54, #805C54);
  stop-opacity: 0;
}

.osxg47drp {
  stop-color: var(--svg-color--743f5a, #743F5A);
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.ou99nli7g {
  stop-color: var(--svg-color--9266df, #9266DF);
}

.ouj1rxh2n {
  fill: var(--svg-color--000, #000);
  d: path("M16.687 11.746c0-.291.232-.524.523-.524a.52.52 0 0 1 .465.764h-.926a.5.5 0 0 1-.062-.24");
}

.p13423bzd {
  stop-color: var(--svg-color--693b40, #693B40);
}

.p3s97ubgt {
  stop-color: var(--svg-color--8866b4, #8866B4);
}

.p5i_qib6t {
  stop-color: var(--svg-color--70504c, #70504C);
}

.p88c31myn {
  stop-color: var(--svg-color--815a5b, #815A5B);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pc7s4vb5y {
  d: path("M27.169 21.112c.59 0 1.07.48 1.07 1.07v2.45h-2.14v-2.45c0-.59.48-1.07 1.07-1.07");
}

.piak5gbhn {
  d: path("M25.628 21.916a.487.487 0 1 0 0-.975a.487.487 0 0 0 0 .975");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppyl6zexo {
  d: path("M10.178 13.579a1.647 1.647 0 1 0 0-3.295a1.647 1.647 0 0 0 0 3.294");
}

.pw_9rdbbc {
  stop-color: var(--svg-color--f32f73, #F32F73);
}

.pxu01k21v {
  stop-color: var(--svg-color--976c5f, #976C5F);
}

.q-0s8ibrs {
  stop-color: var(--svg-color--7d718c, #7D718C);
  stop-opacity: 0;
}

.qcwm1i13v {
  stop-color: var(--svg-color--bfbac7, #BFBAC7);
}

.qkb33eb6n {
  stop-color: var(--svg-color--7d718c, #7D718C);
}

.qna0z9q7a {
  stop-color: var(--svg-color--cbc6d6, #CBC6D6);
}

.qrkl270nd {
  stop-color: var(--svg-color--55447c, #55447C);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r-_s-i5-u {
  d: path("M6.97 28.787v-7.93a11.75 11.75 0 0 0-3.18 5.04l-.03.09c-.29.91-.51 1.85-.66 2.8z");
}

.r0i0_6b9f {
  stop-color: var(--svg-color--947068, #947068);
}

.r0tyikbvd {
  stop-color: var(--svg-color--c0a6d9, #C0A6D9);
}

.r5_wwnbua {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.634 27.265h2.02");
}

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.re3nr4uqt {
  d: path("m24.205 16.801l-4.779.021a1 1 0 0 0-.978.816l-2.096 11.16H19.5l5.325-11.017a.685.685 0 0 0-.62-.98");
}

.ri6vfobjz {
  stop-color: var(--svg-color--860c4f, #860C4F);
}

.rtfknebzn {
  d: path("M15.015 16.824h-.04c.101 0 .194 0 .296.01c-.082-.01-.174-.01-.256-.01");
}

.s_ufbeclz {
  stop-color: var(--svg-color--463358, #463358);
  stop-opacity: 0;
}

.s0eee-boz {
  stop-color: var(--svg-color--aa7bd1, #AA7BD1);
}

.sa1amxacz {
  fill: var(--svg-color--2f1920, #2F1920);
  d: path("M14.357 3.957c-1.16-.256-2.2.9-2.321 1.33c1.077 3.629 3.8 3.43 6.49 3.131c1.61-.179 1.784.555 1.921.91c0-4.026-3.423-4.782-6.061-5.364z");
}

.sc-44pt6z {
  d: path("M6.97 28.788h3.87l-3.87-7.596z");
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sispk3-wg {
  fill: var(--svg-color--47383d, #47383D);
  d: path("m17.437 7.652l-1.459.268a.704.704 0 1 1-.128-1.397h2.396c1.417 0 1.886 1.428 1.944 1.916a3.22 3.22 0 0 0-2.753-.787");
}

.snv-j0a8h {
  fill: var(--svg-color--e7c1f2, #E7C1F2);
  d: path("M12.74 24.048v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.sss616buf {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.079 9.503c-.33-.08-1.151-.04-1.7.352");
}

.t2ncgvb3t {
  cx: 12.463px;
  cy: 11.222px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.399px;
  ry: 0.202px;
}

.t9k87pm2r {
  stop-color: var(--svg-color--875555, #875555);
}

.tbza5h01s {
  d: path("M13.988 8.329a3.9 3.9 0 0 1-1.506-1.303a.27.27 0 0 0-.467.04l-1.905 5.61h1.894l-.522 2.921l3.92-5.504h-2.02z");
}

.tjnac7b5i {
  stop-color: var(--svg-color--8263bd, #8263BD);
  stop-opacity: 0;
}

.toldersuv {
  stop-color: var(--svg-color--d3c3e5, #D3C3E5);
  stop-opacity: 0;
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tsgwb3b4a {
  stop-color: var(--svg-color--7c739f, #7C739F);
}

.tyg1xhaog {
  stop-color: var(--svg-color--6e3c78, #6E3C78);
}

.u1gu0_owu {
  d: path("M17.143 11.025c.064.087-.072.193-.226.309s-.27.197-.335.11s.008-.251.162-.367c.155-.116.333-.139.398-.052");
}

.ub38yepez {
  d: path("M23.02 23.674a.81.81 0 0 1 .816-.802h3.055c.744 0 1.348.589 1.348 1.315v3.514a1.11 1.11 0 0 1-1.124 1.097h-3.279a.81.81 0 0 1-.816-.802a.8.8 0 0 1 .457-.72a.8.8 0 0 1-.457-.721c0-.314.186-.589.457-.72a.8.8 0 0 1-.457-.72a.8.8 0 0 1 .457-.72a.8.8 0 0 1-.457-.72");
}

.uem2to-3r {
  stop-color: var(--svg-color--66383f, #66383F);
  stop-opacity: 0;
}

.uhr48tggx {
  stop-color: var(--svg-color--7f54c6, #7F54C6);
}

.uj7hgsb3u {
  stop-color: var(--svg-color--815a5b, #815A5B);
}

.uo2pcyp2i {
  d: path("M9.767 10.64h.012l-.01-.273l-.01-.313c.02-.971.587-1.347.829-1.472l.052-.021q.028-.013.053-.021c.546-.25.986-.69 1.217-1.264l.084-.198a.27.27 0 0 1 .473-.052a3.95 3.95 0 0 0 3.264 1.712h3.296c.184 0 1.108.09 1.163 1.364l-.122 3.146c-.126 2.868-2.366 4.794-5.1 4.794c-2.735 0-4.975-1.926-5.101-4.795z");
}

.uo3v1mbpg {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m14.583 11.562l-.544 1.74a.552.552 0 0 0 .533.716h.805a.554.554 0 0 0 .532-.716l-.544-1.74c-.116-.386-.66-.386-.782 0");
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.vhp19bbtt {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.422 10.554c.668 0 1.233.46 1.386 1.084a.28.28 0 0 1-.274.348h-2.283a.236.236 0 0 1-.233-.278a1.43 1.43 0 0 1 1.404-1.154");
}

.vslufkb1d {
  stop-color: var(--svg-color--860c4f, #860C4F);
  stop-opacity: 0;
}

.vt6827o2o {
  stop-color: var(--svg-color--725150, #725150);
  stop-opacity: 0;
}

.vwp8f39qz {
  stop-color: var(--svg-color--7e5c5b, #7E5C5B);
  stop-opacity: 0;
}

.w6le0vxed {
  stop-color: var(--svg-color--bc2f50, #BC2F50);
}

.wc1l7vbis {
  stop-color: var(--svg-color--473558, #473558);
  stop-opacity: 0;
}

.wcrnnd4jc {
  d: path("M25.658 19.986a2.498 2.498 0 1 0 0-4.996a2.498 2.498 0 0 0 0 4.996");
}

.wg3eepbwp {
  stop-color: var(--svg-color--805c54, #805C54);
}

.wln98ypvp {
  stop-color: var(--svg-color--693b40, #693B40);
  stop-opacity: 0;
}

.wn22vh-9z {
  stop-color: var(--svg-color--825db9, #825DB9);
  stop-opacity: 0;
}

.wprwrdbxj {
  stop-color: var(--svg-color--453357, #453357);
}

.wrh2b4bbx {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
}

.wsh5tsbcf {
  stop-color: var(--svg-color--836462, #836462);
  stop-opacity: 0;
}

.wszl1wbzf {
  stop-color: var(--svg-color--713c53, #713C53);
}

.wtu393bab {
  stop-color: var(--svg-color--b19a83, #B19A83);
}

.wyf8ygbxi {
  stop-color: var(--svg-color--997c73, #997C73);
}

.x_ik4kbfh {
  stop-color: var(--svg-color--714350, #714350);
}

.x9wt4leow {
  fill: var(--svg-color--352827, #352827);
  fill-rule: evenodd;
  d: path("m18.794 9.644l-.141.235za.275.275 0 0 1-.282.47l-.004-.002a1 1 0 0 0-.116-.06a3 3 0 0 0-.35-.138a2.3 2.3 0 0 0-1.098-.094a.275.275 0 0 1-.095-.54a2.9 2.9 0 0 1 1.36.111a3.4 3.4 0 0 1 .571.244l.01.006z");
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xebb-1bkw {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M10.198 13.03a1.1 1.1 0 1 0 0-2.198a1.1 1.1 0 0 0 0 2.199");
}

.xfetrrneo {
  stop-color: var(--svg-color--504665, #504665);
}

.xl1ms8kso {
  d: path("m28.106 16.828l-4.844-.02a.57.57 0 0 0-.579.579c0 .325.254.578.579.578l4.844.02a.57.57 0 0 0 .578-.578a.585.585 0 0 0-.578-.579");
}

.xmgz7acza {
  d: path("M14.357 3.957c-1.16-.256-2.2.9-2.321 1.33c1.077 3.629 3.8 3.43 6.49 3.131c1.61-.179 1.784.555 1.921.91c0-4.026-3.423-4.782-6.061-5.364z");
}

.yamoh3dov {
  stop-color: var(--svg-color--764e4c, #764E4C);
}

.ycrcotb4u {
  stop-color: var(--svg-color--986f60, #986F60);
  stop-opacity: 0;
}

.yhs78-b2s {
  stop-color: var(--svg-color--7c5aad, #7C5AAD);
}

.yuduhkbqj {
  d: path("M26.91 28.787c-.14-.96-.36-1.91-.65-2.84a11.77 11.77 0 0 0-3.24-5.13v7.97z");
}

.z26rrllgi {
  stop-color: var(--svg-color--6e494b, #6E494B);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.z8cfpebzk {
  stop-color: var(--svg-color--734a4e, #734A4E);
  stop-opacity: 0;
}

.zcmw7p3ld {
  stop-color: var(--svg-color--74464f, #74464F);
}

.zg05wl6cw {
  stop-color: var(--svg-color--a78bc1, #A78BC1);
}

.zg97ljbvw {
  stop-color: var(--svg-color--ad93c6, #AD93C6);
  stop-opacity: 0;
}

.zoq8fuaif {
  stop-color: var(--svg-color--986f60, #986F60);
}

.zshlrwcnu {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.543 14.515c.413.22.906.347 1.431.347c.53 0 1.018-.127 1.432-.347a.21.21 0 0 1 .252.042c.059.063.08.163.021.254m-3.136-.296l3.094.268m-3.094-.268h-.001a.21.21 0 0 0-.252.044a.2.2 0 0 0-.02.252m.273-.296l-.232.268m3.368.028l-.042-.028m.042.028l-.042-.028m.042.028a2.028 2.028 0 0 1-3.41 0m3.368-.028a1.978 1.978 0 0 1-3.326 0m-.042.028l.042-.028m-.042.028l.042-.028");
}

.zxhnj4bqq {
  stop-color: var(--svg-color--eae5f7, #EAE5F7);
}

</style>
