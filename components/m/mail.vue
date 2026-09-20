<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmqh5-yly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmqh5-yly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mail" /></template>
