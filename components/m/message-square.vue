<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxy7mjbqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxy7mjbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:message-square" /></template>
