<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r73fp3gax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r73fp3gax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:shinto-shrine-mirror" /></template>
