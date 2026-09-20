<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocx2hes4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocx2hes4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:receipt-disscount" /></template>
