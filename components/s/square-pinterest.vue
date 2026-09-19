<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smbwhr9xq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="smbwhr9xq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:square-pinterest" /></template>
