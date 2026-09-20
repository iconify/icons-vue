<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbhw0nleb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbhw0nleb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:monitor-screenshot" /></template>
