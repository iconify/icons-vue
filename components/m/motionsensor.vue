<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvw8wccdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvw8wccdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:motionsensor" /></template>
