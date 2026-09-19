<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty3ki5bkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ty3ki5bkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:medicine-pills" /></template>
