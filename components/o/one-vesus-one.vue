<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5p5qxm0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="p5p5qxm0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:one-vesus-one" /></template>
