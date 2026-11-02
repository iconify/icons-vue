<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm03p3z6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vm03p3z6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:refresh-anticlockwise-1-fill" /></template>
