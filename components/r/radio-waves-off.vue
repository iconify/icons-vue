<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjixijb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gjixijb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:radio-waves-off" /></template>
