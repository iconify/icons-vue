<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz0zt2bpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kz0zt2bpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:person-standing" /></template>
