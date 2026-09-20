<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r599scm9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r599scm9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:scatter-diagram-filled" /></template>
