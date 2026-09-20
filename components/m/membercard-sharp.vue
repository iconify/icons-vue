<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivr_cpdrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivr_cpdrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:membercard-sharp" /></template>
