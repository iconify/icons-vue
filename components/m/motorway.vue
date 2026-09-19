<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#icSWaOc)"><rect class="nqx3sxb7k"/></g><rect fill="url(#iUtYbPb)" class="sx2me0beo"/><rect fill="url(#iGAiu5b)" class="sx2me0beo"/><path fill="url(#iGIp8Ee)" class="aln052b2i"/><path fill="url(#imiYu1X)" class="aln052b2i"/><path fill="url(#iq8F8ge)" class="lehjh255u"/><path fill="url(#iotYLYd)" class="nsgksbbrv"/><path fill="url(#iXf7Mvd)" class="yyjkrz8kq"/><path fill="url(#iZrSwXF)" class="yyjkrz8kq"/><path fill="url(#iAyI5be)" class="yyjkrz8kq"/><path fill="url(#icOBD2c)" class="yyjkrz8kq"/><path fill="url(#iHYcJPb)" class="yyjkrz8kq"/><g filter="url(#ibWr3Vd)"><path fill="url(#ipf1wCd)" class="obzixccmv"/></g><path fill="url(#igI1Gco)" class="obzixccmv"/><path fill="url(#iXvbKnd)" class="iekbzgbph"/><path fill="url(#iz07LJc)" class="iekbzgbph"/><path fill="url(#iRn9T4c)" class="owbmr-bbr"/><path fill="url(#igTxo6c)" class="okdj0obpl"/><path fill="url(#iX2C5cd)" class="o0xnm4bam"/><path fill="url(#iXaIblb)" class="o0xnm4bam"/><path fill="url(#iE941re)" class="o0xnm4bam"/><path fill="url(#i5Nwijd)" class="ug7mp7akn"/><path fill="url(#iWH8GJc)" class="ug7mp7akn"/><path fill="url(#idNhL5d)" class="w4yiv15aq"/><path fill="url(#i7R3eqc)" class="tlgljwhmp"/><path fill="url(#iUPkZPH)" class="q7yx3sbtb"/><g filter="url(#i6U2PKe)"><path class="eyra8y61n"/></g><g filter="url(#iVeKzfb)"><path fill="url(#iix5uDb)" class="y5f53eb6e"/></g><g filter="url(#iAwie3d)"><path fill="url(#i90tvbe)" class="scbla3ble"/></g><g filter="url(#iOEoytR)"><path fill="url(#iPoyxoC)" class="d2_w80gjp"/></g><g filter="url(#ieFx8bo)"><path fill="url(#iX6Ix7b)" class="qf-xkwbnm"/></g><path fill="url(#irVDQwf)" class="wahoxjbkt"/><path fill="url(#iAi9z4b)" class="wahoxjbkt"/><path fill="url(#i6urJBZ)" class="s_glwxb3e"/><path fill="url(#iIKPpbd)" class="s_glwxb3e"/><defs><linearGradient id="iUtYbPb" x1="2.329" x2="5.762" y1="8.993" y2="8.993" gradientUnits="userSpaceOnUse"><stop class="m7yyfkb3b"/><stop offset="1" class="yk251db5c"/></linearGradient><linearGradient id="icOBD2c" x1="22.634" x2="20.755" y1="16.232" y2="14.492" gradientUnits="userSpaceOnUse"><stop class="d4anlpzkj"/><stop offset="1" class="n9dbd-vdb"/></linearGradient><linearGradient id="ipf1wCd" x1="22.895" x2="28.398" y1="17.703" y2="9.302" gradientUnits="userSpaceOnUse"><stop class="cwk_xgbmd"/><stop offset="1" class="d8rp_bb0p"/></linearGradient><linearGradient id="iXvbKnd" x1="6.047" x2="2.305" y1="11.454" y2="15.488" gradientUnits="userSpaceOnUse"><stop class="l02e1utju"/><stop offset="1" class="ed1eedcwn"/></linearGradient><linearGradient id="iRn9T4c" x1="15.971" x2="15.971" y1="17.07" y2="26.173" gradientUnits="userSpaceOnUse"><stop class="jv-usebug"/><stop offset=".167" class="k1fw3iblb"/><stop offset="1" class="k1fw3iblb"/></linearGradient><linearGradient id="igTxo6c" x1="16" x2="16" y1="17.07" y2="30.068" gradientUnits="userSpaceOnUse"><stop class="g9mbf690e"/><stop offset="1" class="zw492tbwc"/></linearGradient><linearGradient id="iX2C5cd" x1="20.153" x2="31.216" y1="17.07" y2="28.005" gradientUnits="userSpaceOnUse"><stop class="scwf-2b3c"/><stop offset="1" class="fr4ki7b9a"/></linearGradient><linearGradient id="iXaIblb" x1="23.716" x2="23.872" y1="21.755" y2="21.599" gradientUnits="userSpaceOnUse"><stop class="nrhukf8bt"/><stop offset="1" class="lgqnjebaf"/></linearGradient><linearGradient id="iE941re" x1="25.466" x2="25.263" y1="21.786" y2="22.005" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="i5Nwijd" x1="13.156" x2="1.28" y1="17.07" y2="26.733" gradientUnits="userSpaceOnUse"><stop class="tfqe3dwyz"/><stop offset="1" class="pg7e7abjp"/></linearGradient><linearGradient id="iWH8GJc" x1="6.638" x2="6.964" y1="21.583" y2="21.942" gradientUnits="userSpaceOnUse"><stop class="nrhukf8bt"/><stop offset="1" class="lgqnjebaf"/></linearGradient><linearGradient id="idNhL5d" x1="15.966" x2="15.966" y1="17.583" y2="18.942" gradientUnits="userSpaceOnUse"><stop class="xnlbtsj2j"/><stop offset="1" class="y53y3nbsi"/></linearGradient><linearGradient id="i7R3eqc" x1="15.966" x2="15.966" y1="19.97" y2="22.787" gradientUnits="userSpaceOnUse"><stop class="xnlbtsj2j"/><stop offset="1" class="y53y3nbsi"/></linearGradient><linearGradient id="iUPkZPH" x1="15.966" x2="15.966" y1="24.823" y2="30.068" gradientUnits="userSpaceOnUse"><stop class="xnlbtsj2j"/><stop offset="1" class="y53y3nbsi"/></linearGradient><linearGradient id="iix5uDb" x1="4.018" x2="8.156" y1="12.57" y2="12.57" gradientUnits="userSpaceOnUse"><stop class="jk1lcczln"/><stop offset=".289" class="ddtxmjwzb"/></linearGradient><linearGradient id="i90tvbe" x1="9.156" x2="10.156" y1="12.781" y2="12.147" gradientUnits="userSpaceOnUse"><stop class="jk1lcczln"/><stop offset=".372" class="ddtxmjwzb"/></linearGradient><linearGradient id="iPoyxoC" x1="9.156" x2="10.156" y1="14.781" y2="14.147" gradientUnits="userSpaceOnUse"><stop class="jk1lcczln"/><stop offset=".372" class="ddtxmjwzb"/></linearGradient><linearGradient id="iX6Ix7b" x1="4.063" x2="7.156" y1="14.565" y2="14.565" gradientUnits="userSpaceOnUse"><stop class="jk1lcczln"/><stop offset=".289" class="ddtxmjwzb"/></linearGradient><linearGradient id="iAi9z4b" x1="4.974" x2="4.935" y1="15.958" y2="16.302" gradientUnits="userSpaceOnUse"><stop offset=".233" class="ig13bwy-c"/><stop offset="1" class="z5zbc5b_i"/></linearGradient><linearGradient id="iIKPpbd" x1="9.974" x2="9.935" y1="15.958" y2="16.302" gradientUnits="userSpaceOnUse"><stop offset=".233" class="ig13bwy-c"/><stop offset="1" class="z5zbc5b_i"/></linearGradient><radialGradient id="iGAiu5b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.71658 1.97087 -2.11548 -1.84253 29.094 2.89)" gradientUnits="userSpaceOnUse"><stop class="vrtdiibms"/><stop offset="1" class="x5gymtgmp"/></radialGradient><radialGradient id="iGIp8Ee" cx="0" cy="0" r="1" gradientTransform="rotate(117.698 -.17 6.69)scale(5.13267 7.26821)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset=".926" class="ify6nqmlz"/></radialGradient><radialGradient id="imiYu1X" cx="0" cy="0" r="1" gradientTransform="matrix(-.93233 -.81579 2.0292 -2.31908 4.92 9.492)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="qtz1cg2yw"/><stop offset="1" class="rpt-1nb0h"/></radialGradient><radialGradient id="iq8F8ge" cx="0" cy="0" r="1" gradientTransform="rotate(139.686 5.402 8.128)scale(10.7968 18.3271)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset=".926" class="ify6nqmlz"/></radialGradient><radialGradient id="iotYLYd" cx="0" cy="0" r="1" gradientTransform="rotate(126.72 10.521 12.648)scale(5.79401 9.70997)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset=".926" class="ify6nqmlz"/></radialGradient><radialGradient id="iXf7Mvd" cx="0" cy="0" r="1" gradientTransform="rotate(136.146 9.502 11.227)scale(9.41987 15.7864)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="nspf70rbr"/></radialGradient><radialGradient id="iZrSwXF" cx="0" cy="0" r="1" gradientTransform="matrix(-.89784 3.16193 -1.06591 -.30267 18.874 12.774)" gradientUnits="userSpaceOnUse"><stop class="kpm05s3uz"/><stop offset="1" class="s78t4-kej"/></radialGradient><radialGradient id="iAyI5be" cx="0" cy="0" r="1" gradientTransform="rotate(-148.773 13.648 5.113)scale(5.95769 7.22692)" gradientUnits="userSpaceOnUse"><stop offset=".502" class="kavidu6ou"/><stop offset=".849" class="ehl6u1beo"/></radialGradient><radialGradient id="iHYcJPb" cx="0" cy="0" r="1" gradientTransform="rotate(127.082 6.56 10.785)scale(1.87607 1.58621)" gradientUnits="userSpaceOnUse"><stop class="y2863tbls"/><stop offset="1" class="sllz6jbvi"/></radialGradient><radialGradient id="igI1Gco" cx="0" cy="0" r="1" gradientTransform="matrix(-.09538 2.38412 -1.4682 -.05874 27.966 8.056)" gradientUnits="userSpaceOnUse"><stop class="vd1vp-_ql"/><stop offset="1" class="zw2xt2bxk"/></radialGradient><radialGradient id="iz07LJc" cx="0" cy="0" r="1" gradientTransform="matrix(6.07055 5.86265 -1.59596 1.65256 1.64 6.673)" gradientUnits="userSpaceOnUse"><stop class="mqw7ocbop"/><stop offset="1" class="erokk0rln"/></radialGradient><radialGradient id="irVDQwf" cx="0" cy="0" r="1" gradientTransform="matrix(-.8644 0 0 -2.7563 5.156 17.34)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="y5ysdmsxo"/><stop offset="1" class="dnbqkrcoa"/></radialGradient><radialGradient id="i6urJBZ" cx="0" cy="0" r="1" gradientTransform="matrix(-.8644 0 0 -2.7563 10.156 17.34)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="y5ysdmsxo"/><stop offset="1" class="dnbqkrcoa"/></radialGradient><filter id="icSWaOc" width="29.75" height="29.75" x=".216" y="2.068" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.75" dy="1.75"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.905882 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11689"/></filter><filter id="ibWr3Vd" width="14.642" height="23.217" x="15.824" y="7.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="1.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.211765 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11689"/></filter><filter id="i6U2PKe" width="8.99" height="6" x="2.656" y="10.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.803922 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11689"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.12549 0 0 0 0 0.360784 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_11689" result="effect2_innerShadow_18_11689"/></filter><filter id="iVeKzfb" width="4.15" height="1.15" x="4.006" y="12.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.513726 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11689"/></filter><filter id="iAwie3d" width="1.15" height="1.15" x="9.006" y="12.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.513726 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11689"/></filter><filter id="iOEoytR" width="1.15" height="1.15" x="9.006" y="14.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.513726 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11689"/></filter><filter id="ieFx8bo" width="3.14" height="1.14" x="4.016" y="14.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.513726 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_11689"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:motorway" /></template>
<style>
.aln052b2i {
  d: path("M1.966 13.818V6.922a3.64 3.64 0 1 1 0 6.895");
}

