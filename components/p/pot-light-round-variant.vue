<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njo4stv8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njo4stv8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pot-light-round-variant" /></template>
