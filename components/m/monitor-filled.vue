<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrac7tc6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrac7tc6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:monitor-filled" /></template>
