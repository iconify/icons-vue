<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj173kefi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gj173kefi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:rocket-launch" /></template>
