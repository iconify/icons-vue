<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd9w_l7jo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kd9w_l7jo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:splashy-stream" /></template>
