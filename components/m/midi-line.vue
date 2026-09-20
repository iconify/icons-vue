<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpgw6lgbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpgw6lgbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:midi-line" /></template>
