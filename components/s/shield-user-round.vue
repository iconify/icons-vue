<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfezq7azm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfezq7azm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-user-round" /></template>
