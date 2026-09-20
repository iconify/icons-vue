<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjn0pz9-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjn0pz9-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:perplexity-fill" /></template>
