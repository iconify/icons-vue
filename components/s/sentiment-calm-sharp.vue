<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4nl-ihif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sentiment-calm-sharp" /></template>
<style>
.b4nl-ihif {
  fill: currentColor;
  d: path("M12 17.192q.86 0 1.644-.36q.785-.36 1.464-1.063l-.639-.596q-.569.543-1.194.826q-.625.284-1.275.284t-1.275-.284t-1.194-.826l-.639.596q.704.722 1.486 1.072q.781.351 1.622.351M8.494 20.29q-1.642-.711-2.858-1.926q-1.215-1.216-1.926-2.858T3 12t.71-3.506q.711-1.642 1.927-2.857Q6.852 4.42 8.494 3.71T12 3t3.506.71q1.642.711 2.857 1.927q1.216 1.215 1.926 2.857Q21 10.137 21 12t-.71 3.506q-.711 1.642-1.926 2.857q-1.216 1.216-2.858 1.926Q13.864 21 12 21t-3.506-.71m1.564-9.197q.604-.599.879-1.437l-.854-.216q-.183.55-.553.959t-.934.409t-.934-.409t-.553-.958l-.853.215q.275.838.878 1.437q.604.6 1.462.6t1.462-.6m6.807 0q.604-.599.88-1.437l-.855-.216q-.182.55-.553.959q-.37.409-.933.409t-.934-.409t-.553-.958l-.854.215q.275.838.88 1.437q.603.6 1.46.6q.858 0 1.462-.6");
}

</style>
