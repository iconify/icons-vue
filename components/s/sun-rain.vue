<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw0p3-b3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pw0p3-b3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sun-rain" /></template>
