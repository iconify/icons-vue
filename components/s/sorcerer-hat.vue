<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7_g8vbyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n7_g8vbyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:sorcerer-hat" /></template>
