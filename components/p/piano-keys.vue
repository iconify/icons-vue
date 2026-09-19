<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpv5obb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wpv5obb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:piano-keys" /></template>
