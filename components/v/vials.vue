<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxn4-qbhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dxn4-qbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:vials" /></template>
