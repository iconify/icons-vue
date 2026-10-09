<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5xcwtbtp.css';
import '../../css/d/dq7ui5iby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a5xcwtbtp"/><path class="dq7ui5iby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wattmeter-48-bold" /></template>
