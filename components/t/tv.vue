<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btga03z5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tv" /></template>
<style>
.btga03z5i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.53 1.97L12 5.439l3.47-3.469q.052-.053.113-.094t.13-.069t.141-.043T16 1.75t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.106.105.163.243t.057.287t-.057.287t-.163.243l-2.719 2.72h3.314q2.123 0 3.624 1.501t1.501 3.624v4.75q0 2.123-1.501 3.624t-3.624 1.501H6.875q-2.123 0-3.624-1.501T1.75 15.625v-4.75q0-2.123 1.501-3.624T6.875 5.75h3.314L7.47 3.03q-.106-.105-.163-.243T7.25 2.5t.057-.287t.163-.243t.243-.163T8 1.75t.287.057t.243.163");
}

</style>
