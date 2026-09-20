<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdf_24b_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mdf_24b_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:passport-with-graticule-globe" /></template>
