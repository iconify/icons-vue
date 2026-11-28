<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0p7r5bok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0p7r5bok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:scale-balance-solid" /></template>
