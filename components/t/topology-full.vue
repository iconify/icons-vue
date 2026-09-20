<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxo5hhbcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxo5hhbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:topology-full" /></template>
