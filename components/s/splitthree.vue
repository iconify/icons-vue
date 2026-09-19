<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg3u83fnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rg3u83fnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:splitthree" /></template>
