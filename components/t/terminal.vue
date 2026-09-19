<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_0ix7bza.css';
import '../../css/y/yt0ww0arr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j_0ix7bza"/><path class="yt0ww0arr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:terminal" /></template>
