<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx7cgobta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gx7cgobta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:waves-arrow-down" /></template>
