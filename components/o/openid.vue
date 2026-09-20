<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf4b38bbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mf4b38bbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:openid" /></template>
