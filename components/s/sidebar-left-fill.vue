<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1-0pxo2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1-0pxo2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sidebar-left-fill" /></template>
