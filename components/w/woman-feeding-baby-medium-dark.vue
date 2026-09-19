<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iUETcAb" class="pjf-t617w"/></defs><g class="ft5dv1b6b"><g clip-rule="evenodd" filter="url(#i5xJ80E)" class="d2kvgvbvc"><path fill="url(#io8YD4c)" class="x9_gqbeow"/><path fill="url(#iMskAbc)" class="x9_gqbeow"/><path fill="url(#iDOgkrd)" class="x9_gqbeow"/><path fill="url(#iwsSUxc)" class="x9_gqbeow"/><path fill="url(#ivitxCY)" class="x9_gqbeow"/><path fill="url(#ihTixHb)" class="x9_gqbeow"/><path fill="url(#iYDdUdc)" class="x9_gqbeow"/><path fill="url(#i4YzXmb)" class="x9_gqbeow"/><path fill="url(#ihZasEe)" class="x9_gqbeow"/><path fill="url(#iHeOtFN)" class="x9_gqbeow"/><path fill="url(#ibm4uSd)" class="x9_gqbeow"/></g><path fill="url(#i0ZAoQF)" class="qp4zycbco"/><path fill="url(#ioBmhZT)" class="qp4zycbco"/><path fill="url(#imdmlZB)" class="wn79smb8p"/><path fill="url(#iXwVndb)" class="wn79smb8p"/><g filter="url(#igRWGoq)"><path fill="url(#icxa4Sc)" class="s3mumw3ak"/></g><g filter="url(#i4SqRie)"><path fill="url(#iywTabe)" class="tvynizzfy"/><path fill="url(#i86fBhe)" class="tvynizzfy"/></g><g filter="url(#iRRZ7Oc)"><path class="q2aqe3gcp"/><path fill="url(#iOby6jc)" class="xqfwgwgtk"/></g><g filter="url(#iPqu2jm)"><path class="stf8z_bmm"/><path fill="url(#icr80zd)" class="m-4axzvwu"/></g><g filter="url(#icthXZc)"><path fill="url(#iT9xotc)" class="mjjt73bft"/><path fill="url(#i6mSJWd)" class="mjjt73bft"/><path fill="url(#is5gSrM)" class="mjjt73bft"/><path fill="url(#i6hyhIc)" class="mjjt73bft"/><path fill="url(#i5sKlgc)" class="mjjt73bft"/></g><path fill="url(#iXhpcHd)" class="mjjt73bft"/><path fill="url(#ivBCyyk)" class="mjjt73bft"/><path fill="url(#iQrSwZc)" class="mjjt73bft"/><path fill="url(#iorGMRd)" class="mjjt73bft"/><g filter="url(#iTqUigV)"><path class="kz0x27i9e"/></g><g filter="url(#ihvaHLd)"><path class="i95604atk"/><path fill="url(#iteofTd)" class="a3tbc5xmv"/><path fill="url(#iJHN4bJ)" class="a3tbc5xmv"/><path fill="url(#ijSKxwb)" class="a3tbc5xmv"/><path fill="url(#iUgKrTd)" class="a3tbc5xmv"/></g><g filter="url(#iQXgW1d)"><use href="#iUETcAb"/><path stroke="url(#i5g3qoe)" class="rwag_k89a"/></g><use href="#iUETcAb"/><g filter="url(#iattT5d)"><path class="fgoyeobsk"/></g><g filter="url(#iiuZpZj)"><path clip-rule="evenodd" class="famsaikks"/></g><g filter="url(#ihehhSc)"><path class="x8riombqw"/></g><g filter="url(#iWG4Ocd)"><path class="pmjoy9gfn"/></g><g filter="url(#iRqwbxb)"><path class="hdiks9b2r"/><path fill="url(#i1Ti7je)" class="xhjom1bue"/></g><g filter="url(#i3u7Hme)"><path class="p3j3xcb2e"/><path fill="url(#iID4vun)" class="h4za6vamb"/><path fill="url(#i2fthWZ)" class="h4za6vamb"/></g><g filter="url(#icFJqkc)"><path stroke="url(#iS0ScQd)" class="bpy6x0bnh"/></g><g filter="url(#iZKUxhb)"><path fill="url(#ieHwUgq)" class="slflcebha"/></g><g filter="url(#iGZQeOU)"><path fill="url(#ilNlqOb)" class="s_-u-2bws"/></g><g filter="url(#iqjOz1a)"><path class="m_q3kzbjk"/></g><path fill="url(#i1KMnzQ)" class="suima7b6r"/><path fill="url(#idLrZde)" class="np919joeo"/><g filter="url(#i6aiude)" class="tryqaac1t"><path stroke="url(#iuAXFva)" class="xtnm1oqzo"/><path stroke="url(#icicMpb)" class="xtnm1oqzo"/></g><g filter="url(#iZEpUsH)" class="tryqaac1t"><path stroke="url(#iQ2JE0c)" class="i-0l51two"/><path stroke="url(#iL0qlbe)" class="i-0l51two"/></g><path class="jws74la-i"/><path fill="url(#iinc9Pe)" class="lonlcgbkk"/><path fill="url(#iYnUIsK)" class="lonlcgbkk"/><path fill="url(#iNxIYdc)" class="lonlcgbkk"/><path fill="url(#iEyeN1d)" class="lonlcgbkk"/><path fill="url(#iIM72YB)" class="lonlcgbkk"/><path fill="url(#ip2D9KT)" class="lonlcgbkk"/><path fill="url(#i2vKZpb)" class="lonlcgbkk"/><g filter="url(#iu9Blge)"><path fill="url(#iz2LIVc)" class="udwwosyfv"/><path fill="url(#iObHQKc)" class="udwwosyfv"/><path fill="url(#iYdWN5d)" class="udwwosyfv"/></g><path fill="url(#iufQdVd)" class="a5h73f7hf"/><path fill="url(#i7Cx0eb)" class="a5h73f7hf"/><g filter="url(#iKhQzGe)"><path fill="url(#i2PEBle)" class="j_lfdybnc"/><path fill="url(#iCVzHGc)" class="j_lfdybnc"/></g><g filter="url(#idcOiCd)"><path class="bsw5abbni"/><path fill="url(#iwVO80c)" class="y0bzpp9up"/><path fill="url(#ixLYoYc)" class="y0bzpp9up"/><path fill="url(#i0a8Uwb)" class="y0bzpp9up"/></g><path fill="url(#is6Hltj)" class="a6yw8n_jr"/><path fill="url(#ifnRO1d)" class="a6yw8n_jr"/><path fill="url(#i8RA9ec)" class="u_jhhhb-d"/><path fill="url(#ihg2Wyd)" class="u_jhhhb-d"/><path fill="url(#i18LBxc)" class="eswvf6_-y"/><path fill="url(#inauR5b)" class="eswvf6_-y"/><path fill="url(#iwPU2Gd)" class="eswvf6_-y"/><path fill="url(#ixCpjge)" class="eswvf6_-y"/><path fill="url(#iJ6Cjud)" class="eswvf6_-y"/><path fill="url(#i1OUSlc)" class="s49yvhb5b"/><path fill="url(#irrDAdc)" class="lx_uj7d6x"/><path fill="url(#idnwKRc)" class="lx_uj7d6x"/><path fill="url(#iGv2UGx)" class="lx_uj7d6x"/><g filter="url(#iJmW9BT)"><path stroke="url(#iueQabb)" class="hv801ebgd"/></g><path fill="url(#ijLZBNd)" class="uz4e7xbbx"/><path fill="url(#izguwyQ)" class="uz4e7xbbx"/><path fill="url(#iz2tHLb)" class="zg_57ohhy"/><g filter="url(#iHfRVGe)"><path fill="url(#i8NwaTd)" class="f9v3--b3e"/><path fill="url(#iozFPXb)" class="f9v3--b3e"/><path fill="url(#ijzqaAL)" class="f9v3--b3e"/></g><path fill="url(#iIcMYIc)" class="sr7ktbcah"/><path fill="url(#itPDAnU)" class="sr7ktbcah"/><path fill="url(#iYn7Lbc)" class="sr7ktbcah"/><path fill="url(#iS6wsRh)" class="sr7ktbcah"/><path fill="url(#ipcB3vi)" class="sr7ktbcah"/><path class="ngv91pbee"/><path fill="url(#iVwMbxJ)" class="f1scizbig"/><path fill="url(#i5ffv1F)" class="f1scizbig"/><path class="us39mjvlv"/><path fill="url(#iiSEUDc)" class="ao0yenb4b"/><path fill="url(#iwAvekb)" class="ao0yenb4b"/><path fill="url(#iecaFln)" class="skr_hbbsa"/><path fill="url(#iepGRJe)" class="skr_hbbsa"/><path fill="url(#i8HA8ZY)" class="skr_hbbsa"/><path fill="url(#iFR37tc)" class="skr_hbbsa"/><path fill="url(#iKL3eVd)" class="bqow43gbs"/><path fill="url(#ivob3lU)" class="bqow43gbs"/><path fill="url(#ihCjNZX)" class="bqow43gbs"/><path fill="url(#iZSVhSd)" class="qqjhuct-l"/><path fill="url(#iOKb6cb)" class="qqjhuct-l"/><path fill="url(#ih6KeSb)" class="qqjhuct-l"/><path fill="url(#i8Ymrte)" class="qqjhuct-l"/><g filter="url(#inGJklc)"><path stroke="url(#iN7OdIb)" class="kiwynib4k"/></g><g filter="url(#iMes1jA)" class="mc2zb0bvp"><path class="mg9bjwbnl"/></g><g filter="url(#iocWgwc)" class="mc2zb0bvp"><path class="icdins7mm"/></g><defs><radialGradient id="iMskAbc" cx="0" cy="0" r="1" gradientTransform="matrix(.25363 4.66178 -5.79716 .3154 14.621 13.022)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iDOgkrd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.4997 2.47703 -3.26032 -3.29016 11.874 13.814)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iwsSUxc" cx="0" cy="0" r="1" gradientTransform="matrix(-.97865 1.94948 -1.49508 -.75054 9.683 11.594)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="ivitxCY" cx="0" cy="0" r="1" gradientTransform="matrix(-.88673 2.34779 -1.65025 -.62328 9.753 9.485)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="ihTixHb" cx="0" cy="0" r="1" gradientTransform="rotate(51.764 1.546 11.28)scale(2.99605 4.14789)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iYDdUdc" cx="0" cy="0" r="1" gradientTransform="rotate(124.245 8.66 6.767)scale(2.06477 2.88546)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="i4YzXmb" cx="0" cy="0" r="1" gradientTransform="rotate(153.088 9.892 6.714)scale(1.941 4.06386)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="ihZasEe" cx="0" cy="0" r="1" gradientTransform="rotate(155.281 9.609 8.261)scale(2.93381 3.75274)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iHeOtFN" cx="0" cy="0" r="1" gradientTransform="rotate(-119.38 11.114 -2.263)scale(2.84171 2.23928)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="ibm4uSd" cx="0" cy="0" r="1" gradientTransform="matrix(1.52321 -.12263 .1996 2.4794 8.187 10.729)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="ioBmhZT" cx="0" cy="0" r="1" gradientTransform="matrix(2.19471 3.52472 -6.20084 3.86104 15.93 15.484)" gradientUnits="userSpaceOnUse"><stop offset=".31" class="wcbvx-n_a"/><stop offset="1" class="sbx2zkbbn"/></radialGradient><radialGradient id="iXwVndb" cx="0" cy="0" r="1" gradientTransform="rotate(79.558 -1.928 16.921)scale(2.80186 3.89548)" gradientUnits="userSpaceOnUse"><stop offset=".782" class="wkeybb7kp"/><stop offset="1" class="kp7o84bkn"/></radialGradient><radialGradient id="iywTabe" cx="0" cy="0" r="1" gradientTransform="matrix(2.26019 -1.59227 1.95009 2.7681 18.547 10.157)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="i86fBhe" cx="0" cy="0" r="1" gradientTransform="matrix(1.44461 .49086 -.13911 .40941 19.174 7.85)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="iOby6jc" cx="0" cy="0" r="1" gradientTransform="matrix(1.47843 -.39318 .30879 1.1611 18.835 9.765)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="icr80zd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04865 .1966 -.19754 -1.0536 9.883 11.327)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="iT9xotc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.29581 3.66602 -4.19937 -7.21176 17.589 9.938)" gradientUnits="userSpaceOnUse"><stop class="hix_jbcwc"/><stop offset=".777" class="g4tdpvbfe"/></radialGradient><radialGradient id="i6mSJWd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.98598 1.36335 -.95243 -1.3874 16.468 10.418)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="is5gSrM" cx="0" cy="0" r="1" gradientTransform="matrix(.54545 -4.1601 5.25843 .68946 13.421 16.83)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="i6hyhIc" cx="0" cy="0" r="1" gradientTransform="rotate(89.22 2.917 12.413)scale(7.5975 9.45489)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="mg10me7tz"/><stop offset="1" class="kitn3twkh"/></radialGradient><radialGradient id="i5sKlgc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.6052 2.63828 -4.5621 -11.4217 16.473 11.323)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="iXhpcHd" cx="0" cy="0" r="1" gradientTransform="rotate(169.381 9.339 5.937)scale(1.29879 6.54398)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="ivBCyyk" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03409 -1.14574 1.21486 -1.09648 19.037 14.989)" gradientUnits="userSpaceOnUse"><stop class="ni-4se4rm"/><stop offset="1" class="wsh5tsbcf"/></radialGradient><radialGradient id="iQrSwZc" cx="0" cy="0" r="1" gradientTransform="matrix(1.44578 -1.88507 2.23942 1.71756 11.414 16.402)" gradientUnits="userSpaceOnUse"><stop class="z26rrllgi"/><stop offset="1" class="fs9pa7bci"/></radialGradient><radialGradient id="iorGMRd" cx="0" cy="0" r="1" gradientTransform="rotate(126.339 6.447 7.285)scale(3.20423 3.01014)" gradientUnits="userSpaceOnUse"><stop offset=".152" class="iv3uqpblx"/><stop offset="1" class="cjzjy7zus"/></radialGradient><radialGradient id="iteofTd" cx="0" cy="0" r="1" gradientTransform="rotate(-113.125 11.668 .674)scale(2.12539 .65225)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iUgKrTd" cx="0" cy="0" r="1" gradientTransform="rotate(169.381 7.162 6.68)scale(.78749 .2212)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="i1Ti7je" cx="0" cy="0" r="1" gradientTransform="rotate(-76.112 9.79 -.91)scale(3.07407 1.56779)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iID4vun" cx="0" cy="0" r="1" gradientTransform="matrix(-1.276 4.77542 -7.78462 -2.08006 14.868 2.207)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="i2fthWZ" cx="0" cy="0" r="1" gradientTransform="rotate(88.087 5.128 8.295)scale(1.40425 3.00766)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="icicMpb" cx="0" cy="0" r="1" gradientTransform="rotate(120.053 6.032 9.89)scale(.23344 .22547)" gradientUnits="userSpaceOnUse"><stop class="m-leh6bjs"/><stop offset="1" class="ka236wzgl"/></radialGradient><radialGradient id="iL0qlbe" cx="0" cy="0" r="1" gradientTransform="rotate(120.053 3.705 9.025)scale(.23344 .22547)" gradientUnits="userSpaceOnUse"><stop class="m-leh6bjs"/><stop offset="1" class="ka236wzgl"/></radialGradient><radialGradient id="iNxIYdc" cx="0" cy="0" r="1" gradientTransform="matrix(.28711 3.40925 -4.12958 .34777 8.525 20.6)" gradientUnits="userSpaceOnUse"><stop offset=".604" class="v442oubmz"/><stop offset="1" class="p_ew-572a"/></radialGradient><radialGradient id="iEyeN1d" cx="0" cy="0" r="1" gradientTransform="matrix(-.75 3.4375 -2.71722 -.59285 6.275 19.32)" gradientUnits="userSpaceOnUse"><stop offset=".518" class="m0rm-m-qv"/><stop offset="1" class="wi8a08bum"/></radialGradient><radialGradient id="iIM72YB" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15508 -.34883 1.8893 -6.25609 8.483 29.975)" gradientUnits="userSpaceOnUse"><stop class="wagk6dfaq"/><stop offset="1" class="hfzkti_ts"/></radialGradient><radialGradient id="i2vKZpb" cx="0" cy="0" r="1" gradientTransform="matrix(.1168 1.84919 -2.9447 .18598 8.731 21.804)" gradientUnits="userSpaceOnUse"><stop offset=".6" class="k5vtewq9k"/><stop offset="1" class="z1zjblq2q"/></radialGradient><radialGradient id="iz2LIVc" cx="0" cy="0" r="1" gradientTransform="rotate(109.107 -.4 18.366)scale(6.34981 4.72781)" gradientUnits="userSpaceOnUse"><stop class="v2wkn2ras"/><stop offset="1" class="yxmxw0ard"/></radialGradient><radialGradient id="iObHQKc" cx="0" cy="0" r="1" gradientTransform="rotate(-132.901 14.799 10.158)scale(4.22338 6.72611)" gradientUnits="userSpaceOnUse"><stop class="bji58ac7a"/><stop offset="1" class="eqapwmsga"/></radialGradient><radialGradient id="iYdWN5d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.62501 -3.8277 2.0945 -1.4364 20.994 25.694)" gradientUnits="userSpaceOnUse"><stop offset=".393" class="c8r1g2bnk"/><stop offset="1" class="kyl8adb5j"/></radialGradient><radialGradient id="iufQdVd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.34372 2.81254 -2.95164 -5.608 26.213 21.038)" gradientUnits="userSpaceOnUse"><stop class="z3zsa5bpu"/><stop offset="1" class="c_p6lvbtv"/></radialGradient><radialGradient id="i2PEBle" cx="0" cy="0" r="1" gradientTransform="rotate(164.954 9.003 12.702)scale(3.00943 4.47011)" gradientUnits="userSpaceOnUse"><stop class="dyh_p3bsl"/><stop offset="1" class="acgtzjb8q"/></radialGradient><radialGradient id="iCVzHGc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66156 -1.3125 1.73451 -2.1958 22.687 25.475)" gradientUnits="userSpaceOnUse"><stop class="fo4qq4q_b"/><stop offset="1" class="a6ayzxb8w"/></radialGradient><radialGradient id="iwVO80c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 0 0 -5.73004 19.15 28.913)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="jxwdq3van"/><stop offset="1" class="ytapvgb1c"/></radialGradient><radialGradient id="ixLYoYc" cx="0" cy="0" r="1" gradientTransform="rotate(33.14 -37.831 40.227)scale(2.25791 .79383)" gradientUnits="userSpaceOnUse"><stop class="uuwie8bnd"/><stop offset="1" class="nkti4m6tj"/></radialGradient><radialGradient id="i0a8Uwb" cx="0" cy="0" r="1" gradientTransform="matrix(6.57813 0 0 1.16319 12.81 29.976)" gradientUnits="userSpaceOnUse"><stop class="nz1ipmv-m"/><stop offset="1" class="uw-cne-zt"/></radialGradient><radialGradient id="is6Hltj" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.02344 -.68462 0 19.492 27.994)" gradientUnits="userSpaceOnUse"><stop offset=".372" class="rntqzsbvm"/><stop offset="1" class="kn6547brm"/></radialGradient><radialGradient id="ihg2Wyd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.5625 1.81252 -.47277 -2.23342 28.969 26.447)" gradientUnits="userSpaceOnUse"><stop class="o7yf4tl0b"/><stop offset="1" class="x9s6ceaht"/></radialGradient><radialGradient id="i18LBxc" cx="0" cy="0" r="1" gradientTransform="matrix(.84204 2.73001 -2.93117 .90409 6.65 19.85)" gradientUnits="userSpaceOnUse"><stop class="h0nz-rbjw"/><stop offset="1" class="kfbnffbzx"/></radialGradient><radialGradient id="iwPU2Gd" cx="0" cy="0" r="1" gradientTransform="rotate(110.854 -2.854 12.986)scale(2.10677 2.16117)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="jz746dbzd"/><stop offset="1" class="dzs1febsk"/></radialGradient><radialGradient id="ixCpjge" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 .87171 -.46263 -.67998 9.791 20.823)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="cwu2h0blp"/><stop offset="1" class="f9-tluqmj"/></radialGradient><radialGradient id="iJ6Cjud" cx="0" cy="0" r="1" gradientTransform="matrix(.32031 .75 -.43392 .18532 7.049 20.46)" gradientUnits="userSpaceOnUse"><stop offset=".827" class="yyn9swbvh"/><stop offset="1" class="pviihufyn"/></radialGradient><radialGradient id="iGv2UGx" cx="0" cy="0" r="1" gradientTransform="matrix(-.3711 1.25391 -.1532 -.04534 15.895 18.451)" gradientUnits="userSpaceOnUse"><stop class="tomvu1bgl"/><stop offset="1" class="sinn-3bvk"/></radialGradient><radialGradient id="iueQabb" cx="0" cy="0" r="1" gradientTransform="matrix(-.20313 -.60156 1.71998 -.58078 9.197 22.992)" gradientUnits="userSpaceOnUse"><stop class="ut4bgvb0y"/><stop offset="1" class="gngaedcou"/></radialGradient><radialGradient id="izguwyQ" cx="0" cy="0" r="1" gradientTransform="matrix(-.64063 2 -.16496 -.05284 15.707 17.79)" gradientUnits="userSpaceOnUse"><stop class="njdbcpw8w"/><stop offset="1" class="p6n8nbb9p"/></radialGradient><radialGradient id="iozFPXb" cx="0" cy="0" r="1" gradientTransform="matrix(1.42187 .6875 -.62811 1.29906 11.34 18.479)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="l8v5z5bog"/><stop offset="1" class="ll6ec2bpd"/></radialGradient><radialGradient id="itPDAnU" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0156 3.18752 -2.63101 -1.6637 9.34 18.438)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="d-33bzb2o"/><stop offset=".996" class="g2g0htigy"/></radialGradient><radialGradient id="iYn7Lbc" cx="0" cy="0" r="1" gradientTransform="rotate(119.595 -.1 11.682)scale(3.70167 1.33422)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="ha1dqccsi"/><stop offset="1" class="ziy-jybcv"/></radialGradient><radialGradient id="iS6wsRh" cx="0" cy="0" r="1" gradientTransform="matrix(-.1359 3.04807 -.73147 -.03261 7.16 18.092)" gradientUnits="userSpaceOnUse"><stop class="eim87q2nu"/><stop offset="1" class="ndf7m0b2h"/></radialGradient><radialGradient id="ipcB3vi" cx="0" cy="0" r="1" gradientTransform="matrix(.25 1.01562 -.9916 .24409 8.801 20.648)" gradientUnits="userSpaceOnUse"><stop offset=".412" class="v0y0h5pun"/><stop offset="1" class="sx4xd35ql"/></radialGradient><radialGradient id="iVwMbxJ" cx="0" cy="0" r="1" gradientTransform="matrix(-.97119 .31036 -.1504 -.47062 14.184 16.427)" gradientUnits="userSpaceOnUse"><stop class="y6_vjs3df"/><stop offset="1" class="ui58-1_-x"/></radialGradient><radialGradient id="i5ffv1F" cx="0" cy="0" r="1" gradientTransform="matrix(.03125 -.93275 3.89243 .13041 12.606 17.5)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="w8ej_fbdv"/><stop offset="1" class="ycyum3z7k"/></radialGradient><radialGradient id="iiSEUDc" cx="0" cy="0" r="1" gradientTransform="rotate(-80.715 17.143 2.34)scale(.83681 3.75171)" gradientUnits="userSpaceOnUse"><stop offset=".09" class="qxxa4bmmv"/><stop offset="1" class="j25x9tegw"/></radialGradient><radialGradient id="iwAvekb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 .41406 -.20022 -.51377 13.7 17.497)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="a3emfp-7e"/><stop offset="1" class="tmyz66fau"/></radialGradient><radialGradient id="iecaFln" cx="0" cy="0" r="1" gradientTransform="matrix(-.60938 .84374 -2.96419 -2.14083 11.26 18.866)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="tnkwcrb_w"/><stop offset="1" class="fmfd79b2c"/></radialGradient><radialGradient id="iepGRJe" cx="0" cy="0" r="1" gradientTransform="matrix(1.75 1.28906 -.23264 .31583 11.465 19.211)" gradientUnits="userSpaceOnUse"><stop class="ti3jmkb7y"/><stop offset="1" class="mnw_fc_zm"/></radialGradient><radialGradient id="i8HA8ZY" cx="0" cy="0" r="1" gradientTransform="matrix(-.3672 .53142 -1.08325 -.74848 11.947 18.773)" gradientUnits="userSpaceOnUse"><stop offset=".139" class="t5sd16bfc"/><stop offset="1" class="v3_lnpb5q"/></radialGradient><radialGradient id="iFR37tc" cx="0" cy="0" r="1" gradientTransform="matrix(1.26608 -.19478 .4132 2.68585 8.589 18.473)" gradientUnits="userSpaceOnUse"><stop class="ye-ecgz9l"/><stop offset="1" class="afcdt12xs"/></radialGradient><radialGradient id="iKL3eVd" cx="0" cy="0" r="1" gradientTransform="rotate(-60.743 22.674 3.253)scale(1.93424 2.14966)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="svx6r0gzk"/><stop offset="1" class="tc83oubxb"/></radialGradient><radialGradient id="ivob3lU" cx="0" cy="0" r="1" gradientTransform="matrix(1.15624 .72351 -.29288 .46806 10.653 20.125)" gradientUnits="userSpaceOnUse"><stop class="amlvwb9ik"/><stop offset="1" class="hgj37ubhx"/></radialGradient><radialGradient id="ihCjNZX" cx="0" cy="0" r="1" gradientTransform="matrix(-.42969 1.98437 -4.09811 -.8874 10.082 19.953)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="ud0xernhq"/><stop offset="1" class="diy3tbc3u"/></radialGradient><radialGradient id="iOKb6cb" cx="0" cy="0" r="1" gradientTransform="rotate(105.675 .984 15.742)scale(1.31451 .34383)" gradientUnits="userSpaceOnUse"><stop class="cn05xwrkd"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="ih6KeSb" cx="0" cy="0" r="1" gradientTransform="rotate(105.036 .867 16.218)scale(.54206 .1592)" gradientUnits="userSpaceOnUse"><stop class="em3lc9y5i"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="i8Ymrte" cx="0" cy="0" r="1" gradientTransform="rotate(174.906 8.297 10.276)scale(.43997 .38553)" gradientUnits="userSpaceOnUse"><stop class="tzj34xnjq"/><stop offset="1" class="ugbytbngn"/></radialGradient><radialGradient id="iN7OdIb" cx="0" cy="0" r="1" gradientTransform="matrix(-.26365 -2.21465 3.37212 -.40144 7.653 21.79)" gradientUnits="userSpaceOnUse"><stop class="zbwshaccu"/><stop offset="1" class="piz2rbc3b"/></radialGradient><linearGradient id="io8YD4c" x1="17.814" x2="13.358" y1="2.659" y2="16.486" gradientUnits="userSpaceOnUse"><stop class="c1nwhtznm"/><stop offset="1" class="ogqxd-bue"/></linearGradient><linearGradient id="i0ZAoQF" x1="19.11" x2="12.221" y1="18.58" y2="30.257" gradientUnits="userSpaceOnUse"><stop class="q9xywcr7e"/><stop offset="1" class="jvlxembhy"/></linearGradient><linearGradient id="imdmlZB" x1="15.281" x2="17.104" y1="17.094" y2="18.194" gradientUnits="userSpaceOnUse"><stop class="s-e_5f8em"/><stop offset="1" class="k8_qk-bij"/></linearGradient><linearGradient id="icxa4Sc" x1="8.268" x2="9.499" y1="11.72" y2="11.489" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="iJHN4bJ" x1="13.932" x2="14.865" y1="12.063" y2="11.888" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="ijSKxwb" x1="15.014" x2="14.9" y1="12.685" y2="12.076" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="i5g3qoe" x1="14.168" x2="14.496" y1="14.343" y2="13.547" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="iS0ScQd" x1="10.421" x2="11.204" y1="4.824" y2="5.99" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="ieHwUgq" x1="13.064" x2="10.513" y1="9.77" y2="9.494" gradientUnits="userSpaceOnUse"><stop offset=".249" class="ty9b1kbqd"/><stop offset="1" class="qwt3z0bcj"/></linearGradient><linearGradient id="ilNlqOb" x1="17.564" x2="14.266" y1="9.266" y2="8.17" gradientUnits="userSpaceOnUse"><stop offset=".394" class="vx130hb0m"/><stop offset="1" class="nvx95vy5s"/></linearGradient><linearGradient id="i1KMnzQ" x1="17.509" x2="16.026" y1="9.965" y2="10.748" gradientUnits="userSpaceOnUse"><stop offset=".558" class="incjljb4q"/><stop offset="1" class="j9v6w1g-o"/></linearGradient><linearGradient id="idLrZde" x1="13.239" x2="11.751" y1="10.686" y2="11.466" gradientUnits="userSpaceOnUse"><stop offset=".558" class="incjljb4q"/><stop offset="1" class="j9v6w1g-o"/></linearGradient><linearGradient id="iuAXFva" x1="15.581" x2="17.792" y1="10.058" y2="10.212" gradientUnits="userSpaceOnUse"><stop class="m-leh6bjs"/><stop offset="1" class="ka236wzgl"/></linearGradient><linearGradient id="iQ2JE0c" x1="11.34" x2="13.551" y1="10.773" y2="10.927" gradientUnits="userSpaceOnUse"><stop class="m-leh6bjs"/><stop offset="1" class="ka236wzgl"/></linearGradient><linearGradient id="iinc9Pe" x1="8.994" x2="3.525" y1="26.288" y2="24.819" gradientUnits="userSpaceOnUse"><stop class="g1c-6jb6y"/><stop offset="1" class="hkdf97w8c"/></linearGradient><linearGradient id="iYnUIsK" x1="3.219" x2="5.213" y1="25.916" y2="26.569" gradientUnits="userSpaceOnUse"><stop class="da95trp0k"/><stop offset="1" class="feoz1vgta"/></linearGradient><linearGradient id="ip2D9KT" x1="9.115" x2="8.722" y1="28.306" y2="28.181" gradientUnits="userSpaceOnUse"><stop class="rehc034in"/><stop offset="1" class="psvt8ubmu"/></linearGradient><linearGradient id="i7Cx0eb" x1="24.494" x2="24.182" y1="25.319" y2="23.85" gradientUnits="userSpaceOnUse"><stop class="dy155dxdg"/><stop offset="1" class="dypnkmnss"/></linearGradient><linearGradient id="ifnRO1d" x1="19.28" x2="19.28" y1="26.608" y2="27.447" gradientUnits="userSpaceOnUse"><stop class="y-ymn0bhn"/><stop offset="1" class="he69lvb0i"/></linearGradient><linearGradient id="i8RA9ec" x1="26.432" x2="26.869" y1="26.757" y2="30.476" gradientUnits="userSpaceOnUse"><stop class="tnk2b_bjh"/><stop offset="1" class="p40qzpbtf"/></linearGradient><linearGradient id="inauR5b" x1="5.719" x2="6.797" y1="19.729" y2="21.432" gradientUnits="userSpaceOnUse"><stop class="j4n7g28_w"/><stop offset="1" class="laie_nbgc"/></linearGradient><linearGradient id="i1OUSlc" x1="12.236" x2="11.849" y1="20.238" y2="18.257" gradientUnits="userSpaceOnUse"><stop class="fu3c0cblo"/><stop offset="1" class="pdon63boo"/></linearGradient><linearGradient id="irrDAdc" x1="15.963" x2="15.182" y1="18.038" y2="21.025" gradientUnits="userSpaceOnUse"><stop class="e6bcurcdv"/><stop offset="1" class="jxwnoqbqn"/></linearGradient><linearGradient id="idnwKRc" x1="15.09" x2="15.313" y1="21.244" y2="20.354" gradientUnits="userSpaceOnUse"><stop class="w_57dfb5m"/><stop offset="1" class="t78i98bfv"/></linearGradient><linearGradient id="ijLZBNd" x1="14.838" x2="13.713" y1="17.272" y2="21.6" gradientUnits="userSpaceOnUse"><stop class="nn3wh7bnm"/><stop offset="1" class="tbs366q3s"/></linearGradient><linearGradient id="iz2tHLb" x1="15.15" x2="14.041" y1="17.648" y2="17.288" gradientUnits="userSpaceOnUse"><stop class="h94nvm15h"/><stop offset="1" class="qtvy6rbzh"/></linearGradient><linearGradient id="i8NwaTd" x1="14.338" x2="13.108" y1="17.163" y2="21.913" gradientUnits="userSpaceOnUse"><stop class="qic_n_blg"/><stop offset="1" class="qh-ows9fr"/></linearGradient><linearGradient id="ijzqaAL" x1="12.434" x2="12.653" y1="20.979" y2="19.901" gradientUnits="userSpaceOnUse"><stop class="e122-lbju"/><stop offset="1" class="grqmao4rm"/></linearGradient><linearGradient id="iIcMYIc" x1="8.307" x2="8.85" y1="16.663" y2="21.163" gradientUnits="userSpaceOnUse"><stop class="uptie3ora"/><stop offset="1" class="w5xbz1t2h"/></linearGradient><linearGradient id="iZSVhSd" x1="16.406" x2="15.822" y1="18.538" y2="21.038" gradientUnits="userSpaceOnUse"><stop class="neym138jd"/><stop offset="1" class="kmp3a3cnr"/></linearGradient><filter id="i5xJ80E" width="15.897" height="16.648" x="6.933" y="1.154" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3536"/></filter><filter id="igRWGoq" width="3.403" height="3.267" x="8.172" y="9.709" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3536"/></filter><filter id="i4SqRie" width="3.253" height="3.517" x="17.621" y="7.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3536"/></filter><filter id="iRRZ7Oc" width="3.171" height="3.181" x="17.662" y="7.981" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3536" stdDeviation=".25"/></filter><filter id="iPqu2jm" width="2.671" height="2.681" x="8.483" y="9.999" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3536" stdDeviation=".125"/></filter><filter id="icthXZc" width="10.674" height="10.709" x="9.017" y="6.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3536"/></filter><filter id="iTqUigV" width="2.882" height="3.777" x="13.32" y="9.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3536" stdDeviation=".25"/></filter><filter id="ihvaHLd" width="2.382" height="3.266" x="13.705" y="9.66" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3536" stdDeviation=".125"/></filter><filter id="iQXgW1d" width="3.685" height="1.837" x="13.227" y="12.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3536" stdDeviation=".05"/></filter><filter id="iattT5d" width="2.412" height="1.314" x="10.331" y="7.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3536"/></filter><filter id="iiuZpZj" width="2.507" height=".892" x="15.472" y="7.064" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3536"/></filter><filter id="ihehhSc" width="2.313" height=".776" x="15.496" y="7.184" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3536" stdDeviation=".1"/></filter><filter id="iWG4Ocd" width="2.211" height="1.188" x="10.328" y="7.964" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3536" stdDeviation=".1"/></filter><filter id="iRqwbxb" width="4.069" height="5.117" x="7.384" y="4.132" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.262745 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3536"/><feGaussianBlur result="effect2_foregroundBlur_4002_3536" stdDeviation=".2"/></filter><filter id="i3u7Hme" width="9.45" height="4.734" x="10.087" y="2.559" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3536"/><feGaussianBlur result="effect2_foregroundBlur_4002_3536" stdDeviation=".125"/></filter><filter id="icFJqkc" width="1.46" height="2.204" x="10.057" y="4.181" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3536" stdDeviation=".1"/></filter><filter id="iZKUxhb" width="3.737" height="2.909" x="10.35" y="8.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3536" stdDeviation=".3"/></filter><filter id="iGZQeOU" width="3.557" height="2.828" x="14.973" y="7.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3536" stdDeviation=".3"/></filter><filter id="iqjOz1a" width="7.127" height="3.854" x="12.748" y="3.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3536" stdDeviation=".5"/></filter><filter id="i6aiude" width="2.476" height="1.199" x="15.472" y="9.315" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3536" stdDeviation=".075"/></filter><filter id="iZEpUsH" width="2.476" height="1.199" x="11.231" y="10.03" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3536" stdDeviation=".075"/></filter><filter id="iu9Blge" width="11.192" height="8.359" x="11.351" y="21.867" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.607843 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3536"/></filter><filter id="iKhQzGe" width="7.407" height="8.444" x="18.933" y="18.695" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3536"/></filter><filter id="idcOiCd" width="8.208" height="4.667" x="12.302" y="25.308" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.309804 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3536"/></filter><filter id="iJmW9BT" width="3.456" height="1.701" x="7.266" y="21.779" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3536" stdDeviation=".1"/></filter><filter id="iHfRVGe" width="4.309" height="4.662" x="10.928" y="16.44" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.552941 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3536"/></filter><filter id="inGJklc" width="3.647" height="2.753" x="6.149" y="19.526" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3536" stdDeviation=".05"/></filter><filter id="iMes1jA" width="2.634" height="2.141" x="16.259" y="25.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3536" stdDeviation=".125"/></filter><filter id="iocWgwc" width="4.536" height="1" x="12.632" y="28.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3536" stdDeviation=".15"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-feeding-baby-medium-dark" /></template>
<style>
.a3emfp-7e {
  stop-color: var(--svg-color--967970, #967970);
}

.a3tbc5xmv {
  d: path("m14.168 10.27l-.21 1.796a.547.547 0 0 0 .649.6l.78-.146a.55.55 0 0 0 .387-.795l-.846-1.597c-.184-.354-.712-.255-.76.143");
}

.a5h73f7hf {
  d: path("M23.33 27.135a4.3 4.3 0 1 0 0-8.6a4.3 4.3 0 0 0 0 8.6");
}

.a6ayzxb8w {
  stop-color: var(--svg-color--289d47, #289D47);
  stop-opacity: 0;
}

.a6yw8n_jr {
  d: path("M18.884 26.758a.15.15 0 0 1 .15-.15h.643v3.368h-.793z");
}

.acgtzjb8q {
  stop-color: var(--svg-color--3ba055, #3BA055);
}

.afcdt12xs {
  stop-color: var(--svg-color--7c5c50, #7C5C50);
  stop-opacity: 0;
}

.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.amlvwb9ik {
  stop-color: var(--svg-color--9b7c73, #9B7C73);
}

.ao0yenb4b {
  d: path("M9.555 17.358c.243.25.33.526.343.633l.485.469l2.341.407a.89.89 0 0 0 1.025-.693a.9.9 0 0 0-.775-1.078c-1.09-.133-2.42-.306-2.779-.347c-.613-.07-.945.297-.64.61");
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.bji58ac7a {
  stop-color: var(--svg-color--208d47, #208D47);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.bpy6x0bnh {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M10.357 4.481c.069.238.45 1.11.86 1.604");
}

.bqow43gbs {
  d: path("M8.742 20.905c-.314.22-.722.211-.906-.11c-.391-.947.721-1.579 1.5-1.597c1.168-.027 1.75.629 1.938 1.121s.226 1.477-.672 1.54c-.804.055-.848-.5-.98-.743c-.134-.242-.594-.41-.88-.21");
}

.bsw5abbni {
  fill: var(--svg-color--7d5252, #7D5252);
  d: path("M17.065 25.658a.937.937 0 0 0-1.12 1.497l.931.802a.1.1 0 0 1-.063.176l-3.643.072a.886.886 0 0 0 .017 1.77h6.06v-1l1.062-1.226z");
}

.c_p6lvbtv {
  stop-color: var(--svg-color--31be7d, #31BE7D);
}

.c1nwhtznm {
  stop-color: var(--svg-color--45363a, #45363A);
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c8r1g2bnk {
  stop-color: var(--svg-color--148c3e, #148C3E);
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

.cjzjy7zus {
  stop-color: var(--svg-color--926c64, #926C64);
  stop-opacity: 0;
}

.cn05xwrkd {
  stop-color: var(--svg-color--fed466, #FED466);
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cwu2h0blp {
  stop-color: var(--svg-color--6b3d8e, #6B3D8E);
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.d-33bzb2o {
  stop-color: var(--svg-color--734154, #734154);
  stop-opacity: 0;
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
  stop-opacity: 0;
}

.da95trp0k {
  stop-color: var(--svg-color--8f73b3, #8F73B3);
}

.diy3tbc3u {
  stop-color: var(--svg-color--713d53, #713D53);
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
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

.dzs1febsk {
  stop-color: var(--svg-color--6f409a, #6F409A);
  stop-opacity: 0;
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e122-lbju {
  stop-color: var(--svg-color--8b72aa, #8B72AA);
}

.e6bcurcdv {
  stop-color: var(--svg-color--6cd9f5, #6CD9F5);
}

.eim87q2nu {
  stop-color: var(--svg-color--7f635a, #7F635A);
}

.em3lc9y5i {
  stop-color: var(--svg-color--fed064, #FED064);
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.eqapwmsga {
  stop-color: var(--svg-color--208d47, #208D47);
  stop-opacity: 0;
}

.eswvf6_-y {
  d: path("M10.1 21.662c-.284.88-1.448 1.292-2.6.92c-1.153-.37-1.793-1.177-1.573-2.265c.18-.888.883-1.75 2.738-1.24c1.152.372 1.718 1.705 1.434 2.585");
}

.f1scizbig {
  d: path("M9.984 16.437c.357.124.482.33.516.453l.445.39l2.292.362a.92.92 0 0 0 1.061-.871a.913.913 0 0 0-.922-.95c-1.174.013-2.687.035-3.044.026c-.586-.016-.793.433-.348.59");
}

.f9-tluqmj {
  stop-color: var(--svg-color--6b3d8e, #6B3D8E);
  stop-opacity: 0;
}

.f9v3--b3e {
  d: path("m12.052 16.44l2.636.735c.356.104.644.406.52.797l-.778 2.704c-.096.329-.443.504-.852.393l-2.6-.733z");
}

.famsaikks {
  fill: var(--svg-color--352827, #352827);
  fill-rule: evenodd;
  d: path("m17.601 7.429l-.094.255zc.14.052.213.209.16.35a.27.27 0 0 1-.347.16l-.005-.002a1 1 0 0 0-.123-.037a3 3 0 0 0-.366-.07a2.3 2.3 0 0 0-1.082.107a.272.272 0 0 1-.191-.51a2.8 2.8 0 0 1 1.34-.138a3.3 3.3 0 0 1 .599.134l.01.004l.003.001z");
}

.feoz1vgta {
  stop-color: var(--svg-color--8f73b3, #8F73B3);
  stop-opacity: 0;
}

.fgoyeobsk {
  fill: var(--svg-color--352827, #352827);
  d: path("m10.777 9.087l-.004.003a.27.27 0 0 1-.381-.04a.273.273 0 0 1 .04-.383v-.001l.003-.002l.009-.007a2 2 0 0 1 .137-.098c.092-.062.224-.142.387-.222a2.8 2.8 0 0 1 1.313-.3a.272.272 0 0 1-.017.545a2.3 2.3 0 0 0-1.06.246a3 3 0 0 0-.427.259");
}

.fmfd79b2c {
  stop-color: var(--svg-color--764d50, #764D50);
}

.fo4qq4q_b {
  stop-color: var(--svg-color--289d47, #289D47);
}

.fs9pa7bci {
  stop-color: var(--svg-color--6e494b, #6E494B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fu3c0cblo {
  stop-color: var(--svg-color--f38820, #F38820);
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g1c-6jb6y {
  stop-color: var(--svg-color--8a4fe4, #8A4FE4);
}

.g2g0htigy {
  stop-color: var(--svg-color--612e25, #612E25);
}

.g4tdpvbfe {
  stop-color: var(--svg-color--754b4f, #754B4F);
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gngaedcou {
  stop-color: var(--svg-color--8a68c3, #8A68C3);
  stop-opacity: 0;
}

.grqmao4rm {
  stop-color: var(--svg-color--b59cc2, #B59CC2);
  stop-opacity: 0;
}

.h0nz-rbjw {
  stop-color: var(--svg-color--7f5499, #7F5499);
}

.h4za6vamb {
  d: path("M12.396 2.81c-1.172-.04-1.97 1.278-2.01 1.718c1.709 3.341 4.316 2.652 6.87 1.872c1.53-.468 1.833.216 2.03.536c-.735-3.924-4.194-4.038-6.86-4.126z");
}

.h94nvm15h {
  stop-color: var(--svg-color--43b1db, #43B1DB);
}

.ha1dqccsi {
  stop-color: var(--svg-color--7d5d51, #7D5D51);
}

.hdiks9b2r {
  fill: var(--svg-color--2a191e, #2A191E);
  d: path("M8.298 5.439c.45-.704 1.512-.904 2.02-.907l.635 1.214c-.259.008-.466.14-.62.359c-.21 1.34-1.61 2.321-2.283 2.644c-.427-1.46-.338-2.395.248-3.31");
}

.he69lvb0i {
  stop-color: var(--svg-color--755994, #755994);
  stop-opacity: 0;
}

.hfzkti_ts {
  stop-color: var(--svg-color--8e5de1, #8E5DE1);
  stop-opacity: 0;
}

.hgj37ubhx {
  stop-color: var(--svg-color--9b7c73, #9B7C73);
  stop-opacity: 0;
}

.hix_jbcwc {
  stop-color: var(--svg-color--996c5d, #996C5D);
}

.hkdf97w8c {
  stop-color: var(--svg-color--804ec1, #804EC1);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.hv801ebgd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M7.666 23.007c.578.14 1.919.172 2.656-.828");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i-0l51two {
  d: path("M11.481 10.688c.124.116.492.335.97.283c.479-.052.899-.516 1.007-.69");
}

.i95604atk {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m14.168 10.27l-.21 1.796a.547.547 0 0 0 .649.6l.78-.146a.55.55 0 0 0 .387-.795l-.846-1.597c-.184-.354-.712-.255-.76.143");
}

.icdins7mm {
  stroke: var(--svg-color--8c6565, #8C6565);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.132 29.072h3.535");
}

.incjljb4q {
  stop-color: var(--svg-color--090c09, #090C09);
}

.iv3uqpblx {
  stop-color: var(--svg-color--926c64, #926C64);
}

.j_lfdybnc {
  d: path("M21.46 23.915a4.3 4.3 0 0 1 .71-5.22a4.31 4.31 0 0 0-2.61 6.21a4.304 4.304 0 0 0 6.78 1.01c-1.84.51-3.87-.26-4.88-2");
}

.j25x9tegw {
  stop-color: var(--svg-color--6e413f, #6E413F);
  stop-opacity: 0;
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j4n7g28_w {
  stop-color: var(--svg-color--8e72a9, #8E72A9);
}

.j9v6w1g-o {
  stop-color: var(--svg-color--0a0909, #0A0909);
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.jvlxembhy {
  stop-color: var(--svg-color--7d49d2, #7D49D2);
}

.jws74la-i {
  fill: var(--svg-color--9c84d0, #9C84D0);
  d: path("m29.03 25.315l-4.94-6.05l-3.16 8.57z");
}

.jxwdq3van {
  stop-color: var(--svg-color--6c3d40, #6C3D40);
}

.jxwnoqbqn {
  stop-color: var(--svg-color--3782ce, #3782CE);
}

.jz746dbzd {
  stop-color: var(--svg-color--6f409a, #6F409A);
}

.k_pdrlblj {
  stop-color: var(--svg-color--ebb830, #EBB830);
  stop-opacity: 0;
}

.k5vtewq9k {
  stop-color: var(--svg-color--8b5dd1, #8B5DD1);
}

.k8_qk-bij {
  stop-color: var(--svg-color--805c5f, #805C5F);
}

.ka236wzgl {
  stop-color: var(--svg-color--2b2b2b, #2B2B2B);
  stop-opacity: 0;
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kfbnffbzx {
  stop-color: var(--svg-color--7a45b3, #7A45B3);
}

.kitn3twkh {
  stop-color: var(--svg-color--5f363f, #5F363F);
}

.kiwynib4k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.478 19.726c-.205.432-.318 1.448.875 2.054c1.194.607 1.993.149 2.243-.156");
}

.kmp3a3cnr {
  stop-color: var(--svg-color--ce953a, #CE953A);
}

.kn6547brm {
  stop-color: var(--svg-color--8259a4, #8259A4);
}

.kp7o84bkn {
  stop-color: var(--svg-color--6b4259, #6B4259);
}

.kyl8adb5j {
  stop-color: var(--svg-color--148c3e, #148C3E);
  stop-opacity: 0;
}

.kz0x27i9e {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m14.184 10.41l-.36 1.824c-.043.37.281.67.647.601l.781-.146a.55.55 0 0 0 .386-.795l-.845-1.597c-.184-.355-.56-.284-.609.114");
}

.l__dw9bpv {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
  stop-opacity: 0;
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l8v5z5bog {
  stop-color: var(--svg-color--6e574e, #6E574E);
}

.laie_nbgc {
  stop-color: var(--svg-color--8e72a9, #8E72A9);
  stop-opacity: 0;
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.ll6ec2bpd {
  stop-color: var(--svg-color--6e574e, #6E574E);
  stop-opacity: 0;
}

.lonlcgbkk {
  d: path("m2.086 29.975l2.93-9.156c.352-1.414 2.07-2.104 3.65-1.614s2.49 2.333 2.006 3.692l-2.216 7.078z");
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.lx_uj7d6x {
  d: path("m15.415 17.841l.555.16a.15.15 0 0 1 .102.185l-.783 2.73a.15.15 0 0 1-.186.103l-.555-.16z");
}

.m_q3kzbjk {
  fill: var(--svg-color--47383d, #47383D);
  d: path("m16.057 5.852l-1.36.524a.698.698 0 1 1-.38-1.338l2.322-.435c1.375-.258 2.09 1.05 2.236 1.514a3.17 3.17 0 0 0-2.818-.265");
}

.m-4axzvwu {
  d: path("M10.02 12.411c.588-.11.976-.68.865-1.271a1.09 1.09 0 0 0-1.268-.872c-.589.11-.977.68-.866 1.271c.111.592.679.983 1.268.872");
}

.m-leh6bjs {
  stop-color: var(--svg-color--2b2b2b, #2B2B2B);
}

.m0rm-m-qv {
  stop-color: var(--svg-color--785191, #785191);
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mg10me7tz {
  stop-color: var(--svg-color--794958, #794958);
  stop-opacity: 0;
}

.mg9bjwbnl {
  stroke: var(--svg-color--8f706a, #8F706A);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m16.76 26.266l1.634 1.14");
}

.mjjt73bft {
  d: path("m9.163 10.157l.012-.002l-.06-.263l-.067-.304c-.157-.95.324-1.42.535-1.586l.047-.03l.048-.03c.483-.344.831-.851.95-1.453l.045-.21a.266.266 0 0 1 .45-.136a3.9 3.9 0 0 0 3.48 1.076l3.198-.6c.179-.033 1.091-.114 1.377 1.118l.457 3.089c.402 2.82-1.42 5.105-4.073 5.602c-2.653.498-5.179-.973-5.826-3.746z");
}

.mnw_fc_zm {
  stop-color: var(--svg-color--94776f, #94776F);
  stop-opacity: 0;
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n8jici3hn {
  stop-color: var(--svg-color--fed466, #FED466);
  stop-opacity: 0;
}

.ndf7m0b2h {
  stop-color: var(--svg-color--7f635a, #7F635A);
  stop-opacity: 0;
}

.neym138jd {
  stop-color: var(--svg-color--f3c22a, #F3C22A);
}

.ngv91pbee {
  fill: var(--svg-color--7c5b4d, #7C5B4D);
  d: path("M9.984 16.437c.357.124.482.33.516.453l.445.39l2.292.362a.92.92 0 0 0 1.061-.871a.913.913 0 0 0-.922-.95c-1.174.013-2.687.035-3.044.026c-.586-.016-.793.433-.348.59");
}

.ni-4se4rm {
  stop-color: var(--svg-color--836462, #836462);
}

.njdbcpw8w {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
}

.nkti4m6tj {
  stop-color: var(--svg-color--7d505c, #7D505C);
  stop-opacity: 0;
}

.nn3wh7bnm {
  stop-color: var(--svg-color--58d4f5, #58D4F5);
}

.np919joeo {
  d: path("M13.306 10.12c-.076.009-.133.056-.18.123a1.05 1.05 0 0 1-.703.484a1 1 0 0 1-.816-.21a.24.24 0 0 0-.209-.056a.253.253 0 0 0-.114.446a1.5 1.5 0 0 0 1.234.323a1.52 1.52 0 0 0 1.054-.731c.105-.18-.057-.408-.266-.38");
}

.nvx95vy5s {
  stop-color: var(--svg-color--8e5d56, #8E5D56);
  stop-opacity: 0;
}

.nz1ipmv-m {
  stop-color: var(--svg-color--7c4264, #7C4264);
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.o7yf4tl0b {
  stop-color: var(--svg-color--b087f9, #B087F9);
}

.ogqxd-bue {
  stop-color: var(--svg-color--1c151f, #1C151F);
}

.olqyf7fmb {
  stop-color: var(--svg-color--875e5e, #875E5E);
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

.p_ew-572a {
  stop-color: var(--svg-color--8152c8, #8152C8);
  stop-opacity: 0;
}

.p3j3xcb2e {
  fill: var(--svg-color--2f1920, #2F1920);
  d: path("M12.396 2.81c-1.172-.04-1.97 1.278-2.01 1.718c1.709 3.341 4.316 2.652 6.87 1.872c1.53-.468 1.833.216 2.03.536c-.735-3.924-4.194-4.038-6.86-4.126z");
}

.p40qzpbtf {
  stop-color: var(--svg-color--985ef1, #985EF1);
}

.p6n8nbb9p {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pdon63boo {
  stop-color: var(--svg-color--f38820, #F38820);
  stop-opacity: 0;
}

.piz2rbc3b {
  stop-color: var(--svg-color--875ab4, #875AB4);
  stop-opacity: 0;
}

.pjf-t617w {
  fill: var(--svg-color--88014f, #88014F);
  d: path("M15.108 13.518a3.05 3.05 0 0 1-1.476-.08c-.154-.046-.274.143-.161.257a1.95 1.95 0 0 0 1.78.583a1.95 1.95 0 0 0 1.447-1.188c.062-.152-.117-.28-.243-.181c-.367.295-.825.51-1.347.608");
}

.pmjoy9gfn {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.238 8.268c-.333-.033-1.13.121-1.61.583");
}

.psvt8ubmu {
  stop-color: var(--svg-color--8356d1, #8356D1);
  stop-opacity: 0;
}

.pviihufyn {
  stop-color: var(--svg-color--784787, #784787);
  stop-opacity: 0;
}

.q2aqe3gcp {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M19.448 10.644c.59-.11.977-.68.866-1.272a1.09 1.09 0 0 0-1.268-.872c-.589.11-.976.68-.866 1.272c.111.592.679.982 1.268.872");
}

.q9xywcr7e {
  stop-color: var(--svg-color--9c6ed3, #9C6ED3);
}

.qh-ows9fr {
  stop-color: var(--svg-color--a07cb6, #A07CB6);
}

.qic_n_blg {
  stop-color: var(--svg-color--d2c9d1, #D2C9D1);
}

.qp4zycbco {
  d: path("M7.04 29.975c-1.05 0-1.9-.85-1.89-1.9l.01-2.13c0-5.77 4.79-10.46 10.69-10.46c5.91 0 10.69 4.68 10.69 10.46l.17 4.03z");
}

.qqjhuct-l {
  d: path("m15.339 20.74l.227.069a.5.5 0 0 0 .492-.12l.364-.352a.13.13 0 0 1 .127-.034l.315.084a.485.485 0 0 0 .253-.935l-.303-.083a.13.13 0 0 1-.098-.108l-.069-.44a.5.5 0 0 0-.36-.404l-.26-.072z");
}

.qtvy6rbzh {
  stop-color: var(--svg-color--42b8e0, #42B8E0);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.qwt3z0bcj {
  stop-color: var(--svg-color--70434c, #70434C);
  stop-opacity: 0;
}

.qxxa4bmmv {
  stop-color: var(--svg-color--6e413f, #6E413F);
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.rehc034in {
  stop-color: var(--svg-color--8356d1, #8356D1);
}

.rntqzsbvm {
  stop-color: var(--svg-color--925cbe, #925CBE);
}

.rwag_k89a {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.108 13.518a3.05 3.05 0 0 1-1.476-.08c-.154-.046-.274.143-.161.257a1.95 1.95 0 0 0 1.78.583a1.95 1.95 0 0 0 1.447-1.188c.062-.152-.117-.28-.243-.181c-.367.295-.825.51-1.347.608Z");
}

.s_-u-2bws {
  d: path("M15.65 8.054c.99-.311 2.28.223 2.28 1.542c-.638-.355-1.906-.493-2.357-.355z");
}

.s-e_5f8em {
  stop-color: var(--svg-color--5f3547, #5F3547);
}

.s3mumw3ak {
  d: path("M10.1 12.948a1.63 1.63 0 0 0 1.297-1.905a1.63 1.63 0 0 0-1.9-1.306a1.63 1.63 0 0 0-1.296 1.905a1.63 1.63 0 0 0 1.899 1.306");
}

.s49yvhb5b {
  d: path("M10.45 18.545c-.28.05-.54.19-.74.38c.01-.05.02-.1.04-.15l.12-.33c.28-.78 1.09-1.27 1.91-1.15l1.66.23c.42.06.72.45.66.87s-.45.72-.87.66l-1.57-.22c-.34-.26-.78-.37-1.21-.29");
}

.sbx2zkbbn {
  stop-color: var(--svg-color--89579c, #89579C);
  stop-opacity: 0;
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sinn-3bvk {
  stop-color: var(--svg-color--6cd8f5, #6CD8F5);
  stop-opacity: 0;
}

.skr_hbbsa {
  d: path("M8.406 18.456a.28.28 0 0 1 .133-.27c.982-.69 2.005-.304 2.383 0c.305.236 1 .79 1.363 1.083c.446.36.373.96.043 1.316c-.276.298-.751.241-.93.148l-2.097-1.312c-.055-.312-.234-.562-.48-.637c-.247-.074-.403-.133-.415-.328");
}

.slflcebha {
  d: path("M10.95 8.955c1.305-.25 2.27.34 2.537 1.068c-1.342.197-1.936.36-2.35.583z");
}

.sr7ktbcah {
  d: path("M8.016 17.218c1.03-1.086 1.919-1.37 2.32-1.375l.797.867l-.93 3.516c-.18.315-.564.996-.695 1.152c-.164.195-.735.63-1.766.238c-.887-.337-1.15-.898-1.176-1.148c.234-1.168.65-2.358 1.45-3.25");
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.stf8z_bmm {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M10.02 12.411c.588-.11.976-.68.865-1.271a1.09 1.09 0 0 0-1.268-.872c-.589.11-.977.68-.866 1.271c.111.592.679.983 1.268.872");
}

.suima7b6r {
  d: path("M17.577 9.404c-.076.01-.133.057-.18.124a1.05 1.05 0 0 1-.703.484a.96.96 0 0 1-.817-.219a.27.27 0 0 0-.209-.057a.253.253 0 0 0-.113.447c.332.275.778.408 1.234.322a1.52 1.52 0 0 0 1.053-.73c.105-.181-.056-.409-.265-.37");
}

.svx6r0gzk {
  stop-color: var(--svg-color--713e53, #713E53);
}

.sx4xd35ql {
  stop-color: var(--svg-color--734054, #734054);
  stop-opacity: 0;
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

.tmyz66fau {
  stop-color: var(--svg-color--7d5b50, #7D5B50);
  stop-opacity: 0;
}

.tnk2b_bjh {
  stop-color: var(--svg-color--a078e0, #A078E0);
}

.tnkwcrb_w {
  stop-color: var(--svg-color--846256, #846256);
}

.tomvu1bgl {
  stop-color: var(--svg-color--78e0ff, #78E0FF);
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tryqaac1t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.tvynizzfy {
  d: path("M19.548 11.178a1.63 1.63 0 0 0 1.297-1.906a1.63 1.63 0 0 0-1.899-1.305a1.63 1.63 0 0 0-1.297 1.905a1.63 1.63 0 0 0 1.899 1.306");
}

.ty9b1kbqd {
  stop-color: var(--svg-color--70434c, #70434C);
}

.tzj34xnjq {
  stop-color: var(--svg-color--ffd267, #FFD267);
}

.u_jhhhb-d {
  d: path("M20.5 25.753c1.598-.23 4.567-.809 6.544-1.27c1.522-.263 2.64 1.203 2.64 2.781c0 1.372-1.022 2.237-1.746 2.619a.86.86 0 0 1-.404.093H19.52V26.89c0-.797.282-1 .98-1.137");
}

.ud0xernhq {
  stop-color: var(--svg-color--713d53, #713D53);
  stop-opacity: 0;
}

.udwwosyfv {
  d: path("M21.72 23.996c-1.17-2.04-3.78-2.73-5.81-1.56l-2.43 1.4c-2.04 1.17-2.73 3.78-1.56 5.81l.21.33h7.73l.3-.18a4.23 4.23 0 0 0 1.56-5.8");
}

.ugbytbngn {
  stop-color: var(--svg-color--ffd267, #FFD267);
  stop-opacity: 0;
}

.ui58-1_-x {
  stop-color: var(--svg-color--856053, #856053);
  stop-opacity: 0;
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.uptie3ora {
  stop-color: var(--svg-color--73564c, #73564C);
}

.us39mjvlv {
  fill: var(--svg-color--7c5a4f, #7C5A4F);
  d: path("M9.555 17.358c.243.25.33.526.343.633l.485.469l2.341.407a.89.89 0 0 0 1.025-.693a.9.9 0 0 0-.775-1.078c-1.09-.133-2.42-.306-2.779-.347c-.613-.07-.945.297-.64.61");
}

.ut4bgvb0y {
  stop-color: var(--svg-color--8a68c3, #8A68C3);
}

.uuwie8bnd {
  stop-color: var(--svg-color--6a3e48, #6A3E48);
}

.uw-cne-zt {
  stop-color: var(--svg-color--7c4264, #7C4264);
  stop-opacity: 0;
}

.uz4e7xbbx {
  d: path("m11.824 16.01l3.172.883c.43.125.744.559.627.96l-.899 3.086c-.115.396-.533.607-1.025.474l-3.128-.884z");
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

.v442oubmz {
  stop-color: var(--svg-color--7c4ca4, #7C4CA4);
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.vx130hb0m {
  stop-color: var(--svg-color--8e5d56, #8E5D56);
}

.w_57dfb5m {
  stop-color: var(--svg-color--735caf, #735CAF);
}

.w5xbz1t2h {
  stop-color: var(--svg-color--714f47, #714F47);
}

.w8ej_fbdv {
  stop-color: var(--svg-color--7e574e, #7E574E);
}

.wagk6dfaq {
  stop-color: var(--svg-color--966be0, #966BE0);
}

.wcbvx-n_a {
  stop-color: var(--svg-color--89579c, #89579C);
}

.wg3eepbwp {
  stop-color: var(--svg-color--805c54, #805C54);
}

.wi8a08bum {
  stop-color: var(--svg-color--785191, #785191);
  stop-opacity: 0;
}

.wkeybb7kp {
  stop-color: var(--svg-color--6b4259, #6B4259);
  stop-opacity: 0;
}

.wn79smb8p {
  d: path("M15.57 18.505c1.06 0 1.91-.86 1.91-1.91v-2.26a1.91 1.91 0 1 0-3.82 0v2.26c-.01 1.06.85 1.91 1.91 1.91");
}

.wrh2b4bbx {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
}

.wsh5tsbcf {
  stop-color: var(--svg-color--836462, #836462);
  stop-opacity: 0;
}

.x8riombqw {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.796 7.626c.306-.139 1.109-.249 1.713.034");
}

.x9_gqbeow {
  d: path("M21.853 10.54a3.3 3.3 0 0 0 .055-1.485a3.3 3.3 0 0 0-.511-1.252l.005-.001a3 3 0 0 0-.375-.46l-.003-.003a3.3 3.3 0 0 1-.854-1.669l-.002-.01a3.34 3.34 0 0 0-3.894-2.678a.54.54 0 0 1-.496-.147a3.34 3.34 0 0 0-2.92-.874a3.34 3.34 0 0 0-2.407 1.872a.57.57 0 0 1-.409.317l-.084.017a3.343 3.343 0 0 0-2.575 3.89l.002.01a3.3 3.3 0 0 1-.192 1.865l-.001.004a3.36 3.36 0 0 0 .388 3.28c.097.128.13.3.085.454a3.3 3.3 0 0 0-.058 1.464a3.255 3.255 0 0 0 3.798 2.612l8.524-1.598a3.255 3.255 0 0 0 2.594-3.81a3.3 3.3 0 0 0-.585-1.344a.53.53 0 0 1-.085-.454m-12.677-.384l-.012.002l1.631 2.127c.647 2.774 1.209-.226 3.862-.724c2.654-.497 4.394 2.399 3.992-.42l.53-3.403c-.286-1.232-1.198-1.151-1.377-1.118l-3.198.6a3.9 3.9 0 0 1-3.48-1.076a.266.266 0 0 0-.45.137l-.045.209a2.34 2.34 0 0 1-1.045 1.513c-.211.166-.692.636-.535 1.586l.067.304z");
}

.x9s6ceaht {
  stop-color: var(--svg-color--b087f9, #B087F9);
  stop-opacity: 0;
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xhjom1bue {
  d: path("M8.298 5.439c.45-.704 1.512-.904 2.02-.907l.635 1.214c-.259.008-.466.14-.62.359c-.21 1.34-1.61 2.321-2.283 2.644c-.427-1.46-.338-2.395.248-3.31");
}

.xqfwgwgtk {
  d: path("M19.448 10.644c.59-.11.977-.68.866-1.272a1.09 1.09 0 0 0-1.268-.872c-.589.11-.976.68-.866 1.272c.111.592.679.982 1.268.872");
}

.xtnm1oqzo {
  d: path("M15.722 9.973c.124.116.492.335.97.283c.479-.051.899-.515 1.007-.69");
}

.y-ymn0bhn {
  stop-color: var(--svg-color--755994, #755994);
}

.y0bzpp9up {
  d: path("M17.065 25.658a.937.937 0 0 0-1.12 1.497l.931.802a.1.1 0 0 1-.063.176l-3.643.072a.886.886 0 0 0 .017 1.77h6.06v-1l1.062-1.226z");
}

.y6_vjs3df {
  stop-color: var(--svg-color--987a70, #987A70);
}

.ycrcotb4u {
  stop-color: var(--svg-color--986f60, #986F60);
  stop-opacity: 0;
}

.ycyum3z7k {
  stop-color: var(--svg-color--7e574e, #7E574E);
  stop-opacity: 0;
}

.ye-ecgz9l {
  stop-color: var(--svg-color--7c5c50, #7C5C50);
}

.ytapvgb1c {
  stop-color: var(--svg-color--6c3d40, #6C3D40);
  stop-opacity: 0;
}

.yxmxw0ard {
  stop-color: var(--svg-color--32996b, #32996B);
}

.yyn9swbvh {
  stop-color: var(--svg-color--784787, #784787);
}

.z1zjblq2q {
  stop-color: var(--svg-color--8b5dd1, #8B5DD1);
  stop-opacity: 0;
}

.z26rrllgi {
  stop-color: var(--svg-color--6e494b, #6E494B);
}

.z3zsa5bpu {
  stop-color: var(--svg-color--53f595, #53F595);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zbwshaccu {
  stop-color: var(--svg-color--875ab4, #875AB4);
}

.zg_57ohhy {
  d: path("m14.71 17.073l-2.635-.734l-1.073 3.895l2.6.734c.409.11.755-.065.851-.394l.78-2.703c.122-.391-.165-.694-.522-.798");
}

.ziy-jybcv {
  stop-color: var(--svg-color--7d5d51, #7D5D51);
  stop-opacity: 0;
}

.zoq8fuaif {
  stop-color: var(--svg-color--986f60, #986F60);
}

</style>
