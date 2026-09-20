<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfm7f3bln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfm7f3bln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:rewind-circle-solid" /></template>
