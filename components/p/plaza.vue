<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je-r6vkdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="je-r6vkdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:plaza" /></template>
