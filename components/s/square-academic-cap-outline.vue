<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgdj1qb4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qgdj1qb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-academic-cap-outline" /></template>
