<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqky-rbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqky-rbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sun-fog" /></template>
