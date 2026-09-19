<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipy95sb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ipy95sb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:youtube-shorts" /></template>
