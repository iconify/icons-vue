<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdn1sf72i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sentiment-worried" /></template>
<style>
.gdn1sf72i {
  fill: currentColor;
  d: path("M11.3 17.5h1.4q1.24 0 2.02-.73T15.5 15t-.78-1.77t-2.02-.73h-1.4q-1.24 0-2.02.73T8.5 15t.78 1.77t2.02.73m0-.885q-.885 0-1.4-.466q-.516-.466-.516-1.149t.516-1.149q.516-.467 1.4-.467h1.4q.885 0 1.4.467q.516.466.516 1.149t-.516 1.149t-1.4.467zM6.596 10H8.29q1.038 0 1.807-.683t.866-1.702h-.904q-.116.644-.611 1.072t-1.158.429H6.596zm9.096 0h1.693v-.885h-1.693q-.663 0-1.158-.427q-.495-.429-.611-1.073h-.904q.097 1.02.866 1.702q.769.683 1.807.683M8.494 20.29q-1.642-.711-2.858-1.926q-1.215-1.216-1.926-2.858T3 12t.71-3.506q.711-1.642 1.927-2.857Q6.852 4.42 8.494 3.71T12 3t3.506.71q1.642.711 2.857 1.927q1.216 1.215 1.926 2.857Q21 10.137 21 12t-.71 3.506q-.711 1.642-1.926 2.857q-1.216 1.216-2.858 1.926Q13.864 21 12 21t-3.506-.71");
}

</style>
