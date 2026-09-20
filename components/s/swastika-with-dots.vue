<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pq0_rze8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pq0_rze8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:swastika-with-dots" /></template>
