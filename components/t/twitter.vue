<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nki745thx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nki745thx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:twitter" /></template>
