<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvke21biv.css';
import '../../css/y/y__gdjb1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rvke21biv"/><path class="y__gdjb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:share-square" /></template>
