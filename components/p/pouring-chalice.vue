<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usx2mjb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="usx2mjb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pouring-chalice" /></template>
