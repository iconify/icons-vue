<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ip8hc9c)"><path fill="url(#ik3t6MU)" clip-rule="evenodd" class="btdzh5v7s"/><path fill="url(#iA7iDUd)" clip-rule="evenodd" class="btdzh5v7s"/><path fill="url(#iUUpLvd)" clip-rule="evenodd" class="btdzh5v7s"/><path fill="url(#ilbfCHD)" clip-rule="evenodd" class="btdzh5v7s"/><path fill="url(#ifvkoPe)" clip-rule="evenodd" class="btdzh5v7s"/><path fill="url(#i0PwQge)" clip-rule="evenodd" class="btdzh5v7s"/><path fill="url(#ibpF2gC)" clip-rule="evenodd" class="btdzh5v7s"/><path fill="url(#iBk5sJc)" clip-rule="evenodd" class="btdzh5v7s"/><path fill="url(#iJrj2Gc)" clip-rule="evenodd" class="btdzh5v7s"/><path fill="url(#ijXdyUb)" clip-rule="evenodd" class="btdzh5v7s"/><path fill="url(#iiMvUBc)" clip-rule="evenodd" class="btdzh5v7s"/></g><g filter="url(#iipWane)"><path fill="url(#iBVZi5W)" class="d7pn-80kf"/><path fill="url(#iuAvzJc)" class="d7pn-80kf"/></g><g filter="url(#idyyUMc)"><path class="q6g7x-c0g"/></g><path fill="url(#iyiQikj)" class="v95bqqdny"/><path fill="url(#iqLdKse)" class="v95bqqdny"/><path fill="url(#irVLXnb)" class="y47tc3sih"/><path fill="url(#itK0Psb)" class="y47tc3sih"/><circle fill="url(#iPJVeRT)" class="dhdllmbnv"/><g filter="url(#iSaWYcd)"><path clip-rule="evenodd" class="zhe_95bye"/></g><circle fill="url(#i9ZTklb)" transform="matrix(-1 0 0 1 12.14 16.739)" class="kr_eiac3t"/><g filter="url(#iWyc8AV)"><path clip-rule="evenodd" class="lrux5gb2o"/><path fill="url(#iIk0eOt)" clip-rule="evenodd" class="ms15tsqbf"/></g><g filter="url(#ixVolNd)"><path class="ys_en_m8z"/></g><path fill="url(#ibBC50I)" class="jc4qhqbtm"/><path fill="url(#i2rMUdb)" class="jc4qhqbtm"/><path fill="url(#iNWrYYc)" class="jc4qhqbtm"/><path fill="url(#iMzsorc)" class="jc4qhqbtm"/><path fill="url(#iV8zCkc)" class="jc4qhqbtm"/><path fill="url(#iSC76Cc)" class="mytlpjw-h"/><g filter="url(#imMAkyd)"><path fill="url(#iE4LU4c)" class="x5tf_bc4w"/></g><g filter="url(#i221qon)"><path fill="url(#iskAstc)" class="zve07_b6e"/></g><g filter="url(#i8J138q)"><path class="wt8hn-lfq"/><path fill="url(#imfQs9c)" class="p-i_x_tkg"/></g><g filter="url(#irOg9ic)"><path class="w80noibxf"/><path fill="url(#iuwl5pe)" class="k6opfnbix"/></g><g filter="url(#idXk0Kd)"><path fill="url(#im1uaUb)" class="mizm7xb4g"/><path fill="url(#iHRMued)" class="mizm7xb4g"/><path fill="url(#iwz0D7x)" class="mizm7xb4g"/><path fill="url(#iD3pv8c)" class="mizm7xb4g"/><path fill="url(#iKXWotc)" class="mizm7xb4g"/><path fill="url(#iwDTO4V)" class="mizm7xb4g"/><path fill="url(#iY2LBlb)" class="mizm7xb4g"/></g><path fill="url(#ioi9MXc)" class="mizm7xb4g"/><g filter="url(#ixrDvNb)"><path class="r5g_3dbhv"/></g><g filter="url(#iJpHVRc)"><path fill="url(#iWl6v5B)" class="pmp7oac6x"/><path fill="url(#iaBPBKb)" class="pmp7oac6x"/><path fill="url(#iSZbj7K)" class="pmp7oac6x"/><path fill="url(#ior0YOe)" class="pmp7oac6x"/></g><g filter="url(#i0ntGnZ)"><path stroke="url(#ivSfdKc)" class="qfk268bmk"/></g><path class="jur2mybyp"/><g filter="url(#irBItmd)"><path class="nu-bxvbsr"/></g><g filter="url(#iP8x8Sd)"><path class="aupi9ybyt"/></g><g filter="url(#iDyTeee)"><path class="dr0toebdy"/></g><g filter="url(#i0Ploed)"><path clip-rule="evenodd" class="a3673_uqf"/></g><path class="fv9yutbaq"/><path fill="url(#iC7IgmQ)" class="n-2sfrb-v"/><path class="xqdsnxt8m"/><g filter="url(#iSheDGd)"><path class="aoqd5fdgs"/><path fill="url(#i5qKKrd)" class="j9y5m6c3t"/></g><g filter="url(#iIjCWFd)"><path fill="url(#ihKhuGc)" class="dzbxyhbei"/></g><path class="fvjsqgb0s"/><path fill="url(#iJF4G6d)" class="vzavi8tmc"/><path class="pf43v7bkm"/><g filter="url(#iWE4And)"><path fill="url(#ixiJUZp)" class="ew1xuqo2l"/></g><g filter="url(#ibmkzNe)"><ellipse transform="rotate(-27.914 7.804 7.467)" class="kol252b8f"/><ellipse fill="url(#idFE0Eb)" transform="rotate(-27.914 7.804 7.467)" class="hgjbhwb5c"/></g><g filter="url(#ixSYCyc)"><path class="n18jfcc-k"/></g><g filter="url(#iqSDDQd)"><path class="sofeydi8k"/></g><g filter="url(#iCaaxVM)"><path fill="url(#ib3YCxe)" class="b3w1zebtb"/><path fill="url(#imtQJic)" class="b3w1zebtb"/></g><g filter="url(#ie5qAEb)"><path fill="url(#ig9QWyb)" class="vzb-or29m"/><path fill="url(#ickXoMd)" class="vzb-or29m"/><path fill="url(#i0Bb87e)" class="vzb-or29m"/></g><g filter="url(#irnW0Zd)"><path stroke="url(#iLLqWyc)" class="x3yca2bds"/></g><g filter="url(#i1tcrjk)"><path class="nso6vxtpf"/></g><g filter="url(#iQXACic)"><path class="wlbrcoiqt"/></g><g filter="url(#ig4Ewyc)"><path fill="url(#ivEnbde)" class="q1l1czbkr"/></g><g filter="url(#iuzYrac)"><path fill="url(#iVfUilb)" clip-rule="evenodd" class="d2x5j-bsk"/><path fill="url(#iBLDj1d)" clip-rule="evenodd" class="d2x5j-bsk"/><path fill="url(#iK0QlPc)" clip-rule="evenodd" class="d2x5j-bsk"/><path fill="url(#icbonOc)" clip-rule="evenodd" class="d2x5j-bsk"/><path fill="url(#iLojLUb)" clip-rule="evenodd" class="d2x5j-bsk"/><path fill="url(#imlZbfb)" clip-rule="evenodd" class="d2x5j-bsk"/><path fill="url(#i8h1Gib)" clip-rule="evenodd" class="d2x5j-bsk"/><path fill="url(#iDe6Tgc)" clip-rule="evenodd" class="d2x5j-bsk"/><path fill="url(#iel7ugc)" clip-rule="evenodd" class="d2x5j-bsk"/><path fill="url(#iIeJiCc)" clip-rule="evenodd" class="d2x5j-bsk"/><path fill="url(#if2FRtd)" clip-rule="evenodd" class="d2x5j-bsk"/></g><g filter="url(#i4DcaJc)"><path fill="url(#iZzktmc)" class="bu-vy8bim"/><path fill="url(#iJGUtYb)" class="bu-vy8bim"/></g><g filter="url(#itPrmEc)"><path class="cmre8ebkt"/></g><path fill="url(#iVkHbMe)" class="xnn9y3bie"/><path fill="url(#ipfucwb)" class="xnn9y3bie"/><path fill="url(#i4ktv5d)" class="a9f4hxbhf"/><path fill="url(#icEReie)" class="a9f4hxbhf"/><circle fill="url(#icbe3dU)" class="rdymgqtsv"/><g filter="url(#iJ1Hbrb)"><path clip-rule="evenodd" class="t7ahgabts"/></g><circle fill="url(#i9ZTklb)" transform="matrix(-1 0 0 1 25.185 16.739)" class="kr_eiac3t"/><g filter="url(#iPBY1ir)"><path clip-rule="evenodd" class="wri7c1b3n"/><path fill="url(#iO6yMIb)" clip-rule="evenodd" class="a41cmg3ue"/></g><g filter="url(#i5gc63c)"><path class="ri_r8xb5e"/></g><path fill="url(#ir1bPQb)" class="l2kz2nbvy"/><path fill="url(#iToCvPe)" class="l2kz2nbvy"/><path fill="url(#iL5nSDu)" class="l2kz2nbvy"/><path fill="url(#iqv3jpN)" class="l2kz2nbvy"/><path fill="url(#iJNOPRd)" class="l2kz2nbvy"/><path fill="url(#iUPm7db)" class="psipoacfy"/><g filter="url(#iYXEFDY)"><path fill="url(#iAzZe8c)" class="sm9o9oxie"/></g><g filter="url(#iqOKgdb)"><path fill="url(#iHcpPbd)" class="j15z5b2ap"/></g><g filter="url(#iKDBAMd)"><path class="rusiodlkr"/><path fill="url(#iPfuZWb)" class="f7r0_-hng"/></g><g filter="url(#iBnEErc)"><path class="v3999ro-u"/><path fill="url(#iMLqlYb)" class="p0kg-zbqi"/></g><g filter="url(#i4hs7BN)"><path fill="url(#inbfJoe)" class="wo-g16f9e"/><path fill="url(#icVD0Sb)" class="wo-g16f9e"/><path fill="url(#inbsFvc)" class="wo-g16f9e"/><path fill="url(#inzblri)" class="wo-g16f9e"/><path fill="url(#ievpYYb)" class="wo-g16f9e"/><path fill="url(#i8stJMd)" class="wo-g16f9e"/><path fill="url(#i7G4hsc)" class="wo-g16f9e"/></g><path fill="url(#iuiZb4c)" class="wo-g16f9e"/><g filter="url(#iwo78eb)"><path class="yaqk-qbgh"/></g><g filter="url(#iFCXq3c)"><path fill="url(#i41pIPb)" class="vx526acon"/><path fill="url(#iJo7Hle)" class="vx526acon"/><path fill="url(#iEBPGae)" class="vx526acon"/><path fill="url(#iwIiTFd)" class="vx526acon"/></g><g filter="url(#ir90mbe)"><path stroke="url(#i4DGEit)" class="g-l8-0bhf"/></g><path class="bz-3bacdo"/><g filter="url(#i2BwWze)"><path class="vh2gln4ru"/></g><g filter="url(#iAaRJPe)"><path class="yqzmhsbig"/></g><g filter="url(#ibbaR7d)"><path class="ge3utjblo"/></g><g filter="url(#iepBDWb)"><path clip-rule="evenodd" class="ehl3xubna"/></g><path class="ghy9u737z"/><path fill="url(#i7TEoXj)" class="z5d0by-ny"/><path class="pqggtpb7u"/><g filter="url(#il9iS7c)"><path class="lqdkbomtg"/><path fill="url(#i4eVi3V)" class="u6qsrbphj"/></g><g filter="url(#i4RNved)"><path fill="url(#i5O7d1b)" class="el7d06s8x"/></g><path class="wkiuhjwwj"/><path fill="url(#ivBn0Wc)" class="dmcaafdnb"/><path class="azv0v7pdh"/><g filter="url(#ilLPxlb)"><path fill="url(#irw6aRc)" class="wz37uxbol"/></g><g filter="url(#imL1DQe)"><ellipse transform="rotate(-27.914 20.849 7.467)" class="tep9ytb3r"/><ellipse fill="url(#ig2qPsP)" transform="rotate(-27.914 20.849 7.467)" class="y3kf9motm"/></g><g filter="url(#iv3mCKd)"><path class="sgzpl9b9a"/></g><g filter="url(#ijGR7fc)"><path class="rwhqt0bkw"/></g><g filter="url(#iWG5fDd)"><path fill="url(#ik3yfoe)" class="cbzdjcf_x"/><path fill="url(#ioQALKj)" class="cbzdjcf_x"/></g><g filter="url(#iM0o9Pd)"><path fill="url(#ivqMAUc)" class="zk7-lu68t"/><path fill="url(#i8Ypknt)" class="zk7-lu68t"/><path fill="url(#iESlhde)" class="zk7-lu68t"/></g><g filter="url(#iBH0ccV)"><path stroke="url(#i9gGMSc)" class="b585cfbmk"/></g><g filter="url(#idcHqxd)"><path class="hw6mgnbqq"/></g><g filter="url(#iboPF7b)"><path class="iqag43gby"/></g><g filter="url(#i4C7OJe)"><path fill="url(#ipMYBOe)" class="aepf4rbzo"/></g><defs><radialGradient id="iA7iDUd" cx="0" cy="0" r="1" gradientTransform="rotate(28.301 -12.95 25.39)scale(1.36484 1.93323)" gradientUnits="userSpaceOnUse"><stop offset=".616" class="w3-vy4c8j"/><stop offset="1" class="w72oynbwi"/></radialGradient><radialGradient id="iUUpLvd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.90696 -1.14888 0 6.898 8.633)" gradientUnits="userSpaceOnUse"><stop class="lcrdwk1fj"/><stop offset="1" class="denqa3bda"/></radialGradient><radialGradient id="ilbfCHD" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.38389 -2.48325 0 8.854 8.673)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="ag6fa4z4y"/><stop offset="1" class="qir_1cb0f"/></radialGradient><radialGradient id="ifvkoPe" cx="0" cy="0" r="1" gradientTransform="matrix(-.53093 .689 -.66899 -.5155 6.752 7.9)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="ha2cq84sa"/><stop offset="1" class="p4wkjrbae"/></radialGradient><radialGradient id="i0PwQge" cx="0" cy="0" r="1" gradientTransform="rotate(100.537 .653 6.34)scale(1.09412 1.13932)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="tgqxysbgm"/><stop offset="1" class="p1xq25bjq"/></radialGradient><radialGradient id="ibpF2gC" cx="0" cy="0" r="1" gradientTransform="rotate(62.605 -.15 8.455)scale(1.01884 1.94087)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="esx41hbqq"/><stop offset=".921" class="v9rq5jjti"/></radialGradient><radialGradient id="iBk5sJc" cx="0" cy="0" r="1" gradientTransform="matrix(-.47337 .51641 -.72168 -.66153 11.206 5.305)" gradientUnits="userSpaceOnUse"><stop class="duwob45dr"/><stop offset="1" class="v61l3jbat"/></radialGradient><radialGradient id="iJrj2Gc" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 5.506 4.56)scale(.82163 1.78776)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="hottnizrg"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="ijXdyUb" cx="0" cy="0" r="1" gradientTransform="rotate(-133.315 7.946 2.932)scale(1.99498 2.86503)" gradientUnits="userSpaceOnUse"><stop class="yqk-2gbyp"/><stop offset="1" class="oaxszm67z"/></radialGradient><radialGradient id="iiMvUBc" cx="0" cy="0" r="1" gradientTransform="matrix(-.0036 -.5881 .19282 -.00118 7.696 5.766)" gradientUnits="userSpaceOnUse"><stop offset=".295" class="sufhn4bec"/><stop offset="1" class="kpf8h5ohf"/></radialGradient><radialGradient id="iyiQikj" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04689 2.23436 -1.0009 -.46896 7.541 28.114)" gradientUnits="userSpaceOnUse"><stop class="i7j8_4zgt"/><stop offset="1" class="g4nv9obue"/></radialGradient><radialGradient id="iqLdKse" cx="0" cy="0" r="1" gradientTransform="rotate(51.34 -26.585 21.054)scale(1.30063 3.1796)" gradientUnits="userSpaceOnUse"><stop offset=".522" class="enwi01lgk"/><stop offset="1" class="mta_69bbu"/></radialGradient><radialGradient id="irVLXnb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3576 -2.25 .95212 -.57449 16.204 29.864)" gradientUnits="userSpaceOnUse"><stop class="kuw77jfnz"/><stop offset="1" class="boon_rjzq"/></radialGradient><radialGradient id="itK0Psb" cx="0" cy="0" r="1" gradientTransform="matrix(-.81249 1.26563 -2.71996 -1.74612 15.495 28.41)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="hi3bu5i6r"/><stop offset="1" class="atfd_nb4o"/></radialGradient><radialGradient id="iPJVeRT" cx="0" cy="0" r="1" gradientTransform="rotate(67.546 -9.82 12.19)scale(.82843)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="u61ql_uag"/><stop offset="1" class="x_wj4vl5i"/></radialGradient><radialGradient id="i9ZTklb" cx="0" cy="0" r="1" gradientTransform="rotate(38.794 -1.108 .325)scale(1.30308)" gradientUnits="userSpaceOnUse"><stop class="stug43bab"/><stop offset="1" class="kmwt4ebda"/></radialGradient><radialGradient id="iIk0eOt" cx="0" cy="0" r="1" gradientTransform="matrix(2.74585 1.47356 -.61307 1.1424 13.192 12.312)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="p_drcebab"/><stop offset="1" class="tdgu1u54k"/></radialGradient><radialGradient id="ibBC50I" cx="0" cy="0" r="1" gradientTransform="rotate(-93.983 14.305 6.154)scale(4.67879 2.38208)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="gjropwo4q"/><stop offset="1" class="agepe-_9u"/></radialGradient><radialGradient id="iNWrYYc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.13011 -2.47192 .76781 -.35103 9.97 20.258)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eox5rpbuq"/><stop offset="1" class="g1mnylbkn"/></radialGradient><radialGradient id="iMzsorc" cx="0" cy="0" r="1" gradientTransform="rotate(140.247 3.481 7.695)scale(2.96815 2.79943)" gradientUnits="userSpaceOnUse"><stop class="k0aq2sbpu"/><stop offset="1" class="a3709fbcn"/></radialGradient><radialGradient id="iV8zCkc" cx="0" cy="0" r="1" gradientTransform="rotate(-80.488 15.812 5.366)scale(2.49859 1.02958)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="vobictbgt"/><stop offset="1" class="f97z0ccja"/></radialGradient><radialGradient id="iSC76Cc" cx="0" cy="0" r="1" gradientTransform="matrix(.3461 1.95797 -2.55208 .45113 8.382 9.943)" gradientUnits="userSpaceOnUse"><stop class="mxu7pl5fn"/><stop offset=".902" class="jtnx86cjw"/></radialGradient><radialGradient id="iskAstc" cx="0" cy="0" r="1" gradientTransform="matrix(1.0651 -.48413 .5911 1.30043 10.582 7.951)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="imfQs9c" cx="0" cy="0" r="1" gradientTransform="matrix(.52358 -.19365 .19365 .52358 10.82 7.865)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="iuwl5pe" cx="0" cy="0" r="1" gradientTransform="matrix(-.45962 0 0 -.43966 6.857 7.763)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="im1uaUb" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 4.212 4.872)scale(3.06459 4.1019)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="m45oyzb-o"/></radialGradient><radialGradient id="iHRMued" cx="0" cy="0" r="1" gradientTransform="rotate(152.124 3.862 5.115)scale(1.02129 .86649)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="iwz0D7x" cx="0" cy="0" r="1" gradientTransform="matrix(.35812 -1.73095 2.19626 .45438 7.92 10.435)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="iD3pv8c" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.18391 -5.05691 0 8.742 7.326)" gradientUnits="userSpaceOnUse"><stop offset=".593" class="ajxs5ri3z"/><stop offset="1" class="x05md6_2b"/></radialGradient><radialGradient id="iKXWotc" cx="0" cy="0" r="1" gradientTransform="rotate(164.542 4.002 4.74)scale(2.40746 4.1449)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="iwDTO4V" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.49243 .60434 0 9.838 7.354)" gradientUnits="userSpaceOnUse"><stop class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="iY2LBlb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.58196 .66696 0 8.033 7.391)" gradientUnits="userSpaceOnUse"><stop class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="ioi9MXc" cx="0" cy="0" r="1" gradientTransform="matrix(-.57637 0 0 -1.89744 11.034 7.99)" gradientUnits="userSpaceOnUse"><stop class="f902gfhfn"/><stop offset="1" class="jh40i5bvl"/></radialGradient><radialGradient id="iaBPBKb" cx="0" cy="0" r="1" gradientTransform="matrix(-.29845 -1.04827 .59983 -.17078 9.19 8.302)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="iC7IgmQ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .34717 -.55221 0 9.787 7.508)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i5qKKrd" cx="0" cy="0" r="1" gradientTransform="matrix(-.09916 -.12778 .17592 -.13652 9.69 7.543)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iJF4G6d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .34717 -.55222 0 7.92 7.508)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="idFE0Eb" cx="0" cy="0" r="1" gradientTransform="matrix(-.0033 -.21124 .25392 -.00398 7.797 7.601)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ib3YCxe" cx="0" cy="0" r="1" gradientTransform="rotate(129.554 2.718 4.206)scale(2.29767 1.00208)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="esh4v5qtq"/><stop offset=".911" class="nria2ku7r"/></radialGradient><radialGradient id="imtQJic" cx="0" cy="0" r="1" gradientTransform="rotate(144.458 3.011 3.734)scale(1.63171 .80642)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="dpv-wxbjb"/><stop offset="1" class="abu2lcc5n"/><stop offset="1" class="sxoxd_kke"/></radialGradient><radialGradient id="ig9QWyb" cx="0" cy="0" r="1" gradientTransform="rotate(115.63 3.461 5.17)scale(2.16187 3.06949)" gradientUnits="userSpaceOnUse"><stop offset=".627" class="crfaaqblp"/><stop offset="1" class="ehjghj3fe"/></radialGradient><radialGradient id="ickXoMd" cx="0" cy="0" r="1" gradientTransform="rotate(105.909 3.144 6.158)scale(1.47203 3.08491)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="z-gx2rb2w"/><stop offset="1" class="gbpc14bxe"/></radialGradient><radialGradient id="i0Bb87e" cx="0" cy="0" r="1" gradientTransform="rotate(-117.848 6.852 .8)scale(3.12997 2.798)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="s3t3owbgt"/><stop offset="1" class="yehxt3bls"/></radialGradient><radialGradient id="iBLDj1d" cx="0" cy="0" r="1" gradientTransform="rotate(28.301 -6.428 51.262)scale(1.36484 1.93323)" gradientUnits="userSpaceOnUse"><stop offset=".616" class="w3-vy4c8j"/><stop offset="1" class="w72oynbwi"/></radialGradient><radialGradient id="iK0QlPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.90696 -1.14888 0 19.943 8.633)" gradientUnits="userSpaceOnUse"><stop class="lcrdwk1fj"/><stop offset="1" class="denqa3bda"/></radialGradient><radialGradient id="icbonOc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.38389 -2.48325 0 21.899 8.673)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="ag6fa4z4y"/><stop offset="1" class="qir_1cb0f"/></radialGradient><radialGradient id="iLojLUb" cx="0" cy="0" r="1" gradientTransform="rotate(127.617 7.956 8.82)scale(.86983 .84457)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="ha2cq84sa"/><stop offset="1" class="p4wkjrbae"/></radialGradient><radialGradient id="imlZbfb" cx="0" cy="0" r="1" gradientTransform="rotate(100.537 7.175 11.761)scale(1.09412 1.13932)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="tgqxysbgm"/><stop offset="1" class="p1xq25bjq"/></radialGradient><radialGradient id="i8h1Gib" cx="0" cy="0" r="1" gradientTransform="matrix(.4688 .90458 -1.7232 .89305 20.471 4.698)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="esx41hbqq"/><stop offset=".921" class="v9rq5jjti"/></radialGradient><radialGradient id="iDe6Tgc" cx="0" cy="0" r="1" gradientTransform="matrix(-.47337 .51641 -.72168 -.66153 24.251 5.305)" gradientUnits="userSpaceOnUse"><stop class="duwob45dr"/><stop offset="1" class="v61l3jbat"/></radialGradient><radialGradient id="iel7ugc" cx="0" cy="0" r="1" gradientTransform="matrix(-.78892 .22952 -.4994 -1.7166 25.112 7.4)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="hottnizrg"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="iIeJiCc" cx="0" cy="0" r="1" gradientTransform="rotate(-133.315 14.469 .117)scale(1.99498 2.86503)" gradientUnits="userSpaceOnUse"><stop class="yqk-2gbyp"/><stop offset="1" class="oaxszm67z"/></radialGradient><radialGradient id="if2FRtd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0036 -.5881 .19282 -.00118 20.741 5.766)" gradientUnits="userSpaceOnUse"><stop offset=".295" class="sufhn4bec"/><stop offset="1" class="kpf8h5ohf"/></radialGradient><radialGradient id="iVkHbMe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04689 2.23436 -1.0009 -.46896 20.586 28.114)" gradientUnits="userSpaceOnUse"><stop class="i7j8_4zgt"/><stop offset="1" class="g4nv9obue"/></radialGradient><radialGradient id="ipfucwb" cx="0" cy="0" r="1" gradientTransform="rotate(51.34 -20.062 34.625)scale(1.30063 3.1796)" gradientUnits="userSpaceOnUse"><stop offset=".522" class="enwi01lgk"/><stop offset="1" class="mta_69bbu"/></radialGradient><radialGradient id="i4ktv5d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3576 -2.25 .95212 -.57449 29.248 29.864)" gradientUnits="userSpaceOnUse"><stop class="kuw77jfnz"/><stop offset="1" class="boon_rjzq"/></radialGradient><radialGradient id="icEReie" cx="0" cy="0" r="1" gradientTransform="matrix(-.81249 1.26563 -2.71996 -1.74612 28.54 28.41)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="hi3bu5i6r"/><stop offset="1" class="atfd_nb4o"/></radialGradient><radialGradient id="icbe3dU" cx="0" cy="0" r="1" gradientTransform="rotate(67.546 -3.297 21.944)scale(.82843)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="u61ql_uag"/><stop offset="1" class="x_wj4vl5i"/></radialGradient><radialGradient id="iO6yMIb" cx="0" cy="0" r="1" gradientTransform="matrix(2.74585 1.47356 -.61307 1.1424 26.237 12.312)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="p_drcebab"/><stop offset="1" class="tdgu1u54k"/></radialGradient><radialGradient id="ir1bPQb" cx="0" cy="0" r="1" gradientTransform="rotate(-93.983 20.828 .07)scale(4.67879 2.38208)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="gjropwo4q"/><stop offset="1" class="agepe-_9u"/></radialGradient><radialGradient id="iL5nSDu" cx="0" cy="0" r="1" gradientTransform="matrix(-1.13011 -2.47192 .76781 -.35103 23.016 20.258)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eox5rpbuq"/><stop offset="1" class="g1mnylbkn"/></radialGradient><radialGradient id="iqv3jpN" cx="0" cy="0" r="1" gradientTransform="rotate(140.247 10.004 10.054)scale(2.96815 2.79943)" gradientUnits="userSpaceOnUse"><stop class="k0aq2sbpu"/><stop offset="1" class="a3709fbcn"/></radialGradient><radialGradient id="iJNOPRd" cx="0" cy="0" r="1" gradientTransform="rotate(-80.488 22.334 -2.34)scale(2.49859 1.02958)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="vobictbgt"/><stop offset="1" class="f97z0ccja"/></radialGradient><radialGradient id="iUPm7db" cx="0" cy="0" r="1" gradientTransform="matrix(.3461 1.95797 -2.55208 .45113 21.427 9.943)" gradientUnits="userSpaceOnUse"><stop class="mxu7pl5fn"/><stop offset=".902" class="jtnx86cjw"/></radialGradient><radialGradient id="iHcpPbd" cx="0" cy="0" r="1" gradientTransform="matrix(1.0651 -.48413 .5911 1.30043 23.628 7.951)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="iPfuZWb" cx="0" cy="0" r="1" gradientTransform="matrix(.52358 -.19365 .19365 .52358 23.864 7.865)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="iMLqlYb" cx="0" cy="0" r="1" gradientTransform="matrix(-.45962 0 0 -.43966 19.902 7.763)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="inbfJoe" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 10.735 6.304)scale(3.06459 4.1019)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="m45oyzb-o"/></radialGradient><radialGradient id="icVD0Sb" cx="0" cy="0" r="1" gradientTransform="rotate(152.124 10.384 6.734)scale(1.02129 .86649)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="inbsFvc" cx="0" cy="0" r="1" gradientTransform="matrix(.35812 -1.73095 2.19626 .45438 20.965 10.435)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="inzblri" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.18391 -5.05691 0 21.787 7.326)" gradientUnits="userSpaceOnUse"><stop offset=".593" class="ajxs5ri3z"/><stop offset="1" class="x05md6_2b"/></radialGradient><radialGradient id="ievpYYb" cx="0" cy="0" r="1" gradientTransform="rotate(164.542 10.524 5.625)scale(2.40746 4.1449)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="i8stJMd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.49243 .60434 0 22.884 7.354)" gradientUnits="userSpaceOnUse"><stop class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="i7G4hsc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.58196 .66696 0 21.078 7.391)" gradientUnits="userSpaceOnUse"><stop class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="iuiZb4c" cx="0" cy="0" r="1" gradientTransform="matrix(-.57637 0 0 -1.89744 24.08 7.99)" gradientUnits="userSpaceOnUse"><stop class="f902gfhfn"/><stop offset="1" class="jh40i5bvl"/></radialGradient><radialGradient id="iJo7Hle" cx="0" cy="0" r="1" gradientTransform="matrix(-.29845 -1.04827 .59983 -.17078 22.235 8.302)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="i7TEoXj" cx="0" cy="0" r="1" gradientTransform="matrix(0 .34717 -.55221 0 22.833 7.508)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i4eVi3V" cx="0" cy="0" r="1" gradientTransform="matrix(-.09916 -.12778 .17592 -.13652 22.736 7.543)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ivBn0Wc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .34717 -.55222 0 20.965 7.508)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ig2qPsP" cx="0" cy="0" r="1" gradientTransform="matrix(-.0033 -.21124 .25392 -.00398 20.843 7.601)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ik3yfoe" cx="0" cy="0" r="1" gradientTransform="rotate(129.554 9.24 7.278)scale(2.29767 1.00208)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="esh4v5qtq"/><stop offset=".911" class="nria2ku7r"/></radialGradient><radialGradient id="ioQALKj" cx="0" cy="0" r="1" gradientTransform="rotate(144.458 9.534 5.825)scale(1.63171 .80642)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="dpv-wxbjb"/><stop offset="1" class="abu2lcc5n"/><stop offset="1" class="sxoxd_kke"/></radialGradient><radialGradient id="ivqMAUc" cx="0" cy="0" r="1" gradientTransform="rotate(115.63 9.984 9.276)scale(2.16187 3.06949)" gradientUnits="userSpaceOnUse"><stop offset=".627" class="crfaaqblp"/><stop offset="1" class="ehjghj3fe"/></radialGradient><radialGradient id="i8Ypknt" cx="0" cy="0" r="1" gradientTransform="rotate(105.909 9.666 11.081)scale(1.47203 3.08491)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="z-gx2rb2w"/><stop offset="1" class="gbpc14bxe"/></radialGradient><radialGradient id="iESlhde" cx="0" cy="0" r="1" gradientTransform="rotate(-117.848 13.375 -3.131)scale(3.12997 2.798)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="s3t3owbgt"/><stop offset="1" class="yehxt3bls"/></radialGradient><filter id="ip8hc9c" width="6.676" height="6.676" x="5.641" y="3.864" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.537255 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/></filter><filter id="iipWane" width="3.191" height="11.45" x="5.815" y="18.583" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.717647 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/></filter><filter id="idyyUMc" width="7.861" height="11.169" x="8.342" y="18.864" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.901961 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/></filter><filter id="iSaWYcd" width="5.896" height="7.11" x="2.751" y="10.156" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.541176 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.541176 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_704" result="effect2_innerShadow_4002_704"/></filter><filter id="iWyc8AV" width="5.996" height="7.245" x="9.267" y="10.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.588235 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.588235 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_704" result="effect2_innerShadow_4002_704"/></filter><filter id="ixVolNd" width="8.989" height="10.131" x="4.665" y="9.943" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.196078 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.32549 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_704" result="effect2_innerShadow_4002_704"/></filter><filter id="imMAkyd" width="1.477" height="1.377" x="6.16" y="7.075" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.501961 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/></filter><filter id="i221qon" width="1.377" height="1.627" x="10.231" y="6.825" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/></filter><filter id="i8J138q" width="1.919" height="1.919" x="9.96" y="6.804" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_704" stdDeviation=".25"/></filter><filter id="irOg9ic" width="1.419" height="1.419" x="6.147" y="7.054" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_704" stdDeviation=".125"/></filter><filter id="idXk0Kd" width="4.361" height="5.054" x="6.673" y="5.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/></filter><filter id="ixrDvNb" width="1.803" height="2.148" x="7.883" y="7.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_704" stdDeviation=".25"/></filter><filter id="iJpHVRc" width=".903" height="1.248" x="8.402" y="7.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_704" stdDeviation=".025"/></filter><filter id="i0ntGnZ" width="1.813" height=".882" x="7.947" y="8.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_704" stdDeviation=".05"/></filter><filter id="irBItmd" width="1.399" height=".55" x="9.142" y="7.162" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/></filter><filter id="iP8x8Sd" width="1.399" height=".55" x="7.166" y="7.162" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/></filter><filter id="iDyTeee" width="1.164" height=".581" x="7.224" y="6.439" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/></filter><filter id="i0Ploed" width="1.164" height=".581" x="9.542" y="6.439" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/></filter><filter id="iSheDGd" width=".451" height=".412" x="9.416" y="7.262" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_704" stdDeviation=".05"/></filter><filter id="iIjCWFd" width=".61" height=".62" x="9.718" y="7.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_704" stdDeviation=".1"/></filter><filter id="iWE4And" width=".651" height=".674" x="7.817" y="7.21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_704" stdDeviation=".1"/></filter><filter id="ibmkzNe" width=".505" height=".416" x="7.551" y="7.259" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_704" stdDeviation=".05"/></filter><filter id="ixSYCyc" width="1.011" height=".462" x="9.534" y="6.584" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_704" stdDeviation=".05"/></filter><filter id="iqSDDQd" width="1.011" height=".462" x="7.201" y="6.584" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_704" stdDeviation=".05"/></filter><filter id="iCaaxVM" width="1.991" height="2.089" x="6.054" y="4.721" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_704" stdDeviation=".125"/></filter><filter id="ie5qAEb" width="3.901" height="2.559" x="7.391" y="4.265" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_704" stdDeviation=".075"/></filter><filter id="irnW0Zd" width=".833" height="1.332" x="7.317" y="4.664" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_704" stdDeviation=".125"/></filter><filter id="i1tcrjk" width="1.73" height="2.911" x="6.683" y="1.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_704" result="effect2_innerShadow_4002_704"/></filter><filter id="iQXACic" width="1.73" height="2.911" x="9.394" y="1.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_704" result="effect2_innerShadow_4002_704"/></filter><filter id="ig4Ewyc" width="4.792" height="2.36" x="6.658" y="3.749" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.180392 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.219608 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_704" result="effect2_innerShadow_4002_704"/></filter><filter id="iuzYrac" width="6.676" height="6.676" x="18.686" y="3.864" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.537255 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/></filter><filter id="i4DcaJc" width="3.191" height="11.45" x="18.86" y="18.583" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.717647 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/></filter><filter id="itPrmEc" width="7.861" height="11.169" x="21.388" y="18.864" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.901961 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/></filter><filter id="iJ1Hbrb" width="5.896" height="7.11" x="15.796" y="10.156" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.541176 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.541176 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_704" result="effect2_innerShadow_4002_704"/></filter><filter id="iPBY1ir" width="5.996" height="7.245" x="22.312" y="10.021" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.588235 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.588235 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_704" result="effect2_innerShadow_4002_704"/></filter><filter id="i5gc63c" width="8.989" height="10.131" x="17.71" y="9.943" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.196078 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.32549 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_704" result="effect2_innerShadow_4002_704"/></filter><filter id="iYXEFDY" width="1.477" height="1.377" x="19.205" y="7.075" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.501961 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/></filter><filter id="iqOKgdb" width="1.377" height="1.627" x="23.276" y="6.825" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/></filter><filter id="iKDBAMd" width="1.919" height="1.919" x="23.005" y="6.804" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_704" stdDeviation=".25"/></filter><filter id="iBnEErc" width="1.419" height="1.419" x="19.192" y="7.054" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_704" stdDeviation=".125"/></filter><filter id="i4hs7BN" width="4.361" height="5.054" x="19.718" y="5.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/></filter><filter id="iwo78eb" width="1.803" height="2.148" x="20.928" y="7.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_704" stdDeviation=".25"/></filter><filter id="iFCXq3c" width=".903" height="1.248" x="21.447" y="7.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_704" stdDeviation=".025"/></filter><filter id="ir90mbe" width="1.813" height=".882" x="20.992" y="8.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_704" stdDeviation=".05"/></filter><filter id="i2BwWze" width="1.399" height=".55" x="22.188" y="7.162" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/></filter><filter id="iAaRJPe" width="1.399" height=".55" x="20.212" y="7.162" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/></filter><filter id="ibbaR7d" width="1.164" height=".581" x="20.269" y="6.439" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/></filter><filter id="iepBDWb" width="1.164" height=".581" x="22.587" y="6.439" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/></filter><filter id="il9iS7c" width=".451" height=".412" x="22.461" y="7.262" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_704" stdDeviation=".05"/></filter><filter id="i4RNved" width=".61" height=".62" x="22.764" y="7.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_704" stdDeviation=".1"/></filter><filter id="ilLPxlb" width=".651" height=".674" x="20.862" y="7.21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_704" stdDeviation=".1"/></filter><filter id="imL1DQe" width=".505" height=".416" x="20.596" y="7.259" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_704" stdDeviation=".05"/></filter><filter id="iv3mCKd" width="1.011" height=".462" x="22.579" y="6.584" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_704" stdDeviation=".05"/></filter><filter id="ijGR7fc" width="1.011" height=".462" x="20.246" y="6.584" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_704" stdDeviation=".05"/></filter><filter id="iWG5fDd" width="1.991" height="2.089" x="19.099" y="4.721" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_704" stdDeviation=".125"/></filter><filter id="iM0o9Pd" width="3.901" height="2.559" x="20.436" y="4.265" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_704" stdDeviation=".075"/></filter><filter id="iBH0ccV" width=".833" height="1.332" x="20.362" y="4.664" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_704" stdDeviation=".125"/></filter><filter id="idcHqxd" width="1.73" height="2.911" x="19.728" y="1.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_704" result="effect2_innerShadow_4002_704"/></filter><filter id="iboPF7b" width="1.73" height="2.911" x="22.439" y="1.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_704" result="effect2_innerShadow_4002_704"/></filter><filter id="i4C7OJe" width="4.792" height="2.36" x="19.703" y="3.749" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.34902 0 0 0 0 0.180392 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_704"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.219608 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_704" result="effect2_innerShadow_4002_704"/></filter><linearGradient id="ik3t6MU" x1="10.862" x2="7.763" y1="4.788" y2="10.54" gradientUnits="userSpaceOnUse"><stop class="yr1vjkbzu"/><stop offset="1" class="btu9i2bec"/></linearGradient><linearGradient id="iBVZi5W" x1="5.915" x2="7.807" y1="24.13" y2="24.317" gradientUnits="userSpaceOnUse"><stop class="ffo_sl6yt"/><stop offset="1" class="c9hzilbuh"/></linearGradient><linearGradient id="iuAvzJc" x1="5.807" x2="6.354" y1="24.817" y2="24.817" gradientUnits="userSpaceOnUse"><stop class="iwqqxcc-f"/><stop offset="1" class="ws-68yb9o"/></linearGradient><linearGradient id="i2rMUdb" x1="5.747" x2="6.353" y1="18.475" y2="18.461" gradientUnits="userSpaceOnUse"><stop offset=".262" class="mlh1k8r8i"/><stop offset="1" class="tigrkbwnp"/></linearGradient><linearGradient id="iE4LU4c" x1="6.16" x2="7.426" y1="7.8" y2="7.8" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="iWl6v5B" x1="8.854" x2="8.854" y1="8.635" y2="7.488" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="iSZbj7K" x1="8.406" x2="8.772" y1="8.309" y2="8.354" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="ior0YOe" x1="8.854" x2="8.854" y1="8.675" y2="8.413" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="ivSfdKc" x1="8.542" x2="8.736" y1="9.307" y2="8.934" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="ihKhuGc" x1="10.12" x2="9.986" y1="7.531" y2="7.613" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ixiJUZp" x1="8.238" x2="8.104" y1="7.531" y2="7.613" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iLLqWyc" x1="7.617" x2="7.85" y1="5.111" y2="5.656" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient><linearGradient id="ivEnbde" x1="10.697" x2="7.198" y1="5.208" y2="5.395" gradientUnits="userSpaceOnUse"><stop class="ak32k0b7k"/><stop offset="1" class="cgzrukeil"/></linearGradient><linearGradient id="iVfUilb" x1="23.907" x2="20.808" y1="4.788" y2="10.54" gradientUnits="userSpaceOnUse"><stop class="yr1vjkbzu"/><stop offset="1" class="btu9i2bec"/></linearGradient><linearGradient id="iZzktmc" x1="18.96" x2="20.852" y1="24.13" y2="24.317" gradientUnits="userSpaceOnUse"><stop class="ffo_sl6yt"/><stop offset="1" class="c9hzilbuh"/></linearGradient><linearGradient id="iJGUtYb" x1="18.852" x2="19.399" y1="24.817" y2="24.817" gradientUnits="userSpaceOnUse"><stop class="iwqqxcc-f"/><stop offset="1" class="ws-68yb9o"/></linearGradient><linearGradient id="iToCvPe" x1="18.792" x2="19.398" y1="18.475" y2="18.461" gradientUnits="userSpaceOnUse"><stop offset=".262" class="mlh1k8r8i"/><stop offset="1" class="tigrkbwnp"/></linearGradient><linearGradient id="iAzZe8c" x1="19.205" x2="20.471" y1="7.8" y2="7.8" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="i41pIPb" x1="21.899" x2="21.899" y1="8.635" y2="7.488" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="iEBPGae" x1="21.451" x2="21.817" y1="8.309" y2="8.354" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="iwIiTFd" x1="21.899" x2="21.899" y1="8.675" y2="8.413" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="i4DGEit" x1="21.587" x2="21.781" y1="9.307" y2="8.934" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="i5O7d1b" x1="23.165" x2="23.031" y1="7.531" y2="7.613" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="irw6aRc" x1="21.283" x2="21.149" y1="7.531" y2="7.613" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i9gGMSc" x1="20.662" x2="20.895" y1="5.111" y2="5.656" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient><linearGradient id="ipMYBOe" x1="23.743" x2="20.243" y1="5.208" y2="5.395" gradientUnits="userSpaceOnUse"><stop class="ak32k0b7k"/><stop offset="1" class="cgzrukeil"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-with-bunny-ears" /></template>
<style>
.a3673_uqf {
  fill: var(--svg-color--bd4f26, #BD4F26);
  fill-rule: evenodd;
  d: path("m10.45 6.807l-.058.098za.115.115 0 0 1-.118.197l-.002-.002l-.01-.005l-.039-.02a1 1 0 0 0-.146-.057a1 1 0 0 0-.459-.04a.115.115 0 1 1-.04-.226a1.2 1.2 0 0 1 .569.047a1.4 1.4 0 0 1 .225.094l.014.008l.004.002z");
}

.a3709fbcn {
  stop-color: var(--svg-color--6f597b, #6F597B);
  stop-opacity: 0;
}

.a41cmg3ue {
  fill-rule: evenodd;
  d: path("M22.414 10.716a.8.8 0 0 0 .308 1.088l3.527 1.978a.2.2 0 0 1 .034.325l-1.9 1.763a.8.8 0 1 0 1.068 1.19l1.973-1.72c.93-.82.856-2.148-.347-2.917l-4.252-2.348c-.386-.216-.195.255-.411.64");
}

.a9dfe182j {
  stop-color: var(--svg-color--d4993e, #D4993E);
}

.a9f4hxbhf {
  d: path("M28.675 28.192h-2.142l.142.307a2.64 2.64 0 0 0 2.397 1.534c.122 0 .207-.12.166-.234z");
}

.abu2lcc5n {
  stop-color: var(--svg-color--ffe134, #FFE134);
  stop-opacity: 0;
}

.aepf4rbzo {
  d: path("M24.093 5.75c.019.097-.101.145-.167.071c-.453-.513-1.132-1.01-2.022-1.01c-.84 0-1.554.532-2.033 1.063c-.065.072-.183.026-.166-.07a2.231 2.231 0 0 1 4.388-.053");
}

.ag6fa4z4y {
  stop-color: var(--svg-color--e26b25, #E26B25);
}

.agepe-_9u {
  stop-color: var(--svg-color--472263, #472263);
  stop-opacity: 0;
}

.ajxs5ri3z {
  stop-color: var(--svg-color--f3943b, #F3943B);
  stop-opacity: 0;
}

.ak32k0b7k {
  stop-color: var(--svg-color--695d73, #695D73);
}

.aoqd5fdgs {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M9.76 7.384c.027.037-.03.081-.094.13c-.065.048-.113.082-.14.045c-.027-.036.003-.105.068-.153c.064-.048.139-.058.166-.022");
}

.atfd_nb4o {
  stop-color: var(--svg-color--4c266b, #4C266B);
}

.aupi9ybyt {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M8.365 7.52c-.113-.2-.286-.358-.658-.358a.7.7 0 0 0-.459.158c-.115.093-.1.212-.01.256l.238.136c.279-.09.587-.102.89-.192");
}

.azv0v7pdh {
  fill: var(--svg-color--000, #000);
  d: path("M21.183 7.685a.22.22 0 0 0-.219-.218a.218.218 0 0 0-.194.32h.387a.2.2 0 0 0 .026-.102");
}

.b3w1zebtb {
  d: path("M6.76 5.19c.265-.237.648-.24.864-.201l.172.552a.34.34 0 0 0-.29.1c-.196.54-.866.837-1.177.919c-.065-.639-.029-.961.43-1.37");
}

.b585cfbmk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M20.662 4.964c.01.104.1.495.233.731");
}

.boon_rjzq {
  stop-color: var(--svg-color--4c2d62, #4C2D62);
}

.btdzh5v7s {
  fill-rule: evenodd;
  d: path("M11.928 8.366a1.4 1.4 0 0 0 .024-1.17h.002a1.4 1.4 0 0 0-.12-.218v-.002a1.4 1.4 0 0 1-.226-.758v-.004c0-.78-.632-1.412-1.412-1.412a.23.23 0 0 1-.195-.1a1.415 1.415 0 0 0-2.295 0a.24.24 0 0 1-.195.1h-.036a1.41 1.41 0 0 0-1.376 1.412v.004c0 .269-.077.533-.225.758v.002a1.41 1.41 0 0 0-.095 1.388a.22.22 0 0 1 0 .195a1.375 1.375 0 0 0 1.239 1.979h3.672a1.375 1.375 0 0 0 1.238-1.979a.22.22 0 0 1 0-.195M6.682 7.223h-.005L7.19 8.23c.053 1.199.52 0 1.664 0s1.641 1.335 1.694.135l.486-1.368c-.023-.532-.409-.57-.486-.57H9.17a1.65 1.65 0 0 1-1.365-.716a.113.113 0 0 0-.197.022l-.035.083a1 1 0 0 1-.51.528l-.021.009l-.022.009c-.1.052-.338.21-.347.615l.005.131z");
}

.btu9i2bec {
  stop-color: var(--svg-color--e37923, #E37923);
}

.bu-vy8bim {
  d: path("m18.96 18.583l3.092 1.156l-1.158 8.71a1.83 1.83 0 0 1-1.812 1.584a.12.12 0 0 1-.122-.122z");
}

.bz-3bacdo {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M21.899 9.01c-.223 0-.432-.055-.608-.148c-.06-.032-.125.038-.087.093a.827.827 0 0 0 1.39 0c.038-.058-.027-.125-.087-.093a1.3 1.3 0 0 1-.608.147");
}

.c9hzilbuh {
  stop-color: var(--svg-color--ffd142, #FFD142);
}

.cbzdjcf_x {
  d: path("M19.805 5.19c.265-.237.649-.24.864-.201l.172.552a.34.34 0 0 0-.29.1c-.196.54-.866.837-1.177.919c-.064-.639-.028-.961.43-1.37");
}

.cgzrukeil {
  stop-color: var(--svg-color--5a3e62, #5A3E62);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cmre8ebkt {
  fill: var(--svg-color--ec9534, #EC9534);
  d: path("m25.388 18.864l-2.75.933l4.037 8.702a2.64 2.64 0 0 0 2.398 1.534c.121 0 .206-.12.166-.234z");
}

.crfaaqblp {
  stop-color: var(--svg-color--f49523, #F49523);
  stop-opacity: 0;
}

.d2x5j-bsk {
  fill-rule: evenodd;
  d: path("M24.974 8.366a1.4 1.4 0 0 0 .024-1.17H25a1.4 1.4 0 0 0-.12-.218l-.002-.002a1.4 1.4 0 0 1-.225-.758v-.004c0-.78-.632-1.412-1.412-1.412a.23.23 0 0 1-.194-.1a1.415 1.415 0 0 0-2.296 0a.24.24 0 0 1-.195.1h-.036a1.41 1.41 0 0 0-1.375 1.412v.004c0 .269-.078.533-.226.758v.002a1.41 1.41 0 0 0-.095 1.388a.22.22 0 0 1 0 .195a1.375 1.375 0 0 0 1.239 1.979h3.672a1.375 1.375 0 0 0 1.239-1.979a.22.22 0 0 1 0-.195m-5.247-1.143h-.005l.513 1.008c.053 1.199.52 0 1.664 0s1.642 1.335 1.694.135l.486-1.368c-.023-.532-.409-.57-.486-.57h-1.378a1.65 1.65 0 0 1-1.364-.716a.113.113 0 0 0-.198.022l-.035.083a1 1 0 0 1-.509.528l-.022.009l-.022.009c-.1.052-.338.21-.347.615l.005.131z");
}

.d7pn-80kf {
  d: path("m5.915 18.583l3.092 1.156l-1.158 8.71a1.83 1.83 0 0 1-1.812 1.584a.12.12 0 0 1-.122-.122z");
}

.denqa3bda {
  stop-color: var(--svg-color--d77117, #D77117);
  stop-opacity: 0;
}

.dhdllmbnv {
  cx: 5.514px;
  cy: 16.61px;
  r: 0.766px;
}

.dmcaafdnb {
  d: path("M20.964 7.304a.382.382 0 0 0-.368.482h.738a.384.384 0 0 0-.37-.483");
}

.dpv-wxbjb {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
}

.dr0toebdy {
  fill: var(--svg-color--bd4f26, #BD4F26);
  d: path("m7.4 7.002l-.002.001a.115.115 0 0 1-.118-.196l.002-.002l.004-.002l.014-.008l.05-.025c.042-.02.102-.046.175-.069a1.2 1.2 0 0 1 .568-.047a.115.115 0 0 1-.04.226a1 1 0 0 0-.458.04a1 1 0 0 0-.186.077z");
}

.duwob45dr {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
}

.dzbxyhbei {
  d: path("M10.128 7.635a.36.36 0 0 0-.099-.198l-.11.122l.05.098z");
}

.e0lgwbeaw {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.ehjghj3fe {
  stop-color: var(--svg-color--f49523, #F49523);
}

.ehl3xubna {
  fill: var(--svg-color--bd4f26, #BD4F26);
  fill-rule: evenodd;
  d: path("m23.496 6.807l-.06.098za.115.115 0 0 1-.118.197l-.002-.002l-.049-.025a1 1 0 0 0-.146-.057a1 1 0 0 0-.459-.04a.115.115 0 1 1-.04-.226a1.2 1.2 0 0 1 .569.047a1.4 1.4 0 0 1 .239.102l.004.002z");
}

.el7d06s8x {
  d: path("M23.174 7.635a.36.36 0 0 0-.1-.198l-.11.122l.05.098z");
}

.enwi01lgk {
  stop-color: var(--svg-color--522e71, #522E71);
  stop-opacity: 0;
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.eox5rpbuq {
  stop-color: var(--svg-color--463049, #463049);
}

.esh4v5qtq {
  stop-color: var(--svg-color--ee971b, #EE971B);
  stop-opacity: 0;
}

.esx41hbqq {
  stop-color: var(--svg-color--cba140, #CBA140);
}

.ew1xuqo2l {
  d: path("M8.268 7.64c0-.123-.1-.205-.127-.23l-.124.12l.076.154z");
}

.f7r0_-hng {
  d: path("M23.965 8.223a.46.46 0 1 0 0-.92a.46.46 0 0 0 0 .92");
}

.f902gfhfn {
  stop-color: var(--svg-color--ffda39, #FFDA39);
}

.f97z0ccja {
  stop-color: var(--svg-color--5c4c68, #5C4C68);
  stop-opacity: 0;
}

.ffo_sl6yt {
  stop-color: var(--svg-color--e79f2e, #E79F2E);
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.fkdj3ejgt {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
}

.ft5dv1b6b {
  fill: none;
}

.fv9yutbaq {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.877 7.187c.28 0 .515.193.58.453a.117.117 0 0 1-.115.146h-.955a.098.098 0 0 1-.097-.116a.6.6 0 0 1 .587-.483");
}

.fvjsqgb0s {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.83 7.187a.6.6 0 0 0-.58.453a.117.117 0 0 0 .115.146h.955c.06 0 .11-.056.097-.116a.6.6 0 0 0-.586-.483");
}

.g-l8-0bhf {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M21.899 9.01c-.223 0-.432-.055-.608-.148c-.06-.032-.125.038-.087.093a.827.827 0 0 0 1.39 0c.038-.058-.027-.125-.087-.093a1.3 1.3 0 0 1-.608.147Z");
}

.g1mnylbkn {
  stop-color: var(--svg-color--463049, #463049);
  stop-opacity: 0;
}

.g4nv9obue {
  stop-color: var(--svg-color--44384d, #44384D);
}

.gbpc14bxe {
  stop-color: var(--svg-color--ffe337, #FFE337);
  stop-opacity: 0;
}

.ge3utjblo {
  fill: var(--svg-color--bd4f26, #BD4F26);
  d: path("m20.445 7.002l-.002.001a.115.115 0 0 1-.118-.196l.002-.002l.004-.002l.014-.008l.05-.025c.042-.02.102-.046.175-.069a1.2 1.2 0 0 1 .569-.047a.115.115 0 0 1-.04.226a1 1 0 0 0-.459.04a1 1 0 0 0-.186.077z");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghy9u737z {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.922 7.187c.28 0 .515.193.58.453a.117.117 0 0 1-.115.146h-.954a.1.1 0 0 1-.098-.116a.6.6 0 0 1 .587-.483");
}

.gjropwo4q {
  stop-color: var(--svg-color--472263, #472263);
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

.hgjbhwb5c {
  cx: 7.804px;
  cy: 7.467px;
  rx: 0.167px;
  ry: 0.084px;
}

.hi3bu5i6r {
  stop-color: var(--svg-color--4c266b, #4C266B);
  stop-opacity: 0;
}

.hottnizrg {
  stop-color: var(--svg-color--ffd336, #FFD336);
  stop-opacity: 0;
}

.hw6mgnbqq {
  fill: var(--svg-color--62476a, #62476A);
  d: path("M19.981 3.273c.222.71.522 1.166.645 1.305l.633-.242c-.013-.183-.096-.709-.325-1.356c-.285-.808-.578-1.09-.875-.996c-.21.086-.355.403-.078 1.29");
}

.i7j8_4zgt {
  stop-color: var(--svg-color--59436a, #59436A);
}

.iqag43gby {
  fill: var(--svg-color--62476a, #62476A);
  d: path("M23.817 3.273c-.222.71-.523 1.166-.645 1.305l-.633-.242c.013-.183.096-.709.324-1.356c.286-.808.579-1.09.875-.996c.211.086.356.403.079 1.29");
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.iwqqxcc-f {
  stop-color: var(--svg-color--d9a14c, #D9A14C);
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.j15z5b2ap {
  d: path("M23.965 8.452a.689.689 0 1 0 0-1.377a.689.689 0 0 0 0 1.377");
}

.j9y5m6c3t {
  d: path("M9.76 7.384c.027.037-.03.081-.094.13c-.065.048-.113.082-.14.045c-.027-.036.003-.105.068-.153c.064-.048.139-.058.166-.022");
}

.jc4qhqbtm {
  d: path("M5.915 12.814a2.872 2.872 0 0 1 5.744 0v3.804c0 .23.04.46.117.676l.628 1.748l-2.698 1.005l-.322-.653a.175.175 0 0 0-.33.054l-.084.626l-3.055-1.049z");
}

.jh40i5bvl {
  stop-color: var(--svg-color--ffda39, #FFDA39);
  stop-opacity: 0;
}

.jtnx86cjw {
  stop-color: var(--svg-color--ffc737, #FFC737);
}

.jur2mybyp {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M8.854 9.01c-.223 0-.432-.055-.608-.148c-.06-.032-.125.038-.087.093a.827.827 0 0 0 1.39 0c.038-.058-.027-.125-.087-.093a1.3 1.3 0 0 1-.608.147");
}

.k0aq2sbpu {
  stop-color: var(--svg-color--6f597b, #6F597B);
}

.k6opfnbix {
  d: path("M6.857 8.223a.46.46 0 1 0 0-.92a.46.46 0 0 0 0 .92");
}

.kmwt4ebda {
  stop-color: var(--svg-color--cf7d4f, #CF7D4F);
}

.kol252b8f {
  cx: 7.804px;
  cy: 7.467px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.167px;
  ry: 0.084px;
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.kpf8h5ohf {
  stop-color: var(--svg-color--db6009, #DB6009);
  stop-opacity: 0;
}

.kr_eiac3t {
  r: 0.766px;
}

.kuw77jfnz {
  stop-color: var(--svg-color--645a6f, #645A6F);
}

.l2kz2nbvy {
  d: path("M18.96 12.814a2.872 2.872 0 0 1 5.744 0v3.804c0 .23.04.46.117.676l.628 1.748l-2.698 1.005l-.322-.653a.175.175 0 0 0-.33.054l-.084.626l-3.055-1.049z");
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

.lqdkbomtg {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M22.805 7.384c.027.037-.03.081-.094.13c-.065.048-.113.082-.14.045c-.027-.036.003-.105.068-.153c.064-.048.139-.058.166-.022");
}

.lrux5gb2o {
  fill: var(--svg-color--ffc93a, #FFC93A);
  fill-rule: evenodd;
  d: path("M9.369 10.716a.8.8 0 0 0 .308 1.088l3.527 1.978a.2.2 0 0 1 .034.325l-1.9 1.763a.8.8 0 0 0 1.068 1.19l1.973-1.72c.93-.82.856-2.148-.347-2.917L9.78 10.075c-.386-.216-.195.255-.411.64");
}

.m45oyzb-o {
  stop-color: var(--svg-color--eb9235, #EB9235);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.mizm7xb4g {
  d: path("M6.677 7.223h.005l-.004-.114l-.005-.13c.009-.407.246-.564.347-.616l.022-.009l.022-.009a1 1 0 0 0 .509-.528l.035-.083a.113.113 0 0 1 .197-.022c.308.45.82.716 1.365.716h1.378c.077 0 .463.038.486.57l-.05 1.315c-.054 1.2-.99 2.005-2.133 2.005s-2.08-.806-2.133-2.005z");
}

.mlh1k8r8i {
  stop-color: var(--svg-color--656069, #656069);
}

.ms15tsqbf {
  fill-rule: evenodd;
  d: path("M9.369 10.716a.8.8 0 0 0 .308 1.088l3.527 1.978a.2.2 0 0 1 .034.325l-1.9 1.763a.8.8 0 0 0 1.068 1.19l1.973-1.72c.93-.82.856-2.148-.347-2.917L9.78 10.075c-.386-.216-.195.255-.411.64");
}

.mta_69bbu {
  stop-color: var(--svg-color--522e71, #522E71);
}

.mxu7pl5fn {
  stop-color: var(--svg-color--d77e03, #D77E03);
}

.mytlpjw-h {
  d: path("m7.645 10.179l.972 1.596a.25.25 0 0 0 .435-.004l.936-1.566a2.9 2.9 0 0 0-1.201-.262a2.9 2.9 0 0 0-1.142.236");
}

.n-2sfrb-v {
  d: path("M9.788 7.304a.382.382 0 0 1 .368.482H9.42a.383.383 0 0 1 .37-.483");
}

.n18jfcc-k {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M9.684 6.748a1.02 1.02 0 0 1 .71.147");
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.nria2ku7r {
  stop-color: var(--svg-color--d8772c, #D8772C);
}

.nso6vxtpf {
  fill: var(--svg-color--62476a, #62476A);
  d: path("M6.936 3.273c.222.71.522 1.166.645 1.305l.632-.242c-.013-.183-.096-.709-.324-1.356c-.285-.808-.578-1.09-.875-.996c-.21.086-.355.403-.078 1.29");
}

.nu-bxvbsr {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M9.342 7.52c.114-.2.287-.358.658-.358a.7.7 0 0 1 .46.158c.114.093.099.212.01.256l-.238.136c-.279-.09-.587-.102-.89-.192");
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

.p_drcebab {
  stop-color: var(--svg-color--ffdb40, #FFDB40);
}

.p-i_x_tkg {
  d: path("M10.92 8.223a.46.46 0 1 0 0-.92a.46.46 0 0 0 0 .92");
}

.p0kg-zbqi {
  d: path("M19.902 8.223a.46.46 0 1 0 0-.92a.46.46 0 0 0 0 .92");
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

.pf43v7bkm {
  fill: var(--svg-color--000, #000);
  d: path("M8.138 7.685a.22.22 0 0 0-.219-.218a.218.218 0 0 0-.194.32h.387a.2.2 0 0 0 .026-.102");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmp7oac6x {
  d: path("m8.69 7.609l-.227.727a.23.23 0 0 0 .222.3h.337c.158 0 .27-.153.223-.3l-.228-.727c-.048-.162-.276-.162-.327 0");
}

.pqggtpb7u {
  fill: var(--svg-color--000, #000);
  d: path("M22.615 7.685c0-.121.097-.218.219-.218a.218.218 0 0 1 .194.32h-.387a.2.2 0 0 1-.026-.102");
}

.psipoacfy {
  d: path("m20.69 10.179l.972 1.596a.25.25 0 0 0 .435-.004l.935-1.566a2.9 2.9 0 0 0-1.2-.262a2.9 2.9 0 0 0-1.142.236");
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.q1l1czbkr {
  d: path("M11.048 5.75c.018.097-.102.145-.167.071c-.453-.513-1.132-1.01-2.023-1.01c-.838 0-1.553.532-2.033 1.063c-.064.072-.182.026-.166-.07a2.231 2.231 0 0 1 4.389-.053");
}

.q6g7x-c0g {
  fill: var(--svg-color--ec9534, #EC9534);
  d: path("m12.342 18.864l-2.75.933L13.63 28.5a2.64 2.64 0 0 0 2.397 1.534c.122 0 .207-.12.167-.234z");
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qfk268bmk {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M8.854 9.01c-.223 0-.432-.055-.608-.148c-.06-.032-.125.038-.087.093a.827.827 0 0 0 1.39 0c.038-.058-.027-.125-.087-.093a1.3 1.3 0 0 1-.608.147Z");
}

.qir_1cb0f {
  stop-color: var(--svg-color--e26b25, #E26B25);
  stop-opacity: 0;
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

.r5g_3dbhv {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m8.686 7.668l-.293.727a.23.23 0 0 0 .223.3h.337a.23.23 0 0 0 .222-.3l-.227-.727c-.049-.161-.211-.161-.262 0");
}

.rdymgqtsv {
  cx: 18.559px;
  cy: 16.61px;
  r: 0.766px;
}

.ri_r8xb5e {
  fill: var(--svg-color--654470, #654470);
  d: path("M18.96 12.814a2.872 2.872 0 0 1 5.744 0v3.804c0 .23.04.46.117.676l.628 1.748l-2.698 1.005l-.322-.653a.175.175 0 0 0-.33.054l-.084.626l-3.055-1.049z");
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.rusiodlkr {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M23.965 8.223a.46.46 0 1 0 0-.92a.46.46 0 0 0 0 .92");
}

.rwhqt0bkw {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M21.107 6.748a1.02 1.02 0 0 0-.711.147");
}

.s3t3owbgt {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
  stop-opacity: 0;
}

.sgzpl9b9a {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M22.729 6.748c.138-.034.481-.017.71.147");
}

.sm9o9oxie {
  d: path("M19.894 8.452a.689.689 0 1 0 0-1.377a.689.689 0 0 0 0 1.377");
}

.sofeydi8k {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M8.061 6.748a1.02 1.02 0 0 0-.71.147");
}

.stug43bab {
  stop-color: var(--svg-color--ebb432, #EBB432);
}

.sufhn4bec {
  stop-color: var(--svg-color--db6009, #DB6009);
}

.sxoxd_kke {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
  stop-opacity: 0;
}

.t7ahgabts {
  fill: var(--svg-color--ffbc3b, #FFBC3B);
  fill-rule: evenodd;
  d: path("M21.44 10.716a.8.8 0 0 1-.307 1.088l-3.527 1.978a.2.2 0 0 0-.034.325l1.9 1.763a.8.8 0 1 1-1.069 1.19l-1.973-1.72c-.93-.82-.855-2.148.348-2.917l3.574-2.015a.8.8 0 0 1 1.089.308");
}

.tdgu1u54k {
  stop-color: var(--svg-color--ffdb40, #FFDB40);
  stop-opacity: 0;
}

.tep9ytb3r {
  cx: 20.849px;
  cy: 7.467px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.167px;
  ry: 0.084px;
}

.tgqxysbgm {
  stop-color: var(--svg-color--d76a18, #D76A18);
}

.tigrkbwnp {
  stop-color: var(--svg-color--47364e, #47364E);
  stop-opacity: 0;
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.u61ql_uag {
  stop-color: var(--svg-color--db8723, #DB8723);
}

.u6qsrbphj {
  d: path("M22.805 7.384c.027.037-.03.081-.094.13c-.065.048-.113.082-.14.045c-.027-.036.003-.105.068-.153c.064-.048.139-.058.166-.022");
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v3999ro-u {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M19.902 8.223a.46.46 0 1 0 0-.92a.46.46 0 0 0 0 .92");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v61l3jbat {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
  stop-opacity: 0;
}

.v95bqqdny {
  d: path("m7.883 28.192l-.034.257a1.83 1.83 0 0 1-1.812 1.584a.12.12 0 0 1-.122-.122v-1.719z");
}

.v9rq5jjti {
  stop-color: var(--svg-color--cba140, #CBA140);
  stop-opacity: 0;
}

.vh2gln4ru {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M22.388 7.52c.113-.2.286-.358.657-.358a.7.7 0 0 1 .46.158c.114.093.1.212.01.256l-.238.136c-.279-.09-.587-.102-.89-.192");
}

.vobictbgt {
  stop-color: var(--svg-color--5c4c68, #5C4C68);
}

.vsluyubzo {
  stop-color: var(--svg-color--f8a322, #F8A322);
  stop-opacity: 0;
}

.vx526acon {
  d: path("m21.735 7.609l-.227.727a.23.23 0 0 0 .223.3h.336c.158 0 .27-.153.223-.3l-.228-.727c-.048-.162-.276-.162-.327 0");
}

.vzavi8tmc {
  d: path("M7.92 7.304a.382.382 0 0 0-.369.482h.738a.385.385 0 0 0-.37-.483");
}

.vzb-or29m {
  d: path("M8.595 4.43c-.484-.108-1.004.408-1.054.588c.66 1.549 1.673 1.401 2.797 1.276c.673-.075.746.232.804.38c-.187-1.735-1.442-2-2.547-2.245");
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

.w80noibxf {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M6.857 8.223a.46.46 0 1 0 0-.92a.46.46 0 0 0 0 .92");
}

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.wkiuhjwwj {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.876 7.187a.6.6 0 0 0-.58.453a.117.117 0 0 0 .115.146h.954a.1.1 0 0 0 .098-.116a.6.6 0 0 0-.587-.483");
}

.wlbrcoiqt {
  fill: var(--svg-color--62476a, #62476A);
  d: path("M10.771 3.273c-.222.71-.522 1.166-.644 1.305l-.633-.242c.013-.183.096-.709.324-1.356c.285-.808.578-1.09.875-.996c.211.086.356.403.078 1.29");
}

.wo-g16f9e {
  d: path("M19.722 7.223h.005l-.004-.114l-.005-.13c.01-.407.246-.564.347-.616l.022-.009l.022-.009a1 1 0 0 0 .509-.528l.035-.083a.113.113 0 0 1 .198-.022c.307.45.82.716 1.364.716h1.378c.077 0 .463.038.486.57l-.05 1.315c-.053 1.2-.99 2.005-2.133 2.005s-2.08-.806-2.132-2.005z");
}

.wri7c1b3n {
  fill: var(--svg-color--ffc93a, #FFC93A);
  fill-rule: evenodd;
  d: path("M22.414 10.716a.8.8 0 0 0 .308 1.088l3.527 1.978a.2.2 0 0 1 .034.325l-1.9 1.763a.8.8 0 1 0 1.068 1.19l1.973-1.72c.93-.82.856-2.148-.347-2.917l-4.252-2.348c-.386-.216-.195.255-.411.64");
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.ws-68yb9o {
  stop-color: var(--svg-color--f6a928, #F6A928);
  stop-opacity: 0;
}

.wt8hn-lfq {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M10.92 8.223a.46.46 0 1 0 0-.92a.46.46 0 0 0 0 .92");
}

.wz37uxbol {
  d: path("M21.313 7.64c0-.123-.1-.205-.127-.23l-.124.12l.076.154z");
}

.x_wj4vl5i {
  stop-color: var(--svg-color--ce7557, #CE7557);
}

.x05md6_2b {
  stop-color: var(--svg-color--d97c39, #D97C39);
}

.x3yca2bds {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M7.617 4.964c.01.104.1.495.233.731");
}

.x5tf_bc4w {
  d: path("M6.849 8.452a.689.689 0 1 0 0-1.377a.689.689 0 0 0 0 1.377");
}

.xnn9y3bie {
  d: path("m20.928 28.192l-.034.257a1.83 1.83 0 0 1-1.812 1.584a.12.12 0 0 1-.122-.122v-1.719z");
}

.xqdsnxt8m {
  fill: var(--svg-color--000, #000);
  d: path("M9.57 7.685c0-.121.097-.218.218-.218a.218.218 0 0 1 .195.32h-.387a.2.2 0 0 1-.026-.102");
}

.y3kf9motm {
  cx: 20.849px;
  cy: 7.467px;
  rx: 0.167px;
  ry: 0.084px;
}

.y47tc3sih {
  d: path("M15.63 28.192h-2.142l.142.307a2.64 2.64 0 0 0 2.397 1.534c.122 0 .207-.12.167-.234z");
}

.y7n0ymbzx {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
  stop-opacity: 0;
}

.yaqk-qbgh {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m21.731 7.668l-.293.727a.23.23 0 0 0 .223.3h.337a.232.232 0 0 0 .223-.3l-.228-.727c-.049-.161-.211-.161-.262 0");
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

.yqzmhsbig {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M21.41 7.52c-.113-.2-.286-.358-.658-.358a.7.7 0 0 0-.459.158c-.115.093-.1.212-.01.256l.238.136c.279-.09.587-.102.89-.192");
}

.yr1vjkbzu {
  stop-color: var(--svg-color--ffd93c, #FFD93C);
}

.ys_en_m8z {
  fill: var(--svg-color--654470, #654470);
  d: path("M5.915 12.814a2.872 2.872 0 0 1 5.744 0v3.804c0 .23.04.46.117.676l.628 1.748l-2.698 1.005l-.322-.653a.175.175 0 0 0-.33.054l-.084.626l-3.055-1.049z");
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.z-gx2rb2w {
  stop-color: var(--svg-color--ffe337, #FFE337);
}

.z5d0by-ny {
  d: path("M22.834 7.304a.382.382 0 0 1 .367.482h-.737a.383.383 0 0 1 .37-.483");
}

.zhe_95bye {
  fill: var(--svg-color--ffbc3b, #FFBC3B);
  fill-rule: evenodd;
  d: path("M8.395 10.716a.8.8 0 0 1-.307 1.088L4.56 13.782a.2.2 0 0 0-.035.325l1.9 1.763a.8.8 0 1 1-1.068 1.19l-1.973-1.72c-.93-.82-.856-2.148.347-2.917l3.575-2.015a.8.8 0 0 1 1.088.308");
}

.zk7-lu68t {
  d: path("M21.64 4.43c-.484-.108-1.003.408-1.054.588c.66 1.549 1.673 1.401 2.798 1.276c.672-.075.745.232.803.38c-.187-1.735-1.442-2-2.546-2.245");
}

.zve07_b6e {
  d: path("M10.92 8.452a.688.688 0 1 0 0-1.377a.688.688 0 0 0 0 1.377");
}

</style>
