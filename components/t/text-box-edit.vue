<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb-w5f2ro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wb-w5f2ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:text-box-edit" /></template>
