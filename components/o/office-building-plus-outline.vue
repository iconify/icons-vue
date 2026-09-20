<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njeis7bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njeis7bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:office-building-plus-outline" /></template>
