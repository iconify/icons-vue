<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGTHm46bGA)" class="jkjudaboq"/><path fill="url(#SVGcOblcdtx)" clip-rule="evenodd" class="e9epgwbnk"/><path fill="url(#SVGKXd5EcEu)" clip-rule="evenodd" class="el1ozczul"/><path fill="url(#SVGYNwzKexw)" class="yz59zip3s"/><defs><linearGradient id="SVGTHm46bGA" x1="8.311" x2="20.827" y1="11.714" y2="15.125" gradientUnits="userSpaceOnUse"><stop class="q0dfisbly"/><stop offset="1" class="d4gvsjuxa"/></linearGradient><linearGradient id="SVGcOblcdtx" x1="18.66" x2="9.323" y1="11.468" y2="2.473" gradientUnits="userSpaceOnUse"><stop class="q0dfisbly"/><stop offset="1" class="w3ttn_bra"/></linearGradient><linearGradient id="SVGKXd5EcEu" x1="14.023" x2="5.231" y1="16.707" y2="11.849" gradientUnits="userSpaceOnUse"><stop class="ouz-bjbok"/><stop offset="1" class="wrzqkyhwx"/></linearGradient><linearGradient id="SVGYNwzKexw" x1="9.054" x2="15.173" y1="11.617" y2="19.089" gradientUnits="userSpaceOnUse"><stop class="j9q2sccra"/><stop offset=".984" class="jtkn5w0gi"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rabby" /></template>
<style>
.d4gvsjuxa {
  stop-color: var(--svg-color--abb7ff, #abb7ff);
}

.e9epgwbnk {
  fill-rule: evenodd;
  d: path("M16.077 8.444c.13-.053.11-.253.074-.41c-.082-.362-1.5-1.82-2.833-2.473c-1.815-.89-3.152-.843-3.35-.433c.37.788 2.085 1.529 3.875 2.302c.764.33 1.541.666 2.234 1.014");
}

.el1ozczul {
  fill-rule: evenodd;
  d: path("M13.774 16.38c-.367-.145-.782-.28-1.254-.4c.503-.937.609-2.322.134-3.199c-.666-1.229-1.503-1.883-3.446-1.883c-1.07 0-3.947.374-3.998 2.874q-.009.393.018.724l5.255.04a18.7 18.7 0 0 1-1.953 2.696c.698.186 1.273.342 1.802.486c.501.136.96.26 1.44.388a22 22 0 0 0 2.002-1.726");
}

.ft5dv1b6b {
  fill: none;
}

.j9q2sccra {
  stop-color: var(--svg-color--8898ff, #8898ff);
}

.jkjudaboq {
  d: path("M20.908 13.17c.707-1.644-2.788-6.235-6.127-8.148c-2.105-1.482-4.298-1.279-4.742-.628c-.975 1.428 3.228 2.638 6.038 4.05a3.25 3.25 0 0 0-1.508 1.39c-1.048-1.19-3.347-2.216-6.046-1.39c-1.819.556-3.33 1.868-3.914 3.85a1.1 1.1 0 0 0-.464-.103c-.632 0-1.145.533-1.145 1.191s.513 1.191 1.145 1.191c.117 0 .483-.081.483-.081l5.855.044c-2.341 3.865-4.192 4.43-4.192 5.1s1.77.488 2.436.238c3.182-1.195 6.6-4.919 7.187-5.99c2.463.32 4.533.357 4.994-.715");
}

.jtkn5w0gi {
  stop-color: var(--svg-color--6277f1, #6277f1);
}

.ouz-bjbok {
  stop-color: var(--svg-color--465eed, #465eed);
}

.q0dfisbly {
  stop-color: var(--svg-color--8697ff, #8697ff);
}

.w3ttn_bra {
  stop-color: var(--svg-color--5156d8, #5156d8);
  stop-opacity: 0;
}

.wrzqkyhwx {
  stop-color: var(--svg-color--8697ff, #8697ff);
  stop-opacity: 0;
}

.yz59zip3s {
  d: path("M4.539 14.24c.215 1.898 1.252 2.642 3.371 2.863c2.12.22 3.335.072 4.954.225c1.352.128 2.559.845 3.006.598c.403-.223.178-1.029-.361-1.546c-.7-.67-1.667-1.135-3.369-1.3c.34-.967.244-2.322-.282-3.06c-.762-1.065-2.168-1.547-3.948-1.337c-1.859.22-3.64 1.173-3.371 3.556");
}

</style>
