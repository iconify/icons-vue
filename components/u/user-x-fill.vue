<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5duiv8mu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="b5duiv8mu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:user-x-fill" /></template>
