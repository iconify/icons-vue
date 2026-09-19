<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zonh8mbgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="zonh8mbgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:sign-in" /></template>
