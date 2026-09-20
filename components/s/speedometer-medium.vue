<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhvp3reay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhvp3reay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:speedometer-medium" /></template>
