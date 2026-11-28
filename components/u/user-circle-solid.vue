<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm5og6r_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vm5og6r_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:user-circle-solid" /></template>
