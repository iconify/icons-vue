<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3ud6bc9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3ud6bc9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:record" /></template>
