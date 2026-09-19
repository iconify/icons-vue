<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5bas9i5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z5bas9i5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spotted-wound" /></template>
