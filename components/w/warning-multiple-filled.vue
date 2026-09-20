<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0nrqjbzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="p0nrqjbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:warning-multiple-filled" /></template>
