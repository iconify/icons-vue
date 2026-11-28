<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr6jcd5ew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vr6jcd5ew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:message-alert" /></template>
