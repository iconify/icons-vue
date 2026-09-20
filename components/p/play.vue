<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuj8j_bro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="iuj8j_bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:play" /></template>
