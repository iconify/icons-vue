<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzl52293y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzl52293y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:menu-07" /></template>
