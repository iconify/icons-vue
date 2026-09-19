<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i7AnSdd)" clip-rule="evenodd" class="zdg2othgw"/><g filter="url(#iPKu5nb)"><path stroke="url(#iEH6yRb)" class="a-g_bkb3a"/></g><path fill="url(#i4gkZXj)" clip-rule="evenodd" class="lgwu3mp4p"/><g filter="url(#iGr0x7v)"><path stroke="url(#iu4lzxa)" class="xrx5c8bsy"/></g><path fill="url(#iKkm0uQ)" clip-rule="evenodd" class="xm4ir1jri"/><g filter="url(#inCBVsd)"><path stroke="url(#iWyqkOc)" class="s1coa39bf"/></g><path fill="url(#iEYOOqd)" clip-rule="evenodd" class="gvc8ccc3m"/><path class="b2h9r5bpq"/><path fill="url(#iELvIxb)" class="rnppg-phq"/><path fill="url(#ikccAoe)" class="rnppg-phq"/><g filter="url(#ikruWKb)"><path class="pfwoac42h"/><path fill="url(#iWZz6ve)" class="fne6ftz0k"/><path fill="url(#iQO9MFd)" class="fne6ftz0k"/></g><path fill="url(#iem30yg)" clip-rule="evenodd" class="hzrjwn0bc"/><path fill="url(#i76Fdvc)" clip-rule="evenodd" class="hzrjwn0bc"/><path fill="url(#i8atvrJ)" clip-rule="evenodd" class="hzrjwn0bc"/><path fill="url(#itbShOb)" clip-rule="evenodd" class="hzrjwn0bc"/><path fill="url(#iEZkLhu)" clip-rule="evenodd" class="rid3x9b_r"/><path fill="url(#iaNS0bd)" clip-rule="evenodd" class="rid3x9b_r"/><path fill="url(#i5o7CNw)" clip-rule="evenodd" class="rid3x9b_r"/><path fill="url(#i2YAQ4b)" clip-rule="evenodd" class="rid3x9b_r"/><path fill="url(#iXyeLje)" clip-rule="evenodd" class="yh_iqobuz"/><path fill="url(#iL5J0Pd)" clip-rule="evenodd" class="yh_iqobuz"/><path fill="url(#iAyvNkE)" clip-rule="evenodd" class="yh_iqobuz"/><path fill="url(#iLJvtlc)" clip-rule="evenodd" class="yh_iqobuz"/><path fill="url(#iCWVAtc)" clip-rule="evenodd" class="ul5p0e4al"/><path fill="url(#ipKj36d)" clip-rule="evenodd" class="ul5p0e4al"/><g filter="url(#iFv9CVb)"><path stroke="url(#i2yD6Ed)" class="uuyfv49wq"/></g><g filter="url(#inQvTmb)"><path stroke="url(#iyX4FET)" class="gj-9zcbir"/></g><g filter="url(#ibYzNZc)"><path class="az4c-uwjy"/></g><path fill="url(#i4LMCIc)" class="okhmxbclb"/><path fill="url(#iUsqzsA)" class="okhmxbclb"/><path fill="url(#illVhcd)" class="w1pfz9iya"/><path fill="url(#iJnPTte)" class="w1pfz9iya"/><path fill="url(#iJRDqZd)" class="w1pfz9iya"/><g filter="url(#iIefSIe)"><path fill="url(#ieHF9Pe)" class="imzqxgplv"/><path fill="url(#i69uEre)" class="imzqxgplv"/><path fill="url(#itWAzSb)" class="imzqxgplv"/><path fill="url(#i9l3Wce)" class="imzqxgplv"/><path fill="url(#ikhMaie)" class="imzqxgplv"/></g><path fill="url(#iEnvbdd)" class="bhuk2acuv"/><path fill="url(#ig2IqYb)" class="bhuk2acuv"/><g filter="url(#iuMiNzd)"><path class="sbhrx8_-g"/></g><g filter="url(#iE4p7ye)"><path class="xijl3kbio"/></g><g filter="url(#iZHpjmn)"><path stroke="url(#ii9rWWb)" class="l93r40bgi"/></g><g filter="url(#iAqLsmK)"><path fill="url(#io5OBue)" class="ctxhc-nov"/></g><g filter="url(#iekoCln)"><circle fill="url(#ivD47Nb)" transform="rotate(-4.157 11.343 12.93)" class="p6ft81bps"/></g><g filter="url(#ixiHkYd)"><circle fill="url(#iJ3XsFe)" transform="rotate(-4.157 11.343 12.93)" class="vhilgcbic"/></g><g filter="url(#i70YxNb)"><circle fill="url(#iZRUl5c)" transform="rotate(-4.157 20.077 12.295)" class="zk3v0ppbq"/><circle fill="url(#idzD3Ob)" transform="rotate(-4.157 20.077 12.295)" class="zk3v0ppbq"/></g><g filter="url(#iLUPGCd)"><circle transform="rotate(-4.157 20.078 12.295)" class="pc2hdihrt"/><circle fill="url(#iCvfROc)" transform="rotate(-4.157 20.078 12.295)" class="yc05gmb6r"/><circle fill="url(#ifQSbHd)" transform="rotate(-4.157 20.078 12.295)" class="yc05gmb6r"/></g><g filter="url(#ihrfKce)"><path fill="url(#iRL8Qic)" class="fhfnrlbml"/><path fill="url(#icSs93d)" class="fhfnrlbml"/><path fill="url(#ipWUd1d)" class="fhfnrlbml"/><path fill="url(#iCTbYKr)" class="fhfnrlbml"/><path fill="url(#itC2twc)" class="fhfnrlbml"/><path fill="url(#itgKgeb)" class="fhfnrlbml"/></g><g filter="url(#i19U5Zd)"><path fill="url(#ivwgQcU)" class="r7jrsabqr"/></g><g filter="url(#iaIvDtd)"><path class="w0c3erbfg"/><path fill="url(#iAFWefd)" class="axw4jxbxd"/><path fill="url(#iAlPY2d)" class="axw4jxbxd"/><path fill="url(#iglrt4j)" class="axw4jxbxd"/><path fill="url(#i2YaVEb)" class="axw4jxbxd"/></g><g filter="url(#iGwtCQe)"><path class="r2033b-xr"/></g><g filter="url(#iKln4re)"><path class="nnr_0abuc"/><path fill="url(#ikmLOod)" class="q2pulizxa"/><path fill="url(#ixsj5Ee)" class="q2pulizxa"/><path fill="url(#iaNXv0c)" class="q2pulizxa"/><path fill="url(#iZMnWac)" class="q2pulizxa"/></g><path fill="url(#i3HtJHc)" class="q2pulizxa"/><g filter="url(#i75rAGZ)"><path class="wpfwa-bju"/></g><g filter="url(#iNAmb3c)"><path class="axcmep_vz"/></g><path class="lg2ytybds"/><path fill="url(#iO0Wqoc)" class="wp75_-bdg"/><path class="h9vrqt03z"/><g filter="url(#iS1gRCS)"><path class="grol3wbaq"/><path fill="url(#iC30GQd)" class="ufajf2_pn"/></g><g filter="url(#i8W4cyd)"><path fill="url(#ir5z5Cd)" class="dtjt7_1wd"/></g><path class="snj62e4lx"/><path fill="url(#imzHO7b)" class="lg86-9lbz"/><path class="h2ure6xwp"/><g filter="url(#iWUeRnc)"><path fill="url(#i8gJVrc)" class="y4b827bbp"/></g><g filter="url(#iy6JR1J)"><ellipse transform="rotate(-32.07 13.396 12.063)" class="thwnb_f_q"/><ellipse fill="url(#iZJeovM)" transform="rotate(-32.07 13.396 12.063)" class="zcrioqmxg"/></g><g filter="url(#i36uOgw)"><path stroke="url(#iIjYoGe)" class="rr6l9ibhg"/></g><g filter="url(#iRfIu8d)"><path stroke="url(#iAYqHpe)" class="eg3bq2bcf"/></g><g filter="url(#ieO2Vqe)"><path stroke="url(#iMkDa0w)" class="pzjclfbti"/></g><g filter="url(#iQDh5fe)"><ellipse stroke="url(#iVirdsl)" class="k61iy3-el"/></g><ellipse class="uhjk73brv"/><defs><linearGradient id="i7AnSdd" x1="3.946" x2="6.66" y1="12.719" y2="12.719" gradientUnits="userSpaceOnUse"><stop class="j4wzxsb6s"/><stop offset="1" class="o9qbcmbqu"/></linearGradient><linearGradient id="iEH6yRb" x1="4.252" x2="6.408" y1="11.827" y2="13.976" gradientUnits="userSpaceOnUse"><stop class="adq__h_ba"/><stop offset="1" class="xbm4if2ao"/></linearGradient><linearGradient id="i4gkZXj" x1="2.83" x2="5.254" y1="13.163" y2="13.163" gradientUnits="userSpaceOnUse"><stop class="j4wzxsb6s"/><stop offset="1" class="o9qbcmbqu"/></linearGradient><linearGradient id="iu4lzxa" x1="3.185" x2="5.595" y1="12.096" y2="14.31" gradientUnits="userSpaceOnUse"><stop class="adq__h_ba"/><stop offset="1" class="xbm4if2ao"/></linearGradient><linearGradient id="iKkm0uQ" x1="2.903" x2="5.695" y1="14.02" y2="14.02" gradientUnits="userSpaceOnUse"><stop class="j4wzxsb6s"/><stop offset="1" class="o9qbcmbqu"/></linearGradient><linearGradient id="iWyqkOc" x1="3.109" x2="5.7" y1="13.088" y2="15.086" gradientUnits="userSpaceOnUse"><stop class="adq__h_ba"/><stop offset="1" class="xbm4if2ao"/></linearGradient><linearGradient id="iEYOOqd" x1="3.217" x2="6.014" y1="14.892" y2="14.892" gradientUnits="userSpaceOnUse"><stop class="j4wzxsb6s"/><stop offset="1" class="o9qbcmbqu"/></linearGradient><linearGradient id="iELvIxb" x1="8.744" x2="7.903" y1="15.371" y2="15.371" gradientUnits="userSpaceOnUse"><stop offset=".005" class="dllwv2bqg"/><stop offset="1" class="lfy25fb4x"/></linearGradient><linearGradient id="iWZz6ve" x1="23.785" x2="24.582" y1="15.27" y2="15.27" gradientUnits="userSpaceOnUse"><stop class="g73nf-b6l"/><stop offset="1" class="t8bvpsbnn"/></linearGradient><linearGradient id="iem30yg" x1="28.381" x2="25.687" y1="13.528" y2="13.487" gradientUnits="userSpaceOnUse"><stop class="yludslbit"/><stop offset="1" class="c7b16qb0g"/></linearGradient><linearGradient id="iEZkLhu" x1="29.453" x2="26.909" y1="14.05" y2="14.016" gradientUnits="userSpaceOnUse"><stop class="yludslbit"/><stop offset="1" class="c7b16qb0g"/></linearGradient><linearGradient id="iXyeLje" x1="29.426" x2="26.656" y1="14.811" y2="14.766" gradientUnits="userSpaceOnUse"><stop class="yludslbit"/><stop offset="1" class="c7b16qb0g"/></linearGradient><linearGradient id="iCWVAtc" x1="29.112" x2="26.337" y1="15.589" y2="15.539" gradientUnits="userSpaceOnUse"><stop class="uluqtabwc"/><stop offset="1" class="wgkuwteff"/></linearGradient><linearGradient id="i2yD6Ed" x1="3.397" x2="6.205" y1="14.115" y2="15.796" gradientUnits="userSpaceOnUse"><stop class="adq__h_ba"/><stop offset="1" class="xbm4if2ao"/></linearGradient><linearGradient id="iyX4FET" x1="8.231" x2="7.442" y1="15.622" y2="14.575" gradientUnits="userSpaceOnUse"><stop class="adq__h_ba"/><stop offset="1" class="xbm4if2ao"/></linearGradient><linearGradient id="iUsqzsA" x1="23.662" x2="24.149" y1="17.078" y2="17.069" gradientUnits="userSpaceOnUse"><stop class="g15pupb2m"/><stop offset="1" class="dqcsylboi"/></linearGradient><linearGradient id="illVhcd" x1="7.031" x2="9.719" y1="16.785" y2="16.785" gradientUnits="userSpaceOnUse"><stop class="gy5j7812b"/><stop offset="1" class="vw_f_cbup"/></linearGradient><linearGradient id="iJRDqZd" x1="6.873" x2="6.873" y1="16.095" y2="16.358" gradientUnits="userSpaceOnUse"><stop class="z96fdub7f"/><stop offset="1" class="j3txnddmt"/></linearGradient><linearGradient id="ig2IqYb" x1="13.125" x2="15.688" y1="19.483" y2="19.483" gradientUnits="userSpaceOnUse"><stop class="a1nnhkwvf"/><stop offset="1" class="k2_z139ch"/></linearGradient><linearGradient id="ii9rWWb" x1="9.86" x2="12.86" y1="25.814" y2="20.158" gradientUnits="userSpaceOnUse"><stop class="zuuvnac4f"/><stop offset="1" class="bb3cu5wqs"/></linearGradient><linearGradient id="io5OBue" x1="25.449" x2="21.21" y1="25.899" y2="21.185" gradientUnits="userSpaceOnUse"><stop class="j0u0snf-e"/><stop offset="1" class="kii7weu_o"/></linearGradient><linearGradient id="iJ3XsFe" x1="11.343" x2="10.754" y1="13.186" y2="13.186" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="iZRUl5c" x1="21.078" x2="20.324" y1="11.29" y2="13.625" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="iRL8Qic" x1="19.434" x2="12.498" y1="12.701" y2="14.255" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="icSs93d" x1="10.954" x2="12.677" y1="15.806" y2="15.618" gradientUnits="userSpaceOnUse"><stop class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="itgKgeb" x1="14.669" x2="16.169" y1="-1.972" y2="18.674" gradientUnits="userSpaceOnUse"><stop offset=".979" class="wvw1ebchz"/><stop offset="1" class="y2xm7ibwq"/></linearGradient><linearGradient id="ivwgQcU" x1="15.041" x2="22.324" y1="10.265" y2="7.045" gradientUnits="userSpaceOnUse"><stop class="p7wwt2b_k"/><stop offset="1" class="o1syipbau"/></linearGradient><linearGradient id="ikmLOod" x1="14.979" x2="15.84" y1="13.633" y2="13.571" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="ixsj5Ee" x1="16.655" x2="15.713" y1="13.809" y2="13.864" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="iaNXv0c" x1="16.022" x2="15.984" y1="14.54" y2="14.014" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="i3HtJHc" x1="15.962" x2="15.95" y1="14.583" y2="14.43" gradientUnits="userSpaceOnUse"><stop class="zoxadnjxe"/><stop offset="1" class="gnvm67mtb"/></linearGradient><linearGradient id="ir5z5Cd" x1="18.375" x2="18.1" y1="11.839" y2="12.037" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i8gJVrc" x1="14.338" x2="14.063" y1="12.132" y2="12.331" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iIjYoGe" x1="18.247" x2="17.804" y1="9.873" y2="9.113" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iAYqHpe" x1="13.368" x2="12.243" y1="10.11" y2="9.731" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iMkDa0w" x1="11.095" x2="11.239" y1="8.416" y2="10.396" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><linearGradient id="iVirdsl" x1="15.706" x2="16.023" y1="16.72" y2="15.585" gradientUnits="userSpaceOnUse"><stop class="n9gb1cj0g"/><stop offset="1" class="ovzit_jxc"/></linearGradient><radialGradient id="ikccAoe" cx="0" cy="0" r="1" gradientTransform="matrix(-.52138 .86916 -1.0215 -.61276 7.046 11.138)" gradientUnits="userSpaceOnUse"><stop class="zvb7pjbrz"/><stop offset="1" class="zk7ulfu0q"/></radialGradient><radialGradient id="iQO9MFd" cx="0" cy="0" r="1" gradientTransform="matrix(.85157 -.55469 .26705 .40998 26.262 11.388)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="mc3aerbdu"/><stop offset="1" class="p2xodcbta"/></radialGradient><radialGradient id="i76Fdvc" cx="0" cy="0" r="1" gradientTransform="matrix(1.0788 .95928 -3.2774 3.68572 26.947 12.589)" gradientUnits="userSpaceOnUse"><stop offset=".715" class="r8nvtjbrg"/><stop offset="1" class="w_txxk5nx"/></radialGradient><radialGradient id="i8atvrJ" cx="0" cy="0" r="1" gradientTransform="rotate(-136.326 16.586 .98)scale(1.45051 1.63903)" gradientUnits="userSpaceOnUse"><stop class="twf01ac1b"/><stop offset="1" class="zg5ree2ok"/></radialGradient><radialGradient id="itbShOb" cx="0" cy="0" r="1" gradientTransform="rotate(-53.366 25.87 -22.617)scale(.75938 .43842)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="mc3aerbdu"/><stop offset="1" class="p2xodcbta"/></radialGradient><radialGradient id="iaNS0bd" cx="0" cy="0" r="1" gradientTransform="rotate(45.859 -1.342 39.723)scale(1.46299 5.0306)" gradientUnits="userSpaceOnUse"><stop offset=".715" class="r8nvtjbrg"/><stop offset="1" class="w_txxk5nx"/></radialGradient><radialGradient id="i5o7CNw" cx="0" cy="0" r="1" gradientTransform="rotate(-132.109 17.528 .374)scale(1.4777 1.66303)" gradientUnits="userSpaceOnUse"><stop class="twf01ac1b"/><stop offset="1" class="zg5ree2ok"/></radialGradient><radialGradient id="i2YAQ4b" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 -.54688 .3157 .37883 29.66 11.997)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="mc3aerbdu"/><stop offset="1" class="p2xodcbta"/></radialGradient><radialGradient id="iL5J0Pd" cx="0" cy="0" r="1" gradientTransform="matrix(1.10937 .9375 -3.17994 3.76294 27.952 13.892)" gradientUnits="userSpaceOnUse"><stop offset=".715" class="r8nvtjbrg"/><stop offset="1" class="w_txxk5nx"/></radialGradient><radialGradient id="iAyvNkE" cx="0" cy="0" r="1" gradientTransform="rotate(-137.781 17.255 1.631)scale(1.45679 1.64014)" gradientUnits="userSpaceOnUse"><stop class="twf01ac1b"/><stop offset="1" class="zg5ree2ok"/></radialGradient><radialGradient id="iLJvtlc" cx="0" cy="0" r="1" gradientTransform="matrix(.53125 -.47656 .27377 .30518 29.77 13.02)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="mc3aerbdu"/><stop offset="1" class="p2xodcbta"/></radialGradient><radialGradient id="ipKj36d" cx="0" cy="0" r="1" gradientTransform="matrix(.54297 -.42187 .23663 .30456 29.464 14.044)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="mc3aerbdu"/><stop offset="1" class="p2xodcbta"/></radialGradient><radialGradient id="i4LMCIc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.94297 -2.39063 0 26.203 16.095)" gradientUnits="userSpaceOnUse"><stop class="gqn4jccjs"/><stop offset="1" class="wjksmgbzx"/></radialGradient><radialGradient id="iJnPTte" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.14902 -.68994 0 7.563 16.327)" gradientUnits="userSpaceOnUse"><stop class="ne51g8a0v"/><stop offset="1" class="opxc931wt"/></radialGradient><radialGradient id="ieHF9Pe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.4411 10.6867 0 19.921 29.08)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="g6k-1hpjs"/><stop offset="1" class="msi6qbbpq"/></radialGradient><radialGradient id="i69uEre" cx="0" cy="0" r="1" gradientTransform="matrix(-3.01666 3.53393 -1.57189 -1.3418 9.813 19.694)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="k20ytgb7v"/><stop offset="1" class="mtrk0zxts"/><stop offset="1" class="jbumt9bvj"/></radialGradient><radialGradient id="itWAzSb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.46944 -4.08022 0 27.015 16.642)" gradientUnits="userSpaceOnUse"><stop class="f51--cb4u"/><stop offset="1" class="sp_au2bah"/></radialGradient><radialGradient id="i9l3Wce" cx="0" cy="0" r="1" gradientTransform="matrix(-2.2344 3.40893 -.45438 -.29783 9.719 19.82)" gradientUnits="userSpaceOnUse"><stop class="o18y7cctk"/><stop offset="1" class="p8zx0emkh"/></radialGradient><radialGradient id="ikhMaie" cx="0" cy="0" r="1" gradientTransform="matrix(-5.68753 3.4062 -1.542 -2.57478 14.422 17.57)" gradientUnits="userSpaceOnUse"><stop offset=".066" class="ok0pekb3m"/><stop offset="1" class="l6xrk1bwj"/></radialGradient><radialGradient id="iEnvbdd" cx="0" cy="0" r="1" gradientTransform="matrix(2.0625 2.17783 -3.3043 3.12931 15.594 17.805)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="vercztyxt"/><stop offset="1" class="q0oph8z4o"/></radialGradient><radialGradient id="ivD47Nb" cx="0" cy="0" r="1" gradientTransform="matrix(1.61537 0 0 2.8269 9.806 12.93)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="idzD3Ob" cx="0" cy="0" r="1" gradientTransform="matrix(.76099 -.55412 .63245 .86857 20.42 12.051)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="iCvfROc" cx="0" cy="0" r="1" gradientTransform="matrix(.75598 -1.39046 .81384 .44248 20.04 13.05)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="ifQSbHd" cx="0" cy="0" r="1" gradientTransform="matrix(.23867 .23625 -.30456 .30768 20.078 12.295)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="ipWUd1d" cx="0" cy="0" r="1" gradientTransform="rotate(85.843 1.012 14.512)scale(6.54035 8.87817)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="g0r5sc7jj"/><stop offset="1" class="i5c5eto6f"/></radialGradient><radialGradient id="iCTbYKr" cx="0" cy="0" r="1" gradientTransform="matrix(-.08722 -1.20001 1.47693 -.10734 17.772 11.289)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="itC2twc" cx="0" cy="0" r="1" gradientTransform="matrix(-.0928 -1.27693 1.58798 -.11542 13.585 11.563)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="iAFWefd" cx="0" cy="0" r="1" gradientTransform="rotate(-79.056 14.892 -7.49)scale(2.81893 1.04535)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="iAlPY2d" cx="0" cy="0" r="1" gradientTransform="matrix(3.535 .06795 -.03654 1.90075 17.792 7.047)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="iglrt4j" cx="0" cy="0" r="1" gradientTransform="matrix(.11204 1.54162 -2.38754 .17351 15.129 4.716)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="i2YaVEb" cx="0" cy="0" r="1" gradientTransform="matrix(2.67185 -2.27323 3.5614 4.18591 9.663 11.406)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="iZMnWac" cx="0" cy="0" r="1" gradientTransform="rotate(85.843 .492 15.695)scale(.18125 .5823)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="iO0Wqoc" cx="0" cy="0" r="1" gradientTransform="matrix(.05412 .74469 -1.18452 .0861 17.657 11.841)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iC30GQd" cx="0" cy="0" r="1" gradientTransform="rotate(-131.968 11.385 2.078)scale(.34814 .47931)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="imzHO7b" cx="0" cy="0" r="1" gradientTransform="matrix(.05412 .74473 -1.18458 .08609 13.652 12.132)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iZJeovM" cx="0" cy="0" r="1" gradientTransform="matrix(-.00712 -.45471 .54657 -.00856 13.382 12.352)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iPKu5nb" width="3.052" height="2.539" x="3.552" y="11.372" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4184" stdDeviation=".15"/></filter><filter id="iGr0x7v" width="3.127" height="2.723" x="2.473" y="11.652" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4184" stdDeviation=".15"/></filter><filter id="inCBVsd" width="3.267" height="2.534" x="2.403" y="12.662" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4184" stdDeviation=".15"/></filter><filter id="ikruWKb" width="3.408" height="5.156" x="23.785" y="11.138" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.227451 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4184"/></filter><filter id="iFv9CVb" width="3.431" height="2.258" x="2.702" y="13.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4184" stdDeviation=".15"/></filter><filter id="inQvTmb" width="2.543" height="1.191" x="5.879" y="15.122" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4184" stdDeviation=".15"/></filter><filter id="ibYzNZc" width="2.847" height=".977" x="25.253" y="14.956" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4184" stdDeviation=".15"/></filter><filter id="iIefSIe" width="23.107" height="13.423" x="4.624" y="16.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.396078 0 0 0 0 0.768627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4184"/></filter><filter id="iuMiNzd" width="8.199" height="8.945" x="5.11" y="16.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4184" stdDeviation=".75"/></filter><filter id="iE4p7ye" width="7.102" height="8.493" x="20.783" y="16.333" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4184" stdDeviation=".625"/></filter><filter id="iZHpjmn" width="3.956" height="6.956" x="9.209" y="19.039" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4184" stdDeviation=".25"/></filter><filter id="iAqLsmK" width="5.986" height="5.519" x="20.41" y="21.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4184" stdDeviation=".4"/></filter><filter id="iekoCln" width="3.274" height="3.074" x="9.806" y="11.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4184"/></filter><filter id="ixiHkYd" width="2.832" height="2.832" x="9.927" y="11.514" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4184" stdDeviation=".25"/></filter><filter id="i70YxNb" width="3.324" height="3.324" x="18.541" y="10.508" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4184"/></filter><filter id="iLUPGCd" width="2.832" height="2.832" x="18.662" y="10.879" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4184" stdDeviation=".25"/></filter><filter id="ihrfKce" width="9.545" height="11.358" x="10.828" y="7.397" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4184"/></filter><filter id="i19U5Zd" width="7.943" height="7.001" x="13.615" y="5.184" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4184" stdDeviation="1"/></filter><filter id="iaIvDtd" width="11.575" height="8.202" x="9.616" y="4.189" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4184"/></filter><filter id="iGwtCQe" width="3.118" height="3.999" x="14.04" y="11.496" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4184" stdDeviation=".375"/></filter><filter id="iKln4re" width="2.226" height="2.99" x="14.695" y="11.841" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4184" stdDeviation=".125"/></filter><filter id="i75rAGZ" width="2.784" height="1.675" x="16.607" y="9.083" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4184"/></filter><filter id="iNAmb3c" width="2.734" height="1.846" x="11.906" y="9.366" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4184"/></filter><filter id="iS1gRCS" width=".72" height=".68" x="16.978" y="11.441" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4184" stdDeviation=".05"/></filter><filter id="i8W4cyd" width=".863" height=".881" x="17.746" y="11.452" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4184" stdDeviation=".1"/></filter><filter id="iWUeRnc" width=".956" height=".995" x="13.663" y="11.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4184" stdDeviation=".1"/></filter><filter id="iy6JR1J" width=".838" height=".69" x="12.977" y="11.718" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4184" stdDeviation=".05"/></filter><filter id="i36uOgw" width="2.574" height="1.158" x="16.611" y="9.381" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4184" stdDeviation=".15"/></filter><filter id="iRfIu8d" width="2.589" height="1.404" x="11.854" y="9.718" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4184" stdDeviation=".15"/></filter><filter id="ieO2Vqe" width=".946" height="2.162" x="10.709" y="8.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4184" stdDeviation=".125"/></filter><filter id="iQDh5fe" width="1.869" height="1.911" x="15.136" y="15.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4184" stdDeviation=".05"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-shrugging-dark" /></template>
<style>
.a-g_bkb3a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M4.052 11.872c.196.502 1.018 1.388 2.052 1.54");
}

