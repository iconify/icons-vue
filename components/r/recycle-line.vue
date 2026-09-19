<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpwrgmboq.css';
import '../../css/x/xv2a8c3hx.css';
import '../../css/l/l6u5li4qx.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 rpwrgmboq"/><path class="clr-i-outline clr-i-outline-path-2 xv2a8c3hx"/><path class="clr-i-outline clr-i-outline-path-3 l6u5li4qx"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:recycle-line" /></template>
