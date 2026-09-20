<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3r-_0bnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="x3r-_0bnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:sunny-filled" /></template>
