<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o83uhnb4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o83uhnb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:trophy" /></template>
