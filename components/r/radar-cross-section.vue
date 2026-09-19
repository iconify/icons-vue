<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf60shb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zf60shb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:radar-cross-section" /></template>
