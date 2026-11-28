<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoj50dbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yoj50dbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:pizza-heart" /></template>
