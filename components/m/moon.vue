<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsxagjwuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lsxagjwuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:moon" /></template>
