<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibo4zfbje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibo4zfbje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:view-week" /></template>
