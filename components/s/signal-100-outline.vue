<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtxqo4b9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="dtxqo4b9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:signal-100-outline" /></template>
