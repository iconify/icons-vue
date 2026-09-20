<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msvd_8nos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msvd_8nos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:vector-arrange-below" /></template>
