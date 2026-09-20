<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg5zuubla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hg5zuubla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:surface-right-filled" /></template>
