<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlia8ab3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1408};
const content = `<path class="jlia8ab3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:rss" /></template>
