<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_a8pln_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r_a8pln_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:print" /></template>
