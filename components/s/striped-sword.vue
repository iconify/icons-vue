<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id1pz4b3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="id1pz4b3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:striped-sword" /></template>
