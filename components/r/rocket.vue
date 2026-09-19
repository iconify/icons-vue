<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhmzo7qrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bhmzo7qrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:rocket" /></template>
