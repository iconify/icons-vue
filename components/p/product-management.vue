<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi1222_ni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bi1222_ni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:product-management" /></template>
