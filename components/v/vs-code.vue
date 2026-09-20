<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izo3etbby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izo3etbby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:vs-code" /></template>
