<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6fngdciu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6fngdciu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:maple-leaf-line" /></template>
