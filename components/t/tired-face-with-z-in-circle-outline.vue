<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1o_wkb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v1o_wkb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tired-face-with-z-in-circle-outline" /></template>
