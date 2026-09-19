<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iJR6FMb)"><path fill="url(#i6Z8pHc)" clip-rule="evenodd" class="yu7_obi3v"/><path fill="url(#iX7eZUc)" clip-rule="evenodd" class="yu7_obi3v"/><path fill="url(#iXmdaQb)" clip-rule="evenodd" class="yu7_obi3v"/><path fill="url(#i0nSrle)" clip-rule="evenodd" class="yu7_obi3v"/><path fill="url(#igwIksb)" clip-rule="evenodd" class="yu7_obi3v"/><path fill="url(#iM8WZ1p)" clip-rule="evenodd" class="yu7_obi3v"/><path fill="url(#id9iZsd)" clip-rule="evenodd" class="yu7_obi3v"/><path fill="url(#i1jbPDc)" clip-rule="evenodd" class="yu7_obi3v"/><path fill="url(#i9hLdPe)" clip-rule="evenodd" class="yu7_obi3v"/></g><path fill="url(#iylnvpb)" class="syk9gb6hv"/><path fill="url(#ivi21ub)" class="syk9gb6hv"/><path fill="url(#ihm4w5d)" class="imh8orb1k"/><path fill="url(#iLaz4yd)" class="imh8orb1k"/><path fill="url(#ikBbVZd)" class="imh8orb1k"/><path fill="url(#idBrqQE)" class="gj7ixfb9c"/><path fill="url(#iMSewyS)" class="gj7ixfb9c"/><path fill="url(#iMXI4be)" class="sg1j4mthl"/><path fill="url(#iFXdPQc)" class="sg1j4mthl"/><path fill="url(#iiF2dBb)" class="sg1j4mthl"/><path fill="url(#i6D6ZTc)" class="z9pqso7mp"/><path fill="url(#i2VUaGc)" class="z9pqso7mp"/><path class="knzs36blp"/><path fill="url(#iWyyYSc)" class="fnd6bmb7i"/><path fill="url(#ipxekOb)" class="bxvgrdn8d"/><path fill="url(#iKagqQd)" class="bxvgrdn8d"/><path fill="url(#ic9QKYd)" class="l3uqdwbmc"/><path fill="url(#iNKXo2b)" class="l3uqdwbmc"/><path fill="url(#ijJPsVc)" class="uguyroe_g"/><path fill="url(#iDThGEP)" class="uguyroe_g"/><path fill="url(#ityYhCc)" class="qwrmqwbeg"/><path fill="url(#ispWUNd)" class="qwrmqwbeg"/><path fill="url(#ijE6ptb)" class="qwrmqwbeg"/><g filter="url(#ipjEQGb)"><path fill="url(#ibehgCc)" class="n64pcpbcq"/></g><g filter="url(#iELS3se)"><path fill="url(#ikPAYBd)" class="tg2hgyb7l"/></g><g filter="url(#iGbtL2n)"><path class="dqt_06a7d"/><path fill="url(#ijdGdMe)" class="elhgnqewr"/></g><g filter="url(#i7R2Zed)"><path class="jtdflpb8n"/><path fill="url(#iZYALid)" class="g1821aczo"/></g><g filter="url(#iqUaWSW)"><path fill="url(#ib2qKQb)" class="d4g-zbbev"/><path fill="url(#ipc1cwG)" class="d4g-zbbev"/></g><path fill="url(#iTPoEcd)" class="d4g-zbbev"/><g filter="url(#iObyJWb)"><path class="nf94bbbdk"/></g><g filter="url(#iY369bd)"><path class="msvb4ybbk"/><path fill="url(#io4Ii8b)" class="yd4o9ab3h"/></g><g filter="url(#iHebtFe)"><path fill="url(#ilQiq6b)" class="gmju-3syb"/></g><g filter="url(#iSFSurd)"><path stroke="url(#i4TQ6Qc)" class="vp8k99b3t"/></g><path class="j-l1xfbxd"/><g filter="url(#i2SvaLc)"><path class="l_fectb5m"/></g><g filter="url(#irZ8lhd)"><path class="gm6cubr5k"/></g><path class="ma8s15bfz"/><path fill="url(#icQmM9c)" class="dd-ysdbcy"/><path class="j_fyy6bgf"/><g filter="url(#iGGlYnq)"><path class="shm05pbnp"/><path fill="url(#ijQ2ygV)" class="vtgegwb8d"/></g><g filter="url(#iDuxlpc)"><path fill="url(#iIGMFje)" class="hcz5bq05r"/></g><path class="thxviccqr"/><path fill="url(#iVFFT3d)" class="sb8u_ob9q"/><path class="fqxdxer3q"/><g filter="url(#if86yhe)"><path fill="url(#iaFEZAc)" class="kbbwcocfe"/></g><g filter="url(#imv67Bb)"><ellipse transform="rotate(-27.914 13.242 13.418)" class="gqnfcq7gb"/><ellipse fill="url(#iVz6XMc)" transform="rotate(-27.914 13.242 13.418)" class="drkw4m_di"/></g><path fill="url(#iqJloEe)" class="o-k236b0e"/><path fill="url(#i3kwMJe)" class="o-k236b0e"/><path fill="url(#ix7yNse)" class="o-k236b0e"/><path fill="url(#iboBgJb)" class="o-k236b0e"/><path fill="url(#i1iCHwb)" class="o-k236b0e"/><path fill="url(#iXs217E)" class="o-k236b0e"/><path fill="url(#ia2SCWb)" class="o-k236b0e"/><path fill="url(#irEoioq)" class="o-k236b0e"/><g filter="url(#iv1d2tS)"><path fill="url(#ispODVd)" class="bm7nyqb5j"/><path fill="url(#izJ3uTd)" class="bm7nyqb5j"/><path fill="url(#ipzg10b)" class="bm7nyqb5j"/><path fill="url(#irDBt4j)" class="bm7nyqb5j"/></g><path fill="url(#iJHEdBc)" class="aq7c7ccsd"/><path fill="url(#iCNde1b)" class="aq7c7ccsd"/><path fill="url(#idtJpnd)" class="aq7c7ccsd"/><path fill="url(#iGV0mjd)" class="aq7c7ccsd"/><g filter="url(#ia3nzBd)"><ellipse class="dm49oyb0x"/></g><defs><radialGradient id="iX7eZUc" cx="0" cy="0" r="1" gradientTransform="rotate(69.999 -6.083 16.586)scale(5.88261 3.29512)" gradientUnits="userSpaceOnUse"><stop offset=".138" class="eezsb1bxh"/><stop offset="1" class="nxdi2gb_j"/></radialGradient><radialGradient id="iXmdaQb" cx="0" cy="0" r="1" gradientTransform="rotate(128.016 2.229 8.573)scale(2.64795 1.58886)" gradientUnits="userSpaceOnUse"><stop class="u6kq06bzt"/><stop offset="1" class="yux7yn9ee"/></radialGradient><radialGradient id="i0nSrle" cx="0" cy="0" r="1" gradientTransform="rotate(132.814 2.033 10.132)scale(1.44841 2.72186)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="dljkp6qbr"/><stop offset="1" class="xmk-y9toa"/></radialGradient><radialGradient id="igwIksb" cx="0" cy="0" r="1" gradientTransform="rotate(-119.982 11.496 7.256)scale(1.87604 5.60418)" gradientUnits="userSpaceOnUse"><stop class="g6n7870oj"/><stop offset="1" class="yy757k4tp"/></radialGradient><radialGradient id="iM8WZ1p" cx="0" cy="0" r="1" gradientTransform="matrix(5.78128 8.85396 -14.7297 9.6179 16.8 12.621)" gradientUnits="userSpaceOnUse"><stop offset=".83" class="mnndm4kgz"/><stop offset=".991" class="d9srtldqu"/></radialGradient><radialGradient id="id9iZsd" cx="0" cy="0" r="1" gradientTransform="matrix(2.28593 1.01848 -2.42815 5.44987 19.859 17.98)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="ctoz1_s2k"/><stop offset="1" class="sy1uvdbyp"/></radialGradient><radialGradient id="i1jbPDc" cx="0" cy="0" r="1" gradientTransform="rotate(-112.595 17.813 .259)scale(1.91214 1.80622)" gradientUnits="userSpaceOnUse"><stop class="q21gbz2ll"/><stop offset="1" class="x-ndnlz5c"/></radialGradient><radialGradient id="i9hLdPe" cx="0" cy="0" r="1" gradientTransform="matrix(2.64805 3.25913 -1.4268 1.15928 22.484 11.892)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="iylnvpb" cx="0" cy="0" r="1" gradientTransform="scale(5.6138 7.59375)rotate(90 .06 2.788)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="cr7yd6bcj"/><stop offset="1" class="mv_v0947c"/></radialGradient><radialGradient id="ivi21ub" cx="0" cy="0" r="1" gradientTransform="matrix(-.96875 0 0 -5.28125 18.456 26.277)" gradientUnits="userSpaceOnUse"><stop class="ke__lf9po"/><stop offset="1" class="i5rrmccaf"/></radialGradient><radialGradient id="ihm4w5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.91396 -1.61702 0 13.695 24.67)" gradientUnits="userSpaceOnUse"><stop class="dr2x31jzv"/><stop offset="1" class="omeu62b7c"/></radialGradient><radialGradient id="iLaz4yd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.55816 -.70149 0 13.695 26.337)" gradientUnits="userSpaceOnUse"><stop offset=".35" class="rrfndackx"/><stop offset="1" class="e3j7-mb6u"/></radialGradient><radialGradient id="ikBbVZd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5194 3.01929 -4.9325 -2.48219 14.182 20.142)" gradientUnits="userSpaceOnUse"><stop offset=".343" class="ez-c7ubrp"/><stop offset="1" class="mzrwpxbna"/></radialGradient><radialGradient id="idBrqQE" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.4375 -2.83386 0 20.016 20.371)" gradientUnits="userSpaceOnUse"><stop class="grpyt1-9k"/><stop offset="1" class="p-n74xx1h"/></radialGradient><radialGradient id="iMSewyS" cx="0" cy="0" r="1" gradientTransform="matrix(.88171 0 0 11.0473 18.253 27.49)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="wwty3-ban"/><stop offset="1" class="a41x9tbei"/></radialGradient><radialGradient id="iFXdPQc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.52726 -8.45621 9.64626 -4.02365 12.39 28.99)" gradientUnits="userSpaceOnUse"><stop offset=".684" class="sqvmrgb3n"/><stop offset=".951" class="xnbb4159v"/></radialGradient><radialGradient id="iiF2dBb" cx="0" cy="0" r="1" gradientTransform="matrix(.13057 0 0 9.00654 8.315 30.035)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="jiob30meo"/><stop offset="1" class="v2x6yq-ng"/></radialGradient><radialGradient id="i6D6ZTc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.78322 -2.01004 0 23.633 22.649)" gradientUnits="userSpaceOnUse"><stop offset=".309" class="gt-qelr6u"/><stop offset="1" class="xmtd48u_j"/></radialGradient><radialGradient id="i2VUaGc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.375 -.27856 0 23.633 28.043)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="thq31dj-g"/><stop offset="1" class="qf92jxbjd"/></radialGradient><radialGradient id="iWyyYSc" cx="0" cy="0" r="1" gradientTransform="rotate(-108.091 18.498 10.183)scale(11.6646 18.6686)" gradientUnits="userSpaceOnUse"><stop offset=".566" class="yrdgovb8a"/><stop offset=".971" class="f2js-baog"/></radialGradient><radialGradient id="iKagqQd" cx="0" cy="0" r="1" gradientTransform="matrix(1.79395 -5.21875 8.06034 2.77074 19.214 25.465)" gradientUnits="userSpaceOnUse"><stop offset=".834" class="juo63cbvd"/><stop offset=".998" class="o2jd-jggt"/></radialGradient><radialGradient id="ic9QKYd" cx="0" cy="0" r="1" gradientTransform="matrix(1.87 -7.3125 2.94555 .75325 6.445 28.996)" gradientUnits="userSpaceOnUse"><stop class="ecitxobgm"/><stop offset="1" class="rk8_jsb0a"/></radialGradient><radialGradient id="ijJPsVc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.2124 -8.20544 2.09119 -.30899 25.503 30.035)" gradientUnits="userSpaceOnUse"><stop class="wqe5m4buq"/><stop offset="1" class="zykt_9b7s"/></radialGradient><radialGradient id="iDThGEP" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.32422 .46978 0 23.633 30.035)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="cs69zqbom"/><stop offset="1" class="u77xpkbsk"/></radialGradient><radialGradient id="ityYhCc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.09265 -3.968 0 15.995 20.7)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="evjtz5bic"/><stop offset=".88" class="k_5oi18_f"/></radialGradient><radialGradient id="ispWUNd" cx="0" cy="0" r="1" gradientTransform="rotate(124.286 3.663 15.303)scale(3.10657 1.51707)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="trtw9eqsx"/><stop offset="1" class="n5hwk-_ts"/></radialGradient><radialGradient id="ijE6ptb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.64062 1.5041 -2.68025 -4.70547 16.667 20.406)" gradientUnits="userSpaceOnUse"><stop offset=".706" class="x__bgvnia"/><stop offset="1" class="d_rzkbbzn"/></radialGradient><radialGradient id="ikPAYBd" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 44.24 -40.377)scale(3.06706 3.74474)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="ijdGdMe" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 51.042 -52.248)scale(1.46345)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="iZYALid" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20491 0 0 -1.15257 10.476 14.195)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="ib2qKQb" cx="0" cy="0" r="1" gradientTransform="rotate(165.53 8.688 8.801)scale(7.00342 7.95456)" gradientUnits="userSpaceOnUse"><stop offset=".004" class="d2c6yebwr"/><stop offset="1" class="bponozbjf"/></radialGradient><radialGradient id="ipc1cwG" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.625 -7.06123 0 15.613 12.09)" gradientUnits="userSpaceOnUse"><stop class="q2qywsbdi"/><stop offset="1" class="a-kd6j_2a"/></radialGradient><radialGradient id="iTPoEcd" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.80185 -14.4136 0 15.995 14.09)" gradientUnits="userSpaceOnUse"><stop offset=".666" class="figjawccb"/><stop offset=".974" class="i18lb-zbl"/></radialGradient><radialGradient id="io4Ii8b" cx="0" cy="0" r="1" gradientTransform="matrix(-.42187 -2.40625 1.25712 -.2204 16.863 15.637)" gradientUnits="userSpaceOnUse"><stop class="e2e9miase"/><stop offset="1" class="pgpvnfb3j"/></radialGradient><radialGradient id="i4TQ6Qc" cx="0" cy="0" r="1" gradientTransform="matrix(.19531 -.39062 1.40497 .70248 14.797 17.863)" gradientUnits="userSpaceOnUse"><stop class="sys9_5h7y"/><stop offset="1" class="u-7wekavm"/></radialGradient><radialGradient id="icQmM9c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.2041 1.37012 0 18.443 14.255)" gradientUnits="userSpaceOnUse"><stop offset=".734" class="plcsv1lkf"/><stop offset="1" class="feg1teu5p"/></radialGradient><radialGradient id="ijQ2ygV" cx="0" cy="0" r="1" gradientTransform="matrix(-.25995 -.33498 .46118 -.35789 18.186 13.62)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iVFFT3d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.20411 1.37013 0 13.547 14.255)" gradientUnits="userSpaceOnUse"><stop offset=".734" class="plcsv1lkf"/><stop offset="1" class="feg1teu5p"/></radialGradient><radialGradient id="iVz6XMc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00867 -.55378 .66566 -.01042 13.226 13.77)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iqJloEe" cx="0" cy="0" r="1" gradientTransform="rotate(89.9 6.13 13.43)scale(4.18751 2.64389)" gradientUnits="userSpaceOnUse"><stop class="qq6id-bgn"/><stop offset="1" class="o043sbvrw"/></radialGradient><radialGradient id="i3kwMJe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16 5.79775 0 11.807 9.965)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="lsejgobiz"/><stop offset="1" class="ufkfu5bhx"/></radialGradient><radialGradient id="ix7yNse" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 -8 15.26892 2.44541 17.214 10.402)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="g4-w6ccdn"/><stop offset=".946" class="dan8ctbrb"/></radialGradient><radialGradient id="iboBgJb" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.875 -.59037 0 13.151 6.574)" gradientUnits="userSpaceOnUse"><stop offset=".305" class="ms9ao5bgb"/><stop offset="1" class="gdbdqk9_y"/></radialGradient><radialGradient id="i1iCHwb" cx="0" cy="0" r="1" gradientTransform="matrix(.37503 4.21874 -1.6853 .14982 13.276 2.81)" gradientUnits="userSpaceOnUse"><stop offset=".103" class="x8to7on4z"/><stop offset="1" class="x2t1gbbxv"/></radialGradient><radialGradient id="iXs217E" cx="0" cy="0" r="1" gradientTransform="matrix(-5.24995 -6.37504 7.8363 -6.45332 16.714 9.809)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="oobbay99s"/><stop offset="1" class="hb0fg9dnu"/></radialGradient><radialGradient id="irEoioq" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.59375 5.79687 0 10.932 10.2)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="aa5l6qb6a"/><stop offset="1" class="mgd_z41tu"/></radialGradient><radialGradient id="ipzg10b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.0625 1 0 13.432 9.965)" gradientUnits="userSpaceOnUse"><stop class="lmg939n4j"/><stop offset="1" class="psulmw2ur"/></radialGradient><radialGradient id="irDBt4j" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.78125 1.6875 0 18.307 10.027)" gradientUnits="userSpaceOnUse"><stop class="kyytyn57f"/><stop offset="1" class="xr07nxbnn"/></radialGradient><radialGradient id="iGV0mjd" cx="0" cy="0" r="1" gradientTransform="matrix(.52313 2.06026 -12.32015 3.12823 11.671 9.04)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="nrsb-h28d"/><stop offset="1" class="j07dbhb1v"/></radialGradient><filter id="iJR6FMb" width="17.347" height="16.847" x="7.571" y="4.628" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.560784 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2946"/></filter><filter id="ipjEQGb" width="3.71" height="3.61" x="8.65" y="12.39" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.611765 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2946"/></filter><filter id="iELS3se" width="3.61" height="3.86" x="19.752" y="12.14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2946"/></filter><filter id="iGbtL2n" width="3.41" height="3.41" x="19.852" y="12.49" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2946" stdDeviation=".25"/></filter><filter id="i7R2Zed" width="2.91" height="2.91" x="9.021" y="12.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2946" stdDeviation=".125"/></filter><filter id="iqUaWSW" width="11.932" height="12.201" x="10.279" y="8.69" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.596078 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2946"/></filter><filter id="iObyJWb" width="3.106" height="4.008" x="14.26" y="13.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2946" stdDeviation=".25"/></filter><filter id="iY369bd" width="2.606" height="3.508" x="14.692" y="13.223" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.941176 0 0 0 0 0.580392 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2946"/><feGaussianBlur result="effect2_foregroundBlur_4002_2946" stdDeviation=".125"/></filter><filter id="iHebtFe" width="2.606" height="3.508" x="14.692" y="13.048" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2946" stdDeviation=".125"/></filter><filter id="iSFSurd" width="4.104" height="1.663" x="13.943" y="16.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2946" stdDeviation=".05"/></filter><filter id="i2SvaLc" width="3.343" height="1.442" x="17.076" y="12.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2946"/></filter><filter id="irZ8lhd" width="3.343" height="1.442" x="11.571" y="12.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2946"/></filter><filter id="iGGlYnq" width=".858" height=".756" x="17.631" y="13.044" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2946" stdDeviation=".05"/></filter><filter id="iDuxlpc" width=".951" height=".975" x="18.585" y="13.14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2946" stdDeviation=".1"/></filter><filter id="if86yhe" width="1.057" height="1.118" x="13.602" y="13.069" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2946" stdDeviation=".1"/></filter><filter id="imv67Bb" width=".999" height=".765" x="12.743" y="13.035" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2946" stdDeviation=".05"/></filter><filter id="iv1d2tS" width="5.791" height="8.428" x="12.889" y="2.176" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.658824 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2946"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.92549 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2946" result="effect2_innerShadow_4002_2946"/></filter><filter id="ia3nzBd" width="7.654" height="2.528" x="15.476" y="9.698" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2946" stdDeviation=".5"/></filter><linearGradient id="i6Z8pHc" x1="22.863" x2="11.113" y1="14.809" y2="21.475" gradientUnits="userSpaceOnUse"><stop class="p__xoqbhx"/><stop offset="1" class="b50akeb_m"/></linearGradient><linearGradient id="iMXI4be" x1="9.132" x2="9.132" y1="21.305" y2="30.035" gradientUnits="userSpaceOnUse"><stop class="u14do7mcv"/><stop offset="1" class="qo0y3qb-y"/></linearGradient><linearGradient id="ipxekOb" x1="21.008" x2="21.008" y1="19.841" y2="30.035" gradientUnits="userSpaceOnUse"><stop class="di--38mzt"/><stop offset="1" class="htellnhxv"/></linearGradient><linearGradient id="iNKXo2b" x1="8.442" x2="6.774" y1="30.035" y2="29.875" gradientUnits="userSpaceOnUse"><stop offset=".333" class="x43wds7fi"/><stop offset="1" class="xjs932baa"/></linearGradient><linearGradient id="ibehgCc" x1="8.65" x2="11.969" y1="14.293" y2="14.293" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="ilQiq6b" x1="15.847" x2="16.269" y1="12.98" y2="14.543" gradientUnits="userSpaceOnUse"><stop offset=".27" class="ltm66e5_x"/><stop offset="1" class="e0pdo5baa"/></linearGradient><linearGradient id="iIGMFje" x1="19.315" x2="18.963" y1="13.585" y2="13.802" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iaFEZAc" x1="14.381" x2="14.029" y1="13.585" y2="13.802" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ia2SCWb" x1="9.745" x2="10.557" y1="9.34" y2="9.34" gradientUnits="userSpaceOnUse"><stop class="ms43e0vsz"/><stop offset="1" class="b_iay1xzu"/></linearGradient><linearGradient id="ispODVd" x1="15.784" x2="15.784" y1="2.176" y2="10.604" gradientUnits="userSpaceOnUse"><stop class="ououd5b1f"/><stop offset="1" class="tl7x7-b-x"/></linearGradient><linearGradient id="izJ3uTd" x1="15.784" x2="15.784" y1="2.176" y2="4.777" gradientUnits="userSpaceOnUse"><stop class="ahajb6vmx"/><stop offset="1" class="npjjoacns"/></linearGradient><linearGradient id="iJHEdBc" x1="21.76" x2="5.132" y1="11.349" y2="11.349" gradientUnits="userSpaceOnUse"><stop class="vergo-4jw"/><stop offset="1" class="pj-kb0bjs"/></linearGradient><linearGradient id="iCNde1b" x1="15.561" x2="15.561" y1="9.948" y2="10.261" gradientUnits="userSpaceOnUse"><stop offset=".027" class="xsg9vwb1s"/><stop offset="1" class="t_t6-ha7d"/></linearGradient><linearGradient id="idtJpnd" x1="16.479" x2="16.479" y1="12.254" y2="11.001" gradientUnits="userSpaceOnUse"><stop class="ex-0zhc5k"/><stop offset="1" class="o5ewjjbtz"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-construction-worker" /></template>
<style>
.a-kd6j_2a {
  stop-color: var(--svg-color--f28e2f, #F28E2F);
  stop-opacity: 0;
}

.a41x9tbei {
  stop-color: var(--svg-color--f25937, #F25937);
  stop-opacity: 0;
}

.aa5l6qb6a {
  stop-color: var(--svg-color--c8a03f, #C8A03F);
}

.ahajb6vmx {
  stop-color: var(--svg-color--e7c44c, #E7C44C);
}

.aq7c7ccsd {
  d: path("M22.24 9.948H9.646a1.153 1.153 0 1 0 0 2.306H22.24c.641 0 1.153-.52 1.153-1.153a1.147 1.147 0 0 0-1.153-1.153");
}

.b_iay1xzu {
  stop-color: var(--svg-color--cdac54, #CDAC54);
  stop-opacity: 0;
}

.b50akeb_m {
  stop-color: var(--svg-color--f07b2c, #F07B2C);
}

.bm7nyqb5j {
  d: path("M14.589 2.176h2.39c.829 0 1.5.602 1.5 1.632v6.796h-5.39V3.808c0-1.03.671-1.632 1.5-1.632");
}

.bponozbjf {
  stop-color: var(--svg-color--f29634, #F29634);
}

.bxvgrdn8d {
  d: path("M21.999 20.875v9.16h-1.983V19.841c.698.279 1.355.62 1.983 1.034");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cr7yd6bcj {
  stop-color: var(--svg-color--9d67e1, #9D67E1);
}

.cs69zqbom {
  stop-color: var(--svg-color--8356c7, #8356C7);
}

.ctoz1_s2k {
  stop-color: var(--svg-color--f5832c, #F5832C);
}

.d_rzkbbzn {
  stop-color: var(--svg-color--d87934, #D87934);
}

.d2c6yebwr {
  stop-color: var(--svg-color--ffe131, #FFE131);
}

.d4g-zbbev {
  d: path("M10.279 12.137c.023-1.064.644-1.476.909-1.613l.057-.023q.03-.015.058-.023a2.6 2.6 0 0 0 1.334-1.385l.092-.218a.296.296 0 0 1 .518-.057a4.33 4.33 0 0 0 3.578 1.877h3.612c.202 0 1.213.098 1.274 1.495l-.133 3.447c-.139 3.144-2.594 5.255-5.59 5.255s-5.452-2.111-5.59-5.255l-.108-3.17z");
}

.d9srtldqu {
  stop-color: var(--svg-color--ff6f59, #FF6F59);
}

.dan8ctbrb {
  stop-color: var(--svg-color--eecd67, #EECD67);
}

.dd-ysdbcy {
  d: path("M18.445 12.99a1 1 0 0 1 .965 1.265h-1.934a1.005 1.005 0 0 1 .97-1.265");
}

.di--38mzt {
  stop-color: var(--svg-color--ffda42, #FFDA42);
}

.dljkp6qbr {
  stop-color: var(--svg-color--d36024, #D36024);
}

.dm49oyb0x {
  cx: 19.303px;
  cy: 10.961px;
  fill: var(--svg-color--fff060, #FFF060);
  rx: 2.827px;
  ry: 0.264px;
}

.dqt_06a7d {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M21.557 15.4a1.205 1.205 0 1 0 0-2.41a1.205 1.205 0 0 0 0 2.41");
}

.dr2x31jzv {
  stop-color: var(--svg-color--ff7446, #FF7446);
}

.drkw4m_di {
  cx: 13.242px;
  cy: 13.418px;
  rx: 0.437px;
  ry: 0.221px;
}

.e0pdo5baa {
  stop-color: var(--svg-color--f6a734, #F6A734);
  stop-opacity: 0;
}

.e2e9miase {
  stop-color: var(--svg-color--ffde3e, #FFDE3E);
}

.e3j7-mb6u {
  stop-color: var(--svg-color--ff7e58, #FF7E58);
  stop-opacity: 0;
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.ecitxobgm {
  stop-color: var(--svg-color--966ce3, #966CE3);
}

.eezsb1bxh {
  stop-color: var(--svg-color--d96225, #D96225);
}

.elhgnqewr {
  d: path("M21.557 15.4a1.205 1.205 0 1 0 0-2.41a1.205 1.205 0 0 0 0 2.41");
}

.evjtz5bic {
  stop-color: var(--svg-color--f7803a, #F7803A);
}

.ex-0zhc5k {
  stop-color: var(--svg-color--e1926f, #E1926F);
}

.ez-c7ubrp {
  stop-color: var(--svg-color--da4708, #DA4708);
}

.f2js-baog {
  stop-color: var(--svg-color--cd963a, #CD963A);
}

.feg1teu5p {
  stop-color: var(--svg-color--63423a, #63423A);
}

.figjawccb {
  stop-color: var(--svg-color--f49836, #F49836);
  stop-opacity: 0;
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.fnd6bmb7i {
  d: path("M9.949 20.875v9.16h1.982V19.841c-.697.279-1.355.62-1.982 1.034");
}

.fqxdxer3q {
  fill: var(--svg-color--000, #000);
  d: path("M14.118 13.991a.57.57 0 0 0-.573-.573a.57.57 0 0 0-.51.837h1.015a.6.6 0 0 0 .068-.264");
}

.ft5dv1b6b {
  fill: none;
}

.g1821aczo {
  d: path("M10.476 15.4a1.205 1.205 0 1 0 0-2.41a1.205 1.205 0 0 0 0 2.41");
}

.g4-w6ccdn {
  stop-color: var(--svg-color--eecd67, #EECD67);
  stop-opacity: 0;
}

.g6n7870oj {
  stop-color: var(--svg-color--ff6a37, #FF6A37);
}

.gdbdqk9_y {
  stop-color: var(--svg-color--e1b037, #E1B037);
  stop-opacity: 0;
}

.gj7ixfb9c {
  d: path("M18.253 19.303c.607.135 1.195.31 1.763.538v10.194h-1.763z");
}

.gm6cubr5k {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.714 13.556c-.298-.523-.75-.937-1.725-.937a1.86 1.86 0 0 0-1.203.414c-.302.243-.261.555-.028.672l.624.356c.731-.236 1.54-.268 2.332-.505");
}

.gmju-3syb {
  d: path("m15.566 13.615l-.596 1.907a.605.605 0 0 0 .584.784h.882a.607.607 0 0 0 .584-.784l-.596-1.907c-.128-.423-.724-.423-.858 0");
}

.gqnfcq7gb {
  cx: 13.242px;
  cy: 13.418px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.437px;
  ry: 0.221px;
}

.grpyt1-9k {
  stop-color: var(--svg-color--ff7523, #FF7523);
}

.gt-qelr6u {
  stop-color: var(--svg-color--ff905a, #FF905A);
}

.h11_utkon {
  stop-color: var(--svg-color--b96201, #B96201);
}

.hb0fg9dnu {
  stop-color: var(--svg-color--c3a852, #C3A852);
}

.hcz5bq05r {
  d: path("M19.336 13.859a.94.94 0 0 0-.26-.519l-.29.32l.131.256z");
}

.htellnhxv {
  stop-color: var(--svg-color--ffcf4c, #FFCF4C);
}

.i18lb-zbl {
  stop-color: var(--svg-color--ec7d4e, #EC7D4E);
}

.i5rrmccaf {
  stop-color: var(--svg-color--a271ef, #A271EF);
  stop-opacity: 0;
}

.imh8orb1k {
  d: path("M13.695 19.303c-.608.135-1.196.31-1.764.538v10.194h1.764z");
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.j_fyy6bgf {
  fill: var(--svg-color--000, #000);
  d: path("M17.872 13.991a.57.57 0 0 1 .573-.573a.57.57 0 0 1 .51.837H17.94a.5.5 0 0 1-.068-.264");
}

.j-l1xfbxd {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M15.995 17.46a3.4 3.4 0 0 1-1.595-.386c-.158-.082-.327.1-.228.246a2.167 2.167 0 0 0 3.645 0c.1-.152-.07-.328-.227-.246a3.4 3.4 0 0 1-1.595.387");
}

.j07dbhb1v {
  stop-color: var(--svg-color--dfb83e, #DFB83E);
  stop-opacity: 0;
}

.jiob30meo {
  stop-color: var(--svg-color--de521d, #DE521D);
}

.jtdflpb8n {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M10.476 15.4a1.205 1.205 0 1 0 0-2.41a1.205 1.205 0 0 0 0 2.41");
}

.juo63cbvd {
  stop-color: var(--svg-color--ffce64, #FFCE64);
  stop-opacity: 0;
}

.k_5oi18_f {
  stop-color: var(--svg-color--ffa040, #FFA040);
}

.kbbwcocfe {
  d: path("M14.459 13.873c0-.323-.263-.539-.334-.604l-.323.313l.199.404z");
}

.ke__lf9po {
  stop-color: var(--svg-color--a271ef, #A271EF);
}

.knzs36blp {
  fill: var(--svg-color--ffca44, #FFCA44);
  d: path("M9.949 20.875v9.16h1.982V19.841c-.697.279-1.355.62-1.982 1.034");
}

.kyytyn57f {
  stop-color: var(--svg-color--ffe550, #FFE550);
}

.l_fectb5m {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.276 13.556c.298-.523.75-.937 1.725-.937c.426 0 .837.118 1.203.414c.302.243.261.555.028.672l-.624.356c-.731-.236-1.54-.268-2.332-.505");
}

.l3uqdwbmc {
  d: path("M4.575 30.035c.14-.946.34-1.881.62-2.786a11.56 11.56 0 0 1 3.12-5.019v7.805z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lmg939n4j {
  stop-color: var(--svg-color--e3b438, #E3B438);
}

.lsejgobiz {
  stop-color: var(--svg-color--e9b840, #E9B840);
}

.ltm66e5_x {
  stop-color: var(--svg-color--f6a734, #F6A734);
}

.ma8s15bfz {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.677 12.685c.733 0 1.352.505 1.52 1.188c.05.195-.1.382-.3.382h-2.503a.258.258 0 0 1-.255-.305a1.57 1.57 0 0 1 1.538-1.265");
}

.mgd_z41tu {
  stop-color: var(--svg-color--c8a03f, #C8A03F);
  stop-opacity: 0;
}

.mnndm4kgz {
  stop-color: var(--svg-color--ff9633, #FF9633);
  stop-opacity: 0;
}

.ms43e0vsz {
  stop-color: var(--svg-color--cdac54, #CDAC54);
}

.ms9ao5bgb {
  stop-color: var(--svg-color--d7a439, #D7A439);
}

.msvb4ybbk {
  fill: var(--svg-color--ffb723, #FFB723);
  d: path("m15.566 13.79l-.596 1.907a.605.605 0 0 0 .584.784h.882a.607.607 0 0 0 .584-.784l-.596-1.907c-.128-.423-.724-.423-.858 0");
}

.mv_v0947c {
  stop-color: var(--svg-color--a473f8, #A473F8);
}

.mzrwpxbna {
  stop-color: var(--svg-color--dc5314, #DC5314);
  stop-opacity: 0;
}

.n5hwk-_ts {
  stop-color: var(--svg-color--ffb32d, #FFB32D);
  stop-opacity: 0;
}

.n64pcpbcq {
  d: path("M10.455 16a1.805 1.805 0 1 0 0-3.61a1.805 1.805 0 0 0 0 3.61");
}

.nf94bbbdk {
  fill: var(--svg-color--f6942e, #F6942E);
  d: path("m15.554 13.945l-.766 1.907a.605.605 0 0 0 .584.784h.882a.607.607 0 0 0 .584-.784l-.596-1.907c-.128-.423-.554-.423-.688 0");
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.npjjoacns {
  stop-color: var(--svg-color--e7c44c, #E7C44C);
  stop-opacity: 0;
}

.nrsb-h28d {
  stop-color: var(--svg-color--c4a966, #C4A966);
}

.nxdi2gb_j {
  stop-color: var(--svg-color--f97130, #F97130);
  stop-opacity: 0;
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.o-k236b0e {
  d: path("M9.745 7.284a4.1 4.1 0 0 1 4.1-4.1h3.987a4.1 4.1 0 0 1 4.1 4.1v2.68H9.745z");
}

.o043sbvrw {
  stop-color: var(--svg-color--fd4, #FD4);
}

.o2jd-jggt {
  stop-color: var(--svg-color--ffce64, #FFCE64);
}

.o5ewjjbtz {
  stop-color: var(--svg-color--f9b14d, #F9B14D);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.omeu62b7c {
  stop-color: var(--svg-color--ff6f4e, #FF6F4E);
}

.oobbay99s {
  stop-color: var(--svg-color--c3a852, #C3A852);
  stop-opacity: 0;
}

.ououd5b1f {
  stop-color: var(--svg-color--f9cd2e, #F9CD2E);
}

.p__xoqbhx {
  stop-color: var(--svg-color--ffac2e, #FFAC2E);
}

.p-n74xx1h {
  stop-color: var(--svg-color--fb684a, #FB684A);
}

.pgpvnfb3j {
  stop-color: var(--svg-color--ffde3e, #FFDE3E);
  stop-opacity: 0;
}

.pj-kb0bjs {
  stop-color: var(--svg-color--f0bc33, #F0BC33);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.plcsv1lkf {
  stop-color: var(--svg-color--805351, #805351);
}

.psulmw2ur {
  stop-color: var(--svg-color--e3b438, #E3B438);
  stop-opacity: 0;
}

.q21gbz2ll {
  stop-color: var(--svg-color--ffcc38, #FFCC38);
}

.q2qywsbdi {
  stop-color: var(--svg-color--f28e2f, #F28E2F);
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qf92jxbjd {
  stop-color: var(--svg-color--fe713a, #FE713A);
  stop-opacity: 0;
}

.qo0y3qb-y {
  stop-color: var(--svg-color--f46d40, #F46D40);
}

.qq6id-bgn {
  stop-color: var(--svg-color--ffee61, #FFEE61);
}

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.qwrmqwbeg {
  d: path("M13.784 20.406c.06.796.585 2.387 2.21 2.387c1.627 0 2.152-1.591 2.212-2.387z");
}

.rk8_jsb0a {
  stop-color: var(--svg-color--8d6fbf, #8D6FBF);
}

.rrfndackx {
  stop-color: var(--svg-color--ff7e58, #FF7E58);
}

.sb8u_ob9q {
  d: path("M13.545 12.99a1 1 0 0 0-.965 1.265h1.934q.036-.129.037-.264a1.01 1.01 0 0 0-1.006-1.001");
}

.sg1j4mthl {
  d: path("M8.362 22.123a.15.15 0 0 0-.047.11v7.802h1.634v-9.16c-.56.37-1.092.79-1.587 1.248");
}

.shm05pbnp {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.37 13.202c.072.095-.077.211-.247.338s-.295.216-.366.12c-.071-.095.008-.275.178-.402c.17-.126.364-.151.436-.056");
}

.sqvmrgb3n {
  stop-color: var(--svg-color--e07241, #E07241);
  stop-opacity: 0;
}

.sy1uvdbyp {
  stop-color: var(--svg-color--f5832c, #F5832C);
  stop-opacity: 0;
}

.syk9gb6hv {
  d: path("M15.995 19.425c-.78 0-1.55.08-2.3.23v10.38h4.58v-10.38c-.74-.15-1.5-.23-2.28-.23");
}

.sys9_5h7y {
  stop-color: var(--svg-color--fea837, #FEA837);
}

.t_t6-ha7d {
  stop-color: var(--svg-color--ffd131, #FFD131);
  stop-opacity: 0;
}

.tg2hgyb7l {
  d: path("M21.557 16a1.805 1.805 0 1 0 0-3.61a1.805 1.805 0 0 0 0 3.61");
}

.thq31dj-g {
  stop-color: var(--svg-color--fe713a, #FE713A);
}

.thxviccqr {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.313 12.685c-.733 0-1.352.505-1.52 1.188c-.05.195.1.382.3.382h2.503c.16 0 .287-.146.255-.305a1.57 1.57 0 0 0-1.538-1.265");
}

.tl7x7-b-x {
  stop-color: var(--svg-color--ffca3d, #FFCA3D);
}

.trtw9eqsx {
  stop-color: var(--svg-color--ffb32d, #FFB32D);
}

.u-7wekavm {
  stop-color: var(--svg-color--fea837, #FEA837);
  stop-opacity: 0;
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.u14do7mcv {
  stop-color: var(--svg-color--e6743e, #E6743E);
}

.u6kq06bzt {
  stop-color: var(--svg-color--9c4a00, #9C4A00);
}

.u77xpkbsk {
  stop-color: var(--svg-color--8356c7, #8356C7);
  stop-opacity: 0;
}

.ufkfu5bhx {
  stop-color: var(--svg-color--e9b840, #E9B840);
  stop-opacity: 0;
}

.uguyroe_g {
  d: path("M27.373 30.035c-.14-.946-.34-1.881-.62-2.786a11.56 11.56 0 0 0-3.12-5.019v7.805z");
}

.v2x6yq-ng {
  stop-color: var(--svg-color--de521d, #DE521D);
  stop-opacity: 0;
}

.vergo-4jw {
  stop-color: var(--svg-color--ffe24a, #FFE24A);
}

.vp8k99b3t {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.995 17.46a3.4 3.4 0 0 1-1.595-.386c-.158-.082-.327.1-.228.246a2.167 2.167 0 0 0 3.645 0c.1-.152-.07-.328-.227-.246a3.4 3.4 0 0 1-1.595.387Z");
}

.vtgegwb8d {
  d: path("M18.37 13.202c.072.095-.077.211-.247.338s-.295.216-.366.12c-.071-.095.008-.275.178-.402c.17-.126.364-.151.436-.056");
}

.wqe5m4buq {
  stop-color: var(--svg-color--b087fd, #B087FD);
}

.wwty3-ban {
  stop-color: var(--svg-color--f25937, #F25937);
}

.x__bgvnia {
  stop-color: var(--svg-color--f78b29, #F78B29);
  stop-opacity: 0;
}

.x-ndnlz5c {
  stop-color: var(--svg-color--ffcc38, #FFCC38);
  stop-opacity: 0;
}

.x2t1gbbxv {
  stop-color: var(--svg-color--cba731, #CBA731);
  stop-opacity: 0;
}

.x43wds7fi {
  stop-color: var(--svg-color--735992, #735992);
}

.x8to7on4z {
  stop-color: var(--svg-color--b59741, #B59741);
}

.xjs932baa {
  stop-color: var(--svg-color--735992, #735992);
  stop-opacity: 0;
}

.xmk-y9toa {
  stop-color: var(--svg-color--d36024, #D36024);
  stop-opacity: 0;
}

.xmtd48u_j {
  stop-color: var(--svg-color--ff7955, #FF7955);
}

.xnbb4159v {
  stop-color: var(--svg-color--cc6e42, #CC6E42);
}

.xr07nxbnn {
  stop-color: var(--svg-color--ffe550, #FFE550);
  stop-opacity: 0;
}

.xsg9vwb1s {
  stop-color: var(--svg-color--ffd131, #FFD131);
}

.yd4o9ab3h {
  d: path("m15.566 13.79l-.596 1.907a.605.605 0 0 0 .584.784h.882a.607.607 0 0 0 .584-.784l-.596-1.907c-.128-.423-.724-.423-.858 0");
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.yrdgovb8a {
  stop-color: var(--svg-color--fdbf28, #FDBF28);
  stop-opacity: 0;
}

.yu7_obi3v {
  fill-rule: evenodd;
  d: path("M24.055 15.776a3.64 3.64 0 0 0 .363-1.6c0-.525-.107-1.017-.3-1.465h.005a3.6 3.6 0 0 0-.315-.575l-.003-.004c-.386-.59-1.099-.928-1.099-1.631l-1.25.023c0-2.044.102-4.09-1.942-4.09a.6.6 0 0 1-.51-.262a3.7 3.7 0 0 0-3.01-1.544a3.7 3.7 0 0 0-3.008 1.544a.63.63 0 0 1-.51.261l-.096.001c-2 .05-2.078 2.032-2.078 4.044H9.144c0 .704-.574 1.064-.96 1.654l-.002.004a3.7 3.7 0 0 0-.247 3.64c.08.159.08.352 0 .51a3.7 3.7 0 0 0-.364 1.579a3.605 3.605 0 0 0 3.61 3.61h9.627a3.605 3.605 0 0 0 3.61-3.61c0-.568-.136-1.101-.363-1.578a.58.58 0 0 1 0-.51m-13.753-2.998h-.014l1.345 2.643c.138 3.143 1.365 0 4.362 0s4.303 3.499 4.442.355l-.737-3.639c-.06-1.396.939-1.442.737-1.442h-3.613a4.33 4.33 0 0 1-3.577-1.877a.296.296 0 0 0-.518.057l-.092.218a2.6 2.6 0 0 1-1.392 1.408l-.057.023c-.265.137-.886.549-.909 1.613l.011.344z");
}

.yux7yn9ee {
  stop-color: var(--svg-color--da7919, #DA7919);
  stop-opacity: 0;
}

.yy757k4tp {
  stop-color: var(--svg-color--ff6a37, #FF6A37);
  stop-opacity: 0;
}

.z9pqso7mp {
  d: path("M23.601 22.138a.1.1 0 0 1 .032.072v7.825h-1.634v-9.16a12.5 12.5 0 0 1 1.602 1.262");
}

.zykt_9b7s {
  stop-color: var(--svg-color--9879c9, #9879C9);
}

</style>
