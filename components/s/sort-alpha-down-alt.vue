<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlu2tcchk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="dlu2tcchk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:sort-alpha-down-alt" /></template>
