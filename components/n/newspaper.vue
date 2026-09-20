<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnd1vpbyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnd1vpbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:newspaper" /></template>
