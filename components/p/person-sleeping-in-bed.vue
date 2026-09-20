<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ma8i4wb3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ma8i4wb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-sleeping-in-bed" /></template>
