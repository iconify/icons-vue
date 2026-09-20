<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4q-webeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d4q-webeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:star-add" /></template>
