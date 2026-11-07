<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7gn9tbal.css';
import '../../css/j/j3epy4b7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7gn9tbal"/><path clip-rule="evenodd" class="j3epy4b7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:medal-ribbon-star-bold" /></template>
