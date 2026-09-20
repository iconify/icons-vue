<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl821gjyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yl821gjyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:wand-outline" /></template>
