<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjkn6nbgz.css';
import '../../css/e/e90szm-te.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjkn6nbgz"/><path class="e90szm-te"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:recive-twice-square-bold-duotone" /></template>
