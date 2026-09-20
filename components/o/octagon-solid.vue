<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vww_86bub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vww_86bub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:octagon-solid" /></template>
