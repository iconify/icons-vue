<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mibn7eb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="mibn7eb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:stop-filled" /></template>
