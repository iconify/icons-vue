<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhhffll5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:subwoofer" /></template>
<style>
.bhhffll5e {
  fill: currentColor;
  d: path("M5.5 21.5v-1h4.308v1zm8.692 0v-1H18.5v1zM5.977 19q-.7 0-1.156-.53t-.338-1.224l2.102-13q.092-.548.507-.897T8.06 3h7.88q.545 0 .967.347t.508.9l2.108 13q.117.694-.327 1.223t-1.148.53zM12 15.846q1.362 0 2.306-.944t.944-2.306t-.944-2.305T12 9.346t-2.306.945t-.944 2.305t.944 2.306t2.306.944m0-1q-.928 0-1.589-.663t-.661-1.595t.661-1.587T12 10.346t1.589.66t.661 1.585t-.661 1.59t-1.589.665m0-7.615q.29 0 .51-.21t.22-.521q0-.29-.22-.51t-.52-.22t-.51.22t-.21.52t.21.51t.52.21");
}

</style>
