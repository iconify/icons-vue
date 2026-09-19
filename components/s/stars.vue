<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp29vub2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bp29vub2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:stars" /></template>
