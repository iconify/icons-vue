<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnc_zmbbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnc_zmbbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:notebook-edit-outline" /></template>
