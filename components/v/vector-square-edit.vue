<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p099_modx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p099_modx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vector-square-edit" /></template>
