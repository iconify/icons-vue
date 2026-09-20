<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq31j6bst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eq31j6bst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:presentation-3-line" /></template>
