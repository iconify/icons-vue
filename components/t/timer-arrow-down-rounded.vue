<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3uwdhblm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:timer-arrow-down-rounded" /></template>
<style>
.r3uwdhblm {
  fill: currentColor;
  d: path("M4.207 17.13q-1.86-1.87-1.86-4.534t1.86-4.533t4.524-1.87q1.185 0 2.248.402q1.063.403 1.898 1.128l.62-.62q.14-.14.34-.133t.348.153q.14.14.14.335t-.14.334l-.6.62q.725.834 1.137 1.9t.413 2.284q0 2.663-1.87 4.534T8.73 19t-4.524-1.87m3.1-12.36q-.213 0-.356-.144t-.143-.357t.143-.357t.357-.143h2.884q.214 0 .357.143t.143.357t-.143.357t-.357.143zm1.78 7.99q.144-.143.144-.356V9.596q0-.213-.143-.356t-.357-.144t-.357.144t-.143.356v2.808q0 .213.143.357t.357.143t.357-.143m9.731 5.674l-2.011-2.012q-.16-.165-.16-.357t.166-.35q.165-.16.356-.163q.192-.003.351.163l1.364 1.363V5.5q0-.213.143-.357Q19.17 5 19.384 5q.213 0 .356.143t.144.357v11.585l1.369-1.37q.16-.16.354-.16t.353.16t.16.354t-.16.354l-2.011 2.012q-.242.242-.565.242t-.566-.242");
}

</style>
