<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4-s41boy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="j4-s41boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pixelpotion" /></template>
