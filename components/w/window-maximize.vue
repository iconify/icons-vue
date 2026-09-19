<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6laare-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="d6laare-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:window-maximize" /></template>
