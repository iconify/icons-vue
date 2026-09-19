<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3v6v0bca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a3v6v0bca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:shrink2" /></template>
