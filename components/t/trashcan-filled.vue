<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up0qlm5zo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="up0qlm5zo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:trashcan-filled" /></template>
