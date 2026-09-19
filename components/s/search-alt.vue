<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg-y5lb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="dg-y5lb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:search-alt" /></template>
