<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1uzifn9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g1uzifn9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:megabot" /></template>
