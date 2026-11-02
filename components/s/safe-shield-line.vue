<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xaaq_ob0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xaaq_ob0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:safe-shield-line" /></template>
