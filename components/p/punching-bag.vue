<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqoer8bvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fqoer8bvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:punching-bag" /></template>
