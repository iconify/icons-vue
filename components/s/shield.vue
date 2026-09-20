<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwsxb2bns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwsxb2bns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:shield" /></template>
