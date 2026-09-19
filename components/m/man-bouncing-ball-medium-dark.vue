<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#i9lGIGd)" transform="rotate(26.961 19.37 13.47)" class="r_owdkb9z"/><g filter="url(#in9pYab)"><path class="fi8kapbyt"/></g><circle fill="url(#igd0DZc)" class="idljld4zp"/><circle fill="url(#igS1Qbd)" class="idljld4zp"/><circle fill="url(#iz32gEQ)" class="idljld4zp"/><circle fill="url(#ijFkTLU)" class="idljld4zp"/><g filter="url(#ixlogab)"><path fill="url(#i0yZFVd)" class="ohg8m5b7a"/></g><path fill="url(#itYc30S)" class="pmliwkbra"/><path fill="url(#i4AzWsY)" class="pmliwkbra"/><path fill="url(#iCUMoEc)" class="cvzwhptha"/><path fill="url(#idv3syc)" class="cvzwhptha"/><g filter="url(#ifw763o)"><path fill="url(#iQfxCxb)" class="nzx3or8du"/><path fill="url(#ihvu0fe)" class="nzx3or8du"/><path fill="url(#irTWmse)" class="nzx3or8du"/></g><g filter="url(#iXsHEuc)"><path fill="url(#ihTfWPe)" class="nk1vvujwy"/><path fill="url(#ieA83vb)" class="nk1vvujwy"/></g><path fill="url(#i0488Ae)" class="i5mcpobyz"/><path fill="url(#iWGq1Cd)" class="i5mcpobyz"/><path fill="url(#iXmTP2b)" class="u072kwb9c"/><path fill="url(#iwnOGxb)" class="u072kwb9c"/><path fill="url(#imDgmed)" class="u072kwb9c"/><path fill="url(#imHw3yb)" class="u072kwb9c"/><path class="vam_w95qk"/><path fill="url(#iB3O36Y)" class="k0yxbw7lh"/><path fill="url(#i2oUhlc)" class="k0yxbw7lh"/><path fill="url(#iLGf6rd)" class="k0yxbw7lh"/><g filter="url(#iRiQ9Id)"><path class="hvrhlpbsz"/><path fill="url(#ipRtVxG)" class="o5zmdfb2x"/><path fill="url(#ix89MNd)" class="o5zmdfb2x"/><path fill="url(#iXt88Ec)" class="o5zmdfb2x"/></g><g filter="url(#ibudbNb)"><path fill="url(#i8Nc0jI)" class="g3xz3yb1j"/><path fill="url(#ieUYuJe)" class="g3xz3yb1j"/></g><g filter="url(#i7WjIyb)"><path fill="url(#itXcSrc)" class="jqhqeoboo"/><path fill="url(#iOQGJ1x)" class="jqhqeoboo"/></g><g filter="url(#isRpmle)"><path fill="url(#ikZpzfd)" clip-rule="evenodd" class="sd_n72xhe"/></g><path class="cs99bhbjl"/><path fill="url(#iUb69tc)" class="dfx2m_r2g"/><path fill="url(#iChZRWc)" class="dfx2m_r2g"/><path clip-rule="evenodd" class="xw75uqvlc"/><path fill="url(#iUcCxIc)" clip-rule="evenodd" class="i81i9acqn"/><path clip-rule="evenodd" class="epk04qbku"/><path fill="url(#i00icHe)" clip-rule="evenodd" class="efpbvsb0m"/><path clip-rule="evenodd" class="v7jcm4h7p"/><path fill="url(#iuop6Pe)" clip-rule="evenodd" class="nlyf4ib8d"/><path clip-rule="evenodd" class="x41u_8htb"/><path fill="url(#ikyprXc)" clip-rule="evenodd" class="viuz5dbki"/><path fill="url(#itvErnc)" clip-rule="evenodd" class="mvsqrnbte"/><g filter="url(#i8MrTvb)"><path fill="url(#ig7EJld)" class="ezzpwwmye"/><path fill="url(#i4TzDAb)" class="ezzpwwmye"/></g><path fill="url(#iK2UlDc)" class="ezzpwwmye"/><path fill="url(#iRQLEEU)" clip-rule="evenodd" class="sd_n72xhe"/><g filter="url(#iKnDh9x)"><circle fill="url(#ibB1h2c)" class="gh7tnsbfq"/></g><g filter="url(#iL1zAab)"><circle fill="url(#ieJPsbc)" class="ed6ms7tri"/></g><g filter="url(#iWnTLHh)"><circle fill="url(#iyPZlgd)" class="c83uj9bud"/><circle fill="url(#idDnsqc)" class="c83uj9bud"/></g><g filter="url(#i7KXEre)"><circle class="tw_n9zr7u"/><circle fill="url(#idWgzPe)" class="i03cbbbso"/><circle fill="url(#il3l6hc)" class="i03cbbbso"/></g><g filter="url(#iXZTzRb)"><path fill="url(#idOalie)" class="efrf3-bll"/><path fill="url(#iBwP1Lx)" class="efrf3-bll"/><path fill="url(#iMjeFZd)" class="efrf3-bll"/></g><path fill="url(#id0uhHi)" class="w_s2noode"/><path fill="url(#iYWVPlb)" class="w_s2noode"/><path fill="url(#ifotLDb)" class="w_s2noode"/><path fill="url(#i22DMlK)" class="w_s2noode"/><path fill="url(#iQEJMZc)" class="w_s2noode"/><g filter="url(#iQ1lyPd)"><path fill="url(#iZEx6Sc)" class="dj3o4u2iv"/></g><g filter="url(#i1PaqFc)"><path class="m6rj6pbzb"/><path fill="url(#ihUmyXd)" class="c_xex2bac"/><path fill="url(#iYbTlMb)" class="c_xex2bac"/><path fill="url(#iLy6MRb)" class="c_xex2bac"/><path fill="url(#i1OKCgc)" class="c_xex2bac"/></g><g filter="url(#imRdzHG)"><path class="sj2xsx-sw"/></g><g filter="url(#iNAmXee)"><path class="eky7dp7zo"/><path fill="url(#iqIDWBI)" class="h1n56l72b"/><path fill="url(#iRGycgc)" class="h1n56l72b"/><path fill="url(#iVpcCPe)" class="h1n56l72b"/><path fill="url(#iNW7DDc)" class="h1n56l72b"/></g><path stroke="url(#iHFOAqd)" class="tfg6otbsp"/><g filter="url(#iW6iKIe)"><path class="gpzot6b6r"/><path fill="url(#iAJgrse)" class="ahyxedgsw"/></g><g filter="url(#ifv7cZb)"><path class="v290okb-z"/><path fill="url(#iibpSAc)" class="t-_futbdw"/></g><path class="sj84nybgo"/><path fill="url(#iOQfriH)" class="r6smjf07k"/><path class="lkb85rmyp"/><g filter="url(#ieo5QXd)"><path class="vfn8g2baf"/><path fill="url(#i1P9ume)" class="ifh_31b1f"/></g><g filter="url(#imuNmDc)"><path fill="url(#i6AGzkc)" class="r2j4cwbuw"/></g><path class="brtu2jb1z"/><path fill="url(#iPOJpYc)" class="qefb_nbvu"/><path class="paa99_b5q"/><g filter="url(#iq3SdJc)"><path fill="url(#iiIgaSP)" class="m_6j6qbqv"/></g><g filter="url(#i0K57vf)"><ellipse transform="rotate(-27.914 11.684 5.653)" class="fxofsn1op"/><ellipse fill="url(#iJfhMBd)" transform="rotate(-27.914 11.684 5.653)" class="slawajb_c"/></g><g filter="url(#iXvlY2c)"><path stroke="url(#iEYJIne)" class="ljmdpdbwr"/></g><g filter="url(#iNoHjyd)"><path stroke="url(#ib5OCbd)" class="wxnqr0bgi"/></g><g filter="url(#irHyg6c)"><path stroke="url(#iY4Q8Ce)" class="wbxccxbgh"/></g><path fill="url(#iG2i7ze)" class="swkdpwiwa"/><path fill="url(#ibe4MHY)" class="swkdpwiwa"/><path fill="url(#iH2gfWY)" class="swkdpwiwa"/><path fill="url(#i0EF3bc)" class="swkdpwiwa"/><g filter="url(#iJ3Ml1d)"><path class="wh6405bfr"/></g><g filter="url(#ibSZFAn)"><path class="y5gqwcbjl"/><path fill="url(#ikDRoLc)" class="h-uvj1rjt"/></g><defs><radialGradient id="i9lGIGd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .55552 -.42115 0 19.7 14.025)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="bpjbo-5wq"/><stop offset="1" class="fpwanpawi"/></radialGradient><radialGradient id="igS1Qbd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65625 1.65625 -1.54687 -1.54687 6.337 18.361)" gradientUnits="userSpaceOnUse"><stop class="mdx4akbxm"/><stop offset="1" class="t5qac2c1p"/></radialGradient><radialGradient id="iz32gEQ" cx="0" cy="0" r="1" gradientTransform="rotate(-174.823 3.309 9.543)scale(3.29739 3.69421)" gradientUnits="userSpaceOnUse"><stop offset=".439" class="mneu5xbew"/><stop offset=".947" class="fqax45bnt"/></radialGradient><radialGradient id="ijFkTLU" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 3.98763 -3.995 -.4383 5.462 18.08)" gradientUnits="userSpaceOnUse"><stop offset=".682" class="w7i-07blq"/><stop offset="1" class="o27_2ebdq"/></radialGradient><radialGradient id="i0yZFVd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34374 .78906 -.8071 -1.37445 6.282 18.838)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="rx_o_e39d"/><stop offset="1" class="ancrqsbmw"/></radialGradient><radialGradient id="itYc30S" cx="0" cy="0" r="1" gradientTransform="matrix(.93752 -4.625 2.23622 .4533 11.555 25.112)" gradientUnits="userSpaceOnUse"><stop offset=".131" class="i1ugtm59q"/><stop offset="1" class="jcizzuyvv"/></radialGradient><radialGradient id="i4AzWsY" cx="0" cy="0" r="1" gradientTransform="matrix(3.8125 -.34375 .46441 5.15075 9.868 22.705)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="ita7_2enr"/><stop offset="1" class="xau3og86r"/></radialGradient><radialGradient id="iQfxCxb" cx="0" cy="0" r="1" gradientTransform="matrix(1.34136 3.28833 -5.45057 2.22337 6.741 26.6)" gradientUnits="userSpaceOnUse"><stop class="vhhvj2t-s"/><stop offset="1" class="so34edl-m"/></radialGradient><radialGradient id="ihvu0fe" cx="0" cy="0" r="1" gradientTransform="matrix(-.30078 .14845 -.19933 -.40386 10.865 26.557)" gradientUnits="userSpaceOnUse"><stop class="wg6epmg7n"/><stop offset="1" class="gc9u7lbfl"/></radialGradient><radialGradient id="irTWmse" cx="0" cy="0" r="1" gradientTransform="rotate(52.306 -21.848 22.547)scale(.76023 .57466)" gradientUnits="userSpaceOnUse"><stop class="wg6epmg7n"/><stop offset="1" class="gc9u7lbfl"/></radialGradient><radialGradient id="i0488Ae" cx="0" cy="0" r="1" gradientTransform="rotate(153.3 8.343 12.624)scale(2.99172 1.46479)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="vinvwq12a"/><stop offset="1" class="aaj8m1ghv"/></radialGradient><radialGradient id="iXmTP2b" cx="0" cy="0" r="1" gradientTransform="rotate(153.02 9.532 12.326)scale(1.92866 1.03496)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="pa6b3tb0c"/><stop offset="1" class="sdljx8amv"/></radialGradient><radialGradient id="imDgmed" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21874 .66407 -.44091 -.8092 23.174 18.11)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="don2uv-3m"/><stop offset="1" class="gpus1rbiy"/></radialGradient><radialGradient id="imHw3yb" cx="0" cy="0" r="1" gradientTransform="rotate(112.416 5.88 17.726)scale(2.70434 1.05462)" gradientUnits="userSpaceOnUse"><stop offset=".566" class="n30gi-53g"/><stop offset="1" class="tt7xwipig"/></radialGradient><radialGradient id="iB3O36Y" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5 2.10937 -4.01056 -4.75325 19.634 19.83)" gradientUnits="userSpaceOnUse"><stop offset=".379" class="o7o4d8pps"/><stop offset=".92" class="j1n_ptbit"/></radialGradient><radialGradient id="i2oUhlc" cx="0" cy="0" r="1" gradientTransform="matrix(1.92188 1.03124 -1.60806 2.99689 16.696 19.143)" gradientUnits="userSpaceOnUse"><stop offset=".429" class="eaj548bgj"/><stop offset="1" class="cxprecb8d"/></radialGradient><radialGradient id="iLGf6rd" cx="0" cy="0" r="1" gradientTransform="matrix(-.87818 .60937 -1.28653 -1.85405 19.918 18.752)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="bnpz8rbzn"/><stop offset="1" class="awgn1c4se"/></radialGradient><radialGradient id="ipRtVxG" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 -3.875 4.85233 .35219 16.493 20.924)" gradientUnits="userSpaceOnUse"><stop class="c-qpqdbmc"/><stop offset="1" class="cy6exab_x"/></radialGradient><radialGradient id="ix89MNd" cx="0" cy="0" r="1" gradientTransform="rotate(-75.406 21.679 2.265)scale(3.74586 2.0917)" gradientUnits="userSpaceOnUse"><stop class="sn3dy7bnn"/><stop offset="1" class="qu4z4jkud"/></radialGradient><radialGradient id="iXt88Ec" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.89062 -2.42602 0 16.93 16.846)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="u_3e452pz"/><stop offset="1" class="t5f4fqbxv"/></radialGradient><radialGradient id="i8Nc0jI" cx="0" cy="0" r="1" gradientTransform="rotate(159.963 11.46 11.54)scale(2.82739 3.3966)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="xu1e5_bcz"/><stop offset="1" class="jixz69llq"/></radialGradient><radialGradient id="ikZpzfd" cx="0" cy="0" r="1" gradientTransform="matrix(3.40624 -1.28127 .66322 1.76315 6.712 13.924)" gradientUnits="userSpaceOnUse"><stop class="ibqq90als"/><stop offset="1" class="enjwdpbad"/></radialGradient><radialGradient id="iUb69tc" cx="0" cy="0" r="1" gradientTransform="matrix(2.34375 1.71875 -2.5451 3.4706 12.493 8.049)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="qudtebbqf"/><stop offset="1" class="qle5g2bis"/></radialGradient><radialGradient id="iChZRWc" cx="0" cy="0" r="1" gradientTransform="matrix(3.34375 -1 4.7268 15.80522 13.295 9.934)" gradientUnits="userSpaceOnUse"><stop offset=".713" class="ew_xbgbtk"/><stop offset=".945" class="za46tubip"/></radialGradient><radialGradient id="iUcCxIc" cx="0" cy="0" r="1" gradientTransform="rotate(154.153 1.22 7.576)scale(1.51176 .82196)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="s6non86-m"/><stop offset="1" class="r6n7exbot"/></radialGradient><radialGradient id="i00icHe" cx="0" cy="0" r="1" gradientTransform="rotate(149.949 .803 7.929)scale(1.74533 1.04837)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="s6non86-m"/><stop offset="1" class="r6n7exbot"/></radialGradient><radialGradient id="iuop6Pe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49195 .93111 -.57955 -.92863 5.337 14.93)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="s6non86-m"/><stop offset="1" class="r6n7exbot"/></radialGradient><radialGradient id="ikyprXc" cx="0" cy="0" r="1" gradientTransform="rotate(149.08 .7 8.37)scale(1.53562 .93807)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="s6non86-m"/><stop offset="1" class="r6n7exbot"/></radialGradient><radialGradient id="itvErnc" cx="0" cy="0" r="1" gradientTransform="rotate(129.668 -.12 8.922)scale(1.13713 .21244)" gradientUnits="userSpaceOnUse"><stop class="o9doel8cg"/><stop offset="1" class="b5xboq-mx"/></radialGradient><radialGradient id="ig7EJld" cx="0" cy="0" r="1" gradientTransform="matrix(-3.12494 8.57033 -5.82186 -2.12278 16.9 7.479)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="uqxno_b8g"/><stop offset=".81" class="d4a71bwtp"/></radialGradient><radialGradient id="i4TzDAb" cx="0" cy="0" r="1" gradientTransform="rotate(-104.504 15.358 1.219)scale(8.36833 2.71135)" gradientUnits="userSpaceOnUse"><stop class="g_v4sglua"/><stop offset="1" class="o67susxgp"/></radialGradient><radialGradient id="iK2UlDc" cx="0" cy="0" r="1" gradientTransform="rotate(112.005 5.271 8.996)scale(4.08677 4.31955)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="ip3ktqbqy"/><stop offset="1" class="whspc9bgn"/></radialGradient><radialGradient id="iRQLEEU" cx="0" cy="0" r="1" gradientTransform="matrix(2.53394 .29688 -.19207 1.63939 5.896 13.22)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="y2teulbve"/><stop offset="1" class="rrpkz-bur"/></radialGradient><radialGradient id="ibB1h2c" cx="0" cy="0" r="1" gradientTransform="matrix(.79446 0 0 1.39031 9.89 6.005)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="idDnsqc" cx="0" cy="0" r="1" gradientTransform="matrix(.37426 -.27252 .31105 .42717 15.121 5.886)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="idWgzPe" cx="0" cy="0" r="1" gradientTransform="rotate(-61.467 12.83 -9.371)scale(.77838 .45559)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="il3l6hc" cx="0" cy="0" r="1" gradientTransform="matrix(.11738 .1162 -.1498 .15132 14.954 6.006)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="iBwP1Lx" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.59174 .7283 0 13.858 5.43)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="iMjeFZd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.62208 .77362 0 11.795 5.49)" gradientUnits="userSpaceOnUse"><stop class="z_g0j449a"/><stop offset="1" class="s5xtkwbhw"/></radialGradient><radialGradient id="ifotLDb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.00499 -5.43657 0 12.66 5.202)" gradientUnits="userSpaceOnUse"><stop offset=".619" class="rko8b-bmk"/><stop offset="1" class="whxihzpaf"/></radialGradient><radialGradient id="i22DMlK" cx="0" cy="0" r="1" gradientTransform="matrix(-.77737 -.52296 .29767 -.44247 14.727 8.685)" gradientUnits="userSpaceOnUse"><stop class="m13zyzbuk"/><stop offset="1" class="kzk-_ccou"/></radialGradient><radialGradient id="iQEJMZc" cx="0" cy="0" r="1" gradientTransform="matrix(1.17313 -.2463 .156 .74306 11.15 9.15)" gradientUnits="userSpaceOnUse"><stop class="m13zyzbuk"/><stop offset="1" class="kzk-_ccou"/></radialGradient><radialGradient id="ihUmyXd" cx="0" cy="0" r="1" gradientTransform="matrix(.36119 -1.33851 .6445 .17391 14.763 4.146)" gradientUnits="userSpaceOnUse"><stop offset=".372" class="v4bc9u3un"/><stop offset="1" class="o90gcpqxu"/></radialGradient><radialGradient id="iYbTlMb" cx="0" cy="0" r="1" gradientTransform="matrix(1.73157 .15935 -.08568 .93106 14.02 3.35)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="tti32obdt"/><stop offset="1" class="cpvxurbrw"/></radialGradient><radialGradient id="iLy6MRb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .7602 -1.17733 0 12.796 2.112)" gradientUnits="userSpaceOnUse"><stop class="vpyj0s_ar"/><stop offset="1" class="lkn2u3bae"/></radialGradient><radialGradient id="i1OKCgc" cx="0" cy="0" r="1" gradientTransform="matrix(1.39164 -1.01983 1.59773 2.18023 9.876 5.198)" gradientUnits="userSpaceOnUse"><stop class="zk3m83b4g"/><stop offset="1" class="gey-evbzc"/></radialGradient><radialGradient id="iNW7DDc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .08914 -.28639 0 12.944 6.733)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="iAJgrse" cx="0" cy="0" r="1" gradientTransform="rotate(-80.201 9.956 -5.723)scale(.27715 .81995)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="iibpSAc" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 8.792 -4.34)scale(.27716 .81997)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="iOQfriH" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36722 -.5841 0 13.782 5.697)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i1P9ume" cx="0" cy="0" r="1" gradientTransform="matrix(-.10497 -.13527 .18623 -.14452 13.68 5.735)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iPOJpYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36723 -.58413 0 11.807 5.697)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iJfhMBd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0035 -.22363 .26881 -.0042 11.678 5.796)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iG2i7ze" cx="0" cy="0" r="1" gradientTransform="matrix(-3.75 0 0 -3.07783 14.334 3.733)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="e3m1knbgu"/><stop offset="1" class="o-iz-vbwp"/></radialGradient><radialGradient id="i0EF3bc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.16797 0 0 -.11719 15.16 3.2)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="jy7vazb8a"/><stop offset="1" class="oha5hfbwc"/></radialGradient><radialGradient id="ikDRoLc" cx="0" cy="0" r="1" gradientTransform="rotate(-50.981 21.243 -14.137)scale(2.33289 4.31503)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="ks47q0bjb"/><stop offset="1" class="ep0hblblj"/></radialGradient><filter id="in9pYab" width="7.486" height="8.65" x="14.87" y="7.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.243137 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23228"/></filter><filter id="ixlogab" width="5.439" height="5.49" x="2.462" y="16.577" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.223529 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23228"/></filter><filter id="ifw763o" width="6.264" height="4.296" x="4.74" y="25.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.505882 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23228"/></filter><filter id="iXsHEuc" width="5.105" height="3.176" x="4.74" y="26.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.564706 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23228"/></filter><filter id="iRiQ9Id" width="7.339" height="5.547" x="11.424" y="16.846" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23228"/></filter><filter id="ibudbNb" width="5.437" height="5.553" x="22.676" y="16.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.356863 0 0 0 0 0.4 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23228"/></filter><filter id="i7WjIyb" width="2.689" height="5.353" x="25.225" y="16.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.92549 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23228"/></filter><filter id="isRpmle" width="8.098" height="6.294" x="5.657" y="8.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.298039 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23228"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.411765 0 0 0 0 0.203922 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23228" result="effect2_innerShadow_3987_23228"/></filter><filter id="i8MrTvb" width="7.636" height="9.986" x="11.582" y="7.079" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.227451 0 0 0 0 0.34902 0 0 0 0 0.643137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23228"/></filter><filter id="iKnDh9x" width="1.712" height="1.512" x="9.891" y="5.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23228"/></filter><filter id="iL1zAab" width="1.901" height="1.901" x="9.696" y="5.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23228" stdDeviation=".25"/></filter><filter id="iWnTLHh" width="1.762" height="1.762" x="14.197" y="5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23228"/></filter><filter id="i7KXEre" width="1.901" height="1.901" x="14.003" y="5.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23228" stdDeviation=".25"/></filter><filter id="iXZTzRb" width="4.696" height="5.595" x="10.461" y="3.459" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.137255 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23228"/></filter><filter id="iQ1lyPd" width="5.922" height="5.388" x="10.873" y="1.459" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23228" stdDeviation="1"/></filter><filter id="i1PaqFc" width="5.705" height="3.741" x="9.943" y="2.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23228"/></filter><filter id="imRdzHG" width="2.297" height="2.714" x="11.54" y="5.072" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23228" stdDeviation=".375"/></filter><filter id="iNAmXee" width="1.05" height="1.414" x="12.271" y="5.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23228" stdDeviation=".05"/></filter><filter id="iW6iKIe" width="1.486" height="1.067" x="13.331" y="4.135" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23228"/></filter><filter id="ifv7cZb" width="1.486" height="1.067" x="11.001" y="4.135" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23228"/></filter><filter id="ieo5QXd" width=".466" height=".425" x="13.396" y="5.443" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23228" stdDeviation=".05"/></filter><filter id="imuNmDc" width=".622" height=".632" x="13.721" y="5.422" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23228" stdDeviation=".1"/></filter><filter id="iq3SdJc" width=".665" height=".69" x="11.71" y="5.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23228" stdDeviation=".1"/></filter><filter id="i0K57vf" width=".523" height=".428" x="11.423" y="5.439" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23228" stdDeviation=".05"/></filter><filter id="iXvlY2c" width="1.137" height=".495" x="13.398" y="4.544" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23228" stdDeviation=".05"/></filter><filter id="iNoHjyd" width="1.172" height=".521" x="11.035" y="4.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23228" stdDeviation=".05"/></filter><filter id="irHyg6c" width=".867" height="1.438" x="10.252" y="3.452" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23228" stdDeviation=".125"/></filter><filter id="iJ3Ml1d" width="2.625" height="5.367" x="19.763" y="9.301" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23228" stdDeviation=".25"/></filter><filter id="ibSZFAn" width="3.404" height="3.248" x="18.396" y="8.299" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.760784 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23228"/></filter><linearGradient id="igd0DZc" x1="4.743" x2="6.868" y1="18.986" y2="21.111" gradientUnits="userSpaceOnUse"><stop class="v616eizae"/><stop offset=".904" class="zbj0d-fph"/></linearGradient><linearGradient id="iCUMoEc" x1="11.118" x2="8.993" y1="26.299" y2="25.549" gradientUnits="userSpaceOnUse"><stop class="g7n19jw2p"/><stop offset="1" class="lw0wsfo7o"/></linearGradient><linearGradient id="idv3syc" x1="8.915" x2="10.134" y1="25.299" y2="25.763" gradientUnits="userSpaceOnUse"><stop class="ykf__gbvs"/><stop offset="1" class="jpzj4ccfh"/></linearGradient><linearGradient id="ihTfWPe" x1="5.181" x2="9.845" y1="27.205" y2="29.737" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="ieA83vb" x1="7.524" x2="7.466" y1="28.135" y2="28.241" gradientUnits="userSpaceOnUse"><stop offset=".401" class="poy_ydb2w"/><stop offset="1" class="f_xo_r1_u"/></linearGradient><linearGradient id="iWGq1Cd" x1="21.97" x2="21.54" y1="21.127" y2="20.354" gradientUnits="userSpaceOnUse"><stop class="d5idi46tx"/><stop offset="1" class="cf_a3cr-i"/></linearGradient><linearGradient id="iwnOGxb" x1="23.368" x2="23.009" y1="20.408" y2="19.674" gradientUnits="userSpaceOnUse"><stop class="wh6te8bft"/><stop offset="1" class="yodkvfdyw"/></linearGradient><linearGradient id="ieUYuJe" x1="26.314" x2="26.114" y1="18.838" y2="18.924" gradientUnits="userSpaceOnUse"><stop offset=".244" class="jylqepbzd"/><stop offset="1" class="v2dwqfdba"/><stop offset="1" class="byifs8b3c"/></linearGradient><linearGradient id="itXcSrc" x1="27.533" x2="25.439" y1="21.149" y2="16.272" gradientUnits="userSpaceOnUse"><stop class="rtyid72og"/><stop offset="1" class="bcnephb9f"/></linearGradient><linearGradient id="iOQGJ1x" x1="26.269" x2="26.38" y1="18.967" y2="18.921" gradientUnits="userSpaceOnUse"><stop offset=".401" class="vvs_3yeki"/><stop offset="1" class="waplrebxe"/></linearGradient><linearGradient id="ieJPsbc" x1="10.646" x2="10.356" y1="6.131" y2="6.131" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="iyPZlgd" x1="15.445" x2="15.074" y1="5.511" y2="6.66" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="idOalie" x1="14.623" x2="11.166" y1="6.182" y2="6.697" gradientUnits="userSpaceOnUse"><stop class="ah-u2v6vh"/><stop offset="1" class="hp2sktbkw"/></linearGradient><linearGradient id="id0uhHi" x1="10.353" x2="11.205" y1="7.402" y2="7.372" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="iYWVPlb" x1="14.998" x2="14.52" y1="7.023" y2="6.977" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="iZEx6Sc" x1="12.555" x2="16.242" y1="4.831" y2="3.51" gradientUnits="userSpaceOnUse"><stop offset=".109" class="fxywcj73h"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="iqIDWBI" x1="12.405" x2="12.829" y1="6.48" y2="6.48" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="iRGycgc" x1="13.221" x2="12.756" y1="6.626" y2="6.62" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="iVpcCPe" x1="12.884" x2="12.884" y1="6.962" y2="6.703" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="iHFOAqd" x1="12.327" x2="12.524" y1="7.694" y2="7.382" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="i6AGzkc" x1="14.135" x2="13.993" y1="5.721" y2="5.808" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iiIgaSP" x1="12.144" x2="12.002" y1="5.721" y2="5.809" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iEYJIne" x1="14.142" x2="13.951" y1="4.752" y2="4.364" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="ib5OCbd" x1="11.74" x2="11.202" y1="4.695" y2="4.469" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="iY4Q8Ce" x1="10.685" x2="10.685" y1="3.783" y2="4.759" gradientUnits="userSpaceOnUse"><stop offset=".228" class="tkijdf1cs"/><stop offset="1" class="wg8zzjbli"/></linearGradient><linearGradient id="ibe4MHY" x1="9.716" x2="13.427" y1="3.92" y2="3.92" gradientUnits="userSpaceOnUse"><stop class="uul9_ttvm"/><stop offset="1" class="hwrqknt4x"/></linearGradient><linearGradient id="iH2gfWY" x1="13.49" x2="13.49" y1="4.264" y2="4.147" gradientUnits="userSpaceOnUse"><stop class="g0kn9gb3f"/><stop offset="1" class="nqhicrryp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-bouncing-ball-medium-dark" /></template>
<style>
.aaj8m1ghv {
  stop-color: var(--svg-color--7d4d5e, #7D4D5E);
}

.ah-u2v6vh {
  stop-color: var(--svg-color--9b6c5e, #9B6C5E);
}

.ahyxedgsw {
  d: path("m14.48 4.774l-.002-.001l-.002-.002l-.005-.004l-.07-.049a1.28 1.28 0 0 0-.866-.167a.242.242 0 1 0 .075.478a.8.8 0 0 1 .534.099l.029.02a.242.242 0 0 0 .307-.374");
}

.ancrqsbmw {
  stop-color: var(--svg-color--4c3945, #4C3945);
}

.awgn1c4se {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
  stop-opacity: 0;
}

.b5xboq-mx {
  stop-color: var(--svg-color--835a58, #835A58);
}

.bcnephb9f {
  stop-color: var(--svg-color--d4c1e8, #D4C1E8);
}

.bnpz8rbzn {
  stop-color: var(--svg-color--9e99a0, #9E99A0);
}

.bpjbo-5wq {
  stop-color: var(--svg-color--6f423e, #6F423E);
}

.brtu2jb1z {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.712 5.358a.63.63 0 0 0-.613.479c-.02.079.04.154.121.154h1.01a.104.104 0 0 0 .103-.123a.634.634 0 0 0-.62-.51");
}

.byifs8b3c {
  stop-color: var(--svg-color--ff6937, #FF6937);
  stop-opacity: 0;
}

.c_xex2bac {
  d: path("m14.978 3.073l.194.096a.89.89 0 0 1 .461.966l-.267 1.377c-.024.142-.118.237-.259.24l-.008.001s.024-.41.048-.652c.02-.196-.014-.256-.194-.435a.57.57 0 0 1-.17-.386v-.386a.26.26 0 0 0-.194-.242c-.292-.072-.899-.193-1.773-.193s-1.481.12-1.773.193a.235.235 0 0 0-.194.242v.386a.48.48 0 0 1-.17.386l-.073.073c-.097.072-.145.217-.145.338c.024.266.048.652.048.652h-.022a.29.29 0 0 1-.27-.242l-.266-1.376a.92.92 0 0 1 .485-.942l.195-.096c.121-.073.242-.17.364-.266l.437-.458a.89.89 0 0 1 .996-.145c.242.072.51.072.752 0a1.09 1.09 0 0 1 1.069.241l.364.362c.097.121.219.193.364.266");
}

.c-qpqdbmc {
  stop-color: var(--svg-color--806d93, #806D93);
}

.c0g7wdubv {
  stop-color: var(--svg-color--a27b71, #A27B71);
  stop-opacity: 0;
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c83uj9bud {
  cx: 14.953px;
  cy: 6.005px;
  r: 0.756px;
}

.cf_a3cr-i {
  stop-color: var(--svg-color--7e4d5f, #7E4D5F);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cpvxurbrw {
  stop-color: var(--svg-color--46383d, #46383D);
  stop-opacity: 0;
}

.cs99bhbjl {
  fill: var(--svg-color--9f7b71, #9F7B71);
  d: path("M11.657 11.705c-.237-1.5.143-2.745.383-3.125c.294-.606.987-.804 1.297-.828h2.437c.386.577.634 1.595.744 2.24c.034.203.078.404.145.6c.365 1.063 1.627 4.74 2.14 6.133a.253.253 0 0 1-.239.34h-5.25a.57.57 0 0 1-.55-.391c-.423-1.315-.893-3.616-1.107-4.969");
}

.cvzwhptha {
  d: path("m11.432 25.15l-.853 2.118l-1.976-.969c.175-.463.469-1.25.754-2.041z");
}

.cxprecb8d {
  stop-color: var(--svg-color--93869f, #93869F);
  stop-opacity: 0;
}

.cy6exab_x {
  stop-color: var(--svg-color--806d93, #806D93);
  stop-opacity: 0;
}

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.d4a71bwtp {
  stop-color: var(--svg-color--3b8be5, #3B8BE5);
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.d5idi46tx {
  stop-color: var(--svg-color--7e4d5f, #7E4D5F);
}

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
  stop-opacity: 0;
}

.dfx2m_r2g {
  d: path("M11.657 11.705c-.237-1.5.143-2.745.383-3.125c.294-.606.987-.804 1.297-.828h2.437c.386.577.634 1.595.744 2.24c.034.203.078.404.145.6c.365 1.063 1.627 4.74 2.14 6.133a.253.253 0 0 1-.239.34h-5.25a.57.57 0 0 1-.55-.391c-.423-1.315-.893-3.616-1.107-4.969");
}

.dj3o4u2iv {
  d: path("m14.59 3.46l-1.393.464a.474.474 0 0 0 .213.92l1.385-.186z");
}

.don2uv-3m {
  stop-color: var(--svg-color--9c7f8c, #9C7F8C);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e3m1knbgu {
  stop-color: var(--svg-color--e7dff1, #E7DFF1);
}

.eaj548bgj {
  stop-color: var(--svg-color--695279, #695279);
}

.ed6ms7tri {
  cx: 10.646px;
  cy: 6.005px;
  r: 0.45px;
}

.efpbvsb0m {
  fill-rule: evenodd;
  d: path("M5.23 14.105c-.306.178-.45.37-.473.426a.415.415 0 0 1-.768-.315c.12-.291.436-.603.824-.828c.407-.237.95-.414 1.58-.382a.415.415 0 0 1-.042.829a2.03 2.03 0 0 0-1.121.27");
}

.efrf3-bll {
  d: path("M10.487 5.728h.022s-.024-.385-.048-.651c0-.12.048-.266.146-.338l.073-.073a.48.48 0 0 0 .17-.386v-.386c0-.12.072-.218.194-.242a7.4 7.4 0 0 1 1.772-.193c.875 0 1.482.12 1.773.193a.26.26 0 0 1 .194.242v.386c0 .145.073.29.17.386c.228.16.214.247.195.435a21 21 0 0 0-.049.652h.008l-.12 1.792c-.073.801-.703 1.36-1.453 1.36H12.08c-.775 0-1.38-.559-1.453-1.36z");
}

.eky7dp7zo {
  fill: var(--svg-color--8c5f5e, #8C5F5E);
  d: path("m12.623 5.876l-.24.77a.244.244 0 0 0 .235.316h.356c.167 0 .285-.16.236-.316l-.241-.77c-.052-.17-.292-.17-.346 0");
}

.enjwdpbad {
  stop-color: var(--svg-color--79574b, #79574B);
}

.ep0hblblj {
  stop-color: var(--svg-color--c1add1, #C1ADD1);
  stop-opacity: 0;
}

.epk04qbku {
  fill: var(--svg-color--815d52, #815D52);
  fill-rule: evenodd;
  d: path("M5.23 14.105c-.306.178-.45.37-.473.426a.415.415 0 0 1-.768-.315c.12-.291.436-.603.824-.828c.407-.237.95-.414 1.58-.382a.415.415 0 0 1-.042.829a2.03 2.03 0 0 0-1.121.27");
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.ew_xbgbtk {
  stop-color: var(--svg-color--8e695d, #8E695D);
  stop-opacity: 0;
}

.ezzpwwmye {
  d: path("M11.884 8.91c.147.244.5.623 1.02.623c.886 0 1.253-.43 1.542-1.101c.124-.288.365-.79.438-.953c.695.105.89.273.89.273l.008.012c-.149.277-.4.78-.453.984c-.07.274-.238 1.051.25 1.688c.373.486.812.598 1.233.588c.481 1.403 1.533 4.46 1.99 5.7a.253.253 0 0 1-.238.34h-5.25a.57.57 0 0 1-.55-.39c-.423-1.315-.893-3.616-1.107-4.969c-.19-1.197.015-2.232.227-2.794");
}

.f_xo_r1_u {
  stop-color: var(--svg-color--e4d5e5, #E4D5E5);
  stop-opacity: 0;
}

.fi8kapbyt {
  fill: var(--svg-color--876054, #876054);
  d: path("M15.216 10.026q.559-.015 1.474.059c.827.064 1.691.195 2.138.53c.582.371.909.828 1.026 1.372c.133.614.023 1.139-.23 1.8l-.151.383c-.124.312-.24.6-.287.801c-.06.258.098.433.404.437c.054 0 .106.026.14.068a.4.4 0 0 0 .206.147c.082.022.14.017.22.01q.044-.005.1-.008a.14.14 0 0 1 .117.06a.33.33 0 0 0 .2.146a.45.45 0 0 0 .243-.017a.2.2 0 0 1 .173.021a.6.6 0 0 0 .205.085c.14.02.305-.039.367-.234c.035-.108.08-.297.121-.476c.098-.417.25-.821.25-1.255a4.94 4.94 0 0 0 .121-2.46c-.248-1.15-.915-2.13-1.988-2.813c-1.177-.75-3.758-.943-5.022-.903l-.173.005v2.25q.147-.001.346-.008");
}

.fpwanpawi {
  stop-color: var(--svg-color--703536, #703536);
}

.fqax45bnt {
  stop-color: var(--svg-color--bf5347, #BF5347);
}

.ft5dv1b6b {
  fill: none;
}

.fxofsn1op {
  cx: 11.684px;
  cy: 5.653px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.176px;
  ry: 0.089px;
}

.fxywcj73h {
  stop-color: var(--svg-color--a47f73, #A47F73);
}

.g_v4sglua {
  stop-color: var(--svg-color--5290df, #5290DF);
}

.g0kn9gb3f {
  stop-color: var(--svg-color--b391c2, #B391C2);
}

.g3xz3yb1j {
  d: path("M23.563 19.82v-.779a.27.27 0 0 0-.276-.293c-.162.01-.508-.055-.595-.394c-.087-.34.206-.574.363-.65l2.362-1.327a.4.4 0 0 1 .566.195l1.908 4.586a.3.3 0 0 1-.18.4l-.57.194a.53.53 0 0 1-.624-.246c-.766-1.313-1.607-1.506-2.042-1.521a1.4 1.4 0 0 0-.51.09c-.185.064-.402-.06-.402-.256");
}

.g7n19jw2p {
  stop-color: var(--svg-color--e2cded, #E2CDED);
}

.gc9u7lbfl {
  stop-color: var(--svg-color--53adfa, #53ADFA);
  stop-opacity: 0;
}

.gey-evbzc {
  stop-color: var(--svg-color--453938, #453938);
  stop-opacity: 0;
}

.gh7tnsbfq {
  cx: 10.646px;
  cy: 6.005px;
  r: 0.756px;
}

.gpus1rbiy {
  stop-color: var(--svg-color--ccbdcf, #CCBDCF);
  stop-opacity: 0;
}

.gpzot6b6r {
  fill: var(--svg-color--352827, #352827);
  d: path("m14.48 4.774l-.002-.001l-.002-.002l-.005-.004l-.07-.049a1.28 1.28 0 0 0-.866-.167a.242.242 0 1 0 .075.478a.8.8 0 0 1 .534.099l.029.02a.242.242 0 0 0 .307-.374");
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.h-uvj1rjt {
  d: path("M19.324 8.304a.095.095 0 0 0-.107.03c-.44.55-.75 1.567-.821 2.056q.254.094.432.226c.418.266.704.576.875.93c.812-.549 1.637-.802 2.097-.855c-.342-.803-.922-1.49-1.735-2.009a4 4 0 0 0-.741-.378");
}

.h1n56l72b {
  d: path("m12.623 5.876l-.24.77a.244.244 0 0 0 .235.316h.356c.167 0 .285-.16.236-.316l-.241-.77c-.052-.17-.292-.17-.346 0");
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.hp2sktbkw {
  stop-color: var(--svg-color--744d4a, #744D4A);
}

.hvrhlpbsz {
  fill: var(--svg-color--83788b, #83788B);
  d: path("M12.962 17.455c.094-.275.216-.52.266-.61h5.148c.539 1.52-.652 2.927-1.2 3.24c-.978.6-2.891 1.779-3.085 1.898c-.242.148-.512.238-.73.066c-.759-.531-1.555-1.508-1.844-2.008c-.232-.4.023-.74.18-.86c.827-.698 1.148-1.382 1.265-1.726");
}

.hwrqknt4x {
  stop-color: var(--svg-color--d3c9dc, #D3C9DC);
  stop-opacity: 0;
}

.i03cbbbso {
  cx: 14.953px;
  cy: 6.005px;
  r: 0.45px;
}

.i1ugtm59q {
  stop-color: var(--svg-color--8e625f, #8E625F);
}

.i5mcpobyz {
  d: path("M19.267 22.455c-.213.09-.352.07-.372.047l.754-2.93a.72.72 0 0 0 .555-.039l3.11-1.75l.726 2.145c-1.518.805-4.56 2.437-4.773 2.527");
}

.i81i9acqn {
  fill-rule: evenodd;
  d: path("M6.322 13.685c-.775-.132-1.17.089-1.3.289a.415.415 0 1 1-.697-.451c.392-.605 1.215-.814 2.136-.657a.415.415 0 1 1-.14.819");
}

.ibqq90als {
  stop-color: var(--svg-color--7c5554, #7C5554);
}

.idljld4zp {
  cx: 5.18px;
  cy: 19.346px;
  r: 2.721px;
}

.ifh_31b1f {
  d: path("M13.754 5.566c.029.039-.031.086-.1.137c-.068.05-.119.087-.148.048s.003-.11.072-.162c.068-.051.147-.061.176-.023");
}

.ip3ktqbqy {
  stop-color: var(--svg-color--39bbf9, #39BBF9);
}

.ita7_2enr {
  stop-color: var(--svg-color--774359, #774359);
  stop-opacity: 0;
}

.j1n_ptbit {
  stop-color: var(--svg-color--7b5a93, #7B5A93);
}

.jcizzuyvv {
  stop-color: var(--svg-color--734840, #734840);
}

.jixz69llq {
  stop-color: var(--svg-color--3c93f1, #3C93F1);
}

.jpzj4ccfh {
  stop-color: var(--svg-color--c4b0ca, #C4B0CA);
  stop-opacity: 0;
}

.jqhqeoboo {
  d: path("M25.282 16.554a.1.1 0 0 1 .044-.125l.091-.052a.4.4 0 0 1 .566.195l1.908 4.586a.3.3 0 0 1-.18.4l-.184.063a.15.15 0 0 1-.188-.085z");
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.jy7vazb8a {
  stop-color: var(--svg-color--f0eaf5, #F0EAF5);
}

.jylqepbzd {
  stop-color: var(--svg-color--4079dd, #4079DD);
}

.k0yxbw7lh {
  d: path("M18.292 22.659c-1.2-.713-1.919-1.898-2.143-2.454l2.157-3.015c.377.41 1.05 1.396 1.46 2.022a.9.9 0 0 1 .147.584c-.12 1.06-.567 2.06-.923 2.675a.505.505 0 0 1-.698.188");
}

.ks47q0bjb {
  stop-color: var(--svg-color--9f6ea3, #9F6EA3);
}

.kz100sbcz {
  stop-color: var(--svg-color--855354, #855354);
  stop-opacity: 0;
}

.kzk-_ccou {
  stop-color: var(--svg-color--8b6a6b, #8B6A6B);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljmdpdbwr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.548 4.709c.195-.034.574-.025.837.18");
}

.lkb85rmyp {
  fill: var(--svg-color--000, #000);
  d: path("M13.552 5.885a.23.23 0 0 1 .232-.232a.23.23 0 0 1 .205.338h-.41a.2.2 0 0 1-.027-.106");
}

.lkn2u3bae {
  stop-color: var(--svg-color--3e3034, #3E3034);
  stop-opacity: 0;
}

.lw0wsfo7o {
  stop-color: var(--svg-color--c5b1cb, #C5B1CB);
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.m_6j6qbqv {
  d: path("M12.176 5.837c0-.13-.107-.217-.135-.244l-.13.127l.08.163z");
}

.m13zyzbuk {
  stop-color: var(--svg-color--8b6a6b, #8B6A6B);
}

.m6rj6pbzb {
  fill: var(--svg-color--27151c, #27151C);
  d: path("m14.978 3.073l.194.096a.89.89 0 0 1 .461.966l-.267 1.377c-.024.142-.118.237-.259.24l-.008.001s.024-.41.048-.652c.02-.196-.014-.256-.194-.435a.57.57 0 0 1-.17-.386v-.386a.26.26 0 0 0-.194-.242c-.292-.072-.899-.193-1.773-.193s-1.481.12-1.773.193a.235.235 0 0 0-.194.242v.386a.48.48 0 0 1-.17.386l-.073.073c-.097.072-.145.217-.145.338c.024.266.048.652.048.652h-.022a.29.29 0 0 1-.27-.242l-.266-1.376a.92.92 0 0 1 .485-.942l.195-.096c.121-.073.242-.17.364-.266l.437-.458a.89.89 0 0 1 .996-.145c.242.072.51.072.752 0a1.09 1.09 0 0 1 1.069.241l.364.362c.097.121.219.193.364.266");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdx4akbxm {
  stop-color: var(--svg-color--ff8c60, #FF8C60);
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.mneu5xbew {
  stop-color: var(--svg-color--fa4e2e, #FA4E2E);
  stop-opacity: 0;
}

.mvsqrnbte {
  fill-rule: evenodd;
  d: path("M7.132 13.933a.415.415 0 0 1 .118.575a8 8 0 0 1-.912 1.13a.415.415 0 1 1-.603-.57l.005-.005c.16-.169.494-.522.817-1.012a.415.415 0 0 1 .575-.118");
}

.n30gi-53g {
  stop-color: var(--svg-color--a471bc, #A471BC);
}

.ne4llzbvb {
  stop-color: var(--svg-color--301a2d, #301A2D);
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.nk1vvujwy {
  d: path("M9.794 29.418a.1.1 0 0 1 .043.125l-.04.098a.4.4 0 0 1-.564.197l-4.34-2.418a.3.3 0 0 1-.105-.425l.105-.164a.15.15 0 0 1 .2-.05z");
}

.nlyf4ib8d {
  fill-rule: evenodd;
  d: path("M5.125 14.597c-.293.2-.45.423-.481.5a.415.415 0 1 1-.768-.315c.11-.269.397-.608.78-.87a2.57 2.57 0 0 1 1.588-.457a.415.415 0 0 1-.042.829a1.75 1.75 0 0 0-1.077.313");
}

.nqhicrryp {
  stop-color: var(--svg-color--b391c2, #B391C2);
  stop-opacity: 0;
}

.nzx3or8du {
  d: path("m9.12 25.79l.483.61a.27.27 0 0 0 .398.059c.121-.108.433-.271.71-.059c.279.213.195.579.118.735L9.797 29.64a.4.4 0 0 1-.564.198l-4.34-2.419a.3.3 0 0 1-.105-.424l.326-.506a.53.53 0 0 1 .643-.193c1.414.556 2.194.186 2.545-.071a1.4 1.4 0 0 0 .345-.387c.105-.165.353-.202.473-.049");
}

.o-iz-vbwp {
  stop-color: var(--svg-color--b7a8c2, #B7A8C2);
}

.o27_2ebdq {
  stop-color: var(--svg-color--d85b75, #D85B75);
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.o5zmdfb2x {
  d: path("M12.962 17.455c.094-.275.216-.52.266-.61h5.148c.539 1.52-.652 2.927-1.2 3.24c-.978.6-2.891 1.779-3.085 1.898c-.242.148-.512.238-.73.066c-.759-.531-1.555-1.508-1.844-2.008c-.232-.4.023-.74.18-.86c.827-.698 1.148-1.382 1.265-1.726");
}

.o67susxgp {
  stop-color: var(--svg-color--51b1ff, #51B1FF);
  stop-opacity: 0;
}

.o7o4d8pps {
  stop-color: var(--svg-color--92869f, #92869F);
  stop-opacity: 0;
}

.o90gcpqxu {
  stop-color: var(--svg-color--3d3437, #3D3437);
  stop-opacity: 0;
}

.o9doel8cg {
  stop-color: var(--svg-color--93736e, #93736E);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oha5hfbwc {
  stop-color: var(--svg-color--f0eaf5, #F0EAF5);
  stop-opacity: 0;
}

.ohg8m5b7a {
  d: path("M5.527 16.647c.013.613.238 1.167.599 1.588l.896-.892q.092.085.177.178l-.901.895a2.23 2.23 0 0 0 1.587.621q.013.123.016.25h-.065a2.48 2.48 0 0 1-1.716-.695l-.777.773l1.754 1.913q-.088.089-.185.168l-1.746-1.905l-.77.765a2.76 2.76 0 0 1 .715 1.761a3 3 0 0 1-.251-.018a2.5 2.5 0 0 0-.64-1.567l-.877.872a3 3 0 0 1-.177-.178l.876-.87a2.23 2.23 0 0 0-1.556-.575a3 3 0 0 1-.024-.25l.091-.001c.638 0 1.22.245 1.667.65l.777-.773l-1.757-1.918q.088-.09.183-.17l1.751 1.911l.774-.769a2.77 2.77 0 0 1-.67-1.784q.126.005.25.02");
}

.pa6b3tb0c {
  stop-color: var(--svg-color--cfbedb, #CFBEDB);
}

.paa99_b5q {
  fill: var(--svg-color--000, #000);
  d: path("M12.037 5.885a.23.23 0 0 0-.23-.232a.23.23 0 0 0-.207.338h.41a.23.23 0 0 0 .027-.106");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmliwkbra {
  d: path("m11.001 20.604l.672-.75l2.336 1.86c-.07.046-.328.207-.797.476c-.644.412-1.029 1.088-1.14 1.375l-1.493 3.703l-1.976-.969c.325-.86 1.059-2.837 1.39-3.875s.81-1.646 1.008-1.82");
}

.poy_ydb2w {
  stop-color: var(--svg-color--e4d5e5, #E4D5E5);
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.q3kvcibxc {
  stop-color: var(--svg-color--855354, #855354);
}

.q8x82vmoe {
  stop-color: var(--svg-color--483e3e, #483E3E);
  stop-opacity: 0;
}

.qefb_nbvu {
  d: path("M11.806 5.48a.404.404 0 0 0-.389.511h.78a.407.407 0 0 0-.391-.51");
}

.qle5g2bis {
  stop-color: var(--svg-color--683733, #683733);
  stop-opacity: 0;
}

.qu4z4jkud {
  stop-color: var(--svg-color--9380a4, #9380A4);
  stop-opacity: 0;
}

.qudtebbqf {
  stop-color: var(--svg-color--683733, #683733);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_owdkb9z {
  width: 0.659px;
  height: 1.111px;
  x: 19.371px;
  y: 13.469px;
  rx: 0.33px;
}

.r2j4cwbuw {
  d: path("M14.143 5.831a.4.4 0 0 0-.104-.209l-.118.13l.053.102z");
}

.r6n7exbot {
  stop-color: var(--svg-color--7d4348, #7D4348);
  stop-opacity: 0;
}

.r6smjf07k {
  d: path("M13.783 5.48a.404.404 0 0 1 .39.511h-.78a.406.406 0 0 1 .391-.51");
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.rko8b-bmk {
  stop-color: var(--svg-color--714250, #714250);
  stop-opacity: 0;
}

.rrpkz-bur {
  stop-color: var(--svg-color--805e51, #805E51);
  stop-opacity: 0;
}

.rtyid72og {
  stop-color: var(--svg-color--d5c2e7, #D5C2E7);
}

.rx_o_e39d {
  stop-color: var(--svg-color--4d3a45, #4D3A45);
}

.s5xtkwbhw {
  stop-color: var(--svg-color--6f414d, #6F414D);
  stop-opacity: 0;
}

.s6non86-m {
  stop-color: var(--svg-color--7d4348, #7D4348);
}

.sd_n72xhe {
  fill-rule: evenodd;
  d: path("m11.974 8.996l.053-.092l1.728 1.008l-.074.127c-.712 1.224-1.57 2.698-3.676 3.891c-.769.435-1.654.656-2.382.773c-.256.041-.502.07-.728.091c-.55.05-.994-.403-.988-.955l.01-1.024c.251.002.784.01 1.39-.087c.617-.098 1.238-.27 1.712-.538c1.633-.925 2.26-2.001 2.955-3.194");
}

.sdljx8amv {
  stop-color: var(--svg-color--c7b9c5, #C7B9C5);
}

.sj2xsx-sw {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m12.672 5.95l-.372.77c-.046.158.064.316.221.316h.334c.156 0 .267-.16.22-.317l-.225-.769c-.048-.17-.128-.17-.178 0");
}

.sj84nybgo {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.877 5.358c.296 0 .545.204.613.48a.124.124 0 0 1-.121.153h-1.01a.104.104 0 0 1-.103-.123a.63.63 0 0 1 .621-.51");
}

.slawajb_c {
  cx: 11.684px;
  cy: 5.653px;
  rx: 0.176px;
  ry: 0.089px;
}

.sn3dy7bnn {
  stop-color: var(--svg-color--9380a4, #9380A4);
}

.so34edl-m {
  stop-color: var(--svg-color--3d94fa, #3D94FA);
}

.swkdpwiwa {
  d: path("M9.716 3.302a.1.1 0 0 1 .1-.1h5.925a.1.1 0 0 1 .1.1v.862a.1.1 0 0 1-.1.1H9.816a.1.1 0 0 1-.1-.1z");
}

.t-_futbdw {
  d: path("m11.088 4.774l.002-.001l.002-.002l.005-.004l.07-.049a1.28 1.28 0 0 1 .866-.167a.242.242 0 1 1-.075.478a.8.8 0 0 0-.534.099l-.029.02a.242.242 0 0 1-.307-.374");
}

.t5f4fqbxv {
  stop-color: var(--svg-color--84798d, #84798D);
  stop-opacity: 0;
}

.t5qac2c1p {
  stop-color: var(--svg-color--ff8c60, #FF8C60);
  stop-opacity: 0;
}

.tfg6otbsp {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.192 7.23c.174.09.382.142.604.142a1.3 1.3 0 0 0 .604-.143a.12.12 0 0 1 .142.024a.11.11 0 0 1 .013.143m-1.363-.167l1.32.14m-1.32-.14a.12.12 0 0 0-.142.025a.11.11 0 0 0-.012.142m.154-.167l-.113.14m1.476.027l-.042-.028m.042.028l-.042-.028m.042.028a.9.9 0 0 1-.759.405a.9.9 0 0 1-.758-.405m1.475-.028a.86.86 0 0 1-.717.383a.86.86 0 0 1-.716-.383m-.042.028l.041-.028m-.04.028h-.001l.041-.028");
}

.tkijdf1cs {
  stop-color: var(--svg-color--32272d, #32272D);
}

.tt7xwipig {
  stop-color: var(--svg-color--a471bc, #A471BC);
  stop-opacity: 0;
}

.tti32obdt {
  stop-color: var(--svg-color--46383d, #46383D);
}

.tw_n9zr7u {
  cx: 14.953px;
  cy: 6.005px;
  r: 0.45px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
}

.u_3e452pz {
  stop-color: var(--svg-color--918b96, #918B96);
}

.u072kwb9c {
  d: path("m22.282 20.864l.03-.017l1.728-.92l-.727-2.144l-2.087 1.175z");
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.uqxno_b8g {
  stop-color: var(--svg-color--3da9fd, #3DA9FD);
}

.uul9_ttvm {
  stop-color: var(--svg-color--98919c, #98919C);
}

.v290okb-z {
  fill: var(--svg-color--352827, #352827);
  d: path("m11.088 4.774l.002-.001l.002-.002l.005-.004l.07-.049a1.28 1.28 0 0 1 .866-.167a.242.242 0 1 1-.075.478a.8.8 0 0 0-.534.099l-.029.02a.242.242 0 0 1-.307-.374");
}

.v2dwqfdba {
  stop-color: var(--svg-color--4079dd, #4079DD);
  stop-opacity: 0;
}

.v4bc9u3un {
  stop-color: var(--svg-color--3d3437, #3D3437);
}

.v616eizae {
  stop-color: var(--svg-color--f84c2c, #F84C2C);
}

.v7jcm4h7p {
  fill: var(--svg-color--815d52, #815D52);
  fill-rule: evenodd;
  d: path("M5.125 14.597c-.293.2-.45.423-.481.5a.415.415 0 1 1-.768-.315c.11-.269.397-.608.78-.87a2.57 2.57 0 0 1 1.588-.457a.415.415 0 0 1-.042.829a1.75 1.75 0 0 0-1.077.313");
}

.v9-6-sbuc {
  stop-color: var(--svg-color--483e3e, #483E3E);
}

.vam_w95qk {
  fill: var(--svg-color--92869e, #92869E);
  d: path("M18.292 22.659c-1.2-.713-1.919-1.898-2.143-2.454l2.157-3.015c.377.41 1.05 1.396 1.46 2.022a.9.9 0 0 1 .147.584c-.12 1.06-.567 2.06-.923 2.675a.505.505 0 0 1-.698.188");
}

.vfn8g2baf {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M13.754 5.566c.029.039-.031.086-.1.137c-.068.05-.119.087-.148.048s.003-.11.072-.162c.068-.051.147-.061.176-.023");
}

.vgfjqtbdb {
  stop-color: var(--svg-color--301a2d, #301A2D);
  stop-opacity: 0;
}

.vhhvj2t-s {
  stop-color: var(--svg-color--3e98f5, #3E98F5);
}

.vinvwq12a {
  stop-color: var(--svg-color--825853, #825853);
}

.viuz5dbki {
  fill-rule: evenodd;
  d: path("M6.293 14.778c-.79-.084-1.136.337-1.209.514a.415.415 0 1 1-.768-.315c.211-.515.904-1.147 2.065-1.024a.415.415 0 1 1-.088.825");
}

.vpyj0s_ar {
  stop-color: var(--svg-color--3e3034, #3E3034);
}

.vvs_3yeki {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
}

.w_s2noode {
  d: path("M10.46 5.077c0-.12.05-.266.147-.338l.073-.073a.48.48 0 0 0 .17-.386v-.386c0-.12.072-.218.194-.242a7.4 7.4 0 0 1 1.772-.193c.875 0 1.482.12 1.773.193a.26.26 0 0 1 .194.242v.386c0 .145.073.29.17.386c.228.16.214.247.195.435a21 21 0 0 0-.049.652h.008l-.12 1.792c-.073.801-.703 1.36-1.453 1.36H12.08c-.775 0-1.38-.559-1.453-1.36c-.063-.822-.091-1.647-.166-2.468");
}

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.w7i-07blq {
  stop-color: var(--svg-color--f25c44, #F25C44);
  stop-opacity: 0;
}

.waplrebxe {
  stop-color: var(--svg-color--bfa7d0, #BFA7D0);
  stop-opacity: 0;
}

.wbxccxbgh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.744 3.827v.407c-.004.067-.032.217-.117.281");
}

.wg6epmg7n {
  stop-color: var(--svg-color--53adfa, #53ADFA);
}

.wg8zzjbli {
  stop-color: var(--svg-color--32272d, #32272D);
  stop-opacity: 0;
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.wh6405bfr {
  fill: var(--svg-color--9c776f, #9C776F);
  d: path("M20.857 14.169c.475-1.675-.198-3.354-.594-3.985l.781-.383c.907 1.672.954 2.774.735 3.618z");
}

.wh6te8bft {
  stop-color: var(--svg-color--bb98d6, #BB98D6);
}

.whspc9bgn {
  stop-color: var(--svg-color--39bbf9, #39BBF9);
  stop-opacity: 0;
}

.whxihzpaf {
  stop-color: var(--svg-color--5f3e52, #5F3E52);
}

.wxnqr0bgi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M11.185 4.943c.148-.13.472-.268.872-.204");
}

.x41u_8htb {
  fill: var(--svg-color--815d52, #815D52);
  fill-rule: evenodd;
  d: path("M6.293 14.778c-.79-.084-1.136.337-1.209.514a.415.415 0 1 1-.768-.315c.211-.515.904-1.147 2.065-1.024a.415.415 0 1 1-.088.825");
}

.xau3og86r {
  stop-color: var(--svg-color--774359, #774359);
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.xu1e5_bcz {
  stop-color: var(--svg-color--3c92ef, #3C92EF);
}

.xw75uqvlc {
  fill: var(--svg-color--815d52, #815D52);
  fill-rule: evenodd;
  d: path("M6.322 13.685c-.775-.132-1.17.089-1.3.289a.415.415 0 1 1-.697-.451c.392-.605 1.215-.814 2.136-.657a.415.415 0 1 1-.14.819");
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y2teulbve {
  stop-color: var(--svg-color--805e51, #805E51);
}

.y5gqwcbjl {
  fill: var(--svg-color--e8e5eb, #E8E5EB);
  d: path("M19.324 8.304a.095.095 0 0 0-.107.03c-.44.55-.75 1.567-.821 2.056q.254.094.432.226c.418.266.704.576.875.93c.812-.549 1.637-.802 2.097-.855c-.342-.803-.922-1.49-1.735-2.009a4 4 0 0 0-.741-.378");
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.ykf__gbvs {
  stop-color: var(--svg-color--a38f93, #A38F93);
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.yodkvfdyw {
  stop-color: var(--svg-color--bb98d6, #BB98D6);
  stop-opacity: 0;
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.z_g0j449a {
  stop-color: var(--svg-color--6f414d, #6F414D);
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.za46tubip {
  stop-color: var(--svg-color--8e695d, #8E695D);
}

.zbj0d-fph {
  stop-color: var(--svg-color--ff7937, #FF7937);
}

.zk3m83b4g {
  stop-color: var(--svg-color--453938, #453938);
}

</style>
