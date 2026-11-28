<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9m24lbpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary v9m24lbpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:type-duotone" /></template>
