<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4lpp7fcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4lpp7fcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:piggy-bank" /></template>
