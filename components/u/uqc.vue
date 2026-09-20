<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f6eqs9bhp"/><path class="ozjfy78mb"/><path class="zmwkdj5zh"/><path class="ccpxz0byl"/><path class="hcdtdjbfq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:uqc" /></template>
<style>
.ccpxz0byl {
  fill: var(--svg-color--cf3339, #cf3339);
  d: path("M15.193 20.708H8.806l1.742-2.903h2.903z");
}

.f6eqs9bhp {
  fill: var(--svg-color--e85c50, #e85c50);
  d: path("M15.194 14.322V3.29l2.903 5.806v11.418c-.87.195-2.903.195-2.903.195zl-1.742 3.484H10.55l-1.742-3.484v6.387s-1.786.03-2.903-.195V9.096L8.807 3.29v11.032z");
}

.ft5dv1b6b {
  fill: none;
}

.hcdtdjbfq {
  fill: var(--svg-color--e33937, #e33937);
  d: path("m10.548 17.804l-1.742 2.903V14.32zm4.645 2.903l-1.742-2.903l1.742-3.484z");
}

.ozjfy78mb {
  fill: var(--svg-color--cf3339, #cf3339);
  d: path("M5.903 20.514C4.694 20.232 3 19.037 3 17.823V3.29l2.903 5.806zm12.194 0C19.306 20.232 21 19.037 21 17.823V3.29l-2.903 5.806z");
}

.zmwkdj5zh {
  fill: var(--svg-color--e33936, #e33936);
  d: path("M5.903 9.096L3 3.29h5.806zm12.194 0L21 3.29h-5.806z");
}

</style>
