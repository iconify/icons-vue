<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iqCeyMc)" class="t5xob_buh"/><rect fill="url(#iiprDdc)" class="ub34p6b1y"/><rect fill="url(#ioWzjQd)" class="ub34p6b1y"/><path fill="url(#iqs8X1c)" class="tdekfnbnd"/><path fill="url(#iWCCmRd)" class="zvin7u5xb"/><circle fill="url(#id9k7Fe)" class="j6x4q_h4k"/><circle fill="url(#ivfID2c)" class="j6x4q_h4k"/><g filter="url(#iWbJjfc)"><circle fill="url(#iQzKTjd)" class="pt4idkkwh"/></g><circle fill="url(#imqKCKd)" class="ds8e6968j"/><circle fill="url(#iv9uAae)" class="ds8e6968j"/><g filter="url(#iKUkowc)"><circle fill="url(#igbGPie)" class="l1x0gab1i"/></g><g filter="url(#iQzUtKd)"><path fill="url(#iGVRemI)" clip-rule="evenodd" class="ss1ebabhy"/><path fill="url(#iFAsjNc)" clip-rule="evenodd" class="ss1ebabhy"/><path fill="url(#iGEf3qe)" clip-rule="evenodd" class="ss1ebabhy"/><path fill="url(#izBZXgb)" clip-rule="evenodd" class="ss1ebabhy"/><path fill="url(#iJaHDYO)" clip-rule="evenodd" class="ss1ebabhy"/></g><path fill="url(#iFAsjNc)" clip-rule="evenodd" class="ss1ebabhy"/><path fill="url(#i2F7Pgd)" clip-rule="evenodd" class="ss1ebabhy"/><g filter="url(#iz9Om1b)"><circle fill="url(#ilsJGhb)" class="pu8qn_k-c"/></g><circle fill="url(#il0CDab)" class="ddgegzc8o"/><circle class="fsa4w_a7l"/><g filter="url(#iFhh0Jb)"><circle fill="url(#i17EGDb)" transform="matrix(-1 0 0 1 18.723 13.707)" class="el7r9pbsw"/></g><circle fill="url(#i51g7Pd)" transform="matrix(-1 0 0 1 18.504 13.473)" class="y2c1oq0fx"/><circle fill="url(#iyg3sde)" transform="matrix(-1 0 0 1 18.504 13.473)" class="y2c1oq0fx"/><circle transform="matrix(-1 0 0 1 18.484 13.473)" class="m8bj1mb9s"/><g filter="url(#iRWfWbc)"><path fill="url(#itIgkLd)" class="r0mv4inkj"/></g><g filter="url(#ikGZYNb)"><path stroke="url(#iZ8l23b)" class="i6tafw00v"/></g><path fill="url(#iKFSboc)" class="n5f0f7b6s"/><path class="eyrjcjfhu"/><path fill="url(#igB6WHe)" class="op6z3p63j"/><path fill="url(#ipuiUMc)" class="sfqdrecvz"/><path fill="url(#ihCiVVb)" class="kencgo7xy"/><path stroke="url(#iw8gOob)" class="pia5784be"/><path stroke="url(#iTEuk8b)" class="vm8mukbur"/><g filter="url(#iwAu7Yc)"><path class="uycl7hbwr"/><path fill="url(#iYlfSPe)" class="gsa1cebro"/><path fill="url(#igBitBc)" class="gsa1cebro"/><path fill="url(#iNYPojb)" class="gsa1cebro"/></g><rect fill="url(#isPclrc)" class="nrll1s57d"/><rect fill="url(#ihCOUli)" class="nrll1s57d"/><rect fill="url(#iCs1UAe)" class="nrll1s57d"/><rect fill="url(#i0xK0oS)" class="nrll1s57d"/><rect fill="url(#iDJYDNb)" transform="rotate(-17.452 5.516 21.5)" class="ups_dab2u"/><rect fill="url(#iA8ciyf)" transform="rotate(-17.452 5.516 21.5)" class="ups_dab2u"/><rect fill="url(#i0KgHMc)" transform="rotate(-17.452 5.516 21.5)" class="ups_dab2u"/><rect fill="url(#ia6aRHy)" transform="rotate(-17.452 5.516 21.5)" class="ups_dab2u"/><rect fill="url(#ijHifUb)" transform="rotate(-30.06 2.878 22.898)" class="v-i1htb2z"/><rect fill="url(#iaFeg1c)" transform="rotate(-30.06 2.878 22.898)" class="v-i1htb2z"/><rect fill="url(#iAo0ZMc)" transform="rotate(-30.06 2.878 22.898)" class="v-i1htb2z"/><rect fill="url(#i19Xqom)" transform="rotate(-30.06 2.878 22.898)" class="v-i1htb2z"/><rect fill="url(#itCuVNw)" transform="rotate(-32.714 1.35 25.347)" class="qs15vj7hh"/><rect fill="url(#iVT1fBd)" transform="rotate(-32.714 1.35 25.347)" class="qs15vj7hh"/><rect fill="url(#iE2aLDR)" transform="rotate(-32.714 1.35 25.347)" class="qs15vj7hh"/><g filter="url(#i8ZbO4b)"><path class="wjubkud2f"/><path fill="url(#ieLdowE)" class="ys3eanwrh"/><path fill="url(#iYeavFd)" class="ys3eanwrh"/><path fill="url(#iEskV0x)" class="ys3eanwrh"/><path fill="url(#iyW7LBe)" class="ys3eanwrh"/><path fill="url(#iCXSQNb)" class="ys3eanwrh"/><path fill="url(#iZJRsbb)" class="ys3eanwrh"/></g><rect transform="matrix(-1 0 0 1 23.28 20.947)" class="fk_sd4b3f"/><rect fill="url(#i5cKy7J)" transform="matrix(-1 0 0 1 23.28 20.947)" class="lvqejss-o"/><rect fill="url(#iFbacFb)" transform="matrix(-1 0 0 1 23.28 20.947)" class="lvqejss-o"/><rect transform="scale(-1 1)rotate(-17.452 56.796 97.026)" class="l257jccgu"/><rect fill="url(#iAe9aMb)" transform="scale(-1 1)rotate(-17.452 56.796 97.026)" class="i7m2j00fs"/><rect fill="url(#i56EY8b)" transform="scale(-1 1)rotate(-17.452 56.796 97.026)" class="i7m2j00fs"/><rect transform="scale(-1 1)rotate(-30.061 28.077 65.676)" class="uvhjscb1o"/><rect fill="url(#iXxxUfc)" transform="scale(-1 1)rotate(-30.061 28.077 65.676)" class="gl17utj4l"/><rect fill="url(#iw4dd4c)" transform="scale(-1 1)rotate(-30.061 28.077 65.676)" class="gl17utj4l"/><rect fill="url(#ixP16ad)" transform="scale(-1 1)rotate(-32.714 27.855 64.888)" class="ij5lprb2c"/><rect fill="url(#iWnLhMc)" transform="scale(-1 1)rotate(-32.714 27.855 64.888)" class="ij5lprb2c"/><rect fill="url(#itioSUc)" transform="scale(-1 1)rotate(-32.714 27.855 64.888)" class="ij5lprb2c"/><g filter="url(#io5ntOd)"><path fill="url(#iQHbFcd)" class="wu7rmcc4r"/></g><path class="p_p2m_b9w"/><path fill="url(#iir39nb)" class="lpgc_kbrw"/><path fill="url(#i8DrZZb)" class="lpgc_kbrw"/><path fill="url(#iv97ITc)" class="lpgc_kbrw"/><path fill="url(#iNmg2Be)" class="lpgc_kbrw"/><path fill="url(#iQlJeqP)" class="lpgc_kbrw"/><path fill="url(#iPtKRBc)" class="xdz4q9o4b"/><path fill="url(#iQeJMle)" class="xdz4q9o4b"/><path fill="url(#irnNXnb)" class="xdz4q9o4b"/><path fill="url(#iSOb4Kv)" class="xdz4q9o4b"/><path fill="url(#iMq3r9d)" class="xdz4q9o4b"/><path fill="url(#iEPfRtd)" class="xdz4q9o4b"/><path fill="url(#i0BEySd)" class="xdz4q9o4b"/><g filter="url(#ixPgxYd)"><path class="yibkq3zwf"/><path fill="url(#iM8ndue)" class="xh6f20qst"/></g><path fill="url(#i9AL7Ze)" class="gas_t6b8j"/><path fill="url(#iquG9eb)" class="gas_t6b8j"/><g filter="url(#ihi6Kob)"><path fill="url(#ix1iSSc)" class="mjxxa0b8h"/></g><g filter="url(#iEySyye)"><path fill="url(#if9ltvc)" class="k5i922b3o"/></g><defs><radialGradient id="iqCeyMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.5625 22.9424 0 16.038 29.928)" gradientUnits="userSpaceOnUse"><stop offset=".272" class="udi_mfp4v"/><stop offset="1" class="rvq6gmb5w"/></radialGradient><radialGradient id="iiprDdc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.62521 -2.70813 0 16 21.677)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="dfkyv0s4o"/><stop offset="1" class="i40h4bbfl"/></radialGradient><radialGradient id="ioWzjQd" cx="0" cy="0" r="1" gradientTransform="matrix(.1582 4.32031 -2.99315 .1096 15.842 21.217)" gradientUnits="userSpaceOnUse"><stop offset=".627" class="iv7v1nb3o"/><stop offset=".924" class="q53_zdbrw"/></radialGradient><radialGradient id="iqs8X1c" cx="0" cy="0" r="1" gradientTransform="matrix(1.3885 -.35049 .83578 3.31105 9.196 17.443)" gradientUnits="userSpaceOnUse"><stop offset=".091" class="v0ax-glfp"/><stop offset="1" class="f7t6iccjp"/></radialGradient><radialGradient id="iWCCmRd" cx="0" cy="0" r="1" gradientTransform="matrix(.89421 .4728 -.77087 1.45794 21.873 17.224)" gradientUnits="userSpaceOnUse"><stop class="dgo3vt0eo"/><stop offset="1" class="adr6gcutb"/></radialGradient><radialGradient id="ivfID2c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.14062 0 0 -2.35156 10.076 14.217)" gradientUnits="userSpaceOnUse"><stop offset=".569" class="ult0y8bvs"/><stop offset="1" class="oukb_nb4n"/></radialGradient><radialGradient id="iQzKTjd" cx="0" cy="0" r="1" gradientTransform="matrix(-.89844 0 0 -1.30469 9.834 14.217)" gradientUnits="userSpaceOnUse"><stop offset=".47" class="p-lt9kb3w"/><stop offset="1" class="vsdiecbqp"/></radialGradient><radialGradient id="iv9uAae" cx="0" cy="0" r="1" gradientTransform="matrix(1.61023 0 0 2.38281 22.31 14.217)" gradientUnits="userSpaceOnUse"><stop offset=".596" class="faf527bpe"/><stop offset="1" class="u8epgmbkl"/></radialGradient><radialGradient id="igbGPie" cx="0" cy="0" r="1" gradientTransform="matrix(1.12895 -1.07641 1.63635 1.71621 21.89 14.376)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="lt6k7o0fo"/><stop offset=".791" class="a7iu9vb1v"/></radialGradient><radialGradient id="izBZXgb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.10938 2.28516 0 18.717 13.021)" gradientUnits="userSpaceOnUse"><stop offset=".622" class="m3qe5cb4h"/><stop offset="1" class="hitknonwe"/></radialGradient><radialGradient id="iJaHDYO" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.90625 1.92188 0 13.435 12.803)" gradientUnits="userSpaceOnUse"><stop offset=".279" class="vmtwlbczt"/><stop offset="1" class="gls-i-zvq"/></radialGradient><radialGradient id="ilsJGhb" cx="0" cy="0" r="1" gradientTransform="rotate(69.179 -3.061 15.181)scale(3.15946)" gradientUnits="userSpaceOnUse"><stop class="ltf0tqb9y"/><stop offset="1" class="enitdihfo"/></radialGradient><radialGradient id="il0CDab" cx="0" cy="0" r="1" gradientTransform="rotate(95.856 .802 12.838)scale(1.83772 1.80959)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="h50m5ib7f"/><stop offset="1" class="bng_m2b0t"/></radialGradient><radialGradient id="i17EGDb" cx="0" cy="0" r="1" gradientTransform="rotate(48.116 -1.842 1.568)scale(2.66802)" gradientUnits="userSpaceOnUse"><stop class="bw57fdcce"/><stop offset="1" class="hkndu6boi"/></radialGradient><radialGradient id="i51g7Pd" cx="0" cy="0" r="1" gradientTransform="matrix(-.2461 1.67187 -1.6463 -.24233 1.645 1.426)" gradientUnits="userSpaceOnUse"><stop offset=".618" class="ogpl8rbbb"/><stop offset="1" class="w0ry1tv8g"/></radialGradient><radialGradient id="itIgkLd" cx="0" cy="0" r="1" gradientTransform="rotate(-179.479 10.185 6.496)scale(3.43734 3.6257)" gradientUnits="userSpaceOnUse"><stop class="k589lpbub"/><stop offset=".808" class="ebc1zfyja"/></radialGradient><radialGradient id="iKFSboc" cx="0" cy="0" r="1" gradientTransform="rotate(-81.193 18.389 1.594)scale(2.24522 3.5001)" gradientUnits="userSpaceOnUse"><stop class="nrrnwgb2j"/><stop offset="1" class="ju7pygbji"/></radialGradient><radialGradient id="igB6WHe" cx="0" cy="0" r="1" gradientTransform="matrix(.51562 -1.05469 2.4217 1.18394 14.982 18.764)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="hbx3qwnwa"/><stop offset=".929" class="g3i-1pbcq"/></radialGradient><radialGradient id="iYlfSPe" cx="0" cy="0" r="1" gradientTransform="rotate(73.968 -11.53 15.366)scale(6.46576 13.0703)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="bxi9tgmwe"/><stop offset="1" class="tn-w78xgx"/></radialGradient><radialGradient id="igBitBc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.93323 -.03125 .0265 -1.639 14.244 27.209)" gradientUnits="userSpaceOnUse"><stop offset=".165" class="gbny4_b4j"/><stop offset="1" class="glfls735f"/></radialGradient><radialGradient id="iNYPojb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.59378 3.81248 -2.48353 -1.68964 11.842 24.99)" gradientUnits="userSpaceOnUse"><stop offset=".284" class="oxi0f3b2m"/><stop offset="1" class="vl_ql576y"/></radialGradient><radialGradient id="isPclrc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.6161 1.22861 0 10.293 23.563)" gradientUnits="userSpaceOnUse"><stop class="iw38491ye"/><stop offset="1" class="zl7ptbcaa"/></radialGradient><radialGradient id="ihCOUli" cx="0" cy="0" r="1" gradientTransform="matrix(-1.22395 0 0 -3.23423 10.681 23.328)" gradientUnits="userSpaceOnUse"><stop class="lxs7f3b1j"/><stop offset="1" class="u84zz4ukw"/></radialGradient><radialGradient id="i0xK0oS" cx="0" cy="0" r="1" gradientTransform="matrix(-.33793 2.79084 -2.2828 -.27641 10.118 21.848)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="ws-ofvbpp"/><stop offset="1" class="i2p625zaz"/></radialGradient><radialGradient id="iDJYDNb" cx="0" cy="0" r="1" gradientTransform="matrix(.20372 -3.21174 1.70613 .10822 6.079 24.713)" gradientUnits="userSpaceOnUse"><stop class="x9syn5bsf"/><stop offset="1" class="ippisxk_c"/></radialGradient><radialGradient id="i0KgHMc" cx="0" cy="0" r="1" gradientTransform="matrix(-.02888 -2.796 1.23588 -.01277 7.45 24.693)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="got22lb_s"/><stop offset="1" class="m5racngae"/></radialGradient><radialGradient id="ia6aRHy" cx="0" cy="0" r="1" gradientTransform="matrix(.4982 -1.16022 3.58632 1.53998 5.806 25.158)" gradientUnits="userSpaceOnUse"><stop offset=".098" class="yps5thqls"/><stop offset="1" class="aje_gtbfo"/></radialGradient><radialGradient id="ijHifUb" cx="0" cy="0" r="1" gradientTransform="matrix(1.52841 -2.3289 3.00123 1.96966 3.07 25.426)" gradientUnits="userSpaceOnUse"><stop class="lv9f4sbft"/><stop offset="1" class="gjthckb9a"/></radialGradient><radialGradient id="iaFeg1c" cx="0" cy="0" r="1" gradientTransform="matrix(-.14765 -2.39628 1.0581 -.0652 4.414 26.13)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="p7xh8mbkr"/><stop offset="1" class="so0nfjs_n"/></radialGradient><radialGradient id="iAo0ZMc" cx="0" cy="0" r="1" gradientTransform="rotate(-48.526 30.597 10.143)scale(1.97399 4.7131)" gradientUnits="userSpaceOnUse"><stop class="o5pi4qbos"/><stop offset="1" class="mrh8oxbyb"/></radialGradient><radialGradient id="i19Xqom" cx="0" cy="0" r="1" gradientTransform="matrix(1.4011 -3.5602 2.78505 1.09605 3.124 26.597)" gradientUnits="userSpaceOnUse"><stop offset=".786" class="slfwwoboa"/><stop offset="1" class="htek_b-aw"/></radialGradient><radialGradient id="itCuVNw" cx="0" cy="0" r="1" gradientTransform="rotate(-103.353 12.254 12.845)scale(2.55343 1.41015)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="x4_rgjbgr"/><stop offset="1" class="kyxlbjczl"/></radialGradient><radialGradient id="iVT1fBd" cx="0" cy="0" r="1" gradientTransform="matrix(.64228 -.85953 1.5214 1.13686 1.621 27.79)" gradientUnits="userSpaceOnUse"><stop class="o1u4v1x-w"/><stop offset="1" class="rrdpflbyy"/></radialGradient><radialGradient id="iE2aLDR" cx="0" cy="0" r="1" gradientTransform="matrix(.53113 1.91968 -1.32546 .36672 3.297 25.914)" gradientUnits="userSpaceOnUse"><stop offset=".11" class="libnoft0w"/><stop offset="1" class="oi5b6vt4l"/></radialGradient><radialGradient id="ieLdowE" cx="0" cy="0" r="1" gradientTransform="rotate(106.149 4.423 20.743)scale(6.42022 13.0626)" gradientUnits="userSpaceOnUse"><stop offset=".301" class="bxi9tgmwe"/><stop offset="1" class="tn-w78xgx"/></radialGradient><radialGradient id="iYeavFd" cx="0" cy="0" r="1" gradientTransform="matrix(1.93323 -.03101 .0261 1.62651 17.756 27.23)" gradientUnits="userSpaceOnUse"><stop offset=".165" class="gbny4_b4j"/><stop offset="1" class="glfls735f"/></radialGradient><radialGradient id="iEskV0x" cx="0" cy="0" r="1" gradientTransform="matrix(2.59376 3.78341 -2.47147 1.69434 20.158 25.028)" gradientUnits="userSpaceOnUse"><stop offset=".284" class="oxi0f3b2m"/><stop offset="1" class="vl_ql576y"/></radialGradient><radialGradient id="iyW7LBe" cx="0" cy="0" r="1" gradientTransform="rotate(113.738 6.012 22.143)scale(2.83347 1.67501)" gradientUnits="userSpaceOnUse"><stop offset=".546" class="qzo_nkzbd"/><stop offset="1" class="ht552mbaq"/></radialGradient><radialGradient id="iCXSQNb" cx="0" cy="0" r="1" gradientTransform="rotate(116.054 5.447 20.351)scale(3.13062 2.06753)" gradientUnits="userSpaceOnUse"><stop offset=".26" class="jjhcfiagl"/><stop offset="1" class="d2h5kyjkp"/></radialGradient><radialGradient id="iZJRsbb" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.09375 -3.72984 0 23.545 23.459)" gradientUnits="userSpaceOnUse"><stop class="i-ilo59wi"/><stop offset="1" class="gew0dbs3i"/></radialGradient><radialGradient id="i5cKy7J" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.43452 -1.62962 0 .207 .257)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="s9595bb6g"/><stop offset="1" class="la3tbwntj"/></radialGradient><radialGradient id="iFbacFb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.90968 -2.1392 0 .98 .862)" gradientUnits="userSpaceOnUse"><stop offset=".577" class="o39pnqg0i"/><stop offset="1" class="n3i60zbwo"/></radialGradient><radialGradient id="iAe9aMb" cx="0" cy="0" r="1" gradientTransform="matrix(.07378 3.33306 -1.58148 .035 .381 .326)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="s9595bb6g"/><stop offset="1" class="la3tbwntj"/></radialGradient><radialGradient id="i56EY8b" cx="0" cy="0" r="1" gradientTransform="rotate(97.643 .058 .878)scale(2.7887 2.05026)" gradientUnits="userSpaceOnUse"><stop offset=".577" class="o39pnqg0i"/><stop offset="1" class="n3i60zbwo"/></radialGradient><radialGradient id="iXxxUfc" cx="0" cy="0" r="1" gradientTransform="matrix(.07447 3.3649 -1.59659 .03534 .385 .33)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="s9595bb6g"/><stop offset="1" class="la3tbwntj"/></radialGradient><radialGradient id="iw4dd4c" cx="0" cy="0" r="1" gradientTransform="matrix(-.74734 2.73501 -2.01078 -.54945 1.318 1.001)" gradientUnits="userSpaceOnUse"><stop offset=".577" class="o39pnqg0i"/><stop offset="1" class="n3i60zbwo"/></radialGradient><radialGradient id="ixP16ad" cx="0" cy="0" r="1" gradientTransform="rotate(86.011 .058 .65)scale(2.14376 1.52149)" gradientUnits="userSpaceOnUse"><stop class="xq9watbjp"/><stop offset="1" class="ve2ow0b5f"/></radialGradient><radialGradient id="iWnLhMc" cx="0" cy="0" r="1" gradientTransform="matrix(1.82612 .3373 -.5514 2.98514 .616 .826)" gradientUnits="userSpaceOnUse"><stop offset=".455" class="sl7iwijia"/><stop offset="1" class="sce_y6bah"/></radialGradient><radialGradient id="itioSUc" cx="0" cy="0" r="1" gradientTransform="matrix(-.71567 1.75021 -2.23482 -.91383 1.038 .949)" gradientUnits="userSpaceOnUse"><stop offset=".488" class="es563lbhm"/><stop offset=".926" class="rdi-wfxqd"/></radialGradient><radialGradient id="iir39nb" cx="0" cy="0" r="1" gradientTransform="rotate(-101.325 14.885 .97)scale(4.36627 2.77906)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="e-l33-bot"/><stop offset="1" class="nxovy29zu"/></radialGradient><radialGradient id="iNmg2Be" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.04687 3.76333 0 16.037 16.756)" gradientUnits="userSpaceOnUse"><stop class="y7xy7bb_m"/><stop offset="1" class="xjomt31wk"/></radialGradient><radialGradient id="iQlJeqP" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.9375 -3.86566 0 16 13.959)" gradientUnits="userSpaceOnUse"><stop offset=".846" class="p0u5ydomu"/><stop offset="1" class="woms0-bkw"/></radialGradient><radialGradient id="iQeJMle" cx="0" cy="0" r="1" gradientTransform="matrix(-1.10937 -.42188 1.18506 -3.11625 9.56 8.693)" gradientUnits="userSpaceOnUse"><stop offset=".294" class="zwg4tzbwy"/><stop offset="1" class="y79om8bwc"/></radialGradient><radialGradient id="irnNXnb" cx="0" cy="0" r="1" gradientTransform="matrix(-.29686 2.45312 -4.49518 -.54398 13.795 3.756)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="h3rp3-aib"/><stop offset="1" class="hqev7xbqy"/></radialGradient><radialGradient id="iSOb4Kv" cx="0" cy="0" r="1" gradientTransform="matrix(.41325 -1.2697 2.16104 .70335 16.038 7.354)" gradientUnits="userSpaceOnUse"><stop class="asvtx52la"/><stop offset="1" class="vgsepv73n"/></radialGradient><radialGradient id="iMq3r9d" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 -1.03125 1.9726 1.25529 21.74 7.053)" gradientUnits="userSpaceOnUse"><stop offset=".358" class="aat7v477c"/><stop offset="1" class="sfw3_3huc"/></radialGradient><radialGradient id="iEPfRtd" cx="0" cy="0" r="1" gradientTransform="rotate(-149.349 13.272 .255)scale(2.45193 .58249)" gradientUnits="userSpaceOnUse"><stop class="jn-6ayblt"/><stop offset="1" class="cekjokbuk"/></radialGradient><radialGradient id="i0BEySd" cx="0" cy="0" r="1" gradientTransform="matrix(1.55317 -3.03778 5.17038 2.64354 22.945 12.222)" gradientUnits="userSpaceOnUse"><stop class="b22odi5xr"/><stop offset="1" class="hvrh11btd"/></radialGradient><radialGradient id="iM8ndue" cx="0" cy="0" r="1" gradientTransform="matrix(-4.99855 0 0 -1.1087 15.917 5.625)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="m31dnp5ni"/><stop offset="1" class="x3ufrsr-b"/></radialGradient><radialGradient id="i9AL7Ze" cx="0" cy="0" r="1" gradientTransform="matrix(-4.38752 3.15624 -4.09613 -5.69407 20.717 5.178)" gradientUnits="userSpaceOnUse"><stop offset=".354" class="t2gurh6mq"/><stop offset=".945" class="na-mpf48i"/></radialGradient><radialGradient id="iquG9eb" cx="0" cy="0" r="1" gradientTransform="matrix(5.26562 -1.59375 2.88674 9.53758 17.623 8.771)" gradientUnits="userSpaceOnUse"><stop offset=".827" class="qd5pj149f"/><stop offset="1" class="yrcmunbnd"/></radialGradient><linearGradient id="id9k7Fe" x1="8.779" x2="10.186" y1="12.521" y2="16.248" gradientUnits="userSpaceOnUse"><stop class="q0bx3-bma"/><stop offset="1" class="q2o6fx2nz"/></linearGradient><linearGradient id="imqKCKd" x1="23.436" x2="21.89" y1="12.185" y2="16.615" gradientUnits="userSpaceOnUse"><stop class="lyezpqbcw"/><stop offset="1" class="ppkg-ib8q"/></linearGradient><linearGradient id="iGVRemI" x1="16.026" x2="16.026" y1="8.115" y2="21.979" gradientUnits="userSpaceOnUse"><stop class="q7mg2kdhm"/><stop offset="1" class="icg-h_npp"/></linearGradient><linearGradient id="iFAsjNc" x1="22.217" x2="16.026" y1="15.709" y2="15.709" gradientUnits="userSpaceOnUse"><stop class="cc4o3sbld"/><stop offset="1" class="g0fgwro5e"/></linearGradient><linearGradient id="iGEf3qe" x1="9.873" x2="16.279" y1="14.74" y2="14.615" gradientUnits="userSpaceOnUse"><stop class="a79bej2eg"/><stop offset="1" class="gmo5ddc6p"/></linearGradient><linearGradient id="i2F7Pgd" x1="16.185" x2="16.154" y1="21.979" y2="17.756" gradientUnits="userSpaceOnUse"><stop offset=".042" class="fq3iz8zwy"/><stop offset="1" class="hxj_y6kqd"/></linearGradient><linearGradient id="iyg3sde" x1="1.549" x2="1.549" y1="1.191" y2="1.801" gradientUnits="userSpaceOnUse"><stop class="f4-a9nvel"/><stop offset="1" class="gyuwqf8co"/></linearGradient><linearGradient id="iZ8l23b" x1="14.201" x2="14.74" y1="19.99" y2="18.24" gradientUnits="userSpaceOnUse"><stop class="k1gfo1wgd"/><stop offset="1" class="yq3urh0vb"/></linearGradient><linearGradient id="ipuiUMc" x1="10.58" x2="11.083" y1="15.659" y2="19.743" gradientUnits="userSpaceOnUse"><stop offset=".765" class="y45ewibqy"/><stop offset=".98" class="whhmayblq"/></linearGradient><linearGradient id="ihCiVVb" x1="21.529" x2="20.342" y1="16.053" y2="19.49" gradientUnits="userSpaceOnUse"><stop offset=".681" class="iup3-2b7t"/><stop offset="1" class="z6kuubbbf"/></linearGradient><linearGradient id="iw8gOob" x1="12.377" x2="14.416" y1="10.795" y2="10.16" gradientUnits="userSpaceOnUse"><stop class="mfys3hj4f"/><stop offset="1" class="qudy1_y1m"/></linearGradient><linearGradient id="iTEuk8b" x1="20.572" x2="18.251" y1="11.168" y2="10.16" gradientUnits="userSpaceOnUse"><stop class="mfys3hj4f"/><stop offset="1" class="qudy1_y1m"/></linearGradient><linearGradient id="iCs1UAe" x1="8.72" x2="9.342" y1="22.99" y2="22.975" gradientUnits="userSpaceOnUse"><stop class="zbdko4y_s"/><stop offset="1" class="d5osmbc_d"/></linearGradient><linearGradient id="iA8ciyf" x1="5.347" x2="6.407" y1="23.697" y2="23.67" gradientUnits="userSpaceOnUse"><stop class="j614okoao"/><stop offset="1" class="l2cbxb5tg"/></linearGradient><linearGradient id="iQHbFcd" x1="15.854" x2="15.854" y1="13.584" y2="16.959" gradientUnits="userSpaceOnUse"><stop class="odwb5qh_v"/><stop offset="1" class="mneke1b_s"/></linearGradient><linearGradient id="i8DrZZb" x1="16" x2="16" y1="13.381" y2="14.725" gradientUnits="userSpaceOnUse"><stop class="p3hupxtfd"/><stop offset="1" class="bp9n2ccrq"/></linearGradient><linearGradient id="iv97ITc" x1="14.887" x2="15.373" y1="15.615" y2="15.709" gradientUnits="userSpaceOnUse"><stop class="m7a_bec-v"/><stop offset="1" class="th_2jcizb"/></linearGradient><linearGradient id="iPtKRBc" x1="7.248" x2="25.654" y1="9.865" y2="4.834" gradientUnits="userSpaceOnUse"><stop class="iltm3_bbo"/><stop offset="1" class="bkq1djpng"/></linearGradient><linearGradient id="ix1iSSc" x1="20.748" x2="17.435" y1="2.787" y2="5.006" gradientUnits="userSpaceOnUse"><stop offset=".438" class="ob8_xfbky"/><stop offset="1" class="ed7v7wbpg"/></linearGradient><linearGradient id="if9ltvc" x1="20.951" x2="18.577" y1="6.99" y2="7.056" gradientUnits="userSpaceOnUse"><stop class="ob8_xfbky"/><stop offset="1" class="ed7v7wbpg"/></linearGradient><filter id="iWbJjfc" width="3.209" height="3.209" x="8.582" y="12.612" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2087" stdDeviation=".15"/></filter><filter id="iKUkowc" width="3.209" height="3.209" x="20.285" y="12.612" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2087" stdDeviation=".15"/></filter><filter id="iQzUtKd" width="12.691" height="15.01" x="9.689" y="7.068" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.427451 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2087"/></filter><filter id="iz9Om1b" width="3.885" height="3.935" x="11.447" y="11.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.176471 0 0 0 0 0.0784314 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2087"/></filter><filter id="iFhh0Jb" width="3.785" height="3.885" x="16.83" y="11.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.168627 0 0 0 0 0.0784314 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2087"/></filter><filter id="iRWfWbc" width="3.799" height="1.588" x="16.873" y="11.815" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.517647 0 0 0 0 0.494118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2087"/></filter><filter id="ikGZYNb" width="4.408" height="2.736" x="12.76" y="17.353" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2087" stdDeviation=".05"/></filter><filter id="iwAu7Yc" width="11.828" height="8.938" x="2.666" y="20.99" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.486275 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2087"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.403922 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_2087" result="effect2_innerShadow_2_2087"/></filter><filter id="i8ZbO4b" width="11.828" height="8.875" x="17.756" y="21.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.486275 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2087"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.403922 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_2087" result="effect2_innerShadow_2_2087"/></filter><filter id="io5ntOd" width="3.027" height="4.175" x="14.341" y="13.184" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2087" stdDeviation=".2"/></filter><filter id="ixPgxYd" width="7.744" height="7.243" x="8.801" y="4.184" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.105882 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2087"/><feGaussianBlur result="effect2_foregroundBlur_2_2087" stdDeviation=".05"/></filter><filter id="ihi6Kob" width="4.094" height="3.377" x="17.342" y="2.207" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2087" stdDeviation=".25"/></filter><filter id="iEySyye" width="5.108" height="2.891" x="17.312" y="4.693" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2087" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-zombie" /></template>
<style>
.a79bej2eg {
  stop-color: var(--svg-color--608282, #608282);
}

.a7iu9vb1v {
  stop-color: var(--svg-color--4e9191, #4E9191);
}

.aat7v477c {
  stop-color: var(--svg-color--423051, #423051);
}

.adr6gcutb {
  stop-color: var(--svg-color--261735, #261735);
}

.aje_gtbfo {
  stop-color: var(--svg-color--608c96, #608C96);
  stop-opacity: 0;
}

.asvtx52la {
  stop-color: var(--svg-color--281536, #281536);
}

.b22odi5xr {
  stop-color: var(--svg-color--261a35, #261A35);
}

.bkq1djpng {
  stop-color: var(--svg-color--3d284e, #3D284E);
}

.bng_m2b0t {
  stop-color: var(--svg-color--ffaf5a, #FFAF5A);
}

.bp9n2ccrq {
  stop-color: var(--svg-color--709ca5, #709CA5);
  stop-opacity: 0;
}

.bw57fdcce {
  stop-color: var(--svg-color--493061, #493061);
}

.bxi9tgmwe {
  stop-color: var(--svg-color--2f5657, #2F5657);
}

.cc4o3sbld {
  stop-color: var(--svg-color--71b6af, #71B6AF);
}

.cekjokbuk {
  stop-color: var(--svg-color--41304f, #41304F);
  stop-opacity: 0;
}

.d2h5kyjkp {
  stop-color: var(--svg-color--547986, #547986);
  stop-opacity: 0;
}

.d5osmbc_d {
  stop-color: var(--svg-color--679684, #679684);
  stop-opacity: 0;
}

.ddgegzc8o {
  cx: 13.559px;
  cy: 13.473px;
  r: 1.549px;
}

.dfkyv0s4o {
  stop-color: var(--svg-color--3d567a, #3D567A);
}

.dgo3vt0eo {
  stop-color: var(--svg-color--2c2337, #2C2337);
}

.ds8e6968j {
  cx: 21.89px;
  cy: 14.217px;
  r: 2.031px;
}

.e-l33-bot {
  stop-color: var(--svg-color--81beb9, #81BEB9);
}

.ebc1zfyja {
  stop-color: var(--svg-color--7498a0, #7498A0);
}

.ed7v7wbpg {
  stop-color: var(--svg-color--473158, #473158);
  stop-opacity: 0;
}

.el7r9pbsw {
  r: 1.893px;
}

.enitdihfo {
  stop-color: var(--svg-color--3a2549, #3A2549);
}

.es563lbhm {
  stop-color: var(--svg-color--4f7b7f, #4F7B7F);
  stop-opacity: 0;
}

.eyrjcjfhu {
  fill: var(--svg-color--fba65c, #FBA65C);
  d: path("M16.436 18.404h-2.098a.3.3 0 0 1-.3-.3v-.548l.09-.003h.504c.726 0 1.375.331 1.804.851");
}

.f4-a9nvel {
  stop-color: var(--svg-color--ffb770, #FFB770);
}

.f7t6iccjp {
  stop-color: var(--svg-color--17101e, #17101E);
}

.faf527bpe {
  stop-color: var(--svg-color--63a3a2, #63A3A2);
}

.fk_sd4b3f {
  width: 1.961px;
  height: 3.691px;
  fill: var(--svg-color--5e9886, #5E9886);
  rx: 0.98px;
}

.fq3iz8zwy {
  stop-color: var(--svg-color--585ea6, #585EA6);
}

.fsa4w_a7l {
  cx: 13.578px;
  cy: 13.473px;
  r: 0.623px;
  fill: var(--svg-color--a01b3c, #A01B3C);
}

.ft5dv1b6b {
  fill: none;
}

.g0fgwro5e {
  stop-color: var(--svg-color--78abb4, #78ABB4);
  stop-opacity: 0;
}

.g3i-1pbcq {
  stop-color: var(--svg-color--e98f43, #E98F43);
}

.gas_t6b8j {
  d: path("M19.786 4.522c-.155.193-.296.58-.147.859c.17.32.485.438 1.008.634q.1.036.21.079l.004.001c.65.248 1.577.601 2.082 2.137c.45 1.37-.056 2.511-.574 3.095l.012-.2c.028-.617-.277-1.887-1.727-1.887h-1.625c-.591-.005-1.92-.226-2.508-1.207l-.192-.323l.013-.025V5.092a4 4 0 0 1 .171-1.156a.2.2 0 0 0 .042-.075a2.55 2.55 0 0 1 1.752-1.636c.919-.246 1.834-.145 2.48-.04c.213.035.467.207.524.45c.056.242-.073.46-.27.613c-.349.27-.887.73-1.233 1.2a.1.1 0 0 0-.022.074");
}

.gbny4_b4j {
  stop-color: var(--svg-color--74ada5, #74ADA5);
}

.gew0dbs3i {
  stop-color: var(--svg-color--527483, #527483);
  stop-opacity: 0;
}

.gjthckb9a {
  stop-color: var(--svg-color--6ca895, #6CA895);
}

.gl17utj4l {
  width: 1.995px;
  height: 3.756px;
  rx: 0.998px;
}

.glfls735f {
  stop-color: var(--svg-color--74ada5, #74ADA5);
  stop-opacity: 0;
}

.gls-i-zvq {
  stop-color: var(--svg-color--5f7d9a, #5F7D9A);
  stop-opacity: 0;
}

.gmo5ddc6p {
  stop-color: var(--svg-color--608282, #608282);
  stop-opacity: 0;
}

.got22lb_s {
  stop-color: var(--svg-color--7cbcb2, #7CBCB2);
}

.gsa1cebro {
  d: path("m3.423 27.53l-.757-.68l.703-1.954l.855.648a.1.1 0 0 0 .108.01l.154-.083l-.469-1.778l1.02-1.03l1.164 1.625a.1.1 0 0 0 .134.028l.167-.103l-.22-1.824l1.376-.649l.622 1.428a.225.225 0 0 0 .265.128a.25.25 0 0 0 .18-.23v-.737l1.956.013l.018 3.955c.001.196.092.38.246.5c.168.13.387.166.594.121c.759-.166 1.623-.12 2.049-.014c.421.137.656.451.656.855a.896.896 0 0 1-.896.895h-.62c-.71 0-.945.11-1.648.696c-.563.468-1.443.58-1.813.578H6.173c-1.015 0-1.312-.407-1.64-.774c-.263-.294-.85-1.206-1.11-1.625");
}

.gyuwqf8co {
  stop-color: var(--svg-color--ffb770, #FFB770);
  stop-opacity: 0;
}

.h3rp3-aib {
  stop-color: var(--svg-color--402e4d, #402E4D);
}

.h50m5ib7f {
  stop-color: var(--svg-color--ffdf80, #FFDF80);
}

.hbx3qwnwa {
  stop-color: var(--svg-color--e98f43, #E98F43);
  stop-opacity: 0;
}

.hitknonwe {
  stop-color: var(--svg-color--5b9695, #5B9695);
  stop-opacity: 0;
}

.hkndu6boi {
  stop-color: var(--svg-color--3d274c, #3D274C);
}

.hqev7xbqy {
  stop-color: var(--svg-color--402e4d, #402E4D);
  stop-opacity: 0;
}

.ht552mbaq {
  stop-color: var(--svg-color--476676, #476676);
  stop-opacity: 0;
}

.htek_b-aw {
  stop-color: var(--svg-color--72a292, #72A292);
}

.hvrh11btd {
  stop-color: var(--svg-color--261a35, #261A35);
  stop-opacity: 0;
}

.hxj_y6kqd {
  stop-color: var(--svg-color--5b769a, #5B769A);
  stop-opacity: 0;
}

.i-ilo59wi {
  stop-color: var(--svg-color--2f545a, #2F545A);
}

.i2p625zaz {
  stop-color: var(--svg-color--486686, #486686);
}

.i40h4bbfl {
  stop-color: var(--svg-color--4c7684, #4C7684);
}

.i6tafw00v {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.96 18.72c0-.644.523-1.167 1.168-1.167h.504a2.336 2.336 0 0 1 2.336 2.336h-2.84a1.17 1.17 0 0 1-1.168-1.168Z");
}

.i7m2j00fs {
  width: 1.976px;
  height: 3.721px;
  rx: 0.988px;
}

.icg-h_npp {
  stop-color: var(--svg-color--648896, #648896);
}

.ij5lprb2c {
  width: 1.988px;
  height: 2.636px;
  rx: 0.994px;
}

.iltm3_bbo {
  stop-color: var(--svg-color--2d1834, #2D1834);
}

.ippisxk_c {
  stop-color: var(--svg-color--679f8d, #679F8D);
}

.iup3-2b7t {
  stop-color: var(--svg-color--5a8092, #5A8092);
}

.iv7v1nb3o {
  stop-color: var(--svg-color--4f8387, #4F8387);
  stop-opacity: 0;
}

.iw38491ye {
  stop-color: var(--svg-color--74ad9d, #74AD9D);
}

.j614okoao {
  stop-color: var(--svg-color--407568, #407568);
}

.j6x4q_h4k {
  cx: 10.186px;
  cy: 14.217px;
  r: 2.031px;
}

.jjhcfiagl {
  stop-color: var(--svg-color--355d5e, #355D5E);
}

.jn-6ayblt {
  stop-color: var(--svg-color--41304f, #41304F);
}

.ju7pygbji {
  stop-color: var(--svg-color--0d0512, #0D0512);
}

.k1gfo1wgd {
  stop-color: var(--svg-color--678292, #678292);
}

.k589lpbub {
  stop-color: var(--svg-color--79a7af, #79A7AF);
}

.k5i922b3o {
  d: path("M19.857 6.271c.813.25 1.714.646 2.063.813c-1.578-.484-2.39.234-3.406-.219c-.813-.362-.756-1.265-.625-1.672h1.14c-.062.256.016.828.828 1.078");
}

.kencgo7xy {
  d: path("M22.137 15.659a2.2 2.2 0 0 0-.856.243c-.357.19-.67.5-.922.96c-.254.464-.39 1.044-.461 1.568a7.7 7.7 0 0 0-.067 1.313l.45-.021a7.3 7.3 0 0 1 .063-1.231c.068-.502.194-1.02.41-1.412c.216-.395.47-.636.74-.78c.19-.102.397-.16.617-.185z");
}

.kyxlbjczl {
  stop-color: var(--svg-color--609180, #609180);
}

.l1x0gab1i {
  cx: 21.89px;
  cy: 14.217px;
  r: 1.305px;
}

.l257jccgu {
  width: 1.976px;
  height: 3.721px;
  fill: var(--svg-color--5e9886, #5E9886);
  rx: 0.988px;
}

.l2cbxb5tg {
  stop-color: var(--svg-color--6c9e8f, #6C9E8F);
  stop-opacity: 0;
}

.la3tbwntj {
  stop-color: var(--svg-color--7cc2b2, #7CC2B2);
  stop-opacity: 0;
}

.libnoft0w {
  stop-color: var(--svg-color--456a60, #456A60);
}

.lpgc_kbrw {
  d: path("M16 13.38a.51.51 0 0 0-.49.374l-.6 2.18a.65.65 0 0 0 .627.822h.926a.65.65 0 0 0 .627-.823l-.6-2.18a.51.51 0 0 0-.49-.372");
}

.lt6k7o0fo {
  stop-color: var(--svg-color--62a09f, #62A09F);
}

.ltf0tqb9y {
  stop-color: var(--svg-color--684d78, #684D78);
}

.lv9f4sbft {
  stop-color: var(--svg-color--70a196, #70A196);
}

.lvqejss-o {
  width: 1.961px;
  height: 3.691px;
  rx: 0.98px;
}

.lxs7f3b1j {
  stop-color: var(--svg-color--7abfb2, #7ABFB2);
}

.lyezpqbcw {
  stop-color: var(--svg-color--5ba093, #5BA093);
}

.m31dnp5ni {
  stop-color: var(--svg-color--422850, #422850);
}

.m3qe5cb4h {
  stop-color: var(--svg-color--5b9596, #5B9596);
}

.m5racngae {
  stop-color: var(--svg-color--76b9a7, #76B9A7);
  stop-opacity: 0;
}

.m7a_bec-v {
  stop-color: var(--svg-color--547b7a, #547B7A);
}

.m8bj1mb9s {
  r: 0.623px;
  fill: var(--svg-color--9e1539, #9E1539);
}

.mfys3hj4f {
  stop-color: var(--svg-color--241232, #241232);
}

.mjxxa0b8h {
  d: path("M18.78 5.084c.362-1.588 1.588-2.245 2.155-2.375c-1.762-.063-2.796 1.161-3.093 1.781z");
}

.mneke1b_s {
  stop-color: var(--svg-color--57779e, #57779E);
}

.mrh8oxbyb {
  stop-color: var(--svg-color--5e8a91, #5E8A91);
  stop-opacity: 0;
}

.n3i60zbwo {
  stop-color: var(--svg-color--4c6489, #4C6489);
}

.n5f0f7b6s {
  d: path("M12.96 18.72c0-.644.523-1.167 1.168-1.167h.504a2.336 2.336 0 0 1 2.336 2.336h-2.84a1.17 1.17 0 0 1-1.168-1.168");
}

.na-mpf48i {
  stop-color: var(--svg-color--271434, #271434);
}

.nrll1s57d {
  width: 1.961px;
  height: 3.691px;
  x: 8.72px;
  y: 20.947px;
  rx: 0.98px;
}

.nrrnwgb2j {
  stop-color: var(--svg-color--291632, #291632);
}

.nxovy29zu {
  stop-color: var(--svg-color--608884, #608884);
  stop-opacity: 0;
}

.o1u4v1x-w {
  stop-color: var(--svg-color--576a91, #576A91);
}

.o39pnqg0i {
  stop-color: var(--svg-color--5c818e, #5C818E);
  stop-opacity: 0;
}

.o5pi4qbos {
  stop-color: var(--svg-color--4d678a, #4D678A);
}

.ob8_xfbky {
  stop-color: var(--svg-color--473058, #473058);
}

.odwb5qh_v {
  stop-color: var(--svg-color--5c8a89, #5C8A89);
}

.ogpl8rbbb {
  stop-color: var(--svg-color--ffcf77, #FFCF77);
}

.oi5b6vt4l {
  stop-color: var(--svg-color--669688, #669688);
  stop-opacity: 0;
}

.op6z3p63j {
  d: path("M16.436 18.404h-2.098a.3.3 0 0 1-.3-.3v-.548l.09-.003h.504c.726 0 1.375.331 1.804.851");
}

.oukb_nb4n {
  stop-color: var(--svg-color--586d77, #586D77);
  stop-opacity: 0;
}

.oxi0f3b2m {
  stop-color: var(--svg-color--72b4aa, #72B4AA);
}

.p_p2m_b9w {
  fill: var(--svg-color--5f8783, #5F8783);
  d: path("M16 13.38a.51.51 0 0 0-.49.374l-.6 2.18a.65.65 0 0 0 .627.822h.926a.65.65 0 0 0 .627-.823l-.6-2.18a.51.51 0 0 0-.49-.372");
}

.p-lt9kb3w {
  stop-color: var(--svg-color--546672, #546672);
}

.p0u5ydomu {
  stop-color: var(--svg-color--60829e, #60829E);
  stop-opacity: 0;
}

.p3hupxtfd {
  stop-color: var(--svg-color--709ca5, #709CA5);
}

.p7xh8mbkr {
  stop-color: var(--svg-color--7eb7ae, #7EB7AE);
}

.pia5784be {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-65px, 0.65px);
  d: path("M12.095 10.795c.29-.209 1.086-.64 2.079-.445");
}

.ppkg-ib8q {
  stop-color: var(--svg-color--567d99, #567D99);
}

.pt4idkkwh {
  cx: 10.186px;
  cy: 14.217px;
  r: 1.305px;
}

.pu8qn_k-c {
  cx: 13.34px;
  cy: 13.707px;
  r: 1.893px;
}

.q0bx3-bma {
  stop-color: var(--svg-color--3c5a52, #3C5A52);
}

.q2o6fx2nz {
  stop-color: var(--svg-color--50608c, #50608C);
}

.q53_zdbrw {
  stop-color: var(--svg-color--54958b, #54958B);
}

.q7mg2kdhm {
  stop-color: var(--svg-color--78a8b1, #78A8B1);
}

.qd5pj149f {
  stop-color: var(--svg-color--321d44, #321D44);
  stop-opacity: 0;
}

.qs15vj7hh {
  width: 1.988px;
  height: 2.636px;
  x: 1.35px;
  y: 25.347px;
  rx: 0.994px;
}

.qudy1_y1m {
  stop-color: var(--svg-color--311a3d, #311A3D);
}

.qzo_nkzbd {
  stop-color: var(--svg-color--476676, #476676);
}

.r0mv4inkj {
  d: path("M20.572 13.303h-3.699a1.893 1.893 0 0 1 3.699 0");
}

.rdi-wfxqd {
  stop-color: var(--svg-color--586590, #586590);
}

.rrdpflbyy {
  stop-color: var(--svg-color--588290, #588290);
  stop-opacity: 0;
}

.rvq6gmb5w {
  stop-color: var(--svg-color--070608, #070608);
}

.s9595bb6g {
  stop-color: var(--svg-color--7cc2b2, #7CC2B2);
}

.sce_y6bah {
  stop-color: var(--svg-color--396f65, #396F65);
}

.sfqdrecvz {
  d: path("M9.953 16.114c.22.025.427.083.618.185c.27.144.523.385.74.78c.215.393.341.91.41 1.412c.067.498.075.961.062 1.23l.45.022a7.7 7.7 0 0 0-.067-1.313c-.07-.524-.207-1.104-.46-1.567s-.566-.77-.923-.96a2.2 2.2 0 0 0-.856-.244z");
}

.sfw3_3huc {
  stop-color: var(--svg-color--423051, #423051);
  stop-opacity: 0;
}

.sl7iwijia {
  stop-color: var(--svg-color--396f65, #396F65);
  stop-opacity: 0;
}

.slfwwoboa {
  stop-color: var(--svg-color--6ba18f, #6BA18F);
  stop-opacity: 0;
}

.so0nfjs_n {
  stop-color: var(--svg-color--7eb7ae, #7EB7AE);
  stop-opacity: 0;
}

.ss1ebabhy {
  fill-rule: evenodd;
  d: path("m22.38 11.15l-.063 1.08l.003.001l-.273 4.779c-.02.87-.313 2.604-1.593 3.738c-1.186 1.05-2.456 1.214-4.262 1.23h-.332c-1.806-.016-3.076-.18-4.262-1.23c-1.28-1.134-1.573-2.868-1.593-3.738l-.272-4.774h.003l-.043-.726c-.029-.365.07-1.474.899-2.703a3.92 3.92 0 0 1 3.171-1.739h1.63c.35 0 .668.184.844.485l.284.48c.588.981 1.917 1.202 2.508 1.207h1.625c1.283 0 1.67.995 1.722 1.651q.005.129.003.258");
}

.t2gurh6mq {
  stop-color: var(--svg-color--422e53, #422E53);
}

.t5xob_buh {
  d: path("M7.5 29.928L5.423 26.33a11.99 11.99 0 0 1 10.186-5.653h1.376c3.966 0 7.483 1.924 9.668 4.89l-2.518 4.36z");
}

.tdekfnbnd {
  d: path("M9.28 17.854c-.238-.625-.294-1.735-.266-2.332l1.789.054v3.79c-.633-.352-1.227-.731-1.524-1.512");
}

.th_2jcizb {
  stop-color: var(--svg-color--6c9b96, #6C9B96);
  stop-opacity: 0;
}

.tn-w78xgx {
  stop-color: var(--svg-color--619299, #619299);
  stop-opacity: 0;
}

.u84zz4ukw {
  stop-color: var(--svg-color--7abfb2, #7ABFB2);
  stop-opacity: 0;
}

.u8epgmbkl {
  stop-color: var(--svg-color--75b4b1, #75B4B1);
  stop-opacity: 0;
}

.ub34p6b1y {
  width: 4.969px;
  height: 6.172px;
  x: 13.515px;
  y: 18.131px;
  rx: 2.484px;
}

.udi_mfp4v {
  stop-color: var(--svg-color--351c47, #351C47);
}

.ult0y8bvs {
  stop-color: var(--svg-color--586d77, #586D77);
}

.ups_dab2u {
  width: 1.976px;
  height: 3.721px;
  x: 5.516px;
  y: 21.499px;
  rx: 0.988px;
}

.uvhjscb1o {
  width: 1.995px;
  height: 3.756px;
  fill: var(--svg-color--5e9886, #5E9886);
  rx: 0.998px;
}

.uycl7hbwr {
  fill: var(--svg-color--6a9da1, #6A9DA1);
  d: path("m3.423 27.53l-.757-.68l.703-1.954l.855.648a.1.1 0 0 0 .108.01l.154-.083l-.469-1.778l1.02-1.03l1.164 1.625a.1.1 0 0 0 .134.028l.167-.103l-.22-1.824l1.376-.649l.622 1.428a.225.225 0 0 0 .265.128a.25.25 0 0 0 .18-.23v-.737l1.956.013l.018 3.955c.001.196.092.38.246.5c.168.13.387.166.594.121c.759-.166 1.623-.12 2.049-.014c.421.137.656.451.656.855a.896.896 0 0 1-.896.895h-.62c-.71 0-.945.11-1.648.696c-.563.468-1.443.58-1.813.578H6.173c-1.015 0-1.312-.407-1.64-.774c-.263-.294-.85-1.206-1.11-1.625");
}

.v-i1htb2z {
  width: 1.995px;
  height: 3.756px;
  x: 2.878px;
  y: 22.898px;
  rx: 0.998px;
}

.v0ax-glfp {
  stop-color: var(--svg-color--241d2a, #241D2A);
}

.ve2ow0b5f {
  stop-color: var(--svg-color--508f82, #508F82);
}

.vgsepv73n {
  stop-color: var(--svg-color--281536, #281536);
  stop-opacity: 0;
}

.vl_ql576y {
  stop-color: var(--svg-color--659ea4, #659EA4);
  stop-opacity: 0;
}

.vm8mukbur {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-65px, 0.65px);
  d: path("M20.572 10.795c-.29-.209-1.086-.64-2.078-.445");
}

.vmtwlbczt {
  stop-color: var(--svg-color--5f7d9a, #5F7D9A);
}

.vsdiecbqp {
  stop-color: var(--svg-color--4a6171, #4A6171);
}

.w0ry1tv8g {
  stop-color: var(--svg-color--ffb45c, #FFB45C);
}

.whhmayblq {
  stop-color: var(--svg-color--4f6f7e, #4F6F7E);
  stop-opacity: 0;
}

.wjubkud2f {
  fill: var(--svg-color--618c93, #618C93);
  d: path("m28.577 27.53l.757-.68l-.687-1.977l-.87.671a.1.1 0 0 1-.11.01l-.153-.083l.469-1.778l-1.036-1.007l-1.148 1.603a.1.1 0 0 1-.134.027l-.167-.103l.22-1.824l-1.407-.586l-.591 1.365a.226.226 0 0 1-.264.128a.24.24 0 0 1-.176-.225v-.736l-1.961.007l-.018 3.955a.64.64 0 0 1-.246.5a.71.71 0 0 1-.594.121c-.759-.166-1.623-.12-2.048-.014c-.422.137-.657.452-.657.855c0 .494.401.895.896.895h.62c.71 0 .945.11 1.648.696c.563.468 1.443.58 1.813.578h3.093c1.016 0 1.313-.407 1.641-.774c.263-.294.85-1.205 1.11-1.625");
}

.woms0-bkw {
  stop-color: var(--svg-color--4d6999, #4D6999);
}

.ws-ofvbpp {
  stop-color: var(--svg-color--608d97, #608D97);
  stop-opacity: 0;
}

.wu7rmcc4r {
  d: path("M15.854 13.584a.51.51 0 0 0-.49.373l-.6 2.18a.65.65 0 0 0 .627.822h.926a.65.65 0 0 0 .627-.823l-.6-2.18a.51.51 0 0 0-.49-.372");
}

.x3ufrsr-b {
  stop-color: var(--svg-color--422850, #422850);
  stop-opacity: 0;
}

.x4_rgjbgr {
  stop-color: var(--svg-color--709d99, #709D99);
}

.x9syn5bsf {
  stop-color: var(--svg-color--6fa293, #6FA293);
}

.xdz4q9o4b {
  d: path("M8.912 11.823v.812c.237-.191.517-.33.824-.4l-.043-.725c-.028-.365.07-1.474.899-2.703a3.92 3.92 0 0 1 3.172-1.739h1.63c.348 0 .667.184.844.485l.283.48c.588.981 1.917 1.202 2.508 1.207h1.625c1.45 0 1.755 1.27 1.727 1.887l-.064 1.104c.299.064.572.193.806.372v-.62c0-.52.119-.788.236-1.05l.065-.15l.077-.175c.136-.303.32-.71.372-1.333c.05-.6-.136-1.078-.235-1.242h.555c.18 0 .463-.07.593-.195c.288-.28.36-.586-.021-1.008c-.421-.368-.93-.803-1.282-1.082c-.672-.531-1.774-.621-2.47-.621c-.325.025-.552-.089-.625-.149l-.563-.393a.093.093 0 0 1-.017-.138c.346-.469.884-.93 1.233-1.199c.197-.152.326-.37.27-.613c-.057-.243-.31-.415-.524-.45c-.646-.105-1.561-.206-2.48.04a2.55 2.55 0 0 0-1.752 1.636a.2.2 0 0 1-.154.14a3.4 3.4 0 0 1-.989-.023l-.153-.026c-.62-.11-1.401-.247-2.16.093c-.862.387-1.504 1.036-1.962 1.563c-.193.223-.47.352-.763.373c-2.327.169-3.006 1.456-3.25 2.826c-.12.662-.075 1.26-.01 1.77a.6.6 0 0 0 1.005.356l.265-.25a.18.18 0 0 1 .294.078l.14.45q.093.299.094.612");
}

.xh6f20qst {
  d: path("M15.495 6.99a.75.75 0 0 0 .75-.75v-.922a.723.723 0 0 0-.75-.733c-2.353.114-3.682.77-4.547 1.592C9.995 7.083 8.9 8.552 8.9 9.864c0 .85.381 1.286.682 1.463c-.001-.449.148-1.469.902-2.588a3.92 3.92 0 0 1 3.172-1.738z");
}

.xjomt31wk {
  stop-color: var(--svg-color--6c8ea7, #6C8EA7);
  stop-opacity: 0;
}

.xq9watbjp {
  stop-color: var(--svg-color--7dc3b4, #7DC3B4);
}

.y2c1oq0fx {
  r: 1.549px;
}

.y45ewibqy {
  stop-color: var(--svg-color--4f6f7e, #4F6F7E);
}

.y79om8bwc {
  stop-color: var(--svg-color--33273a, #33273A);
  stop-opacity: 0;
}

.y7xy7bb_m {
  stop-color: var(--svg-color--526c9e, #526C9E);
}

.yibkq3zwf {
  fill: var(--svg-color--301347, #301347);
  d: path("M15.495 6.99a.75.75 0 0 0 .75-.75v-.922a.723.723 0 0 0-.75-.733c-2.353.114-3.682.77-4.547 1.592C9.995 7.083 8.9 8.552 8.9 9.864c0 .85.381 1.286.682 1.463c-.001-.449.148-1.469.902-2.588a3.92 3.92 0 0 1 3.172-1.738z");
}

.yps5thqls {
  stop-color: var(--svg-color--466082, #466082);
}

.yq3urh0vb {
  stop-color: var(--svg-color--6182a0, #6182A0);
}

.yrcmunbnd {
  stop-color: var(--svg-color--321d44, #321D44);
}

.ys3eanwrh {
  d: path("m28.577 27.53l.757-.68l-.687-1.977l-.87.671a.1.1 0 0 1-.11.01l-.153-.083l.469-1.778l-1.036-1.007l-1.148 1.603a.1.1 0 0 1-.134.027l-.167-.103l.22-1.824l-1.407-.586l-.591 1.365a.226.226 0 0 1-.264.128a.24.24 0 0 1-.176-.225v-.736l-1.961.007l-.018 3.955a.64.64 0 0 1-.246.5a.71.71 0 0 1-.594.121c-.759-.166-1.623-.12-2.048-.014c-.422.137-.657.452-.657.855c0 .494.401.895.896.895h.62c.71 0 .945.11 1.648.696c.563.468 1.443.58 1.813.578h3.093c1.016 0 1.313-.407 1.641-.774c.263-.294.85-1.205 1.11-1.625");
}

.z6kuubbbf {
  stop-color: var(--svg-color--5a8092, #5A8092);
  stop-opacity: 0;
}

.zbdko4y_s {
  stop-color: var(--svg-color--3e6d60, #3E6D60);
}

.zl7ptbcaa {
  stop-color: var(--svg-color--629f8d, #629F8D);
}

.zvin7u5xb {
  d: path("M22.765 17.854c.238-.625.315-1.731.288-2.329l-1.811.051v3.805c.633-.352 1.226-.746 1.523-1.527");
}

.zwg4tzbwy {
  stop-color: var(--svg-color--33273a, #33273A);
}

</style>
