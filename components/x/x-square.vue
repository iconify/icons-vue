<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9vj8vb-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="c9vj8vb-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:x-square" /></template>
