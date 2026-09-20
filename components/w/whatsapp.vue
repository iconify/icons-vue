<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w360b4bca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w360b4bca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:whatsapp" /></template>
