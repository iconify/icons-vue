<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze4n_9xuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ze4n_9xuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:snooze-bold" /></template>
