<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_mgn5bus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o_mgn5bus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:stop-sign" /></template>
