<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1_-v3b_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary v1_-v3b_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:phone-duotone" /></template>
