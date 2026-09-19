<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipvd7obbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipvd7obbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:message-edit" /></template>
