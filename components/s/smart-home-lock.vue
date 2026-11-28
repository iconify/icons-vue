<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgnjzj3hk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgnjzj3hk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:smart-home-lock" /></template>
