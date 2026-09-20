<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2k_pab-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u2k_pab-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:upvote-rss-light" /></template>
