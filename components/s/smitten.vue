<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icxq6rm-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="icxq6rm-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:smitten" /></template>
