<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqa1w4vfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="iqa1w4vfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:mounted-scope" /></template>
