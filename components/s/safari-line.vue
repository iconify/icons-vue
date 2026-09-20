<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xneq1mbiq.css';
import '../../css/o/okweau1mj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xneq1mbiq"/><path class="okweau1mj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:safari-line" /></template>
