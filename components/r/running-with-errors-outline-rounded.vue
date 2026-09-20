<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdpkryb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:running-with-errors-outline-rounded" /></template>
<style>
.kdpkryb7f {
  fill: currentColor;
  d: path("M20.336 17.856q-.144-.144-.144-.356V11q0-.213.144-.356t.357-.144t.356.144t.143.356v6.5q0 .213-.144.356q-.143.144-.356.144t-.356-.144m-.077 2.616q-.182-.181-.182-.433t.182-.434t.433-.182t.434.182t.182.434t-.182.433t-.434.182q-.251 0-.433-.182M11.692 21q-1.867 0-3.51-.708t-2.857-1.924T3.4 15.512t-.709-3.509t.709-3.51t1.924-2.859t2.857-1.925T11.692 3q1.645 0 3.217.585q1.572.584 2.765 1.701q.265.248.265.58t-.243.573l-4.63 4.611q-.38.379-.877.171t-.497-.742V4q-3.35 0-5.675 2.325T3.692 12t2.325 5.675T11.692 20q1.677 0 3.177-.693t2.647-1.916q.157-.16.365-.143t.361.175t.14.359t-.172.355q-1.293 1.346-2.974 2.104q-1.682.759-3.544.759");
}

</style>
