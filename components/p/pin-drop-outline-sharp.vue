<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zz8ip4btq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pin-drop-outline-sharp" /></template>
<style>
.zz8ip4btq {
  fill: currentColor;
  d: path("M12 16.975q2.456-2.154 3.728-4.177T17 9.016q0-2.212-1.4-3.614T12 4T8.4 5.402T7 9.016q0 1.759 1.272 3.782T12 16.975m0 1.275q-2.967-2.427-4.484-4.771T6 9.016q0-2.645 1.68-4.33Q9.362 3 12 3t4.32 1.686Q18 6.37 18 9.016q0 2.119-1.516 4.453T12 18.25m0-7.634q.671 0 1.143-.473q.472-.472.472-1.143t-.472-1.143q-.472-.473-1.143-.473t-1.143.473T10.385 9t.472 1.143t1.143.472M6 21v-1h12v1zm6-12");
}

</style>
