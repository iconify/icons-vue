<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-_v0x0lt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-_v0x0lt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:revoltdotchat" /></template>
