<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1qq278_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i1qq278_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:rub-el-hizb" /></template>
