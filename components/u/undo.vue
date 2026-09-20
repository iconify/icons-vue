<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvm4kcb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tvm4kcb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:undo" /></template>
