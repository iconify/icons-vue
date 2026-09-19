<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iKSZuhc)"><path fill="url(#i34XkhC)" clip-rule="evenodd" class="uotx2eifv"/><path fill="url(#icPjkJc)" clip-rule="evenodd" class="uotx2eifv"/><path fill="url(#ioMs38j)" clip-rule="evenodd" class="uotx2eifv"/><path fill="url(#iFb9kSd)" clip-rule="evenodd" class="uotx2eifv"/><path fill="url(#iqGKYPc)" clip-rule="evenodd" class="uotx2eifv"/><path fill="url(#iSzSgwb)" clip-rule="evenodd" class="uotx2eifv"/><path fill="url(#iWuJ6Me)" clip-rule="evenodd" class="uotx2eifv"/><path fill="url(#ihjhBte)" clip-rule="evenodd" class="uotx2eifv"/><path fill="url(#iP5IRIk)" clip-rule="evenodd" class="uotx2eifv"/><path fill="url(#i2y4FTc)" clip-rule="evenodd" class="uotx2eifv"/><path fill="url(#ihAiPCL)" clip-rule="evenodd" class="uotx2eifv"/><path fill="url(#ixTPO6d)" clip-rule="evenodd" class="uotx2eifv"/></g><path fill="url(#iTCwzGY)" class="y319mjb9d"/><path fill="url(#itZZh3b)" class="y319mjb9d"/><path fill="url(#iXbb7te)" class="y319mjb9d"/><path fill="url(#iq2p6Ua)" class="y319mjb9d"/><path fill="url(#im5hvlb)" class="y319mjb9d"/><path fill="url(#izGQ9Fe)" class="y319mjb9d"/><path fill="url(#igEYmqb)" class="y319mjb9d"/><path fill="url(#iZrbGie)" class="xicv_p3ce"/><path fill="url(#iHeLedd)" class="lr_95xbzv"/><path fill="url(#inO5B1d)" class="rfbqtga6z"/><path fill="url(#i2NInie)" class="rfbqtga6z"/><path fill="url(#iN485tb)" class="rfbqtga6z"/><path fill="url(#iO6MbWd)" class="fchyrxbpw"/><path fill="url(#i1CHJhu)" class="fchyrxbpw"/><path fill="url(#iqFNLXc)" class="fchyrxbpw"/><path fill="url(#ijtxjve)" class="h0xboubpx"/><path fill="url(#ilRboHd)" class="h0xboubpx"/><path fill="url(#iZrbGie)" class="xicv_p3ce"/><path fill="url(#iHeLedd)" class="lr_95xbzv"/><g filter="url(#iuxgyqb)"><path class="v769b-w_v"/></g><g filter="url(#ie68MQb)"><path fill="url(#ie5tkGc)" class="qtky_3b3t"/></g><path fill="url(#iGuWf0c)" class="bzptrm36o"/><path fill="url(#i4KLMQe)" class="bzptrm36o"/><path fill="url(#iIkAT6c)" class="bzptrm36o"/><path fill="url(#io5Zhsc)" class="bzptrm36o"/><path fill="url(#iZsQLjc)" class="bzptrm36o"/><path fill="url(#imE4LPb)" class="bzptrm36o"/><path fill="url(#iNJjhMC)" class="jvt5kfcji"/><path fill="url(#ikYuTOc)" class="jvt5kfcji"/><path fill="url(#iif1KFb)" class="jvt5kfcji"/><path fill="url(#iYSysmd)" class="jvt5kfcji"/><path fill="url(#iiAs0sp)" class="jvt5kfcji"/><path fill="url(#iZRfQjr)" class="jvt5kfcji"/><path fill="url(#i6rMTzd)" class="ee3a7kppm"/><path clip-rule="evenodd" class="w2k7zib9b"/><path fill="url(#i42nmwa)" clip-rule="evenodd" class="o7i1pebeu"/><path fill="url(#iqc1s0c)" clip-rule="evenodd" class="o7i1pebeu"/><path fill="url(#iYERtSc)" clip-rule="evenodd" class="o7i1pebeu"/><path fill="url(#iEAwPCd)" clip-rule="evenodd" class="o7i1pebeu"/><g filter="url(#iqmoAIe)"><path class="yuhux9lbj"/></g><path fill="url(#iyZjLqJ)" class="acjr-vb4d"/><g filter="url(#ikYuyec)"><path fill="url(#i1CWygc)" class="j0v18bclr"/></g><g filter="url(#izwDaGc)"><path fill="url(#iONAf6d)" clip-rule="evenodd" class="iwuq58bbk"/></g><g filter="url(#i0pdaMe)"><path class="hp2ou3bgv"/></g><path fill="url(#itFg99b)" clip-rule="evenodd" class="sugd91b_r"/><path fill="url(#iuzyDNo)" clip-rule="evenodd" class="sugd91b_r"/><path fill="url(#iklYvbb)" clip-rule="evenodd" class="b6bhi65kx"/><path fill="url(#ioUunwI)" clip-rule="evenodd" class="b6bhi65kx"/><g filter="url(#iS9Lp4b)"><path fill="url(#iTFs5wb)" class="n9enpnncz"/></g><path fill="url(#indQdzZ)" class="n9enpnncz"/><g filter="url(#i2ZrQ4d)"><path fill="url(#i6sZWwb)" class="qakf2gbwa"/><path fill="url(#iawTd7b)" class="qakf2gbwa"/></g><g filter="url(#i3ndpQe)"><path class="c_809kbzd"/><path fill="url(#iZaKloj)" class="b2cidcc6s"/></g><g filter="url(#iIRF6Bc)"><path class="j24wvbc2z"/><path fill="url(#iL7aExO)" class="wmqo90blr"/></g><g filter="url(#iTTYYKe)"><path fill="url(#ivM85fd)" class="rgo735bpi"/><path fill="url(#iXLVegd)" class="rgo735bpi"/><path fill="url(#iTPYm8c)" class="rgo735bpi"/><path fill="url(#i2Xlb7d)" class="rgo735bpi"/><path fill="url(#iu2I93d)" class="rgo735bpi"/><path fill="url(#iVQxydd)" class="rgo735bpi"/><path fill="url(#i5iFMiY)" class="rgo735bpi"/><path fill="url(#iyZ36qb)" class="rgo735bpi"/></g><path fill="url(#iNWhfhd)" class="rgo735bpi"/><g filter="url(#ih1Cvjh)"><path class="goseu50zy"/></g><g filter="url(#ixQoN7b)"><path class="rx5usmbog"/><path fill="url(#iaEZfHP)" class="rhoewlwza"/><path fill="url(#i9kXKzc)" class="rhoewlwza"/><path fill="url(#i0NhJBd)" class="rhoewlwza"/><path fill="url(#iaDlFzb)" class="rhoewlwza"/></g><path fill="url(#iZZi9Be)" class="rhoewlwza"/><path fill="url(#icupYCq)" class="rhoewlwza"/><path stroke="url(#itNVynb)" class="pr6x_4-el"/><g filter="url(#ia09ese)"><path class="l--nyyiee"/></g><g filter="url(#i53JbPV)"><path class="sbh0zqhft"/></g><g filter="url(#izX2djc)"><path class="jlf3122ku"/></g><g filter="url(#iQkkUbb)"><path clip-rule="evenodd" class="o51x77z6i"/></g><path class="l54r-4bre"/><path fill="url(#it89jFK)" class="r8b6tnb2b"/><path class="f6o95nb4t"/><g filter="url(#iIqHJPc)"><path class="w23khihlj"/><path fill="url(#iGb7Lhb)" class="gh6qe3bwt"/></g><g filter="url(#iwqSfGf)"><path fill="url(#iccsxee)" class="q5hnu0byb"/></g><path class="zfvylccst"/><path fill="url(#ibF6jCe)" class="g440twb_j"/><path class="zhcbbgubg"/><g filter="url(#i40aHwd)"><path fill="url(#inVXZAd)" class="aqjloibyk"/></g><g filter="url(#i7jLKjZ)"><ellipse transform="rotate(-27.914 13.547 9.886)" class="l93m1_oje"/><ellipse fill="url(#iTA5wLM)" transform="rotate(-27.914 13.547 9.886)" class="wzlj6ub9j"/></g><g filter="url(#iUBL1Sb)"><path class="cgbm-4bwm"/></g><g filter="url(#iyg25zc)"><path class="kwpy16lwp"/></g><g filter="url(#iwk3eWd)"><path class="mi9_q0bii"/><path fill="url(#ionCsne)" class="jjfnpib7f"/><path fill="url(#ikzaK1F)" class="jjfnpib7f"/></g><g filter="url(#ishUXwd)"><path class="uiflfplei"/><path fill="url(#iwQ32Ie)" class="n95ebwv8k"/><path fill="url(#i7CCrec)" class="n95ebwv8k"/></g><g filter="url(#ixYWlsC)"><path stroke="url(#i1I8OiP)" class="moec6ccmu"/></g><g filter="url(#ixLf0Cd)"><path class="ms2aglfku"/></g><defs><radialGradient id="icPjkJc" cx="0" cy="0" r="1" gradientTransform="matrix(-.60337 4.55908 -5.69522 -.75373 15.699 13.08)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="w9gpkna4y"/><stop offset="1" class="xvq3mubqy"/></radialGradient><radialGradient id="ioMs38j" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.883 13.348)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="u3fmvdnwh"/><stop offset="1" class="ysga7wb0w"/></radialGradient><radialGradient id="iFb9kSd" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.91 8.157)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="jo-m975mj"/><stop offset="1" class="ecm2ecc2d"/></radialGradient><radialGradient id="iqGKYPc" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.344 7.641)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ksj-40n4x"/><stop offset="1" class="qkj18_koj"/></radialGradient><radialGradient id="iSzSgwb" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 4.154 11.59)scale(2.95399 4.10059)" gradientUnits="userSpaceOnUse"><stop class="bk_mrebvc"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="iWuJ6Me" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.964 6.821)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="g2m4aac5s"/><stop offset="1" class="tulkzacvs"/></radialGradient><radialGradient id="ihjhBte" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.84482 23.51 9.727)" gradientUnits="userSpaceOnUse"><stop class="ii82yjbfl"/><stop offset="1" class="tobrp8lrd"/></radialGradient><radialGradient id="iP5IRIk" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.644 7.983)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="gto3tpbjl"/><stop offset="1" class="k8ni71bqd"/></radialGradient><radialGradient id="i2y4FTc" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 12.975 -3.769)scale(2.80034 2.21491)" gradientUnits="userSpaceOnUse"><stop class="j6tbtfb5n"/><stop offset="1" class="u7ezkxzae"/></radialGradient><radialGradient id="ihAiPCL" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.858 9.691)" gradientUnits="userSpaceOnUse"><stop class="r4e237cot"/><stop offset="1" class="ktpt3tb_i"/></radialGradient><radialGradient id="ixTPO6d" cx="0" cy="0" r="1" gradientTransform="rotate(-102.748 14.168 -3.915)scale(3.79787 1.37073)" gradientUnits="userSpaceOnUse"><stop class="fyy3crxae"/><stop offset="1" class="x7431zb1g"/></radialGradient><radialGradient id="iTCwzGY" cx="0" cy="0" r="1" gradientTransform="matrix(-10.8 0 0 -20.6925 23.195 23.88)" gradientUnits="userSpaceOnUse"><stop class="w-_6jxb_z"/><stop offset="1" class="fr_rdtj9g"/></radialGradient><radialGradient id="im5hvlb" cx="0" cy="0" r="1" gradientTransform="rotate(-121.204 19.142 8.157)scale(16.5873 16.3485)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="o3tc-dnyn"/><stop offset="1" class="l-etq6b9a"/></radialGradient><radialGradient id="izGQ9Fe" cx="0" cy="0" r="1" gradientTransform="matrix(.81252 3.5625 -3.94168 .899 18.05 24.443)" gradientUnits="userSpaceOnUse"><stop class="vgwmt2-9g"/><stop offset="1" class="r24zcwbvl"/></radialGradient><radialGradient id="igEYmqb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.97501 .96027 0 15.966 29.949)" gradientUnits="userSpaceOnUse"><stop class="k3g0v3buh"/><stop offset="1" class="afwov9b1d"/></radialGradient><radialGradient id="inO5B1d" cx="0" cy="0" r="1" gradientTransform="matrix(3.44348 .3125 -.8676 9.56028 5.332 24.662)" gradientUnits="userSpaceOnUse"><stop class="kzw1yxrkd"/><stop offset="1" class="lnyefdcqm"/></radialGradient><radialGradient id="i2NInie" cx="0" cy="0" r="1" gradientTransform="rotate(107.994 -1.695 12.31)scale(6.67657 7.47746)" gradientUnits="userSpaceOnUse"><stop class="o874sbcxz"/><stop offset="1" class="yqete2_ye"/></radialGradient><radialGradient id="iO6MbWd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.07502 1.40623 -3.71957 -8.13362 26.231 21.911)" gradientUnits="userSpaceOnUse"><stop class="dlt2kgbvz"/><stop offset="1" class="n7ni7rtly"/></radialGradient><radialGradient id="i1CHJhu" cx="0" cy="0" r="1" gradientTransform="matrix(0 11 -8.46398 0 24.544 20.286)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="rqdbjlbdw"/><stop offset=".974" class="anyvddbxc"/></radialGradient><radialGradient id="ijtxjve" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.65625 -3.01125 0 16 18.505)" gradientUnits="userSpaceOnUse"><stop offset=".398" class="k7ybb1bik"/><stop offset="1" class="ywx3jq9xy"/></radialGradient><radialGradient id="ilRboHd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.53125 2.8605 0 16.364 30.443)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="p5_0bzbaz"/><stop offset="1" class="iqq-d2brk"/></radialGradient><radialGradient id="io5Zhsc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.1875 -.84559 0 19.139 18.068)" gradientUnits="userSpaceOnUse"><stop class="skz637x0p"/><stop offset="1" class="wxe5vubnr"/></radialGradient><radialGradient id="iZsQLjc" cx="0" cy="0" r="1" gradientTransform="matrix(2.69211 -3.05149 1.0422 .91946 16.447 26.51)" gradientUnits="userSpaceOnUse"><stop class="etbfcvxig"/><stop offset="1" class="oc1bwblbr"/></radialGradient><radialGradient id="imE4LPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.84375 .55327 0 19.139 24.818)" gradientUnits="userSpaceOnUse"><stop class="v2gep8uzg"/><stop offset="1" class="r9qw8z0np"/></radialGradient><radialGradient id="iNJjhMC" cx="0" cy="0" r="1" gradientTransform="rotate(158.705 5.384 11.255)scale(3.25339 6.38774)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="c9e2npbbn"/><stop offset="1" class="cf3hk9c-f"/></radialGradient><radialGradient id="ikYuTOc" cx="0" cy="0" r="1" gradientTransform="matrix(3.46106 -9.38813 7.62182 2.80989 10.13 24.872)" gradientUnits="userSpaceOnUse"><stop offset=".691" class="x7yaztbkk"/><stop offset="1" class="rl5jhib1q"/></radialGradient><radialGradient id="iYSysmd" cx="0" cy="0" r="1" gradientTransform="matrix(.3906 -2.76562 2.11886 .29926 10.302 19.443)" gradientUnits="userSpaceOnUse"><stop class="uwchitapr"/><stop offset="1" class="xag1knb5p"/></radialGradient><radialGradient id="iiAs0sp" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 2.20312 -.6764 -.13432 12.098 18.27)" gradientUnits="userSpaceOnUse"><stop offset=".439" class="c-t0maccw"/><stop offset="1" class="w0rhj52ia"/></radialGradient><radialGradient id="iZRfQjr" cx="0" cy="0" r="1" gradientTransform="rotate(49.295 -16.975 24.201)scale(2.80315 .97425)" gradientUnits="userSpaceOnUse"><stop class="azmrtxbft"/><stop offset="1" class="j-efl5b-c"/></radialGradient><radialGradient id="i6rMTzd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.125 -2.67249 0 15.985 16.34)" gradientUnits="userSpaceOnUse"><stop class="sjbdbzbts"/><stop offset=".47" class="orqwrobrr"/><stop offset=".858" class="nzzp07bei"/></radialGradient><radialGradient id="iqc1s0c" cx="0" cy="0" r="1" gradientTransform="matrix(.5209 2.3152 -1.36598 .30734 18.127 16.014)" gradientUnits="userSpaceOnUse"><stop class="w_gx_6l5c"/><stop offset="1" class="sruu51y8f"/></radialGradient><radialGradient id="iYERtSc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.14062 .59375 0 12.582 19.99)" gradientUnits="userSpaceOnUse"><stop class="viff9wbjp"/><stop offset="1" class="t68so1bro"/></radialGradient><radialGradient id="iEAwPCd" cx="0" cy="0" r="1" gradientTransform="rotate(117.031 1.832 12.17)scale(1.71903 1.83663)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="fv5w29bdg"/><stop offset="1" class="e6fuuiw3e"/></radialGradient><radialGradient id="iyZjLqJ" cx="0" cy="0" r="1" gradientTransform="rotate(121.842 3.168 18.041)scale(1.90409 1.71171)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="ka5t_pbkm"/><stop offset="1" class="y58nhpnsg"/></radialGradient><radialGradient id="i1CWygc" cx="0" cy="0" r="1" gradientTransform="matrix(.78648 -.78648 .51957 .51957 19.248 25.857)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="h4zbx-g8y"/><stop offset="1" class="bmbim-qcd"/></radialGradient><radialGradient id="iuzyDNo" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.5 -.28074 0 10.13 23.52)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="rognhpd5x"/><stop offset="1" class="f923khbrt"/></radialGradient><radialGradient id="indQdzZ" cx="0" cy="0" r="1" gradientTransform="matrix(-.6537 -1.20346 1.36368 -.74073 10.921 12.188)" gradientUnits="userSpaceOnUse"><stop class="wlzou1bho"/><stop offset="1" class="muarw1mje"/></radialGradient><radialGradient id="i6sZWwb" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.04 11.018)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="iawTd7b" cx="0" cy="0" r="1" gradientTransform="matrix(1.20681 0 0 .5196 20.945 8.873)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="iZaKloj" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.392 10.691)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="iL7aExO" cx="0" cy="0" r="1" gradientTransform="rotate(180 5.7 5.29)scale(1.05596)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="ivM85fd" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.328 7.09)scale(7.16175 9.58588)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="iXLVegd" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 7.84 7.337)scale(2.38203 1.65881)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="iTPYm8c" cx="0" cy="0" r="1" gradientTransform="matrix(1.28915 -3.92836 4.98436 1.6357 13.838 16.55)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="i2Xlb7d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28468 7.37319 -9.2164 -1.60583 17.023 9.625)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="fa0q4x0wh"/><stop offset=".955" class="vfgk4hb_x"/></radialGradient><radialGradient id="iu2I93d" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.333 6.752)scale(7.03739 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="iVQxydd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.301 9.623)" gradientUnits="userSpaceOnUse"><stop class="azt-9rbtm"/><stop offset="1" class="ci16jsbol"/></radialGradient><radialGradient id="i5iFMiY" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.924 9.395)" gradientUnits="userSpaceOnUse"><stop class="zemyxxbjg"/><stop offset="1" class="k1zv-ubmt"/></radialGradient><radialGradient id="iyZ36qb" cx="0" cy="0" r="1" gradientTransform="matrix(-.87016 3.22674 -2.58193 -.69627 17.383 7.307)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="iNWhfhd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.095 11.11)" gradientUnits="userSpaceOnUse"><stop class="fyxppic9g"/><stop offset="1" class="kq5b787yl"/></radialGradient><radialGradient id="iaEZfHP" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.784 11.837)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="iaDlFzb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.545 12.05)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="icupYCq" cx="0" cy="0" r="1" gradientTransform="rotate(145.529 6.412 8.267)scale(1.66326 1.99898)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="xs9vt_bzp"/><stop offset="1" class="p13423bzd"/><stop offset="1" class="jjvamgr7p"/></radialGradient><radialGradient id="it89jFK" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.182 9.982)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iGb7Lhb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.954 10.066)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ibF6jCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.818 9.982)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iTA5wLM" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.787 -1.56)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ionCsne" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 11.295 -4.125)scale(3.03069 1.55043)" gradientUnits="userSpaceOnUse"><stop class="gaydocc3b"/><stop offset="1" class="o5ryhdc_j"/></radialGradient><radialGradient id="ikzaK1F" cx="0" cy="0" r="1" gradientTransform="matrix(1.14952 -1.97524 1.06043 .61714 12.05 6.88)" gradientUnits="userSpaceOnUse"><stop class="bkfqk3fbn"/><stop offset="1" class="hrqlkdbpd"/></radialGradient><radialGradient id="iwQ32Ie" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.121 6.958)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ukea7pdhy"/><stop offset="1" class="wuqjd3b5z"/></radialGradient><radialGradient id="i7CCrec" cx="0" cy="0" r="1" gradientTransform="matrix(-.21033 1.3672 -2.94145 -.45252 16.21 3.024)" gradientUnits="userSpaceOnUse"><stop class="y3gk9pbvh"/><stop offset="1" class="j2p90_-bc"/><stop offset="1" class="ru9fl6bjc"/></radialGradient><linearGradient id="i34XkhC" x1="20.693" x2="14.559" y1="3.626" y2="14.387" gradientUnits="userSpaceOnUse"><stop class="ap760fb9g"/><stop offset="1" class="w1etxcbdz"/></linearGradient><linearGradient id="itZZh3b" x1="23.309" x2="22.997" y1="24.56" y2="24.56" gradientUnits="userSpaceOnUse"><stop offset=".225" class="sm4v8rvoi"/><stop offset="1" class="x3e-lhbqh"/></linearGradient><linearGradient id="iXbb7te" x1="8.731" x2="9.067" y1="24.56" y2="24.56" gradientUnits="userSpaceOnUse"><stop offset=".383" class="k2sjcrc_g"/><stop offset="1" class="v717bwb7u"/></linearGradient><linearGradient id="iq2p6Ua" x1="16.176" x2="16.176" y1="30.911" y2="29.099" gradientUnits="userSpaceOnUse"><stop class="vxx0ssbsk"/><stop offset="1" class="q3wk7p4fa"/></linearGradient><linearGradient id="iZrbGie" x1="8.815" x2="23.191" y1="15.389" y2="15.389" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iHeLedd" x1="8.815" x2="23.191" y1="15.358" y2="15.358" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iN485tb" x1="6.995" x2="6.995" y1="30.724" y2="29.265" gradientUnits="userSpaceOnUse"><stop class="vxx0ssbsk"/><stop offset="1" class="q3wk7p4fa"/></linearGradient><linearGradient id="iqFNLXc" x1="22.666" x2="23.445" y1="25.598" y2="25.598" gradientUnits="userSpaceOnUse"><stop offset=".643" class="sm4v8rvoi"/><stop offset="1" class="x3e-lhbqh"/></linearGradient><linearGradient id="ie5tkGc" x1="16.176" x2="23.801" y1="26.943" y2="19.349" gradientUnits="userSpaceOnUse"><stop class="e---z_byu"/><stop offset="1" class="dxszyubmb"/></linearGradient><linearGradient id="iGuWf0c" x1="21.89" x2="16.775" y1="18.338" y2="23.857" gradientUnits="userSpaceOnUse"><stop class="xoshv8bzu"/><stop offset="1" class="i4xusnb1i"/></linearGradient><linearGradient id="i4KLMQe" x1="20.044" x2="19.887" y1="15.62" y2="17.682" gradientUnits="userSpaceOnUse"><stop class="fx7jj2m3f"/><stop offset="1" class="foe4l_bip"/></linearGradient><linearGradient id="iIkAT6c" x1="17.582" x2="18.739" y1="18.865" y2="19.349" gradientUnits="userSpaceOnUse"><stop class="kv70nqbkg"/><stop offset="1" class="y2rlftbia"/></linearGradient><linearGradient id="iif1KFb" x1="12.27" x2="12.598" y1="23.162" y2="22.802" gradientUnits="userSpaceOnUse"><stop class="s7vootu_w"/><stop offset="1" class="hou90zp4m"/></linearGradient><linearGradient id="i42nmwa" x1="20.309" x2="19.637" y1="23.63" y2="23.646" gradientUnits="userSpaceOnUse"><stop offset=".294" class="nrx5bzr9s"/><stop offset="1" class="xmdmj-dwi"/></linearGradient><linearGradient id="iONAf6d" x1="12.205" x2="12.205" y1="19.829" y2="28.412" gradientUnits="userSpaceOnUse"><stop class="sp4_sibjj"/><stop offset="1" class="lpc21p-wa"/></linearGradient><linearGradient id="itFg99b" x1="9.514" x2="10.409" y1="25.228" y2="25.228" gradientUnits="userSpaceOnUse"><stop class="gzrilbbya"/><stop offset="1" class="je8_hbb1l"/></linearGradient><linearGradient id="iklYvbb" x1="13.887" x2="14.559" y1="25.238" y2="25.238" gradientUnits="userSpaceOnUse"><stop class="gzrilbbya"/><stop offset="1" class="je8_hbb1l"/></linearGradient><linearGradient id="ioUunwI" x1="14.95" x2="14.707" y1="24.756" y2="24.756" gradientUnits="userSpaceOnUse"><stop class="pgy4y9bks"/><stop offset="1" class="ll7oxmbau"/></linearGradient><linearGradient id="iTFs5wb" x1="9.705" x2="11.563" y1="10.666" y2="10.666" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="i9kXKzc" x1="15.061" x2="16" y1="11.91" y2="11.91" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="i0NhJBd" x1="16" x2="16" y1="12.617" y2="11.991" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="iZZi9Be" x1="16.078" x2="16.078" y1="12.683" y2="12.544" gradientUnits="userSpaceOnUse"><stop class="b576ppbxh"/><stop offset="1" class="a_xwx-nqh"/></linearGradient><linearGradient id="itNVynb" x1="14.936" x2="15.397" y1="14.119" y2="13.407" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="iccsxee" x1="18.96" x2="18.646" y1="10.036" y2="10.229" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="inVXZAd" x1="14.562" x2="14.248" y1="10.036" y2="10.229" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i1I8OiP" x1="12.891" x2="13.381" y1="3.627" y2="4.892" gradientUnits="userSpaceOnUse"><stop class="olrv_cchi"/><stop offset="1" class="lwhsndh-i"/></linearGradient><filter id="iKSZuhc" width="15.268" height="15.768" x="8.491" y="1.301" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.133333 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24151"/></filter><filter id="iuxgyqb" width="7.147" height="11.557" x="9.03" y="15.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24151" stdDeviation=".5"/></filter><filter id="ie68MQb" width="7.147" height="11.557" x="15.924" y="15.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24151" stdDeviation=".5"/></filter><filter id="iqmoAIe" width="3.699" height="3.699" x="16.995" y="23.959" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24151" stdDeviation=".375"/></filter><filter id="ikYuyec" width="1.42" height="1.42" x="18.965" y="24.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.411765 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24151"/></filter><filter id="izwDaGc" width="5.381" height="7.171" x="9.514" y="19.629" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.239216 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24151"/></filter><filter id="i0pdaMe" width="5.3" height="6.89" x="9.58" y="19.802" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24151" stdDeviation=".15"/></filter><filter id="iS9Lp4b" width="3.368" height="3.218" x="9.705" y="8.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24151"/></filter><filter id="i2ZrQ4d" width="3.218" height="3.468" x="19.218" y="8.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24151"/></filter><filter id="i3ndpQe" width="3.148" height="3.148" x="19.253" y="9.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24151" stdDeviation=".25"/></filter><filter id="iIRF6Bc" width="2.848" height="2.848" x="9.91" y="9.155" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24151" stdDeviation=".175"/></filter><filter id="iTTYYKe" width="10.191" height="11.127" x="10.905" y="5.672" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24151"/></filter><filter id="ih1Cvjh" width="2.877" height="3.682" x="14.399" y="9.574" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24151" stdDeviation=".25"/></filter><filter id="ixQoN7b" width="2.377" height="3.182" x="14.811" y="9.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24151" stdDeviation=".125"/></filter><filter id="ia09ese" width="3.001" height="1.286" x="16.942" y="9.174" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0705882 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24151"/></filter><filter id="i53JbPV" width="3.001" height="1.286" x="12.057" y="9.174" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24151"/></filter><filter id="izX2djc" width="2.453" height="1.091" x="12.192" y="7.751" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24151"/></filter><filter id="iQkkUbb" width="2.453" height="1.091" x="17.609" y="7.751" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24151"/></filter><filter id="iIqHJPc" width=".787" height=".696" x="17.448" y="9.542" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24151" stdDeviation=".05"/></filter><filter id="iwqSfGf" width=".891" height=".913" x="18.288" y="9.617" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24151" stdDeviation=".1"/></filter><filter id="i40aHwd" width=".986" height="1.04" x="13.845" y="9.554" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24151" stdDeviation=".1"/></filter><filter id="i7jLKjZ" width=".913" height=".704" x="13.09" y="9.534" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24151" stdDeviation=".05"/></filter><filter id="iUBL1Sb" width="2.661" height="1.378" x="17.439" y="7.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24151" stdDeviation=".2"/></filter><filter id="iyg25zc" width="2.661" height="1.378" x="11.988" y="7.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24151" stdDeviation=".2"/></filter><filter id="iwk3eWd" width="4.312" height="4.613" x="9.646" y="3.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.286275 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24151"/><feGaussianBlur result="effect2_foregroundBlur_3987_24151" stdDeviation=".2"/></filter><filter id="ishUXwd" width="8.767" height="5.782" x="12.83" y="2.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.317647 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24151"/><feGaussianBlur result="effect2_foregroundBlur_3987_24151" stdDeviation=".125"/></filter><filter id="ixYWlsC" width="1.145" height="2.31" x="12.809" y="3.737" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24151" stdDeviation=".1"/></filter><filter id="ixLf0Cd" width="6.427" height="3.372" x="15.418" y="4.545" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24151" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-health-worker-medium" /></template>
<style>
.a_xwx-nqh {
  stop-color: var(--svg-color--8f5269, #8F5269);
  stop-opacity: 0;
}

.a21bmlbcx {
  stop-color: var(--svg-color--945a73, #945A73);
  stop-opacity: 0;
}

.ab1vgh_ru {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

.acjr-vb4d {
  d: path("M19.675 26.68a1.26 1.26 0 1 0 0-2.52a1.26 1.26 0 0 0 0 2.52");
}

.afwov9b1d {
  stop-color: var(--svg-color--b1909e, #B1909E);
  stop-opacity: 0;
}

.ame5l9u0o {
  stop-color: var(--svg-color--906d53, #906D53);
  stop-opacity: 0;
}

.anyvddbxc {
  stop-color: var(--svg-color--d1c0e3, #D1C0E3);
}

.aotu-xwil {
  stop-color: var(--svg-color--ab8179, #AB8179);
}

.ap760fb9g {
  stop-color: var(--svg-color--6d524e, #6D524E);
}

.aqjloibyk {
  d: path("M14.631 10.293c0-.289-.234-.481-.298-.54l-.288.28l.177.361z");
}

.azmrtxbft {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
}

.azt-9rbtm {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
}

.b2cidcc6s {
  d: path("M20.827 11.653a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.b576ppbxh {
  stop-color: var(--svg-color--8f5269, #8F5269);
}

.b6bhi65kx {
  fill-rule: evenodd;
  d: path("M14.896 23.68v2.47c0 .36-.29.65-.651.65h-.58v-.981h.25v-2.14z");
}

.bk_mrebvc {
  stop-color: var(--svg-color--554543, #554543);
}

.bkfqk3fbn {
  stop-color: var(--svg-color--4b2839, #4B2839);
}

.bmbim-qcd {
  stop-color: var(--svg-color--2c6dbd, #2C6DBD);
}

.bzptrm36o {
  d: path("M16.65 21.64c-.263.516-.263.942-.263 1.306v2.991c0 .17.208.26.327.13l4.818-4.96c.09-.09.09-.23.01-.32l-.753-.83a.23.23 0 0 1 .129-.38l.783-.14a.23.23 0 0 0 .188-.25l-.187-2.06a.25.25 0 0 0-.113-.185a10.5 10.5 0 0 0-2.426-1.135a.3.3 0 0 0-.04.08z");
}

.c_809kbzd {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M20.827 11.653a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.c-t0maccw {
  stop-color: var(--svg-color--ada5ab, #ADA5AB);
}

.c9e2npbbn {
  stop-color: var(--svg-color--efe1e3, #EFE1E3);
}

.cf3hk9c-f {
  stop-color: var(--svg-color--bdb0d0, #BDB0D0);
}

.cg1k0hirj {
  stop-color: var(--svg-color--8d645f, #8D645F);
}

.cgbm-4bwm {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.94 8.206c.322-.078 1.124-.039 1.66.345");
}

.ci16jsbol {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.dlt2kgbvz {
  stop-color: var(--svg-color--fcf9ff, #FCF9FF);
}

.dt7ct4boy {
  stop-color: var(--svg-color--9a7267, #9A7267);
}

.dxszyubmb {
  stop-color: var(--svg-color--d3cfda, #D3CFDA);
}

.e---z_byu {
  stop-color: var(--svg-color--ad9ec2, #AD9EC2);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e6fuuiw3e {
  stop-color: var(--svg-color--261943, #261943);
  stop-opacity: 0;
}

.ecm2ecc2d {
  stop-color: var(--svg-color--27141e, #27141E);
  stop-opacity: 0;
}

.ee3a7kppm {
  d: path("M15.985 18.669a2.1 2.1 0 0 1-2.1-2.1v-1.38h4.2v1.38a2.1 2.1 0 0 1-2.1 2.1");
}

.etbfcvxig {
  stop-color: var(--svg-color--b7a3cf, #B7A3CF);
}

.f6o95nb4t {
  fill: var(--svg-color--000, #000);
  d: path("M17.673 10.397c0-.284.227-.51.511-.51a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.236");
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

.f923khbrt {
  stop-color: var(--svg-color--46a4e7, #46A4E7);
  stop-opacity: 0;
}

.fa0q4x0wh {
  stop-color: var(--svg-color--8d5e67, #8D5E67);
  stop-opacity: 0;
}

.fchyrxbpw {
  d: path("M26.826 27.919c.01-1.75-.25-3.49-.77-5.16c-.56-1.8-1.58-3.37-2.9-4.59v11.78h3.65z");
}

.foe4l_bip {
  stop-color: var(--svg-color--edd8ce, #EDD8CE);
  stop-opacity: 0;
}

.fr_rdtj9g {
  stop-color: var(--svg-color--d4cae9, #D4CAE9);
}

.ft5dv1b6b {
  fill: none;
}

.fv5w29bdg {
  stop-color: var(--svg-color--261943, #261943);
}

.fx7jj2m3f {
  stop-color: var(--svg-color--edd8ce, #EDD8CE);
}

.fyxppic9g {
  stop-color: var(--svg-color--c0967a, #C0967A);
}

.fyy3crxae {
  stop-color: var(--svg-color--3e2125, #3E2125);
}

.g2m4aac5s {
  stop-color: var(--svg-color--6e5350, #6E5350);
}

.g440twb_j {
  d: path("M13.816 9.505a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.236a.9.9 0 0 0-.896-.892");
}

.gaydocc3b {
  stop-color: var(--svg-color--5c4643, #5C4643);
}

.gh6qe3bwt {
  d: path("M18.118 9.694c.064.085-.069.188-.22.301s-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.388-.05");
}

.goseu50zy {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m15.607 10.356l-.683 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.493-.376-.613 0");
}

.gto3tpbjl {
  stop-color: var(--svg-color--564544, #564544);
}

.gzrilbbya {
  stop-color: var(--svg-color--3a97db, #3A97DB);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h0xboubpx {
  d: path("M16.493 22.463c0-.04-.01-.203 0-.243l2.662-6.291c.01-.03.03-.06.04-.08c-1.01-.32-2.08-.49-3.18-.49c-1.11 0-2.19.18-3.21.5c.01.02.03.05.04.07l2.64 6.361c.01.03.055.05.055.09l.055 3.599h.01v3.97h.79v-3.97l.078-3.415z");
}

.h4zbx-g8y {
  stop-color: var(--svg-color--4c7bbf, #4C7BBF);
}

.hjp773b9j {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
}

.hl813wbpa {
  stop-color: var(--svg-color--945a73, #945A73);
}

.hm31m3bmo {
  stop-color: var(--svg-color--875f54, #875F54);
}

.hou90zp4m {
  stop-color: var(--svg-color--b2a6c6, #B2A6C6);
  stop-opacity: 0;
}

.hp2ou3bgv {
  stroke: var(--svg-color--6a5d85, #6A5D85);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M11.19 26.242h-1c-.09 0-.16-.07-.16-.16v-3.63a2.2 2.2 0 0 1 4.4 0v3.63c0 .09-.07.16-.16.16h-.93");
}

.hrqlkdbpd {
  stop-color: var(--svg-color--4b2839, #4B2839);
  stop-opacity: 0;
}

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.i4xusnb1i {
  stop-color: var(--svg-color--bdb2d2, #BDB2D2);
}

.ii82yjbfl {
  stop-color: var(--svg-color--604947, #604947);
}

.iqq-d2brk {
  stop-color: var(--svg-color--574379, #574379);
  stop-opacity: 0;
}

.iwuq58bbk {
  fill-rule: evenodd;
  d: path("M12.205 20.81c-.94 0-1.71.762-1.71 1.71v3.299h.67a.49.49 0 0 1 0 .98h-1a.65.65 0 0 1-.65-.65v-3.63a2.69 2.69 0 0 1 5.38 0v3.63c0 .361-.289.65-.65.65h-.93a.49.49 0 0 1 0-.98h.6v-3.3c0-.94-.762-1.71-1.71-1.71");
}

.izc7dk1pl {
  stop-color: var(--svg-color--ab8179, #AB8179);
  stop-opacity: 0;
}

.j_jb06m8v {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
}

.j-efl5b-c {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
  stop-opacity: 0;
}

.j0v18bclr {
  d: path("M19.675 26.129a.71.71 0 1 0 0-1.42a.71.71 0 0 0 0 1.42");
}

.j24wvbc2z {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M11.334 11.653a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j6tbtfb5n {
  stop-color: var(--svg-color--5f4846, #5F4846);
}

.je8_hbb1l {
  stop-color: var(--svg-color--49a3e2, #49A3E2);
}

.jjfnpib7f {
  d: path("M10.93 4.59c.567-.599 1.637-.6 2.132-.51l.396 1.29c-.253-.039-.296-.001-.486.183c-.137 1.093-1.376 1.757-2.886 2.198c-.148-1.492.109-2.38.845-3.16");
}

.jjvamgr7p {
  stop-color: var(--svg-color--815553, #815553);
}

.jlf3122ku {
  fill: var(--svg-color--432a28, #432A28);
  d: path("m12.602 8.801l-.004.002a.268.268 0 0 1-.276-.46h.002l.003-.002l.01-.006a2 2 0 0 1 .148-.076c.098-.047.239-.108.41-.162c.34-.109.815-.2 1.328-.11a.268.268 0 1 1-.093.529a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.434.18z");
}

.jo-m975mj {
  stop-color: var(--svg-color--27141e, #27141E);
}

.jvt5kfcji {
  d: path("M15.37 21.64c.263.516.263.942.263 1.306v2.991c0 .17-.209.26-.328.13l-4.817-4.96a.234.234 0 0 1-.01-.32l.753-.83c.119-.13.05-.35-.129-.38l-.783-.14a.23.23 0 0 1-.188-.25l.187-2.06a.25.25 0 0 1 .113-.185a10.5 10.5 0 0 1 2.426-1.135a.3.3 0 0 1 .04.08z");
}

.k1zv-ubmt {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
  stop-opacity: 0;
}

.k2sjcrc_g {
  stop-color: var(--svg-color--b7afc3, #B7AFC3);
}

.k3g0v3buh {
  stop-color: var(--svg-color--b1909e, #B1909E);
}

.k7ybb1bik {
  stop-color: var(--svg-color--6d5791, #6D5791);
}

.k8ni71bqd {
  stop-color: var(--svg-color--564544, #564544);
  stop-opacity: 0;
}

.ka5t_pbkm {
  stop-color: var(--svg-color--49a3e6, #49A3E6);
}

.kq5b787yl {
  stop-color: var(--svg-color--c0967a, #C0967A);
  stop-opacity: 0;
}

.ksj-40n4x {
  stop-color: var(--svg-color--230c14, #230C14);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.ktpt3tb_i {
  stop-color: var(--svg-color--56413d, #56413D);
  stop-opacity: 0;
}

.kv70nqbkg {
  stop-color: var(--svg-color--b49089, #B49089);
}

.kwpy16lwp {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.149 8.206c-.323-.078-1.125-.039-1.661.345");
}

.kzw1yxrkd {
  stop-color: var(--svg-color--d3d0d5, #D3D0D5);
}

.l--nyyiee {
  fill: var(--svg-color--2f2c32, #2F2C32);
  d: path("M17.142 10.01c.265-.467.669-.836 1.537-.836c.38 0 .747.106 1.073.369c.27.217.233.495.025.6l-.556.317c-.652-.21-1.373-.24-2.079-.45");
}

.l-etq6b9a {
  stop-color: var(--svg-color--bebac5, #BEBAC5);
}

.l54r-4bre {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.391 9.233c.653 0 1.205.45 1.355 1.06a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.272a1.4 1.4 0 0 1 1.371-1.128");
}

.l65mx1yct {
  stop-color: var(--svg-color--946568, #946568);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l93m1_oje {
  cx: 13.547px;
  cy: 9.886px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll7oxmbau {
  stop-color: var(--svg-color--3d9ad9, #3D9AD9);
  stop-opacity: 0;
}

.lnyefdcqm {
  stop-color: var(--svg-color--c8bfd6, #C8BFD6);
}

.lpc21p-wa {
  stop-color: var(--svg-color--553c83, #553C83);
}

.lr_95xbzv {
  d: path("M16.025 15.359h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.lwhsndh-i {
  stop-color: var(--svg-color--452531, #452531);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mi9_q0bii {
  fill: var(--svg-color--49302e, #49302E);
  d: path("M10.93 4.59c.567-.599 1.637-.6 2.132-.51l.396 1.29c-.253-.039-.296-.001-.486.183c-.137 1.093-1.376 1.757-2.886 2.198c-.148-1.492.109-2.38.845-3.16");
}

.moec6ccmu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.109 4.037c.023.243.234 1.157.544 1.71");
}

.ms2aglfku {
  fill: var(--svg-color--664a4a, #664A4A);
  d: path("m18.406 6.398l-1.425.262a.688.688 0 1 1-.125-1.365h2.34c1.385 0 1.843 1.396 1.9 1.872a3.15 3.15 0 0 0-2.69-.769");
}

.muarw1mje {
  stop-color: var(--svg-color--814e62, #814E62);
  stop-opacity: 0;
}

.n7ni7rtly {
  stop-color: var(--svg-color--e6ddf3, #E6DDF3);
}

.n95ebwv8k {
  d: path("M15.397 2.789c-1.133-.25-2.15.88-2.267 1.299c1.051 3.545 3.713 3.35 6.34 3.059c1.572-.175 1.743.542 1.877.888c0-3.933-3.344-4.671-5.922-5.24z");
}

.n9enpnncz {
  d: path("M11.314 12.188a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.nrx5bzr9s {
  stop-color: var(--svg-color--756a93, #756A93);
}

.nzzp07bei {
  stop-color: var(--svg-color--4f3438, #4F3438);
}

.o3tc-dnyn {
  stop-color: var(--svg-color--bebac5, #BEBAC5);
  stop-opacity: 0;
}

.o51x77z6i {
  fill: var(--svg-color--432a28, #432A28);
  fill-rule: evenodd;
  d: path("m19.732 8.343l-.138.23za.268.268 0 0 1-.275.46l-.005-.002a1 1 0 0 0-.113-.058a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 1 1-.093-.528c.513-.09.988 0 1.328.109a3.3 3.3 0 0 1 .559.238l.009.006z");
}

.o57gz703y {
  stop-color: var(--svg-color--554543, #554543);
  stop-opacity: 0;
}

.o5ryhdc_j {
  stop-color: var(--svg-color--5c4643, #5C4643);
  stop-opacity: 0;
}

.o7i1pebeu {
  fill-rule: evenodd;
  d: path("M15.935 15.07a3.24 3.24 0 0 0-3.24 3.239v2.15h-.98v-2.15a4.22 4.22 0 1 1 8.44 0v7.12h-.98v-7.12a3.24 3.24 0 0 0-3.24-3.24");
}

.o874sbcxz {
  stop-color: var(--svg-color--c4c3c3, #C4C3C3);
}

.oc1bwblbr {
  stop-color: var(--svg-color--b7a3cf, #B7A3CF);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.olrv_cchi {
  stop-color: var(--svg-color--361f1f, #361F1F);
}

.orqwrobrr {
  stop-color: var(--svg-color--7d5952, #7D5952);
}

.ox3481l0h {
  stop-color: var(--svg-color--c79980, #C79980);
}

.p13423bzd {
  stop-color: var(--svg-color--693b40, #693B40);
}

.p5_0bzbaz {
  stop-color: var(--svg-color--574379, #574379);
}

.pgy4y9bks {
  stop-color: var(--svg-color--3d9ad9, #3D9AD9);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pr6x_4-el {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.667 13.393a.2.2 0 0 0-.022-.25a.205.205 0 0 0-.247-.041c-.404.215-.88.339-1.398.339a3 3 0 0 1-1.398-.34a.204.204 0 0 0-.248.044a.196.196 0 0 0-.02.248m3.333 0l-.042-.028l.042.027Zm0 0a1.982 1.982 0 0 1-3.333 0m0 0l.041-.028m-.041.028l.041-.028m0 0a1.932 1.932 0 0 0 3.25 0c.088-.135-.063-.292-.203-.219c-.412.22-.896.345-1.422.345c-.52 0-1.01-.126-1.422-.345c-.14-.073-.291.089-.203.22Z");
}

.q3wk7p4fa {
  stop-color: var(--svg-color--c8b7de, #C8B7DE);
  stop-opacity: 0;
}

.q5hnu0byb {
  d: path("M18.979 10.28a.84.84 0 0 0-.231-.463l-.26.286l.117.228z");
}

.qakf2gbwa {
  d: path("M20.827 12.188a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.qh0bdqbav {
  stop-color: var(--svg-color--9a7267, #9A7267);
  stop-opacity: 0;
}

.qkj18_koj {
  stop-color: var(--svg-color--230c14, #230C14);
  stop-opacity: 0;
}

.qtky_3b3t {
  d: path("m21.893 20.104l-.732.13a.213.213 0 0 0-.12.352l.704.77a.216.216 0 0 1-.01.296L17.23 26.25c-.112.111-.306.037-.306-.12V22.8c0-.036.009-.064.018-.101l2.54-5.888a.15.15 0 0 1 .038-.065a9.7 9.7 0 0 1 2.364 1.122l.186 2.003a.214.214 0 0 1-.177.232");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r24zcwbvl {
  stop-color: var(--svg-color--b2a6c7, #B2A6C7);
  stop-opacity: 0;
}

.r4e237cot {
  stop-color: var(--svg-color--56413d, #56413D);
}

.r8b6tnb2b {
  d: path("M18.184 9.505a.892.892 0 0 1 .86 1.128H17.32a.896.896 0 0 1 .864-1.128");
}

.r9qw8z0np {
  stop-color: var(--svg-color--a298b4, #A298B4);
  stop-opacity: 0;
}

.rfbqtga6z {
  d: path("m5.926 22.72l-.03.08c-.52 1.65-.79 3.36-.79 5.09v2.06h3.67V18.2a10.56 10.56 0 0 0-2.85 4.52");
}

.rgo735bpi {
  d: path("M10.913 9.317h.012l-.01-.266l-.01-.306c.02-.949.574-1.316.81-1.438l.05-.02q.029-.014.052-.021a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.05a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.087 1.135 1.332l-.118 3.073c-.124 2.802-2.312 4.684-4.984 4.684c-2.671 0-4.86-1.882-4.983-4.684z");
}

.rhoewlwza {
  d: path("m15.618 10.218l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.377-.646-.377-.765 0");
}

.rl5jhib1q {
  stop-color: var(--svg-color--b3a299, #B3A299);
}

.rognhpd5x {
  stop-color: var(--svg-color--46a4e7, #46A4E7);
}

.rqdbjlbdw {
  stop-color: var(--svg-color--d1c0e3, #D1C0E3);
  stop-opacity: 0;
}

.ru9fl6bjc {
  stop-color: var(--svg-color--634945, #634945);
  stop-opacity: 0;
}

.rx5usmbog {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m15.618 10.218l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.377-.646-.377-.765 0");
}

.s7vootu_w {
  stop-color: var(--svg-color--b2a6c6, #B2A6C6);
}

.sbh0zqhft {
  fill: var(--svg-color--27232a, #27232A);
  d: path("M14.858 10.01c-.265-.467-.669-.836-1.537-.836c-.38 0-.747.106-1.073.369c-.269.217-.233.495-.025.6l.556.317c.652-.21 1.373-.24 2.079-.45");
}

.sjbdbzbts {
  stop-color: var(--svg-color--996c6e, #996C6E);
}

.skz637x0p {
  stop-color: var(--svg-color--aa98a1, #AA98A1);
}

.sm4v8rvoi {
  stop-color: var(--svg-color--d4ccdc, #D4CCDC);
}

.sp4_sibjj {
  stop-color: var(--svg-color--5d4f77, #5D4F77);
}

.sruu51y8f {
  stop-color: var(--svg-color--271b48, #271B48);
  stop-opacity: 0;
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.sugd91b_r {
  fill-rule: evenodd;
  d: path("M9.514 26.139v-2.47h.982v2.14h.249v.98h-.58c-.36 0-.65-.29-.65-.65");
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t68so1bro {
  stop-color: var(--svg-color--716687, #716687);
  stop-opacity: 0;
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

.tobrp8lrd {
  stop-color: var(--svg-color--604947, #604947);
  stop-opacity: 0;
}

.tulkzacvs {
  stop-color: var(--svg-color--6e5350, #6E5350);
  stop-opacity: 0;
}

.u3fmvdnwh {
  stop-color: var(--svg-color--25131c, #25131C);
}

.u6m78ac0i {
  stop-color: var(--svg-color--604138, #604138);
}

.u7ezkxzae {
  stop-color: var(--svg-color--5f4846, #5F4846);
  stop-opacity: 0;
}

.uiflfplei {
  fill: var(--svg-color--553836, #553836);
  d: path("M15.397 2.789c-1.133-.25-2.15.88-2.267 1.299c1.051 3.545 3.713 3.35 6.34 3.059c1.572-.175 1.743.542 1.877.888c0-3.933-3.344-4.671-5.922-5.24z");
}

.ukea7pdhy {
  stop-color: var(--svg-color--442534, #442534);
  stop-opacity: 0;
}

.uotx2eifv {
  fill-rule: evenodd;
  d: path("M23.185 11.989a3.24 3.24 0 0 0 .324-1.427c0-.468-.096-.906-.268-1.306h.005a3 3 0 0 0-.281-.513l-.002-.003a3.24 3.24 0 0 1-.527-1.77v-.011a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.232A3.3 3.3 0 0 0 16 2.051a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.455.233h-.085a3.3 3.3 0 0 0-3.214 3.3v.01a3.24 3.24 0 0 1-.527 1.771l-.002.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455c-.203.425-.324.9-.324 1.407a3.213 3.213 0 0 0 3.218 3.218h8.582a3.213 3.213 0 0 0 3.218-3.218c0-.506-.121-.982-.324-1.407a.51.51 0 0 1 0-.455m-12.26-2.673h-.012l1.198 2.356c.124 2.802 1.217 0 3.889 0s3.836 3.12 3.96.317l1.136-3.197c-.054-1.245-.956-1.333-1.136-1.333h-3.22a3.86 3.86 0 0 1-3.19-1.673a.264.264 0 0 0-.461.051l-.082.194a2.3 2.3 0 0 1-1.292 1.275c-.236.123-.79.49-.81 1.439l.01.306z");
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.uwchitapr {
  stop-color: var(--svg-color--cbc5cf, #CBC5CF);
}

.v2gep8uzg {
  stop-color: var(--svg-color--a298b4, #A298B4);
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.v5m4qhb2r {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

.v717bwb7u {
  stop-color: var(--svg-color--b7afc3, #B7AFC3);
  stop-opacity: 0;
}

.v769b-w_v {
  fill: var(--svg-color--a49ea5, #A49EA5);
  d: path("m10.207 20.104l.732.13a.213.213 0 0 1 .12.352l-.704.77a.216.216 0 0 0 .01.296l4.505 4.599c.112.111.306.037.306-.12V22.8c0-.036-.01-.064-.018-.101l-2.54-5.888a.15.15 0 0 0-.038-.065a9.7 9.7 0 0 0-2.364 1.122l-.186 2.003a.214.214 0 0 0 .177.232");
}

.vfgk4hb_x {
  stop-color: var(--svg-color--764c51, #764C51);
}

.vgwmt2-9g {
  stop-color: var(--svg-color--b2a6c7, #B2A6C7);
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

.viff9wbjp {
  stop-color: var(--svg-color--716687, #716687);
}

.vw42v6b3v {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

.vxx0ssbsk {
  stop-color: var(--svg-color--c8b7de, #C8B7DE);
}

.w_gx_6l5c {
  stop-color: var(--svg-color--271b48, #271B48);
}

.w-_6jxb_z {
  stop-color: var(--svg-color--efeafb, #EFEAFB);
}

.w0rhj52ia {
  stop-color: var(--svg-color--ada5ab, #ADA5AB);
  stop-opacity: 0;
}

.w1etxcbdz {
  stop-color: var(--svg-color--2c1c24, #2C1C24);
}

.w23khihlj {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.118 9.694c.064.085-.069.188-.22.301s-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.388-.05");
}

.w2k7zib9b {
  fill: var(--svg-color--564a7b, #564A7B);
  fill-rule: evenodd;
  d: path("M15.935 15.07a3.24 3.24 0 0 0-3.24 3.239v2.15h-.98v-2.15a4.22 4.22 0 1 1 8.44 0v7.12h-.98v-7.12a3.24 3.24 0 0 0-3.24-3.24");
}

.w4wkyodwa {
  stop-color: var(--svg-color--6c4640, #6C4640);
}

.w5re42dqy {
  stop-color: var(--svg-color--6c4640, #6C4640);
  stop-opacity: 0;
}

.w9gpkna4y {
  stop-color: var(--svg-color--261326, #261326);
}

.wh0vrhbzi {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

.wlzou1bho {
  stop-color: var(--svg-color--814e62, #814E62);
}

.wmqo90blr {
  d: path("M11.334 11.653a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.wuqjd3b5z {
  stop-color: var(--svg-color--442534, #442534);
}

.wxe5vubnr {
  stop-color: var(--svg-color--dad1e4, #DAD1E4);
  stop-opacity: 0;
}

.wzlj6ub9j {
  cx: 13.547px;
  cy: 9.886px;
  rx: 0.39px;
  ry: 0.197px;
}

.x3e-lhbqh {
  stop-color: var(--svg-color--d4ccdc, #D4CCDC);
  stop-opacity: 0;
}

.x7431zb1g {
  stop-color: var(--svg-color--3e2125, #3E2125);
  stop-opacity: 0;
}

.x7yaztbkk {
  stop-color: var(--svg-color--b3a299, #B3A299);
  stop-opacity: 0;
}

.xag1knb5p {
  stop-color: var(--svg-color--bdb1ad, #BDB1AD);
  stop-opacity: 0;
}

.xicv_p3ce {
  d: path("M16.355 15.359c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.xmdmj-dwi {
  stop-color: var(--svg-color--746992, #746992);
  stop-opacity: 0;
}

.xoshv8bzu {
  stop-color: var(--svg-color--fdf6f9, #FDF6F9);
}

.xqzyuky4n {
  stop-color: var(--svg-color--b28279, #B28279);
}

.xs9vt_bzp {
  stop-color: var(--svg-color--815553, #815553);
  stop-opacity: 0;
}

.xvq3mubqy {
  stop-color: var(--svg-color--261326, #261326);
  stop-opacity: 0;
}

.y2rlftbia {
  stop-color: var(--svg-color--ded4e6, #DED4E6);
  stop-opacity: 0;
}

.y319mjb9d {
  d: path("M15.986 15.359c-2.74 0-5.3 1.06-7.21 2.84v11.75h14.38v-11.78a10.54 10.54 0 0 0-7.17-2.81");
}

.y3gk9pbvh {
  stop-color: var(--svg-color--634945, #634945);
}

.y58nhpnsg {
  stop-color: var(--svg-color--2b86dd, #2B86DD);
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.yqete2_ye {
  stop-color: var(--svg-color--c4c3c3, #C4C3C3);
  stop-opacity: 0;
}

.ysga7wb0w {
  stop-color: var(--svg-color--25131c, #25131C);
  stop-opacity: 0;
}

.yuhux9lbj {
  fill: var(--svg-color--afa3c5, #AFA3C5);
  d: path("M18.844 26.908a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.ywx3jq9xy {
  stop-color: var(--svg-color--3e2672, #3E2672);
}

.zemyxxbjg {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
}

.zfvylccst {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.609 9.233c-.653 0-1.205.45-1.355 1.06c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.371-1.128");
}

.zhcbbgubg {
  fill: var(--svg-color--000, #000);
  d: path("M14.327 10.397a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.236");
}

</style>
