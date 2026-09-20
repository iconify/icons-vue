<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqvu_8b9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uqvu_8b9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:plane-right" /></template>
