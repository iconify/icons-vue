<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbkyprbva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fbkyprbva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:stopwatch-outline" /></template>
