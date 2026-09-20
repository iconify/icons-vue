<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ux9veiblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:no-accounts-outline-rounded" /></template>
<style>
.ux9veiblq {
  fill: currentColor;
  d: path("m14.623 10.989l-4.092-4.093q.292-.188.664-.292t.844-.104q1.244 0 2.102.868Q15 8.236 15 9.5q0 .414-.113.834q-.114.42-.264.655m-8.427 6.496q1.333-.956 2.735-1.47Q10.333 15.5 12 15.5q1.18 0 2.151.288t1.593.593l-3.892-3.892q-1.194-.093-1.974-.863t-.853-1.964L6.041 6.677q-.916 1.025-1.478 2.359Q4 10.369 4 12q0 1.667.593 3.025t1.603 2.46m11.835-.239q.838-1.025 1.404-2.32Q20 13.631 20 12q0-3.325-2.337-5.663T12 4q-1.535 0-2.868.527q-1.334.527-2.378 1.442zM8.48 20.3q-1.642-.701-2.86-1.92T3.7 15.52T3 11.997t.701-3.519t1.92-2.858t2.86-1.919T12.003 3t3.519.701t2.858 1.92t1.919 2.857t.701 3.519q0 1.88-.701 3.522t-1.92 2.86t-2.857 1.92t-3.519.701t-3.522-.701M12 20q1.402 0 2.73-.503q1.33-.503 2.343-1.305q-.975-.782-2.361-1.237T12 16.5t-2.664.426t-2.409 1.266q1.014.802 2.342 1.305T12 20m0-1.75");
}

</style>
