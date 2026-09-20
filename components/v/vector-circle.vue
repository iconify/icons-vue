<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhes_pini.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhes_pini"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vector-circle" /></template>
