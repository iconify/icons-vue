<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi7zp_b_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="oi7zp_b_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:necklace-solid" /></template>
