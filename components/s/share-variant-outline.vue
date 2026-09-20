<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwz9-f8wt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwz9-f8wt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:share-variant-outline" /></template>
