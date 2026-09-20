<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow1e9499a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ow1e9499a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:rectangle-vertical" /></template>
