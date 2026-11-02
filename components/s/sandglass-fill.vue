<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrozomf3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrozomf3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sandglass-fill" /></template>
