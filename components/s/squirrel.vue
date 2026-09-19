<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt8eu321u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zt8eu321u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:squirrel" /></template>
