<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a01e7gm4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a01e7gm4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:netlify" /></template>
