<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v05-206py.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="v05-206py"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:world-clock" /></template>
