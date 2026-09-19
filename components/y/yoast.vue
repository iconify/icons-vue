<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2iqwz2ib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="r2iqwz2ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:yoast" /></template>
