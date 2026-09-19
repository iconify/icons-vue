<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#svgIDa)" transform="rotate(-23.31 19.316 9.154)" class="yh97ver0s"/><path fill="url(#svgIDb)" class="ht_71mb8b"/><path fill="url(#svgIDc)" class="e53sx1y3l"/><g filter="url(#svgIDd)"><path fill="url(#svgIDe)" class="e1g-j13cf"/><path fill="url(#svgIDf)" class="e1g-j13cf"/><path fill="url(#svgIDg)" class="e1g-j13cf"/><path fill="url(#svgIDh)" class="e1g-j13cf"/></g><g filter="url(#svgIDi)"><path fill="url(#svgIDj)" class="uh458k7zv"/><path fill="url(#svgIDk)" class="uh458k7zv"/><path fill="url(#svgIDl)" class="uh458k7zv"/><path fill="url(#svgIDm)" class="uh458k7zv"/></g><path fill="url(#svgIDn)" class="txw7mlbhv"/><path fill="url(#svgIDo)" class="txw7mlbhv"/><path class="kmghwmbgk"/><path fill="url(#svgIDp)" class="x7jby2bwc"/><path fill="url(#svgIDq)" class="zh8wx3bjm"/><ellipse fill="url(#svgIDr)" transform="rotate(24.61 18.034 7.092)" class="lxkzcy4gl"/><g filter="url(#svgIDs)"><path fill="url(#svgIDt)" class="o8vu0vmqg"/></g><path fill="url(#svgIDu)" clip-rule="evenodd" class="pmld2ob6g"/><path fill="url(#svgIDv)" clip-rule="evenodd" class="pmld2ob6g"/><path fill="url(#svgIDw)" clip-rule="evenodd" class="pmld2ob6g"/><path fill="url(#svgIDx)" clip-rule="evenodd" class="g9j5kob3s"/><path fill="url(#svgIDy)" clip-rule="evenodd" class="g9j5kob3s"/><circle fill="url(#svgIDz)" transform="matrix(-1 0 0 1 21.004 7.75)" class="ms4f1oj7g"/><circle fill="url(#svgIDA)" transform="matrix(-1 0 0 1 21.004 7.75)" class="ms4f1oj7g"/><circle fill="url(#svgIDB)" transform="matrix(-1 0 0 1 21.004 7.75)" class="ms4f1oj7g"/><g filter="url(#svgIDC)"><rect transform="matrix(-1 0 0 1 19.05 6.5)" class="i2k7fbb6p"/></g><path class="ln8ibjxtc"/><path fill="url(#svgIDD)" transform="scale(-1 1) rotate(-23.31 15.848 35.324)" class="dm4voe-la"/><path fill="url(#svgIDE)" class="onwu39rgv"/><g filter="url(#svgIDF)"><path class="xsj4wobsw"/></g><g filter="url(#svgIDG)"><path class="qz9j3ivdd"/><path fill="url(#svgIDH)" class="u4ygu_vhg"/></g><path fill="url(#svgIDI)" class="yvrc9xbpg"/><path fill="url(#svgIDJ)" class="yvrc9xbpg"/><path fill="url(#svgIDK)" class="yvrc9xbpg"/><path fill="url(#svgIDL)" class="ziwjwlzyo"/><path fill="url(#svgIDM)" class="ziwjwlzyo"/><path fill="url(#svgIDN)" class="ziwjwlzyo"/><g filter="url(#svgIDO)"><path class="mm65sim_f"/></g><g filter="url(#svgIDP)"><path class="l0-a8nb2d"/></g><g filter="url(#svgIDQ)"><path class="c8s0qablf"/><path fill="url(#svgIDR)" class="p8z6xcc_e"/></g><path fill="url(#svgIDS)" class="gxf7turxa"/><path fill="url(#svgIDT)" class="gxf7turxa"/><g filter="url(#svgIDU)"><path class="lqg5yzb2a"/><path fill="url(#svgIDV)" class="c_c7q3ixi"/><path fill="url(#svgIDW)" class="c_c7q3ixi"/><path fill="url(#svgIDX)" class="c_c7q3ixi"/></g><g filter="url(#svgIDY)"><path class="x9fqyvbmj"/></g><g filter="url(#svgIDZ)"><path class="q2354_btu"/><path fill="url(#svgIDaa)" class="ikr-5kk0l"/><path fill="url(#svgIDab)" class="ikr-5kk0l"/><path fill="url(#svgIDac)" class="ikr-5kk0l"/></g><g filter="url(#svgIDad)"><path fill="url(#svgIDae)" class="hoilpz9zm"/></g><g filter="url(#svgIDaf)"><rect stroke="url(#svgIDag)" transform="rotate(45 8.633 10.132)" class="efhi-0e0h"/></g><rect fill="url(#svgIDah)" transform="rotate(45 8.633 10.132)" class="er7ggnzmt"/><rect fill="url(#svgIDai)" transform="rotate(45 8.633 10.132)" class="er7ggnzmt"/><g filter="url(#svgIDaj)"><path clip-rule="evenodd" class="n1q06yb7u"/></g><path clip-rule="evenodd" class="zns8kxbgp"/><path fill="url(#svgIDak)" clip-rule="evenodd" class="ehqrbmxde"/><path clip-rule="evenodd" class="ngzjmvbel"/><path fill="url(#svgIDal)" clip-rule="evenodd" class="bmsj66cvh"/><path clip-rule="evenodd" class="n7442l93h"/><path fill="url(#svgIDam)" clip-rule="evenodd" class="udoy8tq9u"/><path clip-rule="evenodd" class="jp-rsubez"/><path fill="url(#svgIDan)" clip-rule="evenodd" class="a_ejh2oyx"/><path clip-rule="evenodd" class="s4vz1uxal"/><path fill="url(#svgIDao)" clip-rule="evenodd" class="cg4q2vjsj"/><path fill="url(#svgIDap)" clip-rule="evenodd" class="oy9gm987l"/><path fill="url(#svgIDaq)" clip-rule="evenodd" class="oy9gm987l"/><path fill="url(#svgIDar)" clip-rule="evenodd" class="oy9gm987l"/><rect transform="rotate(-28.166 17.093 15.807)" class="spqa7jbew"/><path fill="url(#svgIDas)" class="uwkao-znc"/><path fill="url(#svgIDat)" class="uwkao-znc"/><path fill="url(#svgIDau)" class="uwkao-znc"/><path fill="url(#svgIDav)" class="om8b18tot"/><path fill="url(#svgIDaw)" class="om8b18tot"/><path fill="url(#svgIDax)" class="om8b18tot"/><g filter="url(#svgIDay)"><path class="r3b5-4bfz"/></g><g filter="url(#svgIDaz)"><path class="ay-2-kl5u"/></g><g filter="url(#svgIDaA)"><path class="xanj4emtj"/><path fill="url(#svgIDaB)" class="q5daohbyq"/></g><path fill="url(#svgIDaC)" class="kxgqu6reh"/><path fill="url(#svgIDaD)" class="kxgqu6reh"/><g filter="url(#svgIDaE)"><path class="e4pbfdbxe"/><path fill="url(#svgIDaF)" class="fjfalibmt"/><path fill="url(#svgIDaG)" class="fjfalibmt"/><path fill="url(#svgIDaH)" class="fjfalibmt"/></g><g filter="url(#svgIDaI)"><path class="ppc2prvwk"/></g><g filter="url(#svgIDaJ)"><path class="t683yih5k"/><path fill="url(#svgIDaK)" class="phx-vgmut"/><path fill="url(#svgIDaL)" class="phx-vgmut"/><path fill="url(#svgIDaM)" class="phx-vgmut"/></g><g filter="url(#svgIDaN)"><path fill="url(#svgIDaO)" class="vw65-prir"/></g><g filter="url(#svgIDaP)"><rect stroke="url(#svgIDaQ)" transform="scale(-1 1) rotate(45 -23.896 -23.149)" class="gg2ehgbth"/></g><rect fill="url(#svgIDaR)" transform="scale(-1 1) rotate(45 -23.896 -23.149)" class="pxj138bcc"/><rect fill="url(#svgIDaS)" transform="scale(-1 1) rotate(45 -23.896 -23.149)" class="pxj138bcc"/><path clip-rule="evenodd" class="dbdhg7bmt"/><path fill="url(#svgIDaT)" clip-rule="evenodd" class="ithzpjn2t"/><path fill="url(#svgIDaU)" class="icmqrjb0b"/><path fill="url(#svgIDaV)" class="icmqrjb0b"/><path class="e17muc3id"/><path fill="url(#svgIDaW)" class="rr-6_qbjy"/><path fill="url(#svgIDaX)" class="rr-6_qbjy"/><path fill="url(#svgIDaY)" class="gvsjiqbgx"/><path fill="url(#svgIDaZ)" class="gvsjiqbgx"/><path class="f7kd4ybpw"/><path fill="url(#svgIDba)" class="io95kkawv"/><g filter="url(#svgIDbb)"><path fill="url(#svgIDbc)" class="de_eaubsl"/><path fill="url(#svgIDbd)" class="de_eaubsl"/><path fill="url(#svgIDbe)" class="de_eaubsl"/><path fill="url(#svgIDbf)" class="de_eaubsl"/></g><g filter="url(#svgIDbg)"><path fill="url(#svgIDbh)" class="w4xvl2bcn"/><path fill="url(#svgIDbi)" class="w4xvl2bcn"/><path fill="url(#svgIDbj)" class="w4xvl2bcn"/><path fill="url(#svgIDbk)" class="w4xvl2bcn"/></g><path fill="url(#svgIDbl)" class="n-_owbcrt"/><path fill="url(#svgIDbm)" class="n-_owbcrt"/><path class="z01wqtbit"/><path fill="url(#svgIDbn)" class="j8zkl2bkx"/><path fill="url(#svgIDbo)" class="l74ely9dg"/><ellipse fill="url(#svgIDbp)" transform="scale(-1 1) rotate(24.61 -23.24 -28.467)" class="f6mg5tnmy"/><g filter="url(#svgIDbq)"><path fill="url(#svgIDbr)" class="j98nf06iw"/></g><path fill="url(#svgIDbs)" clip-rule="evenodd" class="t7s0hbcft"/><path fill="url(#svgIDbt)" clip-rule="evenodd" class="t7s0hbcft"/><path fill="url(#svgIDbu)" clip-rule="evenodd" class="t7s0hbcft"/><path fill="url(#svgIDbv)" clip-rule="evenodd" class="sylpfbbmy"/><path fill="url(#svgIDbw)" clip-rule="evenodd" class="sylpfbbmy"/><circle fill="url(#svgIDbx)" class="n3rn3i52e"/><circle fill="url(#svgIDby)" class="n3rn3i52e"/><circle fill="url(#svgIDbz)" class="n3rn3i52e"/><g filter="url(#svgIDbA)"><rect class="w1isstbai"/></g><path class="r91r1xbti"/><g filter="url(#svgIDbB)"><path class="z4x_sbopl"/></g><g filter="url(#svgIDbC)"><path stroke="url(#svgIDbD)" class="v6badmbjw"/></g><g filter="url(#svgIDbE)"><path fill="url(#svgIDbF)" class="sh3-zfb6o"/></g><defs><radialGradient id="svgIDa" cx="0" cy="0" r="1" gradientTransform="matrix(1.38633 1.36295 -2.28073 2.31985 19.282 10.605)" gradientUnits="userSpaceOnUse"><stop class="dt9uc6s1j"/><stop offset=".919" class="lub5dyb4n"/></radialGradient><radialGradient id="svgIDb" cx="0" cy="0" r="1" gradientTransform="matrix(-.49331 1.0236 -1.6646 -.80223 21.047 7.193)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="bervkqbmz"/><stop offset="1" class="c479w-bpn"/></radialGradient><radialGradient id="svgIDc" cx="0" cy="0" r="1" gradientTransform="matrix(.52071 .2817 -.39763 .735 16.728 8.14)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="ss7zei8xw"/><stop offset=".684" class="d4kn2qv1f"/></radialGradient><radialGradient id="svgIDf" cx="0" cy="0" r="1" gradientTransform="matrix(-.92192 -.05122 .06245 -1.124 20.73 7.372)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="cm3jz64eh"/><stop offset="1" class="lu7jcxbxj"/></radialGradient><radialGradient id="svgIDg" cx="0" cy="0" r="1" gradientTransform="rotate(68.109 5.855 16.935) scale(3.85553 1.76708)" gradientUnits="userSpaceOnUse"><stop class="hrqvsac6m"/><stop offset="1" class="fblnbo7cb"/></radialGradient><radialGradient id="svgIDh" cx="0" cy="0" r="1" gradientTransform="matrix(0 .42681 -.66563 0 18.47 7.423)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="o5l8xobeq"/><stop offset="1" class="plhowgx4z"/></radialGradient><radialGradient id="svgIDj" cx="0" cy="0" r="1" gradientTransform="matrix(2.62985 -2.1284 3.23555 3.99785 19.805 6.327)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="nqgqms1jm"/><stop offset="1" class="w55-gkb2p"/></radialGradient><radialGradient id="svgIDk" cx="0" cy="0" r="1" gradientTransform="matrix(1.31165 -.95606 1.53813 2.1102 17.328 4.674)" gradientUnits="userSpaceOnUse"><stop class="khzpeo26k"/><stop offset="1" class="xktf9pbat"/></radialGradient><radialGradient id="svgIDl" cx="0" cy="0" r="1" gradientTransform="matrix(-.57193 .16217 -.07968 -.28101 22.61 8.328)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="jiuqa9mgc"/><stop offset="1" class="wyd1xpdro"/></radialGradient><radialGradient id="svgIDm" cx="0" cy="0" r="1" gradientTransform="matrix(.97314 -.23048 .61754 2.6074 20.492 6.706)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="dzmi4fing"/><stop offset=".584" class="plkel1bga"/></radialGradient><radialGradient id="svgIDn" cx="0" cy="0" r="1" gradientTransform="matrix(.79387 -.23048 .1125 .38748 20.484 7.244)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="o1rzobcjq"/><stop offset="1" class="v23x_cgsr"/></radialGradient><radialGradient id="svgIDp" cx="0" cy="0" r="1" gradientTransform="matrix(.29908 0 0 .58108 18.148 7.453)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="svgIDq" cx="0" cy="0" r="1" gradientTransform="matrix(.27345 0 0 .59176 17.964 7.477)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="svgIDv" cx="0" cy="0" r="1" gradientTransform="rotate(165.735 10.066 4.356) scale(.2378 2.46193)" gradientUnits="userSpaceOnUse"><stop class="a5dbyd6tf"/><stop offset="1" class="on8sxx3yx"/></radialGradient><radialGradient id="svgIDw" cx="0" cy="0" r="1" gradientTransform="matrix(.52148 1.82813 -.23787 .06785 19.851 4.36)" gradientUnits="userSpaceOnUse"><stop class="ak32k0b7k"/><stop offset="1" class="rknzqr02l"/></radialGradient><radialGradient id="svgIDy" cx="0" cy="0" r="1" gradientTransform="matrix(.35156 .1875 -.70185 1.31597 20.015 9.375)" gradientUnits="userSpaceOnUse"><stop class="kgukkhbth"/><stop offset="1" class="k8s01tfdv"/></radialGradient><radialGradient id="svgIDz" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03124 1.09376 -.96833 -1.7983 2.316 .797)" gradientUnits="userSpaceOnUse"><stop class="zjmmjyoar"/><stop offset="1" class="shic-ydjf"/></radialGradient><radialGradient id="svgIDA" cx="0" cy="0" r="1" gradientTransform="matrix(.76953 0 0 1.98438 0 1.281)" gradientUnits="userSpaceOnUse"><stop class="a0q036gjd"/><stop offset="1" class="q2gydu3zd"/></radialGradient><radialGradient id="svgIDB" cx="0" cy="0" r="1" gradientTransform="matrix(-.76563 -.64062 1.04002 -1.24297 2.348 2.172)" gradientUnits="userSpaceOnUse"><stop class="fk4zrip8m"/><stop offset="1" class="jv-vvdc2h"/></radialGradient><radialGradient id="svgIDD" cx="0" cy="0" r="1" gradientTransform="matrix(1.38633 1.36295 -2.28073 2.31985 -.033 1.45)" gradientUnits="userSpaceOnUse"><stop class="dt9uc6s1j"/><stop offset=".919" class="lub5dyb4n"/></radialGradient><radialGradient id="svgIDE" cx="0" cy="0" r="1" gradientTransform="matrix(.4933 1.02361 -1.6646 .80222 10.953 7.193)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="bervkqbmz"/><stop offset="1" class="c479w-bpn"/></radialGradient><radialGradient id="svgIDH" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71095 2.35327 -5.20382 -5.99476 18.899 10.867)" gradientUnits="userSpaceOnUse"><stop class="eu764gb8n"/><stop offset="1" class="id2qh1bcz"/></radialGradient><radialGradient id="svgIDI" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.96875 1.8125 0 11.656 25.484)" gradientUnits="userSpaceOnUse"><stop class="lshdlpbel"/><stop offset="1" class="d894rgb9r"/></radialGradient><radialGradient id="svgIDJ" cx="0" cy="0" r="1" gradientTransform="matrix(2.14185 1.875 -.94292 1.07712 7.39 20.453)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="ruodvgjtp"/><stop offset="1" class="bpaul1b8u"/></radialGradient><radialGradient id="svgIDK" cx="0" cy="0" r="1" gradientTransform="rotate(144.26 2.246 11.065) scale(1.23051 3.4979)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="gm3gtoamf"/><stop offset="1" class="uj8od9jgc"/></radialGradient><radialGradient id="svgIDR" cx="0" cy="0" r="1" gradientTransform="rotate(-134.195 7.082 8.047) scale(2.212 .64075)" gradientUnits="userSpaceOnUse"><stop class="jjhblb54u"/><stop offset="1" class="bq0pg0bco"/></radialGradient><radialGradient id="svgIDS" cx="0" cy="0" r="1" gradientTransform="rotate(137.394 1.48 9.788) scale(7.8608 1.6626)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="t4m41vbgx"/><stop offset="1" class="hi6yszbkt"/></radialGradient><radialGradient id="svgIDT" cx="0" cy="0" r="1" gradientTransform="matrix(6.96877 -7.18752 5.67939 5.50654 3.781 17.766)" gradientUnits="userSpaceOnUse"><stop offset=".93" class="qpejwlb8n"/><stop offset="1" class="p4686vbiy"/></radialGradient><radialGradient id="svgIDW" cx="0" cy="0" r="1" gradientTransform="rotate(-144.397 8.17 13.096) scale(2.17397 2.91043)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="svgIDab" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64636 -1.26563 1.72963 -2.24994 14.356 28.492)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="svgIDae" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.82813 .85156 0 11.203 26.313)" gradientUnits="userSpaceOnUse"><stop class="nb7sh9bzw"/><stop offset="1" class="l6veklvwf"/></radialGradient><radialGradient id="svgIDah" cx="0" cy="0" r="1" gradientTransform="matrix(-.05524 1.73462 -1.20171 -.03827 10.37 11.411)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="d983fmb_q"/><stop offset="1" class="ojg463bev"/></radialGradient><radialGradient id="svgIDai" cx="0" cy="0" r="1" gradientTransform="matrix(1.49 1.66988 -.81478 .72701 11.379 13.254)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="lff7xxwjk"/><stop offset="1" class="us6-yfb3g"/></radialGradient><radialGradient id="svgIDak" cx="0" cy="0" r="1" gradientTransform="rotate(137.121 3.029 10.198) scale(3.58218 11.0839)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="fi5356bnb"/><stop offset=".963" class="jez0q5b5i"/></radialGradient><radialGradient id="svgIDal" cx="0" cy="0" r="1" gradientTransform="matrix(-.34046 .87888 -2.8453 -1.1022 14.442 18.629)" gradientUnits="userSpaceOnUse"><stop offset=".369" class="r_4d04xgj"/><stop offset="1" class="dyzk46b7s"/></radialGradient><radialGradient id="svgIDam" cx="0" cy="0" r="1" gradientTransform="matrix(-.30444 .89737 -2.62413 -.89026 14.56 19.166)" gradientUnits="userSpaceOnUse"><stop offset=".369" class="r_4d04xgj"/><stop offset="1" class="dyzk46b7s"/></radialGradient><radialGradient id="svgIDan" cx="0" cy="0" r="1" gradientTransform="matrix(-.28295 .92188 -2.48547 -.76287 14.252 19.485)" gradientUnits="userSpaceOnUse"><stop offset=".369" class="r_4d04xgj"/><stop offset="1" class="dyzk46b7s"/></radialGradient><radialGradient id="svgIDap" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37499 1.625 -1.79466 -1.51854 29.313 10.578)" gradientUnits="userSpaceOnUse"><stop class="f8i1cfbfs"/><stop offset="1" class="e48lyqzlo"/></radialGradient><radialGradient id="svgIDaq" cx="0" cy="0" r="1" gradientTransform="matrix(2.12183 -1.33219 1.13322 1.80492 26.394 12.785)" gradientUnits="userSpaceOnUse"><stop offset=".319" class="bn37hgbti"/><stop offset="1" class="zhc3hbcwf"/></radialGradient><radialGradient id="svgIDas" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.96875 1.8125 0 20.343 25.469)" gradientUnits="userSpaceOnUse"><stop class="lshdlpbel"/><stop offset="1" class="d894rgb9r"/></radialGradient><radialGradient id="svgIDat" cx="0" cy="0" r="1" gradientTransform="matrix(-2.14186 1.87499 -.94291 -1.07712 24.61 20.438)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="ruodvgjtp"/><stop offset="1" class="bpaul1b8u"/></radialGradient><radialGradient id="svgIDau" cx="0" cy="0" r="1" gradientTransform="matrix(.99878 .71875 -2.04315 2.83916 21.468 18.719)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="gm3gtoamf"/><stop offset="1" class="uj8od9jgc"/></radialGradient><radialGradient id="svgIDaB" cx="0" cy="0" r="1" gradientTransform="matrix(1.542 -1.58594 .4594 .44667 25.75 18.719)" gradientUnits="userSpaceOnUse"><stop class="jjhblb54u"/><stop offset="1" class="bq0pg0bco"/></radialGradient><radialGradient id="svgIDaC" cx="0" cy="0" r="1" gradientTransform="matrix(5.78575 5.3214 -1.1255 1.22372 22.803 15.973)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="t4m41vbgx"/><stop offset="1" class="hi6yszbkt"/></radialGradient><radialGradient id="svgIDaD" cx="0" cy="0" r="1" gradientTransform="matrix(-6.9688 -7.18748 5.67936 -5.50657 28.218 17.75)" gradientUnits="userSpaceOnUse"><stop offset=".014" class="qpejwlb8n"/><stop offset=".93" class="qpejwlb8n"/><stop offset="1" class="p4686vbiy"/></radialGradient><radialGradient id="svgIDaG" cx="0" cy="0" r="1" gradientTransform="matrix(1.76758 -1.26563 1.69437 2.36637 24.81 28.484)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="svgIDaL" cx="0" cy="0" r="1" gradientTransform="matrix(1.64636 -1.26562 1.72962 2.24995 17.644 28.477)" gradientUnits="userSpaceOnUse"><stop class="ct6_m01bp"/><stop offset="1" class="hh9ibwbje"/></radialGradient><radialGradient id="svgIDaO" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.82813 .85156 0 20.797 26.297)" gradientUnits="userSpaceOnUse"><stop class="nb7sh9bzw"/><stop offset="1" class="l6veklvwf"/></radialGradient><radialGradient id="svgIDaR" cx="0" cy="0" r="1" gradientTransform="matrix(2.16552 .08839 -.06123 1.50022 .395 2.467)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="d983fmb_q"/><stop offset="1" class="ojg463bev"/></radialGradient><radialGradient id="svgIDaS" cx="0" cy="0" r="1" gradientTransform="matrix(1.49 1.66988 -.81478 .72701 2.746 3.121)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="lff7xxwjk"/><stop offset="1" class="us6-yfb3g"/></radialGradient><radialGradient id="svgIDaT" cx="0" cy="0" r="1" gradientTransform="matrix(1.49685 3.75 -10.37919 4.14298 19.25 14.39)" gradientUnits="userSpaceOnUse"><stop offset=".368" class="lqt0qlbse"/><stop offset=".969" class="oqr0o-bmo"/></radialGradient><radialGradient id="svgIDaV" cx="0" cy="0" r="1" gradientTransform="matrix(-2.00452 .04153 -.0243 -1.17307 17.327 16.903)" gradientUnits="userSpaceOnUse"><stop offset=".744" class="lkpmwzkfe"/><stop offset="1" class="av9qa9bga"/></radialGradient><radialGradient id="svgIDaX" cx="0" cy="0" r="1" gradientTransform="matrix(0 .49784 -1.34351 0 16.64 17.783)" gradientUnits="userSpaceOnUse"><stop class="g2g8iabmv"/><stop offset="1" class="oas8dfb-p"/></radialGradient><radialGradient id="svgIDaZ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9726 .04153 -.0247 -1.17306 17.336 17.53)" gradientUnits="userSpaceOnUse"><stop offset=".744" class="lkpmwzkfe"/><stop offset="1" class="av9qa9bga"/></radialGradient><radialGradient id="svgIDba" cx="0" cy="0" r="1" gradientTransform="matrix(-.52071 .2817 -.39763 -.735 15.272 8.14)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="ss7zei8xw"/><stop offset=".684" class="d4kn2qv1f"/></radialGradient><radialGradient id="svgIDbd" cx="0" cy="0" r="1" gradientTransform="matrix(.92192 -.05122 .06244 1.124 11.27 7.372)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="cm3jz64eh"/><stop offset="1" class="lu7jcxbxj"/></radialGradient><radialGradient id="svgIDbe" cx="0" cy="0" r="1" gradientTransform="rotate(111.891 4.553 6.857) scale(3.85553 1.76708)" gradientUnits="userSpaceOnUse"><stop class="hrqvsac6m"/><stop offset="1" class="fblnbo7cb"/></radialGradient><radialGradient id="svgIDbf" cx="0" cy="0" r="1" gradientTransform="matrix(0 .42681 -.66563 0 13.53 7.423)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="o5l8xobeq"/><stop offset="1" class="plhowgx4z"/></radialGradient><radialGradient id="svgIDbh" cx="0" cy="0" r="1" gradientTransform="matrix(-2.62985 -2.1284 3.23555 -3.99785 12.195 6.327)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="nqgqms1jm"/><stop offset="1" class="w55-gkb2p"/></radialGradient><radialGradient id="svgIDbi" cx="0" cy="0" r="1" gradientTransform="matrix(-1.31166 -.95606 1.53811 -2.11021 14.672 4.674)" gradientUnits="userSpaceOnUse"><stop class="khzpeo26k"/><stop offset="1" class="xktf9pbat"/></radialGradient><radialGradient id="svgIDbj" cx="0" cy="0" r="1" gradientTransform="matrix(.57193 .16219 -.07969 .28101 9.39 8.328)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="jiuqa9mgc"/><stop offset="1" class="wyd1xpdro"/></radialGradient><radialGradient id="svgIDbk" cx="0" cy="0" r="1" gradientTransform="rotate(-166.675 6.145 2.68) scale(1.00006 2.67953)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="dzmi4fing"/><stop offset=".584" class="plkel1bga"/></radialGradient><radialGradient id="svgIDbl" cx="0" cy="0" r="1" gradientTransform="matrix(-.79387 -.23048 .1125 -.38748 11.516 7.244)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="o1rzobcjq"/><stop offset="1" class="v23x_cgsr"/></radialGradient><radialGradient id="svgIDbn" cx="0" cy="0" r="1" gradientTransform="matrix(-.29908 0 0 -.58108 13.852 7.453)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="svgIDbo" cx="0" cy="0" r="1" gradientTransform="matrix(-.27345 0 0 -.59176 14.036 7.477)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="svgIDbt" cx="0" cy="0" r="1" gradientTransform="matrix(.23047 .0586 -.60662 2.38602 11.106 6.098)" gradientUnits="userSpaceOnUse"><stop class="a5dbyd6tf"/><stop offset="1" class="on8sxx3yx"/></radialGradient><radialGradient id="svgIDbu" cx="0" cy="0" r="1" gradientTransform="matrix(-.52148 1.82813 -.23787 -.06785 12.149 4.36)" gradientUnits="userSpaceOnUse"><stop class="ak32k0b7k"/><stop offset="1" class="rknzqr02l"/></radialGradient><radialGradient id="svgIDbw" cx="0" cy="0" r="1" gradientTransform="matrix(-.35156 .1875 -.70184 -1.31597 11.985 9.375)" gradientUnits="userSpaceOnUse"><stop class="kgukkhbth"/><stop offset="1" class="k8s01tfdv"/></radialGradient><radialGradient id="svgIDbx" cx="0" cy="0" r="1" gradientTransform="matrix(-2.03124 1.09376 -.96833 -1.7983 12.031 7.266)" gradientUnits="userSpaceOnUse"><stop class="zjmmjyoar"/><stop offset="1" class="shic-ydjf"/></radialGradient><radialGradient id="svgIDby" cx="0" cy="0" r="1" gradientTransform="matrix(.76953 0 0 1.98438 9.715 7.75)" gradientUnits="userSpaceOnUse"><stop class="a0q036gjd"/><stop offset="1" class="q2gydu3zd"/></radialGradient><radialGradient id="svgIDbz" cx="0" cy="0" r="1" gradientTransform="matrix(-.76563 -.64062 1.04002 -1.24297 12.063 8.64)" gradientUnits="userSpaceOnUse"><stop class="fk4zrip8m"/><stop offset="1" class="jv-vvdc2h"/></radialGradient><radialGradient id="svgIDbF" cx="0" cy="0" r="1" gradientTransform="rotate(119.116 11.113 13.892) scale(2.32504 2.59006)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="drxrc2qjv"/><stop offset="1" class="f0p_5mgov"/></radialGradient><linearGradient id="svgIDe" x1="20.388" x2="17.261" y1="8.183" y2="8.37" gradientUnits="userSpaceOnUse"><stop class="vqxmos31w"/><stop offset="1" class="ughobhb7v"/></linearGradient><linearGradient id="svgIDo" x1="20.445" x2="20.569" y1="7.316" y2="7.333" gradientUnits="userSpaceOnUse"><stop class="uysgu56cq"/><stop offset="1" class="ve-3ak5rg"/></linearGradient><linearGradient id="svgIDr" x1="17.956" x2="18.16" y1="7.051" y2="7.117" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="svgIDt" x1="22.06" x2="22.545" y1="6.69" y2="3.523" gradientUnits="userSpaceOnUse"><stop offset=".421" class="h-bh2_bpf"/><stop offset="1" class="pf-fc7btu"/></linearGradient><linearGradient id="svgIDu" x1="20.023" x2="21.097" y1="5.406" y2="6.313" gradientUnits="userSpaceOnUse"><stop class="mqedtfb5e"/><stop offset="1" class="y4pe4ezsu"/></linearGradient><linearGradient id="svgIDx" x1="20.593" x2="19.242" y1="9.016" y2="10.844" gradientUnits="userSpaceOnUse"><stop class="ocru65npv"/><stop offset="1" class="b5skg8e-v"/></linearGradient><linearGradient id="svgIDL" x1="6.625" x2="8.406" y1="19.891" y2="18.203" gradientUnits="userSpaceOnUse"><stop class="xylxrh5lr"/><stop offset="1" class="dpng9pbvi"/></linearGradient><linearGradient id="svgIDM" x1="8.328" x2="8.153" y1="19.281" y2="19.098" gradientUnits="userSpaceOnUse"><stop class="o5qj3ac-m"/><stop offset="1" class="a151cabub"/></linearGradient><linearGradient id="svgIDN" x1="5.563" x2="6.844" y1="19.328" y2="19.391" gradientUnits="userSpaceOnUse"><stop offset=".28" class="azjp5ub3a"/><stop offset="1" class="yvalde4js"/></linearGradient><linearGradient id="svgIDV" x1="2.251" x2="2.836" y1="28.141" y2="28.273" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="svgIDX" x1="5.625" x2="5.625" y1="28.5" y2="28.176" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="svgIDaa" x1="9.756" x2="10.3" y1="28.266" y2="28.249" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="svgIDac" x1="12.899" x2="12.899" y1="28.492" y2="28.168" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="svgIDag" x1="10.365" x2="10.365" y1="10.132" y2="14.706" gradientUnits="userSpaceOnUse"><stop class="d9dzcxb5n"/><stop offset="1" class="aqyl6fvtq"/></linearGradient><linearGradient id="svgIDao" x1="13.406" x2="13.641" y1="20.656" y2="20.227" gradientUnits="userSpaceOnUse"><stop offset=".245" class="tqlb2r3pi"/><stop offset="1" class="w0vebxwgg"/></linearGradient><linearGradient id="svgIDar" x1="25.301" x2="25.832" y1="9.866" y2="11.109" gradientUnits="userSpaceOnUse"><stop class="t86ksxb8y"/><stop offset="1" class="sqy0srbzs"/></linearGradient><linearGradient id="svgIDav" x1="25.375" x2="23.593" y1="19.875" y2="18.188" gradientUnits="userSpaceOnUse"><stop class="xylxrh5lr"/><stop offset="1" class="dpng9pbvi"/></linearGradient><linearGradient id="svgIDaw" x1="23.672" x2="23.847" y1="19.266" y2="19.082" gradientUnits="userSpaceOnUse"><stop class="o5qj3ac-m"/><stop offset="1" class="a151cabub"/></linearGradient><linearGradient id="svgIDax" x1="26.437" x2="25.156" y1="19.313" y2="19.375" gradientUnits="userSpaceOnUse"><stop offset=".28" class="azjp5ub3a"/><stop offset="1" class="yvalde4js"/></linearGradient><linearGradient id="svgIDaF" x1="29.749" x2="29.164" y1="28.125" y2="28.258" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="svgIDaH" x1="26.375" x2="26.375" y1="28.484" y2="28.16" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="svgIDaK" x1="22.244" x2="21.7" y1="28.25" y2="28.233" gradientUnits="userSpaceOnUse"><stop offset=".107" class="oybn7vbqt"/><stop offset="1" class="al_auo8nl"/></linearGradient><linearGradient id="svgIDaM" x1="19.101" x2="19.101" y1="28.477" y2="28.152" gradientUnits="userSpaceOnUse"><stop class="i_emxkhmq"/><stop offset="1" class="qihskpbeg"/></linearGradient><linearGradient id="svgIDaQ" x1="1.732" x2="1.732" y1="0" y2="4.574" gradientUnits="userSpaceOnUse"><stop class="d9dzcxb5n"/><stop offset="1" class="aqyl6fvtq"/></linearGradient><linearGradient id="svgIDaU" x1="16.29" x2="18.034" y1="16.966" y2="16.966" gradientUnits="userSpaceOnUse"><stop offset=".527" class="pibz8jbrb"/><stop offset="1" class="w0zorxbdv"/></linearGradient><linearGradient id="svgIDaW" x1="17.375" x2="17.375" y1="18.553" y2="18.078" gradientUnits="userSpaceOnUse"><stop class="u-8_kd5ks"/><stop offset="1" class="qpd6gmsgb"/></linearGradient><linearGradient id="svgIDaY" x1="16.315" x2="18.032" y1="17.594" y2="17.594" gradientUnits="userSpaceOnUse"><stop offset=".527" class="pibz8jbrb"/><stop offset="1" class="w0zorxbdv"/></linearGradient><linearGradient id="svgIDbc" x1="11.612" x2="14.739" y1="8.183" y2="8.37" gradientUnits="userSpaceOnUse"><stop class="vqxmos31w"/><stop offset="1" class="ughobhb7v"/></linearGradient><linearGradient id="svgIDbm" x1="11.555" x2="11.431" y1="7.316" y2="7.333" gradientUnits="userSpaceOnUse"><stop class="uysgu56cq"/><stop offset="1" class="ve-3ak5rg"/></linearGradient><linearGradient id="svgIDbp" x1="-.007" x2=".196" y1=".054" y2=".121" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="svgIDbr" x1="9.94" x2="9.455" y1="6.69" y2="3.523" gradientUnits="userSpaceOnUse"><stop offset=".421" class="h-bh2_bpf"/><stop offset="1" class="pf-fc7btu"/></linearGradient><linearGradient id="svgIDbs" x1="11.977" x2="10.903" y1="5.406" y2="6.313" gradientUnits="userSpaceOnUse"><stop class="mqedtfb5e"/><stop offset="1" class="y4pe4ezsu"/></linearGradient><linearGradient id="svgIDbv" x1="11.406" x2="12.758" y1="9.016" y2="10.844" gradientUnits="userSpaceOnUse"><stop class="ocru65npv"/><stop offset="1" class="b5skg8e-v"/></linearGradient><linearGradient id="svgIDbD" x1="24.207" x2="19.801" y1="11.922" y2="17.953" gradientUnits="userSpaceOnUse"><stop class="xb-82dbql"/><stop offset="1" class="se2pt8bli"/></linearGradient><filter id="svgIDd" width="4.886" height="5.717" x="17.261" y="4.988" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.101961 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23627"/></filter><filter id="svgIDi" width="6.013" height="5.994" x="17.328" y="3.255" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.101961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23627"/></filter><filter id="svgIDs" width="2.378" height="3.698" x="21.064" y="3.895" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23627" stdDeviation=".25"/></filter><filter id="svgIDC" width="1.258" height=".393" x="17.793" y="6.4" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.027451 0 0 0 0 0.0156863 0 0 0 0 0.0392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23627"/></filter><filter id="svgIDF" width="2.691" height="1.989" x="15.879" y="11.238" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.109804 0 0 0 0 0.101961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23627"/></filter><filter id="svgIDG" width="10.808" height="5.007" x="8.491" y="10.567" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.176471 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23627"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.109804 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23627" result="effect2_innerShadow_3987_23627"/></filter><filter id="svgIDO" width="4.146" height="5.805" x="2.788" y="20.078" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.294118 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23627"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.172549 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23627" result="effect2_innerShadow_3987_23627"/></filter><filter id="svgIDP" width="9.426" height="8.574" x="2.717" y="9.878" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.501961 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23627"/></filter><filter id="svgIDQ" width="5.878" height="6.781" x="2.144" y="13.758" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.501961 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23627"/></filter><filter id="svgIDU" width="5.139" height="3.208" x="2.051" y="25.492" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23627"/></filter><filter id="svgIDY" width="2.686" height="1.05" x="2.698" y="25.492" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.670588 0 0 0 0 0.67451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23627"/></filter><filter id="svgIDZ" width="4.9" height="3.308" x="9.456" y="25.484" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23627"/></filter><filter id="svgIDad" width="2.288" height="1.065" x="9.756" y="25.484" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.627451 0 0 0 0 0.654902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23627"/></filter><filter id="svgIDaf" width="5.149" height="5.149" x="5.666" y="10.4" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23627" stdDeviation=".125"/></filter><filter id="svgIDaj" width="1.796" height="1.427" x="13.37" y="17.817" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.129412 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23627"/></filter><filter id="svgIDay" width="4.146" height="5.805" x="25.066" y="20.063" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.294118 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23627"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.172549 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23627" result="effect2_innerShadow_3987_23627"/></filter><filter id="svgIDaz" width="9.426" height="8.574" x="19.857" y="9.862" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.501961 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23627"/></filter><filter id="svgIDaA" width="5.878" height="6.781" x="23.978" y="13.742" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.501961 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23627"/></filter><filter id="svgIDaE" width="5.139" height="3.208" x="24.61" y="25.477" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23627"/></filter><filter id="svgIDaI" width="2.686" height="1.05" x="26.615" y="25.477" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.694118 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23627"/></filter><filter id="svgIDaJ" width="4.9" height="3.308" x="17.344" y="25.469" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.294118 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23627"/></filter><filter id="svgIDaN" width="2.288" height="1.065" x="20.156" y="25.469" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.690196 0 0 0 0 0.627451 0 0 0 0 0.654902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23627"/></filter><filter id="svgIDaP" width="5.149" height="5.149" x="21.185" y="10.384" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23627" stdDeviation=".125"/></filter><filter id="svgIDbb" width="4.886" height="5.717" x="10.104" y="4.988" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.101961 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23627"/></filter><filter id="svgIDbg" width="6.013" height="5.994" x="8.659" y="3.255" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.101961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23627"/></filter><filter id="svgIDbq" width="2.378" height="3.698" x="8.558" y="3.895" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23627" stdDeviation=".25"/></filter><filter id="svgIDbA" width="1.258" height=".393" x="12.95" y="6.4" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.027451 0 0 0 0 0.0156863 0 0 0 0 0.0392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23627"/></filter><filter id="svgIDbB" width="5.984" height="7.891" x="7.785" y="11.5" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23627" stdDeviation=".25"/></filter><filter id="svgIDbC" width="7.313" height="7.219" x="17.582" y="11.047" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23627" stdDeviation=".25"/></filter><filter id="svgIDbE" width="4.063" height="3.831" x="25.494" y="10.043" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23627" stdDeviation=".3"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-wrestling-dark" /></template>
<style>
.a_ejh2oyx {
  fill-rule: evenodd;
  d: path("M13.393 19.201a.45.45 0 0 1 .624-.12l.973.655a.45.45 0 0 1-.503.747l-.973-.657a.45.45 0 0 1-.121-.625Z");
}

