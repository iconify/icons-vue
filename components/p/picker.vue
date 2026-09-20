<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi8w-tefg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oi8w-tefg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:picker" /></template>
