<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iwU8jVd)"><path fill="url(#is9pnJc)" clip-rule="evenodd" class="u1r10c4ff"/><path fill="url(#i2ViBve)" clip-rule="evenodd" class="u1r10c4ff"/><path fill="url(#iZ5oDBc)" clip-rule="evenodd" class="u1r10c4ff"/><path fill="url(#iKQTyIb)" clip-rule="evenodd" class="u1r10c4ff"/><path fill="url(#ik9MK3b)" clip-rule="evenodd" class="u1r10c4ff"/><path fill="url(#imlVtxb)" clip-rule="evenodd" class="u1r10c4ff"/><path fill="url(#iU03kPb)" clip-rule="evenodd" class="u1r10c4ff"/><path fill="url(#iBEb1UQ)" clip-rule="evenodd" class="u1r10c4ff"/><path fill="url(#iq0Hjoc)" clip-rule="evenodd" class="u1r10c4ff"/><path fill="url(#iKUW69d)" clip-rule="evenodd" class="u1r10c4ff"/><path fill="url(#i77CKhe)" clip-rule="evenodd" class="u1r10c4ff"/></g><path class="f1a_l73ur"/><path class="s0xat5bmb"/><g filter="url(#iwxGrqb)"><path class="cdbsw_bof"/><path fill="url(#i3bfVae)" class="o_hp5nbjg"/></g><path class="iq3r27bkh"/><path fill="url(#iM74tFd)" class="o93ji_bej"/><path fill="url(#iBbR7Bb)" class="o93ji_bej"/><g filter="url(#ioZtSRb)"><path class="cj4aekbtg"/></g><path class="pu1qalb0n"/><path fill="url(#ieyaRhd)" class="pcr8w9bct"/><path fill="url(#i9fb3ne)" class="pcr8w9bct"/><path fill="url(#iek6ihd)" class="pcr8w9bct"/><path fill="url(#izgSJzU)" class="pcr8w9bct"/><path class="myif5tbjr"/><path fill="url(#iNC83fb)" class="u1ssmd66p"/><path fill="url(#iBwD5cu)" class="u1ssmd66p"/><g filter="url(#iQczebd)"><path class="xqme1t_en"/></g><path fill="url(#icWbAmd)" class="cge-036tr"/><path fill="url(#iJO9Dac)" class="cge-036tr"/><path fill="url(#iApyzzd)" class="cge-036tr"/><path fill="url(#ivzWvsb)" class="cge-036tr"/><g filter="url(#iaRpYxc)"><path fill="url(#iCEVb2b)" class="qr3eebgfz"/><path fill="url(#iS5fSJc)" class="qr3eebgfz"/></g><path fill="url(#iO1McLA)" class="qr3eebgfz"/><path fill="url(#iIFRdJe)" class="qr3eebgfz"/><path fill="url(#iTcBSHb)" class="i0vp1so6w"/><path fill="url(#isd2Gab)" class="i0vp1so6w"/><g filter="url(#iq10OOe)"><path class="ise8hkbqb"/></g><path fill="url(#iiFwxIb)" class="ukvj5-vlj"/><path fill="url(#iNo9Upb)" class="ukvj5-vlj"/><g filter="url(#ij5Jtnd)"><path class="hm4ptbkef"/></g><path fill="url(#imXX7Fy)" class="r7p4z7bsm"/><path fill="url(#iFVyysb)" class="d8xf2ibmq"/><g filter="url(#im7LSnr)"><path fill="url(#iGYfdQe)" class="vei8hrc-a"/></g><g filter="url(#iZHR7xb)"><path fill="url(#imNtlec)" class="rek67ibyf"/><path fill="url(#iywL97d)" class="rek67ibyf"/></g><g filter="url(#ipByEub)"><path class="rl7ruxb0r"/><path fill="url(#ixpCONe)" class="r0rwz7r9i"/></g><g filter="url(#ifrG3NF)"><path class="nq2mftbyb"/><path fill="url(#iugspHd)" class="gvyr6bjbh"/></g><g filter="url(#ivI2Zge)"><path fill="url(#iSpTV9c)" class="lik74_beu"/><path fill="url(#ifezkre)" class="lik74_beu"/><path fill="url(#iRpwCmd)" class="lik74_beu"/><path fill="url(#iJJhbjc)" class="lik74_beu"/><path fill="url(#iYD0n2c)" class="lik74_beu"/><path fill="url(#iKC5pvd)" class="lik74_beu"/><path fill="url(#ilLbUud)" class="lik74_beu"/><path fill="url(#ishNNhn)" class="lik74_beu"/></g><path fill="url(#ixFTHje)" class="lik74_beu"/><path fill="url(#i3eLDke)" class="lik74_beu"/><g filter="url(#iNcIsxe)"><path class="xx6d_cb-a"/></g><g filter="url(#i5Luy8c)"><path class="a2i3gpbwf"/><path fill="url(#ibWjS0d)" class="am2w0mqaz"/><path fill="url(#ifTnCZd)" class="am2w0mqaz"/><path fill="url(#iXytPrc)" class="am2w0mqaz"/><path fill="url(#inD89rK)" class="am2w0mqaz"/></g><g filter="url(#iPdIqhd)"><path stroke="url(#ihRy1ae)" class="ubznubc5z"/></g><path class="wirx8nysp"/><g filter="url(#iuFr5ib)"><path class="dysqi-bns"/></g><g filter="url(#iG677lz)"><path class="vli7qpbzc"/></g><g filter="url(#i6ai8Zd)"><path class="a1y31es2q"/></g><g filter="url(#iwyFF8b)"><path clip-rule="evenodd" class="jqpze9b9a"/></g><path class="omj28bchm"/><path fill="url(#iRcKwzd)" class="amtk1ybhw"/><path class="y1s-sz65s"/><g filter="url(#iEeksuc)"><path class="fwox8vyfu"/><path fill="url(#iVa0nKd)" class="mu4khql-m"/></g><g filter="url(#idtCcSd)"><path fill="url(#ipntqvP)" class="jnji2526l"/></g><path class="zoxixubdj"/><path fill="url(#iSyhnVb)" class="ucup2sb_b"/><path class="x106i8gqz"/><g filter="url(#iSM4GKb)"><path fill="url(#it3TIye)" class="k0t-ilbnn"/></g><g filter="url(#iyd7YuI)"><ellipse transform="rotate(-27.914 14.93 5.505)" class="mfgvkccmt"/><ellipse fill="url(#iOqonYb)" transform="rotate(-27.914 14.93 5.505)" class="vks9dsnnd"/></g><g filter="url(#iMDW0jF)"><path class="c17dztsbw"/><path fill="url(#iuzdnYd)" class="c7lg3nbrm"/></g><g filter="url(#ildyaYd)"><path class="j5ojyhbmo"/><path fill="url(#ieHGsvu)" class="vynwlxbbm"/><path fill="url(#iR82D1b)" class="vynwlxbbm"/></g><g filter="url(#iF2zHAe)"><path stroke="url(#iDD89Cd)" class="ytarfqbur"/></g><g filter="url(#inlzAmd)"><path class="v7kodccae"/></g><defs><radialGradient id="i2ViBve" cx="0" cy="0" r="1" gradientTransform="matrix(-.26324 1.98893 -2.48457 -.32884 15.868 6.898)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iZ5oDBc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.25773 .84822 -1.1145 -1.65257 14.64 7.015)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iKQTyIb" cx="0" cy="0" r="1" gradientTransform="matrix(-.57035 .74585 -.57271 -.43795 13.887 5.903)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="ik9MK3b" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 5.635 6.459)scale(1.07976 .7606)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="imlVtxb" cx="0" cy="0" r="1" gradientTransform="matrix(.5996 1.14071 -1.58348 .83234 14.464 2.291)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iU03kPb" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 8.61 5.44)scale(.88931 1.24278)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iBEb1UQ" cx="0" cy="0" r="1" gradientTransform="rotate(163.778 9.25 4.091)scale(.83766 1.74686)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iq0Hjoc" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 9.08 4.634)scale(1.26623 1.61299)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iKUW69d" cx="0" cy="0" r="1" gradientTransform="matrix(-.39457 -1.1562 .91448 -.31208 18.065 4.374)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="i77CKhe" cx="0" cy="0" r="1" gradientTransform="matrix(.6561 .06882 -.11151 1.06307 13.32 5.42)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="i3bfVae" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84375 0 0 -12.369 13.357 16.482)" gradientUnits="userSpaceOnUse"><stop offset=".138" class="v_ft29bcw"/><stop offset="1" class="zhgg7cc0u"/></radialGradient><radialGradient id="iM74tFd" cx="0" cy="0" r="1" gradientTransform="matrix(1.60938 0 0 15.4135 18.872 16.482)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="xsr8v7bqw"/><stop offset="1" class="shh_g2b0q"/></radialGradient><radialGradient id="iBbR7Bb" cx="0" cy="0" r="1" gradientTransform="matrix(.1836 -.5625 .3991 .13026 19.319 18.877)" gradientUnits="userSpaceOnUse"><stop class="gd7pfsb0f"/><stop offset="1" class="liuzkqkjj"/></radialGradient><radialGradient id="ieyaRhd" cx="0" cy="0" r="1" gradientTransform="rotate(107.067 2.409 10.603)scale(1.86331 .9169)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="mwlubcb3u"/><stop offset="1" class="sf6dqgv3q"/></radialGradient><radialGradient id="i9fb3ne" cx="0" cy="0" r="1" gradientTransform="matrix(-3.84619 0 0 -3.93164 15.377 12.374)" gradientUnits="userSpaceOnUse"><stop offset=".865" class="k359d0bjg"/><stop offset="1" class="zqan0v-dy"/></radialGradient><radialGradient id="iek6ihd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51587 1.2383 -.95063 -1.16372 14.562 8.683)" gradientUnits="userSpaceOnUse"><stop class="b9nndyb1o"/><stop offset="1" class="aslchbbcc"/></radialGradient><radialGradient id="iNC83fb" cx="0" cy="0" r="1" gradientTransform="matrix(1.08228 -.29102 1.20718 4.48944 18.794 11.828)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="a76ibt5dn"/><stop offset="1" class="s61flvbkc"/></radialGradient><radialGradient id="iJO9Dac" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.35938 1.91919 0 16 17.953)" gradientUnits="userSpaceOnUse"><stop class="kcjik5o6k"/><stop offset="1" class="j6ndfp4vo"/></radialGradient><radialGradient id="iApyzzd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.26953 1.85938 0 18.075 28.316)" gradientUnits="userSpaceOnUse"><stop class="x7tdxqavt"/><stop offset="1" class="cssy6ccya"/></radialGradient><radialGradient id="ivzWvsb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.32813 1.20581 0 14.794 28.406)" gradientUnits="userSpaceOnUse"><stop class="x7tdxqavt"/><stop offset="1" class="cssy6ccya"/></radialGradient><radialGradient id="iS5fSJc" cx="0" cy="0" r="1" gradientTransform="rotate(140.013 7.454 8.152)scale(2.52874 3.92481)" gradientUnits="userSpaceOnUse"><stop class="elt890uby"/><stop offset="1" class="r2rrbr4ji"/></radialGradient><radialGradient id="iIFRdJe" cx="0" cy="0" r="1" gradientTransform="matrix(-.92188 -7.88477 10.52054 -1.23005 16.423 15.796)" gradientUnits="userSpaceOnUse"><stop offset=".85" class="kqc1q6b3u"/><stop offset=".967" class="dpe-7hbaw"/></radialGradient><radialGradient id="iTcBSHb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.11133 -1.40894 0 16 8.337)" gradientUnits="userSpaceOnUse"><stop offset=".638" class="pr00behdc"/><stop offset="1" class="qqztrtlbt"/></radialGradient><radialGradient id="isd2Gab" cx="0" cy="0" r="1" gradientTransform="matrix(0 .89844 -.2837 0 15.129 8.138)" gradientUnits="userSpaceOnUse"><stop class="kg6c4paol"/><stop offset="1" class="y3uyr4btc"/></radialGradient><radialGradient id="iNo9Upb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66284 -.84375 .32903 -.64844 19.566 29.264)" gradientUnits="userSpaceOnUse"><stop class="z3z2fqbpi"/><stop offset="1" class="qnuhplbln"/></radialGradient><radialGradient id="imNtlec" cx="0" cy="0" r="1" gradientTransform="matrix(1.08587 -.49358 .60263 1.3258 17.762 5.998)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="iywL97d" cx="0" cy="0" r="1" gradientTransform="matrix(.57401 .32174 -.09096 .16229 18.212 5.074)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="ixpCONe" cx="0" cy="0" r="1" gradientTransform="matrix(.6587 -.049 .0383 .51492 17.916 5.856)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="iugspHd" cx="0" cy="0" r="1" gradientTransform="rotate(180 6.996 2.903)scale(.46067)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="iSpTV9c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.83723 1.30834 -1.7512 -3.79758 17.247 5.572)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="ifezkre" cx="0" cy="0" r="1" gradientTransform="matrix(-.95117 .41854 -.29147 -.66237 16.86 5.945)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="iRpwCmd" cx="0" cy="0" r="1" gradientTransform="rotate(-71.832 13.335 -6.188)scale(1.8037 2.28855)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="iJJhbjc" cx="0" cy="0" r="1" gradientTransform="matrix(-.56045 3.2166 -4.02072 -.70056 16.446 5.39)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="mg10me7tz"/><stop offset="1" class="kitn3twkh"/></radialGradient><radialGradient id="iYD0n2c" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.087 3.98)scale(3.07011 5.28578)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="iKC5pvd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.50203 .61613 0 17.004 5.39)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="ilLbUud" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.5726 .65623 0 15.094 5.29)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="ishNNhn" cx="0" cy="0" r="1" gradientTransform="rotate(105.092 6.624 8.55)scale(1.45798 1.16662)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="ixFTHje" cx="0" cy="0" r="1" gradientTransform="matrix(-.56071 0 0 -2.81192 18.223 6.039)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="i3eLDke" cx="0" cy="0" r="1" gradientTransform="matrix(.76345 -.68165 .80937 .9065 14.24 8.072)" gradientUnits="userSpaceOnUse"><stop class="z26rrllgi"/><stop offset="1" class="fs9pa7bci"/></radialGradient><radialGradient id="ibWjS0d" cx="0" cy="0" r="1" gradientTransform="matrix(-.19873 -.89171 .27482 -.06125 16.342 6.356)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="inD89rK" cx="0" cy="0" r="1" gradientTransform="matrix(-.34002 0 0 -.09506 16.238 6.448)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iRcKwzd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35394 -.56298 0 16.952 5.546)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iVa0nKd" cx="0" cy="0" r="1" gradientTransform="matrix(-.10118 -.13038 .1795 -.1393 16.852 5.583)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iSyhnVb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35394 -.56299 0 15.048 5.546)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iOqonYb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00337 -.21554 .25908 -.00406 14.923 5.642)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iuzdnYd" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 10.366 -8.23)scale(1.32216 .67638)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="ieHGsvu" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 7.678 6.467)scale(2.12584 3.47562)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iR82D1b" cx="0" cy="0" r="1" gradientTransform="matrix(-.09176 .59645 -1.28322 -.19742 16.092 2.51)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="iwU8jVd" width="6.802" height="7.302" x="12.724" y="1.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_174"/></filter><filter id="iwxGrqb" width="2.311" height="8.028" x="11.403" y="12.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.407843 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_174"/></filter><filter id="ioZtSRb" width="1.437" height="7.032" x="19.118" y="11.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_174" stdDeviation=".25"/></filter><filter id="iQczebd" width="6.169" height="12.453" x="13.016" y="15.863" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.462745 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_174"/></filter><filter id="iaRpYxc" width="6.517" height="7.694" x="12.941" y="8.32" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".1"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_174"/></filter><filter id="iq10OOe" width="3.316" height="1.848" x="12.434" y="28.316" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.235294 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_174"/></filter><filter id="ij5Jtnd" width="6.594" height="13.766" x="12.841" y="15.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_174" stdDeviation=".5"/></filter><filter id="im7LSnr" width="1.554" height="1.404" x="13.254" y="5.105" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_174"/></filter><filter id="iZHR7xb" width="1.404" height="1.654" x="17.404" y="4.855" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_174"/></filter><filter id="ipByEub" width="1.237" height="1.237" x="17.487" y="5.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_174" stdDeviation=".075"/></filter><filter id="ifrG3NF" width="1.237" height="1.237" x="13.346" y="5.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_174" stdDeviation=".075"/></filter><filter id="ivI2Zge" width="4.446" height="4.845" x="13.777" y="3.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_174"/></filter><filter id="iNcIsxe" width="1.819" height="2.17" x="15.02" y="5.086" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_174" stdDeviation=".25"/></filter><filter id="i5Luy8c" width="1.019" height="1.37" x="15.491" y="5.426" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_174" stdDeviation=".05"/></filter><filter id="iPdIqhd" width="1.691" height=".741" x="15.155" y="6.793" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_174" stdDeviation=".05"/></filter><filter id="iuFr5ib" width="1.422" height=".561" x="16.298" y="5.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_174"/></filter><filter id="iG677lz" width="1.422" height=".561" x="14.28" y="5.194" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_174"/></filter><filter id="i6ai8Zd" width="1.183" height=".589" x="14.339" y="4.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_174"/></filter><filter id="iwyFF8b" width="1.183" height=".589" x="16.702" y="4.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_174"/></filter><filter id="iEeksuc" width=".456" height=".417" x="16.575" y="5.298" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_174" stdDeviation=".05"/></filter><filter id="idtCcSd" width=".614" height=".624" x="16.885" y="5.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_174" stdDeviation=".1"/></filter><filter id="iSM4GKb" width=".656" height=".679" x="14.947" y="5.247" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_174" stdDeviation=".1"/></filter><filter id="iyd7YuI" width=".511" height=".42" x="14.674" y="5.295" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_174" stdDeviation=".05"/></filter><filter id="iMDW0jF" width="2.138" height="2.27" x="13.252" y="2.803" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.262745 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_174"/><feGaussianBlur result="effect2_foregroundBlur_4002_174" stdDeviation=".075"/></filter><filter id="ildyaYd" width="3.985" height="2.604" x="14.448" y="2.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_174"/><feGaussianBlur result="effect2_foregroundBlur_4002_174" stdDeviation=".05"/></filter><filter id="iF2zHAe" width=".838" height="1.346" x="14.439" y="2.653" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_174" stdDeviation=".1"/></filter><filter id="inlzAmd" width="2.65" height="1.317" x="15.823" y="3.252" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_174" stdDeviation=".125"/></filter><linearGradient id="is9pnJc" x1="18.047" x2="15.079" y1="2.774" y2="8.273" gradientUnits="userSpaceOnUse"><stop class="c1nwhtznm"/><stop offset="1" class="ogqxd-bue"/></linearGradient><linearGradient id="izgSJzU" x1="12.466" x2="12.466" y1="12.632" y2="12.474" gradientUnits="userSpaceOnUse"><stop class="d8l0ribxz"/><stop offset="1" class="sgj6b5b-t"/></linearGradient><linearGradient id="iBwD5cu" x1="19.747" x2="19.747" y1="12.632" y2="12.394" gradientUnits="userSpaceOnUse"><stop class="w2wdskbew"/><stop offset="1" class="lj8hkjeee"/></linearGradient><linearGradient id="icWbAmd" x1="16" x2="16" y1="15.863" y2="16.296" gradientUnits="userSpaceOnUse"><stop class="sb3cb-bog"/><stop offset="1" class="hpe4_756h"/></linearGradient><linearGradient id="iCEVb2b" x1="16" x2="16" y1="8.953" y2="15.914" gradientUnits="userSpaceOnUse"><stop class="qb52yacny"/><stop offset="1" class="k3iqnbc3x"/></linearGradient><linearGradient id="iO1McLA" x1="17.173" x2="17.173" y1="15.914" y2="15.654" gradientUnits="userSpaceOnUse"><stop offset=".068" class="d10os3b5g"/><stop offset="1" class="tfix0o_9x"/></linearGradient><linearGradient id="iiFwxIb" x1="18.247" x2="16.5" y1="29.578" y2="29.375" gradientUnits="userSpaceOnUse"><stop class="c2i7i45cq"/><stop offset="1" class="wwbz7ibcz"/></linearGradient><linearGradient id="imXX7Fy" x1="12.866" x2="19.137" y1="7.821" y2="7.821" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iFVyysb" x1="12.866" x2="19.137" y1="7.807" y2="7.807" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iGYfdQe" x1="13.276" x2="13.817" y1="5.845" y2="5.845" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="ifTnCZd" x1="15.591" x2="16" y1="6.388" y2="6.388" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="iXytPrc" x1="16" x2="16" y1="6.736" y2="6.47" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="ihRy1ae" x1="15.536" x2="15.737" y1="7.351" y2="7.04" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="ipntqvP" x1="17.291" x2="17.155" y1="5.57" y2="5.654" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="it3TIye" x1="15.372" x2="15.236" y1="5.57" y2="5.654" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iDD89Cd" x1="14.739" x2="14.976" y1="3.103" y2="3.659" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-standing-medium-dark" /></template>
<style>
.a1y31es2q {
  fill: var(--svg-color--352827, #352827);
  d: path("m14.518 5.031l-.002.001a.117.117 0 0 1-.12-.2l.002-.002l.004-.002l.014-.008l.05-.025a2 2 0 0 1 .18-.071c.148-.047.355-.087.579-.048a.117.117 0 0 1-.04.23a1 1 0 0 0-.468.04a1 1 0 0 0-.19.08z");
}

.a2i3gpbwf {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m15.833 5.65l-.232.741a.235.235 0 0 0 .227.305h.344c.16 0 .274-.155.227-.305l-.232-.742c-.05-.164-.282-.164-.334 0");
}

.a76ibt5dn {
  stop-color: var(--svg-color--624da1, #624DA1);
}

.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.am2w0mqaz {
  d: path("m15.833 5.65l-.232.741a.235.235 0 0 0 .227.305h.344c.16 0 .274-.155.227-.305l-.232-.742c-.05-.164-.282-.164-.334 0");
}

.amtk1ybhw {
  d: path("M16.953 5.338a.39.39 0 0 1 .375.492h-.752a.39.39 0 0 1 .377-.492");
}

.aslchbbcc {
  stop-color: var(--svg-color--5e4f7e, #5E4F7E);
  stop-opacity: 0;
}

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.b9nndyb1o {
  stop-color: var(--svg-color--5e4f7e, #5E4F7E);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.c17dztsbw {
  fill: var(--svg-color--2a191e, #2A191E);
  d: path("M13.789 3.194c.246-.261.713-.261.93-.222l.172.563a.33.33 0 0 0-.291.102c-.196.55-.868.853-1.18.936c-.065-.65.047-1.038.369-1.379");
}

.c1nwhtznm {
  stop-color: var(--svg-color--45363a, #45363A);
}

.c2i7i45cq {
  stop-color: var(--svg-color--5a3f7c, #5A3F7C);
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c7lg3nbrm {
  d: path("M13.789 3.194c.246-.261.713-.261.93-.222l.172.563a.33.33 0 0 0-.291.102c-.196.55-.868.853-1.18.936c-.065-.65.047-1.038.369-1.379");
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cdbsw_bof {
  fill: var(--svg-color--774f4e, #774F4E);
  d: path("M12.112 20.292c-.938-1.982-.769-6.259-.488-7.824h1.672c-.071 2.426.04 5.243.178 6.512c.011.103.084.214 0 .276a.29.29 0 0 1-.438-.115l-.117-.263a.184.184 0 0 0-.226-.1a.176.176 0 0 0-.12.202c.061.299.172.678.265.973a.42.42 0 0 1-.239.513c-.186.076-.401.008-.487-.174");
}

.cge-036tr {
  d: path("m13.016 15.863l.484 12.453h2l.238-9.523c0-.329.029-.86.262-.86c.212 0 .263.555.262.86l.238 9.523h2l.484-12.453z");
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4aekbtg {
  stroke: var(--svg-color--976b64, #976B64);
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M19.767 12.193c.104 1.156.25 3.975 0 6");
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crj44uotj {
  stop-color: var(--svg-color--996b5e, #996B5E);
}

.cssy6ccya {
  stop-color: var(--svg-color--aa9ba7, #AA9BA7);
  stop-opacity: 0;
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.d10os3b5g {
  stop-color: var(--svg-color--614699, #614699);
}

.d8l0ribxz {
  stop-color: var(--svg-color--482f7c, #482F7C);
}

.d8xf2ibmq {
  d: path("M16.01 7.808h-.017c.044 0 .083 0 .127.004q-.054-.005-.11-.004");
}

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
  stop-opacity: 0;
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.dpe-7hbaw {
  stop-color: var(--svg-color--271a45, #271A45);
}

.dysqi-bns {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M16.498 5.559c.116-.204.292-.365.67-.365c.167 0 .327.046.469.16c.117.096.101.217.01.262l-.242.139c-.284-.092-.599-.104-.907-.196");
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.elt890uby {
  stop-color: var(--svg-color--9e85d7, #9E85D7);
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.f1a_l73ur {
  fill: var(--svg-color--5f323e, #5F323E);
  d: path("M12.668 19.011a.22.22 0 0 1-.043-.238h-.438l.32.996c.262.078.54.05.59-.113a.32.32 0 0 0-.074-.301a9 9 0 0 1-.355-.344");
}

.fs9pa7bci {
  stop-color: var(--svg-color--6e494b, #6E494B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fwox8vyfu {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.924 5.42c.028.038-.03.083-.096.132c-.066.05-.115.084-.142.047c-.028-.037.003-.107.069-.156c.066-.05.142-.06.17-.022");
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gcfqr7bfg {
  stop-color: var(--svg-color--714350, #714350);
  stop-opacity: 0;
}

.gd7pfsb0f {
  stop-color: var(--svg-color--713b4b, #713B4B);
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gvyr6bjbh {
  d: path("M13.964 6.275a.469.469 0 1 0 0-.937a.469.469 0 0 0 0 .937");
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hm4ptbkef {
  fill: var(--svg-color--9d98a2, #9D98A2);
  d: path("M13.841 16.234L14.31 28h.812V17.39h2.203V28h.672l.438-11.766z");
}

.hpe4_756h {
  stop-color: var(--svg-color--856988, #856988);
  stop-opacity: 0;
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i0vp1so6w {
  d: path("M15.129 7.226h1.742v1.352a.871.871 0 0 1-1.742 0z");
}

.iq3r27bkh {
  fill: var(--svg-color--89625b, #89625B);
  d: path("M19.888 20.292c.938-1.982.769-6.259.487-7.824h-1.671c.071 2.426-.156 5.254-.294 6.522a.29.29 0 0 0 .555.15l.116-.262a.184.184 0 0 1 .226-.1a.176.176 0 0 1 .12.202c-.061.299-.172.678-.265.973a.42.42 0 0 0 .239.513c.186.076.401.008.487-.174");
}

.ise8hkbqb {
  fill: var(--svg-color--5d4480, #5D4480);
  d: path("M12.434 29.671v.243H15.5v-1.598h-1.992c-.102.367-.574.754-.817.914a.54.54 0 0 0-.257.441");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j5ojyhbmo {
  fill: var(--svg-color--2f1920, #2F1920);
  d: path("M15.737 2.408c-.494-.109-.938.384-.99.567c.46 1.546 1.62 1.462 2.767 1.334c.686-.076.76.237.819.388c0-1.716-1.46-2.038-2.584-2.286z");
}

.j6ndfp4vo {
  stop-color: var(--svg-color--6a597b, #6A597B);
  stop-opacity: 0;
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jnji2526l {
  d: path("M17.3 5.676a.37.37 0 0 0-.101-.202l-.114.125l.052.1z");
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.jqpze9b9a {
  fill: var(--svg-color--352827, #352827);
  fill-rule: evenodd;
  d: path("m17.628 4.832l-.06.1za.117.117 0 0 1-.12.2h-.002l-.05-.026a1 1 0 0 0-.149-.06a1 1 0 0 0-.467-.04a.117.117 0 0 1-.041-.23c.224-.04.431 0 .58.048a1.4 1.4 0 0 1 .243.104l.004.002z");
}

.k0t-ilbnn {
  d: path("M15.403 5.682c0-.126-.103-.21-.13-.235l-.126.121l.077.158z");
}

.k359d0bjg {
  stop-color: var(--svg-color--645b87, #645B87);
  stop-opacity: 0;
}

.k3iqnbc3x {
  stop-color: var(--svg-color--7759b9, #7759B9);
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kcjik5o6k {
  stop-color: var(--svg-color--6a597b, #6A597B);
}

.kg6c4paol {
  stop-color: var(--svg-color--7f5a58, #7F5A58);
}

.kitn3twkh {
  stop-color: var(--svg-color--5f363f, #5F363F);
}

.kqc1q6b3u {
  stop-color: var(--svg-color--4b3677, #4B3677);
  stop-opacity: 0;
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.l__dw9bpv {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
  stop-opacity: 0;
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lik74_beu {
  d: path("M13.78 5.256h.006l-.004-.116l-.005-.133c.009-.414.25-.574.354-.628l.022-.009l.022-.009c.233-.106.42-.293.52-.538l.035-.085a.115.115 0 0 1 .201-.022c.314.458.837.73 1.392.73h1.404c.079 0 .473.038.496.581l-.052 1.34c-.054 1.223-1.008 2.044-2.174 2.044s-2.12-.82-2.174-2.043z");
}

.liuzkqkjj {
  stop-color: var(--svg-color--713b4b, #713B4B);
  stop-opacity: 0;
}

.lj8hkjeee {
  stop-color: var(--svg-color--6c5ca2, #6C5CA2);
  stop-opacity: 0;
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

.mfgvkccmt {
  cx: 14.93px;
  cy: 5.505px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.17px;
  ry: 0.086px;
}

.mg10me7tz {
  stop-color: var(--svg-color--794958, #794958);
  stop-opacity: 0;
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.mu4khql-m {
  d: path("M16.924 5.42c.028.038-.03.083-.096.132c-.066.05-.115.084-.142.047c-.028-.037.003-.107.069-.156c.066-.05.142-.06.17-.022");
}

.mwlubcb3u {
  stop-color: var(--svg-color--4a367d, #4A367D);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.myif5tbjr {
  fill: var(--svg-color--8b7dbc, #8B7DBC);
  d: path("M20.468 12.512c-.487-2.254-1.629-3.334-3.03-3.829v3.95h2.932a.1.1 0 0 0 .098-.121");
}

.nq2mftbyb {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M13.964 6.275a.469.469 0 1 0 0-.937a.469.469 0 0 0 0 .937");
}

.o_hp5nbjg {
  d: path("M12.112 20.292c-.938-1.982-.769-6.259-.488-7.824h1.672c-.071 2.426.04 5.243.178 6.512c.011.103.084.214 0 .276a.29.29 0 0 1-.438-.115l-.117-.263a.184.184 0 0 0-.226-.1a.176.176 0 0 0-.12.202c.061.299.172.678.265.973a.42.42 0 0 1-.239.513c-.186.076-.401.008-.487-.174");
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.o93ji_bej {
  d: path("M19.888 20.292c.938-1.982.769-6.259.487-7.824h-1.671c.071 2.426-.156 5.254-.294 6.522a.29.29 0 0 0 .555.15l.116-.262a.184.184 0 0 1 .226-.1a.176.176 0 0 1 .12.202c-.061.299-.172.678-.265.973a.42.42 0 0 0 .239.513c.186.076.401.008.487-.174");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ogqxd-bue {
  stop-color: var(--svg-color--1c151f, #1C151F);
}

.olqyf7fmb {
  stop-color: var(--svg-color--875e5e, #875E5E);
}

.omj28bchm {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.043 5.22a.61.61 0 0 1 .591.462a.12.12 0 0 1-.117.148h-.973a.1.1 0 0 1-.1-.118a.61.61 0 0 1 .599-.492");
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

.p88c31myn {
  stop-color: var(--svg-color--815a5b, #815A5B);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pcr8w9bct {
  d: path("M11.533 12.512c.486-2.254 1.628-3.334 3.03-3.829v3.95H11.63a.1.1 0 0 1-.098-.121");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pr00behdc {
  stop-color: var(--svg-color--7b4c5a, #7B4C5A);
}

.pu1qalb0n {
  fill: var(--svg-color--64558f, #64558F);
  d: path("M11.533 12.512c.486-2.254 1.628-3.334 3.03-3.829v3.95H11.63a.1.1 0 0 1-.098-.121");
}

.qb52yacny {
  stop-color: var(--svg-color--8467c1, #8467C1);
}

.qnuhplbln {
  stop-color: var(--svg-color--635185, #635185);
  stop-opacity: 0;
}

.qqztrtlbt {
  stop-color: var(--svg-color--7c4d50, #7C4D50);
}

.qr3eebgfz {
  d: path("M12.941 11.378a3.059 3.059 0 0 1 6.118 0v4.442a.094.094 0 0 1-.094.094h-5.93a.094.094 0 0 1-.094-.094z");
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

.r0rwz7r9i {
  d: path("M18.106 6.275a.469.469 0 1 0 0-.937a.469.469 0 0 0 0 .937");
}

.r2rrbr4ji {
  stop-color: var(--svg-color--886cc6, #886CC6);
  stop-opacity: 0;
}

.r7p4z7bsm {
  d: path("M16.155 7.808q.164.008.336.021c-.114-.008-.223-.017-.336-.021");
}

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.rek67ibyf {
  d: path("M18.106 6.509a.702.702 0 1 0 0-1.404a.702.702 0 0 0 0 1.404");
}

.rl7ruxb0r {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M18.106 6.275a.469.469 0 1 0 0-.937a.469.469 0 0 0 0 .937");
}

.s0xat5bmb {
  fill: var(--svg-color--3b2828, #3B2828);
  d: path("M19.333 19.011a.22.22 0 0 0 .043-.238h.437l-.32.996c-.262.078-.54.05-.59-.113a.32.32 0 0 1 .074-.301c.083-.077.271-.253.355-.344");
}

.s61flvbkc {
  stop-color: var(--svg-color--7361ab, #7361AB);
  stop-opacity: 0;
}

.sb3cb-bog {
  stop-color: var(--svg-color--856988, #856988);
}

.sf6dqgv3q {
  stop-color: var(--svg-color--4a367d, #4A367D);
  stop-opacity: 0;
}

.sgj6b5b-t {
  stop-color: var(--svg-color--655690, #655690);
  stop-opacity: 0;
}

.shh_g2b0q {
  stop-color: var(--svg-color--874d4c, #874D4C);
  stop-opacity: 0;
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.t9k87pm2r {
  stop-color: var(--svg-color--875555, #875555);
}

.tfix0o_9x {
  stop-color: var(--svg-color--7c63b5, #7C63B5);
  stop-opacity: 0;
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.u1r10c4ff {
  fill-rule: evenodd;
  d: path("M19.135 6.422c.092-.19.14-.402.14-.623a1.4 1.4 0 0 0-.116-.57h.002a1.4 1.4 0 0 0-.123-.223v-.001c-.15-.23-.23-.5-.23-.773v-.004a1.44 1.44 0 0 0-1.44-1.44a.24.24 0 0 1-.198-.101a1.442 1.442 0 0 0-2.34 0a.25.25 0 0 1-.199.101h-.037a1.44 1.44 0 0 0-1.402 1.44v.004c0 .274-.08.543-.23.773v.001a1.44 1.44 0 0 0-.097 1.416a.23.23 0 0 1 0 .199a1.402 1.402 0 0 0 1.263 2.018h3.744a1.402 1.402 0 0 0 1.263-2.018a.22.22 0 0 1 0-.2m-5.349-1.166h-.005l.523 1.028c.053 1.222.53 0 1.696 0s1.674 1.36 1.727.138l.496-1.395c-.023-.543-.417-.581-.496-.581h-1.404a1.69 1.69 0 0 1-1.392-.73a.115.115 0 0 0-.201.022l-.036.085a1 1 0 0 1-.541.547l-.023.01c-.102.053-.344.213-.353.627l.005.133z");
}

.u1ssmd66p {
  d: path("M20.468 12.512c-.487-2.254-1.629-3.334-3.03-3.829v3.95h2.932a.1.1 0 0 0 .098-.121");
}

.ubznubc5z {
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M16 7.077a1.3 1.3 0 0 1-.62-.15c-.061-.032-.127.038-.089.095a.843.843 0 0 0 1.418 0c.038-.059-.027-.127-.089-.095c-.18.095-.39.15-.62.15Z");
}

.ucup2sb_b {
  d: path("M15.047 5.338a.39.39 0 0 0-.375.492h.752a.392.392 0 0 0-.377-.492");
}

.uj7hgsb3u {
  stop-color: var(--svg-color--815a5b, #815A5B);
}

.ukvj5-vlj {
  d: path("M19.566 29.671v.243H16.5v-1.598h1.992c.102.367.574.754.817.914c.186.123.257.3.257.441");
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.v_ft29bcw {
  stop-color: var(--svg-color--592631, #592631);
}

.v7kodccae {
  fill: var(--svg-color--47383d, #47383D);
  d: path("m17.05 3.983l-.622.114a.3.3 0 1 1-.055-.595h1.021c.604 0 .804.608.829.816a1.37 1.37 0 0 0-1.173-.335");
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.vei8hrc-a {
  d: path("M13.956 6.509a.702.702 0 1 0 0-1.404a.702.702 0 0 0 0 1.404");
}

.vks9dsnnd {
  cx: 14.93px;
  cy: 5.505px;
  rx: 0.17px;
  ry: 0.086px;
}

.vli7qpbzc {
  fill: var(--svg-color--272528, #272528);
  d: path("M15.502 5.559c-.116-.204-.292-.365-.67-.365a.72.72 0 0 0-.469.16c-.117.096-.101.217-.01.262l.242.139c.284-.092.599-.104.907-.196");
}

.vynwlxbbm {
  d: path("M15.737 2.408c-.494-.109-.938.384-.99.567c.46 1.546 1.62 1.462 2.767 1.334c.686-.076.76.237.819.388c0-1.716-1.46-2.038-2.584-2.286z");
}

.w2wdskbew {
  stop-color: var(--svg-color--503a89, #503A89);
}

.wg3eepbwp {
  stop-color: var(--svg-color--805c54, #805C54);
}

.wirx8nysp {
  fill: var(--svg-color--88014f, #88014F);
  d: path("M16 7.077a1.3 1.3 0 0 1-.62-.15c-.061-.032-.127.038-.089.095a.843.843 0 0 0 1.418 0c.038-.059-.027-.127-.089-.095c-.18.095-.39.15-.62.15");
}

.wrh2b4bbx {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
}

.wwbz7ibcz {
  stop-color: var(--svg-color--462f5e, #462F5E);
}

.x_ik4kbfh {
  stop-color: var(--svg-color--714350, #714350);
}

.x106i8gqz {
  fill: var(--svg-color--000, #000);
  d: path("M15.27 5.728a.22.22 0 0 0-.223-.223a.222.222 0 0 0-.198.325h.395a.2.2 0 0 0 .026-.102");
}

.x7tdxqavt {
  stop-color: var(--svg-color--aa9ba7, #AA9BA7);
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xqme1t_en {
  fill: var(--svg-color--827a8a, #827A8A);
  d: path("m13.016 15.863l.484 12.453h2l.238-9.523c0-.329.029-.86.262-.86c.212 0 .263.555.262.86l.238 9.523h2l.484-12.453z");
}

.xsr8v7bqw {
  stop-color: var(--svg-color--6c3537, #6C3537);
}

.xx6d_cb-a {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m15.829 5.71l-.298.741a.235.235 0 0 0 .227.305h.343c.16 0 .274-.155.227-.305l-.232-.741c-.05-.165-.215-.165-.267 0");
}

.y1s-sz65s {
  fill: var(--svg-color--000, #000);
  d: path("M16.73 5.728c0-.124.1-.223.223-.223a.222.222 0 0 1 .198.325h-.395a.2.2 0 0 1-.026-.102");
}

.y3uyr4btc {
  stop-color: var(--svg-color--7f5a58, #7F5A58);
  stop-opacity: 0;
}

.yamoh3dov {
  stop-color: var(--svg-color--764e4c, #764E4C);
}

.ycrcotb4u {
  stop-color: var(--svg-color--986f60, #986F60);
  stop-opacity: 0;
}

.ytarfqbur {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.739 2.953c.01.106.102.504.237.746");
}

.z26rrllgi {
  stop-color: var(--svg-color--6e494b, #6E494B);
}

.z3z2fqbpi {
  stop-color: var(--svg-color--635185, #635185);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zhgg7cc0u {
  stop-color: var(--svg-color--6f353a, #6F353A);
  stop-opacity: 0;
}

.zoq8fuaif {
  stop-color: var(--svg-color--986f60, #986F60);
}

.zoxixubdj {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.957 5.22a.61.61 0 0 0-.591.462a.12.12 0 0 0 .117.148h.973a.1.1 0 0 0 .1-.118a.61.61 0 0 0-.6-.492");
}

.zqan0v-dy {
  stop-color: var(--svg-color--645b87, #645B87);
}

</style>
