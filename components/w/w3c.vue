<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg_99vq4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="cg_99vq4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:w3c" /></template>
