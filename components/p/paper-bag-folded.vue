<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsqgsc7zf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dsqgsc7zf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:paper-bag-folded" /></template>
