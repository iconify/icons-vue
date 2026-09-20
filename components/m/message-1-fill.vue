<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_3rjki6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_3rjki6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-1-fill" /></template>
