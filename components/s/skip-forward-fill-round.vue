<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndcw-pbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndcw-pbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:skip-forward-fill-round" /></template>
