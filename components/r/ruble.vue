<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7hbd3-ms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="o7hbd3-ms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:ruble" /></template>
