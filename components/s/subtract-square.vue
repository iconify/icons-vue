<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2k5pjb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="s2k5pjb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:subtract-square" /></template>
