<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhk07pbay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhk07pbay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:search-status-filled" /></template>
