<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6coo0boo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:running-with-errors-outline" /></template>
<style>
.b6coo0boo {
  fill: currentColor;
  d: path("M11.692 21q-1.867 0-3.51-.708t-2.857-1.924T3.4 15.512t-.709-3.509t.709-3.51t1.924-2.859t2.857-1.925T11.692 3q1.893 0 3.596.746t2.993 2.108l-6.589 6.569V4q-3.35 0-5.675 2.325T3.692 12t2.325 5.675T11.692 20q1.937 0 3.627-.905q1.69-.904 2.873-2.46v1.519q-1.286 1.334-2.965 2.09T11.692 21m8.5-3v-7.5h1V18zm.067 2.472q-.182-.181-.182-.433t.182-.434t.433-.182t.434.182t.182.434t-.182.433t-.434.182q-.251 0-.433-.182");
}

</style>
