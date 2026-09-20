<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2w-uwbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2w-uwbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:star-outline" /></template>
