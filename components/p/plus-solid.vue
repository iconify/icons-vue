<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmc7o3bax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmc7o3bax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:plus-solid" /></template>
