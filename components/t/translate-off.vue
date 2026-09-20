<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d54k03b9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d54k03b9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:translate-off" /></template>
