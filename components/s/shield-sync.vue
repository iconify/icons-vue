<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h67-4dtga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h67-4dtga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shield-sync" /></template>
