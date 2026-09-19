<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g72s45xtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1025};
const content = `<path class="g72s45xtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:repeat" /></template>
