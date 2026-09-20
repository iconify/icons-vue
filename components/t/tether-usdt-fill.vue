<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo2ri5m8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jo2ri5m8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tether-usdt-fill" /></template>
