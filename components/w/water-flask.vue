<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onieinb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="onieinb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:water-flask" /></template>
