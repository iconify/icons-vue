<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i5k56Mm)"><path fill="url(#iIXAWPc)" clip-rule="evenodd" class="cd5t7sbls"/><path fill="url(#iBQkWfc)" clip-rule="evenodd" class="cd5t7sbls"/><path fill="url(#ixoXtPd)" clip-rule="evenodd" class="cd5t7sbls"/><path fill="url(#iGHyJVd)" clip-rule="evenodd" class="cd5t7sbls"/><path fill="url(#iKFe07b)" clip-rule="evenodd" class="cd5t7sbls"/><path fill="url(#iaoM9RR)" clip-rule="evenodd" class="cd5t7sbls"/><path fill="url(#iat4j2c)" clip-rule="evenodd" class="cd5t7sbls"/><path fill="url(#ipRYBeb)" clip-rule="evenodd" class="cd5t7sbls"/><path fill="url(#i3urTlb)" clip-rule="evenodd" class="cd5t7sbls"/><path fill="url(#iYcmOpd)" clip-rule="evenodd" class="cd5t7sbls"/><path fill="url(#iMKQ9Pd)" clip-rule="evenodd" class="cd5t7sbls"/></g><path fill="url(#iyYgwhd)" class="yzbtxw7wo"/><path fill="url(#izNEN8r)" class="yzbtxw7wo"/><path fill="url(#i9ouX8S)" class="yzbtxw7wo"/><path fill="url(#ixH44Wc)" class="yzbtxw7wo"/><path fill="url(#injuHmd)" class="tomby8_it"/><path fill="url(#iCyCExb)" class="tomby8_it"/><path fill="url(#iqEzpMb)" class="tomby8_it"/><path fill="url(#iUznqjb)" class="tomby8_it"/><path fill="url(#iMXA0fd)" class="e-sa4ok2t"/><path fill="url(#isQBS7c)" class="e-sa4ok2t"/><path fill="url(#iJC3Tpd)" class="tscywp1sg"/><path fill="url(#iXHrshd)" class="tscywp1sg"/><path fill="url(#iITtnfb)" class="cjjhh8b4j"/><path fill="url(#i0w8SQa)" class="cjjhh8b4j"/><path fill="url(#idU8wMN)" class="lh8jfxn3e"/><path fill="url(#ilvYAVc)" class="lh8jfxn3e"/><g filter="url(#iyb00ju)"><path fill="url(#ikZKo4b)" class="ccdofwbhq"/><path fill="url(#i3xiuDc)" class="ccdofwbhq"/></g><rect fill="url(#iPJxo1d)" class="fpryn_b8i"/><rect fill="url(#i8VTRNK)" class="fpryn_b8i"/><g filter="url(#iHqCo9c)"><path fill="url(#iNQNlzb)" class="v5f4uubno"/></g><g filter="url(#iz1UQJe)"><path fill="url(#iHebXrr)" class="ts-j4jiou"/></g><g filter="url(#iR7ee5w)"><path fill="url(#iz3AXtD)" class="kektqzbjt"/></g><g filter="url(#i4sanfb)"><path stroke="url(#ifSZc9c)" class="nas6pmb7m"/></g><g filter="url(#iEvZdBb)"><path stroke="url(#iUNBF8c)" class="q_kq4jbxk"/></g><g filter="url(#iRJ4PyL)"><path stroke="url(#irxXhjb)" class="a3rha_1gr"/></g><g filter="url(#iAmUYZb)"><path fill="url(#iXiACAe)" class="t_5j5obsn"/><path fill="url(#ijTKEwa)" class="t_5j5obsn"/></g><path fill="url(#i2ufDRc)" class="mh422-bgz"/><path fill="url(#i4Gpytd)" class="mh422-bgz"/><path fill="url(#ikTuk5c)" class="mh422-bgz"/><path fill="url(#i5Mc26W)" class="mh422-bgz"/><path fill="url(#irrHuAc)" class="mh422-bgz"/><path fill="url(#iDNrTUd)" class="ayxe11bvs"/><path fill="url(#i5qDHOe)" class="ayxe11bvs"/><path fill="url(#iRJ85YM)" class="ayxe11bvs"/><path fill="url(#ipPsDTd)" class="ayxe11bvs"/><path fill="url(#ivzRBCN)" class="irsecfb6v"/><path fill="url(#iit5mOS)" class="irsecfb6v"/><path fill="url(#iBQS5Bd)" class="irsecfb6v"/><g filter="url(#iSOrgBZ)"><path fill="url(#iDCuJ3P)" class="s6n57cb8f"/></g><g filter="url(#iCyxkqc)"><path fill="url(#ibGdoyc)" class="u1dpydk2y"/></g><g filter="url(#itfYJMe)"><path class="urzzixblm"/><path fill="url(#i388H9c)" class="uzcrhl-du"/></g><g filter="url(#iigAedd)"><path class="et2-dew8n"/><path fill="url(#iWVwi2c)" class="y2h-f9s_x"/></g><g filter="url(#iRUBlob)"><path fill="url(#igixabb)" class="sa_mqwsxd"/><path fill="url(#iGOdxxd)" class="sa_mqwsxd"/><path fill="url(#iOHkLpx)" class="sa_mqwsxd"/><path fill="url(#iiNlHKe)" class="sa_mqwsxd"/><path fill="url(#iFuILQe)" class="sa_mqwsxd"/><path fill="url(#iuKccgd)" class="sa_mqwsxd"/><path fill="url(#iKaqyvb)" class="sa_mqwsxd"/></g><path fill="url(#idJm7zi)" class="sa_mqwsxd"/><g filter="url(#iTiN6lb)"><path class="d9y7n6b7k"/></g><g filter="url(#ixjGF2c)"><path fill="url(#irkPrsd)" class="qp60g8bwf"/><path fill="url(#iZi4ojb)" class="qp60g8bwf"/><path fill="url(#ikC7hze)" class="qp60g8bwf"/><path fill="url(#iN6AwAe)" class="qp60g8bwf"/></g><path fill="url(#iq68RnB)" class="qp60g8bwf"/><path fill="url(#iZMglDe)" class="qp60g8bwf"/><path stroke="url(#igpYvlc)" class="epz-1-s-e"/><g filter="url(#ihOkGZd)"><path class="e-3_soqij"/></g><g filter="url(#i5DjFud)"><path class="mw-du8b3f"/></g><g filter="url(#iz21Dhd)"><path class="soxv4gbpk"/></g><g filter="url(#i9Wb2lb)"><path clip-rule="evenodd" class="pepyl0bfp"/></g><path class="js4l338js"/><path fill="url(#i9uzuKc)" class="f2c0hrjyq"/><path class="osx01ib_t"/><g filter="url(#icZbFSc)"><path class="gk-vm5f6h"/><path fill="url(#iWU9yHb)" class="ps9cc7bdf"/></g><g filter="url(#i6MdHkj)"><path fill="url(#idh6Uqb)" class="znpa4_jtv"/></g><path class="udruzobgg"/><path fill="url(#i35XHDe)" class="nhb1mnbxx"/><path class="s_uzjwbke"/><g filter="url(#iz6adlb)"><path fill="url(#ilBHqpm)" class="tl-l61q7a"/></g><g filter="url(#iRCfUYd)"><ellipse transform="rotate(-27.914 13.731 9.969)" class="k15_adb_y"/><ellipse fill="url(#i8bcnkd)" transform="rotate(-27.914 13.731 9.969)" class="ecprl_uag"/></g><g filter="url(#iTsJnQb)"><path class="iopru_05u"/></g><g filter="url(#iPVHLcM)"><path class="rlmvqsjtd"/></g><g filter="url(#iOQCUfc)"><path fill="url(#iODgOPL)" class="o18z-jbxv"/><path fill="url(#iTKszpd)" class="o18z-jbxv"/></g><g filter="url(#iFHivLc)"><path fill="url(#iD8dKKb)" class="j6yebebjj"/><path fill="url(#iIUPpld)" class="j6yebebjj"/><path fill="url(#iOtiygb)" class="j6yebebjj"/></g><g filter="url(#ischGfc)"><path stroke="url(#iVbOuyb)" class="wpdv-0bui"/></g><defs><radialGradient id="iBQkWfc" cx="0" cy="0" r="1" gradientTransform="rotate(28.301 -17.682 46.66)scale(3.18955 4.51784)" gradientUnits="userSpaceOnUse"><stop offset=".616" class="w3-vy4c8j"/><stop offset="1" class="w72oynbwi"/></radialGradient><radialGradient id="ixoXtPd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.45645 -2.68487 0 11.614 12.695)" gradientUnits="userSpaceOnUse"><stop class="lcrdwk1fj"/><stop offset="1" class="denqa3bda"/></radialGradient><radialGradient id="iGHyJVd" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.57099 -5.8032 0 16.185 12.788)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="ag6fa4z4y"/><stop offset="1" class="qir_1cb0f"/></radialGradient><radialGradient id="iKFe07b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24075 1.61016 -1.56338 -1.2047 11.274 10.982)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="ha2cq84sa"/><stop offset="1" class="p4wkjrbae"/></radialGradient><radialGradient id="iaoM9RR" cx="0" cy="0" r="1" gradientTransform="matrix(-.46758 2.51377 -2.61762 -.4869 11.866 8.546)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="tgqxysbgm"/><stop offset="1" class="p1xq25bjq"/></radialGradient><radialGradient id="iat4j2c" cx="0" cy="0" r="1" gradientTransform="rotate(62.605 3.547 12.314)scale(2.38097 4.53569)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="esx41hbqq"/><stop offset=".921" class="v9rq5jjti"/></radialGradient><radialGradient id="ipRYBeb" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 9.76 7.227)scale(1.63713 2.28786)" gradientUnits="userSpaceOnUse"><stop class="duwob45dr"/><stop offset="1" class="v61l3jbat"/></radialGradient><radialGradient id="i3urTlb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.16706 -4.01156 23.694 9.81)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="hottnizrg"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="iYcmOpd" cx="0" cy="0" r="1" gradientTransform="rotate(-133.315 14.703 4.084)scale(4.66215 6.69539)" gradientUnits="userSpaceOnUse"><stop class="yqk-2gbyp"/><stop offset="1" class="oaxszm67z"/></radialGradient><radialGradient id="iMKQ9Pd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00843 -1.37436 .45061 -.00276 13.48 5.993)" gradientUnits="userSpaceOnUse"><stop offset=".295" class="sufhn4bec"/><stop offset="1" class="kpf8h5ohf"/></radialGradient><radialGradient id="ixH44Wc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.75 -7.36742 0 16.17 15.781)" gradientUnits="userSpaceOnUse"><stop offset=".441" class="cao962vhw"/><stop offset="1" class="nf-fa4b-x"/></radialGradient><radialGradient id="injuHmd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -18.9129 5.74827 0 5.095 29.906)" gradientUnits="userSpaceOnUse"><stop class="yihcw4vuy"/><stop offset=".441" class="kszwqub4g"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="iCyCExb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.3871 .84225 0 8.943 29.906)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="iqEzpMb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.10974 -.92291 0 8.943 23.054)" gradientUnits="userSpaceOnUse"><stop class="af-h-_b2n"/><stop offset="1" class="km_8bqcup"/></radialGradient><radialGradient id="iMXA0fd" cx="0" cy="0" r="1" gradientTransform="rotate(-100.677 25.058 4.456)scale(10.3854 2.97327)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="isQBS7c" cx="0" cy="0" r="1" gradientTransform="matrix(.55553 12.0481 -.71816 .03311 23.226 23.058)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="iJC3Tpd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.82081 -1.38289 0 16.94 16.183)" gradientUnits="userSpaceOnUse"><stop class="jv6bd5qpy"/><stop offset="1" class="j21cx9htb"/></radialGradient><radialGradient id="iXHrshd" cx="0" cy="0" r="1" gradientTransform="matrix(.11168 4.2505 -2.51652 .06612 16.17 15.095)" gradientUnits="userSpaceOnUse"><stop offset=".739" class="w608ytq9t"/><stop offset=".975" class="dr_vmzg-z"/></radialGradient><radialGradient id="iITtnfb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.157 .99606 -1.23158 -1.43058 27.918 23.503)" gradientUnits="userSpaceOnUse"><stop class="nv7ilcg1p"/><stop offset="1" class="mdj8rj_9y"/></radialGradient><radialGradient id="i0w8SQa" cx="0" cy="0" r="1" gradientTransform="matrix(.5 -.80469 .9445 .58687 26.31 24.633)" gradientUnits="userSpaceOnUse"><stop class="rloy1eb5h"/><stop offset="1" class="msvvb9k2w"/></radialGradient><radialGradient id="idU8wMN" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 0 0 -6.89354 26.271 24.19)" gradientUnits="userSpaceOnUse"><stop class="guhwv3amf"/><stop offset=".851" class="eknpx1bxe"/></radialGradient><radialGradient id="i3xiuDc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44615 2.39061 -1.97778 -1.19642 27.92 24.5)" gradientUnits="userSpaceOnUse"><stop class="tqgfgwd_y"/><stop offset="1" class="de0rqgbhp"/></radialGradient><radialGradient id="iPJxo1d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.97656 0 0 -.375 26.717 21.367)" gradientUnits="userSpaceOnUse"><stop class="awi5873rb"/><stop offset="1" class="qwu7q3ojv"/></radialGradient><radialGradient id="iXiACAe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.3125 12.819 0 16.151 23.313)" gradientUnits="userSpaceOnUse"><stop offset=".429" class="rr16fpbgs"/><stop offset="1" class="gvd3e3nnk"/></radialGradient><radialGradient id="ijTKEwa" cx="0" cy="0" r="1" gradientTransform="rotate(-94.385 20.51 4.327)scale(10.6778 18.1021)" gradientUnits="userSpaceOnUse"><stop offset=".721" class="mu05ugb8a"/><stop offset="1" class="g044dvbra"/></radialGradient><radialGradient id="ikTuk5c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9294 0 0 -.32098 26.87 17.299)" gradientUnits="userSpaceOnUse"><stop class="ie4iw9rqt"/><stop offset="1" class="y78upfugg"/></radialGradient><radialGradient id="ipPsDTd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07813 0 0 -.3432 23.584 17.125)" gradientUnits="userSpaceOnUse"><stop class="gwbo6ccta"/><stop offset="1" class="e_7rjsbau"/></radialGradient><radialGradient id="iBQS5Bd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 0 0 -.29688 29.35 17.375)" gradientUnits="userSpaceOnUse"><stop class="hjqvsnb9q"/><stop offset="1" class="kc7tdcpzt"/></radialGradient><radialGradient id="ibGdoyc" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.225 11.101)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="i388H9c" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 40.834 -52.587)scale(1.30459)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="iWVwi2c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07411 0 0 -1.02745 11.52 10.66)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="igixabb" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.411 7.152)scale(7.16175 9.58588)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="m45oyzb-o"/></radialGradient><radialGradient id="iGOdxxd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10973 1.11592 -.94678 -1.78996 18.085 10.822)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="iOHkLpx" cx="0" cy="0" r="1" gradientTransform="matrix(.8369 -4.04513 5.13253 1.06187 14.005 16.907)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="iiNlHKe" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.44059 -11.8177 0 15.923 9.64)" gradientUnits="userSpaceOnUse"><stop offset=".593" class="ajxs5ri3z"/><stop offset="1" class="x05md6_2b"/></radialGradient><radialGradient id="iFuILQe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.42256 1.49953 -2.58173 -9.33598 16.813 11.78)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="iuKccgd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.486 9.706)" gradientUnits="userSpaceOnUse"><stop class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="iKaqyvb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36 1.55865 0 14.267 9.793)" gradientUnits="userSpaceOnUse"><stop class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="idJm7zi" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34695 0 0 -4.43421 21.28 11.193)" gradientUnits="userSpaceOnUse"><stop class="f902gfhfn"/><stop offset="1" class="jh40i5bvl"/></radialGradient><radialGradient id="iZi4ojb" cx="0" cy="0" r="1" gradientTransform="matrix(-.69746 -2.44974 1.40177 -.3991 16.97 11.92)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="iZMglDe" cx="0" cy="0" r="1" gradientTransform="rotate(144.462 6.384 8.42)scale(1.57489 2.10945)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="e6-lebcyw"/><stop offset="1" class="b8os9sbcy"/></radialGradient><radialGradient id="i9uzuKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.367 10.065)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iWU9yHb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.554 .633)scale(.37798 .52039)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i35XHDe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 14.003 10.065)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i8bcnkd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00773 -.49366 .5934 -.0093 13.716 10.284)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iODgOPL" cx="0" cy="0" r="1" gradientTransform="rotate(129.554 5.861 5.027)scale(5.36951 2.34181)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="esh4v5qtq"/><stop offset=".911" class="nria2ku7r"/></radialGradient><radialGradient id="iTKszpd" cx="0" cy="0" r="1" gradientTransform="rotate(144.458 5.983 4.265)scale(3.81321 1.88454)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="dpv-wxbjb"/><stop offset="1" class="abu2lcc5n"/><stop offset="1" class="sxoxd_kke"/></radialGradient><radialGradient id="iD8dKKb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.18534 4.55504 -6.4674 -3.10282 17.976 2.537)" gradientUnits="userSpaceOnUse"><stop offset=".627" class="crfaaqblp"/><stop offset="1" class="ehjghj3fe"/></radialGradient><radialGradient id="iIUPpld" cx="0" cy="0" r="1" gradientTransform="rotate(105.909 7.917 8.95)scale(3.44004 7.20923)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="z-gx2rb2w"/><stop offset="1" class="gbpc14bxe"/></radialGradient><radialGradient id="iOtiygb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.41682 -6.46744 5.78149 -3.05443 17.335 9.421)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="s3t3owbgt"/><stop offset="1" class="yehxt3bls"/></radialGradient><linearGradient id="iIXAWPc" x1="20.878" x2="13.637" y1="3.709" y2="17.152" gradientUnits="userSpaceOnUse"><stop class="yr1vjkbzu"/><stop offset="1" class="btu9i2bec"/></linearGradient><linearGradient id="iyYgwhd" x1="16.172" x2="16.172" y1="15.447" y2="30.331" gradientUnits="userSpaceOnUse"><stop class="jko77nbfm"/><stop offset="1" class="jaal1e-1o"/></linearGradient><linearGradient id="izNEN8r" x1="23.599" x2="21.068" y1="26.5" y2="26.531" gradientUnits="userSpaceOnUse"><stop class="pxynpwacq"/><stop offset="1" class="js7rwm17w"/></linearGradient><linearGradient id="i9ouX8S" x1="8.627" x2="10.843" y1="26.316" y2="26.316" gradientUnits="userSpaceOnUse"><stop class="r7k3cqb2o"/><stop offset="1" class="e16pzouhw"/></linearGradient><linearGradient id="iUznqjb" x1="9.091" x2="8.656" y1="28" y2="28" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="ilvYAVc" x1="25.634" x2="25.662" y1="21.902" y2="22.258" gradientUnits="userSpaceOnUse"><stop class="vhte_3bib"/><stop offset="1" class="h0-3hob0r"/></linearGradient><linearGradient id="ikZKo4b" x1="27.631" x2="23.603" y1="27.969" y2="27.969" gradientUnits="userSpaceOnUse"><stop class="ut7pv-xgw"/><stop offset=".861" class="oltxz8b0t"/></linearGradient><linearGradient id="i8VTRNK" x1="25.644" x2="25.644" y1="20.719" y2="21.18" gradientUnits="userSpaceOnUse"><stop offset=".22" class="bwtslccfc"/><stop offset="1" class="aq7ukmb7b"/></linearGradient><linearGradient id="iNQNlzb" x1="17.222" x2="17.222" y1="29.509" y2="22.833" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="iHebXrr" x1="13.215" x2="13.215" y1="29.509" y2="22.833" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="iz3AXtD" x1="21.209" x2="21.209" y1="29.509" y2="22.833" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="ifSZc9c" x1="24.123" x2="25.832" y1="25.977" y2="25.977" gradientUnits="userSpaceOnUse"><stop class="ncgvd-jsx"/><stop offset="1" class="q2ji4cbak"/></linearGradient><linearGradient id="iUNBF8c" x1="24.045" x2="25.754" y1="27.281" y2="27.281" gradientUnits="userSpaceOnUse"><stop class="ncgvd-jsx"/><stop offset="1" class="q2ji4cbak"/></linearGradient><linearGradient id="irxXhjb" x1="24.123" x2="25.832" y1="28.586" y2="28.586" gradientUnits="userSpaceOnUse"><stop class="ncgvd-jsx"/><stop offset="1" class="q2ji4cbak"/></linearGradient><linearGradient id="i2ufDRc" x1="27.912" x2="24.537" y1="20.625" y2="20.25" gradientUnits="userSpaceOnUse"><stop offset=".15" class="yslyejzkq"/><stop offset="1" class="a697hhbbx"/></linearGradient><linearGradient id="i4Gpytd" x1="25.633" x2="25.633" y1="20.891" y2="20.375" gradientUnits="userSpaceOnUse"><stop class="j4l_ybb-i"/><stop offset="1" class="hmw0arboa"/></linearGradient><linearGradient id="i5Mc26W" x1="25.633" x2="25.633" y1="16.745" y2="17.375" gradientUnits="userSpaceOnUse"><stop class="xjh-ixbfp"/><stop offset="1" class="dj_b1_bgk"/></linearGradient><linearGradient id="irrHuAc" x1="23.335" x2="24.077" y1="19.092" y2="19.092" gradientUnits="userSpaceOnUse"><stop class="sl5klgbuk"/><stop offset="1" class="ofpq3rdpo"/></linearGradient><linearGradient id="iDNrTUd" x1="23.506" x2="22.209" y1="18.876" y2="18.876" gradientUnits="userSpaceOnUse"><stop offset=".277" class="o5smz7bvt"/><stop offset=".819" class="ioik6xbji"/></linearGradient><linearGradient id="i5qDHOe" x1="23.756" x2="23.365" y1="19.156" y2="19.156" gradientUnits="userSpaceOnUse"><stop class="k9y_vhbis"/><stop offset="1" class="aib520jbl"/></linearGradient><linearGradient id="iRJ85YM" x1="22.96" x2="22.96" y1="20.987" y2="20.324" gradientUnits="userSpaceOnUse"><stop class="f6yu9itto"/><stop offset="1" class="pt18zyb3d"/></linearGradient><linearGradient id="ivzRBCN" x1="29.207" x2="27.587" y1="19.323" y2="19.323" gradientUnits="userSpaceOnUse"><stop class="lwc0fqtbi"/><stop offset="1" class="b439v2bdt"/></linearGradient><linearGradient id="iit5mOS" x1="28.506" x2="28.506" y1="20.961" y2="20.437" gradientUnits="userSpaceOnUse"><stop class="c2_0e5baj"/><stop offset="1" class="zx6sfmbib"/></linearGradient><linearGradient id="iDCuJ3P" x1="9.89" x2="12.85" y1="10.749" y2="10.749" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="irkPrsd" x1="16.185" x2="16.185" y1="12.7" y2="10.018" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="ikC7hze" x1="15.139" x2="15.993" y1="11.938" y2="12.042" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="iN6AwAe" x1="16.185" x2="16.185" y1="12.792" y2="12.182" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="iq68RnB" x1="16.263" x2="16.263" y1="12.766" y2="12.626" gradientUnits="userSpaceOnUse"><stop class="b8os9sbcy"/><stop offset="1" class="e6-lebcyw"/></linearGradient><linearGradient id="igpYvlc" x1="15.456" x2="15.909" y1="14.269" y2="13.397" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="idh6Uqb" x1="19.145" x2="18.831" y1="10.118" y2="10.312" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ilBHqpm" x1="14.746" x2="14.433" y1="10.118" y2="10.311" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iVbOuyb" x1="13.294" x2="13.838" y1="4.463" y2="5.737" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient><filter id="i5k56Mm" width="15.268" height="15.268" x="8.676" y="1.884" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.537255 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1726"/></filter><filter id="iyb00ju" width="4.568" height="5.556" x="23.603" y="24.35" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.478431 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1726"/></filter><filter id="iHqCo9c" width="1.192" height="6.826" x="15.589" y="23.2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1726" stdDeviation=".125"/></filter><filter id="iz1UQJe" width="1.192" height="6.826" x="11.583" y="23.2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1726" stdDeviation=".125"/></filter><filter id="iR7ee5w" width="1.192" height="6.826" x="19.576" y="23.2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1726" stdDeviation=".125"/></filter><filter id="i4sanfb" width="2.097" height=".3" x="23.973" y="25.748" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1726" stdDeviation=".05"/></filter><filter id="iEvZdBb" width="2.097" height=".3" x="23.895" y="27.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1726" stdDeviation=".05"/></filter><filter id="iRJ4PyL" width="2.097" height=".3" x="23.973" y="28.358" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1726" stdDeviation=".05"/></filter><filter id="iAmUYZb" width="12.911" height="8.622" x="9.695" y="15.657" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.756863 0 0 0 0 0.854902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1726"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.596078 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1726" result="effect2_innerShadow_4002_1726"/></filter><filter id="iSOrgBZ" width="3.318" height="3.218" x="9.89" y="9.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.501961 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1726"/></filter><filter id="iCyxkqc" width="3.218" height="3.468" x="19.403" y="8.803" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1726"/></filter><filter id="itfYJMe" width="3.148" height="3.148" x="19.438" y="9.088" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1726" stdDeviation=".25"/></filter><filter id="iigAedd" width="2.648" height="2.648" x="10.195" y="9.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1726" stdDeviation=".125"/></filter><filter id="iRUBlob" width="10.191" height="11.277" x="11.09" y="5.755" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1726"/></filter><filter id="iTiN6lb" width="2.877" height="3.682" x="14.584" y="9.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1726" stdDeviation=".25"/></filter><filter id="ixjGF2c" width="2.377" height="3.182" x="14.996" y="9.768" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1726" stdDeviation=".125"/></filter><filter id="ihOkGZd" width="3.001" height="1.285" x="17.127" y="9.257" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1726"/></filter><filter id="i5DjFud" width="3.001" height="1.285" x="12.242" y="9.257" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1726"/></filter><filter id="iz21Dhd" width="2.453" height="1.091" x="12.377" y="7.833" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1726"/></filter><filter id="i9Wb2lb" width="2.453" height="1.091" x="17.794" y="7.833" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1726"/></filter><filter id="icZbFSc" width=".786" height=".696" x="17.633" y="9.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1726" stdDeviation=".05"/></filter><filter id="i6MdHkj" width=".891" height=".913" x="18.473" y="9.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1726" stdDeviation=".1"/></filter><filter id="iz6adlb" width=".986" height="1.04" x="14.03" y="9.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1726" stdDeviation=".1"/></filter><filter id="iRCfUYd" width=".912" height=".704" x="13.275" y="9.617" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1726" stdDeviation=".05"/></filter><filter id="iTsJnQb" width="2.661" height="1.378" x="17.625" y="7.756" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1726" stdDeviation=".2"/></filter><filter id="iPVHLcM" width="2.661" height="1.378" x="12.173" y="7.756" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1726" stdDeviation=".2"/></filter><filter id="iOQCUfc" width="4.985" height="5.214" x="9.477" y="3.386" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1726" stdDeviation=".375"/></filter><filter id="iFHivLc" width="8.914" height="5.78" x="12.868" y="2.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1726" stdDeviation=".125"/></filter><filter id="ischGfc" width="1.145" height="2.31" x="12.994" y="3.82" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1726" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-judge" /></template>
<style>
.a3rha_1gr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.123 28.508h1.797");
}

