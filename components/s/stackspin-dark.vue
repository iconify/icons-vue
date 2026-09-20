<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x87xc3biz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x87xc3biz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:stackspin-dark" /></template>
