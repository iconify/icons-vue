<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqdg6rbyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqdg6rbyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:message-circle-plus" /></template>
