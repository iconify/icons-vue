<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mobyvft8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mobyvft8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:swap-line" /></template>
