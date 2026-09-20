<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pehdgxa9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pehdgxa9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:view-stream" /></template>
