<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj5b2hbei.css';
import '../../css/f/f4eetr8fi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zj5b2hbei"/><path class="f4eetr8fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pie-chart-2-bold-duotone" /></template>
