<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swc4nv0cw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="swc4nv0cw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:transport" /></template>
