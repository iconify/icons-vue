<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxzusxbct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxzusxbct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:plane" /></template>
