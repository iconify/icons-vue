<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qeasudnrk"/><path class="cbuss59ae"/><path class="zi3br7bkw"/><path class="etdoxvbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:radio-net" /></template>
<style>
.cbuss59ae {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.58 19.956c-3.872 1.42-8.176-.56-9.612-4.422c-1.435-3.863.54-8.146 4.413-9.566s8.176.56 9.612 4.422a7.43 7.43 0 0 1 .016 5.137");
}

.etdoxvbtc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.747 20.739q1.555-1.555 4.664-1.555h10.882q6.207 0 6.207 6.219v10.87q0 6.218-6.33 6.218H25.41q-6.219 0-6.218-6.218v-10.87");
}

.qeasudnrk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.975 9.857a3.11 3.11 0 1 1-3.11 3.11a3.117 3.117 0 0 1 3.11-3.11");
}

.zi3br7bkw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.312 15.293l8.936 8.935q.447-.38 1.163-.38h10.882q1.543 0 1.543 1.555v10.87q0 1.555-1.543 1.555H25.41q-1.554 0-1.555-1.555v-9.316l-4.272-4.283q-.39 1.174-.391 2.729");
}

</style>
