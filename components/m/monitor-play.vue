<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr0c4zexh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vr0c4zexh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:monitor-play" /></template>
