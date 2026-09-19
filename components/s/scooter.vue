<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbm9v9sot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mbm9v9sot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:scooter" /></template>
