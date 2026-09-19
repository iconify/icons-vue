<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfm9clb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sfm9clb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:zig" /></template>
