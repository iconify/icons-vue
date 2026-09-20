<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6c_8lp1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6c_8lp1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:servers-solid" /></template>
