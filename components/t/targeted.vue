<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za7fcp6wb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="za7fcp6wb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:targeted" /></template>
