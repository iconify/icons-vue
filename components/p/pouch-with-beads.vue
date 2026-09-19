<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qi1q1kb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qi1q1kb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pouch-with-beads" /></template>
