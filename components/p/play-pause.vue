<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of_5_qxwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="of_5_qxwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:play-pause" /></template>
