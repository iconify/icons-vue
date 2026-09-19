<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpdw78y7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="zpdw78y7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:money-box" /></template>
