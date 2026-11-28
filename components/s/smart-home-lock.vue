<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amn23owsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amn23owsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:smart-home-lock" /></template>
