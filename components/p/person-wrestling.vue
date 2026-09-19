<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iibwJkc)" class="bmlajh73u"/><path fill="url(#iPhxkOc)" transform="scale(-1 1)rotate(-23.31 19.294 36.035)" class="dm4voe-la"/><g filter="url(#iFqdBrb)"><path fill="url(#i270lUc)" class="ofgsb13it"/><path fill="url(#i0e765b)" class="ofgsb13it"/></g><g filter="url(#iKWRZvp)"><path class="vro47yafk"/><path fill="url(#isWd7Wd)" class="o98gvps8d"/><path fill="url(#iP3fkvd)" class="o98gvps8d"/><path fill="url(#iX4G2dc)" class="o98gvps8d"/><path fill="url(#ipFUNLe)" class="o98gvps8d"/><path fill="url(#iHu9Rwd)" class="o98gvps8d"/></g><path fill="url(#iTbW8Yb)" class="z0s8_mb4j"/><path class="hrro0vowg"/><path fill="url(#iWM7LSd)" class="ye0_6_2fy"/><path fill="url(#iSjZs2b)" class="tuoskac9t"/><ellipse fill="url(#iMnw01d)" transform="matrix(-.90936 .41601 .41687 .90897 13.97 8.532)" class="f6mg5tnmy"/><g filter="url(#iA7fV3d)"><path class="pq-elqbjd"/></g><g filter="url(#i9EePFe)"><path class="cgkj-oamf"/><path fill="url(#i3n0iPb)" class="csfglkqju"/></g><path fill="url(#iC82hVd)" class="oneeefb7d"/><path fill="url(#iQnOtjd)" class="oneeefb7d"/><path fill="url(#iUjKRfd)" class="oneeefb7d"/><path fill="url(#ieLIobc)" class="ekab7hynw"/><path fill="url(#iUT4Ved)" class="ekab7hynw"/><path fill="url(#iCzBbld)" class="ekab7hynw"/><g filter="url(#iGYNSwc)"><path class="z1ibusbcg"/></g><g filter="url(#iVAfdvd)"><path class="xsj_1jbtv"/></g><g filter="url(#iiP2T6c)"><path class="jsdr1ac4o"/><path fill="url(#imc7P7d)" class="v1mra159b"/></g><path fill="url(#iB3PS0c)" class="jxqc6mbch"/><path fill="url(#iElXErd)" class="jxqc6mbch"/><g filter="url(#ijE35vb)"><path class="sc-_6lb7g"/><path fill="url(#i7cSiHe)" class="aci6iobrg"/><path fill="url(#i0UffXd)" class="aci6iobrg"/><path fill="url(#iRppiQe)" class="aci6iobrg"/></g><g filter="url(#i0zvdke)"><path class="wrq6su8qp"/></g><g filter="url(#iEoVTqe)"><path class="b3xtyyrgk"/><path fill="url(#i1tvNQv)" class="ae6-jibhp"/><path fill="url(#iU4AHwe)" class="ae6-jibhp"/><path fill="url(#iSYTjPd)" class="ae6-jibhp"/></g><g filter="url(#ie8ngTb)"><path fill="url(#ilu9Sid)" class="fqdryqbjp"/></g><g filter="url(#ikmVnye)"><rect stroke="url(#iYf8PSc)" transform="rotate(45 8.633 11.554)" class="qccoatb5w"/></g><rect fill="url(#iMJdzvc)" transform="rotate(45 8.633 11.554)" class="tfv_ikbia"/><rect fill="url(#ipifqzd)" transform="rotate(45 8.633 11.554)" class="tfv_ikbia"/><path fill="url(#i8VLSDb)" clip-rule="evenodd" class="z43rvw5kz"/><path fill="url(#iqAIzAe)" clip-rule="evenodd" class="z43rvw5kz"/><path fill="url(#ifm02De)" clip-rule="evenodd" class="z43rvw5kz"/><path fill="url(#iCB9Zxs)" clip-rule="evenodd" class="rnk52-res"/><path fill="url(#iU5gO1b)" clip-rule="evenodd" class="rnk52-res"/><circle fill="url(#iM82Cwe)" class="cz78e2buv"/><circle fill="url(#ifFq63d)" class="cz78e2buv"/><circle fill="url(#iaiQkHc)" class="cz78e2buv"/><g filter="url(#inRv5rb)"><rect class="mpldlh5nb"/></g><rect class="h6ffxpb2n"/><g filter="url(#iAmrHie)"><path clip-rule="evenodd" class="diyyu_bjy"/></g><path clip-rule="evenodd" class="qeztqxpsc"/><path fill="url(#iyspjhe)" clip-rule="evenodd" class="zhwo_abtx"/><path clip-rule="evenodd" class="x6cs_acbd"/><path fill="url(#iLgJ3yd)" clip-rule="evenodd" class="qf6ieuwex"/><path clip-rule="evenodd" class="q97ggtqqw"/><path fill="url(#it2MJPc)" clip-rule="evenodd" class="t93mqebfe"/><path clip-rule="evenodd" class="q2m86208q"/><path fill="url(#iKzvFHe)" clip-rule="evenodd" class="ibwv6bbpe"/><path clip-rule="evenodd" class="s39fbtb4t"/><path fill="url(#irkpnyI)" clip-rule="evenodd" class="x2fv2isib"/><path fill="url(#i9F2U8b)" clip-rule="evenodd" class="vhx3aibpe"/><path fill="url(#i01dRld)" clip-rule="evenodd" class="vhx3aibpe"/><path fill="url(#i34FvUb)" clip-rule="evenodd" class="vhx3aibpe"/><path fill="url(#iuPvVZb)" clip-rule="evenodd" class="vhx3aibpe"/><g filter="url(#i95zVzb)"><rect transform="rotate(-28.166 17.093 17.229)" class="jmn2gbc3d"/></g><path fill="url(#ifBC6De)" class="d42r-tjxc"/><path fill="url(#io2ciIe)" transform="rotate(-23.31 19.316 10.56)" class="paxj_4b5d"/><g filter="url(#iDwq4nb)"><path fill="url(#ivintme)" class="tfatdpd4n"/><path fill="url(#iS1PW6b)" class="tfatdpd4n"/><path fill="url(#iplzoZd)" class="tfatdpd4n"/></g><g filter="url(#iBNhvic)"><path class="ia326zb5z"/><path fill="url(#izppjFd)" class="not34x1uk"/><path fill="url(#iPmdv5b)" class="not34x1uk"/><path fill="url(#iQrWROd)" class="not34x1uk"/><path fill="url(#i9T4fDd)" class="not34x1uk"/><path fill="url(#i3GFDpb)" class="not34x1uk"/></g><path fill="url(#itgqDSc)" class="debixurdy"/><path class="g7jpnjnbm"/><path fill="url(#ixhpiEb)" class="s5ybnt0dx"/><path fill="url(#io2aeGy)" class="hbwxtr23q"/><ellipse fill="url(#iMnw01d)" transform="rotate(24.583 -10.528 45.634)skewX(-.054)" class="f6mg5tnmy"/><path fill="url(#i7MahPc)" class="y15vqhqts"/><path fill="url(#iYZu1bb)" class="y15vqhqts"/><path fill="url(#ianGbyM)" class="y15vqhqts"/><path fill="url(#i7lMOGd)" class="crlv031te"/><path fill="url(#icVziGe)" class="crlv031te"/><path fill="url(#iElYgnY)" class="crlv031te"/><g filter="url(#ieXbmDb)"><path class="rm96ywbfz"/></g><g filter="url(#i0eQ1ge)"><path class="gqne_n3ft"/></g><g filter="url(#iXLx9rb)"><path class="x0_3yebsu"/><path fill="url(#izhX0Zb)" class="b9-qnjbqz"/></g><path fill="url(#ijrMZld)" class="b68sjlbqt"/><path fill="url(#it8TnFb)" class="b68sjlbqt"/><g filter="url(#iWtP3zc)"><path class="py7x40bno"/><path fill="url(#ihFXcob)" class="nwfwuv-2j"/><path fill="url(#i2GhYHc)" class="nwfwuv-2j"/><path fill="url(#iNqb3Fe)" class="nwfwuv-2j"/></g><g filter="url(#iyd0kOG)"><path class="vjlmb7b0u"/></g><g filter="url(#iTyzune)"><path class="grxvroqtp"/><path fill="url(#iMSDJpb)" class="k39cvgbwc"/><path fill="url(#isRoeSu)" class="k39cvgbwc"/><path fill="url(#iyq4jOc)" class="k39cvgbwc"/></g><g filter="url(#iR60Jue)"><path fill="url(#iMzglnc)" class="cm-j82bru"/></g><g filter="url(#i4Mwloe)"><rect stroke="url(#ilwtjOb)" transform="scale(-1 1)rotate(45 -25.612 -22.438)" class="gg2ehgbth"/></g><rect fill="url(#iD4h8Ac)" transform="scale(-1 1)rotate(45 -25.612 -22.438)" class="pxj138bcc"/><rect fill="url(#i4cwRAb)" transform="scale(-1 1)rotate(45 -25.612 -22.438)" class="pxj138bcc"/><path fill="url(#iuWli6b)" clip-rule="evenodd" class="z8q6w165u"/><path fill="url(#igxF1Pe)" clip-rule="evenodd" class="z8q6w165u"/><path fill="url(#iUxxQMd)" clip-rule="evenodd" class="z8q6w165u"/><path fill="url(#i2Agqzd)" clip-rule="evenodd" class="i4cw3dbzl"/><path fill="url(#i0CbYFe)" clip-rule="evenodd" class="i4cw3dbzl"/><circle fill="url(#i0wCBJc)" transform="matrix(-1 0 0 1 21.004 9.156)" class="ms4f1oj7g"/><circle fill="url(#iXGn3Cd)" transform="matrix(-1 0 0 1 21.004 9.156)" class="ms4f1oj7g"/><circle fill="url(#iNSGxke)" transform="matrix(-1 0 0 1 21.004 9.156)" class="ms4f1oj7g"/><g filter="url(#ikU5oPc)"><rect transform="matrix(-1 0 0 1 19.05 7.906)" class="lzcvp_xbr"/></g><rect transform="matrix(-1 0 0 1 18.695 10.291)" class="b61r46b1w"/><path clip-rule="evenodd" class="hs4lczb0m"/><path fill="url(#iVeWo9b)" clip-rule="evenodd" class="se_2l014i"/><path fill="url(#iv2lj0d)" clip-rule="evenodd" class="se_2l014i"/><path fill="url(#iTQivfd)" class="n13tpebnz"/><path fill="url(#ibGEcDE)" class="n13tpebnz"/><path class="c44z6ubbr"/><path fill="url(#iJWyGad)" class="zby_02b5m"/><path fill="url(#if3mcAd)" class="zby_02b5m"/><path fill="url(#ic56L7b)" class="e2s7i_vvv"/><path fill="url(#i9ABZvc)" class="e2s7i_vvv"/><path class="sq_2lmbxo"/><defs><radialGradient id="iibwJkc" cx="0" cy="0" r="1" gradientTransform="rotate(117.286 4.747 9.242)scale(.7412 .94396)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="fvok_qxen"/><stop offset="1" class="suyap8bzv"/></radialGradient><radialGradient id="iPhxkOc" cx="0" cy="0" r="1" gradientTransform="matrix(1.38633 1.36295 -2.28073 2.31985 -.033 1.45)" gradientUnits="userSpaceOnUse"><stop class="dq68o_b1o"/><stop offset=".919" class="o-96nfzox"/></radialGradient><radialGradient id="i0e765b" cx="0" cy="0" r="1" gradientTransform="matrix(.91857 -.05097 .06206 1.11853 11.285 8.81)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="d7kch3t0q"/><stop offset="1" class="admd7db0k"/></radialGradient><radialGradient id="isWd7Wd" cx="0" cy="0" r="1" gradientTransform="rotate(-134.539 7.552 2.931)scale(2.96161 4.32817)" gradientUnits="userSpaceOnUse"><stop class="re8izvbqw"/><stop offset="1" class="kgio6d1ee"/></radialGradient><radialGradient id="iP3fkvd" cx="0" cy="0" r="1" gradientTransform="matrix(2.31343 .9684 -1.3583 3.24489 9.226 6.389)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="iX4G2dc" cx="0" cy="0" r="1" gradientTransform="matrix(.88455 -.25484 .11838 .41088 9.277 9.872)" gradientUnits="userSpaceOnUse"><stop class="jkk-xsb9b"/><stop offset="1" class="g6je8pe2z"/></radialGradient><radialGradient id="ipFUNLe" cx="0" cy="0" r="1" gradientTransform="rotate(118.652 5.7 7.003)scale(1.72711 1.43803)" gradientUnits="userSpaceOnUse"><stop class="trve6xbqh"/><stop offset="1" class="d7ijg1brg"/></radialGradient><radialGradient id="iHu9Rwd" cx="0" cy="0" r="1" gradientTransform="matrix(-.78125 -.1953 .977 -3.9081 11.39 7.195)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="jm8-xeo6e"/><stop offset=".793" class="bewcn8buk"/></radialGradient><radialGradient id="iTbW8Yb" cx="0" cy="0" r="1" gradientTransform="matrix(.49331 1.0236 -1.6646 .80223 10.953 8.614)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="bervkqbmz"/><stop offset="1" class="c479w-bpn"/></radialGradient><radialGradient id="iWM7LSd" cx="0" cy="0" r="1" gradientTransform="matrix(-.29688 0 0 -.57678 13.859 8.89)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iSjZs2b" cx="0" cy="0" r="1" gradientTransform="matrix(-.27143 0 0 -.58739 14.041 8.913)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="i3n0iPb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71095 2.35327 -5.20382 -5.99476 18.899 12.29)" gradientUnits="userSpaceOnUse"><stop class="bbakdxbza"/><stop offset="1" class="so50u3yvk"/></radialGradient><radialGradient id="iC82hVd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.96875 1.8125 0 11.656 26.906)" gradientUnits="userSpaceOnUse"><stop class="l4a0dtbst"/><stop offset="1" class="l2gyjvi4r"/></radialGradient><radialGradient id="iQnOtjd" cx="0" cy="0" r="1" gradientTransform="matrix(2.14186 1.87499 -.94291 1.07712 7.391 21.875)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="vgnymzutm"/><stop offset="1" class="cttd8qtou"/></radialGradient><radialGradient id="iUjKRfd" cx="0" cy="0" r="1" gradientTransform="rotate(144.26 2.016 11.776)scale(1.23051 3.4979)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="ad7150bof"/><stop offset="1" class="touvs0bsg"/></radialGradient><radialGradient id="imc7P7d" cx="0" cy="0" r="1" gradientTransform="rotate(-134.195 7.383 8.758)scale(2.212 .64075)" gradientUnits="userSpaceOnUse"><stop class="jjhblb54u"/><stop offset="1" class="bq0pg0bco"/></radialGradient><radialGradient id="iB3PS0c" cx="0" cy="0" r="1" gradientTransform="rotate(137.394 1.204 10.498)scale(7.8608 1.6626)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="t4m41vbgx"/><stop offset="1" class="hi6yszbkt"/></radialGradient><radialGradient id="iElXErd" cx="0" cy="0" r="1" gradientTransform="matrix(6.96877 -7.18752 5.67939 5.50654 3.781 19.188)" gradientUnits="userSpaceOnUse"><stop offset=".93" class="qpejwlb8n"/><stop offset="1" class="p4686vbiy"/></radialGradient><radialGradient id="i0UffXd" cx="0" cy="0" r="1" gradientTransform="rotate(-144.397 8.399 13.807)scale(2.17397 2.91043)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="iU4AHwe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64636 -1.26563 1.72963 -2.24994 14.356 29.914)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="ilu9Sid" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.82813 .85156 0 11.203 27.734)" gradientUnits="userSpaceOnUse"><stop class="utx5lkfyi"/><stop offset="1" class="xn9ndqb6s"/></radialGradient><radialGradient id="iMJdzvc" cx="0" cy="0" r="1" gradientTransform="matrix(.00794 2.83955 -1.96718 .0055 10.357 13.289)" gradientUnits="userSpaceOnUse"><stop offset=".545" class="rzbmz9bky"/><stop offset="1" class="km6_kbc8h"/></radialGradient><radialGradient id="ipifqzd" cx="0" cy="0" r="1" gradientTransform="matrix(1.49 1.66988 -.81478 .72701 11.379 14.675)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="gw8ri5cen"/><stop offset="1" class="yxjq9v5jp"/></radialGradient><radialGradient id="iqAIzAe" cx="0" cy="0" r="1" gradientTransform="matrix(.23047 .0586 -.60662 2.38602 11.106 7.52)" gradientUnits="userSpaceOnUse"><stop class="a5dbyd6tf"/><stop offset="1" class="on8sxx3yx"/></radialGradient><radialGradient id="ifm02De" cx="0" cy="0" r="1" gradientTransform="matrix(-.52148 1.82813 -.23787 -.06785 12.149 5.781)" gradientUnits="userSpaceOnUse"><stop class="ak32k0b7k"/><stop offset="1" class="rknzqr02l"/></radialGradient><radialGradient id="iU5gO1b" cx="0" cy="0" r="1" gradientTransform="matrix(-.35156 .1875 -.70184 -1.31597 11.985 10.797)" gradientUnits="userSpaceOnUse"><stop class="kgukkhbth"/><stop offset="1" class="k8s01tfdv"/></radialGradient><radialGradient id="iM82Cwe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03124 1.09376 -.96833 -1.7983 12.031 8.688)" gradientUnits="userSpaceOnUse"><stop class="k0iy46b0f"/><stop offset="1" class="cwawnsbpb"/></radialGradient><radialGradient id="ifFq63d" cx="0" cy="0" r="1" gradientTransform="matrix(.76953 0 0 1.98438 9.715 9.172)" gradientUnits="userSpaceOnUse"><stop class="jdkxlmkke"/><stop offset="1" class="u8cibcbeo"/></radialGradient><radialGradient id="iaiQkHc" cx="0" cy="0" r="1" gradientTransform="matrix(-.76563 -.64062 1.04002 -1.24297 12.063 10.063)" gradientUnits="userSpaceOnUse"><stop class="nuhsp4_no"/><stop offset="1" class="ye033cbdf"/></radialGradient><radialGradient id="iyspjhe" cx="0" cy="0" r="1" gradientTransform="rotate(137.121 2.75 10.909)scale(3.58218 11.0839)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="xhhozw94f"/><stop offset=".963" class="op-7n-bkz"/></radialGradient><radialGradient id="iLgJ3yd" cx="0" cy="0" r="1" gradientTransform="rotate(99.197 -1.34 16.1)scale(1.09458 3.26059)" gradientUnits="userSpaceOnUse"><stop offset=".466" class="spsau2bne"/><stop offset="1" class="hbq83-d0t"/></radialGradient><radialGradient id="it2MJPc" cx="0" cy="0" r="1" gradientTransform="matrix(-.15645 1.10324 -2.89548 -.4106 14.47 20.532)" gradientUnits="userSpaceOnUse"><stop offset=".466" class="spsau2bne"/><stop offset="1" class="hbq83-d0t"/></radialGradient><radialGradient id="iKzvFHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.28295 .92188 -2.48547 -.76287 14.252 20.906)" gradientUnits="userSpaceOnUse"><stop offset=".369" class="spsau2bne"/><stop offset="1" class="hbq83-d0t"/></radialGradient><radialGradient id="i9F2U8b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37499 1.625 -1.79466 -1.51854 29.313 12)" gradientUnits="userSpaceOnUse"><stop class="o043sbvrw"/><stop offset="1" class="esuo4rbni"/></radialGradient><radialGradient id="i01dRld" cx="0" cy="0" r="1" gradientTransform="matrix(2.12183 -1.33219 1.13322 1.80492 26.394 14.207)" gradientUnits="userSpaceOnUse"><stop offset=".319" class="bpd58tbtp"/><stop offset="1" class="c62l-bbjc"/></radialGradient><radialGradient id="ifBC6De" cx="0" cy="0" r="1" gradientTransform="rotate(62.714 .846 18.458)scale(.7412 .94396)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="pxzqtt8pl"/><stop offset="1" class="lwe9_nbqv"/></radialGradient><radialGradient id="io2ciIe" cx="0" cy="0" r="1" gradientTransform="matrix(1.21193 1.13469 -1.89875 2.02802 19.457 12.24)" gradientUnits="userSpaceOnUse"><stop class="l8hx5tsqw"/><stop offset=".919" class="u555vebcp"/></radialGradient><radialGradient id="iS1PW6b" cx="0" cy="0" r="1" gradientTransform="rotate(-176.826 10.48 4.11)scale(.91998 1.12025)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="d7kch3t0q"/><stop offset="1" class="admd7db0k"/></radialGradient><radialGradient id="iplzoZd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.29689 1.53124 -1.48779 -1.26009 21.157 9.219)" gradientUnits="userSpaceOnUse"><stop offset=".437" class="qkiupezfq"/><stop offset="1" class="us4sdgeme"/></radialGradient><radialGradient id="izppjFd" cx="0" cy="0" r="1" gradientTransform="matrix(2.07725 -2.11097 3.08502 3.03574 21.24 10.355)" gradientUnits="userSpaceOnUse"><stop class="re8izvbqw"/><stop offset="1" class="kgio6d1ee"/></radialGradient><radialGradient id="iPmdv5b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.31343 .9684 -1.3583 -3.24489 22.774 6.373)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="iQrWROd" cx="0" cy="0" r="1" gradientTransform="matrix(-.88455 -.25484 .11838 -.41088 22.723 9.856)" gradientUnits="userSpaceOnUse"><stop class="jkk-xsb9b"/><stop offset="1" class="g6je8pe2z"/></radialGradient><radialGradient id="i9T4fDd" cx="0" cy="0" r="1" gradientTransform="matrix(.82812 1.51563 -1.26194 .68951 17.422 5.344)" gradientUnits="userSpaceOnUse"><stop class="trve6xbqh"/><stop offset="1" class="d7ijg1brg"/></radialGradient><radialGradient id="i3GFDpb" cx="0" cy="0" r="1" gradientTransform="matrix(.78125 -.19531 .97702 3.9081 20.61 7.18)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="jm8-xeo6e"/><stop offset=".793" class="bewcn8buk"/></radialGradient><radialGradient id="itgqDSc" cx="0" cy="0" r="1" gradientTransform="matrix(-.49331 1.0236 -1.6646 -.80223 21.047 8.599)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="bervkqbmz"/><stop offset="1" class="c479w-bpn"/></radialGradient><radialGradient id="ixhpiEb" cx="0" cy="0" r="1" gradientTransform="matrix(.29688 0 0 .57678 18.141 8.874)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="io2aeGy" cx="0" cy="0" r="1" gradientTransform="matrix(.27143 0 0 .58739 17.959 8.898)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="i7MahPc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.96875 1.8125 0 20.343 26.89)" gradientUnits="userSpaceOnUse"><stop class="l4a0dtbst"/><stop offset="1" class="l2gyjvi4r"/></radialGradient><radialGradient id="iYZu1bb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.14186 1.87499 -.94291 -1.07712 24.61 21.86)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="vgnymzutm"/><stop offset="1" class="cttd8qtou"/></radialGradient><radialGradient id="ianGbyM" cx="0" cy="0" r="1" gradientTransform="matrix(.99878 .71875 -2.04315 2.83916 21.468 20.14)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="ad7150bof"/><stop offset="1" class="touvs0bsg"/></radialGradient><radialGradient id="izhX0Zb" cx="0" cy="0" r="1" gradientTransform="matrix(1.542 -1.58594 .4594 .44667 25.75 20.14)" gradientUnits="userSpaceOnUse"><stop class="jjhblb54u"/><stop offset="1" class="bq0pg0bco"/></radialGradient><radialGradient id="ijrMZld" cx="0" cy="0" r="1" gradientTransform="matrix(5.78575 5.3214 -1.1255 1.22372 22.803 17.395)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="t4m41vbgx"/><stop offset="1" class="hi6yszbkt"/></radialGradient><radialGradient id="it8TnFb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.9688 -7.18748 5.67936 -5.50657 28.218 19.172)" gradientUnits="userSpaceOnUse"><stop offset=".014" class="qpejwlb8n"/><stop offset=".93" class="qpejwlb8n"/><stop offset="1" class="p4686vbiy"/></radialGradient><radialGradient id="i2GhYHc" cx="0" cy="0" r="1" gradientTransform="matrix(1.76758 -1.26563 1.69437 2.36637 24.81 29.906)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="isRoeSu" cx="0" cy="0" r="1" gradientTransform="matrix(1.64636 -1.26562 1.72962 2.24995 17.644 29.898)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="iMzglnc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.82813 .85156 0 20.797 27.719)" gradientUnits="userSpaceOnUse"><stop class="utx5lkfyi"/><stop offset="1" class="xn9ndqb6s"/></radialGradient><radialGradient id="iD4h8Ac" cx="0" cy="0" r="1" gradientTransform="rotate(18.094 -5.973 -4.332)scale(5.2482 3.63584)" gradientUnits="userSpaceOnUse"><stop offset=".492" class="bhv6r6bju"/><stop offset="1" class="zfu-fxb-u"/></radialGradient><radialGradient id="i4cwRAb" cx="0" cy="0" r="1" gradientTransform="rotate(132.455 .956 2.189)scale(1.40764 3.24456)" gradientUnits="userSpaceOnUse"><stop offset=".134" class="lui_krbte"/><stop offset="1" class="e1m0hbbbn"/></radialGradient><radialGradient id="igxF1Pe" cx="0" cy="0" r="1" gradientTransform="rotate(165.735 9.978 5.06)scale(.2378 2.46193)" gradientUnits="userSpaceOnUse"><stop class="a5dbyd6tf"/><stop offset="1" class="on8sxx3yx"/></radialGradient><radialGradient id="iUxxQMd" cx="0" cy="0" r="1" gradientTransform="matrix(.52148 1.82813 -.23787 .06785 19.851 5.766)" gradientUnits="userSpaceOnUse"><stop class="ak32k0b7k"/><stop offset="1" class="rknzqr02l"/></radialGradient><radialGradient id="i0CbYFe" cx="0" cy="0" r="1" gradientTransform="matrix(.35156 .1875 -.70186 1.31595 20.016 10.781)" gradientUnits="userSpaceOnUse"><stop class="kgukkhbth"/><stop offset="1" class="k8s01tfdv"/></radialGradient><radialGradient id="i0wCBJc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03124 1.09376 -.96833 -1.7983 2.316 .797)" gradientUnits="userSpaceOnUse"><stop class="k0iy46b0f"/><stop offset="1" class="cwawnsbpb"/></radialGradient><radialGradient id="iXGn3Cd" cx="0" cy="0" r="1" gradientTransform="matrix(.76953 0 0 1.98438 0 1.281)" gradientUnits="userSpaceOnUse"><stop class="jdkxlmkke"/><stop offset="1" class="u8cibcbeo"/></radialGradient><radialGradient id="iNSGxke" cx="0" cy="0" r="1" gradientTransform="matrix(-.76563 -.64062 1.04002 -1.24297 2.348 2.172)" gradientUnits="userSpaceOnUse"><stop class="nuhsp4_no"/><stop offset="1" class="ye033cbdf"/></radialGradient><radialGradient id="iVeWo9b" cx="0" cy="0" r="1" gradientTransform="matrix(1.49685 3.75 -10.37919 4.14298 19.25 15.813)" gradientUnits="userSpaceOnUse"><stop offset=".368" class="vkuvqbbwu"/><stop offset=".969" class="elr5y7baq"/></radialGradient><radialGradient id="iv2lj0d" cx="0" cy="0" r="1" gradientTransform="matrix(-.96876 1.75 -2.0554 -1.13783 24.219 12.813)" gradientUnits="userSpaceOnUse"><stop class="r_8k9swvo"/><stop offset="1" class="q9ojxt_ur"/></radialGradient><radialGradient id="ibGEcDE" cx="0" cy="0" r="1" gradientTransform="matrix(-2.00452 .04153 -.0243 -1.17307 17.327 18.325)" gradientUnits="userSpaceOnUse"><stop offset=".744" class="lid3ide5q"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="if3mcAd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .49784 -1.34351 0 16.64 19.205)" gradientUnits="userSpaceOnUse"><stop class="z_yn3vbua"/><stop offset="1" class="j6lbcibwa"/></radialGradient><radialGradient id="i9ABZvc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9726 .04153 -.0247 -1.17306 17.336 18.952)" gradientUnits="userSpaceOnUse"><stop offset=".744" class="lid3ide5q"/><stop offset="1" class="r2t9jab3e"/></radialGradient><linearGradient id="i270lUc" x1="11.625" x2="14.741" y1="9.617" y2="9.804" gradientUnits="userSpaceOnUse"><stop class="egm-dub4f"/><stop offset="1" class="zhwoohbuw"/></linearGradient><linearGradient id="iMnw01d" x1="-.007" x2=".195" y1=".054" y2=".12" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="ieLIobc" x1="6.625" x2="8.406" y1="21.313" y2="19.625" gradientUnits="userSpaceOnUse"><stop class="xylxrh5lr"/><stop offset="1" class="dpng9pbvi"/></linearGradient><linearGradient id="iUT4Ved" x1="8.328" x2="8.153" y1="20.703" y2="20.52" gradientUnits="userSpaceOnUse"><stop class="o5qj3ac-m"/><stop offset="1" class="a151cabub"/></linearGradient><linearGradient id="iCzBbld" x1="5.563" x2="6.844" y1="20.75" y2="20.813" gradientUnits="userSpaceOnUse"><stop offset=".28" class="azjp5ub3a"/><stop offset="1" class="yvalde4js"/></linearGradient><linearGradient id="i7cSiHe" x1="2.251" x2="2.836" y1="29.563" y2="29.695" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="iRppiQe" x1="5.625" x2="5.625" y1="29.922" y2="29.598" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="i1tvNQv" x1="9.756" x2="10.3" y1="29.688" y2="29.671" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="iSYTjPd" x1="12.899" x2="12.899" y1="29.914" y2="29.59" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="iYf8PSc" x1="10.365" x2="10.365" y1="11.554" y2="16.128" gradientUnits="userSpaceOnUse"><stop class="d9dzcxb5n"/><stop offset="1" class="aqyl6fvtq"/></linearGradient><linearGradient id="i8VLSDb" x1="11.977" x2="10.903" y1="6.828" y2="7.734" gradientUnits="userSpaceOnUse"><stop class="nzvqyeb9k"/><stop offset="1" class="cnb6h8b8g"/></linearGradient><linearGradient id="iCB9Zxs" x1="11.406" x2="12.758" y1="10.438" y2="12.266" gradientUnits="userSpaceOnUse"><stop class="mfaot4byg"/><stop offset="1" class="fx9brcb0h"/></linearGradient><linearGradient id="irkpnyI" x1="13.406" x2="13.641" y1="22.078" y2="21.648" gradientUnits="userSpaceOnUse"><stop offset=".245" class="o5wphbctr"/><stop offset="1" class="bev6mnbks"/></linearGradient><linearGradient id="i34FvUb" x1="26.394" x2="26.394" y1="11.288" y2="11.703" gradientUnits="userSpaceOnUse"><stop class="mbxf6yyls"/><stop offset="1" class="rixtyr4np"/></linearGradient><linearGradient id="iuPvVZb" x1="29.203" x2="28.75" y1="14.953" y2="14.688" gradientUnits="userSpaceOnUse"><stop class="mbxf6yyls"/><stop offset="1" class="rixtyr4np"/></linearGradient><linearGradient id="ivintme" x1="20.375" x2="17.259" y1="9.601" y2="9.789" gradientUnits="userSpaceOnUse"><stop offset=".607" class="x9w8qi-jn"/><stop offset="1" class="f8pl1cbjp"/></linearGradient><linearGradient id="i7lMOGd" x1="25.375" x2="23.593" y1="21.297" y2="19.609" gradientUnits="userSpaceOnUse"><stop class="xylxrh5lr"/><stop offset="1" class="dpng9pbvi"/></linearGradient><linearGradient id="icVziGe" x1="23.672" x2="23.847" y1="20.688" y2="20.504" gradientUnits="userSpaceOnUse"><stop class="o5qj3ac-m"/><stop offset="1" class="a151cabub"/></linearGradient><linearGradient id="iElYgnY" x1="26.437" x2="25.156" y1="20.734" y2="20.797" gradientUnits="userSpaceOnUse"><stop offset=".28" class="azjp5ub3a"/><stop offset="1" class="yvalde4js"/></linearGradient><linearGradient id="ihFXcob" x1="29.749" x2="29.164" y1="29.547" y2="29.68" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="iNqb3Fe" x1="26.375" x2="26.375" y1="29.906" y2="29.582" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="iMSDJpb" x1="22.244" x2="21.7" y1="29.672" y2="29.655" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="iyq4jOc" x1="19.101" x2="19.101" y1="29.898" y2="29.574" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="ilwtjOb" x1="1.732" x2="1.732" y1="0" y2="4.574" gradientUnits="userSpaceOnUse"><stop class="d9dzcxb5n"/><stop offset="1" class="aqyl6fvtq"/></linearGradient><linearGradient id="iuWli6b" x1="20.023" x2="21.097" y1="6.813" y2="7.719" gradientUnits="userSpaceOnUse"><stop class="nzvqyeb9k"/><stop offset="1" class="cnb6h8b8g"/></linearGradient><linearGradient id="i2Agqzd" x1="20.593" x2="19.242" y1="10.422" y2="12.25" gradientUnits="userSpaceOnUse"><stop class="mfaot4byg"/><stop offset="1" class="fx9brcb0h"/></linearGradient><linearGradient id="iTQivfd" x1="16.29" x2="18.034" y1="18.388" y2="18.388" gradientUnits="userSpaceOnUse"><stop offset=".527" class="om8lrbchi"/><stop offset="1" class="hsvyf4b5t"/></linearGradient><linearGradient id="iJWyGad" x1="17.375" x2="17.375" y1="19.975" y2="19.5" gradientUnits="userSpaceOnUse"><stop class="ama23x97l"/><stop offset="1" class="naks3_bia"/></linearGradient><linearGradient id="ic56L7b" x1="16.315" x2="18.032" y1="19.016" y2="19.016" gradientUnits="userSpaceOnUse"><stop offset=".527" class="om8lrbchi"/><stop offset="1" class="hsvyf4b5t"/></linearGradient><filter id="iFqdBrb" width="5.019" height="5.69" x="10.122" y="6.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.533333 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23624"/></filter><filter id="iKWRZvp" width="5.991" height="5.966" x="8.682" y="4.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.607843 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23624"/></filter><filter id="iA7fV3d" width="2.691" height="1.989" x="15.879" y="12.66" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.478431 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23624"/></filter><filter id="i9EePFe" width="10.808" height="5.007" x="8.491" y="11.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.878431 0 0 0 0 0.541176 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23624"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.478431 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23624" result="effect2_innerShadow_3987_23624"/></filter><filter id="iGYNSwc" width="4.146" height="5.805" x="2.788" y="21.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.819608 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23624"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.666667 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23624" result="effect2_innerShadow_3987_23624"/></filter><filter id="iVAfdvd" width="9.426" height="8.574" x="2.717" y="11.3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.501961 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23624"/></filter><filter id="iiP2T6c" width="5.878" height="6.781" x="2.144" y="15.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.501961 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23624"/></filter><filter id="ijE35vb" width="5.139" height="3.208" x="2.051" y="26.914" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23624"/></filter><filter id="i0zvdke" width="2.686" height="1.05" x="2.698" y="26.914" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.776471 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23624"/></filter><filter id="iEoVTqe" width="4.9" height="3.308" x="9.456" y="26.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23624"/></filter><filter id="ie8ngTb" width="2.288" height="1.065" x="9.756" y="26.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.690196 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23624"/></filter><filter id="ikmVnye" width="5.149" height="5.149" x="5.666" y="11.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23624" stdDeviation=".125"/></filter><filter id="inRv5rb" width="1.258" height=".393" x="12.95" y="7.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.632517 0 0 0 0 0.207713 0 0 0 0 0.0745123 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23624"/></filter><filter id="iAmrHie" width="1.796" height="1.427" x="13.37" y="19.239" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.756863 0 0 0 0 0.470588 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23624"/></filter><filter id="i95zVzb" width="1.065" height="1.475" x="17.228" y="16.853" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.635294 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23624"/></filter><filter id="iDwq4nb" width="5.019" height="5.69" x="16.859" y="6.421" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.556863 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23624"/></filter><filter id="iBNhvic" width="5.991" height="5.966" x="17.327" y="4.697" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.607843 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23624"/></filter><filter id="ieXbmDb" width="4.146" height="5.805" x="25.066" y="21.484" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.819608 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23624"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.666667 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23624" result="effect2_innerShadow_3987_23624"/></filter><filter id="i0eQ1ge" width="9.426" height="8.574" x="19.857" y="11.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.501961 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23624"/></filter><filter id="iXLx9rb" width="5.878" height="6.781" x="23.978" y="15.164" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.501961 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23624"/></filter><filter id="iWtP3zc" width="5.139" height="3.208" x="24.61" y="26.898" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23624"/></filter><filter id="iyd0kOG" width="2.686" height="1.05" x="26.915" y="26.898" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.776471 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23624"/></filter><filter id="iTyzune" width="4.9" height="3.308" x="17.344" y="26.891" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23624"/></filter><filter id="iR60Jue" width="2.288" height="1.065" x="20.156" y="26.891" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.690196 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23624"/></filter><filter id="i4Mwloe" width="5.149" height="5.149" x="21.185" y="11.806" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23624" stdDeviation=".125"/></filter><filter id="ikU5oPc" width="1.258" height=".393" x="17.793" y="7.806" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.632517 0 0 0 0 0.207713 0 0 0 0 0.0745123 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23624"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-wrestling" /></template>
<style>
.a151cabub {
  stop-color: var(--svg-color--fd5220, #FD5220);
  stop-opacity: 0;
}

.a5dbyd6tf {
  stop-color: var(--svg-color--5e4d44, #5E4D44);
}

.aci6iobrg {
  d: path("m2.919 26.99l-.66 2.62a.25.25 0 0 0 .242.312h4.441c.102 0 .196-.06.22-.159c.127-.503-.196-.866-.763-1.157a87 87 0 0 1-1.695-.9l.375-.719a.05.05 0 0 0-.044-.073h-2.02a.1.1 0 0 0-.096.076");
}

.ad7150bof {
  stop-color: var(--svg-color--e8a22e, #E8A22E);
}

.admd7db0k {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
  stop-opacity: 0;
}

.ae6-jibhp {
  d: path("m9.844 27.851l-.088-.89a.05.05 0 0 1 .05-.055h1.988a.05.05 0 0 1 .05.05v.767c.559.261 1.627.807 2.074 1.117c.378.261.441.563.438.801c-.003.155-.143.273-.298.273h-3.964a.25.25 0 0 1-.25-.25z");
}

.ak32k0b7k {
  stop-color: var(--svg-color--695d73, #695D73);
}

.al_auo8nl {
  stop-color: var(--svg-color--6d6a94, #6D6A94);
  stop-opacity: 0;
}

.ama23x97l {
  stop-color: var(--svg-color--e19839, #E19839);
}

.aqyl6fvtq {
  stop-color: var(--svg-color--ff7837, #FF7837);
}

.azjp5ub3a {
  stop-color: var(--svg-color--ed3424, #ED3424);
}

.b3xtyyrgk {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m9.844 27.851l-.088-.89a.05.05 0 0 1 .05-.055h1.988a.05.05 0 0 1 .05.05v.767c.559.261 1.627.807 2.074 1.117c.378.261.441.563.438.801c-.003.155-.143.273-.298.273h-3.964a.25.25 0 0 1-.25-.25z");
}

.b61r46b1w {
  width: 0.855px;
  height: 0.248px;
  fill: var(--svg-color--87014d, #87014D);
  rx: 0.124px;
}

.b68sjlbqt {
  d: path("M21.353 12.118a2.697 2.697 0 0 1 3.821-.08l3.234 3.126l.045.034q.1.096.188.2l.43.43c.373.326 1.069 1.252.66 2.844a63 63 0 0 1-.938 3.239a.05.05 0 0 1-.02.026l-.027.008h-3.025a.05.05 0 0 1-.05-.054c.075-.715.268-1.758.268-1.758l-.876-.735a2.7 2.7 0 0 1-.38-.308l-3.261-3.178a2.696 2.696 0 0 1-.069-3.794");
}

.b9-qnjbqz {
  d: path("m29.072 15.828l-.664-.664l-3.68 3.953l1.21 1.016s-.192 1.043-.267 1.758a.05.05 0 0 0 .05.054h3.025a.05.05 0 0 0 .047-.034c.16-.506.565-1.792.938-3.24c.409-1.591-.287-2.517-.66-2.843");
}

.bbakdxbza {
  stop-color: var(--svg-color--e48527, #E48527);
}

.bervkqbmz {
  stop-color: var(--svg-color--ffd040, #FFD040);
}

.bev6mnbks {
  stop-color: var(--svg-color--f9bf3b, #F9BF3B);
  stop-opacity: 0;
}

.bewcn8buk {
  stop-color: var(--svg-color--ffca2f, #FFCA2F);
  stop-opacity: 0;
}

.bhv6r6bju {
  stop-color: var(--svg-color--ffd83f, #FFD83F);
}

.bmlajh73u {
  d: path("M14.955 9.099a1.1 1.1 0 0 1-.28-.497h-.196v1.223c.234.149.568.125.667-.098c.085-.19.021-.429-.191-.628");
}

.bpd58tbtp {
  stop-color: var(--svg-color--ea760b, #EA760B);
}

.bq0pg0bco {
  stop-color: var(--svg-color--ff5128, #FF5128);
  stop-opacity: 0;
}

.c44z6ubbr {
  fill: var(--svg-color--efaa37, #EFAA37);
  d: path("M15.846 19.59c0-.212.173-.385.386-.385h1.385l.308.77H16.23a.385.385 0 0 1-.385-.385");
}

.c479w-bpn {
  stop-color: var(--svg-color--fead30, #FEAD30);
}

.c62l-bbjc {
  stop-color: var(--svg-color--ffa31c, #FFA31C);
  stop-opacity: 0;
}

.cgkj-oamf {
  fill: var(--svg-color--ffb330, #FFB330);
  d: path("m16.074 13.137l.536-.516c.123-.11.461-.332.824-.332h.988a.476.476 0 1 1 0 .953h-.866a.22.22 0 0 0-.202.129l-.033.07a.34.34 0 0 0-.002.287l.557-.038a.516.516 0 0 1 .07 1.029l-.669.046c-.739 1.026-1.884 2.055-3.902 2.229c-2.386.056-3.712-1.182-4.258-1.691l-.108-.1l-.103-.092a1.15 1.15 0 1 1 1.47-1.769c.023.02.077-.013.133-.046c.064-.038.132-.078.163-.05q.08.07.17.153c.497.455 1.236 1.132 2.533 1.132c.391 0 .884-.013 1.408-.336c.51-.314.937-.7 1.167-.95a.7.7 0 0 1 .124-.108");
}

.cm-j82bru {
  d: path("M20.156 27.696v-.755a.05.05 0 0 1 .05-.05h1.989a.05.05 0 0 1 .05.055l-.089.89v.02z");
}

.cnb6h8b8g {
  stop-color: var(--svg-color--241e28, #241E28);
}

.crlv031te {
  d: path("m24.855 21.796l1.082-1.007l1.149-1.023l-3.133-1.907a79 79 0 0 1-1.4 1.66a.05.05 0 0 0 .003.069l2.23 2.206a.05.05 0 0 0 .07.002");
}

.csfglkqju {
  d: path("m16.074 13.137l.536-.516c.123-.11.461-.332.824-.332h.988a.476.476 0 1 1 0 .953h-.866a.22.22 0 0 0-.202.129l-.033.07a.34.34 0 0 0-.002.287l.557-.038a.516.516 0 0 1 .07 1.029l-.669.046c-.739 1.026-1.884 2.055-3.902 2.229c-2.386.056-3.712-1.182-4.258-1.691l-.108-.1l-.103-.092a1.15 1.15 0 1 1 1.47-1.769c.023.02.077-.013.133-.046c.064-.038.132-.078.163-.05q.08.07.17.153c.497.455 1.236 1.132 2.533 1.132c.391 0 .884-.013 1.408-.336c.51-.314.937-.7 1.167-.95a.7.7 0 0 1 .124-.108");
}

.ct6_m01bp {
  stop-color: var(--svg-color--5e5a92, #5E5A92);
}

.cttd8qtou {
  stop-color: var(--svg-color--d58b3f, #D58B3F);
  stop-opacity: 0;
}

.cwawnsbpb {
  stop-color: var(--svg-color--403547, #403547);
}

.cz78e2buv {
  cx: 10.996px;
  cy: 9.172px;
  r: 1.281px;
}

.d42r-tjxc {
  d: path("M17.045 9.083c.17-.16.258-.398.28-.497h.196V9.81c-.234.15-.568.126-.667-.097c-.085-.191-.021-.43.191-.629");
}

.d7ijg1brg {
  stop-color: var(--svg-color--ffd835, #FFD835);
  stop-opacity: 0;
}

.d7kch3t0q {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
}

.d9dzcxb5n {
  stop-color: var(--svg-color--ff772a, #FF772A);
}

.debixurdy {
  d: path("m20.306 9.616l.217-1.565a.79.79 0 0 1-.217 1.565");
}

.diyyu_bjy {
  fill: var(--svg-color--f4a72a, #F4A72A);
  fill-rule: evenodd;
  d: path("M15.127 19.616a.4.4 0 0 1-.188.534l-.996.476a.4.4 0 0 1-.346-.721l.996-.477a.4.4 0 0 1 .534.188");
}

.dm4voe-la {
  d: path("M0 0h2.371v3.351H0z");
}

.dpng9pbvi {
  stop-color: var(--svg-color--fe5823, #FE5823);
}

.dq68o_b1o {
  stop-color: var(--svg-color--c26918, #C26918);
}

.e1m0hbbbn {
  stop-color: var(--svg-color--e68f26, #E68F26);
  stop-opacity: 0;
}

.e2s7i_vvv {
  d: path("M15.503 18.853c0-.215.172-.39.384-.39h1.999v.78h-2a.387.387 0 0 1-.383-.39");
}

.egm-dub4f {
  stop-color: var(--svg-color--ffc33e, #FFC33E);
}

.ekab7hynw {
  d: path("m7.145 21.811l-1.082-1.006l-1.149-1.024l3.133-1.906a78 78 0 0 0 1.4 1.66a.05.05 0 0 1-.003.068l-2.23 2.207a.05.05 0 0 1-.07.001");
}

.elr5y7baq {
  stop-color: var(--svg-color--d3843a, #D3843A);
}

.esuo4rbni {
  stop-color: var(--svg-color--ffc230, #FFC230);
}

.f6mg5tnmy {
  rx: 0.07px;
  ry: 0.096px;
}

.f8pl1cbjp {
  stop-color: var(--svg-color--f3a028, #F3A028);
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.fqdryqbjp {
  d: path("M11.844 27.712v-.756a.05.05 0 0 0-.05-.05H9.805a.05.05 0 0 0-.05.055l.089.89v.02z");
}

.ft5dv1b6b {
  fill: none;
}

.fvok_qxen {
  stop-color: var(--svg-color--ffbf42, #FFBF42);
}

.fx9brcb0h {
  stop-color: var(--svg-color--704459, #704459);
}

.g6je8pe2z {
  stop-color: var(--svg-color--ffd237, #FFD237);
  stop-opacity: 0;
}

.g7jpnjnbm {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.84 8.898h1.076c0-.425-.24-.77-.538-.77c-.297 0-.538.345-.538.77");
}

.gg2ehgbth {
  width: 3.464px;
  height: 4.574px;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  rx: 1.732px;
}

.gqne_n3ft {
  fill: var(--svg-color--ff6a39, #FF6A39);
  d: path("M25.174 12.039a2.696 2.696 0 0 0-3.752 3.873l3.261 3.178a2.71 2.71 0 1 0 3.77-3.892z");
}

.grxvroqtp {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m22.156 27.836l.088-.89a.05.05 0 0 0-.05-.055h-1.988a.05.05 0 0 0-.05.05v.766c-.559.262-1.627.807-2.074 1.117c-.378.261-.441.563-.438.801c.003.156.143.273.298.273h3.964a.25.25 0 0 0 .25-.25z");
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gw8ri5cen {
  stop-color: var(--svg-color--f49326, #F49326);
}

.h6ffxpb2n {
  width: 0.855px;
  height: 0.248px;
  x: 13.305px;
  y: 10.307px;
  fill: var(--svg-color--87014d, #87014D);
  rx: 0.124px;
}

.hbq83-d0t {
  stop-color: var(--svg-color--f5a333, #F5A333);
}

.hbwxtr23q {
  d: path("m18.285 8.898l.005-.079c0-.201-.086-.365-.191-.365s-.191.164-.191.365l.004.079z");
}

.hh9ibwbje {
  stop-color: var(--svg-color--5e5a92, #5E5A92);
  stop-opacity: 0;
}

.hi6yszbkt {
  stop-color: var(--svg-color--ff5c2b, #FF5C2B);
  stop-opacity: 0;
}

.hrro0vowg {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.16 8.914h-1.076c0-.426.24-.77.538-.77c.297 0 .538.344.538.77");
}

.hs4lczb0m {
  fill: var(--svg-color--ffca33, #FFCA33);
  fill-rule: evenodd;
  d: path("M23.845 12.67c.627.167 1 .81.833 1.438c-.25.937-.944 2.3-2.011 3.45c-1.075 1.157-2.67 2.248-4.615 2.413a1.175 1.175 0 0 1-1.27-1.071c-.055-.647.363-1.162 1.01-1.217c1.206-.141 2.261-.825 3.112-1.74c.859-.925 1.37-1.944 1.503-2.44c.167-.627.811-1 1.438-.833");
}

.hsvyf4b5t {
  stop-color: var(--svg-color--f5b436, #F5B436);
  stop-opacity: 0;
}

.i_emxkhmq {
  stop-color: var(--svg-color--442f88, #442F88);
}

.i4cw3dbzl {
  fill-rule: evenodd;
  d: path("M20.898 9.847a.25.25 0 0 0-.325.137c-.1.247-.285.645-.511 1.038c-.23.4-.488.767-.733.976a.25.25 0 1 0 .325.38c.312-.267.606-.697.841-1.106c.24-.415.433-.834.541-1.1a.25.25 0 0 0-.138-.325");
}

.ia326zb5z {
  fill: var(--svg-color--ffba23, #FFBA23);
  d: path("M17.454 5.477c.258-.53.769-.645 1.071-.629c.936.051.868.542 1.889.332c.894-.184 1.356-.263 1.739-.09l.007.004c.378.171 1.158.525 1.158 2.12c0 1.47-.525 2.246-.778 2.523l.05.018c.252.091.355.359.265.61c-.078.216-.35.34-.694.285c-.392-.061-.68-.115-.905-.16a.27.27 0 0 1-.218-.265v-1.21c0-.51-.36-.814-.518-.905c-.017-.526-.179-.768-.442-.896c-.437-.21-.573-.106-1.616-.17c-1.05-.063-1.332-.904-1.008-1.567");
}

.ibwv6bbpe {
  fill-rule: evenodd;
  d: path("M13.393 20.623a.45.45 0 0 1 .624-.12l.973.655a.45.45 0 0 1-.503.746l-.973-.656a.45.45 0 0 1-.121-.625");
}

.j6lbcibwa {
  stop-color: var(--svg-color--ffcc3d, #FFCC3D);
  stop-opacity: 0;
}

.jdkxlmkke {
  stop-color: var(--svg-color--656262, #656262);
}

.jjhblb54u {
  stop-color: var(--svg-color--ff5128, #FF5128);
}

.jkk-xsb9b {
  stop-color: var(--svg-color--ffd237, #FFD237);
}

.jm8-xeo6e {
  stop-color: var(--svg-color--ea981a, #EA981A);
}

.jmn2gbc3d {
  width: 0.764px;
  height: 1.4px;
  x: 17.093px;
  y: 17.229px;
  fill: var(--svg-color--ffc427, #FFC427);
  rx: 0.382px;
}

.jsdr1ac4o {
  fill: var(--svg-color--ff6a39, #FF6A39);
  d: path("m2.928 15.844l.664-.664l3.68 3.953l-1.21 1.015s.192 1.044.267 1.758a.05.05 0 0 1-.05.055H3.255a.05.05 0 0 1-.047-.035a63 63 0 0 1-.938-3.238c-.409-1.592.287-2.519.66-2.844");
}

.jxqc6mbch {
  d: path("M10.647 12.133a2.697 2.697 0 0 0-3.821-.079L3.592 15.18l-.045.034q-.1.096-.188.2l-.43.43c-.373.325-1.069 1.252-.66 2.844c.372 1.447.778 2.733.938 3.239q.005.016.02.026l.027.008h3.025a.05.05 0 0 0 .05-.055c-.074-.714-.268-1.758-.268-1.758l.876-.734q.2-.135.38-.309l3.261-3.178a2.696 2.696 0 0 0 .069-3.794");
}

.k0iy46b0f {
  stop-color: var(--svg-color--625a6a, #625A6A);
}

.k39cvgbwc {
  d: path("m22.156 27.836l.088-.89a.05.05 0 0 0-.05-.055h-1.988a.05.05 0 0 0-.05.05v.766c-.559.262-1.627.807-2.074 1.117c-.378.261-.441.563-.438.801c.003.156.143.273.298.273h3.964a.25.25 0 0 0 .25-.25z");
}

.k8s01tfdv {
  stop-color: var(--svg-color--5e5663, #5E5663);
  stop-opacity: 0;
}

.kgio6d1ee {
  stop-color: var(--svg-color--ffa526, #FFA526);
  stop-opacity: 0;
}

.kgukkhbth {
  stop-color: var(--svg-color--5e5663, #5E5663);
}

.km6_kbc8h {
  stop-color: var(--svg-color--ffc437, #FFC437);
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l2gyjvi4r {
  stop-color: var(--svg-color--da9628, #DA9628);
}

.l4a0dtbst {
  stop-color: var(--svg-color--f6b939, #F6B939);
}

.l8hx5tsqw {
  stop-color: var(--svg-color--ca6f1f, #CA6F1F);
}

.lid3ide5q {
  stop-color: var(--svg-color--f5a129, #F5A129);
  stop-opacity: 0;
}

.lui_krbte {
  stop-color: var(--svg-color--e68f26, #E68F26);
}

.lwe9_nbqv {
  stop-color: var(--svg-color--dd8332, #DD8332);
}

.lzcvp_xbr {
  width: 1.258px;
  height: 0.293px;
  fill: var(--svg-color--c76452, #C76452);
  rx: 0.146px;
}

.mbxf6yyls {
  stop-color: var(--svg-color--e8bb3d, #E8BB3D);
}

.mfaot4byg {
  stop-color: var(--svg-color--3f3943, #3F3943);
}

.mpldlh5nb {
  width: 1.258px;
  height: 0.293px;
  x: 12.95px;
  y: 7.922px;
  fill: var(--svg-color--c76452, #C76452);
  rx: 0.146px;
}

.ms4f1oj7g {
  r: 1.281px;
}

.n13tpebnz {
  d: path("M15.464 18.226a.39.39 0 0 1 .39-.39h2.032v.78h-2.032a.39.39 0 0 1-.39-.39");
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.naks3_bia {
  stop-color: var(--svg-color--e19839, #E19839);
  stop-opacity: 0;
}

.not34x1uk {
  d: path("M17.454 5.477c.258-.53.769-.645 1.071-.629c.936.051.868.542 1.889.332c.894-.184 1.356-.263 1.739-.09l.007.004c.378.171 1.158.525 1.158 2.12c0 1.47-.525 2.246-.778 2.523l.05.018c.252.091.355.359.265.61c-.078.216-.35.34-.694.285c-.392-.061-.68-.115-.905-.16a.27.27 0 0 1-.218-.265v-1.21c0-.51-.36-.814-.518-.905c-.017-.526-.179-.768-.442-.896c-.437-.21-.573-.106-1.616-.17c-1.05-.063-1.332-.904-1.008-1.567");
}

.nuhsp4_no {
  stop-color: var(--svg-color--5c405f, #5C405F);
}

.nwfwuv-2j {
  d: path("m29.081 26.974l.66 2.621a.25.25 0 0 1-.242.311h-4.441c-.102 0-.196-.06-.22-.158c-.127-.504.196-.866.763-1.158a86 86 0 0 0 1.696-.9l-.376-.718a.05.05 0 0 1 .044-.074h2.02a.1.1 0 0 1 .096.076");
}

.nzvqyeb9k {
  stop-color: var(--svg-color--4f415a, #4F415A);
}

.o-96nfzox {
  stop-color: var(--svg-color--ff9425, #FF9425);
}

.o043sbvrw {
  stop-color: var(--svg-color--fd4, #FD4);
}

.o5qj3ac-m {
  stop-color: var(--svg-color--e73d40, #E73D40);
}

.o5wphbctr {
  stop-color: var(--svg-color--f9bf3b, #F9BF3B);
}

.o98gvps8d {
  d: path("M14.546 5.493a1.12 1.12 0 0 0-1.071-.629c-.936.051-.868.541-1.889.331c-.894-.184-1.356-.262-1.739-.089l-.007.004c-.378.17-1.158.525-1.158 2.12c0 1.47.525 2.245.778 2.523l-.05.018c-.252.09-.356.358-.265.61c.078.215.35.339.694.285c.392-.062.68-.115.905-.16a.27.27 0 0 0 .217-.265V9.03c0-.51.36-.814.52-.905c.016-.527.178-.769.441-.896c.437-.211.573-.107 1.617-.17c1.05-.064 1.33-.905 1.007-1.567");
}

.ofgsb13it {
  d: path("M14.71 8.05c-.041-.87-.324-1.29-.457-1.413H10.19l-.068 3.44c.943 2.307 3.823 2.406 4.253 1.571c.43-.834.384-2.589.336-3.597");
}

.om8lrbchi {
  stop-color: var(--svg-color--fc3, #FC3);
}

.on8sxx3yx {
  stop-color: var(--svg-color--5e4d44, #5E4D44);
  stop-opacity: 0;
}

.oneeefb7d {
  d: path("m9.172 23.46l-2.039-1.804L9.29 19.47a69 69 0 0 0 1.903 2.277c.67.77.758 1.77.738 2.262l-.102 2.898H9.805c-.068-.734-.211-2.308-.242-2.726a.95.95 0 0 0-.39-.72");
}

.op-7n-bkz {
  stop-color: var(--svg-color--ec9f38, #EC9F38);
}

.oybn7vbqt {
  stop-color: var(--svg-color--6d6a94, #6D6A94);
}

.p4686vbiy {
  stop-color: var(--svg-color--fb5d03, #FB5D03);
}

.paxj_4b5d {
  d: path("M19.316 10.56h2.371v3.351h-2.371z");
}

.pq-elqbjd {
  fill: var(--svg-color--c16c25, #C16C25);
  d: path("m16.47 12.964l-.59.57l.297 1.115l1.425-.506l-.08-.116a.32.32 0 0 1-.023-.311l.03-.064a.2.2 0 0 1 .185-.118h.42a.437.437 0 1 0 0-.874h-.907c-.333 0-.643.203-.756.304");
}

.pxj138bcc {
  width: 3.464px;
  height: 4.574px;
  rx: 1.732px;
}

.pxzqtt8pl {
  stop-color: var(--svg-color--ef9f1e, #EF9F1E);
}

.py7x40bno {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m29.081 26.974l.66 2.621a.25.25 0 0 1-.242.311h-4.441c-.102 0-.196-.06-.22-.158c-.127-.504.196-.866.763-1.158a86 86 0 0 0 1.696-.9l-.376-.718a.05.05 0 0 1 .044-.074h2.02a.1.1 0 0 1 .096.076");
}

.q2m86208q {
  fill: var(--svg-color--ffd93e, #FFD93E);
  fill-rule: evenodd;
  d: path("M13.393 20.623a.45.45 0 0 1 .624-.12l.973.655a.45.45 0 0 1-.503.746l-.973-.656a.45.45 0 0 1-.121-.625");
}

.q97ggtqqw {
  fill: var(--svg-color--ffd93e, #FFD93E);
  fill-rule: evenodd;
  d: path("M13.609 20.317a.4.4 0 0 1 .547-.142l1.215.715a.4.4 0 1 1-.405.689l-1.215-.715a.4.4 0 0 1-.142-.547");
}

.q9ojxt_ur {
  stop-color: var(--svg-color--ffda40, #FFDA40);
  stop-opacity: 0;
}

.qccoatb5w {
  width: 3.464px;
  height: 4.574px;
  x: 8.633px;
  y: 11.554px;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  rx: 1.732px;
}

.qeztqxpsc {
  fill: var(--svg-color--ffd93e, #FFD93E);
  fill-rule: evenodd;
  d: path("M8.23 12.851a1.15 1.15 0 0 1 1.388.847c.33 1.361 1.57 4.162 4.242 5.912c.539.335.765 1.005.43 1.544a1.15 1.15 0 0 1-1.585.37c-3.29-1.75-4.814-4.977-5.323-7.284a1.15 1.15 0 0 1 .847-1.389");
}

.qf6ieuwex {
  fill-rule: evenodd;
  d: path("M13.373 19.785a.4.4 0 0 1 .55-.135c.404.245.859.47 1.375.647a.4.4 0 1 1-.26.757a8 8 0 0 1-1.53-.72a.4.4 0 0 1-.135-.55");
}

.qihskpbeg {
  stop-color: var(--svg-color--524e8d, #524E8D);
  stop-opacity: 0;
}

.qkiupezfq {
  stop-color: var(--svg-color--cf8219, #CF8219);
}

.qpejwlb8n {
  stop-color: var(--svg-color--fb5d03, #FB5D03);
  stop-opacity: 0;
}

.r_8k9swvo {
  stop-color: var(--svg-color--ffda40, #FFDA40);
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.re8izvbqw {
  stop-color: var(--svg-color--ffa526, #FFA526);
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rknzqr02l {
  stop-color: var(--svg-color--695d73, #695D73);
  stop-opacity: 0;
}

.rm96ywbfz {
  fill: var(--svg-color--fabd38, #FABD38);
  d: path("m28.11 23.602l.57-1.727l-2.876-.39c-.013.093-.071.51-.203 1.43c-.13.918.125 1.663.375 2.202l1.22 2.172h1.866c-.245-.77-.844-2.77-.93-3.031c-.085-.262-.085-.48-.023-.656");
}

.rnk52-res {
  fill-rule: evenodd;
  d: path("M11.102 9.862a.25.25 0 0 1 .325.138c.1.247.285.645.511 1.038c.23.399.488.767.732.975a.25.25 0 1 1-.324.38c-.312-.266-.606-.697-.841-1.106a10 10 0 0 1-.541-1.1a.25.25 0 0 1 .138-.325");
}

.rzbmz9bky {
  stop-color: var(--svg-color--ffd53d, #FFD53D);
}

.s39fbtb4t {
  fill: var(--svg-color--fecf3d, #FECF3D);
  fill-rule: evenodd;
  d: path("M13.025 21.138a.4.4 0 0 1 .56-.086l.746.547a.4.4 0 0 1-.473.645l-.746-.546a.4.4 0 0 1-.087-.56");
}

.s5ybnt0dx {
  d: path("M18.498 8.897v-.004c0-.348-.15-.63-.333-.63s-.333.282-.333.63v.004z");
}

.sc-_6lb7g {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m2.919 26.99l-.66 2.62a.25.25 0 0 0 .242.312h4.441c.102 0 .196-.06.22-.159c.127-.503-.196-.866-.763-1.157a87 87 0 0 1-1.695-.9l.375-.719a.05.05 0 0 0-.044-.073h-2.02a.1.1 0 0 0-.096.076");
}

.se_2l014i {
  fill-rule: evenodd;
  d: path("M23.845 12.67c.627.167 1 .81.833 1.438c-.25.937-.944 2.3-2.011 3.45c-1.075 1.157-2.67 2.248-4.615 2.413a1.175 1.175 0 0 1-1.27-1.071c-.055-.647.363-1.162 1.01-1.217c1.206-.141 2.261-.825 3.112-1.74c.859-.925 1.37-1.944 1.503-2.44c.167-.627.811-1 1.438-.833");
}

.so50u3yvk {
  stop-color: var(--svg-color--e48527, #E48527);
  stop-opacity: 0;
}

.spsau2bne {
  stop-color: var(--svg-color--f5a333, #F5A333);
  stop-opacity: 0;
}

.sq_2lmbxo {
  fill: var(--svg-color--ffc936, #FFC936);
  d: path("M16.086 16.939a.384.384 0 1 0 0 .768h.518a.065.065 0 0 1 0 .129h1.158v-.13h.254l-.31-.308a1.57 1.57 0 0 0-1.108-.46z");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.suyap8bzv {
  stop-color: var(--svg-color--eba544, #EBA544);
}

.t4m41vbgx {
  stop-color: var(--svg-color--e6473c, #E6473C);
}

.t93mqebfe {
  fill-rule: evenodd;
  d: path("M13.609 20.317a.4.4 0 0 1 .547-.142l1.215.715a.4.4 0 1 1-.405.689l-1.215-.715a.4.4 0 0 1-.142-.547");
}

.tfatdpd4n {
  d: path("M17.29 8.035c.041-.871.324-1.29.457-1.414h4.063l.068 3.44c-.943 2.307-3.823 2.406-4.253 1.572s-.384-2.59-.336-3.598");
}

.tfv_ikbia {
  width: 3.464px;
  height: 4.574px;
  x: 8.633px;
  y: 11.554px;
  rx: 1.732px;
}

.touvs0bsg {
  stop-color: var(--svg-color--e8a22e, #E8A22E);
  stop-opacity: 0;
}

.trve6xbqh {
  stop-color: var(--svg-color--ffd835, #FFD835);
}

.tuoskac9t {
  d: path("m13.715 8.913l-.005-.078c0-.202.086-.365.191-.365s.191.163.191.365l-.004.078z");
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.u555vebcp {
  stop-color: var(--svg-color--ffb837, #FFB837);
}

.u8cibcbeo {
  stop-color: var(--svg-color--656262, #656262);
  stop-opacity: 0;
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.us4sdgeme {
  stop-color: var(--svg-color--cf8219, #CF8219);
  stop-opacity: 0;
}

.utx5lkfyi {
  stop-color: var(--svg-color--bcabc4, #BCABC4);
}

.v1mra159b {
  d: path("m2.928 15.844l.664-.664l3.68 3.953l-1.21 1.015s.192 1.044.267 1.758a.05.05 0 0 1-.05.055H3.255a.05.05 0 0 1-.047-.035a63 63 0 0 1-.938-3.238c-.409-1.592.287-2.519.66-2.844");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vgnymzutm {
  stop-color: var(--svg-color--d58b3f, #D58B3F);
}

.vhx3aibpe {
  fill-rule: evenodd;
  d: path("M27.133 13.826a.1.1 0 0 0-.09-.14l-3.873-.058l.035-2.34l4.25.06c1.653.024 2.653 1.726 1.919 3.234l-1.186 2.545l-2.062-1.02z");
}

.vjlmb7b0u {
  fill: var(--svg-color--baa4c5, #BAA4C5);
  d: path("m27.297 27.69l-.376-.718a.05.05 0 0 1 .044-.074h2.02a.1.1 0 0 1 .096.076l.22.874z");
}

.vkuvqbbwu {
  stop-color: var(--svg-color--feb036, #FEB036);
  stop-opacity: 0;
}

.vro47yafk {
  fill: var(--svg-color--ffba23, #FFBA23);
  d: path("M14.546 5.493a1.12 1.12 0 0 0-1.071-.629c-.936.051-.868.541-1.889.331c-.894-.184-1.356-.262-1.739-.089l-.007.004c-.378.17-1.158.525-1.158 2.12c0 1.47.525 2.245.778 2.523l-.05.018c-.252.09-.356.358-.265.61c.078.215.35.339.694.285c.392-.062.68-.115.905-.16a.27.27 0 0 0 .217-.265V9.03c0-.51.36-.814.52-.905c.016-.527.178-.769.441-.896c.437-.211.573-.107 1.617-.17c1.05-.064 1.33-.905 1.007-1.567");
}

.wrq6su8qp {
  fill: var(--svg-color--baa4c5, #BAA4C5);
  d: path("m4.703 27.705l.376-.718a.05.05 0 0 0-.044-.073h-2.02a.1.1 0 0 0-.096.076l-.22.874z");
}

.x0_3yebsu {
  fill: var(--svg-color--ff6a39, #FF6A39);
  d: path("m29.072 15.828l-.664-.664l-3.68 3.953l1.21 1.016s-.192 1.043-.267 1.758a.05.05 0 0 0 .05.054h3.025a.05.05 0 0 0 .047-.034c.16-.506.565-1.792.938-3.24c.409-1.591-.287-2.517-.66-2.843");
}

.x2fv2isib {
  fill-rule: evenodd;
  d: path("M13.025 21.138a.4.4 0 0 1 .56-.086l.746.547a.4.4 0 0 1-.473.645l-.746-.546a.4.4 0 0 1-.087-.56");
}

.x6cs_acbd {
  fill: var(--svg-color--ffd93e, #FFD93E);
  fill-rule: evenodd;
  d: path("M13.373 19.785a.4.4 0 0 1 .55-.135c.404.245.859.47 1.375.647a.4.4 0 1 1-.26.757a8 8 0 0 1-1.53-.72a.4.4 0 0 1-.135-.55");
}

.x9w8qi-jn {
  stop-color: var(--svg-color--ffad30, #FFAD30);
}

.xhhozw94f {
  stop-color: var(--svg-color--ffbf38, #FFBF38);
  stop-opacity: 0;
}

.xn9ndqb6s {
  stop-color: var(--svg-color--b09db6, #B09DB6);
}

.xsj_1jbtv {
  fill: var(--svg-color--ff6a39, #FF6A39);
  d: path("M6.826 12.054a2.696 2.696 0 0 1 3.753 3.873l-3.262 3.178a2.71 2.71 0 1 1-3.77-3.891z");
}

.xylxrh5lr {
  stop-color: var(--svg-color--f03814, #F03814);
}

.y15vqhqts {
  d: path("m22.828 23.445l2.039-1.804l-2.156-2.188a69 69 0 0 1-1.903 2.278c-.67.77-.758 1.769-.738 2.261l.102 2.899h2.023c.068-.735.211-2.308.242-2.727a.95.95 0 0 1 .39-.719");
}

.ye0_6_2fy {
  d: path("M13.502 8.913V8.91c0-.348.15-.63.333-.63s.333.282.333.63v.004z");
}

.ye033cbdf {
  stop-color: var(--svg-color--5c405f, #5C405F);
  stop-opacity: 0;
}

.yvalde4js {
  stop-color: var(--svg-color--ed3424, #ED3424);
  stop-opacity: 0;
}

.yxjq9v5jp {
  stop-color: var(--svg-color--ffb032, #FFB032);
  stop-opacity: 0;
}

.z_yn3vbua {
  stop-color: var(--svg-color--ffcc3d, #FFCC3D);
}

.z0s8_mb4j {
  d: path("m11.694 9.632l-.217-1.565a.79.79 0 0 0 .217 1.565");
}

.z1ibusbcg {
  fill: var(--svg-color--fabd38, #FABD38);
  d: path("m3.89 23.617l-.57-1.726l2.876-.391c.013.094.071.51.203 1.43c.13.918-.125 1.664-.375 2.203l-1.22 2.172H2.939c.245-.771.843-2.77.93-3.032c.085-.261.085-.48.023-.656");
}

.z43rvw5kz {
  fill-rule: evenodd;
  d: path("M12.178 5.106a.25.25 0 0 1 .162.314l-.95 2.969a.25.25 0 0 1-.476-.153l.95-2.968a.25.25 0 0 1 .314-.162");
}

.z8q6w165u {
  fill-rule: evenodd;
  d: path("M19.822 5.09a.25.25 0 0 0-.162.314l.95 2.97a.25.25 0 0 0 .476-.153l-.95-2.969a.25.25 0 0 0-.314-.162");
}

.zby_02b5m {
  d: path("M15.846 19.59c0-.212.173-.385.386-.385h1.385l.308.77H16.23a.385.385 0 0 1-.385-.385");
}

.zfu-fxb-u {
  stop-color: var(--svg-color--ffba33, #FFBA33);
}

.zhwo_abtx {
  fill-rule: evenodd;
  d: path("M8.23 12.851a1.15 1.15 0 0 1 1.388.847c.33 1.361 1.57 4.162 4.242 5.912c.539.335.765 1.005.43 1.544a1.15 1.15 0 0 1-1.585.37c-3.29-1.75-4.814-4.977-5.323-7.284a1.15 1.15 0 0 1 .847-1.389");
}

.zhwoohbuw {
  stop-color: var(--svg-color--ffc247, #FFC247);
}

</style>
