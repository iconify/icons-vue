<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1h2e9unp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i1h2e9unp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:nest-eggs" /></template>
