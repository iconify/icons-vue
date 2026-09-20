<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwft6v2va.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-7,"top":-2};
const content = `<path class="zwft6v2va"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:pin-alt" /></template>
