<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i3U4Arb)" class="h_aagwbag"/><path fill="url(#iNQoP4d)" class="h_aagwbag"/><g filter="url(#itjgM4c)"><path fill="url(#iRtd5mc)" class="xq6nvzqsi"/></g><path fill="url(#iIr5KLe)" class="n3fdoubpa"/><path fill="url(#iCGgyAd)" class="n3fdoubpa"/><path class="jh3urib9t"/><path fill="url(#iI5CGmR)" class="zu5-vd24j"/><path fill="url(#iahmwVR)" class="zu5-vd24j"/><path fill="url(#i04Coqh)" class="zu5-vd24j"/><path fill="url(#isvB4Gb)" class="ok5u1w3sx"/><path fill="url(#imZyyPc)" class="ok5u1w3sx"/><path fill="url(#iM7rvQc)" class="ok5u1w3sx"/><path fill="url(#iaZ9hte)" class="ok5u1w3sx"/><g filter="url(#ihSSNAe)"><path class="k8f4j7bnu"/></g><g filter="url(#iM1dWEb)"><path fill="url(#iV5Z1Tc)" class="f01sbdcnp"/><path fill="url(#iqqnwNb)" class="f01sbdcnp"/></g><path fill="url(#ippT0xe)" class="f01sbdcnp"/><g filter="url(#ilVMOdd)"><ellipse class="fxvd_47pj"/></g><g filter="url(#ilZoknb)"><path fill="url(#i6wV25g)" class="utkdp49kv"/><path fill="url(#ixnBDab)" class="utkdp49kv"/><path fill="url(#ifIGXhb)" class="utkdp49kv"/></g><ellipse fill="url(#iynYhTK)" class="fu__w01ad"/><ellipse fill="url(#iv41EXd)" class="fu__w01ad"/><path fill="url(#ipn5Wye)" class="f8d1s3bel"/><path fill="url(#i7ZtD3c)" class="yxlean3rw"/><path fill="url(#iDevtGO)" class="yxlean3rw"/><rect fill="url(#idlRFWl)" class="lbznaibos"/><rect fill="url(#ijWAcVc)" class="lbznaibos"/><g filter="url(#imT5Igc)"><path fill="url(#iNVf1uc)" class="cqtk20epn"/></g><g filter="url(#i7yF4qc)"><path fill="url(#iCADh1d)" class="cqtk20epn"/><path fill="url(#iI6GHJr)" class="cqtk20epn"/><path fill="url(#iur2D5O)" class="cqtk20epn"/><path fill="url(#iUM27kU)" class="cqtk20epn"/><path fill="url(#ibjoY1c)" class="cqtk20epn"/></g><g filter="url(#imJHeOH)"><circle fill="url(#isV2U9b)" class="jtw_6-yua"/></g><circle fill="url(#iEirsue)" class="i4o649bnz"/><circle fill="url(#i1OWTxc)" class="i4o649bnz"/><g filter="url(#iKipkeu)"><circle fill="url(#iRepvfb)" class="t1w2v13iw"/></g><g filter="url(#iATzewd)"><circle fill="url(#iFrMWGc)" class="rzgix9n0j"/></g><g filter="url(#iBTXkGc)"><path fill="url(#izAVwce)" class="il_qbgb8d"/><path fill="url(#i2USAjE)" class="il_qbgb8d"/></g><path fill="url(#iE43HYd)" class="il_qbgb8d"/><path fill="url(#i8fNVic)" class="il_qbgb8d"/><path fill="url(#iMHPkXd)" class="il_qbgb8d"/><path fill="url(#iq8xgoc)" class="il_qbgb8d"/><g filter="url(#ibvNpCc)"><path class="l734e0bav"/></g><path fill="url(#iXq9U9b)" class="urt-asbls"/><path fill="url(#ibsTXSd)" class="urt-asbls"/><g filter="url(#iAK5Tuc)"><path class="vbey9csnv"/><path fill="url(#ik3egAe)" class="jnai-rb9x"/></g><g filter="url(#iE1tvac)"><path stroke="url(#i6n2QSi)" class="shdn2-1cj"/></g><path class="u_i25-byi"/><g filter="url(#iWjH7sb)"><path fill="url(#ineBBFb)" class="fss29_bok"/><path fill="url(#i0ViyXd)" class="fss29_bok"/></g><g filter="url(#iXyZwCc)"><path fill="url(#iemmiec)" class="apxiqlf5v"/><path fill="url(#ip2g4Vx)" class="apxiqlf5v"/><path fill="url(#itTblbg)" class="apxiqlf5v"/><path fill="url(#iKhyJwc)" class="apxiqlf5v"/><path fill="url(#idqHhoc)" class="apxiqlf5v"/><path fill="url(#i576p7t)" class="apxiqlf5v"/></g><path class="f7h5-qb-f"/><path fill="url(#iqITyoe)" class="grxor6t4s"/><path class="unyz2nb7v"/><g filter="url(#iXcW5pb)"><path class="r8_iis6dl"/><path fill="url(#iSx73Nc)" class="f68xt0bbz"/></g><g filter="url(#icG2hTc)"><path fill="url(#iarvSCI)" class="joi32pbhd"/></g><path class="ova749bei"/><path fill="url(#iXk3cSc)" class="m_iky2b5b"/><path class="ntzydvb0y"/><g filter="url(#iV7Ozpe)"><path fill="url(#iQqxaDc)" class="xeef6mbed"/></g><g filter="url(#iQajhlb)"><ellipse transform="rotate(-27.914 13.373 9.947)" class="fy50dsb9i"/><ellipse fill="url(#iShOsye)" transform="rotate(-27.914 13.373 9.947)" class="k3duu_y0r"/></g><defs><radialGradient id="i3U4Arb" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.5824 -20.8203 0 16 18.28)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="gawd5obvo"/><stop offset="1" class="rn540obxc"/></radialGradient><radialGradient id="iNQoP4d" cx="0" cy="0" r="1" gradientTransform="rotate(124.924 1.252 11.006)scale(12.8824 12.131)" gradientUnits="userSpaceOnUse"><stop class="y9rlcreuk"/><stop offset="1" class="xd0kopb5v"/></radialGradient><radialGradient id="iIr5KLe" cx="0" cy="0" r="1" gradientTransform="rotate(123.174 5.769 15.536)scale(11.5365 12.2083)" gradientUnits="userSpaceOnUse"><stop class="r3949-bju"/><stop offset="1" class="s9sui_61e"/></radialGradient><radialGradient id="iCGgyAd" cx="0" cy="0" r="1" gradientTransform="rotate(100.184 -.387 13.98)scale(5.30229 7.65346)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="t-ehpbubw"/><stop offset="1" class="h61yu9bmy"/></radialGradient><radialGradient id="iahmwVR" cx="0" cy="0" r="1" gradientTransform="matrix(5.4375 0 0 14.5199 23.023 29.584)" gradientUnits="userSpaceOnUse"><stop offset=".698" class="oj7ch-bkx"/><stop offset="1" class="ce13789qs"/></radialGradient><radialGradient id="i04Coqh" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.1762 .21924 0 23.523 29.916)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="x8ej_jb7y"/><stop offset="1" class="mjbwacbml"/></radialGradient><radialGradient id="imZyyPc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.6875 0 0 -13.3438 9.398 29.74)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="wx3vdcbzg"/><stop offset="1" class="jug-l4bwb"/></radialGradient><radialGradient id="iM7rvQc" cx="0" cy="0" r="1" gradientTransform="matrix(.14062 -1.5668 5.45335 .48945 5.555 29.916)" gradientUnits="userSpaceOnUse"><stop class="x_0jnxbib"/><stop offset="1" class="wn7157b9l"/></radialGradient><radialGradient id="iaZ9hte" cx="0" cy="0" r="1" gradientTransform="matrix(-.21094 0 0 -15.1051 8.227 29.916)" gradientUnits="userSpaceOnUse"><stop class="ujtti6ofv"/><stop offset="1" class="gewmlvbcg"/></radialGradient><radialGradient id="ippT0xe" cx="0" cy="0" r="1" gradientTransform="matrix(-.70312 .54687 -.67794 -.87163 19.555 23.365)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="l56m45bvi"/><stop offset="1" class="v2ucwt3jq"/></radialGradient><radialGradient id="ixnBDab" cx="0" cy="0" r="1" gradientTransform="matrix(-3.8125 0 0 -3.66953 14.21 15.96)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="rqcot095h"/><stop offset="1" class="jbe42ccmq"/></radialGradient><radialGradient id="ifIGXhb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.53125 -3 0 20.586 15.303)" gradientUnits="userSpaceOnUse"><stop offset=".184" class="mzeokobes"/><stop offset="1" class="qhzdg_bmj"/></radialGradient><radialGradient id="iynYhTK" cx="0" cy="0" r="1" gradientTransform="rotate(126.363 3.374 13.883)scale(1.76569 1.94865)" gradientUnits="userSpaceOnUse"><stop class="su-lx9b4e"/><stop offset="1" class="fh2jv1bsu"/></radialGradient><radialGradient id="iv41EXd" cx="0" cy="0" r="1" gradientTransform="rotate(111.306 1.371 15.393)scale(1.67712 2.10568)" gradientUnits="userSpaceOnUse"><stop offset=".511" class="otqjsqgnm"/><stop offset="1" class="cz6js0bhr"/></radialGradient><radialGradient id="ipn5Wye" cx="0" cy="0" r="1" gradientTransform="matrix(-.61153 3.54705 -4.21362 -.72645 21.314 11.74)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="uhnyo9buy"/><stop offset="1" class="e1m_j1-ji"/></radialGradient><radialGradient id="i7ZtD3c" cx="0" cy="0" r="1" gradientTransform="matrix(1.2784 2.69135 -1.22334 .5811 10.268 12.025)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="iDevtGO" cx="0" cy="0" r="1" gradientTransform="matrix(.17994 1.19788 -1.0508 .15784 11.072 11.82)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="idlRFWl" cx="0" cy="0" r="1" gradientTransform="matrix(1.25001 1.79325 -2.57261 1.79328 15.554 16.865)" gradientUnits="userSpaceOnUse"><stop offset=".352" class="fo-r_8b7l"/><stop offset="1" class="x39b-tbnv"/></radialGradient><radialGradient id="ijWAcVc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.75 .60936 -.75278 -3.39724 16.43 17.084)" gradientUnits="userSpaceOnUse"><stop offset=".555" class="nr4jety8s"/><stop offset="1" class="urt8mz7mv"/></radialGradient><radialGradient id="iI6GHJr" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.64558 6.45926 0 10.588 9.375)" gradientUnits="userSpaceOnUse"><stop class="ytx-8cb1b"/><stop offset="1" class="y3fq4efvh"/></radialGradient><radialGradient id="iur2D5O" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.64559 6.45926 0 20.714 9.375)" gradientUnits="userSpaceOnUse"><stop class="ugkkbdcpr"/><stop offset="1" class="lty0cjbuw"/></radialGradient><radialGradient id="iUM27kU" cx="0" cy="0" r="1" gradientTransform="matrix(-3.26327 -1.24475 .66291 -1.73791 19.957 3.076)" gradientUnits="userSpaceOnUse"><stop class="ofjdtziny"/><stop offset="1" class="znwnmpxvd"/></radialGradient><radialGradient id="ibjoY1c" cx="0" cy="0" r="1" gradientTransform="matrix(.90833 1.48025 -3.42756 2.10327 14.927 1.478)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="mvigw0raw"/><stop offset="1" class="tmhk4ybst"/></radialGradient><radialGradient id="isV2U9b" cx="0" cy="0" r="1" gradientTransform="matrix(1.40308 0 0 2.07344 9.805 10.79)" gradientUnits="userSpaceOnUse"><stop class="y8t70hbxb"/><stop offset="1" class="o1dxquboz"/></radialGradient><radialGradient id="iEirsue" cx="0" cy="0" r="1" gradientTransform="rotate(135.637 9.114 9.47)scale(2.35218 2.04384)" gradientUnits="userSpaceOnUse"><stop class="r_kuisbux"/><stop offset="1" class="m55q8ispu"/></radialGradient><radialGradient id="i1OWTxc" cx="0" cy="0" r="1" gradientTransform="matrix(-.61743 .40625 -.65226 -.99132 21.188 10.131)" gradientUnits="userSpaceOnUse"><stop offset=".547" class="qqmscub7d"/><stop offset="1" class="w08v59e9w"/></radialGradient><radialGradient id="iFrMWGc" cx="0" cy="0" r="1" gradientTransform="matrix(1.18316 -1.06048 .56444 .62974 20.306 11.036)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="l8yxupbpv"/><stop offset="1" class="ys50rfypm"/></radialGradient><radialGradient id="izAVwce" cx="0" cy="0" r="1" gradientTransform="matrix(-8.4375 0 0 -11.5896 19.46 10.962)" gradientUnits="userSpaceOnUse"><stop class="l1md-grhu"/><stop offset=".715" class="a66881bhb"/></radialGradient><radialGradient id="i2USAjE" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.454 8.135)scale(3.38098 2.79127)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="wjwn33b7s"/><stop offset="1" class="zb_y65bxb"/></radialGradient><radialGradient id="iE43HYd" cx="0" cy="0" r="1" gradientTransform="matrix(4.21875 -4.1875 .99164 .99904 10.46 7.24)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="gxsknpbio"/><stop offset="1" class="pswg0plle"/></radialGradient><radialGradient id="i8fNVic" cx="0" cy="0" r="1" gradientTransform="matrix(1.5544 -3.73297 9.67273 4.02772 14.328 17.352)" gradientUnits="userSpaceOnUse"><stop offset=".198" class="nlc0hsb0h"/><stop offset="1" class="frhkfnwcc"/></radialGradient><radialGradient id="iMHPkXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.2176 -12.5359 0 15.883 7.326)" gradientUnits="userSpaceOnUse"><stop offset=".823" class="czrhrjbev"/><stop offset="1" class="ps9y5f8nd"/></radialGradient><radialGradient id="iq8xgoc" cx="0" cy="0" r="1" gradientTransform="matrix(-.48782 7.3125 -3.56778 -.23801 21.011 10.356)" gradientUnits="userSpaceOnUse"><stop class="mbfiytbde"/><stop offset="1" class="fju3u7bml"/></radialGradient><radialGradient id="ik3egAe" cx="0" cy="0" r="1" gradientTransform="matrix(-.47307 -4.01376 1.45513 -.1715 16.777 12.182)" gradientUnits="userSpaceOnUse"><stop offset=".166" class="z12l7tb2s"/><stop offset="1" class="o2ztw4w4i"/></radialGradient><radialGradient id="i6n2QSi" cx="0" cy="0" r="1" gradientTransform="matrix(.3484 -.62165 1.02917 .57679 14.705 14.263)" gradientUnits="userSpaceOnUse"><stop class="x5037tbuk"/><stop offset="1" class="jlx-p80cl"/></radialGradient><radialGradient id="ineBBFb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.82047 1.37847 -.38366 -1.06332 16.09 2.925)" gradientUnits="userSpaceOnUse"><stop class="f6hra4b6c"/><stop offset="1" class="gz-wtrqbh"/></radialGradient><radialGradient id="i0ViyXd" cx="0" cy="0" r="1" gradientTransform="matrix(3.22962 -5.11358 5.66532 3.57809 10.386 7.702)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="nd6y13bdf"/><stop offset=".233" class="z45w8t_um"/><stop offset="1" class="jm3h91bib"/></radialGradient><radialGradient id="iemmiec" cx="0" cy="0" r="1" gradientTransform="matrix(3.39784 .80368 -.44947 1.9003 19.47 4.09)" gradientUnits="userSpaceOnUse"><stop class="dzh_o9bpc"/><stop offset="1" class="d2ds5d49n"/></radialGradient><radialGradient id="ip2g4Vx" cx="0" cy="0" r="1" gradientTransform="matrix(-2.15625 -3.71688 2.07288 -1.20252 20.983 8.71)" gradientUnits="userSpaceOnUse"><stop class="zmfxcpbii"/><stop offset="1" class="t1qc5-b8a"/></radialGradient><radialGradient id="itTblbg" cx="0" cy="0" r="1" gradientTransform="matrix(-1.31202 -2.21013 1.58303 -.93975 20.36 8.41)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="rk366-b7y"/><stop offset="1" class="m70pgaboa"/></radialGradient><radialGradient id="iKhyJwc" cx="0" cy="0" r="1" gradientTransform="rotate(166.509 10.088 3.207)scale(4.95216 5.35347)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="gxl2qg7tq"/><stop offset="1" class="j1i4w4hfh"/></radialGradient><radialGradient id="idqHhoc" cx="0" cy="0" r="1" gradientTransform="matrix(-.11775 .3851 -1.76059 -.53833 19.3 3.847)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="howk4obit"/><stop offset="1" class="r0f0npb-q"/></radialGradient><radialGradient id="i576p7t" cx="0" cy="0" r="1" gradientTransform="matrix(-2.00167 3.76792 -9.71644 -5.16175 19.298 3.022)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="h-4ltow4h"/><stop offset="1" class="rr64b4bjv"/></radialGradient><radialGradient id="iqITyoe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8142 -1.29509 0 18.026 10.043)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iSx73Nc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.378 .706)scale(.37917 .52204)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iXk3cSc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81425 -1.29515 0 13.646 10.043)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iShOsye" cx="0" cy="0" r="1" gradientTransform="matrix(-.00776 -.49554 .59566 -.00933 13.357 10.262)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="itjgM4c" width="25.813" height="14.219" x="3.094" y="15.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_934" stdDeviation=".125"/></filter><filter id="ihSSNAe" width="9.1" height="7.705" x="10.832" y="22.381" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_934" stdDeviation=".5"/></filter><filter id="iM1dWEb" width="7.926" height="6.427" x="11.873" y="22.809" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.670588 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_934"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.407843 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_934" result="effect2_innerShadow_4002_934"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.317647 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_934" result="effect3_innerShadow_4002_934"/></filter><filter id="ilVMOdd" width="3.095" height="3.11" x="14.004" y="18.67" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_934" stdDeviation=".25"/></filter><filter id="ilZoknb" width="11.606" height="4.825" x="10.133" y="15.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.25"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.223529 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_934"/></filter><filter id="imT5Igc" width="12.918" height="8.385" x="9.376" y="1.583" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.152941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_934"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.133333 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_934" result="effect2_innerShadow_4002_934"/></filter><filter id="i7yF4qc" width="12.918" height="8.385" x="9.376" y="1.583" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.733333 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_934"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.678431 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_934" result="effect2_innerShadow_4002_934"/></filter><filter id="imJHeOH" width="3.463" height="3.363" x="9.42" y="8.981" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.607843 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_934"/></filter><filter id="iKipkeu" width="2.793" height="2.793" x="9.705" y="9.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_934" stdDeviation=".125"/></filter><filter id="iATzewd" width="2.893" height="2.893" x="19.124" y="9.216" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_934" stdDeviation=".15"/></filter><filter id="iBTXkGc" width="11.057" height="12.536" x="10.754" y="4.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.627451 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_934"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_934" result="effect2_innerShadow_4002_934"/></filter><filter id="ibvNpCc" width="2.884" height="3.91" x="14.186" y="9.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_934" stdDeviation=".25"/></filter><filter id="iAK5Tuc" width="2.184" height="3.11" x="14.894" y="9.739" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.580392 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_934"/></filter><filter id="iE1tvac" width="3.63" height="1.477" x="14.021" y="13.322" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_934" stdDeviation=".05"/></filter><filter id="iWjH7sb" width="6.606" height="6.011" x="9.734" y="2.675" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_934" stdDeviation=".125"/></filter><filter id="iXyZwCc" width="6.383" height="5.755" x="15.676" y="3.205" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_934" stdDeviation=".125"/></filter><filter id="iXcW5pb" width=".788" height=".697" x="17.289" y="9.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_934" stdDeviation=".05"/></filter><filter id="icG2hTc" width=".893" height=".915" x="18.132" y="9.677" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_934" stdDeviation=".1"/></filter><filter id="iV7Ozpe" width=".988" height="1.042" x="13.674" y="9.614" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_934" stdDeviation=".1"/></filter><filter id="iQajhlb" width=".915" height=".706" x="12.916" y="9.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_934" stdDeviation=".05"/></filter><linearGradient id="iRtd5mc" x1="16" x2="16" y1="16.144" y2="30.249" gradientUnits="userSpaceOnUse"><stop offset=".866" class="tyjpv6bnm"/><stop offset="1" class="xyu2htzlq"/></linearGradient><linearGradient id="iI5CGmR" x1="26.836" x2="26.617" y1="30.209" y2="27.459" gradientUnits="userSpaceOnUse"><stop class="pmf-vsdxp"/><stop offset="1" class="w6_8my7ls"/></linearGradient><linearGradient id="isvB4Gb" x1="8.43" x2="5.18" y1="25.115" y2="25.115" gradientUnits="userSpaceOnUse"><stop offset=".183" class="annwmpbcg"/><stop offset="1" class="l85-jsb-f"/></linearGradient><linearGradient id="iV5Z1Tc" x1="18.398" x2="13.649" y1="23.928" y2="27.272" gradientUnits="userSpaceOnUse"><stop class="big423byp"/><stop offset="1" class="zbo4__e4e"/></linearGradient><linearGradient id="iqqnwNb" x1="15.836" x2="15.836" y1="22.819" y2="24.162" gradientUnits="userSpaceOnUse"><stop class="ash9yfbkf"/><stop offset="1" class="k-dn1jb7a"/></linearGradient><linearGradient id="i6wV25g" x1="14.617" x2="19.961" y1="19.022" y2="17.115" gradientUnits="userSpaceOnUse"><stop class="umjrh49bx"/><stop offset="1" class="d7r2s6row"/></linearGradient><linearGradient id="iNVf1uc" x1="22.712" x2="11.059" y1="5.279" y2="5.279" gradientUnits="userSpaceOnUse"><stop offset=".471" class="vj4yuc0qg"/><stop offset="1" class="yd6vs-kvu"/></linearGradient><linearGradient id="iCADh1d" x1="21.218" x2="11.059" y1="5.279" y2="5.279" gradientUnits="userSpaceOnUse"><stop class="wbaoi1vzd"/><stop offset="1" class="q37q-zblj"/></linearGradient><linearGradient id="iRepvfb" x1="11.219" x2="10.101" y1="10.514" y2="10.514" gradientUnits="userSpaceOnUse"><stop class="ao008lbmy"/><stop offset="1" class="gq7vlu6rg"/></linearGradient><linearGradient id="iXq9U9b" x1="20.273" x2="12.867" y1="10.647" y2="10.647" gradientUnits="userSpaceOnUse"><stop class="z14dz9exi"/><stop offset="1" class="o1uobmugz"/></linearGradient><linearGradient id="ibsTXSd" x1="10.757" x2="12.211" y1="10.334" y2="10.334" gradientUnits="userSpaceOnUse"><stop class="f6x3qhriw"/><stop offset="1" class="onbz4ubrj"/></linearGradient><linearGradient id="iarvSCI" x1="18.806" x2="18.491" y1="10.097" y2="10.291" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iQqxaDc" x1="14.392" x2="14.077" y1="10.097" y2="10.29" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-superhero-medium-light" /></template>
<style>
.a66881bhb {
  stop-color: var(--svg-color--c68d7d, #C68D7D);
}

.annwmpbcg {
  stop-color: var(--svg-color--3e80f0, #3E80F0);
}

.ao008lbmy {
  stop-color: var(--svg-color--bd7760, #BD7760);
}

.apxiqlf5v {
  d: path("m21.067 8.71l-.03-.633c-.01-.766-.643-1.398-1.41-1.43h-1.405a2.43 2.43 0 0 1-2.131-1.264s-.06-.139-.122-.376c-.255-.97.672-1.712 1.657-1.522c.978.19 2.094.52 2.918 1.057c1.751 1.142 1.444 3.2.523 4.169");
}

.ash9yfbkf {
  stop-color: var(--svg-color--40a0f8, #40A0F8);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.big423byp {
  stop-color: var(--svg-color--47a1ff, #47A1FF);
}

.ce13789qs {
  stop-color: var(--svg-color--528adb, #528ADB);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cqtk20epn {
  d: path("M20.708 4.296c.516.177.98.538 1.272 1.055c.468.823.4 1.808-.107 2.535a1.57 1.57 0 0 0-.27.877v1.193a1.75 1.75 0 0 0-.67-.27l.078-1.612a1.455 1.455 0 0 0-1.384-1.437h-1.405a2.43 2.43 0 0 1-2.22-1.448a.67.67 0 0 0-.617-.42h-1.277c-1.853 0-3.354 1.518-3.354 3.392l.031 1.542a1.7 1.7 0 0 0-.723.265V8.763c0-.312-.095-.619-.27-.877a2.4 2.4 0 0 1-.145-2.454a2.35 2.35 0 0 1 1.304-1.13a2.7 2.7 0 0 0 1.39-1.115a2.334 2.334 0 0 1 2.9-.915c.384.167.815.167 1.198 0a2.4 2.4 0 0 1 .916-.189c.846 0 1.586.458 1.996 1.136a2.53 2.53 0 0 0 1.357 1.077");
}

.cz6js0bhr {
  stop-color: var(--svg-color--d79d4a, #D79D4A);
}

.czrhrjbev {
  stop-color: var(--svg-color--b4777e, #B4777E);
  stop-opacity: 0;
}

.d2ds5d49n {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
  stop-opacity: 0;
}

.d7r2s6row {
  stop-color: var(--svg-color--ff3656, #FF3656);
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.dzh_o9bpc {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1m_j1-ji {
  stop-color: var(--svg-color--da8f78, #DA8F78);
}

.f01sbdcnp {
  d: path("M12.975 22.96a.95.95 0 0 0-.819 1.431l2.301 3.907a1.6 1.6 0 0 0 2.758 0l2.3-3.907a.95.95 0 0 0-.818-1.432z");
}

.f68xt0bbz {
  d: path("M17.96 9.754c.064.085-.069.189-.22.302c-.152.113-.264.193-.328.108c-.063-.085.008-.246.16-.36c.15-.113.325-.136.389-.05");
}

.f6hra4b6c {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
}

.f6x3qhriw {
  stop-color: var(--svg-color--ab2d46, #AB2D46);
}

.f7h5-qb-f {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.235 9.291c.656 0 1.21.452 1.36 1.063a.275.275 0 0 1-.269.342h-2.239a.23.23 0 0 1-.228-.273a1.4 1.4 0 0 1 1.376-1.132");
}

.f8d1s3bel {
  d: path("M20.714 12.217c.337-.011.652-.125.908-.31v.934a2.18 2.18 0 0 1-1.346 2.026a4.1 4.1 0 0 0 .348-1.184z");
}

.fh2jv1bsu {
  stop-color: var(--svg-color--f2bb43, #F2BB43);
}

.fju3u7bml {
  stop-color: var(--svg-color--f2ba9c, #F2BA9C);
  stop-opacity: 0;
}

.fo-r_8b7l {
  stop-color: var(--svg-color--b9757b, #B9757B);
}

.frhkfnwcc {
  stop-color: var(--svg-color--c18385, #C18385);
  stop-opacity: 0;
}

.fss29_bok {
  d: path("m16.069 5.327l-.066-.138a.67.67 0 0 0-.618-.42h-1.277c-1.853 0-3.354 1.518-3.354 3.392v.276c-.34-.26-.77-.808-.77-1.694c0-1.076.785-1.62 1.285-1.966c.141-.098.26-.18.332-.255l.1-.105c.35-.372.976-1.035 2.067-1.324a5.5 5.5 0 0 1 1.516-.166c.473.012.806.42.806.893v1.493z");
}

.ft5dv1b6b {
  fill: none;
}

.fu__w01ad {
  cx: 15.836px;
  cy: 20.131px;
  rx: 1.048px;
  ry: 1.055px;
}

.fxvd_47pj {
  cx: 15.552px;
  cy: 20.225px;
  fill: var(--svg-color--2f62b7, #2F62B7);
  rx: 1.048px;
  ry: 1.055px;
}

.fy50dsb9i {
  cx: 13.373px;
  cy: 9.947px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.391px;
  ry: 0.198px;
}

.gawd5obvo {
  stop-color: var(--svg-color--ff3b9a, #FF3B9A);
}

.gewmlvbcg {
  stop-color: var(--svg-color--2154ca, #2154CA);
  stop-opacity: 0;
}

.gq7vlu6rg {
  stop-color: var(--svg-color--c17965, #C17965);
}

.grxor6t4s {
  d: path("M18.028 9.564a.896.896 0 0 1 .863 1.132h-1.73a.9.9 0 0 1 .867-1.132");
}

.gxl2qg7tq {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
  stop-opacity: 0;
}

.gxsknpbio {
  stop-color: var(--svg-color--bf7e60, #BF7E60);
}

.gz-wtrqbh {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
  stop-opacity: 0;
}

.h_aagwbag {
  d: path("M2.063 29.863c0-1.969.39-6.76 3.216-9.86C8.81 16.13 13.793 15.552 16 15.552s7.19.578 10.721 4.453c2.826 3.1 3.217 7.89 3.217 9.86z");
}

.h-4ltow4h {
  stop-color: var(--svg-color--e1b395, #E1B395);
  stop-opacity: 0;
}

.h61yu9bmy {
  stop-color: var(--svg-color--3a7ad3, #3A7AD3);
  stop-opacity: 0;
}

.howk4obit {
  stop-color: var(--svg-color--ffed93, #FFED93);
}

.i4o649bnz {
  cx: 20.57px;
  cy: 10.662px;
  r: 1.682px;
}

.il_qbgb8d {
  d: path("M10.994 13.737a3.93 3.93 0 0 0 3.9 3.418h1.892a3.93 3.93 0 0 0 3.9-3.418c.118-1.89.237-3.773.325-5.663a1.455 1.455 0 0 0-1.384-1.437h-1.405a2.43 2.43 0 0 1-2.22-1.448a.67.67 0 0 0-.617-.42h-1.277c-1.853 0-3.354 1.518-3.354 3.392c0 1.867.117 3.704.24 5.576");
}

.j1i4w4hfh {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
}

.jbe42ccmq {
  stop-color: var(--svg-color--c31852, #C31852);
  stop-opacity: 0;
}

.jh3urib9t {
  fill: var(--svg-color--4e9eff, #4E9EFF);
  d: path("M23.523 18.43v11.487h4.344v-.036c-.22-5.448-1.882-9.175-4.344-11.452");
}

.jlx-p80cl {
  stop-color: var(--svg-color--d39c8e, #D39C8E);
  stop-opacity: 0;
}

.jm3h91bib {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
  stop-opacity: 0;
}

.jnai-rb9x {
  d: path("m15.452 10.245l-.533 1.845c-.11.38.152.759.522.759h.79c.37 0 .63-.385.522-.76l-.534-1.844c-.114-.409-.647-.409-.767 0");
}

.joi32pbhd {
  d: path("M18.825 10.342a.84.84 0 0 0-.232-.465l-.26.287l.117.229z");
}

.jtw_6-yua {
  cx: 11.101px;
  cy: 10.662px;
  r: 1.682px;
}

.jug-l4bwb {
  stop-color: var(--svg-color--407dbe, #407DBE);
}

.k-dn1jb7a {
  stop-color: var(--svg-color--4392f9, #4392F9);
  stop-opacity: 0;
}

.k3duu_y0r {
  cx: 13.373px;
  cy: 9.947px;
  rx: 0.391px;
  ry: 0.198px;
}

.k8f4j7bnu {
  fill: var(--svg-color--2f63d5, #2F63D5);
  d: path("M12.718 23.381a.885.885 0 0 0-.762 1.334l2.143 3.637a1.49 1.49 0 0 0 2.567 0l2.143-3.637a.885.885 0 0 0-.762-1.334z");
}

.l1md-grhu {
  stop-color: var(--svg-color--fbc29e, #FBC29E);
}

.l56m45bvi {
  stop-color: var(--svg-color--53b7ff, #53B7FF);
}

.l734e0bav {
  fill: var(--svg-color--cd8e79, #CD8E79);
  d: path("m15.348 10.442l-.637 1.844c-.11.38.152.76.522.76h.79c.37 0 .63-.386.522-.76l-.986-.516l.453-1.328c-.115-.41-.544-.41-.664 0");
}

.l85-jsb-f {
  stop-color: var(--svg-color--3e77d8, #3E77D8);
}

.l8yxupbpv {
  stop-color: var(--svg-color--e8a589, #E8A589);
}

.lbznaibos {
  width: 4.109px;
  height: 5.399px;
  x: 13.776px;
  y: 13.26px;
  rx: 2.055px;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lty0cjbuw {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
  stop-opacity: 0;
}

.m_iky2b5b {
  d: path("M13.644 9.564a.896.896 0 0 0-.863 1.132h1.73a1 1 0 0 0 .033-.236a.9.9 0 0 0-.9-.896");
}

.m55q8ispu {
  stop-color: var(--svg-color--dea088, #DEA088);
}

.m70pgaboa {
  stop-color: var(--svg-color--dfb086, #DFB086);
  stop-opacity: 0;
}

.mbfiytbde {
  stop-color: var(--svg-color--f6c09a, #F6C09A);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mjbwacbml {
  stop-color: var(--svg-color--286adf, #286ADF);
  stop-opacity: 0;
}

.mvigw0raw {
  stop-color: var(--svg-color--ddca94, #DDCA94);
}

.mzeokobes {
  stop-color: var(--svg-color--f04451, #F04451);
}

.n3fdoubpa {
  d: path("M15.875 15.6c-6.228 0-11.584 4.187-11.992 14.281v.036h23.984v-.036C27.46 19.787 22.103 15.6 15.875 15.6");
}

.nd6y13bdf {
  stop-color: var(--svg-color--d5a088, #D5A088);
}

.nlc0hsb0h {
  stop-color: var(--svg-color--c18385, #C18385);
}

.nr4jety8s {
  stop-color: var(--svg-color--ac695d, #AC695D);
  stop-opacity: 0;
}

.ntzydvb0y {
  fill: var(--svg-color--000, #000);
  d: path("M14.157 10.46a.51.51 0 0 0-.513-.513a.51.51 0 0 0-.456.749h.908a.5.5 0 0 0 .06-.236");
}

.o1dxquboz {
  stop-color: var(--svg-color--c48062, #C48062);
}

.o1uobmugz {
  stop-color: var(--svg-color--c31251, #C31251);
}

.o2ztw4w4i {
  stop-color: var(--svg-color--f0b89b, #F0B89B);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofjdtziny {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
}

.oj7ch-bkx {
  stop-color: var(--svg-color--528adb, #528ADB);
  stop-opacity: 0;
}

.ok5u1w3sx {
  d: path("M8.227 18.43v11.487H3.883v-.036c.22-5.448 1.882-9.175 4.344-11.452");
}

.onbz4ubrj {
  stop-color: var(--svg-color--ba3950, #BA3950);
  stop-opacity: 0;
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.otqjsqgnm {
  stop-color: var(--svg-color--f6c546, #F6C546);
  stop-opacity: 0;
}

.ova749bei {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.436 9.291c-.655 0-1.209.452-1.36 1.063a.275.275 0 0 0 .27.342h2.238a.23.23 0 0 0 .228-.273a1.406 1.406 0 0 0-1.376-1.132");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmf-vsdxp {
  stop-color: var(--svg-color--4d87f8, #4D87F8);
}

.ps9y5f8nd {
  stop-color: var(--svg-color--9f646d, #9F646D);
}

.pswg0plle {
  stop-color: var(--svg-color--c99175, #C99175);
  stop-opacity: 0;
}

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.q37q-zblj {
  stop-color: var(--svg-color--e7c991, #E7C991);
}

.qhzdg_bmj {
  stop-color: var(--svg-color--f04451, #F04451);
  stop-opacity: 0;
}

.qqmscub7d {
  stop-color: var(--svg-color--f3b79b, #F3B79B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_kuisbux {
  stop-color: var(--svg-color--ecb591, #ECB591);
}

.r0f0npb-q {
  stop-color: var(--svg-color--ffed93, #FFED93);
  stop-opacity: 0;
}

.r3949-bju {
  stop-color: var(--svg-color--4690e6, #4690E6);
}

.r8_iis6dl {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.96 9.754c.064.085-.069.189-.22.302c-.152.113-.264.193-.328.108c-.063-.085.008-.246.16-.36c.15-.113.325-.136.389-.05");
}

.rk366-b7y {
  stop-color: var(--svg-color--dfb086, #DFB086);
}

.rn540obxc {
  stop-color: var(--svg-color--ee344d, #EE344D);
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rqcot095h {
  stop-color: var(--svg-color--c31852, #C31852);
}

.rr64b4bjv {
  stop-color: var(--svg-color--e1b395, #E1B395);
}

.rzgix9n0j {
  cx: 20.57px;
  cy: 10.662px;
  r: 1.146px;
}

.s9sui_61e {
  stop-color: var(--svg-color--3e75e1, #3E75E1);
}

.shdn2-1cj {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.836 13.87c-.51 0-.988-.12-1.39-.33c-.138-.07-.286.085-.2.21a1.9 1.9 0 0 0 1.59.848a1.9 1.9 0 0 0 1.589-.849c.086-.13-.061-.28-.199-.21a3 3 0 0 1-1.39.33Z");
}

.su-lx9b4e {
  stop-color: var(--svg-color--fff14e, #FFF14E);
}

.t-ehpbubw {
  stop-color: var(--svg-color--3062ac, #3062AC);
}

.t1qc5-b8a {
  stop-color: var(--svg-color--e4b78d, #E4B78D);
  stop-opacity: 0;
}

.t1w2v13iw {
  cx: 11.101px;
  cy: 10.662px;
  r: 1.146px;
}

.tmhk4ybst {
  stop-color: var(--svg-color--ddca94, #DDCA94);
  stop-opacity: 0;
}

.tyjpv6bnm {
  stop-color: var(--svg-color--790b2c, #790B2C);
}

.u_i25-byi {
  fill: var(--svg-color--89024e, #89024E);
  d: path("M15.836 13.87c-.51 0-.988-.12-1.39-.33c-.138-.07-.286.085-.2.21a1.9 1.9 0 0 0 1.59.848a1.9 1.9 0 0 0 1.589-.849c.086-.13-.061-.28-.199-.21a3 3 0 0 1-1.39.33");
}

.ugkkbdcpr {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
}

.uhnyo9buy {
  stop-color: var(--svg-color--f7bf94, #F7BF94);
}

.ujtti6ofv {
  stop-color: var(--svg-color--2154ca, #2154CA);
}

.umjrh49bx {
  stop-color: var(--svg-color--ce1f66, #CE1F66);
}

.unyz2nb7v {
  fill: var(--svg-color--000, #000);
  d: path("M17.515 10.46a.51.51 0 0 1 .513-.513a.51.51 0 0 1 .456.749h-.908a.46.46 0 0 1-.061-.236");
}

.urt-asbls {
  d: path("M10.845 11.277h.362q.279 0 .529.12l.244.12c.089.04.177.08.265.11l.215.07c.42.13.87.14 1.292.02l.274-.08c.107-.03.215-.07.313-.12l.225-.11q.249-.12.528-.12h.06l.283-.94a.402.402 0 0 1 .773 0l.284.94h.039q.279 0 .528.12l.206.1c.107.05.225.1.342.13l.304.09c.42.12.88.11 1.291-.04l.176-.06l.235-.09l.265-.12q.249-.12.528-.12h.43q.081-1.33.148-2.66h-.48c-.245-.02-.49-.1-.705-.24l-.049-.03a2.2 2.2 0 0 0-.548-.28a2.1 2.1 0 0 0-1.291-.04l-.128.03c-.235.07-.46.17-.665.32s-.45.22-.705.22H15.2c-.254 0-.5-.08-.705-.22l-.01-.01a2.2 2.2 0 0 0-.635-.31l-.088-.03a2.2 2.2 0 0 0-1.292.02l-.04.01c-.205.07-.4.17-.586.29l-.03.03c-.215.14-.46.22-.714.22h-.343c.009.89.042 1.774.088 2.66");
}

.urt8mz7mv {
  stop-color: var(--svg-color--ac695d, #AC695D);
}

.utkdp49kv {
  d: path("m15.836 20.397l-5.04-3.024c-.323-.199-.663-.512-.663-.98c0-.496.584-.533.885-.543l4.818-.078l4.818.078c.3.01.885.047.885.543c0 .468-.34.781-.664.98z");
}

.v2ucwt3jq {
  stop-color: var(--svg-color--49a3ff, #49A3FF);
  stop-opacity: 0;
}

.vbey9csnv {
  fill: var(--svg-color--dca283, #DCA283);
  d: path("m15.452 10.245l-.533 1.845c-.11.38.152.759.522.759h.79c.37 0 .63-.385.522-.76l-.534-1.844c-.114-.409-.647-.409-.767 0");
}

.vj4yuc0qg {
  stop-color: var(--svg-color--614440, #614440);
}

.w08v59e9w {
  stop-color: var(--svg-color--f3b79b, #F3B79B);
  stop-opacity: 0;
}

.w6_8my7ls {
  stop-color: var(--svg-color--4b99ff, #4B99FF);
  stop-opacity: 0;
}

.wbaoi1vzd {
  stop-color: var(--svg-color--fff6b9, #FFF6B9);
}

.wjwn33b7s {
  stop-color: var(--svg-color--eab197, #EAB197);
}

.wn7157b9l {
  stop-color: var(--svg-color--3d71ed, #3D71ED);
  stop-opacity: 0;
}

.wx3vdcbzg {
  stop-color: var(--svg-color--407dbe, #407DBE);
  stop-opacity: 0;
}

.x_0jnxbib {
  stop-color: var(--svg-color--3d71ed, #3D71ED);
}

.x39b-tbnv {
  stop-color: var(--svg-color--e1a18f, #E1A18F);
}

.x5037tbuk {
  stop-color: var(--svg-color--d39c8e, #D39C8E);
}

.x8ej_jb7y {
  stop-color: var(--svg-color--286adf, #286ADF);
}

.xd0kopb5v {
  stop-color: var(--svg-color--bf2370, #BF2370);
  stop-opacity: 0;
}

.xeef6mbed {
  d: path("M14.462 10.354c0-.29-.236-.482-.3-.54l-.288.28l.178.362z");
}

.xq6nvzqsi {
  d: path("M3.344 29.863c0-1.887.355-6.479 2.92-9.45c3.207-3.715 7.732-4.269 9.736-4.269s6.529.555 9.736 4.269c2.565 2.971 2.92 7.563 2.92 9.45z");
}

.xyu2htzlq {
  stop-color: var(--svg-color--790b2c, #790B2C);
  stop-opacity: 0;
}

.y3fq4efvh {
  stop-color: var(--svg-color--e7b286, #E7B286);
  stop-opacity: 0;
}

.y8t70hbxb {
  stop-color: var(--svg-color--c58371, #C58371);
}

.y9rlcreuk {
  stop-color: var(--svg-color--bf2370, #BF2370);
}

.yd6vs-kvu {
  stop-color: var(--svg-color--543f3c, #543F3C);
}

.ys50rfypm {
  stop-color: var(--svg-color--e69d7f, #E69D7F);
}

.ytx-8cb1b {
  stop-color: var(--svg-color--e7b286, #E7B286);
}

.yxlean3rw {
  d: path("M10.957 12.217a1.65 1.65 0 0 1-.908-.31v.934a2.18 2.18 0 0 0 1.346 2.026a4.1 4.1 0 0 1-.347-1.184z");
}

.z12l7tb2s {
  stop-color: var(--svg-color--f0b89b, #F0B89B);
}

.z14dz9exi {
  stop-color: var(--svg-color--ff1781, #FF1781);
}

.z45w8t_um {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
}

.zb_y65bxb {
  stop-color: var(--svg-color--eab197, #EAB197);
  stop-opacity: 0;
}

.zbo4__e4e {
  stop-color: var(--svg-color--3f83f1, #3F83F1);
}

.zmfxcpbii {
  stop-color: var(--svg-color--e3b593, #E3B593);
}

.znwnmpxvd {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
  stop-opacity: 0;
}

.zu5-vd24j {
  d: path("M23.523 18.43v11.487h4.344v-.036c-.22-5.448-1.882-9.175-4.344-11.452");
}

</style>
