<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb7sowwzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-4};
const content = `<path class="tb7sowwzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:stop" /></template>
