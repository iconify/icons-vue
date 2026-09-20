<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgv8c0_nu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgv8c0_nu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:regex" /></template>
