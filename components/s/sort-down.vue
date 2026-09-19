<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3zoyvb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="g3zoyvb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:sort-down" /></template>
