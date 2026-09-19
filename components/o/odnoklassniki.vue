<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t95140brd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="t95140brd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:odnoklassniki" /></template>
