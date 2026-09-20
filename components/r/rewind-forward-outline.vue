<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggbfl18zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggbfl18zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rewind-forward-outline" /></template>
