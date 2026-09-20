<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eeq14dbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eeq14dbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:video" /></template>
