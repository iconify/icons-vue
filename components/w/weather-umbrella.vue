<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0kbq7sil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b0kbq7sil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:weather-umbrella" /></template>
