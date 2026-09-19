<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2206fj4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":384};
const content = `<path class="t2206fj4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:text-format" /></template>
