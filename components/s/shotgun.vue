<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9deklbng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o9deklbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:shotgun" /></template>
