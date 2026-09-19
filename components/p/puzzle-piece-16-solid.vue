<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo0azpb_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bo0azpb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:puzzle-piece-16-solid" /></template>
