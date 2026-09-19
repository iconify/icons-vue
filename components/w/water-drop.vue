<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npwimhb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="npwimhb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:water-drop" /></template>
