<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdzl840ov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdzl840ov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:shield-slash" /></template>
