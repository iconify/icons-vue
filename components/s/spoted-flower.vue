<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6m48cbdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b6m48cbdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spoted-flower" /></template>
