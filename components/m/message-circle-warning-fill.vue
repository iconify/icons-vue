<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkm10qtia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkm10qtia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-circle-warning-fill" /></template>
