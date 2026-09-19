<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3jh0x0el.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="t3jh0x0el"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:square-font-awesome" /></template>
