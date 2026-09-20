<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m52ut1_py.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m52ut1_py"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-walking-with-white-cane" /></template>
