<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u128gjb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u128gjb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:panorama-360-outline" /></template>
