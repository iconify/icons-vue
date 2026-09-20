<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwjbk1txm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwjbk1txm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mark-pen-fill" /></template>
