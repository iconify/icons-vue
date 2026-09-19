<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk7i8db5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="hk7i8db5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:swap-alt" /></template>
