<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fulnzej7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fulnzej7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:reddit-downvote" /></template>
