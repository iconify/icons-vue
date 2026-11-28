<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss65wmbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ss65wmbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:shield-sparkles-solid" /></template>
