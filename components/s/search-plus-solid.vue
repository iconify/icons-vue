<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh_qdbcvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eh_qdbcvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:search-plus-solid" /></template>
