<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9ax1cc5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="m9ax1cc5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:times-circle" /></template>
