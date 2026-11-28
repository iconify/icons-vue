<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugwj_abnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugwj_abnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:message-dots" /></template>
