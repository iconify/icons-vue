<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwg6iibbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwg6iibbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:yoga-bridge-pose-2" /></template>
