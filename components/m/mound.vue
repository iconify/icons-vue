<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zttnk2xct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="zttnk2xct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:mound" /></template>
