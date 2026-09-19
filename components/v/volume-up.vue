<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfwj7h0yt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="mfwj7h0yt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:volume-up" /></template>
