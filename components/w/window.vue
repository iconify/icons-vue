<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2o-8kr3y.css';
import '../../css/q/qx05z4bvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2o-8kr3y"/><path class="qx05z4bvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:window" /></template>
