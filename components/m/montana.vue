<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2g0eci0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d2g0eci0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:montana" /></template>
