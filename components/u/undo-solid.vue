<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij0gr3wtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ij0gr3wtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:undo-solid" /></template>
