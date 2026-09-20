<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrfi3nquj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrfi3nquj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:map-pin-x-inside" /></template>
