<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6i2yccpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:volunteer-activism-sharp" /></template>
<style>
.o6i2yccpo {
  fill: currentColor;
  d: path("M1 22h4V11H1zm13 0l8-3v-2h-9l-2.1-.75l.35-.925L13 16h4v-2l-8.025-3H7v9.025zm2-9l-4.15-4.05q-.775-.75-1.312-1.662T10 5.3q0-1.375.963-2.337T13.3 2q.8 0 1.5.338t1.2.912q.5-.575 1.2-.913T18.7 2q1.375 0 2.338.963T22 5.3q0 1.075-.525 1.988t-1.3 1.662z");
}

</style>
