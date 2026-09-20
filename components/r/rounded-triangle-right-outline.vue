<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mupqp8cxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mupqp8cxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:rounded-triangle-right-outline" /></template>
