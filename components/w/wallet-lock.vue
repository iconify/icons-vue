<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwlu0cchv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwlu0cchv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:wallet-lock" /></template>
