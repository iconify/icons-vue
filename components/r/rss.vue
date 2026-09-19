<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awyp7-bgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awyp7-bgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:rss" /></template>
