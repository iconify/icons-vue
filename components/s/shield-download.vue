<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdkldebal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdkldebal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:shield-download" /></template>
