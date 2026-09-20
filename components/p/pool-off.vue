<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycu1ysb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycu1ysb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pool-off" /></template>
