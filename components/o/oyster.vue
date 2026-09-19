<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i4fQHud)" class="yud86p90m"/><path fill="url(#iMOckmc)" class="yud86p90m"/><path fill="url(#ii1r3de)" class="yud86p90m"/><path fill="url(#ivcRzHe)" class="yud86p90m"/><g filter="url(#i01i3eb)"><path fill="url(#iBSJG1c)" class="ij7yqxb5u"/><path fill="url(#igsHY6o)" class="ij7yqxb5u"/><path fill="url(#ivGdVTc)" class="ij7yqxb5u"/><path fill="url(#ie1PPje)" class="ij7yqxb5u"/><path fill="url(#isLaEde)" class="ij7yqxb5u"/></g><g filter="url(#iA6N3he)"><path class="elfkjwkks"/></g><path fill="url(#i3HoLtO)" class="ksyvuybje"/><path fill="url(#iI4Ivxe)" class="ksyvuybje"/><path fill="url(#i7jFhim)" class="ksyvuybje"/><path fill="url(#i1OIS0o)" class="ksyvuybje"/><g filter="url(#is3lUnb)"><path fill="url(#ia3zfBc)" class="nixet79fe"/><path fill="url(#iYuknyb)" class="nixet79fe"/><path fill="url(#iEtbTNe)" class="nixet79fe"/><path fill="url(#iXKMzDe)" class="nixet79fe"/><path fill="url(#iAuH5te)" class="nixet79fe"/></g><path fill="url(#ib7LSnd)" class="hx9bp5b9f"/><path fill="url(#iRhX43c)" class="hx9bp5b9f"/><path fill="url(#iuDULFe)" class="hx9bp5b9f"/><path fill="url(#ibqiCfc)" class="hx9bp5b9f"/><path fill="url(#it83bYc)" class="hx9bp5b9f"/><path fill="url(#iyKfBvd)" class="hx9bp5b9f"/><path fill="url(#iDLXiLe)" class="hx9bp5b9f"/><path fill="url(#i2dxfse)" class="j5zk2lpac"/><path fill="url(#iaZz28b)" class="j5zk2lpac"/><path fill="url(#iFZdxjJ)" class="j5zk2lpac"/><path fill="url(#i3sreQc)" class="j5zk2lpac"/><g filter="url(#iW9l8Vc)"><path fill="url(#iO4pTWc)" class="cnml4ubhb"/><path class="y00n1z9pq"/></g><path fill="url(#i3Lm4oz)" class="o0jr_9bvb"/><path fill="url(#ip0bLRr)" class="o0jr_9bvb"/><defs><radialGradient id="iMOckmc" cx="0" cy="0" r="1" gradientTransform="matrix(9.8125 12.31251 -12.30336 9.8052 4.875 19.563)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="x84mftbpr"/><stop offset=".961" class="mplyt5utb"/></radialGradient><radialGradient id="ivcRzHe" cx="0" cy="0" r="1" gradientTransform="matrix(2.5625 9.93753 -19.68972 5.07723 16.75 27.688)" gradientUnits="userSpaceOnUse"><stop class="au1rlln2o"/><stop offset="1" class="lfgbnlbog"/></radialGradient><radialGradient id="igsHY6o" cx="0" cy="0" r="1" gradientTransform="matrix(9.316 8.81537 -8.80891 9.30917 5.438 22.25)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="x84mftbpr"/><stop offset=".961" class="mplyt5utb"/></radialGradient><radialGradient id="ivGdVTc" cx="0" cy="0" r="1" gradientTransform="rotate(76.691 -4.52 20.916)scale(11.9458 1.57482)" gradientUnits="userSpaceOnUse"><stop class="t7bfa8ktb"/><stop offset="1" class="t_4epc1wz"/></radialGradient><radialGradient id="ie1PPje" cx="0" cy="0" r="1" gradientTransform="matrix(6 6.875 -1.75804 1.5343 19.25 18.938)" gradientUnits="userSpaceOnUse"><stop class="o18av-bbp"/><stop offset="1" class="t_4epc1wz"/></radialGradient><radialGradient id="isLaEde" cx="0" cy="0" r="1" gradientTransform="matrix(6.625 5.4375 -1.39045 1.69411 7.813 12.25)" gradientUnits="userSpaceOnUse"><stop class="g-wv0k8pb"/><stop offset="1" class="y0eooo6-k"/></radialGradient><radialGradient id="i3HoLtO" cx="0" cy="0" r="1" gradientTransform="matrix(-14.1874 -11.00012 11.703 -15.09394 25.938 17.313)" gradientUnits="userSpaceOnUse"><stop class="t2gmspbti"/><stop offset="1" class="xj6qmjb6r"/></radialGradient><radialGradient id="iI4Ivxe" cx="0" cy="0" r="1" gradientTransform="matrix(4.9375 7.125 -8.1028 5.6151 10.125 9.188)" gradientUnits="userSpaceOnUse"><stop class="dglrogd7a"/><stop offset="1" class="mhexay85v"/></radialGradient><radialGradient id="i7jFhim" cx="0" cy="0" r="1" gradientTransform="matrix(5.5625 19.75002 -4.93012 1.38854 26.563 10.125)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="qrv_v0fil"/><stop offset=".912" class="cc6ej5b5f"/></radialGradient><radialGradient id="i1OIS0o" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.875 -34.6917 0 22.5 21.938)" gradientUnits="userSpaceOnUse"><stop class="jd5jblbwl"/><stop offset=".794" class="emn3bbbwu"/></radialGradient><radialGradient id="ia3zfBc" cx="0" cy="0" r="1" gradientTransform="rotate(-142.212 15.535 4.101)scale(16.3036 17.3454)" gradientUnits="userSpaceOnUse"><stop class="t2gmspbti"/><stop offset=".734" class="eitxp9b6f"/><stop offset="1" class="cot38jp6a"/></radialGradient><radialGradient id="iYuknyb" cx="0" cy="0" r="1" gradientTransform="matrix(3.5625 4.0625 -.91099 .79887 13.625 8.75)" gradientUnits="userSpaceOnUse"><stop offset=".324" class="i0ov7pbkr"/><stop offset="1" class="zioba5rfe"/></radialGradient><radialGradient id="iEtbTNe" cx="0" cy="0" r="1" gradientTransform="matrix(3.93753 4.85153 -1.50467 1.2212 16.875 7.437)" gradientUnits="userSpaceOnUse"><stop offset=".324" class="lw6u3_bwo"/><stop offset="1" class="fgs1m7k9t"/></radialGradient><radialGradient id="iXKMzDe" cx="0" cy="0" r="1" gradientTransform="rotate(-175.764 11.916 9.135)scale(3.38425 .81069)" gradientUnits="userSpaceOnUse"><stop offset=".487" class="crv0pbnmo"/><stop offset="1" class="tjug89thd"/></radialGradient><radialGradient id="iAuH5te" cx="0" cy="0" r="1" gradientTransform="rotate(144.142 10.982 8.524)scale(7.78871 2.32508)" gradientUnits="userSpaceOnUse"><stop class="y6j0-02vk"/><stop offset="1" class="yfq9ocb1a"/></radialGradient><radialGradient id="iRhX43c" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 8.8125 -8.64773 -.24533 19.063 13)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="bofcwovvi"/><stop offset="1" class="u-4y4kb3o"/></radialGradient><radialGradient id="iuDULFe" cx="0" cy="0" r="1" gradientTransform="rotate(93.715 8.309 9.548)scale(4.82264 4.73246)" gradientUnits="userSpaceOnUse"><stop class="okj1n1b5y"/><stop offset="1" class="idaa35bsz"/></radialGradient><radialGradient id="ibqiCfc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.37501 1.24997 -1.2266 -4.2932 30.438 13.188)" gradientUnits="userSpaceOnUse"><stop class="bqbnxcbob"/><stop offset="1" class="smn0rc_gy"/></radialGradient><radialGradient id="it83bYc" cx="0" cy="0" r="1" gradientTransform="matrix(-.8125 6.5 -3.49814 -.43727 29.125 13.375)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="j9s8ppcjh"/><stop offset=".691" class="kenwmzdet"/></radialGradient><radialGradient id="iyKfBvd" cx="0" cy="0" r="1" gradientTransform="matrix(1.875 4.6875 -2.04304 .81722 15 6)" gradientUnits="userSpaceOnUse"><stop class="fulqksb4s"/><stop offset="1" class="qh3x315pc"/></radialGradient><radialGradient id="iDLXiLe" cx="0" cy="0" r="1" gradientTransform="matrix(6.0625 -.33472 .16177 2.92996 18 3.335)" gradientUnits="userSpaceOnUse"><stop offset=".105" class="t-wepab3b"/><stop offset=".691" class="ditxxcb1u"/></radialGradient><radialGradient id="i2dxfse" cx="0" cy="0" r="1" gradientTransform="matrix(-7.07782 14.2513 -14.22076 -7.06265 20.5 13.625)" gradientUnits="userSpaceOnUse"><stop class="x64fbvbre"/><stop offset=".406" class="vwdr7db7z"/><stop offset="1" class="jkq8hibuy"/></radialGradient><radialGradient id="iaZz28b" cx="0" cy="0" r="1" gradientTransform="matrix(-11.68759 11.62493 -9.174 -9.22344 17.813 14.563)" gradientUnits="userSpaceOnUse"><stop offset=".818" class="q4lhr2_ng"/><stop offset="1" class="i1mx43b6a"/></radialGradient><radialGradient id="iFZdxjJ" cx="0" cy="0" r="1" gradientTransform="rotate(125.932 .35 9.04)scale(13.7393 5.58608)" gradientUnits="userSpaceOnUse"><stop offset=".306" class="bu5pcgfnd"/><stop offset="1" class="krh6ezffp"/></radialGradient><radialGradient id="i3sreQc" cx="0" cy="0" r="1" gradientTransform="matrix(5.37498 9.37497 -18.35174 10.52167 12.25 17.125)" gradientUnits="userSpaceOnUse"><stop offset=".593" class="lr6frfbnr"/><stop offset=".895" class="gt8aa0b7u"/></radialGradient><radialGradient id="iO4pTWc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.088 5.37496 -5.36724 -5.0807 13.401 13.25)" gradientUnits="userSpaceOnUse"><stop offset=".095" class="g8yxhacwl"/><stop offset=".633" class="f1z1-nbfa"/><stop offset="1" class="kfqpxobbi"/></radialGradient><radialGradient id="i3Lm4oz" cx="0" cy="0" r="1" gradientTransform="rotate(134.665 4.181 9.233)scale(7.55733)" gradientUnits="userSpaceOnUse"><stop offset=".095" class="g8yxhacwl"/><stop offset=".633" class="f1z1-nbfa"/><stop offset="1" class="kfqpxobbi"/></radialGradient><radialGradient id="ip0bLRr" cx="0" cy="0" r="1" gradientTransform="rotate(96.892 -4.24 15.55)scale(5.7289)" gradientUnits="userSpaceOnUse"><stop class="ouixxkbqt"/><stop offset="1" class="s3c776-lb"/></radialGradient><linearGradient id="i4fQHud" x1="7.688" x2="24.188" y1="8.75" y2="23.5" gradientUnits="userSpaceOnUse"><stop class="wnvb9nk5o"/><stop offset="1" class="tyyksibfr"/></linearGradient><linearGradient id="ii1r3de" x1="4.375" x2="25.188" y1="28.063" y2="5.188" gradientUnits="userSpaceOnUse"><stop class="hsx9h6b8s"/><stop offset=".385" class="pe-jeg5yi"/><stop offset="1" class="nnggy_qgf"/></linearGradient><linearGradient id="iBSJG1c" x1="8.111" x2="23.769" y1="9.12" y2="23.118" gradientUnits="userSpaceOnUse"><stop class="wnvb9nk5o"/><stop offset=".836" class="qa7w3vb0h"/><stop offset="1" class="tyyksibfr"/></linearGradient><linearGradient id="ib7LSnd" x1="11.875" x2="25.298" y1="6.375" y2="19.827" gradientUnits="userSpaceOnUse"><stop class="i7hclabdf"/><stop offset="1" class="yp00hj66r"/></linearGradient><filter id="i01i3eb" width="27.537" height="27.556" x="2.213" y="2.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29562" stdDeviation=".25"/></filter><filter id="iA6N3he" width="21.309" height="20.149" x="7.89" y="2.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29562" stdDeviation=".5"/></filter><filter id="is3lUnb" width="19.536" height="18.703" x="9.214" y="2.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29562" stdDeviation=".5"/></filter><filter id="iW9l8Vc" width="9.688" height="7.692" x="6.719" y="12.808" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29562" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:oyster" /></template>
<style>
.au1rlln2o {
  stop-color: var(--svg-color--914b63, #914B63);
}

.bofcwovvi {
  stop-color: var(--svg-color--9a8d8e, #9A8D8E);
}

.bqbnxcbob {
  stop-color: var(--svg-color--c0b2c9, #C0B2C9);
}

.bu5pcgfnd {
  stop-color: var(--svg-color--aa956b, #AA956B);
}

.cc6ej5b5f {
  stop-color: var(--svg-color--ddd8e3, #DDD8E3);
  stop-opacity: 0;
}

.cnml4ubhb {
  d: path("M15.406 15.031c0 2.486-1.72 4.469-4.1 4.469c-9.547-.812 2.843-8.656 4.1-4.469");
}

.cot38jp6a {
  stop-color: var(--svg-color--c9c4c5, #C9C4C5);
}

.crv0pbnmo {
  stop-color: var(--svg-color--cebecb, #CEBECB);
}

.dglrogd7a {
  stop-color: var(--svg-color--887b86, #887B86);
}

.ditxxcb1u {
  stop-color: var(--svg-color--c6c3ca, #C6C3CA);
  stop-opacity: 0;
}

.eitxp9b6f {
  stop-color: var(--svg-color--bcb5b8, #BCB5B8);
}

.elfkjwkks {
  fill: var(--svg-color--703826, #703826);
  d: path("M9.227 11.734c0-.984-.758-3.836 0-4.902c.757-1.066 2.49-1.11 3.272-2.321l.01-.02c.32-.49.88-.791 1.47-.791c.27 0 .54.06.781.19l.02.01c.56.3 1.2.45 1.831.45c.63 0 1.271-.16 1.831-.45l.02-.01c.24-.12.5-.19.78-.19c.591 0 1.151.3 1.472.79l.01.021a3.96 3.96 0 0 0 3.172 1.833h.02c.88.04 1.6.771 1.64 1.643v.02a3.91 3.91 0 0 0 1.832 3.175l.02.01c.74.481.967 1.574.567 2.365c-.584 1.17-.204 2.442.127 3.633c.238.856.005 1.529-.336 1.888c-.188.198-.737.617-1.172 1.156c-.354.44-.557.986-1.037 1.328c-1.07.763-6.432-.297-7.057.22z");
}

.emn3bbbwu {
  stop-color: var(--svg-color--a67eba, #A67EBA);
  stop-opacity: 0;
}

.f1z1-nbfa {
  stop-color: var(--svg-color--d2c4f4, #D2C4F4);
}

.fgs1m7k9t {
  stop-color: var(--svg-color--b2aab1, #B2AAB1);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fulqksb4s {
  stop-color: var(--svg-color--9f9698, #9F9698);
}

.g-wv0k8pb {
  stop-color: var(--svg-color--825039, #825039);
}

.g8yxhacwl {
  stop-color: var(--svg-color--fbf5ff, #FBF5FF);
}

.gt8aa0b7u {
  stop-color: var(--svg-color--e39ab1, #E39AB1);
}

.hsx9h6b8s {
  stop-color: var(--svg-color--81464b, #81464B);
}

.hx9bp5b9f {
  d: path("M28.453 13.117c.38-.741.144-1.689-.487-2.19L17.65 14.455l3.482-10.348c-.32-.47-.87-.771-1.45-.771c-.271 0-.541.06-.781.19l-.02.01c-.56.3-1.191.45-1.832.45c-.35 0-.7-.05-1.04-.14l-2.592 13.203l.87.23l.421 1.553l13.636-2.706c-.253-1.01-.372-2.044.11-3.008");
}

.i0ov7pbkr {
  stop-color: var(--svg-color--b4adaf, #B4ADAF);
}

.i1mx43b6a {
  stop-color: var(--svg-color--d7a392, #D7A392);
}

.i7hclabdf {
  stop-color: var(--svg-color--afa7af, #AFA7AF);
}

.idaa35bsz {
  stop-color: var(--svg-color--b3aeb6, #B3AEB6);
  stop-opacity: 0;
}

.ij7yqxb5u {
  d: path("M29.018 16.149c-.38-.713-.375-1.603-.06-2.195c.617-1.157.026-3.057-.874-3.855c-.631-.56-1.034-1.133-1.276-2.224c-.27-1.223-1.163-2.38-2.72-2.654c-.977-.173-1.553-.62-2.187-1.298c-.719-.767-2.35-1.693-3.885-.873c-.557.297-1.565.162-2.343-.098c-1.48-.493-2.854.098-3.7 1.082a3.33 3.33 0 0 1-1.942 1.135c-1.77.347-2.684 1.697-2.84 2.854c-.137 1.023-.636 1.458-1.308 2.132c-.839.84-1.39 2.709-.901 3.673c.242.478.197 1.243-.06 1.95L3.44 20.152c-.475 1.236-.727 2.423-.727 3.05c0 3.327 2.754 6.084 6.087 6.084c.893 0 2.292-.279 3.403-.764l4.278-1.527c.646-.238 1.334-.088 1.816.06c1.272.389 2.457.165 3.74-1.12c.84-.84 1.274-.882 2.088-1.145c3.306-1.072 1.905-3 3.87-4.845c1.058-.682 1.594-2.724 1.023-3.796");
}

.j5zk2lpac {
  d: path("M22.713 16.006c0-3.726-3.022-6.751-6.744-6.751a6.72 6.72 0 0 0-5.574 2.955l-5.413 8.775a4.27 4.27 0 0 0-.85 2.574a4.315 4.315 0 0 0 4.312 4.317c.87 0 1.681-.26 2.361-.71l.02-.01c.05-.031.1-.071.15-.111l8.236-5.129a6.72 6.72 0 0 0 3.502-5.91");
}

.j9s8ppcjh {
  stop-color: var(--svg-color--d5cfdd, #D5CFDD);
}

.jd5jblbwl {
  stop-color: var(--svg-color--9f75af, #9F75AF);
}

.jkq8hibuy {
  stop-color: var(--svg-color--f2bc9f, #F2BC9F);
}

.kenwmzdet {
  stop-color: var(--svg-color--c4b9cf, #C4B9CF);
  stop-opacity: 0;
}

.kfqpxobbi {
  stop-color: var(--svg-color--bdabe5, #BDABE5);
}

.krh6ezffp {
  stop-color: var(--svg-color--ac956a, #AC956A);
  stop-opacity: 0;
}

.ksyvuybje {
  d: path("M9.664 11.36c0-.985-.757-3.837 0-4.903c.758-1.066 2.49-1.11 3.272-2.321l.01-.02c.32-.49.88-.791 1.471-.791c.27 0 .54.06.78.19l.02.01c.56.3 1.201.45 1.832.45c.63 0 1.27-.16 1.83-.45l.02-.01c.241-.12.501-.19.781-.19c.59 0 1.151.3 1.471.79l.01.021a3.96 3.96 0 0 0 3.172 1.833h.02c.88.04 1.601.771 1.641 1.643v.02a3.91 3.91 0 0 0 1.832 3.175l.02.01c.74.481.967 1.574.567 2.365c-.584 1.17-.204 2.442.127 3.633c.238.856.004 1.529-.337 1.888c-.188.198-.737.617-1.172 1.156c-.354.44-.557.986-1.037 1.328c-1.069.763-6.431-.297-7.056.22z");
}

.lfgbnlbog {
  stop-color: var(--svg-color--955276, #955276);
  stop-opacity: 0;
}

.lr6frfbnr {
  stop-color: var(--svg-color--e099bc, #E099BC);
  stop-opacity: 0;
}

.lw6u3_bwo {
  stop-color: var(--svg-color--b3acb2, #B3ACB2);
}

.mhexay85v {
  stop-color: var(--svg-color--8a7d87, #8A7D87);
  stop-opacity: 0;
}

.mplyt5utb {
  stop-color: var(--svg-color--703933, #703933);
  stop-opacity: 0;
}

.nixet79fe {
  d: path("M10.52 11.455c0-.894-.688-3.484 0-4.452c.378-.532 2.128-1.69 2.527-2.254c.398-.563 1.167-.811 1.703-.811c.245 0 .672.275.89.393c.53.264.992.418 1.586.418c.573 0 1.154-.145 1.663-.41l.018-.008c.218-.11.455-.173.71-.173c.535 0 1.044.273 1.335.719l.01.018a3.6 3.6 0 0 0 2.88 1.665h.018c.8.036 1.454.7 1.49 1.492v.018a3.55 3.55 0 0 0 1.663 2.883l.018.01c.673.436.88 1.429.516 2.147c-.53 1.062-.186 2.218.115 3.3c.216.777.004 1.388-.306 1.714c-.17.18-.67.56-1.064 1.05c-.321.399-.506.896-.942 1.206c-.97.693-5.84-.27-6.408.199z");
}

.nnggy_qgf {
  stop-color: var(--svg-color--a2755f, #A2755F);
}

.o0jr_9bvb {
  d: path("M11.5 19a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9");
}

.o18av-bbp {
  stop-color: var(--svg-color--925742, #925742);
}

.okj1n1b5y {
  stop-color: var(--svg-color--b4afb6, #B4AFB6);
}

.ouixxkbqt {
  stop-color: var(--svg-color--c6a2ec, #C6A2EC);
}

.pe-jeg5yi {
  stop-color: var(--svg-color--7e4b3b, #7E4B3B);
}

.q4lhr2_ng {
  stop-color: var(--svg-color--daa68f, #DAA68F);
  stop-opacity: 0;
}

.qa7w3vb0h {
  stop-color: var(--svg-color--894a39, #894A39);
}

.qh3x315pc {
  stop-color: var(--svg-color--999092, #999092);
  stop-opacity: 0;
}

.qrv_v0fil {
  stop-color: var(--svg-color--e0dbe6, #E0DBE6);
}

.s3c776-lb {
  stop-color: var(--svg-color--c6a3f6, #C6A3F6);
  stop-opacity: 0;
}

.smn0rc_gy {
  stop-color: var(--svg-color--beb0c9, #BEB0C9);
  stop-opacity: 0;
}

.t_4epc1wz {
  stop-color: var(--svg-color--995f4c, #995F4C);
  stop-opacity: 0;
}

.t-wepab3b {
  stop-color: var(--svg-color--c3c0c7, #C3C0C7);
}

.t2gmspbti {
  stop-color: var(--svg-color--bfacc3, #BFACC3);
}

.t7bfa8ktb {
  stop-color: var(--svg-color--99604c, #99604C);
}

.tjug89thd {
  stop-color: var(--svg-color--c5b3c3, #C5B3C3);
  stop-opacity: 0;
}

.tyyksibfr {
  stop-color: var(--svg-color--8e5340, #8E5340);
}

.u-4y4kb3o {
  stop-color: var(--svg-color--9c8a92, #9C8A92);
  stop-opacity: 0;
}

.vwdr7db7z {
  stop-color: var(--svg-color--fccba0, #FCCBA0);
}

.wnvb9nk5o {
  stop-color: var(--svg-color--8f634e, #8F634E);
}

.x64fbvbre {
  stop-color: var(--svg-color--fffdb1, #FFFDB1);
}

.x84mftbpr {
  stop-color: var(--svg-color--703a29, #703A29);
}

.xj6qmjb6r {
  stop-color: var(--svg-color--b7b1b8, #B7B1B8);
}

.y00n1z9pq {
  fill: var(--svg-color--c3927e, #C3927E);
  d: path("M15.406 15.031c0 2.486-1.72 4.469-4.1 4.469c-9.547-.812 2.843-8.656 4.1-4.469");
}

.y0eooo6-k {
  stop-color: var(--svg-color--83513a, #83513A);
  stop-opacity: 0;
}

.y6j0-02vk {
  stop-color: var(--svg-color--b6a5b4, #B6A5B4);
}

.yfq9ocb1a {
  stop-color: var(--svg-color--ac99a4, #AC99A4);
  stop-opacity: 0;
}

.yp00hj66r {
  stop-color: var(--svg-color--b5a5bc, #B5A5BC);
}

.yud86p90m {
  d: path("M29.719 16.156c-.4-.751-.395-1.688-.063-2.312c.65-1.22.027-3.221-.922-4.063c-.665-.59-1.089-1.193-1.343-2.344c-.285-1.288-1.227-2.507-2.868-2.796c-1.029-.182-1.635-.654-2.304-1.368c-.757-.807-2.476-1.784-4.094-.92c-.587.313-1.648.17-2.469-.103c-1.558-.52-3.008.103-3.898 1.14A3.5 3.5 0 0 1 9.71 4.587c-1.865.366-2.828 1.789-2.992 3.008c-.145 1.078-.67 1.537-1.38 2.246c-.883.885-1.463 2.855-.948 3.87c.255.505.208 1.31-.063 2.056l-1.562 4.609C2.266 21.677 2 22.928 2 23.589c0 3.506 2.902 6.41 6.414 6.41c.94 0 2.415-.293 3.586-.804l4.508-1.61c.68-.25 1.406-.092 1.914.063c1.34.41 2.589.175 3.941-1.18c.885-.884 1.343-.929 2.2-1.206c3.484-1.13 2.007-3.16 4.078-5.106c1.115-.718 1.68-2.87 1.078-4");
}

.zioba5rfe {
  stop-color: var(--svg-color--b6b0b4, #B6B0B4);
  stop-opacity: 0;
}

</style>
