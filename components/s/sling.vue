<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npd735bal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="npd735bal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sling" /></template>
