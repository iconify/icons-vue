<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr2o_74so.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jr2o_74so"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:svg" /></template>
