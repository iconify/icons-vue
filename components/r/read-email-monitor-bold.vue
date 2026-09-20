<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km7s_km6t.css';
import '../../css/y/ygu8evkrm.css';
import '../../css/d/dzn4brbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km7s_km6t"/><path class="ygu8evkrm"/><path class="dzn4brbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:read-email-monitor-bold" /></template>
