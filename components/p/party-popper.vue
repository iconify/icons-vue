<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmcp94bsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zmcp94bsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:party-popper" /></template>
