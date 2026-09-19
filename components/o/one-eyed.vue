<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gifyl0-oi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gifyl0-oi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:one-eyed" /></template>
