<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylgrrwbun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:short-stay-outline" /></template>
<style>
.ylgrrwbun {
  fill: currentColor;
  d: path("M7.23 20h3.58h-5.58zm-1.384 1q-.666 0-1.14-.475t-.475-1.14V4.615q0-.666.474-1.14T5.846 3h7.77q.666 0 1.14.475t.475 1.14v5.752q-.289.071-.529.154t-.471.173V4.615q0-.269-.173-.442T13.616 4h-7.77q-.269 0-.442.173t-.173.443v7.178q.411-.39.924-.592Q6.667 11 7.23 11h6.154v.156q-.339.195-.631.425t-.5.419H7.23q-.825 0-1.413.588T5.231 14v5.385q0 .269.173.442t.442.173h4.964q.16.292.31.545t.326.455zM8.665 8.566Q8.23 8.133 8.23 7.5t.434-1.066Q9.098 6 9.73 6t1.066.434t.434 1.066t-.434 1.066Q10.364 9 9.731 9t-1.066-.434M9.23 18.5h.948v-1.538q-.029-.181-.046-.362q-.017-.18-.017-.361q0-.235.028-.45t.087-.427V13.5h-1v2h-2v1h2zm4.587 1.685Q12.5 18.869 12.5 17.003t1.316-3.185t3.181-1.318q1.867 0 3.185 1.316Q21.5 15.13 21.5 16.997t-1.315 3.185t-3.182 1.318t-3.185-1.315m4.857-.964l.546-.546l-1.836-1.829v-2.73h-.77v3.046z");
}

</style>
