<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqoa4bb0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":512};
const content = `<path class="zqoa4bb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:power" /></template>
