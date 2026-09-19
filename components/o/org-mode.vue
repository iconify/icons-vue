<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgznimbmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":467,"height":512};
const content = `<path class="hgznimbmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:org-mode" /></template>
