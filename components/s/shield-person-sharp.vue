<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jun_68bdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shield-person-sharp" /></template>
<style>
.jun_68bdl {
  fill: currentColor;
  d: path("M14.129 11.629Q15 10.758 15 9.5t-.871-2.129T12 6.5t-2.129.871T9 9.5t.871 2.129T12 12.5t2.129-.871M12 20.962q-3.227-.964-5.113-3.712T5 11.1V5.692l7-2.615l7 2.615V11.1q0 3.402-1.886 6.15T12 20.962m0-1.062q1.34-.436 2.43-1.305q1.09-.868 1.882-2.028q-.999-.511-2.084-.789Q13.142 15.5 12 15.5t-2.228.278t-2.084.79q.793 1.159 1.882 2.027q1.09.869 2.43 1.305");
}

</style>
