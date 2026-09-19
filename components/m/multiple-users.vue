<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8ch-fbis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8ch-fbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:multiple-users" /></template>
