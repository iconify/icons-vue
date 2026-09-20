<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss29dgbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ss29dgbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:rupee-circle-solid" /></template>
