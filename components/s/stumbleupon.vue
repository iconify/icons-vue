<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7fss-03f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="x7fss-03f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:stumbleupon" /></template>
