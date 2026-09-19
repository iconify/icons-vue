<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsla3nsgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dsla3nsgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:paw-print" /></template>
