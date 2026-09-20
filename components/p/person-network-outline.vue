<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aop-n-4fi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aop-n-4fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:person-network-outline" /></template>
