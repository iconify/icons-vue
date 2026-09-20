<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hitf40b6h"/><path class="bi3l93bwc"/><path class="nnry5hxlt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mcb" /></template>
<style>
.bi3l93bwc {
  fill: var(--svg-color--d98041, #d98041);
  d: path("M11.33 16.95H9.298c-.343 0-.558-.397-.39-.72l4.39-8.44c.237-.457.686-.74 1.172-.74h2.03c.343 0 .559.398.391.72L12.5 16.21c-.237.456-.685.74-1.171.74");
}

.ft5dv1b6b {
  fill: none;
}

.hitf40b6h {
  fill: var(--svg-color--59efec, #59efec);
  d: path("M3.449 16.95c-.343 0-.558-.398-.391-.72l4.39-8.44c.238-.458.686-.74 1.172-.74h2.032c.342 0 .558.398.39.72L6.65 16.21c-.238.457-.686.74-1.172.74z");
}

.nnry5hxlt {
  fill: var(--svg-color--fff, #fff);
  d: path("m17.197 10.436l-.983 1.906a1.5 1.5 0 0 0 0 1.361l1.308 2.536c.227.439.654.71 1.116.71h1.935c.326 0 .532-.38.372-.69l-3.004-5.823a.41.41 0 0 0-.744 0");
}

</style>
