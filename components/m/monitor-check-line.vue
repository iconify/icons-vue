<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbz9xohyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbz9xohyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:monitor-check-line" /></template>
