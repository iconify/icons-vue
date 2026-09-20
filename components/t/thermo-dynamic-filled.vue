<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch_ylrb6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ch_ylrb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:thermo-dynamic-filled" /></template>
