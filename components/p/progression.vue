<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl4beeb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fl4beeb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:progression" /></template>
