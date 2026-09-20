<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3efl2s8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3efl2s8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vector-point-edit" /></template>
