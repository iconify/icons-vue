<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovfb4w_au.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ovfb4w_au"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wide-rectangle" /></template>
