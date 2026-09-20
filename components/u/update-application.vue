<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve2wk1-qm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ve2wk1-qm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:update-application" /></template>
