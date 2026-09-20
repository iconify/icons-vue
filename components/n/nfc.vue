<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygksyobav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygksyobav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:nfc" /></template>
