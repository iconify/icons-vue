<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bezyg0w5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bezyg0w5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ocr" /></template>
