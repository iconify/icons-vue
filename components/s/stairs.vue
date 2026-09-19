<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmv0z7b4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wmv0z7b4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:stairs" /></template>
