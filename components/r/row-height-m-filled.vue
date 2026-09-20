<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwda_o2io.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pwda_o2io"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:row-height-m-filled" /></template>
