<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3z_mu5px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3z_mu5px"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:minus-square" /></template>
