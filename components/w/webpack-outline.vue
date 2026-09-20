<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcnqgbyfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wcnqgbyfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:webpack-outline" /></template>
