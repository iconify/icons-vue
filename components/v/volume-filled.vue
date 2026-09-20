<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni8v59ceb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ni8v59ceb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:volume-filled" /></template>
