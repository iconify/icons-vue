<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqpg00fgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqpg00fgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:rupee-diamond-solid" /></template>
