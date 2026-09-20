<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqpu1tbsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqpu1tbsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:megaphone" /></template>
