<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlbz5b3ns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mlbz5b3ns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:qualcomm-logo-solid" /></template>
