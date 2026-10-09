<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hiosb2sjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hiosb2sjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shirt-48-bold" /></template>
