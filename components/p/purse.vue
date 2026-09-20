<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xultr8o4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xultr8o4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:purse" /></template>
