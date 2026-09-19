<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivgvzfb6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ivgvzfb6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:pouring" /></template>
