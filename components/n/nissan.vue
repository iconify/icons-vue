<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s41z-nbzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s41z-nbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:nissan" /></template>
