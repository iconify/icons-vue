<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snm_libuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snm_libuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:record-solid" /></template>
