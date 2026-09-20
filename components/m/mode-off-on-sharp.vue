<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbh076bxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mode-off-on-sharp" /></template>
<style>
.sbh076bxd {
  fill: currentColor;
  d: path("M11.643 11.857q-.143-.143-.143-.357V3.346q0-.213.143-.357T12 2.847t.357.143t.143.357V11.5q0 .214-.143.357T12 12t-.357-.143m-2.761 7.517q-1.455-.626-2.542-1.713t-1.714-2.543T4 12q0-1.467.529-2.828t1.498-2.445q.14-.177.344-.164t.375.183q.14.14.115.329t-.159.366q-.829.938-1.266 2.119Q5 10.74 5 12q0 2.925 2.038 4.963T12 19t4.963-2.037T19 12q0-1.265-.434-2.449q-.433-1.184-1.274-2.122q-.134-.171-.16-.367t.116-.335q.165-.165.37-.168q.203-.003.344.168q.974 1.085 1.506 2.442T20 12q0 1.664-.626 3.118T17.66 17.66t-2.542 1.714T12 20t-3.118-.626");
}

</style>
