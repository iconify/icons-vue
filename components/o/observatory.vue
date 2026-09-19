<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bagg5vb1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bagg5vb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:observatory" /></template>
