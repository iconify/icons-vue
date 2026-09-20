<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pl2gujicm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pl2gujicm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:motion" /></template>
