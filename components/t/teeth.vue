<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz4ox_b4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="lz4ox_b4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:teeth" /></template>
