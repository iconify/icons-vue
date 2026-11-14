<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xszzaobgw"/><path class="oslqirbld"/><path class="sv7c19h2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:podcast-episode-lock" /></template>
<style>
.oslqirbld {
  d: path("M13.5 2.5v3h3M9 13a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.sv7c19h2e {
  d: path("M7.348 15.652q-.13-.13-.247-.273q-.117-.142-.219-.295q-.103-.153-.189-.316q-.087-.162-.158-.333q-.07-.17-.124-.346t-.089-.357t-.054-.364T6.25 13q0-.184.018-.367t.054-.364t.09-.357t.124-.347t.157-.332q.087-.163.189-.316t.219-.295q.117-.143.247-.273q.131-.13.273-.247t.296-.219t.315-.19q.163-.086.333-.157q.17-.07.346-.124q.177-.053.357-.089q.181-.036.364-.054q.184-.018.368-.018t.368.018t.364.054t.357.089t.346.124t.333.157t.315.19q.153.102.296.219q.142.117.273.247q.103.104.199.215q.095.112.182.231q.086.119.163.244t.144.256t.123.266t.102.276q.045.139.08.282q.034.143.058.288q.023.145.035.292q.012.146.012.293t-.011.293t-.034.292q-.022.145-.056.288t-.079.283t-.1.276q-.056.135-.122.267M10 14v4.75m5-1.25h6v4h-6Zm1.5 0v-1a1.5 1.5 0 0 1 3 0v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xszzaobgw {
  d: path("M12.243 21.5H3.5v-19h10l3 3v6.957");
}

</style>
