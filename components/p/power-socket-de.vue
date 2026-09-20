<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aiif26bee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aiif26bee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:power-socket-de" /></template>
