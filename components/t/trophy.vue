<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf9v7e-3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pf9v7e-3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:trophy" /></template>
