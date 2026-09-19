<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="acfwhjb4q"/><path class="bw8dtxsgb"/></g><circle class="kk9yyjwli"/><circle class="cdkoi1bgj"/><circle class="rip50o15n"/><circle class="hkiq67aep"/><circle class="nz9yjrbri"/><circle class="afulovbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vtv-go" /></template>
<style>
.acfwhjb4q {
  d: path("m5.593 9.264l7.427 13.023c.767 1.33 2.296 1.33 3.064 0l4.595-8.426v9.447h7.149V13.86l4.085 8.426c.767 1.328 2.297 1.328 3.064 0L42.4 9.269c.297-.41-.018-.77-.531-.77h-4.596c-.515 0-1.235.363-1.493.801l-2.336 4.561l-2.335-4.557c-.257-.445-.983-.804-1.495-.804H18.38c-.513 0-1.18.316-1.407.771l-2.423 4.59l-2.416-4.575c-.172-.476-.903-.786-1.414-.786H6.126c-.513-.01-.807.334-.534.763zm22.235 4.598h5.617m-12.766 0l3.096-5.361m.223 28.242a2.043 2.043 0 0 1-2.042-2.042v-1.328a2.042 2.042 0 1 1 4.085 0V34.7a2.04 2.04 0 0 1-2.043 2.042m-3.983-5.412v6.127a2.042 2.042 0 0 1-3.487 1.445");
}

.afulovbjk {
  cx: 31.81px;
  cy: 32.403px;
  r: 0.766px;
  fill: currentColor;
}

.bw8dtxsgb {
  d: path("M17.973 31.33c1.128 0 2.043.914 2.043 2.043V34.7a2.042 2.042 0 1 1-4.085 0v-1.328c0-1.128.914-2.042 2.042-2.042");
}

.cdkoi1bgj {
  cx: 30.023px;
  cy: 28.828px;
  r: 0.766px;
  fill: currentColor;
}

.hkiq67aep {
  cx: 30.023px;
  cy: 30.615px;
  r: 0.766px;
  fill: currentColor;
}

.kk9yyjwli {
  cx: 28.236px;
  cy: 28.828px;
  r: 0.766px;
  fill: currentColor;
}

.nz9yjrbri {
  cx: 31.81px;
  cy: 30.615px;
  r: 0.766px;
  fill: currentColor;
}

.rip50o15n {
  cx: 31.81px;
  cy: 28.828px;
  r: 0.766px;
  fill: currentColor;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
