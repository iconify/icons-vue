<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d47xi2b9o.css';
import '../../css/h/hgmaekite.css';
import '../../css/m/m5asxrbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d47xi2b9o"/><path class="hgmaekite"/><path class="m5asxrbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:rupee" /></template>
