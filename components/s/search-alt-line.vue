<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9xgvhb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9xgvhb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:search-alt-line" /></template>
