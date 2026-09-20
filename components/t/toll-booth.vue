<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j70-_o67p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j70-_o67p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:toll-booth" /></template>
