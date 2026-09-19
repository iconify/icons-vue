<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ijRugnb)" class="mbo6hmbkt"/><path fill="url(#iLC24Ib)" class="mbo6hmbkt"/><path fill="url(#iWUO0Qd)" class="pwdeswylh"/><g filter="url(#iMad6jc)"><circle fill="url(#iR0dKHe)" transform="rotate(-10.772 10.392 12.105)" class="xb9y1kefb"/></g><g filter="url(#iwZiOVb)"><circle fill="url(#i0EZFec)" transform="rotate(-10.772 10.391 12.105)" class="x_4zocqjg"/></g><g filter="url(#iWNtM9b)"><circle fill="url(#ix4e4ud)" transform="rotate(-10.772 19.735 10.327)" class="xmbdiacbw"/><circle fill="url(#iNa8fGc)" transform="rotate(-10.772 19.735 10.327)" class="xmbdiacbw"/></g><g filter="url(#ig0Icib)"><circle transform="rotate(-10.772 19.735 10.327)" class="riln3mbhq"/><circle fill="url(#ijYxtzc)" transform="rotate(-10.772 19.735 10.327)" class="b4yeeydho"/><circle fill="url(#i85WHZb)" transform="rotate(-10.772 19.735 10.327)" class="b4yeeydho"/></g><g filter="url(#imLvYZZ)"><path fill="url(#iWcKZnd)" class="tiy4_oniz"/></g><path fill="url(#iBS9PUc)" class="jjtfdacjy"/><path fill="url(#iLk6snd)" class="jjtfdacjy"/><path fill="url(#iEDckie)" class="jjtfdacjy"/><path fill="url(#iQgljGb)" class="jjtfdacjy"/><g filter="url(#icJqv5d)"><path fill="url(#iW5FjTd)" class="yngi1i-3o"/></g><g filter="url(#itoCOfe)"><path class="cxsdcj2oe"/><path fill="url(#irQPADd)" class="k9kdhlz3s"/><path fill="url(#i7tlF8b)" class="k9kdhlz3s"/><path fill="url(#i4YoWBc)" class="k9kdhlz3s"/><path fill="url(#iIDZqve)" class="k9kdhlz3s"/></g><g filter="url(#iDAvP3b)"><path class="bnl185l3q"/></g><g filter="url(#iDoaKse)"><path class="ack7xvbcf"/><path fill="url(#iidPdoc)" class="n5lc-g6le"/><path fill="url(#iUW5gGd)" class="n5lc-g6le"/><path fill="url(#iBfvO7c)" class="n5lc-g6le"/><path fill="url(#iSRlmNc)" class="n5lc-g6le"/></g><path stroke="url(#imjk0Xc)" class="djwtqubvz"/><g filter="url(#iBv2CPb)"><path stroke="url(#iVs9cwb)" class="c8yzn6bob"/></g><path class="s8dqgfsnd"/><path fill="url(#ivqWYwc)" class="z309avbbd"/><path fill="url(#icF2Yqf)" class="z309avbbd"/><path fill="url(#ix4sfCb)" class="z309avbbd"/><path fill="url(#iLvSsik)" class="z309avbbd"/><path fill="url(#i12K5xd)" class="z309avbbd"/><path fill="url(#inZ8zPX)" class="z309avbbd"/><path fill="url(#i6cxqlb)" class="z309avbbd"/><g filter="url(#i0dOWbb)"><path fill="url(#iZh6Bdd)" class="qowxsbcpr"/><path fill="url(#i2sDUNc)" class="qowxsbcpr"/><path fill="url(#iyfhV0e)" class="qowxsbcpr"/></g><path fill="url(#i3ZOmSb)" class="hqap6gbzd"/><path fill="url(#iuN7Aze)" class="hqap6gbzd"/><g filter="url(#i1Tm9Ab)"><path fill="url(#ipqYsEc)" class="y2liwsmbp"/><path fill="url(#i40y3Od)" class="y2liwsmbp"/></g><g filter="url(#iLnfY6d)"><path class="g5eww7b-b"/><path fill="url(#igTR7Od)" class="vl4i5tbfu"/><path fill="url(#i6HxRbd)" class="vl4i5tbfu"/><path fill="url(#iZC8ZLE)" class="vl4i5tbfu"/></g><path fill="url(#i9LPiQb)" class="nhxpakb_r"/><path fill="url(#iyOElUc)" class="nhxpakb_r"/><path fill="url(#iSMedAd)" class="t3sgdibod"/><path fill="url(#iuM5drg)" class="t3sgdibod"/><path fill="url(#iBfcUmd)" class="q3lt_hi5r"/><path fill="url(#i1cseDc)" class="q3lt_hi5r"/><path fill="url(#iPARwzz)" class="q3lt_hi5r"/><path fill="url(#iS4c7Mc)" class="egn1vxbey"/><path fill="url(#iZ8MGPc)" class="jqhijwbgs"/><path fill="url(#iCnuZPb)" class="qd1hv2b2y"/><path fill="url(#ieAqJre)" class="qd1hv2b2y"/><path fill="url(#ihXOzYb)" class="qd1hv2b2y"/><g filter="url(#iTGjtOd)"><path stroke="url(#iDkp70S)" class="zsebb5bfl"/></g><path fill="url(#iPf8ZCb)" class="gk0o4koun"/><path fill="url(#izhasYL)" class="gk0o4koun"/><path fill="url(#i4zR3sc)" class="lsfoj7b0x"/><g filter="url(#ikuSOEd)"><path fill="url(#i6DQlZc)" class="gd7err10h"/><path fill="url(#iIHeSNb)" class="gd7err10h"/><path fill="url(#iLHFbke)" class="gd7err10h"/></g><path fill="url(#i6ifAcb)" class="a5vumnzpj"/><path fill="url(#iFjAHbb)" class="a5vumnzpj"/><path fill="url(#iQVwvfd)" class="a5vumnzpj"/><path fill="url(#iIjM6Sc)" class="a5vumnzpj"/><path fill="url(#iw8YUss)" class="a5vumnzpj"/><path class="eljq4pb7c"/><path fill="url(#iQaONge)" class="amszydpis"/><path fill="url(#iFJSDxd)" class="amszydpis"/><path class="v-wuj75tv"/><path fill="url(#iu0JW2c)" class="z6iupab7r"/><path fill="url(#iJwDboe)" class="z6iupab7r"/><path fill="url(#ivkmCOG)" class="a47yfyb-p"/><path fill="url(#iK9GNyc)" class="a47yfyb-p"/><path fill="url(#iAAIWLe)" class="a47yfyb-p"/><path fill="url(#iIhwMkA)" class="a47yfyb-p"/><path fill="url(#iWLJqhc)" class="hc3tylbek"/><path fill="url(#iNvQqME)" class="hc3tylbek"/><path fill="url(#iCOEHGd)" class="hc3tylbek"/><path fill="url(#idW3M6d)" class="j_bjsebtq"/><path fill="url(#isfuEpe)" class="j_bjsebtq"/><path fill="url(#isoovBd)" class="j_bjsebtq"/><path fill="url(#iTp1dcb)" class="j_bjsebtq"/><g filter="url(#iPIaHkb)"><path stroke="url(#ih6BV4o)" class="jc9dmbctg"/></g><g filter="url(#ie3v0jC)" class="mc2zb0bvp"><path class="dkbldwynw"/></g><g filter="url(#i0zXmGZ)" class="mc2zb0bvp"><path class="nqdk85b9i"/></g><g filter="url(#iuPBkBb)"><circle fill="url(#iFS8LHe)" class="f418ai29f"/></g><g filter="url(#i2S8Z2y)"><circle fill="url(#it65WAc)" class="qorizubst"/></g><path fill="url(#iT3T12c)" class="y-6y6j50i"/><path fill="url(#iIrrNAe)" class="o-5uu3aqr"/><g filter="url(#iDR0kxc)"><path stroke="url(#i95T5db)" class="zvm66wbaj"/><path stroke="url(#izapd8b)" class="zvm66wbaj"/></g><g filter="url(#icr69se)"><path stroke="url(#ibk2dvd)" class="kbqapzbwi"/><path stroke="url(#ijIXL9d)" class="kbqapzbwi"/></g><g filter="url(#iWfap9b)"><path class="u80v6sbei"/><path fill="url(#i5SbK7C)" class="ime8s7bag"/></g><g filter="url(#iW7qOcc)"><path class="azh0llbwh"/><path fill="url(#i94ciHb)" class="bydiw2b0t"/></g><g filter="url(#igjdhyc)"><path stroke="url(#iw5Tmjr)" class="eyhuifigh"/></g><g filter="url(#ipLdltB)"><path stroke="url(#iB9NfBe)" class="r5ah0pa2c"/></g><defs><radialGradient id="iLC24Ib" cx="0" cy="0" r="1" gradientTransform="rotate(63.107 -6.051 21.706)scale(2.97834 5.11643)" gradientUnits="userSpaceOnUse"><stop offset=".114" class="hb881329x"/><stop offset="1" class="ma7f6291s"/></radialGradient><radialGradient id="iR0dKHe" cx="0" cy="0" r="1" gradientTransform="matrix(1.75447 0 0 3.07033 8.723 12.105)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="iNa8fGc" cx="0" cy="0" r="1" gradientTransform="matrix(.82651 -.60183 .68691 .94336 20.107 10.062)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="ijYxtzc" cx="0" cy="0" r="1" gradientTransform="matrix(.82075 -1.5096 .88357 .48039 19.693 11.147)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="i85WHZb" cx="0" cy="0" r="1" gradientTransform="matrix(.25913 .2565 -.33066 .33405 19.735 10.327)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="iWcKZnd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.2761 2.52214 -3.30335 -9.52981 19.08 10.869)" gradientUnits="userSpaceOnUse"><stop class="lljwb4b7o"/><stop offset="1" class="yz3ba2-8e"/></radialGradient><radialGradient id="iEDckie" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84369 9.18752 -12.47157 -2.5027 16.455 8.744)" gradientUnits="userSpaceOnUse"><stop offset=".534" class="p2wpsk9je"/><stop offset=".992" class="lxt4m5pks"/></radialGradient><radialGradient id="iQgljGb" cx="0" cy="0" r="1" gradientTransform="rotate(83.885 1.885 13.755)scale(7.48007 9.10248)" gradientUnits="userSpaceOnUse"><stop offset=".866" class="nld8-1b-b"/><stop offset="1" class="g0w58cbas"/></radialGradient><radialGradient id="irQPADd" cx="0" cy="0" r="1" gradientTransform="matrix(.2311 -3.05295 1.46998 .11128 18.554 6.373)" gradientUnits="userSpaceOnUse"><stop offset=".372" class="v4bc9u3un"/><stop offset="1" class="o90gcpqxu"/></radialGradient><radialGradient id="i7tlF8b" cx="0" cy="0" r="1" gradientTransform="matrix(3.82236 -.36901 .19841 2.05525 16.612 4.952)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="tti32obdt"/><stop offset="1" class="cpvxurbrw"/></radialGradient><radialGradient id="i4YoWBc" cx="0" cy="0" r="1" gradientTransform="rotate(79.228 5.05 9.508)scale(1.6788 2.59998)" gradientUnits="userSpaceOnUse"><stop class="vpyj0s_ar"/><stop offset="1" class="lkn2u3bae"/></radialGradient><radialGradient id="iIDZqve" cx="0" cy="0" r="1" gradientTransform="matrix(2.59816 -2.78687 4.3661 4.07046 8.386 10.672)" gradientUnits="userSpaceOnUse"><stop class="zk3m83b4g"/><stop offset="1" class="gey-evbzc"/></radialGradient><radialGradient id="iSRlmNc" cx="0" cy="0" r="1" gradientTransform="matrix(.0368 .1934 -.62129 .1182 15.699 12.765)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="ix4sfCb" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 .78125 -.62684 2.50735 8.236 21.348)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="wla505bqs"/><stop offset="1" class="rvju2rlnj"/></radialGradient><radialGradient id="iLvSsik" cx="0" cy="0" r="1" gradientTransform="rotate(129.369 -1.266 11.565)scale(2.35689 2.29948)" gradientUnits="userSpaceOnUse"><stop offset=".384" class="eb47hsvqu"/><stop offset="1" class="jqpapdb1m"/></radialGradient><radialGradient id="i12K5xd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15508 -.34883 2.01874 -6.68469 8.598 30.407)" gradientUnits="userSpaceOnUse"><stop class="hk7wqt7lq"/><stop offset="1" class="g3kr4nmzl"/></radialGradient><radialGradient id="i6cxqlb" cx="0" cy="0" r="1" gradientTransform="matrix(1.82811 2.45314 -3.10932 2.3171 8.845 21.347)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="t1ofhibdm"/><stop offset="1" class="imlvuhvwp"/></radialGradient><radialGradient id="iZh6Bdd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0785 6 -4.46735 -1.54757 16.937 25.188)" gradientUnits="userSpaceOnUse"><stop class="v2wkn2ras"/><stop offset="1" class="yxmxw0ard"/></radialGradient><radialGradient id="i2sDUNc" cx="0" cy="0" r="1" gradientTransform="rotate(-132.901 14.95 10.348)scale(4.22338 6.72611)" gradientUnits="userSpaceOnUse"><stop class="bji58ac7a"/><stop offset="1" class="eqapwmsga"/></radialGradient><radialGradient id="iyfhV0e" cx="0" cy="0" r="1" gradientTransform="matrix(-2.62501 -3.8277 2.0945 -1.4364 21.109 26.125)" gradientUnits="userSpaceOnUse"><stop offset=".393" class="c8r1g2bnk"/><stop offset="1" class="kyl8adb5j"/></radialGradient><radialGradient id="i3ZOmSb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.34372 2.81254 -2.95164 -5.608 26.328 21.47)" gradientUnits="userSpaceOnUse"><stop class="z3zsa5bpu"/><stop offset="1" class="c_p6lvbtv"/></radialGradient><radialGradient id="ipqYsEc" cx="0" cy="0" r="1" gradientTransform="rotate(164.954 9.031 12.925)scale(3.00943 4.47011)" gradientUnits="userSpaceOnUse"><stop class="dyh_p3bsl"/><stop offset="1" class="acgtzjb8q"/></radialGradient><radialGradient id="i40y3Od" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66156 -1.3125 1.73451 -2.1958 22.802 25.907)" gradientUnits="userSpaceOnUse"><stop class="fo4qq4q_b"/><stop offset="1" class="a6ayzxb8w"/></radialGradient><radialGradient id="igTR7Od" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 0 0 -5.73004 19.265 29.344)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="jxwdq3van"/><stop offset="1" class="ytapvgb1c"/></radialGradient><radialGradient id="i6HxRbd" cx="0" cy="0" r="1" gradientTransform="rotate(33.14 -38.498 40.635)scale(2.25791 .79383)" gradientUnits="userSpaceOnUse"><stop class="uuwie8bnd"/><stop offset="1" class="nkti4m6tj"/></radialGradient><radialGradient id="iZC8ZLE" cx="0" cy="0" r="1" gradientTransform="matrix(6.57813 0 0 1.16319 12.924 30.406)" gradientUnits="userSpaceOnUse"><stop class="nz1ipmv-m"/><stop offset="1" class="uw-cne-zt"/></radialGradient><radialGradient id="i9LPiQb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.70313 -.62842 0 19.627 28.597)" gradientUnits="userSpaceOnUse"><stop offset=".431" class="hdo03nb1p"/><stop offset="1" class="b26wppbkf"/></radialGradient><radialGradient id="iuM5drg" cx="0" cy="0" r="1" gradientTransform="rotate(168.154 12.812 14.959)scale(6.54566 1.70736)" gradientUnits="userSpaceOnUse"><stop class="s231-6bjz"/><stop offset="1" class="s6qjzwjgb"/></radialGradient><radialGradient id="iBfcUmd" cx="0" cy="0" r="1" gradientTransform="matrix(.84205 2.73 -2.93117 .9041 6.765 20.282)" gradientUnits="userSpaceOnUse"><stop class="ol95frboa"/><stop offset="1" class="i5qbulbys"/></radialGradient><radialGradient id="i1cseDc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 .87171 -.46263 -.67998 9.906 21.254)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="py7fiqzvo"/><stop offset="1" class="rkoscyb2g"/></radialGradient><radialGradient id="iPARwzz" cx="0" cy="0" r="1" gradientTransform="matrix(.32031 .75 -.43392 .18532 7.163 20.891)" gradientUnits="userSpaceOnUse"><stop offset=".827" class="yassptbsb"/><stop offset="1" class="g6isq_a6x"/></radialGradient><radialGradient id="ihXOzYb" cx="0" cy="0" r="1" gradientTransform="matrix(-.3711 1.25391 -.1532 -.04534 16.01 18.882)" gradientUnits="userSpaceOnUse"><stop class="tomvu1bgl"/><stop offset="1" class="sinn-3bvk"/></radialGradient><radialGradient id="iDkp70S" cx="0" cy="0" r="1" gradientTransform="matrix(-.20313 -.60156 1.71998 -.58078 9.312 23.422)" gradientUnits="userSpaceOnUse"><stop class="rihdlqb3v"/><stop offset="1" class="x7yh0i-6p"/></radialGradient><radialGradient id="izhasYL" cx="0" cy="0" r="1" gradientTransform="matrix(-.64063 2 -.16496 -.05284 15.822 18.222)" gradientUnits="userSpaceOnUse"><stop class="njdbcpw8w"/><stop offset="1" class="p6n8nbb9p"/></radialGradient><radialGradient id="iIHeSNb" cx="0" cy="0" r="1" gradientTransform="matrix(1.42187 .6875 -.62811 1.29906 11.455 18.91)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="l8v5z5bog"/><stop offset="1" class="ll6ec2bpd"/></radialGradient><radialGradient id="iFjAHbb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0156 3.18752 -2.63101 -1.6637 9.455 18.869)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="d-33bzb2o"/><stop offset=".996" class="g2g0htigy"/></radialGradient><radialGradient id="iQVwvfd" cx="0" cy="0" r="1" gradientTransform="rotate(119.595 -.167 11.931)scale(3.70167 1.33422)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="ha1dqccsi"/><stop offset="1" class="ziy-jybcv"/></radialGradient><radialGradient id="iIjM6Sc" cx="0" cy="0" r="1" gradientTransform="matrix(-.1359 3.04807 -.73147 -.03261 7.275 18.522)" gradientUnits="userSpaceOnUse"><stop class="eim87q2nu"/><stop offset="1" class="ndf7m0b2h"/></radialGradient><radialGradient id="iw8YUss" cx="0" cy="0" r="1" gradientTransform="matrix(.25 1.01562 -.9916 .24409 8.916 21.08)" gradientUnits="userSpaceOnUse"><stop offset=".412" class="v0y0h5pun"/><stop offset="1" class="sx4xd35ql"/></radialGradient><radialGradient id="iQaONge" cx="0" cy="0" r="1" gradientTransform="matrix(-.97119 .31036 -.1504 -.47062 14.299 16.858)" gradientUnits="userSpaceOnUse"><stop class="y6_vjs3df"/><stop offset="1" class="ui58-1_-x"/></radialGradient><radialGradient id="iFJSDxd" cx="0" cy="0" r="1" gradientTransform="matrix(.03125 -.93275 3.89243 .13041 12.72 17.931)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="w8ej_fbdv"/><stop offset="1" class="ycyum3z7k"/></radialGradient><radialGradient id="iu0JW2c" cx="0" cy="0" r="1" gradientTransform="rotate(-80.715 17.454 2.488)scale(.83681 3.75171)" gradientUnits="userSpaceOnUse"><stop offset=".09" class="qxxa4bmmv"/><stop offset="1" class="j25x9tegw"/></radialGradient><radialGradient id="iJwDboe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 .41406 -.20022 -.51377 13.815 17.928)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="a3emfp-7e"/><stop offset="1" class="tmyz66fau"/></radialGradient><radialGradient id="ivkmCOG" cx="0" cy="0" r="1" gradientTransform="matrix(-.60938 .84374 -2.96419 -2.14083 11.374 19.297)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="tnkwcrb_w"/><stop offset="1" class="fmfd79b2c"/></radialGradient><radialGradient id="iK9GNyc" cx="0" cy="0" r="1" gradientTransform="matrix(1.75 1.28906 -.23264 .31583 11.58 19.642)" gradientUnits="userSpaceOnUse"><stop class="ti3jmkb7y"/><stop offset="1" class="mnw_fc_zm"/></radialGradient><radialGradient id="iAAIWLe" cx="0" cy="0" r="1" gradientTransform="matrix(-.3672 .53142 -1.08325 -.74848 12.062 19.203)" gradientUnits="userSpaceOnUse"><stop offset=".139" class="t5sd16bfc"/><stop offset="1" class="v3_lnpb5q"/></radialGradient><radialGradient id="iIhwMkA" cx="0" cy="0" r="1" gradientTransform="matrix(1.26608 -.19478 .4132 2.68585 8.704 18.904)" gradientUnits="userSpaceOnUse"><stop class="ye-ecgz9l"/><stop offset="1" class="afcdt12xs"/></radialGradient><radialGradient id="iWLJqhc" cx="0" cy="0" r="1" gradientTransform="rotate(-60.743 23.1 3.371)scale(1.93424 2.14966)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="svx6r0gzk"/><stop offset="1" class="tc83oubxb"/></radialGradient><radialGradient id="iNvQqME" cx="0" cy="0" r="1" gradientTransform="matrix(1.15624 .72351 -.29288 .46806 10.767 20.556)" gradientUnits="userSpaceOnUse"><stop class="amlvwb9ik"/><stop offset="1" class="hgj37ubhx"/></radialGradient><radialGradient id="iCOEHGd" cx="0" cy="0" r="1" gradientTransform="matrix(-.42969 1.98437 -4.09811 -.8874 10.197 20.384)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="ud0xernhq"/><stop offset="1" class="diy3tbc3u"/></radialGradient><radialGradient id="isfuEpe" cx="0" cy="0" r="1" gradientTransform="rotate(105.675 .877 16.002)scale(1.31451 .34383)" gradientUnits="userSpaceOnUse"><stop class="cn05xwrkd"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="isoovBd" cx="0" cy="0" r="1" gradientTransform="rotate(105.036 .759 16.478)scale(.54206 .1592)" gradientUnits="userSpaceOnUse"><stop class="em3lc9y5i"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="iTp1dcb" cx="0" cy="0" r="1" gradientTransform="rotate(174.906 8.345 10.495)scale(.43997 .38553)" gradientUnits="userSpaceOnUse"><stop class="tzj34xnjq"/><stop offset="1" class="ugbytbngn"/></radialGradient><radialGradient id="ih6BV4o" cx="0" cy="0" r="1" gradientTransform="matrix(-.26365 -2.21465 3.37212 -.40144 7.768 22.222)" gradientUnits="userSpaceOnUse"><stop class="zxch6_gap"/><stop offset="1" class="upwmevb9h"/></radialGradient><radialGradient id="iFS8LHe" cx="0" cy="0" r="1" gradientTransform="rotate(-62.622 15.28 -4.642)scale(1.6697 2.16279)" gradientUnits="userSpaceOnUse"><stop offset=".053" class="zfr5v_r8t"/><stop offset=".876" class="tpw8-_30q"/></radialGradient><radialGradient id="it65WAc" cx="0" cy="0" r="1" gradientTransform="rotate(-62.622 16.975 -8.778)scale(1.6697 2.16279)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="i89aqmaix"/><stop offset=".535" class="c7hm4yb7u"/></radialGradient><radialGradient id="iT3T12c" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 -.2187 .35569 2.1855 11.447 11.56)" gradientUnits="userSpaceOnUse"><stop class="fdm2y6x_j"/><stop offset="1" class="h1ie4dmkz"/></radialGradient><radialGradient id="iIrrNAe" cx="0" cy="0" r="1" gradientTransform="matrix(1.34375 -.2187 .35569 2.1855 16.078 10.75)" gradientUnits="userSpaceOnUse"><stop class="fdm2y6x_j"/><stop offset="1" class="h1ie4dmkz"/></radialGradient><radialGradient id="izapd8b" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .22656 -.28593 -.22677 13.62 11.195)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="g7xtertqj"/><stop offset="1" class="kloinabmx"/><stop offset="1" class="eovkc4nhj"/></radialGradient><radialGradient id="ijIXL9d" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .22656 -.28593 -.22677 18.25 10.387)" gradientUnits="userSpaceOnUse"><stop offset=".18" class="g7xtertqj"/><stop offset="1" class="kloinabmx"/><stop offset="1" class="eovkc4nhj"/></radialGradient><radialGradient id="i5SbK7C" cx="0" cy="0" r="1" gradientTransform="rotate(-90.973 12.816 -4.032)scale(.61206 1.81073)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="i94ciHb" cx="0" cy="0" r="1" gradientTransform="matrix(-.01039 -.61197 1.81057 -.03073 12.009 9.676)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><linearGradient id="ijRugnb" x1="19.224" x2="12.336" y1="19.011" y2="30.688" gradientUnits="userSpaceOnUse"><stop class="hvtvasx8l"/><stop offset="1" class="sdatcx1hi"/></linearGradient><linearGradient id="iWUO0Qd" x1="15.685" x2="17.218" y1="17.641" y2="18.626" gradientUnits="userSpaceOnUse"><stop offset=".177" class="oxl0s4b8o"/><stop offset="1" class="r2e-k2b3l"/></linearGradient><linearGradient id="i0EZFec" x1="10.391" x2="9.751" y1="12.383" y2="12.383" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="ix4e4ud" x1="20.822" x2="20.003" y1="9.236" y2="11.772" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="iBS9PUc" x1="10.332" x2="12.167" y1="15.257" y2="14.839" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="iLk6snd" x1="20.252" x2="19.197" y1="12.517" y2="12.615" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="iW5FjTd" x1="15.736" x2="21.017" y1="7.9" y2="3.025" gradientUnits="userSpaceOnUse"><stop class="m2z58wb1f"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="iidPdoc" x1="14.424" x2="15.346" y1="12.439" y2="12.264" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="iUW5gGd" x1="16.255" x2="15.245" y1="12.419" y2="12.597" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="iBfvO7c" x1="15.663" x2="15.556" y1="13.287" y2="12.725" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="imjk0Xc" x1="14.733" x2="15.032" y1="15.073" y2="14.317" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="iVs9cwb" x1="9.558" x2="9.961" y1="7.266" y2="9.384" gradientUnits="userSpaceOnUse"><stop offset=".228" class="tkijdf1cs"/><stop offset="1" class="wg8zzjbli"/></linearGradient><linearGradient id="ivqWYwc" x1="9.109" x2="3.64" y1="26.72" y2="25.251" gradientUnits="userSpaceOnUse"><stop class="ena81bblx"/><stop offset="1" class="hjax-mb0n"/></linearGradient><linearGradient id="icF2Yqf" x1="3.515" x2="5.486" y1="26.345" y2="26.91" gradientUnits="userSpaceOnUse"><stop class="eyx6dtigb"/><stop offset="1" class="uels9hbwx"/></linearGradient><linearGradient id="inZ8zPX" x1="9.229" x2="8.837" y1="28.737" y2="28.612" gradientUnits="userSpaceOnUse"><stop class="hkmz0xbqe"/><stop offset="1" class="s03vqlghs"/></linearGradient><linearGradient id="iuN7Aze" x1="24.609" x2="24.296" y1="25.751" y2="24.282" gradientUnits="userSpaceOnUse"><stop class="dy155dxdg"/><stop offset="1" class="dypnkmnss"/></linearGradient><linearGradient id="iyOElUc" x1="19.523" x2="19.437" y1="26.969" y2="27.477" gradientUnits="userSpaceOnUse"><stop class="byw39cbfh"/><stop offset="1" class="uvoxmwj8v"/></linearGradient><linearGradient id="iSMedAd" x1="26.546" x2="26.984" y1="27.188" y2="30.906" gradientUnits="userSpaceOnUse"><stop class="gf4r80b0w"/><stop offset="1" class="jd4hd8b4a"/></linearGradient><linearGradient id="iS4c7Mc" x1="11.144" x2="10.997" y1="22.479" y2="19.836" gradientUnits="userSpaceOnUse"><stop class="fu3c0cblo"/><stop offset="1" class="pdon63boo"/></linearGradient><linearGradient id="iZ8MGPc" x1="12.351" x2="11.964" y1="20.67" y2="18.688" gradientUnits="userSpaceOnUse"><stop class="fu3c0cblo"/><stop offset="1" class="pdon63boo"/></linearGradient><linearGradient id="iCnuZPb" x1="16.078" x2="15.296" y1="18.469" y2="21.455" gradientUnits="userSpaceOnUse"><stop class="e6bcurcdv"/><stop offset="1" class="jxwnoqbqn"/></linearGradient><linearGradient id="ieAqJre" x1="15.205" x2="15.428" y1="21.675" y2="20.784" gradientUnits="userSpaceOnUse"><stop class="w_57dfb5m"/><stop offset="1" class="t78i98bfv"/></linearGradient><linearGradient id="iPf8ZCb" x1="14.952" x2="13.827" y1="17.704" y2="22.032" gradientUnits="userSpaceOnUse"><stop class="nn3wh7bnm"/><stop offset="1" class="tbs366q3s"/></linearGradient><linearGradient id="i4zR3sc" x1="15.265" x2="14.156" y1="18.079" y2="17.719" gradientUnits="userSpaceOnUse"><stop class="h94nvm15h"/><stop offset="1" class="qtvy6rbzh"/></linearGradient><linearGradient id="i6DQlZc" x1="14.453" x2="13.223" y1="17.594" y2="22.344" gradientUnits="userSpaceOnUse"><stop class="qic_n_blg"/><stop offset="1" class="qh-ows9fr"/></linearGradient><linearGradient id="iLHFbke" x1="12.549" x2="12.768" y1="21.41" y2="20.332" gradientUnits="userSpaceOnUse"><stop class="e122-lbju"/><stop offset="1" class="grqmao4rm"/></linearGradient><linearGradient id="i6ifAcb" x1="8.421" x2="8.964" y1="17.094" y2="21.594" gradientUnits="userSpaceOnUse"><stop class="uptie3ora"/><stop offset="1" class="w5xbz1t2h"/></linearGradient><linearGradient id="idW3M6d" x1="16.521" x2="15.937" y1="18.97" y2="21.47" gradientUnits="userSpaceOnUse"><stop class="neym138jd"/><stop offset="1" class="kmp3a3cnr"/></linearGradient><linearGradient id="i95T5db" x1="11.541" x2="13.822" y1="11.602" y2="11.757" gradientUnits="userSpaceOnUse"><stop class="d3bth9bgz"/><stop offset="1" class="pvzvrjbje"/></linearGradient><linearGradient id="ibk2dvd" x1="16.171" x2="18.453" y1="10.794" y2="10.95" gradientUnits="userSpaceOnUse"><stop class="d3bth9bgz"/><stop offset="1" class="pvzvrjbje"/></linearGradient><linearGradient id="iw5Tmjr" x1="17.457" x2="16.884" y1="7.944" y2="7.179" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="iB9NfBe" x1="12.223" x2="10.962" y1="8.81" y2="8.542" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><filter id="iMad6jc" width="3.539" height="3.339" x="8.722" y="10.435" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3537"/></filter><filter id="iwZiOVb" width="2.989" height="2.989" x="8.897" y="10.61" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3537" stdDeviation=".25"/></filter><filter id="iWNtM9b" width="3.589" height="3.589" x="18.066" y="8.408" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3537"/></filter><filter id="ig0Icib" width="2.989" height="2.989" x="18.24" y="8.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3537" stdDeviation=".25"/></filter><filter id="imLvYZZ" width="10.874" height="12.658" x="9.587" y="5.355" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.137255 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3537"/></filter><filter id="icJqv5d" width="8.306" height="7.543" x="12.53" y="2.954" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3537" stdDeviation="1"/></filter><filter id="itoCOfe" width="12.44" height="9.548" x="7.997" y="2.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3537"/></filter><filter id="iDAvP3b" width="3.248" height="4.243" x="13.521" y="10.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3537" stdDeviation=".375"/></filter><filter id="iDoaKse" width="2.362" height="3.225" x="14.191" y="10.433" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3537" stdDeviation=".125"/></filter><filter id="iBv2CPb" width=".927" height="2.29" x="9.329" y="6.964" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3537" stdDeviation=".125"/></filter><filter id="i0dOWbb" width="11.192" height="8.359" x="11.466" y="22.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.607843 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3537"/></filter><filter id="i1Tm9Ab" width="7.407" height="8.444" x="19.048" y="19.127" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3537"/></filter><filter id="iLnfY6d" width="8.208" height="4.667" x="12.416" y="25.739" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.309804 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3537"/></filter><filter id="iTGjtOd" width="3.456" height="1.701" x="7.381" y="22.21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3537" stdDeviation=".1"/></filter><filter id="ikuSOEd" width="4.309" height="4.662" x="11.043" y="16.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.552941 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3537"/></filter><filter id="iPIaHkb" width="3.647" height="2.753" x="6.263" y="19.957" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3537" stdDeviation=".05"/></filter><filter id="ie3v0jC" width="2.634" height="2.141" x="16.374" y="26.197" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3537" stdDeviation=".125"/></filter><filter id="i0zXmGZ" width="4.536" height="1" x="12.746" y="29.003" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3537" stdDeviation=".15"/></filter><filter id="iuPBkBb" width="3.987" height="3.987" x="10.541" y="8.663" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3537" stdDeviation=".325"/></filter><filter id="i2S8Z2y" width="3.987" height="3.987" x="15.13" y="7.934" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3537" stdDeviation=".325"/></filter><filter id="iDR0kxc" width="2.323" height=".964" x="11.446" y="11.076" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3537" stdDeviation=".05"/></filter><filter id="icr69se" width="2.323" height=".964" x="16.076" y="10.269" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3537" stdDeviation=".05"/></filter><filter id="iWfap9b" width="3.02" height="1.667" x="15.705" y="7.185" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3537"/></filter><filter id="iW7qOcc" width="2.88" height="2.147" x="10.719" y="7.978" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3537"/></filter><filter id="igjdhyc" width="3.14" height="1.458" x="15.526" y="7.306" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3537" stdDeviation=".25"/></filter><filter id="ipLdltB" width="3.058" height="2.054" x="10.496" y="8.149" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3537" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-feeding-baby-medium-dark" /></template>
<style>
.a3emfp-7e {
  stop-color: var(--svg-color--967970, #967970);
}

.a47yfyb-p {
  d: path("M8.521 18.887a.28.28 0 0 1 .133-.27c.981-.69 2.005-.304 2.383 0c.304.236 1 .79 1.363 1.082c.446.36.372.961.043 1.317c-.276.298-.751.24-.93.148l-2.097-1.312c-.055-.313-.235-.563-.48-.637c-.247-.074-.403-.133-.415-.328");
}

.a5vumnzpj {
  d: path("M8.13 17.649c1.032-1.086 1.92-1.37 2.32-1.375l.798.867l-.93 3.516c-.18.315-.564.996-.695 1.152c-.164.195-.735.63-1.766.238c-.888-.337-1.15-.898-1.176-1.148c.234-1.168.65-2.358 1.45-3.25");
}

.a6ayzxb8w {
  stop-color: var(--svg-color--289d47, #289D47);
  stop-opacity: 0;
}

.acgtzjb8q {
  stop-color: var(--svg-color--3ba055, #3BA055);
}

.ack7xvbcf {
  fill: var(--svg-color--7d584f, #7D584F);
  d: path("m14.648 11.04l-.204 1.768a.54.54 0 0 0 .642.59l.772-.148a.54.54 0 0 0 .38-.784l-.839-1.57c-.182-.348-.704-.249-.75.143");
}

.afcdt12xs {
  stop-color: var(--svg-color--7c5c50, #7C5C50);
  stop-opacity: 0;
}

.amlvwb9ik {
  stop-color: var(--svg-color--9b7c73, #9B7C73);
}

.amszydpis {
  d: path("M10.1 16.868c.355.125.48.33.515.453l.445.39l2.292.363a.92.92 0 0 0 1.061-.872a.913.913 0 0 0-.922-.95c-1.174.013-2.687.035-3.044.026c-.586-.016-.793.433-.348.59");
}

.azh0llbwh {
  fill: var(--svg-color--352827, #352827);
  d: path("M10.84 9.252V9.25l.002-.002l.004-.004l.01-.012l.03-.033q.037-.04.102-.101c.086-.08.21-.183.373-.286a2.83 2.83 0 0 1 1.436-.434a.534.534 0 1 1 .034 1.067a1.77 1.77 0 0 0-.9.27a1.5 1.5 0 0 0-.27.22a.534.534 0 0 1-.822-.683");
}

.b26wppbkf {
  stop-color: var(--svg-color--286ad9, #286AD9);
}

.b4yeeydho {
  cx: 19.735px;
  cy: 10.327px;
  r: 0.994px;
}

.bji58ac7a {
  stop-color: var(--svg-color--208d47, #208D47);
}

.bnl185l3q {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m14.762 11.15l-.488 1.822c-.035.362.27.66.61.596l.724-.138c.34-.065.513-.459.348-.778l-.806-1.576c-.176-.35-.349-.317-.388.073");
}

.bydiw2b0t {
  d: path("M10.84 9.252V9.25l.002-.002l.004-.004l.01-.012l.03-.033q.037-.04.102-.101c.086-.08.21-.183.373-.286a2.83 2.83 0 0 1 1.436-.434a.534.534 0 1 1 .034 1.067a1.77 1.77 0 0 0-.9.27a1.5 1.5 0 0 0-.27.22a.534.534 0 0 1-.822-.683");
}

.byw39cbfh {
  stop-color: var(--svg-color--0e6996, #0E6996);
}

.c_p6lvbtv {
  stop-color: var(--svg-color--31be7d, #31BE7D);
}

.c0g7wdubv {
  stop-color: var(--svg-color--a27b71, #A27B71);
  stop-opacity: 0;
}

.c7hm4yb7u {
  stop-color: var(--svg-color--8a5a50, #8A5A50);
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c8r1g2bnk {
  stop-color: var(--svg-color--148c3e, #148C3E);
}

.c8yzn6bob {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m9.704 7.339l.167.881c.02.148.021.486-.137.659");
}

.cn05xwrkd {
  stop-color: var(--svg-color--fed466, #FED466);
}

.cpvxurbrw {
  stop-color: var(--svg-color--46383d, #46383D);
  stop-opacity: 0;
}

.cxsdcj2oe {
  fill: var(--svg-color--27151c, #27151C);
  d: path("m18.576 3.956l.461.129c.808.226 1.388.984 1.4 1.905l-.012 3.096c.007.318-.157.564-.462.63l-.018.004s-.116-.9-.163-1.435c-.038-.433-.137-.549-.601-.862c-.25-.17-.469-.454-.528-.768l-.16-.838c-.05-.262-.3-.432-.52-.444c-.663-.037-2.03-.048-3.926.313c-1.897.36-3.164.873-3.767 1.15a.52.52 0 0 0-.321.604l.16.839c.059.314.013.648-.21.908l-.128.187c-.181.197-.227.532-.177.793c.162.567.375 1.395.375 1.395l-.049.007a.63.63 0 0 1-.683-.41L8.099 8.282c-.265-.818-.003-1.737.665-2.244l.382-.29a8 8 0 0 0 .68-.726l.76-1.176c.48-.634 1.292-.951 2.1-.725a2.94 2.94 0 0 0 1.633-.31c.74-.413 1.675-.374 2.417.082l.94.636c.26.221.554.329.9.426");
}

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.d-33bzb2o {
  stop-color: var(--svg-color--734154, #734154);
  stop-opacity: 0;
}

.d3bth9bgz {
  stop-color: var(--svg-color--2d2d2d, #2D2D2D);
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
  stop-opacity: 0;
}

.diy3tbc3u {
  stop-color: var(--svg-color--713d53, #713D53);
}

.djwtqubvz {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.232 14.18c.425.128.908.156 1.398.063c.496-.095.93-.297 1.278-.572a.2.2 0 0 1 .244-.006a.19.19 0 0 1 .066.233m-2.986.282l2.94-.301m-2.94.301a.2.2 0 0 0-.23.086a.19.19 0 0 0 .025.24m.205-.326l-.17.29m3.156-.572l-.046-.02m.046.02l-.046-.02m.046.02a1.94 1.94 0 0 1-1.433 1.156a1.94 1.94 0 0 1-1.758-.549m3.145-.626a1.9 1.9 0 0 1-1.397 1.126a1.9 1.9 0 0 1-1.713-.535m-.035.035v.001l.036-.036m-.036.035l.036-.035");
}

.dkbldwynw {
  stroke: var(--svg-color--8f706a, #8F706A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m16.874 26.697l1.634 1.14");
}

.dy155dxdg {
  stop-color: var(--svg-color--33c966, #33C966);
}

.dyh_p3bsl {
  stop-color: var(--svg-color--279f64, #279F64);
}

.dypnkmnss {
  stop-color: var(--svg-color--33c966, #33C966);
  stop-opacity: 0;
}

.e122-lbju {
  stop-color: var(--svg-color--8b72aa, #8B72AA);
}

.e6bcurcdv {
  stop-color: var(--svg-color--6cd9f5, #6CD9F5);
}

.eb47hsvqu {
  stop-color: var(--svg-color--2170a2, #2170A2);
}

.egn1vxbey {
  d: path("m11.845 21.007l-.46-.5c-.28-.3-.68-.48-1.09-.49c-.42-.01-.82.16-1.11.46l-.17.18l.53-.95c.22-.39.59-.66 1.02-.74s.88.03 1.23.3l.99.8c.33.27.38.75.12 1.09c-.21.26-.56.35-.85.24a.9.9 0 0 0-.21-.39");
}

.eim87q2nu {
  stop-color: var(--svg-color--7f635a, #7F635A);
}

.eljq4pb7c {
  fill: var(--svg-color--7c5b4d, #7C5B4D);
  d: path("M10.1 16.868c.355.125.48.33.515.453l.445.39l2.292.363a.92.92 0 0 0 1.061-.872a.913.913 0 0 0-.922-.95c-1.174.013-2.687.035-3.044.026c-.586-.016-.793.433-.348.59");
}

.em3lc9y5i {
  stop-color: var(--svg-color--fed064, #FED064);
}

.ena81bblx {
  stop-color: var(--svg-color--2f71f9, #2F71F9);
}

.eovkc4nhj {
  stop-color: var(--svg-color--303030, #303030);
  stop-opacity: 0;
}

.eqapwmsga {
  stop-color: var(--svg-color--208d47, #208D47);
  stop-opacity: 0;
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.eyhuifigh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.15 8.094c.409-.155 1.236-.29 1.89.045");
}

.eyx6dtigb {
  stop-color: var(--svg-color--4e83c4, #4E83C4);
}

.f418ai29f {
  cx: 12.535px;
  cy: 10.657px;
  r: 1.344px;
}

.fdm2y6x_j {
  stop-color: var(--svg-color--070509, #070509);
}

.fmfd79b2c {
  stop-color: var(--svg-color--764d50, #764D50);
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

.g0w58cbas {
  stop-color: var(--svg-color--5b4c65, #5B4C65);
}

.g2g0htigy {
  stop-color: var(--svg-color--612e25, #612E25);
}

.g3kr4nmzl {
  stop-color: var(--svg-color--317ff4, #317FF4);
  stop-opacity: 0;
}

.g5eww7b-b {
  fill: var(--svg-color--7d5252, #7D5252);
  d: path("M17.18 26.089a.937.937 0 0 0-1.12 1.497l.93.802a.1.1 0 0 1-.062.175l-3.644.072a.886.886 0 0 0 .018 1.771h6.06v-1l1.062-1.226z");
}

.g6isq_a6x {
  stop-color: var(--svg-color--1a3f75, #1A3F75);
  stop-opacity: 0;
}

.g7xtertqj {
  stop-color: var(--svg-color--303030, #303030);
}

.gd7err10h {
  d: path("m12.167 16.872l2.635.734c.357.104.645.406.521.797l-.779 2.704c-.095.329-.442.504-.851.393l-2.6-.733z");
}

.gey-evbzc {
  stop-color: var(--svg-color--453938, #453938);
  stop-opacity: 0;
}

.gf4r80b0w {
  stop-color: var(--svg-color--27a9f1, #27A9F1);
}

.gk0o4koun {
  d: path("m11.939 16.44l3.172.885c.43.125.744.558.627.96l-.9 3.086c-.115.396-.532.606-1.024.473l-3.129-.883z");
}

.grqmao4rm {
  stop-color: var(--svg-color--b59cc2, #B59CC2);
  stop-opacity: 0;
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.h1ie4dmkz {
  stop-color: var(--svg-color--131212, #131212);
}

.h94nvm15h {
  stop-color: var(--svg-color--43b1db, #43B1DB);
}

.ha1dqccsi {
  stop-color: var(--svg-color--7d5d51, #7D5D51);
}

.hb881329x {
  stop-color: var(--svg-color--1c8ec9, #1C8EC9);
}

.hc3tylbek {
  d: path("M8.857 21.336c-.315.22-.723.211-.906-.11c-.392-.947.72-1.578 1.5-1.597c1.167-.027 1.75.63 1.937 1.121c.188.492.227 1.477-.672 1.54c-.804.055-.847-.5-.98-.743c-.133-.242-.594-.41-.88-.21");
}

.hdo03nb1p {
  stop-color: var(--svg-color--2176c7, #2176C7);
}

.hgj37ubhx {
  stop-color: var(--svg-color--9b7c73, #9B7C73);
  stop-opacity: 0;
}

.hjax-mb0n {
  stop-color: var(--svg-color--246bda, #246BDA);
}

.hk7wqt7lq {
  stop-color: var(--svg-color--5289f2, #5289F2);
}

.hkmz0xbqe {
  stop-color: var(--svg-color--1e7eee, #1E7EEE);
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.hqap6gbzd {
  d: path("M23.445 27.566a4.3 4.3 0 1 0 0-8.6a4.3 4.3 0 0 0 0 8.6");
}

.hvtvasx8l {
  stop-color: var(--svg-color--2ba6ec, #2BA6EC);
}

.i5qbulbys {
  stop-color: var(--svg-color--1f70cf, #1F70CF);
}

.i89aqmaix {
  stop-color: var(--svg-color--936757, #936757);
}

.ime8s7bag {
  d: path("m18.2 7.851l-.002-.001l-.005-.003l-.014-.007l-.04-.02a2.6 2.6 0 0 0-.583-.185a2.83 2.83 0 0 0-1.497.123a.534.534 0 1 0 .361 1.004c.379-.136.706-.123.935-.08a1.5 1.5 0 0 1 .334.106a.534.534 0 0 0 .512-.937");
}

.imlvuhvwp {
  stop-color: var(--svg-color--2e71f4, #2E71F4);
  stop-opacity: 0;
}

.j_bjsebtq {
  d: path("m15.454 21.173l.227.068a.5.5 0 0 0 .492-.12l.363-.352a.13.13 0 0 1 .128-.034l.315.084a.484.484 0 0 0 .253-.935l-.304-.083a.13.13 0 0 1-.097-.109l-.069-.44a.5.5 0 0 0-.36-.403l-.26-.072z");
}

.j25x9tegw {
  stop-color: var(--svg-color--6e413f, #6E413F);
  stop-opacity: 0;
}

.jc9dmbctg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.593 20.157c-.206.432-.319 1.448.875 2.054c1.194.607 1.992.149 2.242-.156");
}

.jd4hd8b4a {
  stop-color: var(--svg-color--297eff, #297EFF);
}

.jjtfdacjy {
  d: path("M9.605 10.167c-.05-.262-.004-.596.177-.793l.128-.187c.224-.26.27-.594.21-.909l-.16-.838a.52.52 0 0 1 .322-.604c.602-.277 1.87-.79 3.766-1.15c1.896-.361 3.263-.35 3.926-.313c.22.012.47.182.52.443l.16.839c.06.314.278.598.528.768c.56.251.565.447.601.862c.047.534.164 1.435.164 1.435l.018-.004l.478 3.938c.173 1.768-.963 3.239-2.592 3.549l-3.153.6c-1.682.32-3.226-.642-3.714-2.35c-.476-1.758-.877-3.536-1.379-5.286");
}

.jqhijwbgs {
  d: path("M10.565 18.977c-.28.05-.54.19-.74.38c.01-.05.02-.1.04-.15l.12-.33c.28-.78 1.09-1.27 1.91-1.15l1.66.23c.42.06.72.45.66.87s-.45.72-.87.66l-1.57-.22c-.34-.26-.78-.37-1.21-.29");
}

.jqpapdb1m {
  stop-color: var(--svg-color--2374a5, #2374A5);
  stop-opacity: 0;
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.jxwdq3van {
  stop-color: var(--svg-color--6c3d40, #6C3D40);
}

.jxwnoqbqn {
  stop-color: var(--svg-color--3782ce, #3782CE);
}

.k_pdrlblj {
  stop-color: var(--svg-color--ebb830, #EBB830);
  stop-opacity: 0;
}

.k9kdhlz3s {
  d: path("m18.576 3.956l.461.129c.808.226 1.388.984 1.4 1.905l-.012 3.096c.007.318-.157.564-.462.63l-.018.004s-.116-.9-.163-1.435c-.038-.433-.137-.549-.601-.862c-.25-.17-.469-.454-.528-.768l-.16-.838c-.05-.262-.3-.432-.52-.444c-.663-.037-2.03-.048-3.926.313c-1.897.36-3.164.873-3.767 1.15a.52.52 0 0 0-.321.604l.16.839c.059.314.013.648-.21.908l-.128.187c-.181.197-.227.532-.177.793c.162.567.375 1.395.375 1.395l-.049.007a.63.63 0 0 1-.683-.41L8.099 8.282c-.265-.818-.003-1.737.665-2.244l.382-.29a8 8 0 0 0 .68-.726l.76-1.176c.48-.634 1.292-.951 2.1-.725a2.94 2.94 0 0 0 1.633-.31c.74-.413 1.675-.374 2.417.082l.94.636c.26.221.554.329.9.426");
}

.kbqapzbwi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.226 10.786c.151.14.548.37 1.063.273c.562-.106.888-.458.96-.64");
}

.kloinabmx {
  stop-color: var(--svg-color--c26f5c, #C26F5C);
  stop-opacity: 0;
}

.kmp3a3cnr {
  stop-color: var(--svg-color--ce953a, #CE953A);
}

.kyl8adb5j {
  stop-color: var(--svg-color--148c3e, #148C3E);
  stop-opacity: 0;
}

.l8v5z5bog {
  stop-color: var(--svg-color--6e574e, #6E574E);
}

.lkn2u3bae {
  stop-color: var(--svg-color--3e3034, #3E3034);
  stop-opacity: 0;
}

.ll6ec2bpd {
  stop-color: var(--svg-color--6e574e, #6E574E);
  stop-opacity: 0;
}

.lljwb4b7o {
  stop-color: var(--svg-color--9a6f5e, #9A6F5E);
}

.lsfoj7b0x {
  d: path("m14.826 17.505l-2.636-.735l-1.073 3.895l2.6.734c.408.11.755-.065.85-.394l.78-2.703c.123-.391-.164-.694-.521-.797");
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.lxt4m5pks {
  stop-color: var(--svg-color--5f3f53, #5F3F53);
}

.m2z58wb1f {
  stop-color: var(--svg-color--a27e72, #A27E72);
}

.ma7f6291s {
  stop-color: var(--svg-color--1c8ec9, #1C8EC9);
  stop-opacity: 0;
}

.mbo6hmbkt {
  d: path("M7.155 30.407c-1.05 0-1.9-.85-1.89-1.9l.01-2.13c0-5.77 4.79-10.46 10.69-10.46c5.91 0 10.69 4.68 10.69 10.46l.17 4.03z");
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.mnw_fc_zm {
  stop-color: var(--svg-color--94776f, #94776F);
  stop-opacity: 0;
}

.n5lc-g6le {
  d: path("m14.648 11.04l-.204 1.768a.54.54 0 0 0 .642.59l.772-.148a.54.54 0 0 0 .38-.784l-.839-1.57c-.182-.348-.704-.249-.75.143");
}

.n8jici3hn {
  stop-color: var(--svg-color--fed466, #FED466);
  stop-opacity: 0;
}

.ndf7m0b2h {
  stop-color: var(--svg-color--7f635a, #7F635A);
  stop-opacity: 0;
}

.ne4llzbvb {
  stop-color: var(--svg-color--301a2d, #301A2D);
}

.neym138jd {
  stop-color: var(--svg-color--f3c22a, #F3C22A);
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.nhxpakb_r {
  d: path("M18.998 27.19a.15.15 0 0 1 .15-.15h.643v3.367h-.793z");
}

.njdbcpw8w {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
}

.nkti4m6tj {
  stop-color: var(--svg-color--7d505c, #7D505C);
  stop-opacity: 0;
}

.nld8-1b-b {
  stop-color: var(--svg-color--6d4b55, #6D4B55);
  stop-opacity: 0;
}

.nn3wh7bnm {
  stop-color: var(--svg-color--58d4f5, #58D4F5);
}

.nqdk85b9i {
  stroke: var(--svg-color--8c6565, #8C6565);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.246 29.503h3.536");
}

.nz1ipmv-m {
  stop-color: var(--svg-color--7c4264, #7C4264);
}

.o-5uu3aqr {
  d: path("M16.184 10.516c.08-.01.16.01.22.06a1.074 1.074 0 0 0 1.6-.29c.04-.07.11-.12.19-.13c.22-.04.39.2.28.4c-.23.39-.63.68-1.1.77c-.48.08-.95-.05-1.3-.34a.263.263 0 0 1 .11-.47");
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.o90gcpqxu {
  stop-color: var(--svg-color--3d3437, #3D3437);
  stop-opacity: 0;
}

.ol95frboa {
  stop-color: var(--svg-color--277aa9, #277AA9);
}

.oxl0s4b8o {
  stop-color: var(--svg-color--553a48, #553A48);
}

.p2wpsk9je {
  stop-color: var(--svg-color--7f5954, #7F5954);
  stop-opacity: 0;
}

.p6n8nbb9p {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
  stop-opacity: 0;
}

.pdon63boo {
  stop-color: var(--svg-color--f38820, #F38820);
  stop-opacity: 0;
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.pvzvrjbje {
  stop-color: var(--svg-color--2d2d2d, #2D2D2D);
  stop-opacity: 0;
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.pwdeswylh {
  d: path("M15.685 18.937c1.06 0 1.91-.86 1.91-1.91v-2.26a1.91 1.91 0 1 0-3.82 0v2.26c-.01 1.06.85 1.91 1.91 1.91");
}

.py7fiqzvo {
  stop-color: var(--svg-color--052e6b, #052E6B);
}

.q3lt_hi5r {
  d: path("M10.214 22.093c-.284.88-1.448 1.292-2.6.92c-1.152-.37-1.793-1.177-1.573-2.265c.18-.888.883-1.75 2.738-1.24c1.153.372 1.719 1.705 1.435 2.585");
}

.q8x82vmoe {
  stop-color: var(--svg-color--483e3e, #483E3E);
  stop-opacity: 0;
}

.qd1hv2b2y {
  d: path("m15.53 18.272l.554.16a.15.15 0 0 1 .103.185l-.784 2.73a.15.15 0 0 1-.185.102l-.555-.159z");
}

.qh-ows9fr {
  stop-color: var(--svg-color--a07cb6, #A07CB6);
}

.qic_n_blg {
  stop-color: var(--svg-color--d2c9d1, #D2C9D1);
}

.qorizubst {
  cx: 17.123px;
  cy: 9.928px;
  r: 1.344px;
}

.qowxsbcpr {
  d: path("M21.835 24.426c-1.17-2.04-3.78-2.73-5.81-1.56l-2.43 1.4c-2.04 1.17-2.73 3.78-1.56 5.81l.21.33h7.73l.3-.18a4.23 4.23 0 0 0 1.56-5.8");
}

.qtvy6rbzh {
  stop-color: var(--svg-color--42b8e0, #42B8E0);
}

.qxxa4bmmv {
  stop-color: var(--svg-color--6e413f, #6E413F);
}

.r2e-k2b3l {
  stop-color: var(--svg-color--706065, #706065);
}

.r5ah0pa2c {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.121 9.578c.267-.345.912-.777 1.808-.804");
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.rihdlqb3v {
  stop-color: var(--svg-color--429ce6, #429CE6);
}

.riln3mbhq {
  cx: 19.735px;
  cy: 10.327px;
  r: 0.994px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.rkoscyb2g {
  stop-color: var(--svg-color--124ea0, #124EA0);
  stop-opacity: 0;
}

.rvju2rlnj {
  stop-color: var(--svg-color--1972ba, #1972BA);
  stop-opacity: 0;
}

.s03vqlghs {
  stop-color: var(--svg-color--1e7eee, #1E7EEE);
  stop-opacity: 0;
}

.s231-6bjz {
  stop-color: var(--svg-color--48b6ff, #48B6FF);
}

.s6qjzwjgb {
  stop-color: var(--svg-color--48b6ff, #48B6FF);
  stop-opacity: 0;
}

.s8dqgfsnd {
  fill: var(--svg-color--58b2ec, #58B2EC);
  d: path("m29.145 25.747l-4.94-6.05l-3.16 8.57z");
}

.sdatcx1hi {
  stop-color: var(--svg-color--1577e2, #1577E2);
}

.sinn-3bvk {
  stop-color: var(--svg-color--6cd8f5, #6CD8F5);
  stop-opacity: 0;
}

.svx6r0gzk {
  stop-color: var(--svg-color--713e53, #713E53);
}

.sx4xd35ql {
  stop-color: var(--svg-color--734054, #734054);
  stop-opacity: 0;
}

.t1ofhibdm {
  stop-color: var(--svg-color--3395d2, #3395D2);
}

.t3sgdibod {
  d: path("M20.615 26.184c1.598-.23 4.567-.809 6.543-1.27c1.522-.263 2.64 1.203 2.64 2.781c0 1.371-1.022 2.236-1.746 2.618a.86.86 0 0 1-.403.093h-8.014V27.32c0-.797.281-1 .98-1.136");
}

.t5sd16bfc {
  stop-color: var(--svg-color--6b463c, #6B463C);
}

.t78i98bfv {
  stop-color: var(--svg-color--735caf, #735CAF);
  stop-opacity: 0;
}

.tbs366q3s {
  stop-color: var(--svg-color--4760c0, #4760C0);
}

.tc83oubxb {
  stop-color: var(--svg-color--886658, #886658);
}

.ti3jmkb7y {
  stop-color: var(--svg-color--94776f, #94776F);
}

.tiy4_oniz {
  d: path("m9.931 11.57l.049-.008s-.212-.828-.375-1.395c-.05-.262-.004-.596.177-.793l.128-.187c.224-.26.27-.594.21-.909l-.16-.838a.52.52 0 0 1 .322-.604c.602-.277 1.87-.79 3.766-1.15c1.896-.361 3.263-.35 3.926-.313c.22.012.47.182.52.443l.16.839c.06.314.278.598.528.768c.56.251.565.447.601.862c.047.534.164 1.435.164 1.435l.018-.004l.478 3.938c.173 1.768-.963 3.239-2.592 3.549l-3.153.6c-1.682.32-3.226-.642-3.714-2.35z");
}

.tkijdf1cs {
  stop-color: var(--svg-color--32272d, #32272D);
}

.tmyz66fau {
  stop-color: var(--svg-color--7d5b50, #7D5B50);
  stop-opacity: 0;
}

.tnkwcrb_w {
  stop-color: var(--svg-color--846256, #846256);
}

.tomvu1bgl {
  stop-color: var(--svg-color--78e0ff, #78E0FF);
}

.tpw8-_30q {
  stop-color: var(--svg-color--6b4041, #6B4041);
}

.tti32obdt {
  stop-color: var(--svg-color--46383d, #46383D);
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
}

.tzj34xnjq {
  stop-color: var(--svg-color--ffd267, #FFD267);
}

.u80v6sbei {
  fill: var(--svg-color--352827, #352827);
  d: path("m18.2 7.851l-.002-.001l-.005-.003l-.014-.007l-.04-.02a2.6 2.6 0 0 0-.583-.185a2.83 2.83 0 0 0-1.497.123a.534.534 0 1 0 .361 1.004c.379-.136.706-.123.935-.08a1.5 1.5 0 0 1 .334.106a.534.534 0 0 0 .512-.937");
}

.ud0xernhq {
  stop-color: var(--svg-color--713d53, #713D53);
  stop-opacity: 0;
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.uels9hbwx {
  stop-color: var(--svg-color--5082c1, #5082C1);
  stop-opacity: 0;
}

.ugbytbngn {
  stop-color: var(--svg-color--ffd267, #FFD267);
  stop-opacity: 0;
}

.ui58-1_-x {
  stop-color: var(--svg-color--856053, #856053);
  stop-opacity: 0;
}

.uptie3ora {
  stop-color: var(--svg-color--73564c, #73564C);
}

.upwmevb9h {
  stop-color: var(--svg-color--377dcb, #377DCB);
  stop-opacity: 0;
}

.uuwie8bnd {
  stop-color: var(--svg-color--6a3e48, #6A3E48);
}

.uvoxmwj8v {
  stop-color: var(--svg-color--0e6996, #0E6996);
  stop-opacity: 0;
}

.uw-cne-zt {
  stop-color: var(--svg-color--7c4264, #7C4264);
  stop-opacity: 0;
}

.v-wuj75tv {
  fill: var(--svg-color--7c5a4f, #7C5A4F);
  d: path("M9.67 17.79c.243.25.33.526.343.632l.485.47l2.34.407a.89.89 0 0 0 1.025-.694a.9.9 0 0 0-.774-1.078c-1.09-.133-2.42-.306-2.779-.347c-.613-.07-.945.297-.64.61");
}

.v0y0h5pun {
  stop-color: var(--svg-color--734054, #734054);
}

.v2wkn2ras {
  stop-color: var(--svg-color--31ae6a, #31AE6A);
}

.v3_lnpb5q {
  stop-color: var(--svg-color--6b463c, #6B463C);
  stop-opacity: 0;
}

.v4bc9u3un {
  stop-color: var(--svg-color--3d3437, #3D3437);
}

.v9-6-sbuc {
  stop-color: var(--svg-color--483e3e, #483E3E);
}

.vgfjqtbdb {
  stop-color: var(--svg-color--301a2d, #301A2D);
  stop-opacity: 0;
}

.vl4i5tbfu {
  d: path("M17.18 26.089a.937.937 0 0 0-1.12 1.497l.93.802a.1.1 0 0 1-.062.175l-3.644.072a.886.886 0 0 0 .018 1.771h6.06v-1l1.062-1.226z");
}

.vpyj0s_ar {
  stop-color: var(--svg-color--3e3034, #3E3034);
}

.w_57dfb5m {
  stop-color: var(--svg-color--735caf, #735CAF);
}

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w5xbz1t2h {
  stop-color: var(--svg-color--714f47, #714F47);
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.w8ej_fbdv {
  stop-color: var(--svg-color--7e574e, #7E574E);
}

.wg8zzjbli {
  stop-color: var(--svg-color--32272d, #32272D);
  stop-opacity: 0;
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.wla505bqs {
  stop-color: var(--svg-color--1972ba, #1972BA);
}

.x_4zocqjg {
  cx: 10.391px;
  cy: 12.105px;
  r: 0.994px;
}

.x7yh0i-6p {
  stop-color: var(--svg-color--429ce6, #429CE6);
  stop-opacity: 0;
}

.xb9y1kefb {
  cx: 10.392px;
  cy: 12.105px;
  r: 1.669px;
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.xmbdiacbw {
  cx: 19.735px;
  cy: 10.327px;
  r: 1.669px;
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y-6y6j50i {
  d: path("M11.554 11.326c.08-.01.16.01.22.06a1.074 1.074 0 0 0 1.6-.29c.04-.07.11-.12.19-.13c.22-.04.39.2.28.4c-.23.39-.63.68-1.1.77c-.48.08-.95-.05-1.3-.34c-.19-.14-.11-.43.11-.47");
}

.y2liwsmbp {
  d: path("M21.575 24.347a4.3 4.3 0 0 1 .71-5.22a4.31 4.31 0 0 0-2.61 6.21a4.304 4.304 0 0 0 6.78 1.01c-1.84.51-3.87-.26-4.88-2");
}

.y6_vjs3df {
  stop-color: var(--svg-color--987a70, #987A70);
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.yassptbsb {
  stop-color: var(--svg-color--1a3f75, #1A3F75);
}

.ycyum3z7k {
  stop-color: var(--svg-color--7e574e, #7E574E);
  stop-opacity: 0;
}

.ye-ecgz9l {
  stop-color: var(--svg-color--7c5c50, #7C5C50);
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.yngi1i-3o {
  d: path("m17.897 4.953l-2.831 1.583a1.047 1.047 0 0 0 .841 1.907l2.929-.974z");
}

.ytapvgb1c {
  stop-color: var(--svg-color--6c3d40, #6C3D40);
  stop-opacity: 0;
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.yxmxw0ard {
  stop-color: var(--svg-color--32996b, #32996B);
}

.yz3ba2-8e {
  stop-color: var(--svg-color--704e48, #704E48);
}

.z309avbbd {
  d: path("m2.201 30.407l2.93-9.156c.351-1.414 2.07-2.104 3.65-1.614s2.49 2.332 2.006 3.692l-2.216 7.078z");
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.z3zsa5bpu {
  stop-color: var(--svg-color--53f595, #53F595);
}

.z6iupab7r {
  d: path("M9.67 17.79c.243.25.33.526.343.632l.485.47l2.34.407a.89.89 0 0 0 1.025-.694a.9.9 0 0 0-.774-1.078c-1.09-.133-2.42-.306-2.779-.347c-.613-.07-.945.297-.64.61");
}

.zfr5v_r8t {
  stop-color: var(--svg-color--74514c, #74514C);
}

.ziy-jybcv {
  stop-color: var(--svg-color--7d5d51, #7D5D51);
  stop-opacity: 0;
}

.zk3m83b4g {
  stop-color: var(--svg-color--453938, #453938);
}

.zsebb5bfl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M7.78 23.438c.579.14 1.92.172 2.657-.828");
}

.zvm66wbaj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M11.596 11.593c.15.14.547.371 1.062.274c.563-.107.888-.459.961-.64");
}

.zxch6_gap {
  stop-color: var(--svg-color--377dcb, #377DCB);
}

</style>
