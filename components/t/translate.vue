<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_l2z6bml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":432};
const content = `<path class="r_l2z6bml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:translate" /></template>
