<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/boij_7x6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="boij_7x6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:rectangle-tall" /></template>
