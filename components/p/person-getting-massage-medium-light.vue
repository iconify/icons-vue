<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iR0VcZb)"><path fill="url(#iNaJQ8d)" class="dkva-0p2a"/><path fill="url(#iSwkn4c)" class="dkva-0p2a"/></g><path class="u0l2jtzsy"/><path fill="url(#idqFcZc)" class="h26e4sgsm"/><path fill="url(#ih0VgSb)" class="h26e4sgsm"/><g filter="url(#iTGmd3d)"><path class="rf58g5bum"/></g><path fill="url(#irCrUbe)" class="g5_ia9syq"/><circle fill="url(#ibgIxKe)" class="i7fnn1bcq"/><g filter="url(#ijqhhFG)" class="mc2zb0bvp"><circle class="zus2iac3j"/></g><circle fill="url(#is19MOb)" class="srcdcl_yh"/><circle fill="url(#iDijiyc)" class="srcdcl_yh"/><g filter="url(#izR0O9b)"><circle fill="url(#ii4bsMB)" class="nnet9bbrm"/></g><g filter="url(#id0hE8b)"><path fill="url(#iTGxvkc)" class="wkqd0hb4b"/></g><path fill="url(#iRpNJuI)" class="wkqd0hb4b"/><g filter="url(#iJHodYc)"><circle fill="url(#iceLCEe)" class="j0j5vybko"/></g><g filter="url(#ijOBBxb)"><path fill="url(#idrk1he)" class="vlr6nmb6w"/></g><g filter="url(#ikXl19u)"><path fill="url(#iXM9iwF)" class="ic-dvmxoa"/></g><g filter="url(#iEjQUYs)"><path class="j94fgem2b"/></g><g filter="url(#ihF0sXb)"><path stroke="url(#i4gkv7d)" class="ze6s0wf9k"/></g><g filter="url(#iJQ5zwe)"><path class="z5n052ywy"/></g><g filter="url(#irbVxxe)"><path stroke="url(#itRXXGe)" class="g-lz2-rad"/></g><path stroke="url(#igRrydb)" class="xjyo8kbbd"/><g filter="url(#iniHqgS)"><path stroke="url(#iQ6Joie)" class="wv6byccxz"/></g><path stroke="url(#i4QMqMd)" class="e4qmmebvg"/><g filter="url(#ia3Aakd)"><path stroke="url(#iLerBGe)" class="g3cj9mbqt"/></g><g filter="url(#idUs7Ce)"><path class="s7bsw33sf"/></g><path class="d-sq5_b-j"/><path fill="url(#idDE8Rn)" class="lln5h90we"/><path fill="url(#iYnmKjc)" class="lln5h90we"/><path fill="url(#i9gMoIy)" class="lln5h90we"/><g filter="url(#ifgiaLd)"><path stroke="url(#iZ8CAwc)" class="p4t0ota3q"/></g><path class="fe7el9-3d"/><g filter="url(#idTKihc)"><path class="gv40t8-iz"/><path fill="url(#iVg20bU)" class="am_6_g2wh"/><path fill="url(#iedgpzn)" class="am_6_g2wh"/></g><g filter="url(#ijAsJie)"><path fill="url(#itQHGwx)" class="kkqz5eb_f"/><path fill="url(#i0nYdgo)" class="kkqz5eb_f"/><path fill="url(#i2jWBhc)" class="kkqz5eb_f"/></g><g filter="url(#i5YPh3f)"><path fill="url(#iKZo7YD)" class="dj4m7-bab"/><path fill="url(#iWUeHMb)" class="dj4m7-bab"/></g><g filter="url(#iASEl7c)"><path class="r5m4p51to"/><path fill="url(#iJYc5Ud)" class="w5a3tprnu"/></g><g filter="url(#i8IJyfd)"><path class="htw-10p4r"/><path fill="url(#i6ADrgd)" class="ajvihphfe"/></g><g filter="url(#iHW4hId)"><path class="vpdouuqcq"/></g><g filter="url(#i9rpydd)"><path fill="url(#ix2SmCX)" class="jvs9aeb5c"/></g><g filter="url(#iIIFQxS)"><path fill="url(#i4oZVMb)" class="eh43pve_h"/></g><g filter="url(#iTTX6tc)"><path fill="url(#i2TMD1x)" class="fgf4_ac8o"/><path fill="url(#ihE7goc)" class="fgf4_ac8o"/></g><defs><radialGradient id="iNaJQ8d" cx="0" cy="0" r="1" gradientTransform="matrix(-18.0313 0 0 -12.0938 23.481 28.558)" gradientUnits="userSpaceOnUse"><stop class="zl8nqy82h"/><stop offset="1" class="yu799baro"/></radialGradient><radialGradient id="iSwkn4c" cx="0" cy="0" r="1" gradientTransform="matrix(-4.65628 -9.43744 11.80863 -5.8262 23.606 28.683)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="dwoq6zbym"/><stop offset="1" class="qmod-43sl"/></radialGradient><radialGradient id="idqFcZc" cx="0" cy="0" r="1" gradientTransform="rotate(142.016 5.147 14.718)scale(3.24973 2.31564)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="p74yltb2p"/><stop offset="1" class="i1uhwuuoc"/></radialGradient><radialGradient id="ih0VgSb" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.8125 -5.89395 3.25184 14.513 21.464)" gradientUnits="userSpaceOnUse"><stop class="qd2j91b8n"/><stop offset="1" class="d7slzly-q"/></radialGradient><radialGradient id="irCrUbe" cx="0" cy="0" r="1" gradientTransform="rotate(107.978 5.41 16.34)scale(2.69404 2.98344)" gradientUnits="userSpaceOnUse"><stop offset=".003" class="blcb75bhw"/><stop offset="1" class="saw93vs6k"/></radialGradient><radialGradient id="ibgIxKe" cx="0" cy="0" r="1" gradientTransform="rotate(46.621 -12.508 17.256)scale(2.88068)" gradientUnits="userSpaceOnUse"><stop class="eusqnibct"/><stop offset="1" class="hkkpz-bpt"/></radialGradient><radialGradient id="is19MOb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7615 .75741 -.7977 -.802 23.307 14.423)" gradientUnits="userSpaceOnUse"><stop class="kew95vbbt"/><stop offset="1" class="qmajx1z3l"/></radialGradient><radialGradient id="iDijiyc" cx="0" cy="0" r="1" gradientTransform="rotate(75.315 1.433 21.15)scale(2.34213)" gradientUnits="userSpaceOnUse"><stop offset=".798" class="bitta5b4f"/><stop offset="1" class="qfofjhlvk"/></radialGradient><radialGradient id="ii4bsMB" cx="0" cy="0" r="1" gradientTransform="matrix(.69531 0 0 .82031 21.666 14.83)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="eevz_mbba"/><stop offset="1" class="xtumd7buv"/></radialGradient><radialGradient id="iTGxvkc" cx="0" cy="0" r="1" gradientTransform="rotate(174.491 9.403 8.468)scale(6.18482 6.87814)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="k12aqibrq"/><stop offset="1" class="dfqtmwbvu"/></radialGradient><radialGradient id="iRpNJuI" cx="0" cy="0" r="1" gradientTransform="rotate(98.215 3.288 13.8)scale(9.91422 11.6571)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="qj0e2uhmt"/><stop offset="1" class="w8m6qxbxc"/></radialGradient><radialGradient id="iceLCEe" cx="0" cy="0" r="1" gradientTransform="matrix(.92789 -1.80184 1.99143 1.02552 13.366 14.187)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="n_pf1oy7u"/><stop offset=".902" class="e0nbxjblq"/></radialGradient><radialGradient id="idrk1he" cx="0" cy="0" r="1" gradientTransform="matrix(-1 3.6875 -3.2061 -.86946 20.885 9.269)" gradientUnits="userSpaceOnUse"><stop offset=".072" class="top4m_b9w"/><stop offset="1" class="gd06x8-mu"/></radialGradient><radialGradient id="iXM9iwF" cx="0" cy="0" r="1" gradientTransform="matrix(.8584 4.94563 -3.25037 .56416 11.073 9.519)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="ac4xzzbrr"/><stop offset="1" class="cpmy9wdkn"/></radialGradient><radialGradient id="igRrydb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 13.578 14.823)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="i6h5s3y2e"/><stop offset="1" class="r-0_iwkut"/></radialGradient><radialGradient id="i4QMqMd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 18.469 14.823)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="i6h5s3y2e"/><stop offset="1" class="r-0_iwkut"/></radialGradient><radialGradient id="iYnmKjc" cx="0" cy="0" r="1" gradientTransform="matrix(.19455 -1.08993 4.30797 .76898 16 17.003)" gradientUnits="userSpaceOnUse"><stop offset=".03" class="csb315wui"/><stop offset="1" class="c2okx_q2g"/></radialGradient><radialGradient id="i9gMoIy" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 .26563 16.541 16.204)" gradientUnits="userSpaceOnUse"><stop class="yp6fmsbhu"/><stop offset="1" class="ea054pq6c"/></radialGradient><radialGradient id="iZ8CAwc" cx="0" cy="0" r="1" gradientTransform="matrix(.20312 -.39063 1.75487 .91251 14.92 18.59)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="gl9j5ld5z"/><stop offset="1" class="b3ziilbku"/></radialGradient><radialGradient id="iVg20bU" cx="0" cy="0" r="1" gradientTransform="matrix(3.21191 -2.35933 .81977 1.116 11.473 6.026)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="eol8oh85h"/><stop offset="1" class="rkbi44biq"/></radialGradient><radialGradient id="iedgpzn" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75 -2.11178 1.39023 -1.15206 20.013 6.964)" gradientUnits="userSpaceOnUse"><stop class="kbotj-bvx"/><stop offset="1" class="wldo5sm4b"/></radialGradient><radialGradient id="i0nYdgo" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69202 -.32813 .16397 -.8455 15.983 6.689)" gradientUnits="userSpaceOnUse"><stop offset=".319" class="ls69o4b3v"/><stop offset="1" class="rq60-qb-m"/></radialGradient><radialGradient id="i2jWBhc" cx="0" cy="0" r="1" gradientTransform="matrix(-.79689 -2.51562 5.42206 -1.71758 13.669 8.23)" gradientUnits="userSpaceOnUse"><stop offset=".731" class="gfxjw2b6r"/><stop offset=".853" class="o6m_l6f4f"/></radialGradient><radialGradient id="iKZo7YD" cx="0" cy="0" r="1" gradientTransform="rotate(32.574 -4.662 35.8)scale(2.67 1.26933)" gradientUnits="userSpaceOnUse"><stop offset=".318" class="wyd3097rt"/><stop offset="1" class="j-io36bgr"/></radialGradient><radialGradient id="iWUeHMb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.27698 2.30148 -3.04643 -4.3377 19.396 6.561)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="f8hhmqb2i"/><stop offset="1" class="nsiq1yeca"/></radialGradient><radialGradient id="iJYc5Ud" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79686 -2.67189 1.32522 -.89122 11.81 10.683)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="xk4wwk53d"/><stop offset="1" class="b0gopucow"/></radialGradient><radialGradient id="i6ADrgd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.14314 -1.29371 0 22.518 1.879)" gradientUnits="userSpaceOnUse"><stop class="pra7rq0gk"/><stop offset="1" class="na9kkhbsz"/></radialGradient><radialGradient id="ix2SmCX" cx="0" cy="0" r="1" gradientTransform="matrix(5.8706 -6.28124 5.4446 5.08866 18.265 9.83)" gradientUnits="userSpaceOnUse"><stop class="zpoasobui"/><stop offset="1" class="ss3psybpi"/></radialGradient><radialGradient id="i2TMD1x" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.21875 .78125 0 11.01 6.36)" gradientUnits="userSpaceOnUse"><stop class="xms_-vb8m"/><stop offset="1" class="wj0_vcbzm"/><stop offset="1" class="dpgj0fl2i"/></radialGradient><radialGradient id="ihE7goc" cx="0" cy="0" r="1" gradientTransform="matrix(-.95862 -1.07283 .90655 -.81004 14.313 9.84)" gradientUnits="userSpaceOnUse"><stop offset=".187" class="cbcg1h21f"/><stop offset="1" class="ecsgmuy6m"/></radialGradient><filter id="iR0VcZb" width="21.451" height="8.965" x="5.649" y="21.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.262745 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24265"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.380392 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24265" result="effect2_innerShadow_3987_24265"/></filter><filter id="iTGmd3d" width="2.256" height="3.995" x="9.377" y="15.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.964706 0 0 0 0 0.745098 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24265"/></filter><filter id="ijqhhFG" width="2.986" height="2.986" x="9.111" y="13.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24265" stdDeviation=".1"/></filter><filter id="izR0O9b" width="2.986" height="2.986" x="19.904" y="13.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24265" stdDeviation=".1"/></filter><filter id="id0hE8b" width="12.252" height="14.898" x="10.124" y="7.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24265"/></filter><filter id="iJHodYc" width="3.829" height="3.829" x="11.609" y="11.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24265" stdDeviation=".25"/></filter><filter id="ijOBBxb" width="7.729" height="10.962" x="15.437" y="4.768" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24265" stdDeviation=".5"/></filter><filter id="ikXl19u" width="7.108" height="9.773" x="8.377" y="5.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24265" stdDeviation=".5"/></filter><filter id="iEjQUYs" width="2.699" height="1.214" x="11.797" y="11.814" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.270588 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24265"/></filter><filter id="ihF0sXb" width="2.399" height=".914" x="11.847" y="12.064" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24265" stdDeviation=".075"/></filter><filter id="iJQ5zwe" width="2.699" height="1.214" x="17.703" y="11.814" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.270588 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24265"/></filter><filter id="irbVxxe" width="2.399" height=".914" x="17.753" y="12.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24265" stdDeviation=".075"/></filter><filter id="iniHqgS" width="2.618" height=".92" x="12.269" y="14.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24265" stdDeviation=".075"/></filter><filter id="ia3Aakd" width="2.618" height=".92" x="17.16" y="14.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24265" stdDeviation=".075"/></filter><filter id="idUs7Ce" width="3.122" height="4.211" x="14.162" y="13.456" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24265" stdDeviation=".25"/></filter><filter id="ifgiaLd" width="4.199" height="1.729" x="13.906" y="17.358" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24265" stdDeviation=".05"/></filter><filter id="idTKihc" width="10.047" height="6.351" x="11.473" y="4.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.670588 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24265"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.827451 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24265" result="effect2_innerShadow_3987_24265"/></filter><filter id="ijAsJie" width="4.387" height="2.271" x="11.746" y="5.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24265" stdDeviation=".075"/></filter><filter id="i5YPh3f" width="4.219" height="4.689" x="15.869" y="5.333" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24265" stdDeviation=".125"/></filter><filter id="iASEl7c" width="6.686" height="12.903" x="8.599" y="1.826" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.592157 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24265"/></filter><filter id="i8IJyfd" width="6.436" height="12.953" x="17.239" y="1.776" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.541176 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24265"/></filter><filter id="iHW4hId" width="6.436" height="12.953" x="17.239" y="1.776" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.447059 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24265"/></filter><filter id="i9rpydd" width="5.843" height="12.292" x="17.83" y="2.067" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24265" stdDeviation=".25"/></filter><filter id="iIIFQxS" width="2.811" height="6.368" x="8.719" y="8.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24265" stdDeviation=".375"/></filter><filter id="iTTX6tc" width="5.14" height="8.355" x="9.673" y="1.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24265" stdDeviation=".25"/></filter><linearGradient id="i4gkv7d" x1="11.796" x2="14.021" y1="13.212" y2="12.289" gradientUnits="userSpaceOnUse"><stop class="tanu-rbxd"/><stop offset="1" class="sykku8w3p"/></linearGradient><linearGradient id="itRXXGe" x1="17.729" x2="19.928" y1="12.466" y2="12.534" gradientUnits="userSpaceOnUse"><stop class="tanu-rbxd"/><stop offset="1" class="sykku8w3p"/></linearGradient><linearGradient id="iQ6Joie" x1="14.936" x2="12.494" y1="14.229" y2="14.229" gradientUnits="userSpaceOnUse"><stop offset=".045" class="vmf5ti4hh"/><stop offset=".32" class="niae35b7q"/><stop offset=".794" class="lphhh6b5o"/><stop offset="1" class="ojzo1eq0m"/></linearGradient><linearGradient id="iLerBGe" x1="19.826" x2="17.385" y1="14.229" y2="14.229" gradientUnits="userSpaceOnUse"><stop offset=".045" class="vmf5ti4hh"/><stop offset=".32" class="niae35b7q"/><stop offset=".794" class="lphhh6b5o"/><stop offset="1" class="ojzo1eq0m"/></linearGradient><linearGradient id="idDE8Rn" x1="16.885" x2="15.848" y1="15.735" y2="15.785" gradientUnits="userSpaceOnUse"><stop offset=".106" class="y_s895zcx"/><stop offset="1" class="gd4v4obak"/></linearGradient><linearGradient id="itQHGwx" x1="13.573" x2="13.573" y1="7.801" y2="6.331" gradientUnits="userSpaceOnUse"><stop class="sxbetcb4w"/><stop offset="1" class="af8o06bmp"/></linearGradient><linearGradient id="i4oZVMb" x1="10.124" x2="10.124" y1="13.342" y2="8.511" gradientUnits="userSpaceOnUse"><stop class="ow5lwmmzq"/><stop offset="1" class="t4_yy204v"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-getting-massage-medium-light" /></template>
<style>
.ac4xzzbrr {
  stop-color: var(--svg-color--97523e, #97523E);
}

.af8o06bmp {
  stop-color: var(--svg-color--f0cb91, #F0CB91);
  stop-opacity: 0;
}

.ajvihphfe {
  d: path("M23.425 2.026h-3.426v3.742c0 .352-.227 1.035-.684 1.43a79 79 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .027 1.714c.453.429 1.09.362 1.554-.054l.978-.74a.527.527 0 0 1 .88.393v3.327a1.2 1.2 0 1 0 2.398 0z");
}

.am_6_g2wh {
  d: path("m12.387 5.628l-.914.773l.914 1.524h3.327c.115 0 .22.066.276.167c.105.19.285.489.53.833c.742 1.047 1.562.953 3.023.984c1.169.025 1.805.406 1.977.594V9.276L20.3 7.972V6.456c-.64-.86-1.202-1.281-1.655-1.445s-.98-.22-1.684-.078c-.563.112-.871.16-1.184.16c-.27 0-.557-.054-1.082-.16c-.832-.169-1.586.109-2.308.695");
}

.b0gopucow {
  stop-color: var(--svg-color--d39c86, #D39C86);
  stop-opacity: 0;
}

.b3ziilbku {
  stop-color: var(--svg-color--d49d8f, #D49D8F);
  stop-opacity: 0;
}

.bitta5b4f {
  stop-color: var(--svg-color--da9779, #DA9779);
  stop-opacity: 0;
}

.blcb75bhw {
  stop-color: var(--svg-color--ffd9ae, #FFD9AE);
}

.c2okx_q2g {
  stop-color: var(--svg-color--d39186, #D39186);
  stop-opacity: 0;
}

.cbcg1h21f {
  stop-color: var(--svg-color--edbfa5, #EDBFA5);
}

.cpmy9wdkn {
  stop-color: var(--svg-color--ab6a5f, #AB6A5F);
}

.csb315wui {
  stop-color: var(--svg-color--d39186, #D39186);
}

.d-sq5_b-j {
  fill: var(--svg-color--dfa789, #DFA789);
  d: path("M16 13.87a.375.375 0 0 0-.358.262l-.677 2.14a.56.56 0 0 0 .535.73h1a.56.56 0 0 0 .535-.73l-.677-2.14A.375.375 0 0 0 16 13.87");
}

.d7slzly-q {
  stop-color: var(--svg-color--c87167, #C87167);
  stop-opacity: 0;
}

.dfqtmwbvu {
  stop-color: var(--svg-color--c9907d, #C9907D);
}

.dj4m7-bab {
  d: path("M16.507 8.493c.547.846 1.51 1.29 1.847 1.279l1.484-2.327c-.861-2.406-2.462-1.924-3.028-1.562c-.694.444-.986 1.554-.303 2.61");
}

.dkva-0p2a {
  d: path("M5.65 29.974h20.7c-.494-4.932-5.203-8.665-10.39-8.665c-5.189 0-9.713 3.764-10.31 8.665");
}

.dpgj0fl2i {
  stop-color: var(--svg-color--fbc8a8, #FBC8A8);
  stop-opacity: 0;
}

.dwoq6zbym {
  stop-color: var(--svg-color--ff7645, #FF7645);
}

.e0nbxjblq {
  stop-color: var(--svg-color--c6867c, #C6867C);
}

.e4qmmebvg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M17.385 14.23c.146.164.536.45 1.023.468c.617.024.95-.304 1.145-.469");
}

.ea054pq6c {
  stop-color: var(--svg-color--f2bea5, #F2BEA5);
  stop-opacity: 0;
}

.ecsgmuy6m {
  stop-color: var(--svg-color--edbfa5, #EDBFA5);
  stop-opacity: 0;
}

.eevz_mbba {
  stop-color: var(--svg-color--e2a786, #E2A786);
}

.eh43pve_h {
  d: path("m9.469 9.256l1.31.78v3.433a.656.656 0 0 1-1.31 0z");
}

.eol8oh85h {
  stop-color: var(--svg-color--ddbf86, #DDBF86);
}

.eusqnibct {
  stop-color: var(--svg-color--c4836f, #C4836F);
}

.f8hhmqb2i {
  stop-color: var(--svg-color--daad86, #DAAD86);
  stop-opacity: 0;
}

.fe7el9-3d {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M14.357 17.578c.344.18.879.383 1.649.384c.77 0 1.304-.204 1.648-.384c.108-.057.243.013.25.135a.15.15 0 0 1-.014.076c-.76 1.472-3.066 1.457-3.769 0a.15.15 0 0 1-.014-.076c.008-.122.142-.192.25-.135");
}

.fgf4_ac8o {
  d: path("M10.173 5.384v-2.9h1.469V6.02a1 1 0 0 0 .28.693l2.262 2.349a.46.46 0 0 1-.636.663L11.184 7.63a3 3 0 0 1-1.011-2.246");
}

.ft5dv1b6b {
  fill: none;
}

.g-lz2-rad {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.928 12.698c-.258-.207-.883-.578-1.95-.43");
}

.g3cj9mbqt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.385 14.23c.146.164.536.45 1.023.468c.617.024.95-.304 1.145-.469");
}

.g5_ia9syq {
  d: path("M22.623 15.636h-2.207v3.894c.934.024 1.977-.949 2.121-2.277z");
}

.gd06x8-mu {
  stop-color: var(--svg-color--c5836c, #C5836C);
}

.gd4v4obak {
  stop-color: var(--svg-color--f3c0a4, #F3C0A4);
  stop-opacity: 0;
}

.gfxjw2b6r {
  stop-color: var(--svg-color--e3c78d, #E3C78D);
  stop-opacity: 0;
}

.gl9j5ld5z {
  stop-color: var(--svg-color--d49d8f, #D49D8F);
}

.gv40t8-iz {
  fill: var(--svg-color--f5e0a1, #F5E0A1);
  d: path("m12.387 5.628l-.914.773l.914 1.524h3.327c.115 0 .22.066.276.167c.105.19.285.489.53.833c.742 1.047 1.562.953 3.023.984c1.169.025 1.805.406 1.977.594V9.276L20.3 7.972V6.456c-.64-.86-1.202-1.281-1.655-1.445s-.98-.22-1.684-.078c-.563.112-.871.16-1.184.16c-.27 0-.557-.054-1.082-.16c-.832-.169-1.586.109-2.308.695");
}

.h26e4sgsm {
  d: path("M13.75 20.245a2.256 2.256 0 0 1 4.512 0v2.102c0 1.246-1.588 1.624-2.256 1.624c-.766 0-2.257-.378-2.257-1.624z");
}

.hkkpz-bpt {
  stop-color: var(--svg-color--c37a6b, #C37A6B);
}

.htw-10p4r {
  fill: var(--svg-color--ffb62d, #FFB62D);
  d: path("M23.425 2.026h-3.426v3.742c0 .352-.227 1.035-.684 1.43a79 79 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .027 1.714c.453.429 1.09.362 1.554-.054l.978-.74a.527.527 0 0 1 .88.393v3.327a1.2 1.2 0 1 0 2.398 0z");
}

.i1uhwuuoc {
  stop-color: var(--svg-color--fdb496, #FDB496);
  stop-opacity: 0;
}

.i6h5s3y2e {
  stop-color: var(--svg-color--7e4630, #7E4630);
}

.i7fnn1bcq {
  cx: 10.604px;
  cy: 14.61px;
  r: 1.979px;
}

.ic-dvmxoa {
  d: path("M9.377 6.692h2.83v.372c0 .29.186.855.564 1.181c.31.287.904.875 1.426 1.397a.987.987 0 0 1-.022 1.416c-.374.354-.898.299-1.282-.045l-.81-.61a.435.435 0 0 0-.725.323v2.748a.99.99 0 0 1-1.981 0z");
}

.j-io36bgr {
  stop-color: var(--svg-color--fff3bc, #FFF3BC);
  stop-opacity: 0;
}

.j0j5vybko {
  cx: 13.524px;
  cy: 13.487px;
  r: 1.415px;
}

.j94fgem2b {
  stroke: var(--svg-color--945c2e, #945C2E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.072 12.753c.258-.207.883-.578 1.95-.43");
}

.jvs9aeb5c {
  d: path("m21.12 8.376l-2.021 1.488c-.245.18-.471.42-.677.196c-.22-.238-.007-.337.229-.559a52 52 0 0 1 1.99-1.786c.875-.734.85-2.108.828-2.57V2.568h1.704V13.28a.579.579 0 0 1-1.157 0V9.044c0-.403-.572-.907-.896-.668");
}

.k12aqibrq {
  stop-color: var(--svg-color--f4bc97, #F4BC97);
}

.kbotj-bvx {
  stop-color: var(--svg-color--cbb076, #CBB076);
}

.kew95vbbt {
  stop-color: var(--svg-color--ecb99c, #ECB99C);
}

.kkqz5eb_f {
  d: path("M12.88 6.098a4.6 4.6 0 0 0-.984.547l.261 1.119l2.828.037a.986.986 0 1 0 .013-1.972h-.646c-.277 0-.96.054-1.472.27");
}

.lln5h90we {
  d: path("M16 13.87a.375.375 0 0 0-.358.262l-.677 2.14a.56.56 0 0 0 .535.73h1a.56.56 0 0 0 .535-.73l-.677-2.14A.375.375 0 0 0 16 13.87");
}

.lphhh6b5o {
  stop-color: var(--svg-color--925d35, #925D35);
}

.ls69o4b3v {
  stop-color: var(--svg-color--fff2b9, #FFF2B9);
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.n_pf1oy7u {
  stop-color: var(--svg-color--d09580, #D09580);
}

.na9kkhbsz {
  stop-color: var(--svg-color--ffe041, #FFE041);
  stop-opacity: 0;
}

.niae35b7q {
  stop-color: var(--svg-color--98623a, #98623A);
}

.nnet9bbrm {
  cx: 21.396px;
  cy: 14.61px;
  r: 1.293px;
}

.nsiq1yeca {
  stop-color: var(--svg-color--daad86, #DAAD86);
}

.o6m_l6f4f {
  stop-color: var(--svg-color--e3c78d, #E3C78D);
}

.ojzo1eq0m {
  stop-color: var(--svg-color--a06b42, #A06B42);
}

.ow5lwmmzq {
  stop-color: var(--svg-color--e1ad98, #E1AD98);
}

.p4t0ota3q {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.357 17.578c.344.18.879.383 1.649.384c.77 0 1.304-.204 1.648-.384c.108-.057.243.013.25.135a.15.15 0 0 1-.014.076c-.76 1.472-3.066 1.457-3.769 0a.15.15 0 0 1-.014-.076c.008-.122.142-.192.25-.135Z");
}

.p74yltb2p {
  stop-color: var(--svg-color--fdb496, #FDB496);
}

.pra7rq0gk {
  stop-color: var(--svg-color--ffe041, #FFE041);
}

.qd2j91b8n {
  stop-color: var(--svg-color--c87167, #C87167);
}

.qfofjhlvk {
  stop-color: var(--svg-color--da9779, #DA9779);
}

.qj0e2uhmt {
  stop-color: var(--svg-color--c78b82, #C78B82);
  stop-opacity: 0;
}

.qmajx1z3l {
  stop-color: var(--svg-color--de9f87, #DE9F87);
}

.qmod-43sl {
  stop-color: var(--svg-color--ff7645, #FF7645);
  stop-opacity: 0;
}

.r-0_iwkut {
  stop-color: var(--svg-color--834f26, #834F26);
}

.r5m4p51to {
  fill: var(--svg-color--e1aa8e, #E1AA8E);
  d: path("M8.599 2.026h3.425v3.742c0 .352.227 1.035.684 1.43a79 79 0 0 1 1.727 1.692a1.195 1.195 0 0 1-.026 1.714c-.454.429-1.088.362-1.553-.054l-.98-.74a.527.527 0 0 0-.879.393v3.327a1.2 1.2 0 0 1-2.398 0z");
}

.rf58g5bum {
  fill: var(--svg-color--e5a684, #E5A684);
  d: path("M9.377 15.636h2.156v3.894c-.933.024-2.035-1.054-2.105-2.27z");
}

.rkbi44biq {
  stop-color: var(--svg-color--ddbf86, #DDBF86);
  stop-opacity: 0;
}

.rq60-qb-m {
  stop-color: var(--svg-color--fff2b9, #FFF2B9);
  stop-opacity: 0;
}

.s7bsw33sf {
  fill: var(--svg-color--cb8a7c, #CB8A7C);
  d: path("M15.872 13.956c-.163 0-.248.093-.297.254l-.887 2.205a.59.59 0 0 0 .112.554a.56.56 0 0 0 .423.198h1a.56.56 0 0 0 .423-.198a.59.59 0 0 0 .112-.554l-.677-2.205c-.05-.16-.045-.254-.209-.254");
}

.saw93vs6k {
  stop-color: var(--svg-color--f6b091, #F6B091);
}

.srcdcl_yh {
  cx: 21.396px;
  cy: 14.61px;
  r: 1.979px;
}

.ss3psybpi {
  stop-color: var(--svg-color--e7b79d, #E7B79D);
  stop-opacity: 0;
}

.sxbetcb4w {
  stop-color: var(--svg-color--f0cb91, #F0CB91);
}

.sykku8w3p {
  stop-color: var(--svg-color--9f6a40, #9F6A40);
}

.t4_yy204v {
  stop-color: var(--svg-color--e1ad98, #E1AD98);
  stop-opacity: 0;
}

.tanu-rbxd {
  stop-color: var(--svg-color--9f6a40, #9F6A40);
  stop-opacity: 0;
}

.top4m_b9w {
  stop-color: var(--svg-color--a66046, #A66046);
}

.u0l2jtzsy {
  fill: var(--svg-color--e09682, #E09682);
  d: path("M13.75 20.245a2.256 2.256 0 0 1 4.512 0v2.102c0 1.246-1.588 1.624-2.256 1.624c-.766 0-2.257-.378-2.257-1.624z");
}

.vlr6nmb6w {
  d: path("M22.166 7.572h-3.173V5.768c0 .352-.21 1.035-.633 1.43a76 76 0 0 0-1.6 1.692a1.263 1.263 0 0 0 .025 1.714c.42.429 1.01.362 1.44-.054l.905-.74a.464.464 0 0 1 .692.043c.08.097.123.221.123.35v3.327c0 .663.497 1.2 1.11 1.2s1.111-.537 1.111-1.2z");
}

.vmf5ti4hh {
  stop-color: var(--svg-color--9d683d, #9D683D);
}

.vpdouuqcq {
  fill: var(--svg-color--d2997d, #D2997D);
  d: path("M23.425 2.026h-3.426v3.742c0 .352-.227 1.035-.684 1.43a79 79 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .027 1.714c.453.429 1.09.362 1.554-.054l.978-.74a.527.527 0 0 1 .88.393v3.327a1.2 1.2 0 1 0 2.398 0z");
}

.w5a3tprnu {
  d: path("M8.599 2.026h3.425v3.742c0 .352.227 1.035.684 1.43a79 79 0 0 1 1.727 1.692a1.195 1.195 0 0 1-.026 1.714c-.454.429-1.088.362-1.553-.054l-.98-.74a.527.527 0 0 0-.879.393v3.327a1.2 1.2 0 0 1-2.398 0z");
}

.w8m6qxbxc {
  stop-color: var(--svg-color--ca6a6a, #CA6A6A);
}

.wj0_vcbzm {
  stop-color: var(--svg-color--c9a18c, #C9A18C);
  stop-opacity: 0;
}

.wkqd0hb4b {
  d: path("m10.127 10.745l.203 6.485c.233 3.376 2.209 4.755 5.637 4.773h.066c3.428-.018 5.404-1.397 5.637-4.773l.203-6.485c.069-2.2-1.117-3.344-1.719-3.64h-8.308c-.602.296-1.788 1.44-1.72 3.64");
}

.wldo5sm4b {
  stop-color: var(--svg-color--e1ca90, #E1CA90);
  stop-opacity: 0;
}

.wv6byccxz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.494 14.23c.146.164.536.45 1.024.468c.617.024.949-.304 1.144-.469");
}

.wyd3097rt {
  stop-color: var(--svg-color--fff3bc, #FFF3BC);
}

.xjyo8kbbd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.494 14.23c.146.164.536.45 1.024.468c.617.024.949-.304 1.144-.469");
}

.xk4wwk53d {
  stop-color: var(--svg-color--be7d75, #BE7D75);
}

.xms_-vb8m {
  stop-color: var(--svg-color--fbc8a8, #FBC8A8);
}

.xtumd7buv {
  stop-color: var(--svg-color--e2a481, #E2A481);
}

.y_s895zcx {
  stop-color: var(--svg-color--f3c0a4, #F3C0A4);
}

.yp6fmsbhu {
  stop-color: var(--svg-color--f2bea5, #F2BEA5);
}

.yu799baro {
  stop-color: var(--svg-color--ff5026, #FF5026);
}

.z5n052ywy {
  stroke: var(--svg-color--945c2e, #945C2E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M19.928 12.753c-.258-.207-.883-.578-1.95-.43");
}

.ze6s0wf9k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.072 12.753c.258-.207.883-.578 1.95-.43");
}

.zl8nqy82h {
  stop-color: var(--svg-color--ff641f, #FF641F);
}

.zpoasobui {
  stop-color: var(--svg-color--e7b79d, #E7B79D);
}

.zus2iac3j {
  cx: 10.604px;
  cy: 14.61px;
  r: 1.293px;
  fill: var(--svg-color--ba765f, #BA765F);
}

</style>
