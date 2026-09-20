<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez-7w8b0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ez-7w8b0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:selfie" /></template>
