<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8v230bli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8v230bli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:swap-horizontal" /></template>
