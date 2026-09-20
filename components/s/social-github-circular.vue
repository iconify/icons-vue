<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1-6q3lmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1-6q3lmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:social-github-circular" /></template>
