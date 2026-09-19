<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dznn1zbmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dznn1zbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tank" /></template>
