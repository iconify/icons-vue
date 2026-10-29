<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr59_4bwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jr59_4bwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:mail-warning" /></template>
