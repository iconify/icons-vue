<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u17r99g-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="u17r99g-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:tent" /></template>
