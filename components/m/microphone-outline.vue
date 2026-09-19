<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imc306b1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imc306b1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:microphone-outline" /></template>
