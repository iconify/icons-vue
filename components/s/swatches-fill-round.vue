<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e21ipqbnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e21ipqbnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:swatches-fill-round" /></template>
