<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebc46_dxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ebc46_dxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:piggy-bank" /></template>
