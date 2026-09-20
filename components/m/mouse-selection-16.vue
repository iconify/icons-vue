<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_cydubst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="s_cydubst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:mouse-selection-16" /></template>
