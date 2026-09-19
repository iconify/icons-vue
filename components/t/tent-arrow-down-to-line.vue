<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdfuk_71m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="sdfuk_71m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:tent-arrow-down-to-line" /></template>
