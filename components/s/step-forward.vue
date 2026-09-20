<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p87_qmbzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p87_qmbzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:step-forward" /></template>
