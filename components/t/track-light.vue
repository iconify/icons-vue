<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o417n3brr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o417n3brr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:track-light" /></template>
