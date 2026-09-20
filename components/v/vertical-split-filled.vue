<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0w1_nr1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d0w1_nr1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:vertical-split-filled" /></template>
