<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydk_n5baj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ydk_n5baj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:trx" /></template>
