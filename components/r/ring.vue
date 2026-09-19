<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx2m1lh8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="kx2m1lh8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:ring" /></template>
