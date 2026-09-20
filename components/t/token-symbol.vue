<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdvjvpb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pdvjvpb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:token-symbol" /></template>
