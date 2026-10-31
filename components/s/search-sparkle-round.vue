<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7q8bf8rq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7q8bf8rq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:search-sparkle-round" /></template>
