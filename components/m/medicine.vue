<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfvfo9eco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfvfo9eco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:medicine" /></template>
