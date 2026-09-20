<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwj_7qynx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zwj_7qynx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:rockrms" /></template>
