<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq50l0kdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="wq50l0kdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:shield" /></template>
