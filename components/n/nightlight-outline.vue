<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl1itr8vi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nightlight-outline" /></template>
<style>
.wl1itr8vi {
  fill: currentColor;
  d: path("M14.5 21q-1.858 0-3.497-.707T8.139 18.36t-1.931-2.864t-.708-3.502t.71-3.5T8.14 5.64t2.864-1.93Q12.651 3 14.5 3q.812 0 1.558.139q.746.138 1.442.442q-1.833 1.498-2.916 3.674Q13.5 9.43 13.5 12t1.084 4.745T17.5 20.42q-.696.304-1.442.443Q15.312 21 14.5 21m0-1h.525q.25 0 .475-.05q-1.425-1.65-2.212-3.687T12.5 12t.788-4.262T15.5 4.05Q15.275 4 15.025 4H14.5q-3.325 0-5.663 2.338T6.5 12t2.338 5.663T14.5 20m-2-8");
}

</style>
