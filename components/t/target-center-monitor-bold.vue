<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oytsm6b5s.css';
import '../../css/d/dxu2gubtq.css';
import '../../css/j/j9hxiotjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oytsm6b5s"/><path class="dxu2gubtq"/><path class="j9hxiotjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:target-center-monitor-bold" /></template>
