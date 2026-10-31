<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tywym2n_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tywym2n_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sort-descending-bulk-round" /></template>
