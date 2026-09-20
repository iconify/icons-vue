<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqlzqm85m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zqlzqm85m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:veterinary" /></template>
