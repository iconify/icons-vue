<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms3qmbcdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ms3qmbcdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:message-square-warning-solid" /></template>
