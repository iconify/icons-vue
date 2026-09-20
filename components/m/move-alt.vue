<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txxrw9wmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-4};
const content = `<path class="txxrw9wmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:move-alt" /></template>
