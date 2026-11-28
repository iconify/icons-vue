<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9qxjwb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="p9qxjwb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:text-wrap-slash" /></template>
