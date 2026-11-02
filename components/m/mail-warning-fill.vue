<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbjpcgl1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbjpcgl1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mail-warning-fill" /></template>
