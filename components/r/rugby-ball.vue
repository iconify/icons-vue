<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2w5z4str.css';
import '../../css/b/bcmzn-obx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2w5z4str"/><path class="bcmzn-obx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:rugby-ball" /></template>
