<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umxgh6bfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umxgh6bfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:xero" /></template>
