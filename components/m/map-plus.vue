<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brc0m0l9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brc0m0l9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:map-plus" /></template>
