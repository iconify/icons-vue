<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2c69btxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2c69btxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:two-circle-solid" /></template>
