<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_4v44_8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f_4v44_8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:street-view-solid" /></template>
