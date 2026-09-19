<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-b-vz0ku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-b-vz0ku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:virus-filled" /></template>
