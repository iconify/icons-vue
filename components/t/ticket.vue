<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybz5izn0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybz5izn0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:ticket" /></template>
