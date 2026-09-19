<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7z5z-b0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7z5z-b0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:toast-butter-filled" /></template>
