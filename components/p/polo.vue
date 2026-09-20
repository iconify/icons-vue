<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d29xc20oi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d29xc20oi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:polo" /></template>
