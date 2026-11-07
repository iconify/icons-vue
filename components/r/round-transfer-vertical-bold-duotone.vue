<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt4erfbgl.css';
import '../../css/d/dqvo1yxlg.css';
import '../../css/c/ccsmm3hcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt4erfbgl"/><path class="dqvo1yxlg"/><path class="ccsmm3hcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-transfer-vertical-bold-duotone" /></template>
