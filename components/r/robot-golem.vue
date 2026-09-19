<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrwb58_hr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wrwb58_hr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:robot-golem" /></template>
