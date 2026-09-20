<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn7rt1cnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yn7rt1cnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:rails-with-derailer" /></template>
