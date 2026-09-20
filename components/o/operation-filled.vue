<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6mslm3di.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="m6mslm3di"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:operation-filled" /></template>
