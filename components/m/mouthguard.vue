<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqvj7x_mx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mouthguard" /></template>
<style>
.vqvj7x_mx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.25 6.001q-2.999 0-3 2.999q0 4.655 2.866 7.301Q7.769 18.75 12 18.75t6.884-2.449Q21.75 13.655 21.75 9q-.002-2.998-3-2.998q-1.499 0-2.249.749Q15.751 6 14.25 6T12 6.75Q11.25 6 9.75 6t-2.251.751q-.75-.75-2.249-.75M12 14q3.661 0 4.829-2.335q.033-.066.079-.125q.045-.058.101-.107q.055-.048.12-.085q.064-.036.134-.06q.07-.023.143-.032t.147-.004t.145.025t.137.052q.134.067.232.18q.097.112.145.254q.047.141.036.29q-.01.149-.077.282Q16.589 15.5 12 15.5t-6.171-3.165q-.033-.066-.052-.137q-.02-.071-.025-.145t.004-.147t.032-.143q.024-.07.06-.134q.037-.065.085-.12q.049-.056.107-.101q.059-.046.125-.079t.137-.052t.145-.025t.147.004t.143.032q.07.024.134.06q.065.037.12.085q.056.049.101.107q.046.059.079.125Q8.339 14 12 14");
}

</style>
