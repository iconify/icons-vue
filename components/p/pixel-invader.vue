<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-tmw3m-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q-tmw3m-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-invader" /></template>
