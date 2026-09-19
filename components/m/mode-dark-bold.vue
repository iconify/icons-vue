<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdvfihbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdvfihbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:mode-dark-bold" /></template>
