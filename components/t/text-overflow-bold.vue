<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwl9-0qxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="fwl9-0qxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:text-overflow-bold" /></template>
