<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vysygrdiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vysygrdiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:toggle-right-solid" /></template>
