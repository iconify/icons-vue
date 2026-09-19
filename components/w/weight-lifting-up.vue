<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpx5clbzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qpx5clbzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:weight-lifting-up" /></template>
