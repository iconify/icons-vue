<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qze7ds5pb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qze7ds5pb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:pause" /></template>
