<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0pgd_b0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="j0pgd_b0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:tram" /></template>
