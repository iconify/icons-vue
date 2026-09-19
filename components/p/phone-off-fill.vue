<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjy8cko8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjy8cko8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:phone-off-fill" /></template>
