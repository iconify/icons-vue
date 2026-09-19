<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgx8uhb9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgx8uhb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:vector-triangle" /></template>
