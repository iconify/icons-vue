<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mji30zbhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mji30zbhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:table-tennis-paddle" /></template>
