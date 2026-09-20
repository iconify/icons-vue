<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx8m87bvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx8m87bvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mkr" /></template>
