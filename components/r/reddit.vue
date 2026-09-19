<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r61s8fx5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":960};
const content = `<path class="r61s8fx5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:reddit" /></template>
