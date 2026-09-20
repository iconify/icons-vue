<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-bxn1n6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="m-bxn1n6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:target" /></template>
