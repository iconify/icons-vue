<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg_x5acni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg_x5acni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:vertical-top-filled" /></template>
