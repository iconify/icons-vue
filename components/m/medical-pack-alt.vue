<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id5b2zbzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="id5b2zbzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:medical-pack-alt" /></template>
