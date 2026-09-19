<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt8u4qbwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vt8u4qbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:superhero-alt" /></template>
