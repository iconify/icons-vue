<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijwutn8tg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ijwutn8tg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:rotating-forward" /></template>
