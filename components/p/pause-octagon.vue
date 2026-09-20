<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_074pcwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_074pcwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:pause-octagon" /></template>
