<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnbi3ybrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bnbi3ybrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:moldova" /></template>
