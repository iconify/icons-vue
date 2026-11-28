<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm1g7_pyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xm1g7_pyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:orbit-solid" /></template>
