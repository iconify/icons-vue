<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-t1h_slz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-t1h_slz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-circle-plus-fill" /></template>
