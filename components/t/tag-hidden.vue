<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vddcv373l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vddcv373l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tag-hidden" /></template>
