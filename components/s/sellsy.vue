<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nekr66b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":1472};
const content = `<path class="nekr66b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:sellsy" /></template>
