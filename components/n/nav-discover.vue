<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckxrjp7pe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ckxrjp7pe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:nav-discover" /></template>
