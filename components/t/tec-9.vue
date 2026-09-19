<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di_vi8bdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="di_vi8bdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tec-9" /></template>
