<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw9gvkbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vw9gvkbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:play-circle-outline" /></template>
