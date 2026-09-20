<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk-2f43fg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hk-2f43fg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:sweat" /></template>
