<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5rfv4tlj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5rfv4tlj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:panel-bottom-inactive-solid" /></template>
