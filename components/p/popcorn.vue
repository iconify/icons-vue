<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iMVp1Yb)" class="lfdbszbhp"/><g filter="url(#ieyr20d)"><ellipse fill="url(#irjWasY)" class="g1dfcxbme"/><ellipse fill="url(#iFNrskd)" class="g1dfcxbme"/></g><path fill="url(#inPdwvh)" class="e25ls8srr"/><g filter="url(#igdoACc)"><ellipse transform="rotate(3.907 12.226 10.51)" class="m9xnkkbfq"/><ellipse fill="url(#iCku36L)" transform="rotate(3.907 12.226 10.51)" class="unw796v7h"/><ellipse fill="url(#iMiiY4o)" transform="rotate(3.907 12.226 10.51)" class="unw796v7h"/></g><g filter="url(#iz2DCIc)"><path fill="url(#iqP5Mtc)" class="xcornb71v"/></g><g filter="url(#idohvGb)"><ellipse fill="url(#iDkjcWT)" class="m2948gb2d"/></g><g filter="url(#iuIfSwb)"><path fill="url(#iShaCce)" class="xvbe4f1jy"/></g><g filter="url(#iJm7Ugy)"><ellipse fill="url(#iT3SRid)" class="wxwysb8rj"/><ellipse fill="url(#isDWuEP)" class="wxwysb8rj"/></g><g filter="url(#iTQsNed)"><circle fill="url(#inC1HAb)" class="tikfkst5o"/></g><g filter="url(#iSIOjgc)"><ellipse fill="url(#iO6JaId)" class="uy5x4fb-n"/></g><g filter="url(#i9njNMk)"><circle fill="url(#iRnUCEk)" class="us6yuiv0y"/><circle fill="url(#ixhmPCd)" class="us6yuiv0y"/><circle fill="url(#irI2Uec)" class="us6yuiv0y"/></g><path fill="url(#iKWvJLd)" class="du3tfi-vj"/><path class="pyr4t6w2p"/><path fill="url(#iUa3XJb)" class="sjuhfhbew"/><g filter="url(#ir9Pr3d)"><ellipse fill="url(#iQwfere)" class="xwzhtxb7d"/><ellipse fill="url(#iOBgdDe)" class="xwzhtxb7d"/><ellipse fill="url(#iUcRDfc)" class="xwzhtxb7d"/></g><g filter="url(#ipXIZQb)"><ellipse fill="url(#iGYRbJb)" class="em5ac7bbj"/><ellipse fill="url(#ism6nPh)" class="em5ac7bbj"/></g><g filter="url(#iYZKIHe)"><path fill="url(#iye7dzL)" class="np0v8rb8u"/></g><g filter="url(#iBZZQMe)"><path fill="url(#i0W45Ec)" class="xc1pkrb1m"/></g><path fill="url(#iHvnNIG)" class="g43ncea8x"/><g filter="url(#iWL7LQc)"><ellipse fill="url(#i4OYOad)" class="u5lcfgjzc"/></g><g filter="url(#iPgq0md)"><path fill="url(#i57z2fx)" class="optlh7ayw"/></g><path fill="url(#iSPnkqK)" class="m4k4_hm1f"/><g filter="url(#idTUNPc)"><ellipse class="bxxa5t7qy"/><ellipse fill="url(#iaTFxOe)" class="ky8p5ab7z"/><ellipse fill="url(#iRsRQQd)" class="ky8p5ab7z"/></g><g filter="url(#i9ncgvS)"><ellipse fill="url(#ienDkye)" class="i873jibqh"/><ellipse fill="url(#imwQHzb)" class="i873jibqh"/><ellipse fill="url(#ivNl7Ib)" class="i873jibqh"/></g><g filter="url(#inrCQHd)"><ellipse fill="url(#i0pQcyc)" class="p4hr50bsc"/><ellipse fill="url(#iBx7Mpb)" class="p4hr50bsc"/><ellipse fill="url(#i8zIXnd)" class="p4hr50bsc"/></g><g filter="url(#iwYXBqd)"><circle fill="url(#imkMULd)" class="ynli1k0ru"/></g><path fill="url(#iJuDkkT)" class="dcem_cbsm"/><g filter="url(#iFcEcje)"><path fill="url(#i0fLCTc)" class="hdz9ribyy"/></g><g filter="url(#ihzw4Sb)"><path class="srcooacwi"/></g><g filter="url(#iSo9Rdd)"><ellipse fill="url(#i8Wc5Oc)" class="qebsbac7l"/><ellipse fill="url(#iyuVQhb)" class="qebsbac7l"/><ellipse fill="url(#i0U9oyt)" class="qebsbac7l"/></g><g filter="url(#iGlLnle)"><path fill="url(#i6vEUfb)" class="pixg2pbuj"/></g><g filter="url(#iZq4F8d)"><ellipse fill="url(#iozUlAc)" class="a89j18bxi"/></g><g filter="url(#iv0H7yI)"><ellipse transform="rotate(3.907 18.268 14.057)" class="zcn4-kcgy"/><ellipse fill="url(#ivRPuce)" transform="rotate(3.907 18.268 14.057)" class="s7eubti3w"/><ellipse fill="url(#iCkJnZz)" transform="rotate(3.907 18.268 14.057)" class="s7eubti3w"/></g><g filter="url(#igHt9Zc)"><ellipse fill="url(#iFJTQMd)" class="gkxuclbyu"/></g><g filter="url(#i4n2Iqd)"><circle fill="url(#iXUkxsc)" class="bqx690bke"/></g><path fill="url(#imIAUhb)" class="iizvm2b2c"/><g filter="url(#i6zzb6d)"><ellipse fill="url(#idKPJqd)" class="ptuzt5bue"/><ellipse fill="url(#ijOqwPc)" class="ptuzt5bue"/><ellipse fill="url(#iNWhomb)" class="ptuzt5bue"/><ellipse fill="url(#iKOopzb)" class="ptuzt5bue"/></g><g filter="url(#iD6yQue)"><path fill="url(#igkDP8b)" class="v_czs0nld"/></g><g filter="url(#io4a1Rd)"><ellipse fill="url(#iljc8Zq)" class="fqhxyjbao"/></g><g filter="url(#i4x5R7x)"><circle fill="url(#iN3dzuL)" class="z20j-vtrw"/></g><path fill="url(#iOPfePW)" class="kb21tlfgm"/><path fill="url(#igZwvLb)" class="kb21tlfgm"/><g filter="url(#iboWuKd)"><path class="ravead3lt"/></g><path fill="url(#iahLgHb)" class="ojfry0p0j"/><path fill="url(#iZvH50Q)" class="ojfry0p0j"/><g filter="url(#iu6jbMb)"><path fill="url(#iZxYTUV)" class="q6f3cl-wf"/><path fill="url(#iE2deyc)" class="q6f3cl-wf"/></g><g filter="url(#i5tYtDd)"><circle fill="url(#i8jz40q)" class="vntqjprsf"/></g><path fill="url(#i1xE9Tc)" class="me8ohew6c"/><path fill="url(#iqcm2TV)" class="me8ohew6c"/><g filter="url(#idOzFSh)"><path class="ogovfhq7c"/></g><path fill="url(#iUIgZ3t)" class="o_b54tapg"/><path fill="url(#iNeJmJb)" class="o_b54tapg"/><g filter="url(#irtN2XU)"><path fill="url(#iVO29Br)" class="g-bqfkpur"/></g><path fill="url(#iVZaFZd)" class="ecwa5oz4x"/><g filter="url(#iPIKRze)"><path fill="url(#iTWnrPe)" class="lxbatibbd"/></g><g filter="url(#iWgSTWd)"><path class="f065mrr_i"/></g><g filter="url(#ijpY2Mc)"><path class="pgj3l8mgx"/></g><g filter="url(#i7fXdFe)"><path class="t-nj21bkj"/></g><defs><radialGradient id="irjWasY" cx="0" cy="0" r="1" gradientTransform="rotate(127.051 6.39 6.288)scale(2.98024 2.96117)" gradientUnits="userSpaceOnUse"><stop class="snmpnslpa"/><stop offset=".639" class="pnc5-7l0z"/><stop offset="1" class="spw5n3bym"/></radialGradient><radialGradient id="iFNrskd" cx="0" cy="0" r="1" gradientTransform="rotate(83.683 3.545 11.245)scale(1.52488 3.38128)" gradientUnits="userSpaceOnUse"><stop class="o2jirabwj"/><stop offset=".806" class="rl6ld-b3g"/></radialGradient><radialGradient id="iCku36L" cx="0" cy="0" r="1" gradientTransform="matrix(-1.10376 2.18375 -1.71116 -.8649 11.888 8.424)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="w1frnv42f"/><stop offset=".85" class="e0c8ic5fw"/><stop offset="1" class="l33tyqbds"/></radialGradient><radialGradient id="iMiiY4o" cx="0" cy="0" r="1" gradientTransform="rotate(138.877 5.553 7.97)scale(2.33484 2.43931)" gradientUnits="userSpaceOnUse"><stop offset=".517" class="agh0_je5x"/><stop offset=".85" class="oba0mltwe"/></radialGradient><radialGradient id="iqP5Mtc" cx="0" cy="0" r="1" gradientTransform="rotate(125.261 7.67 6.031)scale(3.07305 2.43938)" gradientUnits="userSpaceOnUse"><stop class="snmpnslpa"/><stop offset=".639" class="nopmo_btx"/><stop offset="1" class="fapa1buzy"/></radialGradient><radialGradient id="iDkjcWT" cx="0" cy="0" r="1" gradientTransform="matrix(-.04688 -4.17807 3.98137 -.04467 13.813 9.92)" gradientUnits="userSpaceOnUse"><stop class="ylxelbbvo"/><stop offset=".595" class="g4z91_wyt"/><stop offset="1" class="jx2lrr0tu"/></radialGradient><radialGradient id="iShaCce" cx="0" cy="0" r="1" gradientTransform="matrix(-1.81443 2.52811 -2.01668 -1.44737 13.03 6.122)" gradientUnits="userSpaceOnUse"><stop class="snmpnslpa"/><stop offset=".639" class="a1fkg2v-f"/><stop offset="1" class="fapa1buzy"/></radialGradient><radialGradient id="iT3SRid" cx="0" cy="0" r="1" gradientTransform="rotate(127.748 3.79 6.647)scale(2.95779 2.95838)" gradientUnits="userSpaceOnUse"><stop class="snmpnslpa"/><stop offset=".639" class="pnc5-7l0z"/><stop offset="1" class="spw5n3bym"/></radialGradient><radialGradient id="isDWuEP" cx="0" cy="0" r="1" gradientTransform="matrix(.16919 1.49027 -3.38686 .3845 10.433 9.2)" gradientUnits="userSpaceOnUse"><stop class="o2jirabwj"/><stop offset=".806" class="rl6ld-b3g"/></radialGradient><radialGradient id="inC1HAb" cx="0" cy="0" r="1" gradientTransform="rotate(130.839 4.734 6.997)scale(2.48496)" gradientUnits="userSpaceOnUse"><stop class="v1_f85y9k"/><stop offset=".639" class="jkjob7hts"/><stop offset="1" class="m3p3qbb3n"/></radialGradient><radialGradient id="iO6JaId" cx="0" cy="0" r="1" gradientTransform="rotate(120.912 8.147 7.59)scale(2.55927 2.56024)" gradientUnits="userSpaceOnUse"><stop class="v1_f85y9k"/><stop offset=".639" class="dfo1iif6q"/><stop offset="1" class="cr-6c7bjl"/></radialGradient><radialGradient id="iRnUCEk" cx="0" cy="0" r="1" gradientTransform="rotate(124.001 7.196 6.996)scale(2.68237)" gradientUnits="userSpaceOnUse"><stop class="v1_f85y9k"/><stop offset=".639" class="dfo1iif6q"/><stop offset="1" class="cr-6c7bjl"/></radialGradient><radialGradient id="ixhmPCd" cx="0" cy="0" r="1" gradientTransform="rotate(89.055 4.62 11.02)scale(.94703 2.35294)" gradientUnits="userSpaceOnUse"><stop class="radpfinci"/><stop offset="1" class="h-ot04a9y"/></radialGradient><radialGradient id="irI2Uec" cx="0" cy="0" r="1" gradientTransform="rotate(141.895 7.395 5.602)scale(3.27637 2.53574)" gradientUnits="userSpaceOnUse"><stop offset=".601" class="xfa24pbsl"/><stop offset="1" class="og3-lhbfl"/></radialGradient><radialGradient id="iQwfere" cx="0" cy="0" r="1" gradientTransform="matrix(2.26927 -.36307 .35845 2.2404 21.1 7.863)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="dxvfcd3ty"/><stop offset=".407" class="j4xvv9blx"/><stop offset="1" class="ce374hbpu"/></radialGradient><radialGradient id="iOBgdDe" cx="0" cy="0" r="1" gradientTransform="matrix(.95932 .50964 -.28434 .53523 21.052 9.588)" gradientUnits="userSpaceOnUse"><stop class="q395f8bzj"/><stop offset="1" class="rvo07kbtv"/></radialGradient><radialGradient id="iUcRDfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .89936 -.93953 0 22.252 7.58)" gradientUnits="userSpaceOnUse"><stop class="n4er2zrqn"/><stop offset="1" class="vzvitncif"/></radialGradient><radialGradient id="iGYRbJb" cx="0" cy="0" r="1" gradientTransform="rotate(127.748 1.838 7.887)scale(2.95779 2.95838)" gradientUnits="userSpaceOnUse"><stop class="snmpnslpa"/><stop offset=".639" class="pnc5-7l0z"/><stop offset="1" class="spw5n3bym"/></radialGradient><radialGradient id="ism6nPh" cx="0" cy="0" r="1" gradientTransform="matrix(.16919 1.49027 -3.38686 .3845 8.266 12.743)" gradientUnits="userSpaceOnUse"><stop class="o2jirabwj"/><stop offset=".806" class="rl6ld-b3g"/></radialGradient><radialGradient id="iye7dzL" cx="0" cy="0" r="1" gradientTransform="matrix(-1.81747 2.53235 -2.02006 -1.4498 10.916 9.718)" gradientUnits="userSpaceOnUse"><stop class="zbmg46bgb"/><stop offset=".639" class="dn7_tmuhr"/><stop offset="1" class="fapa1buzy"/></radialGradient><radialGradient id="i0W45Ec" cx="0" cy="0" r="1" gradientTransform="rotate(125.261 8.798 8.32)scale(2.95379 2.19101)" gradientUnits="userSpaceOnUse"><stop class="snmpnslpa"/><stop offset=".639" class="u_gomu6jd"/><stop offset="1" class="fapa1buzy"/></radialGradient><radialGradient id="i4OYOad" cx="0" cy="0" r="1" gradientTransform="matrix(-.83629 1.53125 -1.52894 -.83502 20.094 7.926)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="rxxk8pb1u"/><stop offset=".729" class="k9fwxwdhp"/></radialGradient><radialGradient id="i57z2fx" cx="0" cy="0" r="1" gradientTransform="matrix(-2.09373 2.65627 -2.1171 -1.66874 22.802 9.542)" gradientUnits="userSpaceOnUse"><stop offset=".102" class="ncmrgtbfx"/><stop offset=".518" class="e5rrzr_xa"/><stop offset="1" class="e20uvgbum"/></radialGradient><radialGradient id="iaTFxOe" cx="0" cy="0" r="1" gradientTransform="rotate(-169.963 8.823 3.469)scale(1.79307 1.8733)" gradientUnits="userSpaceOnUse"><stop offset=".619" class="f1i-kmg6u"/><stop offset=".852" class="hifiyq4xy"/></radialGradient><radialGradient id="iRsRQQd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.25 .92188 -.96313 -1.30593 18.734 10.375)" gradientUnits="userSpaceOnUse"><stop offset=".517" class="agh0_je5x"/><stop offset=".85" class="oba0mltwe"/></radialGradient><radialGradient id="ienDkye" cx="0" cy="0" r="1" gradientTransform="matrix(2.34887 -.35472 .33148 2.19493 23.33 11.546)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="dxvfcd3ty"/><stop offset=".407" class="j4xvv9blx"/><stop offset="1" class="ce374hbpu"/></radialGradient><radialGradient id="imwQHzb" cx="0" cy="0" r="1" gradientTransform="matrix(1.05502 .64439 -.35064 .57409 23.22 13.085)" gradientUnits="userSpaceOnUse"><stop class="q395f8bzj"/><stop offset="1" class="rvo07kbtv"/></radialGradient><radialGradient id="ivNl7Ib" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87871 -.97248 0 24.524 11.269)" gradientUnits="userSpaceOnUse"><stop class="n4er2zrqn"/><stop offset="1" class="vzvitncif"/></radialGradient><radialGradient id="i0pQcyc" cx="0" cy="0" r="1" gradientTransform="matrix(2.3655 -.37846 .37364 2.3354 18.36 7.64)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="dxvfcd3ty"/><stop offset=".407" class="j4xvv9blx"/><stop offset="1" class="ce374hbpu"/></radialGradient><radialGradient id="iBx7Mpb" cx="0" cy="0" r="1" gradientTransform="matrix(1 .53124 -.2964 .55793 18.313 9.438)" gradientUnits="userSpaceOnUse"><stop class="q395f8bzj"/><stop offset="1" class="rvo07kbtv"/></radialGradient><radialGradient id="i8zIXnd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9375 -.97937 0 19.563 7.344)" gradientUnits="userSpaceOnUse"><stop class="n4er2zrqn"/><stop offset="1" class="vzvitncif"/></radialGradient><radialGradient id="imkMULd" cx="0" cy="0" r="1" gradientTransform="matrix(-.8842 1.6196 -1.61681 -.88269 22.401 11.738)" gradientUnits="userSpaceOnUse"><stop offset=".449" class="rxxk8pb1u"/><stop offset=".729" class="k9fwxwdhp"/></radialGradient><radialGradient id="i0fLCTc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.09373 2.65627 -2.1171 -1.66874 20.656 9.563)" gradientUnits="userSpaceOnUse"><stop offset=".102" class="ncmrgtbfx"/><stop offset=".518" class="e5rrzr_xa"/><stop offset="1" class="e20uvgbum"/></radialGradient><radialGradient id="i8Wc5Oc" cx="0" cy="0" r="1" gradientTransform="matrix(2.39885 -.36228 .33854 2.24164 21.178 11.576)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="dxvfcd3ty"/><stop offset=".407" class="j4xvv9blx"/><stop offset="1" class="ce374hbpu"/></radialGradient><radialGradient id="iyuVQhb" cx="0" cy="0" r="1" gradientTransform="matrix(1.07748 .6581 -.3581 .5863 21.066 13.147)" gradientUnits="userSpaceOnUse"><stop class="q395f8bzj"/><stop offset="1" class="rvo07kbtv"/></radialGradient><radialGradient id="i0U9oyt" cx="0" cy="0" r="1" gradientTransform="matrix(0 .89741 -.99318 0 22.397 11.293)" gradientUnits="userSpaceOnUse"><stop class="n4er2zrqn"/><stop offset="1" class="vzvitncif"/></radialGradient><radialGradient id="i6vEUfb" cx="0" cy="0" r="1" gradientTransform="rotate(125.261 7.536 7.48)scale(3.03349 2.25013)" gradientUnits="userSpaceOnUse"><stop class="snmpnslpa"/><stop offset=".639" class="nopmo_btx"/><stop offset="1" class="fapa1buzy"/></radialGradient><radialGradient id="iozUlAc" cx="0" cy="0" r="1" gradientTransform="rotate(127.051 6.3 7.722)scale(2.98024 2.96117)" gradientUnits="userSpaceOnUse"><stop class="snmpnslpa"/><stop offset=".639" class="pnc5-7l0z"/><stop offset="1" class="spw5n3bym"/></radialGradient><radialGradient id="ivRPuce" cx="0" cy="0" r="1" gradientTransform="matrix(-1.10376 2.18375 -1.71116 -.8649 17.93 11.971)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="w1frnv42f"/><stop offset=".85" class="e0c8ic5fw"/><stop offset="1" class="l33tyqbds"/></radialGradient><radialGradient id="iCkJnZz" cx="0" cy="0" r="1" gradientTransform="rotate(138.877 7.909 10.877)scale(2.33484 2.43931)" gradientUnits="userSpaceOnUse"><stop offset=".517" class="agh0_je5x"/><stop offset=".85" class="oba0mltwe"/></radialGradient><radialGradient id="iFJTQMd" cx="0" cy="0" r="1" gradientTransform="rotate(130.914 7.322 7.908)scale(2.48122 2.48216)" gradientUnits="userSpaceOnUse"><stop class="v1_f85y9k"/><stop offset=".639" class="dfo1iif6q"/><stop offset="1" class="cr-6c7bjl"/></radialGradient><radialGradient id="iXUkxsc" cx="0" cy="0" r="1" gradientTransform="rotate(130.839 7.777 10.675)scale(2.48496)" gradientUnits="userSpaceOnUse"><stop class="v1_f85y9k"/><stop offset=".639" class="dfo1iif6q"/><stop offset="1" class="cr-6c7bjl"/></radialGradient><radialGradient id="idKPJqd" cx="0" cy="0" r="1" gradientTransform="matrix(2.47116 -.39537 .39034 2.43971 16.41 11.99)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="dxvfcd3ty"/><stop offset=".407" class="j4xvv9blx"/><stop offset="1" class="ce374hbpu"/></radialGradient><radialGradient id="ijOqwPc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.96875 2.03124 -1.13329 -1.09842 16.438 9.625)" gradientUnits="userSpaceOnUse"><stop class="q395f8bzj"/><stop offset="1" class="rvo07kbtv"/></radialGradient><radialGradient id="iNWhomb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .97937 -1.02311 0 17.664 11.68)" gradientUnits="userSpaceOnUse"><stop class="n4er2zrqn"/><stop offset="1" class="vzvitncif"/></radialGradient><radialGradient id="iKOopzb" cx="0" cy="0" r="1" gradientTransform="rotate(132.345 6.172 10.895)scale(1.79696 1.82136)" gradientUnits="userSpaceOnUse"><stop offset=".416" class="ma1_ktryp"/><stop offset=".779" class="hw_cj3bmb"/></radialGradient><radialGradient id="igkDP8b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.67291 2.75167 -2.19313 -1.33334 15.844 9.734)" gradientUnits="userSpaceOnUse"><stop class="ncmrgtbfx"/><stop offset=".639" class="gcf0vykjf"/><stop offset="1" class="uixwzj4nr"/></radialGradient><radialGradient id="iljc8Zq" cx="0" cy="0" r="1" gradientTransform="rotate(127.746 4.334 9.304)scale(3.00564 3.00618)" gradientUnits="userSpaceOnUse"><stop class="snmpnslpa"/><stop offset=".639" class="pnc5-7l0z"/><stop offset="1" class="spw5n3bym"/></radialGradient><radialGradient id="iN3dzuL" cx="0" cy="0" r="1" gradientTransform="rotate(130.839 2.865 8.22)scale(2.48496)" gradientUnits="userSpaceOnUse"><stop class="ub0wlybpa"/><stop offset=".639" class="r-8lrwf_z"/><stop offset="1" class="z6cl-3a6w"/></radialGradient><radialGradient id="i8jz40q" cx="0" cy="0" r="1" gradientTransform="rotate(130.839 5.364 9.571)scale(2.48496)" gradientUnits="userSpaceOnUse"><stop class="v1_f85y9k"/><stop offset=".639" class="dfo1iif6q"/><stop offset="1" class="cr-6c7bjl"/></radialGradient><filter id="ieyr20d" width="3.667" height="3.725" x="12.498" y="3.584" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="igdoACc" width="3.562" height="3.432" x="10.445" y="8.794" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="iz2DCIc" width="3.701" height="3.887" x="14.221" y="1.81" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="idohvGb" width="3.694" height="3.826" x="12.361" y="6.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="iuIfSwb" width="3.773" height="3.912" x="10.172" y="4.672" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="iJm7Ugy" width="3.694" height="3.671" x="8.586" y="6.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="iTQsNed" width="3.938" height="3.938" x="10.061" y="6.184" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="iSIOjgc" width="3.32" height="3.313" x="16.305" y="3.633" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="i9njNMk" width="3.938" height="3.938" x="14.082" y="3.478" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="ir9Pr3d" width="3.698" height="3.655" x="19.463" y="6.182" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="ipXIZQb" width="3.694" height="3.671" x="6.42" y="9.887" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="iYZKIHe" width="3.779" height="3.918" x="8.054" y="8.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="iBZZQMe" width="3.576" height="3.784" x="17.971" y="4.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="iWL7LQc" width="3.751" height="3.75" x="17.876" y="6.051" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="iPgq0md" width="3.878" height="4.029" x="19.958" y="8.2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="idTUNPc" width="3.563" height="3.431" x="15.203" y="8.499" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="i9ncgvS" width="3.81" height="3.583" x="21.646" y="9.898" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="inrCQHd" width="3.834" height="3.789" x="16.666" y="5.898" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="iwYXBqd" width="3.938" height="3.938" x="20.07" y="9.77" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="iFcEcje" width="3.878" height="4.029" x="17.812" y="8.221" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="ihzw4Sb" width="3.878" height="4.029" x="15.556" y="10.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="iSo9Rdd" width="3.881" height="3.648" x="19.463" y="9.898" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="iGlLnle" width="3.659" height="3.843" x="15.227" y="4.219" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="iZq4F8d" width="3.667" height="3.725" x="13.499" y="5.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="iv0H7yI" width="3.562" height="3.432" x="16.488" y="12.341" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="igHt9Zc" width="3.938" height="3.928" x="15.031" y="5.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="i4n2Iqd" width="3.938" height="3.938" x="17.876" y="9.965" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="i6zzb6d" width="3.983" height="3.936" x="14.65" y="10.182" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="iD6yQue" width="3.878" height="4.029" x="13.109" y="8.383" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="io4a1Rd" width="3.746" height="3.723" x="11.523" y="10.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="i4x5R7x" width="3.938" height="3.938" x="7.895" y="9.621" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="iboWuKd" width="4.876" height="17.938" x="9.734" y="12" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="iu6jbMb" width="5.473" height="17.906" x="5.886" y="11.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="i5tYtDd" width="3.938" height="3.938" x="13.05" y="9.965" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="idOzFSh" width="4.876" height="18.063" x="17.77" y="12" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="irtN2XU" width="5.397" height="17.938" x="20.938" y="12" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="iPIKRze" width="5.128" height="18.078" x="13.604" y="12" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".125"/></filter><filter id="iWgSTWd" width="2.542" height="2.101" x="15.942" y="11.887" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".15"/></filter><filter id="ijpY2Mc" width="2.221" height="1.852" x="24.244" y="12.003" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".15"/></filter><filter id="i7fXdFe" width="2.802" height="1.91" x="7.2" y="11.982" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29199" stdDeviation=".15"/></filter><linearGradient id="iMVp1Yb" x1="13.125" x2="19.031" y1="4.313" y2="4.313" gradientUnits="userSpaceOnUse"><stop offset=".349" class="p_elfac8r"/><stop offset=".635" class="dxy8aob9t"/><stop offset="1" class="o4twgjg7c"/></linearGradient><linearGradient id="inPdwvh" x1="9.06" x2="15.174" y1="7.263" y2="7.263" gradientUnits="userSpaceOnUse"><stop offset=".349" class="p_elfac8r"/><stop offset=".635" class="d5sfr-bad"/><stop offset="1" class="o4twgjg7c"/></linearGradient><linearGradient id="iKWvJLd" x1="16.715" x2="22.767" y1="7.159" y2="7.16" gradientUnits="userSpaceOnUse"><stop offset=".12" class="ycywsccgi"/><stop offset=".439" class="ixhvjacwe"/><stop offset=".635" class="nly9l8bff"/><stop offset="1" class="qvypz5suf"/></linearGradient><linearGradient id="iUa3XJb" x1="6.912" x2="13.025" y1="10.893" y2="10.893" gradientUnits="userSpaceOnUse"><stop offset=".349" class="p_elfac8r"/><stop offset=".635" class="d5sfr-bad"/><stop offset="1" class="o4twgjg7c"/></linearGradient><linearGradient id="iHvnNIG" x1="18.911" x2="25.024" y1="10.879" y2="10.879" gradientUnits="userSpaceOnUse"><stop offset=".12" class="ycywsccgi"/><stop offset=".439" class="ixhvjacwe"/><stop offset=".635" class="nly9l8bff"/><stop offset="1" class="qvypz5suf"/></linearGradient><linearGradient id="iSPnkqK" x1="14.14" x2="19.89" y1="7.63" y2="7.63" gradientUnits="userSpaceOnUse"><stop class="aq67slbpp"/><stop offset=".315" class="xw_9lkh7t"/><stop offset=".758" class="bm0wgtbzv"/><stop offset=".894" class="exriyrbum"/><stop offset="1" class="uqt1nbc4r"/></linearGradient><linearGradient id="iJuDkkT" x1="16.816" x2="22.929" y1="10.843" y2="10.843" gradientUnits="userSpaceOnUse"><stop offset=".12" class="ycywsccgi"/><stop offset=".439" class="ixhvjacwe"/><stop offset=".635" class="nly9l8bff"/><stop offset="1" class="qob71wbbx"/></linearGradient><linearGradient id="imIAUhb" x1="12.182" x2="18.043" y1="11.316" y2="11.316" gradientUnits="userSpaceOnUse"><stop class="aq67slbpp"/><stop offset=".315" class="xw_9lkh7t"/><stop offset=".758" class="bm0wgtbzv"/><stop offset=".894" class="exriyrbum"/><stop offset="1" class="uqt1nbc4r"/></linearGradient><linearGradient id="iOPfePW" x1="9.984" x2="13.688" y1="12.625" y2="12.625" gradientUnits="userSpaceOnUse"><stop offset=".064" class="ho_dcj9xe"/><stop offset=".663" class="u6mwecb0a"/></linearGradient><linearGradient id="igZwvLb" x1="12.344" x2="12.344" y1="30.02" y2="28.75" gradientUnits="userSpaceOnUse"><stop class="x5-xrj9zy"/><stop offset=".151" class="xjea8_boq"/><stop offset="1" class="ck0r00s8v"/></linearGradient><linearGradient id="iahLgHb" x1="5.996" x2="10.156" y1="13.251" y2="13.251" gradientUnits="userSpaceOnUse"><stop offset=".335" class="pr6zm83zw"/><stop offset="1" class="yguu9g4lg"/></linearGradient><linearGradient id="iZvH50Q" x1="10.563" x2="10.563" y1="29.813" y2="27.688" gradientUnits="userSpaceOnUse"><stop class="v_8ae5gvr"/><stop offset=".235" class="vzx_ey6cj"/><stop offset="1" class="rkstse44d"/></linearGradient><linearGradient id="iZxYTUV" x1="8.686" x2="8.686" y1="12.188" y2="29.594" gradientUnits="userSpaceOnUse"><stop class="qtif9sbzz"/><stop offset="1" class="mu-hpbbnk"/></linearGradient><linearGradient id="iE2deyc" x1="6.75" x2="8.623" y1="20.688" y2="20.438" gradientUnits="userSpaceOnUse"><stop class="m14-r0rif"/><stop offset=".715" class="yeh9qwbdz"/></linearGradient><linearGradient id="i1xE9Tc" x1="18.656" x2="22.396" y1="12.625" y2="12.625" gradientUnits="userSpaceOnUse"><stop offset=".021" class="ho_dcj9xe"/><stop offset=".635" class="u6mwecb0a"/></linearGradient><linearGradient id="iqcm2TV" x1="20.38" x2="20.38" y1="30.02" y2="28.984" gradientUnits="userSpaceOnUse"><stop class="x5-xrj9zy"/><stop offset=".185" class="xy6x6cchm"/><stop offset="1" class="ck0r00s8v"/></linearGradient><linearGradient id="iUIgZ3t" x1="21.09" x2="25.252" y1="13.251" y2="13.251" gradientUnits="userSpaceOnUse"><stop offset=".335" class="pr6zm83zw"/><stop offset="1" class="yguu9g4lg"/></linearGradient><linearGradient id="iNeJmJb" x1="25.659" x2="25.659" y1="29.813" y2="27.688" gradientUnits="userSpaceOnUse"><stop class="v_8ae5gvr"/><stop offset=".235" class="vzx_ey6cj"/><stop offset="1" class="rkstse44d"/></linearGradient><linearGradient id="iVO29Br" x1="26.427" x2="23.289" y1="18.981" y2="18.462" gradientUnits="userSpaceOnUse"><stop class="e6x62_bof"/><stop offset=".563" class="kgd6tw0nv"/></linearGradient><linearGradient id="iVZaFZd" x1="13.758" x2="18.622" y1="13.25" y2="13.25" gradientUnits="userSpaceOnUse"><stop offset=".397" class="bhl8xiuso"/><stop offset="1" class="s_rog4i9o"/></linearGradient><linearGradient id="iTWnrPe" x1="16.168" x2="16.168" y1="12.25" y2="29.828" gradientUnits="userSpaceOnUse"><stop class="qtif9sbzz"/><stop offset="1" class="mu-hpbbnk"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:popcorn" /></template>
<style>
.a1fkg2v-f {
  stop-color: var(--svg-color--e0c4a0, #E0C4A0);
}

.a89j18bxi {
  cx: 15.332px;
  cy: 7.816px;
  rx: 1.584px;
  ry: 1.613px;
}

.agh0_je5x {
  stop-color: var(--svg-color--b7834c, #B7834C);
}

.aq67slbpp {
  stop-color: var(--svg-color--c0a988, #C0A988);
}

.bhl8xiuso {
  stop-color: var(--svg-color--c13444, #C13444);
}

.bm0wgtbzv {
  stop-color: var(--svg-color--d9c7a5, #D9C7A5);
}

.bqx690bke {
  cx: 19.844px;
  cy: 11.934px;
  r: 1.719px;
}

.bxxa5t7qy {
  cx: 16.984px;
  cy: 10.215px;
  fill: var(--svg-color--f4cca9, #F4CCA9);
  rx: 1.531px;
  ry: 1.466px;
}

.ce374hbpu {
  stop-color: var(--svg-color--ffe9be, #FFE9BE);
}

.ck0r00s8v {
  stop-color: var(--svg-color--e39cff, #E39CFF);
  stop-opacity: 0;
}

.cr-6c7bjl {
  stop-color: var(--svg-color--c1a382, #C1A382);
}

.d5sfr-bad {
  stop-color: var(--svg-color--f9dfb1, #F9DFB1);
}

.dcem_cbsm {
  d: path("M23.204 11.59c0-.85-.59-1.29-1.39-1.47a.4.4 0 0 1-.3-.26c-.24-.69-.67-1.44-1.67-1.44s-1.476.75-1.716 1.44c-.05.13-.16.23-.3.26c-.79.18-1.344.62-1.344 1.47s.59 1.55 1.39 1.73c.14.03.25.12.3.26c.24.69.9 1.18 1.67 1.18s1.43-.49 1.67-1.18c.05-.13.16-.23.3-.26c.8-.18 1.39-.88 1.39-1.73");
}

.dfo1iif6q {
  stop-color: var(--svg-color--f4cba8, #F4CBA8);
}

.dn7_tmuhr {
  stop-color: var(--svg-color--dfbf96, #DFBF96);
}

.du3tfi-vj {
  d: path("M23.04 8.01c0-.85-.523-1.453-1.323-1.633a.4.4 0 0 1-.3-.26c-.24-.69-.698-1.445-1.67-1.445c-.895 0-1.195.658-1.434 1.348c-.05.13-.16.23-.3.26c-.79.18-1.626.88-1.626 1.73s.59 1.55 1.39 1.73c.14.03.25.12.3.26c.24.69.9 1.18 1.67 1.18s1.43-.49 1.67-1.18c.05-.13.16-.23.3-.26c.8-.18 1.322-.88 1.322-1.73");
}

.dxvfcd3ty {
  stop-color: var(--svg-color--fffae5, #FFFAE5);
}

.dxy8aob9t {
  stop-color: var(--svg-color--cdc2ae, #CDC2AE);
}

.e0c8ic5fw {
  stop-color: var(--svg-color--c09064, #C09064);
}

.e20uvgbum {
  stop-color: var(--svg-color--d9b68f, #D9B68F);
}

.e25ls8srr {
  d: path("M15.449 8.01c0-.85-.59-1.29-1.39-1.47a.4.4 0 0 1-.3-.26c-.24-.69-.525-1.44-1.67-1.44c-1.019 0-1.472.75-1.722 1.44c-.04.14-.16.23-.3.26c-.79.18-1.338.843-1.338 1.47c0 .967.59 1.55 1.38 1.73c.14.03.26.12.3.26c.24.69.9 1.18 1.67 1.18s1.43-.49 1.67-1.18c.05-.13.16-.23.3-.26c.8-.18 1.4-.88 1.4-1.73");
}

.e5rrzr_xa {
  stop-color: var(--svg-color--f2d4b4, #F2D4B4);
}

.e6x62_bof {
  stop-color: var(--svg-color--fe1951, #FE1951);
}

.ecwa5oz4x {
  d: path("M16.19 11.868c-1.379 0-2.49 1.141-2.43 2.51l.615 15.632h3.63l.615-15.632a2.43 2.43 0 0 0-2.43-2.51");
}

.em5ac7bbj {
  cx: 8.267px;
  cy: 11.723px;
  rx: 1.597px;
  ry: 1.586px;
}

.exriyrbum {
  stop-color: var(--svg-color--ead5b1, #EAD5B1);
}

.f065mrr_i {
  fill: var(--svg-color--ff5a6d, #FF5A6D);
  d: path("M18.047 13.664c.507-.129-.454-1.476-1.805-1.476c1.828.859 1.122 1.65 1.805 1.476");
}

.f1i-kmg6u {
  stop-color: var(--svg-color--c89965, #C89965);
}

.fapa1buzy {
  stop-color: var(--svg-color--c6ac92, #C6AC92);
}

.fqhxyjbao {
  cx: 13.396px;
  cy: 12.041px;
  rx: 1.623px;
  ry: 1.611px;
}

.ft5dv1b6b {
  fill: none;
}

.g-bqfkpur {
  d: path("M24.41 12.25c-1.06 0-1.883.772-1.973 1.773l-1.25 15.665h1.473c.7 0 1.011-.487 1.121-1.145l2.266-14.062c.2-1.173-.397-2.231-1.637-2.231");
}

.g1dfcxbme {
  cx: 14.332px;
  cy: 5.447px;
  rx: 1.584px;
  ry: 1.613px;
}

.g43ncea8x {
  d: path("M25.3 11.73c0-.85-.54-1.472-1.34-1.652a.4.4 0 0 1-.3-.26c-.24-.69-.62-1.427-1.72-1.427c-.77 0-1.43.659-1.67 1.349c-.05.13-.16.23-.3.26c-.79.18-1.39.88-1.39 1.73s.59 1.55 1.39 1.73c.14.03.25.12.3.26c.24.69.9 1.18 1.67 1.18s1.43-.49 1.67-1.18c.05-.13.16-.23.3-.26c.8-.18 1.39-.89 1.39-1.73");
}

.g4z91_wyt {
  stop-color: var(--svg-color--b19168, #B19168);
}

.gcf0vykjf {
  stop-color: var(--svg-color--dfc1a0, #DFC1A0);
}

.gkxuclbyu {
  cx: 17px;
  cy: 7.714px;
  rx: 1.719px;
  ry: 1.714px;
}

.h-ot04a9y {
  stop-color: var(--svg-color--b59062, #B59062);
  stop-opacity: 0;
}

.hdz9ribyy {
  d: path("M21.44 10.243c0 .97-.764 1.757-1.668 1.757s-1.71-.787-1.71-1.757c0-.703.703-1.772 1.71-1.772c.904 0 1.668.802 1.668 1.772");
}

.hifiyq4xy {
  stop-color: var(--svg-color--c69864, #C69864);
  stop-opacity: 0;
}

.ho_dcj9xe {
  stop-color: var(--svg-color--9d9093, #9D9093);
}

.hw_cj3bmb {
  stop-color: var(--svg-color--a58065, #A58065);
  stop-opacity: 0;
}

.i873jibqh {
  cx: 23.551px;
  cy: 11.69px;
  rx: 1.655px;
  ry: 1.541px;
}

.iizvm2b2c {
  d: path("M17.188 10.4a.63.63 0 0 1-.43-.41c-.24-.7-.687-1.357-1.68-1.357s-1.45.667-1.68 1.387c-.07.19-.22.34-.41.4c-.76.25-1.38.99-1.3 1.85c.08.84.85 1.51 1.69 1.59c.76.07 1.43-.34 1.75-.97a1.772 1.772 0 0 0 3.35-.64c.05-.87-.51-1.62-1.29-1.85");
}

.ixhvjacwe {
  stop-color: var(--svg-color--deba8c, #DEBA8C);
}

.j4xvv9blx {
  stop-color: var(--svg-color--ffe6c2, #FFE6C2);
}

.jkjob7hts {
  stop-color: var(--svg-color--eac294, #EAC294);
}

.jx2lrr0tu {
  stop-color: var(--svg-color--a87658, #A87658);
  stop-opacity: 0;
}

.k9fwxwdhp {
  stop-color: var(--svg-color--fde0b2, #FDE0B2);
}

.kb21tlfgm {
  d: path("m9.99 13.863l1.29 16.157h3.08l-.66-16.376a1.856 1.856 0 0 0-1.86-1.776c-1.08 0-1.94.913-1.85 1.995");
}

.kgd6tw0nv {
  stop-color: var(--svg-color--f32064, #F32064);
}

.ky8p5ab7z {
  cx: 16.984px;
  cy: 10.215px;
  rx: 1.531px;
  ry: 1.466px;
}

.l33tyqbds {
  stop-color: var(--svg-color--c3976b, #C3976B);
  stop-opacity: 0;
}

.lfdbszbhp {
  d: path("M19.297 5.03c0-.81-.46-1.073-1.21-1.243a.42.42 0 0 1-.29-.24c-.23-.67-.61-1.547-1.71-1.547s-1.489.887-1.729 1.547c-.04.13-.15.21-.28.24c-.76.17-1.273.635-1.273 1.243c0 .81.652 1.48 1.402 1.65c.13.03.24.12.29.24c.23.66.86 1.13 1.6 1.13a1.7 1.7 0 0 0 1.6-1.13c.04-.13.16-.22.29-.24c.74-.17 1.31-.85 1.31-1.65");
}

.lxbatibbd {
  d: path("M16.168 12.25c-1.312 0-2.369 1.118-2.312 2.457l.585 15.121h3.454l.585-15.12c.047-1.34-1-2.458-2.312-2.458");
}

.m14-r0rif {
  stop-color: var(--svg-color--c83553, #C83553);
}

.m2948gb2d {
  cx: 14.209px;
  cy: 8.257px;
  rx: 1.597px;
  ry: 1.663px;
}

.m3p3qbb3n {
  stop-color: var(--svg-color--ab9674, #AB9674);
}

.m4k4_hm1f {
  d: path("M20.32 7.63c0-.81-.625-1.322-1.375-1.492a.42.42 0 0 1-.29-.24c-.23-.66-.532-1.445-1.66-1.445s-1.36.785-1.6 1.445c-.04.13-.16.22-.29.24c-.74.17-1.457.682-1.457 1.492c0 1.206.717 1.48 1.467 1.65c.13.03.24.12.29.24c.23.66.86 1.13 1.6 1.13a1.7 1.7 0 0 0 1.6-1.13c.04-.13.16-.22.29-.24c.75-.17 1.425-.84 1.425-1.65");
}

.m9xnkkbfq {
  cx: 12.226px;
  cy: 10.51px;
  fill: var(--svg-color--dbb080, #DBB080);
  rx: 1.531px;
  ry: 1.466px;
}

.ma1_ktryp {
  stop-color: var(--svg-color--b38d71, #B38D71);
}

.me8ohew6c {
  d: path("m18.67 13.644l-.65 16.376h3.08l1.29-16.157c.09-1.072-.77-1.995-1.86-1.995c-1 0-1.82.784-1.86 1.776");
}

.mu-hpbbnk {
  stop-color: var(--svg-color--fa1c79, #FA1C79);
}

.n4er2zrqn {
  stop-color: var(--svg-color--fffbd8, #FFFBD8);
}

.ncmrgtbfx {
  stop-color: var(--svg-color--fff5ca, #FFF5CA);
}

.nly9l8bff {
  stop-color: var(--svg-color--e6d2ad, #E6D2AD);
}

.nopmo_btx {
  stop-color: var(--svg-color--e6caae, #E6CAAE);
}

.np0v8rb8u {
  d: path("M11.583 10.217c0 .948-.718 1.717-1.603 1.717c-.886 0-1.676-.769-1.676-1.717c0-.687.689-1.701 1.676-1.701c.885 0 1.602.753 1.602 1.7");
}

.o_b54tapg {
  d: path("M24.41 11.868a2.02 2.02 0 0 0-2.02 1.846l-1.3 16.306h1.57c.7 0 1.3-.506 1.41-1.191L26.4 14.19c.2-1.22-.75-2.322-1.99-2.322");
}

.o2jirabwj {
  stop-color: var(--svg-color--99744a, #99744A);
}

.o4twgjg7c {
  stop-color: var(--svg-color--e0cfaf, #E0CFAF);
}

.oba0mltwe {
  stop-color: var(--svg-color--b27f4c, #B27F4C);
  stop-opacity: 0;
}

.og3-lhbfl {
  stop-color: var(--svg-color--ab9777, #AB9777);
}

.ogovfhq7c {
  fill: var(--svg-color--e7c8ff, #E7C8FF);
  d: path("m18.67 13.969l-.65 15.844h3.08l1.29-15.633c.09-1.037-.77-1.93-1.86-1.93c-1 0-1.82.759-1.86 1.719");
}

.ojfry0p0j {
  d: path("M8.02 11.868a2.018 2.018 0 0 0-2 2.322l2.33 14.639c.11.685.71 1.191 1.41 1.191h1.57l-1.3-16.306c-.07-1.043-.95-1.846-2.01-1.846");
}

.optlh7ayw {
  d: path("M23.587 10.223c0 .97-.765 1.757-1.668 1.757c-.904 0-1.71-.787-1.71-1.757c0-.703.703-1.773 1.71-1.773c.903 0 1.668.802 1.668 1.773");
}

.p_elfac8r {
  stop-color: var(--svg-color--a29175, #A29175);
}

.p4hr50bsc {
  cx: 18.583px;
  cy: 7.793px;
  rx: 1.667px;
  ry: 1.645px;
}

.pgj3l8mgx {
  fill: var(--svg-color--ff5a6d, #FF5A6D);
  d: path("M26.05 13.535c.423-.107-.379-1.232-1.506-1.232c1.526.717.936 1.377 1.506 1.232");
}

.pixg2pbuj {
  d: path("M18.636 6.133c0 .927-.691 1.679-1.545 1.679c-.853 0-1.614-.752-1.614-1.68c0-.671.664-1.663 1.614-1.663c.854 0 1.545.736 1.545 1.664");
}

.pnc5-7l0z {
  stop-color: var(--svg-color--d5b693, #D5B693);
}

.pr6zm83zw {
  stop-color: var(--svg-color--a42131, #A42131);
}

.ptuzt5bue {
  cx: 16.641px;
  cy: 12.15px;
  rx: 1.741px;
  ry: 1.718px;
}

.pyr4t6w2p {
  fill: var(--svg-color--e1c398, #E1C398);
  d: path("M13.3 11.73c0-.85-.59-1.48-1.39-1.66a.4.4 0 0 1-.3-.26c-.24-.69-.602-1.396-1.67-1.396c-1.067 0-1.43.706-1.67 1.396c-.05.13-.16.23-.3.26c-.79.17-1.39.81-1.39 1.66s.59 1.55 1.39 1.73c.14.03.25.12.3.26c.24.69.9 1.18 1.67 1.18s1.43-.49 1.67-1.18c.05-.13.16-.23.3-.26c.8-.18 1.39-.89 1.39-1.73");
}

.q395f8bzj {
  stop-color: var(--svg-color--cf9d67, #CF9D67);
}

.q6f3cl-wf {
  d: path("M8.02 12.188c-1.24 0-2.046 1.082-1.856 2.281L8.625 28.85c.11.673.386.744 1.086.744h1.398L9.844 14c-.07-1.024-.764-1.813-1.824-1.813");
}

.qebsbac7l {
  cx: 21.403px;
  cy: 11.723px;
  rx: 1.69px;
  ry: 1.574px;
}

.qob71wbbx {
  stop-color: var(--svg-color--ebd7b2, #EBD7B2);
}

.qtif9sbzz {
  stop-color: var(--svg-color--f02059, #F02059);
}

.qvypz5suf {
  stop-color: var(--svg-color--e8d4ae, #E8D4AE);
}

.r-8lrwf_z {
  stop-color: var(--svg-color--eec69c, #EEC69C);
}

.radpfinci {
  stop-color: var(--svg-color--b38e5e, #B38E5E);
}

.ravead3lt {
  fill: var(--svg-color--e7c8ff, #E7C8FF);
  d: path("m9.99 14.166l1.29 15.522h3.08l-.66-15.731c-.04-.954-.86-1.707-1.86-1.707c-1.08 0-1.94.877-1.85 1.916");
}

.rkstse44d {
  stop-color: var(--svg-color--f20f81, #F20F81);
  stop-opacity: 0;
}

.rl6ld-b3g {
  stop-color: var(--svg-color--b38d63, #B38D63);
  stop-opacity: 0;
}

.rvo07kbtv {
  stop-color: var(--svg-color--c99762, #C99762);
  stop-opacity: 0;
}

.rxxk8pb1u {
  stop-color: var(--svg-color--fffad8, #FFFAD8);
}

.s_rog4i9o {
  stop-color: var(--svg-color--ff4358, #FF4358);
}

.s7eubti3w {
  cx: 18.268px;
  cy: 14.057px;
  rx: 1.531px;
  ry: 1.466px;
}

.sjuhfhbew {
  d: path("M13.3 11.73c0-.85-.59-1.48-1.39-1.66a.4.4 0 0 1-.3-.26c-.24-.69-.602-1.396-1.67-1.396c-1.067 0-1.43.706-1.67 1.396c-.05.13-.16.23-.3.26c-.79.17-1.39.81-1.39 1.66s.59 1.55 1.39 1.73c.14.03.25.12.3.26c.24.69.9 1.18 1.67 1.18s1.43-.49 1.67-1.18c.05-.13.16-.23.3-.26c.8-.18 1.39-.89 1.39-1.73");
}

.snmpnslpa {
  stop-color: var(--svg-color--fffad9, #FFFAD9);
}

.spw5n3bym {
  stop-color: var(--svg-color--ba8f62, #BA8F62);
}

.srcooacwi {
  fill: var(--svg-color--fce1bb, #FCE1BB);
  d: path("M19.184 12.049c0 .97-.764 1.757-1.668 1.757s-1.71-.787-1.71-1.757c0-.703.703-1.773 1.71-1.773c.904 0 1.668.802 1.668 1.773");
}

.t-nj21bkj {
  fill: var(--svg-color--ff5a6d, #FF5A6D);
  d: path("M9.594 13.563c.487-.19-.753-1.433-2.094-1.266c2.188.672 1.607 1.455 2.094 1.265");
}

.tikfkst5o {
  cx: 12.03px;
  cy: 8.152px;
  r: 1.719px;
}

.u_gomu6jd {
  stop-color: var(--svg-color--f8ddb7, #F8DDB7);
}

.u5lcfgjzc {
  cx: 19.751px;
  cy: 7.926px;
  rx: 1.626px;
  ry: 1.625px;
}

.u6mwecb0a {
  stop-color: var(--svg-color--f6e8ff, #F6E8FF);
}

.ub0wlybpa {
  stop-color: var(--svg-color--ffecba, #FFECBA);
}

.uixwzj4nr {
  stop-color: var(--svg-color--bea281, #BEA281);
}

.unw796v7h {
  cx: 12.226px;
  cy: 10.51px;
  rx: 1.531px;
  ry: 1.466px;
}

.uqt1nbc4r {
  stop-color: var(--svg-color--fcdba9, #FCDBA9);
}

.us6yuiv0y {
  cx: 16.051px;
  cy: 5.447px;
  r: 1.719px;
}

.uy5x4fb-n {
  cx: 17.965px;
  cy: 5.289px;
  rx: 1.41px;
  ry: 1.406px;
}

.v_8ae5gvr {
  stop-color: var(--svg-color--d8107f, #D8107F);
}

.v_czs0nld {
  d: path("M16.738 10.405c0 .97-.765 1.757-1.668 1.757c-.904 0-1.71-.787-1.71-1.757c0-.703.703-1.772 1.71-1.772c.903 0 1.668.802 1.668 1.772");
}

.v1_f85y9k {
  stop-color: var(--svg-color--fff7d4, #FFF7D4);
}

.vntqjprsf {
  cx: 15.019px;
  cy: 11.934px;
  r: 1.719px;
}

.vzvitncif {
  stop-color: var(--svg-color--fffad8, #FFFAD8);
  stop-opacity: 0;
}

.vzx_ey6cj {
  stop-color: var(--svg-color--f71080, #F71080);
}

.w1frnv42f {
  stop-color: var(--svg-color--a5784d, #A5784D);
}

.wxwysb8rj {
  cx: 10.433px;
  cy: 8.179px;
  rx: 1.597px;
  ry: 1.586px;
}

.x5-xrj9zy {
  stop-color: var(--svg-color--c573fd, #C573FD);
}

.xc1pkrb1m {
  d: path("M21.297 6.415c0 .903-.674 1.635-1.504 1.635s-1.572-.732-1.572-1.635c0-.654.646-1.65 1.572-1.65c.83 0 1.504.747 1.504 1.65");
}

.xcornb71v {
  d: path("M17.672 3.746c0 .94-.7 1.7-1.565 1.7c-.864 0-1.636-.76-1.636-1.7c0-.68.673-1.686 1.636-1.686c.864 0 1.565.746 1.565 1.686");
}

.xfa24pbsl {
  stop-color: var(--svg-color--a79376, #A79376);
  stop-opacity: 0;
}

.xjea8_boq {
  stop-color: var(--svg-color--edb2ff, #EDB2FF);
}

.xvbe4f1jy {
  d: path("M13.695 6.62c0 .947-.716 1.714-1.6 1.714s-1.673-.767-1.673-1.714c0-.685.688-1.698 1.673-1.698c.884 0 1.6.751 1.6 1.698");
}

.xw_9lkh7t {
  stop-color: var(--svg-color--a19075, #A19075);
}

.xwzhtxb7d {
  cx: 21.312px;
  cy: 8.01px;
  rx: 1.599px;
  ry: 1.578px;
}

.xy6x6cchm {
  stop-color: var(--svg-color--e9a9ff, #E9A9FF);
}

.ycywsccgi {
  stop-color: var(--svg-color--dab381, #DAB381);
}

.yeh9qwbdz {
  stop-color: var(--svg-color--d52853, #D52853);
  stop-opacity: 0;
}

.yguu9g4lg {
  stop-color: var(--svg-color--fb3a4a, #FB3A4A);
}

.ylxelbbvo {
  stop-color: var(--svg-color--a47250, #A47250);
}

.ynli1k0ru {
  cx: 22.039px;
  cy: 11.738px;
  r: 1.719px;
}

.z20j-vtrw {
  cx: 9.864px;
  cy: 11.59px;
  r: 1.719px;
}

.z6cl-3a6w {
  stop-color: var(--svg-color--b09970, #B09970);
}

.zbmg46bgb {
  stop-color: var(--svg-color--ffeebc, #FFEEBC);
}

.zcn4-kcgy {
  cx: 18.268px;
  cy: 14.057px;
  fill: var(--svg-color--dbb080, #DBB080);
  rx: 1.531px;
  ry: 1.466px;
}

</style>
