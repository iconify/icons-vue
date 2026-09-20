<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hia--8b1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hia--8b1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:warehouse-filled" /></template>
