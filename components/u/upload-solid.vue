<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3t5_iv7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3t5_iv7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:upload-solid" /></template>
