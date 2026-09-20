<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbhiacf9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbhiacf9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shield-edit" /></template>
