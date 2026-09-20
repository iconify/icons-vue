<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2uq_9q7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p2uq_9q7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:shooting-stars" /></template>
