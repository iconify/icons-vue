<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfka-bcwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfka-bcwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:mask-solid" /></template>
