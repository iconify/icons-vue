<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfdry5kvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfdry5kvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:smile-square-solid" /></template>
