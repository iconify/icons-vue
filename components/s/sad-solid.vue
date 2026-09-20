<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpr7u8byr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpr7u8byr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:sad-solid" /></template>
