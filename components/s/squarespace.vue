<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8v_38bzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z8v_38bzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:squarespace" /></template>
