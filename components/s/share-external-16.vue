<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8yeuabmx.css';
import '../../css/o/olvwwtpsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u8yeuabmx"/><path class="olvwwtpsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:share-external-16" /></template>
