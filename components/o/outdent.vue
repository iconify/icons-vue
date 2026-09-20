<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk4hdmknz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dk4hdmknz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:outdent" /></template>
