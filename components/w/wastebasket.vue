<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iZH9yoa)"><path fill="url(#iJtCe4f)" class="yozoco5nl"/><path fill="url(#iUo5XFc)" class="yozoco5nl"/></g><path fill="url(#i6LhZpb)" class="yozoco5nl"/><path fill="url(#is4mEqO)" class="yozoco5nl"/><path fill="url(#iCsB8PB)" class="yozoco5nl"/><path fill="url(#iilUCad)" class="yozoco5nl"/><g filter="url(#iwrj59b)"><path fill="url(#iuiIgDe)" class="mozzehbxx"/><path fill="url(#igWA3iD)" class="mozzehbxx"/></g><path fill="url(#imXQBiG)" class="mozzehbxx"/><path fill="url(#iQPzfCJ)" class="mozzehbxx"/><path fill="url(#iLbFr7c)" class="mozzehbxx"/><path fill="url(#iUFYbxc)" class="mozzehbxx"/><path fill="url(#iNrSuNd)" class="mozzehbxx"/><g filter="url(#iF7XyGe)"><path fill="url(#iCSgMgx)" class="suayr7bwz"/></g><path fill="url(#ieQOnuZ)" class="suayr7bwz"/><path fill="url(#iakJNyc)" class="suayr7bwz"/><path fill="url(#ilGoFKe)" class="suayr7bwz"/><g filter="url(#iY8zdHd)"><path fill="url(#i0GfsOd)" class="fxa0rvb-m"/></g><path fill="url(#iWlHGGb)" class="fxa0rvb-m"/><path fill="url(#i7jJBWc)" class="fxa0rvb-m"/><path fill="url(#ikKC4Bb)" class="fxa0rvb-m"/><g filter="url(#iPstDte)"><path fill="url(#iVmon4o)" class="gd187ybfz"/></g><path fill="url(#inMJR2x)" class="gd187ybfz"/><path fill="url(#iKNjSPe)" class="gd187ybfz"/><g filter="url(#ie4evXc)"><path fill="url(#iolpwee)" class="s51kjac-b"/></g><path fill="url(#in2cDXb)" class="s51kjac-b"/><path fill="url(#ivLXr7c)" class="s51kjac-b"/><g filter="url(#ifKQ8fb)"><path fill="url(#ixY2Uwb)" class="uzn9e8ujc"/></g><path fill="url(#iRtjfVI)" class="uzn9e8ujc"/><g filter="url(#iLRoDte)"><path fill="url(#iKRMxCp)" class="bmnp8kb4f"/></g><path fill="url(#iWBu2rc)" class="bmnp8kb4f"/><path fill="url(#iSluiSu)" class="bmnp8kb4f"/><g filter="url(#i9YFI3c)"><path fill="url(#iGOcdNc)" class="twqetuoqx"/><path fill="url(#iglwpCc)" class="twqetuoqx"/><path fill="url(#imdxaee)" class="twqetuoqx"/></g><g filter="url(#irM153c)"><path fill="url(#iWEjV3b)" class="eehk-wvrd"/><path fill="url(#iHLfJie)" class="eehk-wvrd"/></g><g filter="url(#iTAKFXd)"><rect class="uvtof7duf"/></g><g filter="url(#iJcU7yb)"><rect class="jaz-9uikm"/></g><rect fill="url(#i4Lorcb)" class="la8rcntqa"/><g filter="url(#iI6Xkie)"><path fill="url(#iNafuzp)" class="qhn0mmbns"/></g><g filter="url(#iQNbxHc)"><path fill="url(#ire2RVc)" class="k5jxbiilh"/></g><defs><linearGradient id="iJtCe4f" x1="25.25" x2="12.632" y1="3.991" y2="26.976" gradientUnits="userSpaceOnUse"><stop class="vim1peb5t"/><stop offset="1" class="yn482gb4a"/><stop offset="1" class="mhzvbqbkm"/></linearGradient><linearGradient id="i6LhZpb" x1="24.469" x2="23.625" y1="4.531" y2="8.219" gradientUnits="userSpaceOnUse"><stop offset=".333" class="fvi9yy8bg"/><stop offset="1" class="ky7m56bnl"/></linearGradient><linearGradient id="iuiIgDe" x1="19.157" x2="6.902" y1="3.991" y2="26.314" gradientUnits="userSpaceOnUse"><stop class="vim1peb5t"/><stop offset="1" class="wuz1o1cig"/></linearGradient><linearGradient id="imXQBiG" x1="18.387" x2="17.538" y1="4.51" y2="8.092" gradientUnits="userSpaceOnUse"><stop offset=".333" class="rxi3h3-at"/><stop offset="1" class="uglf2bbgv"/></linearGradient><linearGradient id="iNrSuNd" x1="8" x2="10.625" y1="24.375" y2="22.875" gradientUnits="userSpaceOnUse"><stop offset=".121" class="fyh41zbvb"/><stop offset="1" class="jckcj1bxm"/></linearGradient><linearGradient id="iCSgMgx" x1="12.875" x2="7.719" y1="5.938" y2="14.25" gradientUnits="userSpaceOnUse"><stop class="bk_ru6bry"/><stop offset="1" class="nkdng7qin"/></linearGradient><linearGradient id="iakJNyc" x1="7.688" x2="8.563" y1="14.375" y2="13.938" gradientUnits="userSpaceOnUse"><stop offset=".171" class="uq7q-vq6u"/><stop offset="1" class="jy2stbz6v"/></linearGradient><linearGradient id="ilGoFKe" x1="13.313" x2="11.719" y1="5.438" y2="7.344" gradientUnits="userSpaceOnUse"><stop offset=".341" class="a-qlbbcka"/><stop offset="1" class="vr9nb1a1d"/></linearGradient><linearGradient id="i0GfsOd" x1="25.469" x2="20.656" y1="16.625" y2="25.688" gradientUnits="userSpaceOnUse"><stop class="qdq5kvbux"/><stop offset="1" class="abvsvvbmh"/></linearGradient><linearGradient id="iWlHGGb" x1="25.281" x2="23.531" y1="18.719" y2="18.344" gradientUnits="userSpaceOnUse"><stop offset=".401" class="a020o9b3h"/><stop offset="1" class="x8-9_uoqy"/></linearGradient><linearGradient id="i7jJBWc" x1="25.406" x2="24.031" y1="15.656" y2="16.609" gradientUnits="userSpaceOnUse"><stop offset=".643" class="d1h58x5_m"/><stop offset="1" class="ju2oc3prk"/></linearGradient><linearGradient id="iVmon4o" x1="7.938" x2="20.251" y1="7.125" y2="28.171" gradientUnits="userSpaceOnUse"><stop class="e0xbnjooe"/><stop offset=".454" class="sv68m5bdw"/><stop offset="1" class="mhps47bgq"/></linearGradient><linearGradient id="inMJR2x" x1="7.39" x2="8.649" y1="4.743" y2="7.735" gradientUnits="userSpaceOnUse"><stop offset=".264" class="abuznbbyg"/><stop offset="1" class="aw0c3hbdq"/></linearGradient><linearGradient id="iKNjSPe" x1="20.405" x2="18.942" y1="26.303" y2="24.184" gradientUnits="userSpaceOnUse"><stop class="id64ywl4u"/><stop offset="1" class="a6jvbvbzn"/></linearGradient><linearGradient id="iolpwee" x1="12.695" x2="25.313" y1="3.28" y2="26.265" gradientUnits="userSpaceOnUse"><stop class="osxxlnbzp"/><stop offset=".607" class="yn482gb4a"/></linearGradient><linearGradient id="in2cDXb" x1="24.011" x2="22.681" y1="23.043" y2="22.802" gradientUnits="userSpaceOnUse"><stop offset=".176" class="ub2r41b3h"/><stop offset="1" class="fvf_lxdui"/></linearGradient><linearGradient id="ivLXr7c" x1="13.781" x2="13.781" y1="4.688" y2="6.781" gradientUnits="userSpaceOnUse"><stop offset=".47" class="t4a8kibra"/><stop offset="1" class="fnd_74mpj"/></linearGradient><linearGradient id="ixY2Uwb" x1="5.672" x2="9.767" y1="13.033" y2="23.458" gradientUnits="userSpaceOnUse"><stop class="c1qou8bsy"/><stop offset="1" class="bt-m4sbvq"/></linearGradient><linearGradient id="iRtjfVI" x1="7.063" x2="9" y1="16.563" y2="16.5" gradientUnits="userSpaceOnUse"><stop offset=".047" class="qa420zbuo"/><stop offset="1" class="ev_z6vbec"/></linearGradient><linearGradient id="iKRMxCp" x1="20.938" x2="25.454" y1="5.969" y2="14.027" gradientUnits="userSpaceOnUse"><stop class="hzd12yb0c"/><stop offset="1" class="s65u6g_qp"/></linearGradient><linearGradient id="iWBu2rc" x1="21.925" x2="21.824" y1="5.457" y2="6.835" gradientUnits="userSpaceOnUse"><stop offset=".323" class="uzl_c7b4e"/><stop offset="1" class="m2qb30bkj"/></linearGradient><linearGradient id="iSluiSu" x1="25.125" x2="24.469" y1="16.313" y2="16.281" gradientUnits="userSpaceOnUse"><stop offset=".097" class="qtiu5db5m"/><stop offset="1" class="ae93yobre"/></linearGradient><linearGradient id="iGOcdNc" x1="24.563" x2="27.75" y1="16.738" y2="17.156" gradientUnits="userSpaceOnUse"><stop offset=".082" class="p0tyhe6cx"/><stop offset="1" class="rgyp9gbva"/></linearGradient><linearGradient id="iWEjV3b" x1="5.188" x2="7.813" y1="19.688" y2="19.438" gradientUnits="userSpaceOnUse"><stop offset=".082" class="p0tyhe6cx"/><stop offset="1" class="rgyp9gbva"/></linearGradient><linearGradient id="i4Lorcb" x1="18.938" x2="18.938" y1="29.922" y2="29" gradientUnits="userSpaceOnUse"><stop class="cofa07gce"/><stop offset="1" class="pab10rkhy"/></linearGradient><linearGradient id="iNafuzp" x1="28.407" x2="-.589" y1="3.468" y2="3.468" gradientUnits="userSpaceOnUse"><stop class="a7hc63boh"/><stop offset="1" class="n-euxibfe"/></linearGradient><linearGradient id="ire2RVc" x1="25.695" x2="2.279" y1="27.594" y2="27.594" gradientUnits="userSpaceOnUse"><stop class="a7hc63boh"/><stop offset="1" class="n-euxibfe"/></linearGradient><filter id="iZH9yoa" width="15.163" height="23.697" x="11.323" y="3.173" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.631373 0 0 0 0 0.627451 0 0 0 0 0.643137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23461"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.796078 0 0 0 0 0.780392 0 0 0 0 0.835294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23461" result="effect2_innerShadow_18_23461"/></filter><filter id="iwrj59b" width="14.717" height="23.697" x="5.675" y="3.173" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.580392 0 0 0 0 0.576471 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23461"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.603922 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23461" result="effect2_innerShadow_18_23461"/></filter><filter id="iF7XyGe" width="8.743" height="16.098" x="5.696" y="3.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.52549 0 0 0 0 0.521569 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23461"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.588235 0 0 0 0 0.698039 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23461" result="effect2_innerShadow_18_23461"/></filter><filter id="iY8zdHd" width="11.313" height="20.231" x="16.753" y="7.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.886275 0 0 0 0 0.92549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23461"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.541176 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23461" result="effect2_innerShadow_18_23461"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.901961 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_23461" result="effect3_innerShadow_18_23461"/></filter><filter id="iPstDte" width="15.405" height="23.837" x="6.154" y="3.925" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.619608 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23461"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.898039 0 0 0 0 0.945098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23461" result="effect2_innerShadow_18_23461"/></filter><filter id="ie4evXc" width="15.163" height="23.697" x="11.459" y="2.463" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.662745 0 0 0 0 0.631373 0 0 0 0 0.737255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23461"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.87451 0 0 0 0 0.921569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23461" result="effect2_innerShadow_18_23461"/></filter><filter id="ifKQ8fb" width="11.547" height="20.741" x="4.899" y="8.803" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.498039 0 0 0 0 0.478431 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23461"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.85098 0 0 0 0 0.898039 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23461" result="effect2_innerShadow_18_23461"/></filter><filter id="iLRoDte" width="8.172" height="13.687" x="18.273" y="4.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.639216 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23461"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.776471 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23461" result="effect2_innerShadow_18_23461"/></filter><filter id="i9YFI3c" width="6.281" height="23.086" x="23.09" y="5.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.470588 0 0 0 0 0.529412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23461"/></filter><filter id="irM153c" width="6.281" height="23.086" x="2.863" y="4.039" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.470588 0 0 0 0 0.529412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23461"/></filter><filter id="iTAKFXd" width="28.556" height="4.891" x="2.047" y="1.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.631373 0 0 0 0 0.596078 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23461"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.552941 0 0 0 0 0.509804 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23461" result="effect2_innerShadow_18_23461"/></filter><filter id="iJcU7yb" width="22.744" height="4.891" x="4.953" y="25.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.631373 0 0 0 0 0.596078 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23461"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.552941 0 0 0 0 0.509804 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23461" result="effect2_innerShadow_18_23461"/></filter><filter id="iI6Xkie" width="25.338" height="2.814" x="4.663" y="2.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23461" stdDeviation=".375"/></filter><filter id="iQNbxHc" width="20.75" height="2.814" x="6.376" y="26.187" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23461" stdDeviation=".375"/></filter><radialGradient id="iUo5XFc" cx="0" cy="0" r="1" gradientTransform="matrix(2.25 1.5 -10.2988 15.44817 17.031 14.969)" gradientUnits="userSpaceOnUse"><stop class="ju_ufwk3g"/><stop offset="1" class="mwvi1abkj"/></radialGradient><radialGradient id="is4mEqO" cx="0" cy="0" r="1" gradientTransform="rotate(154.564 9.767 8.017)scale(1.41878 8.71757)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="nja-qfokk"/><stop offset="1" class="wocpbox2r"/></radialGradient><radialGradient id="iCsB8PB" cx="0" cy="0" r="1" gradientTransform="rotate(151.238 7.411 10.46)scale(2.14323 13.1689)" gradientUnits="userSpaceOnUse"><stop offset=".237" class="nja-qfokk"/><stop offset="1" class="wocpbox2r"/></radialGradient><radialGradient id="iilUCad" cx="0" cy="0" r="1" gradientTransform="rotate(152.488 5.309 12.545)scale(1.69126 10.3918)" gradientUnits="userSpaceOnUse"><stop offset=".402" class="nja-qfokk"/><stop offset="1" class="wocpbox2r"/></radialGradient><radialGradient id="igWA3iD" cx="0" cy="0" r="1" gradientTransform="rotate(122.412 5.108 10.437)scale(11.6603 4.2035)" gradientUnits="userSpaceOnUse"><stop class="tfdlsib7z"/><stop offset="1" class="tbtqpx75z"/></radialGradient><radialGradient id="iQPzfCJ" cx="0" cy="0" r="1" gradientTransform="rotate(155.362 6.836 7.185)scale(1.39203 8.62914)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="nja-qfokk"/><stop offset="1" class="wocpbox2r"/></radialGradient><radialGradient id="iLbFr7c" cx="0" cy="0" r="1" gradientTransform="rotate(152.002 4.559 9.484)scale(2.09947 13.056)" gradientUnits="userSpaceOnUse"><stop offset=".237" class="nja-qfokk"/><stop offset="1" class="wocpbox2r"/></radialGradient><radialGradient id="iUFYbxc" cx="0" cy="0" r="1" gradientTransform="rotate(153.266 2.533 11.548)scale(1.6577 10.2967)" gradientUnits="userSpaceOnUse"><stop offset=".402" class="nja-qfokk"/><stop offset="1" class="wocpbox2r"/></radialGradient><radialGradient id="ieQOnuZ" cx="0" cy="0" r="1" gradientTransform="matrix(1.0107 -.53104 1.57029 2.9886 10.446 8.523)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="d5z5ef_uj"/><stop offset="1" class="sg274j6zd"/></radialGradient><radialGradient id="ikKC4Bb" cx="0" cy="0" r="1" gradientTransform="rotate(151.699 8.197 13.79)scale(1.1535 6.30088)" gradientUnits="userSpaceOnUse"><stop offset=".33" class="jqo2n6bya"/><stop offset="1" class="m5yze9bat"/></radialGradient><radialGradient id="iglwpCc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.01557 21.87502 -1.73854 -.23967 29.12 5.875)" gradientUnits="userSpaceOnUse"><stop class="jby0r9b2o"/><stop offset="1" class="efjg-ybdf"/></radialGradient><radialGradient id="imdxaee" cx="0" cy="0" r="1" gradientTransform="matrix(-5.3789 2.5 -.56356 -1.21253 28.469 5)" gradientUnits="userSpaceOnUse"><stop offset=".331" class="hg37rv3_z"/><stop offset="1" class="u_kyqo_tx"/></radialGradient><radialGradient id="iHLfJie" cx="0" cy="0" r="1" gradientTransform="matrix(5.3789 2.5 -.56356 1.21253 3.516 3.969)" gradientUnits="userSpaceOnUse"><stop offset=".331" class="hg37rv3_z"/><stop offset="1" class="u_kyqo_tx"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:wastebasket" /></template>
<style>
.a-qlbbcka {
  stop-color: var(--svg-color--9186a9, #9186A9);
}

.a020o9b3h {
  stop-color: var(--svg-color--797487, #797487);
}

.a6jvbvbzn {
  stop-color: var(--svg-color--d0cfd3, #D0CFD3);
  stop-opacity: 0;
}

.a7hc63boh {
  stop-color: var(--svg-color--dfdee3, #DFDEE3);
}

.abuznbbyg {
  stop-color: var(--svg-color--867e98, #867E98);
}

.abvsvvbmh {
  stop-color: var(--svg-color--e6e4ed, #E6E4ED);
}

.ae93yobre {
  stop-color: var(--svg-color--d9d5e2, #D9D5E2);
  stop-opacity: 0;
}

.aw0c3hbdq {
  stop-color: var(--svg-color--867e98, #867E98);
  stop-opacity: 0;
}

.bk_ru6bry {
  stop-color: var(--svg-color--a098b3, #A098B3);
}

.bmnp8kb4f {
  d: path("M18.473 5.378v-.472h2.61l5.162 9.42l-.782 3.867z");
}

.bt-m4sbvq {
  stop-color: var(--svg-color--bfbcc7, #BFBCC7);
}

.c1qou8bsy {
  stop-color: var(--svg-color--a19dac, #A19DAC);
}

.cofa07gce {
  stop-color: var(--svg-color--9881bb, #9881BB);
}

.d1h58x5_m {
  stop-color: var(--svg-color--726a85, #726A85);
}

.d5z5ef_uj {
  stop-color: var(--svg-color--868489, #868489);
}

.e0xbnjooe {
  stop-color: var(--svg-color--ada8ba, #ADA8BA);
}

.eehk-wvrd {
  d: path("m2.863 4.328l3.125-.039l2.907 22.797l-3.125.039z");
}

.efjg-ybdf {
  stop-color: var(--svg-color--cfcbd9, #CFCBD9);
  stop-opacity: 0;
}

.ev_z6vbec {
  stop-color: var(--svg-color--8f8d97, #8F8D97);
  stop-opacity: 0;
}

.fnd_74mpj {
  stop-color: var(--svg-color--c8c2d8, #C8C2D8);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fvf_lxdui {
  stop-color: var(--svg-color--c7c3d1, #C7C3D1);
  stop-opacity: 0;
}

.fvi9yy8bg {
  stop-color: var(--svg-color--776d8c, #776D8C);
}

.fxa0rvb-m {
  d: path("M27.766 7.863L16.953 27.594h2.9l7.283-13.353z");
}

.fyh41zbvb {
  stop-color: var(--svg-color--9b98a1, #9B98A1);
}

.gd187ybfz {
  d: path("m6.354 5.382l2.162-1.257l12.843 23.438l-2.984-.141z");
}

.hg37rv3_z {
  stop-color: var(--svg-color--797090, #797090);
}

.hzd12yb0c {
  stop-color: var(--svg-color--c4bfd1, #C4BFD1);
}

.id64ywl4u {
  stop-color: var(--svg-color--d0cfd3, #D0CFD3);
}

.jaz-9uikm {
  width: 22.344px;
  height: 3.891px;
  x: 4.953px;
  y: 26.031px;
  fill: var(--svg-color--cccbcd, #CCCBCD);
  rx: 1.945px;
}

.jby0r9b2o {
  stop-color: var(--svg-color--cfcbd9, #CFCBD9);
}

.jckcj1bxm {
  stop-color: var(--svg-color--9b98a1, #9B98A1);
  stop-opacity: 0;
}

.jqo2n6bya {
  stop-color: var(--svg-color--857d98, #857D98);
}

.ju_ufwk3g {
  stop-color: var(--svg-color--e6e2f1, #E6E2F1);
}

.ju2oc3prk {
  stop-color: var(--svg-color--726a85, #726A85);
  stop-opacity: 0;
}

.jy2stbz6v {
  stop-color: var(--svg-color--908e95, #908E95);
  stop-opacity: 0;
}

.k5jxbiilh {
  d: path("M7.126 26.937h18.593a.657.657 0 1 1 0 1.314H7.126z");
}

.ky7m56bnl {
  stop-color: var(--svg-color--a7a0b6, #A7A0B6);
  stop-opacity: 0;
}

.la8rcntqa {
  width: 22.344px;
  height: 3.891px;
  x: 4.953px;
  y: 26.031px;
  rx: 1.945px;
}

.m2qb30bkj {
  stop-color: var(--svg-color--c6c1d3, #C6C1D3);
  stop-opacity: 0;
}

.m5yze9bat {
  stop-color: var(--svg-color--bebac8, #BEBAC8);
  stop-opacity: 0;
}

.mhps47bgq {
  stop-color: var(--svg-color--d6d3e0, #D6D3E0);
}

.mhzvbqbkm {
  stop-color: var(--svg-color--d5d2df, #D5D2DF);
}

.mozzehbxx {
  d: path("M20.193 4.63L18.03 3.373L5.875 25.75l2.296.92z");
}

.mwvi1abkj {
  stop-color: var(--svg-color--e6e2f1, #E6E2F1);
  stop-opacity: 0;
}

.n-euxibfe {
  stop-color: var(--svg-color--c8c7cd, #C8C7CD);
  stop-opacity: 0;
}

.nja-qfokk {
  stop-color: var(--svg-color--847a97, #847A97);
}

.nkdng7qin {
  stop-color: var(--svg-color--b4afc0, #B4AFC0);
}

.osxxlnbzp {
  stop-color: var(--svg-color--c5c0d4, #C5C0D4);
}

.p0tyhe6cx {
  stop-color: var(--svg-color--b2aebd, #B2AEBD);
}

.pab10rkhy {
  stop-color: var(--svg-color--a899c7, #A899C7);
  stop-opacity: 0;
}

.qa420zbuo {
  stop-color: var(--svg-color--8f8d97, #8F8D97);
}

.qdq5kvbux {
  stop-color: var(--svg-color--c2bece, #C2BECE);
}

.qhn0mmbns {
  d: path("M5.413 2.811h23.181a.657.657 0 1 1 0 1.314H5.413z");
}

.qtiu5db5m {
  stop-color: var(--svg-color--69676e, #69676E);
}

.rgyp9gbva {
  stop-color: var(--svg-color--d2cedc, #D2CEDC);
}

.rxi3h3-at {
  stop-color: var(--svg-color--80759b, #80759B);
}

.s51kjac-b {
  d: path("m11.659 3.92l2.161-1.257l12.602 22.993l-2.742.303z");
}

.s65u6g_qp {
  stop-color: var(--svg-color--d9d5e2, #D9D5E2);
}

.sg274j6zd {
  stop-color: var(--svg-color--a49db7, #A49DB7);
  stop-opacity: 0;
}

.suayr7bwz {
  d: path("m12.078 3.217l2.161 1.257l-7.876 14.441l-.467-4.418z");
}

.sv68m5bdw {
  stop-color: var(--svg-color--cec8de, #CEC8DE);
}

.t4a8kibra {
  stop-color: var(--svg-color--978fac, #978FAC);
}

.tbtqpx75z {
  stop-color: var(--svg-color--d3cde1, #D3CDE1);
  stop-opacity: 0;
}

.tfdlsib7z {
  stop-color: var(--svg-color--d3cde1, #D3CDE1);
}

.twqetuoqx {
  d: path("m29.121 5.36l-3.125-.04l-2.906 22.797l3.125.04z");
}

.u_kyqo_tx {
  stop-color: var(--svg-color--8c869c, #8C869C);
  stop-opacity: 0;
}

.ub2r41b3h {
  stop-color: var(--svg-color--8e8a99, #8E8A99);
}

.uglf2bbgv {
  stop-color: var(--svg-color--b2aac4, #B2AAC4);
  stop-opacity: 0;
}

.uq7q-vq6u {
  stop-color: var(--svg-color--908e95, #908E95);
}

.uvtof7duf {
  width: 28.156px;
  height: 3.891px;
  x: 2.047px;
  y: 2.031px;
  fill: var(--svg-color--cccbcd, #CCCBCD);
  rx: 1.945px;
}

.uzl_c7b4e {
  stop-color: var(--svg-color--7d758c, #7D758C);
}

.uzn9e8ujc {
  d: path("m5.1 14.238l8.162 14.965l2.984.14L5.099 9.004z");
}

.vim1peb5t {
  stop-color: var(--svg-color--b9b3c6, #B9B3C6);
}

.vr9nb1a1d {
  stop-color: var(--svg-color--9186a9, #9186A9);
  stop-opacity: 0;
}

.wocpbox2r {
  stop-color: var(--svg-color--d5cfe2, #D5CFE2);
  stop-opacity: 0;
}

.wuz1o1cig {
  stop-color: var(--svg-color--b6b3c0, #B6B3C0);
}

.x8-9_uoqy {
  stop-color: var(--svg-color--797487, #797487);
  stop-opacity: 0;
}

.yn482gb4a {
  stop-color: var(--svg-color--d8d3e4, #D8D3E4);
}

.yozoco5nl {
  d: path("m26.286 4.63l-2.161-1.257l-12.602 22.994l2.742.303z");
}

</style>
