<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3_nl4dxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="m3_nl4dxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:person-2" /></template>
