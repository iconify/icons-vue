<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t07miue5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="t07miue5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:padlet" /></template>
