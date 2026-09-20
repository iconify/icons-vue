<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar0xbeyhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ar0xbeyhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:output" /></template>
