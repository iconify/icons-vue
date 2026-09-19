<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqv-mtbxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zqv-mtbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sun-cloud" /></template>
