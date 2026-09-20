<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk6mn5bot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nk6mn5bot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:zip-file-compress" /></template>
