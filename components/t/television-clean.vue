<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onwn_7qqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="onwn_7qqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:television-clean" /></template>
