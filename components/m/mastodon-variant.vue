<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esdm7_rrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esdm7_rrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mastodon-variant" /></template>
