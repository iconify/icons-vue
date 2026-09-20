<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lykg3ubvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lykg3ubvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:user-bolt" /></template>
