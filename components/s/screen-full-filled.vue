<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na0nagbhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="na0nagbhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:screen-full-filled" /></template>
