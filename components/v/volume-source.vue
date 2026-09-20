<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb86f38iz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qb86f38iz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:volume-source" /></template>
