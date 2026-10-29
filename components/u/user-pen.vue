<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg7z1v_rb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wg7z1v_rb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:user-pen" /></template>
