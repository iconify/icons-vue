<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uicqk6jbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uicqk6jbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:windows" /></template>
