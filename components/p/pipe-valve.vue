<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2u_1obyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2u_1obyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pipe-valve" /></template>
