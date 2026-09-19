<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i4DOBbc)"><path fill="url(#iWLBAOb)" clip-rule="evenodd" class="q498y9b2p"/><path fill="url(#i5fupkb)" clip-rule="evenodd" class="q498y9b2p"/><path fill="url(#iHvAjwd)" clip-rule="evenodd" class="q498y9b2p"/><path fill="url(#i8Gqpod)" clip-rule="evenodd" class="q498y9b2p"/><path fill="url(#ii3ywvd)" clip-rule="evenodd" class="q498y9b2p"/><path fill="url(#ijlWuLd)" clip-rule="evenodd" class="q498y9b2p"/><path fill="url(#iRgT6ke)" clip-rule="evenodd" class="q498y9b2p"/><path fill="url(#ihmtiYb)" clip-rule="evenodd" class="q498y9b2p"/><path fill="url(#iMjXl0l)" clip-rule="evenodd" class="q498y9b2p"/><path fill="url(#ixDpPOd)" clip-rule="evenodd" class="q498y9b2p"/></g><path fill="url(#iV1Kr8b)" class="iopmamb4i"/><path fill="url(#iaTJTHb)" class="iopmamb4i"/><path fill="url(#iJCEzAd)" class="iopmamb4i"/><path fill="url(#iTk19tZ)" class="iopmamb4i"/><rect fill="url(#iBz1xre)" class="px7bzgweo"/><path class="qced8sf2z"/><path fill="url(#isMWwcb)" class="jf2e24bdx"/><path fill="url(#iNAcXVd)" class="jf2e24bdx"/><path clip-rule="evenodd" class="ipjmodbjb"/><path fill="url(#iKgyBNd)" clip-rule="evenodd" class="jko339btq"/><path fill="url(#ipJOdQy)" clip-rule="evenodd" class="jko339btq"/><path fill="url(#iIEGcgd)" clip-rule="evenodd" class="jko339btq"/><path clip-rule="evenodd" class="j2mxgnb6a"/><path fill="url(#iT0YOte)" clip-rule="evenodd" class="rsf68q_lb"/><path fill="url(#iR6Ec7c)" clip-rule="evenodd" class="rsf68q_lb"/><path fill="url(#ihB7LZb)" clip-rule="evenodd" class="rsf68q_lb"/><path clip-rule="evenodd" class="rnki6ubvc"/><path fill="url(#ikjvt9S)" clip-rule="evenodd" class="k4rw0xbwd"/><path fill="url(#iW8noib)" clip-rule="evenodd" class="k4rw0xbwd"/><path fill="url(#ivZ5mPj)" clip-rule="evenodd" class="k4rw0xbwd"/><g filter="url(#iSdi7pc)"><path clip-rule="evenodd" class="rsgza3yef"/><path fill="url(#inVnXQK)" clip-rule="evenodd" class="ilaikjfls"/><path fill="url(#iSNtizc)" clip-rule="evenodd" class="ilaikjfls"/><path fill="url(#i4krjdb)" clip-rule="evenodd" class="ilaikjfls"/></g><path fill="url(#iPniSWO)" class="xm2mt2alw"/><path fill="url(#iZUy5ib)" class="xm2mt2alw"/><path fill="url(#iO2S5kb)" class="d_d61_bgh"/><path fill="url(#idxuF1d)" class="d_d61_bgh"/><g filter="url(#ioD8qHb)"><path fill="url(#i7zc9zd)" class="z7b6rzlke"/><path fill="url(#iNI4rjd)" class="z7b6rzlke"/><path fill="url(#iWLFdzb)" class="z7b6rzlke"/><path fill="url(#im24ZMd)" class="z7b6rzlke"/></g><g filter="url(#i1410XJ)"><path fill="url(#iHxHQ1b)" class="mxguyeblr"/></g><g filter="url(#iq650fc)"><path fill="url(#iLWynuc)" class="xa4i0b44p"/></g><g filter="url(#iJdDXnc)"><path class="q8qkepb9e"/><path fill="url(#igDnJLc)" class="n0ojrlpxd"/></g><g filter="url(#iGzBcMd)"><path class="t1-486sdu"/><path fill="url(#iyBus5c)" class="x1cq4fb-p"/></g><g filter="url(#ihVoIbe)"><path fill="url(#iXVMnEd)" class="wr_32p5jm"/><path fill="url(#ibPrc3b)" class="wr_32p5jm"/><path fill="url(#iLbJoad)" class="wr_32p5jm"/><path fill="url(#irA3N9c)" class="wr_32p5jm"/><path fill="url(#imwEAre)" class="wr_32p5jm"/><path fill="url(#ioM0Ere)" class="wr_32p5jm"/><path fill="url(#ifHVtIw)" class="wr_32p5jm"/></g><path fill="url(#iKZ6UNb)" class="wr_32p5jm"/><g filter="url(#iOs22lb)"><path class="d1bo5fbgs"/></g><g filter="url(#ibioDpe)"><path fill="url(#i7soazd)" class="ynx1-lz2q"/><path fill="url(#iIOe3Oc)" class="ynx1-lz2q"/><path fill="url(#idNnype)" class="ynx1-lz2q"/><path fill="url(#iBRg2Ic)" class="ynx1-lz2q"/></g><path fill="url(#imz7UQb)" class="ynx1-lz2q"/><path fill="url(#iMJCMOd)" class="ynx1-lz2q"/><path stroke="url(#iiL951c)" class="d_iyr-bay"/><g filter="url(#ipBPqmd)"><path class="tbf9ru2pp"/></g><g filter="url(#iF9wLpd)"><path class="badi_znpj"/></g><g filter="url(#iHzrfye)"><path class="lhrjc71pe"/></g><g filter="url(#itVPQfY)"><path clip-rule="evenodd" class="fphs-dbhz"/></g><path class="ot2a8cc6r"/><path fill="url(#iTfpMYd)" class="sz_r4yb-l"/><path class="pb7n9rskv"/><g filter="url(#iRCjFEc)"><path class="wgp383aes"/><path fill="url(#iDHFtMC)" class="d3_d1tf4h"/></g><g filter="url(#icYCczt)"><path fill="url(#ilZnJWx)" class="v3c6zsb7e"/></g><path class="r8i0jzbgg"/><path fill="url(#i9Rpocd)" class="nme7n32qt"/><path class="wlox_vaql"/><g filter="url(#iKm7Nvd)"><path fill="url(#iUFKdnd)" class="dee2n4brb"/></g><g filter="url(#i7SJK8G)"><ellipse transform="rotate(-27.914 9.32 12.367)" class="q9fpg7fso"/><ellipse fill="url(#iQ9Ybte)" transform="rotate(-27.914 9.32 12.367)" class="t48gaybpa"/></g><g filter="url(#iY6CsTQ)"><path class="qvs8x6g_c"/></g><g filter="url(#ixzQZqb)"><path class="iu8_nbbbw"/></g><g filter="url(#i5dbhAG)"><path fill="url(#iG9gfMc)" class="dvynvbccm"/><path fill="url(#isIzxWd)" class="dvynvbccm"/></g><g filter="url(#iWXWlQD)"><path fill="url(#i0Jiaqe)" class="dsvuk0btp"/><path fill="url(#i3VKDPc)" class="dsvuk0btp"/><path fill="url(#i36BUDc)" class="dsvuk0btp"/></g><g filter="url(#i2kKkLe)"><path stroke="url(#iIsSvsd)" class="g9eeijbsg"/></g><defs><radialGradient id="i5fupkb" cx="0" cy="0" r="1" gradientTransform="matrix(3.622 1.95033 -2.76254 5.13039 17.415 17.515)" gradientUnits="userSpaceOnUse"><stop offset=".616" class="w3-vy4c8j"/><stop offset="1" class="w72oynbwi"/></radialGradient><radialGradient id="iHvAjwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.7477 -3.4628 0 6.59 15.883)" gradientUnits="userSpaceOnUse"><stop class="lcrdwk1fj"/><stop offset="1" class="denqa3bda"/></radialGradient><radialGradient id="i8Gqpod" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.18518 -7.48467 0 12.485 16.002)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="ag6fa4z4y"/><stop offset="1" class="qir_1cb0f"/></radialGradient><radialGradient id="ii3ywvd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.60025 2.0767 -2.01637 -1.55377 6.151 13.674)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="ha2cq84sa"/><stop offset="1" class="p4wkjrbae"/></radialGradient><radialGradient id="ijlWuLd" cx="0" cy="0" r="1" gradientTransform="rotate(100.537 -.92 8.139)scale(3.29775 2.66959)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="c42_rqbzh"/><stop offset="1" class="ybrvbdb9p"/></radialGradient><radialGradient id="iRgT6ke" cx="0" cy="0" r="1" gradientTransform="rotate(62.605 .784 8.738)scale(3.07085 5.8499)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="sq6p8ibru"/><stop offset=".921" class="v9rq5jjti"/></radialGradient><radialGradient id="ihmtiYb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.42677 1.5565 -2.17518 -1.99388 19.575 5.85)" gradientUnits="userSpaceOnUse"><stop class="duwob45dr"/><stop offset="1" class="v61l3jbat"/></radialGradient><radialGradient id="iMjXl0l" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 10.218 7.66)scale(2.47645 5.38841)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="hottnizrg"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="ixDpPOd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.12498 -4.37503 6.28304 -5.92395 19.75 22.188)" gradientUnits="userSpaceOnUse"><stop class="yqk-2gbyp"/><stop offset="1" class="oaxszm67z"/></radialGradient><radialGradient id="iaTJTHb" cx="0" cy="0" r="1" gradientTransform="rotate(-128.9 17.771 9.549)scale(14.3752 17.7454)" gradientUnits="userSpaceOnUse"><stop offset=".195" class="kycazvj-d"/><stop offset="1" class="s122v03dg"/></radialGradient><radialGradient id="iJCEzAd" cx="0" cy="0" r="1" gradientTransform="rotate(80.311 -5.78 15.845)scale(6.49895 15.3845)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="r391crypb"/><stop offset="1" class="zkp31ccrs"/></radialGradient><radialGradient id="iTk19tZ" cx="0" cy="0" r="1" gradientTransform="matrix(-4.91897 -8.2177 4.4235 -2.64783 21.231 29.405)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="i5f574mgr"/><stop offset="1" class="bt61m9mqj"/></radialGradient><radialGradient id="iBz1xre" cx="0" cy="0" r="1" gradientTransform="matrix(2.2115 3.95043 -7.41157 4.14908 11.953 19.938)" gradientUnits="userSpaceOnUse"><stop offset=".237" class="yz7y9cc2s"/><stop offset=".826" class="ah57bsbzt"/></radialGradient><radialGradient id="isMWwcb" cx="0" cy="0" r="1" gradientTransform="rotate(131.424 8.973 12.007)scale(2.12546 1.04757)" gradientUnits="userSpaceOnUse"><stop class="id09adcid"/><stop offset="1" class="kruo6kbky"/></radialGradient><radialGradient id="iNAcXVd" cx="0" cy="0" r="1" gradientTransform="rotate(-70.927 22.32 -8.676)scale(3.10812 1.58159)" gradientUnits="userSpaceOnUse"><stop offset=".854" class="av00hmb0p"/><stop offset="1" class="amtu30rgy"/></radialGradient><radialGradient id="iKgyBNd" cx="0" cy="0" r="1" gradientTransform="matrix(-.89575 .18 -.22855 -1.1374 29.73 14.092)" gradientUnits="userSpaceOnUse"><stop class="sn-83pben"/><stop offset="1" class="adnp-y-dh"/></radialGradient><radialGradient id="iIEGcgd" cx="0" cy="0" r="1" gradientTransform="matrix(.04403 .33209 -2.56302 .33983 27.284 13.57)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="rtamvw1ka"/><stop offset="1" class="ax8207b9e"/></radialGradient><radialGradient id="iT0YOte" cx="0" cy="0" r="1" gradientTransform="rotate(164.445 14.17 9.272)scale(.78159 1.2098)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="sn-83pben"/><stop offset="1" class="adnp-y-dh"/></radialGradient><radialGradient id="ihB7LZb" cx="0" cy="0" r="1" gradientTransform="matrix(.04382 .26178 -2.05938 .3447 27.874 13.895)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="rtamvw1ka"/><stop offset="1" class="ax8207b9e"/></radialGradient><radialGradient id="ikjvt9S" cx="0" cy="0" r="1" gradientTransform="matrix(-.89428 .16927 -.20335 -1.07433 30.026 14.864)" gradientUnits="userSpaceOnUse"><stop class="sn-83pben"/><stop offset="1" class="adnp-y-dh"/></radialGradient><radialGradient id="ivZ5mPj" cx="0" cy="0" r="1" gradientTransform="matrix(.0434 .28906 -2.36234 .35465 27.586 14.332)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="rtamvw1ka"/><stop offset="1" class="ax8207b9e"/></radialGradient><radialGradient id="inVnXQK" cx="0" cy="0" r="1" gradientTransform="rotate(169.423 13.892 9.157)scale(.90027 1.06791)" gradientUnits="userSpaceOnUse"><stop class="sn-83pben"/><stop offset="1" class="adnp-y-dh"/></radialGradient><radialGradient id="iSNtizc" cx="0" cy="0" r="1" gradientTransform="rotate(81.573 4.926 23.455)scale(.21324 1.76543)" gradientUnits="userSpaceOnUse"><stop offset=".382" class="rtamvw1ka"/><stop offset="1" class="ax8207b9e"/></radialGradient><radialGradient id="iZUy5ib" cx="0" cy="0" r="1" gradientTransform="rotate(157.027 11.722 9.99)scale(3.12266 1.85514)" gradientUnits="userSpaceOnUse"><stop class="eksmwwbms"/><stop offset="1" class="jxtp3vx1u"/></radialGradient><radialGradient id="iO2S5kb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.05458 -3.66708 0 24.195 17.317)" gradientUnits="userSpaceOnUse"><stop offset=".441" class="i78ibac_i"/><stop offset="1" class="f7viecbbv"/></radialGradient><radialGradient id="iWLFdzb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1875 0 0 -.57813 24.812 19.156)" gradientUnits="userSpaceOnUse"><stop class="z4eucjgkn"/><stop offset="1" class="i3nwakyct"/></radialGradient><radialGradient id="iLWynuc" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 40.763 -33.931)scale(3.52633 4.30549)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="igDnJLc" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 47.1 -44.634)scale(1.68259)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="iyBus5c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.38533 0 0 -1.32516 6.466 13.26)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="iXVMnEd" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 6.707 8.058)scale(9.23686 12.3634)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="m45oyzb-o"/></radialGradient><radialGradient id="ibPrc3b" cx="0" cy="0" r="1" gradientTransform="rotate(152.124 5.797 8.587)scale(3.07822 2.61165)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="iLbJoad" cx="0" cy="0" r="1" gradientTransform="rotate(-78.311 17.925 4.718)scale(5.3277 6.75986)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="irA3N9c" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.59649 -15.2418 0 12.147 11.943)" gradientUnits="userSpaceOnUse"><stop offset=".593" class="ajxs5ri3z"/><stop offset="1" class="x05md6_2b"/></radialGradient><radialGradient id="imwEAre" cx="0" cy="0" r="1" gradientTransform="rotate(164.542 5.65 8.254)scale(7.25623 12.493)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="ioM0Ere" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.48421 1.82152 0 15.453 12.027)" gradientUnits="userSpaceOnUse"><stop class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="ifHVtIw" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.75406 2.01027 0 10.01 12.14)" gradientUnits="userSpaceOnUse"><stop class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="iKZ6UNb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.73723 0 0 -5.71902 19.056 13.946)" gradientUnits="userSpaceOnUse"><stop class="f902gfhfn"/><stop offset="1" class="jh40i5bvl"/></radialGradient><radialGradient id="iIOe3Oc" cx="0" cy="0" r="1" gradientTransform="matrix(-.89955 -3.15955 1.80793 -.51473 13.496 14.883)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="iMJCMOd" cx="0" cy="0" r="1" gradientTransform="rotate(144.462 4.117 9.271)scale(2.03121 2.72066)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="e6-lebcyw"/><stop offset="1" class="b8os9sbcy"/></radialGradient><radialGradient id="iTfpMYd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.04639 -1.66441 0 15.299 12.49)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iDHFtMC" cx="0" cy="0" r="1" gradientTransform="matrix(-.29887 -.38514 .53024 -.41148 15.004 12.598)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i9Rpocd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.0464 -1.66442 0 9.67 12.49)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iQ9Ybte" cx="0" cy="0" r="1" gradientTransform="matrix(-.00997 -.6367 .76534 -.01198 9.3 12.773)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iG9gfMc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.41008 5.3396 -2.32876 -1.92337 8.983 4.293)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="esh4v5qtq"/><stop offset=".911" class="nria2ku7r"/></radialGradient><radialGradient id="isIzxWd" cx="0" cy="0" r="1" gradientTransform="rotate(146.397 3.66 4.108)scale(3.39954 1.68275)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="dpv-wxbjb"/><stop offset="1" class="abu2lcc5n"/><stop offset="1" class="sxoxd_kke"/></radialGradient><radialGradient id="i0Jiaqe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.81855 5.87487 -8.34133 -4.00187 14.795 2.78)" gradientUnits="userSpaceOnUse"><stop offset=".627" class="crfaaqblp"/><stop offset="1" class="ehjghj3fe"/></radialGradient><radialGradient id="i3VKDPc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21617 4.26684 -8.94197 -2.5487 15.72 4.397)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="z-gx2rb2w"/><stop offset="1" class="gbpc14bxe"/></radialGradient><radialGradient id="i36BUDc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.40684 -8.34138 7.45667 -3.93945 13.967 11.66)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="s3t3owbgt"/><stop offset="1" class="yehxt3bls"/></radialGradient><filter id="i4DOBbc" width="19.62" height="19.62" x="2.8" y="2.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.537255 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3787"/></filter><filter id="iSdi7pc" width="7.879" height="3.847" x="21.349" y="13.595" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.603922 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3787"/></filter><filter id="ioD8qHb" width="6.491" height="11.844" x="20.207" y="18.173" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.52549 0 0 0 0 0.337255 0 0 0 0 0.737255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3787"/></filter><filter id="i1410XJ" width="4.301" height="4.401" x="4.366" y="11.185" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.627451 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3787"/></filter><filter id="iq650fc" width="4.151" height="4.401" x="16.635" y="10.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3787"/></filter><filter id="iJdDXnc" width="3.771" height="3.771" x="16.825" y="11.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3787" stdDeviation=".25"/></filter><filter id="iGzBcMd" width="3.271" height="3.271" x="4.831" y="11.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3787" stdDeviation=".125"/></filter><filter id="ihVoIbe" width="13.144" height="14.428" x="5.913" y="6.932" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3787"/></filter><filter id="iOs22lb" width="3.421" height="4.459" x="10.565" y="12.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3787" stdDeviation=".25"/></filter><filter id="ibioDpe" width="2.921" height="3.959" x="11.024" y="12.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3787" stdDeviation=".125"/></filter><filter id="ipBPqmd" width="3.813" height="1.658" x="13.758" y="11.449" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3787"/></filter><filter id="iF9wLpd" width="3.813" height="1.658" x="7.399" y="11.449" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3787"/></filter><filter id="iHzrfye" width="3.106" height="1.349" x="7.573" y="9.67" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3787"/></filter><filter id="itVPQfY" width="3.106" height="1.349" x="14.56" y="9.67" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3787"/></filter><filter id="iRCjFEc" width=".956" height=".84" x="14.381" y="11.952" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3787" stdDeviation=".05"/></filter><filter id="icYCczt" width="1.033" height="1.062" x="15.493" y="12.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3787" stdDeviation=".1"/></filter><filter id="iKm7Nvd" width="1.156" height="1.225" x="9.763" y="11.996" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3787" stdDeviation=".1"/></filter><filter id="i7SJK8G" width="1.119" height=".85" x="8.761" y="11.942" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3787" stdDeviation=".05"/></filter><filter id="iY6CsTQ" width="3.342" height="1.687" x="14.386" y="9.557" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3787" stdDeviation=".2"/></filter><filter id="ixzQZqb" width="3.342" height="1.687" x="7.355" y="9.557" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3787" stdDeviation=".2"/></filter><filter id="i5dbhAG" width="5.995" height="6.29" x="4.051" y="4.093" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3787" stdDeviation=".375"/></filter><filter id="iWXWlQD" width="11.852" height="7.81" x="8.029" y="2.669" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3787" stdDeviation=".25"/></filter><filter id="i2kKkLe" width="1.303" height="2.805" x="8.456" y="4.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3787" stdDeviation=".125"/></filter><linearGradient id="iWLBAOb" x1="18.538" x2="9.198" y1="4.293" y2="21.631" gradientUnits="userSpaceOnUse"><stop class="yr1vjkbzu"/><stop offset="1" class="btu9i2bec"/></linearGradient><linearGradient id="iV1Kr8b" x1="12.473" x2="12.473" y1="30.531" y2="24.991" gradientUnits="userSpaceOnUse"><stop offset=".173" class="qpr7khtkz"/><stop offset="1" class="t_4ix1b_d"/></linearGradient><linearGradient id="ipJOdQy" x1="27.898" x2="27.599" y1="15.64" y2="14.386" gradientUnits="userSpaceOnUse"><stop class="iewh3ibyo"/><stop offset="1" class="dbywulbre"/></linearGradient><linearGradient id="iR6Ec7c" x1="28.319" x2="28.193" y1="15.914" y2="14.688" gradientUnits="userSpaceOnUse"><stop offset=".217" class="iewh3ibyo"/><stop offset="1" class="dbywulbre"/></linearGradient><linearGradient id="iW8noib" x1="28.032" x2="27.914" y1="16.32" y2="15.137" gradientUnits="userSpaceOnUse"><stop offset=".217" class="iewh3ibyo"/><stop offset="1" class="dbywulbre"/></linearGradient><linearGradient id="i4krjdb" x1="24.679" x2="26.273" y1="16.77" y2="16.457" gradientUnits="userSpaceOnUse"><stop offset=".585" class="oc3fsgi2c"/><stop offset="1" class="v-pv693fm"/></linearGradient><linearGradient id="iPniSWO" x1="27.062" x2="27.008" y1="16.934" y2="16.613" gradientUnits="userSpaceOnUse"><stop offset=".101" class="gvo57cbnb"/><stop offset="1" class="wodu9bbyy"/></linearGradient><linearGradient id="idxuF1d" x1="23.574" x2="23.574" y1="18.268" y2="18.094" gradientUnits="userSpaceOnUse"><stop offset=".316" class="eaeluzb_q"/><stop offset="1" class="d1e25fl5t"/></linearGradient><linearGradient id="i7zc9zd" x1="24.445" x2="24.445" y1="19.332" y2="38.645" gradientUnits="userSpaceOnUse"><stop class="ajcxr5b9v"/><stop offset=".621" class="p8hgxvbxj"/></linearGradient><linearGradient id="iNI4rjd" x1="27.859" x2="22.432" y1="28.859" y2="28.859" gradientUnits="userSpaceOnUse"><stop class="gls6vybda"/><stop offset=".458" class="n3kogy75l"/><stop offset="1" class="gls6vybda"/></linearGradient><linearGradient id="im24ZMd" x1="23.403" x2="23.403" y1="18.173" y2="19.207" gradientUnits="userSpaceOnUse"><stop offset=".366" class="sctbmnb9m"/><stop offset="1" class="gme609baj"/></linearGradient><linearGradient id="iHxHQ1b" x1="4.366" x2="8.183" y1="13.373" y2="13.373" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="i7soazd" x1="12.485" x2="12.485" y1="15.889" y2="12.43" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="idNnype" x1="11.135" x2="12.237" y1="14.906" y2="15.041" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="iBRg2Ic" x1="12.485" x2="12.485" y1="16.008" y2="15.22" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="imz7UQb" x1="12.586" x2="12.586" y1="15.974" y2="15.794" gradientUnits="userSpaceOnUse"><stop class="b8os9sbcy"/><stop offset="1" class="e6-lebcyw"/></linearGradient><linearGradient id="iiL951c" x1="11.544" x2="12.128" y1="17.912" y2="16.788" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="ilZnJWx" x1="16.302" x2="15.898" y1="12.559" y2="12.809" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iUFKdnd" x1="10.629" x2="10.225" y1="12.559" y2="12.808" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iIsSvsd" x1="8.756" x2="9.458" y1="5.266" y2="6.909" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-tipping-hand" /></template>
<style>
.a9dfe182j {
  stop-color: var(--svg-color--d4993e, #D4993E);
}

.abu2lcc5n {
  stop-color: var(--svg-color--ffe134, #FFE134);
  stop-opacity: 0;
}

.adnp-y-dh {
  stop-color: var(--svg-color--ffdc47, #FFDC47);
  stop-opacity: 0;
}

.ag6fa4z4y {
  stop-color: var(--svg-color--e26b25, #E26B25);
}

.ah57bsbzt {
  stop-color: var(--svg-color--ffb736, #FFB736);
}

.ajcxr5b9v {
  stop-color: var(--svg-color--9361e2, #9361E2);
}

.ajxs5ri3z {
  stop-color: var(--svg-color--f3943b, #F3943B);
  stop-opacity: 0;
}

.amtu30rgy {
  stop-color: var(--svg-color--eab23a, #EAB23A);
}

.av00hmb0p {
  stop-color: var(--svg-color--eab23a, #EAB23A);
  stop-opacity: 0;
}

.ax8207b9e {
  stop-color: var(--svg-color--e4b833, #E4B833);
  stop-opacity: 0;
}

.b8os9sbcy {
  stop-color: var(--svg-color--e2802f, #E2802F);
}

.badi_znpj {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M11.012 12.526c-.342-.602-.863-1.077-1.983-1.077c-.49 0-.963.136-1.384.475c-.346.28-.3.639-.031.773l.717.41c.84-.272 1.77-.31 2.68-.58");
}

.bt61m9mqj {
  stop-color: var(--svg-color--9a68ed, #9A68ED);
  stop-opacity: 0;
}

.btu9i2bec {
  stop-color: var(--svg-color--e37923, #E37923);
}

.c42_rqbzh {
  stop-color: var(--svg-color--d77016, #D77016);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crfaaqblp {
  stop-color: var(--svg-color--f49523, #F49523);
  stop-opacity: 0;
}

.d_d61_bgh {
  d: path("M21.106 17.478a.25.25 0 0 1 .25-.25h4.093a.25.25 0 0 1 .25.25v1.64h-4.593z");
}

.d_iyr-bay {
  fill: var(--svg-color--8a004f, #8A004F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M10.675 16.527a3.85 3.85 0 0 0 1.81.438c.67 0 1.287-.16 1.81-.438a.25.25 0 0 1 .301.05a.24.24 0 0 1 .026.304l-.042-.027a2.492 2.492 0 0 1-4.19 0zm0 0a.25.25 0 0 0-.302.053a.24.24 0 0 0-.025.301z");
}

.d1bo5fbgs {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m11.978 12.973l-.881 2.192a.695.695 0 0 0 .671.902h1.014a.698.698 0 0 0 .672-.902l-.686-2.192c-.147-.486-.636-.486-.79 0");
}

.d1e25fl5t {
  stop-color: var(--svg-color--724c80, #724C80);
  stop-opacity: 0;
}

.d3_d1tf4h {
  d: path("M15.216 12.118c.082.11-.09.244-.284.39c-.195.145-.34.247-.421.138c-.082-.11.01-.317.204-.462c.195-.146.42-.175.501-.066");
}

.dbywulbre {
  stop-color: var(--svg-color--ffcb38, #FFCB38);
  stop-opacity: 0;
}

.dee2n4brb {
  d: path("M10.719 12.89c0-.372-.303-.62-.384-.694l-.372.36l.229.465z");
}

.denqa3bda {
  stop-color: var(--svg-color--d77117, #D77117);
  stop-opacity: 0;
}

.dpv-wxbjb {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
}

.dsvuk0btp {
  d: path("M11.707 3.212C10.246 2.89 8.68 4.444 8.529 4.985c1.989 4.67 5.043 4.224 8.43 3.848c2.029-.226 2.249.699 2.422 1.146c-.562-5.232-4.345-6.032-7.674-6.767");
}

.duwob45dr {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
}

.dvynvbccm {
  d: path("M6.172 5.504c.801-.714 1.957-.72 2.605-.606l.52 1.665c-.332-.05-.628.065-.876.303c-.588 1.625-2.609 2.522-3.546 2.767c-.194-1.924-.086-2.897 1.297-4.13");
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

.eaeluzb_q {
  stop-color: var(--svg-color--724c80, #724C80);
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.ehjghj3fe {
  stop-color: var(--svg-color--f49523, #F49523);
}

.eksmwwbms {
  stop-color: var(--svg-color--ffd836, #FFD836);
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.esh4v5qtq {
  stop-color: var(--svg-color--ee971b, #EE971B);
  stop-opacity: 0;
}

.f7viecbbv {
  stop-color: var(--svg-color--684995, #684995);
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

.fphs-dbhz {
  fill: var(--svg-color--bd4f26, #BD4F26);
  fill-rule: evenodd;
  d: path("m17.297 10.377l-.177.297za.346.346 0 0 1-.355.594l-.006-.004a2 2 0 0 0-.146-.075a4 4 0 0 0-.441-.174c-.375-.12-.869-.21-1.383-.119a.346.346 0 0 1-.12-.68c.662-.118 1.275 0 1.713.14a4 4 0 0 1 .72.308l.013.007l.003.002z");
}

.ft5dv1b6b {
  fill: none;
}

.g9eeijbsg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M8.756 4.823c.03.313.302 1.491.702 2.205");
}

.gbpc14bxe {
  stop-color: var(--svg-color--ffe337, #FFE337);
  stop-opacity: 0;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gls6vybda {
  stop-color: var(--svg-color--a97afa, #A97AFA);
  stop-opacity: 0;
}

.gme609baj {
  stop-color: var(--svg-color--946ad2, #946AD2);
  stop-opacity: 0;
}

.gsggv-b-p {
  stop-color: var(--svg-color--f09429, #F09429);
  stop-opacity: 0;
}

.gvo57cbnb {
  stop-color: var(--svg-color--e38654, #E38654);
}

.h11_utkon {
  stop-color: var(--svg-color--b96201, #B96201);
}

.ha2cq84sa {
  stop-color: var(--svg-color--c9681c, #C9681C);
}

.hottnizrg {
  stop-color: var(--svg-color--ffd336, #FFD336);
  stop-opacity: 0;
}

.i3nwakyct {
  stop-color: var(--svg-color--ad84f5, #AD84F5);
  stop-opacity: 0;
}

.i5f574mgr {
  stop-color: var(--svg-color--6c41bf, #6C41BF);
}

.i78ibac_i {
  stop-color: var(--svg-color--8167ad, #8167AD);
}

.id09adcid {
  stop-color: var(--svg-color--ffe047, #FFE047);
}

.iewh3ibyo {
  stop-color: var(--svg-color--e48851, #E48851);
}

.ilaikjfls {
  fill-rule: evenodd;
  d: path("M25.66 13.946c-.328.037-.77.086-1.597.155l-.229.019c-1.06.082-2.273.177-2.466 1.345c-.2 1.203 1.183 2.141 2.831 1.954c.594-.068.867-.154 1.175-.251c.243-.076.508-.16.967-.247c.917-.102 1.759-.207 2.234-.309A.825.825 0 0 0 28.23 15c-.37.079-1.053.167-1.874.26l-.203-1.364c-.161.014-.31.03-.493.051");
}

.iopmamb4i {
  d: path("M12.473 19.966c-5.523 0-10 4.477-10 10v.05h20v-.05c0-5.523-4.477-10-10-10");
}

.ipjmodbjb {
  fill: var(--svg-color--ffca37, #FFCA37);
  fill-rule: evenodd;
  d: path("M29.716 14.11a.85.85 0 0 1-.69.986a21 21 0 0 0-.562.112c-.653.136-1.594.332-2.606.428a.85.85 0 0 1-.16-1.692c.909-.086 1.678-.247 2.317-.38q.39-.083.716-.142a.85.85 0 0 1 .985.689");
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.iu8_nbbbw {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M10.097 10.2c-.416-.101-1.45-.05-2.142.444");
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.j2mxgnb6a {
  fill: var(--svg-color--ffca37, #FFCA37);
  fill-rule: evenodd;
  d: path("M30.294 14.44a.85.85 0 0 1-.689.984q-.18.032-.413.076c-.662.124-1.626.305-2.733.41a.85.85 0 1 1-.16-1.693a27 27 0 0 0 2.552-.383q.25-.047.459-.084a.85.85 0 0 1 .984.69");
}

.jf2e24bdx {
  d: path("M22.121 13.806c-.554.648-.74 1.416-.761 1.757l1.847-.101l.887-1.184c.29-.383.54-1.02-.035-1.441c-.466-.342-.946-.067-1.102.105a28 28 0 0 0-.836.864");
}

.jh40i5bvl {
  stop-color: var(--svg-color--ffda39, #FFDA39);
  stop-opacity: 0;
}

.jko339btq {
  fill-rule: evenodd;
  d: path("M29.716 14.11a.85.85 0 0 1-.69.986a21 21 0 0 0-.562.112c-.653.136-1.594.332-2.606.428a.85.85 0 0 1-.16-1.692c.909-.086 1.678-.247 2.317-.38q.39-.083.716-.142a.85.85 0 0 1 .985.689");
}

.jxtp3vx1u {
  stop-color: var(--svg-color--ffd836, #FFD836);
  stop-opacity: 0;
}

.k4rw0xbwd {
  fill-rule: evenodd;
  d: path("M30.023 14.997a.85.85 0 0 1-.773.921c-.32.028-.739.088-1.26.162l-.03.004a53 53 0 0 1-1.787.23a.85.85 0 0 1-.182-1.69c.622-.067 1.204-.149 1.73-.223l.064-.01c.491-.07.949-.134 1.317-.166a.85.85 0 0 1 .92.772");
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.kruo6kbky {
  stop-color: var(--svg-color--fab91d, #FAB91D);
}

.kycazvj-d {
  stop-color: var(--svg-color--9b69f3, #9B69F3);
}

.lcrdwk1fj {
  stop-color: var(--svg-color--c9641b, #C9641B);
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.lhrjc71pe {
  fill: var(--svg-color--bd4f26, #BD4F26);
  d: path("m8.103 10.967l-.006.003a.346.346 0 0 1-.356-.593h.001l.001-.001l.004-.002l.012-.007l.042-.024q.054-.03.15-.075c.127-.061.308-.139.529-.21c.438-.139 1.051-.257 1.713-.14a.346.346 0 0 1-.12.681c-.515-.09-1.009 0-1.383.119a3.5 3.5 0 0 0-.56.234z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
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

.mxguyeblr {
  d: path("M6.441 15.336a2.075 2.075 0 1 0 0-4.151a2.075 2.075 0 0 0 0 4.15");
}

.n0ojrlpxd {
  d: path("M18.71 14.646a1.385 1.385 0 1 0 0-2.771a1.385 1.385 0 0 0 0 2.77");
}

.n3kogy75l {
  stop-color: var(--svg-color--a97afa, #A97AFA);
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.nme7n32qt {
  d: path("M9.668 11.875a1.15 1.15 0 0 0-1.11 1.454h2.224q.04-.148.042-.303a1.16 1.16 0 0 0-1.156-1.151");
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

.oc3fsgi2c {
  stop-color: var(--svg-color--ffca38, #FFCA38);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ot2a8cc6r {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.569 11.524c.842 0 1.553.581 1.747 1.366a.354.354 0 0 1-.345.44h-2.878a.297.297 0 0 1-.293-.351a1.8 1.8 0 0 1 1.768-1.455");
}

.p4wkjrbae {
  stop-color: var(--svg-color--c9681c, #C9681C);
  stop-opacity: 0;
}

.p8hgxvbxj {
  stop-color: var(--svg-color--9661f1, #9661F1);
}

.pb_rvfc5z {
  stop-color: var(--svg-color--ffe842, #FFE842);
}

.pb7n9rskv {
  fill: var(--svg-color--000, #000);
  d: path("M14.642 13.026c0-.366.293-.66.66-.66a.657.657 0 0 1 .585.963h-1.166a.6.6 0 0 1-.079-.303");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.px7bzgweo {
  width: 4.898px;
  height: 6.68px;
  x: 10.035px;
  y: 16.938px;
  rx: 2.449px;
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.q498y9b2p {
  fill-rule: evenodd;
  d: path("M21.752 15.078a4.2 4.2 0 0 0 .417-1.84c0-.603-.124-1.168-.346-1.684h.007a4 4 0 0 0-.363-.661l-.002-.004a4.2 4.2 0 0 1-.68-2.285v-.013a4.256 4.256 0 0 0-4.254-4.255a.7.7 0 0 1-.587-.3a4.26 4.26 0 0 0-3.46-1.775a4.26 4.26 0 0 0-3.458 1.775a.73.73 0 0 1-.588.3l-.11.002A4.256 4.256 0 0 0 4.184 8.59v.013c0 .81-.235 1.606-.678 2.285l-.003.004a4.26 4.26 0 0 0-.285 4.185a.66.66 0 0 1 0 .588A4.2 4.2 0 0 0 2.8 17.48a4.144 4.144 0 0 0 4.15 4.15h11.07a4.144 4.144 0 0 0 4.15-4.15a4.2 4.2 0 0 0-.417-1.814a.66.66 0 0 1 0-.588M5.939 11.632h-.016L7.47 14.67c.16 3.614 1.57 0 5.016 0s4.947 4.023 5.107.408l1.465-4.123c-.07-1.606-1.233-1.718-1.465-1.718H13.44a4.98 4.98 0 0 1-4.114-2.158a.34.34 0 0 0-.595.065l-.106.25a2.97 2.97 0 0 1-1.6 1.619l-.066.026c-.305.158-1.019.632-1.045 1.856l.013.395z");
}

.q8qkepb9e {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M18.71 14.646a1.385 1.385 0 1 0 0-2.771a1.385 1.385 0 0 0 0 2.77");
}

.q9fpg7fso {
  cx: 9.32px;
  cy: 12.367px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.502px;
  ry: 0.254px;
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qced8sf2z {
  fill: var(--svg-color--f1a31e, #F1A31E);
  d: path("M21.349 15.719h4.015v2.016h-4.015z");
}

.qir_1cb0f {
  stop-color: var(--svg-color--e26b25, #E26B25);
  stop-opacity: 0;
}

.qpr7khtkz {
  stop-color: var(--svg-color--9a66f3, #9A66F3);
}

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.qvs8x6g_c {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M14.986 10.2c.416-.101 1.45-.05 2.142.444");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwjswe-rp {
  stop-color: var(--svg-color--e48538, #E48538);
  stop-opacity: 0;
}

.r391crypb {
  stop-color: var(--svg-color--6b3b70, #6B3B70);
}

.r8i0jzbgg {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.401 11.524c-.842 0-1.554.581-1.748 1.366a.354.354 0 0 0 .346.44h2.877c.184 0 .33-.168.293-.351a1.81 1.81 0 0 0-1.768-1.455");
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.rnki6ubvc {
  fill: var(--svg-color--ffca37, #FFCA37);
  fill-rule: evenodd;
  d: path("M30.023 14.997a.85.85 0 0 1-.773.921c-.32.028-.739.088-1.26.162l-.03.004a53 53 0 0 1-1.787.23a.85.85 0 0 1-.182-1.69c.622-.067 1.204-.149 1.73-.223l.064-.01c.491-.07.949-.134 1.317-.166a.85.85 0 0 1 .92.772");
}

.rsf68q_lb {
  fill-rule: evenodd;
  d: path("M30.294 14.44a.85.85 0 0 1-.689.984q-.18.032-.413.076c-.662.124-1.626.305-2.733.41a.85.85 0 1 1-.16-1.693a27 27 0 0 0 2.552-.383q.25-.047.459-.084a.85.85 0 0 1 .984.69");
}

.rsgza3yef {
  fill: var(--svg-color--ffca37, #FFCA37);
  fill-rule: evenodd;
  d: path("M25.66 13.946c-.328.037-.77.086-1.597.155l-.229.019c-1.06.082-2.273.177-2.466 1.345c-.2 1.203 1.183 2.141 2.831 1.954c.594-.068.867-.154 1.175-.251c.243-.076.508-.16.967-.247c.917-.102 1.759-.207 2.234-.309A.825.825 0 0 0 28.23 15c-.37.079-1.053.167-1.874.26l-.203-1.364c-.161.014-.31.03-.493.051");
}

.rtamvw1ka {
  stop-color: var(--svg-color--e4b833, #E4B833);
}

.s122v03dg {
  stop-color: var(--svg-color--9b69f3, #9B69F3);
  stop-opacity: 0;
}

.s3t3owbgt {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
  stop-opacity: 0;
}

.sctbmnb9m {
  stop-color: var(--svg-color--946ad2, #946AD2);
}

.sn-83pben {
  stop-color: var(--svg-color--ffdc47, #FFDC47);
}

.sq6p8ibru {
  stop-color: var(--svg-color--c79e3f, #C79E3F);
}

.sxoxd_kke {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
  stop-opacity: 0;
}

.sz_r4yb-l {
  d: path("M15.302 11.875a1.15 1.15 0 0 1 1.109 1.454h-2.224a1.156 1.156 0 0 1 1.114-1.454");
}

.t_4ix1b_d {
  stop-color: var(--svg-color--8757b3, #8757B3);
}

.t1-486sdu {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M6.466 14.646a1.385 1.385 0 1 0 0-2.771a1.385 1.385 0 0 0 0 2.77");
}

.t48gaybpa {
  cx: 9.32px;
  cy: 12.367px;
  rx: 0.502px;
  ry: 0.254px;
}

.tbf9ru2pp {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M13.958 12.526c.342-.602.862-1.077 1.983-1.077c.49 0 .963.136 1.383.475c.347.28.3.639.032.773l-.717.41c-.84-.272-1.77-.31-2.681-.58");
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.v-pv693fm {
  stop-color: var(--svg-color--ffca38, #FFCA38);
  stop-opacity: 0;
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v3c6zsb7e {
  d: path("M16.326 12.874a1.1 1.1 0 0 0-.298-.597l-.335.368l.152.294z");
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

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.wgp383aes {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M15.216 12.118c.082.11-.09.244-.284.39c-.195.145-.34.247-.421.138c-.082-.11.01-.317.204-.462c.195-.146.42-.175.501-.066");
}

.wlox_vaql {
  fill: var(--svg-color--000, #000);
  d: path("M10.327 13.026a.657.657 0 0 0-.66-.66a.657.657 0 0 0-.585.963h1.166a.65.65 0 0 0 .079-.303");
}

.wodu9bbyy {
  stop-color: var(--svg-color--e99344, #E99344);
  stop-opacity: 0;
}

.wr_32p5jm {
  d: path("M5.923 11.632h.016l-.013-.342l-.013-.395c.026-1.224.74-1.698 1.045-1.856q.03-.01.066-.026l.066-.026a2.97 2.97 0 0 0 1.534-1.593l.106-.25a.34.34 0 0 1 .595-.065a4.98 4.98 0 0 0 4.114 2.158h4.153c.232 0 1.395.112 1.465 1.718l-.154 3.963c-.159 3.615-2.981 6.042-6.427 6.042s-6.268-2.427-6.427-6.042z");
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.x05md6_2b {
  stop-color: var(--svg-color--d97c39, #D97C39);
}

.x1cq4fb-p {
  d: path("M6.466 14.646a1.385 1.385 0 1 0 0-2.771a1.385 1.385 0 0 0 0 2.77");
}

.xa4i0b44p {
  d: path("M18.71 15.336a2.075 2.075 0 1 0 0-4.151a2.075 2.075 0 0 0 0 4.15");
}

.xm2mt2alw {
  d: path("M25.66 13.946c-.328.037-.77.086-1.597.155l-.229.019c-1.06.082-2.273.177-2.466 1.345c-.2 1.203 1.183 2.141 2.832 1.954c.593-.068.873-.095 1.181-.192c.243-.077.5-.219.96-.306c.917-.102 1.759-.207 2.234-.309A.825.825 0 0 0 28.23 15c-.37.079-1.053.167-1.874.26l-.203-1.364c-.161.014-.31.03-.493.051");
}

.y7n0ymbzx {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
  stop-opacity: 0;
}

.ybrvbdb9p {
  stop-color: var(--svg-color--d77016, #D77016);
  stop-opacity: 0;
}

.yehxt3bls {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
}

.ynx1-lz2q {
  d: path("m11.992 12.794l-.686 2.193a.695.695 0 0 0 .672.902h1.014a.698.698 0 0 0 .671-.902l-.685-2.193c-.147-.485-.832-.485-.986 0");
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

.yz7y9cc2s {
  stop-color: var(--svg-color--dd8031, #DD8031);
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.z-gx2rb2w {
  stop-color: var(--svg-color--ffe337, #FFE337);
}

.z4eucjgkn {
  stop-color: var(--svg-color--ad84f5, #AD84F5);
}

.z7b6rzlke {
  d: path("M20.207 18.973a.8.8 0 0 1 .8-.8h4.79a.8.8 0 0 1 .8.8v11.044h-6.39z");
}

.zkp31ccrs {
  stop-color: var(--svg-color--8757b3, #8757B3);
  stop-opacity: 0;
}

</style>
