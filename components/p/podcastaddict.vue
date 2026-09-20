<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t31vdhbwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t31vdhbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:podcastaddict" /></template>
