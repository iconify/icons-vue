<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwqeewr-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dwqeewr-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:thumb-up-outline" /></template>
