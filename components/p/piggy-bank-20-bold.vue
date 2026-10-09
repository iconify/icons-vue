<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxv1t9l-s.css';
import '../../css/t/tlriecbtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nxv1t9l-s"/><path class="tlriecbtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:piggy-bank-20-bold" /></template>
