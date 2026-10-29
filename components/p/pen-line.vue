<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1z0-ebor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1z0-ebor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:pen-line" /></template>
