<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6f3mn3in.css';
import '../../css/z/zw6fdactm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r6f3mn3in"/><path class="zw6fdactm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:specialist" /></template>
