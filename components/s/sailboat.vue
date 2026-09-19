<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpi6zpbro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gpi6zpbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sailboat" /></template>
