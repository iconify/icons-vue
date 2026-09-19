<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7ha_ocpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7ha_ocpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:news" /></template>
