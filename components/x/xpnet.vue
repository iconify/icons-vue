<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdbtnyfee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdbtnyfee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:xpnet" /></template>
