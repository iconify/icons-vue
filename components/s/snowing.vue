<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj8j7x80k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tj8j7x80k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:snowing" /></template>
