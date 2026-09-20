<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xofyrh50b.css';
import '../../css/k/k-n9lzbwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xofyrh50b"/><path class="k-n9lzbwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:upload" /></template>
