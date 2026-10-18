<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntv6edefm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntv6edefm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:shield" /></template>
