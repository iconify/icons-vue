<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk3gbqpff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mk3gbqpff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:polygon-24px" /></template>
