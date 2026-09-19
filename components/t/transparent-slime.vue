<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aarfzzbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aarfzzbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:transparent-slime" /></template>
