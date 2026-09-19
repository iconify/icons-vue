<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojhmxp_8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ojhmxp_8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:r-project" /></template>
