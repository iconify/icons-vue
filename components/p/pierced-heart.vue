<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqoz3rbch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xqoz3rbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pierced-heart" /></template>
