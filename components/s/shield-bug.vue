<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6gyts6an.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6gyts6an"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shield-bug" /></template>
