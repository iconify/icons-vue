<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx8zphbgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rx8zphbgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:social-pinterest-circular" /></template>
