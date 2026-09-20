<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7m5x004v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n7m5x004v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:triangle-down-outline" /></template>
