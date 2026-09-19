<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi8elsf9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xi8elsf9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:plug" /></template>
