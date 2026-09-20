<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwvo3mbkm.css';
import '../../css/h/h_3msknem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwvo3mbkm"/><path clip-rule="evenodd" class="h_3msknem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:siderbar-bold" /></template>
