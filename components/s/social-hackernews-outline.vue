<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bycj2bqiy.css';
import '../../css/n/nfo4jpdxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bycj2bqiy"/><path class="nfo4jpdxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-hackernews-outline" /></template>
