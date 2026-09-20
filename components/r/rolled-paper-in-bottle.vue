<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfomq7brw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kfomq7brw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:rolled-paper-in-bottle" /></template>
