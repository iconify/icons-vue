<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz52zxbce.css';
import '../../css/l/ld9e7wt3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vz52zxbce"/><path class="ld9e7wt3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:monitor-bold" /></template>