.cwk_xgbmd {
  stop-color: var(--svg-color--433b4d, #433B4D);
}

.d2_w80gjp {
  d: path("M9.656 14.07c-.28 0-.5.22-.5.5s.22.5.5.5s.5-.22.5-.5s-.22-.5-.5-.5");
}

.d4anlpzkj {
  stop-color: var(--svg-color--a9abab, #A9ABAB);
}

.d8rp_bb0p {
  stop-color: var(--svg-color--614f71, #614F71);
}

.ddtxmjwzb {
  stop-color: var(--svg-color--cccacd, #CCCACD);
}

.dnbqkrcoa {
  stop-color: var(--svg-color--868587, #868587);
}

.ed1eedcwn {
  stop-color: var(--svg-color--393742, #393742);
}

.ehl6u1beo {
  stop-color: var(--svg-color--e5e5e6, #E5E5E6);
}

.erokk0rln {
  stop-color: var(--svg-color--877499, #877499);
  stop-opacity: 0;
}

.eyra8y61n {
  fill: var(--svg-color--3ead88, #3EAD88);
  d: path("M10.036 11.07h-5.77c-.61 0-1.11.5-1.11 1.11v2.78c0 .61.5 1.11 1.11 1.11h5.77c.61 0 1.11-.5 1.11-1.11v-2.78c.01-.61-.49-1.11-1.11-1.11");
}

.fr4ki7b9a {
  stop-color: var(--svg-color--e6e3e8, #E6E3E8);
}

.ft5dv1b6b {
  fill: none;
}

.g9mbf690e {
  stop-color: var(--svg-color--665278, #665278);
}

.iekbzgbph {
  d: path("m12.146 17.07l-9.78-9.78a2 2 0 0 0-.39-.305V17.07z");
}

.ify6nqmlz {
  stop-color: var(--svg-color--bbbbbc, #BBBBBC);
}

.ig13bwy-c {
  stop-color: var(--svg-color--7c8184, #7C8184);
}

.jk1lcczln {
  stop-color: var(--svg-color--e3e2e4, #E3E2E4);
}

.jv-usebug {
  stop-color: var(--svg-color--6bc589, #6BC589);
}

.k1fw3iblb {
  stop-color: var(--svg-color--5eaa7c, #5EAA7C);
}

.kavidu6ou {
  stop-color: var(--svg-color--e5e5e6, #E5E5E6);
  stop-opacity: 0;
}

.kpm05s3uz {
  stop-color: var(--svg-color--d3d3d4, #D3D3D4);
}

.l02e1utju {
  stop-color: var(--svg-color--6a5a79, #6A5A79);
}

.lehjh255u {
  d: path("M17.643 17.07c.595-1.08.933-2.32.933-3.64a7.55 7.55 0 0 0-14.73-2.34a5.9 5.9 0 0 0-1.87-1.33v7.31z");
}

.lgqnjebaf {
  stop-color: var(--svg-color--928c97, #928C97);
  stop-opacity: 0;
}

.m7yyfkb3b {
  stop-color: var(--svg-color--47a2c2, #47A2C2);
}

.mqw7ocbop {
  stop-color: var(--svg-color--877499, #877499);
}

.n9dbd-vdb {
  stop-color: var(--svg-color--a9abab, #A9ABAB);
  stop-opacity: 0;
}

.nqx3sxb7k {
  width: 28px;
  height: 28px;
  x: 1.966px;
  y: 2.068px;
  fill: var(--svg-color--4bc8f2, #4BC8F2);
  rx: 3.8px;
}

.nrhukf8bt {
  stop-color: var(--svg-color--928c97, #928C97);
}

.nsgksbbrv {
  d: path("M24.906 16a3.16 3.16 0 1 0 0-6.32a3.16 3.16 0 0 0 0 6.32");
}

.nspf70rbr {
  stop-color: var(--svg-color--b9bdbb, #B9BDBB);
}

.o0xnm4bam {
  d: path("M29.966 26.081v.187a3.8 3.8 0 0 1-.237 1.324L19.156 17.07h1z");
}

.obzixccmv {
  d: path("M29.966 7.85v18.418a3.8 3.8 0 0 1-3.8 3.8h-3.942l-5.808-5.808c-.79-.79-.79-2.07 0-2.86l5.68-6.71l4.38-5.26c.41-.5 1.03-.78 1.67-.78h.12c.58 0 1.13-.23 1.54-.64z");
}

.okdj0obpl {
  d: path("M29.944 26.681a3.8 3.8 0 0 1-3.778 3.387h-20.4a3.8 3.8 0 0 1-3.71-2.973l10.1-10.025h8z");
}

.owbmr-bbr {
  d: path("M29.966 17.07H1.976v9.103h27.99z");
}

.pg7e7abjp {
  stop-color: var(--svg-color--b5b2b6, #B5B2B6);
}

.q7yx3sbtb {
  d: path("m16.896 24.285l.57 5.783h-3l.57-5.783z");
}

.qf-xkwbnm {
  d: path("M6.726 14.07h-2.13c-.24 0-.43.19-.43.43v.13c0 .24.19.43.43.43h2.13c.24 0 .43-.19.43-.43v-.13c0-.24-.19-.43-.43-.43");
}

.qtz1cg2yw {
  stop-color: var(--svg-color--c1c0c1, #C1C0C1);
}

.rpt-1nb0h {
  stop-color: var(--svg-color--c1c0c1, #C1C0C1);
  stop-opacity: 0;
}

.s_glwxb3e {
  d: path("M9.166 16.068h.99v1.992h-.99z");
}

.s78t4-kej {
  stop-color: var(--svg-color--d3d3d4, #D3D3D4);
  stop-opacity: 0;
}

.scbla3ble {
  d: path("M9.656 12.07c-.28 0-.5.22-.5.5s.22.5.5.5s.5-.22.5-.5s-.22-.5-.5-.5");
}

.scwf-2b3c {
  stop-color: var(--svg-color--e3e0e4, #E3E0E4);
}

.sllz6jbvi {
  stop-color: var(--svg-color--d6d6d7, #D6D6D7);
  stop-opacity: 0;
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.sx2me0beo {
  width: 28px;
  height: 28px;
  x: 1.966px;
  y: 2.068px;
  rx: 3.8px;
}

.tfqe3dwyz {
  stop-color: var(--svg-color--e6e5e9, #E6E5E9);
}

.tlgljwhmp {
  d: path("m16.436 19.681l.31 3.096l-1.56.01l.31-3.106z");
}

.ug7mp7akn {
  d: path("M2.188 27.55a3.8 3.8 0 0 1-.222-1.282v-.184l10.19-9.014h1z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vd1vp-_ql {
  stop-color: var(--svg-color--6c597d, #6C597D);
}

.vrtdiibms {
  stop-color: var(--svg-color--6df5ff, #6DF5FF);
}

.w4yiv15aq {
  d: path("m16.216 17.444l.15 1.498h-.8l.15-1.498z");
}

.wahoxjbkt {
  d: path("M4.166 16.068h.99v1.992h-.99z");
}

.x5gymtgmp {
  stop-color: var(--svg-color--6df5ff, #6DF5FF);
  stop-opacity: 0;
}

.xnlbtsj2j {
  stop-color: var(--svg-color--ffe039, #FFE039);
}

.y2863tbls {
  stop-color: var(--svg-color--d6d6d7, #D6D6D7);
}

.y53y3nbsi {
  stop-color: var(--svg-color--ffc33c, #FFC33C);
}

.y5f53eb6e {
  d: path("M7.656 12.07h-3c-.28 0-.5.22-.5.5s.22.5.5.5h3c.28 0 .5-.22.5-.5s-.22-.5-.5-.5");
}

.y5ysdmsxo {
  stop-color: var(--svg-color--fbfbfd, #FBFBFD);
}

.yk251db5c {
  stop-color: var(--svg-color--47a2c2, #47A2C2);
  stop-opacity: 0;
}

.yyjkrz8kq {
  d: path("M21.926 21.62a5.06 5.06 0 1 0 0-10.12a5.06 5.06 0 0 0 0 10.12");
}

.z5zbc5b_i {
  stop-color: var(--svg-color--7c8184, #7C8184);
  stop-opacity: 0;
}

.zw2xt2bxk {
  stop-color: var(--svg-color--6c597d, #6C597D);
  stop-opacity: 0;
}

.zw492tbwc {
  stop-color: var(--svg-color--414042, #414042);
}

</style>
