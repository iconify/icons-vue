<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv5xazb2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bv5xazb2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sparkles-fill" /></template>
