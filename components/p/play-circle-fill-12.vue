<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv7snctli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="vv7snctli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:play-circle-fill-12" /></template>
