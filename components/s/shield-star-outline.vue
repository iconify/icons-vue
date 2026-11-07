<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on5jz7bsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="on5jz7bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-star-outline" /></template>
