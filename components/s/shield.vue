<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anmzojybv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anmzojybv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:shield" /></template>
