<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd610k6nr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yd610k6nr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:medkit-solid" /></template>
