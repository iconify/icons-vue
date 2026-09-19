<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1r4dvbnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s1r4dvbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:mdx" /></template>
