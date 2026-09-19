<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j55fwyb9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":1408};
const content = `<path class="j55fwyb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:newspaper-o" /></template>
