<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw8i7gzgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dw8i7gzgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:smugmug" /></template>
