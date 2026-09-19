<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t15t4vbhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t15t4vbhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:podium" /></template>
