<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dc6xhac8s.css';
import '../../css/p/p-3va582c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dc6xhac8s"/><path class="p-3va582c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:messages-bubble-image" /></template>
