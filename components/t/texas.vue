<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci5j7wbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ci5j7wbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:texas" /></template>
