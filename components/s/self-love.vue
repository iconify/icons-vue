<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eiuklobge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eiuklobge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:self-love" /></template>
