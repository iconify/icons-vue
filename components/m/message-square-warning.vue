<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znar6ubig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znar6ubig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:message-square-warning" /></template>
