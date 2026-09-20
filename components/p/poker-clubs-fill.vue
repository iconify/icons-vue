<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rho5ahrvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rho5ahrvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:poker-clubs-fill" /></template>
