<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ep0n2wbmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ep0n2wbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:sun-filled" /></template>
