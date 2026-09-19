<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od9a5k13f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1025};
const content = `<path class="od9a5k13f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:shapes" /></template>
