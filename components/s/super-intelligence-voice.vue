<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm6wsvb4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bm6wsvb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:super-intelligence-voice" /></template>
