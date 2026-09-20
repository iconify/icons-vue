<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho7-23-lx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ho7-23-lx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ppay" /></template>
