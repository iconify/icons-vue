<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7zezab6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d7zezab6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-skiing-downhill" /></template>
