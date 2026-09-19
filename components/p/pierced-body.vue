<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dontj7bcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dontj7bcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pierced-body" /></template>
