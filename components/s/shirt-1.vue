<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fig7rt_5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fig7rt_5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:shirt-1" /></template>
