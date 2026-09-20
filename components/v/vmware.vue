<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmiv2pbgq.css';
import '../../css/v/vh-56ab7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmiv2pbgq"/><path class="vh-56ab7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:vmware" /></template>
