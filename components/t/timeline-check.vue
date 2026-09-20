<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9-co0bvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9-co0bvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:timeline-check" /></template>
