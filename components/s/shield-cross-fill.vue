<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a964un1_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a964un1_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shield-cross-fill" /></template>
