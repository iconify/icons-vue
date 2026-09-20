<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjgnadcey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:reset-shadow-outline-rounded" /></template>
<style>
.mjgnadcey {
  fill: currentColor;
  d: path("M13.318 19.682Q12 18.363 12 16.5t1.318-3.182T16.5 12t3.182 1.318T21 16.5t-1.318 3.182T16.5 21t-3.182-1.318m3.163.299q-.558-.747-.878-1.612t-.32-1.869t.323-1.879T16.48 13q-1.443 0-2.462 1.029T13 16.5t1.02 2.462t2.46 1.019M12 5Q9.075 5 7.038 7.038T5 12q0 2.108 1.11 3.79Q7.222 17.474 9 18.309V15.5q0-.213.143-.357T9.5 15t.357.143t.143.357v3.692q0 .349-.23.578t-.578.23H5.5q-.213 0-.357-.143T5 19.5t.143-.357T5.5 19h2.812q-1.916-1-3.114-2.851T4 12q0-1.664.626-3.118T6.34 6.34t2.542-1.714T12 4q2.562 0 4.562 1.418t2.884 3.688q.073.188 0 .38q-.073.193-.261.266q-.189.073-.384-.01t-.268-.27q-.756-1.97-2.513-3.221T12 5");
}

</style>
