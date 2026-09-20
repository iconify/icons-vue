<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8an2xbxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8an2xbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pisces-line" /></template>
