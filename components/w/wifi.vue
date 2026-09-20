<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5ni_cb0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="t5ni_cb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:wifi" /></template>
