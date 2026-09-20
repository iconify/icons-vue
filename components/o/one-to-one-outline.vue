<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzwy4ibwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pzwy4ibwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:one-to-one-outline" /></template>
