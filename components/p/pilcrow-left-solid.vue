<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbd8do5tr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbd8do5tr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pilcrow-left-solid" /></template>
