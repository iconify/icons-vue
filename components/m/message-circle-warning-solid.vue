<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m90tfysgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m90tfysgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-circle-warning-solid" /></template>
