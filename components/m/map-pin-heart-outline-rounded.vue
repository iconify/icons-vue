<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dz1zrtoto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:map-pin-heart-outline-rounded" /></template>
<style>
.dz1zrtoto {
  fill: currentColor;
  d: path("M12 19.677q2.82-2.454 4.458-4.991t1.638-4.39q0-2.744-1.737-4.53Q14.62 3.981 12 3.981T7.641 5.766t-1.737 4.53q0 1.852 1.638 4.39T12 19.677m-.47.802q-.234-.077-.432-.25q-1.067-.981-2.164-2.185q-1.096-1.203-1.99-2.493t-1.468-2.633t-.572-2.622q0-3.173 2.066-5.234Q9.037 3 12 3t5.03 2.062q2.066 2.061 2.066 5.234q0 1.279-.572 2.613q-.572 1.333-1.458 2.632q-.885 1.3-1.981 2.494T12.92 20.21q-.198.173-.442.26t-.479.086t-.47-.077m.47-6.737q1.177-1.076 1.802-1.701t.973-1.049q.342-.423.476-.77q.134-.349.134-.791q0-.765-.544-1.32q-.545-.553-1.31-.553q-.448 0-.859.183q-.41.184-.672.501q-.261-.317-.67-.5q-.407-.184-.86-.184q-.766 0-1.31.554q-.544.553-.544 1.319q0 .448.13.78t.454.756q.348.423.977 1.048T12 13.743");
}

</style>
