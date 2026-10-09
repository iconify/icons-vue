<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcs_wdb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jcs_wdb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:octagon-20-bold" /></template>
