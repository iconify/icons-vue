<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iFAMpmb)" class="x5dadcc5y"/><path fill="url(#i2nlxsl)" class="x5dadcc5y"/><path fill="url(#iSafFIc)" class="wkugclxgc"/><path fill="url(#iGbe8yb)" class="wkugclxgc"/><path fill="url(#i4tGw8c)" class="wkugclxgc"/><path fill="url(#iHVaqNc)" class="wkugclxgc"/><path fill="url(#iVlHcup)" class="wkugclxgc"/><g filter="url(#i7M04Rb)"><path class="zrg3y_jju"/></g><path fill="url(#i8voukA)" class="aq3v_ubuc"/><path fill="url(#ihR24Id)" class="aq3v_ubuc"/><path fill="url(#ihNAkGe)" class="aq3v_ubuc"/><g filter="url(#iBwvRjb)"><path fill="url(#iVmTZge)" class="nru9q9bpd"/></g><path fill="url(#ilb0Uzd)" clip-rule="evenodd" class="mvoekhbvm"/><path fill="url(#i4OpvcK)" class="pmdv0rzpb"/><path fill="url(#i9MnLNb)" class="pmdv0rzpb"/><path fill="url(#i3wlXhe)" class="pmdv0rzpb"/><g filter="url(#iBUqJ0d)"><path fill="url(#i0KWk4b)" class="w3t25xb8x"/></g><g filter="url(#i4SQ6Lc)"><path stroke="url(#i8HHkHb)" class="q7zgkbbjr"/></g><g filter="url(#i2bKOhK)"><path fill="url(#ifJQAqd)" class="r3cd7sbgg"/></g><path fill="url(#iwqVucc)" class="obq06obmo"/><path fill="url(#itIHtse)" class="g3hon124l"/><path fill="url(#iI9PFJd)" class="g3hon124l"/><path fill="url(#iOL3hPd)" class="g3hon124l"/><path fill="url(#i5v3q9d)" transform="rotate(7.73 23.732 10.855)" class="nttmgt_lp"/><g filter="url(#ieDwXXd)"><path fill="url(#i2PNsZT)" class="muzmk845o"/><path fill="url(#iGd3XKh)" class="muzmk845o"/></g><path fill="url(#iIMYcgc)" clip-rule="evenodd" class="nxybkor6f"/><path fill="url(#ixxH4ee)" clip-rule="evenodd" class="l3vjdnbmd"/><path fill="url(#itHA64b)" clip-rule="evenodd" class="l3vjdnbmd"/><path clip-rule="evenodd" class="xsoywroju"/><path class="q6epy-qya"/><path class="zs9jptbhz"/><path fill="url(#izSUo0c)" class="lto1ixl2y"/><path fill="url(#iHypade)" class="lto1ixl2y"/><path class="h1_p4uiiz"/><path fill="url(#isgaQkc)" class="b81tddb_w"/><path fill="url(#iQ7g8Ce)" class="b81tddb_w"/><path fill="url(#ivZ4OVc)" class="b81tddb_w"/><path fill="url(#i5246se)" class="b81tddb_w"/><path fill="url(#iQEc57s)" class="d2fojsb4f"/><path class="whq5-5bzq"/><circle class="o3js6ibkh"/><path fill="url(#iRjrasb)" class="cx-7836rj"/><path fill="url(#i2Tk0vc)" class="cx-7836rj"/><path fill="url(#i4Kn5Dc)" class="cx-7836rj"/><path fill="url(#iCvgdAc)" class="cx-7836rj"/><path fill="url(#ijGvy2b)" class="cx-7836rj"/><g filter="url(#i1DVkse)"><path class="yu2j1ol9f"/><path fill="url(#iOOmOLe)" class="flspenk-x"/><path fill="url(#iyvrhOd)" class="flspenk-x"/><path fill="url(#i1DlqMc)" class="flspenk-x"/></g><g filter="url(#igYyCMe)"><path class="b5ag2pbme"/><path fill="url(#iIlvKNd)" class="chiotgbzu"/></g><g filter="url(#iAumjge)"><path class="l07i0acay"/><path fill="url(#iuzCDqc)" class="m0cqjqnsx"/><path fill="url(#iQ6J6bc)" class="m0cqjqnsx"/><path fill="url(#iAXvANd)" class="m0cqjqnsx"/></g><g filter="url(#iGcqZte)"><path class="ew7clxbsr"/><path fill="url(#iuzCDqc)" class="m0cqjqnsx"/><path fill="url(#iQ6J6bc)" class="m0cqjqnsx"/><path fill="url(#iAXvANd)" class="m0cqjqnsx"/></g><g filter="url(#iQS9Lcc)"><path class="alc4cpt4h"/><path fill="url(#iMtxBSb)" class="ndyh8979c"/></g><path fill="url(#iQPxfmd)" clip-rule="evenodd" class="wn_6m3bxz"/><path fill="url(#iWAmRRb)" clip-rule="evenodd" class="wn_6m3bxz"/><path fill="url(#iVWSEGM)" clip-rule="evenodd" class="wn_6m3bxz"/><path class="ilq93-bqr"/><path fill="url(#iu8tcue)" class="jshiirb1w"/><path class="apepbtaox"/><path class="xg9yk-b9w"/><path class="um7h7oboh"/><path fill="url(#iDCFYFe)" class="k_9xnjbwb"/><path class="nuvdjsn7g"/><path fill="url(#inFtZFb)" class="rfs6bwbui"/><path class="cizko5beq"/><path fill="url(#iJYbsAc)" class="j_uprv0mx"/><g filter="url(#ifheNIe)"><path fill="url(#igJ2Hhc)" class="b8c0am0gh"/></g><circle fill="url(#im3ppae)" class="wvor0186l"/><path clip-rule="evenodd" class="drd-t4bce"/><path fill="url(#iuFbOOb)" clip-rule="evenodd" class="p4vm9m_fh"/><path fill="url(#isiioOe)" clip-rule="evenodd" class="p4vm9m_fh"/><path fill="url(#iFfe1qc)" clip-rule="evenodd" class="p4vm9m_fh"/><g filter="url(#ikH0LEQ)"><path fill="url(#iXKL6Rc)" class="tf7b0rbrj"/></g><g filter="url(#i9A732d)"><path fill="url(#i9ZhaPO)" class="h175rac5o"/></g><path class="iouh8_b2j"/><path fill="url(#i8UZlVc)" class="p0tyrlbkg"/><g filter="url(#ifKtWVb)"><path clip-rule="evenodd" class="dj5525van"/></g><path fill="url(#iovZs8l)" class="huz3d_teb"/><path fill="url(#itW30kc)" class="huz3d_teb"/><path fill="url(#iBcpLVm)" class="huz3d_teb"/><path fill="url(#iTDVOJx)" class="hy6j1b9bq"/><path fill="url(#iP6DQUd)" class="hy6j1b9bq"/><path fill="url(#iB2S9Ke)" class="hy6j1b9bq"/><defs><radialGradient id="iFAMpmb" cx="0" cy="0" r="1" gradientTransform="matrix(1.4063 -8.03125 17.4103 3.0486 7.508 28.552)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="t-qeblb7d"/><stop offset="1" class="nkzm4gb5h"/></radialGradient><radialGradient id="i4tGw8c" cx="0" cy="0" r="1" gradientTransform="rotate(-83.29 17.225 5.21)scale(2.67447 5.21781)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="mmu9u7bsf"/><stop offset="1" class="tylpo8bot"/></radialGradient><radialGradient id="iHVaqNc" cx="0" cy="0" r="1" gradientTransform="rotate(155.431 3.148 10.663)scale(1.5806 2.92056)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="n7r2-292q"/><stop offset=".695" class="n_3yhnb8a"/></radialGradient><radialGradient id="iVlHcup" cx="0" cy="0" r="1" gradientTransform="matrix(5.21875 -2.75 .52109 .98889 3.913 21.427)" gradientUnits="userSpaceOnUse"><stop offset=".457" class="vp6yj4xxl"/><stop offset="1" class="rdr27y14e"/></radialGradient><radialGradient id="ihNAkGe" cx="0" cy="0" r="1" gradientTransform="rotate(174.89 9.49 5.287)scale(3.85909 10.4756)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="nmynr_cvx"/><stop offset="1" class="p2417ob0x"/></radialGradient><radialGradient id="ilb0Uzd" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 5.5625 -3.9363 .81822 20.32 7.24)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="q4ysocc-i"/><stop offset=".884" class="q264kdbup"/></radialGradient><radialGradient id="i9MnLNb" cx="0" cy="0" r="1" gradientTransform="matrix(9.95983 -3.00679 4.88716 16.18849 2.356 8.59)" gradientUnits="userSpaceOnUse"><stop offset=".897" class="sf7z4ybcf"/><stop offset=".982" class="bpm5gvbdi"/></radialGradient><radialGradient id="i0KWk4b" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 -.8125 1.05147 3.72059 13.163 7.427)" gradientUnits="userSpaceOnUse"><stop offset=".275" class="reex3410h"/><stop offset="1" class="wlyubdb4v"/></radialGradient><radialGradient id="iwqVucc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00002 .65234 -.82062 -.00003 22.874 8.13)" gradientUnits="userSpaceOnUse"><stop offset=".515" class="gbpc64bji"/><stop offset="1" class="ovz69fb_x"/></radialGradient><radialGradient id="iI9PFJd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.17188 1.40443 0 25.554 21.63)" gradientUnits="userSpaceOnUse"><stop class="amik16rrq"/><stop offset="1" class="ibka94bwi"/></radialGradient><radialGradient id="iOL3hPd" cx="0" cy="0" r="1" gradientTransform="matrix(.39063 .6836 -1.70288 .97308 24.476 19.15)" gradientUnits="userSpaceOnUse"><stop class="nwhi_fa4f"/><stop offset="1" class="vps27w8pe"/></radialGradient><radialGradient id="i5v3q9d" cx="0" cy="0" r="1" gradientTransform="matrix(.00508 -1.12418 .93572 .00423 25.04 11.924)" gradientUnits="userSpaceOnUse"><stop class="vx6_akbll"/><stop offset="1" class="crx2hg4yh"/></radialGradient><radialGradient id="i2PNsZT" cx="0" cy="0" r="1" gradientTransform="matrix(2.03124 1.96875 -2.04192 2.10673 23.163 8.724)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="b8g00zlka"/><stop offset="1" class="z7m9rdbog"/></radialGradient><radialGradient id="iGd3XKh" cx="0" cy="0" r="1" gradientTransform="rotate(119.268 10.328 12.005)scale(1.62995 1.31525)" gradientUnits="userSpaceOnUse"><stop class="iooxo1wql"/><stop offset="1" class="hlbcv5m7e"/></radialGradient><radialGradient id="itHA64b" cx="0" cy="0" r="1" gradientTransform="matrix(-.05078 .15625 -1.00516 -.32667 26.011 19.521)" gradientUnits="userSpaceOnUse"><stop class="tslw4_1qu"/><stop offset="1" class="ijj8_s6sp"/></radialGradient><radialGradient id="iHypade" cx="0" cy="0" r="1" gradientTransform="matrix(-2.23438 -.90624 .39526 -.97452 21.646 22)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="m1yqw3kzt"/><stop offset="1" class="afdr7o0yz"/></radialGradient><radialGradient id="isgaQkc" cx="0" cy="0" r="1" gradientTransform="rotate(-144.462 16.226 9.922)scale(.80647 2.46844)" gradientUnits="userSpaceOnUse"><stop class="kt6hdg08n"/><stop offset="1" class="j-c4i6bgu"/></radialGradient><radialGradient id="iQ7g8Ce" cx="0" cy="0" r="1" gradientTransform="rotate(-171.191 12.845 13.261)scale(2.03585 4.1214)" gradientUnits="userSpaceOnUse"><stop offset=".54" class="ylvew1phe"/><stop offset="1" class="rlbn0jwxx"/></radialGradient><radialGradient id="i5246se" cx="0" cy="0" r="1" gradientTransform="matrix(-1.85938 -.29686 .97701 -6.1195 23.1 28.24)" gradientUnits="userSpaceOnUse"><stop offset=".604" class="uuc-lrj5h"/><stop offset="1" class="shmkg3ete"/></radialGradient><radialGradient id="i2Tk0vc" cx="0" cy="0" r="1" gradientTransform="rotate(136.273 10.144 11.756)scale(2.98384 2.4723)" gradientUnits="userSpaceOnUse"><stop class="aamjxwftu"/><stop offset="1" class="kbmwaf_hi"/></radialGradient><radialGradient id="i4Kn5Dc" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 1.35937 -3.85802 .79821 23.85 11.724)" gradientUnits="userSpaceOnUse"><stop class="xs_2ilnpm"/><stop offset="1" class="p8p5c3bvm"/></radialGradient><radialGradient id="iCvgdAc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.06251 1.12498 -.6497 -1.19113 22.929 14.1)" gradientUnits="userSpaceOnUse"><stop class="am3w7_blp"/><stop offset="1" class="couxg3lqo"/></radialGradient><radialGradient id="ijGvy2b" cx="0" cy="0" r="1" gradientTransform="matrix(.98437 .46875 -1.87887 3.94563 21.507 15.255)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="dq08bkdrq"/><stop offset="1" class="wqel62b_c"/></radialGradient><radialGradient id="iOOmOLe" cx="0" cy="0" r="1" gradientTransform="matrix(1.64062 -2.32812 1.8984 1.3378 20.695 21.771)" gradientUnits="userSpaceOnUse"><stop class="mr6mdpt1g"/><stop offset="1" class="jbbp6_bdq"/></radialGradient><radialGradient id="iyvrhOd" cx="0" cy="0" r="1" gradientTransform="matrix(.65625 .48438 -1.05948 1.43542 20.241 19.646)" gradientUnits="userSpaceOnUse"><stop class="pids_pbns"/><stop offset="1" class="xzhs54baa"/></radialGradient><radialGradient id="i1DlqMc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.875 1.75 -.85312 -.91406 22.116 19.568)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="tvjmrrbpc"/><stop offset="1" class="ahho1w97n"/></radialGradient><radialGradient id="iuzCDqc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.25 -1.34374 .47918 -1.15897 22.6 17.834)" gradientUnits="userSpaceOnUse"><stop class="kao1--wwn"/><stop offset="1" class="lykybbi9r"/></radialGradient><radialGradient id="iAXvANd" cx="0" cy="0" r="1" gradientTransform="matrix(-.29687 .53125 -3.08778 -1.7255 23.304 17.177)" gradientUnits="userSpaceOnUse"><stop class="ws0t5un5c"/><stop offset="1" class="t20d06bem"/></radialGradient><radialGradient id="iMtxBSb" cx="0" cy="0" r="1" gradientTransform="matrix(.92186 -1.28125 2.36816 1.7039 10.538 19.333)" gradientUnits="userSpaceOnUse"><stop offset=".68" class="ps4wek9uf"/><stop offset=".964" class="mwbu5sbnw"/></radialGradient><radialGradient id="iVWSEGM" cx="0" cy="0" r="1" gradientTransform="matrix(1.21875 .67969 -.21221 .38051 20.96 16.13)" gradientUnits="userSpaceOnUse"><stop class="uubye-mwc"/><stop offset="1" class="gu1w6obkb"/></radialGradient><radialGradient id="iu8tcue" cx="0" cy="0" r="1" gradientTransform="matrix(.70312 -.09375 .03207 .24052 19.982 6.734)" gradientUnits="userSpaceOnUse"><stop class="z4zbxthsh"/><stop offset="1" class="egb5_lbyf"/></radialGradient><radialGradient id="igJ2Hhc" cx="0" cy="0" r="1" gradientTransform="rotate(126.754 10.899 11.703)scale(1.54063 1.00944)" gradientUnits="userSpaceOnUse"><stop class="ac50icc3e"/><stop offset="1" class="cztd2jqtm"/></radialGradient><radialGradient id="im3ppae" cx="0" cy="0" r="1" gradientTransform="rotate(83.69 7.54 18.852)scale(.81745)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="p1xawgtbo"/><stop offset="1" class="xoq-ina2u"/></radialGradient><radialGradient id="iFfe1qc" cx="0" cy="0" r="1" gradientTransform="matrix(.13672 .11328 -.664 .80138 24.952 9.63)" gradientUnits="userSpaceOnUse"><stop class="pav55masc"/><stop offset="1" class="egqy8jbwr"/></radialGradient><radialGradient id="iXKL6Rc" cx="0" cy="0" r="1" gradientTransform="rotate(129.693 11.703 9.952)scale(2.03059 2.38667)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="w9h_a4buy"/><stop offset=".919" class="jvvv5bmeo"/></radialGradient><radialGradient id="i9ZhaPO" cx="0" cy="0" r="1" gradientTransform="matrix(.36719 -.45313 1.162 .94162 25.663 8.333)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="chmofghwi"/><stop offset="1" class="tn7myqe_j"/></radialGradient><radialGradient id="iovZs8l" cx="0" cy="0" r="1" gradientTransform="rotate(-160.017 12.54 6.872)scale(3.29195 1.49462)" gradientUnits="userSpaceOnUse"><stop class="zf7t0yb1u"/><stop offset="1" class="jpzdg-bwz"/></radialGradient><radialGradient id="itW30kc" cx="0" cy="0" r="1" gradientTransform="matrix(1.15626 -3.3125 9.2644 3.23382 19.741 19.584)" gradientUnits="userSpaceOnUse"><stop offset=".771" class="nuwcoob-p"/><stop offset="1" class="gzdogx1hl"/></radialGradient><radialGradient id="iBcpLVm" cx="0" cy="0" r="1" gradientTransform="rotate(78.869 -1.985 19.889)scale(2.50907 .7401)" gradientUnits="userSpaceOnUse"><stop class="r8uyz9bqp"/><stop offset="1" class="f2xkzabrk"/></radialGradient><radialGradient id="iTDVOJx" cx="0" cy="0" r="1" gradientTransform="rotate(98.903 6.405 16.212)scale(2.42307 5.69158)" gradientUnits="userSpaceOnUse"><stop offset=".274" class="k2smfncym"/><stop offset="1" class="nr_9l6l2k"/></radialGradient><radialGradient id="iB2S9Ke" cx="0" cy="0" r="1" gradientTransform="matrix(-.92187 .21875 -.25309 -1.06657 24.695 13.052)" gradientUnits="userSpaceOnUse"><stop class="vgv_qabik"/><stop offset="1" class="muvudkmkj"/></radialGradient><linearGradient id="i2nlxsl" x1="11.438" x2="11.438" y1="30.099" y2="28.804" gradientUnits="userSpaceOnUse"><stop class="c3098ubep"/><stop offset="1" class="hujbubc9t"/></linearGradient><linearGradient id="iSafFIc" x1="5.32" x2="6.476" y1="17.677" y2="20.959" gradientUnits="userSpaceOnUse"><stop offset=".373" class="gpdazcbld"/><stop offset="1" class="afg7wtasa"/></linearGradient><linearGradient id="iGbe8yb" x1="5.82" x2="6.163" y1="17.677" y2="18.646" gradientUnits="userSpaceOnUse"><stop offset=".142" class="f2yuiwowd"/><stop offset="1" class="zp0x88wix"/></linearGradient><linearGradient id="i8voukA" x1="13.413" x2="11.57" y1="1.99" y2="15.115" gradientUnits="userSpaceOnUse"><stop offset=".518" class="bpm5gvbdi"/><stop offset="1" class="njdjvcttb"/></linearGradient><linearGradient id="ihR24Id" x1="2.601" x2="13.132" y1="17.865" y2="13.709" gradientUnits="userSpaceOnUse"><stop offset=".293" class="boi6lnlog"/><stop offset="1" class="ybn2mcbio"/></linearGradient><linearGradient id="iVmTZge" x1="14.269" x2="16.87" y1="10.816" y2="15.334" gradientUnits="userSpaceOnUse"><stop offset=".368" class="d6jlrzbaa"/><stop offset="1" class="w5vd7udwg"/></linearGradient><linearGradient id="i4OpvcK" x1="4.507" x2="6.882" y1="5.396" y2="13.677" gradientUnits="userSpaceOnUse"><stop class="mn787q_6r"/><stop offset="1" class="mzz_2wq-t"/></linearGradient><linearGradient id="i3wlXhe" x1="5.788" x2="5.507" y1="14.287" y2="13.287" gradientUnits="userSpaceOnUse"><stop class="t20fa7b7o"/><stop offset="1" class="e2k-esbpn"/></linearGradient><linearGradient id="i8HHkHb" x1="19.59" x2="21.516" y1="8.243" y2="11.402" gradientUnits="userSpaceOnUse"><stop class="y6k--c7ym"/><stop offset="1" class="v26q47bkt"/></linearGradient><linearGradient id="ifJQAqd" x1="19.576" x2="20.935" y1="11.098" y2="15.758" gradientUnits="userSpaceOnUse"><stop class="eky141x3a"/><stop offset="1" class="dfv3zlvmf"/></linearGradient><linearGradient id="itIHtse" x1="25.101" x2="26.507" y1="20.443" y2="20.443" gradientUnits="userSpaceOnUse"><stop class="v5_ahxl8w"/><stop offset="1" class="os32btykc"/></linearGradient><linearGradient id="iIMYcgc" x1="24.875" x2="24.601" y1="18.705" y2="18.705" gradientUnits="userSpaceOnUse"><stop offset=".269" class="x9rbvhxej"/><stop offset="1" class="biyiff5mh"/></linearGradient><linearGradient id="ixxH4ee" x1="26.491" x2="24.475" y1="19.983" y2="19.146" gradientUnits="userSpaceOnUse"><stop class="dnpfueb4s"/><stop offset="1" class="e_59tbbed"/></linearGradient><linearGradient id="izSUo0c" x1="22.802" x2="21.677" y1="25.438" y2="26" gradientUnits="userSpaceOnUse"><stop offset=".267" class="bnldzacmr"/><stop offset="1" class="e9dmvq9mi"/></linearGradient><linearGradient id="ivZ4OVc" x1="23.261" x2="23.155" y1="28.064" y2="27.982" gradientUnits="userSpaceOnUse"><stop class="fiw9fyalo"/><stop offset="1" class="n7jws8bws"/></linearGradient><linearGradient id="iQEc57s" x1="23.659" x2="23.905" y1="8.388" y2="7.951" gradientUnits="userSpaceOnUse"><stop class="bie0h0-8q"/><stop offset="1" class="fwnzc4ctw"/></linearGradient><linearGradient id="iRjrasb" x1="24.882" x2="22.695" y1="15.958" y2="12.146" gradientUnits="userSpaceOnUse"><stop class="r1kmajh1r"/><stop offset="1" class="dwwl7kmwu"/></linearGradient><linearGradient id="iIlvKNd" x1="14.177" x2="14.802" y1="17" y2="17.999" gradientUnits="userSpaceOnUse"><stop class="ti929abbi"/><stop offset="1" class="nerh9eh2b"/></linearGradient><linearGradient id="iQ6J6bc" x1="20.132" x2="21.101" y1="20.247" y2="17.271" gradientUnits="userSpaceOnUse"><stop class="msti5wbjw"/><stop offset="1" class="gepa-4uov"/></linearGradient><linearGradient id="iQPxfmd" x1="23.103" x2="23.103" y1="16.834" y2="18.271" gradientUnits="userSpaceOnUse"><stop class="b06izibxm"/><stop offset="1" class="jn6chbb5g"/></linearGradient><linearGradient id="iWAmRRb" x1="24.296" x2="24.527" y1="18.361" y2="17.916" gradientUnits="userSpaceOnUse"><stop offset=".457" class="qd-f9ooxs"/><stop offset="1" class="fy9sosv6u"/></linearGradient><linearGradient id="iDCFYFe" x1="15.617" x2="15.945" y1="11.857" y2="11.474" gradientUnits="userSpaceOnUse"><stop offset=".002" class="zbfwxqbqy"/><stop offset="1" class="foshnm2dn"/></linearGradient><linearGradient id="inFtZFb" x1="15.825" x2="16.22" y1="11.428" y2="10.967" gradientUnits="userSpaceOnUse"><stop offset=".002" class="zbfwxqbqy"/><stop offset="1" class="foshnm2dn"/></linearGradient><linearGradient id="iJYbsAc" x1="16.091" x2="16.528" y1="11.032" y2="10.513" gradientUnits="userSpaceOnUse"><stop offset=".002" class="zbfwxqbqy"/><stop offset="1" class="foshnm2dn"/></linearGradient><linearGradient id="iuFbOOb" x1="24.945" x2="24.624" y1="9.984" y2="9.74" gradientUnits="userSpaceOnUse"><stop class="zcigs7bii"/><stop offset="1" class="nr87if9lw"/></linearGradient><linearGradient id="isiioOe" x1="23.491" x2="23.929" y1="10.537" y2="10.826" gradientUnits="userSpaceOnUse"><stop offset=".324" class="x0zx5qyer"/><stop offset="1" class="k6zficbhz"/></linearGradient><linearGradient id="i8UZlVc" x1="16.509" x2="16.953" y1="10.804" y2="10.359" gradientUnits="userSpaceOnUse"><stop offset=".002" class="zbfwxqbqy"/><stop offset="1" class="foshnm2dn"/></linearGradient><linearGradient id="iP6DQUd" x1="23.21" x2="23.085" y1="14.865" y2="13.943" gradientUnits="userSpaceOnUse"><stop class="m3e4macxz"/><stop offset="1" class="j6phqvxik"/></linearGradient><filter id="i7M04Rb" width="8.743" height="7.346" x="1.956" y="23.154" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.607843 0 0 0 0 0.670588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_854"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.831373 0 0 0 0 0.862745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_854" result="effect2_innerShadow_4002_854"/></filter><filter id="iBwvRjb" width="4.276" height="5.599" x="13.345" y="9.473" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_854" stdDeviation=".375"/></filter><filter id="iBUqJ0d" width="3.479" height="7.738" x="13.92" y="2.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.02" dy="-.06"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.792157 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_854"/></filter><filter id="i4SQ6Lc" width="2.679" height="4.12" x="19.144" y="7.398" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_854" stdDeviation=".15"/></filter><filter id="i2bKOhK" width="2.822" height="15.029" x="19.286" y="2.154" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.47451 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_854"/></filter><filter id="ieDwXXd" width="4.68" height="4.407" x="21.992" y="7.138" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.0980392 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_854"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.278431 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_854" result="effect2_innerShadow_4002_854"/></filter><filter id="i1DVkse" width="5.527" height="3.544" x="18.964" y="18.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.4 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_854"/></filter><filter id="igYyCMe" width="9.577" height="5.489" x="9.645" y="15.129" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.152941 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_854"/></filter><filter id="iAumjge" width="6.672" height="5.002" x="18.132" y="15.246" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.372549 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_854"/></filter><filter id="iGcqZte" width="6.922" height="5.002" x="18.132" y="15.246" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.364706 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_854"/></filter><filter id="iQS9Lcc" width="2.568" height="3.646" x="9.622" y="16.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.247059 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_854"/></filter><filter id="ifheNIe" width="2.604" height="2.473" x="25.109" y="8.922" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0745098 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_854"/></filter><filter id="ikH0LEQ" width="4.913" height="4.647" x="23.386" y="5.562" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.556863 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_854"/></filter><filter id="i9A732d" width="1.588" height="1.361" x="25.048" y="7.424" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.482353 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_854"/></filter><filter id="ifKtWVb" width="6.514" height="4.796" x="15.609" y="10.186" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.180392 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_854"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-climbing-dark" /></template>
<style>
.aamjxwftu {
  stop-color: var(--svg-color--53bfff, #53BFFF);
}

.ac50icc3e {
  stop-color: var(--svg-color--231820, #231820);
}

.afdr7o0yz {
  stop-color: var(--svg-color--3f282f, #3F282F);
  stop-opacity: 0;
}

.afg7wtasa {
  stop-color: var(--svg-color--a5a2a8, #A5A2A8);
}

.ahho1w97n {
  stop-color: var(--svg-color--5e505b, #5E505B);
  stop-opacity: 0;
}

.alc4cpt4h {
  fill: var(--svg-color--5c5089, #5C5089);
  d: path("m12.14 20.158l-.91.455a.2.2 0 0 1-.27-.092l-1.32-2.758c-.046-.096 0-.23.09-.288c.241-.153.506-.097.906.112c.381.2 1.143.895 1.492 1.215l.012-.008z");
}

.am3w7_blp {
  stop-color: var(--svg-color--1b7eec, #1B7EEC);
}

.amik16rrq {
  stop-color: var(--svg-color--5a3c98, #5A3C98);
}

.apepbtaox {
  fill: var(--svg-color--4d3c3d, #4D3C3D);
  d: path("m16.78 10.116l.079.643l.34 1.149l.69-.367c-.175-.184-.309-.336-.44-.875a4 4 0 0 1-.08-.598a.3.3 0 0 0-.312-.28a.293.293 0 0 0-.277.328");
}

.aq3v_ubuc {
  d: path("M14.803 14.834L2.356 19.196V2.154H18.3c-.4 2.851-1.233 8.86-1.49 10.68c-.183 1.303-.801 1.523-2.007 2");
}

.b06izibxm {
  stop-color: var(--svg-color--8bad3a, #8BAD3A);
}

.b5ag2pbme {
  fill: var(--svg-color--432b2a, #432B2A);
  d: path("m18.425 15.51l.797.32l-.836 2.25l-.834-.52a.25.25 0 0 0-.245-.01l-6.036 3.047a.2.2 0 0 1-.27-.091l-1.33-2.759c-.047-.095-.03-.215.06-.272c.24-.153.505-.097.905.112c.381.2 1.143.895 1.492 1.215c1.1-.765 3.307-2.392 4.05-2.945c.837-.621 1.846-.517 2.247-.348");
}

.b81tddb_w {
  d: path("m23.04 26.303l.799.575a.2.2 0 0 1 .046.278l-1.753 2.486c-.06.087-.171.128-.263.075c-.178-.101-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203l-.002-.002z");
}

.b8c0am0gh {
  d: path("m25.161 10.39l.488-1.368l1.663 1.17c-.182.277-.795 1.021-1.025 1.104c-.318.113-.785.19-1.035-.118c-.2-.247-.15-.65-.091-.789");
}

.b8g00zlka {
  stop-color: var(--svg-color--402e2d, #402E2D);
}

.bie0h0-8q {
  stop-color: var(--svg-color--6f443d, #6F443D);
}

.biyiff5mh {
  stop-color: var(--svg-color--333061, #333061);
}

.bnldzacmr {
  stop-color: var(--svg-color--635050, #635050);
}

.boi6lnlog {
  stop-color: var(--svg-color--9c93a5, #9C93A5);
}

.bpm5gvbdi {
  stop-color: var(--svg-color--e5e3e5, #E5E3E5);
}

.c3098ubep {
  stop-color: var(--svg-color--d2cdd5, #D2CDD5);
}

.chiotgbzu {
  d: path("m18.425 15.51l.797.32l-.836 2.25l-.834-.52a.25.25 0 0 0-.245-.01l-6.036 3.047a.2.2 0 0 1-.27-.091l-1.33-2.759c-.047-.095-.03-.215.06-.272c.24-.153.505-.097.905.112c.381.2 1.143.895 1.492 1.215c1.1-.765 3.307-2.392 4.05-2.945c.837-.621 1.846-.517 2.247-.348");
}

.chmofghwi {
  stop-color: var(--svg-color--4b89d0, #4B89D0);
}

.cizko5beq {
  fill: var(--svg-color--4d3c3d, #4D3C3D);
  d: path("M15.192 10.3a.28.28 0 1 1 .368-.421l1.754 1.506l-.368.42z");
}

.couxg3lqo {
  stop-color: var(--svg-color--1b7eec, #1B7EEC);
  stop-opacity: 0;
}

.crx2hg4yh {
  stop-color: var(--svg-color--321f20, #321F20);
}

.cx-7836rj {
  d: path("m22.624 13.052l-1.25 2.82l3.39 2.258c.563-.726 1.267-2.851 1.243-4.242c-.018-1.055-.436-1.404-1.102-1.765c-.316-.172-1.025-.28-1.398-.16s-.73.663-.883 1.09");
}

.cztd2jqtm {
  stop-color: var(--svg-color--151a31, #151A31);
}

.d2fojsb4f {
  d: path("m23.83 8.496l.026-.04c.131-.216.144-.448.027-.519c-.116-.07-.317.047-.448.263l-.015.026z");
}

.d6jlrzbaa {
  stop-color: var(--svg-color--908790, #908790);
}

.dfv3zlvmf {
  stop-color: var(--svg-color--648431, #648431);
}

.dj5525van {
  fill: var(--svg-color--472f32, #472F32);
  fill-rule: evenodd;
  d: path("m18.264 14.343l-2.655-2.435l1.259-1.372l2.59 2.527a.63.63 0 0 0 .581.15l1.65-.423l.433 1.696l-1.65.422a2.38 2.38 0 0 1-2.208-.565");
}

.dnpfueb4s {
  stop-color: var(--svg-color--40347f, #40347F);
}

.dq08bkdrq {
  stop-color: var(--svg-color--67a3db, #67A3DB);
}

.drd-t4bce {
  fill: var(--svg-color--4d3771, #4D3771);
  fill-rule: evenodd;
  d: path("M25.714 8.594a.25.25 0 0 1 .032.353l-1.992 2.394a.25.25 0 0 1-.384-.32l1.992-2.394a.25.25 0 0 1 .352-.033");
}

.dwwl7kmwu {
  stop-color: var(--svg-color--4d94cd, #4D94CD);
}

.e_59tbbed {
  stop-color: var(--svg-color--292557, #292557);
}

.e2k-esbpn {
  stop-color: var(--svg-color--c3c0c6, #C3C0C6);
  stop-opacity: 0;
}

.e9dmvq9mi {
  stop-color: var(--svg-color--635050, #635050);
  stop-opacity: 0;
}

.egb5_lbyf {
  stop-color: var(--svg-color--5f4f4d, #5F4F4D);
  stop-opacity: 0;
}

.egqy8jbwr {
  stop-color: var(--svg-color--4d3a6e, #4D3A6E);
  stop-opacity: 0;
}

.eky141x3a {
  stop-color: var(--svg-color--489778, #489778);
}

.ew7clxbsr {
  fill: var(--svg-color--9f97a9, #9F97A9);
  d: path("m21.093 16.529l.195-.438l3.516 2.024c-.034.107-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.258-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
}

.f2xkzabrk {
  stop-color: var(--svg-color--ada2a2, #ADA2A2);
  stop-opacity: 0;
}

.f2yuiwowd {
  stop-color: var(--svg-color--948b99, #948B99);
}

.fiw9fyalo {
  stop-color: var(--svg-color--4b4386, #4B4386);
}

.flspenk-x {
  d: path("m19.464 20.812l.969-1.17l4.058-.988c-.765 1.394-2 3.052-2.187 3.277c-.234.281-.555.34-.89.176c-.813-.4-1.61-.947-1.95-1.295");
}

.foshnm2dn {
  stop-color: var(--svg-color--432e34, #432E34);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fwnzc4ctw {
  stop-color: var(--svg-color--5a332d, #5A332D);
}

.fy9sosv6u {
  stop-color: var(--svg-color--417c62, #417C62);
  stop-opacity: 0;
}

.g3hon124l {
  d: path("m24.6 19.15l1.907.63v.73a.953.953 0 1 1-1.906 0z");
}

.gbpc64bji {
  stop-color: var(--svg-color--463736, #463736);
}

.gepa-4uov {
  stop-color: var(--svg-color--8c7786, #8C7786);
  stop-opacity: 0;
}

.gpdazcbld {
  stop-color: var(--svg-color--a9a5ad, #A9A5AD);
}

.gu1w6obkb {
  stop-color: var(--svg-color--a6ca7d, #A6CA7D);
  stop-opacity: 0;
}

.gzdogx1hl {
  stop-color: var(--svg-color--7e7776, #7E7776);
}

.h1_p4uiiz {
  fill: var(--svg-color--544583, #544583);
  d: path("m23.04 26.303l.799.575a.2.2 0 0 1 .046.278l-1.753 2.486c-.06.087-.171.128-.263.075c-.178-.101-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203l-.002-.002z");
}

.h175rac5o {
  d: path("M25.111 7.542a.3.3 0 0 1 .423-.055l.984.757a.302.302 0 0 1-.368.479l-.984-.758a.3.3 0 0 1-.055-.423");
}

.hlbcv5m7e {
  stop-color: var(--svg-color--2b1a25, #2B1A25);
  stop-opacity: 0;
}

.hujbubc9t {
  stop-color: var(--svg-color--e3e1e5, #E3E1E5);
  stop-opacity: 0;
}

.huz3d_teb {
  d: path("M21.095 16.524c.654.302 1.479.99 2.021 2.231c.195.446.143.899-.041 1.322c-.619.264-1.291.183-2.013.014c-.906-.21-1.484-.406-1.85-.53q-.12-.042-.213-.071c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012l2.02.782z");
}

.hy6j1b9bq {
  d: path("m21.52 15.138l-.547-2.156c.64-.154 1.85-.479 2.09-.535c.45-.106 1.266-.154 1.465.816c.183.895-.518 1.18-.86 1.281z");
}

.ibka94bwi {
  stop-color: var(--svg-color--5a3c98, #5A3C98);
  stop-opacity: 0;
}

.ijj8_s6sp {
  stop-color: var(--svg-color--63608c, #63608C);
  stop-opacity: 0;
}

.ilq93-bqr {
  fill: var(--svg-color--3f292a, #3F292A);
  d: path("M20.484 7.029a1.4 1.4 0 0 1-.25.816l-.282-.695l-.27.07c-.316.078-.437-.094-.456-.191c-.02-.098-.043-.387.37-.469c.415-.082.884-.023.888.469");
}

.iooxo1wql {
  stop-color: var(--svg-color--2b1a25, #2B1A25);
}

.iouh8_b2j {
  fill: var(--svg-color--4d3c3d, #4D3C3D);
  d: path("M15.765 10.069a.28.28 0 1 1 .367-.42l1.41 1.419l-.226.512z");
}

.j_uprv0mx {
  d: path("M15.192 10.3a.28.28 0 1 1 .368-.421l1.754 1.506l-.368.42z");
}

.j-c4i6bgu {
  stop-color: var(--svg-color--5e598c, #5E598C);
  stop-opacity: 0;
}

.j6phqvxik {
  stop-color: var(--svg-color--2280e0, #2280E0);
  stop-opacity: 0;
}

.jbbp6_bdq {
  stop-color: var(--svg-color--716170, #716170);
  stop-opacity: 0;
}

.jn6chbb5g {
  stop-color: var(--svg-color--337267, #337267);
}

.jpzdg-bwz {
  stop-color: var(--svg-color--aea0a4, #AEA0A4);
  stop-opacity: 0;
}

.jshiirb1w {
  d: path("M20.484 7.029a1.4 1.4 0 0 1-.25.816l-.282-.695l-.27.07c-.316.078-.437-.094-.456-.191c-.02-.098-.043-.387.37-.469c.415-.082.884-.023.888.469");
}

.jvvv5bmeo {
  stop-color: var(--svg-color--52abe4, #52ABE4);
}

.k_9xnjbwb {
  d: path("M14.965 11.348A.232.232 0 0 1 15.27 11l1.245 1.088l-.305.35z");
}

.k2smfncym {
  stop-color: var(--svg-color--34aef0, #34AEF0);
}

.k6zficbhz {
  stop-color: var(--svg-color--72687c, #72687C);
  stop-opacity: 0;
}

.kao1--wwn {
  stop-color: var(--svg-color--aea0a5, #AEA0A5);
}

.kbmwaf_hi {
  stop-color: var(--svg-color--53bfff, #53BFFF);
  stop-opacity: 0;
}

.kt6hdg08n {
  stop-color: var(--svg-color--5e598c, #5E598C);
}

.l07i0acay {
  fill: var(--svg-color--a7959b, #A7959B);
  d: path("m21.093 16.529l.195-.438l3.516 2.024c-.034.107-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.258-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
}

.l3vjdnbmd {
  fill-rule: evenodd;
  d: path("M24.486 19.112a.2.2 0 0 1 .255-.124l1.742.606a.2.2 0 1 1-.131.378l-1.743-.606a.2.2 0 0 1-.123-.254");
}

.lto1ixl2y {
  d: path("m19.195 21.1l.39-.407l2.11 1.187l-.493.5l1.836 3.922l.8.576a.2.2 0 0 1 .047.277l-1.753 2.487c-.06.087-.171.128-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203c-.662-.94-2.138-3.045-2.75-3.945s-.167-1.636.133-1.89");
}

.lykybbi9r {
  stop-color: var(--svg-color--aea0a5, #AEA0A5);
  stop-opacity: 0;
}

.m0cqjqnsx {
  d: path("m21.093 16.529l.195-.438l3.516 2.024c-.034.107-.239.498-.789 1.21c-.86 1.079-1.848 1.024-2.953.766c-1.106-.258-1.723-.492-2.063-.601c-.34-.11-.724-.306-.836-.64c-.09-.27.034-.78.102-.954l.782-2.137a.02.02 0 0 1 .026-.012z");
}

.m1yqw3kzt {
  stop-color: var(--svg-color--3f282f, #3F282F);
}

.m3e4macxz {
  stop-color: var(--svg-color--2280e0, #2280E0);
}

.mmu9u7bsf {
  stop-color: var(--svg-color--bcb9be, #BCB9BE);
}

.mn787q_6r {
  stop-color: var(--svg-color--c7c5c9, #C7C5C9);
}

.mr6mdpt1g {
  stop-color: var(--svg-color--716170, #716170);
}

.msti5wbjw {
  stop-color: var(--svg-color--8c7786, #8C7786);
}

.muvudkmkj {
  stop-color: var(--svg-color--56c0ff, #56C0FF);
  stop-opacity: 0;
}

.muzmk845o {
  d: path("M22.312 9.576c.277-.875.95-1.815 1.21-2.188l2.9 1.867l-.594 2.047a4.5 4.5 0 0 1-1.813 0c-.945-.21-2.067-.578-1.703-1.726");
}

.mvoekhbvm {
  fill-rule: evenodd;
  d: path("M23.664 13.914c-3.618-1.712-4.891-4.456-5.481-6.545c-.111-.427.035-.996.59-1.09l.693-.157a.41.41 0 0 1 .476.341c.33 2.085 1.175 4.09 4.47 5.869z");
}

.mwbu5sbnw {
  stop-color: var(--svg-color--4a4476, #4A4476);
}

.mzz_2wq-t {
  stop-color: var(--svg-color--c2bfc5, #C2BFC5);
}

.n_3yhnb8a {
  stop-color: var(--svg-color--958e9b, #958E9B);
  stop-opacity: 0;
}

.n7jws8bws {
  stop-color: var(--svg-color--4b4386, #4B4386);
  stop-opacity: 0;
}

.n7r2-292q {
  stop-color: var(--svg-color--958e9b, #958E9B);
}

.ndyh8979c {
  d: path("m12.14 20.158l-.91.455a.2.2 0 0 1-.27-.092l-1.32-2.758c-.046-.096 0-.23.09-.288c.241-.153.506-.097.906.112c.381.2 1.143.895 1.492 1.215l.012-.008z");
}

.nerh9eh2b {
  stop-color: var(--svg-color--564748, #564748);
  stop-opacity: 0;
}

.njdjvcttb {
  stop-color: var(--svg-color--ae9ea8, #AE9EA8);
}

.nkzm4gb5h {
  stop-color: var(--svg-color--a297ad, #A297AD);
}

.nmynr_cvx {
  stop-color: var(--svg-color--e3d5d2, #E3D5D2);
}

.nr_9l6l2k {
  stop-color: var(--svg-color--3a9cf8, #3A9CF8);
}

.nr87if9lw {
  stop-color: var(--svg-color--37234c, #37234C);
  stop-opacity: 0;
}

.nru9q9bpd {
  d: path("m16.87 12.409l-.06.425c-.113.802-.39 1.194-.87 1.488l-.857-1.286l-.946-1.329a.232.232 0 0 1 .324-.323l-.127-.178a.28.28 0 0 1 .292-.433l-.024-.033a.28.28 0 1 1 .455-.324l.107.147a.28.28 0 0 1 .5-.223l.499.819l.026-.229a.293.293 0 0 1 .345-.254a.3.3 0 0 1 .238.345a4 4 0 0 0-.06.6c.001.39.072.613.158.788");
}

.nttmgt_lp {
  d: path("M23.732 10.855h1.905v1.844h-1.905z");
}

.nuvdjsn7g {
  fill: var(--svg-color--4d3c3d, #4D3C3D);
  d: path("M15.04 10.815a.28.28 0 0 1 .368-.42l1.5 1.31l-.368.42z");
}

.nuwcoob-p {
  stop-color: var(--svg-color--a49ba8, #A49BA8);
  stop-opacity: 0;
}

.nwhi_fa4f {
  stop-color: var(--svg-color--413b69, #413B69);
}

.nxybkor6f {
  fill-rule: evenodd;
  d: path("M24.675 18.063c.11 0 .2.09.2.2v.883a.2.2 0 0 1-.4 0v-.883c0-.11.09-.2.2-.2");
}

.o3js6ibkh {
  cx: 23.764px;
  cy: 8.032px;
  r: 0.072px;
  fill: var(--svg-color--dfdfdf, #DFDFDF);
}

.obq06obmo {
  d: path("M22.452 8.388c.032-.207.153-.27.45-.351a.7.7 0 0 0 .387-.248l-.458.994c-.21 0-.41-.188-.379-.395");
}

.os32btykc {
  stop-color: var(--svg-color--66619b, #66619B);
}

.ovz69fb_x {
  stop-color: var(--svg-color--483637, #483637);
}

.p0tyrlbkg {
  d: path("M15.765 10.069a.28.28 0 1 1 .367-.42l1.41 1.419l-.226.512z");
}

.p1xawgtbo {
  stop-color: var(--svg-color--402d2f, #402D2F);
}

.p2417ob0x {
  stop-color: var(--svg-color--e3d5d2, #E3D5D2);
  stop-opacity: 0;
}

.p4vm9m_fh {
  fill-rule: evenodd;
  d: path("M25.714 8.594a.25.25 0 0 1 .032.353l-1.992 2.394a.25.25 0 0 1-.384-.32l1.992-2.394a.25.25 0 0 1 .352-.033");
}

.p8p5c3bvm {
  stop-color: var(--svg-color--4788c0, #4788C0);
  stop-opacity: 0;
}

.pav55masc {
  stop-color: var(--svg-color--564975, #564975);
}

.pids_pbns {
  stop-color: var(--svg-color--948f8f, #948F8F);
}

.pmdv0rzpb {
  d: path("M10.22 2.154c.551 1.054 1.37 2.957 1.85 4.836c.78 3.062-.25 5.281-3.75 6.312a881 881 0 0 1-5.964 1.725V2.154z");
}

.ps4wek9uf {
  stop-color: var(--svg-color--4a4476, #4A4476);
  stop-opacity: 0;
}

.q264kdbup {
  stop-color: var(--svg-color--382125, #382125);
}

.q4ysocc-i {
  stop-color: var(--svg-color--3e2829, #3E2829);
}

.q6epy-qya {
  fill: var(--svg-color--fff, #fff);
  d: path("M23.804 7.904c-.201.031-.326.221-.387.32l.735.485c.257-.625-.075-.848-.348-.805");
}

.q7zgkbbjr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.694 7.948c.07.492.482 1.784 1.58 3.02");
}

.qd-f9ooxs {
  stop-color: var(--svg-color--3a5669, #3A5669);
}

.r1kmajh1r {
  stop-color: var(--svg-color--3aadff, #3AADFF);
}

.r3cd7sbgg {
  d: path("M19.286 2.154v9.588c0 .132.027.263.079.384l1.706 3.989l.42.137c.05.114.166.978.28.929a.225.225 0 0 0 .119-.295l-2.112-4.937a.5.5 0 0 1-.042-.207V2.154z");
}

.r8uyz9bqp {
  stop-color: var(--svg-color--ada2a2, #ADA2A2);
}

.rdr27y14e {
  stop-color: var(--svg-color--9f9ca3, #9F9CA3);
  stop-opacity: 0;
}

.reex3410h {
  stop-color: var(--svg-color--e2dfe2, #E2DFE2);
}

.rfs6bwbui {
  d: path("M15.04 10.815a.28.28 0 0 1 .368-.42l1.5 1.31l-.368.42z");
}

.rlbn0jwxx {
  stop-color: var(--svg-color--4d407b, #4D407B);
}

.sf7z4ybcf {
  stop-color: var(--svg-color--d1cfd2, #D1CFD2);
  stop-opacity: 0;
}

.shmkg3ete {
  stop-color: var(--svg-color--7a7996, #7A7996);
}

.t-qeblb7d {
  stop-color: var(--svg-color--e2e0e4, #E2E0E4);
}

.t20d06bem {
  stop-color: var(--svg-color--816878, #816878);
  stop-opacity: 0;
}

.t20fa7b7o {
  stop-color: var(--svg-color--9d94a6, #9D94A6);
}

.tf7b0rbrj {
  d: path("m27.11 10.16l-3.628-2.696a.22.22 0 0 1-.069-.288a4.8 4.8 0 0 1 .655-.866c.906-.957 1.909-.492 2.055-.438c.21.078.754.313 1.5 1.024c.875.834.742 1.703.476 2.226c-.167.33-.457.742-.663 1a.235.235 0 0 1-.326.038");
}

.ti929abbi {
  stop-color: var(--svg-color--564748, #564748);
}

.tn7myqe_j {
  stop-color: var(--svg-color--337bcd, #337BCD);
}

.tslw4_1qu {
  stop-color: var(--svg-color--63608c, #63608C);
}

.tvjmrrbpc {
  stop-color: var(--svg-color--5e505b, #5E505B);
}

.tylpo8bot {
  stop-color: var(--svg-color--bcb9be, #BCB9BE);
  stop-opacity: 0;
}

.um7h7oboh {
  fill: var(--svg-color--4d3c3d, #4D3C3D);
  d: path("M14.965 11.348A.232.232 0 0 1 15.27 11l1.245 1.088l-.305.35z");
}

.uubye-mwc {
  stop-color: var(--svg-color--a6ca7d, #A6CA7D);
}

.uuc-lrj5h {
  stop-color: var(--svg-color--7a7996, #7A7996);
  stop-opacity: 0;
}

.v26q47bkt {
  stop-color: var(--svg-color--584949, #584949);
  stop-opacity: 0;
}

.v5_ahxl8w {
  stop-color: var(--svg-color--554682, #554682);
}

.vgv_qabik {
  stop-color: var(--svg-color--56c0ff, #56C0FF);
}

.vp6yj4xxl {
  stop-color: var(--svg-color--9f9ca3, #9F9CA3);
}

.vps27w8pe {
  stop-color: var(--svg-color--413b69, #413B69);
  stop-opacity: 0;
}

.vx6_akbll {
  stop-color: var(--svg-color--493234, #493234);
}

.w3t25xb8x {
  d: path("M13.94 2.11c.393 1.553.85 4.693.134 7.329a.276.276 0 0 0 .165.331a.23.23 0 0 0 .144.01c.378-.105.836-.512 1.153-1.287c.567-1.385 1.18-3.75 1.637-5.515l.226-.868z");
}

.w5vd7udwg {
  stop-color: var(--svg-color--908790, #908790);
  stop-opacity: 0;
}

.w9h_a4buy {
  stop-color: var(--svg-color--4fbdff, #4FBDFF);
}

.whq5-5bzq {
  fill: var(--svg-color--414141, #414141);
  d: path("m23.672 8.392l.053-.07c.073-.12.081-.25.018-.288c-.062-.038-.173.028-.246.148l-.035.071z");
}

.wkugclxgc {
  d: path("M9.591 17.093a.93.93 0 0 1 .458-.698l-7.693 2.651v2.661c.68-.275 2.227-.92 3.284-1.415c.886-.414 1.715-.409 2.178-.289l3.341.924l-1.32-2.768c-.248-.52-.303-.66-.248-1.066");
}

.wlyubdb4v {
  stop-color: var(--svg-color--d6d4d7, #D6D4D7);
}

.wn_6m3bxz {
  fill-rule: evenodd;
  d: path("M21.072 15.896a.25.25 0 0 1 .341-.092l3.629 2.09a.25.25 0 1 1-.25.434l-3.628-2.09a.25.25 0 0 1-.092-.342");
}

.wqel62b_c {
  stop-color: var(--svg-color--67a3db, #67A3DB);
  stop-opacity: 0;
}

.ws0t5un5c {
  stop-color: var(--svg-color--816878, #816878);
}

.wvor0186l {
  cx: 25.448px;
  cy: 9.445px;
  r: 0.559px;
}

.x0zx5qyer {
  stop-color: var(--svg-color--72687c, #72687C);
}

.x5dadcc5y {
  d: path("M2.356 30.1v-8.954l5.204-1.977l2.513 1.29c-.22-.383.6-.538 1.07.43c.235.48-.113 1.812-.597 2.421l-1.32 1.48a.4.4 0 0 0 .023.557l5 4.752z");
}

.x9rbvhxej {
  stop-color: var(--svg-color--535478, #535478);
}

.xg9yk-b9w {
  fill: var(--svg-color--472f32, #472F32);
  d: path("m16.78 10.116l.079.643l.34 1.149l.69-.367c-.175-.184-.309-.336-.44-.875a4 4 0 0 1-.08-.598a.3.3 0 0 0-.312-.28a.293.293 0 0 0-.277.328");
}

.xoq-ina2u {
  stop-color: var(--svg-color--2e1018, #2E1018);
}

.xs_2ilnpm {
  stop-color: var(--svg-color--4788c0, #4788C0);
}

.xsoywroju {
  fill: var(--svg-color--290017, #290017);
  fill-rule: evenodd;
  d: path("M22.677 9.294a.1.1 0 0 1 .139-.028c.085.055.25.102.52.04a.1.1 0 1 1 .045.195c-.308.071-.533.025-.675-.068a.1.1 0 0 1-.029-.139");
}

.xzhs54baa {
  stop-color: var(--svg-color--948f8f, #948F8F);
  stop-opacity: 0;
}

.y6k--c7ym {
  stop-color: var(--svg-color--584949, #584949);
}

.ybn2mcbio {
  stop-color: var(--svg-color--9c93a5, #9C93A5);
  stop-opacity: 0;
}

.ylvew1phe {
  stop-color: var(--svg-color--4d407b, #4D407B);
  stop-opacity: 0;
}

.yu2j1ol9f {
  fill: var(--svg-color--67636c, #67636C);
  d: path("m19.464 20.812l.969-1.17l4.058-.988c-.765 1.394-2 3.052-2.187 3.277c-.234.281-.555.34-.89.176c-.813-.4-1.61-.947-1.95-1.295");
}

.z4zbxthsh {
  stop-color: var(--svg-color--5f4f4d, #5F4F4D);
}

.z7m9rdbog {
  stop-color: var(--svg-color--41292d, #41292D);
}

.zbfwxqbqy {
  stop-color: var(--svg-color--432e34, #432E34);
}

.zcigs7bii {
  stop-color: var(--svg-color--37234c, #37234C);
}

.zf7t0yb1u {
  stop-color: var(--svg-color--aea0a4, #AEA0A4);
}

.zp0x88wix {
  stop-color: var(--svg-color--aaa6ae, #AAA6AE);
  stop-opacity: 0;
}

.zrg3y_jju {
  fill: var(--svg-color--a29ea7, #A29EA7);
  d: path("M2.356 23.154v6.945H10.7a169 169 0 0 1-2.973-1.578c-1.038-.575-1.31-1.146-1.485-1.524c-.065-.14-.186-.45-.371-.924l-.285-.724c-.322-.816-.953-1.219-1.437-1.422z");
}

.zs9jptbhz {
  fill: var(--svg-color--40262e, #40262E);
  d: path("m19.195 21.1l.39-.407l2.11 1.187l-.493.5l1.836 3.922l.8.576a.2.2 0 0 1 .047.277l-1.753 2.487c-.06.087-.171.128-.263.075c-.178-.102-.37-.296-.37-.579c-.037-.556.193-1.7.313-2.203c-.662-.94-2.138-3.045-2.75-3.945s-.167-1.636.133-1.89");
}

</style>
