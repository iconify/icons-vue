<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co9xgs76y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="co9xgs76y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:show-outline" /></template>
