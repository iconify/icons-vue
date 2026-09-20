<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzx--cc9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rzx--cc9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pill-bottle-with-capsule-pill" /></template>
