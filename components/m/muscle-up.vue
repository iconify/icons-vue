<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwb7bbe5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jwb7bbe5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:muscle-up" /></template>
