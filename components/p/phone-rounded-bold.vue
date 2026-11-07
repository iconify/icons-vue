<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwtl__1sz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwtl__1sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:phone-rounded-bold" /></template>
