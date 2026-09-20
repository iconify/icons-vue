<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy4y9ybpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vy4y9ybpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:vuejs" /></template>
