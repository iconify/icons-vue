<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbwchz17z.css';
import '../../css/j/j8n5sacrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbwchz17z"/><path class="j8n5sacrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:prawn" /></template>
