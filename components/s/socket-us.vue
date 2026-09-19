<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah-cd359b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ah-cd359b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:socket-us" /></template>
