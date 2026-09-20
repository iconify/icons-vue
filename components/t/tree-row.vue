<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y063tcl2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y063tcl2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:tree-row" /></template>
