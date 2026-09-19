<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsj4hypri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dsj4hypri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:stork-delivery" /></template>
