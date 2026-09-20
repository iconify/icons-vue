<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rckfhcc4g.css';
import '../../css/u/u0awpynix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="rckfhcc4g"/><path class="u0awpynix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:postcard" /></template>
