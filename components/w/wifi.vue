<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft81j6ddr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="ft81j6ddr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:wifi" /></template>
