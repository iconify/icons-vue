<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj3idy5_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pj3idy5_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-dashed-check-solid" /></template>
