<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb8db3bor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xb8db3bor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:vivawallet" /></template>
