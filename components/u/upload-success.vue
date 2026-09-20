<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p26q6d9ek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p26q6d9ek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:upload-success" /></template>
