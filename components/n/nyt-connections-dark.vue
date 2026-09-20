<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqkwmdx8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xqkwmdx8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nyt-connections-dark" /></template>
