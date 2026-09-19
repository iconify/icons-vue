<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6w906bqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="a6w906bqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:sass" /></template>
