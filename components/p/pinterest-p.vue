<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adme_kbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="adme_kbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:pinterest-p" /></template>
