<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np8-hccbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="np8-hccbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vector-square-plus" /></template>
