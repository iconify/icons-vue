<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt-z4oblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tt-z4oblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:password-solid" /></template>
