<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgy83lbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgy83lbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:quote-single-right-filled" /></template>
