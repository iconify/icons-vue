<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz5y-8bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gz5y-8bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:paper-windmill" /></template>