.a1nnhkwvf {
  stop-color: var(--svg-color--3e3136, #3E3136);
}

.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.adq__h_ba {
  stop-color: var(--svg-color--5b4b4b, #5B4B4B);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.axcmep_vz {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.057 10.368l.002-.002l.004-.004l.01-.01a1.4 1.4 0 0 1 .136-.109c.087-.064.212-.144.371-.221c.32-.154.783-.293 1.36-.245a.491.491 0 0 1-.083.98a1.6 1.6 0 0 0-.85.15a1.4 1.4 0 0 0-.272.172a.491.491 0 0 1-.678-.71");
}

.axw4jxbxd {
  d: path("m19.694 6.344l.409.167c.714.293 1.165 1.048 1.078 1.891l-.34 2.83c-.027.292-.203.5-.489.528l-.016.001s-.012-.836.002-1.329c.011-.4-.067-.517-.458-.853a1.16 1.16 0 0 1-.402-.758l-.057-.783a.53.53 0 0 0-.43-.461c-.6-.104-1.85-.26-3.623-.131c-1.772.129-2.986.463-3.566.653a.48.48 0 0 0-.358.518l.056.784c.022.294-.055.594-.287.808l-.137.158c-.187.161-.264.462-.246.707c.088.535.195 1.315.195 1.315l-.046.002a.58.58 0 0 1-.58-.449L9.653 9.19c-.156-.776.181-1.588.846-1.98l.38-.225c.235-.165.467-.379.699-.593l.819-.994a1.805 1.805 0 0 1 1.998-.44a2.7 2.7 0 0 0 1.526-.112c.721-.298 1.572-.163 2.203.332l.792.681c.214.23.471.36.777.485");
}

.az4c-uwjy {
  stroke: var(--svg-color--635150, #635150);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M25.653 15.528h1.515a.7.7 0 0 0 .531-.172");
}

.b2h9r5bpq {
  fill: var(--svg-color--40302f, #40302F);
  d: path("M6.002 11.293a.75.75 0 0 1 1.052.138l.805 1.047c.369.48.57 1.07.57 1.675v2.141H5.17v-2.698h1.627a1.3 1.3 0 0 0-.128-.204l-.804-1.047a.75.75 0 0 1 .137-1.052");
}

.bb3cu5wqs {
  stop-color: var(--svg-color--1a7ad4, #1A7AD4);
  stop-opacity: 0;
}

.bhuk2acuv {
  d: path("M16.025 20.749c-1.104 0-2-.95-2-1.867v-2.359c0-.917.896-1.661 2-1.661s2 .744 2 1.661v2.358c0 .918-.895 1.868-2 1.868");
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.c7b16qb0g {
  stop-color: var(--svg-color--4e3533, #4E3533);
}

.cdm_o50ho {
  stop-color: var(--svg-color--533531, #533531);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ctxhc-nov {
  d: path("m21.21 21.823l1.542 3.67c1.207.44 2.534.203 2.844 0z");
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.dllwv2bqg {
  stop-color: var(--svg-color--4d4342, #4D4342);
}

.dqcsylboi {
  stop-color: var(--svg-color--257fbf, #257FBF);
  stop-opacity: 0;
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.dtjt7_1wd {
  d: path("M18.409 12.062a.77.77 0 0 0-.243-.41l-.22.28l.123.201z");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.eg3bq2bcf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.279 10.696c.28-.287.916-.614 1.739-.544");
}

.f51--cb4u {
  stop-color: var(--svg-color--43beff, #43BEFF);
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.fhfnrlbml {
  d: path("m10.98 12.39l.045-.001s-.107-.78-.195-1.315c-.018-.245.06-.546.246-.707l.137-.158c.232-.213.309-.514.288-.808l-.057-.784a.48.48 0 0 1 .358-.518c.58-.19 1.794-.524 3.566-.653c1.773-.129 3.022.027 3.624.13a.53.53 0 0 1 .43.462l.056.783c.022.294.19.577.402.758c.485.29.469.47.458.853c-.014.493-.002 1.33-.002 1.33l.016-.002l.02 3.652c-.029 1.635-1.224 2.86-2.747 2.971l-2.947.214c-1.572.114-2.883-.929-3.148-2.543z");
}

.fne6ftz0k {
  d: path("M26.21 11.293a.75.75 0 0 0-1.051.138l-.805 1.047a2.75 2.75 0 0 0-.57 1.675v2.141h3.258v-2.698h-1.626q.053-.108.127-.204l.805-1.047a.75.75 0 0 0-.138-1.052");
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g0r5sc7jj {
  stop-color: var(--svg-color--3d2138, #3D2138);
  stop-opacity: 0;
}

.g15pupb2m {
  stop-color: var(--svg-color--257fbf, #257FBF);
}

.g6k-1hpjs {
  stop-color: var(--svg-color--3cb2ff, #3CB2FF);
}

.g73nf-b6l {
  stop-color: var(--svg-color--382020, #382020);
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gj-9zcbir {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M6.379 15.622h.998c.226 0 .444.09.604.25v0");
}

.gnvm67mtb {
  stop-color: var(--svg-color--31171f, #31171F);
  stop-opacity: 0;
}

.gqn4jccjs {
  stop-color: var(--svg-color--47adf9, #47ADF9);
}

.grol3wbaq {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.58 11.58c.064.075-.051.179-.182.292c-.132.114-.23.195-.293.12c-.064-.073-.01-.225.121-.339s.29-.146.354-.072");
}

.gvc8ccc3m {
  fill-rule: evenodd;
  d: path("M2.763 13.855a.7.7 0 0 1 .98.142c.181.242.653.84 1.873.84a.7.7 0 1 1 0 1.4c-1.827 0-2.668-.965-2.995-1.402a.7.7 0 0 1 .142-.98");
}

.gy5j7812b {
  stop-color: var(--svg-color--4a9ee0, #4A9EE0);
}

.h2ure6xwp {
  fill: var(--svg-color--000, #000);
  d: path("M14.147 12.48a.47.47 0 0 0-.504-.436a.47.47 0 0 0-.367.716l.83-.06a.5.5 0 0 0 .04-.22");
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
  stop-opacity: 0;
}

.h9vrqt03z {
  fill: var(--svg-color--000, #000);
  d: path("M17.218 12.257a.47.47 0 0 1 .435-.504a.468.468 0 0 1 .467.655l-.83.06a.4.4 0 0 1-.072-.211");
}

.hzrjwn0bc {
  fill-rule: evenodd;
  d: path("M28.69 11.485a.7.7 0 0 0-.977.157c-.044.062-.088.137-.115.183l-.005.01l-.001.002l-.105.174c-.077.12-.17.25-.294.37c-.233.228-.608.468-1.267.5a.7.7 0 1 0 .068 1.398c1.025-.05 1.718-.447 2.179-.898c.224-.22.382-.441.495-.618c.053-.084.098-.16.13-.216l.004-.007l.045-.075v-.002a.7.7 0 0 0-.156-.978");
}

.i5c5eto6f {
  stop-color: var(--svg-color--3d2138, #3D2138);
}

.imzqxgplv {
  d: path("M9.484 20.574a.25.25 0 0 1-.375-.216v-2.564a.6.6 0 0 0-.6-.6H5.224a.6.6 0 0 0-.6.6v4.286c-.005.85.112 2.507 1.485 3.383c1.148.733 2.5.57 3.213.347c.101-.031.208.042.208.148v3.707c0 .082.068.15.15.15h12.994a.15.15 0 0 0 .15-.15v-3.707c0-.106.108-.18.209-.148c.713.223 2.065.386 3.213-.347c1.373-.876 1.49-2.534 1.485-3.383v-4.286a.6.6 0 0 0-.6-.6h-3.285a.6.6 0 0 0-.6.6v2.564a.25.25 0 0 1-.375.216l-6.694-3.932z");
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j0u0snf-e {
  stop-color: var(--svg-color--1870d4, #1870D4);
}

.j3txnddmt {
  stop-color: var(--svg-color--3481c0, #3481C0);
  stop-opacity: 0;
}

.j4wzxsb6s {
  stop-color: var(--svg-color--422d2b, #422D2B);
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
}

.jbumt9bvj {
  stop-color: var(--svg-color--1f74b9, #1F74B9);
  stop-opacity: 0;
}

.k2_z139ch {
  stop-color: var(--svg-color--3e3136, #3E3136);
  stop-opacity: 0;
}

.k20ytgb7v {
  stop-color: var(--svg-color--1f74b9, #1F74B9);
}

.k61iy3-el {
  cx: 16.07px;
  cy: 15.965px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  rx: 0.734px;
  ry: 0.755px;
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.kii7weu_o {
  stop-color: var(--svg-color--1870d4, #1870D4);
  stop-opacity: 0;
}

.l6xrk1bwj {
  stop-color: var(--svg-color--28699c, #28699C);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l93r40bgi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M9.86 25.345c.177-1.146.956-3.881 2.656-5.656");
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.lfy25fb4x {
  stop-color: var(--svg-color--4d4342, #4D4342);
  stop-opacity: 0;
}

.lg2ytybds {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.8 11.14a1.284 1.284 0 0 1 1.313.881a.252.252 0 0 1-.223.331l-2.047.149a.212.212 0 0 1-.227-.234a1.286 1.286 0 0 1 1.183-1.127");
}

.lg86-9lbz {
  d: path("M13.618 11.695a.82.82 0 0 0-.714 1.092l1.582-.115a.827.827 0 0 0-.868-.978");
}

.lgwu3mp4p {
  fill-rule: evenodd;
  d: path("M2.483 11.802a.7.7 0 0 1 .977.157q.05.071.115.168c.262.39.704 1.052 1.516 1.4a.7.7 0 1 1-.551 1.286c-1.246-.533-1.935-1.603-2.156-1.946l-.058-.088a.7.7 0 0 1 .157-.977");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mc3aerbdu {
  stop-color: var(--svg-color--665554, #665554);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.msi6qbbpq {
  stop-color: var(--svg-color--2d92df, #2D92DF);
}

.mtrk0zxts {
  stop-color: var(--svg-color--51aaff, #51AAFF);
  stop-opacity: 0;
}

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.n9gb1cj0g {
  stop-color: var(--svg-color--534243, #534243);
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.ne51g8a0v {
  stop-color: var(--svg-color--3990dd, #3990DD);
}

.nnr_0abuc {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m15.332 12.376l-.374 1.596a.496.496 0 0 0 .524.607l.722-.052a.498.498 0 0 0 .431-.677l-.6-1.525c-.13-.338-.618-.302-.703.051");
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o18y7cctk {
  stop-color: var(--svg-color--389bfa, #389BFA);
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o1syipbau {
  stop-color: var(--svg-color--685654, #685654);
  stop-opacity: 0;
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.o9qbcmbqu {
  stop-color: var(--svg-color--40302f, #40302F);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ok0pekb3m {
  stop-color: var(--svg-color--28699c, #28699C);
}

.okhmxbclb {
  d: path("M27.092 16.345a.25.25 0 0 0-.25-.25h-2.93a.25.25 0 0 0-.25.25v1.318h3.43z");
}

.opxc931wt {
  stop-color: var(--svg-color--3990dd, #3990DD);
  stop-opacity: 0;
}

.ovzit_jxc {
  stop-color: var(--svg-color--534243, #534243);
  stop-opacity: 0;
}

.p2xodcbta {
  stop-color: var(--svg-color--665554, #665554);
  stop-opacity: 0;
}

.p6ft81bps {
  cx: 11.343px;
  cy: 12.93px;
  r: 1.537px;
}

.p7wwt2b_k {
  stop-color: var(--svg-color--685654, #685654);
}

.p8zx0emkh {
  stop-color: var(--svg-color--389bfa, #389BFA);
  stop-opacity: 0;
}

.pc2hdihrt {
  cx: 20.078px;
  cy: 12.295px;
  r: 0.916px;
  fill: var(--svg-color--463133, #463133);
}

.pfwoac42h {
  fill: var(--svg-color--4b3230, #4B3230);
  d: path("M26.21 11.293a.75.75 0 0 0-1.051.138l-.805 1.047a2.75 2.75 0 0 0-.57 1.675v2.141h3.258v-2.698h-1.626q.053-.108.127-.204l.805-1.047a.75.75 0 0 0-.138-1.052");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pzjclfbti {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m11.22 8.498l.06.824c.003.137-.033.446-.196.588");
}

.q0oph8z4o {
  stop-color: var(--svg-color--523a3d, #523A3D);
}

.q2pulizxa {
  d: path("m15.332 12.376l-.374 1.596a.496.496 0 0 0 .524.607l.722-.052a.498.498 0 0 0 .431-.677l-.6-1.525c-.13-.338-.618-.302-.703.051");
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r2033b-xr {
  fill: var(--svg-color--332024, #332024);
  d: path("m15.441 12.519l-.64 1.615c-.07.328.178.632.495.61l.677-.05c.318-.023.518-.365.402-.674l-.571-1.527c-.123-.339-.285-.327-.363.026");
}

.r7jrsabqr {
  d: path("M18.966 7.184L16.21 8.332a.964.964 0 0 0 .567 1.833l2.782-.58z");
}

.r8nvtjbrg {
  stop-color: var(--svg-color--3d2625, #3D2625);
  stop-opacity: 0;
}

.rid3x9b_r {
  fill-rule: evenodd;
  d: path("M29.73 11.802a.7.7 0 0 0-.977.157l-.115.168c-.262.39-.922 1.113-1.733 1.46c-.356.153-.503.45-.32.876c.152.355.733.502 1.088.35c1.246-.533 1.935-1.603 2.156-1.946q.038-.06.058-.088a.7.7 0 0 0-.157-.977");
}

.rnppg-phq {
  d: path("M6.002 11.293a.75.75 0 0 1 1.052.138l.805 1.047c.369.48.57 1.07.57 1.675v2.141H5.17v-2.698h1.627a1.3 1.3 0 0 0-.128-.204l-.804-1.047a.75.75 0 0 1 .137-1.052");
}

.rr6l9ibhg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.036 9.872c.39-.098 1.161-.134 1.724.242");
}

.s1coa39bf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M2.903 13.162c.239.483.967 1.38 2.267 1.534");
}

.sbhrx8_-g {
  stroke: var(--svg-color--40a1ff, #40A1FF);
  stroke-linecap: square;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.36 18.663v3.442a1 1 0 0 0 1.566.824l1.84-1.266");
}

.snj62e4lx {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.41 11.459c-.6.043-1.076.494-1.173 1.062a.252.252 0 0 0 .268.295l2.048-.149a.212.212 0 0 0 .19-.264a1.29 1.29 0 0 0-1.333-.944");
}

.sp_au2bah {
  stop-color: var(--svg-color--43beff, #43BEFF);
  stop-opacity: 0;
}

.t8bvpsbnn {
  stop-color: var(--svg-color--382020, #382020);
  stop-opacity: 0;
}

.thwnb_f_q {
  cx: 13.396px;
  cy: 12.063px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.359px;
  ry: 0.181px;
}

.twf01ac1b {
  stop-color: var(--svg-color--33201d, #33201D);
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.ufajf2_pn {
  d: path("M17.58 11.58c.064.075-.051.179-.182.292c-.132.114-.23.195-.293.12c-.064-.073-.01-.225.121-.339s.29-.146.354-.072");
}

.uhjk73brv {
  cx: 16.07px;
  cy: 15.965px;
  fill: var(--svg-color--290018, #290018);
  rx: 0.734px;
  ry: 0.755px;
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.ul5p0e4al {
  fill-rule: evenodd;
  d: path("M29.45 13.855a.7.7 0 0 0-.98.142c-.181.242-.653.84-1.873.84a.7.7 0 1 0 0 1.4c1.827 0 2.668-.965 2.994-1.402a.7.7 0 0 0-.141-.98");
}

.uluqtabwc {
  stop-color: var(--svg-color--503734, #503734);
}

.uuyfv49wq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M3.202 14.213c.293.452 1.121 1.258 2.431 1.258");
}

.vercztyxt {
  stop-color: var(--svg-color--372228, #372228);
}

.vhilgcbic {
  cx: 11.343px;
  cy: 12.93px;
  r: 0.916px;
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vw_f_cbup {
  stop-color: var(--svg-color--227bc3, #227BC3);
}

.w_txxk5nx {
  stop-color: var(--svg-color--3d2625, #3D2625);
}

.w0c3erbfg {
  fill: var(--svg-color--21181b, #21181B);
  d: path("m19.694 6.344l.409.167c.714.293 1.165 1.048 1.078 1.891l-.34 2.83c-.027.292-.203.5-.489.528l-.016.001s-.012-.836.002-1.329c.011-.4-.067-.517-.458-.853a1.16 1.16 0 0 1-.402-.758l-.057-.783a.53.53 0 0 0-.43-.461c-.6-.104-1.85-.26-3.623-.131c-1.772.129-2.986.463-3.566.653a.48.48 0 0 0-.358.518l.056.784c.022.294-.055.594-.287.808l-.137.158c-.187.161-.264.462-.246.707c.088.535.195 1.315.195 1.315l-.046.002a.58.58 0 0 1-.58-.449L9.653 9.19c-.156-.776.181-1.588.846-1.98l.38-.225c.235-.165.467-.379.699-.593l.819-.994a1.805 1.805 0 0 1 1.998-.44a2.7 2.7 0 0 0 1.526-.112c.721-.298 1.572-.163 2.203.332l.792.681c.214.23.471.36.777.485");
}

.w1pfz9iya {
  d: path("M5.158 16.345a.25.25 0 0 1 .25-.25h2.93a.25.25 0 0 1 .25.25v1.13h-3.43z");
}

.wgkuwteff {
  stop-color: var(--svg-color--4b3330, #4B3330);
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wjksmgbzx {
  stop-color: var(--svg-color--308bdb, #308BDB);
}

.wp75_-bdg {
  d: path("M17.627 11.403a.82.82 0 0 1 .865.978l-1.582.115a.825.825 0 0 1 .718-1.093");
}

.wpfwa-bju {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M18.936 9.867h-.001l-.002-.002l-.005-.003l-.011-.008a1 1 0 0 0-.15-.088a2.4 2.4 0 0 0-.399-.166a2.6 2.6 0 0 0-1.38-.045a.491.491 0 0 0 .222.957c.361-.085.659-.039.864.026a1.4 1.4 0 0 1 .286.126l.008.005a.491.491 0 0 0 .568-.802");
}

.wvw1ebchz {
  stop-color: var(--svg-color--624d68, #624D68);
  stop-opacity: 0;
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.xbm4if2ao {
  stop-color: var(--svg-color--5b4b4b, #5B4B4B);
  stop-opacity: 0;
}

.xijl3kbio {
  stroke: var(--svg-color--4abeff, #4ABEFF);
  stroke-linecap: square;
  d: path("M26.134 18.083v3.99a1 1 0 0 1-1.567.825l-1.839-1.266");
}

.xm4ir1jri {
  fill-rule: evenodd;
  d: path("M2.45 12.824a.7.7 0 0 1 .98.142q.042.054.087.118c.301.42.763 1.062 1.778 1.062a.7.7 0 1 1 0 1.4c-1.775 0-2.636-1.24-2.924-1.655l-.062-.087a.7.7 0 0 1 .142-.98");
}

.xrx5c8bsy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M2.973 12.152c.196.502.845 1.459 2.127 1.724");
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.y2xm7ibwq {
  stop-color: var(--svg-color--624d68, #624D68);
}

.y4b827bbp {
  d: path("M14.419 12.363c-.02-.265-.247-.425-.31-.474l-.245.275l.186.32z");
}

.yc05gmb6r {
  cx: 20.078px;
  cy: 12.295px;
  r: 0.916px;
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yh_iqobuz {
  fill-rule: evenodd;
  d: path("M29.762 12.824a.7.7 0 0 0-.98.142l-.086.118c-.301.42-.763 1.062-1.779 1.062a.7.7 0 1 0 0 1.4c1.776 0 2.637-1.24 2.925-1.655q.037-.054.062-.087a.7.7 0 0 0-.142-.98");
}

.yludslbit {
  stop-color: var(--svg-color--4b3230, #4B3230);
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.z96fdub7f {
  stop-color: var(--svg-color--3481c0, #3481C0);
}

.zcrioqmxg {
  cx: 13.396px;
  cy: 12.063px;
  rx: 0.359px;
  ry: 0.181px;
}

.zdg2othgw {
  fill-rule: evenodd;
  d: path("M3.522 11.485a.7.7 0 0 1 .977.157a2 2 0 0 1 .121.193l.001.002c.034.058.066.113.105.174c.077.12.17.25.294.37c.232.228.607.468 1.267.5a.7.7 0 1 1-.069 1.398c-1.024-.05-1.717-.447-2.178-.898a3.5 3.5 0 0 1-.495-.618a5 5 0 0 1-.13-.216l-.004-.007l-.045-.075l-.001-.002a.7.7 0 0 1 .157-.978");
}

.zg5ree2ok {
  stop-color: var(--svg-color--33201d, #33201D);
  stop-opacity: 0;
}

.zk3v0ppbq {
  cx: 20.077px;
  cy: 12.295px;
  r: 1.537px;
}

.zk7ulfu0q {
  stop-color: var(--svg-color--4d3e3c, #4D3E3C);
  stop-opacity: 0;
}

.zoxadnjxe {
  stop-color: var(--svg-color--31171f, #31171F);
}

.zuuvnac4f {
  stop-color: var(--svg-color--1a7ad4, #1A7AD4);
}

.zvb7pjbrz {
  stop-color: var(--svg-color--4d3e3c, #4D3E3C);
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
