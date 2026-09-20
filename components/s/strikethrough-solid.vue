<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8d7i3boe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="l8d7i3boe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:strikethrough-solid" /></template>
