<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er95ivb0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="er95ivb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:progress-upload" /></template>
