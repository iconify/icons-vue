<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iS5imNa" class="jz3bb8ala"/></defs><g class="ft5dv1b6b"><g filter="url(#iDMe7Pc)"><rect fill="url(#iIk56Pc)" transform="rotate(-45 12.963 13.403)" class="etm0labvf"/></g><g filter="url(#iuYCjid)"><rect fill="url(#i96BfVc)" transform="scale(-1 1)rotate(-45 -3.014 35.5)" class="ffese-y7m"/></g><rect fill="url(#iIRexfS)" transform="scale(-1 1)rotate(-45 -3.014 35.5)" class="ffese-y7m"/><g filter="url(#iWfEQsd)"><path fill="url(#im3tg0d)" class="is89u6ban"/><path fill="url(#iX1BTZW)" class="is89u6ban"/></g><g filter="url(#ivK6gle)"><rect fill="url(#i8mbSfd)" transform="scale(-1 1)rotate(-45 6.585 29.734)" class="z_5s59bdn"/></g><g filter="url(#i9P4bnd)"><path class="g11vnob-s"/></g><g filter="url(#iIC9gze)"><path class="ytl8wkbiv"/></g><g filter="url(#iSVxInd)"><path class="s99p66ikg"/></g><g filter="url(#ia2wvel)"><path class="pv3dgeoha"/></g><g filter="url(#iYorMxd)"><path fill="url(#iCFMXfc)" clip-rule="evenodd" class="m9x84p2nl"/><path fill="url(#igdg57B)" clip-rule="evenodd" class="m9x84p2nl"/><path fill="url(#iIII5Lc)" clip-rule="evenodd" class="m9x84p2nl"/><path fill="url(#ixqJyKc)" clip-rule="evenodd" class="m9x84p2nl"/><path fill="url(#idVZuKb)" clip-rule="evenodd" class="m9x84p2nl"/><path fill="url(#i2CfrAc)" clip-rule="evenodd" class="m9x84p2nl"/><path fill="url(#ifZLWyd)" clip-rule="evenodd" class="m9x84p2nl"/><path fill="url(#iDfWUjd)" clip-rule="evenodd" class="m9x84p2nl"/><path fill="url(#i3Gqiei)" clip-rule="evenodd" class="m9x84p2nl"/><path fill="url(#iW8X7ia)" clip-rule="evenodd" class="m9x84p2nl"/><path fill="url(#iRHyT7b)" clip-rule="evenodd" class="m9x84p2nl"/></g><g filter="url(#iEUk76d)"><rect class="vsr9738qr"/><rect fill="url(#i8a16yi)" class="kq9b5xnhm"/></g><g filter="url(#ikcLrKe)"><path fill="url(#ioitlCc)" class="dv6-6mbxj"/></g><path fill="url(#ipQ5Pnc)" class="dv6-6mbxj"/><path fill="url(#i8KfH3d)" class="dv6-6mbxj"/><path fill="url(#iEdEbnd)" class="dv6-6mbxj"/><path class="dxabh57cr"/><path fill="url(#i7QnpSd)" class="mh57-sx2c"/><path fill="url(#iJU4nte)" class="mh57-sx2c"/><path fill="url(#iuqcTFd)" class="j-tweow-u"/><path fill="url(#iijtwCj)" class="j-tweow-u"/><path fill="url(#iq7Rt9d)" class="j-tweow-u"/><path fill="url(#iIZjT3c)" class="j-tweow-u"/><path fill="url(#iuP6NMd)" class="eayua2tob"/><path fill="url(#iDv7Hjb)" class="eayua2tob"/><g filter="url(#ii4eeYb)"><path class="is80icbry"/><path fill="url(#iA2vlQb)" class="l99mnwbez"/><path fill="url(#iLIXNRI)" class="l99mnwbez"/></g><path fill="url(#iqP8udb)" class="z45oacyxz"/><path fill="url(#ihvNS4d)" class="z45oacyxz"/><circle fill="url(#iLjKZQG)" class="z30kudb-o"/><g filter="url(#iRN0esd)"><path class="f6xfjgb1y"/><path fill="url(#iCc4k6d)" class="k-27-x9ja"/></g><g filter="url(#ieJ116U)"><path class="m3bis1bwo"/></g><g filter="url(#iPI0NVv)"><path class="e9b9gabbg"/><path fill="url(#iXb4XGc)" class="xgq6w0b8s"/><path fill="url(#iQj6ttd)" class="xgq6w0b8s"/></g><g filter="url(#iXKsm1b)"><path class="vt36tzbwu"/></g><path fill="url(#iWroyTd)" class="js5y7fb5r"/><path fill="url(#izNTKdc)" class="js5y7fb5r"/><path fill="url(#iiD6wCc)" class="js5y7fb5r"/><path fill="url(#iKByDMe)" class="js5y7fb5r"/><path fill="url(#iBJnkMe)" class="js5y7fb5r"/><path fill="url(#im8PoCb)" class="b6pcaeboe"/><path fill="url(#iZqj7nm)" class="b6pcaeboe"/><g filter="url(#iGFTeSc)"><path class="zepkmwb6a"/><path fill="url(#iaToRcc)" class="uw9pt0beg"/><path fill="url(#i4dfdjc)" class="uw9pt0beg"/><path fill="url(#ihLxlKX)" class="uw9pt0beg"/></g><g filter="url(#iLKPrEd)"><path stroke="url(#ijXbr6k)" class="iqsdfibon"/></g><path fill="url(#irGgnec)" class="b-q2f27bj"/><path fill="url(#iHeluSb)" class="ju-3ieb_x"/><g filter="url(#iYWDefm)"><path fill="url(#iGsphXd)" class="ehxq-j66x"/></g><g filter="url(#iCXW0yc)"><path fill="url(#ihXhJDd)" class="p3hzj_b1z"/><path fill="url(#iH0ZBKe)" class="p3hzj_b1z"/></g><g filter="url(#if9zRee)"><path class="uoh8f1zsw"/><path fill="url(#idur1Fs)" class="v3rm7ubkk"/></g><g filter="url(#iGl7bUC)"><path class="a07rc2b8w"/><path fill="url(#iop7PnU)" class="wiqvl759c"/></g><g filter="url(#i6VVLTc)"><path fill="url(#iPwBWRd)" class="q05-1fbvc"/><path fill="url(#ibYtEnV)" class="q05-1fbvc"/><path fill="url(#iRxZ1Sb)" class="q05-1fbvc"/><path fill="url(#iULPbLb)" class="q05-1fbvc"/><path fill="url(#inzfTId)" class="q05-1fbvc"/><path fill="url(#ip67EbV)" class="q05-1fbvc"/><path fill="url(#ioULTob)" class="q05-1fbvc"/><path fill="url(#iQikdka)" class="q05-1fbvc"/></g><path fill="url(#iwQQyxe)" class="q05-1fbvc"/><path fill="url(#iPtAWqe)" class="q05-1fbvc"/><path fill="url(#imvr7TF)" class="q05-1fbvc"/><g filter="url(#ifSF1Oe)"><path class="q2-7ses9m"/></g><g filter="url(#imi4eJc)"><path class="o6epg8b8b"/><path fill="url(#icahMhd)" class="y9-pzrhvv"/><path fill="url(#i3MdtTc)" class="y9-pzrhvv"/><path fill="url(#iGaQ7jr)" class="y9-pzrhvv"/><path fill="url(#il9lgTd)" class="y9-pzrhvv"/></g><g filter="url(#ibU6Kkb)"><use href="#iS5imNa"/><path stroke="url(#iPnsnsc)" class="iqfapqb5l"/></g><use href="#iS5imNa"/><g filter="url(#i3bGg5b)"><path class="on1ylhgiq"/></g><g filter="url(#idVLNJe)"><path class="dcv5f0bvr"/></g><g filter="url(#iQnhFuc)"><path class="fa4iypkyf"/></g><g filter="url(#iN9XR3b)"><path clip-rule="evenodd" class="d8hzqublk"/></g><path class="x8ofsbchc"/><path fill="url(#iuUozjb)" class="ht3z4fljp"/><path class="rwna8n39m"/><g filter="url(#isOugtT)"><path class="kj5xpeq-h"/><path fill="url(#iFkhbUc)" class="ewt2hy66x"/></g><g filter="url(#ix1fQFe)"><path fill="url(#iw9Rpdw)" class="nkpzm4bwz"/></g><path class="zyjyshkcz"/><path fill="url(#iKhC9ob)" class="ht353fb7h"/><path class="fclrx3xdq"/><g filter="url(#iyjFA2b)"><path fill="url(#ix8otYb)" class="p-259bkld"/></g><g filter="url(#i6OoyJb)"><ellipse transform="rotate(-27.914 14.958 7.571)" class="bf_mq753d"/><ellipse fill="url(#iQ86r9b)" transform="rotate(-27.914 14.958 7.571)" class="zkuiccvvk"/></g><g filter="url(#i2CQmjd)"><path class="fatyc1wuz"/><path fill="url(#igzX9Pc)" class="q0xlc4b5d"/><path fill="url(#iTDNYAc)" class="q0xlc4b5d"/></g><g filter="url(#i8VRCQe)"><path class="easprfbok"/></g><defs><radialGradient id="iIk56Pc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.87825 -2.80633 3.32449 -2.22505 16.838 21.301)" gradientUnits="userSpaceOnUse"><stop class="vvvf-bx0b"/><stop offset="1" class="rivz2obdn"/></radialGradient><radialGradient id="i96BfVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.75045 -10.1868 0 3.092 .28)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="vm1_cbcaw"/><stop offset="1" class="k356i5yuc"/></radialGradient><radialGradient id="iIRexfS" cx="0" cy="0" r="1" gradientTransform="rotate(-58.508 8.125 5.097)scale(2.87644 1.6899)" gradientUnits="userSpaceOnUse"><stop offset=".419" class="uodqeubaz"/><stop offset="1" class="pha_6_rva"/></radialGradient><radialGradient id="i8mbSfd" cx="0" cy="0" r="1" gradientTransform="matrix(.46404 .88388 -1.60027 .84014 1.815 6.289)" gradientUnits="userSpaceOnUse"><stop class="x6_m96bez"/><stop offset="1" class="s2ceddo5o"/></radialGradient><radialGradient id="igdg57B" cx="0" cy="0" r="1" gradientTransform="rotate(97.539 4.02 11.45)scale(2.00864 2.5092)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iIII5Lc" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 5.946 6.784)scale(1.51882 1.99561)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="ixqJyKc" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 4.987 7.423)scale(.94004 .72182)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="idVZuKb" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 5.069 7.5)scale(1.08104 .76149)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="i2CfrAc" cx="0" cy="0" r="1" gradientTransform="matrix(.60031 1.14206 -1.58535 .83332 14.492 4.354)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="ifZLWyd" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 8.199 6.479)scale(.89036 1.24425)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iDfWUjd" cx="0" cy="0" r="1" gradientTransform="matrix(-.80526 .23427 -.48855 -1.6793 19.31 7.502)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="i3Gqiei" cx="0" cy="0" r="1" gradientTransform="matrix(-1.22986 .30748 -.39169 -1.56667 19.046 8.995)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iW8X7ia" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 11.351 -3.253)scale(1.22311 .96741)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iRHyT7b" cx="0" cy="0" r="1" gradientTransform="matrix(.65687 .0689 -.11164 1.06432 13.347 7.486)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="ioitlCc" cx="0" cy="0" r="1" gradientTransform="rotate(141.509 11.379 5.864)scale(3.31383 3.4775)" gradientUnits="userSpaceOnUse"><stop class="nw_aknb7y"/><stop offset="1" class="pt-h1ccpi"/></radialGradient><radialGradient id="ipQ5Pnc" cx="0" cy="0" r="1" gradientTransform="matrix(.35156 .89062 -.53122 .2097 23.217 2.575)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="vw5e4lbve"/><stop offset="1" class="v_k-57lgf"/></radialGradient><radialGradient id="i8KfH3d" cx="0" cy="0" r="1" gradientTransform="rotate(78.781 8.915 17.107)scale(1.04377 .3506)" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="qlfye6p8o"/></radialGradient><radialGradient id="iEdEbnd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6346 .22 -.12993 -.3748 24.731 3.528)" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="qlfye6p8o"/></radialGradient><radialGradient id="iq7Rt9d" cx="0" cy="0" r="1" gradientTransform="matrix(-.26562 3.7132 -.85217 -.06096 15.406 25.564)" gradientUnits="userSpaceOnUse"><stop offset=".085" class="j7smtkbjw"/><stop offset="1" class="xgtw6wrae"/></radialGradient><radialGradient id="iDv7Hjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.07031 -.19922 1.40814 -.49699 14.503 29.465)" gradientUnits="userSpaceOnUse"><stop class="p5u-_cblu"/><stop offset="1" class="uowu7rarb"/></radialGradient><radialGradient id="iLIXNRI" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 2.2133 -.98624 .20888 19.32 18.972)" gradientUnits="userSpaceOnUse"><stop offset=".091" class="fgis5qzvv"/><stop offset="1" class="blsn939-n"/></radialGradient><radialGradient id="ihvNS4d" cx="0" cy="0" r="1" gradientTransform="matrix(.28516 -.16406 .55035 .95656 16.253 27.216)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="s3hklabia"/><stop offset="1" class="n5igrlbfw"/></radialGradient><radialGradient id="iLjKZQG" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 .1914 -.31978 .73092 6.135 15.73)" gradientUnits="userSpaceOnUse"><stop class="qya8vwbkf"/><stop offset="1" class="d0qi1-blu"/></radialGradient><radialGradient id="iCc4k6d" cx="0" cy="0" r="1" gradientTransform="rotate(-38.729 27.876 -1.303)scale(8.09176 6.39568)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="tj824objr"/><stop offset="1" class="lz6zpisqv"/></radialGradient><radialGradient id="iXb4XGc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.16876 .9375 -.156 -.19448 8.314 14.542)" gradientUnits="userSpaceOnUse"><stop class="gbuovhboa"/><stop offset="1" class="yq1j9wb8r"/></radialGradient><radialGradient id="iQj6ttd" cx="0" cy="0" r="1" gradientTransform="matrix(.8047 -.67969 .45175 .53484 7.442 15.269)" gradientUnits="userSpaceOnUse"><stop offset=".644" class="scofoabvh"/><stop offset="1" class="b4zzki-mx"/></radialGradient><radialGradient id="iiD6wCc" cx="0" cy="0" r="1" gradientTransform="matrix(.10937 1.0625 -3.8587 .39722 15.607 10.59)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="g7dj32byf"/><stop offset="1" class="mv_j9hb5m"/></radialGradient><radialGradient id="im8PoCb" cx="0" cy="0" r="1" gradientTransform="matrix(.13998 1.09283 -2.8057 .35939 15.554 10.298)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="qggerob2g"/><stop offset="1" class="pn9klvbrs"/></radialGradient><radialGradient id="iZqj7nm" cx="0" cy="0" r="1" gradientTransform="matrix(-.82013 .35725 -.19955 -.45811 16.848 10.618)" gradientUnits="userSpaceOnUse"><stop class="wfj08-bsk"/><stop offset="1" class="k9wpgpx3v"/></radialGradient><radialGradient id="ihXhJDd" cx="0" cy="0" r="1" gradientTransform="matrix(1.08715 -.49416 .60335 1.32736 17.794 8.066)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="iH0ZBKe" cx="0" cy="0" r="1" gradientTransform="matrix(.57469 .32212 -.09107 .16247 18.244 7.14)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="idur1Fs" cx="0" cy="0" r="1" gradientTransform="matrix(.65948 -.04906 .03835 .51553 17.948 7.923)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="iop7PnU" cx="0" cy="0" r="1" gradientTransform="rotate(180 7.01 3.937)scale(.46121)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="iPwBWRd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.84057 1.30988 -1.75326 -3.80206 17.278 7.64)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="ibYtEnV" cx="0" cy="0" r="1" gradientTransform="matrix(-.95228 .41903 -.29181 -.66316 16.89 8.012)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="iRxZ1Sb" cx="0" cy="0" r="1" gradientTransform="rotate(-71.832 14.778 -5.173)scale(1.80582 2.29125)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="iULPbLb" cx="0" cy="0" r="1" gradientTransform="rotate(99.884 5.103 10.656)scale(3.26891 4.0861)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="mg10me7tz"/><stop offset="1" class="kitn3twkh"/></radialGradient><radialGradient id="inzfTId" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.002 5.015)scale(3.07373 5.29201)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="ip67EbV" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.50262 .61686 0 17.035 7.456)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="ioULTob" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.57327 .657 0 15.123 7.357)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="iQikdka" cx="0" cy="0" r="1" gradientTransform="rotate(105.092 5.848 9.594)scale(1.4597 1.168)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="iwQQyxe" cx="0" cy="0" r="1" gradientTransform="matrix(-.56137 0 0 -2.81524 18.255 8.106)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="iPtAWqe" cx="0" cy="0" r="1" gradientTransform="matrix(-.34805 -.56643 .6019 -.36984 17.617 10.148)" gradientUnits="userSpaceOnUse"><stop class="ni-4se4rm"/><stop offset="1" class="wsh5tsbcf"/></radialGradient><radialGradient id="imvr7TF" cx="0" cy="0" r="1" gradientTransform="matrix(.76435 -.68245 .81032 .90756 14.267 10.142)" gradientUnits="userSpaceOnUse"><stop class="z26rrllgi"/><stop offset="1" class="fs9pa7bci"/></radialGradient><radialGradient id="icahMhd" cx="0" cy="0" r="1" gradientTransform="matrix(-.19897 -.89277 .27514 -.06132 16.372 8.425)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="il9lgTd" cx="0" cy="0" r="1" gradientTransform="matrix(-.34042 0 0 -.09517 16.267 8.516)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iuUozjb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35436 -.56365 0 16.983 7.613)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iFkhbUc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.813 10.315 -.31)scale(.16522 .22748)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iKhC9ob" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35436 -.56365 0 15.076 7.613)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iQ86r9b" cx="0" cy="0" r="1" gradientTransform="matrix(-.00338 -.2158 .25939 -.00406 14.951 7.709)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="igzX9Pc" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 7.031 7.47)scale(2.12834 3.47972)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iTDNYAc" cx="0" cy="0" r="1" gradientTransform="matrix(-.09187 .59715 -1.28474 -.19765 16.067 4.531)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><filter id="iDMe7Pc" width="7.335" height="7.37" x="13.891" y="10.901" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.075" dy=".08"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.662745 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1148"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.08"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.745098 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1148" result="effect2_innerShadow_4002_1148"/></filter><filter id="iuYCjid" width="10.517" height="10.517" x="14.14" y="4.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1148"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1148" result="effect2_innerShadow_4002_1148"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.788235 0 0 0 0 0.827451 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1148" result="effect3_innerShadow_4002_1148"/></filter><filter id="iWfEQsd" width="9.391" height="10.922" x="7.466" y="4.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1148"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.545098 0 0 0 0 0.811765 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1148" result="effect2_innerShadow_4002_1148"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.521569 0 0 0 0 0.662745 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1148" result="effect3_innerShadow_4002_1148"/></filter><filter id="ivK6gle" width="7.298" height="7.298" x="10.845" y="10.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.654902 0 0 0 0 0.905882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1148"/></filter><filter id="i9P4bnd" width="3.908" height="3.642" x="9.545" y="9.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1148"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1148" result="effect2_dropShadow_4002_1148"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1148" result="shape"/></filter><filter id="iIC9gze" width="6.45" height="6.548" x="9.62" y="5.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1148"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.6 0 0 0 0 0.941176 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1148" result="effect2_dropShadow_4002_1148"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1148" result="shape"/></filter><filter id="iSVxInd" width="3.908" height="3.642" x="18.631" y="9.059" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1148"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.968627 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1148" result="effect2_dropShadow_4002_1148"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1148" result="shape"/></filter><filter id="ia2wvel" width="6.45" height="6.548" x="16.014" y="5.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1148"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.968627 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_dropShadow_4002_1148" result="effect2_dropShadow_4002_1148"/><feBlend in="SourceGraphic" in2="effect2_dropShadow_4002_1148" result="shape"/></filter><filter id="iYorMxd" width="6.809" height="7.309" x="12.75" y="3.399" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1148"/></filter><filter id="iEUk76d" width=".989" height="4.833" x="22.355" y="4.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".35" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.254902 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1148"/></filter><filter id="ikcLrKe" width="4.084" height="3.799" x="20.732" y="2.116" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.05"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.639216 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1148"/></filter><filter id="ii4eeYb" width="5.091" height="8.843" x="15.749" y="18.772" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4 0 0 0 0 0.266667 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1148"/></filter><filter id="iRN0esd" width="7.578" height="5.434" x="6.015" y="10.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.270588 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1148"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.286275 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1148" result="effect2_innerShadow_4002_1148"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.435294 0 0 0 0 0.309804 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1148" result="effect3_innerShadow_4002_1148"/></filter><filter id="ieJ116U" width="1.692" height="1.561" x="6.722" y="14.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.592157 0 0 0 0 0.203922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1148"/></filter><filter id="iPI0NVv" width="1.692" height="1.561" x="6.722" y="14.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.266667 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1148"/></filter><filter id="iXKsm1b" width="5.398" height="7.21" x="18.218" y="7.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.6"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.235294 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1148"/></filter><filter id="iGFTeSc" width="6.349" height="5.065" x="13.14" y="16.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.329412 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1148"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.415686 0 0 0 0 0.717647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1148" result="effect2_innerShadow_4002_1148"/></filter><filter id="iLKPrEd" width="4.609" height="5.161" x="18.951" y="9.386" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1148" stdDeviation=".25"/></filter><filter id="iYWDefm" width="1.556" height="1.406" x="13.28" y="7.171" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1148"/></filter><filter id="iCXW0yc" width="1.406" height="1.656" x="17.435" y="6.921" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1148"/></filter><filter id="if9zRee" width="1.938" height="1.938" x="17.169" y="6.905" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1148" stdDeviation=".25"/></filter><filter id="iGl7bUC" width="1.438" height="1.438" x="13.272" y="7.155" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1148" stdDeviation=".125"/></filter><filter id="i6VVLTc" width="4.451" height="4.801" x="13.804" y="5.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1148"/></filter><filter id="ifSF1Oe" width="1.82" height="2.171" x="15.049" y="7.153" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1148" stdDeviation=".25"/></filter><filter id="imi4eJc" width="1.02" height="1.371" x="15.52" y="7.493" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1148" stdDeviation=".05"/></filter><filter id="ibU6Kkb" width="1.642" height=".692" x="15.208" y="8.887" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1148" stdDeviation=".025"/></filter><filter id="i3bGg5b" width="1.424" height=".561" x="16.329" y="7.261" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1148"/></filter><filter id="idVLNJe" width="1.424" height=".561" x="14.307" y="7.261" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1148"/></filter><filter id="iQnhFuc" width="1.184" height=".589" x="14.367" y="6.526" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1148"/></filter><filter id="iN9XR3b" width="1.184" height=".589" x="16.732" y="6.526" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1148"/></filter><filter id="isOugtT" width=".456" height=".417" x="16.606" y="7.365" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1148" stdDeviation=".05"/></filter><filter id="ix1fQFe" width=".615" height=".624" x="16.916" y="7.341" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1148" stdDeviation=".1"/></filter><filter id="iyjFA2b" width=".656" height=".68" x="14.976" y="7.314" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1148" stdDeviation=".1"/></filter><filter id="i6OoyJb" width=".511" height=".42" x="14.702" y="7.361" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1148" stdDeviation=".05"/></filter><filter id="i2CQmjd" width="3.989" height="2.607" x="14.421" y="4.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1148"/><feGaussianBlur result="effect2_foregroundBlur_4002_1148" stdDeviation=".05"/></filter><filter id="i8VRCQe" width="2.952" height="1.618" x="15.703" y="5.166" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1148" stdDeviation=".2"/></filter><linearGradient id="im3tg0d" x1="8.529" x2="12.668" y1="5.843" y2="9.982" gradientUnits="userSpaceOnUse"><stop class="tx327ubjh"/><stop offset="1" class="vxhtc9kgk"/></linearGradient><linearGradient id="iX1BTZW" x1="11.132" x2="10.694" y1="12.966" y2="9.06" gradientUnits="userSpaceOnUse"><stop class="ubeqdvb2g"/><stop offset="1" class="redus_bqs"/></linearGradient><linearGradient id="iCFMXfc" x1="18.079" x2="15.107" y1="4.837" y2="10.342" gradientUnits="userSpaceOnUse"><stop class="c1nwhtznm"/><stop offset="1" class="ogqxd-bue"/></linearGradient><linearGradient id="i8a16yi" x1="22.921" x2="22.547" y1="5.345" y2="6.127" gradientUnits="userSpaceOnUse"><stop offset=".167" class="zqax3vbfg"/><stop offset="1" class="z0_tnl66g"/></linearGradient><linearGradient id="i7QnpSd" x1="18.792" x2="16.991" y1="16.247" y2="16.247" gradientUnits="userSpaceOnUse"><stop class="utipi7g6i"/><stop offset="1" class="edfwaihfg"/></linearGradient><linearGradient id="iJU4nte" x1="13.267" x2="15.007" y1="16.431" y2="16.431" gradientUnits="userSpaceOnUse"><stop class="bjaenibkq"/><stop offset="1" class="louyt9b7g"/></linearGradient><linearGradient id="iuqcTFd" x1="15.345" x2="13.875" y1="24.348" y2="24.348" gradientUnits="userSpaceOnUse"><stop offset=".267" class="jnedts9qu"/><stop offset=".945" class="jjvamgr7p"/></linearGradient><linearGradient id="iijtwCj" x1="15.517" x2="15.017" y1="26.035" y2="26.009" gradientUnits="userSpaceOnUse"><stop class="uj9y6sbjo"/><stop offset="1" class="pnh1u2g5u"/></linearGradient><linearGradient id="iIZjT3c" x1="13.318" x2="13.75" y1="24.833" y2="24.833" gradientUnits="userSpaceOnUse"><stop class="o5s4dcbqc"/><stop offset="1" class="migaloo2k"/></linearGradient><linearGradient id="iuP6NMd" x1="15.197" x2="13.71" y1="28.891" y2="28.891" gradientUnits="userSpaceOnUse"><stop class="q54t2dj5c"/><stop offset=".159" class="wiovp2snp"/><stop offset=".453" class="wiovp2snp"/><stop offset="1" class="em6gbkb2t"/></linearGradient><linearGradient id="iA2vlQb" x1="18.825" x2="18.304" y1="23.645" y2="23.388" gradientUnits="userSpaceOnUse"><stop class="s5lr0-bjd"/><stop offset="1" class="p4dvxyhsv"/></linearGradient><linearGradient id="iqP8udb" x1="15.835" x2="17.116" y1="26.357" y2="27.044" gradientUnits="userSpaceOnUse"><stop class="wu3iwcc6r"/><stop offset="1" class="evpxnsbrs"/></linearGradient><linearGradient id="iWroyTd" x1="16.03" x2="16.03" y1="10.709" y2="15.544" gradientUnits="userSpaceOnUse"><stop class="z9-ns_cqv"/><stop offset="1" class="voshhcbhx"/></linearGradient><linearGradient id="izNTKdc" x1="13.267" x2="15.139" y1="15.544" y2="15.544" gradientUnits="userSpaceOnUse"><stop class="w8z9c1bqk"/><stop offset="1" class="d1stbzbsu"/></linearGradient><linearGradient id="iKByDMe" x1="18.792" x2="16.607" y1="13.948" y2="13.948" gradientUnits="userSpaceOnUse"><stop class="eo1g38slj"/><stop offset="1" class="s89mq5-5f"/></linearGradient><linearGradient id="iBJnkMe" x1="18.96" x2="17.959" y1="14.225" y2="14.225" gradientUnits="userSpaceOnUse"><stop offset=".049" class="bpn-u35sy"/><stop offset="1" class="ukj380brt"/></linearGradient><linearGradient id="iaToRcc" x1="13.14" x2="15.351" y1="18.9" y2="18.9" gradientUnits="userSpaceOnUse"><stop class="c2g5jlmdp"/><stop offset="1" class="j9-ktqfbw"/></linearGradient><linearGradient id="i4dfdjc" x1="19.255" x2="16.729" y1="18.309" y2="18.9" gradientUnits="userSpaceOnUse"><stop offset=".349" class="hta3d8bay"/><stop offset="1" class="yezlp2beb"/></linearGradient><linearGradient id="ihLxlKX" x1="19.489" x2="18.607" y1="18.386" y2="18.614" gradientUnits="userSpaceOnUse"><stop class="wg5i7s-vd"/><stop offset="1" class="pql-90wca"/></linearGradient><linearGradient id="ijXbr6k" x1="22.451" x2="19.857" y1="11.683" y2="13.527" gradientUnits="userSpaceOnUse"><stop offset=".453" class="a3_z2xhkr"/><stop offset="1" class="k5r_gj7_l"/></linearGradient><linearGradient id="irGgnec" x1="12.937" x2="19.259" y1="10.014" y2="10.014" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iHeluSb" x1="12.937" x2="19.259" y1="10.001" y2="10.001" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iGsphXd" x1="13.303" x2="13.844" y1="7.912" y2="7.912" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="i3MdtTc" x1="15.62" x2="16.03" y1="8.455" y2="8.455" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="iGaQ7jr" x1="16.03" x2="16.03" y1="8.804" y2="8.538" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="iPnsnsc" x1="15.565" x2="15.766" y1="9.42" y2="9.109" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="iw9Rpdw" x1="17.323" x2="17.185" y1="7.637" y2="7.721" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ix8otYb" x1="15.401" x2="15.264" y1="7.637" y2="7.721" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-fairy-medium-dark" /></template>
<style>
.a07rc2b8w {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M13.991 8.343a.47.47 0 1 0 0-.938a.47.47 0 0 0 0 .938");
}

.a3_z2xhkr {
  stop-color: var(--svg-color--a17e73, #A17E73);
}

.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
}

.b-q2f27bj {
  d: path("M16.253 10.001q.166.008.338.022a10 10 0 0 0-.338-.022");
}

.b4zzki-mx {
  stop-color: var(--svg-color--7d534e, #7D534E);
}

.b6pcaeboe {
  d: path("M15.07 10.136v.699a.24.24 0 0 0 .065.157c.135.147.326.443.456.87c.06.195.233.342.437.342a.47.47 0 0 0 .437-.342c.13-.427.322-.723.457-.87a.24.24 0 0 0 .065-.157v-.699z");
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.bf_mq753d {
  cx: 14.958px;
  cy: 7.571px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.17px;
  ry: 0.086px;
}

.bjaenibkq {
  stop-color: var(--svg-color--839927, #839927);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.blsn939-n {
  stop-color: var(--svg-color--a37b73, #A37B73);
  stop-opacity: 0;
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.bpn-u35sy {
  stop-color: var(--svg-color--9771bf, #9771BF);
}

.c1nwhtznm {
  stop-color: var(--svg-color--45363a, #45363A);
}

.c2g5jlmdp {
  stop-color: var(--svg-color--67568f, #67568F);
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
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

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.d0qi1-blu {
  stop-color: var(--svg-color--703d57, #703D57);
}

.d1stbzbsu {
  stop-color: var(--svg-color--8664c8, #8664C8);
  stop-opacity: 0;
}

.d8hzqublk {
  fill: var(--svg-color--352827, #352827);
  fill-rule: evenodd;
  d: path("m17.66 6.898l-.06.1za.117.117 0 0 1-.12.2h-.003l-.05-.026a1 1 0 0 0-.149-.059a1 1 0 0 0-.468-.04a.117.117 0 0 1-.04-.23c.223-.04.43 0 .58.047a1.4 1.4 0 0 1 .243.104l.004.002l.002.001");
}

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
  stop-opacity: 0;
}

.dcv5f0bvr {
  fill: var(--svg-color--272528, #272528);
  d: path("M15.53 7.625c-.115-.203-.291-.364-.67-.364a.72.72 0 0 0-.47.16c-.117.095-.1.217-.01.262l.243.139c.285-.092.6-.105.908-.197");
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.dv6-6mbxj {
  d: path("M22.5 2.293a.22.22 0 0 1 .4.001l.414.896a.22.22 0 0 0 .174.126l.983.115a.22.22 0 0 1 .129.376l-.735.716a.22.22 0 0 0-.062.2l.185.926a.22.22 0 0 1-.319.237l-.864-.459a.22.22 0 0 0-.207 0l-.87.462a.22.22 0 0 1-.319-.235l.177-.932a.22.22 0 0 0-.062-.198l-.726-.718a.22.22 0 0 1 .129-.375l.98-.115a.22.22 0 0 0 .174-.125z");
}

.dxabh57cr {
  fill: var(--svg-color--aed62f, #AED62F);
  d: path("M13.267 16.39v-.861h5.525v.82a49 49 0 0 1-5.525.041");
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e9b9gabbg {
  fill: var(--svg-color--7e5a4e, #7E5A4E);
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.637-.217.723-.129c.1.103.145.418-.093.696c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.014-.561.256-.764");
}

.easprfbok {
  fill: var(--svg-color--47383d, #47383D);
  d: path("m17.08 6.048l-.622.114a.3.3 0 1 1-.055-.596h1.023c.604 0 .805.61.83.818a1.37 1.37 0 0 0-1.175-.336");
}

.eayua2tob {
  d: path("m13.312 28.098l.006 1.49c0 .169.164.288.322.231a7 7 0 0 0 1.287-.603a.47.47 0 0 0 .215-.373l.055-.894z");
}

.edfwaihfg {
  stop-color: var(--svg-color--bff332, #BFF332);
  stop-opacity: 0;
}

.ehxq-j66x {
  d: path("M13.983 8.577a.703.703 0 1 0 0-1.406a.703.703 0 0 0 0 1.406");
}

.em6gbkb2t {
  stop-color: var(--svg-color--4c3866, #4C3866);
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.eo1g38slj {
  stop-color: var(--svg-color--ac8de6, #AC8DE6);
}

.etm0labvf {
  width: 4.843px;
  height: 8.191px;
  x: 12.963px;
  y: 13.403px;
  rx: 2.422px;
}

.evpxnsbrs {
  stop-color: var(--svg-color--66488c, #66488C);
}

.ewt2hy66x {
  d: path("M16.955 7.487c.028.037-.03.083-.096.132c-.067.05-.115.084-.143.047s.003-.107.069-.157s.142-.059.17-.022");
}

.f6xfjgb1y {
  fill: var(--svg-color--7d534e, #7D534E);
  d: path("M13.28 11.279c.194-.188.29-.23.313-.227v2.59c-.399.557-1.783 1.92-3.508 2.176c-1.615.24-2.64-.206-2.883-.47a4 4 0 0 0-.448.378a.44.44 0 0 1-.556.045a.444.444 0 0 1-.133-.56c.558-1.027 1.462-1.373 2.887-1.33c1.256.037 2.117-.522 2.39-.806c.566-.52 1.744-1.609 1.938-1.796");
}

.fa4iypkyf {
  fill: var(--svg-color--352827, #352827);
  d: path("m14.546 7.097l-.002.002a.117.117 0 0 1-.12-.201l.001-.002l.005-.002l.014-.008l.05-.025q.066-.033.18-.071c.148-.047.356-.087.58-.048a.117.117 0 0 1-.041.23a1 1 0 0 0-.468.041a1 1 0 0 0-.19.08z");
}

.fatyc1wuz {
  fill: var(--svg-color--2f1920, #2F1920);
  d: path("M15.712 4.428c-.495-.109-.94.385-.99.568c.459 1.548 1.621 1.463 2.769 1.336c.686-.077.761.236.82.388c0-1.718-1.461-2.04-2.587-2.289z");
}

.fclrx3xdq {
  fill: var(--svg-color--000, #000);
  d: path("M15.299 7.795c0-.124-.1-.224-.223-.224a.222.222 0 0 0-.199.326h.395a.2.2 0 0 0 .027-.102");
}

.ffese-y7m {
  width: 6.894px;
  height: 11.735px;
  rx: 3.447px;
}

.fgis5qzvv {
  stop-color: var(--svg-color--a37b73, #A37B73);
}

.fs9pa7bci {
  stop-color: var(--svg-color--6e494b, #6E494B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g11vnob-s {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.047 9.264a.21.21 0 1 0-.284.31l1.82 1.667l-.84.086a.21.21 0 1 0 .043.418l1.21-.124l.955.875a.21.21 0 1 0 .284-.31z");
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.g7dj32byf {
  stop-color: var(--svg-color--402d65, #402D65);
}

.gbuovhboa {
  stop-color: var(--svg-color--95726c, #95726C);
}

.gcfqr7bfg {
  stop-color: var(--svg-color--714350, #714350);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.ht353fb7h {
  d: path("M15.076 7.405a.39.39 0 0 0-.376.492h.753a.393.393 0 0 0-.377-.493");
}

.ht3z4fljp {
  d: path("M16.984 7.405a.39.39 0 0 1 .375.492h-.753a.39.39 0 0 1 .377-.493");
}

.hta3d8bay {
  stop-color: var(--svg-color--9882d5, #9882D5);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.iqfapqb5l {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.03 9.146c-.228 0-.442-.055-.621-.15c-.062-.033-.128.038-.09.095a.844.844 0 0 0 1.42 0c.039-.06-.027-.128-.089-.096c-.18.096-.39.15-.62.15Z");
}

.iqsdfibon {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m19.701 12.745l2.672 1.045a.1.1 0 0 0 .136-.084l.302-3.57");
}

.is80icbry {
  fill: var(--svg-color--8f6263, #8F6263);
  d: path("m17.672 21.275l-.596-1.31l2.266-.993c.02.062.673 1.888.798 2.307c.125.418-.01.773-.094.898l-3.269 5.344c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l1.85-4.032a.6.6 0 0 0 .019-.453");
}

.is89u6ban {
  d: path("M8.523 10.723a3.454 3.454 0 0 1 .006-4.88a3.454 3.454 0 0 1 4.88-.006l1.19 1.19c.338.337.602.742.775 1.188l1.2 3.086c.154.398.233.822.233 1.249v.56a2.443 2.443 0 0 1-4.17 1.727z");
}

.j-tweow-u {
  d: path("M13.318 29.589v-9.484l2.32.062l-.495 8.676a.47.47 0 0 1-.216.373a7 7 0 0 1-1.287.603a.242.242 0 0 1-.322-.23");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j7smtkbjw {
  stop-color: var(--svg-color--6d494d, #6D494D);
}

.j9-ktqfbw {
  stop-color: var(--svg-color--8266c3, #8266C3);
  stop-opacity: 0;
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jjvamgr7p {
  stop-color: var(--svg-color--815553, #815553);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jnedts9qu {
  stop-color: var(--svg-color--976e6a, #976E6A);
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.js5y7fb5r {
  d: path("M16.017 10.71a24 24 0 0 0-1.985.162c-.722.102-.765.711-.765.992v3.68h5.525v-3.68c0-.28-.043-.89-.764-.992a24 24 0 0 0-1.985-.163h-.026");
}

.ju-3ieb_x {
  d: path("M16.108 10.001h-.018q.064-.001.128.005q-.056-.006-.11-.005");
}

.jz3bb8ala {
  fill: var(--svg-color--88014f, #88014F);
  d: path("M16.03 9.146c-.228 0-.442-.055-.621-.15c-.062-.033-.128.038-.09.095a.844.844 0 0 0 1.42 0c.039-.06-.027-.128-.089-.096c-.18.096-.39.15-.62.15");
}

.k-27-x9ja {
  d: path("M13.28 11.279c.194-.188.29-.23.313-.227v2.59c-.399.557-1.783 1.92-3.508 2.176c-1.615.24-2.64-.206-2.883-.47a4 4 0 0 0-.448.378a.44.44 0 0 1-.556.045a.444.444 0 0 1-.133-.56c.558-1.027 1.462-1.373 2.887-1.33c1.256.037 2.117-.522 2.39-.806c.566-.52 1.744-1.609 1.938-1.796");
}

.k356i5yuc {
  stop-color: var(--svg-color--91deff, #91DEFF);
}

.k5r_gj7_l {
  stop-color: var(--svg-color--a17e73, #A17E73);
  stop-opacity: 0;
}

.k9wpgpx3v {
  stop-color: var(--svg-color--855c58, #855C58);
  stop-opacity: 0;
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kitn3twkh {
  stop-color: var(--svg-color--5f363f, #5F363F);
}

.kj5xpeq-h {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.955 7.487c.028.037-.03.083-.096.132c-.067.05-.115.084-.143.047s.003-.107.069-.157s.142-.059.17-.022");
}

.kq9b5xnhm {
  width: 0.689px;
  height: 4.633px;
  x: 22.355px;
  y: 4.997px;
  rx: 0.345px;
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

.l99mnwbez {
  d: path("m17.672 21.275l-.596-1.31l2.266-.993c.02.062.673 1.888.798 2.307c.125.418-.01.773-.094.898l-3.269 5.344c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l1.85-4.032a.6.6 0 0 0 .019-.453");
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.louyt9b7g {
  stop-color: var(--svg-color--afd730, #AFD730);
  stop-opacity: 0;
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.lz6zpisqv {
  stop-color: var(--svg-color--6b4440, #6B4440);
}

.m3bis1bwo {
  fill: var(--svg-color--ffbd3b, #FFBD3B);
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.637-.217.723-.129c.1.103.145.418-.093.696c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.014-.561.256-.764");
}

.m9x84p2nl {
  fill-rule: evenodd;
  d: path("M19.168 8.49a1.44 1.44 0 0 0 .024-1.194h.002a1.4 1.4 0 0 0-.123-.224v-.001c-.15-.23-.23-.5-.23-.774v-.004c0-.796-.646-1.441-1.441-1.441a.24.24 0 0 1-.2-.102a1.444 1.444 0 0 0-2.342 0a.25.25 0 0 1-.199.102h-.037a1.44 1.44 0 0 0-1.404 1.44v.005c0 .274-.08.544-.23.774v.001a1.44 1.44 0 0 0-.097 1.418a.23.23 0 0 1 0 .199a1.403 1.403 0 0 0 1.264 2.02h3.749a1.403 1.403 0 0 0 1.264-2.02a.23.23 0 0 1 0-.2m-5.355-1.168h-.006l.524 1.03c.054 1.223.532 0 1.698 0c1.167 0 1.676 1.362 1.73.138l.496-1.397c-.023-.543-.417-.582-.496-.582h-1.407a1.69 1.69 0 0 1-1.392-.73a.115.115 0 0 0-.202.022l-.036.084a1 1 0 0 1-.564.557c-.103.054-.345.214-.354.629l.004.134z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg10me7tz {
  stop-color: var(--svg-color--794958, #794958);
  stop-opacity: 0;
}

.mh57-sx2c {
  d: path("M13.267 16.39v-.861h5.525v.82a49 49 0 0 1-5.525.041");
}

.migaloo2k {
  stop-color: var(--svg-color--89625c, #89625C);
  stop-opacity: 0;
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.mv_j9hb5m {
  stop-color: var(--svg-color--634990, #634990);
  stop-opacity: 0;
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n5igrlbfw {
  stop-color: var(--svg-color--593569, #593569);
  stop-opacity: 0;
}

.ni-4se4rm {
  stop-color: var(--svg-color--836462, #836462);
}

.nkpzm4bwz {
  d: path("M17.33 7.743a.37.37 0 0 0-.1-.202l-.114.125l.051.1z");
}

.nw_aknb7y {
  stop-color: var(--svg-color--ffc736, #FFC736);
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.o5s4dcbqc {
  stop-color: var(--svg-color--89625c, #89625C);
}

.o6epg8b8b {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m15.863 7.716l-.232.743a.235.235 0 0 0 .227.305h.343a.236.236 0 0 0 .228-.305l-.232-.743c-.05-.164-.282-.164-.334 0");
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

.on1ylhgiq {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M16.529 7.625c.116-.203.292-.364.671-.364c.166 0 .326.046.469.16c.117.095.101.217.01.262l-.242.139c-.285-.092-.6-.105-.908-.197");
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

.p-259bkld {
  d: path("M15.432 7.749c0-.126-.103-.21-.13-.235l-.127.121l.078.158z");
}

.p3hzj_b1z {
  d: path("M18.138 8.577a.703.703 0 1 0 0-1.406a.703.703 0 0 0 0 1.406");
}

.p4dvxyhsv {
  stop-color: var(--svg-color--91676d, #91676D);
  stop-opacity: 0;
}

.p5u-_cblu {
  stop-color: var(--svg-color--603b8b, #603B8B);
}

.p88c31myn {
  stop-color: var(--svg-color--815a5b, #815A5B);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pha_6_rva {
  stop-color: var(--svg-color--94d8ff, #94D8FF);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn9klvbrs {
  stop-color: var(--svg-color--885d55, #885D55);
}

.pnh1u2g5u {
  stop-color: var(--svg-color--896057, #896057);
  stop-opacity: 0;
}

.pql-90wca {
  stop-color: var(--svg-color--9f8cca, #9F8CCA);
  stop-opacity: 0;
}

.pt-h1ccpi {
  stop-color: var(--svg-color--febb35, #FEBB35);
}

.pv3dgeoha {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.68 6.325a.21.21 0 0 1 .418.048l-.159 1.385l1.024-.928a.21.21 0 1 1 .282.311l-5.73 5.192a.21.21 0 0 1-.282-.312l4.234-3.836z");
}

.q05-1fbvc {
  d: path("M13.808 7.323h.005l-.005-.116l-.004-.134c.009-.415.25-.575.354-.628l.022-.01l.023-.008c.232-.107.42-.294.52-.54l.035-.084a.115.115 0 0 1 .202-.022c.313.459.837.73 1.392.73h1.407c.079 0 .473.039.496.582l-.052 1.343c-.054 1.224-1.01 2.046-2.176 2.046s-2.123-.822-2.177-2.046z");
}

.q0xlc4b5d {
  d: path("M15.712 4.428c-.495-.109-.94.385-.99.568c.459 1.548 1.621 1.463 2.769 1.336c.686-.077.761.236.82.388c0-1.718-1.461-2.04-2.587-2.289z");
}

.q2-7ses9m {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m15.858 7.777l-.299.742a.236.236 0 0 0 .228.306h.343a.236.236 0 0 0 .228-.306l-.233-.742c-.05-.165-.215-.165-.267 0");
}

.q54t2dj5c {
  stop-color: var(--svg-color--664c88, #664C88);
}

.qggerob2g {
  stop-color: var(--svg-color--6e3f3c, #6E3F3C);
}

.qlfye6p8o {
  stop-color: var(--svg-color--ffd545, #FFD545);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.qya8vwbkf {
  stop-color: var(--svg-color--86605c, #86605C);
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.redus_bqs {
  stop-color: var(--svg-color--87c9fb, #87C9FB);
  stop-opacity: 0;
}

.rivz2obdn {
  stop-color: var(--svg-color--91e5ff, #91E5FF);
}

.rwna8n39m {
  fill: var(--svg-color--000, #000);
  d: path("M16.76 7.795c0-.124.1-.224.223-.224a.222.222 0 0 1 .199.326h-.395a.2.2 0 0 1-.027-.102");
}

.s_et88bec {
  stop-color: var(--svg-color--ffd545, #FFD545);
}

.s2ceddo5o {
  stop-color: var(--svg-color--80caf3, #80CAF3);
}

.s3hklabia {
  stop-color: var(--svg-color--593569, #593569);
}

.s5lr0-bjd {
  stop-color: var(--svg-color--91676d, #91676D);
}

.s89mq5-5f {
  stop-color: var(--svg-color--9673d5, #9673D5);
  stop-opacity: 0;
}

.s99p66ikg {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.037 9.264a.21.21 0 1 1 .283.31l-1.819 1.667l.84.086a.21.21 0 1 1-.043.418l-1.211-.124l-.954.875a.21.21 0 1 1-.284-.31z");
}

.scofoabvh {
  stop-color: var(--svg-color--7d534e, #7D534E);
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

.tj824objr {
  stop-color: var(--svg-color--6b4440, #6B4440);
  stop-opacity: 0;
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tx327ubjh {
  stop-color: var(--svg-color--8eefff, #8EEFFF);
}

.ubeqdvb2g {
  stop-color: var(--svg-color--87c9fb, #87C9FB);
}

.uj7hgsb3u {
  stop-color: var(--svg-color--815a5b, #815A5B);
}

.uj9y6sbjo {
  stop-color: var(--svg-color--896057, #896057);
}

.ukj380brt {
  stop-color: var(--svg-color--a585e1, #A585E1);
  stop-opacity: 0;
}

.uodqeubaz {
  stop-color: var(--svg-color--94d8ff, #94D8FF);
}

.uoh8f1zsw {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M18.138 8.343a.47.47 0 1 0 0-.938a.47.47 0 0 0 0 .938");
}

.uowu7rarb {
  stop-color: var(--svg-color--603b8b, #603B8B);
  stop-opacity: 0;
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.utipi7g6i {
  stop-color: var(--svg-color--bff332, #BFF332);
}

.uw9pt0beg {
  d: path("M13.14 20.535c.012-.367.07-2.827.1-4.093a.1.1 0 0 1 .088-.096c1.341-.13 4.082-.09 5.365-.052c.043.001.08.03.091.073c.237.855.655 2.465.692 2.605c.037.144-.016.237-.047.266c-.398.03-.937.539-2.336 1.054c-1.398.516-2.742.61-3.195.594c-.363-.012-.517.012-.584.086c-.034-.013-.174-.144-.174-.437");
}

.v_k-57lgf {
  stop-color: var(--svg-color--ffdd49, #FFDD49);
  stop-opacity: 0;
}

.v3rm7ubkk {
  d: path("M18.138 8.343a.47.47 0 1 0 0-.938a.47.47 0 0 0 0 .938");
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.vm1_cbcaw {
  stop-color: var(--svg-color--90eeff, #90EEFF);
}

.voshhcbhx {
  stop-color: var(--svg-color--8466c6, #8466C6);
}

.vsr9738qr {
  width: 0.689px;
  height: 4.633px;
  x: 22.355px;
  y: 4.997px;
  fill: var(--svg-color--9a6159, #9A6159);
  rx: 0.345px;
}

.vt36tzbwu {
  fill: var(--svg-color--855954, #855954);
  d: path("m21.499 12.27l-3.144-1.206l-.137 2.175l3.578 1.368c.185.083.652.2 1.039 0s.516-.72.531-.953l.249-4.56a.433.433 0 0 0-.433-.456h-.007a.137.137 0 0 0-.137.137v.48a.344.344 0 0 1-.687 0v-.744a.404.404 0 0 0-.805-.036c-.013.162-.03.366-.047.6c-.037.494.276.836.438.961z");
}

.vvvf-bx0b {
  stop-color: var(--svg-color--93efff, #93EFFF);
}

.vw5e4lbve {
  stop-color: var(--svg-color--ffdd49, #FFDD49);
}

.vxhtc9kgk {
  stop-color: var(--svg-color--8bd2ff, #8BD2FF);
}

.w8z9c1bqk {
  stop-color: var(--svg-color--6f5187, #6F5187);
}

.wfj08-bsk {
  stop-color: var(--svg-color--855c58, #855C58);
}

.wg3eepbwp {
  stop-color: var(--svg-color--805c54, #805C54);
}

.wg5i7s-vd {
  stop-color: var(--svg-color--8569c7, #8569C7);
}

.wiovp2snp {
  stop-color: var(--svg-color--6d5191, #6D5191);
}

.wiqvl759c {
  d: path("M13.991 8.343a.47.47 0 1 0 0-.938a.47.47 0 0 0 0 .938");
}

.wrh2b4bbx {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
}

.wsh5tsbcf {
  stop-color: var(--svg-color--836462, #836462);
  stop-opacity: 0;
}

.wu3iwcc6r {
  stop-color: var(--svg-color--543556, #543556);
}

.x_ik4kbfh {
  stop-color: var(--svg-color--714350, #714350);
}

.x6_m96bez {
  stop-color: var(--svg-color--85d1fb, #85D1FB);
}

.x8ofsbchc {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.074 7.286a.61.61 0 0 1 .592.463a.12.12 0 0 1-.117.148h-.975a.1.1 0 0 1-.099-.118a.61.61 0 0 1 .599-.493");
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xgq6w0b8s {
  d: path("M7.08 15.003c.177-.133.339-.264.43-.342c.416-.346.637-.217.723-.129c.1.103.145.418-.093.696c-.25.29-.51.464-.735.601c-.165.1-.46.088-.582-.062c-.238-.242-.014-.561.256-.764");
}

.xgtw6wrae {
  stop-color: var(--svg-color--8d615b, #8D615B);
  stop-opacity: 0;
}

.y9-pzrhvv {
  d: path("m15.863 7.716l-.232.743a.235.235 0 0 0 .227.305h.343a.236.236 0 0 0 .228-.305l-.232-.743c-.05-.164-.282-.164-.334 0");
}

.yamoh3dov {
  stop-color: var(--svg-color--764e4c, #764E4C);
}

.ycrcotb4u {
  stop-color: var(--svg-color--986f60, #986F60);
  stop-opacity: 0;
}

.yezlp2beb {
  stop-color: var(--svg-color--8467c6, #8467C6);
  stop-opacity: 0;
}

.yq1j9wb8r {
  stop-color: var(--svg-color--95726c, #95726C);
  stop-opacity: 0;
}

.ytl8wkbiv {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.403 6.325a.21.21 0 0 0-.417.048l.159 1.385l-1.024-.928a.21.21 0 1 0-.282.311l5.73 5.192a.21.21 0 0 0 .282-.312l-4.235-3.836z");
}

.z_5s59bdn {
  width: 4.843px;
  height: 8.244px;
  rx: 2.422px;
}

.z0_tnl66g {
  stop-color: var(--svg-color--6c2d29, #6C2D29);
  stop-opacity: 0;
}

.z26rrllgi {
  stop-color: var(--svg-color--6e494b, #6E494B);
}

.z30kudb-o {
  cx: 6.572px;
  cy: 15.685px;
  r: 0.438px;
}

.z45oacyxz {
  d: path("m17.397 26.507l-.62 1.014c-.07.116-.233.128-.311.017c-.297-.42-.547-.974-.686-1.358a.55.55 0 0 1 .023-.42l.466-1.017z");
}

.z9-ns_cqv {
  stop-color: var(--svg-color--916ed5, #916ED5);
}

.zepkmwb6a {
  fill: var(--svg-color--8569c7, #8569C7);
  d: path("M13.14 20.535c.012-.367.07-2.827.1-4.093a.1.1 0 0 1 .088-.096c1.341-.13 4.082-.09 5.365-.052c.043.001.08.03.091.073c.237.855.655 2.465.692 2.605c.037.144-.016.237-.047.266c-.398.03-.937.539-2.336 1.054c-1.398.516-2.742.61-3.195.594c-.363-.012-.517.012-.584.086c-.034-.013-.174-.144-.174-.437");
}

.zkuiccvvk {
  cx: 14.958px;
  cy: 7.571px;
  rx: 0.17px;
  ry: 0.086px;
}

.zoq8fuaif {
  stop-color: var(--svg-color--986f60, #986F60);
}

.zqax3vbfg {
  stop-color: var(--svg-color--6c2d29, #6C2D29);
}

.zyjyshkcz {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.986 7.286a.61.61 0 0 0-.592.463a.12.12 0 0 0 .117.148h.974a.1.1 0 0 0 .1-.118a.61.61 0 0 0-.6-.493");
}

</style>
