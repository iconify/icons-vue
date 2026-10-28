<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6r35db5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6r35db5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:nextcloud" /></template>
