<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyb3f2buu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyb3f2buu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:user-cancel-outline" /></template>
