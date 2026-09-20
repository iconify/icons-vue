<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atusk1b4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="atusk1b4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-burger-on-bun" /></template>
