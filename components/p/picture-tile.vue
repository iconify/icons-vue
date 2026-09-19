<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpdks0bky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="bpdks0bky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:picture-tile" /></template>
