<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsgg_6xrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vsgg_6xrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:margin" /></template>
