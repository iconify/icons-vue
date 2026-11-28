<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql2qn_7vp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ql2qn_7vp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-square-x-solid" /></template>
