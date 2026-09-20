<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj6p8koql.css';
import '../../css/m/m_pzdih5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oj6p8koql"/><path class="m_pzdih5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:opul" /></template>
