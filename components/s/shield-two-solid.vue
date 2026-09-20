<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxnj3wrkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxnj3wrkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:shield-two-solid" /></template>
