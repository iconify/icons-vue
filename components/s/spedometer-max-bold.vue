<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tiy2c6lkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tiy2c6lkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:spedometer-max-bold" /></template>
