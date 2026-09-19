<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgkl83cth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":447,"height":512};
const content = `<path class="wgkl83cth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:scrutinizer" /></template>
