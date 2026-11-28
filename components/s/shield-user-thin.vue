<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap1_i8bof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ap1_i8bof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:shield-user-thin" /></template>