.a697hhbbx {
  stop-color: var(--svg-color--663e3d, #663E3D);
}

.a9dfe182j {
  stop-color: var(--svg-color--d4993e, #D4993E);
}

.abu2lcc5n {
  stop-color: var(--svg-color--ffe134, #FFE134);
  stop-opacity: 0;
}

.af-h-_b2n {
  stop-color: var(--svg-color--4e425a, #4E425A);
}

.ag6fa4z4y {
  stop-color: var(--svg-color--e26b25, #E26B25);
}

.aib520jbl {
  stop-color: var(--svg-color--532820, #532820);
  stop-opacity: 0;
}

.ajxs5ri3z {
  stop-color: var(--svg-color--f3943b, #F3943B);
  stop-opacity: 0;
}

.aq7ukmb7b {
  stop-color: var(--svg-color--54201c, #54201C);
  stop-opacity: 0;
}

.awi5873rb {
  stop-color: var(--svg-color--7c5f5a, #7C5F5A);
}

.ayxe11bvs {
  d: path("M23.178 16.861h-.613a.505.505 0 0 0-.504.504v3.022c0 .272.222.504.504.504h.613a.505.505 0 0 0 .504-.504v-3.022a.51.51 0 0 0-.504-.504");
}

.b439v2bdt {
  stop-color: var(--svg-color--62312b, #62312B);
}

.b8os9sbcy {
  stop-color: var(--svg-color--e2802f, #E2802F);
}

.btu9i2bec {
  stop-color: var(--svg-color--e37923, #E37923);
}

.bwtslccfc {
  stop-color: var(--svg-color--54201c, #54201C);
}

.c2_0e5baj {
  stop-color: var(--svg-color--7a464a, #7A464A);
}

.cao962vhw {
  stop-color: var(--svg-color--473e49, #473E49);
}

.ccdofwbhq {
  d: path("M23.603 25.232c0-.401.325-.732.726-.732h2.392a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.592a.731.731 0 0 1-.319-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.cd5t7sbls {
  fill-rule: evenodd;
  d: path("M23.37 12.071c.213-.435.324-.92.324-1.426c0-.468-.096-.906-.268-1.306h.005a3 3 0 0 0-.281-.513l-.002-.003a3.24 3.24 0 0 1-.527-1.771v-.01a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.232a3.3 3.3 0 0 0-2.682-1.376a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.455.233h-.085a3.3 3.3 0 0 0-3.214 3.299v.01a3.24 3.24 0 0 1-.527 1.77l-.002.005A3.3 3.3 0 0 0 9 12.07c.07.142.07.314 0 .456a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 3.218-3.219c0-.505-.121-.981-.324-1.406a.51.51 0 0 1 0-.456M11.11 9.4h-.012l1.198 2.356c.124 2.802 1.218 0 3.889 0s3.836 3.119 3.96.316l1.136-3.197c-.054-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.673a.264.264 0 0 0-.461.05l-.082.195A2.3 2.3 0 0 1 11.9 7.389c-.236.122-.79.49-.81 1.439l.01.306z");
}

.cfl87rzth {
  stop-color: var(--svg-color--3f3647, #3F3647);
  stop-opacity: 0;
}

.cjjhh8b4j {
  d: path("M26.959 22.84c.531 0 .959.426.959.958v2.188H26.01v-2.188a.94.94 0 0 1 .948-.959");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crfaaqblp {
  stop-color: var(--svg-color--f49523, #F49523);
  stop-opacity: 0;
}

.d9y7n6b7k {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m15.792 10.439l-.683 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.493-.377-.613 0");
}

.de0rqgbhp {
  stop-color: var(--svg-color--ffe136, #FFE136);
  stop-opacity: 0;
}

.denqa3bda {
  stop-color: var(--svg-color--d77117, #D77117);
  stop-opacity: 0;
}

.dj_b1_bgk {
  stop-color: var(--svg-color--755144, #755144);
  stop-opacity: 0;
}

.dpv-wxbjb {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
}

.dr_vmzg-z {
  stop-color: var(--svg-color--9f6001, #9F6001);
}

.duwob45dr {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
}

.e_7rjsbau {
  stop-color: var(--svg-color--745e58, #745E58);
  stop-opacity: 0;
}

.e-3_soqij {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.327 10.093c.266-.467.669-.836 1.537-.836c.38 0 .747.105 1.073.369c.27.217.233.495.025.6l-.556.316c-.652-.21-1.373-.239-2.079-.45");
}

.e-sa4ok2t {
  d: path("M23.398 29.906v-11.8c2.355 2.01 3.848 4.986 3.848 8.31v2.49a1 1 0 0 1-1 1z");
}

.e0lgwbeaw {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
}

.e16pzouhw {
  stop-color: var(--svg-color--5a4e68, #5A4E68);
  stop-opacity: 0;
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.e6-lebcyw {
  stop-color: var(--svg-color--e2802f, #E2802F);
  stop-opacity: 0;
}

.ebol5nf6u {
  stop-color: var(--svg-color--4f445b, #4F445B);
  stop-opacity: 0;
}

.ecprl_uag {
  cx: 13.731px;
  cy: 9.969px;
  rx: 0.389px;
  ry: 0.197px;
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.ehjghj3fe {
  stop-color: var(--svg-color--f49523, #F49523);
}

.eknpx1bxe {
  stop-color: var(--svg-color--754636, #754636);
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.epz-1-s-e {
  fill: var(--svg-color--8a004f, #8A004F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.787 13.185a.204.204 0 0 0-.248.043a.196.196 0 0 0-.02.248a1.982 1.982 0 0 0 3.333 0a.2.2 0 0 0-.021-.25a.205.205 0 0 0-.247-.042c-.405.216-.881.34-1.399.34a3 3 0 0 1-1.398-.34Z");
}

.esh4v5qtq {
  stop-color: var(--svg-color--ee971b, #EE971B);
  stop-opacity: 0;
}

.esx41hbqq {
  stop-color: var(--svg-color--cba140, #CBA140);
}

.et2-dew8n {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M11.519 11.736a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.f2c0hrjyq {
  d: path("M18.37 9.588a.892.892 0 0 1 .86 1.127h-1.725a.896.896 0 0 1 .864-1.128");
}

.f6yu9itto {
  stop-color: var(--svg-color--663848, #663848);
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

.fpryn_b8i {
  width: 2.773px;
  height: 1.082px;
  x: 24.257px;
  y: 20.891px;
  rx: 0.541px;
}

.ft5dv1b6b {
  fill: none;
}

.g044dvbra {
  stop-color: var(--svg-color--9b7b6d, #9B7B6D);
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
}

.gbpc14bxe {
  stop-color: var(--svg-color--ffe337, #FFE337);
  stop-opacity: 0;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gk-vm5f6h {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.303 9.777c.063.085-.07.188-.22.301c-.151.113-.263.192-.327.107c-.063-.085.008-.245.158-.358c.151-.113.325-.135.389-.05");
}

.gsggv-b-p {
  stop-color: var(--svg-color--f09429, #F09429);
  stop-opacity: 0;
}

.guhwv3amf {
  stop-color: var(--svg-color--82625c, #82625C);
}

.gvd3e3nnk {
  stop-color: var(--svg-color--bdb2af, #BDB2AF);
}

.gwbo6ccta {
  stop-color: var(--svg-color--745e58, #745E58);
}

.h0-3hob0r {
  stop-color: var(--svg-color--523135, #523135);
  stop-opacity: 0;
}

.h11_utkon {
  stop-color: var(--svg-color--b96201, #B96201);
}

.ha2cq84sa {
  stop-color: var(--svg-color--c9681c, #C9681C);
}

.hjqvsnb9q {
  stop-color: var(--svg-color--83645e, #83645E);
}

.hmw0arboa {
  stop-color: var(--svg-color--703e47, #703E47);
  stop-opacity: 0;
}

.hottnizrg {
  stop-color: var(--svg-color--ffd336, #FFD336);
  stop-opacity: 0;
}

.ie4iw9rqt {
  stop-color: var(--svg-color--8a6a62, #8A6A62);
}

.ioik6xbji {
  stop-color: var(--svg-color--64423e, #64423E);
}

.iopru_05u {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.125 8.289c.322-.078 1.124-.04 1.66.344");
}

.irsecfb6v {
  d: path("M28.704 16.861h-.614a.505.505 0 0 0-.503.504v3.022c0 .272.221.504.503.504h.613a.505.505 0 0 0 .504-.504v-3.022a.51.51 0 0 0-.504-.504");
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.j21cx9htb {
  stop-color: var(--svg-color--f0b327, #F0B327);
}

.j4l_ybb-i {
  stop-color: var(--svg-color--703e47, #703E47);
}

.j6yebebjj {
  d: path("M15.582 2.871c-1.133-.25-2.347.956-2.464 1.375c1.542 3.62 3.91 3.275 6.537 2.983c1.572-.175 1.743.542 1.877.888c-.436-4.056-3.369-4.676-5.95-5.246");
}

.jaal1e-1o {
  stop-color: var(--svg-color--544168, #544168);
}

.jh40i5bvl {
  stop-color: var(--svg-color--ffda39, #FFDA39);
  stop-opacity: 0;
}

.jko77nbfm {
  stop-color: var(--svg-color--546, #546);
}

.js4l338js {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.576 9.316c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.js7rwm17w {
  stop-color: var(--svg-color--493757, #493757);
  stop-opacity: 0;
}

.jv6bd5qpy {
  stop-color: var(--svg-color--e29a29, #E29A29);
}

.k15_adb_y {
  cx: 13.731px;
  cy: 9.969px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.k9y_vhbis {
  stop-color: var(--svg-color--52251c, #52251C);
}

.kc7tdcpzt {
  stop-color: var(--svg-color--83645e, #83645E);
  stop-opacity: 0;
}

.kektqzbjt {
  d: path("M19.826 23.45h.692v6.326h-.692z");
}

.km_8bqcup {
  stop-color: var(--svg-color--4e425a, #4E425A);
  stop-opacity: 0;
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.kpf8h5ohf {
  stop-color: var(--svg-color--db6009, #DB6009);
  stop-opacity: 0;
}

.kszwqub4g {
  stop-color: var(--svg-color--58496a, #58496A);
}

.lcrdwk1fj {
  stop-color: var(--svg-color--c9641b, #C9641B);
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.lh8jfxn3e {
  d: path("M24.879 20.977v6.427h1.51v-6.427z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.lwc0fqtbi {
  stop-color: var(--svg-color--8b6961, #8B6961);
}

.m45oyzb-o {
  stop-color: var(--svg-color--eb9235, #EB9235);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mdj8rj_9y {
  stop-color: var(--svg-color--e4a217, #E4A217);
}

.mh422-bgz {
  d: path("M27.083 16.861h-2.901a.505.505 0 0 0-.504.504v3.022c0 .272.222.504.504.504h2.901a.505.505 0 0 0 .504-.504v-3.022a.51.51 0 0 0-.504-.504");
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.msvvb9k2w {
  stop-color: var(--svg-color--cb831d, #CB831D);
  stop-opacity: 0;
}

.mu05ugb8a {
  stop-color: var(--svg-color--ccb5a7, #CCB5A7);
  stop-opacity: 0;
}

.mw-du8b3f {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M15.043 10.093c-.265-.467-.669-.836-1.537-.836c-.38 0-.747.105-1.073.369c-.269.217-.233.495-.025.6l.556.316c.652-.21 1.373-.239 2.08-.45");
}

.nas6pmb7m {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.123 25.898h1.797");
}

.ncgvd-jsx {
  stop-color: var(--svg-color--d99201, #D99201);
}

.nf-fa4b-x {
  stop-color: var(--svg-color--473e49, #473E49);
  stop-opacity: 0;
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.nhb1mnbxx {
  d: path("M14.001 9.588a.893.893 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.892");
}

.nria2ku7r {
  stop-color: var(--svg-color--d8772c, #D8772C);
}

.nv7ilcg1p {
  stop-color: var(--svg-color--ffe049, #FFE049);
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.o18z-jbxv {
  d: path("M11.29 4.648c.622-.553 1.518-.559 2.02-.47l.403 1.291c-.257-.039-.486.05-.679.235c-.456 1.26-2.023 1.955-2.749 2.145c-.15-1.491-.067-2.246 1.006-3.201");
}

.o2uld0acg {
  stop-color: var(--svg-color--433850, #433850);
}

.o5smz7bvt {
  stop-color: var(--svg-color--6d5150, #6D5150);
}

.oaxszm67z {
  stop-color: var(--svg-color--cb6325, #CB6325);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofpq3rdpo {
  stop-color: var(--svg-color--4c1912, #4C1912);
  stop-opacity: 0;
}

.oltxz8b0t {
  stop-color: var(--svg-color--df9e26, #DF9E26);
}

.osx01ib_t {
  fill: var(--svg-color--000, #000);
  d: path("M17.858 10.48c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.p1xq25bjq {
  stop-color: var(--svg-color--d76a18, #D76A18);
  stop-opacity: 0;
}

.p4wkjrbae {
  stop-color: var(--svg-color--c9681c, #C9681C);
  stop-opacity: 0;
}

.pb_rvfc5z {
  stop-color: var(--svg-color--ffe842, #FFE842);
}

.pepyl0bfp {
  fill: var(--svg-color--bd4f26, #BD4F26);
  fill-rule: evenodd;
  d: path("m19.917 8.426l-.138.23za.268.268 0 0 1-.275.46l-.005-.002a1 1 0 0 0-.113-.059a3 3 0 0 0-.342-.134a2.3 2.3 0 0 0-1.072-.092a.268.268 0 1 1-.093-.529c.513-.09.988.001 1.328.11a3.3 3.3 0 0 1 .559.238l.009.006l.003.001h.001z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ps9cc7bdf {
  d: path("M18.303 9.777c.063.085-.07.188-.22.301c-.151.113-.263.192-.327.107c-.063-.085.008-.245.158-.358c.151-.113.325-.135.389-.05");
}

.pt18zyb3d {
  stop-color: var(--svg-color--663848, #663848);
  stop-opacity: 0;
}

.pts6vr7ld {
  stop-color: var(--svg-color--433850, #433850);
  stop-opacity: 0;
}

.pxynpwacq {
  stop-color: var(--svg-color--6e6478, #6E6478);
}

.q_kq4jbxk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M24.045 27.203h1.797");
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.q2ji4cbak {
  stop-color: var(--svg-color--d99201, #D99201);
  stop-opacity: 0;
}

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qir_1cb0f {
  stop-color: var(--svg-color--e26b25, #E26B25);
  stop-opacity: 0;
}

.qp60g8bwf {
  d: path("M15.803 10.3L15.27 12a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.646-.376-.765 0");
}

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwjswe-rp {
  stop-color: var(--svg-color--e48538, #E48538);
  stop-opacity: 0;
}

.qwu7q3ojv {
  stop-color: var(--svg-color--5d383b, #5D383B);
}

.r7k3cqb2o {
  stop-color: var(--svg-color--5a4e68, #5A4E68);
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.rlmvqsjtd {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.334 8.289c-.323-.078-1.125-.04-1.661.344");
}

.rloy1eb5h {
  stop-color: var(--svg-color--cb831d, #CB831D);
}

.rr16fpbgs {
  stop-color: var(--svg-color--ddd3e4, #DDD3E4);
}

.s_uzjwbke {
  fill: var(--svg-color--000, #000);
  d: path("M14.512 10.48a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.235");
}

.s3t3owbgt {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
  stop-opacity: 0;
}

.s6n57cb8f {
  d: path("M11.5 12.27a1.61 1.61 0 1 0 0-3.217a1.61 1.61 0 0 0 0 3.218");
}

.sa_mqwsxd {
  d: path("M11.098 9.399h.012l-.01-.265l-.01-.306c.02-.95.574-1.317.81-1.439l.051-.02q.028-.013.051-.02a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.087 1.136 1.332l-.12 3.073c-.123 2.803-2.311 4.685-4.983 4.685c-2.67 0-4.86-1.882-4.983-4.685z");
}

.sl5klgbuk {
  stop-color: var(--svg-color--4c1912, #4C1912);
}

.soxv4gbpk {
  fill: var(--svg-color--bd4f26, #BD4F26);
  d: path("m12.787 8.884l-.004.002a.268.268 0 0 1-.276-.46h.002l.003-.002l.01-.006a2 2 0 0 1 .148-.077a3 3 0 0 1 .41-.161c.34-.109.815-.2 1.328-.11a.268.268 0 1 1-.093.529a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.434.18z");
}

.sufhn4bec {
  stop-color: var(--svg-color--db6009, #DB6009);
}

.sxo3xwbvl {
  stop-color: var(--svg-color--3f3647, #3F3647);
}

.sxoxd_kke {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
  stop-opacity: 0;
}

.t_5j5obsn {
  d: path("M13.237 15.986a.196.196 0 0 0-.221-.177c-1.073.163-1.98.714-2.909 1.244c-.195.112-.357.285-.392.508q-.02.12-.02.248c0 .599.333 1.12.825 1.389c.056.03.075.104.04.159a1.582 1.582 0 0 0 1.419 2.43a.114.114 0 0 1 .119.12a1.582 1.582 0 0 0 2.495 1.402a.114.114 0 0 1 .165.039a1.582 1.582 0 0 0 2.786 0a.114.114 0 0 1 .166-.039a1.582 1.582 0 0 0 2.495-1.402a.114.114 0 0 1 .118-.12l.084.002a1.582 1.582 0 0 0 1.335-2.432a.113.113 0 0 1 .04-.16a1.58 1.58 0 0 0 .805-1.636c-.035-.223-.197-.396-.392-.508c-.928-.53-1.836-1.08-2.909-1.244a.196.196 0 0 0-.221.177c-.19 1.636-1.06 3.257-2.914 3.267c-1.854-.01-2.725-1.631-2.914-3.267");
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.tgqxysbgm {
  stop-color: var(--svg-color--d76a18, #D76A18);
}

.tl-l61q7a {
  d: path("M14.816 10.375c0-.288-.235-.48-.298-.539l-.288.28l.177.36z");
}

.tomby8_it {
  d: path("M8.943 29.906V18.17a10.9 10.9 0 0 0-3.848 8.295v3.442z");
}

.tqgfgwd_y {
  stop-color: var(--svg-color--ffe136, #FFE136);
}

.ts-j4jiou {
  d: path("M11.833 23.45h.692v6.326h-.692z");
}

.tscywp1sg {
  d: path("M16.17 18.455a2.07 2.07 0 0 1-2.075-2.075V13.8a2.07 2.07 0 0 1 2.075-2.064c1.149 0 2.075.927 2.075 2.075v2.579a2.083 2.083 0 0 1-2.075 2.065");
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.u1dpydk2y {
  d: path("M21.012 12.27a1.61 1.61 0 1 0 0-3.217a1.61 1.61 0 0 0 0 3.218");
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.udruzobgg {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.794 9.316c-.653 0-1.205.45-1.355 1.059c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.37-1.128");
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.urzzixblm {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M21.012 11.736a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.ut7pv-xgw {
  stop-color: var(--svg-color--ffe132, #FFE132);
}

.uzcrhl-du {
  d: path("M21.012 11.736a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v5f4uubno {
  d: path("M15.839 23.45h.692v6.326h-.692z");
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

.vhte_3bib {
  stop-color: var(--svg-color--523135, #523135);
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

.w608ytq9t {
  stop-color: var(--svg-color--9f6001, #9F6001);
  stop-opacity: 0;
}

.w72oynbwi {
  stop-color: var(--svg-color--e38923, #E38923);
  stop-opacity: 0;
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.wpdv-0bui {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.294 4.12c.023.243.234 1.156.544 1.71");
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.x05md6_2b {
  stop-color: var(--svg-color--d97c39, #D97C39);
}

.xjh-ixbfp {
  stop-color: var(--svg-color--755144, #755144);
}

.y2h-f9s_x {
  d: path("M11.519 11.736a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.y78upfugg {
  stop-color: var(--svg-color--8a6a62, #8A6A62);
  stop-opacity: 0;
}

.y7n0ymbzx {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
  stop-opacity: 0;
}

.yehxt3bls {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
}

.yihcw4vuy {
  stop-color: var(--svg-color--766c83, #766C83);
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

.yslyejzkq {
  stop-color: var(--svg-color--8e6b62, #8E6B62);
}

.yzbtxw7wo {
  d: path("M16.094 15.625c-6.115 0-10.999 4.728-10.999 10.791v3.49h21.65a.5.5 0 0 0 .5-.5v-2.99c0-6.063-5.037-10.791-11.151-10.791");
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.z-gx2rb2w {
  stop-color: var(--svg-color--ffe337, #FFE337);
}

.znpa4_jtv {
  d: path("M19.164 10.362a.84.84 0 0 0-.232-.462l-.26.285l.118.228z");
}

.zx6sfmbib {
  stop-color: var(--svg-color--7a464a, #7A464A);
  stop-opacity: 0;
}

</style>
