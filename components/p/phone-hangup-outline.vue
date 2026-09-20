<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljapotbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljapotbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-hangup-outline" /></template>
