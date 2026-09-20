<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm756ob8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lm756ob8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:media-fast-forward" /></template>
