<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj9z3ob_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qj9z3ob_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:slime" /></template>
