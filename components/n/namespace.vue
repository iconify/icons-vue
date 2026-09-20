<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mec5up-yc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mec5up-yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:namespace" /></template>
