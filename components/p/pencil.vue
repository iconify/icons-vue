<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-nse78zz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="l-nse78zz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:pencil" /></template>
