<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqy_veb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqy_veb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:paper-plane" /></template>
