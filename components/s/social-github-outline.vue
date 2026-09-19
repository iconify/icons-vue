<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdr_w8b1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gdr_w8b1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-github-outline" /></template>
