<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjd6bdbnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="tjd6bdbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:user-remove-subtract" /></template>
