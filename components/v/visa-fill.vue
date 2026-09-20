<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyz0-nt_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyz0-nt_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:visa-fill" /></template>
