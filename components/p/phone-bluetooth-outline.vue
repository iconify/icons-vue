<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqhdlkbro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqhdlkbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-bluetooth-outline" /></template>
