<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4o22cjfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4o22cjfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:middleware" /></template>
