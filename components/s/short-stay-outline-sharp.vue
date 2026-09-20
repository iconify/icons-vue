<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tibz6ac0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:short-stay-outline-sharp" /></template>
<style>
.tibz6ac0p {
  fill: currentColor;
  d: path("M5.23 20h5.58zm-1 1V3h11v7.364q-.288.075-.528.157q-.24.083-.471.173V4h-9v7h8.154v.156q-.339.195-.631.425t-.5.419H5.23v8h5.579q.16.292.31.545t.326.455zM8.666 8.566Q8.23 8.133 8.23 7.5t.434-1.066Q9.098 6 9.73 6t1.066.434t.434 1.066t-.434 1.066Q10.364 9 9.731 9t-1.066-.434M9.23 18.5h.948v-1.538q-.029-.181-.046-.362q-.017-.18-.017-.361q0-.235.028-.45t.087-.427V13.5h-1v2h-2v1h2zm4.587 1.685Q12.5 18.869 12.5 17.003t1.316-3.185t3.181-1.318q1.867 0 3.185 1.316Q21.5 15.13 21.5 16.997t-1.315 3.185t-3.182 1.318t-3.185-1.315m4.857-.964l.546-.546l-1.836-1.829v-2.73h-.77v3.046z");
}

</style>
