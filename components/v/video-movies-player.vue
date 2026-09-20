<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-wkmz4ib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b-wkmz4ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:video-movies-player" /></template>
