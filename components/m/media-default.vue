<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjunlk9ht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jjunlk9ht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:media-default" /></template>
