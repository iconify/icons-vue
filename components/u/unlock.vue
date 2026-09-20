<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tekvm-b2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tekvm-b2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:unlock" /></template>