.a0q036gjd {
  stop-color: var(--svg-color--504d4e, #504D4E);
}

.a151cabub {
  stop-color: var(--svg-color--fd5220, #FD5220);
  stop-opacity: 0;
}

.a5dbyd6tf {
  stop-color: var(--svg-color--5e4d44, #5E4D44);
}

.ak32k0b7k {
  stop-color: var(--svg-color--695d73, #695D73);
}

.al_auo8nl {
  stop-color: var(--svg-color--6d6a94, #6D6A94);
  stop-opacity: 0;
}

.aqyl6fvtq {
  stop-color: var(--svg-color--ff7837, #FF7837);
}

.av9qa9bga {
  stop-color: var(--svg-color--351e21, #351E21);
}

.ay-2-kl5u {
  fill: var(--svg-color--ff6a39, #FF6A39);
  d: path("M25.174 10.617a2.696 2.696 0 0 0-3.752 3.873l3.261 3.178a2.71 2.71 0 1 0 3.77-3.892l-3.28-3.16Z");
}

.azjp5ub3a {
  stop-color: var(--svg-color--ed3424, #ED3424);
}

.b5skg8e-v {
  stop-color: var(--svg-color--522470, #522470);
}

.bervkqbmz {
  stop-color: var(--svg-color--ffd040, #FFD040);
}

.bmsj66cvh {
  fill-rule: evenodd;
  d: path("M13.373 18.363a.4.4 0 0 1 .55-.135c.404.245.859.47 1.375.647a.4.4 0 1 1-.26.757a7.874 7.874 0 0 1-1.53-.72a.4.4 0 0 1-.135-.549Z");
}

.bn37hgbti {
  stop-color: var(--svg-color--421c2f, #421C2F);
}

.bpaul1b8u {
  stop-color: var(--svg-color--3f2631, #3F2631);
  stop-opacity: 0;
}

.bq0pg0bco {
  stop-color: var(--svg-color--ff5128, #FF5128);
  stop-opacity: 0;
}

.c_c7q3ixi {
  d: path("m2.919 25.568l-.66 2.62a.25.25 0 0 0 .242.312h4.441c.102 0 .196-.06.22-.159c.127-.503-.196-.866-.763-1.157a86.273 86.273 0 0 1-1.696-.9l.376-.719a.05.05 0 0 0-.044-.073h-2.02a.1.1 0 0 0-.096.076Z");
}

.c479w-bpn {
  stop-color: var(--svg-color--fead30, #FEAD30);
}

.c8s0qablf {
  fill: var(--svg-color--ff6a39, #FF6A39);
  d: path("m2.928 14.422l.664-.664l3.68 3.953l-1.21 1.016s.192 1.043.267 1.757a.05.05 0 0 1-.05.055H3.255a.05.05 0 0 1-.047-.034a63.198 63.198 0 0 1-.938-3.24c-.409-1.591.287-2.518.66-2.843Z");
}

.cg4q2vjsj {
  fill-rule: evenodd;
  d: path("M13.025 19.717a.4.4 0 0 1 .56-.086l.746.546a.4.4 0 1 1-.473.646l-.746-.547a.4.4 0 0 1-.087-.56Z");
}

.cm3jz64eh {
  stop-color: var(--svg-color--34191a, #34191A);
}

.ct6_m01bp {
  stop-color: var(--svg-color--5e5a92, #5E5A92);
}

.d4kn2qv1f {
  stop-color: var(--svg-color--41212e, #41212E);
}

.d894rgb9r {
  stop-color: var(--svg-color--3b2029, #3B2029);
}

.d983fmb_q {
  stop-color: var(--svg-color--5a4644, #5A4644);
}

.d9dzcxb5n {
  stop-color: var(--svg-color--ff772a, #FF772A);
}

.dbdhg7bmt {
  fill: var(--svg-color--452d2b, #452D2B);
  fill-rule: evenodd;
  d: path("M23.727 11.69c.627.167 1 .81.833 1.437c-.25.938-.826 1.86-1.893 3.008c-1.075 1.158-2.67 2.249-4.615 2.414a1.175 1.175 0 0 1-1.27-1.071c-.055-.647.363-1.162 1.01-1.217c1.206-.142 2.261-.825 3.112-1.74c.859-.926 1.253-1.502 1.385-1.999c.167-.627.811-1 1.438-.833Z");
}

.de_eaubsl {
  d: path("M14.71 6.609c-.043-.876-.327-1.298-.46-1.421h-4.078l-.068 3.457c.946 2.318 3.836 2.417 4.268 1.579c.432-.839.386-2.602.337-3.615Z");
}

.dm4voe-la {
  d: path("M0 0h2.371v3.351H0z");
}

.dpng9pbvi {
  stop-color: var(--svg-color--fe5823, #FE5823);
}

.drxrc2qjv {
  stop-color: var(--svg-color--594443, #594443);
}

.dt9uc6s1j {
  stop-color: var(--svg-color--2b131a, #2B131A);
}

.dyzk46b7s {
  stop-color: var(--svg-color--3c1e32, #3C1E32);
}

.dzmi4fing {
  stop-color: var(--svg-color--363131, #363131);
}

.e17muc3id {
  fill: var(--svg-color--544241, #544241);
  d: path("M15.846 18.169c0-.213.173-.386.386-.386h1.385l.308.77H16.23a.385.385 0 0 1-.385-.384Z");
}

.e1g-j13cf {
  d: path("M17.29 6.609c.043-.876.326-1.298.46-1.421h4.078l.068 3.457c-.946 2.318-3.836 2.417-4.268 1.579c-.432-.839-.386-2.602-.337-3.615Z");
}

.e48lyqzlo {
  stop-color: var(--svg-color--502d2b, #502D2B);
}

.e4pbfdbxe {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m29.081 25.552l.66 2.621a.25.25 0 0 1-.242.311h-4.441c-.102 0-.196-.06-.22-.158c-.127-.504.196-.866.763-1.157a86.753 86.753 0 0 0 1.696-.901l-.376-.718a.05.05 0 0 1 .044-.073h2.02a.1.1 0 0 1 .096.075Z");
}

.e53sx1y3l {
  d: path("M17.046 7.662c.171-.16.26-.4.282-.5h.196v1.23c-.234.15-.57.126-.67-.098c-.085-.192-.021-.431.192-.632Z");
}

.efhi-0e0h {
  width: 3.464px;
  height: 4.574px;
  x: 8.633px;
  y: 10.132px;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  rx: 1.732px;
}

.ehqrbmxde {
  fill-rule: evenodd;
  d: path("M8.23 11.43a1.15 1.15 0 0 1 1.388.846c.33 1.361 1.57 4.162 4.242 5.912c.539.335.765 1.005.43 1.544a1.15 1.15 0 0 1-1.585.37c-3.29-1.75-4.814-4.977-5.323-7.284a1.15 1.15 0 0 1 .847-1.389Z");
}

.er7ggnzmt {
  width: 3.464px;
  height: 4.574px;
  x: 8.633px;
  y: 10.132px;
  rx: 1.732px;
}

.eu764gb8n {
  stop-color: var(--svg-color--311d1e, #311D1E);
}

.f0p_5mgov {
  stop-color: var(--svg-color--594443, #594443);
  stop-opacity: 0;
}

.f6mg5tnmy {
  rx: 0.07px;
  ry: 0.096px;
}

.f7kd4ybpw {
  fill: var(--svg-color--3c202b, #3C202B);
  d: path("M16.086 15.517a.384.384 0 1 0 0 .768h.518a.065.065 0 0 1 0 .13h1.158v-.13h.254l-.31-.31a1.568 1.568 0 0 0-1.108-.458h-.512Z");
}

.f8i1cfbfs {
  stop-color: var(--svg-color--584341, #584341);
}

.fblnbo7cb {
  stop-color: var(--svg-color--614c49, #614C49);
  stop-opacity: 0;
}

.fi5356bnb {
  stop-color: var(--svg-color--371d29, #371D29);
  stop-opacity: 0;
}

.fjfalibmt {
  d: path("m29.081 25.552l.66 2.621a.25.25 0 0 1-.242.311h-4.441c-.102 0-.196-.06-.22-.158c-.127-.504.196-.866.763-1.157a86.753 86.753 0 0 0 1.696-.901l-.376-.718a.05.05 0 0 1 .044-.073h2.02a.1.1 0 0 1 .096.075Z");
}

.fk4zrip8m {
  stop-color: var(--svg-color--483159, #483159);
}

.ft5dv1b6b {
  fill: none;
}

.g2g8iabmv {
  stop-color: var(--svg-color--3e2523, #3E2523);
}

.g9j5kob3s {
  fill-rule: evenodd;
  d: path("M20.898 8.44a.25.25 0 0 0-.325.138a9.05 9.05 0 0 1-.511 1.038c-.23.399-.488.767-.733.975a.25.25 0 0 0 .325.38c.312-.266.606-.696.841-1.105c.24-.415.433-.834.541-1.1a.25.25 0 0 0-.138-.326Z");
}

.gg2ehgbth {
  width: 3.464px;
  height: 4.574px;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  rx: 1.732px;
}

.gm3gtoamf {
  stop-color: var(--svg-color--42302e, #42302E);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gvsjiqbgx {
  d: path("M15.503 17.431c0-.215.172-.39.384-.39h1.999v.78h-2a.387.387 0 0 1-.383-.39Z");
}

.gxf7turxa {
  d: path("M10.647 10.711a2.697 2.697 0 0 0-3.821-.079l-3.234 3.126l-.045.034a2.79 2.79 0 0 0-.188.2l-.43.43c-.373.325-1.069 1.252-.66 2.844c.372 1.447.778 2.733.938 3.239a.048.048 0 0 0 .047.034h3.025a.05.05 0 0 0 .05-.055c-.074-.714-.268-1.757-.268-1.757l.876-.735c.133-.09.26-.193.38-.309l3.261-3.178a2.696 2.696 0 0 0 .069-3.794Z");
}

.h-bh2_bpf {
  stop-color: var(--svg-color--454143, #454143);
}

.hh9ibwbje {
  stop-color: var(--svg-color--5e5a92, #5E5A92);
  stop-opacity: 0;
}

.hi6yszbkt {
  stop-color: var(--svg-color--ff5c2b, #FF5C2B);
  stop-opacity: 0;
}

.hoilpz9zm {
  d: path("M11.844 26.29v-.756a.05.05 0 0 0-.05-.05H9.805a.05.05 0 0 0-.05.055l.089.89v.02l2-.159Z");
}

.hrqvsac6m {
  stop-color: var(--svg-color--614c49, #614C49);
}

.ht_71mb8b {
  d: path("m20.306 8.21l.217-1.565a.79.79 0 0 1-.217 1.565Z");
}

.i_emxkhmq {
  stop-color: var(--svg-color--442f88, #442F88);
}

.i2k7fbb6p {
  width: 1.258px;
  height: 0.293px;
  fill: var(--svg-color--222, #222);
  rx: 0.146px;
}

.icmqrjb0b {
  d: path("M15.464 16.804a.39.39 0 0 1 .39-.39h2.032v.78h-2.032a.39.39 0 0 1-.39-.39Z");
}

.id2qh1bcz {
  stop-color: var(--svg-color--311d1e, #311D1E);
  stop-opacity: 0;
}

.ikr-5kk0l {
  d: path("m9.844 26.43l-.088-.89a.05.05 0 0 1 .05-.056h1.988a.05.05 0 0 1 .05.05v.767c.559.262 1.627.807 2.074 1.117c.378.261.441.563.438.801c-.003.155-.143.273-.298.273h-3.964a.25.25 0 0 1-.25-.25V26.43Z");
}

.io95kkawv {
  d: path("M14.954 7.662c-.171-.16-.26-.4-.282-.5h-.196v1.23c.234.15.57.126.67-.098c.085-.192.021-.431-.192-.632Z");
}

.ithzpjn2t {
  fill-rule: evenodd;
  d: path("M23.727 11.69c.627.167 1 .81.833 1.437c-.25.938-.826 1.86-1.893 3.008c-1.075 1.158-2.67 2.249-4.615 2.414a1.175 1.175 0 0 1-1.27-1.071c-.055-.647.363-1.162 1.01-1.217c1.206-.142 2.261-.825 3.112-1.74c.859-.926 1.253-1.502 1.385-1.999c.167-.627.811-1 1.438-.833Z");
}

.j8zkl2bkx {
  d: path("M13.493 7.477v-.004c0-.35.15-.635.336-.635c.185 0 .335.284.335.635v.004h-.67Z");
}

.j98nf06iw {
  d: path("M10.378 5.43c-.17.695-.27 1.36-.303 1.662a3.166 3.166 0 0 1-1.014-2.045c-.055-.545.629-.827 1.092-.536c.334.21.32.535.225.919Z");
}

.jez0q5b5i {
  stop-color: var(--svg-color--371d29, #371D29);
}

.jiuqa9mgc {
  stop-color: var(--svg-color--464243, #464243);
}

.jjhblb54u {
  stop-color: var(--svg-color--ff5128, #FF5128);
}

.jp-rsubez {
  fill: var(--svg-color--4f3633, #4F3633);
  fill-rule: evenodd;
  d: path("M13.393 19.201a.45.45 0 0 1 .624-.12l.973.655a.45.45 0 0 1-.503.747l-.973-.657a.45.45 0 0 1-.121-.625Z");
}

.jv-vvdc2h {
  stop-color: var(--svg-color--433352, #433352);
  stop-opacity: 0;
}

.k8s01tfdv {
  stop-color: var(--svg-color--5e5663, #5E5663);
  stop-opacity: 0;
}

.kgukkhbth {
  stop-color: var(--svg-color--5e5663, #5E5663);
}

.khzpeo26k {
  stop-color: var(--svg-color--564c49, #564C49);
}

.kmghwmbgk {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.844 7.476h1.08c0-.428-.242-.774-.54-.774c-.298 0-.54.346-.54.774Z");
}

.kxgqu6reh {
  d: path("M21.353 10.696a2.697 2.697 0 0 1 3.821-.08l3.234 3.126l.045.034c.067.064.13.13.188.2l.43.43c.373.326 1.069 1.252.66 2.844a62.46 62.46 0 0 1-.938 3.239a.047.047 0 0 1-.02.026a.052.052 0 0 1-.027.008h-3.025a.05.05 0 0 1-.05-.054c.075-.715.268-1.758.268-1.758l-.876-.735a2.713 2.713 0 0 1-.38-.308l-3.261-3.178a2.696 2.696 0 0 1-.069-3.794Z");
}

.l0-a8nb2d {
  fill: var(--svg-color--ff6a39, #FF6A39);
  d: path("M6.826 10.632a2.696 2.696 0 0 1 3.753 3.873l-3.262 3.178a2.71 2.71 0 1 1-3.77-3.891l3.28-3.16Z");
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l6veklvwf {
  stop-color: var(--svg-color--9e94a2, #9E94A2);
}

.l74ely9dg {
  d: path("M13.707 7.477a.7.7 0 0 1-.004-.08c0-.202.086-.367.192-.367c.106 0 .192.165.192.368a.7.7 0 0 1-.004.079h-.376Z");
}

.lff7xxwjk {
  stop-color: var(--svg-color--3a2022, #3A2022);
}

.lkpmwzkfe {
  stop-color: var(--svg-color--351e21, #351E21);
  stop-opacity: 0;
}

.ln8ibjxtc {
  fill: var(--svg-color--280017, #280017);
  d: path("M18.695 9.009a.124.124 0 0 0-.124-.124h-.607a.124.124 0 1 0 0 .248h.607a.124.124 0 0 0 .124-.124Z");
}

.lqg5yzb2a {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m2.919 25.568l-.66 2.62a.25.25 0 0 0 .242.312h4.441c.102 0 .196-.06.22-.159c.127-.503-.196-.866-.763-1.157a86.273 86.273 0 0 1-1.696-.9l.376-.719a.05.05 0 0 0-.044-.073h-2.02a.1.1 0 0 0-.096.076Z");
}

.lqt0qlbse {
  stop-color: var(--svg-color--391d35, #391D35);
  stop-opacity: 0;
}

.lshdlpbel {
  stop-color: var(--svg-color--4d363a, #4D363A);
}

.lu7jcxbxj {
  stop-color: var(--svg-color--34191a, #34191A);
  stop-opacity: 0;
}

.lub5dyb4n {
  stop-color: var(--svg-color--392523, #392523);
}

.lxkzcy4gl {
  cx: 18.034px;
  cy: 7.092px;
  rx: 0.07px;
  ry: 0.096px;
}

.mm65sim_f {
  fill: var(--svg-color--4b3236, #4B3236);
  d: path("m3.89 22.195l-.57-1.726l2.876-.39c.013.093.071.51.203 1.429c.13.919-.125 1.664-.375 2.203l-1.22 2.172H2.939c.245-.771.843-2.77.93-3.031c.085-.262.085-.48.023-.657Z");
}

.mqedtfb5e {
  stop-color: var(--svg-color--423948, #423948);
}

.ms4f1oj7g {
  r: 1.281px;
}

.n-_owbcrt {
  d: path("m11.682 8.198l-.218-1.573a.794.794 0 0 0 .218 1.573Z");
}

.n1q06yb7u {
  fill: var(--svg-color--52403e, #52403E);
  fill-rule: evenodd;
  d: path("M15.127 18.195a.4.4 0 0 1-.188.533l-.996.476a.4.4 0 1 1-.346-.721l.996-.477a.4.4 0 0 1 .534.189Z");
}

.n3rn3i52e {
  cx: 10.996px;
  cy: 7.75px;
  r: 1.281px;
}

.n7442l93h {
  fill: var(--svg-color--4f3633, #4F3633);
  fill-rule: evenodd;
  d: path("M13.609 18.895a.4.4 0 0 1 .547-.142l1.215.715a.4.4 0 1 1-.405.69l-1.215-.716a.4.4 0 0 1-.142-.547Z");
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.nb7sh9bzw {
  stop-color: var(--svg-color--b1aab6, #B1AAB6);
}

.ngzjmvbel {
  fill: var(--svg-color--4f3633, #4F3633);
  fill-rule: evenodd;
  d: path("M13.373 18.363a.4.4 0 0 1 .55-.135c.404.245.859.47 1.375.647a.4.4 0 1 1-.26.757a7.874 7.874 0 0 1-1.53-.72a.4.4 0 0 1-.135-.549Z");
}

.nqgqms1jm {
  stop-color: var(--svg-color--22191d, #22191D);
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o5l8xobeq {
  stop-color: var(--svg-color--472f2c, #472F2C);
}

.o5qj3ac-m {
  stop-color: var(--svg-color--e73d40, #E73D40);
}

.o8vu0vmqg {
  d: path("M21.622 5.43c.17.695.27 1.36.302 1.662c.69-.631.95-1.407 1.015-2.045c.055-.545-.629-.827-1.092-.536c-.334.21-.32.535-.225.919Z");
}

.oas8dfb-p {
  stop-color: var(--svg-color--3e2523, #3E2523);
  stop-opacity: 0;
}

.ocru65npv {
  stop-color: var(--svg-color--3f3646, #3F3646);
}

.ojg463bev {
  stop-color: var(--svg-color--503838, #503838);
}

.om8b18tot {
  d: path("m24.855 20.374l1.082-1.007l1.149-1.023l-3.133-1.907a77.97 77.97 0 0 1-1.4 1.66a.05.05 0 0 0 .003.069l2.23 2.206a.05.05 0 0 0 .07.002Z");
}

.on8sxx3yx {
  stop-color: var(--svg-color--5e4d44, #5E4D44);
  stop-opacity: 0;
}

.onwu39rgv {
  d: path("m11.694 8.21l-.217-1.565a.79.79 0 0 0 .217 1.565Z");
}

.oqr0o-bmo {
  stop-color: var(--svg-color--391d35, #391D35);
}

.oy9gm987l {
  fill-rule: evenodd;
  d: path("M27.133 12.404a.1.1 0 0 0-.09-.14l-3.873-.058l.035-2.34l4.25.06c1.653.024 2.653 1.726 1.919 3.234l-1.186 2.545l-2.062-1.02l1.007-2.281Z");
}

.oybn7vbqt {
  stop-color: var(--svg-color--6d6a94, #6D6A94);
}

.p4686vbiy {
  stop-color: var(--svg-color--fb5d03, #FB5D03);
}

.p8z6xcc_e {
  d: path("m2.928 14.422l.664-.664l3.68 3.953l-1.21 1.016s.192 1.043.267 1.757a.05.05 0 0 1-.05.055H3.255a.05.05 0 0 1-.047-.034a63.198 63.198 0 0 1-.938-3.24c-.409-1.591.287-2.518.66-2.843Z");
}

.pf-fc7btu {
  stop-color: var(--svg-color--454143, #454143);
  stop-opacity: 0;
}

.phx-vgmut {
  d: path("m22.156 26.414l.088-.89a.05.05 0 0 0-.05-.055h-1.988a.05.05 0 0 0-.05.05v.766c-.559.262-1.627.807-2.074 1.117c-.378.262-.441.563-.438.801c.003.156.143.274.298.274h3.964a.25.25 0 0 0 .25-.25v-1.813Z");
}

.pibz8jbrb {
  stop-color: var(--svg-color--432932, #432932);
}

.plhowgx4z {
  stop-color: var(--svg-color--472f2c, #472F2C);
  stop-opacity: 0;
}

.plkel1bga {
  stop-color: var(--svg-color--363131, #363131);
  stop-opacity: 0;
}

.pmld2ob6g {
  fill-rule: evenodd;
  d: path("M19.822 3.684a.25.25 0 0 0-.162.314l.95 2.969a.25.25 0 0 0 .476-.152l-.95-2.97a.25.25 0 0 0-.314-.161Z");
}

.ppc2prvwk {
  fill: var(--svg-color--9d91a7, #9D91A7);
  d: path("m27.297 26.268l-.376-.718a.05.05 0 0 1 .044-.073h2.02a.1.1 0 0 1 .096.075l.22.874l-2.004-.158Z");
}

.pxj138bcc {
  width: 3.464px;
  height: 4.574px;
  rx: 1.732px;
}

.q2354_btu {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m9.844 26.43l-.088-.89a.05.05 0 0 1 .05-.056h1.988a.05.05 0 0 1 .05.05v.767c.559.262 1.627.807 2.074 1.117c.378.261.441.563.438.801c-.003.155-.143.273-.298.273h-3.964a.25.25 0 0 1-.25-.25V26.43Z");
}

.q2gydu3zd {
  stop-color: var(--svg-color--3e3a3f, #3E3A3F);
  stop-opacity: 0;
}

.q5daohbyq {
  d: path("m29.072 14.406l-.664-.664l-3.68 3.953l1.21 1.016s-.192 1.043-.267 1.758a.05.05 0 0 0 .05.054h3.025a.05.05 0 0 0 .047-.034c.16-.505.565-1.792.938-3.239c.409-1.592-.287-2.518-.66-2.844Z");
}

.qihskpbeg {
  stop-color: var(--svg-color--524e8d, #524E8D);
  stop-opacity: 0;
}

.qpd6gmsgb {
  stop-color: var(--svg-color--3b1f30, #3B1F30);
  stop-opacity: 0;
}

.qpejwlb8n {
  stop-color: var(--svg-color--fb5d03, #FB5D03);
  stop-opacity: 0;
}

.qz9j3ivdd {
  fill: var(--svg-color--523d3c, #523D3C);
  d: path("m16.074 11.715l.536-.516c.123-.11.461-.332.824-.332h.988a.477.477 0 1 1 0 .953h-.866a.224.224 0 0 0-.202.13l-.033.068a.344.344 0 0 0-.002.288l.557-.038a.516.516 0 0 1 .07 1.029l-.669.046c-.739 1.026-1.884 2.056-3.902 2.229c-2.386.057-3.712-1.182-4.258-1.691a10.17 10.17 0 0 0-.108-.1l-.103-.092a1.15 1.15 0 0 1 1.47-1.769c.023.02.077-.013.133-.046c.064-.038.132-.078.163-.05c.054.047.11.098.17.154c.497.454 1.236 1.131 2.533 1.131c.391 0 .884-.013 1.408-.336c.51-.314.937-.699 1.167-.95a.666.666 0 0 1 .124-.108Z");
}

.r_4d04xgj {
  stop-color: var(--svg-color--3c1e32, #3C1E32);
  stop-opacity: 0;
}

.r3b5-4bfz {
  fill: var(--svg-color--4b3236, #4B3236);
  d: path("m28.11 22.18l.57-1.727l-2.876-.39c-.013.093-.071.51-.203 1.43c-.13.918.125 1.663.375 2.202l1.22 2.172h1.866c-.245-.77-.844-2.77-.93-3.031c-.085-.262-.085-.48-.023-.656Z");
}

.r91r1xbti {
  fill: var(--svg-color--280017, #280017);
  d: path("M13.305 9.009c0-.069.056-.124.124-.124h.607a.124.124 0 1 1 0 .248h-.607a.124.124 0 0 1-.124-.124Z");
}

.rknzqr02l {
  stop-color: var(--svg-color--695d73, #695D73);
  stop-opacity: 0;
}

.rr-6_qbjy {
  d: path("M15.846 18.169c0-.213.173-.386.386-.386h1.385l.308.77H16.23a.385.385 0 0 1-.385-.384Z");
}

.ruodvgjtp {
  stop-color: var(--svg-color--3f2631, #3F2631);
}

.s4vz1uxal {
  fill: var(--svg-color--4d3836, #4D3836);
  fill-rule: evenodd;
  d: path("M13.025 19.717a.4.4 0 0 1 .56-.086l.746.546a.4.4 0 1 1-.473.646l-.746-.547a.4.4 0 0 1-.087-.56Z");
}

.se2pt8bli {
  stop-color: var(--svg-color--584442, #584442);
  stop-opacity: 0;
}

.sh3-zfb6o {
  d: path("M26.406 10.643a.3.3 0 1 0-.024.6l.024-.6Zm1.29.353l.013-.3l-.012.3Zm.899 1.343l.282.103l-.282-.103Zm-.514.532a.3.3 0 0 0 .563.206l-.563-.206Zm-1.7-1.628l1.303.053l.025-.6l-1.303-.053l-.024.6Zm1.932.993l-.232.635l.563.206l.233-.635l-.564-.206Zm-.629-.94a.7.7 0 0 1 .63.94l.563.206a1.3 1.3 0 0 0-1.168-1.745l-.025.6Z");
}

.shic-ydjf {
  stop-color: var(--svg-color--2e2d2f, #2E2D2F);
}

.spqa7jbew {
  width: 0.764px;
  height: 1.4px;
  x: 17.093px;
  y: 15.807px;
  fill: var(--svg-color--49322f, #49322F);
  rx: 0.382px;
}

.sqy0srbzs {
  stop-color: var(--svg-color--462f2c, #462F2C);
  stop-opacity: 0;
}

.ss7zei8xw {
  stop-color: var(--svg-color--68534f, #68534F);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.sylpfbbmy {
  fill-rule: evenodd;
  d: path("M11.102 8.44a.25.25 0 0 1 .325.138c.1.247.285.645.511 1.038c.23.399.488.767.732.975a.25.25 0 0 1-.324.38c-.312-.266-.606-.696-.841-1.105a9.537 9.537 0 0 1-.541-1.1a.25.25 0 0 1 .138-.326Z");
}

.t4m41vbgx {
  stop-color: var(--svg-color--e6473c, #E6473C);
}

.t683yih5k {
  fill: var(--svg-color--524d8c, #524D8C);
  d: path("m22.156 26.414l.088-.89a.05.05 0 0 0-.05-.055h-1.988a.05.05 0 0 0-.05.05v.766c-.559.262-1.627.807-2.074 1.117c-.378.262-.441.563-.438.801c.003.156.143.274.298.274h3.964a.25.25 0 0 0 .25-.25v-1.813Z");
}

.t7s0hbcft {
  fill-rule: evenodd;
  d: path("M12.178 3.684a.25.25 0 0 1 .162.314l-.95 2.969a.25.25 0 0 1-.476-.152l.95-2.97a.25.25 0 0 1 .314-.161Z");
}

.t86ksxb8y {
  stop-color: var(--svg-color--462f2c, #462F2C);
}

.tqlb2r3pi {
  stop-color: var(--svg-color--40272f, #40272F);
}

.txw7mlbhv {
  d: path("m20.318 8.198l.218-1.573a.794.794 0 0 1-.218 1.573Z");
}

.u-8_kd5ks {
  stop-color: var(--svg-color--3b1f30, #3B1F30);
}

.u4ygu_vhg {
  d: path("m16.074 11.715l.536-.516c.123-.11.461-.332.824-.332h.988a.477.477 0 1 1 0 .953h-.866a.224.224 0 0 0-.202.13l-.033.068a.344.344 0 0 0-.002.288l.557-.038a.516.516 0 0 1 .07 1.029l-.669.046c-.739 1.026-1.884 2.056-3.902 2.229c-2.386.057-3.712-1.182-4.258-1.691a10.17 10.17 0 0 0-.108-.1l-.103-.092a1.15 1.15 0 0 1 1.47-1.769c.023.02.077-.013.133-.046c.064-.038.132-.078.163-.05c.054.047.11.098.17.154c.497.454 1.236 1.131 2.533 1.131c.391 0 .884-.013 1.408-.336c.51-.314.937-.699 1.167-.95a.666.666 0 0 1 .124-.108Z");
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.udoy8tq9u {
  fill-rule: evenodd;
  d: path("M13.609 18.895a.4.4 0 0 1 .547-.142l1.215.715a.4.4 0 1 1-.405.69l-1.215-.716a.4.4 0 0 1-.142-.547Z");
}

.ughobhb7v {
  stop-color: var(--svg-color--3c262d, #3C262D);
}

.uh458k7zv {
  d: path("M17.456 4.038a1.12 1.12 0 0 1 1.075-.631c.94.051 1.037.526 1.887.35c.897-.184 1.37-.281 1.754-.107l.007.004c.38.172 1.162.527 1.162 2.13c0 1.477-.526 2.257-.78 2.535l.05.018c.252.092.357.361.265.614c-.078.216-.351.34-.696.286a22.601 22.601 0 0 1-.909-.16a.271.271 0 0 1-.218-.267V7.594c0-.512-.36-.818-.52-.91c-.017-.529-.18-.772-.444-.9c-.438-.212-.574-.107-1.622-.17c-1.054-.065-1.336-.91-1.011-1.576Z");
}

.uj8od9jgc {
  stop-color: var(--svg-color--42302e, #42302E);
  stop-opacity: 0;
}

.us6-yfb3g {
  stop-color: var(--svg-color--3a2022, #3A2022);
  stop-opacity: 0;
}

.uwkao-znc {
  d: path("m22.828 22.023l2.039-1.804l-2.156-2.188a68.991 68.991 0 0 1-1.903 2.278c-.67.77-.758 1.77-.738 2.261l.102 2.899h2.023c.068-.735.211-2.308.242-2.727a.954.954 0 0 1 .39-.719Z");
}

.uysgu56cq {
  stop-color: var(--svg-color--48302c, #48302C);
}

.v23x_cgsr {
  stop-color: var(--svg-color--482c2e, #482C2E);
}

.v6badmbjw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M24.02 11.922c-.26 1.312-1.738 4.244-5.563 5.469");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.ve-3ak5rg {
  stop-color: var(--svg-color--48302c, #48302C);
  stop-opacity: 0;
}

.vqxmos31w {
  stop-color: var(--svg-color--432927, #432927);
}

.vw65-prir {
  d: path("M20.156 26.274v-.755a.05.05 0 0 1 .05-.05h1.989a.05.05 0 0 1 .05.055l-.089.89v.02l-2-.16Z");
}

.w0vebxwgg {
  stop-color: var(--svg-color--40272f, #40272F);
  stop-opacity: 0;
}

.w0zorxbdv {
  stop-color: var(--svg-color--432932, #432932);
  stop-opacity: 0;
}

.w1isstbai {
  width: 1.258px;
  height: 0.293px;
  x: 12.95px;
  y: 6.5px;
  fill: var(--svg-color--222, #222);
  rx: 0.146px;
}

.w4xvl2bcn {
  d: path("M14.544 4.038a1.12 1.12 0 0 0-1.075-.631c-.94.051-1.037.526-1.887.35c-.897-.184-1.37-.281-1.754-.107l-.007.004c-.38.172-1.162.527-1.162 2.13c0 1.477.526 2.257.78 2.535l-.05.018c-.252.092-.356.361-.265.614c.078.216.351.34.696.286c.393-.062.682-.116.909-.16a.271.271 0 0 0 .218-.267V7.594c0-.512.36-.818.52-.91c.017-.529.18-.772.444-.9c.438-.212.575-.107 1.622-.17c1.054-.065 1.336-.91 1.011-1.576Z");
}

.w55-gkb2p {
  stop-color: var(--svg-color--342d30, #342D30);
}

.wyd1xpdro {
  stop-color: var(--svg-color--464243, #464243);
  stop-opacity: 0;
}

.x7jby2bwc {
  d: path("M18.506 7.477v-.004c0-.35-.15-.635-.335-.635c-.185 0-.335.284-.335.635v.004h.67Z");
}

.x9fqyvbmj {
  fill: var(--svg-color--baa4c5, #BAA4C5);
  d: path("m4.703 26.283l.376-.718a.05.05 0 0 0-.044-.073h-2.02a.1.1 0 0 0-.096.076l-.22.874l2.004-.159Z");
}

.xanj4emtj {
  fill: var(--svg-color--ff6a39, #FF6A39);
  d: path("m29.072 14.406l-.664-.664l-3.68 3.953l1.21 1.016s-.192 1.043-.267 1.758a.05.05 0 0 0 .05.054h3.025a.05.05 0 0 0 .047-.034c.16-.505.565-1.792.938-3.239c.409-1.592-.287-2.518-.66-2.844Z");
}

.xb-82dbql {
  stop-color: var(--svg-color--584442, #584442);
}

.xktf9pbat {
  stop-color: var(--svg-color--564c49, #564C49);
  stop-opacity: 0;
}

.xsj4wobsw {
  fill: var(--svg-color--2c1524, #2C1524);
  d: path("m16.47 11.542l-.59.57l.297 1.115l1.425-.505l-.08-.117a.316.316 0 0 1-.023-.311l.03-.064a.205.205 0 0 1 .185-.118h.42a.437.437 0 1 0 0-.874h-.907c-.333 0-.643.203-.756.304Z");
}

.xylxrh5lr {
  stop-color: var(--svg-color--f03814, #F03814);
}

.y4pe4ezsu {
  stop-color: var(--svg-color--271e2e, #271E2E);
}

.yh97ver0s {
  d: path("M19.316 9.154h2.371v3.351h-2.371z");
}

.yvalde4js {
  stop-color: var(--svg-color--ed3424, #ED3424);
  stop-opacity: 0;
}

.yvrc9xbpg {
  d: path("m9.172 22.04l-2.039-1.806l2.156-2.187a68.14 68.14 0 0 0 1.903 2.277c.67.77.758 1.77.738 2.262l-.102 2.898H9.805a295.31 295.31 0 0 1-.242-2.726a.954.954 0 0 0-.39-.719Z");
}

.z01wqtbit {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.156 7.476h-1.08c0-.428.242-.774.54-.774c.298 0 .54.346.54.774Z");
}

.z4x_sbopl {
  stroke: var(--svg-color--564040, #564040);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M8.66 12.375c.073 1.375 2.032 4.875 4.235 6.14");
}

.zh8wx3bjm {
  d: path("M18.293 7.477a.7.7 0 0 0 .004-.08c0-.202-.086-.367-.192-.367c-.106 0-.192.165-.192.368a.7.7 0 0 0 .004.079h.376Z");
}

.zhc3hbcwf {
  stop-color: var(--svg-color--4d272d, #4D272D);
  stop-opacity: 0;
}

.ziwjwlzyo {
  d: path("m7.145 20.39l-1.082-1.007l-1.149-1.024l3.133-1.906a77.83 77.83 0 0 0 1.4 1.66a.05.05 0 0 1-.003.068l-2.23 2.207a.05.05 0 0 1-.07.001Z");
}

.zjmmjyoar {
  stop-color: var(--svg-color--554f5c, #554F5C);
}

.zns8kxbgp {
  fill: var(--svg-color--4e3532, #4E3532);
  fill-rule: evenodd;
  d: path("M8.23 11.43a1.15 1.15 0 0 1 1.388.846c.33 1.361 1.57 4.162 4.242 5.912c.539.335.765 1.005.43 1.544a1.15 1.15 0 0 1-1.585.37c-3.29-1.75-4.814-4.977-5.323-7.284a1.15 1.15 0 0 1 .847-1.389Z");
}

</style>
