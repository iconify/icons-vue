<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yabvmqbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":255};
const content = `<path class="yabvmqbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:typesense" /></template>
